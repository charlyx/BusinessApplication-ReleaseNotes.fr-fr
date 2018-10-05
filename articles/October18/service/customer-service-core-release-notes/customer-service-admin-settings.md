---
title: "Comprendre les paramètres d'administration de Customer Service dans Dynamics 365 for Customer Service"
description: "Découvrir les nouvelles fonctionnalités des paramètres d'administration pour Dynamics 365 for Customer Service"
author: vippand
manager: mahesh
ms.date: 9/07/2018
ms.assetid: 516afbde-61a3-4718-8ce1-a4007ada5960
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: Annbe
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: f37556a7ddee0885758aa6cf4e9e442955bb0ccb
ms.openlocfilehash: 6f71b1b6428c0b473731cee61044941c97c2f3d7
ms.contentlocale: fr-fr
ms.lasthandoff: 09/10/2018

---
#  <a name="customer-service-admin-settings"></a>Paramètres d'administration de Customer Service 

[!include[customer-service-core-release-notes banner](../../includes/customer-service-core-release-notes.md)]

L'un des objectifs principaux des clients de Dynamics 365 est de déployer rapidement leurs processus d'entreprise. Le module Gestionnaire de services aide les responsables du service clientèle à automatiser différents processus, à améliorer le temps de réponse des agents et à optimiser la satisfaction des clients. Le Gestionnaire de services permet de configurer et de gérer des tâches de service clientèle (comme configurer des files d'attente publiques ou privées, définir des paramètres d'incidents parent-enfant, configurer des règles d'acheminement, configurer des règles de mise à jour et de création d'enregistrements automatiques et configurer des accords de niveau de service (SLA), etc.).

Avec la dernière version, le Gestionnaire de services passe sous le concentrateur du service client et permet aux responsables d'accéder aux fonctions à partir de l'application. Le nouveau Gestionnaire de services repose sur Unified Interface et aide à configurer facilement les tâches, ce qui offre une meilleure productivité. 

Vous pouvez accéder au Gestionnaire de services via le plan de site dans le concentrateur du service client : 

![Accès au Gestionnaire de services via le plan du site](media/csh-sitemap-service-management.png "Accès au Gestionnaire de services via le plan du site")

> [!NOTE]
> Dans la version d'octobre 2018, vous pouvez accéder à tous les paramètres d'administration et les gérer à partir du plan de site du concentrateur de service client, sauf pour les **ensembles de règles d'acheminement**, la **création automatique d'enregistrements** et les **contrats de niveau de service**. Pour accéder et gérer ces trois paramètres d'administration, accédez à **Paramètres** > **Gestionnaire de services** dans l'application Web. </br>
> Ces trois paramètres d'administration (les ensembles de règles d'acheminement, la création automatique d'enregistrements et les contrats de niveau de service) seront disponibles dans le plan de site du concentrateur de service client à compter de la version de janvier 2019.

Vous pouvez personnaliser différentes fonctionnalités du Gestionnaire de services. Notamment :  

- **Files d'attente** : Les files d'attente du Gestionnaire de services ont été repensées, et aide à classer par priorité et à surveiller la progression des tâches attribuées.

  ![Utilisation des files d'attente dans le Gestionnaire de services](media/service-management-queues.png "Utilisation des files d'attente dans le Gestionnaire de services")

- **Sujets** : Les sujets sont un mécanisme puissant pour classer les incidents, les articles de la base de connaissances, les produits et la documentation commerciale, ce qui de ce fait responsabilise les agents et permet de répondre rapidement aux clients.  

  ![Utilisation des sujets dans le Gestionnaire de services](media/service-management-subjects.png "Utilisation des sujets dans le Gestionnaire de services")

- **Paramètres des incidents** : Avec les paramètres des incidents parents et enfants, les incidents peuvent être associés ensemble, ce qui permet d'offrir de meilleures réponses et un meilleur suivi des problèmes courants.  

- **Règles d'acheminement** : Les règles d'acheminement aident à acheminer automatiquement les incidents vers la file d'attente, l'utilisateur, ou l'équipe correcte sans intervention manuelle. 

- **Règles de mise à jour et de création d'enregistrements automatiques** : Ces règles autorisent la création ou la mise à jour automatique d'un incident ou d'un enregistrement associé basé sur des activités entrantes, comme un courrier électronique, l'activité sociale, ou d'autres catégories d'activités. 

- **Droit** : Les droits permettent de définir et de mesurer le support auquel un client est éligible. Il est possible de spécifier les conditions du support selon un nombre d'heures spécifique ou un certain nombre d'incidents. 

  ![Utilisation des droits](media/service-management-entitlements.png "Utilisation des droits")

- **Modèles de droit** : Les modèles de droit offrent une expérience de configuration rapide car ils fournissent les modèles réutilisables pour configurer des droits.  

- **Calendrier des jours non ouvrés** : La calendrier des jours non ouvrés permet de s'adapter aux fermetures afin que le contrat SLA ne soit pas impacté. 

  ![Planification des vacances](media/service-management-holiday-schedule.png "Planification des vacances")

- **Planification du service clientèle** : La planification du service clientèle peut être utilisée pour définir les heures de travail pour votre équipe.  

  ![Définition du calendrier de service clientèle](media/service-management-customer-service-schedule.png "Définition du calendrier de service clientèle")

- **Contrats de niveau de service** : Les contrats de niveau de service sont utilisés pour les contrats sur les jalons des tâches de service. Les contrats de niveau de service adhèrent aux configurations définies dans le calendrier des jours non ouvrés et le calendrier de service clientèle.  

- **Paramètres de gestion des connaissances** : Les paramètres de gestion des connaissances sont utilisés pour activer les entités pour la gestion des connaissances et les analyses de texte. 






