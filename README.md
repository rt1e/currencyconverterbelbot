**currencyconverterbelbot**

[![Python 3.8](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-3810/) [![Code Style: Black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black) [![PyPI](https://img.shields.io/pypi/v/currencyconverterbelbot)](https://pypi.org/project/currencyconverterbelbot/) [![Docker Image CI](https://github.com/rt1e/currencyconverterbelbot/actions/workflows/docker-image.yml/badge.svg)](https://github.com/rt1e/currencyconverterbelbot/actions/workflows/docker-image.yml) [![Docker Image CI](https://github.com/rt1e/currencyconverterbelbot/actions/workflows/docker-image.yml/badge.svg)](https://github.com/rt1e/currencyconverterbelbot/actions/workflows/docker-image.yml) [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

**Description**

Bot showing exchange rates of Belarusian banks **(Long Poll)**

**how to use**

- [clone or fork this repo](#clone-or-fork-this-repo)
- [install from pypi](#install-from-pypi)
- [run as docker container](#run-as-docker-container)

## clone or fork this repo

- edit the ```config.py``` in folder ```currencyconverterbelbot``` (enter your bot token received from @BotFather to access the HTTP API) or define the TO:KEN as an argument
- run ```poetry install```
- run ``` python3 bot.py -t TOKEN``` if TOKEN in config.py or run ``` python3 bot.py -t TO:KEN```

## install from pypi

- run ```poetry add currencyconverterbelbot```
- run ```currencyconverterbelbot -t TOKEN``` if TOKEN in config.py or run ```currencyconverterbelbot -t TO:KEN```

## run as docker container

- run ```docker build -t currencyconverterbelbot .```
- edited token in ```Dockerfile```
- run ```docker run currencyconverterbelbot```
