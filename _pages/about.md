---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
About me
======

My name is Yuhao Jiang (蒋宇豪). I'm a postdoc researcher working with [Prof. Jamie Paik](https://people.epfl.ch/jamie.paik/?lang=en) at [Reconfigurable Robotics Lab](https://www.epfl.ch/labs/rrl/), EPFL. I obtained my Ph.D. degree in Mechanical Engineering from Arizona State University in Aug. 2023 under the supervision of [Prof. Daniel Aukes](https://search.asu.edu/profile/2727366). I received my M.S. and B.S. degree in Mechanical Engineering respectively from University of Florida in 2017 and Donghua University in 2015.

Research Interest
======

I seek to explore novel mechanisms and control strategies aimed at enhancing the accessibility, functionality, and reliability of modular reconfigurable robotic systems across a spectrum of challenging and unfamiliar environments. My research centers on using dynamic modeling methods, complemented by simulations and machine learning techniques, to study and develop novel mechanisms and advanced controls for modular reconfigurable robots. Moreover, I actively engage in mentoring students, guiding them through designing, modeling, prototyping, and testing cutting-edge robotic systems for locomotion and manipulation tasks.

<style>
.projects-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 2rem;
  justify-content: center;
  margin-bottom: 2rem;
}

.project-col {
  flex: 1 1 340px;
  max-width: 500px;
  min-width: 260px;
  background: #f8f8f8;
  padding: 0 0 1.5rem 0;
  border-radius: 0;
  box-shadow: 0 2px 8px rgba(0,0,0,0.03);
  display: flex;
  flex-direction: column;
  align-items: stretch;
  overflow: hidden;
}

.project-col video {
  width: 100%;
  height: auto;
  border: none;
  border-radius: 0;
  box-shadow: none;
  margin: 0;
  background: #000;
  display: block;
}

.project-title {
  margin: 0;
  padding: 1.2rem 1rem 0.5rem 1rem;
  font-size: 1.13em;
  font-weight: 600;
  text-align: left;
  display: flex;
  align-items: center;
  gap: 0.7em;
}

.project-title img {
  margin-left: auto;
  width: 22%;
  min-width: 46px;
  max-width: 90px;
  height: auto;
  display: inline-block;
}

@media (max-width: 900px) {
  .project-title {
    padding-left: 0.7rem;
    padding-right: 0.7rem;
    font-size: 1em;
  }
  .project-title img {
    width: 28vw;
    min-width: 36px;
    max-width: 70px;
  }
}
@media (max-width: 540px) {
  .project-title {
    padding-left: 0.5rem;
    padding-right: 0.5rem;
    font-size: 0.98em;
  }
  .project-title img {
    width: 34vw;
    min-width: 28px;
    max-width: 50px;
  }
}

.project-desc {
  padding: 0 1rem 0 1rem;
  font-size: 0.93em;
  color: #222;
  overflow-wrap: break-word;
  word-break: break-word;
  flex-grow: 1;
  max-height: none;
  overflow: visible;
  text-align: justify;
}

/* Responsive layout for mobile: stack columns */
@media (max-width: 900px) {
  .projects-grid {
    flex-direction: column;
    gap: 1.5rem;
  }
  .project-col {
    max-width: 100%;
    min-width: 0;
    width: 100%;
    padding-bottom: 1.2rem;
    flex: 0 1 auto !important;
    height: auto !important;
  }
  .project-desc {
    font-size: 0.98em;
    flex-grow: 0 !important;
    max-height: none !important;
    overflow: visible !important;
  }
}

/* For extra small screens */
@media (max-width: 540px) {
  .project-desc {
    font-size: 0.95em;
    flex-grow: 0 !important;
    max-height: none !important;
    overflow: visible !important;
  }
}
</style>

Selected Projects
======

<div class="projects-grid">
  <div class="project-col">
    <video
      src="{{ '/files/videos/CPG_reduced.mp4' | relative_url }}"
      autoplay
      muted
      loop
      playsinline
    ></video>
    <div class="project-title">
      CPG-Based Multi-Module Robotic Manipulation
      <img src="/files/research/eu-flag.png" alt="EU Funding">
    </div>
    <div class="project-desc">
      This project marks the first application of the Central Pattern Generator (CPG) method to manipulation tasks in multi-module robotic systems. A novel data-driven optimization framework, integrated with dynamic simulations, efficiently identifies optimal CPG parameters in complex, high-dimensional spaces. This enables robust manipulation of objects with diverse sizes, shapes, and materials, as demonstrated through simulations and prototype experiments.
    </div>
  </div>
  <div class="project-col">
    <video
      src="{{ '/files/videos/soft_twisted_beam_reduced.mp4' | relative_url }}"
      autoplay
      muted
      loop
      playsinline
    ></video>
    <div class="project-title">
      Soft Twisted Beam Vibration for Robotic Walking
      <img src="/files/research/nsf.png" alt="NSF Funding">
    </div>
    <div class="project-desc">
      This project investigates a novel, underactuated soft twisted beam structure that leverages structural intelligence to achieve effective locomotion. When actuated by a simple 2D vibrational force, the structure generates complex 3D motions. The study first examines the dynamic behavior of a single twisted beam, and then integrates these beams into a quadrupedal robot, Flix_Walker, which demonstrates three distinct and versatile locomotion modes, all achieved with minimal actuation.
    </div>
  </div>
  <div class="project-col">
    <video
      src="{{ '/files/videos/shape_propogation_reduced.mp4' | relative_url }}"
      autoplay
      muted
      loop
      playsinline
    ></video>
    <div class="project-title">
      Shape Change Propagation for Robotic Swimming
      <img src="/files/research/nsf.png" alt="NSF Funding">
    </div>
    <div class="project-desc">
      This project introduces a soft tubular swimming robot that leverages shape propagation—a concept where actuation forces are transformed by the robot's changing shape. By transmitting deformation from a central soft pneumatic actuator to curved fins, the device produces complex, asymmetric swimming strokes from simple, symmetric inputs. This approach simplifies control and power delivery while utilizing the mechanics of curved soft materials for effective locomotion.
    </div>
  </div>
  <div class="project-col">
    <video
      src="{{ '/files/videos/curved_beam_reduced.mp4' | relative_url }}"
      autoplay
      muted
      loop
      playsinline
    ></video>
    <div class="project-title">
      Reconfigurable Curved Beams for Robotic Swimming
      <img src="/files/research/nsf.png" alt="NSF Funding">
    </div>
    <div class="project-desc">
      This project explores how the stiffness and buckling behavior of curved beams can be tuned through changes in length, camber angle, and width. By leveraging the natural tendency of curved beams to preferentially buckle in specific directions, the design enables passive generation of net work and moments from simple, symmetric inputs—reducing the need for complex control in soft robotic systems.
    </div>
  </div>
  <div class="project-col">
    <video
      src="{{ '/files/videos/fish_reduced.mp4' | relative_url }}"
      autoplay
      muted
      loop
      playsinline
    ></video>
    <div class="project-title">
      Bio-inspired Design for Robotic Swimming
      <img src="/files/research/srp.png"  alt="SRP">
    </div>
    <div class="project-desc">
      This work introduces a fish-inspired underwater robot for maneuverability in open-channel canals under external disturbances. A machine learning workflow is used to train and select efficient swimming gaits in the lab, minimizing outdoor data collection by transferring only the most promising gaits for real-world testing. The key contribution is an online learning strategy that reliably identifies gaits with consistent performance across both laboratory and real-world environments.
    </div>
  </div>
  <div class="project-col">
    <video
      src="{{ '/files/videos/pinch_tube_reduced.mp4' | relative_url }}"
      autoplay
      muted
      loop
      playsinline
    ></video>
    <div class="project-title">
      Reconfigurable Soft Hinges via Pinched Tubes
      <img src="/files/research/nsf.png" alt="NSF Funding">
    </div>
    <div class="project-desc">
      This project introduces reconfigurable soft joints created by pinching thin-walled cylindrical tubes. These "virtual hinges" offer tunable compliance and can recover their original shape and stiffness when released. By leveraging 3D printing for rapid prototyping, the design enables easy adjustment of tube geometry and stiffness, allowing for customizable, passive rotational joints in soft robotic systems.
    </div>
  </div>
</div>

<!-- Publications
======
- **Y. Jiang**, S. Asmar, Z. Wang, S. Demirtas, and J. Paik, “CPG-Based Manipulation with Multi-Module Origami Robot Surface,” *IEEE Robotics and Automation Letters*, March 2025, doi: [10.1109/LRA.2025.3555381](https://doi.org/10.1109/LRA.2025.3555381).

- **Y. Jiang**, F. Chen, J. Paik, and D. M. Aukes, "Locomotion via Vibration of Soft, Twisted Beams with an Under-actuated Quadruped," submitted, June 2024.

- X. Zheng, **Y. Jiang**, M. Mete, J. Li, I. Watanabe, T. Yamada, and J. Paik, "Metamaterial Robotics," submitted, November 2024.

- **Y. Jiang**, F. Chen and D. M. Aukes, "Tunable Dynamic Walking via Soft Twisted Beam Vibration," *IEEE Robotics and Automation Letters*, vol. 8, no. 4, pp. 1967-1974, April 2023, [https://doi.org/10.1109/LRA.2023.3244716](https://doi.org/10.1109/LRA.2023.3244716).

- **Y. Jiang**, M. Sharifzadeh, and D. M. Aukes, "Reconfigurable Soft Flexure Hinges via Pinched Tubes," *2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*, 2020, pp. 8843-8850, [https://doi.org/10.1109/IROS45743.2020.9341109](https://doi.org/10.1109/IROS45743.2020.9341109).

- **Y. Jiang**, M. Sharifzadeh, and D. M. Aukes, "Shape Change Propagation Through Soft Curved Materials for Dynamically-Tuned Paddling Robots," *2021 IEEE 4th International Conference on Soft Robotics (RoboSoft)*, 2021, pp. 230-237, [https://doi.org/10.1109/RoboSoft51838.2021.9479208](https://doi.org/10.1109/RoboSoft51838.2021.9479208).

- P. Bupe, **Y. Jiang**, J. Lin, T. Nguyen, M. Han, D. Aukes, C. Harnett, "Embedded Optical Waveguide Sensors for Dynamic Behavior Monitoring in Twisted-Beam Structures," *2024 IEEE 7th International Conference on Soft Robotics (RoboSoft)*, San Diego, CA, USA, 2024, pp. 139-144, [https://doi.org/10.1109/RoboSoft60065.2024.10521938](https://doi.org/10.1109/RoboSoft60065.2024.10521938).

- M. Sharifzadeh, **Y. Jiang**, A. Lafmejani, D. M. Aukes, "Compensating for Material Deformation in Foldable Robots via Deep Learning -- A  Case  Study," *2022 IEEE International Conference on Robotics and Automation (ICRA)*, 2022, [https://doi.org/10.1109/ICRA46639.2022.9811752](https://doi.org/10.1109/ICRA46639.2022.9811752).

- M. Sharifzadeh, **Y. Jiang**, A. Lafmejani, K. Nichols, and D. M. Aukes, "Maneuverable gait selection for a novel fish-inspired robot using a CMA-ES-assisted workflow," *Bioinspiration & Biomimetics*, vol. 16, no. 5, pp. 056017, August 2021, [https://doi.org/10.1088/1748-3190/ac165d](https://doi.org/10.1088/1748-3190/ac165d).

- M. Sharifzadeh, **Y. Jiang**, and D. M. Aukes, "Reconfigurable Curved Beams for Selectable Swimming Gaits in an Underwater Robot," *IEEE Robotics and Automation Letters*, vol. 6, no. 2, pp. 3437-3444, April 2021, [https://doi.org/10.1109/LRA.2021.3063961](https://doi.org/10.1109/LRA.2021.3063961).

- Sharifzadeh, M, **Jiang, Y**, Khodambashi, R, & Aukes, D. "Increasing the Life Span of Foldable Manipulators With Fabric," *ASME 2020 International Design Engineering Technical Conferences and Computers and Information in Engineering Conference*. Volume 10: 44th Mechanisms and Robotics Conference (MR). Virtual, Online. August 17–19, 2020. V010T10A087. ASME. [https://doi.org/10.1115/DETC2020-22757](https://doi.org/10.1115/DETC2020-22757) -->

Patents
======

- "Tunable Motion Using Flexible Twisted Beams", Daniel Aukes, **Yuhao Jiang**, Fuchen Chen - US Patent Application 20240391542

- "Pinched tubes for reconfigurable robots”, Daniel Aukes, Mohammad Sharifzadeh, **Yuhao Jiang**, Nicholas Gravish, Mingsong Jiang - US Patent US20230127106A1
 
- “Buckling beams for underwater and terrestrial autonomous vehicles”, D Aukes, M Sharifzadeh, **Y Jiang** - US Patent US20230121727A1

- “Mechanisms for steering robotic fish”, D Aukes, M Sharifzadeh, K Nichols, **Y Jiang** - US Patent US11124281B2

Presentations
======

- RoboSoft 2025 (in person): CPG-Based Motion Generator for Multi-Module Origami Robot, [https://youtu.be/Gz0DezhwF9U](https://youtu.be/Gz0DezhwF9U).

- RoboSoft 2023 (in person): Tunable Dynamic Walking via Soft Twisted Beam Vibration.

- RoboSoft 2023 Workshop Presentation (in person): Model Order Reduction for Vibrational Soft Twisted Beams Using Pseudo-rigid-body Modeling – A Case Study, [https://youtu.be/7g6SEwEBvhU](https://youtu.be/7g6SEwEBvhU).

- ICRA 2022: Compensating for Material Deformation in Foldable Robots Via Deep Learning -- a Case Study, [https://youtu.be/AwS4vabv-JQ](https://youtu.be/AwS4vabv-JQ).

- ICRA 2022 Workshop Presentation (in person): Workshop on Modular Self-reconfigurable Robots: Yuhao Jiang, Paul Bupe, Jr, Nathan Justus, Curtis Sparks, Daniel Aukes, Nick Gravish, Cindy K. Harnett, Ross Hatton, "Modular Robots Using Soft Curved Reconfigurable Anisotropic Mechanisms", May 23, 2022.

- ICRA 2021: Reconfigurable Curved Beams for Selectable Swimming Gaits in an Underwater Robot, [https://youtu.be/EszTDc9slyw](https://youtu.be/EszTDc9slyw).

- Robosoft 2021: Shape Change Propagation Through Soft Curved Materials for Dynamically-Tuned Paddling Robots.

- IROS 2020: Reconfigurable Soft Flexure Hinges via Pinched Tubes, [https://youtu.be/J5heXXD6mVo](https://youtu.be/J5heXXD6mVo).


Public Outreach
======
* **Media Interview**

1. **RTS Education and Scientific Program:** Feature in “A guide to the future: Swiss Federal Institute of Technology 02”  
   [Watch on YouTube (from 9:21)](https://www.youtube.com/watch?v=9yoNLg5Qho0&t=561s)

* **Organized Events**

1. **IROS 2025 Workshop:**  
   S'MORE: Shape-Morphing Robotics via Embodied Sensing and Mechanisms 
   [Website](https://www.shapemorphingrobot.com/)  

2. **2024 RRL Demo Day:**  
   Full-day public event for projects from RRL and ME-410 class  
   [Website](https://www.paikslab.com/courses)  
   [Report](https://youtu.be/it6jJS-H5x4?si=gyGUmFWXbrALHeCM)

3. **2023 RRL Demo Day:**  
   Full-day public event for projects from RRL and ME-410 class  
   [Website](https://sites.google.com/view/rrl-me410/home)  
   [Report](https://youtu.be/wza144iqfco?si=_HfGVhsnzebmp7ZM)

4. **Robosoft 2021 Workshop:**  
   “Breaking the Mold: Challenging Current Paradigms in Soft Robotics”  
   [Website](https://www.scrambots.com/robosoft-2021-workshop)

* **Demos and Expositions**

1. RRL lab tours (~6 times per year)
2. 2024 RRL Demo Day
3. 2024 Swiss Robotics Day
4. 2023 RRL Demo Day
5. 2023 Swiss Robotics Day
6. IdeaLab lab tours (~4 times per year)
7. 2019 Southwest Robotics Symposium (SWRS)

Academic Services
======

* **Journal Reviewer**: The International Journal of Robotics Research (IJRR), IEEE Transactions on Robotics (T-RO), IEEE Robotics and Automation Letters (RA-L), Soft Robotics (SoRo), Journal of Field Robotics (JFR), ASME Journal of Mechanisms and Robotics (JMR).
* **Conference Reviewer**: IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), International Conference on Robotics and Automation (ICRA), International Conference on Soft Robotics (Robosoft), ACM Symposium on Computational Fabrication (SCF)
