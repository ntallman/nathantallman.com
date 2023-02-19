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
      text:
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
              Currently the academic rank of Assistant Librarian.

        - title: Digital Content Strategist
          company: University of Cincinnati
          company_url: 'https://libraries.uc.edu/'
          company_logo:
          location: Cincinnati, Ohio
          date_start: '2014-01-01'
          date_end: '2017-01-01'
          description: |2-
            Earned the academic rank of Associate Librarian.
              * Facilitated a matrix team of library liaisons, archivists, records managers, technical librarians, repository developers, and other specialists (e.g., metadata, scholarly communication) in the planning, budgeting, strategy formation, and creation of digital content.
              * Coordinated or performed all aspects of digital collection workflows including the creation and organization of digital objects; metadata creation and assignment; collection building through both batch and online methods; and quality control measures.
              * Lead initiatives to design strategies, processes, workflows, content architectures, and standards for curating the digital content of faculty, staff, and students.
              * Worked with the repository development team and steering group to develop strategies for digital preservation of repository content and teamed with archivists and liaisons to integrate preservation strategies into the curation of digital content.
              * Coordinated and lead efforts to develop a digital preservation policy framework and lifecycle diagrams of licensed and library-owned digital content, leading to the creation of a digital preservation policy for all library material.
              * Partnered with special collections staff and managers of rare and unique library and archival collections, to plan and execute large scale digitization projects, including grant writing and fund raising.
              * Planed, implemented, and co-managed on-site digitization facilities, developed workflows and standards for such facilities, and lead efforts to create sustainability strategies.
              * Partnered with Digital Archivist/Records Manager to develop programs and provided support for digital forensics, website and social media archives, and archival information systems.
              * Consulted with, provided training for, and shared expertise with colleagues involved in digital content and digital repositories.
              * Participated in local, state and national digital library initiatives and committees, including formal partnerships with other institutions for the development of digital content.

        - title: Associate Archivist
          company: American Jewish Archives, Hebrew Union College-Jewish Institute of Religion
          company_url: 'https://www.americanjewisharchives.org/'
          company_logo:
          location: Cincinnati, Ohio
          date_start: '2010-02-01'
          date_end: '2013-12-01'
          description: |2-
              *	Arranged and described archival collections using professional standards (DACS, EAD) to ensure access by present and future users.
              *	Assisted onsite and remote researchers, answering reference questions to connect patrons with primary sources.
              *	Streamlined descriptive process through implementation of automated methods for creation of MARC records; EAD finding aids (including print and web derivatives); and labels for collection folders and boxes.
              *	Launched new online discovery layer, to replace outdated catalog, using open-source VuFind; integrating MARC records, institution website searching, and indexing of finding aids and digital objects.
              *	Designed local Microsoft Access databases for tracking Judaic conversions and publication requests.
              *	Implemented, configured, and managed Archivists Toolkit for collection management.
              *	Lead planning for digital collections and preservation, including accessioning, arrangement and description, and geo-redundant backup.
              *	Developed workflows, procedures, and documentation for digitization of collections.
              *	Participated in records management planning for parent institution and sister organizations.
              *	Participated in special projects such as grant writing, exhibitions, and special events.
              * Helped to design, maintain, and update institutional website.

        - title: Processing Assistant
          company: State University of New York at Buffalo
          company_url: 'https://library.buffalo.edu/'
          company_logo:
          location: Buffalo, New York
          date_start: '2007-10-01'
          date_end: '2010-01-01'
          description: |2-
            * Processed collections by surveying materials, identifying an organizational structure, arranging materials, conducting basic preservation work, and describing collections in finding aids.
            *	Preserved archival materials of several formats including photographs, slides, microfilm, video cassettes, audio cassettes, phonographs, CD-ROMs, DVDs, artifacts, maps, and exhibition materials.
            * Created finding aids using professional standards such as Describing Archives: A Content Standard (DACS)
            * Encoded finding aids into Encoded Archival Description (EAD) using XMetal and NoteTab, edit code and validate to local best practices and principals
            * Collaborated to build a digital collection of archival imags of the Love Canal environmental disaster, including selection, subject analysis, and metadata creation.
            * Provided reference service to patrons in the Special Collections reading room and remote researchers.
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
      #buttons:
      #  - name: All
      #    tag: '*'
      #  - name: Sustainability
      #    tag: sustainability
      #  - name: Appraisal
      #    tag: appraisal
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
      title: Recent & Upcoming Talks
      filters:
        folders:
          - talks
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