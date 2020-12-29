# Compile OpenWRT

## Cài Đặt Các Thư Viện Để Compile

```
sudo apt install build-essential ccache ecj fastjar file g++ gawk \
gettext git java-propose-classpath libelf-dev libncurses5-dev \
libncursesw5-dev libssl-dev python python2.7-dev python3 unzip wget \
python3-distutils python3-setuptools rsync subversion swig time \
xsltproc zlib1g-dev
```

Chi tiết [tại đây](https://openwrt.org/docs/guide-developer/build-system/install-buildsystem#examples_of_package_installations)


## Chi Tiết Build From Source

```
git clone https://git.openwrt.org/openwrt/openwrt.git
cd openwrt
git tag
git checkout tags/v19.07.5
./scripts/feeds update -a
./scripts/feeds install -a
```

Xem [tại đây](https://openwrt.org/docs/guide-developer/quickstart-build-images)

## Những Điều Không Nên Làm Khi Compile Source

Xem [tại đây](https://openwrt.org/docs/guide-user/additional-software/beginners-build-guide#compiling_openwrt)

## Hướng Dẫn Viết Firmware Cho Thiết Bị Mới

Xem [tại đây](https://openwrt.org/docs/guide-developer/adding_new_device)


## Ví Dụ Viết Firmware Cho Thiết Bị Mới

Xem [tại đây](https://git.openwrt.org/?p=openwrt/openwrt.git;a=commitdiff;h=c198ca682c187e61730119134e1dde75da2e7a16;hp=6ae71708c9ced26961f73286d794e1aafedd6c52)

[back](/)