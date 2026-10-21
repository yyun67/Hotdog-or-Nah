# Hotdog-or-Nah

Google Colab Link - https://colab.research.google.com/drive/1KpRyPqUWGXYEzjrWbdRFOfHhVPys_ID8?usp=sharing
Temporary Gradio link - https://f00aaeb2755cdf4bbd.gradio.live/

An end-to-end binary image classification pipeline and interactive interface that determines whether an uploaded image contains a hotdog or not, trained on a public Kaggle dataset.
Dataset: https://www.kaggle.com/datasets/dansbecker/hot-dog-not-hot-dog

Implemented the following core features:
- Data Preprocessing: Load the dataset, normalize pixel values, and resize all images to a consistent input dimension suitable for your network.
- Data Splitting: Properly split the data into Training and Validation/Testing sets to evaluate generalization without data leakage.
- Model Training: Train a binary image classifier capable of distinguishing between the two classes (hot_dog vs. not_hot_dog ).
- Evaluation Metrics: Output the model’s Accuracy
- Custom Inference: Provide a function or simple interface where a user can pass a brand-new image file (outside the dataset) and receive a class prediction along with the model’s confidence score.
