# Chip Fuzz

A collection of papers, tools and courses related to chip fuzzing. If there is any additional information that needs to be clarified, please feel free to PR or Issue!

Fuzz everything! Now let's fuzz chip!

## Papers

|                            Title                             |       Venue        |                          Paper                             |                        Github                            |
| :----------------------------------------------------------: | :---------------: |:----------------------------------------------------------: | :----------------------------------------------------------: | 
| Recent Papers Related To Fuzzing (repo)  | Github  |  | [link](https://github.com/wcventure/FuzzingPaper) |
| RFUZZ: Coverage-Directed Fuzz Testing of RTL on FPGAs | ICCAD 2018 | ACM [link](https://dl.acm.org/doi/10.1145/3240765.3240842) | [link](https://github.com/ekiwi/rfuzz) |
| Hyperfuzzing for SoC security validation | ICCAD 2020 | ACM [link](https://dl.acm.org/doi/10.1145/3400302.3415709) | [link](https://github.com/skmuduli92/HyperFuzzer) |
| DifuzzRTL: Differential Fuzz Testing to Find CPU Bugs | IEEE S&P 2021 | IEEE [link](https://ieeexplore.ieee.org/document/9519470) | [link](https://github.com/compsec-snu/difuzz-rtl)|
| Effective Processor Verification with Logic Fuzzer Enhanced Co-simulation | MICRO 2021 | ACM [link](https://dl.acm.org/doi/10.1145/3466752.3480092) | [link](https://github.com/chipsalliance/dromajo.git) |
| DirectFuzz: Automated Test Generation for RTL Designs using Directed Graybox Fuzzing | DAC 2021 | IEEE [link](https://ieeexplore.ieee.org/document/9586289/) |  |
| RTLFuzzLab: Building A Modular Open-Source Hardware Fuzzing Framework | WOSET 2021 | WOSET [link](https://woset-workshop.github.io/PDFs/2021/a10.pdf) |  |
| TheHuzz: Instruction Fuzzing of Processors Using Golden-Reference Models for Finding Software-Exploitable Vulnerabilities | USENIX Security 2022 | USENIX [link](https://www.usenix.org/conference/usenixsecurity22/presentation/kande) |  |
| Fuzzing Hardware Like Software | USENIX Security 2022 | USENIX [link](https://www.usenix.org/conference/usenixsecurity22/presentation/trippel) | [link](https://github.com/googleinterns/hw-fuzzing) |
| Efficient Cross-Level Processor Verification using Coverage-guided Fuzzing | GLSVLSI 2022 | ACM [link](https://dl.acm.org/doi/10.1145/3526241.3530340) |  |
| Cross-Level Processor Verification via Endless Randomized Instruction Stream Generation with Coverage-guided Aging | DATE 2022 | IEEE [link](https://ieeexplore.ieee.org/document/9774771) |  |
| MorFuzz: Fuzzing Processor via Runtime Instruction Morphing enhanced Synchronizable Co-simulation | USENIX Security 2023 | USENIX [link](https://www.usenix.org/conference/usenixsecurity23/presentation/xu-jinyan) | [link](https://github.com/sycuricon/MorFuzz) |
| ProcessorFuzz: Processor Fuzzing with Control and Status Registers Guidance | IEEE HOST 2023 | IEEE [link](https://ieeexplore.ieee.org/document/10133714) | [link](https://github.com/bu-icsg/ProcessorFuzz) |
| Achieving Last-Mile Functional Coverage in Testing Chip Design Software Implementations | ICSE-SEIP 2023 | IEEE [link](https://ieeexplore.ieee.org/document/10172806) |  |
| Cascade: CPU Fuzzing via Intricate Program Generation | USENIX Security 2024 | ETH [link](https://comsec.ethz.ch/research/hardware-design-security/cascade-cpu-fuzzing-via-intricate-program-generation/) | [link](https://github.com/cascade-artifacts-designs/cascade-meta) |
| RISCVuzz: Discovering Architectural CPU Vulnerabilities via Differential Hardware Fuzzing | Black Hat USA 2024 | Black Hat [link](https://ghostwriteattack.com/) | [link](https://github.com/cispa/ghostwrite)|
| SSFuzz: Generating syntactic and semantic seeds for RISC-V processors | GLSVLSI 2024 | ACM [link](https://dl.acm.org/doi/10.1145/3649476.3658712) |  |
| PathFuzz: Broadening Fuzzing Horizons with Footprint Memory for CPUs | DAC 2024 | DAC [link](https://61dac.conference-program.com/presentation/?id=RESEARCH419&sess=sess136) | [link](https://github.com/OpenXiangShan/xfuzz) |
| Beyond Random Inputs: A Novel ML-Based Hardware Fuzzing | DAC 2024 | arXiv [link](https://arxiv.org/abs/2404.06856) |  |
| MABFuzz: Multi-Armed Bandit Algorithms for Fuzzing Processors | DATE 2024 | IEEE [link](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10546726) |  |
| HyPFuzz: Formal-Assisted Processor Fuzzing | USENIX Security 2023 | arXiv [link](https://arxiv.org/pdf/2304.02485.pdf) |  |
| WhisperFuzz: White-Box Fuzzing for Detecting and Locating Timing Vulnerabilities in Processors | USENIX Security 2024 | USENIX [link](https://www.usenix.org/conference/usenixsecurity24/presentation/borkar) | |
| Fuzzerfly Effect: Hardware Fuzzing for Memory Safety | IEEE S&P 2024 | IEEE [link](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10462151) | |
| HScheduler: An execution history-based seed scheduling strategy for hardware fuzzing | Computers & Security | Elsevier [link](https://www.sciencedirect.com/science/article/abs/pii/S0167404825001671) |  |
| FormalFuzzer: Formal Verification Assisted Fuzz Testing for SoC Vulnerability Detection | ASP-DAC 2024| IEEE [link](https://ieeexplore.ieee.org/abstract/document/10473911) |  |
| The Emergence of Hardware Fuzzing: A Critical Review of its Significance  |  Arxiv Survey 2024 |  arxiv [link](https://arxiv.org/abs/2403.12812) | |
| DejaVuzz: Disclosing Transient Execution Bugs with Dynamic Swappable Memory and Differential Information Flow Tracking assisted Processor Fuzzing | ASPLOS 2025 | arXiv [link](https://arxiv.org/abs/2504.20934) | [link](https://github.com/sycuricon/DejaVuzz) |
| FeedbackFuzz: Fuzzing Processors via Intricate Program Generation with Feedback Engine | ICASSP 2025 | IEEE [link](https://ieeexplore.ieee.org/document/10889404) |  |


## Courses
|  Courses  |  Code  |
|-------|-------|
| [Design Verification](https://uobdv.github.io/Design-Verification/) | COMS30026 |
| [Secure Hardware Design](https://shd.mit.edu/2024/) | 6.5950/6.5951 (Previously [6.S983](csg.csail.mit.edu/6.S983/) and 6.888) |
| [One Student One Chip](https://ysyx.oscc.cc/docs/en/) | UCAS |
