---
layout: page
title: Risk Evaluation for State Space Models
description: 
img: /assets/img/nais_smooth.jpg
---
{% include _links_library.md %}

<script type="text/javascript">
 function showhide(id) {
    var e = document.getElementById(id);
    e.style.display = (e.style.display == 'block') ? 'none' : 'block';
 }
</script> 
   
With [Lennart Hoogerheide][LennartHoogerheide] and [Siem Jan Koopman][SiemJanKoopman].  


> Efficient Bayesian risk estimation for nonlinear, non-Gaussian state space models based on importance sampling. The optimal importance density constructed for the augmented parameter space (including the latent volatility process) with a focus on the "high-loss" scenarios.

<i class="fa fa-download fa-ld" aria-hidden="true"></i> PDF: <a class="page-link" href="{{ '/research/BAYSM2016_Borowska_Hoogerheide_Koopman.pdf' | prepend: site.baseurl | prepend: site.url }}">Bayesian Risk Evaluation in State Space Models</a> _(extended abstract)_


<i class="fa fa-sticky-note" aria-hidden="true"></i> <a href="javascript:showhide('baysm')">_Abstract_</a>
<div id="baysm" style="display:none;">
<p>  <div style="font-size:0.85em; text-align: justify;"> We present a novel approach to Bayesian estimation of two financial risk measures, Value at Risk and Expected Shortfall, in nonlinear, non-Gaussian state space models. In particular, we consider two specifications of the stochastic volatility model: with normal and Student’s t observation disturbances. The key insight behind our proposed importance sampling based approach is to accurately approximate the optimal importance density, which focuses on the augmented parameter subspace corresponding to high losses. By oversampling the extreme scenarios and punishing them by lower importance weights, we achieve a much higher precision in characterising the properties of the left tail. We report substantial gains in the accuracy of estimates in an empirical study on daily financial data. </div> </p>
</div>

Code: <a class="github-button" href="https://github.com/aborowska/QERMit" data-size="large" aria-label="Follow @aborowska/QERMit on GitHub">Follow @aborowska/QERMit</a> and <a class="github-button" href="https://github.com/aborowska/NAIS" data-size="large" aria-label="Follow @aborowska/NAIS on GitHub">Follow @aborowska/NAIS</a>