# SWD-Scraper
A Selenium based scraper for student info in BITS Pilani, Goa Campus

## Requirements
1. Python 2.7 and above.
2. Selenium
3. Pandas
4. tqdm
5. logging

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
