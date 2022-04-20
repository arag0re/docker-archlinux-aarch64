# archlinux-aarch64 base image
1. download this repoaitory
2. cd to this repository folder
3. download the lastes archlinux-aarch64 rootfs tarball from [archlinuxarm.org](https://archlinuxarm.org/about/downloads) for example by executing:
```
wget -c http://os.archlinuxarm.org/os/ArchLinuxARM-aarch64-latest.tar.gz
```
4. build docker image from Dockerfile with:
```
docker build -t archlinux-aarch64 .
```
