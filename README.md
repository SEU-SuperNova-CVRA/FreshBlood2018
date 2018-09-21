# FreshBlood2018
This repository is for fresh blood who join in algorithm group

## Advice: 
any of install packages are supposed to be put in `/home/username`, you can type `'pwd'` to locate your current folder.

## qt常见问题
Remember to type these codes in your .pro file

```
#Configs 
TEMPLATE = app 
CONFIG += console
CONFIG -= app_bundle
CONFIG -= qt
CONFIG += c++14

#Libraries
unix: CONFIG += link_pkgconfig

#OpenCV
unix: PKGCONFIG += opencv
```
#### 常见问题
> <br>1.cannot find -lGL</br>
> 解决方案： https://www.cnblogs.com/coding-my-life/p/5677256.html

> <br>2.TypeError: Property 'asciify' of object Core::Internal::UtilsJsExtension(0xa2d060) is not a function </br>
> 解决方案 https://www.cnblogs.com/zhangjunwu/p/7417566.html

## opencv常见问题
记得把opencv压缩包放在/home/username目录下解压
