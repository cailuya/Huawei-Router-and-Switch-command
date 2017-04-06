# 华为交换机与路由器命令汇总

GitHub 使用教程 [怎样使用 GitHub？](https://www.zhihu.com/question/20070065)
## 编写规范
本文档采用 Markdown 编写，在后面会有 Markdown 的编写教程。
文档写作使用文本编码为 UTF-8，回车为 linux 标准的 `LF`，不限制文本编辑器的使用，但是推荐使用 [VScode](https://code.visualstudio.com/)

### 命令行格式约定

<table>
<thead>
<tr>
<th>格式 </th>
<th>意义</th>
</tr>
</thead>

<tbody>
<tr>
<td><em>斜体</em></td>
<td>命令行参数（命令中必须由实际值进行替代的部分）采用斜体表示。</td>
</tr>
<tr>
<td><code>[ ]</code></td>
<td>表示用“[ ]”括起来的部分在命令配置时是可选的。</td>
</tr>
<tr>
<td><code>{ x | y | ... }</code></td>
<td>表示从两个或多个选项中选取一个。</td>
</tr>
<tr>
<td><code>[ x | y | ... ]</code></td>
<td>表示从两个或多个选项中选取一个或者不选。</td>
</tr>
<tr>
<td><code>{ x | y | ... } *</code></td>
<td>表示从两个或多个选项中选取多个，最少选取一个，最多选取所有选项。</td>
</tr>
<tr>
<td><code>[ x | y | ... ] *</code></td>
<td>表示从两个或多个选项中选取多个或者不选。</td>
</tr>
<tr>
<td><code>&amp;&lt;1-n&gt;</code></td>
<td>表示符号&amp;前面的参数可以重复 1 ～ n 次。</td>
</tr>
<tr>
<td><code>#</code></td>
<td>由“#”开始的行表示为注释行。</td>
</tr>
<tr>
<td>---</td>
<td>---</td>
</tr>
</tbody>
</table>

## Markdown 语法
本文档不需要太过复杂，只需要记住下面几种标记用法即可。如果有兴趣的话可以进一步学习：[
献给写作者的 Markdown 新手指南](http://www.jianshu.com/p/q81RER)
### 标题

```
# 第一级标题 
## 第二级标题     
###### 第六级标题 
```

### 斜体
```
*斜体* 
```

效果：*斜体* 
### 粗体
```
**粗体**
```

效果：**粗体**

### 代码引用

```
`单行引用`

```
多行引用只好用图片来演示：

![](https://img.sairoa.me/999001.png)

