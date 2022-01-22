##########Partie 1: How To Build a Node.js Application with Docker ###############

-Docker est une plate-forme ouverte pour le développement, la livraison et l'exécution d'applications. Docker vous permet de séparer vos applications de votre infrastructure afin que vous puissiez fournir des logiciels rapidement. Avec Docker, vous pouvez gérer votre infrastructure de la même manière que vous gérez vos applications. En tirant parti des méthodologies de Docker pour expédier, tester et déployer du code rapidement, vous pouvez réduire considérablement le délai entre l'écriture du code et son exécution en production.
-Dans la premiére partie, Nous allons créer une image d'application pour un site Web statique qui utilise le framework Express et Bootstrap. Ensuite on va créer un conteneur en utilisant cette image et poussez-le vers Docker Hub pour une utilisation future. 
Enfin, nous allons extraire l'image stockée de notre Docker Hub et créez un autre conteneur.

##########Partie 2 :Containerizing a Node.js Application for Development With Docker Compose ###############

-Dans la deuxiéme partie,on va créer deux conteneurs:
- un pour le nœud application et une autre pour la base de données MongoDB — avec Docker Compose. Parce que cette application fonctionne avec Node et MongoDB, notre configuration effectuera les opérations suivantes :
• Synchronisez le code de l'application sur l'hôte avec le code dans le conteneur pour faciliter les changements au cours du développement.
• Assurez-vous que les modifications apportées au code d'application fonctionnent sans redémarrage.
• Créez une base de données protégée par un utilisateur et un mot de passe pour les données de l'application.
• Conservez ces données 😊.

##########Partie 3:How To Migrate a Docker Compose Workflow to Kubernetes ###############

Lors de la création d'applications modernes et sans état, la conteneurisation de votre application composante est la première étape du déploiement et de la mise à l'échelle sur des plates-formes distribuées. Si vous avez utilisé Docker Compose en développement, vous aurez modernisé et conteneurisé votre application en :
• Extraire les informations de configuration nécessaires de votre code.
• Décharger l'état de votre application.
• Emballage de votre application pour une utilisation répétée.

-Pour exécuter vos services sur une plate-forme distribuée comme Kubernetes, vous devrez traduire vos définitions de service Compose en objets Kubernetes. Cela vous permettra pour faire évoluer votre application avec résilience. Un outil qui peut accélérer la traduction processus vers Kubernetes est kompose, un outil de conversion qui aide les développeurs à passer composez des workflows pour des orchestrateurs de conteneurs tels que Kubernetes ou OpenShift.

-Dans cette partie, on va traduire les services Compose en objets Kubernetes à l'aide de composé. on utilisera les définitions d'objet fournies par kompose comme point de départ et faites des ajustements pour on assurer que notre configuration utilisera les secrets, les services, et PersistentVolumeClaims de la manière attendue par Kubernetes. A la fin de la
tutoriel, nous aurons une application Node.js mono-instance avec une base de données MongoDB exécuté sur un cluster Kubernetes.

voici mon docker hub: https://hub.docker.com/u/karima123 
![image](https://user-images.githubusercontent.com/78323027/150656516-17e81f53-0441-436f-82ed-ab9a6e027c59.png)
![image](https://user-images.githubusercontent.com/78323027/150656524-3d6fc192-29d7-48c5-8034-16ce65ade5f0.png)
![image](https://user-images.githubusercontent.com/78323027/150656532-7940b1c0-5e1c-4926-9f96-e4c9a019eee4.png)


