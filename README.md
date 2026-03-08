# Suivi-commerce
Utilitaire suivi CA petite entreprise 
# Suivi Commerce – Tableau de gestion mensuelle

Petit utilitaire HTML permettant de suivre simplement l’activité d’un commerce :

- Chiffre d’affaires journalier
- Nombre de clients
- Panier moyen
- Achats fournisseurs
- Charges
- Résultat mensuel
- Historique mensuel
- Export / sauvegarde JSON

Ce projet est volontairement **simple, autonome et sans serveur**.  
Il fonctionne directement dans un navigateur internet.

---

# Fonctionnalités

### Suivi du chiffre d'affaires

- saisie du CA par jour
- total semaine
- total mois

### Suivi clients

- nombre de clients par jour
- total clients mois

### Panier moyen automatique

Panier moyen calculé automatiquement :

Panier moyen = CA total / Nombre total de clients

### Gestion des achats

- saisie des factures fournisseurs
- regroupement automatique par fournisseur

### Gestion des charges

- loyer
- énergie
- divers

### Résultat mensuel

Le tableau calcule :

Résultat = CA - Achats - Charges

### Historique

Les mois clôturés sont conservés pour analyse.

---

# Sauvegarde des données

Les données sont stockées dans le navigateur.

Possibilité de sauvegarder avec :

Export JSON

et restaurer avec :

Restaurer JSON

---

# Utilisation

1. Ouvrir le fichier HTML dans un navigateur.
2. Choisir l’année et le mois.
3. Saisir les données au fil des jours.
4. Clôturer le mois une fois terminé.

---

# Objectif du projet

Créer un outil **simple et rapide pour un commerçant** afin de suivre :

- activité
- rentabilité
- évolution du panier moyen
- évolution de la fréquentation

---

# Technologies

- HTML
- CSS
- JavaScript

Aucune base de données ni serveur nécessaires.

---

# Licence

Projet libre d’utilisation.
