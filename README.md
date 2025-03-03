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
- [0. Definition of Fairness](#0.)
- [1. Sensitive Attribute Classifiers](#1.)
- [2. Fairness Analysis](#2.)
  - [2.1. Analyzing Fairness in Vision-Language Models (VLM)](#2.1.)
  - [2.2. Analyzing Fairness in Text-to-Image Generation](#2.2.)
- [3. Bias Mitigation Methods](#3.)
  - [3.1. Mitigating Bias in Vision-Language Models (VLM)](#3.1.)
  - [3.2. Mitigating Bias in Text-to-Image Generation](#3.2.)

<a name="0."></a>
## 0. Definition of Fairness


<a name="1."></a>
## 1. Sensitive Attribute Classifiers

| Sensitive Attribute | Venue | Paper | Code |
| -------- |  -------- |  ------- |  ------- |
| Skin Tone | ECCV 2022 | [TRUST: Towards Racially Unbiased Skin Tone Estimation via Scene Disambiguation](https://arxiv.org/abs/2205.03962) | [![Code](https://img.shields.io/github/stars/HavenFeng/TRUST.svg?style=social&label=Official)](https://github.com/HavenFeng/TRUST) | 
| Skin Color | ICCV 2023 | [Beyond Skin Tone: A Multidimensional Measure of Apparent Skin Color](https://arxiv.org/abs/2309.05148) | [![Code](https://img.shields.io/github/stars/SonyResearch/apparent_skincolor.svg?style=social&label=Official)](https://github.com/SonyResearch/apparent_skincolor) |


<a name="2."></a>
## 2. Fairness Analysis

<a name="2.1."></a>
### 2.1. Measuring Fairness in Vision-Language Models (VLM)

<a name="2.2."></a>
### 2.2. Measuring Fairness in Text-to-Image Generation

The general approach to measure fairness of a text-to-image model: 
1. Generate a number of images using neutral text prompts;
2. Use [CLIP classifier](https://github.com/openai/CLIP) or pre-trained sensitive attribute classifiers (listed in [Sec.1](#1.)) to classify sesitive attributes of the generated images;
3. Use **statistical measures** to calculate fairness.

#### Statistical Measures

| Measures | Paper | Note |
| -------- |  -------- |  ------- |
| Distribution Discrepancy $\mathcal{D}_{KL}$ | [ITI-GEN: Inclusive Text-to-Image Generation](https://openaccess.thecvf.com/content/ICCV2023/html/Zhang_ITI-GEN_Inclusive_Text-to-Image_Generation_ICCV_2023_paper.html) | KL Divergence of ideal and real sensitive attribute distribution |


<a name="3."></a>
## 3. Bias Mitigation Methods

<a name="3.1."></a>
### 3.1. Mitigating Bias in Vision-Language Models (VLM)

<a name="3.2."></a>
### 3.2. Mitigating Bias in Text-to-Image Generation

+ [ICCV 2023, Oral] [ITI-GEN: Inclusive Text-to-Image Generation](https://openaccess.thecvf.com/content/ICCV2023/html/Zhang_ITI-GEN_Inclusive_Text-to-Image_Generation_ICCV_2023_paper.html) [![Website](https://img.shields.io/badge/Website-9cf)](https://czhang0528.github.io/iti-gen) [![Code](https://img.shields.io/github/stars/humansensinglab/ITI-GEN.svg?style=social&label=Official)](https://github.com/humansensinglab/ITI-GEN)

