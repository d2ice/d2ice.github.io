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
  - name: Proactive
    img: /assets/img/health_care.png
    desc: How to help people with depressive symptomatology using AI? We aim to use Probabilistic ML to develop optimised approaches to identify these people, giving them proper treatment in the fast way possible. 
    website: ../Projects/proactive_edurado/
    url: ../Projects/proactive_edurado/
---
{% include list-squares.html items=page.team %}
