---
layout: page
title: Predicting left ventricle geometries
description: Published in AIIM
img: /assets/img/CNN.png
---
{% include _links_library.md %}

<script type="text/javascript">
 function showhide(id) {
    var e = document.getElementById(id);
    e.style.display = (e.style.display == 'block') ? 'none' : 'block';
 }
</script>
   
With [Lukasz Romaszko][LukaszRomaszko], Alan Lazarus, David Dalton, Collin Berry, [Xiaoyu Luo][XiaoyuLuo], [Dirk Husmeier][DirkHusmeier] and [Hao Gao][HaoGao].


### Journal paper -- published in Artificial Intelligence in Medicine, 2021

#### Neural network-based left ventricle geometry prediction from CMR images with application in biomechanics

> An automatic CNN-based framework for predicting LV geometries directly from CMR images, without the need to manually annotate any CMR scans. The key feature is  separating the segmentation and geometry reconstruction tasks by training two CNNs, a segmentation network and a geometry prediction network.

<i class="fa fa-sticky-note" aria-hidden="true"></i> <a href="javascript:showhide('2stage')">_Abstract_</a>
<div id="2stage" style="display:none;">
<p>  <div style="font-size:0.85em; text-align: justify;">Background: Combining biomechanical modelling of left ventricular (LV) function and dysfunction with cardiac magnetic resonance (CMR) imaging has the potential to improve the prognosis of patient-specific cardiovascular disease risks. Biomechanical studies of LV function in three dimensions usually rely on a computerized representation of the LV geometry based on finite element discretization, which is essential for numerically simulating in vivo cardiac dynamics. Detailed knowledge of the LV geometry is also relevant for various other clinical applications, such as assessing the LV cavity volume and wall thickness. Accurately and automatically reconstructing personalized LV geometries from conventional CMR images with minimal manual intervention is still a challenging task, which is a pre-requisite for any subsequent automated biomechanical analysis. I this talk I will present a deep learning-based automatic pipeline for predicting the three-dimensional LV geometry directly from routinely-available CMR cine images, without the need to manually annotate the ventricular wall. The framework takes advantage of a low-dimensional representation of the high-dimensional LV geometry based on principal component analysis. I will discuss how the inference of myocardial passive stiffness is affected by using our automatically generated LV geometries instead of manually generated ones. These insights can be used to inform the development of statistical emulators of LV dynamics to avoid computationally expensive biomechanical simulations. The proposed framework enables accurate LV geometry reconstruction, outperforming previous approaches by delivering a reconstruction error 50% lower than reported in the literature. I will further demonstrate that for a nonlinear cardiac mechanics model, using our reconstructed LV geometries instead of manually extracted ones only moderately affects the inference of passive myocardial stiffness described by an anisotropic hyperelastic constitutive law. The developed methodological framework has the potential to make an important step towards personalized medicine by eliminating the need for time consuming and costly manual operations. In addition, the proposed method automatically maps the CMR scan into a low-dimensional representation of the LV geometry, which constitutes an important stepping stone towards the development of an LV geometry-heterogeneous emulator.
</div> </p>
</div>

<i class="fa fa-download fa-ld" aria-hidden="true"></i> PDF: <a class="page-link" href="{{ '/research/Romaszko, Borowska, Lazarus, Dalton, Berry, Luo, Husmeier, Gao - Neural network-based left ventricle geometry prediction from CMR images with application in biomechanics.pdf' | prepend: site.baseurl | prepend: site.url }}">Neural network-based left ventricle geometry prediction from CMR images with application in biomechanics</a>

Code: <a class="github-button" href="https://github.com/aborowska/LVgeometry-prediction" data-size="large" aria-label="Follow @aborowska/LVgeometry-prediction on GitHub">Follow @aborowska/LVgeometry-prediction</a>


----

### Conference papers - published at ICSTA 2019

#### Massive Dimensionality Reduction for the Left Ventricular Mesh

> How to reduce the dimension (17k!) of the LV mesh? With PCA, auto encoders or with a parametric model?

<i class="fa fa-sticky-note" aria-hidden="true"></i> <a href="javascript:showhide('dimred')">_Abstract_</a>
<div id="dimred" style="display:none;">
<p>  <div style="font-size:0.85em; text-align: justify;">Statistical emulation is a promising approach for the translation of cardio-mechanical modelling into the clinical practice. However, a key challenge is to find a low-dimensional representation of the heart, or, for the specific purpose of diagnosing the risk of heart attacks, the left-ventricle of the heart. We consider the problem of dimensionality reduction of the left ventricular mesh, in which we investigate three classes of techniques: principal component analysis (PCA), deep learning (DL) methods based on auto-encoders, and a parametric model from the cardio-mechanical literature. Our finding is that PCA performs as well as the computationally more expensive DL methods, and both outperform the state-of-the-art parametric model.</div> </p>
</div>

<i class="fa fa-download fa-ld" aria-hidden="true"></i> PDF: <a class="page-link" href="{{ '/research/Romaszko, Lazarus, Gao, Borowska, Luo, Husmeier - Massive Dimensionality Reduction for the Left Ventricular Mesh.pdf' | prepend: site.baseurl | prepend: site.url }}">Massive Dimensionality Reduction for the Left Ventricular Mesh</a>



#### Direct Learning Left Ventricular Meshes from CMR Images

> Train a convolutional neural network to learn LV meshes directly from MRI images

<i class="fa fa-sticky-note" aria-hidden="true"></i> <a href="javascript:showhide('cnn')">_Abstract_</a>
<div id="cnn" style="display:none;">
<p>  <div style="font-size:0.85em; text-align: justify;">Biomechanical studies of the left ventricle (LV) typically rely on a mesh of finite element nodes for a discrete representation of the LV geometry, which is used in an approximate numerical solution of the cardio-mechanical equations based on finite-element discretisation. This is typically done by first manually annotating cardiovascular magnetic resonance (CMR) scans, second creating a preliminary mesh, third manually correcting the mesh to account for motion. The whole process requires specialist knowledge, is time consuming and prone to human error, which prohibits its common adoption in the clinics. We propose to overcome these shortcomings by applying statistical pattern recognition techniques to CMR images. In particular, we train a convolutional neural network (CNN) to predict the LVM via learning its principal component representation directly from CMR scans. As a useful side-product we obtain a low-dimensional representation of the LVM, which is of interest for surrogate models (emulators) of the myocardium constitutive models.</div> </p>
</div>

<i class="fa fa-download fa-ld" aria-hidden="true"></i> PDF: <a class="page-link" href="{{ '/research/Romaszko, Borowska, Lazarus, Gao, Luo, Husmeier - Direct Learning Left Ventricular Meshes from CMR Images.pdf' | prepend: site.baseurl | prepend: site.url }}">Direct Learning Left Ventricular Meshes from CMR Images</a>
