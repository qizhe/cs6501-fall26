---
layout: default
title: Schedule
nav_order: 2
permalink: /schedule.html
---

### Overview

| Date | Topic | Readings |
|---|---|---|
| Tue 08/25 | Introduction: datacenter infra | [Slides](Lec1-CourseOverview.pdf) |
| Thu 08/27 | How to profile your system | [Slides](Lec2-HowToProfile.pdf); [Understanding host network stack latency](https://www.qizhecai.com/papers/latency.pdf) |

---

### Network core

| Date | Topic | Readings |
|---|---|---|
| Tue 09/01 | Datacenter topology | [Fat-Tree](https://dl.acm.org/doi/10.1145/1402946.1402967); [Jupiter Rising](https://dl.acm.org/doi/10.1145/2785956.2787508) |
|  |  | *Optional:* [Facebook’s Data Center Fabric](https://conferences.sigcomm.org/sigcomm/2015/pdf/papers/p123.pdf); [VL2](https://web.eecs.umich.edu/~mosharaf/Readings/VL2.pdf); [Jellyfish](https://www.usenix.org/system/files/conference/nsdi12/nsdi12-final82.pdf) |
| Thu 09/03 | Congestion control I: Rate control | [DCQCN](https://dl.acm.org/doi/10.1145/2785956.2787484); [HPCC](https://dl.acm.org/doi/10.1145/3341302.3342085) |
|  |  | *Optional:* [DCTCP](https://dl.acm.org/doi/10.1145/1851275.1851192); [TIMELY](https://dl.acm.org/doi/10.1145/2829988.2787510) |
| Tue 09/08 | Congestion control II: Admission control | [Homa](https://dl.acm.org/doi/10.1145/3230543.3230564); [dcPIM](https://dl.acm.org/doi/10.1145/3544216.3544235) |
|  |  | *Optional:* [NDP](https://dl.acm.org/doi/10.1145/3098822.3098825); [FastPass](https://dl.acm.org/doi/10.1145/2740070.2626309); [pHost](https://dl.acm.org/doi/10.1145/2716281.2836086) |
| Thu 09/10 | Load balancing | [Hedera](https://dl.acm.org/doi/10.5555/1855711.1855730); [CONGA](https://dl.acm.org/doi/10.1145/2619239.2626316) |
|  |  | *Optional:* [HULA](https://dl.acm.org/doi/10.1145/2890955.2890968); [PLB](https://dl.acm.org/doi/10.1145/3544216.3544226); [Conweave](https://dl.acm.org/doi/10.1145/3603269.3604849) |
| Tue 09/15 | Networking infra for ML | [HPN](https://dl.acm.org/doi/10.1145/3651890.3672265); [Distributed AI at Meta](https://cs.stanford.edu/~keithw/sigcomm2024/sigcomm24-final246-acmpaginated.pdf) |
| Thu 09/17 | Network communication for ML | [TCCL](https://dl.acm.org/doi/10.1145/3620666.3651362); [CRUX](https://cs.stanford.edu/~keithw/sigcomm2024/sigcomm24-final380-acmpaginated.pdf) |
|  |  | *Optional:* [TACCL](https://www.usenix.org/system/files/nsdi23-shah.pdf); [TE-CCL](https://dl.acm.org/doi/10.1145/3651890.3672249) |
| Tue 09/22 | Optical networking | [Jupiter Evolving](https://dl.acm.org/doi/10.1145/3544216.3544265); [SIRIUS](https://www.microsoft.com/en-us/research/wp-content/uploads/2020/07/sirius-sigcomm20.pdf) |
|  |  | *Optional:* [Lightwave Fabrics](https://dl.acm.org/doi/10.1145/3603269.3604836); [Rotornet](https://dl.acm.org/doi/10.1145/3098822.3098838); [ProjecToR](https://dl.acm.org/doi/10.1145/2934872.2934911) |

---

### Host HW

| Date | Topic | Readings |
|---|---|---|
| Thu 09/24 | Interconnect I: PCIe | [Understanding PCIe Perf](https://dl.acm.org/doi/10.1145/3230543.3230560); [Routable PCIe](https://www.usenix.org/conference/nsdi24/presentation/hou) |
|  |  | *Optional:* [Low-latency compatible PCIe](https://dl.acm.org/doi/10.1145/3555050.3569128) |
| Tue 09/29 | Interconnect II: CXL | [POND](https://dl.acm.org/doi/abs/10.1145/3575693.3578835); [CXL](https://dl.acm.org/doi/abs/10.1145/3613424.3614256) |
|  |  | *Optional:* [TPP](https://dl.acm.org/doi/abs/10.1145/3582016.3582063); [Model CXL](https://arxiv.org/abs/2410.15908) |
| Thu 10/01 | Interconnect III: CXL II | [CXL-virtual](https://www.usenix.org/system/files/osdi24-zhong-yuhong.pdf); [Octopus](https://www.usenix.org/conference/nsdi26/presentation/zhong) |
| Tue 10/06 | No class | — |
| Thu 10/08 | No class | **Project Proposal Deadline** |
| Tue 10/13 | Silicon Photonics | [sip-ML](https://dl.acm.org/doi/pdf/10.1145/3452296.3472900); [Lightning](https://people.csail.mit.edu/ghobadi/papers/lightning_sigcomm_2023.pdf) |
|  |  | *Optional:* [Server-scale SP connectivity](https://dl.acm.org/doi/pdf/10.1145/3696348.3696856) |
| Thu 10/15 | Host Network I | [Understanding the Host Network](https://www.cs.cornell.edu/~ragarwal/pubs/understanding-the-host-network.pdf); [PingPoint](https://pages.cs.wisc.edu/~mgliu/papers/PingPoint-sigcomm26.pdf) |
|  |  | *Optional:* [Hostping](https://www.usenix.org/conference/nsdi23/presentation/liu-kefei); [HostCC](https://dl.acm.org/doi/10.1145/3603269.3604878); [Federated Cache](https://arxiv.org/abs/2504.16324) |
| Tue 10/20 | Host Network II | [GH](https://dl.acm.org/doi/abs/10.1145/3673038.3673110); [AMD Exascale](https://computermachines.org/joe/publications/pdfs/isca2024_exascale.pdf) |
| Thu 10/22 | FPGA-based computing/networking | [Faery](https://www.usenix.org/system/files/osdi22-zeng.pdf); [ACCL+](https://www.usenix.org/system/files/osdi24-he.pdf) |
|  |  | *Optional:* [OS abstraction](https://www.usenix.org/system/files/osdi20-korolija.pdf); [DUA](https://www.usenix.org/conference/nsdi19/presentation/shu) |

---

### OS layer

| Date | Topic | Readings |
|---|---|---|
| Tue 10/27 | Software network stacks | [Understanding Overheads](https://www.cs.cornell.edu/~ragarwal/pubs/network-stack.pdf); [NetChannel](https://dl.acm.org/doi/10.1145/3544216.3544230) |
|  |  | *Optional:* [Shenango](https://dl.acm.org/doi/10.5555/3323234.3323265); [eRPC](https://www.usenix.org/system/files/nsdi19-kalia.pdf) |
| Thu 10/29 | Hardware network stacks | [ZeroNIC](https://www.usenix.org/system/files/osdi24-skiadopoulos.pdf); [FlexTOE](https://www.usenix.org/system/files/nsdi22-paper-shashidhara.pdf) |
|  |  | *Optional:* [Tonic](https://www.cs.princeton.edu/~jrex/papers/tonic.pdf); [BlueField](https://arxiv.org/abs/2402.03041) |
| Tue 11/03 | No class | — |
| Thu 11/05 | Storage stacks | [XRP](https://www.usenix.org/conference/osdi22/presentation/zhong); [blk-switch](https://www.usenix.org/conference/osdi21/presentation/hwang) |
|  |  | *Optional:* [FlashShare](https://www.usenix.org/conference/osdi18/presentation/zhang) |
| Tue 11/10 | Remote storage stacks | [i10](https://www.usenix.org/system/files/nsdi20-paper-hwang.pdf); [nvme-tcp](https://www.usenix.org/conference/nsdi25/presentation/kang) |
| Thu 11/12 | CPU scheduling | [ZygOS](https://dl.acm.org/doi/10.1145/3132747.3132780); [Caladan](https://dl.acm.org/doi/10.5555/3488766.3488782) |
|  |  | *Optional:* [Arachne](https://www.usenix.org/conference/osdi18/presentation/qin); [Syrup](https://dl.acm.org/doi/10.1145/3477132.3483548) |
| Tue 11/17 | Memory management | [Colloid](https://dl.acm.org/doi/10.1145/3694715.3695968); [TMO](https://dl.acm.org/doi/10.1145/3503222.3507731) |
|  |  | *Optional:* [MEMTIS](https://dl.acm.org/doi/abs/10.1145/3600006.3613167) |
| Thu 11/19 | I/O Memory protection | [F&S](https://www.cs.cornell.edu/~ragarwal/pubs/fands.pdf); [Scalable IOMMU](https://www.usenix.org/conference/atc15/technical-session/presentation/peleg) |
|  |  | *Optional:* [vIOMMU](https://www.usenix.org/legacy/events/atc11/tech/final_files/Amit.pdf); [V-PROBE](https://www.usenix.org/system/files/atc23-wang-yaohui.pdf) |
| Tue 11/24 | I/O Virtualization | [PicNIC](https://dl.acm.org/doi/10.1145/3341302.3342093); [FreeFlow](https://www.usenix.org/conference/nsdi19/presentation/kim) |
|  |  | *Optional:* [FVM](https://www.usenix.org/system/files/osdi20-kwon.pdf) |

---

### ML Sys

| Date | Topic | Readings |
|---|---|---|
| Thu 11/26 | No class | — |
| Tue 12/01 | System for inference | [vLLM](https://arxiv.org/pdf/2309.06180); [DistServe](https://www.usenix.org/conference/osdi24/presentation/zhong-yinmin) |
|  |  | *Optional:* [Parrot](https://www.usenix.org/system/files/osdi24-lin-chaofan.pdf); [AQUA](https://dl.acm.org/doi/pdf/10.1145/3676641.3715983) |
| Thu 12/03 | System for training | [NCCL](https://arxiv.org/pdf/2507.04786); [DeepSeek-v3](https://arxiv.org/pdf/2505.09343) |

---

### Project presentations

| Date | Topic | Readings |
|---|---|---|
| Tue 12/08 | No class | **Final Report Deadline** |
