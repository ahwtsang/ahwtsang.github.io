---
layout: page
title: Sodium MRI of the Human Brain
---

![ualberta]("/assets/img/SodiumMRI/UofA_logo.png" "ualberta")

### About the project

I learned about MRI during my PhD program in the department of [Biomedical Engineering](https://www.mri.ualberta.ca/) at the University of Alberta. My thesis project is about developing non-conventional MRI techniques to image sodium in the human brain.

Hydrogen (1H) is the most abundant naturally occurring isotope in human, which is present in both water and fat molecules. It is, by far, the most sensitive element in vivo that can be detected by nuclear magnetic resonance (NMR). Imaging of 1H in human (proton MRI) constitutes most of the research and the basis of clinical MRI sequences at present.

However, there’s interest to image sodium non-invasively as the distribution of sodium and potassium ions are tightly regulated across cell membrane to generate a resting membrane potential. Under pathological conditions such as cerebral ischemia, the homeostatic condition is disrupted due to the failure of the active transport mechanism across cell membrane.

Sodium (23Na) is the second most NMR sensitive nucleus to be observed in biological environment after 1H. Even though sodium is the second most biological sensitive element detectable using NMR, imaging of this element is challenging. This is due to its smaller gyromagnetic ratio and much lower concentration in vivo compared to hydrogen (protons). MRI of sodium yields inferior image quality and requires longer scan time than proton MRI as seen in the images below. Therefore, sodium imaging has not been applied clinically.

In this project, I optimized a multiple quantum filtered MRI pulse sequence to image sodium in the human brain at 4.7-Tesla (Varian whole-body MRI scanner) to maximize signal-to-noise ratio (SNR) under the constraint of specific absorption rate (SAR) within a clinically reasonable scan time. Specific sequence parameters were optimized by scanning a custom-built phantom and healthy volunteers. I published the first double-quantum filtered sodium image of the human brain and demonstrated potential utility of sodium imaging in acute stroke patients.

{% include image.html url="/assets/img/SodiumMRI/Subject 1 - TSC_cropped.png" description="Brain tissue sodium MRI of a healthy volunteer" %}

{% include image.html url="/assets/img/SodiumMRI/Subject 1 - TQ90deg.png" description="Brain triple-quantum sodium MRI of the same volunteer" %}