# 🌍 Classification du Risque Pays au Maghreb

Ce projet utilise le **Machine Learning** (Arbres de Décision) pour classifier le niveau de risque financier et politique des pays de la région Maghreb. Il s'appuie sur des indicateurs macroéconomiques et institutionnels inspirés de la **Banque Mondiale**, de l'**OCDE** et des rapports **Doing Business**.

## 📌 Objectifs du Projet
L'objectif est de fournir un outil d'analyse interprétable pour détecter les risques systémiques. Le modèle classifie chaque pays selon 4 niveaux :
* 🟢 **Faible**
* 🟡 **Modéré**
* 🟠 **Élevé**
* 🔴 **Très Élevé**

## 📊 Indicateurs Utilisés (Features)
Le modèle se base sur des critères essentiels de stabilité :
1.  **PIB_Croissance** : Santé économique globale.
2.  **Inflation** : Stabilité de la monnaie.
3.  **Dette_PIB** : Capacité d'endettement souverain.
4.  **Stabilite_Politique** : Indice de gouvernance (WB).
5.  **Score_Doing_Business** : Facilité d'investissement et climat des affaires.
6.  **Balance_Courante** : Équilibre des échanges extérieurs.

## 🛠️ Technologies Utilisées
* **Python 3.x**
* **Pandas & Numpy** : Manipulation des données.
* **Scikit-Learn** : Modélisation par Arbre de Décision.
* **Matplotlib & Seaborn** : Visualisation des résultats et de l'arbre.

## 🚀 Installation et Utilisation

1.  **Cloner le dépôt :**
    ```bash
    git clone [https://github.com/votre-utilisateur/risque-pays-maghreb.git](https://github.com/votre-utilisateur/risque-pays-maghreb.git)
    cd risque-pays-maghreb
    ```

2.  **Installer les dépendances :**
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn
    ```

3.  **Lancer l'analyse :**
    Exécutez le script principal pour générer le dataset, entraîner le modèle et afficher l'arbre de décision :
    ```bash
    python main.py
    ```

## 📈 Résultats et Interprétabilité
Ce projet privilégie les **arbres de décision** car ils offrent une transparence totale sur les règles de gestion du risque. Contrairement aux modèles complexes, un analyste peut justifier un score en suivant les branches de l'arbre (ex: Si Dette > 80% ALORS Risque Élevé).

---
*Projet réalisé dans le cadre d'une étude sur la Détection de Fraude & Risque Institutionnel.*
