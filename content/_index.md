---
# Leave the homepage title empty to use the site title
title: Meenakshi Krishnan's webpage
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Assistant
          company: University of Maryland College Park
          company_url: 'https://umd.edu/'
          company_logo: org-x
          location: College Park, MD
          date_start: '2023-06-01'
          date_end: ''
          description: I am working as a Reseach Assistant with Prof. Ramani Duraiswami in the CS department.
        - title: Teaching Assistant
          company: University of Maryland College Park
          company_url: 'https://umd.edu/'
          company_logo: org-x
          location: College Park, MD
          date_start: '2021-08-01'
          date_end: '2023-06-01'
          description: I worked as a TA for MATH120 (Elementary Calculus), MATH141 (Calculus II), AMSC661 (Scientific Computation), AMSC420 (Mathematical Modeling).
    design:
      columns: '2'
  - block: collection
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
#  - block: collection
   # id: talks
 #   content:
  #    title: Recent & Upcoming Talks
 #     filters:
 #       folders:
#          - event
#    design:
 #     columns: '2'
 #     view: compact
---
