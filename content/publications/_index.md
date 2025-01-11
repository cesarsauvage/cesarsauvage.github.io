---
title: Publications
#cms_exclude: true
type: landing

design:
  # Default section spacing
  spacing: "5px"

# # Optional header image (relative to `static/media/` folder).
# banner:
#   caption: ''
#   image: ''

sections:
#  - block: collection
#    content:
#      title: Submitted/In Review
#      filters:
#        folders:
#          - publications
#        publication_type: manuscript
#        exclude_featured: false
#    design:
#      view: citation
  - block: collection
    content:
      title: Journal Articles
      filters:
        folders:
          - publications
        publication_type: article-journal
        exclude_featured: false
      count: 100
    design:
      view: citation
  - block: collection
    content:
      title: White Paper
      text: ""
      filters:
        folders:
          - publications
        publication_type: report
        exclude_featured: false
    design:
      view: citation
  - block: collection
    content:
      title: Dissertation
      text: ""
      filters:
        folders:
          - publications
        publication_type: thesis
        exclude_featured: false
    design:
      view: citation
---
