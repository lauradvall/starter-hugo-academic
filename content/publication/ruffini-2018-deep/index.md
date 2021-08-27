---
title: Deep Learning With EEG Spectrograms in Rapid Eye Movement Behavior Disorder
subtitle: ""
publication_types:
  - "2"
authors:
  - Giulio Ruffini
  - David Ibañez
  - Marta Castellano
  - Laura Dubreuil-Vall
  - Aureli Soria-Frisch
  - Ron Postuma
  - Jean-François Gagnon
  - Jacques Montplaisir
doi: 10.3389/fneur.2019.00806
publication: "*Frontiers in Neurology*"
abstract: REM Behavior Disorder (RBD) is now recognized as the prodromal stage
  of α synucleinopathies such as Parkinson's disease (PD). In this paper, we
  describe deep learning models for diagnosis/prognosis derived from a few
  minutes of eyes-closed resting electroencephalography data (EEG) collected at
  baseline from idiopathic RBD patients (n = 121) and healthy controls (HC, n =
  91). A few years after the EEG acquisition (4±2 years), a subset of the RBD
  patients were eventually diagnosed with either PD (n = 14) or Dementia with
  Lewy bodies (DLB, n = 13), while the rest remained idiopathic RBD. We describe
  first a simple deep convolutional neural network (DCNN) with a five-layer
  architecture combining filtering and pooling, which we train using stacked
  multi-channel EEG spectrograms from idiopathic patients and healthy controls.
  We treat the data as in audio or image classification problems where deep
  networks have proven successful by exploiting invariances and compositional
  features in the data. For comparison, we study a simple deep recurrent neural
  network (RNN) model using three stacked Long Short Term Memory network (LSTM)
  cells or gated-recurrent unit (GRU) cells—with very similar results. The
  performance of these networks typically reaches 80% (±1%) classification
  accuracy in the balanced HC vs. PD-conversion classification problem. In
  particular, using data from the best single EEG channel, we obtain an area
  under the curve (AUC) of 87% (±1%)—while avoiding spectral feature selection.
  The trained classifier can also be used to generate synthetic spectrograms
  using the DeepDream algorithm to study what time-frequency features are
  relevant for classification. We find these to be bursts in the theta band
  together with a decrease of bursting in the alpha band in future RBD
  converters (i.e., converting to PD or DLB in the follow up) relative to HCs.
  From this first study, we conclude that deep networks may provide a useful
  tool for the analysis of EEG dynamics even from relatively small datasets,
  offering physiological insights and enabling the identification of clinically
  relevant biomarkers.
draft: false
featured: false
tags:
  - Machine Learning
  - Deep Learning
  - CNN
  - EEG
  - RBD
  - Parkinson
categories: []
projects:
  - eeg-based-biomarkers-for-adhd
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: featured.jpeg
url_pdf: https://www.frontiersin.org/articles/10.3389/fneur.2019.00806/pdf
summary: ""
lastmod: 2021-08-21T10:45:59-04:00
date: 2019-01-07T05:00:00.000Z
publishDate: 2021-08-21T14:46:10.024Z
---
