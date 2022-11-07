# learning-os-log
此 repo 作为参加开源操作系统训练营的记录

# Day1

Date: 2022-11-04  

## 完成情况
1. 阅读了训练营项目规则与说明等  
2. 收集了 Rust 相关资料，并完成 Hello, world.  
3. 建立了此学习 Repo.  



# Day2

Date: 2022-11-05

## 完成情况
1. 使用 rustlings 做了4道小题
2. 粗略看了一眼 Risc-v 指令级架构
3. 学习了 Rust 中变量、特权、引用与借用等概念。

## 理解

Rust 是无 GC 语言，这意味着没有 STW。应该是 Rust 对内存的这种处理方式，导致了 Rust 的特权、引用与借用等概念的产生。  
另外我发现 Python 的类型标注可能从 Rust 函数语法这里借鉴来的。  
不太担心语言学习的问题，主要担心后面OS实验可能玩不转。  

# Day3
Date: 2022-11-06

## 完成情况
1. 继续学习 Rust，并完成了若干道 rustlings 练习

## 总结 
Rust 的 shadowing 特性，不仅可以用于改变变量的值，还以用于转换变量的类型

```rust
let num = "T-H-R-E-E";
let num = 3;
```
上述代码是可行的。


# Day4

今天继续看了Rust的基础文章，但是做的练习不多，需要继续加油。