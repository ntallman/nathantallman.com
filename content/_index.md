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
        - title: Executive Director of Academic Preservation Trust at University of Virginia
          company: Academic Preservation Trust
          company_url: 'https://aptrust.org/'
          location: Charlottesville, Virginia
          date_start: '2024-01-01'
          description: |2-
              * Articulation of a vision and execution of strategic management for a community-owned distributed digital preservation service.
              * Development of strategies to achieve APTrust’s vision, with regular assessment of outcomes to assure the long-term financial and operational health of the enterprise.
              * Effective management of projects and staff, augmented by contributors from member institutions and consulting entities when needed.
              * Evaluation of service proposals, design of fee structures to support them, and provision of regular status and financial reports to the Board.
              * Regular engagement with Sustaining Members and other interested parties, and exploration of collaborations with related entities such as the Digital Preservation Coalition, the National Digital Stewardship Alliance, and the Digital Preservation Services Collaborative.
              * Coordination of the consortium’s activity in digital preservation research that aligns with APTrust’s mission and is financially prudent.
              * Operational oversight of APTrust preservation-repository operations, including the development of plans and processes for the lifecycle of deposited content and the integration of digital preservation processes at existing and prospective APTrust member institutions.

        - title: Digital Preservation Librarian, Associate Librarian
          company: Penn State University
          company_url: 'https://libraries.psu.edu/'
          company_logo:
          location: University Park, Pennsylvania
          date_start: '2017-02-01'
          date_end: '2023-12-31'
          description: |2-
              * Lead development of an effective and achievable strategy to create a cohesive digital preservation program.
              * Responsible for infrastructure planning; the design, implementation, and management of policies, practices, and workflows; for the long-term protection of, and access to, digital materials created and acquired by University Libraries.
              * Represented Penn State University in digital preservation networks and consortia, such as the Academic Preservation Trust, MetaArchive Cooperative, and the Big Ten Academic Alliance.
              * Served as resource expert in digital content management, establishes and improves workflows, seeks to integrate systems, and bring efficiencies to repository management.
              * Supervised professional staff supporting the digital preservation program.

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
      email: nathan.tallman@aptrust.org
      phone: 434-924-4582
      appointment_url: 'https://scheduler.zoom.us/ntallman'
      autolink: true
    design:
      columns: '2'
---
