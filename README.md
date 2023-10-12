# Central Limit Theorem


$Let\ X_1,...,X_n\ be\ IID\ with\ mean\ \mu\ and\ variance\ \sigma^2.\ Let\ \bar{X_n}= \frac{\Sigma_{i=1}^{n}\ X_i}{n} .\ \, Then$

$$
Z_n \equiv \frac{\bar{X_n}-\mu}{\sqrt{Var(\bar{X_n})}} = \frac{\sqrt{n}(\bar{X_n}-\mu)}{\sigma} \leadsto Z \sim N(0,1)
$$

$That\ is,$

$$
\lim_{n\to\infty}\mathbb{P}(Z_n\leqslant z)=\Phi(z) = \int_{-\infty}^{z} \frac{1}{\sqrt{2\pi}} e^{-x^2/2}dx
$$
