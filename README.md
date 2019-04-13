串口调试工具
========

1、首先，你系统中必须安装Java并配置了环境变量，此处请自行百度/Google。
----

2、解压important下的rxrx.***.zip，
-------

Mac
##
    (1)RXTXcomm.jar和librxtxSerial.jnilib 复制到/Library/Java/Extensions 目录中
    
Windows:
##
    (1)把两个dll文件复制l到“%JAVA_HOME%\jre\bin”和c:/windows/system32下。
    (2)复制RXTXcomm.jar到“%JAVA_HOME%\jre\lib\ext”和“%JAVA_HOME%\lib”下


上面的操作为了使用RXTXcomm调用串口
###

3、直接打开out/artifacts/SerialTools_jar/SerialTools.jar 就可以进行串口调试了，当然主要是Mac上能用
----

如果有问题，请留言或者邮件咨询
###
    E-mail:371934907@qq.com