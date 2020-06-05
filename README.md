#go语言环境搭建
* 下载安装包 https://golang.google.cn/dl/
如：go1.14.4.windows-amd64.msi
* 安装后设置环境变量 bin目录加入PATH
* 编写go语言源文件
如：Hellworld.go
* 编译源文件为可执行文件
go build Hellworld.go
编译成功后windows环境，会在源文件目录生成可执行文件
Hellworld.exe
* 直接运行可执行文件即可
Hellworld.exe
* Linux也一样，生成的是二进制可执行文件，直接可以运行
* 从以上过程来看，go语言是一种编译型语言，即没有中间产物，
也不是在运行期才对源文件进行解释