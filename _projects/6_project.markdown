---
layout: page
title: Delta Negative Binomial
description: Published in JFEC
img: /assets/img/dnb.jpg
---
{% include _links_library.md %}

<script type="text/javascript">
 function showhide(id) {
    var e = document.getElementById(id);
    e.style.display = (e.style.display == 'block') ? 'none' : 'block';
 }
</script>

With Istv&aacute;n Barra and [Siem Jan Koopman][SiemJanKoopman]. 

Published in Journal of Financial Econometrics, 2018.  
  
> Bayesian dynamic modelling of high-frequency integer price changes. Based on the negative binomial difference model with stochastic volatility to allow for heavy tails and to address occurrences of jumps in tick by tick discrete prices changes.

<i class="fa fa-download fa-lg" aria-hidden="true"></i> PDF: <a class="page-link" href="{{ '/research/Barra, Borowska, Koopman - Bayesian Dynamic Modeling of High-Frequency Integer Price Changes.pdf' | prepend: site.baseurl | prepend: site.url }}">Bayesian Dynamic Modeling of High-Frequency Integer Price Changes</a>

<i class="fa fa-sticky-note" aria-hidden="true"></i> <a href="javascript:showhide('longrun')">_Abstract_</a>
<div id="longrun" style="display:none;">
<p>  <div style="font-size:0.85em; text-align: justify;"> We investigate high-frequency volatility models for analyzing intradaily tick by tick stock price changes using Bayesian estimation procedures. Our key interest is the extraction of intradaily volatility patterns from high-frequency integer price changes. We account for the discrete nature of the data via two different approaches: ordered probit models and discrete distributions. We allow for stochastic volatility by modeling the variance as a stochastic function of time, with intraday periodic patterns. We consider distributions with heavy tails to address occurrences of jumps in tick by tick discrete prices changes. In particular, we introduce a dynamic version of the negative binomial difference model with stochastic volatility. For each model we develop a Markov chain Monte Carlo estimation method that takes advantage of auxiliary mixture representations to facilitate the numerical implementation. This new modeling framework is illustrated by means of tick by tick data for two stocks from the NYSE and for different periods. Different models are compared with each other based on predictive likelihoods. We find evidence in favour of our preferred dynamic negative binomial difference model. </div> </p>
</div>



Code: <a class="github-button" href="https://github.com/aborowska/DNB" data-size="large" aria-label="Follow @aborowska/DNB on GitHub">Follow @aborowska/DNB</a>