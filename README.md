# WebScrape


## How to Run
1. Install Scrapy dependencies.
```sh
$ pipenv install --python 3.7 install
```

2. Run the sample spider.
```sh
$ pipenv shell
$ scrapy runspider crawl.py -a seeds_pathname=example.json -a output_pathname=./example -a depth=3
```
