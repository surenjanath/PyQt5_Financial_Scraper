# PyQt5 - Financial Scraper! 

This app created to view financial data given a search query of Nasdaq codes:

## Start

- You can clone it and use it at your own discretion
- Please [open an issue](https://github.com/surenjanath/PyQt5_Financial_Scraper/issues/new) if anything is missing or unclear in this
  documentation.
  
  ## Direct Link to test exe file 
  
  Link : [Pyqt5 - Financial Scraper](https://drive.google.com/file/u/1/d/1Dy0U3XC8GMZRxI4fmsnV04IdjwOem2oS/view?usp=sharing)
 
 ## Pictures of GUI
  
  Welcome screen
  
  ![alt text](https://github.com/surenjanath/PyQt5_Financial_Scraper/blob/main/Images/Start.png?raw=true)
  
  Full App
  
  ![alt text](https://github.com/surenjanath/PyQt5_Financial_Scraper/blob/main/Images/Full.png?raw=true)
  
   Search 
  
  ![alt text](https://github.com/surenjanath/PyQt5_Financial_Scraper/blob/main/Images/Search.png?raw=true)
     
   Random Search 
  
  ![alt text](https://github.com/surenjanath/PyQt5_Financial_Scraper/blob/main/Images/RandomSearch.png?raw=true)
  
## Installation

In order to use this to it's full potential: Must have pyqt5 and python 3.9.6

Using pyqt5-tools designer in cmd to execute the pyqt5 designer application to edit the UI file

If you're looking at the code then it means that you're good at using python .: edit away.

To execute program just type the following in cmd :
```
python main.py
```
NB : Must have pyqt5 installed 

Alternatively, to run designer just type ` pyqt5-tools designer` in cmd.

To convert ui to py 

```
pyuic5 -x [ui file].ui -o [ui].py
```
## To convert .py to .exe
List of things to do before converting file to exe :
Navigate to [This folder](https://github.com/surenjanath/PyQt5_Financial_Scraper/tree/main/Convert_to_EXE)

- Convert ui to py if changes are made

add in these lines to main.py:
- import UI library 
in the main class WelcomeScreen under init function : self.setupUi(self)
- pass Ui_MainWindow to class WelcomeScreen
- delete self.loadUi()

then do the following : 

Install pyinstaller 
```pip install pyinstaller```

open cmd .
Run the following code : 

```
pyinstaller --onefile --windowed --icon=app.ico main.py
```

## Troubleshooting & debugging

- If it freezes , check your internet connection
- If lags , give it a few seconds.

## Video Sample
[![Watch the video](https://img.youtube.com/vi/gXHu0Qjavzw/hqdefault.jpg)](https://youtu.be/gXHu0Qjavzw)

