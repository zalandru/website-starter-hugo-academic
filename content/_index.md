---
# Leave the homepage title empty to use the site title
title: Andrei Zaloilo
date: 2022-10-24
type: landing

sections:
 
  - block: about.biography
    id: about
    content:
       title: Andrei Zaloilo
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: collection
    id: research
    content:
      title: Research
      text: |-
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: list
      # Choose a view for the listings:
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
          
---
