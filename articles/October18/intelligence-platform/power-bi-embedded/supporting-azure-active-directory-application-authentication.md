---
title: Prise en charge de l'authentification d'application Azure Active Directory
description: Prise en charge de l'authentification d'application Azure Active Directory
author: Annbe
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: cba1b690-0d07-4400-8bf6-80de880157ba
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: Annbe
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 3c644df8af2bbc07c910cc7dd6581d55fc95686e
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---
# <a name="azure-active-directory-application-authentication-public-preview"></a>Authentification d'application Azure Active Directory (version préliminaire publique)

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]




Nous ajoutons actuellement l'authentification d'application à Power BI Embedded. Cela permettra d'améliorer le déploiement, la sécurité et l'Application Lifecycle Management des applications Power BI Embedded. Actuellement, la création d'une application Power BI Embedded requiert la création d'un compte d'utilisateur principal, le stockage des informations d'identification de ce compte, puis l'utilisation de celles-ci dans le code d'application pour effectuer une connexion non-interactive à Power BI. Azure Active Directory offre une prise en charge spéciale de l'authentification des applications avec leur propre identité sans contexte d'utilisateur. Cette prise en charge, conçue pour l'authentification réservée aux applications, offre un contrôle et une sécurité supérieurs, implique moins de limitations et constitue l'approche recommandée. 

