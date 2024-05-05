


# Litiaotiao-Backup-MyRule
李跳跳app和自用规则备份

关于李跳跳被腾讯发函[作者停更](https://mp.weixin.qq.com/s/ha6hHr40umlj-ExHdGFXXw)。这是李跳跳“派大星2.2”版本备份，再加上本人目前正在用的一些规则。

本次分享的apk的MD5码：
``
EE2F4E1E7D92EB29A8B36267D7A7C79D
``
作者给出的md5码：[报毒解除公告，望周知](https://mp.weixin.qq.com/s/u5BI-7DIhxirFIPDulf6lA)
## 规则文件（直接复制然后粘贴导入）
```
[{"-1031558479":"{\"popup_rules\":[{\"id\":\"升级完整版\",\"action\":\"ace\"}]}"},{"740556751":"{\"popup_rules\":[{\"id\":\"新版\",\"action\":\"update_close\"},{\"id\":\"开启悬浮窗\",\"action\":\"siv_close\"}]}"},{"-1243492292":"{\"popup_rules\":[{\"id\":\"获取验证码&&登录\",\"action\":\"×\"},{\"id\":\"阅读全文&&APP\",\"action\":\"继续\"}],\"unite_popup_rules\":true}"},{"is_main_switch_on":true},{"-1565570240":"{\"popup_rules\":[{\"id\":\"exit_btn_exit\",\"action\":\"exit_btn_exit\"},{\"id\":\"提示\",\"action\":\"142,1750,723,1918\"}],\"ltt_service\":true,\"click_way\":1}"},{"-973170826":"{\"popup_rules\":[{\"id\":\"hq\",\"action\":\"hq\"},{\"id\":\"jph\",\"action\":\"jph\"},{\"id\":\"不感兴趣原因\",\"action\":\"关闭\"},{\"id\":\"jpa\",\"action\":\"jpa\"},{\"id\":\"container\",\"action\":\"feedbackIcon\"},{\"id\":\"-不感兴趣\",\"action\":\"不感兴趣\"},{\"id\":\"+与我无关\",\"action\":\"与我无关\"},{\"id\":\"+登录&-微信\",\"action\":\"=登录\"}],\"rid\":[\"w0x1\"]}"},{"-1050713937":"{\"ltt_service\":true,\"popup_rules\":[{\"id\":\"发现新版本\",\"action\":\"以后再说\"}]}"},{"-189732215":"{\"popup_rules\":[{\"id\":\"image_close_banner\",\"action\":\"image_close_banner\"}]}"},{"2049668591":"{\"popup_rules\":[{\"id\":\"48,1759,1392,2081\",\"action\":\"1264,1791,1360,1855\"},{\"id\":\"944,1559,1400,1759\",\"action\":\"944,1559,1400,1759\"}]}"},{"fs_message":false},{"foreground_service":true},{"361910168":"{\"popup_rules\":[{\"id\":\"ik1\",\"action\":\"ik1\"},{\"id\":\"关闭此条广告\",\"action\":\"关闭此条广告\"},{\"id\":\"发现QQ版本更新\",\"action\":\"iyx\"},{\"id\":\"广告×\",\"action\":\"广告×\"},{\"id\":\"+登录&-QQ\",\"action\":\"=登录\"}],\"rid\":[\"q0q1\"]}"},{"1994036591":"{\"popup_rules\":[{\"id\":\"屏蔽推广\",\"action\":\"reason1_layout\"},{\"id\":\"屏蔽广告\",\"action\":\"reason1_layout\"},{\"id\":\"upper_ad_container\",\"action\":\"1292,1013,1370,1091\"},null,{\"id\":\"1300,982,1440,1122\",\"action\":\"1300,982,1440,1122\"},{\"id\":\"ad_mark\",\"action\":\"1300,982,1440,1122\"}]}"},{"exclude_from_recents":true},{"toast_text":"已跳过"},{"847156324":"{\"popup_rules\":[{\"id\":\"ad_text_view\",\"action\":\"close_view\"},{\"id\":\"关闭广告\",\"action\":\"不感兴趣\"},{\"id\":\"举报广告\",\"action\":\"不感兴趣\"}],\"ltt_service\":true}"},{"-1709882794":"{\"popup_rules\":[{\"id\":\"1353,2322,1440,2409\",\"action\":\"1353,2322,1440,2409\"}]}"},{"-1896393714":"{\"popup_rules\":[{\"id\":\"发现新版本\",\"action\":\"取消\"}]}"},{"1735523026":"{\"popup_rules\":[{\"id\":\"exit_btn_exit\",\"action\":\"100,1950,719,2140\"}]}"},{"-905066364":"{\"popup_rules\":[{\"id\":\"是否升级\",\"action\":\"下次\"}]}"},{"ltt_suggestions_a":false},{"-1898417322":"{\"popup_rules\":[{\"id\":\"广告\",\"action\":\"closeGray\"}]}"},{"762493631":"{\"popup_rules\":[{\"id\":\"+发现新版本\",\"action\":\"残忍拒绝\"}]}"},{"386107370":"{\"popup_rules\":[{\"id\":\"版本更新\",\"action\":\"取消\"}]}"},{"1087086724":"{\"popup_rules\":[{\"id\":\"+发现\",\"action\":\"288,2365,711,2519\"}]}"},{"hide_toast":true},{"1745698237":"{\"keywords\":[\"关闭\"]}"}]
```
>小红书（精简版），不同版本规则不同。如果不行，可尝试将小红书规则中的"ace"改为"a8w"
>
规则更新日期：2024年3月26日   
包含：微信自动点击公众号的广告，酷安app，小米社区...（编辑了好多，忘了...😢）

由于李跳跳停更，某些app正通过“高明”的手段，突破“封锁”。从而使李跳跳规则失效[视频链接](https://www.bilibili.com/video/BV1zH4y1U7jG "链接到bilibili视频")。我也会将app规则进行整理并附上app版本

|app名称|app包名|版本|是否可用|规则|
|:----:|:---:|:---:|:---:|:---:|
|菜鸟|com.cainiao.wireless|8.7.110|✔|`{"popup_rules":[{"id":"draw_dialog_tv_submit","action":"GLOBAL_ACTION_BACK"}]}`||
|大学搜题酱|com.zmzx.college.search|2.0.0|✔|`{"popup_rules":[{"id":"新版","action":"update_close"},{"id":"开启悬浮窗","action":"siv_close"}]}`|
|到梦空间|com.jingcai.apps.qualitydev|4.5.1|✔|`{"popup_rules":[{"id":"版本更新","action":"取消"}]}`|
|海狸洗衣|com.haier.uhome.washer|3.23.1|✔|`{"popup_rules":[{"id":"+发现","action":"288,2365,711,2519"}]}`|
|酷安|com.coolapk.market|13.2.1|❌|`{"popup_rules":[{"id":"ad_text_view","action":"close_view"},{"id":"关闭广告","action":"不感兴趣"},{"id":"举报广告","action":"不感兴趣"}],"ltt_service":true}`|
|小米浏览器|com.android.browser|17.3.5|未知|`{"popup_rules":[{"id":"获取验证码&&登录","action":"×"},{"id":"阅读全文&&APP","action":"继续"}],"unite_popup_rules":true}`|
|美团|com.sankuai.meituan|12.8.204|✔|`{"popup_rules":[{"id":"1353,2322,1440,2409","action":"1353,2322,1440,2409"}]}`|
|万能遥控|com.duokan.phone.remotecontroller|6.5.3M|✔|`{"popup_rules":[{"id":"image_close_banner","action":"image_close_banner"}]}`|
|万题斩|com.aibear.tiku|1.2.12|✔|`{"popup_rules":[{"id":"是否升级","action":"下次"}]}`|
|微信|com.tencent.mm|8.0.21|✔|`{"popup_rules":[{"id":"hq","action":"hq"},{"id":"jph","action":"jph"},{"id":"不感兴趣原因","action":"关闭"},{"id":"jpa","action":"jpa"},{"id":"container","action":"feedbackIcon"},{"id":"-不感兴趣","action":"不感兴趣"},{"id":"+与我无关","action":"与我无关"},{"id":"+登录&-微信","action":"=登录"}],"rid":["w0x1"]}`|
|下载管理|com.android.providers.downloads.ui|122.11.24.800001|✔|`{"ltt_service":true,"popup_rules":[{"id":"发现新版本","action":"以后再说"}]}`|
|小红书|com.xingin.xhs|7.96.0.5|✔|`{"popup_rules":[{"id":"升级完整版","action":"ace"}]}`|
|小米穿戴|com.xiaomi.wearable|2.16.1|✔|`{"popup_rules":[{"id":"+发现新版本","action":"残忍拒绝"}]}`|
|小米社区|com.xiaomi.vipaccount|4.6.0|✔|`{"popup_rules":[{"id":"广告","action":"closeGray"}]}`|
|游戏服务|com.xiaomi.gamecenter.sdk.service|8.5.1|✔|`{"popup_rules":[{"id":"exit_btn_exit","action":"exit_btn_exit"},{"id":"提示","action":"142,1750,723,1918"}],"ltt_service":true,"click_way":1}`|
|支付宝|com.eg.android.AlipayGphone|10.5.26.8700|✔|`{"popup_rules":[{"id":"48,1759,1392,2081","action":"1264,1791,1360,1855"},{"id":"944,1559,1400,1759","action":"944,1559,1400,1759"}]}`|
|QQ|com.tencent.mobileqq|8.9.20|✔|`{"popup_rules":[{"id":"ik1","action":"ik1"},{"id":"关闭此条广告","action":"关闭此条广告"},{"id":"发现QQ版本更新","action":"iyx"},{"id":"广告×","action":"广告×"},{"id":"+登录&-QQ","action":"=登录"}],"rid":["q0q1"]}`|




## Star History
[![Star History Chart](https://api.star-history.com/svg?repos=FreezingArts/Litiaotiao-Backup-MyRule&type=Date)](https://star-history.com/#FreezingArts/Litiaotiao-Backup-MyRule&Date)
---
>声明：本仓库仅用于备份李跳跳软件，不参与任何商业行为，仅供学习交流使用，如有侵权，请联系本人删除。
