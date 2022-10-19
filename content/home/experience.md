---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Research Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Fellow
    company: Autonomous Networks Research Group
    company_url: 'https://anrg.usc.edu/www/'
    company_logo: anrg
    location: Los Angeles, CA
    date_start: '2021-01-01'
    date_end: ''
    description: |2-
        * Advisor: Bhaskar Krishnamachari
        * Adopted deep Q-learning to train an agent to learn the most efficient and precise policy network for active information gathering in HRI

  - title: Research Fellow
    company: The Robotics Institute
    company_url: 'https://www.ri.cmu.edu/'
    company_logo: ri
    location: California
    date_start: '2016-01-01'
    date_end: '2020-12-31'
    description: |2-
        * Advisor: John M. Dolan
        * Devised a theoretic framework that empowers autonomous agent to probe a human agent to clarify its belief on human’s underlying model by optimizing the Jensen-Shannon Divergence on its belief
        * Identified two use cases in autonomous driving where autonmous vehicle leverages the probed information to influence human vehicles to create better participant experience and system efficiency
        * Submitted paper to 2023 IEEE ICRA (Preprint, Research Poster)

  
  - title: Research Fellow
    company: Autonomous Networks Research Group
    company_url: 'https://anrg.usc.edu/www/'
    company_logo: anrg
    location: California
    date_start: '2016-01-01'
    date_end: '2020-12-31'
    description: |2-
        * Advisor: Bhaskar Krishnamachari
        * Devised a polynomial-time DP-based algorithm that solves the optimal trading policy under dynamic AMMs that performs drastically better than baseline algorithms like the exhaustive search or the Lagrange multiplier
        * Presented the paper at 2022 IEEE ICBC and answered questions from peers (Conference Paper, Presentation Video)

design:
  columns: '2'
---
