---
title: Lenz Vertical Turbine Optimization
description: Geometry optimization of a wind turbine, using computational fluid dynamics and evolutionary algorithms
image: assets/images/Optimized%20Lenz%20Turbine.png
---
![Our Optimized Turbine Rotor Design](/assets/images/Lenz%20Turbine%20Assembly.png){: .inline-img-right style="width:20%"}
Vertical Axis Wind Turbines are a promising renewable energy technology due to their manufacturing and maintenance simplicity, and their ability to operate in turbulent and omnidirectional wind conditions. However, most traditional VAWT designs generate significantly less power than their more common horizontal axis cousins. For my undergraduate capstone design course at Trine University, my team and I worked to use computational fluid dynamics and evolutionary algorithms to iteratively optimize a LENZ-inspired vertical axis wind turbine blade design for power efficiency and ease of startup. 

---

This project heavily used ANSYS Fluent fluids simulation suite to simulate the unsteady effects of the turbine blades rotate over time, calculating the complex wake effects that are the primary influence on turbine performance. In addition to simulation, we also validated our results experimentally using 3d printed turbine models tested in a wind tunnel. With these two analysis tools, I developed an evolutionary algorithm to generate hundreds of design variations and evaluate them in simulation, which over time began producing better and better turbine designs. 

![CFD Simulation](/assets/images/animation-ke.webp){: style="height:250px"}

---

![2021 Regional Conference Winners](/assets/images/AIAA%20Conference%20Winners.jpg){: .inline-img-left}
By the end of the 8 month long project, we had tested over 150 different designs and found a turbine which boasted efficiency on-par with the state-of-the-art in VAWT research, but also with guaranteed startup behavior. Our work was submitted and [published](https://doi.org/10.2514/6.2023-0017) in the 2022 AIAA Student Paper Competition, where we won first place and a ticket to the national 2023 AIAA SciTech Conference Competition the following year.
