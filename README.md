Chatbot FudicIA - Interface Web
	Projet de Prairie : Création d’un CHATBOT générative
	Réalisation : GOUHEAN Cedric Semindey Yannick
	Lien Github : https://github.com/ygouhean/projetchatbot.git
	


I-	Description
Ce projet est une interface de chatbot interactif pour une assistance en assurance santé. Il permet aux utilisateurs de poser des questions et d'obtenir des réponses sur divers sujets liés à leur assurance. Le chatbot est intégré avec l'API Google Generative AI (modèle Gemini 1.5 Flash) pour générer des réponses intelligentes et pertinentes.
 
1-	Objectif Principal
L'objectif principal de ce projet est de développer un chatbot interactif spécialisé en assurance santé. Il permet aux utilisateurs d'obtenir des informations sur leurs garanties, de localiser des centres médicaux partenaires, de suivre leurs remboursements et d'envoyer des rappels pour des rendez-vous médicaux.

1.1-	Objectifs Spécifiques
1.	Faciliter la communication entre les utilisateurs et leur assureur santé.
2.	Automatiser les réponses aux questions fréquentes sur les garanties et les remboursements.
3.	Offrir une interface conviviale et intuitive basée sur HTML, CSS et JavaScript.
4.	Intégrer un modèle d'intelligence artificielle pour répondre de manière pertinente aux demandes des utilisateurs.
5.	Assurer la compatibilité multi-appareils grâce à un design responsive basé sur Bootstrap.

1.2-	Prérequis
Avant d'exécuter ce projet, assurez-vous d'avoir :
•	Un navigateur web moderne (Chrome, Firefox, Edge, etc.)
•	Une connexion Internet stable
•	Une clé API Google Generative AI


II-	Installation et Mise en Place
1.	Téléchargez ou clonez le projet :
2.	git clone https://github.com/votre-repo/chatbot-fudicia.git
3.	Ouvrez le fichier HTML dans un navigateur :
o	Accédez au dossier du projet et ouvrez index.html avec un navigateur.
4.	Ajoutez votre clé API Google Generative AI :
o	Remplacez VOTRE_CLE_API_ICI dans le script JavaScript par votre propre clé API.
5.	Interagissez avec le chatbot :
o	Tapez un message dans l'input et cliquez sur "Envoyer" ou appuyez sur Entrée.


III-	Difficultés Rencontrées et Solutions Appliquées
Difficulté	Solution
Intégration de l'API Google Generative AI	Vérification de la clé API et test avec des requêtes simples avant d'implémenter dans le chatbot.
Problèmes d'affichage du chatbot	Ajustement des styles CSS et utilisation de Bootstrap pour garantir un design responsive.
Gestion des messages et mise à jour dynamique	Utilisation de JavaScript pour manipuler le DOM et afficher dynamiquement les messages.
Erreurs lors des requêtes à l'API	Gestion des erreurs avec try...catch pour afficher un message d'erreur clair à l'utilisateur.


IV-	Explication du Code

1-	HTML (Structure du Chatbot)
•	<div class="main-container"> : Conteneur principal du chatbot.
•	<div class="torch-container"> : Élément décoratif en haut du chatbot.
•	<div class="chat-container"> : Contient toute l'interface du chatbot.
•	<div class="chat-header"> : En-tête avec le titre et l'image du chatbot.
•	<div class="chat-messages"> : Zone d'affichage des messages échangés.
•	<div class="chat-input"> : Zone de saisie du message avec un bouton d'envoi.

2-	CSS (Mise en forme et styles)
•	.main-container : Style général du chatbot (taille, bordures, flexbox).
•	.chat-container : Conteneur des messages avec une hauteur et un design spécifiques.
•	.chat-messages : Gère le défilement des messages.
•	.message.user : Style des messages envoyés par l'utilisateur.
•	.message.bot : Style des réponses du chatbot.
•	.user-profile : Contient l'image de profil et la description du chatbot.

3-	JavaScript (Logique du Chatbot)
3.1-	Importation du SDK Google Generative AI
•	Permet d'accéder aux fonctionnalités de l'API Google Generative AI.

3.2-	Configuration de l'API
•	API_KEY : Clé API pour authentifier les requêtes.
•	genAI : Instance de l'API Google Generative AI.
•	model : Modèle de génération de texte utilisé.

3.3-	Fonction pour envoyer un message et recevoir une réponse
•	Récupère le message de l'utilisateur et l'affiche.
•	Envoie la requête à l'API et affiche la réponse du chatbot.
•	Gère les erreurs en cas de problème avec l'API.

3.4-	Événement pour envoyer un message avec la touche Entrée
•	Permet d'envoyer un message en appuyant sur la touche "Entrée".


V-	Fonctionnalités Futures
•	Amélioration de l'interface utilisateur.
•	Enregistrement des conversations.
•	Ajout d'une base de données pour sauvegarder les questions fréquemment posées.

