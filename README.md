# NCM格式文件转换 (Python version)

## 简介

本项目 fork 自[FakeC0de/NCM_dump](https://github.com/FakeC0de/NCM_dump).
与原版的唯一区别是在转换过程中会爱comment内写入歌曲的ID，以便我进行管理。

## 依赖

- python 3.6 （3.*系列）

```
pip(3) install pycryptodomex mutagen
```

## 使用

运行GUI即可打开可视化界面
```
python(3) GUI.py
```
包含两种处理：`单个ncm文件处理`和`指定文件夹内所有ncm文件批量处理`

两种输入方式：

- `输入`文件（夹）路径
- `按钮选择`单个文件或文件夹

点击`转换`按钮即可进行转换
