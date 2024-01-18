# Scrapy example project

Examples, tutorials and experiments

## Installation

- Init virtual env `python -m venv venv`
- Activate virtual env `source venv/bin/activate`
- Install deps `pip install -r requirements.txt`

## Basic usage

View the project spiders: `scrapy list`

Run the project spider: `scrapy crawl <spider_name>`

Running command with `-O` will save and overwrite the data `scrapy crawl <spider_name> -O <filename>.<josn|csv>`. Lowercase `-o` will append to exsiting file.
Usage of `-o` is not necessary to persist output if `FEEDS` key is defined in spider's `settings.py`

## Refs

[Scrapy Official website](https://scrapy.org/) | [Scrapy Docs](https://docs.scrapy.org/en/latest/)

[Python Scrapy Playbook](https://scrapeops.io/python-scrapy-playbook/)

[Python Scrapy Beginners Course](https://thepythonscrapyplaybook.com/freecodecamp-beginner-course/) and its correspondent video [Scrapy Course – Python Web Scraping for Beginners (YT)](www.youtube.com/watch?v=mBoX_JCKZTE)

### Proxies

[Free proxies](https://geonode.com/free-proxy-list) | [Smartproxy](https://smartproxy.com/)
