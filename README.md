# Magic feed/魔法分享

[English](https://github.com/ShinChven/ShareMoments/blob/master/README.md#a-tool-for-you-to-master-your-web-contents)

[中文](https://github.com/ShinChven/ShareMoments/blob/master/README.md#%E9%AD%94%E6%B3%95%E5%88%86%E4%BA%AB---web%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB%E5%8A%A9%E6%89%8B)

## New updates

### ver.1.8.0

- UI:
  - New drawer navigation menu;
  - New translucent style full screen feed list;
  - 新增抽屉导航；
  - 沉浸式的feed列表；
- Name:
  - Renamed to Magic Feed;

### ver.1.7.0:

- Gallery:
  - Gallery is out, now you can browse all images you downloaded within gallery. All files are in your `picture/ShareMoments/` directory.
  - If you found some image you downloaded previewsly can not be loaded, please remove them in other file manager due to a file name bug. `?` are not allowed in filename, and I made a mistake that I did not replace them in early versions.
  - 新增内置图片浏览器，现在大家可以从app里面直接查看下载过的图片。这些图片都存在了`picture/ShareMoments/` 文件夹中。
  - 如果发现有图片显示不出来，那是由于写了一个bug，没有把`?`号替换掉而直接写到文件名里面。图片文件路径不支持`?`号，因此请从其他的文件管理器中将它们重命名或者删除掉。
- Tweet Video url:
  - Now you can see tweet video url in media file list.
  - In case you don't know how to use it, please share a tweet with video's link to WebMaster, click image in dialog to enter image list, then click button on right top to enter `media file list`. Then video file links will show up.
  - Please use with care, only download media file when you are allowed by its owner.
  - 现在可以在媒体文件列表中获取twitter的视频链接，请在下载媒体文件时，不要侵犯他人隐私和版权。
  - 如果你还不知道怎么使用魔法分享的`媒体文件列表`功能，请先分享一个链接到`魔法分享`，在弹出的对话窗口中点击图片进入图片列表，再点击右上角的按钮进入`媒体文件列表`，在这里你可以浏览该网页上的图片和视频链接。现在兼容情况还不清楚，请不要尝试一些奇奇怪怪的网站。🐶


# A tool for you to master your web contents

Most contents we enjoy and share each day on internet and mobile are hosted on the web, and they are made up of text and media files. I developed this app so that we can dig a little bit deeper into the web html and make the most use of them.

## Quick guide: master your web content in 5 steps

1. Share/send url from any app or brower to Magic Feed.
2. Magic Feed will parse title, description, image url and video url from html for you.
3. Click image in Magic Feed's dialog to view all media files the app has found for you.
4. Download or share media files by simple selection.
5. Revisit your feed in app later.

## Share a link like a pro

We share links every day, but raw URLs are sometimes hard for people to understand. So normally we'll have to type in some description so that our receivers can understand the URL at first sight without open it.
If you know something about the html, then you'll probably know such things like title, description, cover image and etc. are all there for you to reach.
To help you master the web,  Magic Feed can parse the title, description and pictures from a web link. And you can get a copy of well composed message to share a link by 1 single tap from the app.

## Save your feed across apps

Each app has its own bookmarks, but why can't we just save everything together and search everything we saved in one place?
Save your URLs in Magic Feed and make a feed list for yourself. When you need them again, just go back to Magic Feed and find them.

## Grab images from web

- Image download: If you are interested in some images from a web page, Magic Feed can do batch download and batch forward for you.
- Reverse Image Search: If you are interested in some particular images from one web,  Magic Feed can send it to Google for you to do `search image by image`.

## Download Tweet and Instagram video

- Magic Feed always takes a deep look into html, you can download videos from a tweet or Instagram url.
- Many other sites are supported by it's default extraction rule.

## Respect content owner's copyright and privacy

✘ You should NOT download or forward any copyrighted image or video from the open internet unless you are allowed by it's owner.
✘ YouTube is NOT supported.

## Share a link via QRCode

Don't bother if you want share a link without adding someone to your contacts. Just show the QR Code.

## 魔法分享 - Web内容分享助手

在我们每天都使用的App和网站中有很多精彩的内容，它们大部分都承载在🌐Web中。很多时候，我们如果只是单单分享一个🔗Web链接，还需要花很长时间向别人说明我们在分享什么内容。于是我制作了这个App，让你能轻松地从Web Link中获取标题、描述和图片，以分享给朋友。

## 特色功能

- 💬 微信链接卡片：如果你是微信的用户，它能帮你生成一个优雅的分享卡片，让你分享的链接能马上抓住别人的眼球；
- 🖼️ 批量图片分享：如果你喜欢Web中的图片，你可以批量分享给你的朋友，当然你也可以批量下载它们；
- 🔍 图片逆向搜索：如果你喜欢Web中的一张图片，你还可以以图搜索，做逆向图片查找（由Google提供）；
- ⭐ 智能链接收藏夹：你所分享过的链接会存在你的手机中，你随时可以重新浏览、查找和分享；

## Web内容解析规则

- 优先读取Web页面中的OpenGraph标识以获取标题、介绍和封面图片；
- 再在页面查找图片；
- 针对Twitter、Instagram、Deviant、Bilibili这些热门的站点，编写了专门的解析方案，让你能更准确地的获取相关内容；

## 下载

- [Google Play Store](https://play.google.com/store/apps/details?id=net.atlassc.shinchven.sharemoments)（推荐，可加入beta频道，抢先试用新功能）
- [酷安](https://www.coolapk.com/apk/net.atlassc.shinchven.sharemoments)

## 联系我

- Twitter [@ShinChven](https://twitter.com/ShinChven)可以找到我；

## 内容声明

- 本应用不提供任何内容，仅为用户提供链接分享、收藏和网页内容感知功能，不对用户操作的内容负责。
- 所有用户在使用本应用分享网页链接时，应当遵守当地法律法规，不得散布危害社会安定和国家统一的言论。

## Privacy Policy

### camera

- This app uses camera to scan QR CODE.
- 此应用需要使用摄像头来扫描二维码。

### storage

- This app uses internal storage to cache and download images.
- 此应用使用设备内部存储空间来下载或缓存图片。

### analytics

- This app will anonymously report user's usage actions to let developer know how and how many times users are using its function. user's personal information and content will not be recorded.
- App 会使用Firebase Analytics 匿名记录用户的操作习惯，以帮助开发者更好的了解用户是否使用或者了解App里面的各种功能以及使用频率，但不会上传任何用户的个人信息和用户访问过的内容（链接、图片等）。


## OPEN SOURCE LICENSE

[OPEN SOURCE CREDITS](OpenSourceCredits.md)

## 恰饭

https://github.com/ShinChven/donation
