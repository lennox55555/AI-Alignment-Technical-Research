# Adversarial AI Patch Exploration

## Overview

This folder contains code and research notes focused on understanding and experimenting with **adversarial evasion attacks and conceptual methods for defense** using patches on computer vision models. The primary focus is to replicate the findings from a recent paper on safety-critical computer vision systems and adversarial defenses.

This work was inspired by the paper **"Safety‐critical computer vision: an empirical survey of adversarial evasion attacks and defenses on computer vision systems"** by Charles Meyers, Tommy Löfstedt, and Erik Elmroth (2023). The paper covers a variety of adversarial attack methods and defenses for computer vision models. You can read the paper [here]([https://link-to-paper](https://link.springer.com/article/10.1007/s10462-023-10521-4)).

## Research Motivation

The paper provides a deep dive into how adversarial attacks, particularly evasion attacks, compromise the reliability of AI models in safety-critical applications. The authors present numerous experiments with attacks and defenses, focusing on the impact of adversarial noise on model performance. In particular, Section 4 defense methods, which was the key area of focus for this exploration.

Through my own research and experiments, I aimed to investigate **how adversarial patches** can fool pre-trained image classification models. I used **adversarial patches** and other attacks like FGSM (Fast Gradient Sign Method) as mentioned in the paper. I also explored conceptual defenses that might improve robustness to these attacks.

## Conceptual Models for Adversarial Defense

One takeaway from the research was that to truly align AI systems with human thinking and ensure safety, we must understand how human thinking differs from machine learning. My conceptual models for adversarial defense were derived from studying the methods in Section 4 of the paper, which discusses attacker identification and subset analysis.

While I followed a Jupyter notebook to perform and visualize attacks, I also came up with some **conceptual factors for adversarial defense**:
- **Attacker Identification**: Using graph theoretical methods to isolate potential attackers based on network behavior.
- **Subset Analysis**: Analyzing subsets of data to detect adversarial inputs by assessing how their removal impacts model performance.

## Content of the Subfolder

In this folder, you will find:
- **Jupyter Notebook**: Code that demonstrates adversarial patch attacks on a pre-trained model, visualizes adversarial patches, and evaluates the model's robustness.
- **Patch Images**: Generated adversarial patches that were applied to fool the model during classification tasks.
- **Model Output Logs**: Logs of the model's performance before and after adversarial patches were applied, showcasing accuracy degradation.
- **Research Notes**: Additional conceptual thoughts on adversarial defenses, derived from the experiments and reading of the paper.

## Conclusion

This work is an exploration into how adversarial attacks, particularly **patch attacks**, can affect AI models, and what can be done to defend against them. By understanding these attacks in a hands-on way, we can improve the robustness of AI in critical systems. 
