# Markdown特殊字符转义

环境：
Markdown

------

## 前言

Markdown 是 2004 年由 John Gruberis 设计和开发的纯文本格式的语法，是一种可以使用普通文本编辑器编写的标记语言，通过简单的标记语法，可以使普通文本内容具有一定的格式。

[MarkDown中文文档](https://markdown-zh.readthedocs.io/en/latest/)

```
Markdown自身是有格式要求的，例如# * < 等字符都是格式化字符，如果我们真的要用这些字符该怎么处理呢？
1
```

## 1.反斜杠忽略Markdown格式(推荐)

通过在Markdown字符前使用\来忽略（或转义）Markdown格式。

Markdown允许您使用反斜杠转义来生成文字字符，否则这些字符在Markdown的格式化语法中具有特殊含义。 例如，如果您想用文字星号包围一个单词，则可以在星号之前使用反斜杠，如下所示：

```
\*literal asterisks\*
1
```

Markdown为以下字符提供反斜杠转义：

| 转义字符 | 英文名称            | 中文名称       |
| -------- | ------------------- | -------------- |
| \        | backslash           | 反斜杠         |
| `        | backtick            | 反引号         |
| *        | asterisk            | 星号           |
| _        | underscore          | 下划线         |
| {}       | curly braces        | 大括号         |
| []       | square brackets     | 方括号         |
| ()       | parentheses         | 括弧           |
| #        | hash mark           | 井号           |
| +        | plus sign           | 加号           |
| -        | minus sign (hyphen) | 减号（连字符） |
| .        | dot                 | 小数点         |
| !        | exclamation mark    | 感叹号         |

## 2.HTML *标签*

```
<em>*literal asterisks*</em>
1
```

## 3.Html ASCII转义

示例

```
&lt;test>
1
```

常用html转义字符

| 字符                           | 十进制 | 转义字符 |
| ------------------------------ | ------ | -------- |
| "                              | &#34;  | &quot;   |
| &                              | &#38;  | &amp;    |
| <                              | &#60;  | &lt;     |
| >                              | &#62;  | &gt;     |
| 不断开空格(non-breaking space) | &#160; | &nbsp;   |

------

Reference：
1.https://help.github.com/articles/basic-writing-and-formatting-syntax/
2.https://daringfireball.net/projects/markdown/syntax
3.http://tool.oschina.net/commons?type=2

