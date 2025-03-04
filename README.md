<h1 align="center"><b>Awesome Activation Engineering</b></h1>

<p align="center">
  <a href="https://github.com/Zfancy/awesome-activation-engineering/pulls"><img src="https://img.shields.io/badge/PRs-Welcome-yellow" alt="PRs"></a>
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="awesome"></a>
  <img src="https://badges.toozhao.com/badges/01JKE9NZ8SDNSTTCKBASSND3D2/green.svg" />
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-red.svg" alt="Liscence"></a>
  <img src="https://img.shields.io/github/stars/ZFancy/awesome-activation-engineering?color=yellow&label=Star" alt="Stars" >
</p>

⭐ A curated list of research papers and resources related to ***Activation Engineering*** for foundation models, especially the Large Language Models (LLMs). 

### What is "Activation Engineering"?

> [!NOTE]
> **Activation engineering** (with LLMs) refers to the process of modifying or controlling the internal activation or intermediate output of neurons to analyze or influence model behavior, which is an emerging research feild related to model interpretability, neural network transparency, and controlled generation. It aims to better understand the internal workings of foundation models, particulaly with those high level concepts which are aligned with human cognitions.

### How this repo is organized?

> [!IMPORTANT]
Regarding the objectives of activation engineering in analyzing or steering model behavior with arbitrary concepts, this repo delves into the key related areas like **concept representation and extraction**, **concept activation detection**, and **concept activation steering**. The goal is to investigate how concepts are represented within the models, how these concepts can be activated or detected during model inference, and how to steer activation vectors for more targeted control over model behavior. 

-----

This repo serves as a resource for researchers and developers interested in the inner workings of neural networks and LLMs, offering methods and experimental findings for advancing the field of activation engineering, which targets to understanding and manipulating model activations toward building more transparent and controllable powerful intelligent.

>💭 *This repo is ongoing update; If some related papers are missing, please contact me via pull requests :)*

>🤗 Please also feel free to let me know if there is any mistake or any suggestion for better categorization, Thanks!

## Outline of this repo

- [Categories](#categories)
  - [Concept Representation and Extraction](#concept-representation-and-extraction)
  - [Concept Activation Detection](#concept-activation-detection)
  - [Activation Vector Steering](#activation-vector-steering)
- [Collected Related Work (Uncategoried)](#collected-related-work-uncategoried)
- [Relevant Repo and Blog](#relevant-repo-and-blog)

## Categories


### Concept Representation and Extraction
Papers and resources that explore how concepts are represented in model hidden states.

- [arXiv 2025] - **ConceptAttention: Diffusion Transformers Learn Highly Interpretable Features** - Alec Helbling, Tuna Han Salih Meral, Ben Hoover, Pinar Yanardag, Duen Horng Chau. [[Paper](https://arxiv.org/abs/2502.04320)]
- [ICLR 2025] - **Not All Language Model Features Are Linear** - Joshua Engels, Eric J Michaud, Isaac Liao, Wes Gurnee, Max Tegmark. [[Paper](https://openreview.net/forum?id=d63a4AM4hb)][[Code](https://github.com/JoshEngels/MultiDimensionalFeatures)]
- [ICLR 2025] - **The Geometry of Categorical and Hierarchical Concepts in Large Language Models** - Kiho Park, Yo Joong Choe, Yibo Jiang, Victor Veitch. [[Paper](https://arxiv.org/abs/2406.01506)][[Code](https://github.com/KihoPark/LLM_Categorical_Hierarchical_Representations)]
- [NeurIPS 2024] - **Do LLMs dream of elephants (when told not to)? Latent concept association and associative memory in transformers** - Yibo Jiang, Goutham Rajendran, Pradeep Ravikumar, Bryon Aragam. [[Paper](https://arxiv.org/abs/2406.18400)][[Code](https://openreview.net/forum?id=WJ04ZX8txM&referrer=%5Bthe%20profile%20of%20Yibo%20Jiang%5D(%2Fprofile%3Fid%3D~Yibo_Jiang2))]
- [NeurIPS 2024] - **From Causal to Concept-Based Representation Learning** - Goutham Rajendran, Simon Buchholz, Bryon Aragam, Bernhard Schölkopf, Pradeep Kumar Ravikumar. [[Paper](https://openreview.net/forum?id=r5nev2SHtJ)] [[Code](link)]
- [ICML 2024] - **The Linear Representation Hypothesis and the Geometry of Large Language Models** - Kiho Park, Yo Joong Choe, Victor Veitch. [[Paper](https://arxiv.org/abs/2311.03658)] [[Code](https://github.com/KihoPark/linear_rep_geometry)]
- [ICLR 2024] - **Demystifying Embedding Spaces using Large Language Models** - Guy Tennenholtz, Yinlam Chow, Chih-Wei Hsu, Jihwan Jeong, Lior Shani, Azamat Tulepbergenov, Deepak Ramachandran, Martin Mladenov, Craig Boutilier. [[Paper](https://arxiv.org/abs/2310.04475)]
- [ICLR 2024] - **Identifying Representations for Intervention Extrapolation** - Sorawit Saengkyongam, Elan Rosenfeld, Pradeep Ravikumar, Niklas Pfister, Jonas Peters. [[Paper](https://arxiv.org/abs/2310.04295)]
- [COLM 2024] - **The Geometry of Truth: Emergent Linear Structure in Large Language Model Representations of True/False Datasets** - Samuel Marks, Max Tegmark. [[Paper](https://arxiv.org/abs/2310.06824)]
- [ACL 2024] - **Language Models Linearly Represent Sentiment** - Curt Tigges, Oskar J. Hollinsworth, Atticus Geiger, Neel Nanda. [[Paper](https://aclanthology.org/2024.blackboxnlp-1.5.pdf)]
- [ACL 2015] - **Linguistic Regularities in Continuous Space Word Representations** - Tomas Mikolov, Wen-tau Yih, Geoffrey Zweig. [[Paper](https://aclanthology.org/N13-1090/)]

### Concept Activation Detection
Research on methods to detect and identify specific concepts or features in activations.

- [arXiv 2025] - **Identifiable Steering via Sparse Autoencoding of Multi-Concept Shifts** - Shruti Joshi, Andrea Dittadi, Sébastien Lachapelle, Dhanya Sridhar. [[Paper](https://www.arxiv.org/abs/2502.12179)]
- [arXiv 2025] - **Are Sparse Autoencoders Useful? A Case Study in Sparse Probing** - Subhash Kantamneni, Joshua Engels, Senthooran Rajamanoharan, Max Tegmark, Neel Nanda. [[Paper](https://arxiv.org/abs/2502.16681)]
- [NeurIPS 2024] - **LG-CAV: Train Any Concept Activation Vector with Language Guidance** - Qihan Huang, Jie Song, Mengqi Xue, Haofei Zhang, Bingde Hu, Huiqiong Wang, Hao Jiang, Xingen Wang, Mingli Song. [[Paper](https://arxiv.org/abs/2410.10308)] [[Code](https://github.com/hqhQAQ/LG-CAV)]
- [NeurIPS 2024] - **Uncovering Safety Risks in Open-source LLMs through Concept Activation Vector** - Zhihao Xu, Ruixuan Huang, Xiting Wang, Fangzhao Wu, Jing Yao, Xing Xie. [[Paper](https://arxiv.org/abs/2404.12038)][[Code](https://github.com/SproutNan/AI-Safety_SCAV)]
- [MICCAI 2024] - **TextCAVs: Debugging vision models using text** - Angus Nicolson, Yarin Gal, J. Alison Noble. [[Paper](https://arxiv.org/abs/2408.08652)]
- [arXiv 2024] - **Decision Trees for Interpretable Clusters in Mixture Models and Deep Representations** - Maximilian Fleissner, Maedeh Zarvandi, Debarghya Ghoshdastidar. [[Paper](https://arxiv.org/abs/2411.01576)]
- [arXiv 2024] - **KTCR: Improving Implicit Hate Detection with Knowledge Transfer driven Concept Refinement** - Samarth Garg, Vivek Hruday Kavuri, Gargi Shroff, Rahul Mishra. [[Paper](https://arxiv.org/abs/2410.15314)]
- [arXiv 2024] - **Explaining Explainability: Understanding Concept Activation Vectors** - Angus Nicolson, Lisa Schut, J. Alison Noble, Yarin Gal. [[Paper](https://arxiv.org/abs/2404.03713)]
- [ICLR 2023] - **Concept Gradient: Concept-based Interpretation Without Linear Assumption** - Andrew Bai, Chih-Kuan Yeh, Pradeep Ravikumar, Neil Y. C. Lin, Cho-Jui Hsieh. [[Paper](https://arxiv.org/abs/2208.14966)][[Code](https://github.com/jybai/concept-gradients)]
- [NeurIPS 2022] - **Probing Classifiers are Unreliable for Concept Removal and Detection** - Abhinav Kumar, Chenhao Tan, Amit Sharma. [[Paper](https://arxiv.org/abs/2207.04153)]
- [NeurIPS 2022] - **Concept Activation Regions: A Generalized Framework For Concept-Based Explanations** - Jonathan Crabbé, Mihaela van der Schaar. [[Paper](https://arxiv.org/abs/2209.11222)][[Code](https://github.com/JonathanCrabbe/CARs)]
- [NeurIPS 2020] - **On Completeness-aware Concept-Based Explanations in Deep Neural Networks** - Chih-Kuan Yeh, Been Kim, Sercan Arik, Chun-Liang Li, Tomas Pfister, Pradeep Ravikumar. [[Paper](https://proceedings.neurips.cc/paper/2020/hash/ecb287ff763c169694f682af52c1f309-Abstract.html)][[Code](https://github.com/chihkuanyeh/concept_exp)]
- [ICML 2018] - **Interpretability Beyond Feature Attribution: Quantitative Testing with Concept Activation Vectors (TCAV)** - Been Kim, Martin Wattenberg, Justin Gilmer, Carrie Cai, James Wexler, Fernanda Viegas, Rory Sayres. [[Paper](https://arxiv.org/abs/1711.11279)][[Code](https://github.com/soumyadip1995/TCAV)]
 
### Concept Activation Steering
Methods about steering or manipulating activation status to influence model behavior or outputs.
- [arXiv 2025] - **SAIF: A Sparse Autoencoder Framework for Interpreting and Steering Instruction Following of Language Models** - Zirui He, Haiyan Zhao, Yiran Qiao, Fan Yang, Ali Payani, Jing Ma, Mengnan Du. [[Paper](https://arxiv.org/abs/2502.11356)]
- [arXiv 2025] - **Uncovering Latent Chain of Thought Vectors in Language Models** - Jason Zhang, Scott Viteri. [[Paper](https://arxiv.org/abs/2409.14026)]
- [arXiv 2025] - **AxBench: Steering LLMs? Even Simple Baselines Outperform Sparse Autoencoders** - Zhengxuan Wu, Aryaman Arora, Atticus Geiger, Zheng Wang, Jing Huang, Dan Jurafsky, Christopher D. Manning, Christopher Potts. [[Paper](https://arxiv.org/abs/2501.17148)][[Code](https://arxiv.org/pdf/2501.17148)]
- [ICLR 2025] - **Beyond Single Concept Vector: Modeling Concept Subspace in LLMs with Gaussian Distribution** - Haiyan Zhao, Heng Zhao, Bo Shen, Ali Payani, Fan Yang, Mengnan Du. [[Paper](https://arxiv.org/abs/2410.00153)]
- [ICLR 2025] - **Programming Refusal with Conditional Activation Steering** - Bruce W. Lee, Inkit Padhi, Karthikeyan Natesan Ramamurthy, Erik Miehling, Pierre Dognin, Manish Nagireddy, Amit Dhurandhar. [[Paper](https://arxiv.org/abs/2409.05907)][[Code](https://github.com/IBM/activation-steering)]
- [ICLR 2025] - **Semantics-Adaptive Activation Intervention for LLMs via Dynamic Steering Vectors** - Weixuan Wang, Jingyuan Yang, Wei Peng. [[Paper](https://arxiv.org/abs/2410.12299)] [[Code](https://github.com/weixuan-wang123/SADI)] 
- [ICLR 2025] - **Improving Instruction-Following in Language Models through Activation Steering** - Alessandro Stolfo, Vidhisha Balachandran, Safoora Yousefi, Eric Horvitz, Besmira Nushi. [[Paper](https://arxiv.org/abs/2410.12877)][[Code](https://openreview.net/forum?id=wozhdnRCtw)]
- [NeurIPS 2024] - **Personalized Steering of Large Language Models: Versatile Steering Vectors Through Bi-directional Preference Optimization** - Yuanpu Cao, Tianrong Zhang, Bochuan Cao, Ziyi Yin, Lu Lin, Fenglong Ma, Jinghui Chen. [[Paper](https://arxiv.org/abs/2406.00045)][[Code](https://github.com/CaoYuanpu/BiPO)]
- [NeurIPS 2024] - **Enhancing Multiple Dimensions of Trustworthiness in LLMs via Sparse Activation Control** - Yuxin Xiao, Chaoqun Wan, Yonggang Zhang, Wenxiao Wang, Binbin Lin, Xiaofei He, Xu Shen, Jieping Ye. [[Paper](https://arxiv.org/abs/2411.02461)]
- [NeurIPS 2024] - **Refusal in Language Models Is Mediated by a Single Direction** - Andy Arditi, Oscar Obeso, Aaquib Syed, Daniel Paleka, Nina Panickssery, Wes Gurnee, Neel Nanda. [[Paper](https://arxiv.org/abs/2406.11717)][[Code](https://github.com/andyrdt/refusal_direction)]
- [NeurIPS 2024] - **Analyzing the Generalization and Reliability of Steering Vectors** - Daniel Tan, David Chanin, Aengus Lynch, Dimitrios Kanoulas, Brooks Paige, Adria Garriga-Alonso, Robert Kirk. [[Paper](https://arxiv.org/abs/2407.12404)]
- [NeurIPS 2024] - **Who's asking? User personas and the mechanics of latent misalignment** - Asma Ghandeharioun, Ann Yuan, Marius Guerard, Emily Reif, Michael A. Lepori, Lucas Dixon. [[Paper](https://arxiv.org/abs/2406.12094)][[Code](https://openreview.net/forum?id=eSes1Mic9d)]
- [NeurIPS 2024 workshop] - **Towards Reliable Evaluation of Behavior Steering Interventions in LLMs** - Itamar Pres, Laura Ruis, Ekdeep Singh Lubana, David Krueger. [[Paper](https://arxiv.org/abs/2410.17245)]
- [NeurIPS 2024 workshop] - **Steering Large Language Models using Conceptors: Improving Addition-Based Activation Engineering** - Joris Postmus, Steven Abreu. [[Paper](https://arxiv.org/abs/2410.16314)][[Code](https://github.com/jorispos/conceptorsteering)]
- [NeurIPS 2024 workshop] - **Relational Composition in Neural Networks: A Survey and Call to Action** - Martin Wattenberg, Fernanda B. Viégas. [[Paper](https://arxiv.org/abs/2407.14662)]
- [NeurIPS 2024 workshop] - **Can sparse autoencoders be used to decompose and interpret steering vectors?** - Harry Mayne, Yushi Yang, Adam Mahdi. [[Paper](https://arxiv.org/abs/2411.08790)] [[Code](https://github.com/HarryMayne/SV_interpretability)]
- [NeurIPS 2024 workshop] - **Extracting Unlearned Information from LLMs with Activation Steering** - Atakan Seyitoğlu, Aleksei Kuvshinov, Leo Schwinn, Stephan Günnemann. [[Paper](https://arxiv.org/abs/2411.02631)]
- [ICML 2024] - **In-context Vectors: Making In Context Learning More Effective and Controllable Through Latent Space Steering** - Sheng Liu, Haotian Ye, Lei Xing, James Zou. [[Paper](https://arxiv.org/abs/2311.06668)][[Code](https://github.com/shengliu66/ICV)]
- [ICML 2024 workshop] - **Controlling Large Language Model Agents with Entropic Activation Steering** - Nate Rahn, Pierluca D'Oro, Marc G. Bellemare. [[Paper](https://arxiv.org/abs/2406.00244)]
- [ICLR 2024] - **ReFT: Representation Finetuning for Language Models** - Zhengxuan Wu, Aryaman Arora, Zheng Wang, Atticus Geiger, Dan Jurafsky, Christopher D. Manning, Christopher Potts. [[Paper](https://arxiv.org/abs/2404.03592)][[Code](https://github.com/stanfordnlp/pyreft)]
- [ICLR 2024] - **Function Vectors in Large Language Models** - Eric Todd, Millicent L. Li, Arnab Sen Sharma, Aaron Mueller, Byron C. Wallace, David Bau. [[Paper](https://arxiv.org/abs/2310.15213)][[Code](https://github.com/ericwtodd/function_vectors)]
- [EMNLP 2024] - **Activation Scaling for Steering and Interpreting Language Models** - Niklas Stoehr, Kevin Du, Vésteinn Snæbjarnarson, Robert West, Ryan Cotterell, Aaron Schein. [[Paper](https://arxiv.org/abs/2410.04962)] [[Code](https://github.com/niklasstoehr/activationScaling)]
- [EMNLP 2024] - **Householder Pseudo-Rotation: A Novel Approach to Activation Editing in LLMs with Direction-Magnitude Perspective** - Van-Cuong Pham, Thien Huu Nguyen. [[Paper](https://arxiv.org/abs/2409.10053)]
- [ACL 2024] - **Towards Tracing Trustworthiness Dynamics: Revisiting Pre-training Period of Large Language Models** - Chen Qian, Jie Zhang, Wei Yao, Dongrui Liu, Zhenfei Yin, Yu Qiao, Yong Liu, Jing Shao. [[Paper](https://arxiv.org/abs/2402.19465)] [[Code](https://github.com/ChnQ/TracingLLM)]
- [ACL 2024] - **InferAligner: Inference-Time Alignment for Harmlessness through Cross-Model Guidance** - Pengyu Wang, Dong Zhang, Linyang Li, Chenkun Tan, Xinghao Wang, Ke Ren, Botian Jiang, Xipeng Qiu. [[Paper](https://arxiv.org/abs/2401.11206)] [[Code](https://github.com/Jihuai-wpy/InferAligner)]
- [ACL 2024] - **Steering Llama 2 via Contrastive Activation Addition** - Nina Rimsky, Nick Gabrieli, Julian Schulz, Meg Tong, Evan Hubinger, Alexander Matt Turner. [[Paper](https://arxiv.org/abs/2312.06681)] [[Code](https://github.com/nrimsky/CAA)]
- [CIKM 2024] - **Trojan Activation Attack: Red-Teaming Large Language Models using Activation Steering for Safety-Alignment** - Haoran Wang, Kai Shu. [[Paper](https://arxiv.org/abs/2311.09433)] [[Code](https://github.com/wang2226/Backdoor-Activation-Attack)]
- [arXiv 2024] - **Representation Engineering: A Top-Down Approach to AI Transparency** - Andy Zou et al. [[Paper](https://arxiv.org/abs/2310.01405)][[Code](https://github.com/andyzoujm/representation-engineering)]
- [arXiv 2024] - **Improving Steering Vectors by Targeting Sparse Autoencoder Features** - Sviatoslav Chalnev, Matthew Siu, Arthur Conmy. [[Paper](https://arxiv.org/abs/2411.02193)] [[Code](https://github.com/slavachalnev/SAE-TS)]
- [arXiv 2024] - **Uncovering Latent Chain of Thought Vectors in Language Models** - Jason Zhang, Scott Viteri. [[Paper](https://arxiv.org/abs/2409.14026)]
- [arXiv 2024] - **Future Events as Backdoor Triggers: Investigating Temporal Vulnerabilities in LLMs** - Sara Price, Arjun Panickssery, Sam Bowman, Asa Cooper Stickland. [[Paper](https://arxiv.org/abs/2407.04108)]
- [arXiv 2024] - **Steering Without Side Effects: Improving Post-Deployment Control of Language Models** - Asa Cooper Stickland, Alexander Lyzhov, Jacob Pfau, Salsabila Mahdi, Samuel R. Bowman. [[Paper](https://arxiv.org/abs/2406.15518)] [[Code](https://github.com/AsaCooperStickland/kl-then-steer)]
- [arXiv 2024] - **Adaptive Activation Steering: A Tuning-Free LLM Truthfulness Improvement Method for Diverse Hallucinations Categories** - Tianlong Wang, Xianfeng Jiao, Yifan He, Zhongzhi Chen, Yinghao Zhu, Xu Chu, Junyi Gao, Yasha Wang, Liantao Ma. [[Paper](https://arxiv.org/abs/2406.00034)]
- [arXiv 2024] - **Activation Steering for Robust Type Prediction in CodeLLMs** - Francesca Lucchetti, Arjun Guha. [[Paper](https://arxiv.org/abs/2404.01903)]
- [arXiv 2024] - **Extending Activation Steering to Broad Skills and Multiple Behaviours** - Teun van der Weij, Massimo Poesio, Nandi Schoots. [[Paper](https://arxiv.org/abs/2403.05767)] [[Code](https://github.com/TeunvdWeij/extending-activation-addition)]
- [arXiv 2024] - **MiMiC: Minimally Modified Counterfactuals in the Representation Space** - Shashwat Singh, Shauli Ravfogel, Jonathan Herzig, Roee Aharoni, Ryan Cotterell, Ponnurangam Kumaraguru. [[Paper](https://arxiv.org/abs/2402.09631)]
- [arXiv 2024] - **Investigating Bias Representations in Llama 2 Chat via Activation Steering** - Dawn Lu, Nina Rimsky. [[Paper](https://arxiv.org/abs/2402.00402)]
- [arXiv 2023] - **Improving Activation Steering in Language Models with Mean-Centring** - Ole Jorgensen, Dylan Cope, Nandi Schoots, Murray Shanahan. [[Paper](https://arxiv.org/abs/2312.03813)]
- [EMNLP 2023] - **In-Context Learning Creates Task Vectors** - Roee Hendel, Mor Geva, Amir Globerson. [[Paper](https://arxiv.org/abs/2310.15916)]
- [arXiv 2023] - **Activation Addition: Steering Language Models Without Optimization** - Alexander Matt Turner, Lisa Thiergart, David Udell, Gavin Leech, Ulisse Mini, Monte MacDiarmid. [[Paper](https://arxiv.org/abs/2308.10248)] [[Code](https://github.com/montemac/activation_additions)]
- [ACL 2022] - **Extracting Latent Steering Vectors from Pretrained Language Models** - Nishant Subramani, Nivedita Suresh, Matthew E. Peters, 2022-05. [[Paper](https://arxiv.org/abs/2205.05124)] [[Code](https://github.com/nishantsubramani/steering_vectors)]

### Collected Related Work (Uncategoried)

- [arXiv 2025] - **LatentQA: Teaching LLMs to Decode Activations Into Natural Language** - Alexander Pan, Lijie Chen, Jacob Steinhardt. [[Paper](https://arxiv.org/abs/2412.08686)][[Code](https://github.com/aypan17/latentqa)]
- [ICLR 2025] - **Do I Know This Entity? Knowledge Awareness and Hallucinations in Language Models** - Javier Ferrando, Oscar Obeso, Senthooran Rajamanoharan, Neel Nanda. [[Paper](https://arxiv.org/abs/2411.14257)]
- [NeurIPS 2024] - **Concept Algebra for (Score-Based) Text-Controlled Generative Models** - Zihao Wang, Lin Gui, Jeffrey Negrea, Victor Veitch. [[Paper](https://arxiv.org/abs/2302.03693)][[Code](https://github.com/zihao12/concept-algebra-code)]
- [NeurIPS 2023] - **Inference-Time Intervention: Eliciting Truthful Answers from a Language Model** - Kenneth Li, Oam Patel, Fernanda Viégas, Hanspeter Pfister, Martin Wattenberg. [[Paper](https://arxiv.org/abs/2306.03341)][[Code](https://github.com/likenneth/honest_llama)]
- [ICLR 2020] - **On the "steerability" of generative adversarial networks** - Ali Jahanian, Lucy Chai, Phillip Isola. [[Paper](https://arxiv.org/abs/1907.07171)][[Code](https://github.com/ali-design/gan_steerability)]

### Relevant Repo and Blog

- [Activation Engineering - LessWrong](https://www.lesswrong.com/w/activation-engineering)
- [Anthropic Transformer Ciruits Thread](https://transformer-circuits.pub)
- [TransformerLens](https://github.com/TransformerLensOrg/TransformerLens)
- [Neel Nanda's Blog](https://www.neelnanda.io/mechanistic-interpretability/getting-started)
- [Awesome Representation Engineering](https://github.com/chrisliu298/awesome-representation-engineering)

## License
This project is licensed under the [MIT License](LICENSE).

---

**Disclaimer**: This repository is for research purposes only. The papers and resources listed here are the property of their respective authors.
