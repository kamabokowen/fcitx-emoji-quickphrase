# 写在前面
本项目旨在可以让fcitx输入法更快速且符合中国人直觉地输入emoji表情。项目主要是利用快速输入功能。

This project aims to make fcitx input emoji more quickly and intuitively for Chinese people. 
This project uses pinyin as the keyword of emoji.

项目兼容桌面端的fcitx5输入法以及安卓端的fcitx5-android.

Special thanks for this repository / 特别感谢该项目：[fcitx5-android](https://github.com/fcitx5-android/fcitx5-android)

Inspired by this repository / 灵感源自该项目：[levinit/fcitx-emoji](https://github.com/levinit/fcitx-emoji)

拼音命名的名称参考了以下网站：[Emoji大全](http://emojidaquan.com/)和[EmojiXD](https://emojixd.com/)

# 使用方法

本项目具体使用方法与[levinit/fcitx-emoji](https://github.com/levinit/fcitx-emoji) 使用方法相同。

**安卓端的fcitx5-android**的安装方法是：下载后打开输入法👉拼音右侧设置按钮👉快速输入👉右下角➕👉选中

然后在输入法中使用“v”键（如果您启用了“使用v来触发快速输入”）+emoji名称拼音来输入。

本项目的目的是更全面覆盖emoji表情，同一表情可能对应多个不同的名称。

例如：❌可以通过“错”(cuo)打出，也可通过“不对”(budui)打出。“猩猩”(xingxing)、“狒狒”(feifei)同时指的是 [🦍]

# 介绍

### emoji_phrase.mb

包含一些**非常抽象**的Emoji词语、成语和互联网用语。


如：“给爷爬”(geiyepa)指的是 [🤲👴🐛]、“哭笑不得”(kuxiaobude)指的是 [😭😄🙅🉐]

### emoji_nature.mb

包含动物与自然类的emoji表情。

如：“猩猩”(xingxing)指的是 [🦍]、“向日葵”(xiangrikui)指的是 [🌻]

### emoji_food.mb

包含食品与饮料类的emoji表情。

如：“鸡腿”(jitui)指的是 [🍗]、“米饭”(mifan)指的是 [🍚]

### emoji_objects.mb

包含物品类的emoji表情。

如：“磁铁”(citie)指的是 [🧲]、“胶囊”(jiaonang)指的是 [💊]

### emoji_people.mb

包含人物类emoji表情。（内容较多，共计539条）

包含各种人脸表情

（如：[喜欢]"xihuan"🥰, [吐舌]"tushe"😛）、各种手势（如："ok" 👌、[比心]"bixin"🫰、[左]"zuo"👈、[右]"you"👉

还包括各种职业（如：[医生]"yisheng"🧑‍⚕️、[老师]"laoshi"🧑‍🏫、[法官]"faguan"🧑‍⚖️）

### emoji_activities.mb

包含活动类emoji表情，主要是运动，以及运动相关事物。

（如：[击剑]"jijian"🤺, [冲浪]"chonglang"🏄）、各种物品（如：[乒乓球]"pingpangqiu" 🏓）

### emoji_Places.mb

包含emoji中大部分的地点。
（如：[日本]"riben"🗾, [情趣酒店]"qingqujiudian"🏩，[日落]"riluo" 🌇）
