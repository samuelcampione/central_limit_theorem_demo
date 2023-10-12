# Central Limit Theorem

<br>

> *I know of scarcely anything so apt to impress the imagination as the wonderful form of cosmic order expressed by the "Law of Frequency of Error". The law would have been personified by the Greeks and deified, if they had known of it. It reigns with serenity and in complete self-effacement, amidst the wildest confusion. The huger the mob, and the greater the apparent anarchy, the more perfect is its sway. It is the supreme law of Unreason. Whenever a large sample of chaotic elements are taken in hand and marshalled in the order of their magnitude, an unsuspected and most beautiful form of regularity proves to have been latent all along.* <br> -- Sir Francis Galton

<br>


 **The Central Limit Theorem (CLT):**



$Let\ X_1,...,X_n\ be\ IID\ with\ mean\ \mu\ and\ variance\ \sigma^2.\ Let\ \bar{X_n}= \frac{\Sigma_{i=1}^{n}\ X_i}{n} .\ \, Then$

$$
Z_n \equiv \frac{\bar{X_n}-\mu}{\sqrt{Var(\bar{X_n})}} = \frac{\sqrt{n}(\bar{X_n}-\mu)}{\sigma} \leadsto Z \sim N(0,1)
$$

$That\ is,$

$$
\lim_{n\to\infty}\mathbb{P}(Z_n\leqslant z)=\Phi(z) = \int_{-\infty}^{z} \frac{1}{\sqrt{2\pi}} e^{-x^2/2}dx
$$

<br>

As n approaches infinity, the distribution of the normalized sample means approaches standard normal distribution regardless of the original distributions.

<br>

**History**

- De Moivre and Laplace developed the first versions of the CLT based around binomial approximations.
- Lindeberg, Lévy, and Feller (amongst others) in the early 1900s and 1930s worked on refinements, generalizations, and proofs of the CLT under various conditions, setting a strong mathematical foundation for our modern day CLT



<br>

The Central Limit Theorem is the unofficial ruler of probability theory. Galton captures this perfectly.

