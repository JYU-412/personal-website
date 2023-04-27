---
date: "2022-10-24"
sections:

- block: about 
  content: 
    text: 
    username: Jiao
- block: features
  content:
    items:
    - description: ""
      icon: chart-simple
      icon_pack: fas
      name: Stata      
    - description: ""
      icon: r-project
      icon_pack: fab
      name: R
    - description: ""
      icon: chart-line
      icon_pack: fas
      name: Statistics
    - description: ""
      icon: dna
      icon_pack: fas
      name: Sequence Analysis
    - description: ""
      icon: chart-pie
      icon_pack: fas
      name: Data Visualization
    - description: ""
      icon: magnifying-glass-chart
      icon_pack: fas
      name: Machining Learning      
    title: Skills
- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Posts
  design:
    columns: "2"
    view: compact
  id: posts

#- block: collection
 #  content:
 #   count: 2
 #   buttons:
  #  - name: All
  #    tag: '*'
  #    - name: Deep Learning
  #      tag: Deep Learning
  #    - name: Other
  #      tag: Demo
   #   default_button_index: 0
  #  filters:
  #   folders:
  #   - project
  #  title: Teaching
  #design:
  # columns: "2"
  #    flip_alt_rows: false
  # view: showcase
  #id: projects

#- block: collection
#  content:
#    filters:
#     featured_only: true
 #     folders:
#      - publication
 #   title: Publications
#  design:
 #   columns: "2"
 #   view: card
 # id: featured
- block: collection
  content:
    count: 3
    filters:
     tag: ''
     category: ''
     publication_type: ''
     author: ''
     featured_only: true
     folders:
     - publication
    title: Recent Publications
  design:
   columns: "2"
   view: compact
  id: publication
  
- block: tag_cloud
  content:
    title: Key Words
  design:
    columns: "2"

- block: contact
  content:
    address:
      city: Minneapolis 
      country: United States
      country_code: US
      postcode: "55414"
      region: MN
      street: 50 Willey Hall, 225 19th Avenue South
    # appointment_url: https://calendly.com
    autolink: true
    contact_links:
 # - icon: twitter
  #  icon_pack: fab
  #  link: https://twitter.com/Jiao_Jo_Yu
  #  name: DM Me
    
    email: yu015354@umn.edu
    title: Contact
  design:
    columns: "2"
  id: contact
title: 
type: landing
---
