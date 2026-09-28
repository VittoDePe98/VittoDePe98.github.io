---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 👋 About Me

I am an Italian-Brazilian PhD student at [King Abdullah University of Science and Technology (KAUST)](https://www.kaust.edu.sa/) and a Doctoral Researcher with the industry-funded [DeepWave Consortium](https://deepwave.kaust.edu.sa/), which builds machine- and deep-learning workflows for subsurface reservoir characterization. My advisor is Prof. Tariq Alkhalifah.

💻 I focus on **deep generative AI** — especially **video diffusion models** — to model multi-phase subsurface fluid-flow dynamics. I build latent conditional and progressive autoregressive video diffusion models tailored to reservoir simulation data, generating video sequences of key field variables such as CO₂ gas saturation and pressure build-up for **geological carbon sequestration** studies. My workflows rely on CUDA-aware, reproducible CPU/GPU parallel pipelines running at scale on the KAUST IBEX supercomputing cluster.

🔍 **Research interests:** Deep Learning · Deep Generative Modeling · Diffusion Models · Reservoir Simulation · Petrophysics & Well-Logging · Geological Carbon Storage

📄 You can find my full CV [here](files/CV_Vittoria_De_Pellegrini.pdf).

<a href='https://scholar.google.com/citations?user=aUvIDgUAAAAJ'>Google Scholar citations <strong><span id='total_cit'>0</span></strong></a> <a href='https://scholar.google.com/citations?user=aUvIDgUAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

# 🔥 News
- *2026.02*: &nbsp;📄 Updated version (v2) of **LAViG-FLOW** released on arXiv.
- *2026.01*: &nbsp;🎉 **LAViG-FLOW: Latent Autoregressive Video Generation for Fluid Flow Simulations** is out on [arXiv](https://arxiv.org/abs/2601.13190), with code on [GitHub](https://github.com/VittoDePe98/LAViG-FLOW-pub).
- *2026.06*: &nbsp;🎤 Presented *Latent Autoregressive Video Diffusion Models for Fluid Flow Simulations* at the **87th EAGE Annual Conference & Exhibition**. <!-- TODO confirm month -->
- *2025.08*: &nbsp;🎤 Presented *Towards Generative Modeling of CO₂ Geological Storage with Latent Conditional Diffusion Models* at the **Fifth International Meeting for Applied Geoscience & Energy (SEG/AAPG)**.
- *2025.06*: &nbsp;🎤 Presented *A Conditional Diffusion Model for CO₂ Monitoring and Forecasting in Heterogeneous Geological Formations* at the **86th EAGE Annual Conference & Exhibition**.
- *2024.01*: &nbsp;🎓 Started my PhD in Earth Science and Engineering at KAUST, joining the DeepWave Consortium.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/lavigflow.gif' alt="LAViG-FLOW" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LAViG-FLOW: Latent Autoregressive Video Generation for Fluid Flow Simulations](https://arxiv.org/abs/2601.13190)

**Vittoria De Pellegrini**, Tariq Alkhalifah

[**arXiv**](https://arxiv.org/abs/2601.13190) \| [**Code**](https://github.com/VittoDePe98/LAViG-FLOW-pub)
- A latent autoregressive video generation diffusion framework that explicitly learns the **coupled evolution of saturation and pressure fields**.
- Dedicated autoencoders compress each state variable; a Video Diffusion Transformer models their temporal distribution.
- Autoregressive fine-tuning enables extrapolation beyond the observed time window, running **two orders of magnitude faster** than traditional numerical solvers.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EAGE 2025</div><img src='images/dmfco2.png' alt="DMFCO2" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Conditional Diffusion Model for CO₂ Monitoring and Forecasting in Heterogeneous Geological Formations](https://doi.org/10.3997/2214-4609.202510212)

**Vittoria De Pellegrini**, Damir Wamriew, Tariq Alkhalifah

*86th EAGE Annual Conference & Exhibition, Vol. 2025, pp. 1–5, June 2025*

[**DOI**](https://doi.org/10.3997/2214-4609.202510212) \| [**Code**](https://github.com/VittoDePe98/DMFCO2-pub)
- A conditional diffusion model for monitoring and forecasting CO₂ plume migration in heterogeneous geological formations.
</div>
</div>

- [Latent Autoregressive Video Diffusion Models for Fluid Flow Simulations](https://scholar.google.com/citations?user=aUvIDgUAAAAJ), **Vittoria De Pellegrini**, Tariq Alkhalifah, **87th EAGE Annual Conference & Exhibition, 2026**
- [Towards Generative Modeling of CO₂ Geological Storage with Latent Conditional Diffusion Models](https://github.com/VittoDePe98/DMFCO2-pub), **Vittoria De Pellegrini**, Tariq Alkhalifah, **Fifth International Meeting for Applied Geoscience & Energy (SEG/AAPG), Expanded Abstracts 44(1), 1290–1294, 2025**
- [Development of Supervised Machine Learning Models for the Prediction of Well-Logs & Application on Wells at São Francisco and Santos Basins, Brazil](https://github.com/VittoDePe98/Well-Logs_Predictive_Models), **Vittoria De Pellegrini**, **M.Sc. Thesis, Politecnico di Torino, 2023**

# 📖 Educations
- *2024.01 - 2027.12 (expected)*, **Ph.D. in Earth Science and Engineering**, King Abdullah University of Science and Technology (KAUST), Thuwal, Saudi Arabia. *GPA 3.89*
- *2020.10 - 2023.07*, **M.Sc. in Petroleum Engineering**, Politecnico di Torino, Turin, Italy. *Grade 108/110*
- *2017.10 - 2020.07*, **B.Sc. in Civil Engineering**, Università degli Studi di Padova, Padua, Italy. *Grade 110/110*

# 💻 Experience
- *2024.01 - present*, **Doctoral Researcher**, DeepWave Research Consortium, KAUST, Thuwal, Saudi Arabia.
  - Build deep generative models for multi-phase subsurface fluid-flow dynamics, including latent conditional and progressive autoregressive video diffusion models for reservoir simulation data.
  - Run large-scale training and inference on the KAUST IBEX multi-GPU cluster with CUDA-aware job scripts and CPU/GPU parallel workflows.
- *2023.02 - 2023.07*, **Graduate Researcher**, Politecnico di Torino, Turin, Italy.
  - Developed supervised machine learning models for conventional and advanced well-log prediction, applied to wells from the São Francisco and Santos basins in Brazil using PETROBRAS datasets.
- *2022.09 - 2022.11*, **Geophysics Intern**, Aramco Overseas Company B.V., Delft, Netherlands.
  - Built a 3D multi-physics synthetic model for a geothermal site in Saudi Arabia, generated surface wave dispersion curves and produced synthetic seismograms.

# 🌍 Languages
Italian (bilingual) · Brazilian Portuguese (bilingual) · English (advanced) · Spanish (intermediate) · Khaliji Arabic (basic)
