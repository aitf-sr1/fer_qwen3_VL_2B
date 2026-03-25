# QWEN 3-VL 2B

This project focuses on fine-tuning a Vision-Language Model (VLM) using Qwen3-VL (2B parameters) on a custom dataset.

## Features

* Dataset preprocessing and balancing
* Auto-labeling using GPT-4o mini
* Fine-tuning pipeline for Qwen3-VL
* Evaluation script for model performance

## Requirements

* Python 3.12.3 or higher
* uv for dependency management

## Environment Variables

This project uses a `.env` file to store configurations such as API keys and file paths.

Create a `.env` file in the root directory:

```
API_KEY=your_api_key_here
DATASET_PATH=your_dataset_path
OUTPUT_DIR=your_output_directory
```

Make sure `.env` is added to `.gitignore` and not uploaded to the repository.

## Installation

Clone the repository and install dependencies:

```
git clone <repository-url>
cd <repository-name>

uv sync
```

## Model

The main model used in this project is Qwen3-VL with 2 billion parameters.

For auto-labeling, this project uses GPT-4o mini.

## Usage

Run the fine-tuning process:

```
finetuning.ipynb
```

Ensure that the dataset path is set correctly in the `.env` file and all dependencies are installed.

## Evaluation

To evaluate the model:

```
evaluasi.ipynb
```

## Notes

This program is designed to run locally for fine-tuning. Ensure that your system has sufficient computational resources.

## Project Structure

```
preprocessin
auto-labeling 
fine-tuning
evaluation
```
