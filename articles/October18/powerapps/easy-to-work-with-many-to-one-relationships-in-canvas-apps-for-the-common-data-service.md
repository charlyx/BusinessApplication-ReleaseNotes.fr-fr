---
title: "Utilisation simple des relations plusieurs-à-une dans des applications de canevas pour Common Data Service pour les applications"
description: "Plus besoin d'associer ou d'effectuer des recherches manuellement. PowerApps développe automatiquement les relations plusieurs-à-une, ainsi les informations sont à portée de main."
author: gregli
manager: AnnBe
ms.date: 7/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 12b5d7ce158263a16f558e96e9cbe3c7dc4f43a6
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---
# <a name="easy-to-work-with-many-to-one-relationships-in-canvas-apps-for-common-data-service-for-apps"></a>Utilisation simple des relations plusieurs-à-une dans des applications de canevas pour Common Data Service pour les applications

[!include[powerapps banner](../includes/powerapps.md)]




L'utilisation des données relationnelles est essentielle pour de nombreuses applications de gestion. Il peut en effet être fastidieux d'écrire des requêtes pour récupérer les informations requises, joindre des clés étrangères, et contrôler la prévision.

Avec cette fonctionnalité, tout devient plus facile pour les créateurs d'application de canevas lorsqu'ils utilisent Common Data Service pour les applications. Par exemple, dans le modèle standard CDS pour les applications, il existe une entité Compte avec un champ de recherche pour PrimaryContact qui pointe vers l'entité Contacts. Imaginons que vous ayez besoin d'afficher le nom du contact principal dans un contrôle de galerie. Tout ce que vous devez entrer c'est **ThisItem.PrimaryContact.LastName**. La source de données Contacts n'a même pas besoin d'être chargée. PowerApps analyse l'application pour déterminer les informations souhaitées et importer uniquement les champs requis pour la prévision.

