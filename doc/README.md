```shell
sudo docker pull ubuntu
sudo docker pull ubuntu:20.04
sudo docker search calibre
sudo docker pull linuxserver/calibre-web
sudo docker pull linuxserver/calibre

sudo docker run --name moredoc --privileged -itd -p 8880:8880 -v "$(pwd)"/moredoc:/moredoc ubuntu:20.04
sudo docker run -itd linuxserver/calibre-web
sudo docker run -itd linuxserver/calibre

docker run -d --name=calibre -p 8083:8083 -v /calibre/config:/config -v /calibre/books:/books technosoft2000/calibre-web

sudo docker exec -it calibre bash

sudo docker exec -it moredoc bash
sudo docker stop moredoc
sudo docker start moredoc
sudo docker rm moredoc
apt-get update
apt-get install vim
apt-get install sudo
apt-get install wget
apt-get install python
# apt-get install libgl1-mesa-glx
# sudo apt-get install build-essential
apt-get install libegl1
apt-get install libopengl0

libegl1 and libopengl0

sudo apt-get install net-tools
sudo apt-get install openssh-server
sudo apt-get install build-essential
sudo apt-get install libgl1-mesa-dev
sudo apt-get install gdb
apt-get install cmake
https://www.cnblogs.com/Jankin-Wen/p/15647042.html
wget https://download.qt.io/archive/qt/6.4/6.4.0/single/qt-everywhere-src-6.4.0.tar.xz
wget http://ftp.br.debian.org/debian/pool/main/x/xcb-util/libxcb-util1_0.4.0-1+b1_amd64.deb

xz -d qt-everywhere-src-6.4.0.tar.xz
tar -xf qt-everywhere-src-6.4.0.tar
tar -Jxf qt-everywhere-src-6.4.0.tar.xz

sudo dpkg -i libxcb-util1_0.4.0-1+b1_amd64.deb

https://www.bookstack.cn/read/moredoc/install-linux.md
https://www.bookstack.cn/read/dochub/env-calibre.md
sudo -v && wget -nv -O- https://download.calibre-ebook.com/linux-installer.py | sudo python -c "import sys; main=lambda:sys.stderr.write('Download failed\n'); exec(sys.stdin.read()); main()"

docker build -t truthhun/dochub:v2.3 .
docker run -d -p 8090:8090 --name dochub-v2.3 truthhun/dochub:v2.3

https://code.calibre-ebook.com/signatures
docker pull linuxserver/calibre

https://new.qq.com/rain/a/20210312A08MGH00
Tiny
https://github.com/OpenAtomFoundation/TencentOS-tiny
```

```
# deb http://snapshot.debian.org/archive/debian/20211220T000000Z bullseye main
deb http://mirrors.aliyun.com/debian bullseye main
# deb http://snapshot.debian.org/archive/debian-security/20211220T000000Z bullseye-security main
deb http://mirrors.aliyun.com/debian-security bullseye-security main
# deb http://snapshot.debian.org/archive/debian/20211220T000000Z bullseye-updates main
deb http://mirrors.aliyun.com/debian bullseye-updates main
```

```
apt-get install qt6
libQt6Core.so.6: cannot open shared object file: No such file or directory
```