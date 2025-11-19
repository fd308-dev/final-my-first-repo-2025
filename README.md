# final-my-first-repo-2025

# My First Repo!

Learning and practicing version control!

## Setup

Clone the Repo to download it from GitHub. Perhaps onto the Desktop.

Navigate to the repo using the command line.

``` sh
cd ~/Documents/final-my-first-repo-2025
```
## Configuration
The stocks functionality requires an AlphaVantage API key. Obtain a premium AlphaVantage API Key (using the [form](https://www.alphavantage.co/support/#api-key) or shared by the prof).

Create a local ".env" file and store your environment variable in there:


```sh
# this is the ".env" file...

ALPHAVANTAGE_API_KEY="______________"
# also tell flask where our web app is defined:
FLASK_APP=web_app
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

# replace "demo" with your premium key:
ALPHAVANTAGE_API_KEY="demo"
Also, for the stocks tests to work on GitHub Actions, you will need to set a repository secret named ALPHAVANTAGE_API_KEY via the repository's settings on GitHub.

Usage
Play a game of rock, paper scissors:

# only works if this file does NOT import from other local py files:
python app/rps.py

# if this file imports from other local py files:
Run the stocks dashboard:

python -m app.stocks

# find all the tests and run them:
pytest

### Web App

Run the web app (then view in the browser at http://localhost:5000/):

```sh
 # if we have the FLASK_APP=web_app env var in the ".env" file:
flask run
```
# Mac OS:
FLASK_APP=web_app flask run

# Windows OS: 
# ... if `export` doesn't work for you, try `set` instead
# ... or set FLASK_APP variable via ".env" file
export FLASK_APP=web_app
flask run
