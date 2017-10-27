# 开发环境搭建教程
## golang安装
由于众所周知的原因，国内正常情况是上不去golang官网的，所以国内有几大论坛提供go安装包的下载    

[golang中国](https://www.golangtc.com/download)    

[go语言中文网](https://studygolang.com/dl)     

[gocn](https://dl.gocn.io/)     

[官网安装教程](http://docs.studygolang.com/doc/install)     

### windows
请选择msi文件直接下一步安装

安装完成后需要配置gopath工作路径，选择c盘或者d盘建立gopath文件夹，下面创建src、bin、pkg三个目录

右键计算机->属性->高级环境设置->环境变量，设置GOPATH=C:/gopath

### linux
1.使用自带的软件安装工具如yum,apt等安装
2.使用压缩包安装，并配置环境变量
3.使用源码安装
## git安装
[git官网](https://git-scm.com/)

### 生成ssh
`
cd ~/.ssh
ssh-keygen -t rsa -C "youremail@example.com"
`
## golang编码规范
[如何使用go编程](http://docscn.studygolang.com/doc/code.html)(中文翻译版)

[How to Write Go Code](https://golang.org/doc/code.html)(官方原版)

[如何使用go实效编程](http://docscn.studygolang.com/doc/effective_go.html)(中文翻译版)

[Effective Go](https://golang.org/doc/effective_go.html)(官方原版)

[Go Code Review Comments](https://github.com/golang/go/wiki/CodeReviewComments)
