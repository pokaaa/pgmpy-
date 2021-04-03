# pgmpy源码学习笔记

## 学习目标
 - 学习[pgmpy](https://github.com/pgmpy/pgmpy)的过程记录
 - 查找[对应源码](https://github.com/pgmpy/pgmpy/tree/dev/pgmpy)，学习贝叶斯网络的各部分实现细节

## 学习来源
> **原笔记**源自：*[pgmpy/examples](https://github.com/pgmpy/pgmpy/tree/dev/examples)*.

## 我的笔记
> **我的学习笔记**以"""红色注释"""的形式添加在了**原笔记**的代码部分
> 希望对大家了解学习pgmpy有帮助

## 目前已完成源码学习：
 - 创建贝叶斯网络
   - 定义模型结构、CPD 
   - 判断d-分隔/有向分隔
   - 马尔可夫性 
 - 贝叶斯网络的推理问题
   - 后验概率问题——变量消元算法
   - 最大后验假设（MAP）问题

