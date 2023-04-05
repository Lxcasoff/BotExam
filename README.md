
# README

## Titre

Quiz en ligne automatisé avec réponse aléatoire

## Description

Ce script Python utilise Selenium pour automatiser la connexion et la navigation sur un site de quiz en ligne. Il répond de manière aléatoire aux questions du quiz, puis passe à la question suivante jusqu'à ce que le processus soit interrompu manuellement. Il est spécifiquement conçu pour le site Global Exam.

## Dépendances

- Python 3
- Selenium
- ChromeDriver (assurez-vous que ChromeDriver est compatible avec votre version de Chrome)

## Installation


```shell
sudo su
sudo apt update
sudo apt install fish
sudo apt install snap
snap install chromium
sudo apt install python3
sudo apt install git
snap install code --classic
git clone https://github.com/Lxcasoff/BotExam.git
cd BotExam/
sudo apt install pip
pip install selenium
sudo apt-get install chromium-chromedriver
echo 'export PATH=$PATH:/usr/lib/chromium-browser/' >> ~/.bashrc
```
## Configuration

Remplacez les variables `USERNAME` et `PASSWORD` par votre nom d'utilisateur et mot de passe pour le site de quiz en ligne.

```python
USERNAME = ''
PASSWORD = ''
```
