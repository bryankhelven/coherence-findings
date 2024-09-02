# Coherence Classification and Incoherence  with LLMs

This repository contains prompts designed for Large Language Models (LLMs) specializing in text analysis.
The prompts are tailored for various tasks related to evaluating and annotating text coherence.
The three prompts included in this repository focus on classifying text coherence, assessing coherence levels, and annotating incoherent segments within a text.

## Prompts

### 1. **Local Coherence Classification Prompt**
   - **Purpose:** The LLM is tasked with determining whether a given text is coherent or incoherent based on logical flow, connection of ideas, and transition clarity.
   - **Instructions:** The LLM reads the text thoroughly, evaluates its logical progression and connection of ideas, and classifies it as either "coherent" or "incoherent."
   - **Use Case:** Suitable for scenarios requiring a binary classification of text coherence.

### 2. **Global Coherence Classification Prompt**
   - **Purpose:** The LLM is tasked with classifying the coherence of a text as "Low Coherence," "Medium Coherence," or "High Coherence" based on specific criteria such as understandability, organization, and relevance of details.
   - **Instructions:** The LLM assesses the text’s overall structure, organization, and relevance to the main point, ignoring grammatical errors, and assigns a coherence level accordingly.
   - **Use Case:** Ideal for tasks requiring a more nuanced evaluation of text coherence.

### 3. **Incoherence Identification Prompt**
   - **Purpose:** The LLM is tasked with identifying and annotating specific incoherent segments within a text. Categories include incorrect use of logical connectors, unnecessary repetition, irrelevant information, contradictions, sequence of events, and inconsistent verb tenses.
   - **Instructions:** The LLM reads the text carefully and marks incoherent segments with annotations indicating the category of incoherence and the reason for it.
   - **Use Case:** Useful for detailed text analysis where specific incoherence needs to be identified and annotated.

## Usage

These prompts can be used directly with LLMs capable of text analysis, such as GPT-based models. To use a prompt:

1. Select and copy the prompt that best suits your task.
2. Input the text you want to analyze on the right place.
3. Follow the instructions in the prompt to obtain the desired output.

## Contributions

Contributions to this repository are welcome. If you have additional prompts or enhancements to existing ones, please submit a pull request.
