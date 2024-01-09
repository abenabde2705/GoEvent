# GoEvent
Développement et Conception d’une application web de gestion d’évènements
# Projet Gestionnaire d'événements

## Démarrage du Projet

### Backend Symfony (projectweb)

1. **Installation des dépendances avec Composer:**
   ```bash
   composer install

2. **Démarrage du service MySQL:**
   ```bash
   sudo service mysql start
3. **Restauration de la base de données:**

   Utilisez le fichier de sauvegarde SQL fourni (lastsql.sql) pour restaurer la base de données.

4. **Lancement du serveur Symfony:**
   ```bash
   symfony server:start

5. **Accès au Dashboard Symfony:**

   Ouvrez votre navigateur et accédez à:
   http://localhost:8000/admin pour accéder au Dashboard Symfony où vous pouvez gérer les événements.

### Frontend Vue.js (projectwebvuejs)

1. **Installation des dépendances avec npm:**
   ```bash
   npm install

2. **Lancement du serveur de développement:**
   ```bash
   npm run dev

### ATTENTION ! : 

Problème avec l'API Vue.js:

Actuellement, il y a un problème avec l'upload et la récupération des données via l'API Vue.js.
Les données peuvent être récupérées mais l'upload ne fonctionne pas correctement.
Veuillez utiliser le Dashboard Symfony pour gérer les événements en attendant la résolution du problème.
