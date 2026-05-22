# Answer of Homework

# Author: Caesar James LEE

# Date: Thursday, May 14, 2026

---

# 一、奇偶

1. $f(x) = {x}^{3} - \sin {x}$: `奇`
2. $f(x) = {x}^{2} \cos {x}$: `偶`
3. $f(x) = \frac {x} {1 + {x}^{2}}$: ~~偶~~
    > [!CAUTION]
    > **奇**
    $$
        \begin{align*}
            f(x) &= \frac {x} {1 + {x}^{2}} \\
            f(-x) &= \frac {-x} {1 + {-x}^{2}} \\
            f(-x) &= -\frac {x} {1 + {x}^{2}} \\
            \because f(x) &= -f(-x) \\
            \therefore f(x) &\text{ is an odd function}
        \end{align*}
    $$
4. $f(x) = {x}^{4} + 3{x}^{2} - 5$: `偶`
5. $f(x) = 2{x}^{3} + {x}^{2}$: `双非`
6. $f(x) = \frac {{e}^{x} + {e}^{-x}} {2}$: `偶`
7. $f(x) = \sqrt [3] {x}$: ~~双非~~
    > [!CAUTION]
    > **奇**
    $$
    \begin{align*}
        f(x) &= \sqrt [3] {x} \\
        f(-x) &= \sqrt [3] {-x} \\
        f(-x) &= -\sqrt [3] {x} \\
        \because f(x) &= -f(x) \\
        \therefore f(x) &\text { is an odd function}
    \end{align*}
    $$
8. $f(x) = {x}^{2} + \sin {x}$: 双非

---

# 二、週期性

1. $y = \sin {2x}$: $\pi$
2. $y = \cos {\frac {1} {2} x}$: $4 \pi$
3. $y = \tan {\frac {1} {3} x}$: $3 \pi$
4. $y = \sin {3x} + \cos {2x}$: $2 \pi$
5. $y = \sin {\frac {1} {2} x} + \tan {\frac {1} {4} x}$: $4 \pi$

---

# 三、有界性

1. $y = \log_{3} {x}$ in $[3, 9]$: `有`， $y \in [1, 2]$
2. $y = \frac {1} {1 + {x}^{2}}$ in $\mathbb {R}$: `有`， $y \in (0, \infty)$
3. $y = \frac {1} {x}$ in $(1, 2)$: ~~无~~， $y \in (\frac {1} {4}, \frac {1} {2})$
    > [!CAUTION]
    > **有**
    > 
    > 只要所求值域無 () 或 $\infty$ 皆有界
4. $y = \frac {1} {x}$ in $(0, 1)$: `无`， $y \in (1, \infty)$
5. $y = {x}^{2} - 3x$ in $[-1, 2]$: `有`， $y \in [-\frac {9} {4}, 4]$

---

# 四、單調性

1. $f(x)$ is **monotone increasing** in $\mathbb {R}$, compare $f(-2)$ and $f(1)$
$$
    \begin {aligned}
        \because -2 &< 1 \\
        \therefore f(-2) &< f(1)
    \end {aligned}
$$

2. $f(x)$ is **monotone decreasing** in $(0, \infty)$, compare $f(3)$ and $f(2)$
$$
    \begin {aligned}
        \because 2 &< 3 \\
        \therefore f(2) &> f(3)
    \end {aligned}
$$

3. $f(x)$ is **monotone increasing** in $(-\infty, 0)$, compare $f(-5)$ and $f(-3)$
$$
    \begin {align*}
        \because -5 &< -3 \\
        \therefore f(-5) &< f(-3)
    \end {align*}
$$
