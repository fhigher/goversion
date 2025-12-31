# goversion
### a simple go multiple version manage tool by shell language.

使用步骤：
1. 使用gover init 创建仓库，初始时执行一次
2. 下载适合当前系统，指定版本的go安装包，解压到仓库，并重命名为版本号，例：1.24.3
3. 执行gover use 1.24.3，指定使用该版本
4. 设置环境变量GOROOT为 "仓库路径/current"
5. GOPATH, GOPROXY自行定义

### gover命令：
    'help': 查看帮助信息
    
    'init'：初始化Go多版本管理仓库目录。

    'list'：查看当前安装的所有Go版本。

    'use 1.*.*'：切换到指定的Go版本。
