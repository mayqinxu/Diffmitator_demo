---
layout: page
title: Abstract
permalink: /abstract/
---


The demand for deep learning-based audio generation has grown significantly in various multimedia and gaming domains, but its application in sound effect generation remains largely limited due to several challenges.  While previous works have increased the availability of cross-modal datasets and improved the training of universal models for different input modalities, two significant issues persist: the trade-off between model performance and training cost, and the inconsistency in timbre between reference audio and generated audio. To tackle these challenges, we propose two methods: D-HTSAT and C-Copaint. D-HTSAT achieves promising results with low training costs by decomposing the audio generation task into semantic content generation and timbre content generation sub-tasks. C-Copaint addresses the issue of inconsistent timbre by transforming the problem into a conditional inpainting task, which ensures consistent timbre through supervision during the DDIM denoising process. Upon D-HTSAT and C-Copaint, we build Diffmitator -- a model that combines the language model and the diffusion model for conditional audio generation. Experimental results demonstrate the effectiveness of Diffmitator, showcasing improved content-timbre quality and better subjective perception compared to existing methods.