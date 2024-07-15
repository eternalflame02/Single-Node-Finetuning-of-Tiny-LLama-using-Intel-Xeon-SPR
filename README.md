<h1 align="center" id="title">Single-Node-Finetuning-of-Tiny-LLama-using-Intel-Xeon-SPR</h1>

<p align="center"><img src="https://socialify.git.ci/eternalflame02/Single-Node-Finetuning-of-Tiny-LLama-using-Intel-Xeon-SPR/image?font=Source%20Code%20Pro&amp;name=1&amp;pattern=Circuit%20Board&amp;theme=Dark" alt="project-image"></p>

<p id="description">This repository contains the implementation of Single-Node Finetuning of the Tiny LLaMA language model utilizing Intel Xeon Scalable Processors (SPR). The project was undertaken as part of the Intel Unnati Industrial Training program for the year 2024. The primary objective of this project aligns with Problem Statement PS-04: Introduction to Generative Artificial Intelligence (GenAI) Basic Large Language Model (LLM) Inference on CPUs and subsequent LLM Model Finetuning for the development of a Custom Chatbot.</p>

<h2>🛠️ Installation Steps:</h2>

<p>1. Prepare Environment(Execute them in terminal):</p>

```
conda create -n itrex-1 python=3.10 -y
```

```
conda activate itrex-1
```

```
pip install intel-extension-for-transformers
```

```
git clone https://github.com/eternalflame02/Single-Node-FInetuning-of-Tiny-LLama-using-Intel-Xeon-SPR.git
```

```
cd ./Single-Node-FInetuning-of-Tiny-LLama-using-Intel-Xeon-SPR/Fine Tuning/
```

```
pip install -r requirements.txt
```

```
huggingface-cli login
```

```
python3 -m pip install jupyter ipykernel
```

```
python3 -m ipykernel install --name neural-chat--user
```
