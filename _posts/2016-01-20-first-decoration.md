---
layout: default
title: 装饰一下这个BLOG
---
# 装饰一下这个BLOG

## 基本背景
博客建立以后我继续投入写paper的战斗。中间也就简单地把这次NGA舰区的榛名应援签名给弄上，然后挑了个NGA上最浅的配色放进去作为背景色。不过“榛名大丈夫”这几个字放在这个背景上还真的很瞎眼，也没办法，所有的NGA配色我都试了，好像浅色的反而好一些。其实这一次所有的应援签名里面，最舒服的一张反而是秋活最新的舰娘萩风。

![萩风](/images/post_images/20160120/hagikaze.png)

然而根据基本法

> Remember to just have 1 waifu, getting more waifu will desroy your laifu.

对于萩风的赞美我只能深深地埋在心里。

![哭哭](/images/emotion_images/ACMusu/16.png)

## 先解决排版问题。
前几天看到老大哥做的视频DEMO，非常牛逼。当时老板问是不是要改一下颜色，老大哥说，直接用CSS改一下就是了。我突然想起CSS是很久以前我在高中的时候学网页制作的时候讲的东西<font class="dark">，当时好像流连于超级玛丽的DOS版本根本没听</font>。后来我的网页基本上是hardcode的HTML文件连javascript都很少，~~做出来效果非常丑~~。

![瞎](/images/emotion_images/ACMusu/50.png)

不过对CSS我的认知大概就是“HTML上面对应的TAG的信息不需要一个个设置”这样，于是就想找找一些现成的博客的CSS，简单一点为好，想来想去貌似[王垠的博客](http://yinwang.org)那种非常简单的就挺好。于是直接上去扒下来用。

## 背景图片

然后我就发现不对了，榛名的签名本身就是一张图片，跟着img的标签增加的边框，然后想居中也没有成功居中，而且还被框在了文本框里面。

于是只能谷歌CSS的body background image怎么设置，多次试错后（无数次PUSH GITHUB），终于找到了合适的放置方法。

然后我为了增加一下~~耻~~尺度，想把南小鸟抢镜的脑袋放页面左下角，可惜能找到的那个颜色失真很厉害，只能作罢，放个萌百娘吧。

>~~但是既然提到了我也不想放过你们。~~<br/>
>![南小鸟](/images/Kotori-dash.gif)

接着我又在右边放了一个<font class="dark">漏尿凤</font>大凤，这种神神秘秘的感觉很好呢。

## 结语
好了，最后就成了这个样子，写到这里我就觉得我的学术博客是不是得再开一个新的Github的project了？
