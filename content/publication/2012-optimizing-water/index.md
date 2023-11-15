---
title: "Transcranial Phase Correction Using Pulse-echo Ultrasound and Deep Learning: A 2D Numerical Study"
date: 2023-06-15
publishDate: 2023-06-15
authors: ["**Zixuan Tian**", "Matthew Olmstead", "Yun Jing", "Aiguo Han"]
publication_types: ["2"]
abstract: "Phase aberration caused by human skulls severely degrades the quality of transcranial ultrasound images, posing a major challenge in the practical application of transcranial ultrasound techniques in adults. Aberration can be corrected if the skull profile (i.e., thickness distribution) and speed of sound (SOS) are known. However, accurately estimating the skull profile and SOS using ultrasound with a physics-based approach is challenging due to the complexity of the interaction between ultrasound and the skull. A deep learning approach is proposed herein to estimate the skull profile and SOS using ultrasound radiofrequency (RF) signals backscattered from the skull. A numerical study was performed to test the approach's feasibility. Realistic numerical models were constructed from computed tomography (CT) scans of five ex vivo human skulls in this numerical study. Acoustic simulations were performed at various skull locations (N=3,595) to generate array-based ultrasound backscattered signals. A deep learning model was developed and trained to estimate skull thickness and SOS from RF channel data. The trained model was shown to be highly accurate. The mean absolute error was 0.15 mm (2% error) for thickness estimation and 13 m/s (0.5% error) for SOS estimation. The Pearson correlation coefficient between the estimated and ground-truth values was 0.99 for thickness and 0.95 for SOS. Aberration correction performed using deep-learning-estimated skull thickness and SOS values yielded significantly improved beam focusing (e.g., narrower beams) and transcranial imaging quality (e.g., improved spatial resolution and reduced artifacts) compared with no aberration correction. The results demonstrate the feasibility of the proposed approach for transcranial phase aberration correction."
featured: true
publication: "Techrxiv"
links:
  - icon_pack: fas
    icon: scroll
    name: Link
    url: 'https://www.techrxiv.org/articles/preprint/Transcranial_Phase_Correction_Using_Pulse-echo_Ultrasound_and_Deep_Learning_A_2D_Numerical_Study/23528310'
---