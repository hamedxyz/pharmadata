# Scraping Pharmaceuticals Data

### Used:

- python, BeautifulSoup for scraping data into text, csv and json files

- curl and web inspector for testing HTTP requests

- docker image of postgres for database

<hr>

i didn't connect the scraper with the database, i used the produced csv files to generate tables.

TODO: clean the data and do that 
<hr>

### Dependencies: 
<br>

on linux:
```
python3 -m venv venv && source venv/bin/activate
pip install -r requirements.txt
```
<br>


on windows:
```
python -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt
```
and you're set
<br>

<hr>
<br>

## Scraper in Action
![Screenshot1](https://github.com/user-attachments/assets/96817377-cbb4-4dac-972e-4cb940323f24)

<hr>
<br>

## Database
![Screenshot2](https://github.com/user-attachments/assets/a8ac5cb5-ee69-4304-87a9-812bf498a1b0)
