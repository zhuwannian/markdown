# markdown
markdown使用


# 在线markdown编辑器说明(这个是一级标题)

## 跳转 在线编辑器

网址1: [mahua](http://mahua.jser.me/)

网址2: [stackedit](https://stackedit.io/)

Mac下离线编辑器Mou

下载地址（不支持Mac Sierra版本）：http://mouapp.com/

MacDown 下载地址：https://macdown.uranusjr.com/

还有一种可以直接在android studio上进行编辑：参考他人博客：https://www.jianshu.com/p/3a79fe462ffb

## markdown是什么?
是一个编辑器

不知道为啥

## 这个是案例

* 第一级列表`高亮区域`
    *  第一个列表随意写点功能
    *  第二个列表文笔不好
* 就这样`的高亮区域`，哈哈（且看且珍惜）

##链接
* 邮件(zhu_wannian@163.com007#gmail.com, 把#换成@)
* QQ: 1531913496
* QQ空间: [名字忘了](http://weibo.com/ihubo)
* 百度: [跳转到百度](http://www.baidu.com)

## 一、标题写法：(这个是二级标题)

### 第一种方法：(这个是三级标题)

1. 在文本下面加上 等于号 = ，那么上方的文本就变成了大标题。等于号的个数无限制，但一定要大于0个哦。。
2. 在文本下面加上 下划线 - ，那么上方的文本就变成了中标题，同样的 下划线个数无限制。
3. 要想输入=号，上面有文本而不让其转化为大标题，则需要在两者之间加一个空行。

### 第二种方法：(这个是三级标题) （推荐这种方法；注意⚠️中间需要有一个空格）

关于标题还有等级表示法，分为六个等级，显示的文本大小依次减小。不同等级之间是以井号  #  的个数来标识的。一级标题有一个 #，二级标题有两个# ，以此类推。

例如：
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

## 二、编辑基本语法
### 字体格式强调

   1. 我们可以使用下面的方式给我们的文本添加强调的效果
 
      + *强调*  (示例：斜体)

      + _强调_  (示例：斜体)
 
      * **加重强调**  (示例：粗体)

      * __加重强调__ (示例：粗体)
 
      - ***特别强调*** (示例：粗斜体)

      - ___特别强调___  (示例：粗斜体)

### 代码
   * `<hello world>`
### 代码块高亮
```
@Override
protected void onDestroy() {
    EventBus.getDefault().unregister(this);
    super.onDestroy();
}
```
### 表格 （建议在表格前空一行，否则可能影响表格无法显示）

 表头  | 表头  | 表头
 ---- | ----- | ------
 单元格内容  | 单元格内容 | 单元格内容
 单元格内容  | 单元格内容 | 单元格内容

### 其他引用
   * 图片展示
      1. ![百度logo图片展示](https://www.baidu.com/img/bd_logo1.png)
   * 链接跳转
      1. [跳转指定链接](https://www.baidu.com/)

### 有序列表
   1. 项目1
   2. 项目2
   3. 项目3

### 无序列表
   * 项目1 （一个*号会显示为一个黑点，注意⚠️有空格，否则直接显示为*项目1）
   * 项目2
   * 项目3

### 有序列表相互嵌套
   1. 项目1
      1. 项目1.1
         1. 项目1.1.1
            1. 项目1.1.1.1
            2. 项目1.1.1.2
            3. 项目1.1.1.3
         2. 项目1.1.2
         3. 项目1.1.3
      2. 项目1.2
      3. 项目1.3
   2. 项目2
      1. 项目2.1
      2. 项目2.2
      3. 项目2.3
   3. 项目3

### 无序列表相互嵌套

   * 项目1
      - 项目1.1
         - 项目1.1.1
            - 项目1.1.1.1
            - 项目1.1.1.2
            - 项目1.1.1.3
         - 项目1.1.2
         - 项目1.1.3
      - 项目1.2
      - 项目1.3
   * 项目2
      + 项目2.1
      + 项目2.2
      + 项目2.3
   * 项目3
      * 项目3.1
      * 项目3.2
      * 项目3.3

### 有序/无序相互嵌套

   1. 项目1
      - 项目1.1
         1. 项目1.1.1
            + 项目1.1.1.1
            + 项目1.1.1.2
            + 项目1.1.1.3
         2. 项目1.1.2
         3. 项目1.1.3
      - 项目1.2
         1. 项目1.2.1
         2. 项目1.2.2
         3. 项目1.2.3
      - 项目1.3
         1. 项目1.3.1
         2. 项目1.3.2
         3. 项目1.3.3
   2. 项目2
      + 项目2.1
      + 项目2.2
      + 项目2.3
   3. 项目3
      * 项目3.1
      * 项目3.2
      * 项目3.3


### 换行（建议直接在前一行后面补两个空格）
直接回车不能换行，
可以在上一行文本后面补两个空格，
这样下一行的文本就换行了。  
或者就是在两行文本直接加一个空行。

也能实现换行效果，不过这个行间距有点大，不怕扯到裤裆的可以这样用（哈哈）。

### 引用
> 第一个引用文字
> 第二个引用文字

> 第二行引用文字  
> 第三行引用文字









# -------------分割线-------------以下是本次案例具体代码，你可以直接copy下面代码去看显示结果-------------------











```javascript

# 在线markdown编辑器说明(这个是一级标题)

## 跳转 在线编辑器

网址1: [mahua](http://mahua.jser.me/)

网址2: [stackedit](https://stackedit.io/)

Mac下离线编辑器Mou

下载地址（不支持Mac Sierra版本）：http://mouapp.com/

MacDown 下载地址：https://macdown.uranusjr.com/

还有一种可以直接在android studio上进行编辑：参考他人博客：https://www.jianshu.com/p/3a79fe462ffb

## markdown是什么?
是一个编辑器

不知道为啥

## 这个是案例

* 第一级列表`高亮区域`
    *  第一个列表随意写点功能
    *  第二个列表文笔不好
* 就这样`的高亮区域`，哈哈（且看且珍惜）

##链接
* 邮件(zhu_wannian@163.com007#gmail.com, 把#换成@)
* QQ: 1531913496
* QQ空间: [名字忘了](http://weibo.com/ihubo)
* 百度: [跳转到百度](http://www.baidu.com)

## 一、标题写法：(这个是二级标题)

### 第一种方法：(这个是三级标题)

1. 在文本下面加上 等于号 = ，那么上方的文本就变成了大标题。等于号的个数无限制，但一定要大于0个哦。。
2. 在文本下面加上 下划线 - ，那么上方的文本就变成了中标题，同样的 下划线个数无限制。
3. 要想输入=号，上面有文本而不让其转化为大标题，则需要在两者之间加一个空行。

### 第二种方法：(这个是三级标题) （推荐这种方法；注意⚠️中间需要有一个空格）

关于标题还有等级表示法，分为六个等级，显示的文本大小依次减小。不同等级之间是以井号  #  的个数来标识的。一级标题有一个 #，二级标题有两个# ，以此类推。

例如：
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

## 二、编辑基本语法
### 字体格式强调

   1. 我们可以使用下面的方式给我们的文本添加强调的效果
 
      + *强调*  (示例：斜体)

      + _强调_  (示例：斜体)
 
      * **加重强调**  (示例：粗体)

      * __加重强调__ (示例：粗体)
 
      - ***特别强调*** (示例：粗斜体)

      - ___特别强调___  (示例：粗斜体)

### 代码
   * `<hello world>`
### 代码块高亮
```
@Override
protected void onDestroy() {
    EventBus.getDefault().unregister(this);
    super.onDestroy();
}
```
### 表格 （建议在表格前空一行，否则可能影响表格无法显示）

 表头  | 表头  | 表头
 ---- | ----- | ------
 单元格内容  | 单元格内容 | 单元格内容
 单元格内容  | 单元格内容 | 单元格内容

### 其他引用
   * 图片展示
      1. ![百度logo图片展示](https://www.baidu.com/img/bd_logo1.png)
   * 链接跳转
      1. [跳转指定链接](https://www.baidu.com/)

### 有序列表
   1. 项目1
   2. 项目2
   3. 项目3

### 无序列表
   * 项目1 （一个*号会显示为一个黑点，注意⚠️有空格，否则直接显示为*项目1）
   * 项目2
   * 项目3

### 有序列表相互嵌套
   1. 项目1
      1. 项目1.1
         1. 项目1.1.1
            1. 项目1.1.1.1
            2. 项目1.1.1.2
            3. 项目1.1.1.3
         2. 项目1.1.2
         3. 项目1.1.3
      2. 项目1.2
      3. 项目1.3
   2. 项目2
      1. 项目2.1
      2. 项目2.2
      3. 项目2.3
   3. 项目3

### 无序列表相互嵌套

   * 项目1
      - 项目1.1
         - 项目1.1.1
            - 项目1.1.1.1
            - 项目1.1.1.2
            - 项目1.1.1.3
         - 项目1.1.2
         - 项目1.1.3
      - 项目1.2
      - 项目1.3
   * 项目2
      + 项目2.1
      + 项目2.2
      + 项目2.3
   * 项目3
      * 项目3.1
      * 项目3.2
      * 项目3.3

### 有序/无序相互嵌套

   1. 项目1
      - 项目1.1
         1. 项目1.1.1
            + 项目1.1.1.1
            + 项目1.1.1.2
            + 项目1.1.1.3
         2. 项目1.1.2
         3. 项目1.1.3
      - 项目1.2
         1. 项目1.2.1
         2. 项目1.2.2
         3. 项目1.2.3
      - 项目1.3
         1. 项目1.3.1
         2. 项目1.3.2
         3. 项目1.3.3
   2. 项目2
      + 项目2.1
      + 项目2.2
      + 项目2.3
   3. 项目3
      * 项目3.1
      * 项目3.2
      * 项目3.3


### 换行（建议直接在前一行后面补两个空格）
直接回车不能换行，
可以在上一行文本后面补两个空格，
这样下一行的文本就换行了。  
或者就是在两行文本直接加一个空行。

也能实现换行效果，不过这个行间距有点大，不怕扯到裤裆的可以这样用（哈哈）。

### 引用
> 第一个引用文字
> 第二个引用文字

> 第二行引用文字  
> 第三行引用文字


```
