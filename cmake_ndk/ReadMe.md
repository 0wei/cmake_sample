[【Cmake】利用NDK进行Android的交叉编译（附实例）_android ndk 交叉编译-CSDN博客](https://blog.csdn.net/qq_38410730/article/details/103622813)


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