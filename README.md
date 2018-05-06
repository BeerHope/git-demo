# git-demo
---
# 关于项目中的使用框架
## boosrtap的使用
## less快速编写css样式
---
## boostrap


## less的使用
### 在客户端使用
引入你的 .less 样式文件的时候要设置 rel 属性值为 “stylesheet/less”:
<link rel="stylesheet/less" type="text/css" href="styles.less">
然后点击页面顶部download按钮下载 less.js, 在<head> 中引入:
	<script src="less.js" type="text/javascript"></script>
注意你的less样式文件一定要在引入less.js前先引入。
备注：请在服务器环境下使用！本地直接打开可能会报错！

监视模式
监视模式是客户端的一个功能，这个功能允许你当你改变样式的时候，客户端将自动刷新。
要使用它，只要在URL后面加上'#!watch'，然后刷新页面就可以了。另外，你也可以通过在终端运行less.watch()来启动监视模式。
