---
layout: archive
title: "Career"
permalink: /career/
author_profile: true
type: grid
---

<img src="/images/intel.png" alt="image" width="150" height="150">

## Intel Corporation
### Device Engineer | Portland, OR | May 2021 - May 2024

I worked in the Device Engineering group to enhance the performance of Intel's future nodes using Gate-All-Around FETs (GAAFET) and Extreme-UV scaling. I received two Divisional Awards for my outstanding contributions to key performance and yield-improving projects in the early stages of process development.

My primary focus areas were –

**Silicon Performance** 
1.	Supported key FE process and module teams in the GAAFET loop by studying transistor low-voltage and short-channel behavior 
2.	Performed statistical analysis of device performance in controlled process change experiments, and develop physical models to explain the modulations
3.	Driving novel backend projects to improve shorting margin, RC performance of interconnects
4.	Developed and derived new metrics to study electrical performance on different kinds of test structures to study process improvements on BEOL 

**Test Chip Development**
1.	Supported Test Chip development by building transistors and isolation structures to test the limits of device physics and process margins
2.	Designing leading-edge test vehicles on Cadence Virtuoso involves a detailed understanding of devices and process parameters

**Skills**: Electrical Characterization, Statistical Process Control, Device Physics, Thin Films, Physical Design

<!----
As a part of the Test Chip Integration team, I examine transistor performance and isolation structures in _RibbonFETs_ as a key contributor towards R&D efforts into Intel's future technology nodes. 

On a daily basis, I work on building and optimizing test structures that probe into process margins and performance gains for a given node/product. Being a device engineer, I enjoy analyzing I-V characteristics, developing leakage models, and understanding inherent process in novel transistor architectures.

**Projects**:
1. **Pathfinding Test Vehicle** - Currently, I am working on developing device architectures and backside power rail technologies for next generation Intel products. This line of products are expected to hit the market post-2026. My focus is on studying process margins in opens/shorts different front end layers. As we scale down further, in accordance to Moore's law, it is crucial to understand the shorting margins so that we can pack more transistors!
2. **Intel 3** - In my first test chip project, I was involved in an **Enchancement Test Vehicle** for the Alder Lake processors. My task was to develop experiments through Physical Design to study crucial device physics - strained channel, DIBL, off-state leakage - affecting drive current and gain of FinFETs in that node. Being at a relatively matured stage, this technology node was a good lauchpad for making the transition from academia to industry.
----->
-----
![GF logo](/images/GlobalFoundries-New-Logo.png)
## GlobalFoundries
### Antenna Design and Electrical Modeling Intern | Albany, NY | June 2020 - Aug 2020

During the COVID pandemic, I worked remotely in the Advanced Silicon Packaging team at GlobalFoundries on the following -

**Projects:**
1. An **aperture coupled antenna design** for **5G Antenna-in-Package system** operating at 28 GHz on **ANSYS HFSS**. The design of the slot/aperture was crucial along with the placement of the ground plane under the radiating patch. The build also involved multi-parameter optimization to minimize return loss (< -20 db) and achieve a gain (?). 
2. **Electrical characterization of Deep Trench Capacitors** used to decouple the power supply in the 32 nm node on **KLayout** and **ANSYS Q3D**. An RLC model was extracted and compared to back-of-envelope calculations as a preliminary check. GF's integration team would later used this model to evaluate their process understanding and performance objectives.
3. AC/DC resistance evaluation of a test chip designed to study package-chip interactions on **ANSYS Q3D**. A via-chain structure was designed and simulated to act as a point-of-reference for studying process maturity.
4. Characterization of **insertion loss induced by a 100 micron Through-Silicon-Via** in a test vehicle for 2.5 D/psuedo 3D packaging on **ANSYS HFSS** and **KLayout**. Once again, this modeling efforts were aimed to give an initial estimate to the integration team about the performance of their new packaging technology.

**Skills**: Antenna Design, EM simulations, Silicon modeling

-----

![isitfresh logo](/images/isitfresh.png)
## is it fresh GmbH
### Antenna Design Intern | Aachen, Germany | May 2018 - Jul 2018 and Jan 2019 - May 2019

**is it fresh GmbH** works on smart tags that monitor food freshness through humidity and oxygen-levels which are read out using a NFC interface.

I worked two stints in Germany - first, on a [DAAD-UGC Scholarship](https://www.daad.in/en/2021/06/30/daad-ugc-project-based-personnel-exchange-programme-ppp-2021/) in the summer after my junior year undergrad, and second, as an intern sponsored by the company to pursue my Bachelor's thesis with them.

Work in a startup is always fun and dynamic. I was involved in many roles - from building SMD prototypes integrating the printed sensors with NFC circuitry to woodwork and glass cutting for building our own assembly line demo. This place solidified my passion in engineering and helped me decide my path ahead. 

**Projects:**
1. Design and manufacture of non-standard sized NFC reader antennas to increase the read-out range without increasing the output power.
2. Design, production and testing of high resistance thin-film Aluminium NFC tag antennas.

**Skills**: Antenna Design, EM simulations, Thin Films, Prototyping and fabrication
<!---
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
--->
