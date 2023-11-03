---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: "PhD Research Assistant"
    company: "University of Southern California - InfoLab"
    company_url: "https://infolab.usc.edu/"
    company_logo: usc_logo
    location: "Los Angeles"
    date_start: "2022-01-01"
    date_end: ""
    description: |
      #### Project Highlights
      ##### [Wearables for Health (W4H) Toolkit](https://github.com/USC-InfoLab/w4h-integrated-toolkit/)

      * Led the development of the W4H Integrated Toolkit, an open-source toolkit centralizing both real-time and offline wearable data from various sources (e.g., Garmin, Apple Watch, Fitbit).
      * Designed a scalable system architecture separating data engineering, analysis, and visualization.
      * The toolkit comprises the following open-sourced tools:
        <br><br/>
        * [**StreamSim**](https://github.com/USC-InfoLab/StreamSim): Real-time data streaming simulator using Python and Flask.

        * [**W4H ImportHub**](https://github.com/USC-InfoLab/W4H-ImportHub): Integrates stored datasets with Python, SQLAlchemy, and Streamlit.

        * [**pyGarminAPI**](https://github.com/USC-InfoLab/pyGarminAPI): Python library for interacting with the Garmin API.

        * [**Integrated Analytics Dashboard**](https://github.com/USC-InfoLab/w4h-integrated-toolkit/): Core component for data extraction and analysis using Streamlit, pandas, Flask, Spark, and Kafka.

      * Released the toolkit in two modes: a Docker image for local setup and a centralized version on USC clusters.

      ##### Accurate EEG Seizure Detection and Classification

      I developed a GNN-based deep learning model to analyze brain correlations across spatial, semantic, and temporal dimensions using EEG signals.

      * Designed and implemented a GNN-based model using PyTorch and PyTorch Geometric to dynamically model brain correlations using EEG signals.
      * Utilized pretrained LLMS to enhance model performance, unveiling dynamic brain dependencies.

      
      ##### [Learning Dynamic Graphs for Accurate Point-of-Interest Visit Forecasting](/publication/bysgnn/)

      Addressing the complex task of predicting visits to Points of Interest (POIs), I formulated the problem as a multivariate time-series forecasting challenge.

      * Transformed the problem of predicting POI visits in the U.S. into a time-series forecasting task, leveraging multi-context correlations.
      * Introduced BysGNN, a temporal graph neural network implemented using PyTorch.
      * Utilized pretrained LLMS to optimize the model, achieving significant improvement in forecasting accuracy.


      ##### Mentoring and Training
      Trained and guided two undergraduate students on an academic project during the Summer of 2022, enhancing their research capabilities and ensuring project success. 


  - title: "Software R&D Intern"
    company: "Gam Electronics Co."
    company_url: ""
    location: "Tehran"
    date_start: "2020-07-11"
    date_end: "2020-09-20"
    description: |
      **Responsibilities include:**

      * Engineered automated business processes using Python, Flask, and Selenium, enhancing efficiency.
      * Conducted unit and integration testing using pytest and unittest libraries in Python.
      * Developed interactive web dashboards using HTML, CSS, and JavaScript for enhanced user experience.

  - title: "Research: Design and Analysis of a Secure Smart-Card-Based Healthcare System"
    company: "Amirkabir University of Technology"
    company_url: "https://aut.ac.ir/en"
    company_logo: amirkabir_university_of_technology
    location: "Tehran"
    date_start: "2020-02-20"
    date_end: "2020-08-11"
    description: |
      The research consists of 2 main parts, the investigation of smart card architectures and modeling security threats in an Electronic Healthcare System. A functional system architecture has been proposed to address these security threats which specifies a smart-card-based authentication method. The research was conducted in the Spring and Summer of 2020.
      
  # - title: CEO
  #   company: GenCoin
  #   company_url: ''
  #   company_logo: org-gc
  #   location: California
  #   date_start: '2021-01-01'
  #   date_end: ''
  #   description: |2-
  #       Responsibilities include:
        
  #       * Analysing
  #       * Modelling
  #       * Deploying

  # - title: Professor of Semiconductor Physics
  #   company: University X
  #   company_url: ''
  #   company_logo: org-x
  #   location: California
  #   date_start: '2016-01-01'
  #   date_end: '2020-12-31'
  #   description: Taught electronic engineering and researched semiconductor physics.

design:
  columns: '2'
---
