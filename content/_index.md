---
# Leave the homepage title empty to use the site title
title: "William Brasic"
date: 2024-07-26
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: /CV/Brasic_William_CV_4.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: background.jpg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        My current research investigates the effects of pricing algorithms on competition.  Broadly, I am interested in understanding the implications of emerging technologies, such as machine learning, on market dynamics as well as antitrust and competition policy.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Working Papers and Works in Progress
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

  # - block: collection
    #content:
      #title: Recent Publications
      #text: ""
      #filters:
        #folders:
          #- publication
        #exclude_featured: false
    #design:
      #view: citation
  #- block: collection
    #id: talks
    #content:
      #title: Recent & Upcoming Talks
      #filters:
        #folders:
          #- event
    #design:
      #view: article-grid
      #columns: 1
  # - block: collection
    #id: news
    # content:
      #title: Recent News
      #subtitle: ''
      #text: ''
      # Page type to display. E.g. post, talk, publication...
      #page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      #count: 5
      # Filter on criteria
      #filters:
        #author: ""
        #category: ""
        #tag: ""
        #exclude_featured: false
        #exclude_future: false
        #exclude_past: false
        #publication_type: ""
      # Choose how many pages you would like to offset by
      #offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      #order: desc
    #design:
      # Choose a layout view
      #view: date-title-summary
      # Reduce spacing
      #spacing:
        #padding: [0, 0, 0, 0]


---
