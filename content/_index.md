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
  - block: features
    content:
      title: Skills
      items:
        - name: Archiving
          icon: archive
          icon_pack: ai
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
        - title: Digital Preservation Librarian
          company: Penn State University
          company_url: 'https://libraries.psu.edu/'
          company_logo: org-gc
          location: Pennsylvania
          date_start: '2017-02-01'
          date_end: ''
          description: |2-
              Academic rank of Assistant Librarian. Responsibilities include:
              * Analysing
              * Modelling
              * Deploying
        - title: Digital Content Strategist
          company: University of Cincinnati
          company_url: 'https://libraries.uc.edu/'
          company_logo: org-x
          location: Ohio
          date_start: '2014-01-01'
          date_end: '2017-01-01'
          description: |2-
              Academic rank of Associate Librarian.
        - title: Associate Archivist
          company: American Jewish Archives
          company_url: 'https://www.americanjewisharchives.org/'
          company_logo: org-x
          location: Ohio
          date_start: '2010-02-01'
          date_end: '2013-12-01'
          description: |2-
              *	Arranged and described content of complex collections, providing context of creation while adhering to professional standards (DACS, EAD) to ensure access by present, future, and cross-institutional users
              *	Assisted on- and off-site researchers, answering reference questions to connect patrons with primary sources
              *	Streamlined descriptive process through implementation of automated methods for creation of MARC records; EAD finding aids (including print and web derivatives); and labels for collection folders and boxes
              *	Launched new online discovery layer, to replace outdated catalog, using open-source VuFind; integrating MARC records, institution website searching, and plans to include indexing of EAD and digital objects
              *	Designed in-house MS Access databases for tracking Judaic conversions and publication requests
              *	Implemented, configured, and managed Archivists Toolkit for collection management
              *	Administered two Linux servers: a production server for AJA website and online catalog; and development server for new catalog features, database server (for Archivists Toolkit), internal access copies, and digital repository exploration
              *	Lead planning for digital records and preservation, including accessioning, arrangement and description, geo-redundant backup, and medium-term planning with goal of launching digital repository
              *	Developed workflow, procedures, and documentation for digitization of collection material to ensure consistency
              *	Participated in records management planning for parent institution and sister organizations
              *	Participated in special projects such as grant writing, exhibitions, and special events
              *	Built, maintained, and updated institutional website, taking advantage of new web technologies
        - title: Archives Processing Assistant
          company: State University of New York at Buffalo
          company_url: 'https://library.buffalo.edu/'
          company_logo: org-x
          location: New York
          date_start: '2007-10-01'
          date_end: '2010-01-01'
          description: |2-
            * Processed collections by surveying materials, identifying an organizational structure, arranging materials, conducting basic preservation work, and describing collections in finding aids
            *	Preserved several formats and objects including photographs, slides, microfilm, video cassettes, audio cassettes, phonographs, CD-ROMs, DVDs, artifacts, maps, and exhibit materials
            * Created finding aids and follow professional standards such as Describing Archives: A Content Standard (DACS)
            * Encoded finding aids into Encoded Archival Description (EAD) using XMetal and NoteTab, edit code and validate to local best practices and principals
            * Collaborated on an online digital collection of over 600 Love Canal images, including image selection, subject analysis, and metadata collection and input
            * Staffed Special Collections reference desk to assists researchers
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
          date_start: '2021-01-25'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Neural Networks and Deep Learning
          url: ''
        - certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2021-01-01'
          description: Formulated informed blockchain models, hypotheses, and use cases.
          organization: edX
          organization_url: https://www.edx.org
          title: Blockchain Fundamentals
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Object-Oriented Programming in R'
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
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
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
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: test@example.org
      phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
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
