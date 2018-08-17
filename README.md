# Netease Cloud Music Copyright Protection File Dump (Python version)

## 简介

本项目 fork 自大佬的移植 python 版本项目[nondanee/ncmdump](https://github.com/nondanee/ncmdump) 在此非常感谢

也非常感谢原 C++ 版本代码大佬的 [anonymous5l/ncmdump ](https://github.com/anonymous5l/ncmdump)项目，感谢源代码作者的 Walkman帮了大忙（大雾）

如原作者描述 python 版本运行相对较慢 但是优势在于安装简单（原C++版本需要自行编译taglib相对操作较多）

另：原python版本使用的是pycrypto库相对较老且在部分一体包中的实现相对较差 已替换使用相对较新兼容性较好的pycryptodomex（pycryptodome的共存版本）

## 依赖

```
pip(3) install pycryptodomex mutagen
```

## 使用

指定ncm文件
```
python(3) ncmdump.py [files ...]
```
工作目录下所有ncm文件
```
python(3) ncmdump.py
```
