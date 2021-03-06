# wp-plugin-sinapicv2
官方主页 http://inn-studio.com/sinapicv2

> 一款最好用的 WordPress 微博图床插件。上传到插入图片只需 3 步即完成，其高效的操作和可靠的表现，想必您会喜欢，这就是“屌图床V2”—— WP 最屌图床，没有之一。

![logo截图](https://ww1.sinaimg.cn/large/686ee05djw1eo5djzez4mj20ob0590ta.jpg)

![主界面截图](https://ww1.sinaimg.cn/thumb150/686ee05djw1eo5dk290s8j20o20aotb8.jpg)

#使用说明
* 上传图片前，请使用您的新浪微博授权插件，再刷新插件界面即可使用。
* 上传图片前，请按照自己的需求，在微博帐号设置是否选用水印，推荐不选用。
* 上传的图片，是上传到您授权帐号里面，请留意。
* 如需更换帐号重新授权，请推出登录微博帐号，再在插件设置页面点击“授权链接”，登录相应帐号授权即可。
* 在使用V2版之前，请禁用或卸装V1版，否则会导致上传界面冲突而无法正常使用。
* 本插件不支持IE678，请使用Firefox、Chrome、IE10+等支持HTML5的浏览器进行使用。
* 本插件支持平板或手机使用。

# 图片大小是怎样的规格？
在上传后的图片分别拥有以下几种格式供选择使用：
* thumb150 格式：将原始图片不论大小，有截取地缩放为宽高均为 150像素 的小型图片（不保持纵横比），特别适合大部分主题的缩略特色图。
* mw600 格式：如果原始图片宽度超过 600像素，则将其缩小为宽度为 600像素 的中型图片（保持纵横比），适合大部分主题的正文内容。
* large 格式：原始图片规格，不进行处理。
* square 格式：将原始图片尽可能无截取地缩放为宽高均为 80像素 的超小型图片（保持纵横比），适合部分主题的缩略特色图。
* thumbnail 格式：将原始图片尽可能无截取地缩放为宽高均为 120像素 的小型图片（保持纵横比），特别适合大部分主题的缩略特色图。
* bmiddle 格式：如果原始图片宽高其中一边超过 400像素，则将其最长边缩小为 400像素 的中型图片（保持纵横比），适合大部分主题的正文内容。

# 备份与还原
数据的备份和还原功能，属于风险性功能。虽然该功能经过数万（baǐ）次测试，但若操作不当，也有可能出现无法预料的问题。以下列出必须注意的事项：
* 在进行任何还原操作前，请必须进行一次备份，否则将无法正确匹配最新日志的数据。
* 在进行互转还原前，建议先备份 SQL 日志内容，防止还原过程中出现意外情况（如断水断网断电服务器宕机等）导致的资料丢失。
* 请再次阅读上述事项一次。

# ChangeLog
2015-01-10 2.0.1

* 修正无法批量插入不带链接的图片问题
* 修正无法正确保存自定义特色图字段名称问题
* 即将更新作为文章特色图功能

2015-01-09 2.0.0 王者归来版
* 重构插件界面和代码
* 全新的备份策略
* 全新的微博服务器与我的空间图片互转恢复功能
* 全新的上传体验
* 新增 SSL 图片地址选项
* 新增图片 title 属性选项
* 修正部分错别字
* 即将更新作为文章特色图功能
