# GuShiWen
Scrapy练习项目，利用Scrapy抓取古诗（唐诗三百首，宋词三百首等），并保存为json格式（不断完善ing）
## 采用的技术
- Scrapy爬取网站的基本技术
- xpath提取网页中的内容
- dict list str 的相关操作
- re配合xpath提取网页（解决文字图片问题）
- requests提取网页源码（解决Scrapy yield request异步访问诗的标题和内容不对应的问题）
- HtmlResponse 转换源码为Scrapy响应对象，从而可以利用Selector

##遇到的问题
> 转换成json数据的时候多了很多无用的空格
