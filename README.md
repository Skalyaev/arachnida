# Arachnida

*Introductory project to web scraping and metadata.*

This project will allow you to process data from the web.
First you will create a small program to automatically extract information from the web.
Then you will create a second program to analyze these files and manipulate the metadata.
Metadata is information which purpose is to describe other data.
It’s essentially data about data. It is frequently used to describe information contained on images and documents, and can reveal sensitive information about those who have created or manipulated them.

## Usage
```sh
sudo apt update
sudo apt install git python3 python3-pip
pip3 install pyexiv2
```
```sh
git clone git@github.com:Skalyaeve/arachnida.git
cd arachnida/bonus
chmod +x *.py
echo "http://42.fr" | ./main.py
```
