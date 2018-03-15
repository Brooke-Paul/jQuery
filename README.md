# jQuery
1.jQuery 加载顺序<br>
父页面通过load方法加载子类页面,子类引用父类（jquery申明过的）的公用方法时，再次引用jquery会导致界面报错<br>
正确用法：
1）.子类不直接引用jquery。<br>
2）.通过短路的方式 ，window.jQuery(浏览器中的全局变量里的jQuery)去加载

