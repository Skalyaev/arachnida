# <p align="center">arachnida</p>

> _Projet d'introduction au web scraping et aux métadonnées._
>
> _Dans un premier temps, vous allez créer un petit programme capable d'extraire automatiquement des images présentes sur internet. Ensuite, vous développerez un second programme pour analyser ces images et manipuler leurs métadonnées._
>
> _Les métadonnées sont des informations dont le but est de décrire d'autres données. En résumé, ce sont des données sur des données. Elles sont fréquemment utilisées pour décrire le contenu d'images et de documents, et peuvent révéler des informations sensibles sur ceux qui les ont créés ou modifiés._

## Install

```bash
pip install requests
pip install bs4
pip install pillow
pip install pyexiv2
pip install tk
```

```bash
git clone https://github.com/Skalyaeve/arachnida.git
cd arachnida/main
```

## Usage

```bash
./main.py
```

- Starting input with `http(s)://` will download images
- Starting input without will open the corresponding folder from `./data`
