---
# Leave the homepage title empty to use the site title
title: Odelia Melamed
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: card
#  - block: collection
#    id: talks
#    content:
#      title: Talks
#      filters:
#        folders:
#          - event
#    design:
#      columns: '2'
#      view: compact
  
---
