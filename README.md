# archlinux-aarch64 base image

1. cd to this repository folder
2. download the lastes archlinux-aarch64 rootfs tarball from [archlinuxarm.org](https://archlinuxarm.org/about/downloads) for example by executing

```
wget -c http://os.archlinuxarm.org/os/ArchLinuxARM-aarch64-latest.tar.gz
```

3. build docker image from Dockerfile

```
docker build -t archlinux-aarch64 .
```
