# 解决下载安装配置java的困难

- ### [「下載java jdk」](https://www.oracle.com/technetwork/java/javase/downloads/jdk12-downloads-5295953.html)
  
- ## 使用管理員運行`cmd`來配置 

 1. 输入`SET JAVA_HOME=C:\Program Files\Java\jdk1.8.0_77`（等号后面为自己jdk的安装目录）
 2. 输入`SET CLASSPATH=%JAVA_HOME%\lib`（%JAVA_HOME%的意思是取得JAVA_HOME代表的值)
 3. 输入`SET Path=%JAVA_HOME%\bin`（%%里的内容与上条一致）

- ## 驗證

  输入`java`或者`javac`确认是否已经成功安装
---
本教程意在解決通過系統設置不能成功設置系統變量的問題。

亦可以用來快速設置。
