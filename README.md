# Tic Tac Toe Game

This is a tic tac toe game playable in the terminal

## How to play

1. Make sure you have Python installed

## How to Develop

### Setup fresh development environment

```
# create empty git repo on GitHub
# clone the git repo from GitHub
git clone https://github.com/ianchen06/techin509-au24-tictactoe
cd techin509-au24-tictactoe

# setup a new virtual environment, and activate it for this terminal session
python -m venv venv
source venv/bin/activate

# Install packages and freeze into requirements.txt file
pip install numpy openai django
pip freeze > requirements.txt

# commit requirements.txt to GitHub so others can use to reproduce your environment
git add requirements.txt
```

### Setup Environment for developing exiting project

```
# clone exiting project from GitHub
git clone https://github.com/ianchen06/techin509-au24-tictactoe
cd techin509-au24-tictactoe

# Create and activate Python virtual environment
python -m venv venv
source venv/bin/activate

# Install packages listed in requirements.txt to the virtual environment
pip intall -r requirements.txt
```

### Git Review

#### commit and push new version

```
git status
git add README.md
git commit -m 'updated README to include set up instructions'
git push origin main
```
