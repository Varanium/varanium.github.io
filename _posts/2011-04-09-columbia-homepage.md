---
layout: default
title: 如何建立你的哥大个人主页
---
# 如何建立你的哥大个人主页

昨天从淡定帝那里得知每个哥大学生都能搞个人主页，于是向他询问了一下入口，接着就摸索了一下。

本教程所涉及的必须品：Unix/类Unix系统+Windows，哥大uni

首先在Unix/类Unix系统上的“终端”（有点类似于那种命令行，我是用的苹果系统，没有苹果电脑的去图书馆抢……占一台或者去Apple Store抢……购一台，不喜欢苹果的用Linux，不熟悉这些的自行谷歌）里输入

    ssh xx1234@cunix.cc.columbia.edu

xx1234是你的哥大uni，反正要uni密码打uni密码，没uni密码退学重申请，要打yes就打yes，不行的话砸了电脑换一台。

接着输入

    ls

看看里面有没有public_html文件夹，一般来说呢是有的。如果有的话，只要输入以下两行

    chmod a+x ~
    chmod a+rx ~/public_html

如果没有的话，就输入三行

    chmod a+x ~
    mkdir ~/public_html
    chmod a+rx ~/public_html

具体是啥意思别管那么多，我也不太懂，懂的也不用教育我，因为懂的人不用看这教程

下面做网页，最简单的那种，在word下，保存为网页文件，取名index.htm，一般来说会有个包含index名称的文件夹出现。

接着么大多数孩子用的是Windows，去哥大CUIT下

[WinSCP](http://www.columbia.edu/acis/software/winscp/)

MAC党有个[FUGU](http://www.columbia.edu/acis/software/fugu/)

Linux党么我只能遗憾地说学校木有提供这些ftp软件。。。

打开后，Host name填`cunix.cc.columbia.edu`，User name填uni，Password填uni密码，随后save下，登陆。

把index.htm和那个index的文件夹一起拷进public_html文件夹下面，把你的网址分给同学好友看吧。

最后欢迎围观[（已经失效）](www.columbia.edu/~tz2163/)