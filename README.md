# qpis


## 老系统开发环境记录
1. 安装vc++6，打开工程文件后编译报fores.h找不到，搜索后发现该文件在一个叫C:\include\UCanCode.Net Software\XD++ Library\FO\Include的目录下，copy大部分的.h文件后依然存在一个找不到文件的问题。

切换到虚机，碰到编译时指定的是c盘不带x86的program files目录，修改配置后编译通过并正常运行。
