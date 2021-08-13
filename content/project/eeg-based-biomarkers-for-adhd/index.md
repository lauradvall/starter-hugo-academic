---
title: Deep learning for EEG-based biomarkers for ADHD
date: 2021-08-13T16:48:13.594Z
summary: ""
draft: false
featured: false
external_link: " "
links:
  - url: https://linkinghub.elsevier.com/retrieve/pii/S2451902220303487
    name: Check out the paper
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
Attention deficit hyperactivity disorder (ADHD) is a heterogeneous neurodevelopmental disorder that affects 5% of the pediatric and adult population worldwide. The diagnosis remains essentially clinical, based on history and exam, with no available biomarkers. In this paper, we describe a deep convolutional neural network (DCNN) with a four-layer architecture combining filtering and pooling, which we train using stacked multi-channel EEG time-frequency decompositions (spectrograms) of electroencephalography data (EEG), particularly of event-related potentials (ERP) from ADHD patients (n=20) and healthy controls (n=20) collected during the Flanker Task, with 2800 samples for each group. We treat the data as in audio or image classification approaches, where deep networks have proven successful by exploiting invariances and compositional features in the data. The model reaches a classification accuracy of 88% ± 1.12%, outperforming the Recurrent Neural Network and the Shallow Neural Network used for comparison, and with the key advantage, compared with other machine learning approaches, of avoiding the need for manual selection of EEG spectral or channel features. The event-related spectrograms also provide greater accuracy compared to resting state EEG spectrograms. Finally, through the use of feature visualization techniques such as *DeepDream*, we show that the main features exciting the DCNN nodes are a decreased power in the alpha band and an increased power in the delta-theta band around 100 ms for ADHD patients compared to healthy controls, suggestive of attentional and inhibition deficits, which have been previously suggested as pathophyisiological signatures of ADHD. While confirmation with larger clinical samples is necessary, these results suggest that deep networks may provide a useful tool for the analysis of EEG dynamics even from relatively small datasets, highlighting the potential of this methodology to develop central nervous system biomarkers of practical clinical utility.