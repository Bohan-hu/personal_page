---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
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
  - title: Research Intern
    company: Peng Cheng National Lab
    company_url: 'https://www.pcl.ac.cn'
    # company_logo: org-gc
    location: Shenzhen, Guangdong
    date_start: '2021-05-01'
    date_end: '2022-07-01'
    description: |2-
        Responsibilities include:
        
        * Hardware design of RV-based binary translation accelerator. 
        * Implementation of CPU-FPGA communication scheme for OSOC(一生一芯) Project.

  - title: Microprocessor Design Intern
    company: Loongson Technology
    company_url: 'https://www.loongson.cn'
    location: Beijing
    date_start: '2020-09-01'
    date_end: '2021-04-01'
    description: Work on the optimization of floating point unit and compiler support.
    
  - title: Teaching Assistant
    company: Harbin Institute of Technology, Shenzhen
    company_url: 'https://www.hitsz.edu.cn'
    location: Shenzhen
    date_start: '2020-09-01'
    date_end: '2021-07-01'
    description: |2-
        [Principles of Computer Organization](https://comp2008.gitee.io/archived) (2020 Spring & 2021 Spring)
        * Designed and improved lab instructions for the two courses and answered students’ questions
        * Built automated test platform with Docker running Vivado and Icarus Verilog simulator, wrote scripts for grading homework
        * Designed training programs for National Student Computer System Capability Challenge (NSCSCC) and delivered lectures

        [Computer Architecture](https://hitsz-cslab.gitee.io/arch/) (2021 Spring)
        * Helped solving student's questions and grading lab reports.

        [Computer Design Practice](https://hitsz-cslab.gitee.io/cpu/) (2020 Spring & 2021 Summer)
        * Developed a [RISC-V CPU verification framework](https://github.com/HITSZ-CDP/cdp-tests) for course labs
        * Developed an automated building and testing system to help student evaluate their design

design:
  columns: '2'
---
