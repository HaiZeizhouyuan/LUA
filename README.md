# LUA
Lua 环境安装
Linux 系统上安装
Linux & Mac上安装 Lua 安装非常简单，只需要下载源码包并在终端解压编译即可，本文使用了5.3.0版本进行安装：

curl -R -O http://www.lua.org/ftp/lua-5.3.0.tar.gz
tar zxf lua-5.3.0.tar.gz
cd lua-5.3.0
make linux test
make install
Mac OS X 系统上安装
curl -R -O http://www.lua.org/ftp/lua-5.3.0.tar.gz
tar zxf lua-5.3.0.tar.gz
cd lua-5.3.0
make macosx test
make install
接下来我们创建一个 HelloWorld.lua 文件，代码如下:
print("Hello World!")
执行以下命令:

$ lua HelloWorld.lua
输出结果为：

Hello World!

Window 系统上安装 Lua
window下你可以使用一个叫"SciTE"的IDE环境来执行lua程序，下载地址为：

本站下载地址：LuaForWindows_v5.1.4-46.exe
Github 下载地址：https://github.com/rjpcomputing/luaforwindows/releases
Google Code下载地址 : https://code.google.com/p/luaforwindows/downloads/list
双击安装后即可在该环境下编写 Lua 程序并运行。

你也可以使用 Lua 官方推荐的方法使用 LuaDist：http://luadist.org/
