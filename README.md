# LLM Text Generation Mini Project

A simple project that converts bullet points into a professional email using a pre-trained language model.

## Overview

This project demonstrates how to use Hugging Face Transformers to generate structured text (emails) from simple bullet point inputs.

## Model Used

- **`google/flan-t5-base`** - An instruction-tuned encoder-decoder model that can follow natural language instructions to generate text.

## How It Works

1. User provides bullet points (e.g., "Sick Leave", "Monday", "Back on Tuesday")
2. Bullet points are formatted into a prompt with instructions
3. The model generates a complete professional email based on the input

## Requirements

```bash
pip install transformers torch
```

## Usage

Run the Jupyter notebook `text-gen.ipynb` to:
1. Load the model and tokenizer
2. Input your bullet points
3. Generate a professional email

## Example

**Input:**
- Sick Leave
- Monday
- Back on Tuesday

**Output:**
A professional email requesting sick leave for Monday with a return date of Tuesday.

## Author

**Nilay Srivastava**  
SRN: PES2UG23CS390