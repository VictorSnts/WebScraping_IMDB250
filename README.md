# WebScraping_IMDB250

![GitHub repo size](https://img.shields.io/github/repo-size/VictorSnts/WebScraping_IMDB250?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/VictorSnts/WebScraping_IMDB250?style=for-the-badge)

> Projeto desenvolvido no promeiro contato com WebScraping. Este projeto gera um arquivo com os Top 250 filmes do IMDB.

## 💻 Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:
<!---Estes são apenas requisitos de exemplo. Adicionar, duplicar ou remover conforme necessário--->
* Você instalou a versão mais recente do `Python`
* Você instalou a versão mais recente da biblioteca `Scrapy`

## 🚀 Usando WebScraping_IMDB250

Para instalar o WebScraping_IMDB250, siga estas etapas:

```
git clone https://github.com/VictorSnts/WebScraping_IMDB250.git
cd WebScraping_IMDB250/filmes_imdb/imdb_project
```

Para usar o WebScraping_IMDB250, siga estas etapas:
* Gerando um CSV com os Top 250 filmes do IMDB.
    ```
    scrapy crawl imdb -O imdb.csv 
    ```
* Gerando um JSON com os Top 250 filmes do IMDB.
    ```
    scrapy crawl imdb -O imdb.json 
    ```
