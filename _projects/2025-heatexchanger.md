---
layout: project
title: Heat Exchanger Lab
description: Analyzing Devices Using Thermodynamic Principles
technologies: [Heat Exchanger]
image: /assets/images/heatexchanger.2.jpg
---

For our Thermodynamics class, we were tasked with analyzing a device from a thermodynamic perspective. I attended a heat-exchanger lab. 

The device used in the lab was a heat exchanger designed to transfer thermal energy between two flowing liquid streams that can either flow parallel to each other or in counterflow. In this lab, both streams used were liquid water, with one stream being pumped from a heated reservoir and the other, a cold reservoir. The heat exchanger keeps the streams physically separate, while permitting 
heat flow through the barrier separating the streams. This allows for the cold stream to absorb heat thermal energy from the hot stream due to the temperature difference between the stream and the tendency for heat to flow from hot to cold. 


#### **Lab Schematic:**

![Shaded rendering of earlier version]({{ "/assets/images/heatexchangerschematic2.jpg" | relative_url }}){: .inline-image-r style="width: 250px"}

![Shaded rendering of earlier version]({{ "/assets/images/heatexchangerschematic1.jpg" | relative_url }}){: .inline-image-l style="width: 250px"}


<div style="clear: both;"></div>

#### **Modeling Equations:**

![Shaded rendering of earlier version]({{ "/assets/images/labequation3.jpg" | relative_url }}){: .inline-image-l style="width: 500px"}

<div style="clear: both;"></div>

![Shaded rendering of earlier version]({{ "/assets/images/labequation4.jpg" | relative_url }}){: .inline-image-l style="width: 500px"}

<div style="clear: both;"></div>

#### **Lab Documentation:**

<div style="overflow: hidden;"> 
  <figure style="float: left; width: 260px; margin-right: 20px;">
    <img src="{{ '/assets/images/heatlab.jpg' | relative_url }}" alt="Shaded rendering of earlier version" style="width: 100%;">
    <figcaption style="text-align: center;">Pre-flow</figcaption>
  </figure>

  <figure style="float: right; width: 260px; margin-left: 20px;">
    <img src="{{ '/assets/images/heatlabdoc2.jpg' | relative_url }}" alt="Shaded rendering of earlier version" style="width: 100%;">
    <figcaption style="text-align: center;">Post-flow</figcaption>
  </figure>
</div>


<div style="clear: both;"></div>

#### **Data:**
![Shaded rendering of earlier version]({{ "/assets/images/heatexchangerdata.jpg" | relative_url }}){: .inline-image-l style="width: 500px"}

<div style="clear: both;"></div>

#### **Calculation With Data:**

![Shaded rendering of earlier version]({{ "/assets/images/labdatacalc.jpg" | relative_url }}){: .inline-image-l style="width: 500px"}

<div style="clear: both;"></div>

#### **Analysis:**

The data shows that the cold stream warms substantially and the hot stream cools significantly, demonstrating the effective function of the heat exchanger. However, our results reveal that the idealized steady-state model is not entirely accurate, as the temperature differences between the hot and cold streams do not precisely match. Additionally, the observed changes in the heat exchanger’s metal surface raise questions about the validity of the externally adiabatic assumption used in our steady-state calculations. Although the device is not perfectly adiabatic, the significant temperature changes in the heat exchanger are likely caused by heat transfer between the streams and the metal, which may also explain the non-ideal temperature relationships observed between the streams.

When examining different flow configurations, we found that operating the heat exchanger in a cross-flow arrangement at higher speeds resulted in greater temperature changes compared to parallel-flow at the same speeds. While data collection at lower flow rate speeds was rushed, we observed that higher flow rates generally produced larger temperature changes. This further highlights the limitations of the idealized model, which typically allows us to neglect/cancel out mass flow rate. In the future, I would like to run each stream at a different speed, which would require incorporating the varying mass flow rates into our calculations, allowing a more accurate assessment of the model’s validity. Based on our observations, we expect that increasing the flow rate of the cold stream while maintaining the hot stream at lower temperatures (still above the cold stream) would result in greater energy transfer and enhanced cooling of the hot stream.




