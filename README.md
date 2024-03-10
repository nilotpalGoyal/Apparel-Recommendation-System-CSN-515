# Apparel-Recommendation-System-CSN-515

In the modern era of e-commerce, personalized recommendations play a pivotal role in
enhancing user experience and driving sales. This project introduces an innovative Apparel
Recommendation System, leveraging machine learning techniques to offer tailored clothing
suggestions to users based on their preferences, past purchases, browsing history, and
demographic information. The system employs content-based filtering approach to provide
accurate and diverse recommendations, thereby addressing the challenge of information
overload and helping users discover relevant apparel items effortlessly. Through extensive
experimentation and evaluation, the efficacy and performance of the recommendation system
are demonstrated, showcasing its potential to revolutionize the online apparel shopping
experience.

## How to run project

1. Clone the project repository to your local machine.
2. upload ipynd to google colab.
3. Install all the required libraries given below.
4. Now run all components of ipynb one by one, if any component stops in between re-run it again.
5. And if any segment of ipynb have some comment like "uncomment this if you are running this for first time" then for the first time uncomment all the code in that segment, it is for mainly downloading dataset or saving model if once trained.

## Requirements

- Python 3.x
- Jupyter Notebook
- TensorFlow
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Usage

1. *Data Loading and Preprocessing*: Load the images and metadata using pandas and preprocess the data for further analysis.
2. *Exploratory Data Analysis*: Visualize the distribution of different attributes of fashion items using matplotlib and seaborn.
3. *Feature Extraction*: Use a pre-trained VGG16 model to extract features from the images.
4. *PCA*: Apply PCA to reduce the dimensionality of the extracted features for visualization.
5. *Nearest Neighbors Classification*: Use K-Nearest Neighbors to find similar fashion items based on their features.
