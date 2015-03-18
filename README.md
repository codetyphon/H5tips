# H5tips

关于HTML5的一些tips，也可以作为HTML5的面试题。

>html部分

  * 语义化
  * input
  * 
>禁止自动更正

```
<input type="text autocorrect="off" />
```

禁止首字母大写
```
<input autocapitalize="off" />
```

```
<input type="text" pattern="\d*" novalidate />   <!-- number -->


<input type="email" />
<input type="number" />

```


>email
```
E-mail: <input type="email" name="user_email" />
```
>url
```
Homepage: <input type="url" name="user_url" />
```
>number
```
Points: <input type="number" name="points" min="1" max="10" />
```
>range    可以用來做滑動
```
<input type="range" name="points" min="1" max="10" />
```
>時間日期
```
Date: <input type="date" name="user_date" />
```

>search
```
Date: <input type="search" name="user_date" />
```
>輸入列表
```
Webpage: <input type="url" list="url_list" name="link" />
<datalist id="url_list">
<option label="W3School" value="http://www.W3School.com.cn" />
<option label="Google" value="http://www.google.com" />
<option label="Microsoft" value="http://www.microsoft.com" />
</datalist>
```

>自動焦點
```
User name: <input type="text" name="user_name"  autofocus="autofocus" />
```

>自定義驗證
```
Country code: <input type="text" name="country_code"
pattern="[A-z]{3}" title="Three letter country code" />
```
默認值
```
<input type="search" name="user_search"  placeholder="Search W3School" />
```
不能為空
```
Name: <input type="text" name="usr_name" required="required" />
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
 
```
<div id="test"></div>
```


```
var el = document.getElementById("test");
el.dataset.name = "chaomao";
el.dataset.age = 15;
console.log(el.dataset.name); //return chaomao
console.log(el.dataset.age); //return 15
```

```
<div id="test" data-name="chaomao" data-age="15"></div>
```


居中定位法：

.example {
    position: absolute; left: 50%; top: 50%; 
    margin-left: -100px; margin-top: -100px;
}

自動播放音樂IOS
```
<audio id="audio" src="音乐地址" loop preload="auto" autoplay="true" class="hide"></audio>
<img src="1.png" onload="audio.play()" />
```
