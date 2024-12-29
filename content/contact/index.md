---
title: Contact
date: 2024-12-28

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        We look forward to hearing from you
      email: yuanchao.fan@sz.tsinghua.edu.cn
      phone: 180 2698 4060
      address:
        street: 2279 Lishui Road
        city: Shenzhen
        region: Guangdong
        postcode: '518071'
        country: China
        country_code: CN
      coordinates:
        latitude: '22.5957885'
        longitude: '113.9654182'
      directions: University Town, Tsinghua SIGS, Building F, 304 & 415
      # office_hours:
      #   - 'Monday 08:00 to 18:00'
      #   - 'Friday 09:00 to 19:00'
      appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact2.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
