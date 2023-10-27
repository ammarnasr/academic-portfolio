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

        - title: NLP Consultant
          company : Clingendael - the Netherlands Institute of International Relations
          company_url: 'https://www.clingendael.org/'
          company_logo: clingendael
          location: Remote
          date_start: '2023-10-01'
          date_end: ''
          description: |2-
              * Working as an NLP consultant on a research project analyzing polarization in Twitter discussions related to the conflict in Sudan.
              * Manually annotated part of the Arabic dataset for stance detection, sentiment analysis and bot identification.
              * Collaborated with senior researchers to design a pipeline for stance classification and bot detection using BERT models fine-tuned on our annotated dataset.
              * Applying state-of-the-art NLP techniques like transformers and transfer learning to enhance ML models for low-resource Arabic text.

        - title: Teaching Assistant
          company: School of Informatics, The University of Edinburgh
          company_url: 'https://www.ed.ac.uk/informatics'
          company_logo: edinburgh
          location: Edinburgh, UK
          date_start: '2023-01-01'
          date_end: '2023-06-01'
          description: |2-
              * Served as a TA for the Computer Graphics course, instructing over 100 students.
              * Designed and implemented 3 programming assignments on core graphics algorithms including raytracing, meshes and optimization.
              * Hosted lab sessions to mentor students in C++, OpenGL and Belnder.
              * Achieved an overall student satisfaction rating of 4.8/5.0 in course evaluations.

        - title: Data Scientist
          Company: AmunData, Data-Driven Research, and Advisory
          company_url: 'https://www.linkedin.com/company/amundata/'
          company_logo: amundata
          location: Khartoum, Sudan
          date_start: '2021-07-01'
          date_end: '2022-09-01'
          description: |2-
              * Led the development of an open-source precision agriculture web application using Python, Streamlit, and Azure to provide crop monitoring and insights to clients. The application leveraged Sentinel-2 satellite imagery and vegetation indices to enable low-cost, customized field monitoring.
              * Created automated workflows to process and store raw Sentinel-2 data by extracting vegetation insights like NDVI, LAI then storing raw processed imagery in Azure Blob storage.
              * Designed and implemented a crop classification pipeline using Random Forest and Sentinel-2 multispectral bands. Achieved 89.22% accuracy in categorizing key crops in the state of El Gezira. Analysis provided area estimates for strategic planning on food security.
              * Developed predictive yield models by combining satellite data with ground truth data from surveys. Models were used by clients like FGM International to monitor crop health and compare seed performance.
              * Led migration of the company’s crop monitoring platform from a licensed solution to open source, which reduced running costs by 85% and enabled greater customization.
              * Managed interns, provided technical guidance, wrote project proposals, and maintained existing data solutions.
              * Contributed to various agricultural projects using remote sensing and ML.

        - title: Full Stack Developer
          Company: Code Software Sudan
          company_url: 'https://code.sd/'
          company_logo: code
          location: Khartoum, Sudan
          date_start: '2020-12-01'
          date_end: '2021-06-01'
          description: |2-
              * Led migration of Sudatel’s Direct Carrier Billing platform from Java to GoLang, enabling more scalable concurrent implementations. Migration resulted in 10% increase in revenue for Anghami subscription service.
              * Optimized Anghami’s MySQL database serving over 700,000 users by redesigning schema to limit storage growth and implementing indexing/optimization. Reduced database size growth from exponential to linear.
              * Led migration of monolithic Code Management System (CMS) from Java to Golang microservices architecture, enabling 100% reduction in downtime during upgrades and integration of new services.
              * Implemented concurrent modules using Goroutines in Go which increased frequency of health checks for critical services by 2x.
              * Enhanced CMS frontend built with NodeJS by adding mentor assignment and email alerts for faster issue resolution, significantly lowering client complaints.


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
