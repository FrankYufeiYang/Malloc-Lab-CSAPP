# Malloc-Lab-CSAPP

## 背景
* 课程: System programming
* 教材: Computer Systems: A Programmer's Perspective (CSAPP)

## 语言
C

## 环境与使用
linux下给定的实验环境
* code `mm.c`文件


## 实验目标
Part1: 在`mm.c`文件中实现以下函数
 * `malloc`: 分配特定大小的内存空间
 * `free`: 释放空间
 * `realloc`: 重新分配内存空间
 * `calloc`: 分配指定数量大小的空间
 
 ## 调试
 * 熟悉给定的内存模拟环境
 * 组织free block的方式：
   * 隐式空闲链表
   * 显式空闲链表
   * 分离的空闲链表
 * 检查free block的方式：
   * `first fit`
   * `best fit`
   * `ordered by address`
  * 利用`mydirver.c`文件进行正确性测试
  
  ## 总结
  虽然在刚开始学编程语言时就已经接触过 `malloc`和`free`这样的函数但其实只是会用，并不知道他们在系统底层是以一个什么样的形式和逻辑处理着内存分配问题。 借着这个实验，我们深入到stack里面以以一个字节一个字节的形式去处理内存分配问题，这相当于我们获得了对系统底层的理解又一块拼图。
  
  
 
