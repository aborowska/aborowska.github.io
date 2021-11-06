---
layout: page
title: Partially Censored Posterior
description: Published in J Econom
img: /assets/img/pcp.jpg
---
{% include _links_library.md %}

<script type="text/javascript">
 function showhide(id) {
    var e = document.getElementById(id);
    e.style.display = (e.style.display == 'block') ? 'none' : 'block';
 }
</script>

With [Lennart Hoogerheide][LennartHoogerheide], [Siem Jan Koopman][SiemJanKoopman] and [Herman K. van Dijk][HermanVanDijk].  

Published in Journal of Econometrics, 2020.

> A novel estimation method  providing a more accurate inference for a specific region of the predictive density  in case of misspecification. Based on the censored likelihood, where the observations outside the region of interest are censored (i.e. for them only the probability of being outside the region of interest matters). 

<i class="fa fa-download fa-ld" aria-hidden="true"></i> PDF: <a class="page-link" href="{{ '/research/Borowska, Hoogerheide, Koopman, Van Dijk - Partially Censored Posterior for Robust and Efficient Risk Evaluation.pdf' | prepend: site.baseurl | prepend: site.url }}">Partially Censored Posterior for Accurate Left Tail Density Prediction</a>

<i class="fa fa-sticky-note" aria-hidden="true"></i> <a href="javascript:showhide('pcp')">_Abstract_</a>
<div id="pcp" style="display:none;">
<p>  <div style="font-size:0.85em; text-align: justify;"> A novel approach to inference for a specific region of the predictive distribution is introduced. An important domain of application is accurate prediction of financial risk measures, where the area of interest is the left tail of the predictive density of logreturns. Our proposed approach originates from the Bayesian approach to parameter estimation and time series forecasting, however it is robust in the sense that it provides a more accurate estimation of the predictive density in the region of interest in case of misspecification. The first main contribution of the paper is the novel concept of the Partially Censored Posterior (PCP), where the set of model parameters is partitioned into two subsets: for the first subset of parameters we consider the standard marginal posterior, for the second subset of parameters (that are particularly related to the region of interest) we consider the conditional censored posterior. The censoring means that observations outside the region of interest are censored: for those observations only the probability of being outside the region of interest matters. This approach yields more precise parameter estimation than a fully censored posterior for all parameters, and has more focus on the region of interest than a standard Bayesian approach. The second main contribution is that we introduce two novel methods for computationally efficient simulation: Conditional MitISEM, a Markov chain Monte Carlo method to simulate model parameters from the Partially Censored Posterior, and PCP-QERMit, an Importance Sampling method that is introduced to further decrease the numerical standard errors of the Value-at-Risk and Expected Shortfall estimators. The third main contribution is that we consider the effect of using a time-varying boundary of the region of interest, which may provide more information about the left tail of the distribution of the standardized innovations. Extensive simulation and empirical studies show the ability of the introduced method to outperform standard approaches.</div> </p>
</div>

Code: <a class="github-button" href="https://github.com/aborowska/PCP" data-size="large" aria-label="Follow @aborowska/PCP on GitHub">Follow @aborowska/PCP</a>