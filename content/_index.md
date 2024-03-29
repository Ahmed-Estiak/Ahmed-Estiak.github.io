---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
      
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text: I am Ahmed Estiak, a student and young researcher. I have very broad interest area. I am very much enthusiast in AGN, Galaxy Mergers, Galaxy Evolution, Gravitational Wave Research, Machine Learning and theoretical study of Gravitomagnetic Clock Effect. I have received my BSc and MS in Physics from Shahjalal University of Science and Technology, Sylhet. 

  - block: experience
    id: Fellowship
    content:
      title: Fellowship
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: NST Research Fellow
          company: National Science and Technology Ministry, Bangladesh
          company_url: 'http://103.69.149.45:9207/en/services/most/nst-fellowship'
          company_logo: nst
          location: Bangladesh
          date_start: '2020-01-01'
          date_end: '2020-12-31'
          description: |2-

              * Received this fellowship for the research of my MS thesis.



    design:
      columns: '2'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: experience
    id: Education
    content:
      title: Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Master of Science (Physics)
          company: Shahjalal University of Science and Technology, Sylhet
          company_url: 'https://www.sust.edu/'
          company_logo: org-x
          location: Bangladesh 
          date_start: '2019-04-04'
          date_end: '2022-05-05'
          description: |2-
              Major Achievements:
              * CGPA 3.71 on a scale of 4.00
              * Obtained highest mark in MS thesis work
              * Received university scholarships for my result
        - title: International School for Young Astronomers
          company: International Astronomical Union (Summer School)
          company_url: 'https://www.sust.edu/'
          company_logo: org-gc
          location: Yunnan Observatories, Kunming, China
          date_start: '2019-10-10'
          date_end: '2019-11-11'
          description: |2-
              Description:
              * 3-week long summer school
              * Used 1-m and 60-cm optical telesocope for an astronomy group project 
              * A total of 130 hours of lectures and training covered a wide range of astronomy topics
        - title: Bachelor of Science (Physics)
          company: Shahjalal University of Science and Technology, Sylhet
          company_url: 'https://www.sust.edu/'
          company_logo: org-x
          location: Bangladesh
          date_start: '2013-12-11'
          date_end: '2019-04-04'
          description: |2-
              Major Achievements:
              * CGPA 3.66 on a scale of 4.00
              * Among the top 5 percent of the students
              * Received university scholarships for my result


    design:
      columns: '2'

  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Astronomy
          tag: Astronomy
        - name: Other
          tag: Other
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  #- block: features
    #content:
      #title: Skills
      #items:
        #- name: R
          #description: 90%
          #icon: r-project
          #icon_pack: fab
        #- name: Statistics
          #description: 100%
          #icon: chart-line
          #icon_pack: fas
        #- name: Photography
          #description: 10%
          #icon: camera-retro
          #icon_pack: fas

  - block: experience
    content:
      title: Certification
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: OASIS Basic Patent Course (Credential ID- KIPA-21-033)
          company: Ministry of Justice, Republic of Korea
          company_url: 'http://www.oasisvisa.com/about.html'
          company_logo: korea
          location: Seoul, South Korea
          date_start: '2021-03-03'
          date_end: ''
          description: |2-
              
        - title: OASIS Advanced Intellectual Property Course
          company: Ministry of Justice, Republic of Korea
          company_url: 'https://grad.smu.ac.kr/_attach/file/2021/10//QcHEPJnaLPXzOGNpeHMS.pdf'
          company_logo: korea
          location: Seoul, South Korea
          date_start: '2021-03-03'
          date_end: ''
          description: 
        - title: Start-up Course
          company: Korea Productivity Centre
          company_url: 'https://eng.kpc.or.kr/eng/'
          company_logo: kpc
          location: Seoul, South Korea
          date_start: '2021-03-03'
          date_end: ''
          description: 
    design:
      columns: '2'
  #- block: accomplishments
    #content:
      ## Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      #title: 'Certification'
      #subtitle:
      ## Date format: https://wowchemy.com/docs/customization/#date-format
      #date_format: Jan 2006
      ## Accomplishments.
      ##   Add/remove as many `item` blocks below as you like.
      ##   `title`, `organization`, and `date_start` are the required parameters.
      ##   Leave other parameters empty if not required.
      ##   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      #items:
        #- certificate_url: http://www.oasisvisa.com/about.html
          #date_end: ''
          #date_start: '2021-03-03'
          #description: ''
          #organization: Ministry of Justice, Republic of Korea
          #organization_url: http://www.oasisvisa.com/about.html
          #title: OASIS Basic Patent Course (Credential ID- KIPA-21-033)
          #url: http://www.oasisvisa.com/about.html
        #- certificate_url: https://grad.smu.ac.kr/_attach/file/2021/10//QcHEPJnaLPXzOGNpeHMS.pdf
          #date_end: ''
          #date_start: '2021-03-01'
          #description: ''
          #organization: Ministry of Justice, Republic of Korea
          #organization_url: https://grad.smu.ac.kr/_attach/file/2021/10//QcHEPJnaLPXzOGNpeHMS.pdf
          #title: OASIS Advanced Intellectual Property Course
          #url: http://www.oasisvisa.com/
        #- certificate_url: https://eng.kpc.or.kr/eng/
          #date_end: ''
          #date_start: '2021-03-01'
          #description: ''
          #organization: Korea Productivity Centre
          #organization_url: https://eng.kpc.or.kr/eng/
          #title: Start-up Course
          #url: ''
    #design:
      #columns: '2'

  #- block: collection
    #id: posts
    #content:
      #title: Recent Posts
      #subtitle: ''
      #text: ''
      ## Choose how many pages you would like to display (0 = all pages)
      #count: 5
      ## Filter on criteria
      #filters:
        #folders:
          #- post
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
      #view: compact
      #columns: '2'

  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  #- block: collection
    #id: talks
    #content:
      #title: Recent & Upcoming Talks
      #filters:
        #folders:
          #- event
    #design:
      #columns: '2'
      #view: compact
  #- block: tag_cloud
    #content:
      #title: Popular Topics
    #design:
      #columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        I am waiting for your message!
      # Contact (add or remove contact options as necessary)
      email: ahmedestiak14@gmail.com
      #phone: 888 888 88 88
      #appointment_url: 'https://calendly.com'
      address:
        street: Shahjalal University of Science and Technology
        city: Sylhet
        #region: CA
        postcode: '3114'
        country: Bangladesh
        #country_code: US
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #office_hours:
        #- 'Monday 10:00 to 13:00'
        #- 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/AhmedEstiak4'
        #- icon: skype
          #icon_pack: fab
          #name: Skype Me
          #link: 'skype:echo123?call'
        #- icon: video
          #icon_pack: fas
          #name: Zoom Me
          #link: 'https://zoom.com'
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
      columns: '2'
---
