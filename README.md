# ShuleGPT.
Fine-tuning Gemma 2B on medical Q&amp;A for Tanzanian Students
ShuleGPT Fine-Tuning Project

This project contains scripts and processed data for fine-tuning a medical Large Language Model (LLM) using the [MedMCQA](https://huggingface.co/datasets/openlifescienceai/medmcqa) dataset.

Project Structure

- `data/medmcqa_instructions.jsonl`: Cleaned, instruction-formatted dataset for fine-tuning.
- `notebooks/prepare_dataset.ipynb`: Notebook to load, preprocess, and export dataset to JSONL format.
- `requirements.txt`: Python libraries required.

Objective

To fine-tune Gemma-2B using Swahili-English instruction data to support medical education in Africa via an AI assistant.

Dataset Format (JSONL)

```json
{
  "instruction": "What is the function of hemoglobin?\nA. Oxygen transport\nB. Digestion\nC. Vision\nD. Reflexes",
  "input": "",
  "output": "A. Oxygen transport"
}
