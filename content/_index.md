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
        url: /CV/Brasic_William_CV_20260610.pdf
      buttons:
        - text: Download Job Market Paper
          url: /Research/JMP_20260611.pdf
    design:
      css_class: dark
      background:
        color: black
        # image:
          # Add your image background to `assets/media/`.
          # filename: background.jpg
          # filters:
          #   brightness: 1.0
          # size: cover
          # position: center
          # parallax: false
  - block: markdown
    content:
      title: 'My Research'
      subtitle: ''
      text: |-
        <p style="color: white;">My research uses industrial organization and applied microeconomics to answer questions within artificial intelligence, health economics, and antitrust and competition policy. More specifically, I have done work on the effects of pricing algorithms on competition and my job market paper investigates the effects of flavored e-cigarette policies on addiction and consumer behavior via a dynamic structural model.</p>
    design:
      columns: '1'

  - block: markdown
    content:
      title: 'My Hobbies'
      subtitle: ''
      text: |-
        <p style="color: white;">When I'm not doing economics, you can usually find me at the gym working on my calisthenics and running, or talking about the Chicago Bears 🐻⬇️.</p>
    design:
      columns: '1'

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
