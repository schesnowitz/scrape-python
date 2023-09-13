pip install scrapy
scraper startproject scraper

#### cd into spiders
scrapy genspider nameofspider sitetoscrape.com


#### install ipython:
pip install ipython

#### inside scrapy.cfg add:
shell = 'ipython'

#### in terminal run:
scrapy shell
fetch('https://books.toscrape.com/')
