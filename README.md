
This project is licensed under Apache 2.0, meaning you are free to use it, but you must provide attribution to the original author.

Copyright (c) 2025 [Christopher Salnave]

# LLM Computational Graph Profiler & Memory Analyzer

## Author: [PhotonMechanic]  
## License: Apache 2.0

## 🔍 Overview
This application provides a comprehensive profiling tool for large language models (LLMs) by analyzing computational graphs, memory efficiency, FLOPs, and time complexity. Users can dynamically explore various sequence lengths, quantization methods, reinforcement learning techniques, and graph structures, generating real-time 3D visualizations and extracting key model performance insights.

## ⚡ Features
✅ **Model Selection:** Supports Hugging Face models like GPT-2, DistilBERT, and BERT-BASE.  
✅ **Quantization Options:** Choose between FP32, FP16, and INT8 for model execution.  
✅ **Custom Time Complexity Trends:** Supports logarithmic, linear, parabolic (O(n²)), etc.  
✅ **Reinforcement Learning Support:** Includes Meta-Chain of Thought, Chain-of-Thought, Monte Carlo Tree Search (MCTS), and DQN.  
✅ **GPU Selection:** Compare performance across T4, A100, V100, and other GPUs. **Please use A100 in Colab to run models that are greater than 7 billion parameters!**  
✅ **Graph-Based Analysis:**  
   - **Hypergraph Generation:** Template-level model execution flow.  
   - **Computational Graph:** Detailed execution trace for individual operations.  
✅ **3D & 2D Visualizations:**  
   - Queue Space State-Action 3D Surface  
   - 3D Scatterplots of Memory, Time, and FLOPs  
✅ **Speech-to-Text Integration (Upcoming Feature! 🚀):** Planned support for Whisper to analyze the impact of speech-transcribed text on model performance.  
✅ **Computation Graph Glossary:** Defines each node operation, execution order, and efficiency metrics.  

## 📥 Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt
```

## 🛠 Usage
Run the profiler with default settings:

```bash
python main.py --model bert --sequence_length 512 --quantization int8
```

Select reinforcement learning methods:

```bash
python main.py --rl_method dqn
```

Test memory efficiency across GPUs:

```bash
python main.py --gpu A100 --quantization fp16
```

## 📊 Visualizations & Output
After execution, the profiler generates:
- Computational Graphs & Hypergraphs
- 3D Queue Space Visualizations
- Memory vs. FLOPs vs. Time Scatterplots
- Exportable Performance Data

**!!!! Users must provide their own nGrok token and HuggingFace token to run the program !!!!**

## 🔐 Code Access Policy
If you would like access to the code, you must provide a **legitimate reason** explaining why you need access. Additionally, we must manually **add you as a collaborator** before you can view or contribute to the project.

## 🔗 License
This project is licensed under **Apache 2.0**, meaning you are free to use it, but you must provide attribution to the original author.

**Copyright (c) 2025 [Christopher Salnave]**

