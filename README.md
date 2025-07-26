# ShuleGPT.
Fine-tuning Gemma 2B on medical Q&amp;A for Tanzanian Students
ShuleGPT Fine-Tuning Project

This project contains scripts and processed data for fine-tuning a medical Large Language Model (LLM) using the [MedMCQA](https://huggingface.co/datasets/openlifescienceai/medmcqa) dataset.

Objective

To fine-tune Gemma-2B using English instruction data to support medical education in Africa via an AI assistant.
Support swahili and local healthcare education
deploy via chatbot(web+whatsapp)

Dataset Format (JSONL)

```json
{
  "instruction": "What is the function of hemoglobin?\nA. Oxygen transport\nB. Digestion\nC. Vision\nD. Reflexes",
  "input": "",
  "output": "A. Oxygen transport"
}
source; HuggingFace openlifescienceai/medmcqa
