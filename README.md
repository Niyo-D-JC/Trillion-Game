# Asset-Pricing-and-Management
 
## Description
Ce projet couvre plusieurs aspects du pricing et de la gestion d'actifs :

1. **Extraction ou Simulation de Données de Marché**  
   - Courbe des taux zéro-coupon extraite du site de la **Banque de France** (dossier `data/`).
   - Données de marché pour les actions et la volatilité implicite simulées ou extraites.

2. **Pricing d'instruments de taux vanille**  
   - Calcul du prix d'une obligation à coupons.
   - Pricing d'un Swap ou d'un Future sans modèle.

3. **Implémentation et calibration d’un modèle equity (Black-Scholes)**  
   - Modèle Black-Scholes pour le pricing d'options.
   - Calibration des paramètres.

4. **Pricing d’un produit optionnel Equity avec les grecques**  
   - Pricing d’options européennes, américaines ou asiatiques.
   
5. **Optimisation de portefeuille**  
   - Construction d’un portefeuille optimal avec la théorie de Markowitz.
   - Réplication d’un indice via une gestion passive.

## Installation et Exécution
### 1. Créer un environnement virtuel (Windows)
```sh
python -m venv env
```

### 2. Activer l'environnement virtuel
```sh
env\Scripts\activate
```

### 3. Installer les dépendances
```sh
pip install -r requirements.txt
```

### 4. Lancer l'application Dash
```sh
python app.py
```

L'application Dash permet d'interagir avec les résultats du pricing et de la gestion d'actifs via une interface web.

## Structure du Projet
```
📂 Projet_Pricing
├── 📂 data               # Données de marché (courbe zéro-coupon, etc.)
├── 📂 components         # Implémentation des vues de dash
├── 📂 tools_class        # Class et méthode de calcul
├── app.py                # Application Dash
├── requirements.txt      # Dépendances du projet
├── README.md             # Instructions du projet
```


Merci ! 🚀

