# url-scheme-collection
![platform](https://img.shields.io/badge/platform-iOS-blue)
![collection](https://img.shields.io/badge/collection-URL%20Scheme-orange)

不同应用场景下的 iOS URL Scheme 信息获取，**将持续更新！**

### 扫一扫
| 应用 | URL Scheme |
| :----:| :---- |
| 微信 | weixin://scanqrcode
| 支付宝 | alipays://platformapi/startapp?saId=10000007
| QQ | mqqapi://qrcode/scan_qrcode?version=1&src_type=app
| Tim | tim://qrcode/scan_qrcode?version=1&src_type=app
| 美团 | imeituan://www.meituan.com/scanQRCode?openAR=1
| 滴滴青桔 | blackhorse://qrscan
| 飞书 | feishu://applink.feishu.cn/client/qrcode/main?
| 京东 | openapp.jdmobile://virtual?params={"category":"jump","des":"saoasao"}
| 钉钉 | dingtalk://dingtalkclient/page/scan
| 淘宝 | taobao://tb.cn/n/scancode
| 知乎 | zhihu://codereader
| bilibili | bilibili://qrcode
| 微博 | sinaweibo://qrcode
| 微博极速版 | weibolite://qrcode
| 微博国际版 | weibointernational://qrcode
| 快手 | kwai://qrscan
| 快手极速版 | ksnebula://qrscan
| 饿了么 | eleme://code_scanner
| 多点 | scanDesktop://
| 爱奇艺 | iqiyi://mobile/scan
| 58同城 | wbmain://jump/core/capture
| 115 | oof.disk://scan
| Line | https://line.me/R/nv/QRCodeReader
| Facebook | fb://qrcode

<br>

### 用户主页
| 应用 | URL Scheme |
| :----:| :---- |
| 抖音 | snssdk1128://user/profile/{uid}
| 抖音极速版 | snssdk2329://user/profile/{uid}
| 抖音火山版 | snssdk1112://profile?id={uid}
| 抖音国际版 | snssdk1233://user/profile/{uid}
| 今日头条 | snssdk141://profile?uid={uid}
| 快手 | kwai://profile/{uid}
| 快手极速版 | ksnebula://profile/{uid}
| QQ | mqqapi://card/show_pslcard?src_type=internal&version=1&uin={uid}
| 小红书 | xhsdiscover://user/{uid}
| bilibili | bilibili://space/{uid}
| 钉钉 | dingtalk://dingtalkclient/page/link?url=https://h5.dingtalk.com/zproject/profile.html?profile={uid}
| 微博 | sinaweibo://userinfo?uid={uid}
| 微视 | weishi://profile?person_id={uid}
| 网易云音乐 | orpheus://nm/user/home?id={uid}
| 唱吧 | changba://?ac=personalpage&userid={uid}
| 全民k歌 | qmkege://kege.com?action=profile&uid={uid}
| 绿洲 | oasis://user?uid={uid}
| Linkedin | linkedin://profile/{uid}
| Instagram | instagram://user?username={uid}
| Facebook | fb://profile/{uid}
| Twitter | twitter://user?screen_name={uid}
| Pinterest | pinterest://user/{uid}

<br>

### 应用内搜索
| 应用 | URL Scheme |
| :----:| :---- |
| 美团 | imeituan://www.meituan.com/search?q={query}
| 美团外卖 | meituanwaimai://waimai.meituan.com/search?query={query}
| 大众点评 | dianping://searchshoplist?keyword={query}
| 淘宝 | taobao://s.taobao.com?q={query}
| 天猫 | tmall://page.tm/search?q={query}
| 京东 | openapp.jdmobile://virtual?params={"des":"productList","keyWord":"{query}","from":"search","category":"jump"}
| 拼多多 | pinduoduo://yangkeduo.com/search_result.html?search_key={query}
| 小红书 | xhsdiscover://search/result?keyword={query}
| 快手 | kwai://search?keyword={query}
| 快手极速版 | ksnebula://search?keyword={query}
| 微博 | sinaweibo://searchall?q={query}
| 微博极速版 | weibolite://searchall?q={query}
| 微博国际版 | weibointernational://searchall?q={query}
| bilibili | bilibili://search?keyword={query}
| 知乎 | zhihu://search?q={query}
| 豆瓣 | douban:///search?q={query}
| 欧陆词典 | eudic://dict/{query}
| 什么值得买 | smzdm://search?json={"channelName":"home","search_type":"1","keyWord":"{query}"}
| Safari | x-web-search://?{query}
| Twitter | twitter://search?query={query} 
| Instagram | instagram://tag?name={query}
| Youtube | youtube://results?search_query={query}

<br>

### 网址搜索
| 应用 | URL Scheme |
| :----:| :---- |
| Safari | x-web-search://?{url}
| 百度浏览器 | baiduboxapp://browse?url={url}
| UC浏览器 | ucbrowser://{url}
| QQ浏览器 | mqqbrowser://url={url}
| Firefox | firefox://open-url?url={url}
| Google Chrome | googlechrome://{url}
| 抖音(WebView) | snssdk1128://webview?url={url}&from=webview&refer=web
| 快手(WebView) | kwai://webview?url={url}

<br>

### 内容搜索 (作品/直播/新闻/贴文)
| 应用 | 业务 | URL Scheme |
| :----:| :----: | :---- |
| 抖音 | 作品 | snssdk1128://aweme/detail/{itemId}
| 抖音 | 直播 | snssdk1128://aweme/live/{roomId}
| 西瓜视频 | 作品 | snssdk32://detail?groupid={itemId}
| 西瓜视频 | 直播 | snssdk32://xigua_live?room_id={roomId}
| 抖音火山版 | 作品 | snssdk1112://item?id={itemId}
| 皮皮虾 | 作品 | bds://cell_detail?item_id={itemId}
| 快手 | 作品 | kwai://work/{itemId}
| 快手 | 直播 | kwai://live/play/{roomId}
| 快手 | 游戏 | kwai://gamezone/game/{gameId}
| 微视 | 作品 | weishi://feed?feed_id={itemId}
| 网易新闻 | 新闻 | newsapp://doc/{postId}
| 知乎 | 问题 | zhihu://question/{qid}

<br>

### 台灣的朋友看這裡
| 應用 | 業務 | URL Scheme |
| :----:| :----: | :---- |
| Line | 付款碼 | line://pay/generateQR
| Line | 付款碼 ( Line Pay Money) | line://pay/generateQR?from=SC&menuOrigin=IPASS
| Line | 二維碼名片 | line://nv/QRCode
| Line | 掃一掃 | https://line.me/R/nv/QRCodeReader
| 台灣Pay | 掃一掃 | twmpshortcut://?type=payment
| 台灣Pay | 付款碼 | twmpshortcut://?type=scan
| 悠遊付 | 付款碼 | tw.com.easycard.easycardwallet://paymentCode
| OpenPoint | 付款碼 | openpointapp://gofeature?featureId=OPWAAB24
| FamilyMart | 付款碼 | familymart://action.go/pay/barcode

