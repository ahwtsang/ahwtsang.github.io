---
layout: page
title: Arterial plaque detection from routine CT scans
---

### About the disease
Stroke and heart attack are medical emergencies that require immediate medical attention. From the American Heart Association, a stroke occurs when a blood vessel that carries oxygen and nutrients to the brain is either blocked by a clot or bursts (or ruptures). It is the fifth leading cause of death and a leading cause of disability in the United States. A heart attack occurs when the blood flow that brings oxygen to the heart muscle is severely reduced or cut off completely. This happens when coronary arteries that supply the heart muscle with blood flow become narrowed from a buildup of fat, cholesterol and other substances that together are called plaque. This slow process is known as atherosclerosis. About every 40 seconds, someone in the United States has a heart attack.*

*<https://www.heart.org>


### About the project
Elucid is an early-stage startup company developing a commercial image analysis software to non-invasively detect atherosclerotic plaque buildup in the arterial walls from routine CT angiography images. This is critical to provide clinicians the ability to accurately identify patients at risk of having a heart attack or stroke. I am in the image processing team where we focus on developing innovative solutions for the core technology in the software. We are continuously developing and improving the algorithm that accurately delineates calcified and other high risk plaques and supporting Quality Assurance and Regulatory teams to validate the algorithm against histopathology ground truth that meets or exceeds regulatory requirements. The image below shows an axial view of a contrast enhanced CT angiography image where the coronary arterial vessel lumen and wall can be identified and applying advanced image processing algorithm to detect plaque composition in the wall. In addition, we collaborate internally with another team to train deep-learning based models using the results from the plaque detection algorithm to predict fractional flow reserve (FFR) metric to assess severity of the cardiovascular disease and assist clinicians to decide whether patient requires revascularization procedure. Furthermore, our team is also responsible for developing AI-based solutions to simplify the analysis workflow in the software. We are developing a deep-learning based method to automatically extract arterial vessel tree and calcified plaque along with vessel labels to assist CT technologist to quickly analyze a case and generate results for clinicians. 

{% include image.html url="/assets/img/Elucid/elucid_ai_soft_plaque_assessment_coronary_cta.jpg" description="3D plaque analysis in arterial vessel wall" %}


### My contributions
* Provided internal capability to support running batch analysis on various datasets for algorithm development and verification
* Collaborated cross-functionally to support algorithm validation against histopathology ground truth and FDA 510(k) submission
* Collaborated to develop an AI solution based on the nnUNet architecture to automatically extract coronary arterial vessel tree and calcified plaques, including tools to process data for model training and computing metrics to evaluate model performance
* Supported to demonstrate a working prototype to key internal stakeholders and contributed to integrate prototype into the software product
* Explored deploy strategy using Triton Inference Server ensemble pipeline that aims to significantly reduce inference time and on the overall analysis time of a case 
