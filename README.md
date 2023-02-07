# DevOpsProjet

Projet réaliser par : Antonio Gernac-Aleixo et Arsene Onambele

Afin de réaliser correctement le projet il suffit de lancer le script bash install.sh.

Celui-ci va installer le gestionnaire de paquets hombrew, homebrew va nous permettre d'installer minikube et kubectl.

Par la suite il suffit de lancer les commandes suivantes:

-minikube start

-kubectl apply -f mysqlConfig.yaml

mysqlConfig.yaml est le fichier de configuration qui va nous permettre de déployer les deployments mysql/apache.
