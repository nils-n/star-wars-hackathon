# star-wars-hackathon

# Installation and Setup 

- for Mac OS
- install VS Code
- clone the repository
```
git clone https://github.com/bezebee/star-wars-hackathon.git
cd star-wars-hackathon && code .
```
- in VS Code > New Terminal 
- install virtual environment 
```
python3 -m venv work_env
```

- Select "Yes" to select virtual python as Interpreter
- confirm that python3 is from venv 
```
which python3 
```
- install packages and run the game
```
python3 -m pip install -r requirements.txt
python3 assets/scripts/game.py
```