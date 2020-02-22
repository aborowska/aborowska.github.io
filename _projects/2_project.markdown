---
layout: page
title: Long Run Risk Forecasting
description: Submitted
img: /assets/img/qermit.jpg
---
{% include _links_library.md %}

<script type="text/javascript">
 function showhide(id) {
    var e = document.getElementById(id);
    e.style.display = (e.style.display == 'block') ? 'none' : 'block';
 }
</script>
  
With [Lennart Hoogerheide][LennartHoogerheide] and [Siem Jan Koopman][SiemJanKoopman].  

  
> Precise forecasts of the tail of the distribution of returns for very long horizons, even one-month and one-year ahead (not barely for the 10-days-ahead horizon required by the Basel Committee). An importance sampling based approach where the importance densities are constructed sequentially to "guide" the draws into the tail.

<blockquote class="style1"> <strong>Why do we care?</strong> Check: <a href="https://vlab.stern.nyu.edu/doc/4?topic=apps" title="VaR">Long Run Value at Risk (VaR)</a> analysed by <a href="https://vlab.stern.nyu.edu/#tabs-4)" title ="VLab">NYU Stern V-Lab</a>!  </blockquote>


<i class="fa fa-download fa-lg" aria-hidden="true"></i> PDF: <a class="page-link" href="{{ '/research/Borowska, Hoogerheide, Koopman - Bayesian Risk Forecasting for Long Horizons.pdf' | prepend: site.baseurl | prepend: site.url }}">Bayesian Risk Forecasting for Long Horizons</a>

<i class="fa fa-sticky-note" aria-hidden="true"></i> <a href="javascript:showhide('longrun')">_Abstract_</a>
<div id="longrun" style="display:none;">
<p>  <div style="font-size:0.85em; text-align: justify;"> We present an accurate and efficient method for Bayesian forecasting of two financial risk measures, Value-at-Risk and Expected Shortfall, for a given volatility model. We obtain precise forecasts of the tail of the distribution of returns not only for the 10-days-ahead horizon required by the Basel Committee but even for long horizons, like one-month or one-year-ahead. The latter has recently attracted considerable attention due to the different properties of short term risk and long run risk. The key insight behind our importance sampling based approach is the sequential construction of marginal and conditional importance densities for consecutive periods. We report substantial accuracy gains for all the considered horizons in empirical studies on two datasets of daily financial returns, including a highly volatile period of the recent financial crisis. To illustrate the flexibility of the proposed construction method, we present how it can be adjusted to the frequentist case, for which we provide counterparts of both Bayesian applications.</div> </p>
</div>



Code: <a class="github-button" href="https://github.com/aborowska/QERMit" data-size="large" aria-label="Follow @aborowska/QERMit on GitHub">Follow @aborowska/QERMit</a>