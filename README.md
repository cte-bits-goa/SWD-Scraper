# SWD-Scraper
A Selenium based scraper for student info in BITS Pilani, Goa Campus

## Requirements
If you have only python 3 installed try
```python``` instead of ```python3```

macOS:
1. [Firefox](https://www.mozilla.org/en-US/firefox/new/)
2. [Python 3](https://www.python.org/downloads/)
3. Run the below code
```
python3 -m pip install -r requirements.txt
./geckodriver-install.sh
xattr -r -d com.apple.quarantine geckodriver
```
Linux:
1. [Firefox](https://www.mozilla.org/en-US/firefox/new/)
2. [Python 3](https://www.python.org/downloads/)
3. Run the below code
```
python3 -m pip install -r requirements.txt
./geckodriver-install.sh
```
Windows:
1. [Firefox](https://www.mozilla.org/en-US/firefox/new/)
2. [Python 3](https://www.python.org/downloads/)
3. [Geckodriver](https://github.com/mozilla/geckodriver/releases)
4. Run the below code
```
python3 -m pip install -r requirements.txt
```

## Instructions
1. The main scrapper can be run as follows
```
python swd_scrapper.py <filename>
```
- If there is a file called `data.csv` in the `csvs` folder then mentioning the filename is optional.
- SWD Website mandates the entry of username and password. Hence enter the username and password when prompted.

2. Instructions for the source file:
- The source file contains the names and IDs of the students whose names are to be extracted.
- Make sure that the names are put inder column name `Name` and IDs are put under column name `Id`.

3. The extracted data will be saved in the `csvs` folder with filename `data_extracted.csv`

## Issues
Please feel free to put up any issues or bugs in Issues. Feel free to contribute by sending a Pull Request.
