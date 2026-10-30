# Interactive demos

Browser demos for *Bayesian Machine Learning with Generative AI Applications* (MS in Applied Data Science, The University of Chicago).

**Live:** https://uchicago-dsi-bayesianml.github.io/demos/

| Demo | What it shows |
|---|---|
| [Monte Carlo: Back to Our Evil World](https://uchicago-dsi-bayesianml.github.io/demos/monte-carlo/) | Draw θ from the posterior Beta(3, 9), then the next 10 days from Bin(10, θ); again, and again. The histogram settles on the beta-binomial, the posterior predictive. |

## Run it on your own computer

Each demo is one HTML file with no libraries and no build step. Download this repository (Code → Download ZIP) and open `monte-carlo/index.html` in a browser. It works offline.

Keys: Space or → takes a step, A starts and pauses the auto-run, F adds 100 draws, R resets. "Change the numbers", under the controls, lets you try another prior or other data.

## Fonts

Chivo and Chivo Mono, under the SIL Open Font License ([fonts/OFL.txt](fonts/OFL.txt)).
