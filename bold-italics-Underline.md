# 加粗倾斜下划线等  markdown使用

## 加粗倾斜删除

### 代码（直接复制以下即可）：

```markdown

**粗体**

***加粗斜体***

*斜体*或_斜体_

~~删除线~~

```


### 显示效果：

**粗体**

***加粗斜体***

*斜体*或_斜体_

~~删除线~~


### 强调也可以直接插在文字中间：

### 代码（直接复制以下即可）：

```markdown

看我**变粗**了没有

un**frigging**believable

```

### 显示效果：

看我**变粗**了没有

un**frigging**believable


## 如果 * 和 _ 与强调文字之间有空格的话，它们就只会被当成普通的符号。比如：

### 代码（直接复制以下即可）：

```markdown

不是** 把学的东西用起来 **，

而是** 为了用而学**！

```

### 显示效果：

不是** 把学的东西用起来 **，

而是** 为了用而学**！


## 上标 / 下标

### 代码（直接复制以下即可）：

```markdown

上标：O<sup>2</sup>

下标：H<sub>2</sub>O

```

### 显示效果：

上标：O<sup>2</sup>

下标：H<sub>2</sub>O


## 下划线

### 代码（直接复制以下即可）：

```html

<u>下划线 underline</u>

用数学公式：

下划线 $\underline{X}$

上划线 $\overline{X}$

```


### 显示效果：

<u>下划线 underline</u>

用数学公式：

下划线 $\underline{X}$

上划线 $\overline{X}$


## 个性化下划线，可以使用 html 的 span 标签、设置行内 CSS 的 border-bottom 属性来添加下划线。这种方式自定义程度最高。

### 代码（直接复制以下即可）：

```markdown

<span style="border-bottom: 2px dashed red;">下划虚线</span>

<span style="border-bottom: 1px solid red;">单下划线</span>

<span style="border-bottom: thick double #32a1ce;">双下划线</span>

<span style="border-bottom: 2px dotted red;">下划虚线</span>

### Markdown 无法表现中文的着重号 ```．```，实在是没有办法的办法：

<span style="border-bottom: 8px dotted red;">假冒着重号</span>

```

### 显示效果：

<span style="border-bottom: 2px dashed red;">下划虚线</span>

<span style="border-bottom: 1px solid red;">单下划线</span>

<span style="border-bottom: thick double #32a1ce;">双下划线</span>

<span style="border-bottom: 2px dotted red;">下划虚线</span>

### Markdown 无法表现中文的着重号 ．，实在是没有办法的办法：

<span style="border-bottom: 8px dotted red;">假冒着重号</span>


## 添加注音
### ruby 语法说明

* <ruby> — 用它将需要注释或注音标的文字内容包围住。
* <rt> — 这里面放置音标或注释，这个标记要跟在需要注释的文本后边。rt 里的文字，对于横向显示的文章，它会显示在上方。对于竖向显示的文字，它会显示到右边。
* <rp> — 这个标记是防备那些不支持 ruby 标记的浏览器，主要用来放置括弧。对于支持这个标记的浏览器，rp 标记的 CSS 样式是 {display:none;}，也就是不可见。


### 代码（直接复制以下即可）：

```markdown

<ruby>
我<rp>（</rp><rt>wǒ</rt><rp>）</rp>
爱<rp>（</rp><rt>ài</rt><rp>）</rp>
你<rp>（</rp><rt>nǐ</rt><rp>）</rp>
中<rp>（</rp><rt>zhōng</rt><rp>）</rp>
国<rp>（</rp><rt>guó</rt><rp>）</rp>
</ruby>

#### 偷懒的写法：

<ruby>
我爱你中国<rt>wǒàinǐzhōngguó</rt>
</ruby>

```

### 显示效果：

<ruby>
我<rp>（</rp><rt>wǒ</rt><rp>）</rp>
爱<rp>（</rp><rt>ài</rt><rp>）</rp>
你<rp>（</rp><rt>nǐ</rt><rp>）</rp>
中<rp>（</rp><rt>zhōng</rt><rp>）</rp>
国<rp>（</rp><rt>guó</rt><rp>）</rp>
</ruby>

#### 偷懒的写法：

<ruby>
我爱你中国<rt>wǒàinǐzhōngguó</rt>
</ruby>

## 使用特殊符号
### 写作的时候，也可以灵活运用一些其他特殊符号：

> 根据个人喜好选择使用，喜欢简单希望节约时间的朋友，可以不用搞得那么复杂！

### 常用符号大全

### 代码（直接复制以下即可）：

```html

▬▬▬▬.◙.▬▬▬▬
 ▂▄▄▓▄▄▂
 ◢◤ █▀▀████▄▄▄▄◢◤
 █ 陈独秀专属座驾█▀……╬
 ◥██████◤
  ══╩══╩═══


```

### 显示效果：

```html

▬▬▬▬.◙.▬▬▬▬
 ▂▄▄▓▄▄▂
 ◢◤ █▀▀████▄▄▄▄◢◤
 █ 陈独秀专属座驾█▀……╬
 ◥██████◤
  ══╩══╩═══


```






### 代码（直接复制以下即可）：

```markdown



```

### 显示效果：

