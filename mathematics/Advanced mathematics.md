# 高等数学学习笔记（Advanced mathematics notes）

这是我的高等数学学习笔记，用于方便的查询我学习的进度（以及学一下latex语法） ~~脑子一抽想试试用markdown来记数学笔记，希望不会又不填坑~~ 

---

## 目录（Table of Contents）
- [高等数学学习笔记（Advanced mathematics notes）](#高等数学学习笔记advanced-mathematics-notes)
  - [目录（Table of Contents）](#目录table-of-contents)
  - [一.零基础知识](#一零基础知识)
    - [1.基本逻辑](#1基本逻辑)
    - [2.数学归纳法](#2数学归纳法)
  - [二.函数极限与连续](#二函数极限与连续)
    - [1.定义](#1定义)


---

## 一.零基础知识

*一些基础知识防止上大学上成傻逼了都忘了*

### 1.基本逻辑

~~*歪日真有点记不清了*~~

若A $\Rightarrow$ B,则称A是B的充分条件，B是A的必要条件  
若A $\Leftrightarrow$ B,则称A是B的充要条件  
若A $\neq$ B,则称A是B的无关条件  

$$A\Rightarrow B,则\neg B \Rightarrow \neg A$$  
$$\neg (A \cap B)=\neg A \cup \neg B$$
$$\neg (A \cup B)=\neg A \cap \neg B$$

### 2.数学归纳法

设T(n)是关于自然数n的命题，  
1. T(1)成立
2. 设T(k)(k>=1)成立
3. 证明T(k+1)成立  

 则T(n)成立

## 二.函数极限与连续

### 1.定义

**1.函数极限的 ε-δ 定义**


函数 $f(x)$ 在 $x$ 趋近于 $c$ 时的极限是 $L$，记作：

$$
\lim_{x \to c} f(x) = L
$$

这直观地表示：当 $x$ 的值“足够接近”点 $c$ 时（但不等于 $c$），函数 $f(x)$ 的值就可以“任意地接近”值 $L$。

---

**2. 形式化定义：**

设函数 $f$ 在点 $c$ 的一个去心邻域内有定义。极限 $\lim_{x \to c} f(x) = L$ 成立，当且仅当：

对于**任意**给定的正数 $\epsilon$（无论它有多小），**总存在**一个正数 $\delta$，使得对于**所有**满足 $0 < |x - c| < \delta$ 的 $x$，都有 $|f(x) - L| < \epsilon$ 成立。

用逻辑量词的语言来表达，即：

$$
\forall \epsilon > 0, \exists \delta > 0 \text{ 当 }  \forall x, (0 < |x - x_{0}| < \delta \rightarrow |f(x) - L| < \epsilon)
$$




