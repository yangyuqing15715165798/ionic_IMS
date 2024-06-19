代码运行环境配置
1简介
该APP基于ionic3 + cordova 开发（非原生APP），其中，ionic3基于angular。
2环境配置
2.1安装 node.js，下载链接：https://nodejs.org/en/，安装完成后在cmd分别执行node -v，npm –v，如能显示版本号，则安装成功。
2.2安装 cordova，在cmd执行安装命令：npm install -g cordova，安装完成后执行 cordova –v，如能显示版本号，则安装成功。
2.3安装 ionic，在cmd执行安装命令：npm install –g ionic，安装完成后执行 ionic –v，如能显示版本号，且主版本号为3，则安装成功。
2.4IDE：WebStorm
3运行
3.1用WebStorm打开项目后，在Terminal执行命令：npm install，用于安装相关依赖文件。
3.2在Terminal执行命令：ionic serve，在浏览器打开的页面中可以看到页面效果（注：因该APP通过cordova插件调用了部分手机原生功能，所以在浏览器无法直接预览，浏览器页面会报错）。
3.3在Terminal中按 ctrl + C，可结束运行。
4编译/打包
4.1本地部署好Android开发环境后，在webStorm的Terminal执行命令：ionic cordova build android，用于打包APP安装包。命令执行成功后，在项目的platforms/android/build/outputs/apk/debug目录下会生成android-debug.apk文件。
