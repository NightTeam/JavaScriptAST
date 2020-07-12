# JavaScriptAST

JavaScript 抽象语法树相关的理论知识和实战教程索引，帮助各位工程师掌握 AST 相关知识点和技术应用。


### AST 结构在线解析

https://astexplorer.net/

https://resources.jointjs.com/demos/rappid/apps/Ast/index.html



### 常用的 AST 解析库

Babel: https://github.com/jamiebuilds/babel-handbook/blob/master/translations/zh-Hans/user-handbook.md

Esprima: https://esprima.org/

Acorn: https://github.com/acornjs/acorn

UglifyJS: http://lisperator.net/uglifyjs/


### 相关教程

[AST 还原 obfuscator 混淆](https://blog.csdn.net/zhao_5352269/article/details/106492177)

[操作AST还原混淆代码基础系列课程三:十六进制字符串还原](https://mp.weixin.qq.com/s/bB3lF5mg1wJEYEBfBPjG3g)

[操作AST还原混淆代码:让代码分析变得如此简单](https://mp.weixin.qq.com/s/Iy4gaUCfb76Km7ZdOFNS9w)

[AST实战:全自动解密经obfuscator混淆的加密字符串](https://mp.weixin.qq.com/s/L4FOxc7fwKB7bq0eQb2r9g)

[操作AST还原混淆代码课程九:还原简单的CallExpression 类型](https://mp.weixin.qq.com/s/CI9I4D3aJUoGUvud1uFj7w)


### AST 节点类型对照表

| 序号 | 类型原名称           | 中文名称      | 描述                                                  |
| ---- | -------------------- | ------------- | ----------------------------------------------------- |
| 1    | Program              | 程序主体      | 整段代码的主体                                        |
| 2    | VariableDeclaration  | 变量声明      | 声明一个变量，例如 var let const                      |
| 3    | FunctionDeclaration  | 函数声明      | 声明一个函数，例如 function                           |
| 4    | ExpressionStatement  | 表达式语句    | 通常是调用一个函数，例如 console.log()                |
| 5    | BlockStatement       | 块语句        | 包裹在 {} 块内的代码，例如 if (condition){var a = 1;} |
| 6    | BreakStatement       | 中断语句      | 通常指 break                                          |
| 7    | ContinueStatement    | 持续语句      | 通常指 continue                                       |
| 8    | ReturnStatement      | 返回语句      | 通常指 return                                         |
| 9    | SwitchStatement      | Switch 语句   | 通常指 Switch Case 语句中的 Switch                    |
| 10   | IfStatement          | If 控制流语句 | 控制流语句，通常指 if(condition){}else{}              |
| 11   | Identifier           | 标识符        | 标识，例如声明变量时 var identi = 5 中的 identi       |
| 12   | CallExpression       | 调用表达式    | 通常指调用一个函数，例如 console.log()                |
| 13   | BinaryExpression     | 二进制表达式  | 通常指运算，例如 1+2                                  |
| 14   | MemberExpression     | 成员表达式    | 通常指调用对象的成员，例如 console 对象的 log 成员    |
| 15   | ArrayExpression      | 数组表达式    | 通常指一个数组，例如 [1, 3, 5]                        |
| 16   | NewExpression        | New 表达式    | 通常指使用 New 关键词                                 |
| 17   | AssignmentExpression | 赋值表达式    | 通常指将函数的返回值赋值给变量                        |
| 18   | UpdateExpression     | 更新表达式    | 通常指更新成员值，例如 i++                            |
| 19   | Literal              | 字面量        | 字面量                                |
| 20   | BooleanLiteral       | 布尔型字面量  | 布尔值，例如 true false                               |
| 21   | NumericLiteral       | 数字型字面量  | 数字，例如 100                                        |
| 22   | StringLiteral        | 字符型字面量  | 字符串，例如 vansenb                                  |
| 23   | SwitchCase           | Case 语句     | 通常指 Switch 语句中的 Case                           |

> 
