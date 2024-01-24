---
date: 2024-01-16
category: concept
stage: working
---

In the [[../docs/Computational/{vlndr}|{vlndr}]] software package, one simple concept is that of evaluating interaction. 
When evaluating a model that contains interaction terms, particularly categorical interaction terms, we can assess the interaction estimates on each level of the term.
For example, in the case of two binary variables $x_{1}$ and $x_{2}$, with $\beta_{0}$ being the intercept term and $\epsilon$ being the error term, we can assess their interaction in the following equation:

$$
y = \beta_{0} + \beta_{1} x_{1} + \beta_{2} x_{2} + \beta_{3} x_{1} x_{2} + \epsilon
$$

In the case that $x_{2} = 0$ (or the referent category), then its effects are nulled. $n$ is the sample size and $p$ is number of variables in the model.

$$
\begin{align}
y &= \beta_{1} x_{1} \\
CI_{1 - \alpha}[\beta_{1}] &= \hat{\beta_{1}} \pm t_{n - p - (1 - \frac{\alpha}{2})} \times \sqrt{var(\hat{\beta_{1}})}
\end{align}
$$

But in the case that they are a value such that $x_{2} \neq 0$, then the coefficient for both terms including $x_{2}$ must be maintained in the equation.  That means that the value for the confidence interval will differ based on the levels present.

$$
\begin{align}
y &= \beta_{1} x_{1} + \beta_{2} x_{2} + \beta_{3} x_{1} x_{2} \\
CI_{1 - \alpha}[\beta_{1} + \beta_{2} x_{2}] 
	&= (\hat{\beta_{1}} + \hat{\beta_{2}} x_{2}) 
	\pm t_{n - p - (1 - \frac{\alpha}{2})} 
	\times 
	\sqrt{var(\hat{\beta_{1}}) + x_{2}^{2} var(\beta_{2}) + 2 x_{2} cov(\beta_{1}, \beta_{2})}
\end{align}
$$

However, this method, suggested by @Figueiras1998, is simplified when assuming the value of $x_{2} \in (0, 1)$ , e.g. is *binary*or either `TRUE` or `FALSE`. 

$$
\begin{align}
y &= \beta_{1} x_{1} + \beta_{2} x_{2} + \beta_{3} x_{1} x_{2} \\
CI_{1 - \alpha}[\beta_{1} + \beta_{2}] 
	&= (\hat{\beta_{1}} + \hat{\beta_{2}})
	\pm t_{n - p - (1 - \frac{\alpha}{2})} 
	\times 
	\sqrt{var(\hat{\beta_{1}}) + var(\hat{\beta_{2}}) + 2 cov(\hat{\beta_{1}}, \hat{\beta_{2}})}
\end{align}
$$

To generalize this to categorical variables, such that $x_{2} \in ("a", "b", "c")$, **dummy variables** should/can be utilized. In this case, $x_{2a}, x_{2b}, x_{2c}$ are used as an example, while $x_{1}$ remains a continuous variable.



#TODO 
#statistics 
#epidemiology 
#methods 
#equations
