# 国内某家好像有名气的大数据公司 - AI平台开发实习生


## 要求
- 扎实的数据结构、算法基础，熟悉c++, java或者scala优先
- 熟悉spark或者tensorflow
- 有大规模分布式计算引擎设计与实现经验的优先
- 熟悉机器学习框架者优先
- 有大数据经验，熟练部署与使用Hadoop/Spark集群的优先

## Debut
- 自我介绍，项目经验（大约15分钟）

## 深度学习
- CNN的结构是怎么样的？
- 解释一下在你的项目中是怎么使用CNN的

## JAVA & Python
- JAVA中的Thread是怎么样实现的？
  JAVA中定义了Runnbable和Thread的接口，需要一段程序在子线程中运行时，将这段程序封装在一个类中，让这个类继承Runnable或者Thread（继承两者的方式不同）。  
  重写接口的run方法。
  
- JAVA中有没有线程安全的数据类型？
  - 有。JAVA中我们常见的int，long，boolean类型都不是线程安全的。他们都具有线程安全的版本：AtomicInteger, AtomicLong, AtomicBoolean  
  又，ArrayList和Vector的区别在于，ArrayList不是线程安全的，而vectoer则是线程安全的。
  
- JAVA中的MAP，怎么查找一个键值是否存在，如果不存在的话，新建这个键值，并赋值（put操作）。
- 介于我并不熟JAVA中的MAP，该问Python中的字典如何实现上述操作
- JAVA中如果多个线程同时访问MAP，并对它进行如上操作，怎么保证操作的原子性？（我翻译了一下的）
- Python中的多线程是如何实现/使用的？

## Online Test

在一个没有编译or运行功能在线测试平台上写，还没有缩进对齐（思维破碎）

leetcode上的一道题：

- [原题](https://leetcode.com/problems/two-sum/)

给定一个整数数组，一个整数目标值，找出这个数组中所有的一对数字，使得这对数字的和是目标值。

``` 
lis=[1,2,3,4,5]
target=5
return=[[1,4],[2,3]]
```

