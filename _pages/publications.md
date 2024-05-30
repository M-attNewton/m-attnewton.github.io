---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">Full links to my publications are available on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

Conference papers

O. Gates, M. Newton and K. Gatsis, “Scalable Forward Reachability Analysis of Multi-Agent Systems with Neural Network Controllers,” 2023 62nd IEEE Conference on Decision and Control (CDC), Singapore, Singapore, 2023.

M. Newton and A. Papachristodoulou, “Stability of Non-linear Neural Feedback Loops using Sum of Squares,” 2022 61st IEEE Conference on Decision and Control (CDC), Cancun, Mexico, 2022.

M. Newton and A. Papachristodoulou, “Reachability Analysis of Neural Feedback Loops using Sparse Polynomial Optimisation,” 2022 61st IEEE Conference on Decision and Control (CDC), Cancun, Mexico, 2022.

M. Newton and A. Papachristodoulou, “Neural Network Verification using Polynomial Optimisation,” 2021 60th IEEE Conference on Decision and Control (CDC), Austin, Texas, 2021.

M. Newton and A. Papachristodoulou, “Exploiting Sparsity for Neural Network Verification,” 3rd Annual Learning for Dynamics and Control Conference (L4DC), Zurich, Switzerland, 2021.

M. Newton and A. Papachristodoulou, “Network Lyapunov Functions for Epidemic Models," 2020 59th IEEE Conference on Decision and Control (CDC), Jeju, Korea (South), 2020.

Journal papers

M. Newton and A. Papachristodoulou, “Sparse Polynomial Optimisation for Neural Network Verification", Automatica, 157, 2023.

M. Newton and A. Papachristodoulou, “Rational Neural Network Controllers", arXiv preprint arXiv:2307.06287, 2023.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
