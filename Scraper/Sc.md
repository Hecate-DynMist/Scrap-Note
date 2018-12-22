# Scraper

Virtual environment

```bash
virtualenv scrapEnv
cd scrapEnv/
source bin

pip install beautifulsoup4
python
from bs4 import BeautifulSoup

deactivite
```

BeautifulSoup

```python
from urllib.request import urlopen
from bs4 import BeautifulSoup as Soup
html=urlopen("http://pythonscraping.com/pages/page1.html")
bSo=Soup(html.read())
print(bSo.h1)
```

