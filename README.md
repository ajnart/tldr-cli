*Ce workshop à pour but de vous faire découvrir OpenAi et son API publique, en créant un CLI pour résumer du texte.*

# Déroulement du workshop
- [Introduction](#Introduction)
- [Introduction à l'api](#API)
- [Création d'un cli](#Cli)

# Introduction
## OpenAI
![](https://upload.wikimedia.org/wikipedia/fr/thumb/2/2d/OpenAI_Logo_2017.svg/1200px-OpenAI_Logo_2017.svg.png)

OpenAI est une entreprise en intelligence artificielle, basée à San Francisco. Son but est de promouvoir et développer une intelligence artificielle à visage humain qui bénéficiera à toute l'humanité. *(Wikipedia)*

## GPT-3

GPT-3 est une intelligence artificielle de génération de langage créée par OpenAI. Il s’agit à ce jour du réseau de neurones artificiels le plus complexe du monde, et de l’IA linguistique et textuelle la plus avancée. 

Ce modèle a 175 milliards de paramètres, à savoir les valeurs qu’un réseau de neurones essaye d’optimiser pendant l’entraînement. En comparaison, son prédécesseur GPT-2 en avait déjà 1,5 milliard.

*(GTP-4 cible les 100 Billards de paramètres, 500x plus que GPT-3)*

## L'API openAI

Lors du lancement de GPT-2, OpenIA craignait que son outil soit trop dangereux pour être relâché dans la nature. La firme basée à San Francisco craignait qu’il soit utilisé pour produire des  "Fake News" en masse. Elle avait donc choisi dans un premier temps de ne proposer qu’une version limitée au téléchargement.

Faisant preuve de la même prudence pour GPT-3, OpenAI a préféré proposer cette nouvelle version sous forme d’endpoint API basée sur le Cloud. L’outil est donc délivré sous la forme d’un service Cloud pour éviter son usage par des acteurs mal intentionnés et à des fins lucratives. Ainsi, l’entreprise garde un contrôle sur sa créature.

# API

Tout d’abord, nous allons voir comment l’API fonctionne.
Pour faire des requêtes, il faut utiliser une clé d’API. Pour obtenir une clé d’API, inscrivez vous sur [OpenAI](https://beta.openai.com/signup).
Vous trouverez une clé d’API dans votre [compte](https://beta.openai.com/account/api-keys).
