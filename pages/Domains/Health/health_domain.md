---
layout: page
title: Projects
full-width: True
footer-extra: footerlogo.html
<!-- subtitle:  -->

team:
  - name: Deep learning for Medical Images with limited labels
    img: /assets/img/hello_world.jpeg
    desc: Detection of tumour from CT scans is one of the challenging problems in the medical image analysis. We aim to develop novel methods to accurately delineate tumour in limited data regime.
    website: ../Projects/DL_medical_images/
    url: ../Projects/DL_medical_images/
  - name: Applying Graph neural networks for medical image analysis
    img: /assets/img/thumb.png
    desc: Applying GNN (Graph Neural Networks) method to learn latent features from medical image data, applying representation learning techniques for better classification and segmentation of medical images. Exploration of difference between Deep neural networks learning and Graph neural networks learning, explainablity of GNNs. 
    website: ../Projects/GNN_medical/
    url: ../Projects/GNN_medical/
  - name: Fast identification of depressive symptomatology using probabilistic machine learning. 
    img: /assets/img/health_care.png
    desc: Depression is an extremely common disorder, yet often not diagnosed. We aim to use Probabilistic Machine Learning to develop optimised approaches to help the specialists to identify these people, giving them the chance to access proper treatment as soon as possible. 
    website: ../Projects/proactive_edurado/
    url: ../Projects/proactive_edurado/
  - name: Ultra-brief questionnaires for pre-screening for depressive symptomatology
    img: /assets/img/health_care.png
    desc: Find the optimal ultra-brief questionnaire to identify depressive symptoms.   
    website: ../Projects/proactive_darragh/
    url: ../Projects/proactive_darragh/
  
---
{% include list-squares.html items=page.team %}
