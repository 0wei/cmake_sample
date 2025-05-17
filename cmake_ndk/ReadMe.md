[【Cmake】利用 NDK 进行 Android 的交叉编译（附实例）\_android ndk 交叉编译-CSDN 博客](https://blog.csdn.net/qq_38410730/article/details/103622813)

NDK 下载地址: https://googledownloads.cn/android/repository/android-ndk-r26d-linux.zip

运行编译脚本: `build.sh`
推送到设备端: `adb push cmake_sample\demo_02\build\hello /data/local/tmp/`
设备端运行:

```shell
adb shell
cd /data/local/tmp
chmod chmod +x hello
./hello
```

# VSCode 配置 NDK 自动构建

参考 [kpa32/vscode-ndk-quickstart](https://github.com/kpa32/vscode-ndk-quickstart)

主要配置 CMakePresets.json 文件即可
