---
title: "Unknown Object Grasping for Assistive Robotics"
collection: publications
permalink: /publication/2024-04-23-grasping-unknown-objects
excerpt: 'This paper proposes a novel pipeline for unknown object grasping in shared robotic autonomy scenarios such as assisted living. The research was undertaken during my time with DLR.'
date: 2024-04-23 (arxiv preprint)
venue: 'ICRA 2024'
paperurl: 'https://arxiv.org/abs/2404.15001'
---

We propose a novel pipeline for unknown object grasping in shared robotic autonomy scenarios. State-of-the-art methods for fully autonomous scenarios are typically learning-based approaches optimised for a specific end-effector, that generate grasp poses directly from sensor input. In the domain of assistive robotics, we seek instead to utilise the user's cognitive abilities for enhanced satisfaction, grasping performance, and alignment with their high level task-specific goals. Given a pair of stereo images, we perform unknown object instance segmentation and generate a 3D reconstruction of the object of interest. In shared control, the user then guides the robot end-effector across a virtual hemisphere centered around the object to their desired approach direction. A physics-based grasp planner finds the most stable local grasp on the reconstruction, and finally the user is guided by shared control to this grasp. In experiments on the DLR EDAN platform, we report a grasp success rate of 87% for 10 unknown objects, and demonstrate the method's capability to grasp objects in structured clutter and from shelves.

[Download paper here](https://arxiv.org/abs/2404.15001)

Recommended citation: 
@misc{miller2024unknown,
      title={Unknown Object Grasping for Assistive Robotics}, 
      author={Elle Miller and Maximilian Durner and Matthias Humt and Gabriel Quere and Wout Boerdijk and Ashok M. Sundaram and Freek Stulp and Jorn Vogel},
      year={2024},
      eprint={2404.15001},
      archivePrefix={arXiv},
      primaryClass={cs.RO}
}