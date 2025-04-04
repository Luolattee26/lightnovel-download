<h1 align="center">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;文库吧/轻小说文库 EPUB下载器
</h1>





[文库吧/轻小说文库](www.wenku8.net)(wenku8)网站小说下载，EPUB打包。

原项目地址：https://github.com/ShqWW/lightnovel-download


## 使用前安装需要的包
```
pip install -r requirements.txt -i https://pypi.org/simple/
```
## 使用命令行模式运行(无需安装图形界面库，支持Linux):
```
python lightnovel.py
```

## 参数介绍
* `-h, --help`：显示帮助信息
* `-b, --book_no`：需要下载小说在文库吧的编号
* `-v, --volume_no`：需要下载的卷号，支持范围（如1-3）或者使用逗号分隔的列表（如1,2,3）
* `-s, --no_input`：无交互式模式，直接下载，需要在命令行中提供`-b`和`-v`参数，默认是交互式模式
* `-o, --output`：输出目录，默认是当前系统的下载目录




## EPUB书籍编辑和管理工具推荐：
1. [Sigil](https://sigil-ebook.com/) 
2. [Calibre](https://www.calibre-ebook.com/)

