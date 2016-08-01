# My Glitter

A personal fork of [Glitter](https://github.com/Polytonic/Glitter) by Polytonic.

### Usage

This project is intended to be downloaded, modified and then built.

```bash
$ git clone --recursive https://github.com/mottosso/myglitter
$ cp -r myglitter myproject
$ cd myproject
$ mkdir build
$ cd build
$ cmake -G "Visual Studio 14 2015" ..
$ msbuild myproject.vcxproj
```
