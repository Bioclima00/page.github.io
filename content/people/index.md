---
title: People
date: 2024-12-28

type: landing

sections:
  - block: markdown
    content:
      title: Meet the i-Ecoclimatology team
      align: center
      subtitle: ''
      text:
      text_color_light: true
    design:
      columns: '1'
      background:
        image: 
          filename: team1.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  # - block: hero
  #   content:
  #     title: |
  #       Meet the team
  #     image:
  #       filename: team1.jpg
  #     text: |
  #       <br>
        
  #        **i-Ecoclimatology Members** 

  # - block: slider
  #   content:
  #     slides:
  #     - title: Meet the i-Ecoclimatology Team
  #       content: 
  #       align: center
  #       background:
  #       image:
  #         filename: coders.jpg
  #         filters:
  #           brightness: 0.8
  #       position: right
  #       color: '#666'

  - block: people
    content:
      title: 
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigator
          - Researchers
          - Grad Students
          - Administration
          - Visitors
          - Alumni
          - Support
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
      # show_experience: true
---