# Mac上QQ音乐无损保存音频方法



# 概述

前提是==Mac电脑,QQ绿钻==(~~我白嫖的7天绿钻~~)
只是偶然发现有缓存这个东西,有的音频可以直接在QQ音乐for Mac播放,有的加密的音频就得先解密一下.

#  步骤
1.**在设置打开无损播放**![设置无损音质](https://img-blog.csdnimg.cn/20200209200631844.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0ludmluY2libGVNdXJQSHk=,size_16,color_FFFFFF,t_70)
(~~不要在意QQ昵称~~)

 2.**播放一首无损音质的音乐**(别的音质也可以,可能最后都是要破解掉的)![播放无损音乐](https://img-blog.csdnimg.cn/2020020920115890.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0ludmluY2libGVNdXJQSHk=,size_16,color_FFFFFF,t_70)
>(*Hardstyle never dies!!!*)

 3.**播放到缓存条走完以后,按照这个路径找一下,这是缓存所在路径**
 
 ![找到缓存文件夹](https://img-blog.csdnimg.cn/20200209201811978.png)
 路径是
```
//cd /Users/<你的用户名>/Library/Containers/com.tencent.QQMusicMac/Data/Library/Application\ Support/QQMusicMac/iMusic
```
![下载的编码音乐](https://img-blog.csdnimg.cn/20200209201035662.png)
(附带一个付费音乐下载后所在路径)
```
//cd /Users/<你的用户名>/Library/Containers/com.tencent.QQMusicMac/Data/Library/Application\ Support/QQMusicMac/iQmc
```

4.**按照修改日期排序,找到最新的文件夹**
![找到最新文件夹](https://img-blog.csdnimg.cn/20200209203722152.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0ludmluY2libGVNdXJQSHk=,size_16,color_FFFFFF,t_70)
然后就可以把flac文件提取出来了,右键可以直接QQ音乐播放
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200209203901170.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0ludmluY2libGVNdXJQSHk=,size_16,color_FFFFFF,t_70)
但是没有名字,没有歌手,没有图片,以后可以用music tag edit pro自行编辑...
最要命的是flac文件只能QQ音乐播放,别的软件网易云,audirvana打不开,这只是QQ音乐的缓存,所以我也指不定哪天就不能用了...

![各种格式的锁码音频](https://img-blog.csdnimg.cn/20200209204527331.png)
如图可见,如果播放别的音质,就会出现很多锁码的音频,比如qmc,tm,qmcflac文件,所以要**解码**一下[^1] 
==(工具的链接点一下标注[^1]就可以复制)==
 ## [工具链接](https://moresound.tk/music/tool/)
>工具建议用Chrome,Firefox等浏览器打开,用Safari也行吧...就是显示时候可能有点问题

4~5~.**建议直接在搜索栏搜索tm,qmc,flac,然后直接全选拖到工具里去**

**以上为找到QQ缓存文件在哪里的教程全部内容,其实用这个方法虽然麻烦,但是,,,批量操作还是蛮爽的,只要你听歌,然后等缓存完成,然后拖动进去解码就可以了,个人认为~~白嫖~~还是很快乐的
且轻松,虽然没有歌手什么的tag的确是麻烦了点,但好歹是无损啊,单车不比摩托香?**

最后附赠一个~~白嫖~~7天绿钻的链接,到2月12号前有效
## [不会有毒的,这是IT基地,没坑.点蓝链直接进去扫码就好,抓紧时间](https://url.cn/5w6GcAO)
[^1]:https://moresound.tk/music/tool/
