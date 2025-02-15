# Fine-Tuning DeepSeek-R1 Reasoning Model

## Overview

This project focuses on fine-tuning the **DeepSeek-R1-Distill-Llama-8B** model for medical reasoning tasks. The primary objective is to enhance the model’s ability to generate **logical, step-by-step explanations** before providing final responses. By leveraging **Unsloth's optimized framework**, the fine-tuning process is made efficient while ensuring high-quality outputs.

---



## Installation & Setup

To run this project, you need:

- **Python 3.8+**
- **Jupyter Notebook**
- Required libraries like `unsloth`, `transformers`, `datasets`, and `wandb`.

Follow the instructions in the notebook to set up the environment and install dependencies.

---

## Dataset Information

The project uses the **FreedomIntelligence/medical-o1-reasoning-SFT** dataset, which includes:

- **Medical Questions**
- **Complex Chain-of-Thought Reasoning**
- **Final Responses**

The dataset is formatted to match the model’s training needs, ensuring structured and consistent learning.

---

## Model Training Process

The fine-tuning process consists of the following steps:

1. **Loading Pre-trained Model** – Utilizing DeepSeek-R1-Distill-Llama-8B with optimized parameters.
2. **Defining a Structured Prompt** – Ensuring logical, step-by-step reasoning for better interpretability.
3. **Dataset Preprocessing** – Formatting the dataset to fit the model’s structured training requirements.
4. **Fine-Tuning with LoRA** – Applying Low-Rank Adaptation (LoRA) for efficient training.
5. **Training the Model** – Using supervised fine-tuning techniques to improve model accuracy.
6. **Evaluating Performance** – Measuring improvements in reasoning and answer quality.

---

## Results & Performance

After fine-tuning, the model:

- Demonstrates **enhanced reasoning skills** for complex medical cases.
- Produces **structured and logical responses**.
- Shows **improved accuracy and reliability** in generated outputs.

Performance metrics and evaluation results are stored in the `results/` directory.







## License

This project is licensed under the **MIT License**.

---

