# 自己实现所有STL容器！

比起艰深的 STL 源码解读，不如自己动手实现STL，更能生动直观地掌握底层技术细节，破除模棱两可心理，了解常见的最佳实践。

作为一个教学用的 STL 实现，所有代码均写得尽量可读易懂，尽可能照顾 C++ 初学者，不像真正的标准库那样命名规范复杂，为了追求极致性能和灵活性牺牲可读性。代码中在必要时还附有注释帮助读者理解，建议结合我的 B 站视频观看。

## 第一课：Function

视频链接：[BV1yH4y1d74e](https://www.bilibili.com/video/BV1yH4y1d74e)

相关文件：

- [Function.hpp](Function.hpp)
- [test_Function.cpp](test_Function.cpp)

这是本系列试水的第一课，自己实现std::function容器。本期视频中我们从C语言传统函数指针的痛点入手，介绍了现代C++的仿函数思想，通过cppinsights.io这个在线工具解构了C++11 lambda语法糖的原理，最终，我们借助类型擦除思想，实现了和标准库一样的万能函数容器：std::function。

## 第二课：UniquePtr

视频链接：[BV1Hw411y7g5](https://www.bilibili.com/video/BV1Hw411y7g5)

相关文件：

- [UniquePtr.hpp](UniquePtr.hpp)
- [test_UniquePtr.cpp](test_UniquePtr.cpp)

小彭老师C++实战演练系列之“自己实现所有STL容器”。比起艰深的STL源码解读，不如自己动手实现STL，更能生动直观地掌握底层技术细节，破除模棱两可心理，了解常见的最佳实践。这是本系列试水的第二课，自己实现std::unique_ptr智能指针。本期视频中我们从封装C语言的FILE为内存安全的类的入手，介绍了现代C++如何借助RAII思想安全管理资源，避免内存泄漏，了解五大函数各自的作用。最终借助所学知识，实现了和标准库一样的独占型智能指针：std::unique_ptr。

## 第三课：Array

视频链接：[BV1Tw411k7QB](https://www.bilibili.com/video/BV1Tw411k7QB)

相关文件：

- [Array.hpp](Array.hpp)
- [test_Array.cpp](test_Array.cpp)

小彭老师C++实战演练系列之“自己实现所有STL容器”。比起艰深的STL源码解读，不如自己动手实现STL，更能生动直观地掌握底层技术细节，破除模棱两可心理，了解常见的最佳实践。这是本系列试水的第三课，自己实现std::array静态数组。本期视频中我们从封装C语言的原始数组为深拷贝的容器类入手，介绍了现代C++如何借助封装思想把底层细节隐藏起来，初步认识了迭代器的概念，同时科普了正经的标准库中为什么都是形如_Tp、__traits这种一堆下划线开头的变量名。最终借助所学知识，封装了和标准库一样的静态数组：std::array。

## 第四课：Vector

视频链接：[BV1V84y127Pi](https://www.bilibili.com/video/BV1V84y127Pi)

小彭老师C++实战演练系列之“自己实现所有STL容器”。比起艰深的STL源码解读，不如自己动手实现STL，更能生动直观地掌握底层技术细节，破除模棱两可心理，了解常见的最佳实践。这是本系列试水的第四课，自己实现std::vector动态数组。本期视频中我们从封装C++98的new数组为深拷贝的容器类入手，介绍了现代C++如何借助RAII思想保障内存安全，初步认识了迭代器的概念，同时科普了size与capacity的区别，认识了push_back的底层原理。最终借助所学知识，封装了和标准库一样的动态数组：std::vector。

## 第五课：List

视频链接：[BV1SC4y1G7Ab](https://www.bilibili.com/video/BV1SC4y1G7Ab)

相关文件：

- [List.hpp](List.hpp)
- [test_List.cpp](test_List.cpp)

小彭老师C++实战演练系列之“自己实现所有STL容器”。比起艰深的STL源码解读，不如自己动手实现STL，更能生动直观地掌握底层技术细节，破除模棱两可心理，了解常见的最佳实践。这是本系列试水的第五课，自己实现std::list双向循环链表。本期视频中我们从封装经典的双向循环链表为C++容器类入手，介绍了如何借助一个假节点避免尾节点特殊判断的开销，并深入认识了迭代器的分类，自己动手实现了一款双向迭代器，同时科普了代码复用(DRY原则)的重要性。最终借助所学知识，封装出了和标准库一样的双向循环链表容器std::list，完美支持增删改查等操作。

## 第六课：Optional

视频链接：[BV___](https://www.bilibili.com/video/BV___)

相关文件：

- [Optional.hpp](Optional.hpp)
- [test_Optional.cpp](test_Optional.cpp)
