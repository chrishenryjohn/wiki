---
tags:
  - Markdown
---
# Markdown 基本语法

## 1. 标题

``` markdown
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```

## 2. 段落
创建段落，请使用空白行将一行或多行文本进行分隔。

## 3. 换行
在一行的末尾添加两个或多个空格，然后按回车键,即可创建一个换行(`<br>`)。
``` markdown
<br>
```

## 4. 强调

``` markdown
**粗体**
__粗体__
*斜体*
_斜体_
***粗体和斜体***
___粗体和斜体___
*__粗体和斜体__*
**_粗体和斜体_**
```

**粗体**  
__粗体__  
*斜体*  
_斜体_  
***粗体和斜体***  
___粗体和斜体___  
*__粗体和斜体__*  
**_粗体和斜体_**  


## 5. 引用
``` markdown
> 引用
>
>> 嵌套块引用
```

> 引用
>
>> 嵌套块引用


## 6. 列表
有序列表
``` markdown
1. 第一项
2. 第二项
3. 第三项
4. 第四项
```

1. 第一项
2. 第二项
3. 第三项
4. 第四项


无序列表
``` markdown
* 第一项
* 第二项
+ 第三项
- 第四项
```

* 第一项
* 第二项
+ 第三项
- 第四项


## 7. 代码
要将单词或短语表示为代码，请将其包裹在反引号 ( `) 中。
``` markdown
`print()` 函数
```

代码块
```` markdown
```python
print("Hello World")
```
````


## 8. 分隔线
``` markdown
***

---

_________________
```

***

---

_________________



## 9. 链接
``` markdown
[链接名称](链接地址)
这是一个链接 [Markdown语法](https://markdown.com.cn)。
```

这是一个链接 [Markdown语法](https://markdown.com.cn)。


## 10. 图片
``` markdown
![alt 属性文本](图片地址)

![alt 属性文本](图片地址 "可选标题")

对应的HTML代码：<img src="图片链接" alt="图片alt" title="图片title">
```


## 11. 转义字符
要显示原本用于格式化 Markdown 文档的字符，请在字符前面添加反斜杠字符 `\` 。


## 12. 表格
``` markdown
|  表头   | 表头  |
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |
```

|  表头   | 表头  |
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |

- `-:` 设置内容和标题栏居右对齐。
- `:-` 设置内容和标题栏居左对齐。
- `:-:` 设置内容和标题栏居中对齐。

``` markdown
| 左对齐 | 右对齐 | 居中对齐 |
| :-----| ----: | :----: |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |
```

| 左对齐 | 右对齐 | 居中对齐 |
| :-----| ----: | :----: |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |