# Awesome rules of URL Auto Redirector

![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
![](https://img.shields.io/badge/license-MIT-blue.svg)

## What's URL Auto Redirector

[URL Auto Redirector](https://urlautoredirector.github.io) is a chrome extension that enables you to skip certain pages, mostly useless referral/ad pages, in order to make browsing quicker and simpler.

[Download and install URL Auto Redirector](https://github.com/UrlAutoRedirector/UrlAutoRedirector/wiki/Installation).

## Preset Rules

| Name | Source | Destination | RegExp |
|------|--------|-------------|--------|
| 京东中间页 | `^http://re.jd.com/cps/item/([0-9]*).html` | `http://item.jd.com/$1.html` | :heavy_check_mark: |
| 点评移动页 | `^http://m.dianping.com/appshare/shop/([0-9]*)$` | `http://www.dianping.com/shop/$1` | :heavy_check_mark: |
| 微博个人页 | `^http://m.weibo.cn/([0-9]+)$` | `http://weibo.com/$1` | :heavy_check_mark: |
| 腾讯新闻体育 | `^http://xw.qq.com/sports/(\d{8})(\d{6})/(.*)$` | `http://sports.qq.com/a/$1/$2.htm` | :heavy_check_mark: |
| 汽车之间说客 | `^http://m.autohome.com.cn/shuoke/(.*).html` | `http://shuoke.autohome.com.cn/article/$1.html` | :heavy_check_mark: |
| 自如 | `^http://m.ziroom.com/BJ/room/(.*).html` | `http://www.ziroom.com/z/vr/$1.html` | :heavy_check_mark: |
| CSDN 文章 | `^http://m.csdn.net/article/(.*)$` | `http://www.csdn.net/article/$1` | :heavy_check_mark: |
| 空翼网 | `^http://m.afwing.com/(.*)$` | `http://www.afwing.com/$1` | :heavy_check_mark: |

## Contributed Rules

* None

## Contribution

* If you have useful rules in getting convenience by URL Auto Redictor, comment in the [Collection of awesome rules](https://github.com/UrlAutoRedirector/UrlAutoRedirector/issues/17).
* PR(Pull Request) is welcomed.
