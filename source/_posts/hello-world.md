title: 迁移到github博客的第一个页面
categories: 杂项
---

经过一番的折腾，还是把博客变成静态的了，github + [hexo](http://hexo.io/) ，大道至简~
hexo和markdown之前接触都不算太多，这里对一些个人比较关注的点做个记录。
首先当然是代码的高亮，强迫症你懂的~ :)

## Markdown 代码高亮的几种方法
### 三点式
书写格式：

>&#96;&#96;&#96; php
><?php
>&nbsp;&nbsp;&nbsp;&nbsp;echo "Hello World!";
>?>
>&#96;&#96;&#96;

显示格式：

``` php
<?php
    echo "Hello World!";
?>
```

### 缩进式
书写格式(注意缩进)：

>&nbsp;&nbsp;&nbsp;&nbsp;<?php
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;echo "Hello World!";
>&nbsp;&nbsp;&nbsp;&nbsp;?>

显示格式：

    <?php
        echo "Hello World";
    ?>

### Hexo式
书写格式：

>{&#37; codeblock Hello World Demo lang:php http&#58;//php.net php &#37;}
><?php
>&nbsp;&nbsp;&nbsp;&nbsp;echo "Hello World";
>?>
>{&#37; endcodeblock &#37;}

显示样式：

{% codeblock Hello World Demo lang:php http://php.net php %}
<?php
    echo "Hello World";
?>
{% endcodeblock %}