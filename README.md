# Medical LLM RAG & Fine-Tuning Pipeline - Introduction to Data Science

#### Overview
This repository provides a compact workflow for developing medical-domain Large Language Models (LLMs), for the purposes of a mandatory subject in Introduction to Data Science. It compares two approaches: Retrieval-Augmented Generation (RAG) and QLoRA-based supervised fine-tuning, enabling the creation of these systems that can answer medical questions using both external literature and domain-specific training data.

#### RAG Pipeline (`extract_&_rag.ipynb`)
This notebook implements document extraction, semantic chunking, embedding generation, and vector retrieval. It processes medical PDFs and PubMed Central articles to build a retrieval backend that supports grounded question answering and medical literature analysis.

#### Fine-Tuning Pipeline (`finetune.ipynb`)
This notebook performs QLoRA fine-tuning on a medical instruction dataset. It formats data in ChatML style, trains the model using TRL’s SFTTrainer, and produces QLoRA adapters that improve the model’s medical reasoning and communication abilities.

## Authors
- Simona Ristovska
- Matej Mitev
