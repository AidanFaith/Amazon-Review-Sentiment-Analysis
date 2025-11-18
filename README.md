This repo houses a sentiment analysis practice project following the tutorial by Rob Mulla:

Tutorial Link: https://www.youtube.com/watch?v=QpzMWQvxXWk

This project utilizes two models: VADER (a "Bag of Words" model) and Roberta (a Hugging Face transformer model pre-trained on sentiment).

Dataset: "Amazon Fine Food Reviews" - the dataset is a Kaggle CSV of Amazon food reviews collected over 10 years and ending in 2012. 

Dataset Link: https://www.kaggle.com/datasets/snap/Amazon-fine-food-reviews

NOTE: I downsized the CSV as the file was too big to upload to GitHub. This project uses only the first 500 reviews just for practice's sake, and the input file now consists of the first 1000 reviews. The model training can be upscaled with the entire dataset by redownloading from Kaggle and renaming the file to "Reviews.csv" in your directory.
