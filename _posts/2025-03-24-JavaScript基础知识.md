---
layout: post
title: "JavaScript基础知识"
author: "活学老"
tags: 
---
JavaScript 数据类型详解

JavaScript 是一种动态类型的编程语言，这意味着变量的类型在运行时可以改变。了解 JavaScript 的数据类型对于编写高效且健壮的代码至关重要。

基本数据类型

JavaScript 中有以下几种基本数据类型：

字符串（String）： 用于表示文本数据。可以使用单引号或双引号创建字符串。
示例："Hello, world!", 'JavaScript'
数字（Number）： 用于表示数值数据。JavaScript 中的数字可以是整数或浮点数。
示例：10, 3.14, -5
布尔值（Boolean）： 用于表示逻辑值，只有 true 和 false 两个值。
示例：true, false
空值（Null）： 表示一个空值或不存在的对象。
示例：null
未定义（Undefined）： 表示一个已声明但尚未赋值的变量。
示例：undefined
符号（Symbol）： ES6 中新增的数据类型，用于创建唯一的标识符。
示例：Symbol('foo')
大整数（BigInt）： ES10 中新增的数据类型，用于表示任意精度的整数。
示例：12345678901234567890n
引用数据类型

JavaScript 中还有以下几种引用数据类型：

对象（Object）： 用于表示复杂的数据结构，可以包含多个键值对。
示例：{ name: 'John', age: 30 }
数组（Array）： 用于表示有序的数据集合。
示例：[1, 2, 3, 4, 5]
函数（Function）： 用于表示可执行的代码块。
示例：function sayHello() { console.log('Hello!'); }
数据类型转换

JavaScript 允许在不同数据类型之间进行转换。可以使用以下方法进行数据类型转换：

String()：将值转换为字符串。
Number()：将值转换为数字。
Boolean()：将值转换为布尔值。
let name = "John"; // 字符串
let age = 30; // 数字
let isStudent = false; // 布尔值
let address = null; // 空值
let city; // 未定义
let id = Symbol("id");
let bigNumber = 9007199254740991n;

let person = { name: "John", age: 30 }; // 对象
let numbers = [1, 2, 3, 4, 5]; // 数组
function sayHello() {
  console.log("Hello!");
} // 函数

console.log(String(age)); // "30"
console.log(Number("123")); // 123
console.log(Boolean(0)); // false
