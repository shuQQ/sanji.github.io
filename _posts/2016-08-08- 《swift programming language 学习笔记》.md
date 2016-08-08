---
layout: post  
title: 《swift programming language 学习笔记》  
description: 学习笔记  
image: 
categories: [linux]  
---  

## the Basics  
### 变量和常量（Constants and Variables）  
  
* 用let 声明一个常量，var 声明一个变量，比如：    
<pre><code>let maximumNumberOfLoginAttempts = 10
var currentLoginAttempt = 0
</code></pre>
我们通常把不会变的值声明为常量，比如这个maximumNumberOfLoginAttempts代表最大尝试登录次数；把currentLoginAttempt声明为变量，代表当前登录次数.  

* 类型声明  （Type Annotations）

 <pre><code>var welcomeMessage: String
welcomeMessage = "Hello"
let π = 3.14159
let 你好 = "你好世界"
let 🐶🐮 = "dogcow"
</code></pre>
* 整数（Integers)  
 
  Integers代表整数，在8位、16位、32位、64位系统中提供了有符号型（signed）和无符号型（unsigned）
  <pre><code>在32位系统中，Int 等同于 Int32,同理Int64,Int8,Int16
  无符号型就是UInt8,Uint16,UInt32,Uint64 
</code></pre>
* 浮点型（Floating-Point Numbers）
 <pre><code>double 代表64 bits的浮点数
 float 代表32bits的浮点数
</code></pre>

