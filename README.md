# Visual-Aware Graph Convolutional Network (VAGCN) for Fashion Compatibility

## Project Description
This project aims to enhance item compatibility predictions in the fashion e-commerce domain through the innovative use of graph-based learning models. The Visual-Aware Graph Convolutional Network (VAGCN) leverages deep-stacked autoencoders to transform high-dimensional visual data from fashion items into actionable, low-dimensional insights. This technology enables a sophisticated analysis of compatibility across diverse fashion categories, including Men, Women, Boys, Girls, and Babies, improving predictive accuracy and user experience on e-commerce platforms.

## Repository Structure

### Notebooks
- **Build-Dataset.ipynb**: Prepares and structures the dataset for processing by the GCN. This includes initial data cleaning and setup.
- **extract_deep_features_using_AE.ipynb**: Utilizes autoencoders to reduce the dimensionality of raw CNN visual features, making them suitable for graph-based processing.
- **GAE_Training.ipynb**: Contains the training routines for the Graph Autoencoder, setting up the foundational model architecture.
- **GAE_Testing.ipynb**: Focuses on testing the GAE model by experimenting with various neighborhood sizes to optimize model performance.
- **Evaluation Results UC_ROC.ipynb**: Evaluates the VAGCN model using AUC-ROC metrics across different categories, presenting comparative results against traditional methods.

### Folders
- **trained models, results and logs**: Includes all trained models and detailed logs of the training process along with the results for compatibility predictions across all categories (Men, Women, Boys, Girls, Baby).

## Data Availability
The datasets used in this project were curated by the UCSD CSE department and are maintained by Professor Julian McAuley. These datasets can be accessed through the following link: [UCSD Datasets](https://cseweb.ucsd.edu/~jmcauley/).

## Results
Detailed performance analysis and comparative studies show that the VAGCN model not only meets but consistently exceeds established benchmarks, demonstrating its advanced ability to integrate and analyze complex product relationships through its sophisticated graph convolutional architecture. 

## Contact
- Umar Subhan Malhi – umarsubhanmalhi@outlook.com
