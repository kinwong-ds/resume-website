---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      name: Kin Wong
      summary: Data Scientist with 6+ years of experience in machine learning operations, NLP, and data analytics. Specializes in optimizing claim processing, transformer model tuning, and enhancing model accuracy to pro actionable business insights. Certified in Azure DP-100 and eager to leverage expertise in designing and implementing local and cloud-based AI solutions.
      location: Kirkland, WA
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Resume
        url: uploads/resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
  - block: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: skills
    content:
      title: Skills
      username: admin
  - block: awards
    content:
      title: Awards & Certifications
      username: admin
  # - block: languages
  #   content:
  #     title: Languages
  #     username: admin
---
