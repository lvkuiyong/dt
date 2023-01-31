# 构建说明

## 安装依赖包

git-core libc6-dev-i386 x11proto-core-dev libx11-dev libgl1-mesa-dev unzip fontconfig
bc bison build-essential ccache curl flex g++-multilib gcc-multilib git gnupg gperf imagemagick
lib32ncurses5-dev lib32readline-dev lib32z1-dev libelf-dev liblz4-tool libncurses5 libncurses5-dev
libsdl1.2-dev libssl-dev libxml2 libxml2-utils lzop pngcrush rsync
schedtool squashfs-tools xsltproc
zip zlib1g-dev

## 初始化储存库并下载

```sh
repo init -u https://github.com/LineageOS/android.git -b lineage-20.0

repo sync
```

## 构建系统

使用脚本初始化ROM环境

```sh
source build/envsetup.sh
# 或
. build/envsetup.sh
```

选择构建目标

```
breakfast
```

开始编译

```
brunch
```