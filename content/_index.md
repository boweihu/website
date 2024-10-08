---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Welcome
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Recent Awards & Grants'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url:
          date_end: '2024-06-30'
          date_start: '2023-07-01'
          description:
          organization: American Sociological Association
          organization_url: https://www.asanet.org
          title: ASA Doctoral Dissertation Research Improvement Grant
          url: https://www.asanet.org/academic-professional-resources/asa-grants-and-fellowships/asa-doctoral-dissertation-research-improvement-grants-asa-ddrig
        - certificate_url:
          date_end:
          date_start: '2023-08-01'
          description:
          organization: International Sociological Association
          organization_url: https://www.isa-sociology.org/en/research-networks/research-committees/rc28-social-stratification/
          title: ISA RC 28 on Social Stratification and Mobility Student Travel Award
          url:
        - certificate_url:
          date_end: 
          date_start: '2023-07-01'
          description: 
          organization: Society for the Advancement of Socio-Economics
          organization_url: https://sase.org
          title: SASE Early Career Workshop Award
          url: 
        - certificate_url:
          date_end: '2024-07-31'
          date_start: '2023-08-01'
          description: 
          organization: National Science and Technology Council, Taiwan 
          organization_url: https://www.nstc.gov.tw/?l=en
          title: Taiwanese Overseas Pioneers Grant
          url:
        - certificate_url:
          date_end: '2024-07-31'
          date_start: '2023-08-01'
          description: 
          organization: University of California, Los Angeles
          organization_url: https://www.ucla.edu
          title: UCLA Dissertation Year Fellowship
          url:
        - certificate_url:
          date_end: 
          date_start: '2023-11-01'
          description: 
          organization: International Journal of Taiwan Studies
          organization_url: https://eats-taiwan.eu/international-journal-of-taiwan-studies/
          title: IJTS Open Access Award
          url:
        - certificate_url:
          date_end: 
          date_start: '2024-06-02'
          description: 
          organization: ASA Section on Economic Sociology
          organization_url: https://www.asanet.org/asa_sections/economic-sociology
          title: Ronald Burt Student Paper Award Honorable Mention
          url:
        - certificate_url:
          date_end: 
          date_start: '2024-06-01'
          description: 
          organization: ASA Section on Sociology of Consumers and Consumption
          organization_url: https://www.asanet.org/asa_sections/sociology-of-consumers-and-consumption
          title: Consumers and Consumption Student Paper Award 
    design:
      columns: '2'
  - block: portfolio
    id: research
    content:
      title: Research Projects
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
        - name: Household Debt
          tag: Household Debt
        - name: Venture Capital
          tag: Venture Capital
        - name: Global Taiwan Studies
          tag: Global Taiwan
        - name: All
          tag: '*'
       # - name: Market Structure
       #   tag: Market Structure
       # - name: Taiwanese Firms
       #   tag: Taiwanese Firms
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: True
    
#  - block: collection
#    id: publication
#    content:
#      title: Publications
#      text: |-
#        {{% callout note %}}
#        Quickly discover relevant content by [filtering publications](./publication/).
#        {{% /callout %}}
#      filters:
#        folders:
#          - publication
#        exclude_featured: true
#    design:
#      columns: '2'
#      view: citation
    
 # - block: collection
 #   id: teaching
 #   content:
 #     title: Teaching
 #     filters:
 #       folders:
 #         - event
 #   design:
 #     columns: '2'
 #     view: compact
  
---
