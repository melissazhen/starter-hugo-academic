---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Research Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Computer-Aided Synthesis Planning
    company: advised by [_Pro. Yiming Mo_](https://person.zju.edu.cn/yimingmo) from [Zhejiang University Mo Research Lab](http://www.mo-group.cn/)
    company_url: 'http://www.mo-group.cn/'
    company_logo: zju
    location: Hangzhou, China
    date_start: '2022-07-01'
    # date_end: '2023-09-01'
    description: |2-
        - **Method**: Used the open source RDKit and the rdchiral package to construct a model about retrosynthesis based on  molecular similarity in Python,  involving the process of atom-mapping, calculating fingerprints, calculating similarity scores, extracting reaction templates, proposing candidate precursors and so on, which analyzed reactions from both the open patent literature and the reaction database of energetic material synthesis collected individually
        - **Result**: Realized retrosynthesis planning by proposing suitable precursors for the given target compound

  - title: Magnesium-Air Battery Based on Dual-Layer Gel Electrolyte
    company: advised by [_Pro. Yanna Nuli_](https://scce.sjtu.edu.cn/en/jiaoshi.php?aid=112&c=3) from [SJTU Electrochemistry and Energy Technology Institute](https://scce.sjtu.edu.cn/en/)
    location: Shanghai, China
    company_url: 'https://scce.sjtu.edu.cn/en/'
    company_logo: sjtu
    date_start: '2021-12-01'
    # date_end: '2022-09-01'
    description: |2-
        - **Method**: Synthesized the PEO organic gel and the PAM hydrogel as electrolyte, and used glove box  to dry the PEO gel, then assembled magnesium-air battery with the dual-layer gel electrolyte in different types, like the sandwich type and the cable type.
        - **Result**: Made a battery which could stably run for over 60h with a low voltage, and it endowed a loose needle-like discharge product to take place of the passive magnesium hydroxide layer, which prevented the corrosion of Mg and promoted the utilization of Mg anode.

  - title: The Optimization of an Automatic Platform for Microflow Synthesis
    company: advised by [_Pro. Yuanhai Su_](https://scce.sjtu.edu.cn/en/jiaoshi.php?aid=444&c=2) from [SJTU Continuous-Flow Reactor Technology Research Group](https://scce.sjtu.edu.cn/en/)
    location: Shanghai, China
    company_url: 'https://scce.sjtu.edu.cn/en/'
    company_logo: sjtu
    date_start: '2021-08-01'
    # date_end: '2022-08-01'
    description: |2-
        - **Method**: Analyzed the kinetic mechanism and screened the structures of the photomicroreactor to optimize an automatically continuous-microflow platform.
        - **Result**: Increased the space-time yield of the organic synthesis for quadricyclane to 40 times higher than the previously reported synthetic process

  - title: Investigation on Covalent Modification of Black Phosphorus
    company: advised by [_Pro. Gang Liu_](https://dmne.sjtu.edu.cn/dmne/6764-2/) from [SJTU Brain-Inspired and Smart Bionic Device Lab](hhttps://dmne.sjtu.edu.cn/dmne/)
    company_url: 'https://dmne.sjtu.edu.cn/dmne/'
    company_logo: sjtu
    location: Shanghai, China
    date_start: '2020-08-01'
    date_end: '2021-08-01'
    description: |2-
        - **Method**: Focused on the covalent modification of black phosphorus nanosheets and used the capture and release effects of BPNSs-TPA on electrons to construct a resistive random access memory (RRAM)
        - **Result**: Completed the anti-oxidative passivation of black phosphorus and tested the constructed RRAM which showed stable erasing and writing over 150 times
design:
  columns: '2'
---
