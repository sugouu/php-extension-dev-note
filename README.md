# php-extension-simple-dev-note
> php扩展基础开发学习笔记

### 扩展是什么

用过php的人一定也用过php扩展。php本身带有86个扩展，扩展是对php语言功能的一个延伸，php的核心由两部分组成：最底层的 Zend引擎 和 PHP内核 。ze把脚本解析成机器可读的符号，也会处理内存管理，变量作用域，程序调度。PHP内核则主要涉及主机环境（Apache，IIS，Nginx），处理与主机的通信。

### 为什么要开发php扩展
php本身已经拥有很丰富的函数库，再加上php7的发布php性能提高了很多，一般情况下已经够我们使用了，那为什么我们要开发php扩展呢？

- 比较注重效率的应用，比如：图像算法
- 有些系统调用不能通过php直接访问，比如：linux下fork函数创建进程
- 想商业化一个应用但又不想暴露源码，也可以使用zend公司的加密工具 Zend Guard
- 对php扩展开发相关的学习，能学习到php语言层面学不到的知识

### 学习内容
- 配置编译环境
- 第一个简单的php扩展
- PHP扩展源码基本结构
- PHP扩展的参数
- PHP扩展函数值返回
- 开发一个UUID扩展

### 参考资料

- [《PHP扩展开发及内核应用》](https://github.com/qzfzz/php7-extension-dev-book)
- 《PHP+核心技术与最佳实践》搜索下载


## lets go
[学习开始](<index.md>)




