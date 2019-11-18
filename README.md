# opentdb-cli

A simple CLI trivia client/game written in python and powered by the **Open Trivia Database API**. The API lives at https://opentdb.com/ and is created/maintained by the cool people at **PIXELTAIL GAMES LLC**.

The API and this application are licensed under the **Creative Commons BY-SA 4.0** license.

## Requirements

Python 3.7 (Earlier Python 3 may work as well)
Requests 2.22.0

## Installation

**Linux**
```
git clone https://github.com/plarabee/opentdb-cli.git
cd opentdb-cli
```

with pipenv:
```
pipenv install
pipenv run python3 opentdb-cli.py
```
with pip:
```
pip3 install requests
python3 opentdb-cli.py
```
(Optional) Make an alias:
```
echo 'alias trivia="python3 /path/to/opentdb-cli.py"' >> ~/.bashrc
source ~/.bashrc
trivia
```

## What's Next?

This is honestly a minimally viable product at this point. It is in dire need of error-handling when
reading user input. I would also like to fix the quotes in the API output (shows ANSI codes). Finally, 
I would like to jazz up the interface some either with colorama or something fancier.

