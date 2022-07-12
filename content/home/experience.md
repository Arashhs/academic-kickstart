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
      ##### Accurate Multivariate Time-Series Forecasting of POI Visits Numbers

      * Building a state-of-the-art GNN-based forecasting model to predict the hourly number of visits to 500 most visited POIs in Houston
      * More specifically, we are building our multivariate time-series forecasting model by applying Recurrent Neural Networks (RNNs) to capture the time dependencies within POIs and an attention-based mechanism to capture the inter-POI correlations. We further utilize Graph Neural Networks (GNNs) to learn new representations for POIs based on the derived intra- and inter-series correlations to be able to make accurate predictions

      ##### W4H: Wearables for Health and Disease Knowledge

      * In this project, we are building an open-source toolkit to enable health facilities efficiently store, analyze, and visualize real-time wearable data from heterogeneous sources (e.g., Fitbit, Garmin, Apple Watch) under a unified data format that we are developing
      * We are developing a layered system architecture to separate the data engineering, data analysis, and data visualization tasks
      * We have utilized big data frameworks such as Spark and Kafka to meet the scalability and reliability requirements of our system
  - title: "Software R&D Intern"
    company: "Gam Electronics Co."
    company_url: ""
    location: "Tehran"
    date_start: "2020-07-11"
    date_end: "2020-09-20"
    description: |
      **Responsibilities include:**

      * Designing and building automated business processes
      * Participating in the development of complex business processes
      * Taking the high-level requirements and transforming them into functional specifications with detailed
      development plans
      * Preparing and executing User Acceptance Testing (UAT) and developing improvement plans as well as
      taking accountability in fixing identified errors
      * Creating Web Forms for the given specifications

  - title: "Research: Design and Analysis of a Secure Smart-Card-Based Healthcare System"
    company: "Amirkabir University of Technology"
    company_url: "https://aut.ac.ir/en"
    company_logo: amirkabir_university_of_technology
    location: "Tehran"
    date_start: "2020-02-20"
    date_end: "2020-08-11"
    description: |
      The research consists of 2 main parts, the investigation of smart card architectures and modeling security threats in an Electronic Healthcare System. A functional system architecture has been proposed to address these security threats which specifies a smart-card-based authentication method. The research was conducted in the Spring and Summer of 2020 for my Research Method and Technical Presentation course (which includes both Written and Oral Presentations).

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
