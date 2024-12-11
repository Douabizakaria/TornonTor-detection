## Description

Ce projet vise à analyser et classifier le trafic réseau comme étant Tor ou non-Tor en utilisant des techniques d'apprentissage automatique. Le script effectue les étapes suivantes :

- Importation et prétraitement des données
- Analyse exploratoire des données
- Préparation des caractéristiques pour l'apprentissage automatique
- Entraînement et évaluation du modèle

## Prérequis

- Python 3.x
- Bibliothèques Python :
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - statsmodels
  - scipy

## Installation

Installez les dépendances requises avec la commande suivante :

```bash
pip install pandas numpy matplotlib seaborn statsmodels scipy
```

## Utilisation

1. Assurez-vous que le fichier de données `Scenario-A-merged_5s.csv` est dans le même répertoire que le script.
2. Exécutez le script Python :

```bash
python TorNonTor_Detection.py
```

## Structure du Projet

```
text.
├── TorNonTor_Detection.py
├── Scenario-A-merged_5s.csv
└── README.md
```

## Fonctionnalités

- Chargement et prétraitement des données de trafic réseau
- Visualisation des distributions de caractéristiques
- Analyse statistique des caractéristiques du trafic
- Classification du trafic en Tor et non-Tor

## Contribution

Les contributions à ce projet sont les bienvenues. Veuillez suivre ces étapes pour contribuer :

1. Forkez le projet
2. Créez votre branche de fonctionnalité (`git checkout -b feature/AmazingFeature`)
3. Commitez vos changements (`git commit -m 'Add some AmazingFeature'`)
4. Poussez vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrez une Pull Request

## Licence

Distribué sous la licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus d'informations.

## Contact

Douabi Zakaria zakariadouabi@gmail.com

Lien du projet : [GitHub Repository](https://github.com/Douabizakaria/TornoTor-detection)
```

