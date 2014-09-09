In-progress manuscript, code, and data for the paper tentatively titled "Reasonable Measures of Uncertainty Under Separation."

Here's the main point: 

When dealing with separation under logistic regression, you had better choose your prior distribution carefully--your choice will (most likely) affect your inferences. To see how, just look at the differences in the posterior summaries from this real data set using four different, but plausible, prior distributions. Note that Jeffreys' prior and the Cauchy(2.5) prior are two *defaults* recommended in the literature, yet the 90% credible interval for the latter is more than *twice as wide* as the former and the posterior mean is almost *twice as large*.

![An illustration that the choice of prior matters.](matters-ci.png)

And here's a working abstract:

> When facing data sets with small numbers of observations or ``rare events,'' political scientists often encounter important explanatory variables that perfectly predict binary events or non-events. In this situation, maximum likelihood provides implausible estimates and the researcher must incorporate some form of prior information in the estimation. The most sophisticated research uses Jeffreys' invariant prior to stabilize the estimates. While Jeffreys' prior has the advantage of being automatic, I show that, in many cases, it offers too much prior information, providing confidence intervals that are much too narrow. I show that the choice of a more reasonable prior can lead to different substantive conclusions about the likely magnitude of an effect and I offer practice advice for choosing a prior distribution that represents actual prior information.

If you have any comments or suggestions, please [open an issue](https://github.com/carlislerainey/priors-for-separatioin/issues) or just [e-mail](mailto:carlislerainey@gmail.com) me.