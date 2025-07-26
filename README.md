# Multi-Modal Sentiment Analysis for Predicting Mental Health Trends

## Overview
This project uses Natural Language Processing (NLP), Computer Vision, and data fusion to analyze social media posts. It aims to identify sentiment patterns that correlate with mental health indicators like anxiety, depression, and stress at a population level.

## Objectives
- Extract sentiment from text, images, and post behavior.
- Fuse multi-modal features into a unified deep learning model.
- Visualize trends and detect potential mental health crises early.

## Tools & Technologies
- **Transformers (BERT)**, **TextBlob**, **VADER**
- **CNNs (ResNet/MobileNet)** for image sentiment
- **Fusion models** using attention layers
- **Dash/Plotly** for trend dashboard

## Folder Structure
data/ - Tweets, Instagram images  
notebooks/ - NLP, Vision, Fusion notebooks  
models/ - Saved NLP and CV models  
outputs/ - Sentiment scores and dashboards  
src/ - Python modules for each task

## Notebooks
- `nlp_sentiment.ipynb`: Sentiment analysis from text  
- `vision_analysis.ipynb`: Image-based emotion detection  
- `fusion_model.ipynb`: Multi-modal prediction and visualization

## Sample Output
> Trend: Increase in negative sentiment tweets in Q2  
> Alert: Mental health decline among teenagers in region X

## Impact
Supports mental health NGOs, government health departments, and researchers in identifying at-risk populations using social media signals.
