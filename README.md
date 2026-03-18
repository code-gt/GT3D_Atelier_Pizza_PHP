# GT3D_Atelier_Pizza_PHP
Traitement d'une commande de pizza avec POST

# 🍕 Exercice PHP – Commande de pizza

## 🎯 Objectif

Créer une page web en **PHP** permettant :
- d’afficher un **menu de pizzas**
- de créer un **formulaire de commande**
- de traiter les données envoyées en **POST**
- d’afficher un **récapitulatif avec le prix total**

---

## 🧩 Étape 1 – Affichage du menu

Avant le formulaire, afficher :

### 🍕 Les pizzas
- Margherita : 8€
- Reine : 10€
- 4 Fromages : 11€
- Végétarienne : 9€

### 📏 Les tailles
- Petite : prix normal
- Grande : +50% (coefficient x1.5)

### ➕ Supplément (1 seul)
- Fromage : +1€
- Champignons : +1€
- Jambon : +2€

---

## 🧾 Étape 2 – Création du formulaire

Créer un formulaire avec la méthode **POST** contenant :

### 👤 Informations client
- Nom (input texte)
- Prénom (input texte)
- Email (input email)
- Adresse (textarea)

### 🍕 Commande
- Choix de la pizza (liste déroulante `<select>`)
- Taille (boutons radio : petite / grande)
- Supplément (liste déroulante `<select>`)
- Quantité (input number)

---

## ⚙️ Étape 3 – Traitement en PHP

Dans le même fichier :

### 🔹 Vérifier l’envoi du formulaire
Utiliser :
```php
$_SERVER["REQUEST_METHOD"] === "POST"
```

🔹 Récupérer les données

🔹 Créer les tableaux de prix

🔹 Calculer le total


## 🧮 Étape 4 – Affichage du résultat

Afficher après le formulaire les informations client, le détail de la commande et le prix total.


## 🚀 Bonus (facultatif)

Sécuriser les données avec htmlspecialchars()

Formater le prix avec number_format()

Ajouter du style (CSS ou Bootstrap)
