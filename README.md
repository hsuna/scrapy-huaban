# 爬虫-花瓣网

> 最近由于花瓣网关了，有好友问起能不能帮他把他的图片下载下来，所以写了个爬虫。

```
./root
├── huaban                 // scrapy项目
│   ├── spiders            
│   ├── items.py           
│   ├── middlewares.py     
│   ├── pipelines.py       
│   └── settings.py        
├── crawl.py               // pyinstall打包入口
├── crawl.spec             // 打包spec文件
└── scrapy.cfg             // scrapy配置
```

**注：**

登录账号后，可能会提示需要验证的情况，这里需要自个登入[http://login.meiwu.co/login](http://login.meiwu.co/login)进行验证，验证完毕后，重新执行程序。


[使用pyinstaller打包scrapy](http://blog.hsuna.com/article.html?id=5c4d53c7e39bc1780deeb49f)