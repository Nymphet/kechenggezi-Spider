# kechenggezi-Spider
第一次写爬虫，爬课程格子的校花榜，比较简陋，没用多线程。

---

## 使用说明

修改主程序里的token和图片保存位置，运行

    python xhspider.py

保存的list.txt是代表编号，名字，票数。

本来是用名字作为图片的名字，但存在重名和一些细节上的bug，所以换成了这种形式。

本程序仅供学习参考，请勿做违法的事情> <.也希望大家提出宝贵的意见让我改进。

以上。。。

以下功能需要 scrapy

爬取所有妹子的详细信息（多线程），保存文件为 jsonline 格式

    scrapy crawl KcgzXh
    
下载所有妹子的图片（多线程）

    mkdir images
    scrapy crawl XhImage
