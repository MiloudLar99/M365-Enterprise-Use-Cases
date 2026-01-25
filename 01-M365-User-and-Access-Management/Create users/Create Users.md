# Lab – Création et gestion des utilisateurs dans Microsoft Entra ID

## Objectif du lab

Ce lab a pour objectif de démontrer la création et la gestion d’utilisateurs internes dans Microsoft Entra ID (anciennement Azure Active Directory).
Il couvre les étapes essentielles réalisées dans un environnement professionnel : création d’un compte utilisateur, configuration des informations de base, validation et vérification de l’utilisateur dans le tenant.
Ce type d’opération fait partie des tâches quotidiennes d’un support IT / administrateur Microsoft 365.

## Environnement
- Microsoft Entra ID
- Tenant : LabsM365.onmicrosoft.com
- Rôle utilisé : Administrateur
- Utilisateur créé : John Doe

  ## Étape 1 – Accéder à la gestion des utilisateurs
- Depuis le Centre d’administration Microsoft Entra :

1. Ouvrir Microsoft Entra
2. Aller dans Utilisateurs
3. Cliquer sur Nouvel(le) utilisateur(-trice)
4. Sélectionner Créer un utilisateur

![](/screenshots/Entra-Id.png)   
![](./screenshots/Create-User.png)


## Étape 2 – Renseigner les informations de base
- Dans l’onglet Informations de base, compléter les champs suivants:
1. Nom d’utilisateur principal (UPN):
john.doe@LabsM365.onmicrosoft.com
2. Nom d’affichage :
John Doe
3. Pseudonyme de messagerie :
Dérivé automatiquement du nom d’utilisateur
4. Mot de passe :
Pa55w0r.d.
5. Compte activé :
Activé

![](./screenshots/Account-User.png)

## Étape 3 – Configurer les propriétés de l’utilisateur
- Dans l’onglet Propriétés, renseigner les informations professionnelles :

1. Identité
- Prénom : John
- Nom : Doe
- Type d’utilisateur : Membre
2. Informations de travail
- Poste : Administrative Assistant
- Département : Administration
- Lieu d’utilisation : États-Unis
Ces informations facilitent la gestion des utilisateurs et peuvent être utilisées pour des règles de sécurité ou d’attribution.

![](./screenshots/Info-User.png)
![](./screenshots/Liu-d'utilisation.png)

## Étape 4 – Vérifier et créer l’utilisateur
1. Accéder à l’onglet Vérifier + créer
2. Vérifier l’exactitude des informations saisies
3. Cliquer sur Créer
   
![](./screenshots/Description-User-Fin.png)

## Étape 5 – Vérification dans la liste des utilisateurs

Après la création :
1. Revenir dans Utilisateurs
2. Vérifier la présence de John Doe dans la liste
3. Confirmer :
- Type d’utilisateur : Membre
- Domaine : LabsM365.onmicrosoft.com
- Compte actif
  
![](./screenshots/User-Created.png)

## Résultat final

- L’utilisateur John Doe a été créé avec succès dans Microsoft Entra ID
- Le compte est actif et prêt à être utilisé
- Les informations professionnelles sont correctement renseignées
- L’utilisateur peut être ensuite :
- affecté à des groupes
- assigné à des licences
- ciblé par des stratégies Intune ou de sécurité

# Attribution de licences Microsoft 365 aux utilisateurs

## Objectif de cette étape

Après la création de l’utilisateur, cette étape consiste à lui attribuer une licence Microsoft 365 afin de finaliser son intégration dans l’environnement Microsoft 365.

## Étape 2 – Lancer l’attribution de licence

1. Cliquer sur Affecter des licences
2. Une fenêtre latérale s’ouvre pour sélectionner les utilisateurs
   
![](./screenshots/Add-License.png)

## Étape 3 – Sélectionner l’utilisateur
Dans la fenêtre Attribuer des licences aux utilisateurs :
1. Rechercher l’utilisateur John Doe
2. Sélectionner l’utilisateur
3. Vérifier que la licence Office 365 E5 EEE (sans Teams) est bien sélectionnée
4. Laisser les applications et services par défaut
5. Cliquer sur Attribuer des licences
6. Attendre la confirmation de l’opération

![](./screenshots/Add-License2.png)


## Étape 5 – Vérification de l’attribution
Une fois l’opération terminée :
- Un message de confirmation s’affiche indiquant que la licence a été attribuée à John Doe
- L’utilisateur apparaît dans la liste des utilisateurs licenciés
- Le nombre de licences utilisées est mis à jour

![](./screenshots/License-Added.png)

## Résultat final
- La licence Office 365 E5 EEE (sans Teams) a été attribuée avec succès
- L’utilisateur John Doe peut désormais accéder aux services Microsoft 365 inclus dans la licence
- Le compte est prêt pour :
  - l’accès aux applications Microsoft 365
  - l’application de politiques de sécurité
  - la gestion via Intune et Entra ID






























