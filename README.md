# sensortag-weather


## Setup 

```bash
# clone the repository
git clone https://github.com/vithursant/sensortag-weather.git`
cd sensortag-weather

# install dependencies
sudo apt-get install python-dev libglib2.0-dev 
pip install -U gspread oauth2client PyOpenSSL

# install bluepy
sudo apt-get install git build-essential
git clone https://github.com/IanHarvey/bluepy.git
cd bluepy
python setup.py build
sudo python setup.py install
```


## Run script

```bash
python sensortag_weather.py
```