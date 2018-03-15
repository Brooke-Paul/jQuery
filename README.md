# jQuery
1.jQuery 加载顺序
父页面通过load方法加载子类页面
子类引用父类（jquery申明过的）的公用方法时，再次引用jquery会导致界面报错
正确用法：
子类不直接引用jquery。
通过短路的方式：
<script>window.jQuery || document.write('<script src="../js/jquery-1.11.0.js"><\/script>')</script>


