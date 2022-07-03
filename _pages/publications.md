---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

[Learning Minimal Representations with Model Invariance](https://openreview.net/pdf?id=v3LXWP63qOZ). **Manan Tomar**, Amy Zhang, Matthew E. Taylor. Pre-print.

[Learning Representations for Pixel-based Control: What Matters and Why?](https://arxiv.org/pdf/2111.07775.pdf). **Manan Tomar**\*, Utkarsh A. Mishra\*, Amy Zhang, Matthew E. Taylor. Pre-print; RLDM 2022.

[Model-Invariant State Abstractions for Model-based Reinforcement Learning](https://arxiv.org/pdf/2102.09850.pdf). **Manan Tomar**, Amy Zhang, Roberto Calandra, Matthew E. Taylor, Joelle Pineau. Pre-print; Spotlight at Sparsity in Neural Networks workshop.

[Mirror Descent Policy Optimization](https://arxiv.org/abs/2005.09814.pdf). **Manan Tomar**, Lior Shani, Yonathan Efroni, Mohammad Ghavamzadeh. ICLR 2022; Contributed talk at the DeepRL NeurIPS 2020 workshop.

[Multi-step Greedy Reinforcement Learning Algorithms](https://arxiv.org/abs/1910.02919.pdf). **Manan Tomar**\*, Yonathan Efroni\*, Mohammad Ghavamzadeh. ICML 2020.

[Successor Options : An Option Discovery Algorithm for Reinforcement Learning](https://arxiv.org/pdf/1905.05731.pdf). Rahul Ramesh\*, **Manan Tomar\***, Balaraman Ravindran. IJCAI 2019.

[MaMiC: Macro and Micro Curriculum for Robotic Reinforcement Learning](https://arxiv.org/pdf/1905.07193.pdf). **Manan Tomar**, Akhil Sathuluri, Balaraman Ravindran. AAMAS 2019.

{% comment %} 
## Other Projects

// [Multi-Agent Reinforcement Learning using Graph Neural Networks](https://drive.google.com/file/d/1VBZl4GTlL-Hwl2iL8p-EJkE1gv3RVt3R/view?usp=sharing). Rohan Saphal\*, Manan Tomar\*, Balaraman Ravindran. <em>Pre-print.</em>

// [A Survey on Successor Representation](https://drive.google.com/file/d/1RynGuSgBclTc7c-fJ2COtlHzybVvItWm/view?usp=sharing). Manan Tomar, Balaraman Ravindran. <em>Pre-print.</em>

// [Quantum Entanglement in Learning Representations](https://drive.google.com/file/d/1ePTa7dO9l3oNAEQAIgWk_QAklN3XMVQ3/view?usp=sharing). Ashish Kumar\*, Manan Tomar\*, Sutanu Chakraborti. <em>Pre-print.</em>
{% endcomment %}
