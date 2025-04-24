---
title: "Publications"
summary: "Peer-reviewed research and preprints"
type: landing

design:
  spacing: "6rem"

sections:
  - block: markdown
    content:
      title: "Selected Research"
      text: |-
        Below is a selection of my published and preprint work. For a full list of papers, see my [Google Scholar](https://scholar.google.com/citations?user=zwUZP5cAAAAJ) profile.
    design:
      columns: "1"

  - block: collection
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: All Publications
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
---