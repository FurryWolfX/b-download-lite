简化原库的下载逻辑，交付给 aria2

## :dolphin:运行环境

Version: Python3

## :dolphin:安装依赖库

```
pip3 install -r requirements.txt
```

## 生成 manifest 后用 aria2 下载

```
aria2c -i manifestFile.txt
```