---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

<link rel="icon" type="image/png" href="assets/media/icon.png"/>

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: publications
    content:
      title: Publications
      #text: |-
      #  {{% callout note %}}
      #  Quickly discover relevant content by [filtering publications](./publication/).
      #  {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '1'
      view: citation
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - talks
    design:
      columns: '2'
      view: compact
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Awards'
      id: awards
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
          date_end: ''
          date_start: '2020-10-15'
          description: ''
          organization: Ecole polytechnique
          organization_url: https://www.polytechnique.edu
          title: Research Centre prize (Prix du Centre de Recherche, Ecole polytechnique)
          url: 'https://portail.polytechnique.edu/hss/programmes/annee-3/stages-de-recherche'
    design:
      columns: '2'
#  - block: contact
#   id: contact
#    content:
#      title: Contact
#      subtitle:
#      text: |-
#        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
#       Contact (add or remove contact options as necessary)
      email: 
      phone: 
      appointment_url:
      address:
        street:
        city:
        region:
        postcode:
        country:
        country_code:
      directions:
      office_hours:
      contact_links:
        - icon:
          icon_pack: 
          name:
          link:
        - icon:
          icon_pack:
          name:
          link:
        - icon:
          icon_pack:
          name:
          link:
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
