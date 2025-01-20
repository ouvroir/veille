---
title: Rapport sur la diffusion des événements en histoire de l'art sur le site du doc-inter
description: étude des outils et possibilité
author: Zoë Renaudie
date: 2025-01-15
draft: true
tags:
  - veille
  - calendrier
  - agenda
  - liste de diffusion

---

# Rapport sur la diffusion des événements en histoire de l'art sur le site du doc-inter

## Question

Comment partager efficacement l'information sur les évènements d'histoire de l'art à toute la communauté de Doc-Inter ?

## Analyse

### Le site Doc-Inter

Le site Doc-Inter est un site WordPress géré par une attachée de communication.

#### Calendrier

- Le site propose un calendrier accessible ici : https://docinterhar.ca/events/.
- Problème actuel : ce calendrier est peu rempli en raison de la difficulté à collecter l'information.
- Points positifs :
  - Le calendrier est esthétique et fonctionnel.
  - Les utilisateurs peuvent s’y abonner via leur propre plateforme d’agenda (export ICS disponible).

#### News & Events

- La page regroupe des évènements et appels à contribution, avec une classification par onglets et tags. Ce sont les mêmes que dans le calendrier. 

#### Liste de diffusion

- Une newsletter Mailchimp est disponible, permettant de diffuser les évènements. Tous les membres de Doc-Inter devraient y être automatiquement inscrits.

### Les calendriers universitaires

#### Université de Montréal (UdeM)

- Le [calendrier UdeM](https://calendrier.umontreal.ca/) permet aux professeurs de publier des événements via une plateforme dédiée ([Guide utilisateur](https://calendrier.umontreal.ca/docs/GuidedutilisateurUdeM.pdf)).
- Les événements UdeM étaient intégré à un calendrier général montréalais via Caligram. Limitation : Caligram (anciennement Mur Mitoyen) est peu actif.
- Intégration dans les pages "Nouvelles" et "Événements" du département d’histoire de l’art.
- Le Mur mitoyen et Caligram ne seront plus utilisés dans la  nouvelle version du calendrier institutionnel. L’outil est désormais  hébergé dans TYPO3, la même plateforme que votre site Web départemental.
- Pour les événements extérieurs, le département de l'Udem transfère les mails qui leurs sont envoyés. Pas écologique et fait exploser les boites mails. Pas éditorialisé. Comment ça se passe pour l'UQAM et Concordia ?

#### Université du Québec à Montréal (UQAM)

- UQAM utilise également Caligram : https://evenements.uqam.ca/.

#### Université Concordia

- Le site https://concordia.ab.ca/events/ ne propose pas de formulaire pour renseigner les événements.
- La page du département d’histoire de l’art ([Concordia Art History](https://www.concordia.ca/finearts/art-history.html)) était inaccessible lors de cette analyse.

### Calendrier Aesthesis

L’association Aesthesis utilise un agenda Google pour partager les événements en histoire de l’art. Au lieu d'ajouter les événements à son agenda personnel, les membres du bureau le font dans cet agenda. Ce système est collaboratif mais repose sur une plateforme privée. 

## Problèmes identifiés

### 1. Collecte d’information

- Les signalements d’événements arrivent par mail et doivent être traités manuellement par l’attachée de communication ce qui est chronophage 
- Peu de personne partage leurs événements au doc-inter ce qui explique le faible nombre d’événements publiés.

### 2. Limitation des outils actuels

- Le site utilise le plugin gratuit [The Events Calendar](https://theeventscalendar.com/) pour WordPress. Ajouter un formulaire direct pour les événements nécessiterait le plugin payant [Community Events](https://theeventscalendar.com/products/community/) (à 129 $/an).
- Une alternative serait de créer un formulaire personnalisé permettant de recevoir des événements pré-traités par mail.
- Les calendriers universitaires ne semblent pas pouvoir être ajoutés à son agenda perso. Il faut donc aller vérifier les informations.

### 3. Liste de diffusion 

La liste de diffusion peut-être une lettre d'information mais aussi un espace de partage. Les personnes inscrites à la liste peuvent partager leurs informations aux autres abonnés. Ça peut être pratique pour centraliser le partage de l'information. Il faudra cependant aussi saisir les informations dans le calendrier si cette solution souhaite être maintenue. 

- Bien que pratique, Mailchimp est une solution propriétaire et payante.
- Alternatives : listes de diffusion libres (ex. : Sympa, offert par l’UdeM).
- Mise à jour annuelle nécessaire pour s’assurer que tous les membres sont inscrits.
- Les listes de diffusions arrivent dans la boites des indésirables

### 4. Coordination interuniversitaire

- Chaque université gère ses propres outils et pratiques, rendant la collecte et la diffusion d’information complexe.
- Publier exclusivement sur Doc-Inter pourrait exclure un public extérieur à l’histoire de l’art. 
- Il me semble important que les départements universitaires continuent de promouvoir leurs événements internes. 

## Propositions

### **Problème 1 : Difficulté à collecter et à traiter les informations sur les événements**

#### Solution : Création d’un formulaire en ligne intégré

- Mettre en place un formulaire simple et intuitif sur le site WordPress de Doc-Inter.
- Utiliser un plugin gratuit ou peu coûteux pour collecter les informations essentielles (titre, description, date, lieu, image, contact, etc.).
- Automatiser l'envoi des données collectées vers l'attachée de communication, réduisant le traitement manuel.
- https://calenda.org/ site à formulaire pour proposer événements. 

#### Solution : Automatisation partielle du traitement

- Configurer des règles dans le formulaire pour normaliser les entrées (par ex., un menu déroulant pour les types d'événements ou les lieux).
- Explorer les fonctionnalités payantes de « The Events Calendar » pour permettre une modération rapide des propositions avant publication.

### **Problème 2 : Faible utilisation du calendrier Doc-Inter**

#### Solution : Passer le calendrier sur Caligram. 

1. ​	Avantages : 
   - le calendrier peut être affiché sur le wordpress.
   - interface de saisie des événements simple
2. Inconvénients :
   - La coop en charge de l'outil semble péricliter. Vérifier que les universités restent sur l'outil avant de s'engager. 
   - on ne peut pas s'abonner (ce qui pour moi serait vraiment un plus par rapport aux propositions des universités et autres plateformes)
   - Les événements seront multiplié sur leurs plateformes s'ils sont sur sur les groupes des universités Et de doc inter.
   - Ne résout pas la problématique de la lettre d'information

#### Solution : Implication des membres dans l’alimentation du calendrier

- Encourager les membres (étudiants, professeurs) à ajouter leurs propres événements dans le calendrier via des campagnes d’information (ex. : newsletters, courriels de rappel).
- Former les membres clés des universités partenaires à l’utilisation du système.

#### Solution : Synchronisation interuniversitaire

- Proposer une intégration avec les calendriers des universités (UdeM, UQAM, Concordia) pour récupérer automatiquement les événements pertinents.
- Explorer les API disponibles pour automatiser la synchronisation avec les plateformes existantes. 
- Solutions IA?

### **Problème 3 : Liste de diffusion**

Avec l'information traitées grâce aux solutions précédentes, l'éditorialisation sera plus simple. 

#### Solution : Passage à une solution open-source

- Migrer de Mailchimp vers une solution libre comme Sympa.
- Configurer une gestion centralisée pour garantir l'inscription automatique des membres du doc-inter tout en respectant leur droit de désinscription.

#### Solution : Optimisation des newsletters

- Simplifier le contenu des newsletters avec des liens directs vers le calendrier en ligne.
- Rappeler de s'abonner à l'agenda

### **Problème 4 : Manque de visibilité interuniversitaire**

#### Solution : Collaboration entre départements

- Mettre en place une charte ou un accord informel pour harmoniser la diffusion des événements entre les universités partenaires.
- Nommer des référents dans chaque département pour assurer une veille sur les événements.

#### Solution : Élargir la diffusion

- Publier les événements non seulement sur Doc-Inter, mais aussi sur des plateformes grand public comme Eventbrite ou les réseaux sociaux universitaires.
- Intégrer des outils comme Mur Mitoyen ou Caligram (s’ils sont encore fonctionnels) pour toucher un public plus large.

### **Problème 5 : Temps et ressources limités**

#### Solution : Renforcer les ressources humaines

- Mobiliser des bénévoles ou stagiaires (étudiants en communication ou histoire de l’art), associations étudiantes, CEDISC pour aider à l’organisation et la diffusion des événements.
- Nommer un ou deux représentants étudiants ou membres du personnel dans chaque université pour assurer une veille et une transmission d’événements vers Doc-Inter.

#### Solution : Automatisation accrue

- Explorer des solutions automatisées pour la gestion des événements, comme des scripts ou des outils no-code pour l'intégration entre plateformes.

## Préconisations

### SOLUTION 1

Avoir un calendrier avec les informations sur le site doc-inter.

#### Étape 1 : Récolter l’information

1. **Formulaire de soumission :**
   - Créer un formulaire personnalisé sur le site Doc-Inter pour permettre aux utilisateurs de soumettre des événements.
   - Si possible, inclure des champs clés : titre, date, lieu, description, type d’événement, lien d’inscription.
2. **Responsabiliser les membres :**
   - Encourager les membres à renseigner directement les événements dans le calendrier Doc-Inter. Les professeurs devraient également publier leurs événements sur Doc-Inter pour toucher une audience interuniversitaire.
   - Informer les départements d'histoire de l'art. Créer un mail de réponse type si un événement leur est envoyé. Maintenir la publication d’événements sur les calendriers universitaires.

#### Étape 2 : Partager l’information

1. **Validation et éditorialisation :**
   - La soumission d’événements via formulaire serait validée par l’attachée de communication avant publication.
2. **Lettre d'information** :
   - L'attachée de communication doit continuer de faire une lettre d'information à partir du calendrier. Il est conseillé d'en faire une tous les 15 jours pour éviter l'accumulation. 

### SOLUTION 2

#### Étape 1 : Créer une liste de diffusion

Les départements et les professeurs de doc inter s'inscrivent et partagent leurs événements sur une liste de diffusion. Les personnes extérieures au doc inter sont aussi invités à partager l'info sur la liste de diffusion. 

#### Étape 2 : Calendrier

Si le doc-inter veut maintenir un calendrier sur leur site, il est préconisé que l'attachée à la communication entre manuellement les informations de la liste de diffusion. 

Une solution pour avoir un formulaire serait que le contenu soit envoyé directement sur la liste de diffusion.

### Suggestions techniques

- Il est possible d'investir dans le plugin "Community Events" pour simplifier la soumission d’événements. L'attachée de communication n'aura pas à renseigner les informations pour qu'elles soient publiées dans le calendrier. 
- Explorer les autres plugin calendrier pour wordpress.
- Passer à une solution libre et open-source pour la newsletter, comme Sympa.

### Implication communautaire

- Sensibiliser les membres du Doc-Inter à l’importance de contribuer activement au calendrier.
- Créer une campagne de communication pour expliquer l’utilisation des outils (formulaire, calendrier, newsletter).

## Conclusion

La mise en place de solutions collaboratives et la simplification des processus techniques permettraient d’améliorer la visibilité et l’accès aux événements d’histoire de l’art sur Doc-Inter, tout en allégeant la charge de travail de l’attachée de communication. En favorisant une participation active de la communauté, Doc-Inter peut devenir une plateforme centrale pour la diffusion d’événements culturels.
