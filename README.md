# Udacity_Project_TV_Script (RNN - LSTM)

This was a REALLY interesting project.  Here we get to play with a Recurrent Neural Network (RNN).  We take all of the scripts from all of the Seinfeld TV episodes and train our RNN to generate scripts from nothing.  Granted, the script output is a bit off ... but the "essence" of a Seinfeld script is there.  It will blow your mind.  Makes me wonder what it would take to craft a model that can write a fiction novel with just a few parameters input.  I've actually been loosing sleep over this question.

The Seinfeld scripts are pulled from here [Seinfeld Dataset](https://www.kaggle.com/thec03u5/seinfeld-chronicles#scripts.csv).

There is good code in here that does good stuff.  Hopefully there is content here that I can cut/past/modify for future projects as well.  Key code is offered for the following steps:

- Pull the data

- Data pre-processing
     - Here I make a lookup table vs. a HUGE collection of one-hot encoded vectors.
     - Pull the punctuation
     - Create tokens
     - Batch up the data
     - Load the data
     
-Build a Neural Network
     - Long Short Term Memory RNN

- Create the forward and back propagation

- Set Hyperparameters

- Train the Network

- And finally, generate a sample script from noise.
