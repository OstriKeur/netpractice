# NetPractice

Apprentissage des réseaux TCP/IP - Projet 42 Paris

## À propos

NetPractice est un projet pédagogique interactif qui permet d'apprendre les concepts fondamentaux des réseaux TCP/IP. C'est une application web qui propose des exercices pratiques pour comprendre le routage, les sous-réseaux, et la configuration réseau.

Ce projet m'a permis de comprendre en profondeur comment fonctionnent les réseaux, les adresses IP, les masques de sous-réseau, et le routage. C'est un excellent complément théorique avant de passer aux projets réseau plus avancés.

## Objectifs

- Comprendre les adresses IP et les masques de sous-réseau
- Apprendre le routage et les tables de routage
- Maîtriser la configuration de réseaux
- Comprendre les différents types d'adresses (host, routeur, broadcast)
- Apprendre à calculer les plages d'adresses IP

## Utilisation

L'application NetPractice est accessible via un navigateur web. Elle propose une série d'exercices progressifs pour apprendre les réseaux, du niveau 0 (bases) au niveau 9 (défi final).

## Concepts appris

### Adresses IP

- Format des adresses IPv4 (xxx.xxx.xxx.xxx)
- Classes d'adresses (A, B, C)
- Adresses privées vs publiques
- Adresses spéciales (localhost, broadcast)

### Masques de sous-réseau

- Notation CIDR (/24, /16, etc.)
- Calcul de masques de sous-réseau
- Détermination du nombre d'hôtes possibles
- Plages d'adresses IP

### Routage

- Tables de routage
- Route par défaut (default gateway)
- Routage statique
- Routage entre plusieurs réseaux

### Configuration réseau

- Configuration d'interfaces réseau
- Attribution d'adresses IP
- Configuration de routeurs
- Connexion de plusieurs réseaux

## Ce que j'ai appris

- Compréhension complète du modèle TCP/IP
- Calcul et attribution d'adresses IP
- Création et gestion de sous-réseaux
- Configuration de routeurs et tables de routage
- Diagnostic et correction de configurations réseau
- Conception de topologies réseau simples

## Exemples de concepts

### Calcul de sous-réseau

Pour une adresse `192.168.1.0/24` :
- Masque : `255.255.255.0`
- Plage d'adresses : `192.168.1.0` à `192.168.1.255`
- Adresses utilisables : `192.168.1.1` à `192.168.1.254`
- Broadcast : `192.168.1.255`

### Configuration de routeur

Un routeur doit avoir :
- Une adresse IP sur chaque réseau auquel il est connecté
- Une table de routage configurée
- Les interfaces correctement configurées

## Notes

Ce projet est principalement théorique et pédagogique. Il ne nécessite pas de code mais une bonne compréhension des concepts réseau. Les exercices sont progressifs et permettent d'apprendre étape par étape.

---

**Projet réalisé dans le cadre du cursus 42 Paris**
