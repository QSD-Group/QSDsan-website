---
layout: splash
permalink: /

features:
  - image_path: /images/index/integrated.png
    image_width: 25%
    alt: 'integrated'
    title: 'integrated'
    excerpt: 'QSDsan is an open-source platform that integrates system design, process modeling & simulation, techno-economic analysis & life cycle assessment (TEA-LCA).'
  - image_path: /images/index/under_uncertainty.png
    image_width: 25%
    alt: 'under uncertainty'
    title: 'under uncertainty'
    excerpt: 'Uncertainty can be easily incorporated into each of QSDsan’s interface to navigate across the vast opportunity space of numerous technology pathways.'
  - image_path: /images/index/with_visualization.png
    image_width: 25%
    alt: 'with visualization'
    title: 'with visualization'
    excerpt: 'Convenient visualization functions are built into QSDsan’s major classes and the statistical module for a quick grasp of the system and results.'

community_led:
  - image_path: /images/index/community_led.png
    alt: 'community-led'
    title: 'Open and Community-Led'
    excerpt: 'We strive to build QSDsan as an open and community-led platform with online documentation, topical tutorials (including video demonstrations), and transparent management with clear contribution guidelines.'
    url: 'https://github.com/QSD-Group/QSDsan'
    btn_label: 'Source Code'
    btn_class: 'btn--primary'

research:
  - image_path: /images/index/research.png
    alt: 'research'
    title: 'Research'
    excerpt: 'Learn more about how the QSDsan platform can be leveraged in quantitative sustainable design (QSD) to advance technology research, development, and deployment, as well as to navigate tradeoffs across dimensions of sustainability and technology-specific indicators of engineering performance.'
    url: '/research'
    btn_label: 'Learn More'
    btn_class: 'btn--primary'

learning:
  - image_path: /images/index/learning.png
    alt: 'learning'
    title: 'Learning'
    excerpt: 'To make the QSDsan platform more accessible to everyone, we have hosted "teaser" workshops with a simple system to go through the steps of QSD and how that can be executed using QSDsan.'
    url: '/learning'
    btn_label: 'Learn More'
    btn_class: 'btn--primary'
---

<img src='/images/index/splash.png' alt='QSDsan header'>

<br>
{% include feature_row id='features'%}

<br>
{% include feature_row id='community_led' type='left' %}

<br>
{% include feature_row id='research' type='left' %}

<br>
{% include feature_row id='learning' type='left' %}