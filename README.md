
# 选择器
## CSS元素选择器  
以标签名命名  
 html { color: black; }  
 
 a { font-size : 20px; }  

## CSS 选择器分组  
  一组选择器设置相同的样式  
  
  h2, p {color:gray;}

## CSS 类选择器  
  &lt;div class="cls"&gt;123&lt;/div&gt;  
  
  &lt;p class="cls"&gt;456&lt;/p&gt;  
  
  .cls { color:black; }  
  
  *.cls { color:black; }  
  
  p.cls { color:red; }
  
  .cls,.cls1
  .cls.cls1 区别
  class="cls cls1 cls2"

## CSS ID 选择器  
  ID选择器是唯一的，因为一个文档中，同一个id只会出现一次  
  
  #mostImportant {color:red; background:yellow;}  
  
  &lt;h1 id="mostImportant"&gt;This is important!&lt;/h1&gt;
  

## CSS 属性选择器  
  对标签对应拥有该属性的元素生效  
  
  img[alt] {border: 5px solid red;}  
  

## CSS 后代选择器  
  有包含关系的标签，通常用于一整块组件等情况。  
  
  div h1 {color:red;}    
  &lt;div&gt;  
      &lt;h1&gt; content  &lt;/h1&gt;  
  &lt;div&gt;  
  

## CSS 子元素选择器
  有父子关系的标签，通常用于一整块组件等情况。  

  div>h1 {color:red;}    
  &lt;div&gt;  
      &lt;h1&gt; content  &lt;/h1&gt;  
  &lt;div&gt;  

## CSS 相邻兄弟选择器  
  h5 + p + p {margin-top:50px;color:red}  
  &lt;h5&gt;This is a heading.&lt;/h5&gt;  
  &lt;p&gt;This is paragraph.&lt;/p&gt;  
  &lt;p&gt;This is paragraph.&lt;/p&gt;  
  
## CSS 伪类  
系统默认伪类
<table class="dataintable">
  <tbody><tr>
    <th style="width:30%;">属性</th>
    <th style="width:65%;">描述</th>
    <th style="width:5%;">CSS</th>
  </tr>
  <tr>
    <td><a href="/cssref/pr_pseudo_active.asp">:active</a></td>
    <td>向被激活的元素添加样式。</td>
    <td>1</td>
  </tr>
	<tr>
    <td><a href="/cssref/pr_pseudo_focus.asp">:focus</a></td>
    <td>向拥有键盘输入焦点的元素添加样式。</td>
    <td>2</td>
  </tr>
	<tr>
    <td><a href="/cssref/pr_pseudo_hover.asp">:hover</a></td>
    <td>当鼠标悬浮在元素上方时，向元素添加样式。</td>
    <td>1</td>
  </tr>
  <tr>
    <td><a href="/cssref/pr_pseudo_link.asp">:link</a></td>
    <td>向未被访问的链接添加样式。</td>
    <td>1</td>
  </tr>
  <tr>
    <td><a href="/cssref/pr_pseudo_visited.asp">:visited</a></td>
    <td>向已被访问的链接添加样式。</td>
    <td>1</td>
  </tr>
  <tr>
    <td><a href="/cssref/pr_pseudo_first-child.asp">:first-child</a></td>
    <td>向元素的第一个子元素添加样式。</td>
    <td>2</td>
  </tr>
  <tr>
    <td><a href="/cssref/pr_pseudo_lang.asp">:lang</a></td>
    <td>向带有指定 lang 属性的元素添加样式。</td>
    <td>2</td>
  </tr>
</tbody></table>  
  
  自定义伪类
   q:lang(no) { font-size: 30px }  
   &lt;p&gt;文字&lt;q lang="no"&gt;段落中的引用的文字&lt;/q&gt;文字&lt;/p&gt;


## CSS 伪元素  
<table class="dataintable">
  <tbody><tr>
    <th style="width:30%;">属性</th>
    <th style="width:65%;">描述</th>
    <th style="width:5%;">CSS</th>
  </tr>
  <tr>
    <td><a href="/cssref/pr_pseudo_first-letter.asp">:first-letter</a></td>
    <td>向文本的第一个字母添加特殊样式。</td>
    <td>1</td>
  </tr>
  <tr>
    <td><a href="/cssref/pr_pseudo_first-line.asp">:first-line</a></td>
    <td>向文本的首行添加特殊样式。</td>
    <td>1</td>
  </tr>
  <tr>
    <td><a href="/cssref/pr_pseudo_before.asp">:before</a></td>
    <td>在元素之前添加内容。</td>
    <td>2</td>
  </tr>
  <tr>
    <td><a href="/cssref/pr_pseudo_after.asp">:after</a></td>
    <td>在元素之后添加内容。</td>
    <td>2</td>
  </tr>
</tbody></table>


# 框模型
<img src="http://www.w3school.com.cn/i/ct_boxmodel.gif"/>  

## 内边距
<table class="dataintable">
  <tbody><tr>
    <th>属性</th>
    <th>描述</th>
  </tr>
  <tr>
    <td><a href="/cssref/pr_padding.asp" title="CSS padding 属性">padding</a></td>
    <td>简写属性。作用是在一个声明中设置元素的所内边距属性。</td>
  </tr>
  <tr>
    <td><a href="/cssref/pr_padding-bottom.asp" title="CSS padding-bottom 属性">padding-bottom</a></td>
    <td>设置元素的下内边距。</td>
  </tr>
  <tr>
    <td><a href="/cssref/pr_padding-left.asp" title="CSS padding-left 属性">padding-left</a></td>
    <td>设置元素的左内边距。</td>
  </tr>
  <tr>
    <td><a href="/cssref/pr_padding-right.asp" title="CSS padding-right 属性">padding-right</a></td>
    <td>设置元素的右内边距。</td>
  </tr>
  <tr>
    <td><a href="/cssref/pr_padding-top.asp" title="CSS padding-top 属性">padding-top</a></td>
    <td>设置元素的上内边距。</td>
  </tr>
</tbody></table>  

## 边框

## 外边距
<table class="dataintable">
  <tbody><tr>
    <th>属性</th>
    <th>描述</th>
  </tr>
  <tr>
    <td><a href="/cssref/pr_margin.asp" title="CSS margin 属性">margin</a></td>
    <td>简写属性。在一个声明中设置所有外边距属性。</td>
  </tr>
  <tr>
    <td><a href="/cssref/pr_margin-bottom.asp" title="CSS margin-bottom 属性">margin-bottom</a></td>
    <td>设置元素的下外边距。</td>
  </tr>
  <tr>
    <td><a href="/cssref/pr_margin-left.asp" title="CSS margin-left 属性">margin-left</a></td>
    <td>设置元素的左外边距。</td>
  </tr>
  <tr>
    <td><a href="/cssref/pr_margin-right.asp" title="CSS margin-right 属性">margin-right</a></td>
    <td>设置元素的右外边距。</td>
  </tr>
  <tr>
    <td><a href="/cssref/pr_margin-top.asp" title="CSS margin-top 属性">margin-top</a></td>
    <td>设置元素的上外边距。</td>
  </tr>
</tbody></table>  

# 定位  

## 相对定位  
  设置为相对定位的元素框会偏移某个距离。元素仍然保持其未定位前的形状，它原本所占的空间仍保留。  
  position: relative;  
  
## 绝对定位
  绝对定位使元素的位置与文档流无关，因此不占据空间。

## 浮动  
  浮动的框可以向左或向右移动，直到它的外边缘碰到包含框或另一个浮动框的边框为止。
  
  
# 参考地址：http://www.w3school.com.cn/css/
