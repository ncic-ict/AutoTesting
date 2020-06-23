PyAndroidPermanceTest
==========================
此脚本目前需要少量的修改才能够用在你的工作中
环境搭建： 

> 1.本地还是需要有android sdk环境。至少adb能够使用
> 2.本地需要安装python2.7版本

使用流程：
> 1. git clone项目到本地
> 2. 电脑链接机器，adb识别出来机器
> 3. 安装listener.apk，并启动，隐藏到后台
> 4. 打开终端，并且输入python Test_File.py {package name} {time(hour)}
> 5. 然后就进行测试
> 6. 测试结束之后，可以等设置的时间到了，也可以切换到终端，然后Ctrl+C，终止程序


> 报告会在根目录下生成。注意：Android4.3以及以上机器流量无法获取暂时

