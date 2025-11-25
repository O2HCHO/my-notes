# Markdown 终极语法指南 (The Ultimate Markdown Cheatsheet)

欢迎来到我的个人知识库！这是一个全面的 Markdown 语法参考。它涵盖了从基础到高级的各种语法，特别包含了 GitHub Flavored Markdown (GFM) 的常用功能以及 LaTeX 数学公式的用法。

---

## 目录 (Table of Contents)

- [Markdown 终极语法指南 (The Ultimate Markdown Cheatsheet)](#markdown-终极语法指南-the-ultimate-markdown-cheatsheet)
  - [目录 (Table of Contents)](#目录-table-of-contents)
  - [1. 标题 (Headings)](#1-标题-headings)
  - [2. 文本格式化 (Text Formatting)](#2-文本格式化-text-formatting)
  - [3. 段落与换行 (Paragraphs \& Line Breaks)](#3-段落与换行-paragraphs--line-breaks)
  - [4. 引用 (Blockquotes)](#4-引用-blockquotes)
  - [5. 列表 (Lists)](#5-列表-lists)
    - [无序列表 (Unordered Lists)](#无序列表-unordered-lists)
    - [有序列表 (Ordered Lists)](#有序列表-ordered-lists)
  - [6. 代码 (Code)](#6-代码-code)
    - [行内代码 (Inline Code)](#行内代码-inline-code)
    - [代码块 (Fenced Code Blocks)](#代码块-fenced-code-blocks)
  - [7. 链接 (Links)](#7-链接-links)
  - [8. 图片 (Images)](#8-图片-images)
  - [9. 水平分割线 (Horizontal Rules)](#9-水平分割线-horizontal-rules)
  - [10. 表格 (Tables)](#10-表格-tables)
  - [11. 任务列表 (Task Lists)](#11-任务列表-task-lists)
  - [12. LaTeX 数学公式 (Mathematical Formulas)](#12-latex-数学公式-mathematical-formulas)
    - [行内公式 (Inline Formulas)](#行内公式-inline-formulas)
    - [块级公式 (Block Formulas)](#块级公式-block-formulas)
  - [13. 高级技巧 (Advanced Tips)](#13-高级技巧-advanced-tips)
    - [转义字符 (Escaping Characters)](#转义字符-escaping-characters)
    - [嵌入 HTML](#嵌入-html)
  - [14. 彩色提示框 (Admonitions)](#14-彩色提示框-admonitions)
    - [基础用法](#基础用法)
    - [更多类型展示](#更多类型展示)
      - [1. 警告 (Warning)](#1-警告-warning)
      - [2. 成功 (Success)](#2-成功-success)
      - [3. 小贴士 (Tip)](#3-小贴士-tip)
      - [4. 错误/失败 (Failure)](#4-错误失败-failure)
      - [5. 折叠样式 (Collapsible)](#5-折叠样式-collapsible)

---

## 1. 标题 (Headings)

使用 `#` 号来创建标题，`#` 的数量代表标题的级别。

```markdown
# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题
```

## 2. 文本格式化 (Text Formatting)

| 样式 | 语法 | 示例 |
| :--- | :--- | :--- |
| **粗体** | `**文字**` 或 `__文字__` | **Hello, World!** |
| *斜体* | `*文字*` 或 `_文字_` | *Hello, World!* |
| ***粗斜体*** | `***文字***` 或 `___文字___` | ***Hello, World!*** |
| ~~删除线~~ | `~~文字~~` | ~~Goodbye, World!~~ |

如下：
```
| 样式 | 语法 | 示例 |
| :--- | :--- | :--- |
| **粗体** | `**文字**` 或 `__文字__` | **Hello, World!** |
| *斜体* | `*文字*` 或 `_文字_` | *Hello, World!* |
| ***粗斜体*** | `***文字***` 或 `___文字___` | ***Hello, World!*** |
| ~~删除线~~ | `~~文字~~` | ~~Goodbye, World!~~ |
```

---

## 3. 段落与换行 (Paragraphs & Line Breaks)

- **新段落**: 在两段文字之间留一个空行。

- **强制换行**: 在一行的末尾输入两个或更多的空格，然后按回车。  
这行文字的末尾有两个空格，所以会强制换行。

---

## 4. 引用 (Blockquotes)
使用 `>` 符号来创建引用块。可以进行嵌套。

> 这是一个引用。
>
> > 这是一个嵌套的引用。
> >
> > > 嵌套可以有很多层。

---

## 5. 列表 (Lists)

### 无序列表 (Unordered Lists)
使用 `*`, `+`, 或 `-` 来创建无序列表。(他们是等价的)

- 列表项 A
  - 嵌套列表项 A1
  - 嵌套列表项 A2
* 列表项 B
+ 列表项 C

$\int_{a}^{b}a^n *b$

### 有序列表 (Ordered Lists)
使用数字加点 `.` 来创建有序列表。

1. 第一步
2. 第二步
   1. 步骤 2.1
   2. 步骤 2.2
3. 第三步

## 6. 代码 (Code)

### 行内代码 (Inline Code)
使用反引号 `` ` `` 来包裹代码。例如, `console.log('Hello');` 是一个行内代码。

### 代码块 (Fenced Code Blocks)
使用三个反引号 `` ``` `` 来创建代码块，并可以在后面指定语言以获得语法高亮。

```python
# 这是一个 Python 代码块
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)

print(factorial(5))
```
```JavaScript
// 这是一个 JavaScript 代码块
const greet = (name) => {
  console.log(`Hello, ${name}!`);
};

greet('GitHub');
```

## 7. 链接 (Links)

- **基本链接**: `[链接文字](URL)`
  [访问谷歌](https://www.google.com)

- **带标题的链接**: `[链接文字](URL "悬停时显示的文字")`
  [GitHub官网](https://github.com/ "最好的代码托管平台")

---

## 8. 图片 (Images)
语法与链接类似，只是在前面加一个感叹号 `!`。

`![文字](图片URL)`

![HCHO](images/HCHO.jpg)

---

## 9. 水平分割线 (Horizontal Rules)
在一行中使用三个或更多的 `*`, `-`, 或 `_` 来创建分割线。

***
---
___

---

## 10. 表格 (Tables)
使用管道符 `|` 和连字符 `-` 来创建表格。使用冒号 `:` 控制对齐方式。

| 左对齐 | 居中对齐 | 右对齐 |
| :--- | :---: | ---: |
| 苹果 | 香蕉 | 橙子 |
| 笔记本 | 显示器 | 鼠标 |
| Markdown | LaTeX | Git |

---


## 11. 任务列表 (Task Lists)
在列表项前加上 `[ ]` 或 `[x]` 来创建任务列表。

- [x] 完成 Markdown 语法学习
- [x] 将笔记上传到 GitHub
- [ ] 学习 Git 的更多高级用法

---

## 12. LaTeX 数学公式 (Mathematical Formulas)
这是在技术笔记中非常有用的功能。GitHub 的 Markdown 渲染器支持 MathJax。

### 行内公式 (Inline Formulas)
使用一对美元符号 `$` 包裹 LaTeX 代码。

**示例**:
爱因斯坦的质能方程是$E=mc^2$。一个简单的二次方程是 $ax^2 + bx + c = 0$。

### 块级公式 (Block Formulas)
使用两对美元符号 `$$` 包裹 LaTeX 代码，公式会居中并单独成行。

**示例**:
著名的欧拉恒等式：

$$
e^{i\pi} + 1 = 0
$$

高斯积分：

$$
\int_{-\infty}^{\infty} e^{-x^2} \,dx = \sqrt{\pi}
$$

**常用 LaTeX 语法**:

| 描述 | 语法 | 渲染效果 |
| :--- | :--- | :--- |
| 分数 | `\frac{a}{b}` | $\frac{a}{b}$ |
| 求和 | `\sum_{i=1}^{n}` | $\sum_{i=1}^{n}$ |
| 积分 | `\int_{a}^{b}` | $\int_{a}^{b}$ |
| 极限 | `\lim_{x \to \infty}` | $\lim_{x \to \infty}$ |
| 希腊字母 | `\alpha, \beta, \gamma` | $\alpha, \beta, \gamma$ |
| 上标/下标 | `x^2`, `y_{10}` | $x^2$, $y_{10}$ |

**更多LaTex语法：**

| 含义 (Meaning) | LaTeX 命令 (Command) | 显示效果 (Rendered) |
| :--- | :---: | :---: |
| **逻辑连词 (Logical Connectives)** | | |
| 与 (and) | `\land` 或 `\wedge` | $\land, \wedge$ |
| 或 (or) | `\lor` 或 `\vee` | $\lor, \vee$ |
| 非 (not) | `\neg` | $\neg$ |
| 蕴含 (implies) | `\rightarrow` | $\rightarrow$ |
| 逻辑蕴含 (logical implication) | `\Rightarrow` | $\Rightarrow$ |
| 当且仅当 (if and only if, iff) | `\leftrightarrow` | $\leftrightarrow$ |
| 逻辑等价 (logical equivalence) | `\Leftrightarrow` | $\Leftrightarrow$ |
| 否定|`\neg`|$\neg$|
| **量词 (Quantifiers)** | | |
| 对所有 (for all) | `\forall` | $\forall$ |
| 存在 (there exists) | `\exists` | $\exists$ |
| **集合论 (Set Theory)** | | |
| 属于 (element of) | `\in` | $\in$ |
| 不属于 (not an element of) | `\notin` | $\notin$ |
| 子集 (subset of) | `\subset` | $\subset$ |
| 子集或等于 (subset or equal to) | `\subseteq` | $\subseteq$ |
| 父集 (superset of) | `\supset` | $\supset$ |
| 父集或等于 (superset or equal to) | `\supseteq` | $\supseteq$ |
| 并集 (union) | `\cup` | $\cup$ |
| 交集 (intersection) | `\cap` | $\cap$ |
| 空集 (empty set) | `\emptyset` | $\emptyset$ |
| **证明与推论 (Proof and Inference)** | | |
| 所以 (therefore) | `\therefore` | $\therefore$ |
| 因为 (because) | `\because` | $\because$ |
| Tautology (顶) | `\top` | $\top$ |
| Contradiction (底) | `\bot` | $\bot$ |
| 断言/推导出 (turnstile) | `\vdash` | $\vdash$ |

**希腊字母 (Greek Letters)**

**注意：** 大写希腊字母的命令通常是首字母大写，例如 `\gamma` (小写 $\gamma$) 和 `\Gamma` (大写 $\Gamma$)。

| 小写字母 | LaTeX 命令 | 大写字母 | LaTeX 命令 |
| :---: | :---: | :---: | :---: |
| $\alpha$ | `\alpha` | $A$ | `A` (就是A) |
| $\beta$ | `\beta` | $B$ | `B` (就是B) |
| $\gamma$ | `\gamma` | $\Gamma$ | `\Gamma` |
| $\delta$ | `\delta` | $\Delta$ | `\Delta` |
| $\epsilon$ | `\epsilon` | $E$ | `E` (就是E) |
| $\zeta$ | `\zeta` | $Z$ | `Z` (就是Z) |
| $\eta$ | `\eta` | $H$ | `H` (就是H) |
| $\theta$ | `\theta` | $\Theta$ | `\Theta` |
| $\iota$ | `\iota` | $I$ | `I` (就是I) |
| $\kappa$ | `\kappa` | $K$ | `K` (就是K) |
| $\lambda$ | `\lambda` | $\Lambda$ | `\Lambda` |
| $\mu$ | `\mu` | $M$ | `M` (就是M) |
| $\nu$ | `\nu` | $N$ | `N` (就是N) |
| $\xi$ | `\xi` | $\Xi$ | `\Xi` |
| $o$ | `o` | $O$ | `O` (就是o) |
| $\pi$ | `\pi` | $\Pi$ | `\Pi` |
| $\rho$ | `\rho` | $P$ | `P` (就是P) |
| $\sigma$ | `\sigma` | $\Sigma$ | `\Sigma` |
| $\tau$ | `\tau` | $T$ | `T` (就是T) |
| $\upsilon$ | `\upsilon` | $\Upsilon$ | `\Upsilon` |
| $\phi$ | `\phi` | $\Phi$ | `\Phi` |
| $\chi$ | `\chi` | $X$ | `X` (就是X) |
| $\psi$ | `\psi` | $\Psi$ | `\Psi` |
| $\omega$ | `\omega` | $\Omega$ | `\Omega` |

**特殊的变体字母：**

| 变体 | LaTeX 命令 |
| :---: | :---: |
| $\varepsilon$ | `\varepsilon` |
| $\vartheta$ | `\vartheta` |
| $\varpi$ | `\varpi` |
| $\varrho$ | `\varrho` |
| $\varsigma$ | `\varsigma` |
| $\varphi$ | `\varphi` |

---

**基本运算符 (Basic Operators)**

| 含义 | LaTeX 命令 | 渲染效果 |
| :--- | :---: | :---: |
| 加号 | `+` | $+$ |
| 减号 | `-` | $-$ |
| 乘号 (点) | `\cdot` | $\cdot$ |
| 乘号 (叉) | `\times` | $\times$ |
| 除号 (分数线) | `\frac{a}{b}` | $\frac{a}{b}$ |
| 除号 (横线) | `\div` | $\div$ |
| 正负号 | `\pm` | $\pm$ |
| 负正号 | `\mp` | $\mp$ |
| 等于号 | `=` | $=$ |
| 不等于 | `\ne` 或 `\neq` | $\ne$ |
| 约等于 | `\approx` | $\approx$ |
| 大于 | `>` | $>$ |
| 小于 | `<` | $<$ |
| 大于等于 | `\ge` 或 `\geq` | $\ge$ |
| 小于等于 | `\le` 或 `\leq` | $\le$ |

---

## 13. 高级技巧 (Advanced Tips)

### 转义字符 (Escaping Characters)
如果你想显示 Markdown 中的特殊字符（如 `*` 或 `#`），可以在它们前面加上反斜杠 `\`。

我想显示一个星号 \*，而不是让它变成斜体。

### 嵌入 HTML
Markdown 支持直接写入 HTML 代码，这给了你更大的灵活性。

**示例**:
使用 `<u>` 标签实现<u>下划线效果</u>。

使用 `<details>` 和 `<summary>` 创建一个可折叠的内容区域。
<details>
  <summary>点击这里展开/折叠</summary>
  这里是可以被隐藏和显示的内容捏^-^。
</details>

## 14. 彩色提示框 (Admonitions)

这是我们新安装的 `mdbook-admonish` 插件的效果展示。它可以生成醒目的彩色区块，非常适合用来写提示、警告或补充说明。

### 基础用法

**语法代码**：

````markdown

```admonish note "这是标题"
这里写提示框的内容。支持 **Markdown** 语法。
```
````

**渲染效果**：

```admonish note "这是标题"
这里写提示框的内容。支持 **Markdown** 语法。

```

---

### 更多类型展示

#### 1. 警告 (Warning)
```admonish warning "注意安全"
这是一条警告信息！请务必小心操作。
```

#### 2. 成功 (Success)
```admonish success
**恭喜！** 你的插件配置完美运行。如果不写标题，默认为 "Success"。
```

#### 3. 小贴士 (Tip)
```admonish tip "小技巧"
这是一个有用的小知识点。
```

#### 4. 错误/失败 (Failure)
```admonish failure "运行错误"
哎呀，程序崩溃了。
```

#### 5. 折叠样式 (Collapsible)
如果不希望内容占用太多空间，可以设置为默认折叠：

````admonish example "点击展开查看详细代码"

```python
def hello():
    print("Hello Admonish!")
```
````