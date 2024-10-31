
# Jax-RS/Jersey Webservices

Ce projet consiste en une application Java construite avec Spring Boot, qui met en œuvre des services web RESTful. L'API permet de gérer des comptes (`Compte`) et fournit des données en formats XML et JSON s'adaptant aux préférences du client.
## Video 
[Watch the video](https://drive.google.com/file/d/1ag614PF4GgGSrv2mQRKIMJOTqWMrz7xD/view?usp=sharing).
## Structure du Projet

Ci-dessous l'Architecture du Projet

```
├── src
│   ├── main
│   │   ├── java
│   │   │   └── ma
│   │   │       └── emsi
│   │   │           └── tp_jax_rs
│   │   │               ├── config
│   │   │               │   └── Myconfig.java
│   │   │               ├── webservice
│   │   │               │   └── CompteRestJaxRSAPI.java
│   │   │               ├── entities
│   │   │               │   └── Compte.java
│   │   │               │   └── TypeCompte.java
│   │   │               └── repositories
│   │   │                   └── CompteRepo.java
│   │   └── resources
│   │       ├── application.properties
│   │       ├── static
│   │       └── templates
