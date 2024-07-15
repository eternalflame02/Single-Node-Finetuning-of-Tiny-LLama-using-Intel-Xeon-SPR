<h1 align="center" id="title">Single-Node-Finetuning-of-Tiny-LLama-using-Intel-Xeon-SPR</h1>

<p align="center"><img src="https://socialify.git.ci/eternalflame02/Single-Node-Finetuning-of-Tiny-LLama-using-Intel-Xeon-SPR/image?font=Source%20Code%20Pro&amp;name=1&amp;pattern=Circuit%20Board&amp;theme=Dark" alt="project-image"></p>

<p id="description">This repository contains the implementation of Single-Node Finetuning of the Tiny LLaMA language model utilizing Intel Xeon Scalable Processors (SPR). The project was undertaken as part of the Intel Unnati Industrial Training program for the year 2024. The primary objective of this project aligns with Problem Statement PS-04: Introduction to Generative Artificial Intelligence (GenAI) Basic Large Language Model (LLM) Inference on CPUs and subsequent LLM Model Finetuning for the development of a Custom Chatbot.</p>

<h2>🛠️ Installation Steps:</h2>

<h3>1. Environment Setup(Execute them in terminal):</h3>

<p>Set up a Python environment with the necessary dependencies.</p>
<p>1.1.  Create and activate a Conda environment:</p>

```
conda create -n itrex-1 python=3.10 -y
conda activate itrex-1
```
<p>This creates a new Conda environment named itrex-1 with Python 3.10 and activates it.</p>

<p>1.2.	Install required Python packages:</p>

```
pip install intel-extension-for-transformers
```

<h3>2. Cloning the Repository</h3>
<p>2.1.	Clone the repository:</p>

```
git clone https://github.com/eternalflame02/Single-Node-FInetuning-of-Tiny-LLama-using-Intel-Xeon-SPR.git
```
<p>2.2.	Navigate to the fine-tuning directory:</p>

```
cd ./Single-Node-FInetuning-of-Tiny-LLama-using-Intel-Xeon-SPR/Fine Tuning/
```

<h3>3. Installing Additional Dependencies</h3>
<p>Install additional dependencies required for fine-tuning.</p>
<p>3.1.	Install dependencies from the requirements.txt file:</p>


```
pip install -r requirements.txt
```
<p>3.2.	Install Jupyter and IPython kernel:</p>

```
python3 -m pip install jupyter ipykernel
python3 -m ipykernel install --name neural-chat--user
```
<h3>4. Setting Up Hugging Face Authentication</h3>
<p>Authenticate with Hugging Face to access and download models.</p>
<p>4.1.	Login to Hugging Face:</p>

```
huggingface-cli login
```
<p>Create a token in https://huggingface.co/settings/tokens insert them in the huggingface login interface.</p>

<h3>5. Downloading Data</h3>
<p>Download the dataset required for fine-tuning.</p>
<p>1.	Download the Alpaca dataset:</p>

```
Curl -O https://github.com/tatsu-lab/stanford_alpaca/raw/main/alpaca_data.json
```