---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
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
          url: https://www.asanet.org/academic-professional-resources/2023-asa-ddrig-recipients/
        - certificate_url:
          date_end:
          date_start: '2023-08-01'
          description:
          organization: International Sociological Association
          organization_url: https://www.isa-sociology.org/en/research-networks/research-committees/rc28-social-stratification/
          title: RC 28 on Social Stratification and Mobility Student Travel Award
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
          title: Dissertation Year Fellowship
          url:
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Research
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
  - block: collection
    id: featured
    content:
      title: Publications
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
      title: Teaching
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  
---
