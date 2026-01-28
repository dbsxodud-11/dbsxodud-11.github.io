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

I am a PhD student at <a href="http://silab.kaist.ac.kr/" style="color: #7289da; text-decoration: none;">System Intelligence</a> lab in KAIST. I am fortunate to be advised by Professor <a href="https://scholar.google.com/citations?user=sH2a0nkAAAAJ&hl=en" style="color: #7289da; text-decoration: none;">Jinkyoo Park</a>. Here is my <a href="https://dbsxodud-11.github.io/assets/cv.pdf" class="link-in-list" style="color: #7289da; text-decoration: none;"> cv</a>.

My research interest lies in controllable generative modeling with large models (e.g., LLMs, Diffusion/Flow-based models) via exploring their latent spaces. Especially, I'm interested in building an amortized sampler that can extract crucial latents for generating desired samples. To accomplish this, my research focuses on the amortizing inference of generative models with off-policy RL approaches.

I'm also interested in various decision making problems such as Multi-turn/Multi-agent RL. I've also participated in several transportation-related projects based on high-dimensional black-box optimization methods. 


# 🔥 News
- 2026.01: &nbsp;🎉🎉 3 papers accepted in 2026 (1 WSDM, 1 TMLR, 1 ICLR) 
- 2025.06: &nbsp;🎉🎉 I started internship at Mila, Hosted by <a href="https://yoshuabengio.org/" style="color: #7289da; text-decoration: none;">Yoshua Bengio</a>
- 2025.05: &nbsp;🎉🎉 5 papers accepted in 2025 (1 ICLR, 1 CVPR, 2 ICML, 1 KDD)
- 2024.12: &nbsp;🎉🎉 5 papers accepted in 2024 (1 ICLR, 1 ICML, 1 KDD, 2 NeurIPS)
- 2024.09: &nbsp;🎉🎉 I started remote internship at HKUST, Hosted by <a href="https://ling-pan.github.io/" style="color: #7289da; text-decoration: none;">Ling Pan</a>

<!-- - *2024.05*: &nbsp;🎉🎉 One paper accepted to KDD 2024 -->
<!-- - *2024.05*: &nbsp;🎉🎉 One paper accepted to ICML 2024 -->
<!-- - *2024.03*: &nbsp;🎉🎉 One paper accepted to ICLR GenAI4DM Workshop 2024 (Spotlight) -->
<!-- - *2024.01*: &nbsp;🎉🎉 One paper accepted to ICLR 2024 (Spotlight) -->
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2024.05 - current*, Ph.D in Industrial and Systems Engineering, KAIST (Korea Advanced Institute of Science and Technology)
- *2022.09 - 2024.02*, M.S in Graduate School of AI, KAIST
- *2018.03 - 2022.08*, B.S in Industrial and Systems Engineering & Computer Science, KAIST

# 💻 Internships
<!-- - *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
- *2025.06 - 2025.08*, Internship at Mila, hosted by <a href="https://yoshuabengio.org/" style="color: #7289da; text-decoration: none;">Yoshua Bengio</a>
- *2024.09 - 2025.03*, Remote Internship at HKUST (Hong Kong University of Science and Technology), hosted by <a href="https://ling-pan.github.io/" style="color: #7289da; text-decoration: none;">Ling Pan</a>
- *2021.03 - 2021.08*, Internship at Kakao Recommendation Team


# 📝 Publications 
(\*: Equal Contribution) 

## Preprints

- **[P3] Improving Sampling Distribution of Off-policy Training in Generative Flow Networks**  
[[paper]]() / [[code]]()  
**Taeyoung Yun**, Sujin Yun, Jinkyoo Park, Ling Pan  
<span style="color:darkorchid">**Arxiv 2025**</span> 

- **[P2] Active Attacks: Red-teaming LLMs via Adaptive Environments**  
[[paper]](https://www.arxiv.org/abs/2509.21947) / [[code]](https://github.com/dbsxodud-11/active_attacks)  
**Taeyoung Yun**, Pierre-Luc St-Charles, Jinkyoo Park, Yoshua Bengio, Minsu Kim  
<span style="color:darkorchid">**Arxiv 2025**</span>

- **[P1] Posterior Inference in Latent Space for Scalable Constrained Black-box Optimization**  
[[paper]](https://arxiv.org/abs/2507.00480) / [[code]](https://github.com/umkiyoung/CiBO)  
Kiyoung Om\*, Kyuil Sim\*, **Taeyoung Yun\***, Hyeongyu Kang, Jinkyoo Park  
<span style="color:darkorchid">**Arxiv 2025**</span>  
<span style="color:darkorchid">**NeurIPS 2025 SPIGM Workshop (Oral)**</span>

## Conference Publications

- **[C12] Diffusion Alignment as Variational Expectation-Maximization**  
[[paper]](https://arxiv.org/abs/2510.00502) / [[code]](https://github.com/Jaewoopudding/dav)  
Jaewoo Lee, Minsu Kim, Sanghyeok Choi, Inhyuck Song, Sujin Yun, Hyeongyu Kang, Woocheol Shin, **Taeyoung Yun**, Kiyoung Om, Jinkyoo Park \\
<span style="color:darkorchid">**ICLR 2026**</span> 

- **[C11] Urban Traffic Network Layout Optimization with Guided Discrete Diffusion Models** \\
[[paper]]() / [[code]]()  
**Taeyoung Yun**, Inhyuck Song, Woocheol Shin, Yujin Shin, Sungpil Woo, Sunhwan Lim, Jinkyoo Park  
<span style="color:darkorchid">**WSDM 2026**</span>

- **[C10] Wind Farm Layout Optimization with Diffusion Models**  
[[paper]](https://dl.acm.org/doi/10.1145/3711896.3737181) / [[code]](https://github.com/dbsxodud-11/layopt)  
Yujin Shin\*, **Taeyoung Yun\***, Sujin Yun, Sungpil Woo, Sunhwan Lim, Jinkyoo Park  
<span style="color:darkorchid">**KDD 2025**</span>

- **[C9] Posterior Inference with Diffusion Models for High-dimensional Black-box Optimization**  
[[paper]](https://arxiv.org/abs/2502.16824) / [[code]](https://github.com/umkiyoung/DiBO)  
**Taeyoung Yun\***, Kiyoung Om\*, Jaewoo Lee, Sujin Yun, Jinkyoo Park  
<span style="color:darkorchid">**ICML 2025**</span> \\
<span style="color:darkorchid">**ICLR 2025 FPI Workshop**</span>

- **[C8] Improved Off-policy Reinforcement Learning in Biological Sequence Design**  
[[paper]](https://arxiv.org/abs/2410.04461) / [[code]](https://github.com/hyeonahkimm/delta_cs)  
Hyeonah Kim, Minsu Kim, **Taeyoung Yun**, Sanghyeok Choi, Emmanuel Bengio, Alex Hernández-García, Jinkyoo Park  
<span style="color:darkorchid">**ICML 2025**</span>  
<span style="color:darkorchid">**NeurIPS 2024 AIDrugX Workshop**</span>

- **[C7] Learning to Sample Effective and Diverse Prompts for Text-to-Image Generation**  
[[paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Yun_Learning_to_Sample_Effective_and_Diverse_Prompts_for_Text-to-Image_Generation_CVPR_2025_paper.html) / [[code]](https://github.com/dbsxodud-11/PAG)  
**Taeyoung Yun**, Dinghuai Zhang, Jinkyoo Park, Ling Pan  
<span style="color:darkorchid">**CVPR 2025**</span> \\
<span style="color:darkorchid">**Qualcomm Innovation Fellowship Korea Finalist**</span>

- **[C6] Adaptive Teachers for Amortized Samplers**  
[[paper]](https://arxiv.org/abs/2410.01432) / [[code]](https://github.com/alstn12088/adaptive-teacher)  
Minsu Kim\*, Sanghyeok Choi\*, **Taeyoung Yun**, Emmanuel Bengio, Leo Feng, Jarrid Rector-Brooks, Sungsoo Ahn, Jinkyoo Park, Nikolay Malkin, Yoshua Bengio  
<span style="color:darkorchid">**ICLR 2025**</span>

- **[C5] Guided Trajectory Generation with Diffusion Models for Offline Model-based Optimization**  
[[paper]](https://arxiv.org/abs/2407.01624) / [[code]](https://github.com/dbsxodud-11/GTG)  
**Taeyoung Yun**, Sujin Yun, Jaewoo Lee, Jinkyoo Park  
<span style="color:darkorchid">**NeurIPS 2024**</span>

- **[C4] GTA: Generative Trajectory Augmentation with Guidance for Offline Reinforcement Learning**  
[[paper]](https://arxiv.org/abs/2405.16907) / [[code]](https://github.com/Jaewoopudding/GTA)  
Jaewoo Lee\*, Sujin Yun\*, **Taeyoung Yun**, Jinkyoo Park  
<span style="color:darkorchid">**NeurIPS 2024**</span> \\
<span style="color:darkorchid">**ICLR 2024 GenAI4DM Workshop**</span>

- **[C3] An Offline Meta Black-box Optimization Framework for Adaptive Design of Urban Traffic Light Management Systems**  
[[paper]](https://arxiv.org/abs/2408.07327) / [[code]](https://github.com/dbsxodud-11/offline_meta_bbo)  
**Taeyoung Yun\***, Kanghoon Lee\*, Sujin Yun, Ilmyung Kim, Won-Woo Jung, Min-Cheol Kwon, Kyujin Choi, Yoohyeon Lee, Jinkyoo Park  
<span style="color:darkorchid">**KDD 2024**</span>

- **[C2] Learning to Scale Logits for Temperature-conditional GFlowNets**  
[[paper]](https://arxiv.org/abs/2310.02823) / [[code]](https://github.com/dbsxodud-11/logit-gfn)  
Minsu Kim\*, Juhwan Ko\*, **Taeyoung Yun\***, Dinghuai Zhang, Ling Pan, Woochang Kim, Jinkyoo Park, Yoshua Bengio  
<span style="color:darkorchid">**ICML 2024**</span> \\
<span style="color:darkorchid">**NeurIPS 2023 AI4Science Workshop**</span>

- **[C1] Local Search GFlowNets**  
[[paper]](https://arxiv.org/abs/2310.02710) / [[code]](https://github.com/dbsxodud-11/ls_gfn)  
Minsu Kim, **Taeyoung Yun**, Emmanuel Bengio, Dinghuai Zhang, Yoshua Bengio, Sungsoo Ahn, Jinkyoo Park  
<span style="color:darkorchid">**ICLR 2024 (Spotlight)**</span>

## Journal Publications

- **[J1] Offline Model-Based Optimization: Comprehensive Review**  
[[paper]](https://openreview.net/forum?id=QcSZWo1TLl) / [[code]](https://github.com/mila-iqia/Awesome-Offline-Model-Based-Optimization)  
Minsu Kim\*, Jiayao Gu\*, Ye Yuan, **Taeyoung Yun**, Zixuan Liu, Yoshua Bengio, Can Chen \\
<span style="color:darkorchid">**TMLR 2026 (Survey Certification)**</span>

# 🎖 Honors and Awards
- *2025.11* Qualcomm Innovation Fellowship Korea Finalist 2025
- *2025.10* Top Reviewer in NeurIPS 2025
- *2021.12* Excellence Award on DACON NH Big Data Competition. 
- *2021.09* Dean's List (Honor for Top 2% Students). 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->
