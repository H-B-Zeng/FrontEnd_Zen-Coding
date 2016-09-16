**開發環境**:以下三種都有支援
1.Visual Studio 2012可以安裝Web Essentials 2012擴充套件，安裝完就預設啟用
2.Sublime Text 2，透過Package Control尋搜"Zen Coding"安裝後也能取得支援
3.NotePad++

HTML4 && HTML5，以下快速開局
```
html:4t
html:5
html:xt for an XHTML transitional doctype
```
快速建立參考 CSS & Script
```
link:css
script:src
```

Body常用語法 Table
```
ul>li*5
ul>li*5>lorem5 (快速建立文章)
dl+

table+
table>tbody>th>td*3
table>tbody>th>td*3^^tr>td*3

form:get
form:post

input:t
input:t*3
```

Body常用語法 DIV
```
div#name (Create ID)
div.one.two (Create class)
div#name.one.two(Create ID && class)
div#name>li.item
div#name>li.item##*4 (Create Item00 ~ Item04)
div+p+p
div#name>p.one+p.two
div#name>p.title
div[title]
div#page>div.log+ul#nav>li*5>a (>表示子層裡新增  +表示新增在同一層)
```

Body常用語法 Select > option 
```
select>option#item-$*5 (Create option id=item-1  ~ id=item-5)
select>option#item-${opt $}*5 (Create <option id="item-1">opt 1</option>)
```

Body常用語法 a & p
```
a[title="Hello World"] (<a href="" title="Hello World"></a>)
p>{點擊}+a{這裡}+{繼續}
```


Body常用語法 ul[ ] (客製化內容)  
```
ul[data-bind="foreach:customers"]>li*4>sapn{內容 $$}+input[type=text data-bind="value:$$]
```


參考資料
[ZEN-CODING - 教你極速撰寫HTML5與CSS3程式碼](http://blog.kkbruce.net/2012/11/zen-coding-extremely-speed-write-your-html5-css3-code.html#.VzGLfoR94dU)