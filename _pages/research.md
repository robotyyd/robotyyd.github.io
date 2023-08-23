---
layout: archive
permalink: /research/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Magnetic Tweezers
=====
Different kinds of magnetic tweezers that I developed: singlepoel, tripole, quadrupole, and Hexapole.

Magnetic tweezers employ electromagnetic coils and tip-shaped poles to create a magnetic field gradient, thereby exerting a magnetic force on magnetic particles when an input current is applied to the coils. 

The yoke is 3D printed using Metal PLA. The magnetic poles are constructed from a Nickel-Iron soft ferromagnetic alloy (Mu-Metal). The electromagnetic coils are wound with 28 AWG Enameled Copper Wire.
<div style="display: flex; align-items: center;">
  <img src='/images/tweezerall.png' style="height: 200px;">
</div>
<br>

Helmholtz Coils
=====
Helmholtz Coils that I made: 

<div style="display: flex; align-items: center;">
  <img src='/images/helmholtz.jpg' style="height: 200px;">
</div>
[More information here](https://en.wikipedia.org/wiki/Helmholtz_coil)
<br>

Microrobots Tracking and Speed Estimation
=====
Use OpenCV to extract foreground mask, do morphological processing, and find the contours.
<div style="display: flex; align-items: center;">
  <img src='/images/speed.gif' style="height: 200px;">
</div>
<br>

Closed Loop Control (Rolling) of Magnetic Microrobots
=====
Use Helmholtz coils to generate rotating magnetic field to actuate microrobots to roll, and use microscope camera to get visual feedback to minimize the error between desired trajectory and actual trajectory. Our study demonstrated a satisfactory tracking performance of the microrobot, with a peak error of 2.5 μm for a 10 μm microrobot.
<div style="display: flex; align-items: center;">
  <img src='/images/helical.gif' style="height: 200px; margin-right: 10px;">
  <img src='/images/rotating_field.png' style="height: 200px; margin-right: 10px;">
  <img src='/images/compare.png' style="height: 200px; margin-right: 10px;">
</div>
<br>

Closed Loop Control (Orienting) of Self-Propelled Microrobots
=====
The self-propelled microrobot has the ability to move itself, we only need to control its direction. Using a Helmholtz coil to generate a uniform magnetic field to orient the microrobot, and use microscope camera to get visual feedback to minimize the error between desired trajectory and actual trajectory. Experimental results demonstrate that this approach achieves satisfactory tracking performance, with an average error of 6.7 μm for a microrobot with a diameter of 24 μm.
<div style="display: flex; align-items: center;">
  <img src='/images/bubble.gif' style="height: 200px; margin-right: 10px;">
  <img src='/images/closeloop.png' style="height: 200px;">
</div>
<br>

Single Pole Magnetic Tweezer
=====
Currently it’s just a prototype to decrease the number of the poles, thereby it's expected to reduce heat generated and improve control precision.
<div style="display: flex; align-items: center;">
  <img src='/images/one.gif' style="height: 200px;">
</div>
<br>

UV Emitter for Light-steered Microrobots
=====
A UV LED prototype for light-steered microrobot control. Use UV Fused Silica Plano-Convex Lens (Uncoated) to transfer point light source to parallel light source. Use heat sink and thermal interface material (thermal paste) under MCPCB for cooling.
<div style="display: flex; align-items: center;">
  <img src='/images/light.png' style="height: 200px;">
</div>
<br>

Portable Control System
=====
A simple control system for the micromanipulators. Include: 1 Raspberry Pi 4 Model B, 2 Motor HAT (8 coils output), and 1 touch screen. 
Max input voltage: 12V. 
Max output current: 3.5A.
Also the system is equipped with a PS5 controller to control the direction of the microrobot by operating the joystick manually.
<div style="display: flex; align-items: center;">
  <img src='/images/system.png' style="height: 200px;">
</div>
