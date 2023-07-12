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
          description: 90%
          icon: python
          icon_pack: fab
        - name: Statistics
          description: 100%
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
        - title: Teaching Assistant
          company: School of Informatics, The University of Edinburgh
          company_url: 'https://www.ed.ac.uk/informatics'
          company_logo: edinburgh
          location: Edinburgh, UK
          date_start: '2023-01-01'
          date_end: ''
          description: |2-
              * Worked as TA with Dr. Amir Vaxman for the Computer Graphics Course which introduces classic and state-of-the-art methodology in computer graphics.
              * I was responsible for the coursework in which we designed three programming exercises -a skeleton code and an automatic self-checker- each covering a single major algorithm learned in class.
        - title: Data Scientist
          company: AmunData, Data-Driven Research, and Advisory
          company_url: 'https://twitter.com/AmunData_'
          company_logo: amundata
          location: Khartoum, Sudan
          date_start: '2022-01-01'
          date_end: '2022-09-01'
          description: |2-
              * Designing and implementing services primarily focused on precision agriculture using remote sensing data.
              * Modelling and analyzing time-series satellite data as well as field measurements to provide our clients with real-time crop monitoring
              * Deploying and maintaining a web application that analyzes time-series satellite data as well as field measurements to provide our clients with real-time crop monitoring
        - title: Research Assistant
          company: University College Dublin
          company_url: 'https://www.ucd.ie/'
          company_logo: ucd
          location: Dublin, Ireland
          date_start: '2022-03-01'
          date_end: '2022-08-01'
          description: |2-
              * Worked with DR Mohamed Saadeldin -Assistant Professor in School of Computer Science, UCD- on a project about multi-label image classification.
              * Evaluated and compared performance of neural networks with conventional output layer against neural networks utilizing the Kasami Orthogonal Classification Layer (KOCL) in the task of multi-label image classification
              * Our work extended neural networks trained on single class data to provide classification output for multi-label data without further training. The results were presented in the NLDL2022 conference
        - title: Backend Developer
          company: KooshLyncs For Software Solutions
          company_url: ''
          company_logo: 
          location: Khartoum, Sudan
          date_start: '2021-07-01'
          date_end: '2021-12-01'
          description: |2-
              * Worked in the fin-tech sector to develop an online marketplace for Sudan.
              * Designed the company’s back-end microservices for data storage, authentication and third-party integration. The services were implemented in GoLang and hosted on AWS Elastic Beans to ensure performance and scalability
        - title: Full Stack Developer
          company: Code Software Sudan
          company_url: 'https://code.sd/'
          company_logo: code
          location: Khartoum, Sudan
          date_start: '2020-12-01'
          date_end: '2021-06-01'
          description: |2-
              * Worked as Full stack developer to provide specialized solutions in web development, systems integrations, process management systems, mobile development
              * Migrated Sudatel’s Direct Carrier Billing -a type of online payment that allows consumers to charge the cost of a purchase to their phone bill,- from Java to GoLang. This enabled more flexibility in implementing concurrent modules of the system, which resulted in a 10% increase in revenue for Sudatel’s Anghami subscription service.
              * Improved the company's internal Code Management System (CMS) web application. By using a micro-service structure (rather than the monolithic), the CMS became easier to reuse in many sites and blogs. I also add a central dashboard to monitor all of the companies applications statuses and send alerts in case of failures. The CMS is implemented in GoLang and NodeJs
    design:
      columns: '2'
  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://github.com/ammarnasr/pdfs/blob/main/ICT%202019%20Certificate_Final.pdf
  #         date_end: ''
  #         date_start: '2019-09-30'
  #         description: ''
  #         organization: Ericsson
  #         organization_url: https://www.ericsson.com/en
  #         title: ICT Professional Foundation Program
  #         url: ''
  #       - certificate_url: https://www.coursera.org/account/accomplishments/verify/EMWHW5H8DXGS
  #         date_end: ''
  #         date_start: '2018-11-20'
  #         description: ''
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #   design:
  #     columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
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
        - name: Deep Learning
          tag: Deep Learning
        - name: Geospatial Analysis
          tag: Geospatial Analysis
        - name: Software Development
          tag: Software Development
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
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
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact

  
# \begin{center}
#     \textbf{\Huge \scshape Ammar Khairi} \\ \vspace{3pt}
#     \small
#     \faMobile \hspace{.5pt} \href{tel:44737506538}{+44 737 750 6528}
#     $|$
#     \faAt \hspace{.5pt} \href{mailto:ammarnasraza@gmail.com}{ammarnasraza@gmail.com}
#     $|$
#     \faLinkedinSquare \hspace{.5pt} \href{https://www.linkedin.com/in/ammarkhairi97}{LinkedIn}
#     $|$
#     \faGithub \hspace{.5pt} \href{https://github.com/ammarnasr}{GitHub}
#     $|$
#     \faGlobe \hspace{.5pt} \href{https://ammarkhairi.netlify.app/}{Portfolio}
#     $|$
#     \faMapMarker \hspace{.5pt} \href{https://goo.gl/maps/kMKL6x6Yb6camj2d8}{Edinburgh, UK}
# \end{center}



      subtitle:
      text: |-
        Send me a message and I'll get back to you as soon as possible.
      # Contact (add or remove contact options as necessary)| Copy from above
      email: ammarnasraza@gmail.com
      phone: +44 737 750 6528
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/ammarnasr1'

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
