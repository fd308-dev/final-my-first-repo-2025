# final-my-first-repo-2025

# My First Repo!

Learning and practicing version control!

## Setup

Clone the Repo to download it from GitHub. Perhaps onto the Desktop.

Navigate to the repo using the command line.

``` sh
cd ~/Documents/final-my-first-repo-2025
```


## Usage
Example Script:

```sh
python app/my_script.py
```

Game of Rock Paper Scissors:


```sh
python app/rps.py
```
Create a virtual environment:

```sh
conda create -n my-first-env-fall-2025 python=3.11
```

Activate the virtual environment:
conda activate my-first-env-fall-2025
```sh

```

Install package dependencies:

```sh
pip install -r requirements.txt

## Testing

Run tests:

```sh
pytest
```

# pip install pytest

pip install -r requirements.txt
Secret Credentials
For the stocks dashboard, you will need to acquire a "premium" AlphaVantage API key (from the prof) and supply it as an environment variable. Create a local ".env" file and place inside contents like the following:

# this is the ".env" file...

# replace "demo" with your premium key:
ALPHAVANTAGE_API_KEY="demo"
Also, for the stocks tests to work on GitHub Actions, you will need to set a repository secret named ALPHAVANTAGE_API_KEY via the repository's settings on GitHub.

Usage
Play a game of rock, paper scissors:

# only works if this file does NOT import from other local py files:
python app/rps.py

# if this file imports from other local py files:
python -m app.rps
Run the stocks dashboard:

python -m app.stocks
Tests
Run the tests:

# find all the tests and run them:
pytest
