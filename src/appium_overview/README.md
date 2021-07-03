# Appium概览

移动端测试框架中，流行度最广的是：`Appium`

* `Appium`
  * 概述
    * Appium是最主流的自动化测试框架，支持自动化操作`iOS`手机、`Android`手机和`Windows`系统中的`原生`、`移动Web`和`混合`的应用。
      * `原生应用`：用`iOS`、`Android`或`Windows SDKs`编写的应用
      * `移动Web应用`：用移动端浏览器访问的应用
        * `iOS`上的`Safari`、`Chrome`
        * `Android`上的内置浏览器
      * `混合应用`：带有一个`Webview`的包装器，用来和Web内容交互的原生控件
  * 主页
    * GitHub
      * [appium/appium: Automation for iOS, Android, and Windows Apps.](https://github.com/appium/appium)
    * 官网
      * [Appium: Mobile App Automation Made Awesome.](http://appium.io)

## Appium依赖于底层的系统框架

* iOS
    * Appium在`iOS >9.3` 后全面采用`WebDriverAgent`的方案
* `Android >= 4.3`: Google's [UiAutomator / UiAutomator2](https://developer.android.com/training/testing/ui-automator)
* `Windows`: Microsoft's [WinAppDriver](http://github.com/microsoft/winappdriver)
