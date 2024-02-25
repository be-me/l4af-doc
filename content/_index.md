---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: The Future is Undefined, All Options Exist Today
      text: Welcome to the Library for Alternate Futures' website 🎉
      primary_action:
        text: Learn More
        url: /community/
        icon: rocket-launch
      secondary_action:
        text: Our documents
        url: /docs/
      announcement:
        text: "Second annual meeting on March 1, 2024"
        link:
          text: "Read more"
          url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: ""
      background:
        color: ""
        image:
          # Add your image background to `assets/media/`.
          filename: "58910025.jpg"
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "1M+"
          description: |
            people living in Southern Illinois 
            with Hugo Blox
        - statistic: "130k+"
          description: |
            people living in the Carbondale-Marion area  
            as of 2022
        - statistic: "1"
          description: |
            Library for Alternate Futures
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-800"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: Features
      text: Collaborate, publish, and maintain technical knowledge with an all-in-one documentation site. Used by 100,000+ startups, enterprises, and researchers.
      items:
        - name: Access to Tools
          icon: beaker
          description: Automatic sitemaps, RSS feeds, and rich metadata take the pain out of SEO and syndication.
        - name: Opportunities to Connect
          icon: bolt
          description: Collaboration brings better results than competition.
        - name: Easy to Join
          icon: sparkles
          description: One-click deployment to GitHub Pages. Have your new website live within 5 minutes!
        - name: Get as Involved as You Want
          icon: face-smile
          description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
        - name: Highly Rated
          icon: star
          description: Rated 5-stars by the community.
        - name: A Library Collection
          icon: building-library
          description: Get informed and inspired
  - block: cta-card
    content:
      title: "Create your best tomorrow today!"
      text: The Library for Alternate Futures provides a knowledge base and strategic support.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/details/docs/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
