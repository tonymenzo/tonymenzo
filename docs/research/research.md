---
layout: default
title: Research
nav_order: 3
mathjax: true
---
# Research 
{: .fw-700}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Summary
{: .py-3}

Many sub-fields of physics focus on formulating theories of macroscopic behavior from microscopic dynamics. High energy physics takes this to the extreme by using particle colliders as ''zeptoscopes'' (i.e. machines that can probe distances of $$\approx 10^{-21}$$ meters) to investigate the microscopic properties of fundamental matter. Amazingly, a relatively simple quantitative model, known as the Standard Model (SM) of elementary particle physics, can be used to predict the results of these collider experiments with astounding precision. However, while the SM correctly predicts a vast amount of collected experimental data there remains a subset of observations that are in *tension* with its theoretical predictions. My current research primarily focuses on *understanding* and *bridging* this gap between discrepant theoretical predictions and experimental measurements.

My research portfolio is comprised of two distinct approaches to this problem: (1) the design and development of numerical and symbolic computational frameworks, methodologies, and algorithms that allow for more precise and accurate comparisons between theory and experiment and (2) the investigation of novel precision tests and extensions beyond the SM (BSM) in the context of currently available and anticipated future experimental data.

I also have a keen interest in a range of other high-energy physics subjects, including holography, string phenomenology, black holes, and jet phenomenology.

## Publications
{: .py-3}

"***Modeling hadronization using machine learning***" - ***[2203.04983](https://arxiv.org/abs/2203.04983)*** - Authors: Ahmed Youssef, Phil Ilten, *Tony Menzo*, and Jure Zupan
<!--- ><details><summary><strong><em>Abstract</em></strong></summary> 
We present the first steps in the development of a new class of hadronization models utilizing machine learning techniques. We successfully implement, validate, and train a conditional sliced-Wasserstein autoencoder to replicate the Pythia generated kinematic distributions of first-hadron emissions, when the Lund string model of hadronization implemented in Pythia is restricted to the emissions of pions only. The trained models are then used to generate the full hadronization chains, with an IR cutoff energy imposed externally. The hadron multiplicities and cumulative kinematic distributions are shown to match the Pythia generated ones. We also discuss possible future generalizations of our results. /--->

"***On the implications of positive W mass shift***" - ***[2204.05992](https://arxiv.org/abs/2204.05992)*** - Authors: Reuven Balkin, Eric Madge, *Tony Menzo*, Yotam Soreq, Gilad Perez, and Jure Zupan
<!--- ><details><summary><strong><em>Abstract</em></strong></summary> 
We investigate the phenomenological implications of the recent W mass measurement by the CDF collaboration, which exhibits tension with the standard model (SM) electroweak fit. Performing the fit to the electroweak observables within the SM effective field theory, we find that the new physics that contributes either to the determination of the electroweak vacuum expectation value, or to the oblique parameters, can improve the agreement with data. The best description is obtained from a fit where flavor universality is not required in the new physics operators, with 2 to 3 σ indications for several nonzero Wilson coefficients. We point out that top partners with order TeV masses could lead to the observed shift in the W mass. /--->

"***The Earth Mover's Distance as a Measure of CP Violation***" - ***[2301.13211](https://arxiv.org/abs/2301.13211)*** - Authors: Adam Davis, *Tony Menzo*, Ahmed Youssef, and Jure Zupan
<!--- ><details><summary><strong><em>Abstract</em></strong></summary> 
We introduce a new unbinned two sample test statistic sensitive to CP violation utilizing the optimal transport plan associated with the Wasserstein (earth mover's) distance. The efficacy of the test statistic is shown via two examples of CP asymmetric distributions with varying sample sizes: the Dalitz distributions of $B^0\rightarrow K^+\pi^-\pi^0$ and  of $'D^0 \rightarrow \pi^+\pi^-\pi^0'$ decays. The windowed version of the Wasserstein distance test statistic is shown to have comparable sensitivity to CP violation as the commonly used energy test statistic, but also retains information about the localized distributions of CP asymmetry over the Dalitz plot. For large statistic datasets we introduce two modified Wasserstein distance based test statistics --- the binned and the sliced Wasserstein distance statistics, which show comparable sensitivity to CP violation, but  improved computing time and memory scalings. Finally, general extensions and applications of the introduced statistics are discussed. /--->

"***New physics in multi-electron muon decays***" - ***[2306.15631](https://arxiv.org/abs/2306.15631)*** - Authors: Matheus Hostert, *Tony Menzo*, Maxim Pospelov, and Jure Zupan 
<!--- ><details><summary><strong><em>Abstract</em></strong></summary> 
We study the exotic muon decays with five charged tracks in the final state. First, we investigate the Standard Model rate for $\mu \rightarrow 5e$ $(\mathcal{B}=4.0 \times 10^{-10})$ and find that the Mu3e experiment should have tens to hundreds of signal events per $10^{15}$ $\mu^+$ decays, depending on the signal selection strategy. We then turn to a neutrinoless $\mufivee$ decay that may arise in new-physics models with lepton-flavor-violating effective operators involving a dark Higgs $h_d$. Following its production in $\mu^+ \to e^+ h_d$ decays, the dark Higgs can undergo a decay cascade to two $e^+e^-$ pairs through two dark photons, $h_d \to \gamma_d \gamma_d \to 2(e^+e^-)$. We show that a $\mu \rightarrow 5e$ search at the Mu3e experiment, with potential sensitivity to the branching ratio at the $${\mathcal O}(10^{-12})$$ level or below, can explore new regions of parameter space and new physics scales as high as $$ \Lambda \sim 10^{15} $$ GeV. /--->

"***Reweighting Monte Carlo Predictions and Automated Fragmentation Variations in Pythia 8***" - ***[2308.13459](https://arxiv.org/abs/2308.13459)*** - Authors: Christian Bierlich, Phil Ilten, *Tony Menzo*, Stephen Mrenna, Maniel Szwec, Ahmed Youssef, and Jure Zupan 
<!--- ><details><summary><strong><em>Abstract</em></strong></summary> 
This work reports on a method for uncertainty estimation in simulated collider-event predictions. The method is based on a Monte Carlo-veto algorithm, and extends previous work on uncertainty estimates in parton showers by including uncertainty estimates for the Lund string-fragmentation model. This method is advantageous from the perspective of simulation costs: a single ensemble of generated events can be reinterpreted as though it was obtained using a different set of input parameters, where each event now is accompanied with a corresponding weight. This allows for a robust exploration of the uncertainties arising from the choice of input model parameters, without the need to rerun full simulation pipelines for each input parameter choice. Such explorations are important when determining the sensitivities of precision physics measurements. Accompanying code is available at [https://gitlab.com/uchep/mlhad-weights-validation](https://gitlab.com/uchep/mlhad-weights-validation)./--->


## On the horizon
{: .py-3}

- ***Towards a data-driven model of hadronization using normalizing flows***

- ***Connecting small and large scales at $$\mu \rightarrow e$$ conversion experiments: an EFT simulation tool***

- ***Flavorful low-scale leptogenesis***