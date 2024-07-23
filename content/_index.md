---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        The Reproducibility Working Group Bibliography
     
      text: |
        <br>

       This website gathers (useful) resources for the study of reproducibility in neuroimaging. This website is maintained by the reproducibility working group (PI: Camille Maumet) of the Empenn research team.
  
  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

---
