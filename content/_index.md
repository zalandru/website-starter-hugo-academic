---
# Leave the homepage title empty to use the site title
title: Andrei Zaloilo
date: 2022-10-24
type: landing

sections:
 
  - block: about.biography
    id: about
    content:
      title: Welcome!
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: collection
    id: research
     # Choose how many pages you would like to display (0 = all pages)
      count: 5
    content:
      title: Research
      text: |-
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation

---
