# Fine-Tuning Llama Models (1B and 3B) with SFT 
(LlaVa models required resources that weren't currently available)

This project involves fine-tuning the Llama models (1B and 3B parameters) using Supervised Fine-Tuning (SFT) and other techniques, aimed at optimizing language models with efficient dependency management. The project includes a workflow for model quantization, training, and evaluation, and uses Colab for initial experimentation with cloud GPU resources.

## Project Summary

- **Model**: Llama3.2 1B and 3B
- **Techniques**: Supervised Fine-Tuning (SFT), quantization, dependency reduction
- **Dependencies**: Unsloth (initially), PyTorch trainer
- **Hosting**: [Hugging Face Repository](https://huggingface.co/SaiAnkith/fine-tuning_Llama_model-Unsloth)

## Features

1. **Fine-Tuning with SFT**:
   - Trained Llama3.2 models (1B and 3B) on Colab using Supervised Fine-Tuning (SFT).
   - Integrated basic code to monitor training loss per step for better tracking.

2. **Dependency Management**:
   - Initially used Unsloth for fine-tuning.
   - Planned to fine-tune the model without Unsloth to reduce dependencies and improve portability.

3. **Quantization**:
   - Quantized models to 4-bit for more efficient deployment.

4. **Training and Resource Optimization**:
   - Explored Colab for GPU resources, but faced limitations with memory.
   - Attempted to use Krutrim’s GPU credits, though encountered challenges with beta version bugs.

5. **Chat Template and Dataset Preparation**:
   - Developed a chat template to adapt conversational datasets for tokenization and fine-tuning.
   - Evaluated SFT and PyTorch trainer for model training, considering Colab's resource constraints.

## Visualization and Monitoring

- **Training Loss Tracking**: Added basic code to monitor training loss at each step.
- **WandB Integration**: Incorporated WandB for experiment tracking and visualizations. Currently refining the code to generate a detailed learning curve.

## Future Plans

- **Dependency Minimization**: Further optimization by reducing dependency on Unsloth.
- **GPU Resources**: Exploring alternative, stable GPU resources for larger models.
- **Enhanced Visualization**: Update WandB integration for comprehensive learning curve visualization.

## Repository

All code and model artifacts are available in the [Hugging Face repository](https://huggingface.co/SaiAnkith/fine-tuning_Llama_model-Unsloth).

