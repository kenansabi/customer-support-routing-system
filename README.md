# Customer Support Ticket Classification and Routing System

## Project Overview

This project classifies customer support tickets into:

- Complaint
- Sales Inquiry
- Spam

and routes them to the appropriate system.

## Technologies

- Python
- Pandas
- Scikit-Learn
- TF-IDF
- PyTorch
- Matplotlib

## Workflow

1. Data preprocessing
2. Label generation
3. TF-IDF vectorization
4. Train/Test split
5. PyTorch neural network training
6. Model evaluation
7. Ticket routing

## Model Architecture

Input Layer → Linear(123 → 64)

ReLU

Dropout(0.3)

Linear(64 → 3)

Output Classes:
- Complaint
- Sales Inquiry
- Spam

## Routing Logic

- Complaint → Customer Support System
- Sales Inquiry → AI Sales Assistant
- Spam → Spam Detection System

## Author

Kenan Sabi
