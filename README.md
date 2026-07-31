# Mathematical Statistics — Lab Assignments

4 labs from a university course on mathematical statistics: sampling distributions, point estimation (method of moments, maximum likelihood), goodness-of-fit tests, and statistical hypothesis testing — all implemented in Python (NumPy/SciPy).

## Contents

| # | Topic | Methods |
|---|---|---|
| [Lab 1](./Math_statistics_1.ipynb) | Sampling distributions | Simulating samples of increasing size (n=10 … 10,000) from a Rayleigh distribution, sample mean & variance, convergence to true parameters (law of large numbers) |
| [Lab 2](./Math_Statistics_2.ipynb) | Point estimation | Method of moments vs. maximum likelihood estimation, likelihood function, bias/variance/MSE of an estimator, histogram vs. theoretical density, empirical CDF (Sturges' rule) |
| [Lab 3](./Math_Statistics_3.ipynb) | Goodness-of-fit tests & correlation | Pearson's χ² test, Kolmogorov's test, hypothesis testing for the correlation coefficient (Student's t-test) |
| [Lab 4](./Math_Statistics_4.ipynb) | Hypothesis testing | Comparing two variances (F-test), comparing two means (z-test, large samples), comparing several variances (Bartlett's test) |

Each notebook: problem statement → simulation → statistical procedure → conclusion (accept/reject H₀).

## Getting started

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
pip install -r requirements.txt
jupyter notebook
```

Notebooks are saved with all cells already executed, so plots and results render directly on GitHub.

## Tech stack

`numpy`, `scipy.stats` · `pandas` · `matplotlib`, `seaborn`
