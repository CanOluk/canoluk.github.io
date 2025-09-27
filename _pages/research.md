---
title: ""
permalink: /research/
layout: single_full
author_profile: false
classes: left-toc  # custom hook for CSS below
---
<div class="toc-left">
  {% include toc %}
</div>

## 1. Visual Perception

I am interested in how the human visual system extracts information about the physical world to guide action. 

My approach: Scaling principled, interpretable models to build mechanistic understanding.

### The advantages

1. Posing novel questions about mechanisms of visal processing (e.g. Oluk et al., 2023)
2. Allow us to explore the model space rigorously by thinking about the constraints and biologically plausible approbations (e.g. Oluk & Geisler, 2024)
3. Provides us a benchmark performance where we can compare the human and other models performance, especially useful for gaining insight about the performance of machine learning models that can handle much complex tasks where benchmarks are unavailable (e.g. Oluk & Geisler, 2025)
4. Applicable to broad range of problems (e.g. 3D perception, motion perception, target identification)

<figure style="max-width:720px; margin:0.75rem 0 0.25rem 0; text-align:left;">
  <img src="/images/figure.png" alt="My figure" style="display:block; width:100%; height:auto;">
</figure>

**Mechanistic understanding**: To understand the principles of visual processing, I develop and compare image-computable models that transform images into perceptual decisions. 

**Principled and interpretable models**: A principled model is optimal with respect to a well-defined objective (cost function) under explicit, well-defined task-imposed and experimenter-imposed constraints, making its assumptions and thus its strengths and weaknesses rigorously specified. An interpretable model has clearly specified computational components whose roles in achieving the overall objective are transparent.

**Scaling**: Such models are typically available only for narrowly defined, highly constrained (simple) tasks. By scaling, I mean (i) developing this class of models for relatively complex tasks that incorporate properties of natural settings, and (ii) designing models that generalize across variations of the same task. 

### Examples

#### 1. Target Identification under high levels of uncertainty
[**Oluk, C**., & Geisler, W. S. (2025)](https://jov.arvojournals.org/article.aspx?articleid=2802525). Target identification under high levels of amplitude, size, orientation and background uncertainty. Journal of Vision, 25(2), 3. [GitHub Page.](https://github.com/CanOluk/Target_Identification) 

[**Oluk, C**., & Geisler, W. S. (2023)](https://jov.arvojournals.org/article.aspx?articleid=2792955). Effects of Target-Amplitude and Background-Contrast Uncertainty Predicted by a Normalized Template-Matching Observer. Journal of Vision, 23(12), 8. [GitHub Page.](https://github.com/CanOluk/Amplitude_Contrast_Uncertainty) 

My Dissertation is available [online](https://repositories.lib.utexas.edu/handle/2152/115685).

#### 2. Perception of 3D orientation and depth of a planar surface
[**Oluk, C**., Bonnen, K., Burge, J., Cormack, L. K., & Geisler, W. S. (2022)](https://jov.arvojournals.org/article.aspx?articleid=2778771). Stereo slant discrimination of planar 3D surfaces: Frontoparallel versus planar matching. Journal of Vision, 22(5), 6-6. [GitHub Page.](https://github.com/CanOluk/Stereo-Slant-Discrimination)  

[**Oluk, C**., & Geisler, W. S. (2020).](https://jov.arvojournals.org/article.aspx?articleid=2771656) Ideal Observers for the estimation of disparity in random-pixel stereograms. Journal of Vision, 20(11), 578-578. [GitHub Page.](https://github.com/CanOluk/OptimalDisparityEstimation) 

#### 3. Perception of the global motion direction (ongoing)

#### 4. Perception direction and magnitude of the vernier presented in a motion stream (ongoing)

## 2. Beyond Visual Perception

I am also broadly interested in human behavior and its underlying neural mechanisms. My approach can be easily extended to tasks where there are non-visual mechanisms (e.g. confidence, awareness) also leading the behavior in addition to perceptual mechanisms.

### Examples

#### Confidence in perception of the global motion direction (ongoing)

#### Awareness of the perception of the vernier presented in a motion stream (ongoing)

## 3. Theory for model selection

The theoretical model space for each task is vast, and with recent advances in machine learning and computational resources it is now far easier to develop mechanistic models, which makes the practical model space large. Thus, we rely on secondary principles such as simplicity, normative criteria, and assumptions about model type to identify models that are more likely to be human like. I am interested in formalizing these model selection and development procedures, emphasizing generalizability and scalability as prerequisites. 

### Examples

#### Efficiency as a model selection criteria (ongoing)
