# Awesome Rules for URL Auto Redirector

![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)

## What's URL Auto Redirector?

[URL Auto Redirector](https://urlautoredirector.github.io) is a Chrome Extension that uses for redirecting URLs automatically with Regular Expression presets. It enables you to skip referral/AD pages and adapt mobile pages gracefully, which is time-saving, helps to be more productive and improves web browsing experiences.

[Get URL Auto Redirector](https://urlautoredirector.github.io/docs.html#installation).

## Preset Rules

| Name | Source | Destination |
|------|--------|-------------|
| 京东中间页 | `^https?://re.jd.com/cps/item/([0-9]*).html` | `https://item.jd.com/$1.html` |
| 点评移动页 | `^http://m.dianping.com/appshare/shop/([0-9]*)$` | `http://www.dianping.com/shop/$1` |
| 微博个人页 | `^http://m.weibo.cn/([0-9]+)$` | `http://weibo.com/$1` |
| 腾讯新闻体育 | `^http://xw.qq.com/sports/(\d{8})(\d{6})/(.*)$` | `http://sports.qq.com/a/$1/$2.htm` |
| 汽车之间说客 | `^http://m.autohome.com.cn/shuoke/(.*).html` | `http://shuoke.autohome.com.cn/article/$1.html` |
| 自如 | `^http://m.ziroom.com/BJ/room/(.*).html` | `http://www.ziroom.com/z/vr/$1.html` |
| CSDN 文章 | `^http://m.csdn.net/article/(.*)$` | `http://www.csdn.net/article/$1` |
| 空翼网 | `^http://m.afwing.com/(.*)$` | `http://www.afwing.com/$1` |
| 京东 | `^https?://item.m.jd.com/product/(.*).html` | `http://item.jd.com/$1.html` |
| 京东全球购 | `^https?://mitem.jd.hk/ware/view.action\\?wareId=(\\d+)(&.*)` | `https://item.jd.hk/$2.html` |
| 豆瓣日记 | `^https://m.douban.com/note/(.*)/` | `https://www.douban.com/note/$1/` |
| 饿了么 | `^https://h5.ele.me/shop/#id=(\\d+)` | `https://www.ele.me/shop/$1` |
| 糯米电影 | `^https://mdianying.baidu.com/movie/detail\\?movieId=(\\d+)` | `https://www.nuomi.com/film/$1` |
| 哔哩哔哩 | `^http://www.bilibili.com/mobile/video/(av\\d+).html` | `http://www.bilibili.com/video/$1/` |
| AcFun | `^http://m.acfun.tv/v/\\?ac=(\\d+)` | `http://www.acfun.tv/v/ac$1` |
| 淘宝 | `^https?://h5.m.taobao.com/awp/core/detail.htm\\?id=(\\d+)` | `https://item.taobao.com/item.htm?id=$1` |
| 起点 | `^http://m.qidian.com/book/showbook.aspx\\?bookid=(\\d+)` | `http://book.qidian.com/info/$1` |
| 音悦台 | `^http://m.yinyuetai.com/video/(.*)` | `http://v.yinyuetai.com/video/$1` |
| 链家北京 | `^https?://m.lianjia.com/bj/ershoufang/(\\d+).html` | `http://bj.lianjia.com/ershoufang/$1.html` |
| 链家上海 | `^https?://m.sh.lianjia.com/ershoufang/(.*)` | `http://sh.lianjia.com/ershoufang/$1` |
| 网易严选 | `^https?://m.you.163.com/item/detail\\?id=(.*)` | `http://you.163.com/item/detail?id=$1` |
| 澎湃新闻 | `^https?://m.thepaper.cn/(.*)` | `http://www.thepaper.cn/$1` |
| 直播吧新闻 | `^https?://m.zhibo8.cc/news/web/zuqiu/(.*)` | `https://news.zhibo8.cc/zuqiu/$1` |

## Contributed Rules

* None

## Contribution

* If you have useful rules in getting convenience by URL Auto Redictor, comment in the [Collection of awesome rules](https://github.com/UrlAutoRedirector/UrlAutoRedirector/issues/17).
* PR(Pull Request) is welcomed.
