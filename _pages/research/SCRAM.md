---
layout: archive
title: "SCRAMS: Soft, Curved, Reconfigurable, Anisotropic Mechanisms"
permalink: /research/SCRAM
author_profile: true
---
# Outline of the study on SCRAM

## Introduction

Soft Curved Reconfigurable Anisotropic Mechanisms (SCRAMs) is a new class of soft robotic technology that will enable new multi-functional soft robots with reconfigurable actuation and shapes. \
The key to the proposed technology is the ability to change the mechanical properties of a thin-walled structure by changing its local curvature. For example, curving a flat sheet of paper along one direction greatly increases its stiffness in the other two directions. Exploiting the coupling between curvature and mechanical behavior in planar materials will enable the design, modeling, and control of reconfigurable soft robots. Based on this concept, we have proposed two different models made from soft materials that can all be used to alter the mechanical behavior via tuning the structural stiffness. These three models are thin-walled cylindrical tubes, and curve beams. \
In addition to tuning the stiffness, we also found another intersting behavior lies in soft shapeable surfaces that can be used as a transmitting media through which the actuation forces can be altered. This concept leverages the mechanics of materials to generate highly nonlinear stiffness and buckling behavior that induces an asymmetric output locomotion via an cyclic symmetric input actuation. This approach can be used to simplify actuation signals in soft robotic systems.

## Pinched Tubes
![](/files/research/pinched_tube.png)\
<br/>
Thin-walled cylindrical tubes can be pinched to create compliant, virtual joints in any radial direction, and then recover their original shape and stiffness once released. Through careful design and material selection, this can result in large changes in stiffness between the original shape, the intended degree of freedom, and orthogonal axes; resulting flexures can then used as passive, compliant rotational joints. Since the manufacturing of these tubes it is compatible with 3D printing processes, its shape can be easily adjusted and reprinted as more is learned about its performance.Thin-walled cylindrical tubes can be pinched to create compliant, virtual joints in any radial direction, and then recover their original shape and stiffness once released. Through careful design and material selection, this can result in large changes in stiffness between the original shape, the intended degree of freedom, and orthogonal axes; resulting flexures can then used as passive, compliant rotational joints. Since the manufacturing of these tubes it is compatible with 3D printing processes, its shape can be easily adjusted and reprinted as more is learned about its performance.\
![](/files/research/pinched_tube_stiffness.png)
<br/>
Thin-walled cylindrical tubes can be pinched to create compliant, virtual joints in any radial direction, and then recover their original shape and stiffness once released. Through careful design and material selection, this can result in large changes in stiffness between the original shape, the intended degree of freedom, and orthogonal axes; resulting flexures can then used as passive, compliant rotational joints. Since the manufacturing of these tubes it is compatible with 3D printing processes, its shape can be easily adjusted and reprinted as more is learned about its performance.

### Related published paper
- **Y. Jiang**, M. Sharifzadeh and D. M. Aukes, "Reconfigurable Soft Flexure Hinges via Pinched Tubes," 2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2020, pp. 8843-8850, doi: 10.1109/IROS45743.2020.9341109.

## Buckling Beams
![](/files/research/buckling_beam_1.png)
<br/>

A flat, slender, compliant beam shows little resistance towards bending; however, by inducing curvature in it, the resulting curved beam resists bending in the direction opposing its camber (known as opposite sense bending) more than when the beam is bent in the direction of the beam’s camber (equal sense bending). The influence of curvature results in different buckling limits in equal and opposite sense bending as well.

![](/files/research/buckling_beam_2.png)
<br/>
The beam stiffness can be tuned through changing the beam length, camber angle, and width. By careful consideration during mechanical design, the preferential buckling of curved beams can be used to passively produce positive net work and moments even during symmetric inputs; this reduces the complexity of the control problem.

### Related published papers

- M. Sharifzadeh, **Y. Jiang** and D. M. Aukes, "Reconfigurable Curved Beams for Selectable Swimming Gaits in an Underwater Robot," in IEEE Robotics and Automation Letters, vol. 6, no. 2, pp. 3437-3444, April 2021, doi: 10.1109/LRA.2021.3063961.

## Shape Change Propagation
![](/files/research/shape_change.png)
<br/>
Due to the shape change in soft structures, the actuation forces, when transmitting through the structure, can be altered. This interesting behavior enables the robotic systems to achieve an complex, asymmetric locomotion via a simple, symmetric actuation input. This shape propagation concept leverages the mechanics of materials and studies the impact that curvature can have on the ability to transmit shape change between two different surfaces of a soft body in order to simplify the power delivery and control signals required for locomoting soft robotic systems.  In this study, a soft tubular swimming device has been developed which utilizes the proposed shape propagation concept; it is actuated by a soft pneumatic actuator which has been adapted to be co-printed within the tubular geometry and change the tube's curvature when inflated. The proposed device transmits the deformation of a central tube to two connected curved fins to produce an asymmetric paddling stroke in which the anisotropic stiffness of curved surfaces is leveraged to preferentially buckle the system in one direction.

### Related published paper
- **Y. Jiang**, M. Sharifzadeh and D. M. Aukes, "Shape Change Propagation Through Soft Curved Materials for Dynamically-Tuned Paddling Robots," 2021 IEEE 4th International Conference on Soft Robotics (RoboSoft), 2021, pp. 230-237, doi: 10.1109/RoboSoft51838.2021.9479208.
