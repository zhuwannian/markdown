# 插入音乐 markdown使用

## 方法 1

**嵌入在线音乐**，到 <http://www.170mv.com/song> 或者 http://www.333ttt.com/up/ 获得外链：

```html
<audio id="audio" controls="" preload="none">
<source id="mp3" src="http://sc1.111ttt.cn:8282/2018/1/03m/13/396131229550.m4a?tflag=1546606800&pin=97bb2268ae26c20fe093fd5b0f04be80#.mp3">
</audio>
```


<audio id="audio" controls="" preload="none">
<source id="mp3" src="http://sc1.111ttt.cn:8282/2018/1/03m/13/396131229550.m4a?tflag=1546606800&pin=97bb2268ae26c20fe093fd5b0f04be80#.mp3">
</audio>

**本地音乐的话**，将 SRC 源地址指向本地文件：

```html
<audio id="audio" controls="" preload="none">
<source id="mp3" src="/music/BWhatUWannaB.mp3">
</audio>
```

## 方法 2

进入 [网易云音乐](https://music.163.com/) 歌曲界面，点击光碟下方的生成外链播放器：

```html
<iframe
    frameborder="no"
    border="0"
    marginwidth="0"
    marginheight="0"
    width=330
    height=86
    src="//music.163.com/outchain/player?type=2&id=393697&auto=1&height=66">
</iframe>
```

<iframe
    frameborder="no"
    border="0"
    marginwidth="0"
    marginheight="0"
    width=330
    height=86
    src="//music.163.com/outchain/player?type=2&id=393697&auto=1&height=66">
</iframe>
