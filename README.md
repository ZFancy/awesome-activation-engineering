<h1 align="center"><b>Awesome Activation Engineering</b></h1>

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="awesome"></a>
  <img src="https://img.shields.io/github/stars/ZFancy/awesome-activation-engineering?color=yellow&label=Star" alt="Stars" >
</p>

A curated list of research papers and resources related to **Activation Engineering** for Large Language Models (LLMs). This repository focuses on understanding and manipulating model activations toward building more transparent and controllable powerful intelligent.

This repo delves into key areas such as concept representation, concept activation detection, and activation vector steering. The goal is to investigate how concepts are represented within LLMs, how these concepts can be activated or detected during model inference, and how to manipulate activation vectors for more targeted control over model behavior. By building on these ideas, we may unlock new methods for improving interpretability, increasing model control, and fostering more ethical and reliable deployment of LLMs in various applications.

This repo serves as a resource for researchers and developers interested in the inner workings of neural networks and LLMs, offering tools, techniques, and experimental findings for advancing the field of activation engineering. Ongoing update.

> *If some related papers are missing, please contact us via pull requests :)*

## Outline of this repo

- [Categories](#categories)
  - [Concept Representation](#concept-representation)
  - [Concept Activation Detection](#concept-activation-detection)
  - [Activation Vector Steering](#activation-vector-steering)
  - [Relevant Repo and Blog](#relevant-repo-and-blog)

## Categories

### Concept Representation
Papers and resources that explore how concepts are represented in model hidden states.

- [ICLR 2025] - **The Geometry of Categorical and Hierarchical Concepts in Large Language Models** - Kiho Park, Yo Joong Choe, Yibo Jiang, Victor Veitch. [[Paper](https://arxiv.org/abs/2406.01506)][[Code](https://github.com/KihoPark/LLM_Categorical_Hierarchical_Representations)]
- [NeurIPS 2024] - **From Causal to Concept-Based Representation Learning** - Goutham Rajendran, Simon Buchholz, Bryon Aragam, Bernhard Schölkopf, Pradeep Kumar Ravikumar. [[Paper](https://openreview.net/forum?id=r5nev2SHtJ)] [[Code](link)]
- [ICML 2024] - **The Linear Representation Hypothesis and the Geometry of Large Language Models** - Kiho Park, Yo Joong Choe, Victor Veitch, 2023-11. [[PDF](https://arxiv.org/abs/2311.03658)] [[Code](https://github.com/KihoPark/linear_rep_geometry)]
- [ICLR 2024] - **Demystifying Embedding Spaces using Large Language Models** - Guy Tennenholtz, Yinlam Chow, Chih-Wei Hsu, Jihwan Jeong, Lior Shani, Azamat Tulepbergenov, Deepak Ramachandran, Martin Mladenov, Craig Boutilier, 2023-10. [[PDF](https://arxiv.org/abs/2310.04475)]
- [ACL 2022] - **Extracting Latent Steering Vectors from Pretrained Language Models** - Nishant Subramani, Nivedita Suresh, Matthew E. Peters, 2022-05. [[PDF](https://arxiv.org/abs/2205.05124)] [[Code](https://github.com/nishantsubramani/steering_vectors)]

### Concept Activation Detection
Research on methods to detect and identify specific concepts or features in activations.

- **Visual-TCAV: Concept-based Attribution and Saliency Maps for Post-hoc Explainability in Image Classification** - Antonio De Santis, Riccardo Campi, Matteo Bianchi, Marco Brambilla, 2024-11. [[PDF](https://arxiv.org/abs/2411.05698)]
- **Decision Trees for Interpretable Clusters in Mixture Models and Deep Representations** - Maximilian Fleissner, Maedeh Zarvandi, Debarghya Ghoshdastidar, 2024-11. [[PDF](https://arxiv.org/abs/2411.01576)]
- **Exploiting Text-Image Latent Spaces for the Description of Visual Concepts** - Laines Schmalwasser, Jakob Gawlikowski, Joachim Denzler, Julia Niebling, 2024-10. [[PDF](https://arxiv.org/abs/2410.17832)]
- **KTCR: Improving Implicit Hate Detection with Knowledge Transfer driven Concept Refinement** - Samarth Garg, Vivek Hruday Kavuri, Gargi Shroff, Rahul Mishra, 2024-10. [[PDF](https://arxiv.org/abs/2410.15314)]
- **LG-CAV: Train Any Concept Activation Vector with Language Guidance** - Qihan Huang, Jie Song, Mengqi Xue, Haofei Zhang, Bingde Hu, Huiqiong Wang, Hao Jiang, Xingen Wang, Mingli Song, 2024-10. [[PDF](https://arxiv.org/abs/2410.10308)] [[Code](https://github.com/hqhQAQ/LG-CAV)]
- **Looking into Concept Explanation Methods for Diabetic Retinopathy Classification** - Andrea M. Storås, Josefine V. Sundgaard, 2024-10. [[PDF](https://arxiv.org/abs/2410.03188)]
- **EQ-CBM: A Probabilistic Concept Bottleneck with Energy-based Models and Quantized Vectors** - Sangwon Kim, Dasom Ahn, Byoung Chul Ko, In-su Jang, Kwang-Ju Kim, 2024-09. [[PDF](https://arxiv.org/abs/2409.14630)]
- **TextCAVs: Debugging vision models using text** - Angus Nicolson, Yarin Gal, J. Alison Noble, 2024-08. [[PDF](https://arxiv.org/abs/2408.08652)]
- **Uncovering Safety Risks in Open-source LLMs through Concept Activation Vector** - Zhihao Xu, Ruixuan Huang, Xiting Wang, Fangzhao Wu, Jing Yao, Xing Xie, 2024-04. [[PDF](https://arxiv.org/abs/2404.12038)]
- **Explaining Explainability: Understanding Concept Activation Vectors** - Angus Nicolson, Lisa Schut, J. Alison Noble, Yarin Gal, 2024-04. [[PDF](https://arxiv.org/abs/2404.03713)]

### Activation Vector Steering
Methods about steering or manipulating activation vectors to influence model behavior or outputs.

- **Can sparse autoencoders be used to decompose and interpret steering vectors?** - Harry Mayne, Yushi Yang, Adam Mahdi, 2024-11. [[PDF](https://arxiv.org/abs/2411.08790)] [[Code](https://github.com/HarryMayne/SV_interpretability)]
- **Extracting Unlearned Information from LLMs with Activation Steering** - Atakan Seyitoğlu, Aleksei Kuvshinov, Leo Schwinn, Stephan Günnemann, 2024-11. [[PDF](https://arxiv.org/abs/2411.02631)]
- **Improving Steering Vectors by Targeting Sparse Autoencoder Features** - Sviatoslav Chalnev, Matthew Siu, Arthur Conmy, 2024-11. [[PDF](https://arxiv.org/abs/2411.02193)] [[Code](https://github.com/slavachalnev/SAE-TS)]
- **Improving Instruction-Following in Language Models through Activation Steering** - Alessandro Stolfo, Vidhisha Balachandran, Safoora Yousefi, Eric Horvitz, Besmira Nushi, 2024-10. [[PDF](https://arxiv.org/abs/2410.12877)]
- **Semantics-Adaptive Activation Intervention for LLMs via Dynamic Steering Vectors** - Weixuan Wang, Jingyuan Yang, Wei Peng, 2024-10. [[PDF](https://arxiv.org/abs/2410.12299)] [[Code](https://github.com/weixuan-wang123/SADI)]
- **Activation Scaling for Steering and Interpreting Language Models** - Niklas Stoehr, Kevin Du, Vésteinn Snæbjarnarson, Robert West, Ryan Cotterell, Aaron Schein, 2024-10. [[PDF](https://arxiv.org/abs/2410.04962)] [[Code](https://github.com/niklasstoehr/activationScaling)]
- **Uncovering Latent Chain of Thought Vectors in Language Models** - Jason Zhang, Scott Viteri, 2024-09. [[PDF](https://arxiv.org/abs/2409.14026)]
- **Householder Pseudo-Rotation: A Novel Approach to Activation Editing in LLMs with Direction-Magnitude Perspective** - Van-Cuong Pham, Thien Huu Nguyen, 2024-09. [[PDF](https://arxiv.org/abs/2409.10053)]
- **Analyzing the Generalization and Reliability of Steering Vectors** - Daniel Tan, David Chanin, Aengus Lynch, Dimitrios Kanoulas, Brooks Paige, Adria Garriga-Alonso, Robert Kirk, 2024-07. [[PDF](https://arxiv.org/abs/2407.12404)]
- **Future Events as Backdoor Triggers: Investigating Temporal Vulnerabilities in LLMs** - Sara Price, Arjun Panickssery, Sam Bowman, Asa Cooper Stickland, 2024-07. [[PDF](https://arxiv.org/abs/2407.04108)]
- **Steering Without Side Effects: Improving Post-Deployment Control of Language Models** - Asa Cooper Stickland, Alexander Lyzhov, Jacob Pfau, Salsabila Mahdi, Samuel R. Bowman, 2024-06. [[PDF](https://arxiv.org/abs/2406.15518)] [[Code](https://github.com/AsaCooperStickland/kl-then-steer)]
- **Who's asking? User personas and the mechanics of latent misalignment** - Asma Ghandeharioun, Ann Yuan, Marius Guerard, Emily Reif, Michael A. Lepori, Lucas Dixon, 2024-06. [[PDF](https://arxiv.org/abs/2406.12094)]
- **Controlling Large Language Model Agents with Entropic Activation Steering** - Nate Rahn, Pierluca D'Oro, Marc G. Bellemare, 2024-06. [[PDF](https://arxiv.org/abs/2406.00244)]
- **Adaptive Activation Steering: A Tuning-Free LLM Truthfulness Improvement Method for Diverse Hallucinations Categories** - Tianlong Wang, Xianfeng Jiao, Yifan He, Zhongzhi Chen, Yinghao Zhu, Xu Chu, Junyi Gao, Yasha Wang, Liantao Ma, 2024-06. [[PDF](https://arxiv.org/abs/2406.00034)]
- **Activation Steering for Robust Type Prediction in CodeLLMs** - Francesca Lucchetti, Arjun Guha, 2024-04. [[PDF](https://arxiv.org/abs/2404.01903)]
- **Extending Activation Steering to Broad Skills and Multiple Behaviours** - Teun van der Weij, Massimo Poesio, Nandi Schoots, 2024-03. [[PDF](https://arxiv.org/abs/2403.05767)] [[Code](https://github.com/TeunvdWeij/extending-activation-addition)]
- **Towards Tracing Trustworthiness Dynamics: Revisiting Pre-training Period of Large Language Models** - Chen Qian, Jie Zhang, Wei Yao, Dongrui Liu, Zhenfei Yin, Yu Qiao, Yong Liu, Jing Shao, 2024-02. [[PDF](https://arxiv.org/abs/2402.19465)] [[Code](https://github.com/ChnQ/TracingLLM)]
- **MiMiC: Minimally Modified Counterfactuals in the Representation Space** - Shashwat Singh, Shauli Ravfogel, Jonathan Herzig, Roee Aharoni, Ryan Cotterell, Ponnurangam Kumaraguru, 2024-02. [[PDF](https://arxiv.org/abs/2402.09631)]
- **Investigating Bias Representations in Llama 2 Chat via Activation Steering** - Dawn Lu, Nina Rimsky, 2024-02. [[PDF](https://arxiv.org/abs/2402.00402)]
- **InferAligner: Inference-Time Alignment for Harmlessness through Cross-Model Guidance** - Pengyu Wang, Dong Zhang, Linyang Li, Chenkun Tan, Xinghao Wang, Ke Ren, Botian Jiang, Xipeng Qiu, 2024-01. [[PDF](https://arxiv.org/abs/2401.11206)] [[Code](https://github.com/Jihuai-wpy/InferAligner)]
- **Steering Llama 2 via Contrastive Activation Addition** - Nina Rimsky, Nick Gabrieli, Julian Schulz, Meg Tong, Evan Hubinger, Alexander Matt Turner, 2024-12. [[PDF](https://arxiv.org/abs/2312.06681)] [[Code](https://github.com/nrimsky/CAA)]
- **Improving Activation Steering in Language Models with Mean-Centring** - Ole Jorgensen, Dylan Cope, Nandi Schoots, Murray Shanahan, 2023-12. [[PDF](https://arxiv.org/abs/2312.03813)]
- **Backdoor Activation Attack: Attack Large Language Models using Activation Steering for Safety-Alignment** - Haoran Wang, Kai Shu, 2023-11. [[PDF](https://arxiv.org/abs/2311.09433)] [[Code](https://github.com/wang2226/Backdoor-Activation-Attack)]
- **Activation Addition: Steering Language Models Without Optimization** - Alexander Matt Turner, Lisa Thiergart, David Udell, Gavin Leech, Ulisse Mini, Monte MacDiarmid, 2023-08. [[PDF](https://arxiv.org/abs/2308.10248)] [[Code](https://github.com/montemac/activation_additions)]

### Relevant Repo and Blog

- [Activation Engineering - LessWrong](https://www.lesswrong.com/w/activation-engineering)
- [Awesome Representation Engineering](https://github.com/chrisliu298/awesome-representation-engineering)

## Contributing
We welcome contributions to this list! If you have a paper, tool, or resource that fits into one of the categories, please submit a pull request or open an issue.

1. Fork the repository.
2. Add your contribution to the appropriate section.
3. Submit a pull request with a brief description of your changes.

## License
This project is licensed under the [MIT License](LICENSE).

---

**Disclaimer**: This repository is for educational and research purposes only. The papers and resources listed here are the property of their respective authors and organizations.
