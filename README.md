
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

## CSS 伪元素

## 参考地址：http://www.w3school.com.cn/css/css_selector_type.asp

# 框模型


# 背景和边框


# 文本效果


# 2D/3D 转换


# 动画


# 多列布局


# 用户界面

