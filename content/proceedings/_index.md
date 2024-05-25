---
title: Conference papers
cms_exclude: true

# View.
#   1 = List
#   2 = Compact
#   3 = Card
#   4 = Citation
view: 4

# Optional header image (relative to `static/media/` folder).
header:
  caption: ''
  image: ''

sections:
  - block: collection
    id: proceedings
    content:
      title: Conference papers
      #text: |-
      #  {{% callout note %}}
      #  Quickly discover relevant content by [filtering publications](./publication/).
      #  {{% /callout %}}
      filters:
        folders:
          - proceedings
        exclude_featured: true
    design:
      columns: '1'
      view: citation
---
