<p align="center">
    <img src="https://telegra.ph/file/842aae2019983b9b6347e.png" width="100%" style="margin-left: auto;margin-right: auto;display: block;">
</p>
<h1 align="center">Rev - Anjay</h1>

# Python Web Scraping
Web Scraping adalah salah satu Teknik yang digunakan untuk mengambil data dari sebuah situs website. Data yang diambil adalah data yang tidak terstruktur dalam format HTML yang kemudian diubah menjadi data terstruktur dalam spreadsheet atau database sehingga dapat digunakan dalam berbagai aplikasi.

## Instalasi Via Google Colab
----------
<img 
src="https://telegra.ph/file/60bcda32c516cbcda3979.gif" width="100%" style="margin-left: auto;margin-right: auto;display: block;">

----------
- **[1]**
```bash
import pandas as pd
```
- **[2]**
```bash
web = 'link website'
```
- **[3]**
```bash
df = pd.read_html(web)
```
- **[4]**
```bash
!pip install selenium bs4
```
- **[5]**
```bash
!apt-get update
```
- **[6]**
```bash
from selenium import webdriver
from bs4 import BeautifulSoup
import pandas as pd
```
- **[7]**
```bash
options = webdriver.ChromeOptions()
options.add_argument('--headless')
options.add_argument('--no-sandbox')
options.add_argument('--disable-dev-shm-usage')
```
- **[8]**
```bash
site = 'link website'
```
- **[9]**
```bash
wd = webdriver.Chrome(options=options)
```
- **[10]**
```bash
html = wd.page_source
```
- **[11]**
```bash
df[0].to_csv ('Nama File.csv')
```

- Note: Hanya bisa untuk Website Wikipedia
----------

[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://python.org/)

[![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

[![Wikipedia](https://img.shields.io/badge/Wikipedia-%23000000.svg?style=for-the-badge&logo=wikipedia&logoColor=white)](https://wikipedia.org/)
