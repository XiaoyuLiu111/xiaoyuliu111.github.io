---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I'm a Ph.D. student at Simon Fraser University, advised by [Yuepeng Wang](https://www.cs.sfu.ca/~yuepeng/). My research interests lie in automated reasoning for program synthesis and verification problems in graph and vector databases. Currently, I am especially interested in how formal methods can be used to verify and reason about performance and security properties in database systems. I am also keen to explore robustness and security challenges in AI agents. ⚡️⚡️ Looking for internships as Research Scientist or Research Engineer in 2027. 


# 📖 Educations
- *2024.01 - present, Ph.D. in Computing Science, Simon Fraser University 
- *2020.09 - 2022.06*, Master of Science in Data Science, UW-Madison
- *2016.09 - 2020.06*, Bachelor of Science in Statistics, Hunan University

# 💻 Work Experience
- *2023.11 - 2024.01 (Left role for Ph.D. studies)*, Software Engineer, TikTok
- *2022.01 - 2023.08*, Software Engineer, DataChat 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/wkfl' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Synthesizing graph queries from user demonstrations (OOPSLA 2026)]()

**Xiaoyu Liu**, Qikang Liu, Evan Dyce, Yuepeng Wang

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- Writing graph queries is challenging for non-experts due to the complexity of graph data models and the need to identify proper graph patterns. While recent research has advanced query synthesis for relational and document databases, the problem of synthesizing graph queries remains under-explored. We present a novel approach for synthesizing graph queries from computation demonstrations, where users specify the desired output through expressions over properties of input graphs. Our method addresses the challenge of inferring meaningful graph patterns for matching and efficiently constructing the remaining components of the query. Specifically, we combine graph mining, which identifies candidate patterns across input graphs, with deduction-based pruning, which guides an efficient synthesis of the filtering predicate and return clause. We have implemented our approach in a tool called DMiner and evaluated it on 90 benchmarks. Experimental results show that DMiner successfully synthesizes desired queries for 87 benchmarks, with an average synthesis time of 0.6 seconds per query. This outperforms both enumerative search and LLM baselines. We also conducted a user study, which shows that users can provide demonstrations with modest effort and 87.5% of the provided demonstrations are sufficient for DMiner to synthesize the desired query.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/biostat.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Single-cell network biology characterizes cell-type gene regulation for drug repurposing and phenotype prediction in Alzheimer's disease](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1010287)

Chirag Gupta, Jielin Xu, Ting Jin, Saniya Khullar, **Xiaoyu Liu**, Sayali Alatkar, Feixiong Cheng, Daifeng Wang

</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->


# 💬 Blogs
- Out Soon! 🔥 
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
