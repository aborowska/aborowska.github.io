---
layout: page
title: Semi-Complete Data Augmentation
description: R&R for JCGS
img: /assets/img/sv_hmm.jpg
---
{% include _links_library.md %}

<script type="text/javascript">
 function showhide(id) {
    var e = document.getElementById(id);
    e.style.display = (e.style.display == 'block') ? 'none' : 'block';
 }
</script>
   
With [Ruth King][RuthKing]

> Improving the efficiency of data augmentation for state space models. Combining data augmentation with numerical integration in a Bayesian hybrid approach to reduce a high autocorrelation in the posterior draws, typically leading to poor mixing of the MCMC algorithm.	


<i class="fa fa-download fa-ld" aria-hidden="true"></i> Paper: <a class="page-link" href="{{ '/research/Borowska, King - Semi-Complete Data Augmentation for Efficient State Space Model Fitting.pdf' | prepend: site.baseurl | prepend: site.url }}">Semi-Complete Data Augmentation for Efficient State Space Model Fitting</a>

<i class="fa fa-download fa-ld" aria-hidden="true"></i> Slides: <a class="page-link" href="{{ '/research/A.Borowska - Semi-Complete Data Augmentation for Efficient State Space Model Fitting.pdf' | prepend: site.baseurl | prepend: site.url }}">Semi-Complete Data Augmentation for Efficient State Space Model Fitting</a>

<i class="fa fa-sticky-note" aria-hidden="true"></i> <a href="javascript:showhide('scda')">_Abstract_</a>
<div id="scda" style="display:none;">
<p>  <div style="font-size:0.85em; text-align: justify;">
A novel efficient model-fitting algorithm for state space models is proposed. State space models are an intuitive and flexible class of models, frequently used due to the combination of their natural separation of the different mechanisms acting on the system of interest: the latent underlying system process; and the observation process. This flexibility, however, often comes at the price of substantially more complicated fitting of such models to data due to the associated likelihood being analytically intractable. For the general case a Bayesian data augmentation approach is often employed, where the true unknown states are treated as auxiliary variables and imputed within the MCMC algorithm. However, standard "vanilla" MCMC algorithms may perform very poorly due to high correlation between the imputed states and/or parameters, leading to the need for specialist algorithms. The proposed method circumvents the inefficiencies of traditional approaches by combining data augmentation with numerical integration in a Bayesian hybrid approach. This approach permits the use of standard "vanilla" updating algorithms that perform considerably better than the traditional approach in terms of considerably improved mixing and hence lower autocorrelation. A proposed semi-complete data augmentation algorithm is used in different application areas and associated types of models, leading to distinct implementation schemes and demonstrating efficiency gains in empirical studies.</div> </p>
</div>




Code: <a class="github-button" href="https://github.com/aborowska/DA_in_SSM" data-size="large" aria-label="Follow @aborowska/DA_in_SSM on GitHub">Follow @aborowska/DA_in_SSM</a>