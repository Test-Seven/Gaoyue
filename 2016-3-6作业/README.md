#Gaoyue 2016-3-6作业

**作业一：反编译apk，并用JD-GUI打开jar包，截图对比了反编译后的代码和源码**
<br>如下图是把dex文件转换成jar包,步骤记录：修改debug-app.apk修改后缀名为zip,然后解压，
<br>把classes.dex文件放到dex2jar工具中d2j-dex2jar.bat文件所在目录下,执行命令行：d2j-dex2jar.bat classes.dex
<br>![](https://raw.githubusercontent.com/Test-Seven/Gaoyue/master/img/%E8%BD%AC%E6%8D%A2%E6%88%90jar.jpg)
<br>如下图是反编译后的代码
<br>![](https://raw.githubusercontent.com/Test-Seven/Gaoyue/master/img/%E5%8F%8D%E7%BC%96%E8%AF%91%E5%90%8E%E7%9A%84%E6%BA%90%E7%A0%81.jpg)
<br>如下图是源码
<br>![](https://raw.githubusercontent.com/Test-Seven/Gaoyue/master/img/%E6%BA%90%E7%A0%81.jpg)

**作业二：用appt命令查看apk权限**
<br>![](https://raw.githubusercontent.com/Test-Seven/Gaoyue/master/img/permission.jpg)

**作业三：不同切入点编写monkey命令，并执行成功**
<br>多点击：
<br>![](https://raw.githubusercontent.com/Test-Seven/Gaoyue/master/img/touch1.jpg)
<br>![](https://raw.githubusercontent.com/Test-Seven/Gaoyue/master/img/touch2.jpg)
<br>![](https://raw.githubusercontent.com/Test-Seven/Gaoyue/master/img/touch3.jpg)
<br>多应用切换：
<br>![](https://raw.githubusercontent.com/Test-Seven/Gaoyue/master/img/appswitch1.jpg)
<br>![](https://raw.githubusercontent.com/Test-Seven/Gaoyue/master/img/appswitch2.jpg)
<br>![](https://raw.githubusercontent.com/Test-Seven/Gaoyue/master/img/appswitch3.jpg)
<br>手机硬件按钮对于应用的效果:
<br>![](https://raw.githubusercontent.com/Test-Seven/Gaoyue/master/img/syskeys1.jpg)
<br>![](https://raw.githubusercontent.com/Test-Seven/Gaoyue/master/img/syskeys2.jpg)
<br>![](https://raw.githubusercontent.com/Test-Seven/Gaoyue/master/img/syskeys3.jpg)

**作业四：查找motion和touch源码的方法，以及monkey中实现点击的最基本方法是什么**
<br>motion
<br>![](https://raw.githubusercontent.com/Test-Seven/Gaoyue/master/img/motioncode.jpg)
<br>touch
<br>![](https://raw.githubusercontent.com/Test-Seven/Gaoyue/master/img/touchcode.jpg)
<br>点击的最基本方法
<br>![](https://raw.githubusercontent.com/Test-Seven/Gaoyue/master/img/touchbasecode.jpg)

**作业五：找到应用下面的数据文件并打开**
<br>![](https://raw.githubusercontent.com/Test-Seven/Gaoyue/master/img/db1.jpg)
<br>![](https://raw.githubusercontent.com/Test-Seven/Gaoyue/master/img/db2.jpg)
<br>![](https://raw.githubusercontent.com/Test-Seven/Gaoyue/master/img/sqlite_db.jpg)

**作业六：monkey.js，运行结果截图**
<br>![](https://raw.githubusercontent.com/Test-Seven/Gaoyue/master/img/monkeyjs.jpg)

**作业七：安装ideviceinstaller，查看ios日志**
<br>brew install ideviceinstaller,然后通过idevicesyslog查看
<br>![](https://raw.githubusercontent.com/Test-Seven/Gaoyue/master/img/ios_log.jpg)
