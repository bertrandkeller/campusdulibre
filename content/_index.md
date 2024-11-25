---
title: Digital Accessibility Inclusion
subtitle: Capitalisation des savoirs
seo_title:

primary_cta_page: "about"
secondary_cta_page: "projects"

posts_section_heading: Recent Posts
projects_section_heading: Projects

outputs:
  - html
  - json

disableKinds:
  - RSS
  - taxonomy
  - taxonomyTerm

cascade:
- _target:
    path: /publication/**
  outputs:
    - html
    - presentation
- _target:
    path: /assessment/**
  outputs:
    - html
    - presentation
---
