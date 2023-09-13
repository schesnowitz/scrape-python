pip install scrapy
scraper startproject scraper

#### cd into spiders
scrapy genspider booksdetail books.toscrape.com


#### install ipython:
pip install ipython

#### inside scrapy.cfg add:
shell = 'ipython'

#### in terminal run:
scrapy shell
fetch('https://books.toscrape.com/')


If we want to save the data to a JSON file we can use the -O option, followed by the name of the file.

scrapy crawl bookspider -O myscrapeddata.json

If we want to save the data to a CSV file we can do so too.

scrapy crawl bookspider -O myscrapeddata.csv