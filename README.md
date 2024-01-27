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
<img width="319" alt="Screenshot 2024-01-27 130112" src="https://github.com/aymanehed/PatientsApplication/assets/93987581/947159fb-a168-4071-bbee-9593407cf0b9">


## Screen 2
<img width="269" alt="Screenshot 2024-01-27 130123" src="https://github.com/aymanehed/PatientsApplication/assets/93987581/2f4e789e-032c-4f5d-b5b8-04bf968b07c8">


## Screen 3
<img width="411" alt="Screenshot 2024-01-27 130132" src="https://github.com/aymanehed/PatientsApplication/assets/93987581/c20555bc-78ca-45f4-9fc5-a9920ea25f01">

## Screen 4

<img width="454" alt="Screenshot 2024-01-27 130147" src="https://github.com/aymanehed/PatientsApplication/assets/93987581/9f245a55-ee16-4eef-bc67-063d8e7c6b10">






