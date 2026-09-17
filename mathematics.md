---
layout: page
title: Mathematics
permalink: /mathematics/
---

# Mathematics

Welcome to my Mathematics page — where I document topics I teach and explore, from basic rules to worked examples.

<details markdown="1">
<summary><span style="color:#2d7a4f; font-size:1.1em"><strong>Inverse Trigonometric Functions</strong></span></summary>

<iframe width="560" height="315" src="https://www.youtube.com/embed/tG60Mif8BOs?si=X-kUBXG63Mw25tCw" title="Inverse Trigonometric Functions" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

This video explains inverse trigonometric functions — arcsin, arccos, and arctan — and how they differ from regular trig functions like sin, cos, and tan.

### <span style="color:#333333">**Function vs. Inverse Function**</span>

A function $f$ takes an input and gives one output: $f(x) = y$. An inverse function $f^{-1}$ reverses that — it takes the output and gives back the original input: $f^{-1}(y) = x$.

Key idea: if $f$ and $f^{-1}$ undo each other, then $f^{-1}(f(x)) = x$.

**Important condition:** a function only has an inverse if it's *one-to-one* (each output comes from exactly one input). This matters a lot for trig functions, since $\sin(x)$, $\cos(x)$, $\tan(x)$ repeat their values over and over — so we have to **restrict their domain** before we can invert them.

### <span style="color:#333333">**Notation**</span>

- $f^{-1}(x)$ means "the inverse function of $f$" — **not** $\frac{1}{f(x)}$
- Same for trig: $\sin^{-1}(x) \neq \frac{1}{\sin(x)}$. That's why many textbooks prefer **arcsin, arccos, arctan** — it avoids the confusion entirely

### <span style="color:#333333">**Arcsine, Arccosine, Arctangent**</span>

| Function | Restricted domain of original | Range of inverse |
|---|---|---|
| $\arcsin(x) = \sin^{-1}(x)$ | $\sin(x)$ restricted to $[-\frac{\pi}{2}, \frac{\pi}{2}]$ | $[-\frac{\pi}{2}, \frac{\pi}{2}]$ |
| $\arccos(x) = \cos^{-1}(x)$ | $\cos(x)$ restricted to $[0, \pi]$ | $[0, \pi]$ |
| $\arctan(x) = \tan^{-1}(x)$ | $\tan(x)$ restricted to $(-\frac{\pi}{2}, \frac{\pi}{2})$ | $(-\frac{\pi}{2}, \frac{\pi}{2})$ |

In plain terms: $\arcsin(x)$ answers the question "what angle has a sine of $x$?" — same logic for the other two.

**Example:** $\sin(30°) = 0.5$, so $\arcsin(0.5) = 30°$.

</details>

<details markdown="1">
<summary><span style="color:#2d7a4f; font-size:1.1em"><strong>Basic Differentiation Rule</strong></span></summary>

<iframe width="560" height="315" src="https://www.youtube.com/embed/o_aIts2oi5o" title="Basic differentiation rule" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

This video walks through the basic differentiation rule, $\frac{d}{dx}(x^{n}) = nx^{n-1}$, and how it applies to polynomial functions.

### <span style="color:#333333">**Summary & Examples**</span>

- Derivative of $y=f(x)$ with respect to $x$ is denoted by $\frac{dy}{dx}, \frac{df}{dx}, f^{\prime}(x)$.

### <span style="color:#333333">**Power Rule**</span>

(a) $f(x)=x^{6}$<br>
(b) $g(q)=\sqrt{q}$<br>
(c) $h(p)=\frac{1}{p^{2}}$<br>

**Solution:**

(a) $$\frac{df}{dx}=6x^{5}$$

(b) $$g(q)=\sqrt{q}=q^{1/2} \Rightarrow g^{\prime}(q)=\frac{1}{2}q^{-1/2}$$

(c) $$h(p)=\frac{1}{p^{2}}=p^{-2} \Rightarrow h^{\prime}=-2p^{-3}$$


### <span style="color:#333333">**Constant Multiple Rule**</span>

(a) $h(x)=5x^{3}$
<div style="margin-left:20px">$$\frac{dh}{dx}=5\frac{d}{dx}(x^{3})=5(3)x^{2}=15x^{2}$$</div>

(b) $g(x)=2\ln x$
<div style="margin-left:20px">$$\frac{dg}{dx}=2\frac{d}{dx}(\ln x)=2\left(\frac{1}{x}\right)=\frac{2}{x}$$</div>

</details>

<details markdown="1">
<summary><span style="color:#2d7a4f; font-size:1.1em"><strong>Basic Differentiation - Product Rule</strong></span></summary>

<iframe width="560" height="315" src="https://www.youtube.com/embed/NA7OLSLOZfE" title="Basic Differentiation - Product Rule" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

An introduction to the Product Rule in differentiation — how to find the derivative of a function that is the product of two other functions.

### <span style="color:#333333">**Worked Example**</span>

Find the derivative of $f(x)=x^{2}\sin(x)$.

**Solution:**

The product rule states that for two differentiable functions $u(x)$ and $v(x)$:

$$\frac{d}{dx}[u(x)\cdot v(x)]=u^{\prime}(x)v(x)+u(x)v^{\prime}(x)$$

Step 1 : Identify the components:
   - $u(x)=x^{2} \Longrightarrow u^{\prime}(x)=2x$
   - $v(x)=\sin(x) \Longrightarrow v^{\prime}(x)=\cos(x)$

Step 2 : Apply the product rule:

$$f^{\prime}(x)=(2x)\sin(x)+x^{2}\cos(x)$$

Step 3 : Simplify (optional):

$$f^{\prime}(x)=x(2\sin(x)+x\cos(x))$$

</details>
<details markdown="1">
<summary><span style="color:#2d7a4f; font-size:1.1em"><strong>Basic Differentiation - Quotient Rule</strong></span></summary>

<iframe width="560" height="315" src="https://www.youtube.com/embed/_H7BH0NlBRk?si=NzduFHgCVRONfQDJ" title="Basic Differentiation - Quotient Rule" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

The Quotient Rule tells you how to differentiate a function that is one function divided by another.

### <span style="color:#333333">**Formula**</span>

$$\frac{d}{dx}\left[\frac{u(x)}{v(x)}\right] = \frac{u'(x)\,v(x) - u(x)\,v'(x)}{[v(x)]^2}$$

A common way to remember it: **"low d-high minus high d-low, over the square of what's below"** — where "high" = $u$ (numerator) and "low" = $v$ (denominator).

### <span style="color:#333333">**How to Apply It**</span>

**Step 1 — Identify the components:** Split the function into $u(x)$ (top) and $v(x)$ (bottom), then find $u'(x)$ and $v'(x)$ separately.

**Step 2 — Plug into the formula:**
$$f'(x) = \frac{u'v - uv'}{v^2}$$

**Step 3 — Simplify** (combine like terms in the numerator, factor if possible).

### <span style="color:#333333">**Worked Example**</span>

Find the derivative of $f(x) = \dfrac{\sin(x)}{x}$.

- $u(x) = \sin(x) \Rightarrow u'(x) = \cos(x)$
- $v(x) = x \Rightarrow v'(x) = 1$

$$f'(x) = \frac{\cos(x)\cdot x - \sin(x)\cdot 1}{x^2} = \frac{x\cos(x) - \sin(x)}{x^2}$$

**Common mistake to watch for:** the order in the numerator matters — it's $u'v - uv'$, not $uv' - u'v$. Swapping the order flips the sign of the whole answer.

</details>

<details markdown="1">
<summary><span style="color:#2d7a4f; font-size:1.1em"><strong>Integration of Fundamental Functions</strong></span></summary>

Integration is the reverse of differentiation. For each standard function, remember its antiderivative plus a constant $C$ (since the derivative of any constant is 0).

### <span style="color:#333333">**Standard Functions**</span>

| $f(x)$ | $\int f(x)\,dx$ |
|---|---|
| $x^k$ | $\dfrac{x^{k+1}}{k+1} + C$ (Power Rule, $k \neq -1$) |
| $e^x$ | $e^x + C$ |
| $\dfrac{1}{x}$ | $\ln\lvert x \rvert + C$ |
| $\sin x$ | $-\cos x + C$ |
| $\cos x$ | $\sin x + C$ |

**Key points to note:**

- $x^k$ rule breaks when $k = -1$ (that's exactly when $1/x$ takes over, giving $\ln|x|$ instead)
- $e^x$ is unique — it integrates to itself
- Sign flips for $\sin x$: integrating gives $-\cos x$, not $+\cos x$ (easy to mix up)
- Always add $+C$ — dropping it is the most common mistake

**Example:** $\int t^3\, dt = \dfrac{t^4}{4} + C$

### <span style="color:#333333">**When a Function Doesn't Match a Standard Form**</span>

If the integral isn't directly one of these standard results, a technique is needed to reduce it to one. Three common methods (not an exhaustive list):

1. **Integration by Substitution** — rewrite the integral in terms of a new variable to simplify it into a standard form
2. **Integration by Parts** — used for a product of two functions
3. **Partial Fractions** — break a complex rational function into simpler fractions, then integrate each term using the standard results above

</details>

<details markdown="1">
<summary><span style="color:#2d7a4f; font-size:1.1em"><strong>Integration by Substitution (Recognition Method)</strong></span></summary>

This method works when the integrand contains a function $f(x)$ and its derivative $f'(x)$ together. Once you recognize the pattern, you can integrate directly — no formal substitution needed.

### <span style="color:#333333">**Three Standard Forms**</span>

**1.** $$\int \frac{f'(x)}{f(x)}\,dx = \ln\lvert f(x) \rvert + C$$

*Derivation:* since $\dfrac{d}{dx}\ln\lvert f \rvert = \dfrac{f'}{f}$, integrating both sides gives the result.

**2.** $$\int [f(x)]^n f'(x)\,dx = \frac{[f(x)]^{n+1}}{n+1} + C$$

*Derivation:* let $u = f(x)$, so $du = f'(x)\,dx$. This turns the integral into $\int u^n\,du = \dfrac{u^{n+1}}{n+1} + C$.

**3.** $$\int e^{f(x)} f'(x)\,dx = e^{f(x)} + C$$

*Derivation:* since $\dfrac{d}{dx}e^f = e^f \cdot f'$, integrating both sides gives the result.

### <span style="color:#333333">**Worked Example 1 — Recognition Method**</span>

$$\int \frac{e^{2x}}{e^{2x}-2}\,dx$$

**Step 1 — Identify $f(x)$ and $f'(x)$:**
Let $f(x) = e^{2x} - 2$, so $f'(x) = 2e^{2x}$.

**Step 2 — Rewrite the numerator to match $f'(x)$:**
$$e^{2x} = \frac{1}{2}f'(x)$$

**Step 3 — Apply Formula 1:**
$$\int \frac{e^{2x}}{e^{2x}-2}\,dx = \frac{1}{2}\int \frac{f'(x)}{f(x)}\,dx = \frac{1}{2}\ln\lvert e^{2x}-2 \rvert + C$$

**Key point:** the constant $\frac{1}{2}$ is pulled out to make the numerator match $f'(x)$ exactly — this adjustment step is the main skill to practice with the recognition method.

### <span style="color:#333333">**Worked Example 2 — Change of Variable**</span>

Not every integral fits the recognition shortcut directly. Sometimes it's clearer to formally substitute a new variable $u$, rewrite the *entire* integral in terms of $u$ (including $x$ itself), integrate, then substitute back.

$$\int x\sqrt{x+1}\,dx$$

**Step 1 — Choose the substitution:**
Let $u = x+1$, so $x = u-1$ and $du = dx$.

**Step 2 — Rewrite the whole integral in terms of $u$:**
$$\int x\sqrt{x+1}\,dx = \int (u-1)\sqrt{u}\,du = \int \left(u^{3/2} - u^{1/2}\right) du$$

**Step 3 — Integrate using the Power Rule:**
$$= \frac{2}{5}u^{5/2} - \frac{2}{3}u^{3/2} + C$$

**Step 4 — Substitute back $u = x+1$:**
$$\int x\sqrt{x+1}\,dx = \frac{2}{5}(x+1)^{5/2} - \frac{2}{3}(x+1)^{3/2} + C$$

**Key point:** unlike Example 1, here $x$ itself had to be rewritten in terms of $u$ (as $u-1$) before integrating — this is the defining feature of the change-of-variable method, as opposed to just spotting a ready-made $f$ and $f'$ pair.

</details>

<details markdown="1">
<summary><span style="color:#2d7a4f; font-size:1.1em"><strong>Integration by Parts</strong></span></summary>

<iframe width="560" height="315" src="https://www.youtube.com/embed/6QCrB3y9IyE?si=3dmHwrV7PNBzla4g" title="Integration by Parts" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

This video explains Integration by Parts — a technique for integrating a product of two functions when standard formulas or substitution don't directly work.

### <span style="color:#333333">**Formula**</span>

$$\int u\,dv = uv - \int v\,du$$

Used when integrating a product of two functions that doesn't fit substitution.

### <span style="color:#333333">**How to Choose u and dv**</span>

A common guide is **LIATE** — pick $u$ in this priority order: **L**ogarithmic, **I**nverse trig, **A**lgebraic, **T**rigonometric, **E**xponential. Whichever type appears first in that list becomes $u$; the rest becomes $dv$.

### <span style="color:#333333">**Worked Example**</span>

Find $\int x\,e^x\,dx$.

**Step 1 — Choose $u$ and $dv$:**
By LIATE, $x$ (algebraic) ranks above $e^x$ (exponential), so:
$$u = x, \quad dv = e^x\,dx$$

**Step 2 — Find $du$ and $v$:**
$$du = dx, \quad v = e^x$$

**Step 3 — Apply the formula:**
$$\int x\,e^x\,dx = x\,e^x - \int e^x\,dx$$

**Step 4 — Integrate what's left and simplify:**
$$\int x\,e^x\,dx = x\,e^x - e^x + C$$

**Key point:** the whole trick is choosing $u$ so that $\int v\,du$ ends up simpler than the original integral — here, differentiating $x$ down to $1$ (via $du$) is what made the leftover integral trivial.

</details>

<details markdown="1">
<summary><span style="color:#2d7a4f; font-size:1.1em"><strong>Solving Difference Equation</strong></span></summary>

<iframe width="560" height="315" src="https://www.youtube.com/embed/Kly41QaoB_U?si=U3AEcZLwW4LZ3Ikz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

**Example:** A sequence of numbers $x_1, x_2, x_3 \ldots$ is given by

$$x_{t+2}+3x_{t+1}+3x_{t}=0$$

Find an explicit formula for $x_t$:

### <span style="color:#333333">**Method 1: Apply Formula**</span>

Auxiliary equation: $m^{2}+3m+3=0$ where $a=1, b=3, c=3$

$$\left(\sqrt{\frac{c}{a}}\right)^{t}=\left(\sqrt{\frac{3}{1}}\right)^{t}=(\sqrt{3})^{t}$$

$$\theta=\cos^{-1}\left(-\frac{b}{2\sqrt{ac}}\right)=\cos^{-1}\left(-\frac{3}{2\sqrt{3}}\right)=\frac{5\pi}{6}$$

**Complementary function:**

$$x_{t}=\left(\sqrt{\frac{c}{a}}\right)^{t}[A\cos\theta t+B\sin\theta t]$$

$$x_{t}=(\sqrt{3})^{t}\left[A\cos\left(\frac{5\pi}{6}t\right)+B\sin\left(\frac{5\pi}{6}t\right)\right]$$

### <span style="color:#333333">**Method 2: Geometric Approach**</span>

Auxiliary Equation: $m^{2}+3m+3=0$ where $a=1, b=3, c=3$

![Angle diagram showing R, θ, and reference triangle](/blog/images/angle-diagram.png)

$$\cos\theta=\frac{\text{Adj}}{R}=\frac{-3/2}{\sqrt{3}}$$

$$\theta=\cos^{-1}\left(\frac{-3}{2\sqrt{3}}\right)=\frac{5\pi}{6}$$

<span style="font-size:0.85em">Complementary function $\Rightarrow x_{t}=(\sqrt{3})^{t}\left[A\cos\left(\frac{5\pi}{6}t\right)+B\sin\left(\frac{5\pi}{6}t\right)\right]$</span>

</details>


---

More topics will be added here as this page grows.
