---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

Research
===

**Natural language processing:**
1. Integrate pre-trained language models for neural machine translation (**Thesis**): explored different strategies of incorporating pre-trained language models (BERT, GPT-2) to the transformer-based seq2seq architecture. Evaluated integration strategies on different translation datasets {German, Chinese, Turkish, Romanian, Korean} $\leftrightarrow$ English, and obtained great BLEU improvements comparing to the transformer baseline. Thesis advisor: Prof. [Michael Collins](http://www.cs.columbia.edu/~mcollins/).
2. Detect urgency status of crisis Tweets for low resource languages with zero-shot transfer approach: released a dataset of tweets with annotations of urgency status, established various classifiers that consist of different architectures and embeddings (monolingual and cross-lingual) built using different methods (VecMap, [Proc-B](https://www.aclweb.org/anthology/P19-1070/), [LASER](https://research.fb.com/downloads/laser-language-agnostic-sentence-representations/), BERT). We employed self-training and [MultiFit](https://arxiv.org/abs/1909.04761) to augment the dataset with synthetic annotations, and investigated different strategies to ensemble the classifiers. This project is advised by Prof. [Kathleen McKeown](http://www.cs.columbia.edu/~kathy/). **[Work in submission]**

**Healthcare and biotechnology:**
3. [Assess the ability of CNNs to detect glaucoma from OCT probability maps](https://iovs.arvojournals.org/article.aspx?articleid=2741905&resultClick=1): evaluated various CNN architectures, with or without pre-training on non-medical images, at distinguishing between healthy controls and glaucoma suspects using retinal nerve fiber layer (RNFL) probability maps from wide-field OCT imaging. Work accepted to The Association for Research in Vision and Ophthalmology (ARVO) Annual Meeting, 2019.
4. [High quality protein Q8 secondary structure prediction by diverse neural network architectures](https://arxiv.org/abs/1811.07143): predicted protein Q8 secondary structure using diverse neural network architectures and achieved state-of-the-art performance on existing protein dataset. Work accepted to NeurIPS Workshop on Machine Learning for Molecules and Materials, 2018.

5. [Accurate protein structure prediction by embeddings and deep learning representations](https://arxiv.org/abs/1911.05531): predicted protein 3D structure by first predicting backbone atom distance matrices and torsion angles, from which we recovered 3D coordinates of backbone atoms by optimization. Work accepted to Machine Learning in Computational Biology, 2019.

**Adversarial ML, Robustness and interpretability of ML systems:**

6. Distinguish neural network architectures using adversarial examples of diverse CNN models: exploring adversarial attacks and defenses for image classifiers of different neural network architectures, and investigating strategies of distinguishing architectures using adversarial examples. This project is advised by Prof. [Changxi Zheng](http://www.cs.columbia.edu/~cxz/). **[Work in progress]**
