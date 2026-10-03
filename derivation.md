```math
\text{Calculate} \int \sqrt{\frac{ax+b}{cx+t}}\,dx
\qquad
\text{where:}
\qquad
x,a,b,c,t\in\mathbb C,
\qquad
(c,t)\neq(0,0),
\qquad
D=at-bc
```

```math
\text{Case 1: } D=0,\ c\neq 0
```

```math
D=at-bc=0
\quad\Longrightarrow\quad
at=bc
\quad\Longrightarrow\quad
b=\frac{at}{c}
```

```math
\frac{ax+b}{cx+t}
=\frac{ax+\frac{at}{c}}{cx+t}
=\frac{a}{c}
```

```math
\begin{aligned}
\int \sqrt{\frac{ax+b}{cx+t}}\,dx
&=\int \sqrt{\frac{a}{c}}\,dx\\
&=x\sqrt{\frac{a}{c}}+C_1
\end{aligned}
```

```math
\text{Case 2: } D=0,\ c=0
```

```math
D=at-bc=at=0,
\qquad
t\neq 0
\quad\Longrightarrow\quad
a=0
```

```math
\frac{ax+b}{cx+t}
=\frac{b}{t}
```

```math
\begin{aligned}
\int \sqrt{\frac{ax+b}{cx+t}}\,dx
&=\int \sqrt{\frac{b}{t}}\,dx\\
&=x\sqrt{\frac{b}{t}}+C_2
\end{aligned}
```

```math
\text{Case 3: } D\neq 0,\ c=0
```

```math
D=at-bc=at,
\qquad
D\neq 0
\quad\Longrightarrow\quad
a\neq 0,\ t\neq 0
```

```math
\sqrt{\frac{ax+b}{cx+t}}
=\sqrt{\frac{ax+b}{t}}
```

```math
\text{Let }
u=\sqrt{\frac{ax+b}{t}},
\qquad
u^2=\frac{ax+b}{t}
```

```math
ax+b=tu^2
\quad\Longrightarrow\quad
x=\frac{tu^2-b}{a}
```

```math
dx=\frac{2tu}{a}\,du
```

```math
\begin{aligned}
\int \sqrt{\frac{ax+b}{cx+t}}\,dx
&=\int u\cdot\frac{2tu}{a}\,du\\
&=\frac{2t}{a}\int u^2\,du\\
&=\frac{2t}{3a}u^3+C_3\\
&=\frac{2t}{3a}\left(\frac{ax+b}{t}\right)^{3/2}+C_3
\end{aligned}
```

```math
\text{Case 4: } D\neq 0,\ c\neq 0,\ a=0
```

```math
D=at-bc=-bc,
\qquad
D\neq 0
\quad\Longrightarrow\quad
b\neq 0,\ c\neq 0
```

```math
\sqrt{\frac{ax+b}{cx+t}}
=\sqrt{\frac{b}{cx+t}}
```

```math
\text{Let }
u=\sqrt{\frac{b}{cx+t}},
\qquad
u^2=\frac{b}{cx+t}
```

```math
cx+t=\frac{b}{u^2}
\quad\Longrightarrow\quad
x=\frac{b}{cu^2}-\frac{t}{c}
```

```math
dx=-\frac{2b}{cu^3}\,du
```

```math
\begin{aligned}
\int \sqrt{\frac{ax+b}{cx+t}}\,dx
&=\int u\cdot\left(-\frac{2b}{cu^3}\right)du\\
&=-\frac{2b}{c}\int u^{-2}\,du\\
&=\frac{2b}{cu}+C_4\\
&=\frac{2b}{c\sqrt{\dfrac{b}{cx+t}}}+C_4
\end{aligned}
```

```math
\text{Case 5: } D\neq 0,\ c\neq 0,\ a\neq 0
```

```math
\text{[WIP]}
```
