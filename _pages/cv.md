---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Summary
Principal Engineer at Samsung Electronics with nearly a decade of experience endowing robots with sophisticated visual intelligence. I lead the 3D vision AI for industrial automation, specializing in core technologies like stereo matching and 6-DoF object pose estimation. My work bridges academic research excellence, demonstrated by multiple top-tier publications, with the creation of robust, scalable automation solutions for real-world manufacturing environments.

---

Education
======
* **Ph.D. & M.S. in Bio and Brain Engineering**, KAIST, 2010-2016
* **Research Trainee, Biomedical Imaging Group**, EPFL, 2012-2013
* **B.S. in Electrical Engineering**, Hanyang University, 2005-2010

---

Work experience
======
* **Sep 2016 - present: Principal Engineer**
  * Samsung Electronics
  * Duties included:
    * Led the development of a proprietary 3D stereo vision system, unifying all aspects from custom hardware design and data generation to the core AI model implementation.
    * Served as the project lead for factory automation, successfully developing and deploying numerous robotic applications across Samsung's global manufacturing lines.

---

Projects
======
* **3D Vision System Development (2022 - present)**
  * Led the development of a proprietary 3D stereo vision system, culminating in a world-class stereo matching model that achieves state-of-the-art precision.
  * Pioneering a novel technique for selective depth processing to handle challenging environments with numerous transparent objects.

* **Advanced Perception for Robotics (2020 - 2024)**
  * Engineered RGB-D based 6-DoF object detection and pose estimation models for robotic manipulation in cluttered environments.
  * Pioneered the use of large-scale, CAD-based synthetic data to achieve superior model generalization across diverse industrial components.
  
* **Automation Solution Deployment (2018 - 2024)**
  * Engineered and deployed robust vision-guided automation solutions across Samsung's global manufacturing sites, including Random Bin-Picking, Depalletizing, and high-precision Pick and Place.

---

Skills
======
* **Programming:** Python, C, C++, MATLAB
* **ML/CV Libraries:** PyTorch, TensorFlow, OpenCV, Open3D, Scikit-learn, Pandas
* **Simulation:** Blender, OpenAI Gym, Mujoco, Pybullet
* **Domains:** 3D Vision, Robot Manipulation, Factory Automation, Medical Imaging

---

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
---

Patents
======
* "ROBOT CONTROL APPARATUS AND METHOD FOR LEARNING TASK SKILL OF THE ROBOT", US11911912
* "APPARATUS AND METHOD FOR IDENTIFYING AND PICKING OBJECT USING ARTIFICIAL INTELLIGENCE ALGORITHM", US11645778

---

Awards & Leadership
======
* 2nd place, the Samsung Creative Idea Competition, 2018
* 2nd place (out of 103), AAPM Low Dose CT Grand Challenge, 2016
* Organizer, 2nd Localization Microscopy Challenge in SMLMS, 2016
* Best Student Paper Award, IEEE ISBI, 2013
* Organizer, Localization Microscopy Challenge in IEEE ISBI, 2013
* 2nd place, Future Idea Competition, KOLON-KAIST, 2011
* National Scholarship for Ph.D. and M.S., 2010-2016