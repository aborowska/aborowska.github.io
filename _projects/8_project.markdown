---
layout: page
title: GP-ABC for chemotaxis
description: Published in J Comput Phys
img: /assets/img/XYOverTime.png
---
{% include _links_library.md %}

<script type="text/javascript">
 function showhide(id) {
    var e = document.getElementById(id);
    e.style.display = (e.style.display == 'block') ? 'none' : 'block';
 }
</script>
   
With Diana Giurghita and [Dirk Husmeier][DirkHusmeier].

Published in Journal of Computational Physics, 2020.

> Gaussian process enhanced ABC for parameter inference in a stochastic differential equation system describing the behaviour of cells migrating as a response to chemotaxis.

<i class="fa fa-sticky-note" aria-hidden="true"></i> <a href="javascript:showhide('pcp')">_Abstract_</a>
<div id="pcp" style="display:none;">
<p>  <div style="font-size:0.85em; text-align: justify;">Chemotaxis is a type of cell movement in response to a chemical stimulus which plays a key role in multiple biophysical processes, such as embryogenesis and wound healing, and which is crucial for understanding metastasis in cancer research. In the literature, chemotaxis has been modelled using biophysical models based on systems of nonlinear stochastic partial differential equations (NSPDEs), which are known to be challenging for statistical inference due to the intractability of the associated likelihood and the high computational costs of their numerical integration. Therefore, data analysis in this context has been limited to comparing predictions from NSPDE models to laboratory data using simple descriptive statistics. We present a statistically rigorous framework for parameter estimation in complex biophysical systems described by NSPDEs such as the one of chemotaxis. We adopt a likelihood-free approach based on approximate Bayesian computations with sequential Monte Carlo (ABC-SMC)which allows for circumventing the intractability of the likelihood. To find informative summary statistics, crucial for the performance of ABC, we propose to use a Gaussian process (GP) regression model. The interpolation provided by the GP regression turns out useful on its own merits: it relatively accurately estimates the parameters of the NSPDE model and allows for uncertainty quantification, at a very low computational cost. Our proposed methodology allows for a considerable part of computations to be completed before having observed any data, providing a practical toolbox to experimental scientists whose modes of operation frequently involve experiments and inference taking place at distinct points in time. In an application to externally provided synthetic data we demonstrate that the correction provided by ABC-SMC is essential for accurate estimation of some of the NSPDE model parameters and for more flexible uncertainty quantification.
</div> </p>
</div>

<i class="fa fa-download fa-ld" aria-hidden="true"></i> Paper: <a class="page-link" href="{{ '/research/Borowska, Giurghita, Husmeier - Gaussian process enhanced semi-automatic approximate Bayesian computation.pdf' | prepend: site.baseurl | prepend: site.url }}">Gaussian process enhanced semi-automatic approximate Bayesian computation: parameter inference in a stochastic differential equation system for chemotaxis</a> 

<i class="fa fa-download fa-ld" aria-hidden="true"></i> Supplementary material: <a class="page-link" href="{{ '/research/Borowska, Giurghita, Husmeier - Supplementary material for Gaussian process enhanced semi-automatic approximate Bayesian computation.pdf' | prepend: site.baseurl | prepend: site.url }}">Supplementary material for Gaussian process enhanced semi-automatic approximate Bayesian computation: parameter inference in a stochastic differential equation system for chemotaxis</a> 