# 3dxmas

> Nodejs application to control The PiHiut [3D Xmas Tree for Raspberry Pi](https://thepihut.com/products/3d-xmas-tree-for-raspberry-pi)

![3dxmas](3dxmas.gif)

## Install

The deb package is built for Raspbian.  To install download the latest deb package on the Raspberry Pi and install

```
curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
sudo apt-get install -y nodejs
sudo dpkg -i 3dxmas*.deb
```

## Uninstall

```
sudo dpkg --remove 3dxmas
```

## Building

Install [docker](https://docs.docker.com/install/) and [docker-compose](https://docs.docker.com/compose/install/) then run

```
git clone https://github.com/martinbark/3dxmas.git
cd 3dxmas
./dockerbuild
```

This will build the .deb file using a raspbian based Docker container.

## License

See the [LICENSE](LICENSE) file for license rights and limitations (MIT).
