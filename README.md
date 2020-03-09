# JD_comment_spider
 京东商品评论爬虫


### jdspider.py
    实现代码部分，用request爬的，没有代理，当时爬的时候没有任何问题。轻松获取评论信息。
    大体思路：首先通过JD搜索页面获得相关商品的ID，然后通过ID获得特定商品的网址和header里面相应的数据。
             再通过getdata（）获得评价信息。
    商品评论分为差评（1）、中评（2）、好评（3）。分别保存在不同的文件里。
    详细说明在代码注释里。
    
### 数据保存
   分隔符\t。
   数据名为  商品类别_评价类型.csv    (其实应该是tsv，懒得改了）
