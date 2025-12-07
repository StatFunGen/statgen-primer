# statgen-primer

These notes are written to help ([some of our own](https://wanggroup.org/)) trainees who already have some grounds in basic (human) genetics concepts and undergraduate-level statistics, 
yet find it difficult to learn in somewhat detail various statistical methods commonly used in statistical genetics research nowadays. 
The goal is to bridge the knowledge gap between these existing backgrounds and the more advanced learning goal of interest.

## Overview of Contents

| Section | Subsection | Topic |
|---------|------------|-------|
| **Basic Concepts** | | [Genotype Coding](https://statfungen.github.io/statgen-primer/genotype_coding.html) |
| | | [Minor Allele Frequency](https://statfungen.github.io/statgen-primer/minor_allele_frequency.html) |
| | | [Hardy-Weinberg Equilibrium](https://statfungen.github.io/statgen-primer/Hardy_Weinberg_equilibrium.html) |
| **Correlation** | Between variants | [Linkage Disequilibrium](https://statfungen.github.io/statgen-primer/linkage_disequilibrium.html) |
| | | [Linkage Disequilibrium Score](https://statfungen.github.io/statgen-primer/linkage_disequilibrium_score.html) |
| | Between individuals | [Genetic Relationship Matrix](https://statfungen.github.io/statgen-primer/genetic_relationship_matrix.html) |
| | Between variables | [Factor Analysis](https://statfungen.github.io/statgen-primer/factor_analysis.html) |
| | | [Principal Component Analysis](https://statfungen.github.io/statgen-primer/principal_component_analysis.html) |
| **Genetic Associations** | Basic model | [Ordinary Least Squares](https://statfungen.github.io/statgen-primer/ordinary_least_squares.html) |
| | Extend to binary outcome | [Odds Ratio](https://statfungen.github.io/statgen-primer/odds_ratio.html) |
| | Extend to multiple variables| [Marginal vs. Joint Effects](https://statfungen.github.io/statgen-primer/marginal_joint_effects.html) |
| | | [Summary Statistics](https://statfungen.github.io/statgen-primer/summary_statistics.html) |
| **Genetic effects** | | [Random Effect](https://statfungen.github.io/statgen-primer/random_effect.html) |
| | | [Proportion of Variance Explained](https://statfungen.github.io/statgen-primer/proportion_of_variance_explained.html) |
| | | [Linear Mixed Model](https://statfungen.github.io/statgen-primer/linear_mixed_model.html) |
| | Covariates | [Confounder](https://statfungen.github.io/statgen-primer/confounder.html) |
| | | [Collider](https://statfungen.github.io/statgen-primer/collider.html) |
| | | [Mediator](https://statfungen.github.io/statgen-primer/mediator.html) |
| | Multiple studies | [Meta Analysis Fixed Effect](https://statfungen.github.io/statgen-primer/meta_analysis_fixed_effect.html) |
| | | [Meta Analysis Random Effect](https://statfungen.github.io/statgen-primer/meta_analysis_random_effect.html) |
| **Statistical Inference** | Likelihood and MLE | [Likelihood](https://statfungen.github.io/statgen-primer/likelihood.html) |
| | | [Maximum Likelihood Estimation](https://statfungen.github.io/statgen-primer/maximum_likelihood_estimation.html) |
| | LR and LRT | [Likelihood Ratio](https://statfungen.github.io/statgen-primer/likelihood_ratio.html) |
| | Bayesian versus Frequentist | [Bayesian and Frequentist](https://statfungen.github.io/statgen-primer/Bayesian_frequentist.html) |
| | | [Bayes Rule](https://statfungen.github.io/statgen-primer/Bayes_rule.html) |
| | | [Bayes Factor](https://statfungen.github.io/statgen-primer/Bayes_factor.html) |
| | | [P-value](https://statfungen.github.io/statgen-primer/p_value.html) |
| | Bayesian Model | [Bayesian Normal Mean Model](https://statfungen.github.io/statgen-primer/Bayesian_normal_mean_model.html) |
| | | [Bayesian Multivariate Normal Mean Model](https://statfungen.github.io/statgen-primer/Bayesian_multivariate_normal_mean_model.html) |
| | Multiple Bayesian Models | [Bayesian Model Comparison](https://statfungen.github.io/statgen-primer/Bayesian_model_comparison.html) |
| | | [Bayesian Mixture Model](https://statfungen.github.io/statgen-primer/Bayesian_mixture_model.html) |

These notes draw inspiration from [fiveMinutesStats](https://stephens999.github.io/fiveMinuteStats/index.html) by Matthew Stephens and [statistical genetics equations](https://rawgit.com/uqrmaie1/statgen_equations/master/statgen_equations.html) by Robert Maier. Compared to Matthew's materials, these notes are more narrowly focused on human and statistical genetics with only as much statistical details to understand the applications. Compared to Robert's materials, these notes include a slightly stronger statistical component to serve as "primer" for readers to advance into learing full details of these relevant methods.
