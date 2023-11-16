# ProjetDockerFinal

pour php vous devez créer vous même avec un dockerfile (vous pouvez utiliser n’importe quel FROM ) ( le
fichier de configuration pour nginx n’est pas fournis )
Vous devez être capable d’accéder au code des deux serveur nginx par votre navigateur web. et exécuter
les commande de démarrage de laravel dans vos deux services PHP ( trouver comment automatiser ça ):
composer install ( installer composer )
npm run build ( installer node )
php artisan key:generate
php artisan migrate:fresh —seed
ne pas oublier que pour lier laravel et la db le .env peut vous servir ( dupliquer .env.exemple en .env et
remplir les champs db )
>
Changer le code des deux serveurs pour quand je tappe sur Nginx 1 je vois d’affiché “Serveur 1” et sur
Nginx 2 “Serveur 2” mais garder les bouton de connexion et inscription ( fichier /ressources/views/welcome.
blade.php )
réussir à vous inscrire et vous connecter sur les deux nginx
vérifier que vous avez bien dorénavent 2 utilisateurs en database
Tout ajout que vous pouvez mettre sera des points en plus ( ‘exemple : traefik, minio, mailship , node etc
… ) mais cela doit être logique ( et encore plus de points si vous n’utilisez pas d’image préfaites et que vous
les faites vous même )
N’oubliez pas d’ajouter les .env de votre code dans le rendu le rendu doit être fait sous un repos Github en
public ( sinon c’est zéro )
La notation se fera en 4 points :
5 points sur la complexité et vos ajouts personnels
5 points sur la compréhension Dockerfile
5 points sur la compréhension Docker-compose
5 points sur l’automatisation et la logique du système
ATTENTION c’est un TP sur Docker et non sur d’autres langages tout autre ajout de code ne sera pas
compris dans la notation
Le rendu doit se faire sous github ET Zip sur myges ET faire une vidéo expliquant comment fonctionne le
projet comme si j'étais devant vous, humour et troll fortement apprécié