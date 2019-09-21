# 解决下载安装配置java的困难

- ### [「下載java jdk」](https://www.oracle.com/technetwork/java/javase/downloads/jdk12-downloads-5295953.html)

- ## ~~使用管理員運行`cmd`來配置~~

  
 在win下要使用我的电脑=>的属性。
 运行 `sysdm.cpl`直接打开环境变量

 1. `SET JAVA_HOME=（自己jdk的安装目录）`
 2. `SET CLASSPATH=.`
 3. `SET CLASSPATH=%JAVA_HOME%\lib`（%JAVA_HOME%的意思是取得JAVA_HOME代表的值)
 4. `SET Path=%JAVA_HOME%\bin`

- ## 驗證

  输入`java`或者`javac`确认是否已经成功安装
---

