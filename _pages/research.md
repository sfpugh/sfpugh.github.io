---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research focuses on developing trustworthy and explainable multimodal artificial intelligence (AI) systems for healthcare. I apply state-of-the-art AI technologies to provide clinical decision support and optimize clinical workflows. Below you will find a sample of the projects I work(ed) on.

## WATCH-SS (Warning Assessment and Alerting Tool for Cognitive Health from Spontaneous Speech)

![WATCH-SS info graphic.](/files/watch-graphic.png)

Over 50% of people living with Alzheimer's disease (AD) are <span style="color:red">**undiagnosed**</span>. Many people who have emerging concerns about their cognitive health first consult their primary care physician (PCP), but very few actually receive a diagnosis for cognitive decline due to factors like PCPs' time constraints, competing priorities, lack of expertise or comfort with AD diagnosis. **Thus we are developing WATCH-SS, a screening tool for primary care which passively analyzes a patient's speech during a clinic visit to assess risk of cognitive impairment (CI).** To do this, WATCH-SS runs a set of detectors for five acoustic and linguistic signs of CI and these detections are fed through a predictive model to predict CI. The detectors are a mixture of natural language processing (NLP) -based algorithms and large-language models (LLMs). Our evaluation shows that WATCH-SS achieves strong predictive performance (AUC 0.95 for test and 0.80 for train on DementiaBank data), and its design allows us to effectively explain and verify our risk prediction.

[[Paper]](https://doi.org/10.1142/9789819824755_0024) [[Poster]](https://doi.org/10.7490/f1000research.1120305.1) [[Code]](https://github.com/kbjohnson-penn/WATCH-SS)

---

## Evaluating Robustness of Medical AI Systems with Naturally Adversarial Datasets 

![Robustness evaluation info graphic.](/files/robustness-graphic.png)

To ensure robustness of medical AI systems, we must move beyond unrealistic synthetic perturbations and evaluate against **naturally occurring adversarial examples that reflect true healthcare challenges and effectively deceive models**. To address this, we developed a weakly-supervised framework that curates **naturally adversarial datasets for evaluating robustness** using existing real-world unlabeled data. Our method first generates probabilistic labels via weak supervision, then orders the examples based on label uncertainty to generate a sequence of datasets that are progressively more adversarial. We can then validate model robustness by confirming a statistically significant decrease in agreement between model predictions and weak labels across the datasets. This trend reflects the expectation that a robust model maintains accuracy on both expected and unexpected inputs, effectively diverging from weak labels as they become unreliable on the unexpected inputs.

[[Paper]](https://doi.org/10.1145/3734695) [[Code]](https://github.com/sfpugh/Naturally-Adversarial-Datasets)

---

## Evaluating Physiologic Monitoring Alarm Suppression Systems with High-Confidence Data Programming

![High confidence data programming info graphic.](/files/high-conf-data-prog-graphic.png)

[[Paper]](https://dl.acm.org/doi/pdf/10.1145/3549942) [[Code]](https://github.com/sfpugh/Evaluating-Alarm-Classifiers-with-High-Confidence-Data-Programming)

---

## Automating Weak Label Generation for Data Programming with Clinicians in the Loop

![Weak label generation info graphic.](/files/weak-label-gen-graphic.png)

[[Paper]](https://arxiv.org/pdf/2407.07982)
