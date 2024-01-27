### Travail à faire ###

Vidéo à utiliser comme ressource principale : https://www.youtube.com/watch?v=KKw2u_5nW7k
1. Installer IntelliJ Ultimate.
2. Créer un projet Spring Initializer avec les dépendances JPA, H2, Spring Web et Lombok.
3. Créer l'entité JPA Patient ayant les attributs :
       - id de type Long,
       - nom de type String,
       - dateNaissanec de type Date,
       - malade de type boolean,
       - score de type int.
4. Configurer l'unité de persistance dans le ficher application.properties.
5. Créer l'interface JPA Repository basée sur Spring data.
6. Tester quelques opérations de gestion de patients :
    - Ajouter des patients
    - Consulter tous les patients
    - Consulter un patient
    - Chercher des patients
    - Mettre à jour un patient 
    - supprimer un patient
7. Migrer de H2 Database vers MySQL

### Présentation du Spring Boot ###  
Spring Boot est un framework open source pour le développement d'applications Java. Il fournit un cadre prêt à l'emploi pour créer des applications et des services Web en utilisant la configuration plutôt qu'une approche programmatique. 
Spring Boot aide à créer des applications qui ne sont pas liées à une plate-forme spécifique et qui peuvent s'exécuter localement sur un appareil sans connexion Internet ou autres services installés pour être fonctionnelles.


### La configuration du projet ### 
- SDK : 1.8 Oracle OpenJDK version 18.0.2
- Java : 17
- Type : Maven 
=> Un projet Maven est un projet logiciel qui utilise l'outil de gestion de projet Maven pour automatiser la construction, la documentation et les dépendances du projet. Maven fournit un ensemble de conventions de configuration standard pour les projets Java, ainsi qu'une structure de projet organisée en modules.
- Packaging : Jar 
=>Les fichiers JAR nous permettent de regrouper plusieurs fichiers afin de les utiliser comme bibliothèque, plug-in ou tout type d'application.
Lorsqu'un projet Maven est construit avec un package de "jar", Maven compilera le code source Java, regroupera les classes compilées et les ressources associées dans un fichier Jar, et installera ou déploiera le fichier Jar résultant dans un référentiel local ou distant pour consommation.

### Les dépendances utilisées ### 
- Lombok : Un outil de bibliothèque Java qui génère du code pour minimiser le code ‘boilerplate’. La bibliothèque remplace le code ‘boilerplate’ par des annotations faciles à utiliser (Exemples : @NoArgsConstructor, @Getter, @Setter…).
- Spring Web : pour créer des applications Web, y compris RESTful, à l'aide de Spring MVC. Utilise Apache Tomcat comme conteneur intégré par défaut.
- Spring DATA JPA : Pour conserver les données dans ‘SQL stores‘ avec Java Persistance API à l’aide de Spring Data et Hibernate. C'est un module qui facilite le ORM basé sur JPA. Il est utilisé avec les bases de données relationnelles.
- H2 Database : Une base de données intégrée, open source et en mémoire. C'est un système de gestion de base de données relationnelle écrit en Java. C'est une application client/serveur et elle est généralement utilisée dans les tests unitaires.
- MySQL : MySQL est l'un des systèmes de bases de données relationnelles les plus populaires et il est souvent utilisé dans les applications Spring Boot.

### OUTPUT ### 
## Screen 1

<img width="425" alt="i11" src="https://github.com/ACHRAFHED/TP2JEE/assets/102471232/4cfbb12c-850f-40b0-b2e7-063b12b81444">

## Screen 2

<img width="363" alt="i1" src="https://github.com/ACHRAFHED/TP2JEE/assets/102471232/6e95860a-f77b-4e8c-8ffa-d6f37703b048">

## Screen 3

<img width="547" alt="i2" src="https://github.com/ACHRAFHED/TP2JEE/assets/102471232/6c6ed53d-f06d-4c64-874c-e77c7641f10d">

## Screen 4

<img width="609" alt="i3" src="https://github.com/ACHRAFHED/TP2JEE/assets/102471232/49918bcd-3650-44c7-8be7-2fb0af0b7c72"> 





