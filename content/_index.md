---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:

  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: Python
          description: 100%
          icon: r-project
          icon_pack: fab
        - name: Julia
          description: 50%
          icon: chart-line
          icon_pack: fas
        - name: Photography
          description: 10%
          icon: camera-retro
          icon_pack: fas
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Assistant
          company: Nanyang Technological University
          company_url: ''
          company_logo: org-ntu
          location: Singapore
          date_start: '2022-07-01'
          date_end: '2023-04-01'
          description: |2-
              Participating in NTU-SUNSEAP: Mitigating Solar Intermittency using Energy Storage System and Demand Side Management.

        - title: Research Assistant
          company: Chinese University of Hong Kong
          company_url: ''
          company_logo: org-cuhk
          location: Shenzhen
          date_start: '2023-04-01'
          date_end: '2023-08-01'
          description: AI-Powered Power System.
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2022-07-04'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Python for Data Science, AI & Development
          url: ''

    design:
      columns: '2'
 
---
