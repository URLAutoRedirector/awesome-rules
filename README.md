# Awesome rules of UrlAutoRedirector

## Preset Rules

| Name | Source | Destination | RegExp |
|------|--------|-------------|--------|
| 京东中间页跳过 | ^http://re.jd.com/cps/item/([0-9]*).html | http://item.jd.com/$1.html | - [x] |
| 点评无线转PC | ^http://m.dianping.com/appshare/shop/([0-9]*)$ | http://www.dianping.com/shop/$1 | - [x] |
| 微博无线转PC | ^http://m.weibo.cn/(.*)$ | http://weibo.com/$1 | - [x] |
| BaiduToGoogle | https://www.baidu.com/ | https://www.google.com/ | - [] |

## Contribution

* If you have useful rules in getting convenience by URL Auto Redictor, comment in the [Collection of awesome rules](https://github.com/crispgm/UrlAutoRedirector/issues/17).
* PR(Pull Request) is welcomed.
