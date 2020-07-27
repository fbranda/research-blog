---
# Course title, summary, and position.
linktitle: Analisi di Immagini e Video (Computer Vision)
summary: Il corso mira a fornire solide basi in merito all’analisi di immagini e video e fornire una conoscenza delle principali tecniche di deep learning per il riconoscimento di oggetti e l’individuazione di sequenze rilevanti in un video. 


weight: 1

# Page metadata.
title: Panoramica
date: "2020-02-26T00:00:00Z"
lastmod: "2020-04-18T00:00:00Z"
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
menu: 
  ds4iot:
    name: "Course Overview"
    weight: 1
  
---

## Annunci

- **[27/07/2020]** created.


## Breve descrizione del corso


Il corso è finalizzato ad acquisire e sperimentare le tecniche di base per l’analisi di immagini e video. Verranno illustrati i concetti fondamentali per l’analisi delle immagini e verranno illustrate le principali tecniche di object detection, object tracking e action detection. Durante il corso saranno presentati modelli di reti neurali CNN e RNN, tecniche di transfer learning, Residual and Attention network ed una introduzione ai modelli generativi e alle Adversarial networks. Gli esempi applicativi faranno uso del linguaggio Python e dei framework di Deep Learning Pytorch/Tensorflow.

Competenze specifiche:

* comprensione dei concetti legati all’image e al video processing
* conoscenza degli aspetti caratterizzanti di machine learning e deep learning
* comprensione delle principali tecniche per l’analisi di immagini e video
* abilità di utilizzare algoritmi di image analysis per la risoluzione di problemi specifici



## Docenti
- Giuseppe Manco. Ricevimento: mercoledì’ 14:30-16:30. 
- Francesco Pisani. Rivevimento lunedì 15-17.

## Programma

1.	**Introduzione alla computer vision**
	-	Concetti fondamentali su Image processing e analysis: Image Basics, Python per Image Processing, Manipolazione di immagini.
	-	Trasformazioni: Normalizzazione, filtri, Edge detection, morfologia, thresholding e segmentazione.
2.	**Classificazione di immagini e video**
	-	Introduzione alla classificazione: applicazioni; approcci classici; scikit-Learn per la classificazione; limitazioni.
	-	Deep Learning: Review su Neural Networks per l'analisi di immagini e video. Convolutional Neural Networks. Reti ricorrenti. R-CNN. Gestione dell'overfitting.
	-	Concetti avanzati. Principali architetture di rete e loro caratteristiche: VGG, AlexNet, Inception and Residual Networks, Attention Networks. Transfer Learning.
3.	**Concetti avanzati**
	-	Object Detection: Sliding windows, boundary boxes e anchors. Region Proposal Networks. Yolo e Darknet. Applicazioni.
	-	Object tracking e action recognition. Optical flow; Single/multiple objects tracking; Action classification and localization.
	-	Image segmentation e synthesis. UNet. Neural style transfer.
	-	Modelli Generativi: Probabilistic Modeling, Autoencoders. Generative Adversarial Networks. Applicazioni: Colorization, Reconstruction, Super-Resolution, Synthesis, Text-to-image.
	-	Adversarial Machine Learning. Principali attacchi e contromisure. Adversarial-free deep networks.



## Materiale didattico
- Lucidi delle lezioni
- Notebooks e lucidi delle esercitazioni
- Libri di consultazione:
	- E.R. Davies, Computer Vision: Principles, Algorithms, Applications, Learning. Fifth edition. Elsevier/Academic Press, 2018 **[Davies18]**
	- Jan Erik Solem, Programming Computer Vision with Python. O'Reilly Media, 2012. **[Solem12]**
	- Mohamed Elgendy, [Deep Learning for Vision Systems](https://www.manning.com/books/deep-learning-for-vision-systems). Manning, 2020. **[Elg20]**
	- Rafael C. Gonzalez, Richard E. Woods, Digital image processing. 4th edition. Pearson, 2018. **[Gon18]**
	- Richard Szeliski, Computer Vision: Algorithms and Applications. Springer, 2011. **[Sze11]**
	- Jason M.Kinser, Image operators: image processing in Python. CRC Press, 2019. **[Kin19]**

## Sillabo delle lezioni


| Lezione | Argomenti                                            | Materiale didattico | Data       |
| ------- | ---------------------------------------------------- | ------------------- | ---------- |
| 1       | Introduzione al corso |[Slides]({{< relref "../ds4iot/lecture1.md" >}}) |27/07/2020 |
