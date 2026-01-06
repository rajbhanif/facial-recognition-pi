# Système de Sécurité par Reconnaissance Faciale

Un système de sécurité intelligent basé sur la reconnaissance faciale utilisant Raspberry Pi. Ce projet offre un contrôle d'accès sécurisé pour les entreprises ou les habitations, avec une activation par bouton tactile et un retour visuel/sonore immédiat.

## Aperçu du Projet

Ce système de sécurité IoT combine matériel et logiciel pour créer une solution de contrôle d'accès fiable. Lorsqu'un utilisateur active le système via le TouchSwitch, la caméra capture et analyse les visages en temps réel. Le système détermine si la personne est autorisée et répond instantanément avec des indicateurs LED et une alarme sonore.

## Fonctionnalités

### Contrôle d'Accès Intelligent
- Activation par TouchSwitch - Interface physique simple pour activer/désactiver
- Reconnaissance Faciale en Temps Réel - Analyse instantanée des visages via caméra
- Système de Retour Dual :
  - LED Verte - Accès autorisé
  - LED Rouge + Buzzer - Accès non autorisé avec alarme
- Gestion des Permissions - Seuls les utilisateurs autorisés peuvent arrêter le système
- Base de Données Sécurisée - Stockage local des visages autorisés

### Caractéristiques Techniques
- Intégration Matérielle Complète - Contrôle GPIO des capteurs et actionneurs
- Performance Optimisée - Fonctionne efficacement sur Raspberry Pi
- Interface Utilisateur Intuitive - Retour visuel et sonore clair
- Configuration Flexible - Paramètres ajustables selon les besoins

## Matériel 

| Composant | Quantité | Rôle |
|-----------|----------|------|
| Raspberry Pi (3/4/Zero) | 1 | Contrôleur principal |
| Module Caméra Raspberry Pi | 1 | Capture des visages |
| Bouton Tactile (TouchSwitch) | 1 | Activation du système |
| LED Double Couleur (RGB) | 1 | Indicateur d'état |
| Buzzer Actif | 1 | Alarme sonore |
| Câbles Dupont | 10 | Connexions |
| Breadboard | 1 | Prototypage |
| Alimentation 5V/3A | 1 | Alimentation |


## Comment Utiliser

### Processus d'Accès :
1. Activation : Appuyer sur le TouchSwitch (LED verte clignote)
2. Identification : Se placer face à la caméra
3. Résultat :
   - Accès Autorisé : LED verte allumée, accès accordé
   - Accès Refusé : LED rouge + alarme buzzer pendant 5 secondes
4. Désactivation : Appuyer à nouveau sur le TouchSwitch (utilisateurs autorisés seulement)


## Projet Scolaire - Non partageable

Ce projet a été développé dans le cadre du cours d'objets connectés.
Le code source n'est pas disponible pour des raisons académiques.

## Démonstration

### Regarder la vidéo (cmd + click)
*Processus complet : Activation → Scan facial → Résultat d'autorisation*

<a href="https://rajbhanif.github.io/facial-recognition-pi/facial-recognition.mp4" target="_blank">▶ Cliquez ici pour ouvrir la vidéo</a>

*La vidéo s'ouvrira directement dans votre navigateur*



## Auteur
**Raj Beghum Hanif**  
Projet académique - Cours d'objets connectés
