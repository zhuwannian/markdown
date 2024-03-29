# quote引用 markdown使用

## 引用的多层嵌套

只要根据层次加上不同数量的 > 。

### 代码（直接复制以下即可）：

```markdown

>  小白请问  Markdown  怎么用？  -  小白

>>  自己看教程！  -  愤青

>>>  教程在哪？  -  小白

>>  
>>  我也不知道在哪！  -  愤青

>

>  那你回答个屁。  -  小白

```

### 显示效果：

>  小白请问  Markdown  怎么用？  -  小白

>>  自己看教程！  -  愤青

>>>  教程在哪？  -  小白

>>  
>>  我也不知道在哪！  -  愤青

>

>  那你回答个屁。  -  小白


## 引用其它要素
引用的区块内也可以使用其他的语法，包括标题、列表、代码区块等。

### 代码：

```markdown

> 1.1 这是第一行列表项。

>> 2.1 这是第二行列表项。

>>> - 这是第三行列表项。

> ### 给出一些例子代码：

> ```bash
> return shell_exec("echo $input | $markdown_script");
> ```

```

### 显示效果：

> 1.1 这是第一行列表项。

>> 2.1 这是第二行列表项。

>>> - 这是第三行列表项。

> ### 给出一些例子代码：

> ```bash
> return shell_exec("echo $input | $markdown_script");
> ```

## 引用中内容换行
有时候引用的内容太长，需要分段落层次，可以使用 ``` <br> ``` 实现换行。 举例：

### 代码：

```markdown

> $\underline{幽默小故事，笑死人不偿命}$ <br> 我：“老板，你这清炒油麦菜是荤菜还是素菜？ 老板：“当然是素菜了” <br> 我：“那这条虫是怎么回事” 老板：“呃……它也是来吃饭的。” <br> 我：“它吃饭凭什么我付钱？我又不认识它！” 老板哭着说：“它为了这顿饭，把命都丢了，你还能要求它AA制吗？”

```

### 显示效果：

> $\underline{幽默小故事，笑死人不偿命}$ <br> 我：“老板，你这清炒油麦菜是荤菜还是素菜？ 老板：“当然是素菜了” <br> 我：“那这条虫是怎么回事” 老板：“呃……它也是来吃饭的。” <br> 我：“它吃饭凭什么我付钱？我又不认识它！” 老板哭着说：“它为了这顿饭，把命都丢了，你还能要求它AA制吗？”


