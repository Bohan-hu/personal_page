---
title: A RISC-V Processor Core running Linux
summary: OSOC Project Phase 2 (“一生一芯”项目二期)
tags:
  - CPU
date: '2021-09-01T10:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

url_code: 'https://github.com/Bohan-Hu/RV-Lite-OSOC'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---
-	Designed a minimal die-area but fully functional core capable of running Linux operating system
-	Self-implemented the processor core from scratch
-	Designed a 3-stage pipeline including (1) instruction fetch, (2) decode & execute and (3) commit & exception handling
-	Implemented Translation Lookaside Buffer and hardware Page Table Walker to support hardware virtual memory management
-	Implemented AXI interface to integrate the core into SoC that work with peripherals (DDR controllers, Ethernet, etc.)
-	Taped-out on Dec. 29th with SMIC 110nm technology node

