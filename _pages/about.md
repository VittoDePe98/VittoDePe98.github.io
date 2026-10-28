---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

# 👋 About Me ([CV](files/CV_Vittoria_De_Pellegrini.pdf))

I am an Italian-Brazilian PhD candidate at [King Abdullah University of Science and Technology (KAUST)](https://www.kaust.edu.sa/) and a Doctoral Researcher with the industry-funded [DeepWave Consortium](https://deepwave.kaust.edu.sa/), which builds machine- and deep-learning workflows for subsurface reservoir characterization. My advisor is Prof. [Tariq Alkhalifah](https://www.kaust.edu.sa/en/study/faculty/tariq-alkhalifah).

💻 I focus on **deep generative AI**, especially **video diffusion models**, to model multi-phase subsurface fluid-flow dynamics. I build latent conditional and progressive autoregressive video diffusion models tailored to reservoir simulation data, generating video sequences of key field variables such as CO₂ gas saturation and pressure build-up for **geological carbon sequestration** studies. My workflows rely on CUDA-aware, reproducible CPU/GPU parallel pipelines running at scale on the KAUST IBEX and ORIX supercomputing clusters.

🔍 **Research interests:** Deep Learning · Deep Generative Modeling · Diffusion Models · Agentic AI · Reservoir Simulation · Petrophysics & Well-Logging · Geological Carbon Sequestration


# 🔥 News
- *2026.10*: &nbsp;🎉 **LAViG-FLOW** is published in **Journal of Geophysical Research: Machine Learning and Computation** (open access). [<a href="https://doi.org/10.1029/2026JH001294">Paper</a>] [<a href="https://github.com/VittoDePe98/LAViG-FLOW-pub">Code</a>]
- *2026.08*: &nbsp;🎤 Presented *Physics-Informed Latent Autoregressive Video Diffusion Models for Fluid Flow Simulations* at the **Sixth International Meeting for Applied Geoscience & Energy (SEG/AAPG)**.
- *2026.06*: &nbsp;🎤 Presented *Latent Autoregressive Video Diffusion Models for Fluid Flow Simulations* at the **87th EAGE Annual Conference & Exhibition**. [<a href="https://www.earthdoc.org/content/papers/10.3997/2214-4609.202610173">Paper</a>] [<a href="https://github.com/VittoDePe98/LAViG-FLOW-pub">Code</a>]
- *2025.08*: &nbsp;🎤 Presented *Towards Generative Modeling of CO₂ Geological Storage with Latent Conditional Diffusion Models* at the **Fifth International Meeting for Applied Geoscience & Energy (SEG/AAPG)**. [<a href="https://doi.org/10.1190/image2025-4303381.1">Paper</a>] [<a href="https://github.com/VittoDePe98/DMFCO2-pub">Code</a>]
- *2025.06*: &nbsp;🎤 Presented *A Conditional Diffusion Model for CO₂ Monitoring and Forecasting in Heterogeneous Geological Formations* at the **86th EAGE Annual Conference & Exhibition**. [<a href="https://doi.org/10.3997/2214-4609.202510212">Paper</a>] [<a href="https://github.com/VittoDePe98/DMFCO2-pub">Code</a>]
- *2024.01*: &nbsp;🎓 Started my PhD in Earth Science and Engineering at KAUST, joining the DeepWave Consortium.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Coming soon 🤗</div><a href="images/co2vidbench.gif"><img src='images/co2vidbench.gif' alt="CO2-VidBench" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

<span class=PaperTitle><b>CO2-VidBench: A Multiphysics 2D Video Dataset and Benchmark for Reservoir-Scale Generative Modeling of Geological CO₂ Sequestration</b></span> \\
 *Dataset and benchmark, to be released on Hugging Face* \\
**Vittoria De Pellegrini**
- 5,742 OPM Flow simulations of the SPE11B benchmark (an 8.4 km × 1.2 km cross-section): 4,242 on the reference geology and 1,500 with varied internal geology, plus **200 independent test simulations**, half in-distribution and half out-of-distribution (shifted injection rate, rock properties, geology, or all combined).
- Each simulation is a **201-frame video**, one frame per year for 200 years, on a 232 × 336 grid. It pairs **CO₂ gas saturation** and **pressure** with derived **density**, **P- and S-wave velocities**, and **near- and far-angle seismic stacks**.
- Comes with a benchmark of four tasks (**compression**, **unconditional** and **conditional generation**, and **post-injection forecasting**), plus simulator inputs, data loaders and evaluation code.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JGR: MLC 2026</div><a href="images/lavigflow.gif"><img src='images/lavigflow.gif' alt="LAViG-FLOW" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

<a class=PaperTitle href="https://doi.org/10.1029/2026JH001294"><b>LAViG-FLOW: Latent Autoregressive Video Generation for Fluid Flow Simulations</b></a> \\
 *Journal of Geophysical Research: Machine Learning and Computation, Vol. 3(5), e2026JH001294, October 2026* · Open Access \\
**Vittoria De Pellegrini**, Tariq Alkhalifah \\
[<a href="https://doi.org/10.1029/2026JH001294">Paper</a>] [<a href="https://github.com/VittoDePe98/LAViG-FLOW-pub">Code</a>]
- A latent autoregressive video generation diffusion framework that explicitly learns the **coupled evolution of saturation and pressure fields**.
- Dedicated autoencoders compress each state variable; a Video Diffusion Transformer models their temporal distribution.
- Autoregressive fine-tuning enables extrapolation beyond the observed time window, running **two orders of magnitude faster** than traditional numerical solvers.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EAGE 2025</div><a href="images/dmfco2.png"><img src='images/dmfco2.png' alt="DMFCO2" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

<a class=PaperTitle href="https://doi.org/10.3997/2214-4609.202510212"><b>A Conditional Diffusion Model for CO₂ Monitoring and Forecasting in Heterogeneous Geological Formations</b></a> \\
 *86th EAGE Annual Conference & Exhibition, Vol. 2025, pp. 1–5, June 2025* \\
**Vittoria De Pellegrini**, Damir Wamriew, Tariq Alkhalifah \\
[<a href="https://doi.org/10.3997/2214-4609.202510212">DOI</a>] [<a href="https://github.com/VittoDePe98/DMFCO2-pub">Code</a>]
- A conditional diffusion model for monitoring and forecasting CO₂ plume migration in heterogeneous geological formations.
</div>
</div>

- <span class=PaperTitle><b>Physics-Informed Latent Autoregressive Video Diffusion Models for Fluid Flow Simulations</b></span>, **Vittoria De Pellegrini**, Tariq Alkhalifah, *Sixth International Meeting for Applied Geoscience & Energy (SEG/AAPG), Expanded Abstracts, August 2026*
- <a class=PaperTitle href="https://www.earthdoc.org/content/papers/10.3997/2214-4609.202610173"><b>Latent Autoregressive Video Diffusion Models for Fluid Flow Simulations</b></a>, **Vittoria De Pellegrini**, Tariq Alkhalifah, *87th EAGE Annual Conference & Exhibition, Vol. 2026, pp. 1–5, June 2026* [<a href="https://www.earthdoc.org/content/papers/10.3997/2214-4609.202610173">DOI</a>] [<a href="https://github.com/VittoDePe98/LAViG-FLOW-pub">Code</a>]
- <a class=PaperTitle href="https://doi.org/10.1190/image2025-4303381.1"><b>Towards Generative Modeling of CO₂ Geological Storage with Latent Conditional Diffusion Models</b></a>, **Vittoria De Pellegrini**, Tariq Alkhalifah, *Fifth International Meeting for Applied Geoscience & Energy (SEG/AAPG), Expanded Abstracts 44(1), 1290–1294, August 2025* [<a href="https://doi.org/10.1190/image2025-4303381.1">DOI</a>] [<a href="https://github.com/VittoDePe98/DMFCO2-pub">Code</a>]
- <span class=PaperTitle><b>Development of Supervised Machine Learning Models for the Prediction of Well-Logs & Application on Wells at São Francisco and Santos Basins, Brazil</b></span>, **Vittoria De Pellegrini**, *M.Sc. Thesis, Politecnico di Torino, 2023* [<a href="https://github.com/VittoDePe98/Well-Logs_Predictive_Models">Code</a>]

# 📖 Education
- *2024.01 - 2028.11 (expected)*, **Ph.D. in Earth Science and Engineering**, King Abdullah University of Science and Technology (KAUST), Thuwal, Saudi Arabia. Advisor: Prof. Tariq Alkhalifah. *GPA 3.89/4.0*
- *2020.10 - 2023.07*, **M.Sc. in Petroleum Engineering**, Politecnico di Torino, Turin, Italy. *Grade 108/110*
- *2017.10 - 2020.07*, **B.Sc. in Civil Engineering**, Università degli Studi di Padova, Padua, Italy. *Grade 110/110*

# 💻 Experience
- *2024.01 - present*, **Doctoral Researcher**, DeepWave Research Consortium, KAUST, Thuwal, Saudi Arabia.
  - Build deep generative models for multi-phase subsurface fluid-flow dynamics, including latent conditional and progressive autoregressive video diffusion models for reservoir simulation data.
  - Run large-scale training and inference on the KAUST IBEX and ORIX multi-GPU clusters with CUDA-aware job scripts and CPU/GPU parallel workflows.
- *2023.02 - 2023.07*, **Graduate Researcher**, Politecnico di Torino, Turin, Italy.
  - Developed supervised machine learning models for conventional and advanced well-log prediction, applied to wells from the São Francisco and Santos basins in Brazil using PETROBRAS datasets.
- *2022.09 - 2022.11*, **Geophysics Intern**, Aramco Overseas Company B.V., Delft, Netherlands.
  - Built a 3D multi-physics synthetic model for a geothermal site in Saudi Arabia, generated surface wave dispersion curves and produced synthetic seismograms.

# 🌍 Languages
Italian (bilingual) · Brazilian Portuguese (bilingual) · English (advanced) · Spanish (intermediate) · Khaliji Arabic (basic)
