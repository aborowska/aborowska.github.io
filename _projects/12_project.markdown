---
layout: page
title: ABC for cell movement
description: Published in Computational Statistics
img: /assets/img/ABC.jpg
---
{% include _links_library.md %}

<script type="text/javascript">
 function showhide(id) {
    var e = document.getElementById(id);
    e.style.display = (e.style.display == 'block') ? 'none' : 'block';
 }
</script>
   
With Jon Devlin, Dirk Husmeier and John Mackenzie

Published in Computational Statistics, 2025

> A comparison and selection of ABC algorithms for a novel hybrid discrete-continuum model describing the movement of a population of cells in response to a self-generated chemotactic gradient.

<i class="fa fa-download fa-ld" aria-hidden="true"></i> Paper: <a class="page-link" href="{{ '/research/Devlin, Borowska, Husmeier, Mackenzie - Approximate Bayesian inference in a model for self-generated gradient collective cell movement.pdf' | prepend: site.baseurl | prepend: site.url }}">Approximate Bayesian inference in a model for self-generated gradient collective cell movement</a>

<i class="fa fa-sticky-note" aria-hidden="true"></i> <a href="javascript:showhide('compstat')">_Abstract_</a>
<div id="compstat" style="display:none;">
<p>  <div style="font-size:0.85em; text-align: justify;">
In this article we explore parameter inference in a novel hybrid discrete-continuum model describing the movement of a population of cells in response to a self-generated chemotactic gradient. The model employs a drift-diffusion stochastic process, rendering likelihood-based inference methods impractical. Consequently, we consider approximate Bayesian computation (ABC) methods, which have gained popularity for models with intractable or computationally expensive likelihoods. ABC involves simulating from the generative model, using parameters from generated observations that are “close enough” to the true data to approximate the posterior distribution. Given the plethora of existing ABC methods, selecting the most suitable one for a specific problem can be challenging. To address this, we employ a simple drift-diffusion stochastic differential equation (SDE) as a benchmark problem. This allows us to assess the accuracy of popular ABC algorithms under known configurations. We also evaluate the bias between ABC-posteriors and the exact posterior for the basic SDE model, where the posterior distribution is tractable. The top-performing ABC algorithms are subsequently applied to the proposed cell movement model to infer its key parameters. This study not only contributes to understanding cell movement but also sheds light on the comparative efficiency of different ABC algorithms in a well-defined context. </div> </p>
</div>
