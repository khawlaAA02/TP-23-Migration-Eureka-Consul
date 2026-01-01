# TP 23 : Migration de Eureka vers Consul

## Objectif

L’objectif de ce TP est de remplacer Netflix Eureka par HashiCorp Consul pour la découverte des microservices dans une architecture Spring Boot – Spring Cloud.

À la fin du TP :

-Les microservices ne sont plus enregistrés dans Eureka

-Ils sont automatiquement enregistrés dans Consul

-Le Gateway et les services communiquent via Consul

## Architecture

| Composant      | Rôle                 |
| -------------- | -------------------- |
| Consul         | Service Discovery    |
| Gateway        | Point d’entrée       |
| SERVICE-CLIENT | Microservice client  |
| SERVICE-CAR    | Microservice voiture |
| MySQL          | Base de données      |

 ## Vidéo de démonstration :
 
https://github.com/user-attachments/assets/7f9690f8-6254-4953-a6d0-bf72b7f0f12b

<img width="892" height="382" alt="image" src="https://github.com/user-attachments/assets/b3601816-e7c5-4d6d-b59f-9590e965988d" />



## Conclusion

La migration de Eureka vers Consul permet :

-Une meilleure gestion de la découverte

-Une meilleure supervision

-Une architecture plus moderne et robuste

-Les microservices utilisent désormais Consul comme source de vérité.
