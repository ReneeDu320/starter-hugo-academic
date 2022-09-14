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

  - title: Data Scientist Intern
    company: Volvo Group
    company_url: 'https://www.volvogroup.com/en/'
    company_logo: volvo
    location: Greensboro, NC
    date_start: '2022-05-16'
    date_end: '2022-08-12'
    description: |2-
        Responsibilities include:
        
        * Accelerated the identification of what influenced cost using Machine Learning, provided a scalable framework that can process more variants and data, presented result to key stakeholders and suggested strategies for reducing vehicle unit costs ;
        * Replicated and optimized Cost per Unit Calculation logic from PowerBI in Databricks, saved manual work of computing cost using Python Script, which benefit 3+ teams;
        * Designed and built PySpark ETL pipeline to extract parquet data (5+ GB each) from Azure containers, load and preprocess using SparkSQL for analysis, optimized code that can reduce code execution time from 2 hour to ~20 minutes;
        * Implemented bootstrapping feature selection algorithm from scratch; constructed feature library and mapped top features from Random Forest Feature Importance; improved 50% time efficiency using MLFlow, Hyperopt with Spark Trails

  - title: Data Scientist Intern
    company: Ally Financial
    company_url: ''
    company_logo: org-x
    location: California
    date_start: '2016-01-01'
    date_end: '2020-12-31'
    description: Taught electronic engineering and researched semiconductor physics.
    
  - title: Professor of Semiconductor Physics
    company: University X
    company_url: ''
    company_logo: org-x
    location: California
    date_start: '2016-01-01'
    date_end: '2020-12-31'
    description: Taught electronic engineering and researched semiconductor physics.
    
 - title: Professor of Semiconductor Physics
    company: University X
    company_url: ''
    company_logo: org-x
    location: California
    date_start: '2016-01-01'
    date_end: '2020-12-31'
    description: Taught electronic engineering and researched semiconductor physics.

design:
  columns: '2'
---
