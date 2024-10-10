## Emotion-Recognition
This project is an emotion classification tool built using the distilbert-base-uncased model from Hugging Face's transformers library. The tool classifies a given text into one of five emotions: anger, fear, joy, sadness, or surprise. It includes a simple graphical user interface (GUI) built with Tkinter for user-friendly interaction.

## Table of Contents
Overview
Features
Installation
Usage
Training the Model
Model Performance
License

## Overview
This project leverages DistilBERT, a lighter and faster variant of BERT, for the task of emotion classification. Given a sentence or text input, the model predicts the corresponding emotion. The GUI provides an easy interface for non-technical users to interact with the model.

Key Technologies
Transformers: Hugging Face's transformers library to load and fine-tune the distilbert-base-uncased model.
PyTorch: For deep learning model training and inference.
Tkinter: A Python library for creating the GUI.
Features
Classifies input text into one of five emotions: anger, fear, joy, sadness, or surprise.
Pre-trained on distilbert-base-uncased for state-of-the-art NLP performance.
Simple and intuitive GUI using Tkinter for ease of use.
GPU acceleration support via PyTorch (CUDA-enabled if available).

## Installation
# Prerequisites
Before running the project, ensure you have the following installed:

Python 3.8+
pip for package management
PyTorch (with GPU support if available)
Hugging Face transformers library
