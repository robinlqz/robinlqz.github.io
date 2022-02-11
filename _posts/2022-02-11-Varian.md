# Technology

## Problem 1

True or false? If $V(y)$ is a convex set, then the associated production set Y must be convex.

Answer:

False.

If Y is a convex set, then for x and x' that makes $(y,-x)$ and $(y,-x')$ in Y, there must be $(ty+(1-t)y,-tx-(1-t)x')$ in Y. i.e. $(y,-tx+(1-t)x')$ in Y.

If x and x' in V(y), then $tx+(1-t)x'$ also in V(y), then V(y) is convex.

Counterexample that shows convex input set doesn't mean convex production set. 

Consider $f(x)=x^2$ production function. Production set $Y=\{(y,-x):y\leq x^2\}$ is not convex. But input set $v(y)=\{x:x\geq\sqrt y\}$ is convex.

Notes:

We need to raise a counterexample to tackle this proof. 

## Problem 2

What is the elasticity of substitution for the general CES technology $y=(a_1x_1^\rho+a_2x_2^\rho)^{1/\rho}$ when $a_1\neq a_2$?

Answer:

To calculate elasticity of substitution, we need to calculate substitution of technology.
$$
TRS=-\frac{\frac{\partial f}{\partial x_1}}{\frac{\partial f}{\partial x_2}}=-\frac{a_1x_1^{\rho-1}}{a_2x_2^{\rho-1}}
$$
Take log
$$
\ln\{TRS\}=\ln\frac{a_1}{a_2}+(1-\rho)\ln\frac{x_2}{x_1}
$$

$$
\sigma=\frac{d\ln(x_2/x_1)}{d\ln TRS}=\frac{1}{1-\rho}
$$

Note: 

This problems tests the concept of elasticity of substitution ($\sigma$), and its relationship with TRS. 

The function of TRS is $TRS=-\frac{\frac{\partial f}{\partial x_1}}{\frac{\partial f}{\partial x_2}}$, then you can get the sigma.

## Problem 3

Define the output elasticity of a factor i to be
$$
\varepsilon_i(x)=\frac{\partial f(x)}{\partial x_i}\cdot\frac{x_i}{f(x)}
$$
If $f(x)=x_1^ax_2^b$, what is the output elasticity of each factor?

Answer:

$f_1(x)=ax_1^{a-1}x_2^b$, $f_2(x)=bx_1^ax_2^{b-1}$, so the elasticity of production of factor 1 is:
$$
\varepsilon_1(x)=f_1(x)\frac{x_1}{f(x)}=ax_1^{a-1}x_2^b\frac{x_1}{x_1^ax_2^b}=a
$$
the elasticity of production of factor 2 is:
$$
\varepsilon_2(x)=f_2(x)\frac{x_2}{f(x)}=bx_1^ax_2^{b-1}\frac{x_2}{x_1^ax_2^b}=b
$$
*Note*:

This is an interesting thing. Output elasticity is denoted by $\varepsilon_i(x)=\frac{\partial f(x)}{\partial x_i}\cdot\frac{x_i}{f(x)}$. I will do it.
