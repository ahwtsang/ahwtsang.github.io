---
layout: page
title: MRI real-world evidence generation in MS
---

<p align="left">
<img src="/assets/img/MSPATHS/biogenlogo.jpeg" alt="biogen" style="width:50%; height50%;">
</p>

### About the disease
Multiple sclerosis is an autoimmune disease of the central nervous system where the myelin of nerve fibers is damaged resulting in distinct areas of scar tissues. It is the most common disabling neurological disease of young adults with symptom onset generally occurring between 20 to 40 years of age.*

*https://www.ninds.nih.gov/health-information/disorders/multiple-sclerosis

### About the project
MRI plays a critical role in the diagnosis and monitoring of MS disease course as it can visualize lesions using clinically available pulse sequences. However, the heterogeneity of MS in symptoms and response to treatment pose a challenge to clinical management at the individual patient level. Routine clinical assessment is somewhat subjective, where multiple tests and review of patient’s medical history are typically used to confirm a diagnosis of the disease.

In 2015, Biogen initiated a real-world evidence generation program to improve personalized medicine in MS with the objective to better characterize the value of treatment and patient outcomes. This is achieved through the collection of clinical data from patients in their routine visits and using digital health technology to harness real-world data to inform decision making in MS clinical practice.* The program named MS PATHS, which stands for Multiple Sclerosis Partners Advancing Technology Health Solutions, involves partnership with 10 healthcare institutions, IT vendor, imaging vendor (Siemens Healthineers)** to standardize clinical assessments and bring the clinical data into a centralized database to enable research that can elucidate the disease and introduce quantitative measures into routine practice. This collective approach has been termed the Learning Health System (LHS). This program also involved collaboration between Biogen and Siemens Healthineers to codevelop and integrate an image analysis tool named MSPie in routine radiology workflow to introduce metrics that quantify disease progression. In 2022, the LHS has collected clinical data including MRI from 20,000 patients, where many with longitudinal scans.

*Harnessing Real-World Data to Inform Decision-Making: Multiple Sclerosis Partners Advancing Technology and Health Solutions (MS PATHS).
https://doi.org/10.3389/fneur.2020.00632

**Multiple sclerosis: Improve monitoring, inform treatment decisions.
[Siemens Communications](https://www.siemens-healthineers.com/perspectives/neuro-mri-collaborations)

{% include image.html url="/assets/img/MSPATHS/MSPATHS_network.png" description="High-level overview of real-world data generation and collection in MS PATHS" %}

### My contributions
* Collaborate with clinical operations, study coordinator at sites, lead radiologists to design and execute clinical studies and working with CROs, internal biostatisticians and medical writers for writing clinical study reports
* Work with cross-functional teams to implement data collection workflow transferring MRI clinical scans from hospital through the broker to redact PHI and ingest data into LHS in Biogen in compliant to HIPAA and GDPR
* Develop MRI data transfer monitoring and data management using MySQL database
* Perform internal check to ensure consistency between data entries and files in storage
* Data quality control to ensure MRI scans are from standardized 3D-MPRAGE and 3D-FLAIR sequences and Siemens 3T scanners. Compute metrics (MRIQC) to check image quality
* Package MRI DICOM series and post-processed results for data sharing with investigators in the network to enable RWE research projects in MS
* Develop brain segmentation algorithm on 3D-FLAIR images and co-develop image analysis tool (MSPie) with research team at Siemens Healthineers to derive novel brain parenchymal fraction (BPF) metric and assist to improve accuracy of AI approach to automatically detect new or enlarged white matter lesions
* Support partners at Siemens Healthineers to integrate prototype in routine radiology workflow at 3 healthcare institutions to translate BPF metric in clinical use and ability to visualize lesions shortly after patient scan session
* Obtain MRI data of normal subjects from internal study and supplement with external datasets to define normative percentile of BPF across the adult age
* Collaborate with internal data scientist to develop and evaluate AI approaches to reduce false positive lesions detected by prototype
* Build and maintain relationships with key opinion leaders, present updates at investigator meetings and interact with radiologists to discuss standardization of future clinical imaging protocol and future research focus