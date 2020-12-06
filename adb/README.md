# ADB Common cmd

~~~bash
$ adb connect 127.0.0.1:7555            #连接mumu模拟器,其他模拟器端口上网查
$ adb devices                           #查看当前所有连接设备
$ adb -s <deviceid> <cmd>               #用于在有多个连接设备时指定某个设备执行某些命令
$ adb shell                             #shell登录手机,类似linux交互式登录,有很多linux命令可以用
$ adb push <local path> <remote path>   #本地文件上传到手机
$ adb pull <remote path> <local path>   #手机文件下载到本地
$ adb logcat -s Unity:E                 #日志查看  Unity表示查看Unity日志 日志级别 :D :I :W :F :S :V
$ adb logcat -b crash                   #查看crash日志,卡死,闪退时用
$ adb logcat -c                         #清除logcat日志缓存区 一般是512kb
~~~
