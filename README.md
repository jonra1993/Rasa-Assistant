# Rasa-Assistant

## Setup

### Python setup
Currently this projects just work using **python 3.7** so It is recommend that make sure you have this python version. To check run on command line:
```
python3 --version
```

If you do not have the correct version, please download it from [here](http:/https://www.python.org/downloads// "here")


### Installation
The following commands helps to install python packages needed to make this project run correctly locally.
```
pip3 install poetry
https://github.com/jonra1993/Rasa-Assistant.git
cd Rasa-Assistant
```

#### Package setup using poetry
```
poetry shell
poetry install
poetry add "rasa[full]"
poetry add https://pypi.rasa.com/api/package/rasa-x/rasa_x-0.42.5-py3-none-any.whl
python3 rasa train
```

## Development

### Activate ngrok to serve on https
In order to make this example to test, please use ngrok. You can setup ngrok in you pc from [here](https://ngrok.com/ "here").

Run on console the following command. It will expose 5005 local port on internet.
```
./ngrok http 5005
```

### Start project
Run on console the following command. It will start project on port 5005
```
poetry shell
rasa shell
rasa run --enable-api --cors "*"
```

poetry run python myscript.py

poetry run production

## Extras
- [Rasa API](https://rasa.com/docs/rasa/pages/http-apihttp:// "Rasa API")
- [Poetry Manager](https://hackersandslackers.com/python-poetry-package-manager/ "Poetry Manager")
- [Poetry doc](https://python-poetry.org/docs/cli/ "Poetry doc")