## 在Windows上配置CLion

- MinGW
- Cygwin

### Cygwin

​	MinGW 安装 packages 的时候，总是报错，可能需要开启代理吧。没找到哪里可以添加国内源

> Cygwin

- 下载 [setup-x86_64.exe](https://cygwin.com/setup-x86_64.exe)
  - 安装的时候，会有一个弹框，可以添加国内源（阿里、网易）
  - https://mirrors.aliyun.com
  - C:\cygwin64

### 配置CLion

- 设置->构建、执行、部署（查看参考[官方文档]）
  - 工具链
- 其他
  - 在设置里面修改编码为UTF-8
  - 换行模式 Unix
  - 主题、文字样式、文字大小

## 参考

- [官方文档](https://www.jetbrains.com/help/clion/quick-tutorial-on-configuring-clion-on-windows.html)
- [Cygwin-Install](https://cygwin.com/install.html)