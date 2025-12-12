---
title: "Resume"
date: 2025-11-21
description: "My professional resume and work experience"
draft: false
---

# David Yang (aka anion)

*   Currently Studying
*   anionex@qq.com
*   [https://github.com/Anionex](https://github.com/Anionex)

---

## Education

**Jinan University (JNU)** [Project 211, Double First-Class University] | Computer Science and Technology | Undergraduate | 2023-09 ~ 2027-06  
Full-time | School of Information Science and Technology | Guangzhou, China

---

## Professional Skills

### Algorithms and Data Structures
Proficient in various algorithms and data structures, capable of applying dynamic programming, greedy algorithms, backtracking, divide and conquer, and other algorithms to solve practical problems. Have won awards in algorithm competitions including NOI, CSP, and Blue Bridge Cup.

### Version Control (Git) and Collaborative Development
Familiar with Git tools, with experience in team collaboration and open-source project participation. Have contributed code to large projects (GitHub repositories with thousands to tens of thousands of stars) and received community recognition.

### Web Application Development and Operations
Proficient in modern web application development technologies. Have served as a technical backbone in multiple projects, using frameworks such as Django and Flask to build web applications. Possess basic Linux operations skills, capable of independently completing web application deployment and management; have experience with Docker containerization deployment.

### Large Model Engineering
Experienced in fine-tuning, quantization, and inference performance optimization of large models. Proficient in deploying and performance tuning of large language models on inference frameworks including but not limited to Ktransformers, vLLM, and llama.cpp. Related projects have participated in national-level competitions and won national awards.

### AI Application Development
Familiar with AI application development technologies such as prompt engineering basics, model fine-tuning, RAG, and the use of frameworks such as LangChain and Agently Workflow, with related project experience. Familiar with building workflows and agents using platforms such as Dify and Coze, and applying them to improve efficiency in daily learning and work.

---

## Major Awards and Honors

1.  2025 "Challenge Cup" China Youth Science and Technology Innovation "Unveiling and Leading" Arena National Grand Prize (Top 0.1%)
2.  19th "Challenge Cup" National College Students' Extracurricular Academic Science and Technology Works Competition 2024 "Unveiling and Leading" Special Competition National First Prize
3.  14th "China Software Cup" College Students Software Design Competition Finals, General Higher Education Group, National Third Prize
4.  2025 Jinan University Outstanding Students Commendation Conference - Innovation and Entrepreneurship Practice Award
5.  Yi Chuang Xing - 2024 Shenzhen Nanshan District 7th College Students Social Innovation Project Competition Silver Award, Shuqi Youth Innovation Leadership Special Award, Best Popularity Award
6.  Jinan University 2024 College Students New Liberal Arts Practice Innovation School-level Gold Award, National-level Bronze Award
7.  National Olympiad in Informatics (NOIP) First Prize

---

## Project Experience

### Project 1: Intelligent Industrial Quality Inspection System Based on Deep Learning
(This project won the National First Prize in the 19th "Challenge Cup" National College Students' Extracurricular Academic Science and Technology Works Competition 2024 "Unveiling and Leading" Special Competition)

**Project Features:**

**1. High-Precision Detection**  
Advanced Algorithm Application: Adopts the YOLOv10 object detection model developed by Tsinghua University, leveraging self-attention mechanisms and non-maximum suppression training techniques to achieve precise identification of tiny, hidden defects in industrial products, breaking through the precision bottleneck of traditional quality inspection methods.  
Model Optimization and Training: To address the scarcity of real defect images, innovatively applies overlapping small window cutting + RandAugment dual augmentation strategies to expand the dataset, and improves small target detection accuracy through slice-assisted super inference algorithms, continuously adjusting model parameters; experiments prove that this solution can effectively reduce missed detection rates and false detection rates.

**2. Efficient and Lightweight Deployment**  
Fast Processing Capability: Based on the Ascend 910B NPU hardware acceleration platform, combined with mixed precision training technology and ModelArts customized images, builds a ready-to-use model training environment, significantly improving computing resource utilization; during the inference phase, reduces memory usage through block processing and accelerates detection speed.

**3. Intelligent Analysis and Feedback**  
Data Analysis and Report Generation: Developed a quality inspection application based on HarmonyOS NEXT, integrating real-time image acquisition, detection result display, historical record storage and filtering, data visualization, and detection report generation functions, providing strong data support for enterprises to optimize production processes and improve product quality.

**4. Autonomous and Controllable Technology Integration**  
Full-Link Closed Loop: Connects the complete technology chain of algorithm design (YOLOv10), platform training (ModelArts), hardware acceleration (Ascend 910B), and terminal application (HarmonyOS), forming a domestically produced technology solution.

**5. Scalability Design:**  
Through environment image encapsulation and standardized documentation construction, ensures that the training process is reproducible and the deployment solution is transferable, providing a replicable practical case for the intelligent upgrading of the manufacturing industry.

---

### Project 2: Smart Model Ascend Computing - Large Model System Optimization Solution Based on Fully Autonomous Technology Stack with Software-Hardware Collaboration
(This project won the 2025 "Challenge Cup" China Youth Science and Technology Innovation "Unveiling and Leading" Arena National Grand Prize, ranking Top 0.1%)

**Project Overview:**  
The "Smart Model Ascend Computing" project is a software-hardware collaborative large model system optimization solution. This solution covers the full-link process from large model accuracy improvement, performance enhancement to edge deployment, and designs and develops a personalized intelligent learning application that can run offline on the native HarmonyOS operating system. The project combines full-stack autonomous and controllable technology, using engine optimization, model quantization, operator optimization and other means to significantly improve model inference throughput, and ultimately won the top position in the competition algorithm ranking. In addition, the team contributed more than 600 lines of code to well-known high-performance inference engine projects and received community recognition, making beneficial explorations and contributions to the large model and computing power ecosystem.

**Project Highlights:**

**Efficient Model Optimization**  
Precise Capability Transfer: Applies inference distillation technology, combined with improved algorithms such as SFT LoRA+ and RSLORA, to efficiently transfer the inference capabilities of the teacher large model to the target model, improving core capabilities such as code and mathematics by an average of 8%, while successfully controlling the loss of other capabilities within 2%.

**Full-Stack Performance Acceleration**  
Three-Level Collaborative Optimization: Constructs a three-level acceleration system of "engine-model-operator", through Ascend ACL graph compilation and in-depth development of key operators (siluandmul/rmsnorm), achieving a 110% improvement in total throughput relative to the baseline, with a single-card peak performance of 800 TPS. Won first place in the performance ranking and second place overall.

**Lightweight Edge Deployment**  
Ultimate Model Compression: Based on the Ascend toolchain, implements W4A8 dynamic quantization, combined with algorithms such as SmoothQuant, compressing model memory usage by 62% while maintaining core metrics above 90% of the original precision, successfully deploying on resource-constrained terminal devices.

**Open Source Ecosystem Contribution**  
Contribution to Well-Known Projects: Participated in the open-source community and contributed more than 600 lines of code to the internationally renowned inference engine vLLM-project, implementing complete functionality and testing for new quantization versions, fixing existing model loading issues, and contributing 2 new format quantization models to the Ascend official repository, which have gone online.

**Full-Link Technology Integration**  
End-to-End Closed Loop: Successfully connects the complete technology chain from cloud model distillation, efficient fine-tuning, full-stack acceleration optimization, to HarmonyOS native application offline inference, forming a reproducible and scalable domestically produced AI solution.

---

## Research Experience

As a core member, led and participated in the conceptualization, algorithm design, and engineering implementation of the paper "TravelDesigner: A generative AI-based tourist recommendation system using large language models for travel itinerary planning".

- This work designed TravelDesigner, a generative AI travel recommendation system based on LLM agents, specifically designed to address the core problems of traditional recommendation systems that generate travel routes lacking personalization, impracticality, and poor user experience due to inherent limitations such as data sparsity and unrealistic assumptions. A major feature of this system is its ability to directly understand users' free-format input, achieving a more natural interaction experience; at the same time, it has more intelligent planning capabilities, capable of generating complete multi-day cross-city itineraries covering all travel elements; and, as proven by experiments, its recommendation quality has fully surpassed traditional professional tools, demonstrating more excellent application effects.
