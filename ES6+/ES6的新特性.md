# ES6的新特性

## 一、let和const命令

> ES6 新增了let命令，用来声明变量。它的用法类似于var，但是所声明的变量，只在let命令所在的代码块内有效。
1. 块级作用域
2. 不存在变量提升
3. 暂时性死区
4. 不允许重复声明

>const声明一个只读的常量。一旦声明，常量的值就不能改变。

>ES5 只有两种声明变量的方法：var命令和function命令。ES6 除了添加let和const命令，后面章节还会提到，另外两种声明变量的方法：import命令和class命令。所以，ES6 一共有 6 种声明变量的方法。

## 二、变量的解构赋值

1. 数组的解构赋值
2. 对象的解构赋值
3. 字符串的解构赋值
4. 数值和布尔值的解构赋值
5. 函数参数的解构赋值

- 指定默认值
- 嵌套模式

### 不能使用圆括号的情况

1. 变量声明语句
2. 函数参数
3. 赋值语句的模式

### 可以使用圆括号的情况

1. 赋值语句的非模式部分，可以使用圆括号

### 主要用途
1. 交换变量的值
2. 从函数返回多个值
3. 函数参数的定义
4. 提取JSON数据
5. 函数参数的默认值
6. 遍历Map结构
7. 输入模块的指定方法


## 三、字符串的扩展

1. 字符的 Unicode 表示法
2. 字符串的遍历器接口
3. 直接输入 U+2028 和 U+2029
4. JSON.stringify() 的改造
5. 模板字符串
6. 实例：模板编译
7. 标签模板
8. 模板字符串的限制

## 四、字符串的新增方法

1. String.fromCodePoint()

ES5 提供`String.fromCharCode()`方法，用于从 Unicode 码点返回对应字符，但是这个方法不能识别码点大于0xFFFF的字符。

ES6 提供了`String.fromCodePoint()`方法，可以识别大于0xFFFF的字符，弥补了`String.fromCharCode()`方法的不足。在作用上，正好与下面的`codePointAt()`方法相反。

2. String.raw()

ES6 还为原生的 String 对象，提供了一个`raw()`方法。该方法返回一个斜杠都被转义（即斜杠前面再加一个斜杠）的字符串，往往用于模板字符串的处理方法。

3. 实例方法：codePointAt()
4. 实例方法：normalize()
5. 实例方法：includes(), startsWith(), endsWith()
6. 实例方法：repeat()
7. 实例方法：padStart()，padEnd()
8. 实例方法：trimStart()，trimEnd()
9. 实例方法：matchAll()
10. 实例方法：replaceAll()
11. 实例方法：at()

## 正则的扩展

## 数值的扩展

## 函数的扩展

## 对象的扩展

## 对象的新增方法

## 运算符的扩展

## Symbol

## Set和Map数据结构

## Proxy

## Reflect

## Promise对象

## Iterator 和 for...of 循环

## Generator函数的语法

## Generator函数的异步应用

## async函数

## Class的基本语法

## Class的继承

## Module的语法

## Module的加载实现

