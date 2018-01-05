---
title: 星期五！
---
# 新年第一周就这么结束了。
```
现在，你已经成功安装并启用了 NexT 主题。下一步我们将要更改一些主题的设定，包括个性化以及集成第三方服务。

4）主题设定

选择 Scheme

Scheme 是 NexT 提供的一种特性，借助于 Scheme，NexT 为你提供多种不同的外观。同时，几乎所有的配置都可以 在 Scheme 之间共用。目前 NexT 支持三种 Scheme，他们是：

Muse - 默认 Scheme，这是 NexT 最初的版本，黑白主调，大量留白
Mist - Muse 的紧凑版本，整洁有序的单栏外观
Pisces - 双栏 Scheme，小家碧玉似的清新
Scheme 的切换通过更改 主题配置文件，搜索 scheme 关键字。 你会看到有三行 scheme 的配置，将你需用启用的 scheme 前面
1
2
3
4
注释 # 即可。 选择 Pisce Scheme
#scheme: Muse
#scheme: Mist
scheme: Pisces
1
2
3
5）设置语言

编辑 站点配置文件， 将 language 设置成你所需要的语言。建议明确设置你所需要的语言，例如选用简体中文，配置如下：

language: zh-Hans
1
目前 NexT 支持的语言如以下表格所示：

语言	代码	设定实例
English	en	language: en
简体中文	zh-Hans	language: zh-Hans
Français	fr-FR	language: fr-FR
Português	pt	language: pt
繁體中文	zh-hk 或者 zh-tw	language: zh-hk
Русский язык	ru	language: ru
Deutsch	de	language: de
日本語	ja	language: ja
Indonesian	id	language: id
6）设置 菜单

菜单配置包括三个部分，第一是菜单项（名称和链接），第二是菜单项的显示文本，第三是菜单项对应的图标。 NexT 使用的是 Font Awesome 提供的图标， Font Awesome 提供了 600+ 的图标，可以满足绝大的多数的场景，同时无须担心在 Retina 屏幕下 图标模糊的问题。

编辑主题配置文件，修改以下内容：

设定菜单内容，对应的字段是 menu。 菜单内容的设置格式是：item name: link。其中 item name 是一个名称，这个名称并不直接显示在页面上，她将用于匹配图标以及翻译。

菜单示例配置

menu:
  home: /
  archives: /archives
  #about: /about
  #categories: /categories
  tags: /tags
  #commonweal: /404.html
	现在，你已经成功安装并启用了 NexT 主题。下一步我们将要更改一些主题的设定，包括个性化以及集成第三方服务。

4）主题设定

选择 Scheme

Scheme 是 NexT 提供的一种特性，借助于 Scheme，NexT 为你提供多种不同的外观。同时，几乎所有的配置都可以 在 Scheme 之间共用。目前 NexT 支持三种 Scheme，他们是：

Muse - 默认 Scheme，这是 NexT 最初的版本，黑白主调，大量留白
Mist - Muse 的紧凑版本，整洁有序的单栏外观
Pisces - 双栏 Scheme，小家碧玉似的清新
Scheme 的切换通过更改 主题配置文件，搜索 scheme 关键字。 你会看到有三行 scheme 的配置，将你需用启用的 scheme 前面
1
2
3
4
注释 # 即可。 选择 Pisce Scheme
#scheme: Muse
#scheme: Mist
scheme: Pisces
1
2
3
5）设置语言

编辑 站点配置文件， 将 language 设置成你所需要的语言。建议明确设置你所需要的语言，例如选用简体中文，配置如下：

language: zh-Hans
1
目前 NexT 支持的语言如以下表格所示：

语言	代码	设定实例
English	en	language: en
简体中文	zh-Hans	language: zh-Hans
Français	fr-FR	language: fr-FR
Português	pt	language: pt
繁體中文	zh-hk 或者 zh-tw	language: zh-hk
Русский язык	ru	language: ru
Deutsch	de	language: de
日本語	ja	language: ja
Indonesian	id	language: id
6）设置 菜单

菜单配置包括三个部分，第一是菜单项（名称和链接），第二是菜单项的显示文本，第三是菜单项对应的图标。 NexT 使用的是 Font Awesome 提供的图标， Font Awesome 提供了 600+ 的图标，可以满足绝大的多数的场景，同时无须担心在 Retina 屏幕下 图标模糊的问题。

编辑主题配置文件，修改以下内容：

设定菜单内容，对应的字段是 menu。 菜单内容的设置格式是：item name: link。其中 item name 是一个名称，这个名称并不直接显示在页面上，她将用于匹配图标以及翻译。

菜单示例配置

menu:
  home: /
  archives: /archives
  #about: /about
  #categories: /categories
  tags: /tags
  #commonweal: /404.html
```