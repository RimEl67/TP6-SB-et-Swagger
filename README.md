# TP 6 Spring Boot et Swagger par: Rim EL ABBASSI

Cette application Spring Boot permet de gérer des étudiants (opérations CRUD) et de fournir des statistiques simples basées sur les données enregistrées.

---

## ✨ Objectifs du projet

- Implémenter une architecture Spring Boot complète (entités, DAO/service, contrôleur REST).
- Connecter une base MySQL pour la persistance des données.
- Exposer des endpoints REST testables via Postman, Swagger UI.
- Fournir des statistiques simples sur les étudiants par année de naissance.


## 🚀 Fonctionnalités principales

| Fonctionnalité         | Endpoint                | Méthode | Description                              |
|------------------------|-------------------------|---------|------------------------------------------|
| Ajouter un étudiant    | `/students/save`        | POST    | Création d'un nouvel étudiant            |
| Liste des étudiants    | `/students/all`         | GET     | Retourne tous les étudiants              |
| Nombre total           | `/students/count`       | GET     | Compte les étudiants enregistrés         |
| Suppression            | `/students/delete/{id}` | DELETE  | Supprime un étudiant par ID              |
| Statistiques par année | `/students/byYear`      | GET     | Retourne le nombre d'étudiants par année |


## ✅ Tests
### 1. Ajouter un étudiant

Endpoint: `POST /students/save`

<img width="1366" height="768" alt="save" src="https://github.com/user-attachments/assets/9ba9ce08-4beb-4a0d-b957-0733dfda13ee" />


### 2. Récupérer tous les étudiants

Endpoint: `GET /students/all`

<img width="1366" height="768" alt="all" src="https://github.com/user-attachments/assets/772297c5-4ac6-4ba2-ab97-0e1245fc469f" />


### 3. Compter le nombre d'étudiants

Endpoint: `GET /students/count`
<img width="1366" height="773" alt="count" src="https://github.com/user-attachments/assets/0911708f-fdaa-4ade-98c8-bb820eb55824" />
<img width="1366" height="679" alt="DB" src="https://github.com/user-attachments/assets/a0a32a4e-b63f-4fa6-94eb-2ad670d9e68e" />


### 4. Supprimer un étudiant

Endpoint: `DELETE /students/delete/1`
<img width="1366" height="768" alt="delete" src="https://github.com/user-attachments/assets/c1de87a6-952d-424a-9f59-e08879829f41" />


### 5. Statistiques par année

Endpoint: `GET /students/byYear`
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/e35d7c62-afd2-434b-a817-9772979def7b" />

### 6. StudentControllerTest
<img width="1366" height="768" alt="testtt" src="https://github.com/user-attachments/assets/9168c859-6739-4511-b32e-c33d3f1b5f95" />

### 7. Intégration de Swagger
<img width="1366" height="592" alt="image" src="https://github.com/user-attachments/assets/d23ea6ea-8a4a-44ea-8335-7abedfc1e333" />
<img width="1366" height="500" alt="image" src="https://github.com/user-attachments/assets/762a5cba-8448-4bad-bb28-cf949e515708" />
