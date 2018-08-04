# 拼多多爬虫


## description:

爬取拼多多某个一级分类下的商品信息:

![](https://ws2.sinaimg.cn/large/006tKfTcgy1ftxuhpq3zoj315o0e07nz.jpg)


- 多代理



---

## Usage:

![](https://ws2.sinaimg.cn/large/006tKfTcgy1ftxu5yfvbpj30zm0k61fj.jpg)

opt_id : 一级分类商品的id

```
python firstcat_spider.py {opt_id}
```

start to crawl all goods info with this opt_id

---

## To-do-list:


* [x] 爬取分类信息(一级-二级)
* [x] MongoDB入库
    * [x] 入分类信息
* [x] 爬取某一级分类下的所有商品信息
    * [x] 入库-入商品信息
    * [x] 入库-入offset_num信息

---



## log:


- 2018.8.4 18:16:
 - offsetnum：1944
 - goods num:4312


