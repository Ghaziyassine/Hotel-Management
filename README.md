# Application de Gestion d'un Hôtel

## Aperçu

Le Système de Gestion d'Hôtel est une application web construite avec Spring Boot, React + Vite, et JWT Spring Security. Il offre une plateforme pour gérer les opérations hôtelières, y compris les réservations de chambres, les informations sur les clients et les tâches administratives.

## Fonctionnalités

- **Authentification et Autorisation d'Utilisateur :** Sécurisez votre application avec une authentification basée sur JWT et une autorisation utilisant Spring Security.

- **Gestion des Chambres :** Ajoutez, modifiez et supprimez des chambres. Capturez les détails de la chambre tels que le type de chambre, le prix et la disponibilité.

- **Système de Réservation :** Permettez aux clients de réserver des chambres. Gérez et visualisez les détails de réservation, y compris les dates d'arrivée et de départ.

- **Tableau de Bord :** Surveillez les principales métriques et visualisez les données pour une meilleure prise de décision.

## Video démonstrative



https://github.com/user-attachments/assets/94fffe1d-baff-4e3e-a708-d97704a7c3d7





## Technologies Utilisées

- **Backend :**
  - Spring Boot : Framework basé sur Java pour construire des applications backend robustes et évolutives.
  - Spring Security : Gère l'authentification et l'autorisation.
  - JWT (JSON Web Tokens) : Transmettez des informations de manière sécurisée entre les parties.

- **Frontend :**
  - React : Bibliothèque JavaScript pour la construction d'interfaces utilisateur.
  - Vite : Outil de construction rapide pour le développement web moderne.

## Configuration

### Cloner le projet depuis GitHub
```bash
git clone https://github.com/Ghaziyassine/Hotel-Management.git
```
### Utiliser Docker
- Build the Docker images :
```bash
docker-compose build
```

- Run the Docker containers :
```bash
docker-compose up
```
![Capture d’écran 2025-01-14 160830](https://github.com/user-attachments/assets/3a80ed89-b3a2-46f6-9344-a3b6886afb51)

- Connect to phpMyadmin server on port 8081 ( user:"root"-password:"root") and restart the backend from Docker Desktop
### Utiliser un deploiment local
- cd Base de donnée: 
  Créez une base de données "mazagan" où vous importez la bdd ci-dessus hotel.sql
(dans cette base de données vous trouvez les accés d'un utilisateur par défaut dont le login : user@user et mdp : user@user et un admin par défaut dont le login : admin@admin et mdp: admin@admin)
- Backend:
  ```bash
   mvn clean install
   ```
   ```bash
     mvn spring-boot:run
   ```
- Frontend:
  ```bash
  npm install
  ```
  ```bash
    npm run dev
  ```
- Ouvrir l'url suivant : http://localhost:5173/

## Auteurs

- GHAZI Yassine





