## Python-iOS
---- 
### What is this?
---- 

这是一个使用Python开发iOS程序的demo。详细介绍可以参考这篇博客：

**[http://ifujun.com/shi-yong-pythonkai-fa-ioscheng-xu/](http://ifujun.com/shi-yong-pythonkai-fa-ioscheng-xu/)**

主要使用了:
- [pybee](http://pybee.org/)开源的编译脚本[Python-iOS-support](https://github.com/pybee/Python-iOS-support)。
- [rubicon-objc](https://github.com/pybee/rubicon-objc)，一个连接Python和objc的桥梁。
- [cookiecutter](http://cookiecutter.rtfd.org/)，一个可以在模板中快速创建工程的一个工具。
- [Python-iOS-template](https://github.com/pybee/Python-iOS-template)，[pybee](http://pybee.org/)开源的使用Python开发iOS工程的模板。

### How to install it?
---- 

1. clone下工程。
2. [下载](https://github.com/pybee/Python-iOS-support/releases)一个可用版本的`Python.framework`和`OpenSSL.framework`。
3. 将下载好的`Python.framework`和`OpenSSL.framework`放置于工程根目录上，也就是和`xcodeproj`文件同级目录。
4. 编译运行。

运行结果：

![](http://7i7i81.com1.z0.glb.clouddn.com/blogimage_python_ios_6.png)

demo中只修改了rootViewController的背景，然后在上面添加了一个label。

当然，它还能做很多事情。

### License
---- 
MIT.