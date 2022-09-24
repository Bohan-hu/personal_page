---
title: MIPS Out-of-Order Superscalar Processor on FPGA
summary: National Student Computer System Capability Challenge
tags:
  - CPU
date: '2020-08-05T10:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

url_code: 'https://github.com/Superscalar-HIT-Core/Superscalar-HIT-Core-NSCSCC2020'
url_pdf: 'https://github.com/Superscalar-HIT-Core/Superscalar-HIT-Core-NSCSCC2020/blob/master/design_doc.pdf'
url_slides: 'https://github.com/Superscalar-HIT-Core/Superscalar-HIT-Core-NSCSCC2020/blob/master/presentation.pdf'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---
- Self-learned micro-processor design and implemented a 10-stage Out-of-Order superscalar processor, with 2-way fetch, 2-way dispatch, 4-way issue, 2-way commit
- Implemented features: (1) GShare / TAGE overriding branch predictor, with a 256-entry Branch Target Buffer and a 16-entry Next Line Predictor; (2) Pipeline flushing on branch misprediction and precise exception handling; (3) 2 integer units, 1 pipelined multiplication and division unit and 1 pipelined load/store unit, with grouped bypass network; (4) 4KiB 4-way instruction cache with Pseudo-LRU replacement policy and 16KiB non-blocking data cache to avoid stalling the load/store pipeline on cache misses; (5) Use ROB to force the MMIO access seen in order; (6) Explicit register renaming to handle WAW, WAR hazards
- Considered area-timing trade-off to improve the timing on issue unit, reorder buffer and instruction queue, and improved the frequency by 15 MHz using canonical diagrams, multi-selector path optimization, and redundant logic elimination
- RTL design using Verilog, synthesis and implementation using Vivado, with target frequency 88 MHz on Artix-7 FPGA
- Implemented AXI interface and integrated the processor in a SoC with LCD, UART and DDR, capable of running RTOS

