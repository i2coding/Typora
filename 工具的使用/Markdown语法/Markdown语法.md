## 前期准备

首先需要一款可以记笔记的软件——推荐使用[Typora](https://so.csdn.net/so/search?q=Typora&spm=1001.2101.3001.7020): https://www.typora.io/
编写语法——推荐使用Markdown语法
详细请移步Markdown官方教程 https://markdown.com.cn/

## Markdown语法

Markdown 是一种轻量级标记语言，它允许人们使用易读易写的纯文本格式编写文档，Markdown文件的后缀名便是“.md”。

## 基本语法

这些是 John Gruber 的原始设计文档中列出的元素。所有 Markdown 应用程序都支持这些元素。

### 标题

```
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```

注意#和文字之间有空格

### 字体

```
**文字**   加粗
*文字*     斜体
***文字*** 加粗斜体
```

**加粗**
*斜体*
***加粗斜体***

### 引用

```
> 引用文字
>> 嵌套引用文字
12
```

> 学习java入门
>
> > Markdown语法学习

### 代码

```
要将单词或短语表示为代码，请将其包裹在反引号 (`) 中。
`代码`
12
hello world
```

### 分隔线

```
--- 分割线
```

------

### 列表

```
有序列表(.后有空格)
1. First item
2. Second item
3. Third item
无序列表(-后有空格)
- First item
- Second item
- Third item
```

1. A
2. B
   1. b1
   2. b2
3. C

- A
- B
  - b1
  - b2
- C

### 超链接

```
超链接Markdown语法代码：[超链接显示名](超链接地址 "超链接title")

对应的HTML代码：<a href="超链接地址" title="超链接title">超链接显示名</a>
```

[点击跳转到b站](https://www.bilibili.com/)

### 图片

```
插入图片Markdown语法代码：![图片alt](图片链接 "图片title")。

对应的HTML代码：<img src="图片链接" alt="图片alt" title="图片title">
```

![](../../assets/Markdown语法/98271773_p0_master1200.jpg)

扩展语法

> 这些元素通过添加额外的功能扩展了基本语法。但是，并非所有 Markdown 应用程序都支持这些元素。
> 您需要检查您的应用程序所使用的轻量级标记语言是否支持您要使用的扩展语法元素。如果没有，那么仍然有可能在Markdown处理器中启用扩展。

### 文字

```
~~删除文字~~
```

删除文字

### 代码块

```
​```语言
代码
​```
123
public class HelloWorld {
    public static void main(String []args) {
       System.out.println("Hello World!");
    }
}
```

### 表格

> 要添加表，请使用三个或多个连字符（—）创建每列的标题，并使用管道（|）分隔每列。您可以选择在表的任一端添加管道。

```
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |
```

| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |

```text
<table border="1px">
    <tr>
        <th>标题1</th>
        <th>标题2</th>
        <th>标题3</th>
    </tr>
    <tr>
      <td colspan="3">java入门</td>
    </tr>
    <tr>
      <td rowspan="2">1</td>
      <td>2</td>
      <td>3</td>
    </tr>
    <tr>
      <td>4</td>
      <td>5</td>
    </tr>
</table>
```

用html编写，可更加灵活

<table border="1px">
    <tr>
        <th>标题1</th>
        <th>标题2</th>
        <th>标题3</th>
    </tr>
    <tr>
      <td colspan="3">java入门</td>
    </tr>
    <tr>
      <td rowspan="2">1</td>
      <td>2</td>
      <td>3</td>
    </tr>
    <tr>
      <td>4</td>
      <td>5</td>
    </tr>
</table>

### 任务列表

```text
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
```

- [x] Write the press release 

- [ ] Update the website 
- [ ] Contact the media

### 使用 Emoji 表情

```
方式一：粘贴复制  相关网站https://emojipedia.org/
方式二：使用表情符号简码  相关网站  https://gist.github.com/rxaviers/7360908
去露营了！ :tent: 很快回来。
真好笑！ :joy:
```

去露营了！ ⛺️ 很快回来。
真好笑！ 😂标题