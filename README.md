# Interactive demos

Browser demos for *Bayesian Machine Learning with Generative AI Applications* (MS in Applied Data Science, The University of Chicago).

**Live:** https://uchicago-dsi-bayesianml.github.io/demos/

| Demo | What it shows |
|---|---|
| [Monte Carlo: Back to Our Evil World](https://uchicago-dsi-bayesianml.github.io/demos/monte-carlo/) | Draw θ from the posterior Beta(3, 9), then the next 10 days from Bin(10, θ); again, and again. The histogram settles on the beta-binomial, the posterior predictive. |
| [Metropolis on Two Humps](https://uchicago-dsi-bayesianml.github.io/demos/metropolis/) | The Metropolis algorithm on ½ N(−1, 0.5²) + ½ N(1, 0.5²), one step in three parts or 5,000 at speed. The proposal width σ is the knob: too narrow and the walk crawls, too wide and it rarely moves. The trace shows which. |

## Run it on your own computer

Each demo is one HTML file with no libraries and no build step. Download this repository (Code → Download ZIP) and open `monte-carlo/index.html` or `metropolis/index.html` in a browser. They work offline.

Keys: Space or → takes a step, A starts and pauses the auto-run, F adds 100 draws or iterations, R resets. In the Monte Carlo demo, "Change the numbers", under the controls, lets you try another prior or other data; in the Metropolis demo, the slider and the 0.1 / 1 / 10 buttons set the proposal width.

## Fonts

Chivo and Chivo Mono, under the SIL Open Font License ([fonts/OFL.txt](fonts/OFL.txt)).
