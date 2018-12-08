# DL 岗位，没几个问题，基本凉凉

- C++中static修饰词在成员变量和成员函数前分别表示什么？
  - static 修饰变量： 一个 student class 有一个静态成员，年龄。实例化了多个student类型的对象，小明和小红，修改小明的年龄，小红的年龄也会变化。  
  静态变量只占据一份内存空间，使用静态变量可以节省内存空间。
  - static 修饰成员函数： 使用静态函数不需要实例化这个类，并且这个函数不能访问这个类中的成员。因为它不具有指向本对象的指针。

- C++中const修饰函数表示什么？
  - 在成员变量前表示这个成员变量不可修改。
  ```
  const int * a4 = &a1;   ///const data,non-const pointer
  int * const a5 = &a1;   ///non-const data,const pointer
  int const * const a6 = &a1;   ///const data,const pointer
  const int * const a7 = &a1;   ///const data,const pointer
  ```
  const的指针表示地址是固定的，但是这个地址上的值是可以变化的
  - const 修饰成员函数
  const 在参数后表示此函数不能调用非const成员函数，并且只能调用const的成员变量
  ```
  void func(int x) const
  {
  
  }
  ```
  
  - const 修饰函数返回值
  如果返回的是const的值，那么函数返回值必须赋给一个const的变量
  ```
  const int * func()
  {  
 
  }
  ```
  
- python中map函数和reduce的函数的用法分别是？
  - map: 
  ```
  map(function, iterable）
  ```
  fuction 函数依次以iterable内的元素为参数运行，返回function函数的返回值的列表
  
  - reduce
  //太棒了我完全按照mapreduce里的reduce讲的：）
  ```
  reduce(lambda x, y: x+y, [1,2,3,4,5])
  ```
  1+2+3+4+5=15
  return 15
  
- pytorch中dataloader的用法是？

  - [解答](https://blog.csdn.net/zw__chen/article/details/82806900)

  //不想写了，答得完全不着调
