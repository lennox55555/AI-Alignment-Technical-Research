# AI Alignment Research Repository - README

Welcome to my **AI Alignment Research** repository! This project is dedicated to exploring, analyzing, and improving alignment between artificial intelligence models and human reasoning through a combination of **technical research** and **machine learning experiments**. The goal is to contribute to the field of **AI alignment**, focusing on understanding how well models make decisions that align with human expectations and how to measure that alignment systematically.

## Overview
This repository contains:
1. **Research Paper**: "Shared Interest: Measuring Human-AI Alignment to Identify Recurring Patterns in Model Behavior" by Angie Boggust et al. [Link to paper](https://dl.acm.org/doi/abs/10.1145/3491102.3501965)
2. **Jupyter Notebooks**: Hands-on technical analysis using the **Shared Interest** metrics for evaluating model alignment with human reasoning. [Link to notebook](./Al-Alignment-Shared-Interest.ipynb)


## Purpose of This Repository
I’m passionate about the field of **AI alignment**, and this repository serves as a hub for my research and experiments. My aim is to dive deeper into:
- **Measuring Human-AI Alignment**: How to quantify alignment between AI model decisions and human logic using metrics like **Intersection over Union (IoU)**, **Ground Truth Coverage (GTC)**, and **Saliency Coverage (SC)**.
- **Recurring Patterns in Model Behavior**: Identifying patterns where AI models align with or deviate from human reasoning.

## How I Performed Technical Research
The research is centered around the **Shared Interest** framework introduced in the paper. Here’s a summary of what I did:
1. **Model Training & Saliency Methods**: I used pre-trained models (such as **EfficientNet** and **ResNet**) and various **saliency methods** (e.g., **Grad-CAM**, **LIME**) to interpret model predictions and visualize the features models rely on.
2. **Metric Calculation**: Using **IoU**, **GTC**, and **SC**, I compared the model's salient features to human-labeled ground truth annotations to determine how well the model's decision-making aligns with human reasoning.
3. **Interactive Probing**: In the Jupyter Notebook, I explored different case studies and experimented with **real-world tasks** (like image classification using the CIFAR-10 dataset) to see how the metrics reveal patterns in model behavior.
4. **Visualization**: Generated saliency maps to visually inspect model decisions and understand when models over-rely on irrelevant features or align perfectly with human reasoning.

## Planned Growth
This repository is the beginning of a much larger journey into **AI alignment**. Moving forward, I plan to:
- **Explore More Models**: Analyze different architectures (e.g., transformers, RNNs) to understand alignment across various types of AI systems.
- **Expand Dataset Scope**: Incorporate **medical, natural language processing**, and **self-driving car** datasets to see how alignment patterns differ in critical real-world applications.
- **Develop New Metrics**: As AI alignment research evolves, I aim to contribute by developing new methods to measure alignment beyond saliency.
- **Interactive Tools**: Build tools for interactive model analysis and comparison to allow broader engagement in the field of AI alignment research.

## Why AI Alignment?
AI alignment is crucial for the future of AI. Models need to make decisions that align with human values, especially in high-stakes applications like healthcare and autonomous vehicles. I’m driven by the desire to better understand how AI models think and ensure that they can be trusted to act in ways that are aligned with human intentions.

Stay tuned for more updates as I continue to learn and contribute to the growing field of **AI alignment**!

---

Feel free to explore the notebooks, experiment with the models, and contribute to the project. Let’s ensure AI aligns with the values and reasoning we expect!
