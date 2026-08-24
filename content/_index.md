---
# Leave the homepage title empty to use the site title
title: "William Brasic"
date: 2024-07-26
type: landing

design:
  # Default section spacing
  spacing: "2rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: CV
        url: https://drive.google.com/file/d/16GgBBClxaF0fsSlEhAgO4GYQYbQYjljf/view?usp=drive_link
      buttons:
        - text: Job Market Paper
          url: https://drive.google.com/file/d/1QVyke0nyIxgv5jUvWM3OXV3niEwzh9I5/view?usp=drive_link
        - text: Teaching Evaluations
          url: https://drive.google.com/file/d/1ZtwydBayajGDX8IyMiRtlwb4vzN_QHCQ/view?usp=drive_link
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
        <p style="color: white;">My research answers questions in health economics, artificial intelligence, and antitrust and competition policy. My job market paper <a href="https://drive.google.com/file/d/1QVyke0nyIxgv5jUvWM3OXV3niEwzh9I5/view?usp=drive_link" target="_blank" rel="noopener" style="color: rgb(255, 165, 0);"><em>Hooked on Flavor: Addiction, Present Bias, and the Consequences of E-Cigarette Flavor Policy</em></a> examines how flavored e-cigarette regulations affect addiction and consumer behavior through a dynamic structural model. I also study the competitive effects of pricing algorithms and recommendation systems, an area of growing antitrust enforcement interest. My paper <a href="https://drive.google.com/file/d/1m2-YP24WV-qyHhqeCn4uiozMNZUVehqE/view?usp=drive_link" target="_blank" rel="noopener" style="color: rgb(255, 165, 0);"><em>Algorithmic Pricing, Recommendation Systems, and Competition</em></a> is currently under a Revise and Resubmit at the International Journal of Industrial Organization, and multiple of my papers in this area have each received a best paper award at The University of Arizona.</p>
    design:
      columns: '1'

  - block: markdown
    content:
      title: 'My Professional Experience'
      subtitle: ''
      text: |-
        <p style="color: white;">Beyond research, I have gained hands-on experience applying my training in industrial organization and applied microeconomics to real-world economic issues. As an Associate Extern at Analysis Group, I analyzed financial and subscriber data to estimate damages and inform strategic recommendations in a high-profile carriage-fee dispute. As a research assistant for the Arizona Residential Utility Consumer Office, I supported expert witness testimony by conducting data-driven impact assessments of proposed utility rate increases.</p>
    design:
      columns: '1'

  - block: markdown
    content:
      title: 'My Toolkit'
      subtitle: ''
      text: |-
        <p style="color: white;">I am well-versed in quasi-experimental methods such as difference-in-differences, regression discontinuity design, and synthetic control, along with applying structural models, both static and dynamic, to help answer empirical questions. I implement these methods using R, MATLAB, C++, Julia, and Python, along with Git/GitHub for version control, Docker for reproducible environments, and Slurm for high-performance computing.</p>
    design:
      columns: '1'

  - block: markdown
    content:
      title: 'My Hobbies'
      subtitle: ''
      text: |-
        <p style="color: white;">When I'm not doing economics, you can usually find me traveling with my wife, hanging out with our cat, at the gym training calisthenics, running in the Tucson desert, or talking about the Chicago Bears 🐻⬇️.</p>
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
