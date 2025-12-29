---
layout: home
title: Research
nav_order: 1 
mathjax: true
---
<!---1. TOC
{:toc}
/--->
<!---
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## **Summary**
{: .py-3}
/--->
<!---Many sub-fields of physics focus on formulating theories of macroscopic behavior from microscopic dynamics. High energy physics takes this to the extreme by using particle colliders as ''zeptoscopes'' (i.e. machines that can probe distances of $$\approx 10^{-21}$$ meters) to investigate the microscopic properties of fundamental matter. A relatively simple quantitative model, known as the Standard Model (SM) of elementary particle physics, can be used to predict the results of these collider experiments with astounding precision. However, while the SM correctly predicts a vast amount of collected experimental data there are still subsets of observations that are in *tension* with its theoretical predictions. My research primarily focuses on *understanding* and *bridging* this gap between discrepant theoretical predictions and experimental measurements./--->

# **Research** 
{: .fw-700}

I'm a theoretical particle physicist -- my research focuses on understanding how theoretical models defined at high-energies manifest in experimentally accessible observables. I spend my time (1) developing computational frameworks, methodologies, and algorithms to enable more precise and accurate comparisons between theory and experiment, and (2) investigating, estimating, and constraining novel phenomenology related experimental signatures of theoretical predictions in extensions of the Standard Model.

More specifically, I'm interested in model building, machine learning, optimal transport, hadronization, rare lepton decays, effective field theory, proton decay, solutions to the hierarchy problem, tumbling gauge theories, grand unified theories, gauge/gravity duality, cosmology, string phenomenology, functional programming, and more...

# **Publications**
{: .fw-700}

<style>
  .project-container {
    display: grid;
    grid-template-columns: 1fr;
    gap: 2rem 1rem;
    width: 98%;
  }

  .project-block {
    position: relative;
    overflow: hidden;
    width: 100%;
    aspect-ratio: 3.236 / 2.2;
    max-width: 350px;
    background-color: #e0e0e0;
    display: block;
    border: 1px solid black;
    text-decoration: none;
    color: inherit;
  }

  .project-block img {
    width: 100%;
    height: 100%;
    object-fit: contain;
    object-position: center;
    transform: scale(var(--thumb-scale, 1));  /* zoom out effect, defaults to 1 */
    transform-origin: center;
    display: block;
  }

  .project-overlay {
    position: absolute;
    top: 0; 
    left: 0;
    width: 100%; height: 100%;
    display: flex;
    /*align-items: flex-end;*/ /* Place text box at top */
    align-items: flex-start;   /* Place text box at bottom */
    justify-content: center;
    padding: 3px 3px 3px 3px;
    background-color: rgba(250, 250, 250, 0.6);
  }

  .project-text-strip {
    width: 100%;
    margin-top: 0;
    background: rgba(255, 255, 255, 0.4);
    backdrop-filter: blur(3px);
    -webkit-backdrop-filter: blur(3px);
    color:  rgba(49, 49, 49, 1);;
    font-size: 0.9em;
    font-weight: 900;
    padding: 0.5em 0.75em;
    text-align: left;
    border: 1px solid #ccc;
  }

  .project-top-text {
  position: absolute;
  /*top: 10px;*/
  bottom: 0px;
  right: 10px;
  color: rgba(134, 0, 0, 1);
  font-weight: bold;
  /*background: rgba(255, 255, 255, 0.6);*/
  padding: 0em 0em;
  /*border: 1px solid #ccc;*/
  /*backdrop-filter: blur(5px);*/
  /*-webkit-backdrop-filter: blur(5px);*/
  z-index: 2;
}

  @media (min-width: 600px) {
    .project-container {
      grid-template-columns: repeat(2, 1fr);
    }
  }
</style>

<!--- Import external font /--->
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@900&display=swap" rel="stylesheet">
<style>
.special-text {
  font-family: "Orbitron", normal;  /* or any web-safe or imported font */
  font-size: 1.1em;
  font-weight: 900;
  color: #111111ff;
  margin: 0.1em 0.1em;
}
</style>

<div class="project-container">
  <a href="https://arxiv.org/abs/2512.15867" class="project-block" style="--thumb-scale: 1;">
    <img src="{{ './images/thumbnails/code/heptapod_diagram_focused.svg' | relative_url }}" alt="iHOMER">
    <div class="project-top-text special-text">2512.15867</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        HEPTAPOD: Orchestrating High-Energy-Physics Workflows Towards Autonomous Agency
      </div>
    </div>
  </a>
  <a href="https://arxiv.org/abs/2509.03592" class="project-block" style="--thumb-scale: 1.5;">
    <img src="{{ './images/thumbnails/iHOMER.png' | relative_url }}" alt="iHOMER">
    <div class="project-top-text special-text">2509.03592</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        Iterative HOMER with uncertainties
      </div>
    </div>
  </a>

  <a href="https://arxiv.org/abs/2507.15271" class="project-block" style="--thumb-scale: 1.3;">
    <img src="{{ './images/thumbnails/SHiP_tau_ALP.svg' | relative_url }}" alt="tau_init_ALPs">
    <div class="project-top-text special-text">2507.15271</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        Long-lived Axion-Like Particles from Tau Decays
      </div>
    </div>
  </a>

  <a href="https://arxiv.org/abs/2505.00142" class="project-block">
    <img src="{{ './images/thumbnails/posthoc_flav.png' | relative_url }}" alt="posthocflavor" style="--thumb-scale: 1.6;">
    <div class="project-top-text special-text">2505.00142</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        Post-hoc reweighting of hadron production in the Lund string model
      </div>
    </div>
  </a>

  <a href="https://arxiv.org/abs/2503.07722" class="project-block" style="--thumb-scale: 0.9;">
    <img src="{{ './images/thumbnails/time_dependence.svg' | relative_url }}" alt="LFV_ULDM">
    <div class="project-top-text special-text">2503.07722</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        Direct Detection of Ultralight Dark Matter via Charged Lepton Flavor Violation
      </div>
    </div>
  </a>

  <a href="https://arxiv.org/abs/2503.05667" class="project-block" style="--thumb-scale: 1.25;">
    <img src="{{ './images/thumbnails/HOMER_gluons.svg' | relative_url }}" alt="HOMER_gluons">
    <div class="project-top-text special-text">2503.05667</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        Characterizing the hadronization of parton showers using the HOMER method
      </div>
    </div>
  </a>

  <a href="https://arxiv.org/abs/2502.12314" class="project-block" style="--thumb-scale: 1.2;">
    <img src="{{ './images/thumbnails/production_detection_schematic.svg' | relative_url }}" alt="fusion_scalars">
    <div class="project-top-text special-text">2502.12314</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        Searching for exotic scalars at fusion reactors
      </div>
    </div>
  </a>

  <a href="https://arxiv.org/abs/2411.02194" class="project-block" style="--thumb-scale: 1.25;">
    <img src="{{ './images/thumbnails/RSA.svg' | relative_url }}" alt="RSA">
    <div class="project-top-text special-text">2411.02194</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        Rejection Sampling with Autodifferentiation - Case study: Fitting a Hadronization Model
      </div>
    </div>
  </a>

  <a href="https://arxiv.org/abs/2410.06342" class="project-block" style="--thumb-scale: 1.25;">
    <img src="{{ './images/thumbnails/HOMER.svg' | relative_url }}" alt="HOMER">
    <div class="project-top-text special-text">2410.06342</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        Describing hadronization via Histories and Observables for Monte Carlo Event Reweighting
      </div>
    </div>
  </a>

  <a href="https://arxiv.org/abs/2407.03450" class="project-block" style="--thumb-scale: 0.9;">
    <img src="{{ './images/thumbnails/muon_capture.svg' | relative_url }}" alt="muon_BNV">
    <div class="project-top-text special-text">2407.03450</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        Muon-induced baryon number violation
      </div>
    </div>
  </a>

  <a href="https://arxiv.org/abs/2406.13818" class="project-block" style="--thumb-scale: 0.9;">
    <img src="{{ './images/thumbnails/tower.svg' | relative_url }}" alt="mu2e_EFT">
    <div class="project-top-text special-text">2406.13818</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        Effective theory tower for &mu; &rarr; e conversion
      </div>
    </div>
  </a>

  <a href="https://arxiv.org/abs/2311.09296" class="project-block" style="--thumb-scale: 1.2;">
    <img src="{{ './images/thumbnails/MAGIC.png' | relative_url}}" alt="MAGIC">
    <div class="project-top-text special-text">2311.09296</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        Towards a data-driven model of hadronization using normalizing flows
      </div>
    </div>
  </a>

  <a href="https://arxiv.org/abs/2308.13459" class="project-block" style="--thumb-scale: 1.9;">
    <img src="{{ './images/thumbnails/insitu_kin.png' | relative_url }}" alt="insitu_kin">
    <div class="project-top-text special-text">2308.13459</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        Reweighting Monte Carlo Predictions and Automated Fragmentation Variations in Pythia 8
      </div>
    </div>
  </a>

  <a href="https://arxiv.org/abs/2306.15631" class="project-block" style="--thumb-scale: 0.9;">
    <img src="{{ './images/thumbnails/mu5e.svg' | relative_url}}" alt="mu5e">
    <div class="project-top-text special-text">2306.15631</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        New physics in multi-electron muon decays
      </div>
    </div>
  </a>

  <a href="https://arxiv.org/abs/2301.13211" class="project-block" style="--thumb-scale: 1.2;">
    <img src="{{ './images/thumbnails/WqCP_ACP.png' | relative_url }}" alt="gaussian_flow">
    <div class="project-top-text special-text">2301.13211</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        The Earth Mover's Distance as a Measure of CP Violation
      </div>
    </div>
  </a>

  <a href="https://arxiv.org/abs/2204.05992" class="project-block" style="--thumb-scale: 1.1;">
    <img src="{{ './images/thumbnails/Wmass_NP.png' | relative_url}}" alt="mW">
    <div class="project-top-text special-text">2204.05992</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        On the implications of positive W mass shift
      </div>
    </div>
  </a>

  <a href="https://arxiv.org/abs/2203.04983" class="project-block" style="--thumb-scale: 0.9;">
    <img src="{{ './images/thumbnails/hadronization_cartoon.svg' | relative_url }}" alt="hadronization">
    <div class="project-top-text special-text">2203.04983</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        Modeling hadronization using machine learning
      </div>
    </div>
  </a>
</div>

<!---
"***Post-hoc reweighting of hadron production in the Lund string model***" - ***[2505.00142](https://arxiv.org/abs/2505.00142)*** - Authors: Benoit Assi, Christian Bierlich, Phil Ilten, *Tony Menzo*, Stephen Mrenna, Manuel Szewc, Micheal Wilkinson, Ahmed Youssef, and Jure Zupan

"***Direct Detection of Ultralight Dark Matter via Charged Lepton Flavor Violation***" - ***[2503.07722](https://arxiv.org/abs/2503.07722)*** - Authors: Innes Bigaran, Patrick Fox, Yann Gouttenoire, Roni Harnik, Gordan Krnjaic, *Tony Menzo*, and Jure Zupan

"***Characterizing the hadronization of parton showers using the HOMER method***" - ***[2503.05667](https://arxiv.org/abs/2503.05667)*** - Authors: Benoit Assi, Christian Bierlich, Phil Ilten, *Tony Menzo*, Stephen Mrenna, Manuel Szewc, Micheal Wilkinson, Ahmed Youssef, and Jure Zupan

"***Searching for exotic scalars at fusion reactors***" - ***[2502.12314](https://arxiv.org/abs/2502.12314)*** - Authors: Chaja Baruch, Patrick Fitzpatrick, *Tony Menzo*, Yotam Soreq, Sokratis Trifinopoulos, and Jure Zupan

"***Rejection Sampling with Autodifferentiation - Case study: Fitting a Hadronization Model***" - ***[2411.02194](https://arxiv.org/pdf/2411.02194)*** - Authors: Nick Heller, Phil Ilten, *Tony Menzo*, Stephen Mrenna, Benjamin Nachman, Andrzej Siodmok, Manuel Szwec, and Ahmed Youssef

"***Describing hadronization via Histories and Observables for Monte Carlo Event Reweighting***" - ***[2410.06342](https://arxiv.org/abs/2410.06342)*** - Authors: Christian Bierlich, Phil Ilten, *Tony Menzo*, Stephen Mrenna, Maniel Szwec, Michael Wilkinson, Ahmed Youssef, and Jure Zupan

"***Muon-induced baryon number violation***" - ***[2407.03450](https://arxiv.org/abs/2407.03450)*** - Authors: Patrick J. Fox, Matheus Hostert, *Tony Menzo*, Maxim Pospelov, and Jure Zupan

"***Effective theory tower for $$\mu \to e$$ conversion***" - ***[2406.13818](https://arxiv.org/abs/2406.13818)*** - Authors: Wick Haxton,  Kenneth McElvain,*Tony Menzo*, Evan Rule, and Jure Zupan


"***Towards a data-driven model of hadronization using normalizing flows***" - ***[2311.09296](https://arxiv.org/abs/2311.09296)*** - Authors: Christian Bierlich, Phil Ilten, *Tony Menzo*, Stephen Mrenna, Maniel Szwec, Michael Wilkinson, Ahmed Youssef, and Jure Zupan

"***Reweighting Monte Carlo Predictions and Automated Fragmentation Variations in Pythia 8***" - ***[2308.13459](https://arxiv.org/abs/2308.13459)*** - Authors: Christian Bierlich, Phil Ilten, *Tony Menzo*, Stephen Mrenna, Manuel Szwec, Michael Wilkinson, Ahmed Youssef, and Jure Zupan

"***New physics in multi-electron muon decays***" - ***[2306.15631](https://arxiv.org/abs/2306.15631)*** - Authors: Matheus Hostert, *Tony Menzo*, Maxim Pospelov, and Jure Zupan

"***The Earth Mover's Distance as a Measure of CP Violation***" - ***[2301.13211](https://arxiv.org/abs/2301.13211)*** - Authors: Adam Davis, *Tony Menzo*, Ahmed Youssef, and Jure Zupan

"***On the implications of positive W mass shift***" - ***[2204.05992](https://arxiv.org/abs/2204.05992)*** - Authors: Reuven Balkin, Eric Madge, *Tony Menzo*, Yotam Soreq, Gilad Perez, and Jure Zupan

"***Modeling hadronization using machine learning***" - ***[2203.04983](https://arxiv.org/abs/2203.04983)*** - Authors: Ahmed Youssef, Phil Ilten, *Tony Menzo*, and Jure Zupan

/--->


# **Dissertation**
{: .fw-700}
<div class="project-container">
  <a href="dissertation/[Menzo]RareLeptonDecaysAndDifferentiableHadronizationModels.pdf" class="project-block" style="--thumb-scale: 0.9;">
    <img src="{{ './images/thumbnails/dissertation.png' | relative_url}}" alt="dissertation">
    <div class="project-overlay">
      <div class="project-text-strip" style="text-align: center;">
        Rare Lepton Decays and Differentiable Hadronization Models<br> <small>From Signatures of New Physics to Data-driven Event Generation</small>
      </div>
    </div>
  </a>
</div>

# **Presentations**
{: .fw-700}
<!---
Containers for displaying project/presentation blocks
/--->

<style>
  .container {
    display: flex;
    flex-direction: column;
    gap: 1rem;
    width: 98%;
  }

  .responsive-block {
    flex: 1;
    position: relative;
    overflow: hidden;
    width: 100%;
    aspect-ratio: 3.236 / 2.3;
    max-width: 500px;
    background-color: #e0e0e0;
    display: block;
    border: 1px solid black;
    text-decoration: none;
    color: inherit;
  }

  .responsive-block img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
  }

  .overlay {
    position: absolute;
    top: 0; left: 0;
    width: 100%; height: 100%;
    display: flex;
    align-items: flex-end;
    justify-content: center;
    padding: 0 10px 10px 10px;
    pointer-events: none;
    background-color: rgba(250, 250, 250, 0.6);
  }

  .text-strip {
    width: 100%;
    background: rgba(255, 255, 255, 0.4);
    backdrop-filter: blur(5px);
    -webkit-backdrop-filter: blur(5px);
    color: black;
    font-size: 0.9em;
    font-weight: bold;
    padding: 0.5em 0.75em;
    text-align: left;
    z-index: 2;
    pointer-events: auto;
    border: 1px solid #ccc;
    <!---border-radius: 4px;--->
  }

  @media (min-width: 600px) {
    .container {
      flex-direction: row;
    }
  }
</style>

<!---
Examples of syntax for project/presentation blocks.
/--->

<div class="container">
  <a href="presentations/[Menzo]AFlavorfulAndDarkCascadeForLowScaleLeptogenesis.pdf" class="responsive-block">
    <img src="{{ './images/thumbnails/fdlslg.svg' | relative_url }}" alt="fdlslg">
    <div class="overlay">
      <div class="text-strip">
        A Flavorful and Dark Cascade for Low-scale Leptogenesis
      </div>
    </div>
  </a>

  <!-- Add more blocks like this if needed -->
  <a href="/another-page/" class="responsive-block">
    <img src="{{ './images/thumbnails/mu5e.svg' | relative_url }}" alt="mu5e">
    <div class="overlay">
      <div class="text-strip">
        Heavy and Light New Physics in Rare Muon Decays
      </div>
    </div>
  </a>

</div>

<!---
## On the horizon
{: .py-3}

- ***Flavorful low-scale leptogenesis***
/--->
