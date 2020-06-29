# 环境搭建
1. 下载并安装Java SE8,且目前只能安装SE8版本[地址](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html "需要登录oracle账号")

2. 下载并安装Android SDK installer_r24.4.1-windows.exe [地址](https://www.androiddevtools.cn/)，sdk路径修改后配置系统环境变量ANDROID_HOME = D:\Program Files (x86)\Android\android-sdk; 添加系统环境变量path中，%ANDROID_HOME%\tools，%ANDROID_HOME%\platform-tools 直接添加即可

3. 下载Flutter SDK并配置 [地址](https://flutter.dev/docs/get-started/install/windows)， 执行flutter doctor下载相关依赖，网络遇到问题时配置国内镜像（新增系统环境变量)

   > ```
   > export PUB_HOSTED_URL=https://pub.flutter-io.cn
   > export FLUTTER_STORAGE_BASE_URL=https://storage.flutter-io.cn
   > ```

   再次执行flutter doctor，遇到问题并解决

4.  安装夜神模拟器，并启用开发者模式，解决设备连接不上的问题

6. vscode 安装flutter插件，ctrl + shift + p 执行flutter new 新建flutter项目

   

   

   

   

