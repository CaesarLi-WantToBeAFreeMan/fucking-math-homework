# Title: Odd Even Properties of Functions

# Author: Caesar James LEE

# Date: Friday, May 29, 2026

---

## Definitions

| property | definition | common examples |
| :-: | :-: | :-: |
| `odd` | $f(-x) = -f(x)$ | ${x}^{n}$ $(n \text{ is odd})$, $\frac {1} {x^n}$ $(n \text{ is odd})$, $\sin {x}$, $\tan {x}$, $\cot {x}$, $\arcsin {x}$, $\arctan {x}$, $\sinh {x}$, $\operatorname {sgn}(x)$ |
| `even` | $f(-x) = f(x)$ | ${x}^{n}$ $(n \text{ is even})$, $\frac {1} {x^n}$ $(n \text{ is even})$, $\cos {x}$, $\sec {x}$, $\lvert x \rvert$, $\cosh {x}$ |
| `neither odd nor even` | functions that are neither odd nor even | ${a}^{x}$, $\log_{a} {x}$, $x + 1$, ${e}^{x}$, $\sqrt{x}$ |

> [!TIP]
> `sign function`:
> $$
>   \text {sgn} ({x}) = 
>   \begin{cases}
>       1, & x > 0\\
>       0, & x = 0\\
>       -1, & x < 0
>   \end{cases}
> $$
>
>> `odd/even`: `odd`
>>
>> `domain`: {-1, 0, 1}
>>
>> `range`: $\mathbb {R}$
>
> `hyperbolic sine`:
> $$
>   \sinh {x} = \frac {{e}^{x} - {e}^{-x}} {2}
> $$
>
>> `odd/even`: `odd`
>>
>> `domain`: $\mathbb {R}$
>>
>> `range`: $\mathbb {R}$
>>
>
> `hyperbolic cosine`:
> $$
>   \cosh {x} = \frac {{e}^{x} + {e}^{-x}} {2}
> $$
>
>> `odd/even`: `even`
>>
>> `domain`: $\mathbb {R}
>>
>> `range`: $[1, \infty)$

---

## Calculations

### Between `Odd` and `Even` functions

| operation | result | example |
| :-: | :-: | :-: |
| **odd** $\pm$ **odd** | **odd** | ${x}^{3} + \sin {x}$ |
| **even** $\pm$ **even** | **even** | ${x}^{2} + \cos {x}$ |
| **odd** $\pm$ **even** | **neither** | $x + {x}^{2}$ |
| **odd** $\times$ **odd** | **even** | $x \sin {x}$ |
| **even** $\times$ **even** | **even** | ${x}^{2} \cos {x}$ |
| **odd** $\times$ **even** | **odd** | ${x}^{3} \cos {x}$ |
| **odd** $\div$ **odd** | **even** | $\frac {\sin {x}} {x}$ |
| **even** $\div$ **even** | **even** | $\frac {{x}^{2}} {\lvert x \rvert}$ |
| **odd** $\div$ **even** | **odd** | $\frac {x}{{x}^{2} + 1}$ |
| **even** $\div$ **odd** | **odd** | $\frac {{x}^{2}} {x}$ |

> [!TIP]
> You can think of:
> 
> `odd`: sign **flip** `-`
>
> `even`: sign stays the **same** `+`


### Nested (Composite) Functions

> [!IMPORTANT]
> `f(x)`: **outer** function
>
> `g(x)`: **inner** function

| outer | inner | result | example |
| :-: | :-: | :-: | :-: |
| **odd** | **odd** | **odd** | $\sin({x}^{3})$ |
| **odd** | **even** | **even** | $\sin({x}^{2})$ |
| **even** | **odd** | **even** | $\cos({x}^{3})$ |
| **even** | **even** | **even** | $\cos({x}^{2})$ |
| **odd** | **neither** | usually **neither** | $\sin({x + 1})$ |
| **even** | **neither** | usually **neither** | $\cos({x + 1})$ |
| **neither** | **odd** | may be **odd**/**even**/**neither** | $e^{{x}^{3}}$ |
| **neither** | **even** | may become **even** | ${e}^{{x}^{2}}$ |
| **neither** | **neither** | usually **neither** | $\ln({x + 1})$ |

> [!TIP]
> - if the **inner** function is `even`,
>
>   then the whole function is `even`
>
> - if **both** inner and outer functions aren't `neither`,
>
>   and **either** inner and outer function is `even`,
>
>   then the whole function is `even`