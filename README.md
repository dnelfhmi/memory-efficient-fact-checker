# 🧠 Memory-Efficient Fact Checker

This repository contains a set of Jupyter notebooks implementing a three-stage, memory-efficient fact-checking pipeline. The project focuses on scalable evidence retrieval, claim classification, and advanced reasoning for automated fact verification.

## 🚦 Stages

### 1️⃣ Stage 1 – Retrieval
Develop and evaluate a memory-efficient retriever and reranker system to identify the top-k evidence passages for each claim.

### 2️⃣ Stage 2 – Classification
Use the retrieved evidence to classify claims into one of three categories:
- ✅ **SUPPORTED**
- ❌ **REFUTED**
- ❓ **NOT_ENOUGH_INFO**

This stage leverages both supervised and in-context learning approaches.

### 3️⃣ Stage 3 – Advanced Reasoning
Explore advanced techniques such as Chain-of-Thought prompting and ensemble strategies to further improve evidence-based claim verification.

## 📒 Notebooks

- 📗 **Stage1.ipynb**: Experimental setups and results for Stage 1 (Retrieval).
- 📘 **Stage2_and_3_baseline.ipynb**: Initial/baseline runs for Stages 2 & 3 (Classification & Advanced Reasoning).
- 📙 **Stage2_and_3_train_exp.ipynb**: Experiments for Stages 2 & 3 using the train-claims dataset.
- 📕 **Stage2_and_3_dev_exp.ipynb**: Experiments for Stages 2 & 3 using the dev-claims dataset.

## 🚀 Getting Started

1. Clone this repository.
2. Open the notebooks in your preferred Jupyter environment.
3. Follow the instructions in each notebook to reproduce the experiments.

## 📄 License

This project is licensed under the terms of the [LICENSE](LICENSE) file in this repository. 