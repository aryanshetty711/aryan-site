---
layout: project
title: "Can LLMs Adapt to Speakers When Answering Questions?"
description: Exploring the use of Direct Preference Optimization (DPO) to train language models that adapt their communication style based on the speaker’s identity and complexity level.
img: /assets/img/llm_adaptation.jpg
order: 1
---

<br>

Large Language Models (LLMs) have shown promise in generating human-like text, but their ability to adapt to the speaker’s identity, complexity level, or knowledge remains underexplored. My research focuses on training LLMs to dynamically adapt their communication style using a novel method known as **Direct Preference Optimization** (DPO). This project explores whether an LLM can autonomously adjust its language to match the proficiency of the speaker, such as simplifying its responses when engaging with non-native speakers or ESL learners, without explicit instructions.

The primary objective of the project is to investigate if an LLM can modify its language complexity—using tools like the **Flesch-Kincaid Grade Level (FKGL)** and **Flesch-Kincaid Reading Ease (FKRE)**—to improve accessibility and communication clarity. This is achieved through fine-tuning a pre-existing model with datasets such as the **Teacher-Student Chatroom Corpus (TSCC)**, where dialogues between teachers and students of varying English proficiency levels provide a robust basis for training.

### Project Highlights:
- **Training Method**: We employ **Direct Preference Optimization** (DPO) to directly optimize the model’s output preferences, making it responsive to different levels of language complexity.
- **Datasets**: The **TSCC** dataset includes diverse student-teacher conversations annotated with student proficiency levels, allowing the model to learn to adapt its language based on input complexity.
- **Results**: Our experiments demonstrate that fine-tuning an LLM using DPO improves its ability to simplify responses when required, although challenges remain in ensuring that the simplifications don't detract from the informational content.

### Future Directions:
1. **Improved Negative Data Handling**: A more suitable dataset of negative examples is needed to refine the model’s ability to avoid overgeneralization.
2. **Diverse Model Testing**: The research will be expanded to evaluate how different models (e.g., ChatGPT, Gemini) adapt across various complexities and linguistic backgrounds.
3. **Real-Time Adaptation**: Future work will explore real-time feedback mechanisms to allow the model to fine-tune its responses during live interactions.

If you have suggestions or would like to collaborate, feel free to reach out!

Best,  
Aryan Shetty
