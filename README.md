# Linear Regression

Deck 09 of the [Mathematics for Machine Learning &mdash; Companion Series](https://github.com/BrendanJamesLynskey/MML_Hub).

**Live presentation:** https://brendanjameslynskey.github.io/MML_09_Linear_Regression/

Least squares as orthogonal projection onto the column space, ridge / MAP
regularisation, Bayesian linear regression with posterior predictive
distribution, and feature maps. Interactive regression playground that
updates the conjugate Gaussian posterior point-by-point.

## What's inside

- Problem formulation: $y_n = \boldsymbol\theta^\top\boldsymbol\phi(\mathbf{x}_n) + \varepsilon_n$
- Maximum likelihood = least squares = orthogonal projection (deck 03 connection)
- The normal equation and the pseudoinverse
- Ridge regression as MAP under a Gaussian prior
- Bayesian linear regression: conjugate posterior in closed form
- Posterior predictive distribution
- Feature maps: polynomial, radial basis, kernel
- Interactive: drop points and watch the Gaussian posterior shrink

Companion to chapter 9 of:

> Deisenroth, M. P., Faisal, A. A. &amp; Ong, C. S. (2020). *Mathematics for Machine Learning.* Cambridge University Press. Free PDF: [mml-book.github.io](https://mml-book.github.io/).

Single-page HTML, KaTeX-rendered maths, no build step. Open `index.html` directly.
