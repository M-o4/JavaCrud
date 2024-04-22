# Gestion des Notes Étudiantes

## Description
Ce projet est une application Java pour la gestion des notes des étudiants dans une institution éducative. L'application permet aux administrateurs de gérer les notes, calculer les moyennes, et effectuer des recherches rapides sur les performances des étudiants à travers différentes matières.

### Fonctionnalités
- **CRUD sur Étudiants et Matières**: Ajouter, modifier, supprimer et afficher des étudiants et des matières.
- **Gestion des Notes**: Enregistrement des notes des contrôles, des travaux pratiques et des examens.
- **Calcul de Moyennes**: Calcul des moyennes pour chaque étudiant dans une matière donnée.
- **Recherche Rapide**: Accès rapide aux notes d'un étudiant ou d'un groupe d'étudiants.

## Prérequis
- Java SE Development Kit (JDK 8 ou plus)
- MySQL Server (Version 5.7 ou plus)
- IDE supportant Java (Eclipse recommandé)
- JDBC Driver pour MySQL

## Installation

### Base de Données
1. Créez une base de données MySQL nommée `javacrud`.
2. Importez le fichier `bddgesnote.sql` fourni dans le dossier du projet pour configurer la structure de la base de données.

### Configuration de l'Application
1. Clonez le dépôt ou téléchargez le fichier ZIP du projet.
2. Ouvrez le projet dans Eclipse ou un autre IDE Java.
3. Assurez-vous que le driver JDBC pour MySQL est ajouté au classpath du projet.
4. Configurez les paramètres de connexion à la base de données dans le fichier `ConnexionMySql.java` (si nécessaire).

## Utilisation
Pour lancer l'application, exécutez le fichier `Main.java` qui se trouve dans le dossier `src`.
Utilisez les interfaces graphiques pour naviguer dans l'application et gérer les données des étudiants et leurs notes.

## Interfaces Graphiques
- **Gestion des Étudiants et des Matières**: Interface permettant d'ajouter, de modifier, de supprimer et de visualiser les étudiants et les matières.
- **Accès aux Requêtes**: Interface à partir de laquelle différentes requêtes peuvent être exécutées pour afficher des listes d'étudiants, de matières, et de notes.
- **Affichage des Notes et des Moyennes**: Interfaces spécifiques pour visualiser les notes des étudiants dans diverses matières et calculer leurs moyennes.

## Contribution
Les contributions à ce projet sont bienvenues. Veuillez suivre les pratiques standard pour contribuer à ce projet, notamment la mise à jour de ce README si vous introduisez des changements significatifs.

## Support
Pour obtenir de l'aide ou rapporter des problèmes, veuillez envoyer un email à celikmucahit04@gmail.com.

## Auteur Read Me
- Chris Nassi
- Mbarakou Maiga

## Licence
Ce projet est sous licence XYZ. Voir le fichier `LICENSE` pour plus de détails.

## Remerciements
Merci à tous ceux qui ont contribué à ce projet, en particulier les développeurs et concepteurs des interfaces utilisateur.
