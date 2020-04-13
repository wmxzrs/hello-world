JavaScrpt
=========

**是ECMAScript标准的具现。1997年是ECMSAScript第一版标准的发布。**

> JavaScript代码可以直接嵌在网页的任何地方，不过通常我们都把JavaScript代码放到```<head>```中:

```HTML

     <html>
     <head>
       <script>
         alert("hello,world");
       </script>
     </head>
     <body>
     ……
     </body>
     </html>

```

> 第二种方法是把JavaScript代码放到一个单独的<kbd>.js</kbd>  然后在HTML中通过<kbd>```<script src=""></script>```
</kbd>  

有些时候你会看到```<script>```标签还设置了一个type属性：

```HTML
<script type="text/javascript">
  ...
</script>
```

但这是没有必要的，因为默认的type就是JavaScript，所以不必显式地把type指定为JavaScript。  

怎么在浏览器中调试JavaScript代码呢
-------------------

> 步骤：

+ 首先，你需要安装Google Chrome浏览器，Chrome浏览器对开发者非常友好，可以让你方便地调试JavaScript代码。
  从这里下载Chrome浏览器。
  打开网页出问题的童鞋请移  步国内镜像。

+ 安装后，随便打开一个网页，然后点击菜单“查看(View)”-“开发者(Developer)”-“开发者工具(Developer Tools)”，
  浏览器窗口就会一分为二，下方就是开发者工具：

+ 先点击“控制台(Console)“，在这个面板里可以直接输入JavaScript代码，按回车后执行。

+ 要查看一个变量的内容，在Console中输入console.log(a);，回车后显示的值就是变量的内容。

+ 关闭Console请点击右上角的“×”按钮。请熟练掌握Console的使用方法，在编写JavaScript代码时，
  经常需要在Console运行测试代码。

+ 如果你对自己还有更高的要求，可以研究开发者工具的“源码(Sources)”，掌握断点、单步执行等高级调试技巧。
