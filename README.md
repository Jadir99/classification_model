
#  CamemBERT Text Classification - Inference Pipeline

Ce projet utilise un modèle **CamemBERT** fine-tuné pour effectuer de la classification automatique de textes à partir d’un fichier CSV.

##  Structure du projet

```
project-root/
├── saved_model/              # Modèle CamemBERT entraîné
├── data/
│   └── froid_new.csv         # Données CSV avec les textes à prédire
├── Camembert_model.ipynb              # Script d’inférence
├── requirements.txt          # Dépendances du projet
└── README.md                 # Ce fichier
```

##  Prérequis

- Python 3.8 ou +
- pip
- (optionnel) Environnement virtuel Python

##  Installation

### 1. Cloner le projet

```bash
git clone https://github.com/Jadir99/classification_model.git
cd classification_model
```

### 2. Créer un environnement virtuel (optionnel)

```bash
python -m venv venv
source venv/bin/activate       # Linux/macOS
venv\Scripts\activate        # Windows
```

### 3. Installer les dépendances

```bash
pip install -r requirements.txt
```

##  Lancer l’inférence

Assurez-vous que le modèle entraîné se trouve dans `./saved_model/` et les données dans `./data/`.

```bash
run file Camembert_model.ipynb
```


##  Exemple de données (CSV)

Le fichier `froid_new.csv` doit contenir au minimum :

| TEXTE_AUTRE             | CLASSE    |
|--------------------------|-----------|
| "Texte à classer ici"    | "ClasseA" |

##  Auteur

Projet réalisé par **JADIR Mohammed** – Feel free to contribute or fork.
