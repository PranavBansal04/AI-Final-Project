# Solving Wordle using Artificial Intelligence

In this project we have implemented several AI algorithms to play wordle. 

*Rules of the standard game*:

* Your goal is to guess a 5 letter word.
* You have 6 chances to guess the word.
* Whenever you guess a word, the game will provide feedback as follows:
  1. all correct letters in correct positions will turn green. 🟩
  2. correct letters in wrong positions will turn yellow. 🟨
  3. wrong letters will turn gray. ⬛

Tha game.py file contains the Game class for playing the standard wordle game.

To play the game, run main.py file which will open up a Tkinter GUI.


## Requirements

The provided code is written in Python 3.9. Following libraries are required for runnin the game:

- tkinter
- requests
- pandas
- string
- IPython


## Setup

1. The best way to use this code is to [clone the repository](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository) to your local machine. To do so in VS Code, open a terminal and navigate to the parent directory of your choice using the `cd` command, e.g.:

        $ cd ~/Documents/wordle

    Then, use `git clone` to create a new subdirectory called wordle with the code from this repository:

        $ git clone https://github.com/emilyjcosta5/AI-Final-Project

    Go into the directory and make sure the appropriate files are there by using the `ls` command:

        $ cd wordle
        $ ls

2. Before running the code, you need to make sure the required libraries are installed. The recommended way to do this is to [create a virtual environment](https://docs.python.org/3/library/venv.html) so that you can have separate environments for different projects. To create a virtual environment, use the `venv` command:

        $ python -m venv /path/to/new/virtual/environment

    If you do not have a preferred location for your environments, try putting them in a hidden folder in your home directory, such as:

        $ python -m venv ~/.venv/wordle

    Next, you need to activate the virtual environment using the `source` command:

        $ source ~/.venv/wordle/Scripts/activate

    You will know that you have done it correctly if you see the environment name in parentheses in your terminal, e.g. (wordle). After you are in your virtual environment, use `pip install` to install the libraries you need. It is easiest to do this with the requirements.txt file provided in the repository.

        $ pip install -r requirements.txt
        $ pip list

    Note that the second command above will list all installed libraries, which is useful for verification purposes.
    
    
 
## Usage

Use the following commands to play the game:

- To play Wordle as a human player,

        $ python main.py
        
  Below is a sample run:
  
  ![image](https://github.com/pranavbansal04/AI-Final-Project/blob/main/Images/game_example.png?raw=true)
  

- To play Wordle using an AI player,

        $ python algorithms.py
        
  Below is a sample run for algorithms.py:
  
 ![img2](https://github.com/pranavbansal04/AI-Final-Project/blob/main/Images/algo_run.png?raw=true)


- To evaluate the performance of different algorithms,
  
        $ python evaluation.py
  
  All the outputs are generated inside the output folder.



## Performance Analysis of the Algorithms


![img112](https://github.com/pranavbansal04/AI-Final-Project/blob/main/Images/wordle_cmp_algos.jpg?raw=true)

![img11](https://github.com/pranavbansal04/AI-Final-Project/blob/main/Images/cmp_word_length.jpg?raw=true)