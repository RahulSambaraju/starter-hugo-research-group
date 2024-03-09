---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        Send me questions, comments, and inquiries. I'd love to hear what you have to say and share papers, ideas, and thoughts!
      email: leo.sambaraju@gmail.com
      phone: 00441316504521
      address:
        street: George Square
        city: Edinburgh
        region: Scotland
        postcode: 'EH8 9JZ'
        country: United Kingdom
        country_code: UK
      coordinates:
        latitude: '55.8566'
        longitude: '-4.2501'
      
      office_hours:
        - 'Tuesday 14:00 to 15:00'
       
      appointment_url: '(https://dashboard.appointlet.com/profiles/126081/scheduling-pages/130424)'
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
          filename: contact.jpg
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
