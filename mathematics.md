---
layout: page
title: Mathematics
permalink: /mathematics/
---

# Mathematics

Welcome to my Mathematics page — where I document topics I teach and explore, from basic rules to worked examples.

<details>
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

<details>
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

<details>
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

<details>
\section*{Function vs. Inverse Function}

A function $f$ takes an input and gives one output: $f(x)=y$.
An inverse function $f^{-1}$ reverses that - it takes the output and gives back the original input: $f^{-1}(y)=x$.

Key idea: if $f$ and $f^{-1}$ undo each other, then $f^{-1}(f(x))=x$.
Important condition: a function only has an inverse if it's one-to-one (each output comes from exactly one input). This matters a lot for trig functions, since $\sin (x), \cos (x), \tan (x)$ repeat their values over and over - so we have to restrict their domain before we can invert them.

Notation
\begin{itemize}
\item[-] $f^{-1}(x)$ means "the inverse function of $f$ " - not $\frac{1}{f(x)}$
\item[-] Same for trig: $\sin ^{-1}(x) \neq \frac{1}{\sin (x)}$. That's why many textbooks prefer $\arcsin$, arccos, arctan - it avoids the confusion entirely
\end{itemize}

\section*{Arcsine, Arccosine, Arctangent}

\begin{tabular}[t]{|l|l|l|}
\hline Function & Restricted domain of original & Range of inverse \\
\hline $\arcsin (x)=\sin ^{-1}(x)$ & $\sin (x)$ restricted to $\left[-\frac{\pi}{2}, \frac{\pi}{2}\right]$ & $\left[-\frac{\pi}{2}, \frac{\pi}{2}\right]$ \\
\hline $\arccos (x)=\cos ^{-1}(x)$ & $\cos (x)$ restricted to $[0, \pi]$ & $[0, \pi]$ \\
\hline $\arctan (x)=\tan ^{-1}(x)$ & $\tan (x)$ restricted to ( $-\frac{\pi}{2}, \frac{\pi}{2}$ ) & $\left(-\frac{\pi}{2}, \frac{\pi}{2}\right)$ \\
\hline
\end{tabular}

In plain terms: $\arcsin (x)$ answers the question "what angle has a sine of $x$ ?" - same logic for the other two.

Example: $\sin \left(30^{\circ}\right)=0.5$, so $\arcsin (0.5)=30^{\circ}$.
</details>
---

More topics will be added here as this page grows.
