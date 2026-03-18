🍽️ Smart Restaurant Using AI

An AI-powered restaurant system that enhances customer experience through personalized food recommendations, automated ordering, and smart interaction using deep learning.

📌 Project Overview

The Smart Restaurant Using AI system is designed to modernize traditional restaurant operations by integrating artificial intelligence. It provides:

Personalized food recommendations

Digital ordering system

Efficient restaurant management

The system uses a Convolutional Autoencoder (CAE) to analyze food relationships and suggest relevant combinations to users.

🎯 Objectives

Improve customer experience through smart recommendations

Reduce dependency on waiters for ordering

Provide a seamless digital food ordering system

Enhance operational efficiency in restaurants

❗ Problem Statement

Design and implement a recommendation system using Convolutional Autoencoder to suggest food combinations based on user-selected items.

💡 Key Features

🍜 AI-based food recommendation system

📱 Digital menu & ordering system

🔐 User login system

🧠 Deep learning-based recommendation engine

🛒 Cart and ordering interface

⚡ Fast and efficient processing

🧠 AI Model Used
Convolutional Autoencoder (CAE)

Converts food relationships into an adjacency matrix

Learns patterns between food items

Generates low-dimensional representations

Uses similarity measures to recommend items

🔄 Workflow

Dataset collection (5100+ rows)

Data preprocessing

Convert data into adjacency matrix

Train Convolutional Autoencoder

Extract feature representations

Compute similarity between items

Generate top-k recommendations

📊 Dataset Details

Total Rows: 5100

Unique Dishes: 4893

Columns:

Item

Combination1

Combination2

Combination3

⚙️ Technologies Used
💻 Programming & Tools

Python

Google Colab

Jupyter Notebook

📚 Libraries

TensorFlow

Keras

NumPy

Pandas

Matplotlib

Gradio

🖥️ System Requirements
Hardware

GPU (recommended)

Minimum 12GB RAM

SSD Storage

Software

Python 3.x

Required libraries (see requirements)

📈 Model Training

Training Samples: 4896

Testing Samples: 612

Epochs: 20

Loss Function: MSE (Mean Squared Error)

Optimizer: Adam

📊 Evaluation Metrics

Precision@K

Recall@K

These metrics measure the accuracy and effectiveness of recommendations.

🖥️ Implementation
1. Gradio Interface

Interactive UI for recommendations

Takes input and shows predicted suggestions

2. Web Application

Login page

Menu display

Recommendation system

Cart system

🚀 Applications

Personalized food recommendation

Automated ordering systems

Restaurant management optimization

AI-based customer interaction

🔮 Future Enhancements

Advanced personalization using real-time data

NLP-based feedback analysis

Augmented Reality (AR) menu

Voice-based ordering system

📚 References

Zhang et al., Collaborative Convolution AutoEncoder for Recommendation Systems

Xue et al., Deep learning-based classification using CAE
