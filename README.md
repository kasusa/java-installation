# 解决下载安装配置java的困难

- [「下載java jdk」](https://www.oracle.com/technetwork/java/javase/downloads/jdk12-downloads-5295953.html)

- ~~使用管理員運行`cmd`來配置这样根本没有用！~~
  
 在win下要使用我的电脑=>的属性。
 也运行 `sysdm.cpl`直接打开环境变量

 1. `SET JAVA_HOME=（自己jdk的安装目录）`
 2. `SET CLASSPATH=.`
 3. `SET CLASSPATH=%JAVA_HOME%\lib`（%JAVA_HOME%的意思是取得JAVA_HOME代表的值)
 4. `SET Path=%JAVA_HOME%\bin`

  ## 驗證

输入`java`或者`javac`确认是否已经成功安装

---
# 解决下载安装配置gcc的困難

1. [mingw下載站](http://www.mingw.org/)
2. 記得開啓翻qiang
3. 安裝所有`mingw32-gcc-g++`以及`mingw32-gdb`開頭的東西
4. 运行 `sysdm.cpl`直接打开环境变量
5. 编辑`Path`
6. 点击“新建”，并输入`C:\MinGW\bin`（如果自行更改了MinGW的安装路径请自行对照修改此处的路径）
7. 全部点“确定”关闭所有对话框。
  ## 驗證
控制臺输入`gcc -v`确认是否已经成功安装
