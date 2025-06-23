# LoRA Fine-Tuning for LLMs with MLX

A collection of Jupyter notebooks demonstrating Low-Rank Adaptation (LoRA) fine-tuning techniques for Large Language Models using Apple's MLX framework. This repository provides practical examples and implementations for both standard LoRA fine-tuning and advanced reinforcement learning approaches like Group Relative Policy Optimization (GRPO).

## 📚 What's Inside

This repository contains comprehensive tutorials and implementations for:

- **Standard LoRA Fine-Tuning**: Complete walkthrough of LoRA fine-tuning using MLX LM with the HellaSwag dataset
- **GRPO Fine-Tuning**: Implementation of Group Relative Policy Optimization, a reinforcement learning approach similar to PPO for LLM fine-tuning
- **Practical Examples**: Real-world applications using Microsoft's Phi-3 models
- **Performance Analysis**: Training visualization, evaluation metrics, and troubleshooting guides

## 🚀 Getting Started

### Prerequisites

This project uses [uv](https://github.com/astral-sh/uv) for dependency management. Make sure you have it installed:

## 📓 Notebooks

### 1. MLX LM LoRA Fine Tune.ipynb
A comprehensive guide to standard LoRA fine-tuning covering:
- Data preprocessing and preparation
- LoRA configuration and setup
- Training loop implementation
- Model evaluation and accuracy measurement
- Adapter fusion and model deployment
- Troubleshooting tips for common issues

### 2. MLX LM GRPO.ipynb
Advanced reinforcement learning fine-tuning using GRPO:
- Group Relative Policy Optimization implementation
- Reward function design and optimization
- Policy gradient methods for LLM training
- Advanced RL techniques for language models

*Note: The GRPO notebook currently includes a placeholder reward function. Contributions for more sophisticated reward implementations are welcome!*

## 🛠️ Key Features

- **Apple Silicon Optimized**: Leverages MLX for efficient training on Apple Silicon
- **Memory Efficient**: Includes QLoRA support and memory optimization techniques
- **Production Ready**: Complete pipeline from training to deployment
- **Well Documented**: Detailed explanations and troubleshooting guides
- **Reproducible**: Fixed seeds and clear dependency management

## 🤝 Contributing

We welcome contributions! Whether you want to:
- Add new fine-tuning techniques
- Improve existing implementations
- Fix bugs or add features
- Enhance documentation
- Share your fine-tuning results

Please feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

For major changes, please open an issue first to discuss what you would like to change.

## 📋 Requirements

- Python 3.12+
- Apple Silicon Mac (recommended for optimal performance)
- MLX and MLX-LM
- Jupyter Lab/Notebook
- Additional dependencies managed via uv

## 📈 Performance Tips

The notebooks include extensive guidance on:
- Memory optimization techniques
- Hyperparameter tuning
- Quantization (QLoRA) for resource-constrained environments
- Gradient checkpointing
- Batch size optimization

## 🔍 Troubleshooting

Each notebook includes dedicated troubleshooting sections covering:
- Underfitting vs. overfitting diagnosis
- Memory usage optimization
- Training instability issues
- Post-fusion model performance

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [MLX Team](https://github.com/ml-explore/mlx) for the excellent MLX framework
- [Microsoft](https://huggingface.co/microsoft/Phi-3-mini-4k-instruct) for the Phi-3 models
- [HellaSwag](https://rowanzellers.com/hellaswag/) dataset creators
- [LLM-Adapters](https://github.com/AGI-Edgerunners/LLM-Adapters) for preprocessed datasets

## 📚 Further Reading

- [LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685)
- [MLX Documentation](https://ml-explore.github.io/mlx/)
- [MLX Examples Repository](https://github.com/ml-explore/mlx-examples)

---

⭐ If you find this repository helpful, please consider giving it a star!
