# debian-example-nodejs-package

an example Node.js bin script as a Debian package

## demo

first install build dependencies

```shell
sudo apt install debmake devscripts debhelper
```

then

```
git clone https://github.com/debian-example-nodejs-package
cd debian-example-nodejs-package
cd nodejs-package
debuild
cd ..
dpkg -i example-nodejs_1.0.0_amd64.deb
example-nodejs
```
