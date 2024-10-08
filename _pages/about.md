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

I am currently a third-year Ph.D. candidate in Atmospheric Science at the Department of Earth System Science, Tsinghua University. I am in AI4Earth Laboratory and my advisor is Prof. [Xiaomeng Huang](http://faculty.dess.tsinghua.edu.cn/huangxiaomeng/en/index.htm). If you are interested in academic communication and cooperation with me, I am so willing to receive your emails at [xiongw21@mails.tsinghua.edu.cn](mailto:xiongw21@mails.tsinghua.edu.cn) or [wei.xiong@yale.edu](mailto:wei.xiong@yale.edu).

<!-- You can find my CV here: [Curriculum Vitae](./files/cv.pdf).-->

My research aims to solve partial differential equations to achieve modeling of the geophysical fluid dynamics by deep learning methods. I am mainly focused on the following research topics:
* **Operator Learning Theory**: Focusing on exploring how to combine universal approximation theorems with the physical theory of operators to design better operator learning methods and provide more numerical analyses.
* **Numerical Algorithm**: Enhancing numerical algorithms for solving partial differential equations by combining deep learning methods.
* **Geometry Deep Learning**: Focusing on exploring how to use geometric features of neural networks, combined with abstract algebra and differential geometry, to model physical variables with more physical inductive bias.
* **Geophysical Fluid Dynamics**: Focusing on real-world geophysical fluid modeling issues, including fluid simulation, weather forecasting, climate prediction and other related areas.

I also share some content about operator learning theory, numerical algorithms and high performance computing in [Zhihu](https://www.zhihu.com/people/Venney).

# 🔥 News
- *07/2024* &nbsp;🎉 1 [paper](https://www.researchgate.net/publication/381423520_Koopman_neural_operator_as_a_mesh-free_solver_of_non-linear_partial_differential_equations) was accepted to **Journal of Computational Physics**.
- *05/2024* &nbsp;🎉 1 [paper](https://doi.org/10.1145/3637528.3671779) was accepted to **KDD 2024**.
- *01/2024* &nbsp;🎉 1 paper was accepted to AI for Time Series (AI4TS) Workshop @ **AAAI 2024**.
- *12/2023* &nbsp;🎉 Oral presentation in AGU 2023 Fall Meeting @ **San Francisco, CA**.
- *12/2023* &nbsp;🎉 1 [paper](https://arxiv.org/abs/2312.08403) was accepted to **AAAI2024**.
- *09/2023* &nbsp;🎉 1 [paper](https://www.researchgate.net/publication/373888508_KoopmanLab_Machine_learning_for_solving_complex_physics_equations) was accepted to APL Machine Learning.
- *01/2023* &nbsp;🔥 We release [KoopmanLab](https://github.com/Koopman-Laboratory/KoopmanLab)(⭐️210+) scientific computing library.
- *11/2023* &nbsp;👏 Obtain Taihulight Scholarship from National Supercomputing Center in Wuxi.
- *04/2023* &nbsp;👏 Obtain Outstanding Presentation award in Artificial Intelligence Oceanography Forum.
- *12/2022* &nbsp;🎉 1 paper was accepted to Science Bulletin (IF = 18.9).
- *11/2021* &nbsp;🎉 1 [paper](https://www.sciencedirect.com/science/article/pii/S146350032100130X) was accepted to Ocean Modelling.


# 💻 Research Experience
<div style="display: flex; align-items: center;">
  <img src="../images/experience/Yale.png" alt="" style="width: 150px; margin-right: 10px; margin-left: 20px; "/>
  <ul style="list-style-type: disc; padding-left: 0px;">
    <li style="list-style-type: none;"> Department of Statistics and Data Science, Yale University </li>
    <li style="list-style-type: none;"><em>2024.08 - 2025.02</em>, <strong>Visiting Research in Assistant</strong></li>
    <li style="list-style-type: none;">mentored by <a href="https://lugroup.yale.edu/">Prof. Lu Lu</a></li>
  </ul>
</div>

<div style="display: flex; align-items: center;">
  <img src="../images/experience/wuxi.png" alt="" style="width: 150px; margin-right: 10px; margin-left: 20px; "/>
  <ul style="list-style-type: disc; padding-left: 0px;">
    <li style="list-style-type: none;">National Supercomputing Center in Wuxi (<a href="https://www.nsccwx.cn/">NSC</a>)</li>
    <li style="list-style-type: none;"><em>2020.06 - 2020.08</em>, <strong>Summer intern</strong></li>
    <li style="list-style-type: none;">mentored by <a href="http://faculty.dess.tsinghua.edu.cn/huangxiaomeng/en/index.htm">Prof. Xiaomeng Huang</a></li>
  </ul>
</div>

<div style="display: flex; align-items: center;">
  <img src="../images/experience/MEL.png" alt="" style="width: 150px; margin-right: 10px; margin-left: 20px; "/>
  <ul style="list-style-type: disc; padding-left: 0px;">
    <li style="list-style-type: none;">Carbon Biogeochemistry Group, the State Key Laboratory of Marine Environmental Science, Xiamen University</li>
    <li style="list-style-type: none;"><em>2019.06 - 2019.08</em>, <strong>Summer intern</strong></li>
    <li style="list-style-type: none;">mentored by <a href="https://dgo.xmu.edu.cn/info/1026/1100.htm">Prof. Guizhi Wang</a> </li>
  </ul>
</div>


# 📃 Publications 

#### &nbsp;&nbsp; Operator Learning Theory
- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``KDD 2024``</span> [Neural Manifold Operators for Learning the Evolution of Physical Dynamics](https://doi.org/10.1145/3637528.3671779). Hao Wu, Kangyu Weng, Shuyi Zhou, Xiaomeng Huang #, **Wei Xiong** #. Proceedings of the 30th ACM SIGKDD Conference on Knowledge Discovery and Data Mining
, 2024.
- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``Journal of Computational Physics``</span> [Koopman neural operator as a mesh-free solver of non-linear partial differential equations](https://doi.org/10.1016/j.jcp.2024.113194). **Wei Xiong**, Xiaomeng Huang, Ziyang Zhang, Ruixuan Deng, Pei Sun, Yang Tian. Journal of Computational Physics, 2024.
- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``APL Machine Learning``</span> [KoopmanLab: Machine learning for solving complex physics equations](https://www.researchgate.net/publication/366846352_KoopmanLab_machine_learning_for_solving_complex_physics_equations). **Wei Xiong**, Muyuan Ma, Xiaomeng Huang, Ziyang Zhang, Pei Sun, Yang Tian. APL Machine Learning, 2023.


#### &nbsp;&nbsp; Geophysical System Modeling
- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``ArXiv``</span> [AI-GOMS: Large AI-Driven Global Ocean Modeling System](https://arxiv.org/abs/2308.03152). **Wei Xiong** *, Yanfei Xiang *, Hao Wu, Shuyi Zhou, Yuze Sun, Muyuan Ma, Xiaomeng Huang. arXiv preprint arXiv:2308.03152, 2023.
- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``Science Bulletin``</span> [Super-resolution reconstruction of a 3 arc-second global DEM dataset](https://pubmed.ncbi.nlm.nih.gov/36604030/). Bo Zhang, **Wei Xiong**, Muyuan Ma, Mingqing Wang, Dong Wang, Xing Huang, Le Yu, Qiang Zhang, Hui Lu, Danfeng Hong, Fan Yu, Zidong Wang, Jie Wang, Xuelong Li, Peng Gong, Xiaomeng Huang. Science Bulletin, 2022.
- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``Ocean Modelling``</span> [MERF v3. 0, a highly computationally efficient non-hydrostatic ocean model with implicit parallelism: Algorithms and validation experiments](https://www.sciencedirect.com/science/article/pii/S146350032100130X). Qiang Tang, Xiaomeng Huang, Lei Lin, **Wei Xiong**, Dong Wang, Mingqing Wang, Xing Huang. Ocean Modelling, 2021.

#### &nbsp;&nbsp; Time Series Prediction
- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``AAAI 2024``</span> [Earthfarseer: Versatile Spatio-Temporal Dynamical Systems Modeling in One Model](https://arxiv.org/abs/2308.03152). Hao Wu, Shilong Wang, Yuxuan Liang, Zhengyang Zhou, Wei Huang, **Wei Xiong** #, Kun Wang #. Proceedings of the AAAI Conference on Artificial Intelligence (<b>AAAI</b>), 2024.
- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``ArXiv``</span> [PastNet: Introducing Physical Inductive Biases for Spatio-temporal Video Prediction](https://arxiv.org/abs/2305.11421). Hao Wu *, **Wei Xiong** *, Fan Xu, Xiao Luo, Chong Chen, Xian-Sheng Hua, Haixin Wang. arXiv preprint arXiv:2308.03152, 2023.

# ✨ Honors and Awards
- *2023.10* Taihulight Scholarship, National Supercomputing Center in Wuxi.
- *2023.04* Outstanding Presentation Award, Artificial Intelligence Oceanography Forum.
- *2021.06* Province-level Outstanding Graduate Student Award, Shandong Provincial Education Department.
- *2020.11* National Scholarship, Ministry of Education of the People's Republic of China.
- *2019.04* 2nd Place Award at ASC Student Supercomputer Challenge, Asian Supercomputing Association.
- *2019.11* National Scholarship, Ministry of Education of the People's Republic of China.
- *2019.04* 2st Place Award at the 10th National Mathematics Competition, Chinese Mathematical Society.
- *2019.04* 1st Place Award at the 9th Shandong Province Mathematics Competition, Shandong Mathematical Society.


# 🎓 Educations
- *2021.08 - present*, Tsinghua University.
- *2017.08 - 2021.06*, Ocean University of China.

# ⚓ Academic Services
Reviewer:
- ICLR 2025
- KDD 2024


# 😊 Miscellaneous
- ⛳️ I am a golf amateur.
- 🏀 I am very interested in basketball.
<br>
<br>
