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

🔥**Welcome to My Page!**🔥
I am currently a Final-Year undergraduate student in Robotics Engineering at the [College of Mechanical and Electrical Engineering](https://mech.buct.edu.cn/en_mech/main.htm), Beijing University of Chemical Technology (BUCT). My research interests include soft robots, robot navigation, robot learning, medical mechatronics, and healthcare robots.

<img src="images/my.jpg" alt="sym" width="50%" style="display: block; margin: 0 auto;">


# 🔥 News
- *2023.01*: &nbsp;🎉🎉 After my summer internship, I'm working as Research Assistant supervised by Prof. Hongliang Ren in CUHK-SZRI!
- *2022.10*: &nbsp;🎉🎉 After my summer internship, one of my co-first authored papers has been finally submitted to a top-tier IEEE Transactions Journal and is currently under review!
- *2022.05*: &nbsp;🎉🎉 Won the Third Prize at [ICRA2022 RoboMaster University Sim2Real Challenge](https://air.tsinghua.edu.cn/robomaster/sim2real_icra22.html)!
- *2022.05*: &nbsp;🎉🎉 Won the Meritorious Award at [2022 Mathematical Contest in Modeling (MCM2022)](https://www.comap.com/contests/mcm-icm)!

# 📝 Ongoing Project


<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">CAD</div><img src='images/ONE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-image'><div><div class="badge">Real Machine</div><img src='images/onecable.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-image'><div><div class="badge">SOFA Simulation</div><img src='images/onesim.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**OneCable Continuum Robot Project**


- Using only one cable to achieve 3 motions: Pushing, Pulling and Twisting
- Will submit to a top-tier journal!
</div>
</div>



# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE-TII 1st Round Review</div><img src='images/sim2.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Sim-to-Real Method for Soft Robotic Navigation (To be Revealed)**

J. Lai, **T.-A. Ren (Co-first author)**, W. Yue, S. Su, J. Y. K. Chan, and H. Ren

- Medical scene 3D reconstruction in [SOFA Framework](https://www.sofa-framework.org/)
- Soft robot modeling and navigation with [SOFTROBOTS plugin](https://project.inria.fr/softrobot/)
- Closed-loop soft robot navigation with that **learns** from the virtual eye-in-hand vision
- [Supply Video](https://youtu.be/vQ4xzFM9iwk)
<!-- [Preprint](https://arxiv.org/abs/2206.11804) \| [Demo](https://github.com/lofrienger/Single_SurgicalScene_For_Segmentation) -->

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/domain.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Domain Adaptive Sim-to-Real Segmentation of Oropharyngeal Organs**

Guankun Wang, **Tian-Ao Ren**, Jiewen Lai, Long Bai, and Hongliang Ren

- Contribute the simulation data and test the performance

</div>
</div>

# 💬 Projects
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Cruising</div><img src='images/crusing.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Floor Cruising with Dynamic Obstacle Avoidance**
- Maximum speed of 2 m/s
- TEB algorithm for local planning
- Multi-sensor fusion positioning to increase localization accuracy
- [Supply Video](https://youtu.be/cD4d4wI3bkI)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Sim2Real</div><img src='images/rm.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[ICRA2022 RoboMaster University Sim2Real Challenge](https://air.tsinghua.edu.cn/robomaster/sim2real_icra22.html)**
- Team *777* - on behalf of Beijing University of Chemical Technology (Third Prize)
- Use VINS-Mono location algorithm
- D435 + IMU mode to improve motion tracking performance and make up gaps in illumination changes
- [Supply Video](https://youtu.be/BxEthzIn8SQ)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SwarmingRobot</div><img src='images/muliti.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Swarming Robot Navigation: Sim2Real Transfer**
- Migrated multi-machine cooperative operation composite robot model in IsaacSIM
- High stability and obstacle avoidance ability
- [Supply Video](https://youtu.be/3UGTcBENg5Y)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Robotics Arm</div><img src='images/arm.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Sim2Real Transfer of ARX-5s robot (a 6-DOF robotic arm)**
- [Supply Video](https://youtu.be/jVsMxDsDUM4)
- [Robotics Arm Dancing](https://www.youtube.com/watch?v=NW4ZE4y-8hU)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Composite Robot</div><img src='images/composite.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Cooperative composite bipedal wheel-legged robot model with a 6-DOF arm in Isaac SIM**
- [Supply Video1](https://youtu.be/QRQFf7kP7Zo)
- [Supply Video2](https://youtu.be/XL2fsJj2BDk)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">HASEL</div><img src='images/HASEL.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


**Design and Characteristics of A Hydraulic Amplification-Based Soft-Exoskeleton Robotic Module**
- Specially designed the casting mold to adapt to different application scenarios
- Simulated the deformation of soft beam with pneumatic-HASELs and the assembled soft gripper in SOFA

</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">Intro PouchJacket</div><img src='images/pounchPic.png' alt="sym" width="100%"></div></div>
<div class='paper-box-image'><div><div class="badge">Simulation</div><img src='images/pounch.gif' alt="sym" width="100%"></div></div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IPR Model</div><img src='images/mcm.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Bitcon or Gold? --- An investment strategy of IPR(Imatation-Prediction-Risk) model based on ARIMA**
- Compared ARIMA and LSTM models, resulted in ARIMA achieving better accuracy, even when adding the less effective LSTM model to our Imitation model and Risk model.

</div>
</div>


# 🎖 Honors and Awards
- *2021-2022* National Scholarship of China (**TOP 0.2% in China**)
- *2019-2020* Li Wen & Yang Yan Scholarship (**TOP 1/3870 in Class 2023 of BUCT**)
- *2020-2021* Jinfa Technological Scholarship (**TOP 0.5% in College of Mechanical and Electrical Engineering**)  
- *2021-2022* First Prize Scholarship of BUCT (**Twice**) 

# 📖 Educations
- *2019.09 - 2023.07 (now)*, B.Eng., Robotics Engineering, Beijing University of Chemical Technology, Beijing, China


# 💻 Internships
- *2023.01 - 2023.09*, [Research Assistant] Shenzhen Research Institute, The Chinese University of Hong Kong, Hong Kong. Supervised by [Prof. Hongliang Ren](https://www.ee.cuhk.edu.hk/en-gb/people/academic-staff/professors/prof-ren-hongliang), PI of [MMLab](http://www.labren.org/mm/)

- *2022.06 - 2022.10*, [Summer Research Intern] Dept of Electronic Engineering, The Chinese University of Hong Kong, Hong Kong. Supervised by [Prof. Hongliang Ren](https://www.ee.cuhk.edu.hk/en-gb/people/academic-staff/professors/prof-ren-hongliang), PI of [MMLab](http://www.labren.org/mm/)

- *2021.12 - now*, [Research Intern], [Institute of AI Industry Research (AIR)](https://air.tsinghua.edu.cn/en/index.htm), Tsinghua University, Beijing. Supervised by [Prof. Guyue Zhou](https://air.tsinghua.edu.cn/en/info/1046/1196.htm), PI of AIR DISCOVER Lab.