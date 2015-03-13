# H5tips

关于HTML5的一些tips，也可以作为HTML5的面试题。

>html部分

  * 语义化
  * input
  *  * email
```
E-mail: <input type="email" name="user_email" />
```
  * 完成js的效果

>css 部分

  * 字体圆润
  * 字体图标 font-icon
  * 盒模型做三角形等形状
  * 阴影渲染出其他图形
  * svg
  * 动画效果
  * 替换图片
  * 替换js动画

>js  部分

  * 本地存储
  * canvas
  * 优化
  * 按需执行
  * 动态内容
在选择将列表插入页面的时候，我们有两种方式。
一种是动态加载json文件，用JS生成内容，插入页面；另一种是使用XHR加载html文件，使用responseText获取内容，插入页面。其实，使用第二种方法有明显的好处。第一是，html文件体积比json文件小，加载量减少；第二是直接使用html文件，减少了JS动态生成结构的开销。

 * 延时加载
 * 
