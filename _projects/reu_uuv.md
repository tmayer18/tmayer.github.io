---
title: Dead-Reckoning for Underwater Navigation
layout: project
image: /assets/images/uuv_model.png
description: ROS simulation tools for evaluating long-term dead-reckoning navigation algorithms

---
![UUV in Gazebo](/assets/images/uuv_model.png){: .inline-img-right style="width:25%"}
The worlds oceans play a huge part in global climate patterns, and understanding those changing patterns requires large amounts of temperature data from throughout the ocean. This is an ideal task for long-mission autonomous aquatic robots, but most current subsea navigation techniques require fixed reference points nearby, such as bouys or surface boats. Dead-reckoning, a navigation approach that tracks your speed and heading to determine position, is one promising method in the deep sea, but is well known for facing difficulties as sensor noise accumulates error. 

During the Summer of 2021, I had the opportunity to be a part of the ApREECE REU at Oakland University. My research project involved developing and testing different dead-reckoning algorithms for an autonomous aquatic drone, aimed to collect temperature data across large regions of the oceans for 6 months. I heavily utilized simulation tools like ROS's Gazebo to test these algorithms in different ocean conditions, and prepare for their eventual incorporation onto a physical prototype by future researchers.

---
![Odometry Error Methods](/assets/images/odometry_evaluation_error.png){: .inline-img-left style="width:40%"}
At the end of the summer, my team and I submitted our work for a ASEE conference, and published a [conference paper](https://peer.asee.org/39245) on our findings. With only a few months in the summer, we only analyzed a handful of algorithms, but found that with occasional surfacing to reset accumulated errors was an excellent solution to combatting the challenges of dead-reckoning.

During this project, I worked to develop a suite of simulation and testing tools in the ROS and Gazebo ecosystem that can be used by future researchers to easily test new navigation techniques. These purely software based systems are incredibly useful for rapid iteration and evaluation of large scale robotics projects, and is a valuable skill to have learned from this project.
