---
layout: project
title: Fluid Mechanics Lab Project  
description: Design and Evaluation of Wind Blades 
technologies: [MATLAB, Fusion 360, Wind Tunnel Lab Operation]
image: /assets/images/wind_turbine.jpg
---

<strong>Project Overview</strong>
As part of a class project，we were designing a wind blade for operation and performance testing in Big Blue wind tunnel in Upson 256, Cornell University. The The main constraints for the blades are:

- Maximum blade length of **6 inches**
- Blade compatible with a standard hub piece of **1 in radius**
- Wind turbine operating at a fixed angular velocity under **2000 rpm**
- Wind velocity follows a **Weibull distribution** with parameters **k = 5** and **c = 5**


<strong>Design and Testing</strong>
We approached the expected wind speed by two expression of power, which estimates an optimal wind speed of approximately 4.82 m/s (7.3Hz). The corresponding Re number is 14,000 while we compromised to use aerodynamics data at Re of 50,000 for blade design due to limitation of data accessibility. In the blade design, we adapted an angle of attack of 9.75 degrees and a taper ratio of 0.142. As we adjusted the angle of airfoil as radius increased, we remove the last segements of blade as airfoil gets inefficiently small which kept our blade length 4.5 inches. In the testing process, we found that our design was available and safe to approach higher speed of 9 Hz and a more optimal power of 0.17W which may result from our use of higher Re in simulation. My role is contributing to the math calculation to determine the estimated wind speed and power ouput and designing the experimental procedures to ensure the accruacy and safety of data collection. Please refer to [our final report]({{ "/assets/MAE_4272_Final_Report.pdf" | relative_url }}) in PDF format for more details!

![Diagram]({{ "/assets/images/blade_design.png" | relative_url }})
