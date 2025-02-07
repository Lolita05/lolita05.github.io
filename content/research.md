---
title: Research
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '1rem'

# Page sections
sections:
  - block: markdown
    content:
      title: 📚 Research
      subtitle: Experience
      text: |
        Here are a selection of papers that I have worked on. To see more, please visit my [ORCID](https://orcid.org/0000-0002-8224-7298).

  - block: collection
    content:
      title: Cancer Research
      text: Here is a list of my publications in cancer research.
      filters:
        folders:
          - cancer
    design:
      view: article-grid
      fill_image: false
      columns: 3

  - block: markdown
    content:
      title: Microbiome Research
      subtitle: Experience
      text: |
        Here are some of my publications in microbiome research.

  - block: collection
    content:
      title: About MTB
      text: |
        Here is a list of my publications in MTB
        <div style="text-align: center;">
          <img src="/images/mtb.jpg" alt="Teaching Photo" style="width:10cm; height:auto;" />
        </div>
      filters:
        folders:
          - mtb
    design:
      view: article-grid
      fill_image: false
      columns: 3
---
