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
      ##### Spectral-Temporal Graph Neural Network for Forecasting Visiting Patterns

      * Modeled the problem of predicting the hourly number of visits to Points of Interest (POIs) across the U.S. as a multivariate time-series forecasting task.
      * Developed a novel **Graph Neural Network-based** forecasting architecture to capture the POI relationships based on their associated feature and temporal correlations to build a dynamic graph. The proposed model captures temporal intra- and inter-series correlations using a two-step **attention** mechanism. The generated graph is then fed to a GNN layer to build new representations for POIs and conduct the forecasting based on the learned latent representations.

      ##### W4H: Wearables for Health and Disease Knowledge

      * Building an open-source toolkit to enable health facilities efficiently store, analyze, and visualize real-time wearable data from heterogeneous sources (e.g., Fitbit, Garmin, Apple Watch) under a unified Geo-Referenced Multivariate Time-Series (GeoMTS) data format.
      * Developed a layered system architecture to separate the data engineering, analysis, and visualization tasks.
      * Utilized big data frameworks such as **Spark** and **Kafka** to meet the scalability and reliability requirements of the system.
  - title: "Software R&D Intern"
    company: "Gam Electronics Co."
    company_url: ""
    location: "Tehran"
    date_start: "2020-07-11"
    date_end: "2020-09-20"
    description: |
      **Responsibilities include:**

      * Designed and developed complex automated business processes.
      * Took the high-level requirements and transformed them into functional specifications with detailed development plans.
      * Prepared and executed User Acceptance Testing (UAT), developed improvement plans, and took accountability for fixing identified errors.
      * Designed and developed web forms for the given specifications.

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
