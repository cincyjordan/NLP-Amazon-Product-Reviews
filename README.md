# Text Classification: Bert-Based Uncased with PyTorch

This repository includes a Jupyter Notebook that incorporates a sentiment analysis model using the Bert-Based Uncased architecture, best described in the academic paper "BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding" by Devlin, Jacob, et al. “BERT: Pre-Training of Deep Bidirectional Transformers for Language Understanding.” arXiv, Cornell University, 11 Oct. 2018, https://arxiv.org/abs/1810.04805. Accessed 30 June 2024. 

<img src='https://nlp.gluon.ai/_images/bert-sentence-pair.png' width='800'>

## About

In this project, I will be using Hugging Face's Bert-Based Uncased encoder architecture to train a sentiment analysis model on an amazon product review dataset. This model will allow many different functions of a amazon's business such as marketing or product to analyze customer sentiment of the products they sell with high precision and speed to allow stakeholders to focus on the decision making process.

## Training 

- **Training:**
   - The model is trained using the Bert-Based Uncased
   - Hyperparameters:
     - **Epochs**: 4
     - **Batch Size**: 8
     - **Learning Rate**: 2e-5
     - **Weight Decay**: 0.01

## Results (First 10)

Input: me and the kids love this and play it everywhere waiting for our food while i'm shopping its a must have to keep everyone busy
Actual Label: 1
Prediction: 1 with probability 0.9556

Input: By boys promised I would like Angry Birds, and thy are right .It's A very fun game It's hard to put down once you get started.and easy to lose track of time when your playing.best game ever
Actual Label: 1
Prediction: 1 with probability 0.9508

Input: I downloaded this right after Christmas and have a hard time putting down, it's so addictive! My daughter has all of the Angry birds games on both the pc and my laptop, but she's not allowed to play on my Kindle. Why does this game draw me in so much? Th
Actual Label: 1
Prediction: 1 with probability 0.9498

Input: Who doesn't like angry birds? It's free and after you finish each episode, the next challenge is to do them all perfectly. It's harder than you might think.
Actual Label: 1
Prediction: 1 with probability 0.9505

Input: I think that my 5 year old loves this game the most of all of us in the family. She always says Bingo when she gets the high score in a level. I would recommend this game to one and all!!
Actual Label: 1
Prediction: 1 with probability 0.9534

Input: I had this already on my IPhone and I really like it so I knew on a bigger screen would be great, so I was right. Thanks for the free app I like it alot.
Actual Label: 1
Prediction: 1 with probability 0.9406

Input: This is another game that will keep a child entertained for hours if you let them. especially good for waiting rooms .
Actual Label: 1
Prediction: 1 with probability 0.9512

Input: This is one of my son's favorite games to play and he loves it. Really like that I could download this one
Actual Label: 1
Prediction: 1 with probability 0.9479

Input: This is a great &quot;bejewled&quot; type of game. The graphics are great and the combos keep things interesting. Unlike a lot of other match 3 games, the game feels like it is progressing and going somewhere, which I really liked. There are a bunch of l
Actual Label: 1
Prediction: 1 with probability 0.9356

Input: I absolutely loved it and tried the Space Birds, thought not as addicting, it is okay. Good when I'm not online.
Actual Label: 1
Prediction: 1 with probability 0.9446

## Getting Started
1. **Download the Amazon Product Reviews Dataset:**
   - Obtain the dataset from [Kaggle](https://www.kaggle.com/datasets/mahmudulhaqueshawon/amazon-product-reviews) and place it in the project directory.

2. **Set Up Google Colab (Optional):**
   - If using Google Colab, mount your Google Drive and store your Kaggle credentials using `google.colab.userdata`.

3. **Run the Jupyter Notebook:**
   - Open and execute the `NLP train_model` notebook to train and evaluate the model.
  

## Acknowledgments

- The Bert-Based Uncased architecture is based off of the published article "BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding" by Devlin, Jacob, et al. “BERT: Pre-Training of Deep Bidirectional Transformers for Language Understanding.” arXiv, Cornell University, 11 Oct. 2018, https://arxiv.org/abs/1810.04805. Accessed 30 June 2024. 
- The Amazon Product Reviews dataset is used for training and evaluation.

