# causal-inference-project
Explore whether farmers purchase insurance based on default option presented.

The data is courtesy of the `causaldata` R package: https://cran.r-project.org/web/packages/causaldata/index.html. I used the `social_insure` data, based on the essay "Social Networks and the Decision to Insure" (Cai et al. 2014).

In this report, I examine data from a study about social networks’ influence on a farmer’s decision topurchase weather insurance based on the default option the farmer is presented with: to purchase or to not purchase. This analysis can help inform whether an “opt-in” structure noticeably influences the individual’s decision. The experiment was randomized on farmers in rural China, who were asked to attend information sessions with their peers and presented a default option to buy or not. Information on whether they chose to purchase insurance was then collected.

Methods: causal inference, logistic regression adjustment, propensity score regression, propensity score stratification, propensity score k:1 matching, bootstrap
