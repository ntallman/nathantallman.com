---
# Leave the homepage title empty to use the site title
title: Nathan Tallman
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
        - title: Digital Preservation Librarian, Assistant Librarian
          company: Penn State University
          company_url: 'https://libraries.psu.edu/'
          company_logo:
          location: University Park, Pennsylvania
          date_start: '2017-02-01'
          date_end: ''
          description: |2-
              * Leads development of an effective and achievable strategy to create a cohesive digital preservation program.
              * Responsible for infrastructure planning; the design, implementation, and management of policies, practices, and workflows; for the long-term protection of, and access to, digital materials created and acquired by University Libraries.
              * Represents Penn State University in digital preservation networks and consortia, such as the Academic Preservation Trust, MetaArchive Cooperative, and the Big Ten Academic Alliance.
              * Serves as resource expert in digital content management, establishes and improves workflows, seeks to integrate systems, and bring efficiencies to repository management.
              * Supervises professional staff supporting the digital preservation program.

        - title: Digital Content Strategist, Associate Librarian
          company: University of Cincinnati
          company_url: 'https://libraries.uc.edu/'
          company_logo:
          location: Cincinnati, Ohio
          date_start: '2014-01-01'
          date_end: '2017-01-01'
          description: |2-
              * Facilitated a matrix team of library liaisons, archivists, records managers, technical librarians, repository developers, and other specialists (e.g., metadata, scholarly communication) in the planning, budgeting, strategy formation, and creation of digital content. Planed, implemented, and co-managed on-site digitization facilities.
              * Coordinated or performed all aspects of digital collection workflows including the creation and organization of digital objects; metadata creation and assignment; collection building through both batch and online methods; and quality control measures.
              * Lead efforts to develop a digital preservation policy framework and lifecycle diagrams of licensed and library-owned digital content, leading to the creation of a digital preservation policy for all library material.
              * Partnered with special collections staff and managers of rare and unique library and archival collections, to plan and execute large scale digitization projects, including grant writing and fund raising.

        - title: Associate Archivist
          company: American Jewish Archives, Hebrew Union College-Jewish Institute of Religion
          company_url: 'https://www.americanjewisharchives.org/'
          company_logo:
          location: Cincinnati, Ohio
          date_start: '2010-02-01'
          date_end: '2013-12-01'
          description: |2-
              *	Arranged and described archival collections using professional standards (DACS, EAD) to ensure access by present and future users. Implemented, configured, and managed Archivists Toolkit for collection management.
              *	Streamlined descriptive process through implementation of automated methods for creation of MARC records; EAD finding aids (including print and web derivatives); and labels for collection folders and boxes.
              *	Built online discovery layer using open-source VuFind for searching online catalog, website, finding aids, and digital objects.
              *	Coordinated management of digital collections and their preservation by developing workflows, procedures, and documentation.

        - title: Processing Assistant
          company: State University of New York at Buffalo
          company_url: 'https://library.buffalo.edu/'
          company_logo:
          location: Buffalo, New York
          date_start: '2007-10-01'
          date_end: '2010-01-01'
          description: |2-
            * Processed collections by surveying materials, identifying an organizational structure, arranging materials, conducting basic preservation work, and describing collections in finding aids.
            * Created finding aids using professional standards such as Describing Archives: A Content Standard (DACS) and encoded finding aids into Encoded Archival Description (EAD).
            * Collaborated to build a digital collection of archival images of the Love Canal environmental disaster, including selection, subject analysis, and metadata creation.
            * Provided reference service to patrons in the Special Collections reading room and remote researchers.
    design:
      columns: '2'
  - block: collection
    id: research
    content:
      title: Research
      filters:
        folders:
          - research
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Recent Publications
      count: 2
      filters:
        folders:
          - publications
    design:
      columns: '2'
      view: card
  - block: collection
    id: talks
    content:
      title: Recent Talks
      count: 2
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
