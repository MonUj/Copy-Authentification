# Copy-Authentification

Etape pour tester mon projet Authentification:
1 - Dl le repo github

2 - Modifiez le .env avec vos informations ou avec une bdd sqlite : ligne DATABASE_URL : sqlite:///%kernek.project_dir%/var/data.db ou avec vos paramètres de votre base de données MySQL.
(La config de base est root avec wamp sur le port 3306)

3 - Executez la base de données : php bin/console doctrine:schema:update --force

4 - Executez les données : php bin/console doctrine:fixtures:load --no-interaction

5 - Lancez le serveur interne : php bin/console server:run

6- Rendez-vous sur la page /login

7- Tu as juste à prendre un e-mail dans la bdd et le mdp est : Pass1234@ pour se connecter

Vous pouvez à présent testez mon projet !
