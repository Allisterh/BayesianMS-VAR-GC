# BayesianMS-VAR-GC
### Bayesian Estimation of Markov-Switching VARs for Granger Causal Inference in R

by Matthieu Droumaguet, Anders Warne, \& Tomasz Woźniak

> **Summary.** A block Metropolis-Hastings algorithm for the Bayesian estimation of the Markov-switching Vector Autoregressive models with restrictions for Granger noncausality is provided, as well as an appropriate estimator for the marginal data density. 
>
> **Keywords.** R, Markov-switching VARs, Block Metropolis-Hastings Sampler, Marginal Data Density

## Citation

To refer to the codes in publications, please, cite the following paper:

> Droumaguet, M., Warne, A., Woźniak, T. (2017) Granger Causality and Regime Inference in Markov-Switching VAR Models with Bayesian Methods, *Journal of Applied Econometrics*, 32(4), pp. 802--818, DOI: [10.1002/jae.2531](http://doi.org/10.1002/jae.2531).

## Project contents

The project's file structure includes:

- [`BayesianMSVAR.pdf`](https://github.com/donotdespair/BayesianMS-VAR-GC/blob/master/BayesianMSVAR.pdf) - a document presenting the model, main functions, and their application
- `BayesianMSVAR-example.R` - a file presenting code application for a simple example
- `BayesianMSVAR` - a folder containing the functions for the estimation of the considered models
- `ReproductionScripts` - a folder containing scripts for the reproduction of all the results contained in the JAE paper
- `data.csv` and `data.RData` - data used in the paper

## Downloading the codes

To download the codes follow the steps (requires a [GitHub account](https://github.com) and [GitHub Desktop](https://desktop.github.com/)):

1. **On this page:** fork the project by clicking the icon on the top of this page ([more info](https://guides.github.com/activities/forking/))

   ![](https://github-images.s3.amazonaws.com/help/bootcamp/Bootcamp-Fork.png)

2. **In GitHub Desktop:** go to the application menu to select: `File -> Clone Repository...`, choose the forked repository from the list of available repositories from GitHub.com, select your local folder to store the repository, and click `Clone`. ([even more info](https://docs.github.com/en/get-started/quickstart/fork-a-repo))

3. **Optional:** if you find a bug or if you improve the code, please feel free to submit a pull request. (more info [here](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) and [here](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request))

