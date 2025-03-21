 # Fake News Detection using RoBERTa

This project demonstrates how to fine-tune the RoBERTa model for fake news detection using two datasets: BuzzFeed and ISOT. The goal is to classify news articles as either "fake" or "real" based on their content using a pre-trained RoBERTa model.

# Datasets

**1. BuzzFeed Dataset**

The BuzzFeed dataset contains articles labeled as "fake" or "real".
This dataset is used as one of the main sources of data for training the fake news detection model.

**2. ISOT Dataset**

The ISOT dataset includes various news articles with labels for "fake" and "real" news.
It provides additional data for training and evaluation of the model.

# Project Structure

**data/:** Contains the dataset files (e.g., buzzfeed.csv, isot.csv).

**code:** Contains the Python script for fine-tuning RoBERTa.

**requirements.txt**: Lists the dependencies for running the project.

# How to Run
**Prepare the Dataset:**

Place your buzzfeed.csv and isot.csv files in the data/ directory.

Ensure that both datasets have a text column containing the news article content and a label column with binary labels (0 for fake, 1 for real).

#Run the python file:



# Model Architecture

The model uses a RoBERTa architecture for text embedding, followed by a linear classifier for binary classification (fake news or real news). The main components are:

**RoBERTa Model:** Pre-trained transformer-based model for generating contextual word embeddings.

**Linear Classifier:** A fully connected layer that predicts whether the news is real or fake based on the embeddings from RoBERTa.
# if you found this repository helpful please cite our paper:
@inproceedings{safdar2024rafah,


  title={RAFAH: RoBERTa Fine-Tuned Model and a Hybrid Features Set for Fake News Detection},

  
  author={Safdar, Sehrash and Wasim, Muhammad},

  
  booktitle={2024 18th International Conference on Open Source Systems and Technologies (ICOSST)},

  
  pages={1--6},

  
  year={2024},

  
  organization={IEEE}

  
}


