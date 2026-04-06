Theorem:
Let $g:[0,1]^d$ be any L-Lipschitz function. Then for any error $\epsilon \gt 0$ $\exists$ a 3-layer ReLu network with $N=4d(\frac{L}{\epsilon})^d$ units such that $\int_{[0,1]^d} | f(x)-g(x) | dx \lt 2\epsilon$

**Theorem.** Let $f : \mathbb{R} \to \mathbb{R}$ be continuous. Then $f$ is integrable.

**Proof.** Since $f$ is continuous on a compact set, it is bounded. Therefore,

$$
\int_a^b f(x)\,dx
$$

exists. $\square$

$$
\begin{aligned}
y &= Wx + b \\
  &= W_2(W_1 x + b_1) + b_2
\end{aligned}
$$

### Theorem
Let $X$ be compact...

### Proof
...

> **Theorem.**
> Let $X$ be compact...

> **Proof.**
> ...

$\mathbb{R}$

A CNN layer consists of:
- A convolution operator $K * x$
- A bias term $b$
- A nonlinearity $\sigma$

Thus,

$$
y = \sigma(K * x + b)
$$

---

**Definition.** A CNN layer is a function

$$
f(x) = \sigma(K * x + b)
$$

where $K$ is a convolution kernel.

---

**Proposition.** Two CNN layers compose as:

$$
f_2(f_1(x)) = \sigma_2(K_2 * \sigma_1(K_1 * x + b_1) + b_2)
$$

---

**Proof.** Substitute $f_1$ into $f_2$ and simplify. $\square$

---

# Title of Document

Short description or abstract. Keep it tight and informative.

---

## 1. Introduction

State the goal clearly. Use inline math like $f(x) = x^2$ when it fits naturally in text.

---

## 2. Preliminaries

**Definition 2.1.** A function $f : \mathbb{R} \to \mathbb{R}$ is continuous if for all $\epsilon > 0$ there exists $\delta > 0$ such that

$$
|x - y| < \delta \implies |f(x) - f(y)| < \epsilon.
$$

**Remark.** Keep remarks short and informal when helpful.

---

## 3. Main Results

**Theorem 3.1.** Let $f$ be continuous on $[a,b]$. Then $f$ is integrable.

**Proof.** Since $f$ is continuous on a compact set, it is bounded. Hence the integral

$$
\int_a^b f(x)\,dx
$$

exists. $\square$

---

## 4. Structured Derivations

Use aligned equations for clarity:

$$
\begin{aligned}
y &= Wx + b \\
  &= W_2(W_1 x + b_1) + b_2 \\
  &= W_2 W_1 x + W_2 b_1 + b_2
\end{aligned}
$$

---

## 5. Key Example

A CNN layer can be written as:

$$
y = \sigma(K * x + b)
$$

A composition of two layers gives:

$$
y = \sigma_2\big(K_2 * \sigma_1(K_1 * x + b_1) + b_2\big)
$$

---

## 6. Lists for Clarity

A model consists of:
- Input $x$
- Parameters $\theta$
- Output $f_\theta(x)$

This prevents the “wall of text” problem without losing conciseness.

---

## 7. Proposition + Proof Pattern

**Proposition 7.1.** The composition of continuous functions is continuous.

**Proof.** Let $f$ and $g$ be continuous. Then for any $\epsilon > 0$, continuity of $g$ gives a $\delta_1$, and continuity of $f$ gives a $\delta_2$. Combining them yields continuity of $f \circ g$. $\square$

---

## 8. Notes / Intuition

> Use blockquotes for intuition or commentary.
>
> This is especially useful when explaining ideas informally without breaking the mathematical flow.

---

## 9. Section Break

---

## 10. Style Guidelines (for yourself)

- Inline math: `$...$`
- Display math for important equations:
  $$
  ...
  $$
- Use **bold labels** instead of LaTeX environments
- Keep proofs tight
- Use spacing (`---`) to separate ideas
- Prefer aligned equations over dense inline chains

---

## 11. Optional: Compact Kelley-Style Section

If you want dense exposition:

A function $f : X \to Y$ is continuous if for every open set $U \subseteq Y$, the preimage $f^{-1}(U)$ is open in $X$. In particular, if $X$ is compact and $f$ is continuous, then $f(X)$ is compact, and hence closed and bounded in $\mathbb{R}^n$.

---

## 12. Ending

Summarize briefly or leave clean.
