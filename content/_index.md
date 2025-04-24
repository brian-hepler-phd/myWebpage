---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Resume
        url: uploads/Brian_Hepler_Resume_DS.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: endless-constellation.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'My Research'
      subtitle: ''
      text: |-
        I’m a research mathematician and educator with 13+ years of experience working at the intersection of abstract theory and practical computation. My expertise lies in **relational structures, category theory, and topological methods**, and I specialize in translating these concepts into **efficient data models, algorithms**, and **mathematical infrastructure for machine learning and quantum computing**.

        I’ve published 5 peer-reviewed research articles and presented at over 20 international conferences. I’m actively building on my mathematical background to develop tools and frameworks that bridge theory and practice, with applications in machine learning, quantum computing, and data science.

        I’ve also taught university-level mathematics for more than a decade, most recently designing and delivering a course on ["Lie Groups with Applications"](https://quantumformalism.academy/lie-groups-with-applications) through Quantum Formalism Academy.

        From 2023–2024, I was a postdoctoral researcher in the algebraic analysis group at **IMJ-PRG (Sorbonne Université)**, working with François Loeser on the **FSMP-funded** project *Condensed Mathematics, Ind-Sheaves, and Irregular Singularities*. Before that, I held research appointments at **UW–Madison**, including a Van Vleck Visiting Assistant Professorship and a later honorary fellowship, collaborating with Laurentiu Maxim in **geometry and topology**.

        I earned my Ph.D. from **Northeastern University** in 2019 under David B. Massey, with a dissertation on some invariants of complex analytic singularities titled *Hypersurface Normalizations and Numerical Invariants*. You can learn more on my [Experience](/content/experience.md) page.
    design:
      columns: '1'
---