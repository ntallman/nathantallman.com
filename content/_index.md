---
# Leave the homepage title empty to use the site title
title:
date: 2023-02-19
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text: |2-
        Nathan Tallman is Digital Preservation Librarian at Penn State University. His research interests include distributed infrastructure, cloud computing, and appraisal and selection. He leads the digital preservation program at Penn State University Libraries. Interests. Education?

  - block: experience
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: Digital Preservation Librarian
          company: Penn State University
          company_url: 'https://libraries.psu.edu/'
          company_logo:
          location: University Park, Pennsylvania
          date_start: '2017-02-01'
          date_end: ''
          description: |2-
              Academic rank of Assistant Librarian. Responsibilities include:
              * Analyzing
              * Modelling
              * Deploying
        - title: Digital Content Strategist
          company: University of Cincinnati
          company_url: 'https://libraries.uc.edu/'
          company_logo:
          location: Cincinnati, Ohio
          date_start: '2014-01-01'
          date_end: '2017-01-01'
          description: |2-
              Academic rank of Associate Librarian.
        - title: Associate Archivist
          company: American Jewish Archives
          company_url: 'https://www.americanjewisharchives.org/'
          company_logo:
          location: Cincinnati, Ohio
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
          company_logo:
          location: Buffalo, New York
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
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - projects
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
        - name: Sustainability
          tag: sustainability
        - name: Appraisal
          tag: appraisal
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Presentations
      filters:
        folders:
          - presentations
    design:
      columns: '2'
      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text:
      email: ntt7@psu.edu
      phone: 814-865-0860
      appointment_url: 'https://outlook.office.com/bookwithme/user/5dac012c04834c74a229fc574bc93cff@psu.edu?anonymous&ep=plink'
      address:
        street: 402 Central Pattee Library
        city: University Park
        region: PA
        postcode: '16866'
        country: United States
        country_code: US
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---