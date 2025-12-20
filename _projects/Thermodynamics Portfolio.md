---
layout: project
title: Thermodynamics Porfolio
description: Actuator system analysis
technologies: [Goodnotes, Excel]
image: /assets/images/system.png

---

### Introduction
I chose to do the mini lab offered by the class where me and 3 others worked with a heat exchanger. A heat exchanger is a type of control volume device where two fluids of different temperatures are flown past each other. In this lab we did a trial with parallel flow and a trial with counter flow between blue ice water and red hot water (at 40 degrees Celsius).

![Shaded rendering of earlier version]({{ "/assets/images/display.png" | relative_url }}){: .inline-image-r style="width: 200px"}

 The image on the right shows an overall set up of this experiment. In the experiment for parallel, we ran the pumps where 1 was the input for hot, 2 was the input for cold, 3 was the output for hot and 4 was the output for cold. For the counterflow these were just flipped. This is a system drawing of the heat exchanger using the colors blue and red to accurately display what system as we could delta heat and work equal to 0. The system drawing is using control volume referencing.![Shaded rendering of earlier version]({{ "/assets/images/Thermo-Calc.jpg" | relative_url }}){: .inline-image-r style="width: 400px"}.
When doing the experiment we ran the pumps from their respective reservoirs and measured the before and after temperatures from the system. The pump would move the hot or cold water throught the heat exchanger and bring it to the other side. 

The images show us measuring the temperatures of the hot and cold reservoirs after each step of the experiment for both parallel and counter flow. The data is listed below.

![Shaded rendering of earlier version]({{ "/assets/images/IMG_6429.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

![Shaded rendering of earlier version]({{ "/assets/images/IMG_6431.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

## Our Data

### Parallel Flow
- Red liquid inlet: 40°C  
- Red liquid outlet: 25.5°C  
- Blue liquid inlet: 4.7°C  
- Blue liquid outlet: 20.0°C  

### Counterflow
- Red liquid inlet: 40.1°C  
- Red liquid outlet: 24.6°C  
- Blue liquid inlet: 6.5°C  
- Blue liquid outlet: 26.0°C  

### Observation
As the experiment progressed, the heat exchanger housing itself became noticeably warmer, indicating that some thermal energy was being transferred to the surroundings rather than remaining entirely within the fluid streams. Additionally, the counterflow configuration resulted in a higher cold fluid outlet temperature compared to parallel flow, consistent with theoretical expectations for counterflow heat exchangers.

### Change
A change that you could do is increase the mass flow rate which would allow more of the cold fluid to pass through and more overall energy removed from the hotter fluid so that the delta t for cold would decrease as it is distribubted over time. 

### Reflection
Heat exchangers can be used in everyday devices like HVAC systems and car radiators. The systems from the lab is definetly not adiabatics as we assume when doing calculations. The system did not fully achieve steady-state operation. Temperature measurements continued to change over time due to heat loss to the surroundings and changes in reservoir temperatures. To better approach steady state, the system could be insulated to reduce environmental heat transfer, and the experiment could be run for a longer period until temperature readings stabilize. In thermodynamic analysis, heat exchangers are often assumed to be adiabatic with respect to the surroundings, meaning no heat is transferred to or from the external environment. However, this assumption did not hold for the experimental setup used in this lab.

The system was not insulated, and heat exchange with the surrounding room air was evident. The ice water reservoir melted quickly due to ambient heat transfer, which affected temperature readings and reduced experimental accuracy. Because the system was not adiabatic, the temperature changes of the hot and cold fluids were not equal in magnitude, as would be expected in an idealized adiabatic heat exchanger. Also, if it was adiabtics when doing the energy balance equations the delta temperature changes would equal but they do not due to excess heat dissipating and imput from the surroundings. This shows it is not actually steady state but creating an insulated system would be a way to get there. We would be able to ignore kinetic energy change as the velocity is low, the kinetic energy term matters more in higher speed systems like jet turbines.
```
```




