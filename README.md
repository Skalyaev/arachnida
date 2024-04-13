# <p align="center">arachnida</p>
> *Projet d'introduction au web scraping et aux métadonnées.*
>
> *Dans un premier temps, vous allez créer un petit programme capable d'extraire automatiquement des images présentes sur internet. Ensuite, vous développerez un second programme pour analyser ces images et manipuler leurs métadonnées.*
>
> *Les métadonnées sont des informations dont le but est de décrire d'autres données. En résumé, ce sont des données sur des données. Elles sont fréquemment utilisées pour décrire le contenu d'images et de documents, et peuvent révéler des informations sensibles sur ceux qui les ont créés ou modifiés.*

## Install
```bash
sudo apt update -y
sudo apt install -y python3
sudo apt install -y python3-bs4
sudo apt install -y python3-tk
sudo apt install -y python3-pil
sudo apt install -y python3-pil.imagetk
sudo apt install -y python3-py3exiv2
```
```bash
link=Skalyaeve/arachnida
name=arachnida

git clone https://github.com/$link.git $name
cd $name/main
```

## Usage
```bash
./main.py
```
- Starting input with `http(s)://` will download images
- Starting input without will open the corresponding folder from `./data`

