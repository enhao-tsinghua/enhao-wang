---
# Leave the homepage title empty to use the site title
title: Dr Enhao Wang
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: experience
    content:
      title: Professional Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Assistant Professor of Ocean Engineering
          company: Shenzhen International Graduate School, Tsinghua University
          company_url: ''
          company_logo: org-thu
          location: Shenzhen
          date_start: '2021-06-02'
          date_end: ''
          description: 
        - title: Lecturer of Ocean Engineering/Postdoctoral Research Fellow (On-the-Job)
          company: Tianjin University
          company_url: ''
          company_logo: org-tju
          location: Tianjin
          date_start: '2018-04-20'
          date_end: '2021-05-31'
          description:
        - title: Postdoctoral Research Assistant
          company: University of Glasgow
          company_url: ''
          company_logo: org-uog
          location: Glasgow
          date_start: '2017-02-01'
          date_end: '2017-12-31'
          description:
    design:
      columns: '2'
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
      # Contact (add or remove contact options as necessary)
      address:
        street: Fluid-Structure Interaction Laboratory
        city: Ocean Centre, Tsinghua Campus, Xili University Town, Nanshan District
        region: Shenzhen
        postcode: '518055, Guangdong, China'
        country: China
        country_code: CN
    design:
      columns: '2'
---
