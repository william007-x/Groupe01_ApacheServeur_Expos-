# Groupe01_ApacheServeur_Expos-
Projet de mise en place et de la sécurisation d'un Serveur Web Apache, dans le cadre du cours de système d'exploitation.
Projet : Déploiement et sécurisation d’un serveur Apache sous Linux
1. Présentation du projet

Ce projet a été réalisé dans le cadre du cours de Système d’Exploitation I & II.
Il porte sur la mise en place, la configuration et la sécurisation d’un serveur web Apache HTTP Server dans un environnement Linux (Ubuntu).

L’objectif principal est de comprendre :
          
l’architecture interne d’Apache,

le rôle des fichiers et répertoires de configuration,

la mise en œuvre des Virtual Hosts,

la gestion des permissions Linux,

la sécurisation des communications via TLS/HTTPS.

2. Objectifs du projet

Installer et configurer Apache HTTP Server sous Linux

Comprendre l’organisation des fichiers de configuration d’Apache

Mettre en place des hôtes virtuels (Virtual Hosts)

Gérer correctement les permissions et propriétaires des fichiers

Sécuriser le serveur web à l’aide du protocole HTTPS (TLS)

Tester et valider le bon fonctionnement du serveur

3. Environnement et outils utilisés

Système d’exploitation : Ubuntu Linux

Serveur web : Apache HTTP Server

Sécurité : OpenSSL (certificats TLS)

Outils système :

apt, systemctl

a2enmod, a2ensite, a2dissite

chmod, chown, openssl

Toutes les opérations ont été réalisées en ligne de commande.

4. Méthodologie

Le projet a été mené selon une approche progressive :

Installation

Installation d’Apache

Vérification du service et des ports d’écoute

Configuration

Analyse de l’architecture d’Apache (/etc/apache2)

Création et activation de Virtual Hosts

Organisation des répertoires web (/var/www)

Configuration des journaux (logs)

Sécurisation

Activation du module SSL

Génération de certificats TLS

Configuration HTTPS

Redirection HTTP vers HTTPS

Renforcement des permissions et bonnes pratiques

Chaque étape a été validée par des tests avant de passer à la suivante.

5. Tests et validation

Les tests réalisés incluent :

Vérification du service Apache

Accès HTTP et HTTPS via navigateur

Validation de la configuration (apache2ctl configtest)

Vérification des ports d’écoute (80 et 443)

Contrôle des journaux d’erreurs et d’accès

Les résultats confirment que le serveur est fonctionnel, sécurisé et conforme aux objectifs du projet.

6. Contenu du repository

Rapport.pdf : rapport final du projet

Diapositives.pdf : support de présentation (≤ 15 slides)

README.md : description du projet et méthodologie

7. Conclusion

Ce projet a permis d’acquérir une compréhension concrète et approfondie de l’administration d’un serveur web Apache sous Linux. Il constitue une base solide pour la gestion, la sécurisation et la maintenance de services web en environnement réel. 
