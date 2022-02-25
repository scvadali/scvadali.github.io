---
layout: archive
title: "Career"
permalink: /career/
author_profile: true
---

![Intel logo](/images/intel.png)
## Intel
### Device Engineer | May 2021 - Present 

As a part of the Test Chip Integration team, I examine transistor performance and isolation structures in _RibbonFETs_ as a key contributor towards R&D efforts into Intel's future technology nodes. 

On a daily basis, I work on building and optimizing test structures that probe into process margins and performance gains for a given node/product. Being a device engineer, I enjoy analyzing I-V characteristics, developing leakage models, and understanding inherent process in novel transistor architectures.

**Projects**:
1. **Intel 18A** - Currently working on a **Pathfinding Test Vehicle** for Intel's 18A node which is due beyond 2025.
2. **Intel 3** - In my first test chip project, I was involved in an **Enchancement Test Vehicle** for the Alder Lake processors. My task was to develop experiments through Physical Design to study crucial device physics - strained channel, DIBL, off-state leakage - affecting drive current and gain of FinFETs in that node. Being at a relatively matured stage, this technology node was a good lauchpad for making the transition from academia to industry.


![GF logo](/images/GlobalFoundries-New-Logo.png)
## GlobalFoundries
### Antenna Design and Electrical Modeling Intern | June 2020 - Aug 2020

I worked in the Advanced Silicon Packaging team of GlobalFoundries to develop and model the following modules -

**Projects:**
1. An **aperture coupled antenna design** for **5G Antenna-in-Package system** operating at 28 GHz on **ANSYS HFSS**. The design of the slot/aperture was crucial along with the placement of the ground plane under the radiating patch. The build also involved multi-parameter optimization to minimize return loss (< -20 db) and achieve a gain (?). 
2. **Electrical characterization of Deep Trench Capacitors** used to decouple the power supply in the 32 nm node on **KLayout** and **ANSYS Q3D**. An RLC model was extracted and compared to back-of-envelope calculations as a preliminary check. GF's integration team would later used this model to evaluate their process understanding and performance objectives.
3. AC/DC resistance evaluation of a test chip designed to study package-chip interactions on **ANSYS Q3D**. A via-chain structure was designed and simulated to act as a point-of-reference for studying process maturity.
4. Characterization of **insertion loss induced by a 100 micron Through-Silicon-Via** in a test vehicle for 2.5 D/psuedo 3D packaging on **ANSYS HFSS** and **KLayout**. Once again, this modeling efforts were aimed to give an initial estimate to the integration team about the performance of their new packaging technology.


![isitfresh logo](/images/isitfresh.png)
## is it fresh GmbH
### Antenna Design Intern | May 2018 - Jul 2018 and Jan 2019 - May 2019

**is it fresh GmbH** works on smart tags that monitor food freshness through humidity and oxygen-levels which are read out using a NFC interface.

I worked two stints in Germany - first, on a [DAAD-UGC Scholarship](https://www.daad.in/en/2021/06/30/daad-ugc-project-based-personnel-exchange-programme-ppp-2021/) in the summer after my Junior Year Undergrad, and second, as an Intern sponsored by the company to pursue my Bachelor's thesis with them.

Work in a startup is always fun and dynamic. I was involved in many roles - from building SMD prototypes integrating the printed sensors with NFC circuitry to woodwork and glass cutting for building our own assembly line demo. This place solidified my passion in engineering and helped me decide my path ahead. 

**Projects:**
1. Design and manufacture of non-standard sized NFC reader antennas to increase the read-out range without increasing the output power.
2. Design, production and testing of high resistance thin-film Aluminium NFC tag antennas.

<!---
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
--->
