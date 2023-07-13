# README

## First Time:

### Setup python virtual enviroment

MacOS:
`python3 -m venv env`

Windows:
`python -m vent env`

### Activate virtual environment

MacOS:
`source ./env/bin/activate`

Windows:
`env\Scripts\activate`

### Install dependcies

`pip install -r requirements.txt`

### Setup Directory structure

Need to have the data file in the following location:

#### Mosquito Data

`<year>/Mosquito Count Graphs <year>.xlsx`

example:

`2023/Mosquito Count Graphs 2023.xlsx`

#### Spray Data

`sprays.csv`

#### Trap sites

`trap_sites.csv`

#### Weather

`weather.csv`

## Run the script

MacOS:
`python3 Data_Handler.py`

Windows:
`python Data_Handler.py`