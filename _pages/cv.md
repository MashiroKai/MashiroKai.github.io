---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
Chinese version CV can be downloaded [here](https://mashirokai.github.io/files/cv_kaiyu.pdf).

English version CV can be downloaded [here](https://mashirokai.github.io/files/cv_mashiro.pdf).

Education
======
* M.S. in Astronomy, University of Science and Technology of China, 2022
* B.S. in Safty Engineering, GuangDong University of Petrochemical Technology, 2018

Project experience
======
* Research on readout electronics methods for CsI crystal arrays based on SiPM arrays.(2024-4 to Present)
  * Designed frontend circuits including operational amplifiers, ADC sampling, and et al. 
  
    (to amplify weak analog signals and convert them to digital signals.)
  * Developed a multiplexed resistor-encoded network circuit. 

    (to encode signals using analog circuitry, reducing the number of readout channels.)

  * Designed PC software in LabWindows/CVI to provide an interactive data processing interface (C programming).

    (for interactive data processing and display).

* Developed a testing system for the LNGS.(2023-6 to 2024-4)
  * Designed FPGA PCB backplane, differential signal conversion circuits, serial and USB transmission circuits (hardware design).

  * Developed internal FPGA logic to implement functions like timing control, error checking, and data transmission (FPGA programming).

  * Designed PC software in LabWindows/CVI to provide an interactive control interface (C programming).

Skills
======
Proficient in digital and analog circuit design.
* Program languages
  * Hardware languages
    CHISEL, Verilog
  * Software languages
    C, Scala
* English Proficency
  * TOFEL 105/120
  * CET6 526/710
* PCB design software
  * Altium Design
  * JLC EDA

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
