# GenderShield

> Un agent conversationnel en ligne pour la lutte contre les violences conjugales et les violences discursives liées au genre

## Présentation du projet

**GenderShield** est un projet open source combinant les techniques de Traitement Automatique des Langues (TAL / NLP) et une perspective de recherche en sociolinguistique, ayant pour objectif de développer un agent conversationnel intelligent en ligne capable d'offrir un soutien et une orientation aux victimes de violences conjugales et de violences discursives liées au genre.

L'idée fondatrice de ce projet est la suivante : en tant qu'étudiante poursuivant simultanément un Master en Langue et Informatique (spécialité TAL) à Sorbonne Université, ainsi qu'un Master en Sciences du langage, parcours Sociolinguistique et Analyse du Discours à l'Université Paris Cité, je souhaite, à travers ce projet, véritablement combiner les connaissances et compétences issues de ces deux domaines d'études.

## Contexte du projet

- Les violences liées au genre, notamment les violences discursives en ligne (discours misogynes, slut-shaming, discours entourant le viol conjugal, etc.), constituent un problème social grave et transversal, tant sur le plan linguistique que culturel ;
- Les ressources existantes d'accompagnement psychologique et juridique présentent souvent des limites : un seuil d'accès élevé, une réactivité insuffisante, ainsi qu'un manque de garanties en matière d'anonymat ;
- Les technologies d'agents conversationnels offrent un potentiel intéressant pour proposer un canal de soutien accessible **24h/24 et 7j/7**, à faible seuil d'entrée et respectueux de l'anonymat des utilisateurs ;
- Ce projet ne vise en aucun cas à se substituer à un accompagnement psychologique ou juridique professionnel, mais souhaite constituer un **canal complémentaire d'orientation informative et de premier soutien émotionnel**.

## Objectifs du projet

1. Constituer un corpus conversationnel adapté au contexte de la lutte contre les violences conjugales et les violences liées au genre ;
2. Développer un prototype d'agent conversationnel doté de capacités de base en reconnaissance d'intentions, en analyse des émotions et en recommandation de ressources ;
3. Explorer l'application des méthodes d'analyse du discours issues de la sociolinguistique à la conception de systèmes conversationnels, afin que les réponses de l'agent soient davantage adaptées au contexte social réel ainsi qu'à l'état psychologique des victimes ;
4. Documenter et réfléchir sur les enjeux éthiques soulevés par le développement technologique (protection des données, risque de victimisation secondaire, biais algorithmiques, etc.).

## Stack technique (à titre indicatif)

- **Traitement du langage** : Python, spaCy / Hugging Face Transformers
- **Framework de dialogue** : à déterminer (Rasa / moteur de règles développé en interne combiné à une API de modèle de langage)
- **Traitement des corpus** : Pandas, expressions régulières, outils d'annotation à définir
- **Interface front-end** (le cas échéant) : à déterminer

## Structure du projet (planification initiale)

```
GenderShield/
├── corpus/              # Collecte et prétraitement des corpus
├── agent/                # Logique centrale de l'agent conversationnel
├── docs/                 # Documentation du projet, charte éthique, bibliographie
├── notebooks/            # Notebooks d'expérimentation et d'analyse
└── README.md
```

## État d'avancement du projet

🚧 **Phase de développement initiale** — La collecte et l'organisation des corpus sont actuellement en cours.
