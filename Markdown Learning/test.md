# Hello World!

## 二级标题

### 三级标题

---

### 段落
写完一个段落要空行。

每写完都要空行。

---

### 分割线

三条横线表示分割线。

---

### 加粗、斜体、删除线和高亮

**重点加粗**

*斜体*

~~删除线~~

**Markdown Preview Enhanced拓展功能：**  ==高亮==

---

### 列表

* 无序列表
  * 嵌套无序列表
  * 嵌套无序列表
* 无序列表
* 无序列表

1. 有序列表1
2. 有序列表2
   1. 嵌套有序列表1
   2. 嵌套有序列表2
3. 有序列表3

**Markdown Preview Enhanced 拓展功能：**

任务列表：

- [ ] 未完成的事 1
- [ ] 未完成的事 2
- [x] 已完成的事 3
- [x] 已完成的事 4
- [ ] 未完成是事 5

---

### 引用和代码

引用文本：

> 引用别人说的话

这是 `行内代码` 的语法。

代码块语法：

``` C
printf("Hello, world!");
```
**Markdown Preview Enhanced 拓展功能：**

代码的行数显示：

``` C {.line-numbers}
viod P(int x){
    printf("You print %d", x)
}
```
---

### 超链接和图片

[超链接名称](链接地址)

![图片提示语](图片地址)

**例如：**

[AcFun](www.acfun.cn)

![桶帅](https://imgs.aixifan.com/newUpload/550318_2764be531b4544cb8d41dba2e240b47e.gif)

**或者使用本地相对地址：**

[超链接测试](超链接.md)

![蕉哥哥](images/jiao.jpg)

**Paste Image 拓展功能：**

Ctrl + Alt + V : 自动把复制的图片保存到当前目录下并粘贴到文件中

![qyqx](images/2022-07-25-12-46-47.png)

---

### 表格

| 表头 | 表头 |
| ---- | ---- |
| 内容 | 内容 |
| 内容 | 内容 |

**Markdown Preview Enhanced 拓展语法：**

**==不知道为什么用不了合并单元格!!!==**

| 表头 | 表头 |
| ---- | ---- |
| 内容 | 内容 |
| >    | 内容 |

| 表头 | 表头 |
| ---- | ---- |
| 内容 | 内容 |
| ^    | 内容 |

---

### 注释

<!-- 注释看不见 -->

<!-- 多行注释 
有点丑 -->

VS Code 会在每次修改代码后重新渲染一次。如果有很多的数学公式，渲染会很慢。

建议：
1. 分成多个文件，避免单文件过大
2. 将暂时不看的部分注释掉，加快渲染速度

---

### 数学公式支持

行内公式：

单位圆: $x^2+y^2=1$

公式块：

$$
\begin{cases}
x=\rho\cos\theta \\
y=\rho\sin\theta \\
\end{cases}
$$

**==只能说，细节有点复杂，日后再学！==**

---

### 云端存储
