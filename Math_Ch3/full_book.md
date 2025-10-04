# Chapter 3 - Text Book
## Differentiation

---

### Section 1: The Derivative

#### 1.1 The gradient of a curve

Let $C$ be a "smooth" curve and $P$ be a point on this curve. Consider a variable secant passing through the point $P$ cutting $(C)$ in $Q_1, Q_2, Q_3, \dots$ such that $Q_1, Q_2, Q_3, \dots$ are successively closer to $P$.

As the sequence of points $Q_1, Q_2, Q_3, \dots$ get closer and closer to $P$ the secant lines get closer and closer to a fixed line $T$ that is tangent to $C$. Consequently, the slopes of the secant lines get closer and closer to a fixed number, which is equal to the slope of $T$.

In this case, the gradient of the curve at $P$ is defined as the gradient of the tangent to the curve at $P$.

![The secant lines are approaching the tangent line at P](./media/image_1.png)

**The gradient at a given point**

> ### Example 1
>
> Consider the curve whose equation is given by $y = 2x^2$.
>
> a) Find the slope of the secant line joining $P(1, 2)$ with $Q_1(2, 8)$.
>
> b) Tabulate the slopes of the secant lines joining $P(1, 2)$ with the points $Q_2, Q_3, Q_4, \dots, Q_{10}$ whose abscissas are, respectively, $1.9, 1.8, 1.7, \dots, 1.1$.
>
> c) Tabulate the slopes of the secant lines joining $P(1, 2)$ with $Q_{11}, Q_{12}, Q_{13},$ and $Q_{14}$, whose abscissas are, respectively, $1.08, 1.04, 1.02, \text{ and } 1.01$.
>
> d) What trend is observed for the slopes of the secant lines? What claim can be made from this observation?
>
> **Solution**
>
> a) The slope of $\overline{PQ_1}$ is given by $\frac{y_2 - y_1}{x_2 - x_1} = \frac{8 - 2}{2 - 1} = 6$.
>
> b) The slopes of $\overline{PQ_2}, \overline{PQ_3}, \dots, \overline{PQ_{10}}$ are obtained similarly.
>
> For instance, $Q_3(1.8, 2(1.8)^2) = (1.8, 6.48)$ and the slope of $\overline{PQ_3}$ is given by $\frac{y_2 - y_1}{x_2 - x_1} = \frac{6.48 - 2}{1.8 - 1} = 5.6$. The table below summarizes the results.
>
> | i | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
> | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :-- |
> | $x$ of $Q_i$ | 2 | 1.9 | 1.8 | 1.7 | 1.6 | 1.5 | 1.4 | 1.3 | 1.2 | 1.1 |
> | Slope of $\overline{PQ_i}$ | 6.0 | 5.8 | 5.6 | 5.4 | 5.2 | 5.0 | 4.8 | 4.6 | 4.4 | 4.2 |
>
> c) The slopes of $\overline{PQ_{11}}, \overline{PQ_{12}}, \overline{PQ_{13}}, \text{ and } \overline{PQ_{14}}$ are
>
> | i | 11 | 12 | 13 | 14 |
> | :--- | :--- | :--- | :--- | :--- |
> | $x$ of $Q_i$ | 1.08 | 1.04 | 1.02 | 1.01 |
> | Slope of $\overline{PQ_i}$ | 4.16 | 4.08 | 4.04 | 4.02 |
>
> d) The slopes of the secant lines are approaching $4$. The tangent to the curve, and thus the curve, both have a gradient of $4$.

> ### Example 2
>
> Consider again the curve whose equation is given by $y = 2x^2 + 4x - 1$.
>
> a) Find the slope of the secant lines joining $P(1, 5)$ with $Q_h$, a variable point on the curve whose abscissa is $1+h$.
>
> b) What is the value of the slope, obtained in a), as $h$ gets closer and closer to zero?
>
> c) What can be deduced about the gradient of the curve at $P$?
>
> **Solution**
>
> a) The ordinate of $Q_h$ is $2(1+h)^2 + 4(1+h) - 1 = 5 + 8h + 2h^2$.
>
> The slope of $\overline{PQ_h}$ is given by
>
> $\frac{y_2 - y_1}{x_2 - x_1} = \frac{5 + 8h + 2h^2 - 5}{1+h - 1} = \frac{8h + 2h^2}{h} = 8 + 2h$
>
> b) As $h$ approaches zero, $8 + 2h$ approaches $8$ and therefore, the slope of $\overline{PQ_h}$ approaches $8$.
>
> c) The gradient of the curve at $P$ is $8$.

> ### Activity
>
> Consider the curve whose equation is given by $y = 2x^2$. Find the slope of the secant lines joining $P(3, 18)$ with $Q_h$, a variable point on the curve whose abscissa is $3+h$.

---

### 1.2 The derived function

**Notations**

In dealing with the gradient of a curve at one of its points, small changes in the coordinates of this point are usually considered. The Greek letter $\delta$ (read delta) is used to indicate these small changes; for instance, $\delta x, \delta y, \delta t, \dots$ will denote small changes in $x, y, t, \dots$, respectively. Note that each of $\delta x, \delta y, \delta t, \dots$ has to be considered as a single symbol and not as the product of $\delta$ by $x, y, \text{ or } t$.

Moreover an arrow will be used to abbreviate expressions such as "approaches to", or "tends to"; for instance: " $Q$ approaches $P$ " may be abbreviated as " $Q \to P$ ".

"The gradient of a curve at $P$ is the limit of the gradient of the chord $\overline{PQ}$ " may be written as: "The gradient of the chord $\overline{PQ} \to$ the gradient of the curve at $P$ " and " $\delta x$ approaches zero" may be abbreviated by: " $\delta x \to 0$ ".

**The gradient at a variable point**

> ### Example 1
>
> Find the slope of the secant lines joining $P(x, 2x^2)$ with $Q$, a variable point whose abscissa is $x + \delta x$. What value, if any, do the slopes of $\overline{PQ}$ approach as $\delta x \to 0$? Investigate the case when $x=1$.
>
> **Solution**
>
> The ordinate of $Q$ is $2(x + \delta x)^2 = 2x^2 + 4x(\delta x) + 2(\delta x)^2$.
>
> The slope of $\overline{PQ}$ is given by
>
> $\frac{y_2 - y_1}{x_2 - x_1} = \frac{2x^2 + 4x(\delta x) + 2(\delta x)^2 - 2x^2}{x + \delta x - x} = \frac{4x(\delta x) + 2(\delta x)^2}{\delta x} = 4x + 2(\delta x)$.
>
> As $\delta x \to 0$, $4x + 2\delta x \to 4x$ and therefore, the slope of $\overline{PQ}$ approaches $4x$. If $x=1$ the gradient of the curve is $4$.

> ### Activity 1
>
> Find the slope of the secant lines joining $P(x, 4x^2)$ with $Q$, a variable point whose abscissa is $x + \delta x$. What value, if any, do the slopes of $\overline{PQ}$ approach as $\delta x \to 0$? Investigate the case when $x=1$.

**The derived function**

The gradient of a function given by $y = f(x)$ at a point whose abscissa is $x$ is called the derived function of $f$, denoted by $f'(x)$, $\frac{dy}{dx}$, or simply $y'$ and is called the derivative of $f(x)$ or the derivative of $y$. The process of finding the derived function is sometimes referred to as differentiating the function. In example 1 above, the derived function of $y = 2x^2$ is the function $y' = 4x$ or equivalently, differentiating $2x^2$ yields $4x$.

Note that, $\frac{dy}{dx}$ is not a ratio of $dy$ by $dx$. It is merely a notation for the gradient of $y$. The reason behind the notation is the fact that $\frac{dy}{dx}$ is the limiting value of $\frac{\delta y}{\delta x}$ as $\delta x \to 0$.

**The derivative of $y=x^2$**

Let $P(x, x^2)$ represent any point on the curve whose equation is given by $y=x^2$. Let $Q$ be a variable point whose abscissa is $x+\delta x$.
The ordinate of $Q$ is $(x+\delta x)^2 = x^2 + 2x(\delta x) + (\delta x)^2$.
The slope of $\overline{PQ}$ is given by:
$\frac{y_2 - y_1}{x_2 - x_1} = \frac{x^2 + 2x(\delta x) + (\delta x)^2 - x^2}{x+\delta x - x} = \frac{2x(\delta x) + (\delta x)^2}{\delta x} = 2x + \delta x$.

As $\delta x \to 0$, $2x + \delta x \to 2x$ and hence, the slope of $\overline{PQ} \to 2x$.
Therefore, the derivative of $y=x^2$ is $y' = 2x$.

**The derivative of $y=x^3$**

Let $P(x, x^3)$ represent any point on the curve whose equation is given by $y=x^3$. Let $Q$ be a variable point whose abscissa is $x+\delta x$.
The ordinate of $Q$ is $(x+\delta x)^3 = x^3 + 3x^2(\delta x) + 3x(\delta x)^2 + (\delta x)^3$.
The slope of $\overline{PQ}$ is given by:
$\frac{y_2 - y_1}{x_2 - x_1} = \frac{x^3 + 3x^2(\delta x) + 3x(\delta x)^2 + (\delta x)^3 - x^3}{x+\delta x - x} = \frac{3x^2(\delta x) + 3x(\delta x)^2 + (\delta x)^3}{\delta x} = 3x^2 + 3x(\delta x) + (\delta x)^2$.

As $\delta x \to 0$, $3x^2 + 3x(\delta x) + (\delta x)^2 \to 3x^2$ and hence, the slope of $\overline{PQ} \to 3x^2$.
Therefore, the derivative of $y=x^3$ is $y' = 3x^2$.

**The derivative of $y=x^{-1} = \frac{1}{x}$**

Let $P(x, \frac{1}{x})$ represent any point on the curve whose equation is given by $y=\frac{1}{x}$. Let $Q$ be a variable point whose abscissa is $x+\delta x$. The ordinate of $Q$ is $\frac{1}{x+\delta x}$.
The slope of $\overline{PQ}$ is given by:
$\frac{y_2 - y_1}{x_2 - x_1} = \frac{\frac{1}{x+\delta x} - \frac{1}{x}}{\delta x} = \frac{\frac{x-(x+\delta x)}{x(x+\delta x)}}{\delta x} = \frac{-\delta x}{x(x+\delta x)(\delta x)} = \frac{-1}{x(x+\delta x)}$.

As $\delta x \to 0$, $\frac{-1}{x(x+\delta x)} \to \frac{-1}{x(x+0)}$ and hence, the slope of $\overline{PQ}$ approaches $\frac{-1}{x^2}$.
Therefore, the derivative of $y=\frac{1}{x}$ is $y' = -\frac{1}{x^2}$.

Summing up,
* If $y=x^2$ then $\frac{dy}{dx} = 2x$
* If $y=x^3$ then $\frac{dy}{dx} = 3x^2$
* If $y=x^{-1}$ then $\frac{dy}{dx} = -1x^{-2}$

---

The previous three cases are special cases of the more general rule that is stated here without a proof: if $y = x^n$ then $\frac{dy}{dx} = nx^{n-1}$ where $n$ is any rational number.

> ### Example 2
>
> Using the rule for differentiating $x^n$, find $y'$ in each of the following cases:
>
> a) $y = x^5$
>
> b) $y = \sqrt{x}$
>
> c) $y = \frac{1}{x^3}$
>
> d) $y = \frac{x}{\sqrt{x}}$
>
> **Solution**
>
> a) $y = x^5 \implies \frac{dy}{dx} = 5x^{5-1} = 5x^4$
>
> b) $y = \sqrt{x} = x^{1/3} \implies \frac{dy}{dx} = \frac{1}{3}x^{\frac{1}{3}-1} = \frac{1}{3}x^{-2/3} = \frac{1}{3\sqrt{x^2}}$
>
> c) $y = \frac{1}{x^3} = x^{-3} \implies \frac{dy}{dx} = -3x^{-3-1} = -3x^{-4} = -\frac{3}{x^4}$
>
> d) $y = \frac{x}{\sqrt{x}} = \frac{x^1}{x^{1/3}} = x^{2/3} \implies y' = \frac{2}{3}x^{\frac{2}{3}-1} = \frac{2}{3}x^{-1/3} = \frac{2}{3\sqrt{x}}$
>

> ### Activity 2
>
> Find $\frac{dy}{dx}$ in each of the following cases:
>
> a) $y=\sqrt{x}$
>
> b) $y = -\frac{1}{x}$
>
> c) $y = \frac{1}{\sqrt{x}}$
>
> d) $y = \frac{x^2}{\sqrt{x}}$

---

### 1.3 The derivative of a polynomial function

The following two properties of the derived function will be stated here without a proof. A proof will be given in the next section.

* If $u$ and $v$ are functions of $x$, and $y = u+v$ then $y' = u' + v'$.
* If $u$ is function of $x$, $a$ is a constant, and $y = au$ then $y' = au'$.

Note that, the first rule can be generalized to include the sum of many terms. Thus, if $y = u+v+w+\dots$ then $y' = u' + v' + w' + \dots$.

Moreover, if $y = u-v$ then $y = u + (-1)v$ and $y' = u' + [(-1)v]' = u' + (-1)v' = u' - v'$.

> ### Example 1
>
> Differentiate $y = x^5 + x^4 + x$.
>
> **Solution**
>
> $\frac{dy}{dx} = \frac{d(x^5)}{dx} + \frac{d(x^4)}{dx} + \frac{d(x)}{dx} = 5x^4 + 4x^3 + 1$

> ### Example 2
>
> Differentiate $y=5x^3$.
>
> **Solution**
>
> $y' = 5(x^3)' = 5 \cdot 3x^2 = 15x^2$

> ### Example 3
>
> Differentiate $y=2x^3+4x^2-2x$.
>
> **Solution**
>
> $y' = (2x^3+4x^2-2x)'$
> $= (2x^3)' + (4x^2)' - (2x)'$
> $= 2(x^3)' + 4(x^2)' - 2(x)'$
> $= 2(3x^2) + 4(2x) - 2(1)$
> $= 6x^2 + 8x - 2$

Since every polynomial is sums and/or differences of powers of $x$ multiplied by a scalar then the rules of differentiation discussed so far are sufficient to find the derived function of any polynomial. In particular, if $y = P(x) = a_n x^n + a_{n-1}x^{n-1} + \dots + a_2 x^2 + a_1 x + a_0$ then,
$y' = a_n n x^{n-1} + a_{n-1}(n-1)x^{n-2} + \dots + 2a_2 x + a_1$.

Note that if $u=k$ (constant) then $u$ can be expressed as $u=kx^0$ and $u' = k \cdot 0 x^{-1} = 0$, and if $v=ax$ then $v$ can be expressed as $v=ax^1$ and $v' = a \cdot 1 x^0 = a$.

> ### Example 4
>
> Differentiate.
>
> a) $y = 10^5$
>
> b) $y = 4x^6 - 3x^3 + 5$
>
> c) $y = ax+b$, $a$ and $b$ are constants
>
> **Solution**
>
> a) $y=10^5$ is a constant $\to \frac{dy}{dx} = 0$
>
> b) $y = 4x^6 - 3x^3 + 5 \to \frac{dy}{dx} = 24x^5 - 9x^2$
>
> c) $y = ax+b \to \frac{dy}{dx} = a$

> ### Example 5
>
> Differentiate.
>
> a) $y = x^2(4x^3 - 2)$
>
> b) $y = \frac{5x^4+3x^3}{x}$
>
> c) $y = ax^2 + bx + c$; $a, b, \text{ and } c$ are constants
>
> **Solution**
>
> a) $y = x^2(4x^3 - 2) = 4x^5 - 2x^2 \implies y' = 20x^4 - 4x$
>
> b) $y = \frac{5x^4+3x^3}{x} = 5x^3 + 3x^2 \implies y' = 5(3x^2) + 3(2x) = 15x^2 + 6x$
>
> c) $y = ax^2 + bx + c \implies y' = 2ax + b$
>

> ### Activity 1
>
> 1. Given $y$, find $y'$.
>
>    a) $y = \sqrt{x^2}$
>
>    b) $y = \frac{5}{2\sqrt{x}}$
>
>    c) $y = \frac{x^2}{\sqrt{5x}}$
>
>    d) $y = \sqrt{\frac{2x}{x}}$
>
> 2. Find $\frac{dy}{dx}$ in each of the following cases:
>
>    a) $y = -5x^4 + 2x^3 - 6x^2 + x - 2$
>
>    b) $y = \frac{4x^5 - 3x^4 + x^2}{3x^2}$
>
>    c) $y = \frac{1}{5}x^5 + \frac{1}{3}x^3 - \frac{3}{2}x^2$
>
>    d) $y = 2x(x-3)(x+3)$
>

> ### Example 6
>
> Consider the curve given by $y = 5x^3 - 2x$. Find $y'$ at $x=3$.
>
> **Solution**
>
> $y' = 15x^2 - 2 \implies y'$ at $x=3$ is equal to $15(3)^2 - 2 = 133$.

> ### Example 7
>
> Find the point on the curve $y=5x^3 - 2x$ at which the gradient is $13$.
>
> **Solution**
>
> $y' = 15x^2 - 2 = 13 \implies 15x^2 = 15 \implies x^2 = 1 \implies x=1 \text{ or } x=-1$.
>
> The points are: $(1, 3)$ and $(-1, -3)$.

> ### Activity 2
>
> Find the point on the curve $y=3x^2 - 2$ at which the gradient is $0.5$.

---

### 1.4 Tangents and normals to a curve

The tangent to a curve at a point $P$ on the curve is the line passing through $P$ with a slope equal to the gradient of the curve at $P$. The normal to a curve at a point $P$ on the curve is the line passing through $P$ and perpendicular to the tangent line at $P$.

![A normal and a tangent to a curve](./media/image_2.png)

> ### Example 1
> Find the equation of the tangent line to the curve $y=5x^3 - 2x$ at the point whose abscissa is $-2$.
>
> **Solution**
>
> $y' = 15x^2 - 2 \implies$ the slope of the tangent is $15(-2)^2 - 2 = 58$.
>
> The ordinate of the point of tangency is obtained from the equation of the curve:
> $y = 5(-2)^3 - 2(-2) = -40+4 = -36$.
>
> The equation of the line passing through $(a,b)$ with a slope of $m$ is given by: $y-b=m(x-a)$. Thus, the equation of the tangent line is:
> $y - (-36) = 58[x - (-2)]$
>
> $y+36 = 58(x+2)$
>
> $y+36 = 58x + 116$
>
> $y = 58x + 80$.

> ### Activity 1
>
> Find the equation of the tangent to the curve $y=x^2-1$ at the point $(1,0)$.

> ### Example 2
>
> Find the equation of the normal line to the curve $y=5x^3 - 2x + 3$ at the point where the curve meets the $y$-axis.
>
> **Solution**
>
> The point where the curve meets the $y$-axis corresponds to $x=0$.
> Thus its ordinate is $y = 5(0)^3 - 2(0) + 3 = 3$.
>
> $y' = 15x^2 - 2 \implies$ the slope of the tangent at $x=0$ is $15(0)^2 - 2 = -2$.
>
> The normal at $x=0$ is perpendicular to the tangent at $x=0$ and hence its slope is $\frac{-1}{-2} = \frac{1}{2}$.
>
> The equation of the line passing through $(0,3)$ with a slope of $\frac{1}{2}$ is given by:
>
> $y-3 = \frac{1}{2}(x-0)$.
>
> Therefore, the equation of the normal line at $x=0$ is:
>
> $y-3 = \frac{1}{2}x \implies y = \frac{1}{2}x+3 \implies 2y-x=6$.
>

> ### Activity 2
>
> 1. Find the equations of the tangent and the normal to the curve $y = 3x^2 - 2x + 5$ at $x=-1$.
>
> 2. Find the equations of the tangent and the normal to the curve $y = x^3 - 2x^2 + 1$ at the point where it cuts the $y$-axis.
>
> 3. a) Find the coordinates of the points of intersection of the line $y = -\frac{1}{3}x$ with the curve $y=(1-x)(x+x^2)$.
>
>    b) If these points are $M, N,$ and $P$, such that $x_M < x_N < x_P$, show that the tangents to the curve at $M$ and $P$ are parallel and,
>
>    c) the tangent at $N$ is perpendicular to them.
>
> 4. The figure shows a sketch of a part of the curve $C$ with equation: $2y = 3x^3 - 7x^2 + 4x$ which meets the $x$-axis at the origin $O$, the point $A(1,0)$ and the point $B$.
>
>    ![A sketch of the curve C](./media/image_3.png)
>
>    a) Find the coordinates of $B$.
>
>    b) The normals to the curve $C$ at the points $O$ and $A$ meet at the point $N$. Find the coordinates of $N$.
>
>    c) Calculate the area of $\triangle OAN$.
>

---

### Section 2: Rules of Differentiation

#### 2.1 The sum and constant multiple rule

**The sum rule**

Consider the function $y = f(x) = u(x) + v(x)$.

If $P(x,y)$ and $Q(x+\delta x, y+\delta y)$ are two points on the curve given by $f$ then
$y = f(x) = u(x)+v(x)$ and $y+\delta y = f(x+\delta x) = u(x+\delta x) + v(x+\delta x)$.

The slope of the secant line $\overline{PQ}$ is given by:

$\frac{(y+\delta y) - y}{(x+\delta x) - x} = \frac{u(x+\delta x) + v(x+\delta x) - [u(x)+v(x)]}{\delta x}$

$\frac{\delta y}{\delta x} = \frac{u(x+\delta x) - u(x) + v(x+\delta x) - v(x)}{\delta x} = \frac{u(x+\delta x) - u(x)}{\delta x} + \frac{v(x+\delta x) - v(x)}{\delta x}$

As $\delta x \to 0$, $\frac{\delta y}{\delta x} \to \frac{dy}{dx}$, $\frac{u(x+\delta x) - u(x)}{\delta x} \to \frac{du}{dx}$, and $\frac{v(x+\delta x) - v(x)}{\delta x} \to \frac{dv}{dx}$.

Consequently, $\frac{dy}{dx} = \frac{du}{dx} + \frac{dv}{dx}$ or $y' = u' + v'$.

> ### Example 1
>
> Given $y=x^3+\sqrt{x}$ find $y'$ when $x=4$.
>
> **Solution**
>
> $y=x^3+\sqrt{x} = x^3 + x^{1/2}$. The derivative of $x^3$ is $3x^2$ and the derivative of $x^{1/2}$ is $\frac{1}{2}x^{-1/2}$. Therefore, the derivative of $y=x^3+\sqrt{x}$ is $3x^2 + \frac{1}{2}x^{-1/2}$.
>
> or $y' = 3x^2 + \frac{1}{2}x^{-1/2} = 3x^2 + \frac{1}{2\sqrt{x}}$.
>
> $y'|_{x=4} = 3(4)^2 + \frac{1}{2\sqrt{4}} = 48 + \frac{1}{4} = 48.25$.

> ### Example 2
>
> Given $y = x^3 + \frac{1}{x^2}$ find the gradient of $y$ at $x=4$.
>
> **Solution**
>
> $y = x^3 + \frac{1}{x^2} = x^3 + x^{-2} \implies y' = 3x^2 - 2x^{-3} = 3x^2 - \frac{2}{x^3}$.
>
> At $x=4, y' = 3(4)^2 - \frac{2}{(4)^3} = 48 - \frac{2}{64} = 48 - \frac{1}{32} \approx 47.96875$.

> ### Activity 1
>
> Given $y=x^4 + \frac{1}{x^2}$ find $y'$.

**The constant multiple rule**

Consider the function $y=f(x) = cu(x)$ where $c$ is a constant.

If $P(x,y)$ and $Q(x+\delta x, y+\delta y)$ are two points on the curve given by $f$ then
$y=f(x) = cu(x)$ and $y+\delta y = f(x+\delta x) = cu(x+\delta x)$. The slope of the secant line $\overline{PQ}$ is given by:

$\frac{(y+\delta y)-y}{(x+\delta x)-x} = \frac{cu(x+\delta x) - cu(x)}{\delta x} \implies \frac{\delta y}{\delta x} = c\left(\frac{u(x+\delta x)-u(x)}{\delta x}\right)$

As $\delta x \to 0$, $\frac{\delta y}{\delta x} \to \frac{dy}{dx}$ and $\frac{u(x+\delta x) - u(x)}{\delta x} \to \frac{du}{dx}$.

Consequently, $\frac{dy}{dx} = c \frac{du}{dx}$ or $y' = cu'$.

> ### Example 3
>
> Given $y=8\sqrt{x}$ find $y'$.
>
> **Solution**
>
> $y=8\sqrt{x} = 8x^{1/2}$. The derivative of $x^{1/2}$ is $\frac{1}{2}x^{-1/2}$.
>
> Therefore, the derivative of $8x^{1/2}$ is $8(\frac{1}{2}x^{-1/2}) = 4x^{-1/2} = \frac{4}{\sqrt{x}}$.

> ### Example 4
>
> Given $y = \frac{6}{x^2}$ find the gradient of $y$ at $x=2$.
>
> **Solution**
>
> $y = \frac{6}{x^2} = 6x^{-2} \implies y' = 6(-2)x^{-3} = -\frac{12}{x^3}$.
>
> At $x=2, y' = -\frac{12}{(2)^3} = -\frac{12}{8} = -1.5$.

> ### Activity 2
>
> Given $y = \frac{4}{x^3}$ find the gradient of $y$ at $x=-1$.

**The difference rule**

Consider the function $y = f(x) = u(x) - v(x)$.
$y = f(x) = u(x) - v(x) \implies y = u(x) + [(-1)v(x)] \implies y' = u'(x) + [(-1)v(x)]'$
$\implies y' = u'(x) + (-1)v'(x) \implies y' = u'(x) - v'(x)$.

> ### Example 5
>
> Given $y = 5x^2 - \frac{2}{x^2} + 4\sqrt{x}$ find $y'$.
>
> **Solution**
>
> $y = 5x^2 - 2x^{-2} + 4x^{1/3} \implies y' = 10x - 2(-2)x^{-3} + 4(\frac{1}{3})x^{-2/3}$
>
> $\implies y' = 10x + 4x^{-3} + \frac{4}{3}x^{-2/3} = 10x + \frac{4}{x^3} + \frac{4}{3\sqrt{x^2}}$

> ### Example 6
>
> Given $y = x^2 - \frac{1}{\sqrt{x}}$ find the gradient of $y$ at $x=1$.
>
> **Solution**
>
> $y = x^2 - \frac{1}{\sqrt{x}} = x^2 - x^{-1/2} \implies y' = 2x - (-\frac{1}{2})x^{-3/2} = 2x + \frac{1}{2}x^{-3/2} = 2x + \frac{1}{2\sqrt{x^3}}$
>
> At $x=1, y' = 2(1) + \frac{1}{2\sqrt{(1)^3}} = 2 + \frac{1}{2} = 2.5$.

> ### Activity 3
>
> Given $y = 3x^4 - 10x^2 + \frac{2}{\sqrt{x}}$ find $y'$.

---

### 2.2 The product rule

Consider the function $y=f(x) = u(x)v(x)$.

If $P(x,y)$ and $Q(x+\delta x, y+\delta y)$ are two points on the curve given by $f$ then
$y = f(x) = u(x)v(x)$ and $y+\delta y = f(x+\delta x) = u(x+\delta x)v(x+\delta x)$.

The slope of the secant line $\overline{PQ}$ is given by:

$\frac{(y+\delta y)-y}{(x+\delta x)-x} = \frac{u(x+\delta x)v(x+\delta x) - u(x)v(x)}{\delta x}$

$\implies \frac{\delta y}{\delta x} = \frac{u(x+\delta x)v(x+\delta x) - u(x)v(x+\delta x) + u(x)v(x+\delta x) - u(x)v(x)}{\delta x}$

$\implies \frac{\delta y}{\delta x} = \frac{u(x+\delta x) - u(x)}{\delta x}v(x+\delta x) + u(x)\frac{v(x+\delta x) - v(x)}{\delta x}$

As $\delta x \to 0$, $\frac{\delta y}{\delta x} \to \frac{dy}{dx}$, $\frac{u(x+\delta x)-u(x)}{\delta x} \to \frac{du}{dx}$, and $\frac{v(x+\delta x)-v(x)}{\delta x} \to \frac{dv}{dx}$.

Consequently, $\frac{dy}{dx} = \frac{du}{dx}v(x) + u(x)\frac{dv}{dx}$ or $y' = u'v + uv'$.

> ### Example 1
>
> Given $y = (x^3+2x)\sqrt{x}$ find $y'$.
>
> **Solution**
>
> Set $u = x^3+2x$ and $v=\sqrt{x}$. Then $u' = 3x^2+2$ and $v' = \frac{1}{2\sqrt{x}}$.
>
> Therefore, $y' = (3x^2+2)\sqrt{x} + (x^3+2x)\frac{1}{2\sqrt{x}}$.

> ### Example 2
>
> Given $y=(x^2+1)(1-\sqrt{x})$ find the gradient of $y$ at $x=1$.
>
> **Solution**
>
> Set $u=x^2+1$ and $v=1-\sqrt{x}$. Then $u'=2x$ and $v'=-\frac{1}{2\sqrt{x}}$.
>
> Therefore, $y' = 2x(1-\sqrt{x}) + (x^2+1)(-\frac{1}{2\sqrt{x}}) = 2x(1-\sqrt{x}) - \frac{x^2+1}{2\sqrt{x}}$.
>
> At $x=1, y' = 2(1)(1-\sqrt{1}) - \frac{1^2+1}{2\sqrt{1}} = 0 - \frac{2}{2} = -1$.

> ### Activity
>
> Given $y = (5x^2+4x-1)(4\sqrt{x})$ find $y'$.

---

### 2.3 The quotient rule

Consider the function $y = f(x) = \frac{u(x)}{v(x)}$.

If $P(x,y)$ and $Q(x+\delta x, y+\delta y)$ are two points on the curve given by $f$ then
$y = f(x) = \frac{u(x)}{v(x)}$ and $y+\delta y = f(x+\delta x) = \frac{u(x+\delta x)}{v(x+\delta x)}$.

The slope of the secant line $\overline{PQ}$ is given by: $\frac{(y+\delta y)-y}{(x+\delta x)-x} = \frac{\frac{u(x+\delta x)}{v(x+\delta x)} - \frac{u(x)}{v(x)}}{\delta x}$

$\implies \frac{\delta y}{\delta x} = \frac{u(x+\delta x)v(x) - u(x)v(x+\delta x)}{[v(x+\delta x)v(x)]\delta x}$

$\implies \frac{\delta y}{\delta x} = \frac{u(x+\delta x)v(x) - u(x)v(x) + u(x)v(x) - u(x)v(x+\delta x)}{[v(x+\delta x)v(x)]\delta x}$

$\implies \frac{\delta y}{\delta x} = \frac{[\frac{u(x+\delta x)-u(x)}{\delta x}]v(x) - u(x)[\frac{v(x+\delta x)-v(x)}{\delta x}]}{v(x+\delta x)v(x)}$

As $\delta x \to 0$, $\frac{\delta y}{\delta x} \to \frac{dy}{dx}$, $\frac{u(x+\delta x)-u(x)}{\delta x} \to \frac{du}{dx}$, $\frac{v(x+\delta x)-v(x)}{\delta x} \to \frac{dv}{dx}$, and $v(x+\delta x)v(x) \to [v(x)]^2$.

Consequently, $\frac{dy}{dx} = \frac{u'v - uv'}{v^2}$.

> ### Example 1
>
> Given $y = \frac{x^2+2x-3}{1+\sqrt{x}}$ find $y'$.
>
> **Solution**
>
> Set $u = x^2+2x-3$ and $v=1+\sqrt{x}$. Then $u' = 2x+2$ and $v' = \frac{1}{2\sqrt{x}}$.
>
> Therefore, $y' = \frac{(2x+2)(1+\sqrt{x}) - (x^2+2x-3)(\frac{1}{2\sqrt{x}})}{(1+\sqrt{x})^2}$.

> ### Example 2
>
> Given $y=\frac{2x}{x^2+1}$ find the gradient of $y$ at $x=2$.
>
> **Solution**
>
> Set $u=2x$ and $v=x^2+1$. Then $u'=2$ and $v'=2x$.
>
> Therefore, $y' = \frac{2(x^2+1) - 2x(2x)}{(x^2+1)^2} = \frac{2x^2+2-4x^2}{(x^2+1)^2} = \frac{2-2x^2}{(x^2+1)^2} = \frac{2(1-x^2)}{(x^2+1)^2}$.
>
> At $x=2, y' = \frac{2(1-2^2)}{(2^2+1)^2} = \frac{2(-3)}{(5)^2} = -\frac{6}{25}$.

> ### Activity
>
> Given $y = \frac{x^3+1}{x^2+1}$ find $y'$.

---

### 2.4 The chain rule

Consider the function $y=f(x) = \sqrt{x^2+2x+3}$. $y$ can be thought of as $u \circ v$, the composite of $u$ and $v$, where $u(x) = \sqrt{x}$ and $v(x) = x^2+2x+3$. Here, $u(v(x)) = \sqrt{x^2+2x+3}$.

If $P(x,y)$ and $Q(x+\delta x, y+\delta y)$ are two points on the curve given by $y=f(x) = u(v(x))$ then $y=u(v(x))$ and $y+\delta y = u(v(x+\delta x))$. The slope of the secant line $\overline{PQ}$ is given by:

$\frac{(y+\delta y)-y}{(x+\delta x)-x} = \frac{u(v(x+\delta x)) - u(v(x))}{\delta x}$

$\implies \frac{\delta y}{\delta x} = \frac{u(v(x+\delta x)) - u(v(x))}{v(x+\delta x) - v(x)} \times \frac{v(x+\delta x) - v(x)}{\delta x}$

As $\delta x \to 0$, let $\delta v = v(x+\delta x) - v(x)$, so $\delta v \to 0$.

$\frac{\delta y}{\delta x} \to \frac{dy}{dx}$, $\frac{v(x+\delta x)-v(x)}{\delta x} \to \frac{dv}{dx}$, and $\frac{u(v+\delta v) - u(v)}{\delta v} \to \frac{dy}{dv}$.

Consequently, $\frac{dy}{dx} = \frac{dy}{dv} \times \frac{dv}{dx}$. This rule of differentiation for the composite of two functions is referred to as the chain rule.

To understand what $\frac{dy}{dv}$ means, consider again the function $y = f(x) = \sqrt{x^2+2x+3}$.
If $v(x)=x^2+2x+3$ then $y(v)$ becomes $\sqrt{v}$ and $\frac{dy}{dv} = \frac{1}{2\sqrt{v}} = \frac{1}{2\sqrt{x^2+2x+3}}$.

> ### Example 1
>
> Given $y = \sqrt{x^2+2x+3}$ find $y'$.
>
> **Solution**
>
> Set $v=x^2+2x+3$ and $y=\sqrt{v}$. Hence, $\frac{dy}{dv} = \frac{1}{2\sqrt{v}} = \frac{1}{2\sqrt{x^2+2x+3}}$.
>
> $\frac{dv}{dx} = 2x+2$. Therefore, $y' = \frac{1}{2\sqrt{x^2+2x+3}} \times (2x+2) = \frac{x+1}{\sqrt{x^2+2x+3}}$.

> ### Example 2
>
> Given $y = (x^2+1)^{-10}$, find $y'$.
>
> **Solution**
>
> Set $v=x^2+1$ and $y=v^{-10}$. Then $\frac{dy}{dv} = -10v^{-11}$ and $\frac{dv}{dx}=2x$.
>
> Therefore, $y' = -10v^{-11}(2x) = -20x(x^2+1)^{-11}$.

> ### Example 3
>
> Given $y = \frac{x^2-1}{\sqrt{x^2+1}}$, find $y'$.
>
> **Solution**
>
> Set $u=x^2-1$ and $w=\sqrt{x^2+1}$.
>
> To compute $\frac{dw}{dx}$ let $v=x^2+1$. Then $w=\sqrt{v}$.
>
> $\frac{dw}{dv} = \frac{1}{2\sqrt{v}} = \frac{1}{2\sqrt{x^2+1}}$ and $\frac{dv}{dx}=2x$, hence, $\frac{dw}{dx} = \frac{dw}{dv}\frac{dv}{dx} = \frac{1}{2\sqrt{x^2+1}}(2x) = \frac{x}{\sqrt{x^2+1}}$.
>
> Also, $\frac{du}{dx}=2x$.
>
> Using the quotient rule $y' = \frac{u'w - uw'}{w^2}$:
>
> Therefore, $y' = \frac{2x\sqrt{x^2+1} - (x^2-1)\frac{x}{\sqrt{x^2+1}}}{(\sqrt{x^2+1})^2} = \frac{\frac{2x(x^2+1)-x(x^2-1)}{\sqrt{x^2+1}}}{x^2+1} = \frac{2x^3+2x-x^3+x}{(x^2+1)\sqrt{x^2+1}} = \frac{x^3+3x}{(x^2+1)^{3/2}}$.

> ### Activity
>
> 1. Find $\frac{dy}{dx}$
>
>    a) $y=3(5x+2)^5$
>
>    b) $y=(x^2-6x)^{-10}$
>
>    c) $y=\sqrt{(1+3x^2)^2}$
>
> 2. Given $y$ find $y'$.
>
>    a) $y=(3x+1)^6 + 6x^2 - 5x$
>
>    b) $y=-x^4+\sqrt{2x+5}+6x$
>
>    c) $y=x(x^2-1)^4$
>
>    d) $y=(x^2+1)\sqrt{x^2-1}$
>
> 3. Given $y$ find $y'$.
>
>    a) $y = \frac{x^3}{x^2-1}$
>
>    b) $y = \frac{x^3}{\sqrt{x^2-1}}$

---

## Chapter Summary

Consider a sequence of variable points $Q_1, Q_2, Q_3, \dots$ on a curve $C$ that are approaching a point $P$ on the curve. If the slopes of the secant lines joining the $Q$'s to $P$ get closer and closer to a limiting value, then this value is called the **gradient of the curve**. The line passing through $P$ whose slope is equal to this value is called the **tangent** to $C$.

The gradient of a function given by $y=f(x)$ at a point whose abscissa is $x$ is called the **derived function** of $f$, denoted by $f'(x)$, $\frac{dy}{dx}$, or simply $y'$ and is called the **derivative** of $f(x)$ or the derivative of $y$. The process of finding the derived function is sometimes referred to as **differentiating** the function.

*   If $y=c$ (constant) then $\frac{dy}{dx} = 0$
*   If $y=x$ then $\frac{dy}{dx} = 1$
*   If $y=x^n$ then $\frac{dy}{dx} = nx^{n-1}$
*   If $y = P(x) = a_n x^n + a_{n-1}x^{n-1} + \dots + a_1 x + a_0$ then, $y' = a_n n x^{n-1} + a_{n-1}(n-1)x^{n-2} + \dots + a_1$.

If $u$ and $v$ are functions of $x$, and $a$ is a constant then
*   $y=au \implies y' = au'$
*   $y=u+v \implies y'=u'+v'$ and $y=u-v \implies y'=u'-v'$
*   $y=uv \implies y'=u'v+uv'$ and $y=\frac{u}{v} \implies y' = \frac{u'v-uv'}{v^2}$
*   $y=u(v(x)) \implies y' = \frac{dy}{dv}\frac{dv}{dx}$

The **tangent** to a curve at a point $P$ is the line passing through $P$ with a slope equal to $y'$ evaluated at the abscissa of $P$.

The **normal** to a curve at a point $P$ is the line passing through $P$ and perpendicular to the tangent to the curve at $P$.

---
## Chapter Test

### Part I. Multiple Choice
Circle the correct answer.

1. Given $y = \frac{2}{x^3}$, find $y'$.
   
   a) $y' = -\frac{6}{x^4}$

   b) $y' = \frac{6}{x^2}$

   c) $y' = -\frac{6}{x^2}$

   d) $y' = \frac{2}{3x^2}$

2. Consider the curve $C$ given by the equation $y=x^2+1$. What is the slope of the secant line joining $P$ and $Q$ on $C$ where $x_P=-1$ and $x_Q=3$?

   a) 1

   b) 2

   c) 3

   d) 4

3. Consider the curve $\mathcal{L}$ given by the equation $y=x^2-x+12$. What is the slope of the tangent to the curve at $x=2$?
4. 
   a) 1

   b) 2

   c) 3

   d) 4

5. Consider the curve $\mathcal{Q}$ given by the equation $y=-2x^3+4x^2+4x$. What is the gradient of the curve at $x=1$?
   a) 2

   b) 4

   c) 6

   d) 8

6. Given $y = x(x^2-4)$, find $y'$.
   
   a) $y' = 1(2x)$

   b) $y' = x^2-4x$

   c) $y' = 3x^2 - 4$

   d) None of the above

7. Given $y=4^3$, find $y'$.
   
   a) $y'=0$

   b) $y'=3(4^2)$

   c) $y'=64$

   d) None of the above

8. The gradient of $y=x^3$ is $3$ at
  
   a) $x=0$ only
 
   b) $x=1$ or $x=-1$
 
   c) $x=1$ only

   d) $x=0$ or $x=1$

9.  The equation of the normal line to the curve $C$ given by $y=x+\sqrt{x}$ at $x=1$ is:
 
   a) $3y+2x=-8$
 
   b) $3y-2x=8$
 
   c) $3y+2x=8$
 
   d) $3y-2x=-8$

10. Find, to one decimal place, the gradient of $y=\sqrt{x^2+9}$ when $x=2$.
 
   a) 0.6
  
   b) 1.2
   
   c) 1.6
   
   d) 2.4

11. Given $y=\frac{1}{\sqrt{x+1}}$, find $y'$.
   
    a) $y' = \frac{1}{(x+1)\sqrt{x+1}}$
   
    b) $y' = \frac{-1}{(x+1)\sqrt{x+1}}$
   
    c) $y' = \frac{1}{2(x+1)\sqrt{x+1}}$
   
    d) $y' = \frac{-1}{2(x+1)\sqrt{x+1}}$

12. The equation of the tangent line to the curve $C$ given by $y=x+\sqrt{x}$ at $x=1$ is:
   
    a) $2y+3x=1$
   
    b) $2y-3x=1$
   
    c) $2y-3x=-1$
   
    d) $2y+3x=-1$

13. Find the point on $y=x^2$ where the tangent is parallel to $y=16x+5$.
   
    a) $(1,1)$
   
    b) $(2,4)$
   
    c) $(4,16)$
   
    d) $(8,64)$

14. If $u, v,$ and $w$ are functions of $x$ and $y=uvw$ then
   
    a) $y'=u'v'w'$
   
    b) $y'=u'v'w + uvw'$
   
    c) $y'=u'vw + uv'w + uvw'$
   
    d) None of the above

15. The graph of $y=-2x^2+3x+1$ crosses the $y$-axis at the point $P$. Find the equation of the normal to the curve at $P$.
   
    a) $3y+x=-3$
   
    b) $y+3x=1$
   
    c) $y-3x=1$
   
    d) $3y+x=3$

# Chapter 3 - Work Book
## 3.1. The Derivative
### 3.1.1. The gradient of a curve
1. Find the gradient of $y = 4x^2$ at $P(1, 4)$ by performing the following steps.

a) Take successive values of the variable point Q's abscissa to be 0, 0.2, 0.4, 0.6, 0.8, 0.9, 0.95, 0.99, and 0.999.

b) Evaluate the gradients of the secants $\overline{PQ}$.

c) Observe the limiting value of the gradients of the secants $\overline{PQ}$.

2. Find the gradient of $y = 2x^3$ at $P(1, 2)$ by performing the same steps as in #1.

3. Find the gradient of $y = x^2 + 4$ at $P(0, 4)$ by performing the same steps as in #1. In this case, take the successive values of the variable point Q's abscissa to be 1, 0.5, 0.4, 0.2, 0.1, 0.05, 0.02, 0.01, and 0.001.

4. $P(2, 8)$ is a point on the curve (C) given by: $y = x^2 + 2x$. Let Q be a variable point on (C) that is approaching P on the curve, find the gradient of $\overline{PQ}$ and deduce the gradient of the curve (C) at point P.

### 3.1.2. The derived function
1. Find the derived function of $y = 4x^2$ at $P(1, 4)$ by performing the following steps.

a) Take the variable point Q to have abscissa $1 + h$ and evaluate its ordinate.

b) Evaluate the vertical change from P to Q and note that the horizontal change is $h$.

c) Evaluate the gradients of the secants $\overline{PQ}$ and simplify the expression.

d) Set $h = 0$ and simplify.

2. Find the derived function of $y = 2x^3$ at $P(1, 2)$ by performing the same steps as in #1.

3. Find the derived function of $y = x^2 + 4$ at $P(0, 4)$ by performing the same steps as in #1. In this case, the abscissa of the variable point Q must be taken to be $0 + h = h$.

4. Find the derived function of $y = 4x^2$ at $P(x, 4x^2)$ by performing the following steps.

a) Take the variable point Q to have abscissa $x + h$ and evaluate its ordinate.

b) Evaluate the vertical change from P to Q and note that the horizontal change is $h$.

c) Evaluate the gradients of the secants $\overline{PQ}$ and simplify the expression.

d) Set $h = 0$ and simplify.

5. Find the gradient functions of the following curves.

a) $y = x^{10}$

b) $y = x^4$

c) $y = x$

6. Find $\frac{dy}{dx}$

a) $xy = 1$

b) $x^3y = 1$

7. Find the derived function of:

a) $y = x^8$

b) $y = x^{12}$

c) $y = \frac{1}{x}$

d) $y = \frac{x^3}{\sqrt{x}}$

e) $y = x\sqrt{x}$

f) $y = \sqrt[3]{x^2}$

**Challenging exercise**

If $n$ is a natural number and $y = x^n$, prove that $\frac{dy}{dx} = nx^{n-1}$.

### 3.1.3. The derivative of a polynomial function

1. Find the gradient function.

a) $y = 5x^2 + 3$

b) $y = 44$

c) $y = 5x^3 - 3x$

2. Find the derived function $f'(x)$.

a) $f(x) = 3x^6 - 2x^4 - x^3 + x^2 + 10$

b) $f(x) = 2x^3 + \frac{1}{3}x^2 - \frac{1}{4}x - 2x^{-2} + 5$

c) $f(x) = -3x^4 + 2x^3 - x^2 + 3x - 3$

d) $f(x) = \frac{1}{4}x^4 + \frac{1}{3}x^3 - \frac{1}{2}x^2 + 1$

e) $f(x) = ax^4 + bx^3 + cx^2 + d$

f) $y = 3x^2 + 2$

g) $f(x) = \frac{10x^5 + 3x^2}{2x^3}$

h) $f(x) = 2x(3x^2 - 4)$

i) $y = 1 - \frac{1}{x^3}$

j) $y = (x + \frac{1}{x})^3$

k) $f(x) = \frac{6x^5 + 3x^3 + x^2}{2x^2}$

3. Evaluate.

a) $\frac{d}{dx}(4 - 7x - 4x^2 + 5x^4)$

b) $\frac{d}{dx}(x^3 - a^3 - \frac{8}{x})$; $a$ is constant.

c) $\frac{d}{dy}(y^2 + 4y)$

d) $\frac{d}{dt}(t^3 - 6t^2 + 4t - 1)$

4. Differentiate.

a) $f(x) = -x$

b) $f(x) = a^3$, ($a$ = constant)

c) $f(x) = 3x^5 - 6x + 10$

d) $f(x) = \frac{1}{3}x^3 + 2bx^2 - cx + d$

e) $f(x) = 3(x^3 + x^2 + 1)$

f) $f(x) = \frac{(x-3)(x+3)}{9}$

g) $f(x) = 2 - 9x + 6x^3 + 5x^4$

h) $f(x) = \frac{4}{x} - \frac{x}{5}$

5. Find the gradient at the given value of $x$.

a) $y = x^3 - 2x^2 + 5$; $x = 2$

b) $y = x^2 - \frac{x}{2}$; $x = 1$

c) $y = (9x - 5)^2$; $x = \frac{1}{3}$

d) $y = 20x + 14$; $x = 7$

6. Find the gradient of $y = 3x^2 - 2x - 9$ at the point $(1, -8)$.

7. Find the gradient of $y = 4x^3 + 2x - 12$ at the point $(2, 24)$.

8. Find $a$ and $b$ if $P(a, b)$ belongs to the given curve and satisfies the given condition.

a) $y = 2x^2$; $y' = 8$

b) $y = x(3-x)$; $y' = 3$

c) $y = x^2 - 3x + 1$; $y' = 0$

d) $y = 3x^2 + 4x - 5$; $y' = \frac{1}{3}$

9. Find the point on the curve of $y = 1 - x^2$ at which the tangent is parallel to the graph of $y = 2x$.

10. Find the y-coordinate, and the gradient, at the point whose abscissa is given.

a) $y = 3x^2 - 4x + 7$, $x = 3$

b) $y = x^3 + 3x + 1$, $x = 0$

c) $y = \frac{1}{2}x^2 - 2x + 3$, $x = \frac{1}{3}$

d) $y = (2x+3)(x-4)$, $x=4$

e) $y = \frac{3}{2}x^3 - \frac{2}{3}x^2$, $x = \frac{4}{3}$

f) $y = (3x-4)^3$, $x = \frac{1}{2}$

11. Find the coordinates of the point at which the gradient has the given value.

a) $y = 2x^2$; gradient = 20

b) $y = 3x^2$; $\frac{dy}{dx} = 12$

12. Find the values of $x$ for which the gradient function of the curve $y = 2x^3 - x^2 - 3$ is zero.

13. Given Functions $f$ and $g$ by $f: x \to 2x-1$ and $g: x \to 3x^2-1$.

a) Find the functions $f'$ and $g'$.

b) Calculate the values of $f'(-2)$ and $g'(2)$.

c) If $h = gf$, find $h(x)$ and $h'(x)$.

### 3.1.4. Tangents and normals to a curve
1. Find the equation of the tangent to the curve of the given equation at the points corresponding to the given values of $x$.

a) $y = 2x^3 - 3x + 1$; $x = -1$

b) $y = 1 - 4x^2 - 2x^4$; $x = 0$

2. Find the equation of the tangent to the curve $y = x^2 + x - 2$ at the points where it cuts the x-axis.

3. Find the equation of the tangent to the curve $y = x^4 - 3x^2 - 2$ at the point of intersection with the y-axis.

4. Find the equation of the tangent and normal to the curve C: $y = x - 2x^3$ at $(-1, 1)$.

5. Find the equations of the tangents to the curve $y = \frac{4}{3}x^3 + 5x^2 + 2x + 12$ which are parallel to the line $y = -4x + 2$.

6. Find the equations of the tangents and the normals to the curve whose equation is given at the point whose abscissa is indicated.

a) $y = 2x^3 - 3x + 1$, $x = -1$

b) $y = 1 - 4x^2 - 2x^4$, $x = 0$

7. Find the equations of the tangent(s) and the normal(s) to the curve $y = x^2 + x - 2$ at the point(s) where the curve cuts the x-axis.

8. Find the equation of the tangent to the curve $y = x^4 - 3x^2 - 2$ at the point of intersection with the y-axis.

9. Find the equations of the tangents and the normals to the following curves at the points corresponding to the given values of $x$.

a) $y = 5 - 3x^2$, $x = 3$

b) $y = 3x^2 + 2$, $x = 4$

c) $y = x - 2x^3$, $x = -2$

d) $y = 1 - x^2 + x$, $x = -1$

10. Find the equations of the tangent(s) and the normal(s) to the curve $y = 2x(x + 4)^2$ at the point(s) where it cuts the x-axis.

11. Find the equation of the tangent to the curve $y = 2x^3 - 4x^2 + 2$ at the point of intersection with the y-axis.

12. Find the equation of the tangent to the curve $y = x^3 + x^2 + 1$ at the point $(1, 1)$. Find the coordinates of another point on the curve where the tangent is parallel to that at the point $(1, 1)$.

13. Find the equation of the tangent at the point $(1, -1)$ to the curve $y = 1 - 3x^2 + x^3$. Does the tangent to the curve at $(1, -1)$ intersect the curve again?

14. Find the coordinates of the points of intersection of the line $y = \frac{1}{3}x$ with the curve $y = (1-x)(x+x^2)$. If these points are in order M, N, P, where $x_M < x_N < x_P$, show that:

a) The tangents to the curve at M and P are parallel.

b) The tangent at N is perpendicular to them.

15. The curve $y = (x-2)(x+3)(x-4)$ cuts the x-axis at the points M, N and P, where $x_M < x_N < x_P$. Find:

a) The equations of the tangents at points M, N and P.

b) The equation of the normal to the graph at N.

16. a) Differentiate $y = 3x^2 - x + 8$.

b) Hence, or otherwise, determine two points on the curve $y = 3x^2 - x + 8$ at which the gradient of the tangent to the curve is 8.

c) Find the equations of the tangent and the normal to the curve $y = 3x^2 - x + 8$ at the point on the curve where $x = 3$.

## 3.2. Rules of Differentiation
### 3.2.1. The sum and constant multiple rule
1. Given $y$ find $y'$.

a) $y = x + \frac{1}{x}$

b) $y = x^2 + \frac{1}{x}$

c) $y = x^3 + \frac{1}{x}$

d) $y = x + \sqrt{x}$

e) $y = x^2 + x + 1 + \sqrt{x}$

f) $y = x^3 + \frac{1}{\sqrt{x}}$

2. Given $y$ find $y'$.

a) $y = 2x + \frac{3}{x^2}$

b) $y = \frac{1}{2}x^2 + \frac{2}{x}$

c) $y = 7x^3 + \frac{4}{x} + 2\sqrt{x}$

d) $y = 2x + 3\sqrt{x}$

e) $y = 4x^2 + 4x + 1 + 2\sqrt{x}$

f) $y = 5x^3 + \frac{4}{\sqrt{x}}$

3. Given $y$ find $\frac{dy}{dx}$.

a) $y = 2x - \frac{3}{x}$

b) $y = \frac{1}{2}x^2 - \frac{2}{x} + \sqrt{x}$

c) $y = 3x^2 + \frac{2}{x^2} - 2\sqrt{x}$

d) $y = 2x - \frac{2}{x}$

e) $y = 4x^2 - \frac{4}{x}$

f) $y = 3x^3 - \frac{4}{\sqrt{x}}$

4. Find the gradient of the curve whose equation is given at the point whose abscissa is indicated.

a) $y = 2x - \frac{3}{x}$; $x=1$

b) $y = \frac{1}{3}x^3 - \sqrt{x}$; $x=4$

c) $y = -x^2 - 2\sqrt{x}$; $x=9$

d) $y = 4x + \frac{4}{x}$; $x=-1$

e) $y = 2x^2 + 1$; $x=0$

f) $y = 3x^2 - 2x + 1$; $x=0$

### 3.2.2. The product rule
1. Given $y$ find $y'$.

a) $y = (x+1)(1 - \frac{1}{\sqrt{x}})$

b) $y = (1 + \sqrt{x})(x-x^2)$

c) $y = (x^{2/3} + x^{-1/2})(x - \sqrt{x})$

2. Given $y = (x+1)(x-1)$.

a) Using the product rule, find $y'$.

b) Expand the right hand side of the expression for $y$.

c) Use the expression obtained in b), find $y'$.

d) Show that the answers in a) and c) are identical.

3. Given $y = (x+1)(x^2-x+1)$.

a) Using the product rule, find $y'$.

b) Expand the right hand side of the expression for $y$.

c) Use the expression obtained in b), find $y'$.

d) Show that the answers in a) and c) are identical.

**Critical thinking**

4. Suppose $u$, $v$, and $w$ are functions of $x$ and let $y=uvw$.

a) Show that $y' = (uv)'w + (uv)w'$.

b) Find $y'$ in terms of $u, v, w, u', v'$, and $w'$.

c) State, in words, how the product rule can be extended to products of three or more functions of $x$.

**Critical thinking**

5. Let $y = ku$ where $k$ is a constant. Apply the product rule of differentiation and show that in this case it reduces to the constant multiple rule.

6. Given $y$, find the gradient of the curve whose equation is given at the point whose abscissa is indicated.

a) $y = x(1 + \sqrt{x})$; $x=1$

b) $y = (2x - x^2)(x + x^3)$; $x=1$

**Challenging exercise**

7. If $\begin{vmatrix} a & b \\ c & d \end{vmatrix} = ad-bc$,

show that if $f(x) = \begin{vmatrix} u(x) & v(x) \\ w(x) & q(x) \end{vmatrix}$ then $f'(x) = \begin{vmatrix} u'(x) & v'(x) \\ w(x) & q(x) \end{vmatrix} + \begin{vmatrix} u(x) & v(x) \\ w'(x) & q'(x) \end{vmatrix}$

### 3.2.3. The quotient rule
1. Given $y$ find $y'$.

a) $y = \frac{x}{x-1}$

b) $y = \frac{x+1}{x-1}$

c) $y = \frac{x^2+1}{x^2-1}$

d) $y = \frac{x\sqrt{x}}{x^2+1}$

e) $y = \frac{x^3-1}{x^3+1}$

f) $y = \frac{2x}{x^2+1}$

2. Given $y$ find $y'$.

a) $y = \frac{x(1-\sqrt{x})}{x^2+1}$

b) $y = \frac{x+1}{(x-1)(3-\sqrt{x})}$

c) $y = \frac{2+\sqrt{x}}{x+2}$

3. Given that $f(x) = 2x - 1 + \frac{1}{x+1}$, $x \neq -1$, find the values of $x$ for which $f'(x) = 0$.

4. Given $y = \frac{x^2-1}{x-1}$, $x \neq 1$.

a) Using the quotient rule, find $y'$.

b) Simplify the expression for $y$.

c) Use the expression obtained in b), find $y'$.

d) Show that the answers in a) and c) are identical.

5. Given $y = \frac{x^3-1}{x-1}$, $x \neq 1$.

a) Using the quotient rule, find $y'$.

b) Simplify the expression for $y$.

c) Use the expression obtained in b), find $y'$.

d) Show that the answers in a) and c) are identical.

### 3.2.4. The chain rule
1. Differentiate with respect to $x$.

a) $y = (3x-4)^8$

b) $y = 2(3x^2+4)^8$

c) $y = (3-x)^{1/2}$

2. Find $\frac{dy}{dx}$.

a) $y = \frac{3}{3x+2}$

b) $y = \frac{3}{\sqrt{3x+2}}$

c) $y = \frac{1}{\sqrt{x^2+1}}$

3. Differentiate.

a) $(3x^2-7)^5$

b) $(3x^2-5x^4)^{1/3}$

c) $(3x^2-5x)^{2/3}$

d) $\frac{1}{2(3x^2+2)^3}$

e) $\frac{1}{(x^2-7x)^7}$

f) $(2x^3-x)^2$

4. Find $y'$.

a) $y = x^2(x-1)^5$

b) $y = x^3(x+1)^6$

c) $y = x^{-2}(x^2+1)$

d) $y = (2x-7)^{-3}$

e) $y = (3x+1)^{-2/3}$

f) $y = \frac{1}{\sqrt{2x-3}}$

g) $y = (x+1)^2(x^2-1)$

h) $y = \frac{x^2+1}{(x+1)^2}$

i) $y = x^2(1-\frac{1}{x})$

j) $y = \sqrt{\frac{x}{1-x^2}}$

k) $y = \frac{(x-1)^2}{\sqrt{x}}$

l) $y = \sqrt{x^2+2} - \sqrt{x^3+3}$

m) $y = \sqrt{3x^2-2} + 3x^5 - 2x^3 + 1$

n) $y = (-3x^2+2)^5 + 3x - 10x^2$

5. Differentiate with respect to $x$.

a) $f(x) = (1+x^2)^3(1-x^2)$

b) $g(x) = (1-x^2)^2(1-x^3)$

c) $h(x) = (x^2+1)\sqrt{x^2-1}$

d) $k(x) = \frac{x}{\sqrt{x+1}}$

e) $f(x) = x^3\sqrt{1+x^3}$

f) $g(x) = \frac{x^3}{\sqrt{1-x^2}}$

6. Given $y = \sqrt{ax+b}$, where $a$ and $b$ are constant real numbers. Find $\frac{dy}{dx}$.

7. Find $\frac{dy}{dx}$.

a) $y = \frac{\sqrt{x}}{\sqrt{x+1}}$

b) $y = (x^4-2)(x-2)^{-4}$

8. Differentiate with respect to $x$.

a) $y = \frac{x^n}{x^{2n}}$

b) $y = x^{-4-2}$

c) $y = 3(x^5)^{-3}$

d) $y = \sqrt[n]{x^n}$

9. Differentiate with respect to $x$ and simplify.

a) $y = (x^2-2)^4$

b) $y = \sqrt{(2x^3-3)^2}$

c) $y = \sqrt{(x-1)^3}$

d) $y = \frac{x}{x+\sqrt{x}}$

e) $y = \frac{x^2+2}{(x+2)^2}$

f) $y = \frac{1}{\sqrt{2x-x^2}}$

g) $y = \frac{x-2}{x^2-1}$

h) $y = \frac{x+1}{\sqrt{x-1}}$

i) $y = \sqrt{\frac{x}{x-1}}$

j) $y = \frac{(x-1)^3}{x^3-1}$

k) $y = \sqrt{\frac{(x+2)^3}{x-1}}$

l) $y = \sqrt{\frac{x+1}{x+2}}$

**Critical thinking**

10. Prove the quotient rule by expressing $y = \frac{u}{v}$ as a product $y = u(v^{-1})$.

# Chapter Review - Work Book
## Section 1

1. Find the derived function of $y = 5x^2$ at $P(2, 20)$ by performing the following steps.

a) Take the variable point Q to have abscissa $2 + h$ and evaluate its ordinate.

b) Evaluate the vertical change from P to Q and note that the horizontal change is $h$.

c) Evaluate the gradients of the secants $\overline{PQ}$ and simplify the expression.

d) Set $h = 0$ and simplify.

2. Find $\frac{dy}{dx}$ in each of the following cases.

a) $y = \sqrt{x}$

b) $y = \frac{\sqrt{2x}}{x^2}$

c) $y = \frac{(2\sqrt{x}-3x)(\sqrt{x}+x)}{3x}$

3. Find the gradient function of $y = 12x^2 + 3x - 17$.

4. Find the derived function of $f(x) = 2x^4 - 5x^3 - 2x^2 + \frac{2}{x^3}$.

5. Evaluate $\frac{d}{dx}(2 - 3x + 3x^2)$.

6. Differentiate $f(x) = 3ax^3 + 2bx^2 + cx + d$.

7. Find the gradient of $y = x^2 - 5x + 3$ at $x = -1$.

8. Find $a$ and $b$ if $P(a, b)$ belongs to $y = 5x^2 + 1$ and $y'|_{x=a} = -2$.

9. Find the equation of the tangent to the curve $y = x^3 - x^2 - 4x + 4$ at the point $(-1, 6)$.

10. Consider the curve (C): $y = x^3 - x^2 - x - 1$.

a) Find the coordinates of the points at which the tangent(s) to the curve are horizontal lines. Hence, find the equations of the tangents and the normals to the curve at these points.

b) Find the coordinates of the point(s) of the curve at which the tangent to the curve is parallel to line (L): $y-7x+2=0$.

11. Given that the y-intercept of the curve (D): $y = ax^3 + bx + c$, $a \neq 0$, is 4 and that the gradient of the curve (D) at $(1, 2)$ is 3. Find the values of $a$, $b$ and $c$ and hence find the equation of the tangent and the equation of the normal to the curve at point $M(3, t)$.

## Section 2
Differentiate with respect to $x$ and simplify.

a) $y = (2x-1)^4 + 3x^2 - 6$

b) $y = -x^3 + \sqrt{2-3x^2}$

c) $y = \frac{(3x+2)^2}{2x-1}$

d) $y = (x^2+3x)^5(3x-1)^3$

e) $y = -\frac{\sqrt{x}}{2x+1}$

f) $y = x^2\sqrt{x^3+1}$

g) $y = x^2(x-1)^{1/4}$

h) $y = (x+1)^{3/2}(x-1)^{1/2}$

i) $y = x(x+1)^{3/2}$

j) $y = \sqrt{(x^2+1)(x-2)^3}$

k) $y = (1-x^2)^{3/2}\sqrt{1-2x^3}$

l) $y = x^2\sqrt{x^2-1}$

## Additional Exercises
1. Find the gradient of the curve $y = \frac{9}{x^2-4x}$ at the point where $x=3$.

2. A curve has equation $y = \frac{k}{x}$. Given that the gradient of the curve is $-1$ when $x=4$, find the value of the constant $k$.

3. A curve has equation $y = 2x^3 - 2x^2 + 5x + 8$. Show that the gradient of the curve is never negative.

4. The diagram below shows part of the curve $y = 3 - \frac{15}{2x+3}$, which crosses the x-axis at A and the y-axis at B. The normal to the curve at A crosses the y-axis at C.

![Graph of a curve y=3 - 15/(2x+3) intersecting axes at A and B, with a normal line at A intersecting the y-axis at C.](./media/image_1.png)

(a) Show that the equation of the line AC is $5x+6y=5$.

(b) Find the length of $\overline{BC}$.

5. A curve has equation $y = \frac{10}{3x-4}$ and $P(3, 2)$ is a point on the curve.

(a) Find the equation of the tangent to the curve at P.

(b) Find the angle that this tangent makes with the x-axis.

6. The equation of a curve is $y = x^3 - 4x + 6$ and the equation of a line is $y + 2x = 9$. The curve and the line intersect at the points A and B.

(a) The midpoint of $\overline{AB}$ is M. Show that the coordinates of M are $(1, 7)$.

(b) Find the coordinates of the point Q on the curve at which the tangent is parallel to the line $y+2x=9$.

(c) Find the distance $\overline{MQ}$.

7. The equation of a curve is $y = 7 - \frac{9}{x}$.

(a) Show that the equation of the normal to the curve at the point $P(3, 4)$ is $x+y=7$. This normal meets the curve again at the point Q.

(b) Find the coordinates of Q.

(c) Find the length of $\overline{PQ}$.

8.
![Graph showing the intersection of the line 2y = x + 2 and the curve y = x^2 - 5x + 7 at points A and B.](./media/image_2.png)

(a) The diagram shows the line $2y = x + 2$ and the curve $y = x^2 - 5x + 7$, which intersect at the points A and B. Find

(i) the x-coordinates of A and B,

(ii) the equation of the tangent to the curve at B,

(iii) the acute angle, in degrees to 1 decimal place, between this tangent and the line $2y=x+2$.

(b) Determine the set of values of $k$ for which the line $2y=x+k$ does not intersect the curve $y=x^2-5x+7$.

9. The equation of a curve is $y = 7+3x-x^2$.

(a) Show that the equation of the normal to the curve at the point $(2, 9)$ is $y=x+7$.

(b) Given that the normal meets the coordinate axes at points A and B, find the coordinates of the midpoint of $\overline{AB}$.

(c) Find the coordinates of the point at which the normal meets the curve again.