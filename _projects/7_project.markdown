---
layout: page
title: Bayesian Optimization for Biomechanics
description: submitted
img: /assets/img/LVs.png
---
{% include _links_library.md %}

<script type="text/javascript">
 function showhide(id) {
    var e = document.getElementById(id);
    e.style.display = (e.style.display == 'block') ? 'none' : 'block';
 }
</script>
   
With [Hao Gao][HaoGao], Alan Lazarus and [Dirk Husmeier][DirkHusmeier], 

> An efficient, Bayesian optimisation-based framework for parameter inference in a cardiac mechanic model of the left ventricle. Our method  converges to lower values of the objective functions considered and requires fewer invocations of the forward simulator than alternative state-of-the-art multi-step algorithms.

<i class="fa fa-sticky-note" aria-hidden="true"></i> <a href="javascript:showhide('pcp')">_Abstract_</a>
<div id="pcp" style="display:none;">
<p>  <div style="font-size:0.85em; text-align: justify;">.</div>We consider parameter inference in cardio-mechanic models of the left ventricle, in particular the one based on the Holtzapfel-Ogden (HO) constitutive law, using clinical in vivo data. The equations underlying these models do not admit closed form solutions and hence need to be solved numerically. These numerical procedures are computationally expensive making computational run times associated with numerical optimisation or sampling excessive for the uptake of the models in the clinical practice. To address this issue, we adopt the framework of Bayesian optimisation (BO), which is an efficient statistical technique of global optimisation. BO seeks the optimum of an unknown black-box function by sequentially training a statistical surrogate-model and using it to select the next query point by leveraging the associated exploration-exploitation trade-off. To guarantee that the estimates based on the in vivo data are realistic also for high-pressures, unobservable in vivo, we include a penalty term based on a previously published empirical law developed using ex vivo data. Two case studies based on real data demonstrate that the proposed BO procedure outperforms the state-of-the-art inference algorithm for the HO law.</p>
</div>

[//]: <> (<i class="fa fa-download fa-ld" aria-hidden="true"></i> Paper: <a class="page-link" href="{{ '/research/Borowska, Gao, Lazarus, Husmeier - Bayesian optimisation for efficient parameter inference in a cardiac mechanics model of the left ventricle.pdf' | prepend: site.baseurl | prepend: site.url }}">Bayesian optimisation for efficient parameter inference in a cardiac mechanics model of the left ventricle</a> )

[//]: <> (Code: <a class="github-button" href="https://github.com/aborowska/LV_BO" data-size="large" aria-label="Follow @aborowska/LV_BO on GitHub">Follow @aborowska/LV_BO</a>)


