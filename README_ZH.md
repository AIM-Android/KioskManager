[View English](https://github.com/AIM-Android/KioskManager/blob/main/README.md)
# Kiosk设定管理
[Kiosk设定管理工具下载](https://github.com/AIM-Android/KioskManager/raw/main/KioskSetting_v1.0.5.apk)<br>
KioskSetting.apk需要 system权限，所以下载后，需要系统签名才能使用。<br>
[签过名的KioskSetting.Apk，适用研华AIM-78](https://github.com/AIM-Android/KioskManager/raw/main/KioskSetting_v1.0.5_signed_aim78.apk)

Kiosk管理工具可以将任意一个应用设置成开机全屏自动全屏启动，Android系统的状态栏和导航栏也会自动隐藏，如果设备工作在这种模式，我们就称为Kiosk模式。
在日常生活中，也我们也可以看到很多设备工作在Kiosk模式，比如：自助机，数位广告机，导览设备，ATM机，POS收银机等等。还有一些我们平时见不到的场景，如果工厂产线，工业自动化现场的设备，一版也会工作在Kiosk模式，即开机就运行业务程序，而不是启动到系统的桌面。
kiosk管理软件的功能：就是可以将客人第三方App，设置成为kiosk APP，开机后会自动启动该app，一般Kiosk应用场景对安全性要求也较高，所以，想要退出Kiosk模式，需要管理员输入正确密码才能退出。
研华kiosk管理方案的功能及优势：
* 可以将任意APP应用设置成Kiosk开机自动全屏启动应用，自动隐藏状态栏和导航栏
* 提供基于Web浏览器的Kiosk应用，可制成Web应用URL访问白名单
* 对管理工具，可根据需求设定密码；
* 可以禁止卸载，安装App应用；
* 可设置管理App应用白名单；
* 可修改系统参数；
管理工具主要界面如下:

![image](https://user-images.githubusercontent.com/20899121/158548501-f0e24739-d7f5-43a1-9d64-c590ce12171b.png)

在上图中，选择你需要设置成Kiosk模式的App进行设定即可，选择的App就可以开机自动全屏启动。
如果是想开机直接打开浏览器，并访问某个网页，我们在Kiosk管理工具中内置了webview组件（Firefox, chrome等浏览器，无法自动隐藏浏览器自身的菜单，工具栏，导航栏等，所以无法做到真正的Kiosk）。通过我们内置的webview组件，可以做到真正的web Kiosk，相关操作如下：
webview URL，点击下图中的WebStation Setup.

![image](https://user-images.githubusercontent.com/20899121/158548549-989aba05-907b-4d1c-9b22-76d5bab933d8.png)

输入你希望Webview默认访问的网页

![image](https://user-images.githubusercontent.com/20899121/158548604-48c78b7c-e5a1-442c-8869-7dcc9a7744e4.png)

选中WebStation图标，将它设置为Kiosk应用，WebStation就会全屏显示，并展示刚才设定的网页。即使重启后，WebStation仍会自动全屏启动，并展示该网页。
![image](https://user-images.githubusercontent.com/20899121/158548641-3f4f8eb3-1d77-4305-aecb-0deb6cec7441.png)

这就是展示的效果，可以开到，已经看不到Android的桌面了，也看不到Android设备的状态栏和导航栏。

![image](https://user-images.githubusercontent.com/20899121/158548682-2a8cbfe1-7e3c-4526-949d-9ed7fb36eab4.png)

也可以设定其他应用作为Kiosk应用，比如设置第三方Firefox 作为kiosk APP，选中Firefox，点击Lock & Launch，就可以完成设定：

![image](https://user-images.githubusercontent.com/20899121/158551397-3290f424-913c-49bf-9011-bc47a363bb69.png)

![image](https://user-images.githubusercontent.com/20899121/158551398-be191c81-3b38-4445-aeec-22346869f5c7.png)

一旦设定好以后，每次开机都会自动全屏启动，那万一要回退到到桌面，做一些操作，或者要修改设置另一个APP为Kiosk App，要如何退出呢？
退出kiosk mode相关操作:
屏幕左上角，从左往右拉，并持续一秒以上的手势，会触发退出kiosk mode的处理程序，弹出输入密码的对话框。

![image](https://user-images.githubusercontent.com/20899121/158551445-bd6c8ab8-da79-44be-83c1-6d518ef69738.png)

输入正确密码后，就可以退出。密码可以有管理员设置和修改。
![image](https://user-images.githubusercontent.com/20899121/158551525-4c3d6a85-0626-496c-bc20-9a1f312ac94e.png)

如果需要远程设定和控制设备的Kiosk模式，我们提供的AppHub远程设备管理方案可以满足你的需求，可以联系我们,<br>
Email:jianfeng.dai@advantech.com.cn;zhang.yang@advantech.com.cn
