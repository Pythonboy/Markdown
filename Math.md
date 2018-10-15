# 插入数学公式
在Markdown中插入数学公式的语法是 $数学公式$ 和 $$数学公式$$                       
行内公式是可以让公式在文中与文字或其他东西混编，不独占一行。
```
质能方程$E = mc^2$
```
独立公式使公式单独占一行，不与文中其他文字等混编。
```
质能方程$$E = mc^2$$
```

# 普通公式
普通的加减乘除数学公式的输入方法与平常的书写一样
```
$$x = 100 * y + z - 10 / 33 + 10 % 3$$
```

# 上下标
使用^来表示上标，_来表示下标，同时如果上下标的内容多于一个字符，可以使用{}来将这些内容括起来当做一个整体，与此同时，上下标是可以嵌套的
```
$$x = a_{1}^n + a_{2}^n + a_{3}^n$$
```
如果希望左右两边都能有上下标，可以使用\sideset语法
```
$$\sideset{^1_2}{^3_4}A$$
```

# 括号
()，[]和|都表示它们自己，但是{}因为有特殊作用因此当需要显示大括号时一般使用\lbrace \rbrace来表示
```
$$f(x, y) = 100 * \lbrace[(x + y) * 3] - 5\rbrace$$

```

# 分数 
分数使用\frac{分母}{分子}这样的语法，不过推荐使用\cfrac来代替\frac，显示公式不会太挤
```
$$\frac{1}{3} 与 \cfrac{1}{3}$$

```

# 开方
开方使用\sqrt[次数]{被开方数}这样的语法
```
$$\sqrt[3]{X}$$
$$\sqrt{5 - x}$$

```

# 微积分运算符
|符号|	代码|
|:-:|:-:|
|′	|\prime|
|∫|	\int|
|∬|	\iint|
|∭|	\iiint|
|∬∬	|\iiiint|
|∮|	\oint|
|lim|	\lim|
|∞|	\infty|
|∇|	\nabla|
|d	|\mathrm{d}|


# 三角运算符

|符号|	代码|
|:-:|:-:|
|⊥|	\bot|
|∠|	\angle|
|sin|	\sin|
|cos|	\cos|
|tan|	\tan|
|cot|	\cot|
|csc|	\csc|

# 对数运算符
|符号|代码|
|:-:|:-:|
|log|	\log|
|lg|	\lg|
|ln|	\ln|

# 关系运算符
|符号|	代码|
|:-:|:-:|
|±|	\pm|
|×|	\times|
|÷|	\div|
|∣|	\mid|
|∤|	\nmid|
|⋅|	\cdot|
|∘|	\circ|
|∗|	\ast|
|⨀|	\bigodot|
|⨂|	\bigotimes|
|⨁|	\bigoplus|
|≤|	\leq|
|≥|	\geq|
|≠|	\neq|
|≈|	\approx|
|≡|	\equiv|
|∑|	\sum|
|∏|	\prod|
|∐|	\coprod|

# 希腊字母表

|代码|	大写|	代码|	小写|
|:-:|:-:|:-:|:-:|
|A|	A|	\alpha|	α|
|B|	B|	\beta|	β|
|\Gamma|	Γ	|\gamma	|γ|
|\Delta|	Δ|	\delta|	δ|
|E	|E|	\epsilon|	ϵ|
|Z|	Z|	\zeta|	ζ|
|H|	H	|\eta	|η|
|\Theta|	Θ|	\theta|	θ|
|I	|I|	\iota|	ι|
|K|	K	|\kappa|	κ|
|\Lambda|	Λ|	\lambda|	λ|
|M|	M|	\mu|	μ|
|N|	N|\nu|	ν|
|\Xi|	Ξ|	\xi|	ξ|
|O|	O|	\omicron|	ο|
|\Pi|	Π|	\pi|	π|
|P|	P|	\rho|	ρ|
|\Sigma|	Σ|	\sigma|	σ|
|T|	T|	\tau|	τ|
|\Upsilon|	Υ|	\upsilon|	υ|
|\Phi|	Φ|	\phi|	ϕ|
|X|	X|	\chi|	χ|
|\Psi|	Ψ|	\psi|	ψ|
|\Omega|	Ω|	\omega|	ω|
