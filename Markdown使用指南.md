# Markdown使用指南

<div></div>

## 1.多级标题

总共有六级标题,分别为: 
```
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题 
###### 六级标题 
```
PS：#和标题名称之间有一个空格

<div id="article">
</div>




## 2.列表

### 2.1无序列表

 ```
  - 列表内容1
  
  + 列表内容2
  
  * 列表内容3
 ```

### 2.2有序列表

 ```
   1. 列表内容
   2. 列表内容
 ```

<div></div>

## 3.引用

```
> this is a test
> 引用的内容
```

<div style="page-break-after:always;height:200px" ></div>

## 4.字体设置

### 格式

```
<font face="黑体">黑体字</font>
<font face="微软雅黑">微软雅黑</font>
<font face="STCAIYUN">华文彩云</font>
<font color=blue>蓝色</font>
<font color=#008000>绿色</font>
<font color=Red>红色</font>
<font size=5>尺寸</font>
<font face="黑体" color=green size=5>黑体，绿色，尺寸为5（任意内容）</font>
```

### 粗体

```
**需要加粗的文字**
__需要加粗的文字__
```

### 斜体

```
*需要斜体的问题*
_需要斜体的问题_
```

### 加粗并斜体

```
*** 需要加粗和斜体的文字***
```
### 设置背景颜色

利用table实现文字背景颜色加载

<table><tr><td bgcolor=blue><font color=Red>颜色背景</font></td></tr></table>

### 全家福版

```
<table><tr><td bgcolor=gray><font face="黑体" color=green size=5>***黑体，绿色，尺寸为5（任意内容）***</font></td></tr></table>
```


<div style="page-break-after:always"></div>

## 5.分割线

```
***或---代表分割线
```

<div style="page-break-after:always"></div>

## 6.代码框和代码块

代码框：

```
`代码框内容`
```

代码块：

```
	``` 代码块所用编辑的语言名称
    代码块内容
'   ```
```

<div style="page-break-after:always"></div>

## 7.列表


三行四列的表格为例;
```
| 姓名 | 年龄 | 性别 |
| ---- | ---- | ---- |
| 张三 | 35 | 男 |
| 李四 | 77 | 女 |
```

<div style="page-break-after:always"></div>

## 8.可选框

```
- [ ] 可选框后的内容
- [x] 可选框后的内容
```


<div style="page-break-after:always"></div>

## 9.插入分页符

```
<div style="page-break-after:always"></div>
```

