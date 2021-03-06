## 使用方法

* sublime text

  ```
  直接在编辑器中输入 HTML 或 CSS 的代码的缩写，然后按 tab键（或 ctrl+e）就可以拓展为完整的代码片段
  ```



## 语法

### 后代：>

* 缩写：nav>ul>li

  ```html
  <nav>
  	<ui>
  		<li></li>
  	</ui>
  </nav>
  ```



### 兄弟：+

* 缩写：div+p+bq

  ```html
  <div></div>
  <p></p>
  <blockquote></blockquote>
  ```



### 上级：^

* 缩写：div+div>p>span+em^bq

  ```html
  <div></div>
  <div>
  	<p><span></span><em></em></p>
  	<blockquote></blockquote>
  </div>
  ```

* 缩写：div+div>p>span+em^^bq

  ```html
  <div></div>
  <div>
  	<p><span></span><em></em></p>
  </div>
  <blockquote></blockquote>
  ```



### 分组：()

* 缩写：div>(header>ul>li*2>a)+footer>p

  ```html
  <div>
  	<header>
  		<ul>
  			<li><a href=""></a></li>
  			<li><a href=""></a></li>
  		</ul>
  	</header>
  	<footer>
  		<p></p>
  	</footer>
  </div>
  ```

* 缩写：(div>dl>(dt+dd)*3)+footer>p

  ```html
  <div>
  	<dl>
  		<dt></dt>
  		<dd></dd>
  		<dt></dt>
  		<dd></dd>
  		<dt></dt>
  		<dd></dd>
  	</dl>
  </div>
  <footer>
  	<p></p>
  </footer>
  ```
  ​


### 乘法：*

* 缩写：ul>li*5

  ```html
  <ul>
  	<li></li>
  	<li></li>
  	<li></li>
  	<li></li>
  	<li></li>
  </ul>
  ```



### 自增符号：$

* 缩写：ul>li.item$*5

  ```html
  <ul>
  	<li class="item1"></li>
  	<li class="item2"></li>
  	<li class="item3"></li>
  	<li class="item4"></li>
  	<li class="item5"></li>
  </ul>
  ```

  * 缩写：h$[title=item$]{Header $}*3

  ```html
  <h1 title="item1">Header 1</h1>
  <h2 title="item2">Header 2</h2>
  <h3 title="item3">Header 3</h3>
  ```

* 缩写：ul>li.item$$$*5

  ```html
  <ul>
  	<li class="item001"></li>
  	<li class="item002"></li>
  	<li class="item003"></li>
  	<li class="item004"></li>
  	<li class="item005"></li>
  </ul>
  ```

* 缩写：ul>li.item$@3*5

```html
<ul>
  <li class="item3"></li>
  <li class="item4"></li>
  <li class="item5"></li>
  <li class="item6"></li>
  <li class="item7"></li>
</ul>
```
### ID 和类属性

* 缩写：#header
```html
<div id="header"></div>
```

* 缩写：.title
```html
<div class="title"></div>
```

* 缩写：form#search.wide
```html
<form action="" id="search" class="wide"></form>
```

* 缩写：p.class1.class2.class3
```html
<p class="class1 class2 class3"></p>
```

### 自定义属性

* 缩写：td[rowspan=2 colspan=3 title]
```html
<td rowspan="2" colspan="3" title=""></td>
```

* 缩写：[a='value1' b="value2"]
```html
<div a="value1" b="value2"></div>
```


### 文本：{}
* 缩写：a{Click me}
```html
<a href="">Click me</a>
```

### HTML
* 缩写：!
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Document</title>
</head>
<body>
  
</body>
</html>
```


[参考地址](https://www.w3cplus.com/tools/emmet-cheat-sheet.html)






