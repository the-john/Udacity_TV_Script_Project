# Udacity_Project_TV_Script (RNN - LSTM)

This was a REALLY interesting project.  Here is my first attempt to craft a Recurrent Neural Network (RNN).  I take all of the scripts from all of the Seinfeld TV episodes and train my Long Short Term Memory (LSTM) RNN to generate scripts from nothing.  Have a look at the jupyter notebook [dlnd_tv_script_generation.ipynb](https://github.com/the-john/Udacity_TV_Script_Project/blob/master/dlnd_tv_script_generation.ipynb).  An HTML version of the project can be found here [dlnd_tv_script_generation.html](https://github.com/the-john/Udacity_TV_Script_Project/blob/master/dlnd_tv_script_generation.html).

Granted, the script output is a bit off ... but the "essence" of a Seinfeld script is there.  It will blow your mind.  Makes me wonder what it would take to craft a model that can write a fiction novel with just a few input parameters.  I've actually been loosing sleep over this question.

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

# Generated Scripts
You can actually see the outcome of the LSTM model here [generated_script_1.txt](https://github.com/the-john/Udacity_TV_Script_Project/blob/master/generated_script_1.txt) and here [generated_script_2.txt](https://github.com/the-john/Udacity_TV_Script_Project/blob/master/generated_script_2.txt).
