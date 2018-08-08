---
title: Authentification unique pour Azure SQL Database
description: Authentification unique pour Azure SQL Database
author: MargoC
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: defe56c9-38a5-48c6-ba86-e1c6371bfb75
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 4e774f63cd021959f0fe95f44598a2d937ada967
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---
#  <a name="power-bi-embedded-single-sign-on-for-azure-sql-database"></a>Authentification unique Power BI Embedded pour Azure SQL Database


[!include[banner](../../../includes/banner.md)]

Cela permet à Power BI Embedded de respecter les paramètres de sécurité configurés au niveau de la source de données. Power BI Embedded n'a aucune connaissance de l'utilisateur de l'application. Pour les applications souhaitant définir une sécurité au niveau de la ligne dans Azure SQL Database, il est nécessaire de transférer les informations d'utilisateur de l'application à SQL Database. En activant l'option d'authentification unique, Power BI Embedded envoie les informations d'identification Azure Active Directory authentifiées pour les utilisateurs accédant à des rapports dans les requêtes à Azure SQL Database. 

