# LLM With Custom Data: A LoRA and QLoRA Approach

## Description

This Jupyter Notebook (.ipynb) demonstrates the process of fine-tuning Large Language Models (LLMs) for Text-to-SQL tasks using LoRA (Low-Rank Adaptation) and QLoRA (Quantized Low-Rank Adaptation) techniques. We experiment with multiple models to determine the most effective one for this specific task.

Our findings indicate that Mistral outperforms other models in the Text-to-SQL domain. The models tested in this notebook include:

1. Mistral
2. CodeLlama
3. LLaMA 3
4. LLaMA 2
5. Granite

## Getting Started

### Prerequisites

- Jupyter Notebook or Vscode
- Python 3.9
- Required libraries (listed in the notebook)

### Usage

1. Clone this repository:

   ```
   git clone https://github.com/Aremstrom/LLM-Custom-Data.git
   ```

2. Navigate to the project directory:

   ```
   cd LLM-Custom-Data
   ```

3. Open the Jupyter Notebook:

   ```
   jupyter notebook <FileName>.ipynb
   ```

4. Run the cells in the notebook sequentially to reproduce the experiments and results.

## Notebook Contents

The notebook includes the following main sections:

1. Setup and Installation
2. Data Preparation
3. Model Initialization
4. Fine-tuning with LoRA/QLoRA
5. Evaluation
6. Results and Comparison

## Results

The notebook provides detailed results of our experiments, showcasing the performance of each model on the Text-to-SQL task. Mistral demonstrates superior performance compared to other tested models.

## Contributing

We welcome contributions to improve this notebook. Please feel free to fork the repository, make your changes, and submit a pull request.
