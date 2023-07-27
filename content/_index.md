---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: publications
    content:
      title: Publications
      text: |-
        Find specific content by [searching publications](./publication/).
      filters:
        folders:
          - publication-old
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      # buttons:
      #  - name: All
      #    tag: '*'
      #  - name: Topic 1
      #    tag: Tag 1
    design:
      columns: '1'
      view: compact
  - block: markdown
    id: teaching
    content:
      title: Teaching
      text: |2-
        **Instructor, Fundamentals of Group Theory, MIT PRIMES Circle,** 2021-2023  
        *Department of Mathematics, MIT, Cambridge, MA*  

        **Lab Assistant, 6.036 Introduction to Machine Learning,** Spring 2021  
        *Department of Electrical Engineering & Computer Science, MIT, Cambridge, MA*

        **Teaching Assistant, Fundamentals of Scientific Writing,** Summer 2019 
        *Research Science Institute (RSI), MIT, Cambridge, MA*
    design:
      columns: '1'
      view: compact
---
