---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem'

sections:
  # ===========================
  # BIOGRAPHY SECTION
  # ===========================
  - block: resume-biography-3
    content:
      username: admin
      text: ''
      button:
        text: Download CV
        url: uploads/Hamza_Boudhair_CV.pdf
      headings:
        about: 'About me'
        education: 'Education'
        interests: 'Research interests'
    design:
      css_class: hbx-bg-gradient
      avatar:
        size: medium
        shape: circle

  # ===========================
  # ABOUT MY WORK
  # ===========================
  - block: markdown
    content:
      title: '🌍 About My Work'
      text: |-
        I am a Renewable Energy Engineer specializing in **wind turbine aerodynamics**, **photovoltaic systems**, and **energy performance optimization**.

        My work focuses on:
        - Aerodynamic & structural analysis of HAWT blades (QBlade, BEMT, XFoil, QFEM)
        - PV system design & techno-economic evaluation (PVSyst, RETScreen, PV*SOL)
        - Hybrid PV–battery systems and off-grid engineering
        - Energy modelling, simulation & performance assessment
        - Optimization of clean energy solutions for real-world applications

        I am passionate about applying advanced simulation tools to support the global energy transition.
    design:
      columns: '1'

  # ===========================
  # EDUCATION (PREMIUM)
  # ===========================
  - block: collection
    id: education
    content:
      title: "Education"
      subtitle: ""
      text: ""
      filters:
        folders:
          - education
    design:
      view: card
      columns: 2

  # ===========================
  # PROJECTS
  # ===========================
  - block: collection
    id: projects
    content:
      title: 'Projects'
      subtitle: ''
      text: ''
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 2

  # ===========================
  # PUBLICATIONS
  # ===========================
  - block: collection
    id: papers
    content:
      title: 'Research Publications'
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  # ===========================
  # CERTIFICATIONS
  # ===========================
  - block: markdown
    content:
      title: 'Certifications'
      text: |-
        - **PVSyst Technical Training** – Photovoltaic system simulation.  
        - **HOMER Pro Microgrid Modelling** – PV–battery–grid modeling.  
        - **MATLAB & Simulink Onramp** – Numerical modelling.  
        - **IBM Python for Data Science** – Data processing & visualization.  
        - **RETScreen Expert Certification** – Feasibility & economic analysis.  
        - **AutoCAD Electrical Certification** – Electrical schematics design.  
        - **NREL SAM / PVWatts** – Solar resource modelling.  
        - **IRENA Renewable Energy Training** – Energy transition.  
        - **Electrical Safety & Protection** – Industrial safety.  
        - **DTU Wind Energy Course** – Wind turbine aerodynamics.
    design:
      columns: '1'

  # ===========================
  # TALKS
  # ===========================
  - block: collection
    id: talks
    content:
      title: 'Recent & Upcoming Talks'
      filters:
        folders:
          - events
    design:
      view: card

  # ===========================
  # NEWS
  # ===========================
  - block: collection
    id: news
    content:
      title: 'Recent News'
      page_type: blog
      count: 5
      filters:
        exclude_future: false
        exclude_past: false
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---
