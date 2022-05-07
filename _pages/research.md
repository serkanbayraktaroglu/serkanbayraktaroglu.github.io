---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

My academic research mainly falls in the area of understanding and developing the role of design in societal challanges of sustainablity.

In the early stages of my academic life, I was more interested in sustainable development, especially in rural areas. I believe that rural areas present both the most important challenges and opportunities for global sustainability. During my Ph.D. research, I studied endogenous development theories, rural entrepreneurship, craft practices and business models. The fieldwork of the research took about six months in India to examine seven cases illustrating the impact of design oriented development interventions, and I had the opportunity to take the guidance of valuable academics such as Prof. M.P.Ranjan from NID and Prof. Anil Gupta from IIM. The results of the case study research were threefold: (i) identifying the changing roles of design targeting sustainable development and social innovation, (ii) discussing the actor-based characteristics of rural innovation (iii) investigating the bridging roles of social innovations in rural development.

Since my early studies, I have been interested in sustainable product service systems as a research area. System analysis tools and the design of processes have always intrigued me. During industrial design studios, I guided many students to adopt PSS perspectives. We also developed an undergraduate course at Kadir Has University called "Strategic Design", which focuses on systemic urban interventions using PSS.

The City and Child studies curriculum was designed with the collaboration of national and international experts as a study field that combines issues of design, urban planning, political studies and psychology. Our aim was to explore transdisciplinary issues among these different disciplines, considering the needs of children and caregivers in the city. In this field of study, I am interested in design of public services,  examining social impacts of urban interventions, and developing methods and tools for participatory design processes involving children and caregivers.

In line with global research perspectives, my focus has shifted more towards the "circular economy" and "design for repair and upgrade". I am particularly interested in repair as a creative practice, DIY repair and its impact on the product-user relationship and brand identity. I'm also interested in circular business models having repair and upgrade as a business strategy. My colleague and I are currently working on two articles on this topic.

In addition to the field of sustainability, I am interested in the use of artificial intelligence and constructive design research approaches for qualitative research.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
