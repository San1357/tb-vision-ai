

# TB-Vision AI

AI-based screening system for early detection of Tuberculosis (TB) using chest X-ray images.

## Problem
Tuberculosis diagnosis requires trained radiologists, who are often unavailable in rural and resource-constrained healthcare centers. Delayed diagnosis leads to disease spread and increased mortality.

## Solution
TB-Vision AI is a deep learning-based screening tool that analyzes chest X-ray images and classifies them as TB-positive or normal. The system is designed as a decision-support tool to help healthcare workers prioritize high-risk cases.

## Approach
- Chest X-ray image analysis using CNN
- Transfer learning with pretrained models (ResNet/DenseNet)
- Binary classification (TB vs Normal)
- Grad-CAM for explainability

## Dataset
Publicly available TB chest X-ray datasets from NIH, Shenzhen Hospital, and Kaggle.

## Demo Plan
A simple web interface where users upload an X-ray image and receive a prediction with a confidence score.

## Disclaimer
This tool is intended for screening purposes only and does not replace professional medical diagnosis.

## Status
Project under active development for hackathon submission.
