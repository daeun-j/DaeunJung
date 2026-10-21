### About Me

I am a Ph.D. student in Computer Science at the **University of Maryland, College Park**, advised by **Prof. Ang Li**.

My research focuses on **trustworthy AI**, with a particular interest in how AI systems handle uncertainty, learn from data, and make decisions based on incomplete or imperfect information.

One question that drives my research is: **How can we tell whether an AI system's decisions are genuinely supported by the information it has learned or observed?**

I have explored this question from different perspectives. In **machine unlearning**, I study whether models actually remove the influence of training data or simply stop producing certain outputs. In **genomic privacy**, I investigate how sensitive information can be exposed through learned models. More recently, I have been working on **clinical AI agents**, focusing on how they interpret uncertain patient responses, decide what information to gather next, and verify that their conclusions are supported by clinical evidence.

Beyond model reliability, I am also interested in making large-scale AI systems more efficient. My experience includes optimizing LLM inference through **CUDA/HIP kernels, speculative prefill, and KV-cache optimization**.

Ultimately, I want to develop AI systems that can reason reliably under uncertainty, recognize when they need more information, and provide decisions that we can meaningfully verify.

### Research Interests

- **Trustworthy AI & Machine Unlearning:** Understanding how training data influences model behavior, distinguishing genuine knowledge removal from behavioral suppression, and developing methods to evaluate these effects.
- **Uncertainty-Aware Reasoning & AI Agents:** Representing uncertain evidence, updating beliefs, and deciding what information to seek during multi-step reasoning.
- **Clinical AI & Evidence-Grounded Verification:** Building diagnostic agents that handle incomplete patient information and verifying clinical findings against medical evidence.
- **Privacy-Preserving Machine Learning:** Investigating privacy leakage and information control in genomic foundation models and distributed learning.
- **Efficient LLM Inference:** Improving inference performance through GPU kernel optimization, speculative prefill, and memory-efficient computation.

## Research & Publications

### Under Review

**Exposure Leaves a Trace: A Provenance Audit for Machine Unlearning**  
Daeun Jung and Ang Li.  
*International Conference on Learning Representations (ICLR 2027)* — Under Review.

**Privacy Risks of Federated Genomic Foundation Models for Multi-institutional Digital Medicine**  
Daeun Jung, Ziyao Wang, Jiaheng Guo, Song Wang, Tianlong Chen, and Ang Li.  
*npj Digital Medicine* — Under Review, 2026.

**FedMOA: Federated GRPO for Personalized Reasoning LLMs under Heterogeneous Rewards**  
Ziyao Wang\*, Daeun Jung\*, Yexiao He, Guoheng Sun, Zheyu Shen, Myungjin Lee, and Ang Li.  
*ACL Rolling Review (ARR), October 2026 Cycle* — Under Review.  
\* Equal contribution.

### International Conferences

- [Feature Expansion of Single Dimensional Time Series Data for Machine Learning Classification](/pdf/ICUFN2021.pdf) — First author.
- [Traffic Data Classification using Machine Learning Algorithms in SDN Networks](/pdf/ICTC2020.pdf) — Co-first author.
- [An Iterative Algorithm of Key Feature Selection for Multi-class Classification](/pdf/ICUFN2019.pdf) — First author.

### Domestic Conferences

- **Impact of Input Data Randomness on Training Performance of Autoencoder** — Second author, **Best Paper Award**.
- On Improving Network Data Anomaly Detection Performance based on Meta Characteristics — Second author.
- Machine Learning-based Algorithm for Small-scale Multi-featured Data Classification — First author.
- Study on Impact of Class Combinations on Performance of Multi-class Classification — First author.

### Domestic Journal Articles

- Survey on Machine Learning Algorithms for SDN/NFV Automation — Second author.

## Experience

### University of Maryland, College Park
**Graduate Research Assistant** | Aug. 2022 – Present

- Investigate causal data influence and representation-level auditing in large language models, particularly the distinction between knowledge removal and behavioral suppression.
- Study privacy risks in genomic foundation models and personalized reasoning under heterogeneous learning objectives.
- Develop uncertainty-aware clinical reasoning methods and evidence-grounded medical AI systems.

**Teaching Assistant** | Aug. 2022 – May 2023

- Advanced Data Structures (CMSC 420)
- Discrete Structures (CMSC 250)
- Led discussion sessions and supported students in understanding algorithms, data structures, and mathematical reasoning.

### Runara.ai
**Research Intern** | May 2026 – Jul. 2026

- Optimized large language model inference using **vLLM, CUDA, and HIP** across NVIDIA H100 and AMD MI300X GPUs.
- Developed and benchmarked fused transformer kernels, achieving up to **2.17× single-operation speedup** and **1.24× end-to-end speedup**.
- Evaluated speculative prefill for GPT-OSS-120B, achieving **3.70–3.88× reduction in target-model time to first token** in benchmarked settings.
- Investigated KV-cache optimization and quantization for efficient inference of large reasoning models.

### Carnegie Mellon University
**Visiting Scholar** | Jan. 2020 – Jul. 2020

- Full scholarship recipient for the Intensive AI Program supported by the Ministry of Science and ICT.
- Developed NLP-based conversational systems and worked on large-scale multimedia generation using GANs and AWS.
- Led system architecture design and explored recommendation algorithms, including collaborative and content-based filtering.

## Honors & Awards

- **Best Paper Award**, KICS Summer Conference, 2021.
- Research Assistant Scholarship, Ewha Womans University, 2020.
- Dean's List, Ewha Womans University, 2015, 2017, 2018.
