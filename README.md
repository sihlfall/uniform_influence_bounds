# Uniform Bounds on the Influence of Independent and Pairwise Independent Variables

*Johannes Gerd Becker*

v1.0, 2026/10/19

For independent random variables $X_1,\ldots,X_n$,
an arbitrary random variable $Z$, and a suitable class
$\mathcal F$ of functions, we show that

$$
\mathrm E\sum_{i=1}^n \mathrm{esssup}_{f\in\mathcal F}
\bigl(\mathrm E[f(Z)\mid X_i]-\mathrm E f(Z)\bigr)^2
\le 4\mathcal R_2(\mathcal F)^2,
$$

where $\mathcal R_2$ is an $\ell_2$-normalized Rademacher
complexity. For real-valued $Z$, the sum of expected
squared uniform distances between conditional and
unconditional distribution functions is therefore at most $4$,
independently of $n$. Under mere pairwise independence, a
bracketing argument yields a bound of order
$(\log n)^2$. Both orders are sharp up to constants,
the latter by an example based on a pairwise-independent
random-walk construction of Narayanan. The results also
yield population-size-independent bounds on the number of
agents who are distributionally pivotal for a collective
outcome.
