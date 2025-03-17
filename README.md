Projet VPN Itinérant

Description

Ce projet vise à mettre en place un VPN itinérant permettant à un utilisateur distant d'accéder à ses fichiers à distance en toute sécurité. Le VPN repose sur WireGuard et fonctionne sur une machine virtuelle Debian 11.

Objectifs

Permettre une connexion sécurisée entre un utilisateur distant et son réseau

Assurer un chiffrement des données via WireGuard

Mettre en place un système simple et efficace de connexion VPN

Prérequis

Pour déployer ce projet, il est nécessaire d'avoir :

Une machine virtuelle sous Debian 11

Un accès root ou des privilèges sudo

Une connexion internet stable

Déroulement du Projet

Installation et Configuration

Le projet commence par l'installation de WireGuard sur une machine Debian 11. Une fois le logiciel installé, la configuration du serveur VPN est réalisée en générant des clés de chiffrement et en définissant les paramètres du tunnel VPN.

Routage et Sécurisation

Le routage des paquets entre les différents réseaux est activé afin de permettre la communication entre les clients et le serveur. Un pare-feu est mis en place pour assurer la sécurité des échanges de données.

Configuration du Client

Une configuration est également requise du côté des utilisateurs distants. Chaque client WireGuard doit disposer des informations de connexion du serveur ainsi que de sa propre clé de chiffrement.

Tests et Validation

Une fois le VPN configuré, des tests de connexion et de transfert de fichiers sont effectués pour vérifier la stabilité et la sécurité du système. Des comparaisons avec d'autres solutions comme OpenVPN peuvent être réalisées pour mesurer les performances.
