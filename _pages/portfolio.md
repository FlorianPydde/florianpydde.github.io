---
layout: single
title: "Portfolio"
permalink: /portfolio/
author_profile: true
header:
    overlay_image: /assets/images/test.jfif
    caption: "Photo by [Gradienta](https://unsplash.com/@gradienta) on [Unsplash](https://unsplash.com/photos/bKESVqfxass)"
classes: wide

fr1:
  - title: "MLOps Solution Accelerator"
    # image_path: assets/images/deep_learning.png
    # alt: "placeholder image 2"
    text: "My clients often required guidance in implementing an MLOps process in Azure. To accelerate and standardize our deliveries, I created the base MLOps template and lead a team of MSFT data scientist which improved it based on field feedback, and ramped-up colleagues. The template served as a basis of over 15 customer projects and increased delivery speed by up to 50%. The project is a 100% open-source."
    url: "https://github.com/microsoft/dstoolkit-mlops-base"
    btn_label: "Code"
    btn_class: "btn--primary"
    tags: 
        - MLOps
        - Cross-industry

fr2:
  - title: "Multi-Level Demand Forecasting"
    # image_path: assets/images/deep_learning.png
    # alt: "placeholder image 2"
    text: "The goal of the project was to create a multi-model approach to forecast the demand for multiple geographical regions and levels (national to city). Leveraging Databricks, I built a pipeline of sequential notebooks to: (1) Prepare the data: inputting erroneous data and ensuring correct temporal train-test split.(2) Multi-model approach: training multiple models (Prophet, lstm, and xgboost) following a similar AutoMl approach. (3) Map-reduce orchestrator: to apply the step above to each geographical level, I applied the multi-model function to defined level using sparks' map-reduce trick. Similar approach can be found in the link."
    url: "https://github.com/microsoft/solution-accelerator-many-models"
    btn_label: "AML Approach"
    btn_class: "btn--primary"
    tags: 
        - Demand Forecasting
        - Energy Utilities

fr3:
  - title: "Recommendation System"
    # image_path: assets/images/deep_learning.png
    # alt: "placeholder image 2"
    text: "The objective was to build the foundation of the recommendation system for their video content. The solution was used to build a generic code repository"
    url: "https://github.com/microsoft/Azure-Synapse-Content-Recommendations-Solution-Accelerator"
    btn_label: "Code"
    btn_class: "btn--primary"
    url2: "https://github.com/microsoft/recommenders"
    btn_label2: "Resource"
    btn_class2: "btn--primary"
    tags: 
        - Recommender System
        - Entertainment

fr4:
  - title: "Team Lead"
    # image_path: assets/images/deep_learning.png
    # alt: "placeholder image 2"
    text: "For big customer projects, I was assigned to the projects as DS development lead to support the leadership team. I was responsible for team aligned with architect team, project manager, and data science team. My activities included progress tracking and unblocking, sprint planning with the team and supporting technical designs. My approach always consists in keeping the team up to date and make the individual participate in technical decisions. This means creating an atmosphere of trust withing the team, driving the right discussions with the right people, and empowering peers to own their work."
    tags: 
        - DS Team Lead
        - Cross-Industry
---


**Selected projects**:
You can find a list of past projects I worked on during my business engagements.

{% include feature_row id="fr1" type="left" %}
{% include feature_row id="fr2" type="left" %}
{% include feature_row id="fr3" type="left" %}
{% include feature_row id="fr4" type="left" %}
