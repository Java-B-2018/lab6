# lab6
学习递归的使用
## 问题一：字符串倒序（无需使用递归）
### 问题描述：给定一个字符串，将其中的单词进行倒序打印
### 示例输入：
```
the sky is blue
```
### 示例输出：
```
blue is sky the
```
> 注意: 单个单词不需要进行倒序。

## 问题二：切钢管问题
### 背景 
某公司生产长钢管，会将钢条切断，变成不同长度，然后去售卖。不同长度的钢管的售价是不一样的，它们并不是完全按照比例来，比如2米的钢管售价要比3米的钢管售价要少，但是并不是2比3的比例。钢管的长度售价表如下：

|长度|1|2|3|4|5|6|7|8|9|10|
|-|-|-|-|-|-|-|-|-|-|-
|售价|1|5|8|9|10|17|17|20|24|28|

### 问题
对于给定的任意长度的钢管，要如何切割，切割成多长的几条，才能让收益最高呢？
### 示例输入（钢管长度）
```
9
```
### 示例输出（第一行打印最大收益，第二行打印切割后每段钢管的长度）
```
25
3 6
```
### 思考（无须解答）
使用递归求解是否不妥？如果钢管长度非常长可能导致什么后果？如何优化？
## DeadLine与上传
在```11月11日23:59```之前将整个工程打包上传至ftp对应目录下。

