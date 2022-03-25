[查看中文版说明](https://github.com/AIM-Android/KioskManager/blob/main/README_ZH.md)
# Kiosk Manager

[Click to download Kiosk management tool]()

Kiosk management tool can set any application to start automaticly in full-screen when boot, Android system status bar and navigation bar will also be automatically hidden, if the device works in this mode, we are called Kiosk mode.

In daily life, we can also see a lot of device working in Kiosk mode, such as: self-service machines, digital signage, navigation device, ATM, POS device and so on. There are also some scenes that we usually do not see, if the factory, industrial automation device will also work in Kiosk mode, that is, Run the automation program immediately after booting , rather than boot to the system desktop.

Kiosk management software function: You can set the any App as a kiosk APP, that is, the kiosk App will automatically start after booting in full screen. Because kiosk application scenario requirement higher security, so if you want to exit the kiosk mode, the password is required to enter to exit this kiosk mode.

Functions and benefits of Advantech kiosk management solution:

* You can set any APP application to kiosk boot automatic full-screen launch application, automatically hide the status bar and navigation bar
* Provides a Web browser-based Kiosk application
* For management tools, passwords can be set to enhanced security ;
* Permission to uninstall or install App can be prohibited 
* You can enable whitelist for App, only the App in whitelist can run;

The main interface of the management tool is as follows:

![image](https://user-images.githubusercontent.com/20899121/158548501-f0e24739-d7f5-43a1-9d64-c590ce12171b.png)

In the above figure, You can easily select an app and set it as Kiosk APP, and then the App can start automatically in full screen.

If you want to open the browser directly when boot and visit a fixed webpage, we have built a webview component into the Kiosk management tool (Firefox, chrome and other browsers, can not automatically hide the browser's own menus, toolbars, navigation bars, etc., so it is impossible to do the real web Kiosk with these browsers). Through our built-in webview component, you can do a real web Kiosk, the operations are as follows:

Webview URL, click WebStation App in the image below
![image](https://user-images.githubusercontent.com/20899121/158548549-989aba05-907b-4d1c-9b22-76d5bab933d8.png)

Enter the web page that you want Webview to visit by default:

![image](https://user-images.githubusercontent.com/20899121/158548604-48c78b7c-e5a1-442c-8869-7dcc9a7744e4.png)

Select the WebStation icon and set it to the Kiosk app, and WebStation will display it in full screen and display the web page you just set up. Even after restarting, WebStation will automatically start full screen and display this webpage.

![image](https://user-images.githubusercontent.com/20899121/158548641-3f4f8eb3-1d77-4305-aecb-0deb6cec7441.png)

With kiosk management, you can no longer see the Android desktop, nor can you see the status bar and navigation bar of the Android device.

![image](https://user-images.githubusercontent.com/20899121/158548682-2a8cbfe1-7e3c-4526-949d-9ed7fb36eab4.png)

You can also set other applications as Kiosk applications, such as setting any third-party App as a kiosk APP, for examples ,set Firefox as kiosk App, select Firefox, click Lock & Launch, you can complete the setting:

![image](https://user-images.githubusercontent.com/20899121/158551397-3290f424-913c-49bf-9011-bc47a363bb69.png)

![image](https://user-images.githubusercontent.com/20899121/158551398-be191c81-3b38-4445-aeec-22346869f5c7.png)

after setting, every time you boot it will automatically start full screen, so if you have to show to the desktop, do some operations, or modify the setting of another APP as Kiosk App, how to quit?

Exit kiosk mode-related operations:

The gesture in the upper left corner of the screen, swipe from left to right, and lasting more than a second, triggers to exits kiosk mode, poping up a dialog box for entering the password.

![image](https://user-images.githubusercontent.com/20899121/158551445-bd6c8ab8-da79-44be-83c1-6d518ef69738.png)

Once you have entered the correct password, you can exit. Passwords can be set and modified by administrators.

![image](https://user-images.githubusercontent.com/20899121/158551525-4c3d6a85-0626-496c-bc20-9a1f312ac94e.png)

If you need to remotely manage Kiosk mode of the device, we provide AppHub remote device management solutions to meet your needs, if you need this solution, please contact us:<br>
email:jianfeng.dai@advantech.com.cn;zhang.yang@advantech.com.cn
