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

I am a PhD student at <a href="http://silab.kaist.ac.kr/">System Intelligence</a> lab in KAIST (Korea Advanced Institute of Science and Technology). I am fortunate to be advised by Professor <a href="https://scholar.google.com/citations?user=sH2a0nkAAAAJ&hl=en">Jinkyoo Park</a>. Previously, I was a research intern at <a href="https://europe.naverlabs.com/">NaverLabs Europe</a> and <a href="https://mila.quebec/en">Mila</a>, and a visiting intern at <a href="https://hkust.edu.hk/">HKUST</a>. Here is my <a href="https://dbsxodud-11.github.io/assets/cv.pdf" class="link-in-list"> cv</a>.

My research interest lies in building generative agents that make reliable decisions in the real world. Simulators of real-world systems are becoming easier to build with the help of LLMs, but they never perfectly reflect reality or user intent. I am interested in how to align simulators with user intent and how to train generative policies that stay robust under such uncertainty. To this end, my research focuses on user-simulator alignment, reinforcement learning under uncertainty, and black-box optimization.

During my earlier PhD years, I studied amortized samplers, such as GFlowNets, that learn diverse generative policies for text, image, and biological sequence generation. I also worked on transportation-related projects, such as traffic light management and network layout design, where I formulated each task as a black-box optimization problem over an existing simulator.


# 🔥 News
- *2026.09*: &nbsp;🎉🎉 8 papers accepted in 2026 (1 WSDM, 1 TMLR, 1 ICLR, 1 ICML, 1 CIKM, 3 NeurIPS) 
- *2026.08*: &nbsp;🎉🎉 I started internship at NaverLabs Europe, Hosted by <a href="https://scholar.google.com/citations?user=B3-rbrcAAAAJ&hl=en">Darko Drakulic</a> and <a href="https://www.linkedin.com/in/sofiazaourar/">Sofia Michel</a>
- *2025.12*: &nbsp;🎉🎉 5 papers accepted in 2025 (1 ICLR, 1 CVPR, 2 ICML, 1 KDD)
- *2025.06*: &nbsp;🎉🎉 I started internship at Mila, Hosted by <a href="https://yoshuabengio.org/">Yoshua Bengio</a>
- *2024.12*: &nbsp;🎉🎉 5 papers accepted in 2024 (1 ICLR, 1 ICML, 1 KDD, 2 NeurIPS)
- *2024.09*: &nbsp;🎉🎉 I started internship at HKUST, Hosted by <a href="https://ling-pan.github.io/">Ling Pan</a>

<!-- - *2024.05*: &nbsp;🎉🎉 One paper accepted to KDD 2024 -->
<!-- - *2024.05*: &nbsp;🎉🎉 One paper accepted to ICML 2024 -->
<!-- - *2024.03*: &nbsp;🎉🎉 One paper accepted to ICLR GenAI4DM Workshop 2024 (Spotlight) -->
<!-- - *2024.01*: &nbsp;🎉🎉 One paper accepted to ICLR 2024 (Spotlight) -->
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2024.03 - current*, Ph.D in Industrial and Systems Engineering, KAIST
- *2022.09 - 2024.02*, M.S in Graduate School of AI, KAIST
- *2018.03 - 2022.08*, B.S in Industrial and Systems Engineering & Computer Science, KAIST

# 💻 Internships
<!-- - *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
- *2026.08 - 2026.11*, Research Intern at NaverLabs Europe, hosted by <a href="https://scholar.google.com/citations?user=B3-rbrcAAAAJ&hl=en">Darko Drakulic</a> and <a href="https://www.linkedin.com/in/sofiazaourar/">Sofia Michel</a>
- *2025.06 - 2025.11*, Research Intern at Mila, hosted by <a href="https://yoshuabengio.org/">Yoshua Bengio</a>
- *2024.09 - 2025.03*, Visiting Intern at HKUST, hosted by <a href="https://ling-pan.github.io/">Ling Pan</a>
- *2021.03 - 2021.08*, Research Intern at Kakao Recommendation Team


# 📝 Publications 
(\*: Equal Contribution) 

## Preprints

- **[P4] Noise-Space Reward Alignment for Few-Step Generative Models**  
[[paper]](https://arxiv.org/abs/2610.21125) / [[code]](https://github.com/Shin-woocheol/NPO)  
Woocheol Shin, **Taeyoung Yun**, Jiwon Sung, Hyeongyu Kang, Jeongmin Park, Jaewoo Lee, Kyuil Sim, Dohyun Kim, Yutong He, Jinkyoo Park  
<span class="venue">**Arxiv 2026**</span>

- **[P3] Decoupling Exploration and Exploitation in GFlowNets via Policy Evaluation**  
[[paper]]() / [[code]]()  
**Taeyoung Yun\***, Inhyuck Song\*, Jinkyoo Park, Ling Pan  
<span class="venue">**Arxiv 2026**</span>

- **[P2] Robust Exploration through Generative Replay**  
[[paper]](https://openreview.net/forum?id=sJbMlWrd9b) / [[code]]()  
Inhyuck Song, **Taeyoung Yun**, Jaewoo Lee, Jinkyoo Park  
<span class="venue">**Arxiv 2026**</span> <span class="venue">**ICML 2026 RLxF Workshop**</span>

- **[P1] Improving Sampling Distribution of Off-policy Training in Generative Flow Networks**  
[[paper]](https://openreview.net/forum?id=yyMfN4EHqD) / [[code]]()  
**Taeyoung Yun**, Sujin Yun, Jinkyoo Park, Ling Pan  
<span class="venue">**Arxiv 2025**</span> 

## Conference Publications

- **[C17] Posterior Inference in Latent Space for Scalable Constrained Black-box Optimization**  
[[paper]](https://arxiv.org/abs/2507.00480) / [[code]](https://github.com/umkiyoung/CiBO)  
Kiyoung Om\*, Kyuil Sim\*, **Taeyoung Yun\***, Hyeongyu Kang, Jinkyoo Park  
<span class="venue">**NeurIPS 2026**</span> <span class="venue">**NeurIPS 2025 SPIGM Workshop**</span>

- **[C16] Aligning Few-Step Generative Models by Amortizing Sample-based Variational Inference**  
[[paper]](https://arxiv.org/abs/2605.26552) / [[code]](https://github.com/Jaewoopudding/FAV)  
Jaewoo Lee\*, Hyeongyu Kang\*, Dohyun Kim, Kyuil Sim, Woocheol Shin, Minsu Kim, **Taeyoung Yun**, Jeongjae Lee, Sanghyeok Choi, Tabitha Edith Lee, Jongchul Ye, Jinkyoo Park  
<span class="venue">**NeurIPS 2026**</span> <span class="venue">**ICML 2026 SPIGM Workshop**</span>

- **[C15] Automated Kernel Discovery for Understanding High-dimensional Bayesian Optimization**  
[[paper]](https://arxiv.org/abs/2605.20249) / [[code]](https://github.com/dbsxodud-11/automatic_kernel_discovery)  
**Taeyoung Yun\***, Woocheol Shin\*, Inhyuck Song, Jaewoo Lee, Jinkyoo Park  
<span class="venue">**NeurIPS 2026**</span> <span class="venue">**ICML 2026 DEMO Workshop**</span>

- **[C14] SUMO-SimQA: A Benchmark for LLM Cross-File Reasoning over Traffic Simulation Files**  
[[paper]]() / [[code]](https://github.com/urban-ai-institute/kra34-sumo-llm-qa-benchmark)  
Jeeyun Chang\*, **Taeyoung Yun\***, Minwoo Jeong, Jinkyoo Park, Yoonjin Yoon  
<span class="venue">**CIKM 2026**</span> <span class="venue">**Short Paper**</span>

- **[C13] Active Attacks: Red-teaming LLMs via Adaptive Environments**  
[[paper]](https://www.arxiv.org/abs/2509.21947) / [[code]](https://github.com/dbsxodud-11/active_attacks)  
**Taeyoung Yun**, Pierre-Luc St-Charles, Jinkyoo Park, Yoshua Bengio, Minsu Kim  
<span class="venue">**ICML 2026**</span>

- **[C12] Diffusion Alignment as Variational Expectation-Maximization**  
[[paper]](https://arxiv.org/abs/2510.00502) / [[code]](https://github.com/Jaewoopudding/dav)  
Jaewoo Lee, Minsu Kim, Sanghyeok Choi, Inhyuck Song, Sujin Yun, Hyeongyu Kang, Woocheol Shin, **Taeyoung Yun**, Kiyoung Om, Jinkyoo Park \\
<span class="venue">**ICLR 2026**</span> 

- **[C11] Urban Traffic Network Layout Optimization with Guided Discrete Diffusion Models** \\
[[paper]](https://dl.acm.org/doi/abs/10.1145/3773966.3777950) / [[code]](https://github.com/dbsxodud-11/traffic_layout)  
**Taeyoung Yun**, Inhyuck Song, Woocheol Shin, Yujin Shin, Sungpil Woo, Sunhwan Lim, Jinkyoo Park  
<span class="venue">**WSDM 2026**</span>

- **[C10] Wind Farm Layout Optimization with Diffusion Models**  
[[paper]](https://dl.acm.org/doi/10.1145/3711896.3737181) / [[code]](https://github.com/dbsxodud-11/layopt)  
Yujin Shin\*, **Taeyoung Yun\***, Sujin Yun, Sungpil Woo, Sunhwan Lim, Jinkyoo Park  
<span class="venue">**KDD 2025**</span>

- **[C9] Posterior Inference with Diffusion Models for High-dimensional Black-box Optimization**  
[[paper]](https://arxiv.org/abs/2502.16824) / [[code]](https://github.com/umkiyoung/DiBO)  
**Taeyoung Yun\***, Kiyoung Om\*, Jaewoo Lee, Sujin Yun, Jinkyoo Park  
<span class="venue">**ICML 2025**</span> <span class="venue">**ICLR 2025 FPI Workshop**</span>

- **[C8] Improved Off-policy Reinforcement Learning in Biological Sequence Design**  
[[paper]](https://arxiv.org/abs/2410.04461) / [[code]](https://github.com/hyeonahkimm/delta_cs)  
Hyeonah Kim, Minsu Kim, **Taeyoung Yun**, Sanghyeok Choi, Emmanuel Bengio, Alex Hernández-García, Jinkyoo Park  
<span class="venue">**ICML 2025**</span> <span class="venue">**NeurIPS 2024 AIDrugX Workshop**</span>

- **[C7] Learning to Sample Effective and Diverse Prompts for Text-to-Image Generation**  
[[paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Yun_Learning_to_Sample_Effective_and_Diverse_Prompts_for_Text-to-Image_Generation_CVPR_2025_paper.html) / [[code]](https://github.com/dbsxodud-11/PAG)  
**Taeyoung Yun**, Dinghuai Zhang, Jinkyoo Park, Ling Pan  
<span class="venue">**CVPR 2025**</span> <span class="venue venue--award">**Qualcomm Innovation Fellowship Korea Finalist**</span>

- **[C6] Adaptive Teachers for Amortized Samplers**  
[[paper]](https://arxiv.org/abs/2410.01432) / [[code]](https://github.com/alstn12088/adaptive-teacher)  
Minsu Kim\*, Sanghyeok Choi\*, **Taeyoung Yun**, Emmanuel Bengio, Leo Feng, Jarrid Rector-Brooks, Sungsoo Ahn, Jinkyoo Park, Nikolay Malkin, Yoshua Bengio  
<span class="venue">**ICLR 2025**</span>

- **[C5] Guided Trajectory Generation with Diffusion Models for Offline Model-based Optimization**  
[[paper]](https://arxiv.org/abs/2407.01624) / [[code]](https://github.com/dbsxodud-11/GTG)  
**Taeyoung Yun**, Sujin Yun, Jaewoo Lee, Jinkyoo Park  
<span class="venue">**NeurIPS 2024**</span>

- **[C4] GTA: Generative Trajectory Augmentation with Guidance for Offline Reinforcement Learning**  
[[paper]](https://arxiv.org/abs/2405.16907) / [[code]](https://github.com/Jaewoopudding/GTA)  
Jaewoo Lee\*, Sujin Yun\*, **Taeyoung Yun**, Jinkyoo Park  
<span class="venue">**NeurIPS 2024**</span> <span class="venue">**ICLR 2024 GenAI4DM Workshop**</span>

- **[C3] An Offline Meta Black-box Optimization Framework for Adaptive Design of Urban Traffic Light Management Systems**  
[[paper]](https://arxiv.org/abs/2408.07327) / [[code]](https://github.com/dbsxodud-11/offline_meta_bbo)  
**Taeyoung Yun\***, Kanghoon Lee\*, Sujin Yun, Ilmyung Kim, Won-Woo Jung, Min-Cheol Kwon, Kyujin Choi, Yoohyeon Lee, Jinkyoo Park  
<span class="venue">**KDD 2024**</span>

- **[C2] Learning to Scale Logits for Temperature-conditional GFlowNets**  
[[paper]](https://arxiv.org/abs/2310.02823) / [[code]](https://github.com/dbsxodud-11/logit-gfn)  
Minsu Kim\*, Juhwan Ko\*, **Taeyoung Yun\***, Dinghuai Zhang, Ling Pan, Woochang Kim, Jinkyoo Park, Yoshua Bengio  
<span class="venue">**ICML 2024**</span> <span class="venue">**NeurIPS 2023 AI4Science Workshop**</span>

- **[C1] Local Search GFlowNets**  
[[paper]](https://arxiv.org/abs/2310.02710) / [[code]](https://github.com/dbsxodud-11/ls_gfn)  
Minsu Kim, **Taeyoung Yun**, Emmanuel Bengio, Dinghuai Zhang, Yoshua Bengio, Sungsoo Ahn, Jinkyoo Park  
<span class="venue">**ICLR 2024**</span> <span class="venue venue--honor">Spotlight</span>

## Journal Publications

- **[J1] Offline Model-Based Optimization: Comprehensive Review**  
[[paper]](https://openreview.net/forum?id=QcSZWo1TLl) / [[code]](https://github.com/mila-iqia/Awesome-Offline-Model-Based-Optimization)  
Minsu Kim\*, Jiayao Gu\*, Ye Yuan, **Taeyoung Yun**, Zixuan Liu, Yoshua Bengio, Can Chen \\
<span class="venue">**TMLR 2026**</span> <span class="venue venue--honor">Survey Certification</span>

# 🎖 Honors and Awards
- *2025.11* Qualcomm Innovation Fellowship Korea Finalist 2025
- *2025.10* Top Reviewer in NeurIPS 2025
- *2021.12* Excellence Award on DACON NH Big Data Competition. 
- *2021.09* Dean's List (Honor for Top 2% Students). 

# 💬 Invited Talks
- *2026.05* AutoML Seminar - Posterior Inference in Generative Models for High-dimensional Black-box Optimization [\[video\]](https://automl-seminars.github.io/talks/)
