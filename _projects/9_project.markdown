---
layout: page
title: Tackling LV Meshes
description: Published at ICSTA
img: /assets/img/CNN.png
---
{% include _links_library.md %}

<script type="text/javascript">
 function showhide(id) {
    var e = document.getElementById(id);
    e.style.display = (e.style.display == 'block') ? 'none' : 'block';
 }
</script>
   
With [Lukasz Romaszko][LukaszRomaszko], Alan Lazarus, [Hao Gao][HaoGao], [Xiaoyu Luo][XiaoyuLuo] and [Dirk Husmeier][DirkHusmeier].


----

#### Massive Dimensionality Reduction for the Left Ventricular Mesh

> How to reduce the dimension (17k!) of the LV mesh? With PCA, auto encoders or with a parametric model?

<i class="fa fa-sticky-note" aria-hidden="true"></i> <a href="javascript:showhide('dimred')">_Abstract_</a>
<div id="dimred" style="display:none;">
<p>  <div style="font-size:0.85em; text-align: justify;">Statistical emulation is a promising approach for the translation of cardio-mechanical modelling into the clinical practice. However, a key challenge is to find a low-dimensional representation of the heart, or, for the specific purpose of diagnosing the risk of heart attacks, the left-ventricle of the heart. We consider the problem of dimensionality reduction of the left ventricular mesh, in which we investigate three classes of techniques: principal component analysis (PCA), deep learning (DL) methods based on auto-encoders, and a parametric model from the cardio-mechanical literature. Our finding is that PCA performs as well as the computationally more expensive DL methods, and both outperform the state-of-the-art parametric model.</div> </p>
</div>

<i class="fa fa-download fa-ld" aria-hidden="true"></i> PDF: <a class="page-link" href="{{ '/research/Romaszko, Lazarus, Gao, Borowska, Luo, Husmeier - Massive Dimensionality Reduction for the Left Ventricular Mesh.pdf' | prepend: site.baseurl | prepend: site.url }}">Massive Dimensionality Reduction for the Left Ventricular Mesh</a>


----

#### Direct Learning Left Ventricular Meshes from CMR Images

> Train a convolutional neural network to learn LV meshes directly from MRI images

<i class="fa fa-sticky-note" aria-hidden="true"></i> <a href="javascript:showhide('cnn')">_Abstract_</a>
<div id="cnn" style="display:none;">
<p>  <div style="font-size:0.85em; text-align: justify;">Biomechanical studies of the left ventricle (LV) typically rely on a mesh of finite element nodes for a discrete representation of the LV geometry, which is used in an approximate numerical solution of the cardio-mechanical equations based on finite-element discretisation. This is typically done by first manually annotating cardiovascular magnetic resonance (CMR) scans, second creating a preliminary mesh, third manually correcting the mesh to account for motion. The whole process requires specialist knowledge, is time consuming and prone to human error, which prohibits its common adoption in the clinics. We propose to overcome these shortcomings by applying statistical pattern recognition techniques to CMR images. In particular, we train a convolutional neural network (CNN) to predict the LVM via learning its principal component representation directly from CMR scans. As a useful side-product we obtain a low-dimensional representation of the LVM, which is of interest for surrogate models (emulators) of the myocardium constitutive models.</div> </p>
</div>

<i class="fa fa-download fa-ld" aria-hidden="true"></i> PDF: <a class="page-link" href="{{ '/research/Romaszko, Borowska, Lazarus, Gao, Luo, Husmeier - Direct Learning Left Ventricular Meshes from CMR Images.pdf' | prepend: site.baseurl | prepend: site.url }}">Direct Learning Left Ventricular Meshes from CMR Images</a>
