---
lang: en-US
layout: box
title: About Me
permalink: /about/en
---

I am a 5th-year Ph.D. student at Binghamton University working on **Interactive Symbol Grounding** research to realize human-robot interaction systems that integrate language/knowledge with physical experience under the supervision of Prof. Shiqi Zhang.

[Download CV](/assets/downloads/CV_Yohei_Hayamizu.pdf)

I am organizing the Human Robot Systems (HRS)-Reading Group at Binghamton University. These weekly meetings bring together students and faculty to explore cutting-edge developments in robotics, artificial intelligence, and human-robot interaction. Please contact me if interested in joining us. [Website](https://yoheihayamizu.github.io/hrs-reading-group/)

-------------------

# Research Vision: Interactive Symbol Grounding

My research goal is to bridge the gap between **language/knowledge** and **physical actions/experiences** in robotic systems. While robots can conduct a variety of tasks by navigating and manipulating objects, the lack of a grounded understanding remains a challenge of why they act or how to convey their physical experiences to humans.

To address this challenge, I am building a unified framework for Interactive Symbol Grounding, focusing on three interconnected directions:

## Knowledge → Action (Grounding Downward)
**Leveraging human knowledge and LLMs to guide robotic exploration and RL**

Traditional RL requires extensive trial-and-error before robots can learn efficiently. To solve this problem, we develop methods that leverage human expertise and logical rules to guide robot learning processes. For example, in quadruped locomotion control, we incorporated physical laws about gait stability as logical rules, achieving safer and more efficient learning (ICAPS 2024). We also proposed the "Guided Dyna-Q" algorithm that uses automated planning techniques to predetermine exploration directions, reducing wasteful trials and achieving performance significantly superior to conventional methods in delivery tasks with actual Segway robots (ICAPS 2021). Recently, we developed the DKPROMPT method that combines large language models (LLMs) with vision models to effectively incorporate domain knowledge into prompts, improving robot planning accuracy in open-world environments.

## Action ↔ Language (Real-time Alignment)
**Synchronizing physical navigation with dialogue during collaboration**

When humans and robots collaborate on tasks, conventional systems designed dialogue management and navigation control independently, resulting in unnatural interactions. My research developed an integrated learning framework that allows robots to simultaneously optimize "when to speak," "what to say," and "where to move" (IROS 2023). Specifically, RL agents handle dialogue actions and movement actions in a unified manner, enabling natural collaborative behavior while understanding human intentions. We implemented this approach on Segway-based robots and achieved significant improvements in both task completion rates and user satisfaction compared to conventional separated systems in office delivery tasks.

## Physical Experience → Meaning (Grounding Upward)
**Enabling robots to verbalize their visual and physical experiences to assist humans**

For robots to become true human partners, they must be able to express their physical experiences as language and share them with humans. My most significant contribution in this area is the development of **robotic guide dogs** that assist visually impaired individuals (AAAI 2026). While traditional guide dogs provide only physical guidance, the robotic guide dogs I develop describe environmental information sensed by cameras and LiDAR in natural language, performing navigation through continuous dialogue with users. Through specific situational descriptions such as "There are stairs ahead" and "I can see a cafe entrance on the right," I realized a system that allows users to move with greater confidence.

-------------------

# Education

**The State University of New York at Binghamton** <span class="tag">Aug. 2021 - Present</span>

Ph.D. in Computer Science,
GPA: 3.89/4.0,
Advisor: Prof. Shiqi Zhang

**University of Electro-Communications (UEC)** <span class="tag">Apr. 2018 - Mar. 2021</span>

M.S. in Computer Science,
GPA: 2.80/3.0,
Advisor: Prof. Keiki Takadama

**Iwate University** <span class="tag">Apr. 2014 - Mar 2018</span>

B.E. in Computer Science,
GPA: 3.33/4.0,
Advisor: Prof. Chon Hae Kim
