---
title: People
date: 2024-12-28

type: landing

sections:
  - block: hero
    content:
      title: |
        i-Ecoclimatology Lab
      image:
        filename: team1.jpg
      text: |
        <br>
        
         **Meet the team** 

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