# Awesome Fair Generative AI [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
This repository contains a list of works on fairness in generative AI, including fairness measurements and bias mitigation methods.

![overall_structure](./figures/image.webp)

## 🚀 Get Involved

This repository is dedicated to highlighting the efforts of researchers from all over the world aimed at enhancing fairness in the realm of generative AI. Recognizing the critical importance of fostering a fairer world, I hope this initiative encourages greater awareness and appreciation for fairness and inclusivity in our daily lives.​

As the sole maintainer, I acknowledge that the listings here may be incomplete or reflect certain biases. To enrich and diversify this compilation, your contributions are welcome. You can:​

- raise an [Issue](https://github.com/itsmag11/Awesome-Fair-Generative-AI/issues) to suggest improvements or highlight omissions
- [Pull](https://github.com/itsmag11/Awesome-Fair-Generative-AI/pulls) a request with additional resources or corrections
- Contact [Xinyu Hou](https://itsmag11.github.io/) at itsmag11@gmail.com

Together, we can build a more comprehensive and representative resource that reflects the collective commitment to fairness in AI.

## 📖 Table of Contents
- [Awesome Fair Generative AI ](#awesome-fair-generative-ai-)
  - [🚀 Get Involved](#-get-involved)
  - [📖 Table of Contents](#-table-of-contents)
  - [1. Sensitive Attribute Classifiers](#1-sensitive-attribute-classifiers)
  - [2. Bias Analysis](#2-bias-analysis)
  - [3. Bias Mitigation Methods](#3-bias-mitigation-methods)
    - [3.1. Mitigating Bias in Text-to-Image Generation](#31-mitigating-bias-in-text-to-image-generation)
  - [4. Evaluation Metrics](#4-evaluation-metrics)
    - [4.1. Measuring Fairness in Text-to-Image Generation](#41-measuring-fairness-in-text-to-image-generation)
      - [Statistical Measures](#statistical-measures)

<!-- <a name="0."></a>
## 0. Definition of Fairness

> **TL;DR:** We believe a fair AI system should ensure **equal representation** of societal groups, despite divergence from current demographic distributions.

Fairness AI pertains to the principle that AI systems should operate impartially and equitably, ensuring that their outcomes do not favor or disadvantage any particular group. This concept is crucial in preventing the perpetuation or amplification of existing societal biases through AI technologies.

In the context of AI-generated content, such as producing a "photo of a doctor", the representation of different demographics becomes a focal point for assessing fairness. Historically, certain professions have been predominantly occupied by specific demographic groups—often males in the case of doctors. If an AI system generates images reflecting this historical imbalance, it risks reinforcing outdated stereotypes and perpetuating existing biases.

Advocating for equal representation in AI-generated content, even if it diverges from current demographic distributions, serves several vital purposes:

1. **Challenging Stereotypes**: Presenting a balanced mix of male and female doctors in AI-generated images can help dismantle traditional gender roles, encouraging broader societal acceptance of women in medicine and inspiring future generations.

2. **Promoting Inclusivity**: Ensuring diverse representation in AI outputs fosters a sense of belonging among underrepresented groups, reinforcing the notion that these professions are accessible to all, regardless of gender or background.

3. **Mitigating Bias Reinforcement**: By consciously balancing representations, AI systems can avoid perpetuating existing biases, contributing to a more equitable portrayal of various professions.

Research underscores the importance of addressing biases in AI. For instance, studies have shown that AI systems trained on biased data can produce discriminatory outcomes, affecting marginalized groups adversely. Moreover, AI-generated images have been found to over-represent certain demographics, leading to skewed perceptions.

Therefore, striving for equal representation in AI-generated imagery is not merely about reflecting current realities but about shaping a more inclusive and fair future. This approach aligns with ethical AI development practices that seek to prevent the reinforcement of societal biases and promote diversity across all platforms. -->

<a name="1."></a>
## 1. Sensitive Attribute Classifiers

| Sensitive Attribute | Venue | Paper | Code |
| -------- |  -------- |  ------- |  ------- |
| Skin Tone | ECCV 2022 | [TRUST: Towards Racially Unbiased Skin Tone Estimation via Scene Disambiguation](https://arxiv.org/abs/2205.03962) *Note: FAIR dataset introduced* | [![Code](https://img.shields.io/github/stars/HavenFeng/TRUST.svg?style=social&label=Official)](https://github.com/HavenFeng/TRUST) | 
| Skin Color | ICCV 2023 | [Beyond Skin Tone: A Multidimensional Measure of Apparent Skin Color](https://arxiv.org/abs/2309.05148) | [![Code](https://img.shields.io/github/stars/SonyResearch/apparent_skincolor.svg?style=social&label=Official)](https://github.com/SonyResearch/apparent_skincolor) |


<a name="2."></a>
## 2. Bias Analysis

+ [NeurIPS 2018] [Bias and Generalization in Deep Generative Models: An Empirical Study](https://papers.nips.cc/paper_files/paper/2018/hash/5317b6799188715d5e00a638a4278901-Abstract.html)

+ [VAST 2019] [FairVis: Visual Analytics for Discovering Intersectional Bias in Machine Learning](https://arxiv.org/abs/1904.05419)
  
+ [ICCV 2023] [DALL-Eval: Probing the Reasoning Skills and Social Biases of Text-to-Image Generation Models](https://arxiv.org/abs/2202.04053)
  [![Code](https://img.shields.io/github/stars/j-min/DallEval.svg?style=social&label=Official)](https://github.com/j-min/DallEval)

+ [NeurIPS 2023, Spotlight] [Stable Bias: Evaluating Societal Representations in Diffusion Models](https://arxiv.org/abs/2303.11408)

<a name="3."></a>
## 3. Bias Mitigation Methods

<a name="3.1."></a>
### 3.1. Mitigating Bias in Text-to-Image Generation

+ [NeurIPS 2022] [Generative Visual Prompt: Unifying Distributional Control of Pre-Trained Generative Models](https://arxiv.org/abs/2209.06970)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://chenwu.io/PromptGen/) 
  [![Code](https://img.shields.io/github/stars/ChenWu98/Generative-Visual-Prompt.svg?style=social&label=Official)](https://github.com/ChenWu98/Generative-Visual-Prompt)

+ [EMNLP 2022, Oral] [How well can Text-to-Image Generative Models understand Ethical Natural Language Interventions?](https://arxiv.org/abs/2210.15230)
  [![Code](https://img.shields.io/github/stars/Hritikbansal/entigen_emnlp.svg?style=social&label=Official)](https://github.com/Hritikbansal/entigen_emnlp)

+ [CVPR 2023] [Safe Latent Diffusion: Mitigating Inappropriate Degeneration in Diffusion Models](https://arxiv.org/abs/2211.05105)
  [![Code](https://img.shields.io/github/stars/ml-research/safe-latent-diffusion.svg?style=social&label=Official)](https://github.com/ml-research/safe-latent-diffusion)

+ [arXiv 2023] [Fair Diffusion: Instructing Text-to-Image Generation Models on Fairness](https://arxiv.org/abs/2302.10893)
  [![Code](https://img.shields.io/github/stars/ml-research/Fair-Diffusion.svg?style=social&label=Official)](https://github.com/ml-research/Fair-Diffusion)

+ [ICCV 2023, Oral] [ITI-GEN: Inclusive Text-to-Image Generation](https://openaccess.thecvf.com/content/ICCV2023/html/Zhang_ITI-GEN_Inclusive_Text-to-Image_Generation_ICCV_2023_paper.html) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://czhang0528.github.io/iti-gen) 
  [![Code](https://img.shields.io/github/stars/humansensinglab/ITI-GEN.svg?style=social&label=Official)](https://github.com/humansensinglab/ITI-GEN)

+ [WACV 2024] [Unified Concept Editing in Diffusion Models](https://arxiv.org/abs/2308.14761)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://unified.baulab.info/) 
  [![Code](https://img.shields.io/github/stars/rohitgandikota/unified-concept-editing.svg?style=social&label=Official)](https://github.com/rohitgandikota/unified-concept-editing)

+ [arXiv 2023] [What is a Fair Diffusion Model? Designing Generative Text-To-Image Models to Incorporate Various Worldviews](http://arxiv.org/abs/2309.09944)

+ [AAAI 2024] [Fair Sampling in Diffusion Models through Switching Mechanism](https://arxiv.org/abs/2401.03140) 
  [![Code](https://img.shields.io/github/stars/uzn36/AttributeSwitching.svg?style=social&label=Official)](https://github.com/uzn36/AttributeSwitching)

+ [arXiv 2024] [MIST: Mitigating Intersectional Bias with Disentangled Cross-Attention Editing in Text-to-Image Diffusion Models](https://arxiv.org/abs/2403.19738)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://mist-diffusion.github.io/) 

+ [arXiv 2024] [AITTI: Learning Adaptive Inclusive Token for Text-to-Image Generation](https://arxiv.org/abs/2406.12805)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://itsmag11.github.io/AITTI/) 
  [![Code](https://img.shields.io/github/stars/itsmag11/AITTI.svg?style=social&label=Official)](https://github.com/itsmag11/AITTI)

+ [NeurIPS 2024, Spotlight] [Association of Objects May Engender Stereotypes: Mitigating Association-Engendered Stereotypes in Text-to-Image Generation](https://proceedings.neurips.cc/paper_files/paper/2024/hash/5c7465e4a236b56226ca221f3d16bf2b-Abstract-Conference.html)
  
+ [NeurIPS 2024] [FairQueue: Rethinking Prompt Learning for Fair Text-to-Image Generation](https://arxiv.org/abs/2410.18615)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sutd-visual-computing-group.github.io/FairQueue/) 
  [![Code](https://img.shields.io/github/stars/Bearwithchris/FairQueue_Code.svg?style=social&label=Official)](https://github.com/Bearwithchris/FairQueue_Code)

+ [arXiv 2024] [DebiasDiff: Debiasing Text-to-image Diffusion Models with Self-discovering Latent Attribute Directions](https://arxiv.org/abs/2412.18810) 
  [![Code](https://img.shields.io/github/stars/leigest519/DebiasDiff.svg?style=social&label=Official)](https://github.com/leigest519/DebiasDiff)

<!-- <a name="3.2."></a>
### 3.2. Mitigating Bias in Vision-Language Models (VLM) -->

## 4. Evaluation Metrics

<a name="4.1."></a>
### 4.1. Measuring Fairness in Text-to-Image Generation

The general approach to measure fairness of a text-to-image model involve: 
1. Generate a number of images using neutral text prompts;
2. Use [CLIP classifier](https://github.com/openai/CLIP) or pre-trained sensitive attribute classifiers (listed in [Sec.1](#1.)) to classify sesitive attributes of the generated images;
3. Use **statistical measures** to calculate fairness.

#### Statistical Measures

| Measures | Paper | Note |
| -------- |  -------- |  ------- |
| Distribution Discrepancy $\mathcal{D}_{KL}$ | [ITI-GEN: Inclusive Text-to-Image Generation](https://openaccess.thecvf.com/content/ICCV2023/html/Zhang_ITI-GEN_Inclusive_Text-to-Image_Generation_ICCV_2023_paper.html) | KL Divergence of ideal and real sensitive attribute distribution |

<!-- <a name="4.2."></a>
### 4.2. Measuring Fairness in Vision-Language Models (VLM) -->