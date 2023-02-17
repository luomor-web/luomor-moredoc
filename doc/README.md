```shell
sudo docker pull ubuntu
sudo docker pull ubuntu:20.04

sudo docker run --name moredoc --privileged -itd -p 8880:8880 -v "$(pwd)"/moredoc:/moredoc ubuntu:20.04

sudo docker exec -it moredoc bash
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

https://www.bookstack.cn/read/moredoc/install-linux.md
https://www.bookstack.cn/read/dochub/env-calibre.md
sudo -v && wget -nv -O- https://download.calibre-ebook.com/linux-installer.py | sudo python -c "import sys; main=lambda:sys.stderr.write('Download failed\n'); exec(sys.stdin.read()); main()"

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