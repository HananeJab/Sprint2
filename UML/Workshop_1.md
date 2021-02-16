# Step 1 : Conception d'un système de suivi des projets Youcode

## Objectifs :
* Élaborer les diagrammes des cas d’utilisation.
* Élaborer les digrammes de séquence.
* Élaborer le digramme de classe.

## Énoncé :  
Il s'agit de concevoir une application permettant de gérer les projets au sein de l'école Youcode.

Les utilisateurs de l'application (Apprenants, Responsable, Formateur, CME, Secrétaires, …) auront la possibilité de consulter et mettre à jour les informations aux quelles ils auront accès. Ces informations peuvent concerner un projet en cours ou clôturé. 

Un projet possède les informations suivantes: un code, un nom, une description, l'organisme client(s'il s'agit d'un projet externe ), une date de début, une date de fin et un ensemble de documents techniques. Un projet est géré par un formateur.

Chaque projet appartient à un type (Brief Projet, Projet Fil Rouge, Projet de stage, Projet client), et chaque type possède un code et un libellé.

Un projet est décomposé en Sprint dont chacun possède: un code, un libellé, une description, une date de début, une date de fin, un ensemble d'apprenants chargés de la réaliser, l'état de réalisation (terminée ou non). Un Sprint possède également un ensemble de documents qui constituent les livrables.

Un livrable est caractérisé par: un code, un libellé, une description et le chemin vers un document sur disque. 

Chaque utilisateur possède: un matricule, un nom et prénom, un numéro de téléphone, un email, un login et un mot de passe. Les utilisateurs sont classés par profil (Apprenants, Responsable, Secrétaire, Formateur, CME, …).

 Un organisme client est caractérisé par: un code, un nom, une adresse, un numéro de téléphone, le nom du contact, un email du contact et une adresse web.

Cette application doit permettre :

 1. A l'administrateur de:
    * Ajouter, modifier et supprimer des utilisateurs (secrétaires, formateurs, apprenants, CME …).
    * Ajouter et modifier un projet.
    `N.B: les données saisies ou modifiées sont le nom du projet, la description, l'organisme client, la date de début et la date de fin.`
    * Ajouter et modifier les organismes.
    * Faire des recherches de projets et avoir les informations qu'elle peut modifier

 2. Au Responsable de:
    * Modifier toutes les informations d'un projet.
    * Faire des recherches de projets et avoir toutes les informations.

 3. Au Formateur de:
    * Ajouter et modifier les projets qu'il dirige en les décomposant en sprint et en indiquant pour chaque sprint: le libellé, la description, la date de début, la date de fin, les apprenants qui vont la réaliser.
    * Modifier un sprint en indiquant les livrables ou son état de clôture.

4. Au CME de : 
    * Ajouter et modifier un projet.
    * Ajouter et modifier les organismes.
    * Faire des recherches de projets et avoir les informations qu'elle peut modifier

## T.A.F :
* Élaborer les diagrammes des cas d’utilisation.
* Élaborer les digrammes de séquence boite noire et boite blanche.
* Élaborer le digramme de classe.
