---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

My academic research mainly falls in the area of understanding and developing the role of design in societal challanges of sustainablity. 

During early phases of my academic life, I was more interested in sustainable development specifically in the scope of rural areas. I have studied endegenous development theories, rural entrepreneurship, craft practice and business models during my Ph.D. research. I spent six months in India for identifying the outcomes social innovation and craft oriented development projects mainly held by NID; and used mapping tools for illustrating the impact of decades old design interventions. 

I am interested in sustainable product service systems as a research field but also we have developed an undergraduate course at Kadir Has Unviersity called "Strategic Design" which focuses on systemic urban interventions for sustainablity. 

In the scope of City and Children Studies, I am interested in design of public services, and development of inclusive tools for constructive design research. 

Recently my focus on sustainablity has shifted more into circular design and design for repair and upgrade. Specifically, I am interested in repair as a creative practice, DIY repair and its influence in product-user relationship, and brand identity. Moreover, I am interested in circualar business models employing repair and upgrade as an essential domain.


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
