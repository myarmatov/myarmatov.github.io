---
layout: archive
title:
permalink: /projectsandskills/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Skills
======
* **Programming Languages:**
   Python, C++, Java, MATLAB
  
* **Frameworks:**
  PyTorch, TensorFlow, Keras, OpenCV, Scikit-Learn, spaCy, Raspberry Pi, OrCAD etc.
  
* **Languages:**
   English (Fluent), Turkish (Fluent), Korean (Basic), Russian (Basic), Turkmen (Native)
  
  
Ongoing projects
======
* **Fault detection for autonomous vehicles**
* **Hand Pose Estimation**

Finished projects
======

* **Airport Service Robots:**
  * We built service robots that autonomously collect and distribute passenger trolleys in busy airports. I developed deep learning based computer vision algorithms that would enable robots to detect, classify, and track idle trolleys using state-of-the-art object detection architectures such as RCNN, Faster-RCNN, and YOLOv3. We collected a huge amount of data not only in the airport but also in various different places such as car parks.
* **Object Recognition/Classification using BOW, and Deep Learning with CNN:** 
  * I implemented several state-of-the-art methods of computer vision for object recognition and classification problem using 20 Objects and CIFAR10 datasets.
  
    The first one was a Bag-of-visual-words model. For the feature extraction part, I used OpenCV's ORB method which is a fusion of FAST key-point detector and BRIEF descriptor with many modications. Then for learning a visual dictionary, I used the K-Means clustering algorithm. To represent images by frequencies of visual words and to nd the nearest
codeword for images, I used the k-Nearest Neighbors algorithm and applied level-0 and level-1 extension of histograms. Then I trained an SVM model with Intersection Kernel by using the descriptor we have created and target labels.

    The second one was a Deep Learning with CNN method. First, I created a class using PyTorch with Convolutional Neural Network layers (CNN), Fully Connected layers (FC), and an application of the Forward propagation. After loading the dataset and converting it to Tensors, I trained my model by applying forward/backward propagation with the CrossEntropyLoss loss function and Adam optimizer to minimize the error.

* **Graduate Admissions Prediction:** 
  * I developed a model that estimates the students' chance of getting admitted to US universities based on their academic background. I used Machine Learning algorithms such as Linear Regression, SVM, and Random Forest for the prediction. The results were not so good because the dataset (from "The Grad Cafe") I used has so many outliers. After doing some data pre-processing, the best accuracy was achieved with SVM.
* **Math Word Problem Solver:**
  * We made an application that can help primary school students to solve math word problems. The application solves the given problem and shows its solution. Various Natural Language Processing (NLP) techniques were used for the application. We used a source code of the software package associated with the paper "Named Entity Recognition without Labelled Data: a Weak Supervision Approach". Named Entity Recognition (NER) was used to locate and classify named entities mentioned in unstructured text into predefined categories such as person names, organizations, locations, etc. Then, Hidden Markov Models (HMM) was used to learn the best labels among labels annotated with various NER models. For our specific application, we did several tasks such as sentence simplification, information extraction, creating equations based on the extracted information, and solving the obtained equation. We have done most of our tasks using a powerful NLP library "spaCy".
* **eDoctor:** 
  * Misdiagnosing diseases that have similar symptoms outside of a medical setting can be fatal. Therefore, I proposed a user-friendly mobile application as a solution to this problem. The application utilizes classification algorithms of machine learning such as k-Nearest Neighbors, Decision Tree, and SVM to diagnose diseases based on users' answers to guiding questions.
* **Smart Camera:**
  * I conducted research on video processing and feature extraction methods to make surveillance cameras smart enough to detect car accidents and immediately summon an ambulance to save lives.
  
  

  
