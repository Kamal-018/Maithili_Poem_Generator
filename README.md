# Maithili Instruction-Tuned LLM 

A specialized generative model fine-tuned for **Maithili poetry** and creative text generation. This project focuses on adapting large-scale language models to low-resource languages using parameter-efficient fine-tuning and robust data engineering.

## Tech Stack
* **Base Model:** Gemma-2B, Qwen2.5-1.5B
* **Optimization:** Unsloth (4-bit QLoRA)
* **Frameworks:** PyTorch, Hugging Face (PEFT, TRL, Transformers)
* **Data Processing:** Regex, Unicode Normalization

## Key Features
* **Instruction Fine-Tuning:** Trained using the **Alpaca template** to enable instruction-following capabilities specifically for Maithili literary forms.
* **Data Engineering Pipeline:** Implemented a custom preprocessing suite to resolve complex UTF-8 encoding artifacts and script-specific noise in the Devanagari dataset.
* **Efficient Architecture:** Leveraged **4-bit quantization** and **PEFT** (Parameter-Efficient Fine-Tuning) to minimize VRAM usage while maintaining high linguistic coherence.
* **Linguistic Validation:** Integrated quantitative metrics including **Perplexity** and **Type-Token Ratio (TTR)** to monitor model diversity and prevent repetitive generation patterns.

Developed as part of a research project into Low-Resource Language Generation while exploring the field of Causal Language Modeling (CLM) away from the MLM to perform continued pretraining or pretrain a Small Language Model in future.
