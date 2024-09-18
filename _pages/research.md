---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

## Research Interests

My research primarily focuses on the role of design in addressing societal challenges related to sustainability. Over the course of my academic career, I have explored various domains, including sustainable development, circular economy, design for repair, and the intersection of design and artificial intelligence. I am particularly interested in how design can foster sustainable transitions, both in urban contexts and rural areas, and how it can contribute to education for future sustainability challenges.

## Research Themes

### 1. Sustainability and Circular Economy
My early research centered on rural development and sustainability, particularly exploring craft practices, business models, and rural innovation. During my Ph.D., I conducted a six-month field study in rural India, guided by experts like Prof. M.P. Ranjan (NID) and Prof. Anil Gupta (IIM), investigating the impact of design interventions on rural development. The key findings highlighted the evolving role of design in social innovation and rural entrepreneurship.

More recently, my focus has shifted to the **circular economy** and the role of design for repair and upgrade. I’m particularly interested in how DIY repair can strengthen the product-user relationship and brand identity, and how circular business models can integrate repair as a value co-creation method.

- **Ongoing Project**: "Circular Design Awareness and Applications in the Furniture Industry" (2023 - Ongoing), Bilgi University (TR), Istanbul University (TR). This project explores opportunities and challenges for circular economy transition in Türkiye's furniture industry.

### 2. Design for Repair and Product Service Systems (PSS)
I have long been interested in sustainable Product Service Systems (PSS). In my teaching, I encourage students to adopt PSS thinking for sustainable design, and I’ve developed courses that focus on systemic urban interventions through PSS, including "Strategic Design" at Kadir Has University.

In my current research, I explore **design for repair** as a strategy for circular economy. This includes studying DIY repair practices and speculative design for future repair scenarios in collaboration with colleagues from Lucerne University.

- **Publication**: "Redefining Repair as a Value Co-Creation Process for Circular Economy: Facilitated Do-It-Yourself Repair" (International Journal of Design, 2024).

### 3. Rural Development and Social Innovation
In rural settings, I have studied the bridging role of design in social innovation and the potential for rural development through craft initiatives. My Ph.D. research in India highlighted the actor-based characteristics of rural innovation and the role of social innovation in sustainable development.

- **Supervision**: "Social Innovation Ecosystems in Sustainable Rural Development" (Ongoing Ph.D. project), Istanbul Technical University.

### 4. AI and Digital Methods in Design Research
I am also interested in how **artificial intelligence (AI)** can be integrated into design research and education. In 2024, I supervised a thesis on AI’s role in creative design processes, focusing on how AI tools intersect with design practices.

- **Thesis Supervision**: "Artificial Intelligence in the Creative Processes of Design" (MSc thesis, 2024), Istanbul University. Results from this research have been presented at conferences and are being prepared for publication.

### Ongoing Collaborations and Grants
I am actively engaged in international research projects and collaborations that explore urban sustainability transitions and the role of design in fostering eco-social innovation.

- **ENCODUS: Excellence in Eco-Social Design for Urban Sustainability Transition** (2023, Above Threshold). Horizon Europe Project with partners from Switzerland, Germany, and Italy.

### Future Research Directions
Looking ahead, I plan to deepen my research in the following areas:
- **Design for Circular Economy and Product-Service Systems**
- **Social Aspects of Sustainability Transitions in Urban Contexts**
- **Leveraging Design Education for Future Sustainability Challenges**

I continue to explore opportunities for participatory design processes, especially involving vulnerable user groups, and aim to incorporate emerging technologies like AI in design education and research.

![image](https://github.com/user-attachments/assets/338bb38f-17a3-4ec9-97ed-dbb4e0038882)


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
