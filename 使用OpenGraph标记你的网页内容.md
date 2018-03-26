# 如何让【魔法分享】app能更好的抓取你网页上的内容

【魔法分享】app会优先对网页上的[OpenGraph](http://ogp.me/)标记进行抓取，然后再抓取全文内容。目前主要抓取了以下标记：

```html
<html>
<head>
<!--OpenGraph Tags-->
<meta property="og:title" content="标题" />
<meta property="og:description" content="描述" />
<meta property="og:image" content="完整图片地址1.jpg" />
<meta property="og:image" content="完整图片地址2.jpg" />
<!--End of OpenGraph Tags-->
</head>
</html>

```
# 如果你的网站使用JavaScript填充内容

- 由于【魔法分享】app仅仅只是get一下你网站的html，如果你的网站内容是通过JavaScript加载上来的，目前暂时没有办法可以获取；
- 【魔法分享】app稍后会在get你网站的时候带上share-moment的user-agent标识，你可以在获得到这个标志的时候返回包含OpenGraph标签的html数据；

