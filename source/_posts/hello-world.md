title: 迁移到github博客的第一个页面
categories: 杂项
tags: hexo,markdown
---
经过一番的折腾，还是把博客变成静态的了，github + [hexo](http://hexo.io/) ，大道至简~


## Markdown 一行代码的几种写法

### 行内式
`<?php echo "Hello World!"; ?>`

### 三点式

``` php
<?php
	echo "Hello World!";
?>
```

### 缩进式
	<?php
		echo "Hello World";
	?>

### Hexo式
{% codeblock Hello World Demo lang:php %}
	<?php
		echo "Hello World";
	?>
{% endcodeblock %}
