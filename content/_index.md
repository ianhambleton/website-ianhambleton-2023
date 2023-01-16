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

  - block: markdown
    id: cv
    content:
      title: Download
      subtitle: Two CV flavours, long and short
      text: '{{< table path="cv-download.csv" header="true" caption="false" caption="" >}}'
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'

  - block: experience
    id: experience
    content:
      title: Employment and Committee Work
      subtitle: The University Appointments...
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Professor of Biostatistics and Informatics
          company: The University of the West Indies
          company_url: 'https://cavehill.uwi.edu/'
          company_logo: 
          location: Barbados, West Indies
          date_start: '2010-01-01'
          date_end: ''
          description: |2-
              Head, Data Group. Data handling for, and analysis of population surveys, longitudinal health cohorts, and clinical trials. National disease registries in cancer, stroke, cardiovascular disease, and diabetes. Statistical advisor to PAHO, EU, UNICEF, Barbados Government, CARPHA, CDEMA, regional NGOs involved in health and wellness.

        - title: Senior Lecturer in Biostatistics
          company: The University of the West Indies
          company_url: 'https://cavehill.uwi.edu/'
          company_logo: 
          location: Barbados, West Indies
          date_start: '2006-01-01'
          date_end: '2010-01-01'
          description: |2-
              Data Management and analysis of Clinical Trials, Population Surveys and Epidemiological studies. National disease registries in cancer, stroke, and cardiovascular disease. National risk factor health surveys. Advisor to PAHO, EU, Barbados Government, other regional NGO involved in health.

        - title: Clinical Trials Statistician
          company: London School of Hygiene and Tropical Medicine
          company_url: 'https://www.lshtm.ac.uk/'
          company_logo: 
          location: Mwanza, Tanzania
          date_start: '2005-01-01'
          date_end: '2006-01-01'
          description: |2-
              Study management, data management and statistical analysis of two double-blind, randomised clinical trials of HIV interventions in women (1) Aciclovir for HSV-2 infection for HIV prevention (2) Microbicide gel for HIV prevention.

        - title: Senior Lecturer in Biostatistics
          company: The University of the West Indies
          company_url: 'https://mona.uwi.edu/'
          company_logo: 
          location: Kingston, Jamaica
          date_start: '2002-01-01'
          date_end: '2005-01-01'
          description: |2-
              Analyses of ongoing studies, teaching, consultancy. Development of Masters programme in Biostatistics. Managing the activities of the TMRI Statistics Group (Jamaica and Barbados).

        - title: MRC Scientist - statistician
          company: UK Medical Research Council Laboratories (Jamaica), The Jamaican Sickle Cell Unit
          company_url: 'https://mrc.ukri.org/'
          company_logo: 
          location: Kingston, Jamaica
          date_start: '1996-08-01'
          date_end: '2002-01-01'
          description: |2-
              Statistical analysis of all Unit research. Statistical consultancy. Teaching of statistical software. MRC-funded cohort study analytics using the Jamaican Sickle Cell Disease Cohort Study. Development of guidelines for good practice when analysing observational sickle-cell disease data.

        - title: Lecturer in Medical Statistics
          company: Charing Cross Medical School, Department of Public Health and Primary Care
          company_url: 'https://cavehill.uwi.edu/'
          company_logo: 
          location: London, UK
          date_start: '1995-08-01'
          date_end: '1996-07-01'
          description: |2-
              Statistical consultancy. Analysis of major funded projects. Teaching of statistical techniques and software.
    design:
      columns: '2'


  - block: accomplishments
    id: committees
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: Employment and Committee Work
      subtitle: The Committee Appointments...
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: 
          date_end: ''
          date_start: '2018-01-01'
          description: |2-
            Yale-TCC operates an adult and child cohort in 4 Eatern Caribbean territories (Barbados, Puerto Rico, Trinidad and Tobago, USVI). This group provides advice and support for the dissemination of research results to Caribbean stakeholders.'
          organization: Yale University
          organization_url: https://medicine.yale.edu/intmed/genmed/tcc/
          title: Chair, Yale-TCC Data Sharing Working Group (Ongoing).
          url: ''


        - certificate_url: 
          date_end: ''
          date_start: '2017-01-01'
          description: |2-
            Funded initially by a Wellcome Trust Centre for Global Health Research, the Cohorts Consortium of Latin American and the Caribbean (CC_LAC) is a regional data pooling project to examine the association between cardio-metabolic risk factors (e.g. blood pressure, glucose and lipids) and non-fatal and fatal cardiovascular outcomes (e.g. stroke or myocardial infarction).
          organization: Imperial College, Global Environmental Health
          organization_url: http://globalenvhealth.org/
          title: Steering Committee Member, Cohorts Collaboration of Latin America and the Caribbean (Ongoing).
          url: 

        - certificate_url: 
          date_end: '2019-01-01'
          date_start: '2017-01-01'
          title: 'Member of technical advisory committee for the development of methods to analyze mortality in the presence of small numbers.'
          description: |2-
            The committee has supported the development of materials to guide analysts in the Small Island Developing States (SIDS), where small numbers of health events often limit the analytic options available.
          organization: Pan-American Health Organization
          organization_url: https://paho.org/
          url: ''

        - certificate_url: 
          date_end: '2017-01-01'
          date_start: '2015-01-01'
          title: 'Analytics and training on measuring inequality across the SDGs.'
          description: |2-
            Approved statistician for provision of statistical support to UNICEF research output.
          organization: United Nations Children's Fund (UNICEF)
          organization_url: https://unicef.org/
          url: ''

        - certificate_url: 
          date_end: '2019-01-01'
          date_start: '2012-01-01'
          title: 'Committee member for the Diabetes Atlas.'
          description: |2-
            Contributed to diabetes Atlas (6th / 7th / 8th editions). Included focus on methodology for prevalence rate sensitivity analyses.
          organization: International Diabetes Federation (IDF)
          organization_url: https://idf.org/
          url: ''

        - certificate_url: 
          date_end: ''
          date_start: '2011-01-01'
          title: 'HIV/AIDS National Surveillance reporting (Ongoing).'
          description: |2-
            Statistical Support and member of writing committee for the analysis & production of the annual Barbados HIV/AIDS Surveillance Report.
          organization: Ministry of Health and Wellness (MOHW), Government of Barbados
          organization_url: https://www.gov.bb/ministries/health
          url: ''
          
        - certificate_url: 
          date_end: ''
          date_start: '2010-01-01'
          title: 'Barbados National Ethics Committee (Joint UWI / MOHW committee) (Ongoing).'
          description: |2-
            Member of University of the West Indies / Ministry of Health Institutional Review Board (Ethics Board) for the review of research involving human subjects.
          organization: The University of the West Indies (UWI)
          organization_url: https://www.cavehill.uwi.edu
          url: ''
          
        - certificate_url: 
          date_end: ''
          date_start: '2009-01-01'
          title: 'Statistical Editor, Cystic Fibrosis and Genetic Disorders Group (CFGD) (Ongoing)'
          description: |2-
            Appointed statistical editor with the Cochrane Collaboration (Cystic Fibrosis and Genetic Disorders Group). Full editorial duties for this global network for systematic reviews of randomised clinical trials. Also provide haemoglobinopathy editorial support as required.
          organization: The Cochrane Collaboration
          organization_url: https://www.cochrane.org
          url: 'https://cfgd.cochrane.org/'
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
        - name: Current
          tag: current project
        - name: Completed
          tag: completed project
        - name: Analytics
          tag: analytics
        - name: Data handling
          tag: data handling
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false



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
      view: compact


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


  - block: contact
    id: contact
    content:
      title: Contact Me
      subtitle:
      text: |-
        Email me using the form below. Give me a day to get back to you.
      # Contact (add or remove contact options as necessary)
      email: ian.hambleton@cavehill.uwi.edu
      appointment_url: ''
      contact_links:
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
    # Automatically link email and phone or display them just as text?
      autolink: true
      # Choose an email form provider (netlify/formspree)
      form:
        provider: netlify
        formspree:
          # If using Formspree, enter your Formspree form ID
          id: ''
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
      # Coordinates to display a map - set your map provider in `params.yaml`
      coordinates:
        latitude: '37.4275'
        longitude: '-122.1697'
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
---
