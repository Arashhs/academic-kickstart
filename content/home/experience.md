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
      ##### W4H: Wearables for Health and Disease Knowledge

      I am leading the development of an open-source toolkit to centralize real-time wearable data, aiming to improve healthcare data management.

      * Developed a unified Geo-Referenced Multivariate Time-Series (GeoMTS) format to integrate data from various sources.
      * Created scalable solutions using big data frameworks such as Spark and Kafka, and developed visualization dashboards for real-time analysis.
      * This work has contributed to real-time outlier detection in healthcare data and supported the open-source community with custom tools.

      ##### Accurate EEG Seizure Detection and Classification

      I developed a GNN-based deep learning model to analyze brain correlations across spatial, semantic, and temporal dimensions using EEG signals.

      * Utilized a dynamic graph that reflects dependencies in the brain for precise seizure classification.
      * This work contributes to further understanding and advancements in the field of medical diagnostics.

      
      ##### Learning Dynamic Graphs from All Contextual Information for Accurate Point-of-Interest Visit Forecasting
      
      Addressing the complex task of predicting visits to Points of Interest (POIs), I formulated the problem as a multivariate time-series forecasting challenge.

      * Proposed the Busyness Graph Neural Network (BysGNN), uncovering multi-context correlations for accurate forecasting.
      * Integrated temporal, spatial, and semantic signals, achieving significant improvement in forecasting accuracy over existing models, thereby contributing to real-world applications.


  - title: "Software R&D Intern"
    company: "Gam Electronics Co."
    company_url: ""
    location: "Tehran"
    date_start: "2020-07-11"
    date_end: "2020-09-20"
    description: |
      **Responsibilities include:**

      * Engineered and implemented sophisticated automated business processes, utilizing cutting-edge technologies and methodologies to enhance efficiency and accuracy.
      * Translated high-level requirements into comprehensive functional specifications, devising detailed development plans that aligned with strategic objectives and technical constraints.
      * Orchestrated and executed rigorous User Acceptance Testing (UAT), employing systematic testing strategies to identify and rectify errors, demonstrating a commitment to quality and continuous improvement.
      * Conceptualized, designed, and developed intricate web forms in accordance with given specifications, leveraging modern web technologies and best practices to ensure compliance with business requirements.

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
