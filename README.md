# 项目简介

这是一个基于 web 的用来读取 rss 源的应用，以及相应的基于 Jasmine 编写的测试套件。其中测试套件的范围包括：rss 数据源的定义，DOM 操作，loadFeed函数的功能。

# 项目所需的知识点

- Jasmine 的内置 Matcher：[Javascript测试框架Jasmine（二）：Matchers](http://keenwon.com/1197.html)
- jQuery API:
  - 检查选定的 jQuery 对象是否具有指定 class 名称：`hasClass()`
  - 在选定元素上直接触发事件：`triggerHanlder()`
  - [jQuery 中文文档](http://www.jquery123.com)

# 如何使用

直接 clone 本项目到本机，用浏览器打开 index.html。在网页的下方可以看到 Jasmine 的检查结果。