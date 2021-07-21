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
  - title: Research Assistant
    company: Silence Laboratories
    company_url: 'https://silencelaboratories.com/'
    location: Singapore
    date_start: '2020-07-01'
    date_end: ''
    description: |2-
        Project 1: Proximity detection and verification of devices
        Designed a robust system aimed at verifying co-presence of two or multi-party systems using acoustic information and pair them using shared secret key. Achieved accuracy of $>$92\% across different scenarios when tested in noisy markets of India.
        
        Project 2: Landmark extraction from infrastructure for seamless indoor mobility
        Developed a human activity detection engine using mobile sensors data and WiFi AP to substantiate proof-of-attempt for multiple use-cases.
        
        Project 3: Inertial sensor based authentication systems
        Developed a human activity detection engine using mobile sensors data and WiFi AP to substantiate proof-of-attempt for multiple use-cases.
     
        Project 4: Tracking of gestures
        Developed a real-time syste to track human gestures done using mobile device and verify them with minimal false-positive rates. 
        
        All the projects are in line to be deployed with agreed customer companies as part of trials and filed as patents.

        
  - title: Security Research Intern
    company: Cyber Security Research Centre @ NTU, Singapore 
    company_url: ''
    location: Singapore
    date_start: '2020-01-01'
    date_end: '2020-07-31'
    description: |2-
         Project: Malware Detection on Highly Imbalanced Data through Sequence Modeling(undergraduate thesis)
         
         Performed dynamic analysis on mobile application activity sequences for the purpose of malware detection on highly imbalanced dataset.
         Used the state-of-the-art language representation model BERT, to create a sequential model and achieved an F1 score of 0.919 with just 0.5\% of the examples being malware in the dataset.
         
  - title: Mitacs Summer Scholar
    company: School of Computer Science @ University of Windsor, Canada 
    company_url: ''
    location: Canada
    date_start: '2019-05-01'
    date_end: '2019-08-31'
    description: |2-
        Project Title: Integrating Continuous Authentication into the Personal Health Record Applications

        Developed a protocol to authenticate users based on their interaction with the phone using anomaly in inertial sensor data.
        Analysed across 6 different classification models and achieved 95–97\% accuracy for each, when tested using tenfold cross validation.        

design:
  columns: '2'
---
