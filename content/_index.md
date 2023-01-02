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
      text:
      design:
        columns: '2'

  - block: experience
    content:
      title: Education
      items:
        - title: Bsc in Statistic & Probability
          company: Federal University of Paraná
          company_url: 'https://www.ufpr.br/portalufpr/'
          company_logo:
          location: Curitiba
          date_start: '2018-02-15'
          date_end: ''
    design:
      columns: '2'
      
  - block: experience
    content:
      title: Experience
      items:
        - title: Data Analytics
          company: Solvay
          company_url: 'https://www.solvay.com/en/'
          company_logo: 
          location: Curitiba
          date_start: '2021-12-15'
          date_end: ''
          description: |2-
              Responsibilities include:

              - Process automation and data extraction, assisting in the elaboration of analyzes and decision-making in the financial sector;
              - Support in the maintenance of reports and dashboards (Qliksense and Data Studio), being a technical point of contact and helping global teams in their daily activities;
              - Database extraction obtained through extensive databases, for manipulation and treatment in order to assist in decision making;
              - Search for new data-driven solutions and improvements for the Credit team.
              
        - title: Business Intelligence
          company: Mirum Agency
          company_url: 'https://www.mirumagency.com.br/'
          company_logo: 
          location: Curitiba
          date_start: '2020-02-17'
          date_end: '2021-12-08'
          description: |2-
              Responsibilities include:

              - Market research and information gathering using tools such as Google Analytics, Facebook Analytics, and other digital marketing tools
              - Development of dashboards using DataStudio, helping in the automation of processes and facilitating metric analysis
              - Database update and manipulation using Excel, Google Sheets, and BigQuery queries
              - Preparation of reports and presentations using PowerPoint and DataStudio.
              
        - title: Credit Modeling (intern)
          company: Bradesco
          company_url: 'https://banco.bradesco/html/classic/index.shtm'
          company_logo: 
          location: Curitiba
          date_start: '2019-07-17'
          date_end: '2019-11-08'
          description: |2-
              Responsibilities include:

              - Manipulation and approval of databases using SAS and Excel
              - Organization of spreadsheets and documents
              - Assistance in preparing presentations
    design:
      columns: '2'
    
      
  - block: accomplishments
    content:
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      items:
        - certificate_url: https://www.datacamp.com
          date_end: ''
          date_start: '2022-12-25'
          description: ''
          organization:  DataCamp
          organization_url: https://www.datacamp.com
          title: Manipulating Time Series Data in R
          url: ''
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Understanding Data Science'
          url: ''
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Intermediate SQL Queries'
          url: ''
    design:
      columns: '2'

      
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
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
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
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
  
  
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
       Para entrar em contato comigo, por favor mande-me um email pelo caminho abaixo:
      # Contact (add or remove contact options as necessary)
      email: amabilegaldin11@gmail.com
      phone: (41) 991752952
      appointment_url: 'https://www.linkedin.com/in/amabile-galdino/'
      address:
        city: Curitiba
        region: PR
        country: Brazil
        country_code: BR
      contact_links: 
      autolink: true
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          captcha: false
    design:
      columns: '2'
---
