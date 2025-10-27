# **RISC-V** **based Open-Source GPU Architecture and Design Exploration**



![img](https://raw.githubusercontent.com/chenweiphd/typopic/master/%E8%AF%BE%E7%A8%8Blogo.png)

## Passing the Torch to Cultivate the Next Generation of Turing Award Laureates  

As a core direction in the strategic priorities of the global chip industry and technology powerhouses, RISC-V, with its efficient instruction set, royalty-free licensing, and flexible extensibility, is reshaping the technical landscape of GPUs in large language model computing. This course focuses on the hot interdisciplinary frontiers of RISC-V open-source architecture and GPU design, constructing an exploratory knowledge system spanning from instruction sets to many-core computing architectures. It aims to achieve entry into RISC-V GPU architecture in the shortest path while exploring the application potential of technologies such as 2.5D/3D/3.5D Chiplet and open-source EDA in open-source GPUs. Beyond passing the torch of knowledge, the course takes "cultivating the next generation of Turing Award laureates" as its ultimate goal. Through a trinity training model of "theory-practice-innovation," it inspires students' deep insights into core architectures and their ability to innovate disruptively.  

The core content covers: integrated design of RISC-V Instruction Set Architecture (ISA) and GPU parallel computing architectures; open-source GPU core modules (e.g., stream processors, memory architecture, TensorCore); and principles and exploratory implementations of core compilers. Building on this, the course extends to cutting-edge research areas: On one hand, relying on C-Model simulation and FPGA prototypes/OpenEDA chip prototype verification platforms, students must complete the full chip design process from architectural modeling, functional verification to deployment implementation, honing their "from-scratch" system-level design capabilities through practice. On the other hand, the course focuses on pain points in computational demands of large language models (LLM/Transformer), guiding students to explore architectural optimization strategies for open-source RISC-V GPUs in scenarios like tensor computation and mixed-precision training, and even challenging frontier topics such as "custom instruction extensions" and "memory compute integration units."  

![image-20251018175829993](https://raw.githubusercontent.com/chenweiphd/typopic/master/image-20251018175829993.png)

To meet the needs of cultivating "Turing Award-caliber" talent, the course breaks traditional teaching boundaries, adopting a "problem-driven + academic symbiosis" model: On one hand, it sets up project clusters for "Open-Source GPU Architecture Exploration," training students to team up and complete academically competitive prototype designs—from analyzing performance bottlenecks in existing open-source GPUs, to proposing new parallel computing units based on RISC-V extended instructions, and validating optimization effects through simulation and testing, simulating the entire process of top research teams' breakthroughs. On the other hand, the course deeply collaborates with the global RISC-V Foundation, open-source GPU communities, and top university labs, allowing students to directly contribute to open-source projects and even lead sub-project research, accumulating international academic influence. Additionally, the course invites leading figures in GPU architecture and chief architects of top AI chip companies to host specialized seminars, sparking intellectual exchanges on topics like "evolution of open-source RVGPU architecture" and "reconstruction of computing paradigms by open-source ecosystems," inspiring students' forward-looking expansion and exploration of technological trends.  

The course emphasizes dual cultivation of research thinking and industrial literacy in the "Berkeley mode": fostering students' resilience in facing technical challenges, guiding reflection on the social value of technological innovation through "architectural design," and breaking down disciplinary barriers via "interdisciplinary collisions" (e.g., cross-domain discussions with computer architecture, artificial intelligence, and integrated circuits). Ultimately, students will possess the hard power to independently conduct cutting-edge architecture research—able to delve into micro-architectural details of RISC-V GPUs while gaining insight into the essence of computing beyond technical specifics; mastering solid simulation and verification toolchains while driving technical consensus in open-source communities.  

From the intricacies of the RISC-V instruction set to the grand design of GPU many-core architectures, from the rigorous logic of simulation and verification to collaborative innovation in open-source ecosystems, this course not only imparts knowledge but also strives to ignite students' passion for computing architecture, cultivating them into next-generation computing architecture leaders with technical depth, innovative courage, and academic vision. We believe this course will produce pioneers defining processor and AI computing paradigms for the next decade, and perhaps even nurture future Turing Award laureates.



## Syllabus（2025/Draft）



**RISC-V based Open-Source GPU Architecture and Design Exploration（Open Course）**

| Week    | Date     | Daily Topic of Teaching Content                              | Guest/Video Sharing Content                                  | Technical Report Content                                     |
| ------- | -------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 课周    | 日期     | 授课内容当天主题                                             | 嘉宾分享内容                                                 | 技术报告内容                                                 |
|         |          | 9:00-9:50                                                    | 10:00-10:50                                                  | 11:00-11:50                                                  |
| Week 1  | 10月18日 | Course Overview and GPU Introduction                         | UC Berkeley: Berkeley Approach to Graduate Education in EECS（David Patterson Video） | Data Format and Converter Design in GPU                      |
|         |          | RIOS与零一代表讲话 课程概述与GPU简介（陈）                   | 加州伯克利：伯克利EECS教学模式（大卫·帕特森）                | GPU中的数据格式与转换                                        |
| Week 2  | 10月25日 | SoC Design Flow and OpenEDA                                  | UC San Diego: OpenROAD-The journey so far and roadmap (Andrew Kahng) | OpenTensorCore Architecture<br>Open3DNoC Architecture        |
|         |          | SoC设计流程与OpenEDA（陈）                                   | 加州圣地亚哥：OpenROAD进展与路线图（Andrew Kahng）           | OpenTensorCore 架构 <br/>Open3DNoC 架构                      |
| Week 3  | 11月1日  | RISC-V Instruction Set and Architecture                      | Synopsys：Advanced Design Flow                               | OpenRoad Architecture Analysis <br/>llama.cpp Arcitecture Analysis |
|         |          | RISC-V指令集与架构（任）                                     |                                                              | OpenRoad架构分析 <br>llama.cpp架构分析                       |
| Week 4  | 11月8日  | GPU Architecture and Open-Source RISC-V GPU                  | Tsinghua: Introduction to Ventus GPGPU Architecture          | RVGPU Architecture                                           |
|         |          | GPU架构与开源RISC-V GPU（任、陈）                            |                                                              |                                                              |
| Week 5  | 11月15日 | 2.5D/3D/3.5D Architecture and Memory Compute Integration     | DeToolIC: EDA Design Flow for Advanced Packaging/ Integration | GigaDevice: Advanced Memory (HBM or Hybrid Bonding DRAM)     |
|         |          | 2.5D/3D/3.5D架构与存算一体（任、陈）                         |                                                              |                                                              |
| Week 6  | 11月22日 | Tensor Core (TensorCore) and Transformer                     | Introduction to TPU Architecture                             | Technical Report                                             |
|         |          | 张量核心（TensorCore）与Transformer                          |                                                              |                                                              |
| Week 7  | 11月29日 | Memory Architecture and On-Chip Network (NoC)                | Technical Report                                             | Technical Report                                             |
|         |          | 存储架构与片上网络（NoC）                                    |                                                              |                                                              |
| Week 8  | 12月6日  | GPU Programming with CUDA/OpenCL                             | A Compilation Platform                                       | Technical Report                                             |
|         |          | GPU编程与CUDA/OpenCL                                         |                                                              |                                                              |
| Week 9  | 12月13日 | GPU Compiler and Triton                                      | High-Level Compiler Platform                                 | Technical Report                                             |
|         |          | GPU编译器与Triton                                            |                                                              |                                                              |
| Week 10 | 12月20日 | GPU Deployment Acceleration and DeepSeek Optimization Principles | Cross-Platform Acceleration Framework                        | Technical Report                                             |
|         |          | GPU部署加速与deepseek优化原理                                |                                                              |                                                              |

## Exploring Projects

OpenTensorCore

Open3DNoC

OpenRVGPU

OpenLLMRoad



## Guest Expert



## Main Contributor of Lecture 

![image-20251018172931236](https://raw.githubusercontent.com/chenweiphd/typopic/master/image-20251018172931236.png)

<img width="933" height="62" alt="image" src="https://github.com/user-attachments/assets/39c5d16e-9783-49a6-b9ed-25f4c363db97" />


