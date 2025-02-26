---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Networked and Embedded Intelligent Systems Lab
      # image:
        # filename: welcome.jpg
      text: |
        <br>
        
        Welcome to the Networked and Embedded Intelligent Systems Lab at Purdue University! We are developing the next-generation computing and networking technologies to make embedded, mobile, and Internet-of-Things systems more efficient and trustworthy.

  - block: collection
    content:
      title: Research
      # subtitle:
      # text:
      count: 3
      filters:
        folders:
          - research
        # author: ''
        # category: ''
        # exclude_featured: false
        # publication_type: ''
        # tag: ''
      # offset: 0
      # order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

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

  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'

# sections:
  - block: people
    content:
      title: Members
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          # - Principal Investigator
          # - Researchers
          # - Graduate Research Assistants
          # - Administration
          # - Visitors
          # - Alumni
          - Member
      sort_by: Params.year_joined
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
---