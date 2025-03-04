# AI-Powered Fashion Recommender System

This project implements a **fashion recommendation system** that analyzes a dataset of clothing items (e.g., hats, pants, shoes) and recommends visually similar items based on an input image. It extracts **image embeddings** using a deep learning model and applies **K-Nearest Neighbors (KNN)** to find and suggest similar fashion items.

## Watch a Demo
[See end of Fashion_Recom_Model.ipynb](https://github.com/cajabor/fashion-recommender/blob/main/Fashion_Recom_Model.ipynb) 

## Technical Challenges Solved
- **Feature Extraction from Images**: Uses a deep learning model to transform images into numerical embeddings that represent their visual characteristics.
- **Efficient Nearest Neighbor Search**: Implements **K-Nearest Neighbors (KNN)** to quickly identify and recommend similar fashion items from a large dataset.
- **Dimensionality Reduction & Visualization**: Embeddings are projected into a lower-dimensional space, allowing for effective visualization and similarity search.
- **Scalability for Large Datasets**: The system efficiently processes a large number of fashion items, ensuring fast and accurate recommendations.

## Features
- **Image-Based Search**: Input an image, and the model recommends similar fashion items.
- **Deep Learning Embeddings**: Uses a pre-trained model (e.g., ResNet, ViT, or EfficientNet) to extract meaningful visual features.
- **Fast Similarity Matching**: Implements KNN to retrieve the most visually similar items in real time.
- **GRaphical User Interface**: Sreamlit powered UI for more user friendly recommendation interactions,



# fashion-recommender  🚧 Under construction🚧
Fashion recommender uses CNNs, collaborative filtering and feature extraction to recommend similar outfits to users based on user input. App hosted using streamlit. Run app.py
