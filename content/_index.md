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
  - block: portfolio
    id: publications
    content:
      title: 'Publications'
      text: '*Find specific content by [searching publications](./publication/).*'
#      text: '*Find specific content by [searching publications](./publication-old/) or using the filters below.*'
      filters:
        folders:
          - publication
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        #- name: Topic 1
        #  tag: AI ethics
        #- name: Topic 2
        #  tag: AI 
    design:
      columns: '2'
      view: compact
  - block: markdown
    id: teaching
    content:
      title: Teaching
      text: |2-
        **Head Teaching Assistant, [CPSC 477/577 Natural Language Processing](https://nlp.cs.yale.edu/cpsc477/),** Spring 2025  
        *Department of Computer Science, Yale University, New Haven, CT*  

        **Instructor, [MIT Menezes Challenge PRIMES Circle](https://math.mit.edu/research/highschool/primes/circle/),** 2021-2023  
        *Department of Mathematics, MIT, Cambridge, MA*  
        Fundamentals of Group Theory  

        **Lab Assistant, 6.036 Introduction to Machine Learning,** Spring 2021  
        *Department of Electrical Engineering & Computer Science, MIT, Cambridge, MA*  

        **Teaching Assistant, [Research Science Institute (RSI)](https://www.cee.org/programs/research-science-institute),** Summer 2019  
        *MIT, Cambridge, MA*  
        Fundamentals of Scientific Writing
    design:
      columns: '2'
      view: compact
---
