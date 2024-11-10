---
permalink: /pub/
title: "Publications"
author_profile: true
redirect_from: 
  - /pub/
  - /pub.html
---

## Preprint

- ### <span style="color: #4682B4; font-weight: bold;">RED QUEEN: Safeguarding Large Language Models against Concealed Multi-Turn Jailbreaking</span>
   ***Yifan Jiang***, Kriti Aggarwal, Tanmay Laud, Kashif Munir, Jay Pujara, Subhabrata Mukherjee
  <img src="../assets/paper_image/red_queen_image.png" alt="RED QUEEN Image" style="width: 500px;">
  <details style="margin-left: 20px; padding: 5px;">
    <summary style="font-weight: bold; color: #0073e6; cursor: pointer;">Abstract</summary>
    <p style="margin-top: 10px; padding-left: 15px;">
      The rapid progress of Large Language Models (LLMs) has opened up new opportunities across various domains and applications; yet it also presents challenges
      related to potential misuse. To mitigate such risks, red teaming has been employed
      as a proactive security measure to probe language models for harmful outputs via
      jailbreak attacks. However, current jailbreak attack approaches are single-turn with
      explicit malicious queries that do not fully capture the complexity of real-world
      interactions. In reality, users can engage in multi-turn interactions with LLM-based
      chat assistants, allowing them to conceal their true intentions in a more covert
      manner. To bridge this gap, we, first, propose a new jailbreak approach, RED
      QUEEN ATTACK. This method constructs a multi-turn scenario, concealing the
      malicious intent under the guise of preventing harm. We craft 40 scenarios that
      vary in turns and select 14 harmful categories to generate 56k multi-turn attack
      data points. We conduct comprehensive experiments on the RED QUEEN ATTACK
      with four representative LLM families of different sizes. Our experiments reveal
      that all LLMs are vulnerable to RED QUEEN ATTACK, reaching 87.62% attack
      success rate on GPT-4o and 75.4% on Llama3-70B. Further analysis reveals that
      larger models are more susceptible to the RED QUEEN ATTACK, with multi-turn
      structures and concealment strategies contributing to its success. To prioritize
      safety, we introduce a straightforward mitigation strategy called RED QUEEN
      GUARD, which aligns LLMs to effectively counter adversarial attacks. This approach reduces the attack success rate to below 1% while maintaining the model’s
      performance across standard benchmarks.
    </p>
  </details>  
  [<span style="color: #1E90FF;">Paper</span>](https://arxiv.org/pdf/2409.17458) | [<span style="color: #1E90FF;">Github</span>](https://github.com/kriti-hippo/red_queen) | [<span style="color: #1E90FF;">Project Website</span>](https://redqueen1011.github.io/)


- ### <span style="color: #4682B4; font-weight: bold;">COLUMBUS: Evaluating COgnitive Lateral Understanding through Multiple-choice reBUSes</span>
    Koen Kraaijveld, ***Yifan Jiang***, Kaixin Ma, Filip Ilievski
  <img src="../assets/paper_image/columbus_image.png" alt="COLUMBUS_Image" style="width: 500px;">
  <details style="margin-left: 20px; padding: 5px;">
    <summary style="font-weight: bold; color: #0073e6; cursor: pointer;">Abstract</summary>
    <p style="margin-top: 10px; padding-left: 15px;">
      While visual question-answering (VQA) benchmarks have catalyzed the development of reasoning techniques, they have focused on vertical thinking. Effective  
      problem-solving also necessitates lateral thinking, which remains understudied in AI and has not been used to test visual perception systems. To bridge this
      gap, we formulate visual lateral thinking as a multiple-choice question-answering task and describe a three-step taxonomy-driven methodology for instantiating
      task examples. Then, we develop COLUMBUS, a synthetic benchmark that applies the task pipeline to create QA sets with text and icon rebus puzzles based on
      publicly available collections of compounds and common phrases. COLUMBUS comprises over 1,000 puzzles, each with four answer candidates. While the SotA vision
      language models (VLMs) achieve decent performance, our evaluation demonstrates a substantial gap between humans and models. VLMs benefit from human-curated
      descriptions but struggle to self-generate such representations at the right level of abstraction.
    </p>
  </details>  
  [<span style="color: #1E90FF;">Paper</span>](https://arxiv.org/abs/2409.04053) | [<span style="color: #1E90FF;">GitHub</span>](https://github.com/koen-47/COLUMBUS) | [<span style="color: #1E90FF;">Notebook</span>](https://github.com/koen-47/COLUMBUS/tree/main/notebooks)| [<span style="color: #1E90FF;">Project Website</span>](https://columbus-vqa.github.io/) | [<span style="color: #1E90FF;">Media Coverage</span>](https://www.bbc.com/future/article/20240912-what-riddles-teach-us-about-the-human-mind)



---

## 2024

- ### <span style="color: #4682B4; font-weight: bold;">MARVEL: Multidimensional Abstraction and Reasoning through Visual Evaluation and Learning</span>
  *NeurIPS DB track*<br>
   ***Yifan Jiang***\*, Jiarui Zhang*, Kexuan Sun*, Zhivar Sourati, Kian Ahrabian, Kaixin Ma, Filip Ilievski, Jay Pujara
  <img src="../assets/paper_image/marvel_image.png" alt="MARVEL_Image" style="width: 500px;">
  <details style="margin-left: 20px; padding: 5px;">
    <summary style="font-weight: bold; color: #0073e6; cursor: pointer;">Abstract</summary>
    <p style="margin-top: 10px; padding-left: 15px;">
     While multi-modal large language models (MLLMs) have shown significant progress on many popular visual reasoning benchmarks, whether
    they possess abstract visual reasoning abilities remains an open question.
    Similar to the Sudoku puzzles, abstract visual reasoning (AVR) problems
    require finding high-level patterns (e.g., repetition constraints) that control
    the input shapes (e.g., digits) in a specific task configuration (e.g., matrix). However, existing AVR benchmarks only considered a limited set
    of patterns (addition, conjunction), input shapes (rectangle, square), and
    task configurations (3 × 3 matrices). To evaluate MLLMs’ reasoning abilities comprehensively, we introduce MARVEL, a multidimensional AVR
    benchmark with 770 puzzles composed of six core knowledge patterns,
    geometric and abstract shapes, and five different task configurations. To inspect whether the model accuracy is grounded in perception and reasoning,
    MARVEL complements the general AVR question with perception questions in a hierarchical evaluation framework. We conduct comprehensive
    experiments on MARVEL with nine representative MLLMs in zero-shot
    and few-shot settings. Our experiments reveal that all models show nearrandom performance on the AVR question, with significant performance
    gaps (40%) compared to humans across all patterns and task configurations. Further analysis of perception questions reveals that MLLMs struggle
    to comprehend the visual features (near-random performance) and even
    count the panels in the puzzle (<45%), hindering their ability for abstract
    reasoning.
    </p>
  </details>  
  [<span style="color: #1E90FF;">Paper</span>](https://arxiv.org/pdf/2404.13591) | [<span style="color: #1E90FF;">GitHub</span>](https://github.com/1171-jpg/MARVEL_AVR) | [<span style="color: #1E90FF;">Project Website</span>](https://marvel770.github.io/)  | [<span style="color: #1E90FF;">Hugging Face</span>](https://huggingface.co/datasets/kianasun/MARVEL)  

- ### <span style="color: #4682B4; font-weight: bold;">ARN: Analogical Reasoning on Narratives</span><br>
  *TACL*<br>
  Zhivar Sourati, Filip Ilievski, Pia Sommerauer, ***Yifan Jiang***
  <img src="../assets/paper_image/arn_image.png" alt="ARN_Image" style="width: 500px;">
  <details style="margin-left: 20px; padding: 5px;">
    <summary style="font-weight: bold; color: #0073e6; cursor: pointer;">Abstract</summary>
    <p style="margin-top: 10px; padding-left: 15px;">
      As a core cognitive skill that enables the transferability of information across domains, analogical reasoning has been extensively studied for both humans and computational models. However, while cognitive theories of analogy often focus on narratives and study the distinction between surface, relational, and system similarities, existing work in natural language processing has a narrower focus as far as relational analogies between word pairs. This gap brings a natural question: can state-of-the-art large language models (LLMs) detect system analogies between narratives? To gain insight into this question and extend word-based relational analogies to relational system analogies, we devise a comprehensive computational framework that operationalizes dominant theories of analogy, using narrative elements to create surface and system mappings. Leveraging the interplay between these mappings, we create a binary task and benchmark for Analogical Reasoning on Narratives (ARN), covering four categories of far (cross-domain)/near (within-domain) analogies and disanalogies. We show that while all LLMs can largely recognize near analogies, even the largest ones struggle with far analogies in a zero-shot setting, with GPT4.0 scoring below random. Guiding the models through solved examples and Chain-of-Thought reasoning enhances their analogical reasoning ability. Yet, since even in the few-shot setting, the best model only performs halfway between random and humans, ARN opens exciting directions for computational analogical reasoners.
    </p>
  </details>  
  [<span style="color: #1E90FF;">Paper</span>](https://watermark.silverchair.com/tacl_a_00688.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAA0kwggNFBgkqhkiG9w0BBwagggM2MIIDMgIBADCCAysGCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMmsJwVnMxmrOhl3kRAgEQgIIC_BhUDBVHzgjmnETwcxlOCsdfKu-bO54lCB9GqGpeXXpWmUnryHCb0czjbAD3dc4bNc93xNaZYFzh1FHrWFAHKdvVUw1-Xx7DczHUlaAYTUDyPu5qPzEqqpKu3HK1W2eO4qqoKaR2VqLdm4xnPFg0x5JP-IZmLj5pS_X4n4n_Nbj8R_6SvF8_aDewRcXqXyAf_GlNcVb704T5Z23YHNtjNwapLl18YHGU2qX0PV-BJuCfOMqo0W2kG3Bfophe0V2OaSrUCvc--IxbPtx5E2cPeJJRpj9yh8G8D52Mdrzaa4sUdJiS-89HYEOAuFXB8xj3yY1ogOHrqDWNujI4vdfy9R6Z4gcOSLKrAazQiX1vLVJDR_FBSNmcRmmS8SYDPBf8q_BdrWN26_7tuxl-FpOIf4huH8KLaWd4jmbCb6eXlYxWxbSt9nUBIu_rQVZA5diDBCNlG2_bELMDoIevLqf98OIvIIy_Vvekh5sKfarut_hw6u_nXXVjfuutFiyleoKL4cKeHBIX6A1PDK6Jl14Z4K2o2ZgWnJ7gyprvS3a0XdF2-ncTzZWR72Nd_6hs2SvRGhkCdu_r7tPPJsAdfgMvFj5UtS14M9c-jL-nGR6sbvF6TJ_1IPbictM0fjNC7aZIPTPPgg2yjB3nO_0tjvGvIyy0ZSvyUi2omLL332qFcoYFaOOhjgIdZUjaA2y5cMuEki-tztsQLAJWTL49nT3Q6ApFNZaJNfp8mEXtFP-53R_nxjFc2qgUWlsu9K1xVoC95F80iXCVtspLfk6f1onn-LiuwiL0Z9jehR1_MdJkFVccR_3ObIIksNBZjRFULplDog9YKAiJkvKGoX8JJeHp0OAMJgTsA8cn6kCrLkzrydzY3gWcg-iIdysxTtcfKSNVe77k-6itiv-OTZ1GZiARXmsHBYLWMzrMt3Be-T5h_5wj0yB87WBKCmdhKyC3Od8LCAzITqpLesAI1WRp6BjUrPn3R__46wg2lXWzX1a4RBpq6xwCRSNVolejV51c) | [<span style="color: #1E90FF;">Data</span>](https://zenodo.org/records/11044026) 


- ### <span style="color: #4682B4; font-weight: bold;">Semeval-2024 task 9: Brainteaser: A novel task defying common sense</span>
  *Semeval@NAACL*<br>
  ***Yifan Jiang***, Filip Ilievski, Kaixin Ma
  <details style="margin-left: 20px; padding: 5px;">
    <summary style="font-weight: bold; color: #0073e6; cursor: pointer;">Abstract</summary>
    <p style="margin-top: 10px; padding-left: 15px;">
      While vertical thinking relies on logical and commonsense reasoning, lateral thinking requires systems to defy commonsense associations and overwrite them through unconventional thinking. Lateral thinking has been shown to be challenging for current models but has received little attention. A recent benchmark, BRAINTEASER, aims to evaluate current models' lateral thinking ability in a zero-shot setting. In this paper, we split the original benchmark to also support fine-tuning setting and present SemEval Task 9: BRAIN-TEASER(S), the first task at this competition designed to test the system's reasoning and lateral thinking ability. As a popular task, BRAINTEASER(S)'s two subtasks receive 483 team submissions from 182 participants during the competition. This paper provides a fine-grained system analysis of the competition results, together with a reflection on what this means for the ability of the systems to reason laterally. We hope that the BRAINTEASER(S) subtasks and findings in this paper can stimulate future work on lateral thinking and robust reasoning by computational models.
    </p>
  </details>  
  [<span style="color: #1E90FF;">Paper</span>](https://aclanthology.org/2024.semeval-1.274/) | [<span style="color: #1E90FF;">GitHub</span>](https://github.com/1171-jpg/BrainTeaser) | [<span style="color: #1E90FF;">Colab Website</span>](https://codalab.lisn.upsaclay.fr/competitions/15566)| [<span style="color: #1E90FF;">Project Website</span>](https://brainteasersem.github.io/) 

---

## 2023

