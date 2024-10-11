# Optimisation Automatisée des Emails et Réunions avec des Solutions IA
![image](https://github.com/user-attachments/assets/2e4508a3-5e37-4435-9be3-35d6cfe963e0)


## Description

Ce projet propose une automatisation complète des flux de travail pour la gestion des emails et des réunions Google Meet, en utilisant des outils IA comme ChatGPT, Whisper API, Google Sheets, et Hugging Face. L'objectif est de simplifier les processus d'analyse, de tri et de récapitulation des emails et réunions en automatisant les tâches manuelles et répétitives.

## Workflow

### Workflow 1 : Automatisation des Emails

1. **Email** : Les emails sont reçus et capturés pour traitement.
2. **Traitement ChatGPT** : Utilisation de ChatGPT pour extraire des informations clés comme la date, l'objet, le contenu et l'urgence de l'email.
3. **Retranscription dans Google Sheets** : Les données extraites sont automatiquement transcrites dans une feuille Google Sheets pour un suivi structuré.
![image](https://github.com/user-attachments/assets/aaa79c3d-df10-43c0-adcd-164286c06aa0)



### Workflow 2 : Automatisation des Réunions Google Meet

1. **Réunion Google Meet** : Enregistrement d'une réunion Google Meet dans un dossier dans le drive.
2. **Enregistrer la Réunion et Stockage sur Google Drive** : La réunion est enregistrée et stockée dans Google Drive pour une utilisation ultérieure.
3. **Speech-to-Text Whisper API** : Transcription de l'audio de la réunion en texte à l'aide de l'API Whisper.
4. **Hugging Face (Modèle de Résumé Automatique)** : Utilisation de l'API Hugging Face pour générer automatiquement un résumé basé sur la transcription obtenue.
   ![image](https://github.com/user-attachments/assets/fb9f50f8-6134-4809-81f9-c8bfa9c57718)


### Résultat

- **Envoi d'un Email avec le Résumé** : Une fois le résumé généré, on a le résultat dans notre folder sur le drive
  ![image](https://github.com/user-attachments/assets/632b5a53-f15b-40c0-9db0-acc17723e798)


## Technologies Utilisées

- **ChatGPT** : Pour l'analyse et l'extraction d'informations à partir des emails.
- **Google Sheets** : Pour stocker et organiser les données extraites des emails.
- **Google Meet** : Outil de visioconférence utilisé pour organiser et enregistrer les réunions.
- **Google Drive** : Pour stocker les enregistrements des réunions.
- **Whisper API** : API de reconnaissance vocale pour transcrire les enregistrements de réunions.
- **Hugging Face** : Modèle NLP utilisé pour générer des résumés automatiques des réunions.
- **MAKE**: https://www.make.com/en
## Bénéfices

- **Gain de temps** : Automatisation des tâches répétitives comme le tri des emails et la rédaction de résumés de réunions.
- **Réduction des erreurs** : Minimisation des erreurs humaines dans le traitement des emails et la gestion des réunions.
- **Centralisation des informations** : Toutes les données sont centralisées et organisées dans Google Sheets et Google Drive pour un accès facile.

## Installation et Utilisation

1. **Pré-requis** :
   - Un compte Google pour utiliser Google Sheets, Google Meet, et Google Drive.
   - Un compte Make pour automatiser le processus de connexion entre les différents outils.
   - Accès à ChatGPT et Whisper API pour les fonctionnalités d'IA.
   - Accès à Hugging Face pour les modèles NLP de génération de résumés.

2. **Mise en place** :
   - Créer les automatisations avec Zapier pour connecter Gmail, Google Sheets, et les autres services.
   - Configurer ChatGPT et Whisper API pour analyser les emails et transcrire les réunions.
   - Utiliser Hugging Face pour générer automatiquement des résumés.

## Auteurs

Ce projet a été réalisé dans le cadre de l'automatisation des flux de travail en entreprise avec des outils IA.

