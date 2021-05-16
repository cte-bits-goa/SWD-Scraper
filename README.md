# SWD-Scraper
A Selenium based scraper for student info in BITS Pilani, Goa Campus

## Requirements
1. Python 2.7 and above.
2. Selenium
3. Pandas
4. tqdm
5. logging
6. [Geckodriver] (https://github.com/mozilla/geckodriver/releases)

## Instructions
1. If the operating systen is macOS, the below code has to be run in the directory containing [Geckodriver] (https://github.com/mozilla/geckodriver/releases)
```
xattr -r -d com.apple.quarantine geckodriver
```
2. The main scrapper can be run as follows
```
python swd_scrapper.py <filename>
```
- If there is a file called `data.csv` in the `csvs` folder then mentioning the filename is optional.
- SWD Website mandates the entry of username and password. Hence enter the username and password when prompted.

3. Instructions for the source file:
- The source file contains the names and IDs of the students whose names are to be extracted.
- Make sure that the names are put inder column name `Name` and IDs are put under column name `Id`.

4. The extracted data will be saved in the `csvs` folder with filename `data_extracted.csv`

## Issues
Please feel free to put up any issues or bugs in Issues. Feel free to contribute by sending a Pull Request.
