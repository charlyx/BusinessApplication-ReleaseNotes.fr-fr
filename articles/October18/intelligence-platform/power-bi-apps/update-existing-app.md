---
title: "Mettre à jour une application Power BI existante dans AppSource"
description: "Mettre à jour une application Power BI existante dans AppSource"
author: ezaviv
manager: HaydnR
ms.date: 07/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: avive
audience: Admin, end user
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: a870e8f0d03f19cfd9ba3d93a7bcfce85524d332
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---
# <a name="update-an-existing-power-bi-app-in-appsource"></a>Mettre à jour une application Power BI existante dans AppSource

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



Application Lifecycle Management (ALM) comporte les fonctionnalités suivantes :

- Une application est basée sur un espace de travail Power BI avec des paramètres supplémentaires.
- Il existe trois niveaux de version pour une application : espace de travail (travaux en cours) --> package (version finale) --> application publiée (contenu disponible publiquement pour l'installation via AppSource).
- À chaque niveau de lancement, nous conservons une version unique : un espace de travail dans les travaux en cours, un package et une application publiée. Pour effectuer une mise à jour vers une application publiée, il vous suffit de déployer un package. Le déploiement d'un package remplace l'application publiée dans AppSource.
- La conception de l'application peut continuer à tout moment sur l'espace de travail des travaux en cours.
- Lorsque vous êtes prêt à créer une version finale, enregistrez le package.

