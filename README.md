# Gestion de la Facturation

## Description
Ce projet Excel est une application de gestion de facturation complète développée avec des fonctionnalités automatisées via des macros (VBA). Il permet de gérer l'ensemble du cycle de facturation, depuis la création des devis jusqu'à la gestion des factures, en passant par le suivi des commandes et des livraisons.

## Fonctionnalités
- **Dashboard** : Vue d'ensemble des données clés, incluant les performances et les indicateurs.
- **Devis** : Création et gestion des devis clients.
- **Commande** : Suivi des commandes passées par les clients.
- **Livraison** : Gestion des livraisons associées aux commandes.
- **Facture** : Création et génération de factures personnalisées.
- **Liste Factures** : Suivi des factures générées et archivage.
- **Parameters** : Configuration des informations de l'entreprise (nom, adresse, coordonnées), des produits, des clients et du chemin d'enregistrement des fichiers PDF.

## Fonctionnement
### Données nécessaires
Pour les feuilles **Devis**, **Commande**, **Livraison** et **Facture**, les informations suivantes sont requises : 
1. **Désignation des produits** : Sélection dans une liste déroulante issue de la feuille **Parameters**.
2. **Nom du client** : Sélection dans une liste déroulante issue de la feuille **Parameters**.
3. **Quantité voulue** : Saisie manuelle.

### Gestion des produits et clients
- Les nouveaux produits et clients doivent être ajoutés dans les tableaux correspondants dans la feuille **Parameters** pour qu'ils apparaissent dans les listes déroulantes des autres feuilles.

### Sauvegarde des fichiers PDF
- Dans la feuille **Parameters**, indiquez le chemin de sauvegarde des fichiers PDF pour :
  - **Devis**
  - **Bon de commande**
  - **Bon de livraison**
  - **Facturation**
- Si le chemin n'est pas défini, cliquer sur "Imprimer" ou "Enregistrer" dans les feuilles **Devis**, **Commande**, **Livraison** ou **Facture** générera une erreur.

## Prérequis
- Microsoft Excel (version prenant en charge les macros, comme Excel 2016 ou plus récent).
- Activer les macros à l'ouverture pour un fonctionnement optimal.

## Installation
1. Téléchargez le fichier Excel : **Gestion de la facturation.xlsm**
2. Ouvrez le fichier dans Excel.
3. Activez les macros lorsque demandé.

## Utilisation
1. **Paramétrage initial** :
   - Configurez les informations de l'entreprise, les produits, les clients, et le chemin de sauvegarde des fichiers PDF dans la feuille **Parameters**.
2. **Création de devis** :
   - Allez dans la feuille **Devis** pour créer un devis en remplissant les champs nécessaires.
3. **Suivi des commandes** :
   - Enregistrez les commandes dans la feuille **Commande**.
4. **Gestion des livraisons** :
   - Suivez les livraisons dans la feuille **Livraison**.
5. **Facturation** :
   - Générer des factures à partir de la feuille **Facture**.
6. **Consulter l'historique** :
   - Visualisez les factures dans la feuille **Liste Factures**.
7. **Suivi global** :
   - Consultez le **Dashboard** pour un aperçu rapide.

## Avertissements
- **Sauvegarde** : Sauvegardez régulièrement vos données pour éviter les pertes dues à des erreurs ou à des interruptions.
- **Macros** : Les macros doivent être activées pour garantir un fonctionnement complet.

## Captures d'écran
![Dashboard](https://github.com/user-attachments/assets/d9360840-a999-4632-a040-66b170e05032)

![Devis](https://github.com/user-attachments/assets/b929fd63-b99f-4a8a-83e6-c1f7f9e9f04a)

![Commande](https://github.com/user-attachments/assets/3ee2a23c-22b7-47e3-b191-15bf9d460452)

![Livraison](https://github.com/user-attachments/assets/d908464b-67f3-431c-91c1-3a465869249b)

![Facture](https://github.com/user-attachments/assets/2f759d21-9b5e-4f99-8d40-787ade498f10)

![ListeFactures](https://github.com/user-attachments/assets/cf3cdf05-6362-4e8e-8679-2a1ffa82b200)

![Paramètres](https://github.com/user-attachments/assets/0e425e5b-72ac-41f9-b9c8-b0bdaac742d1)

## Auteur
MOULOLO Eden (Codeur16G)
Moulololeden@gmail.com
