## 本fork修改

 - **本 fork 为 1.7.1 版本添加了 Python3.5 支持（唯一改动），将其中不符合 3.5 语法特性的语句进行了修改。**
 
 > 暂未发现除语法特性以外的其他运行时错误

### V1

> ~~仅支持 Python3.6+~~ 支持Python3.5+


## 🔰 安装

**pip 安装**
```shell
# 安装 v1 以上版本
$ pip install pyecharts35 -U
```

**源码安装**
```shell
# 安装 v1 以上版本
$ git clone https://github.com/sailist/pyecharts
$ cd pyecharts
$ pip install -r requirements.txt
$ python setup.py install

# 如果linux下无权限，使用：
$ python setup.py install --user
```

## 📝 使用

请参考原 repo [pyechart/pyechart](https://github.com/pyecharts/pyecharts)

> 版本限定：1.7.1

## 📃 License

MIT [©chenjiandongx](https://github.com/chenjiandongx)