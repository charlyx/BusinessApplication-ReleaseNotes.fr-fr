---
title: Activer le vote pour des raisons de statut dans Dynamics 365 Portal
description: Activez le vote pour des raisons de statut dans votre portail.
author: neerajnandwana-ms
manager: ramalingamkrishnan
ms.date: 09/20/2018
ms.assetid: D81BD65F-E1D6-42CF-BF48-667DFA8A2852
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: nenandw
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 7e0954b5f4a23af4780aa48b1b609c68fc7ae6e3
ms.openlocfilehash: 4cc4cae09f6e22a6ec165d69a19c70777175b3ef
ms.contentlocale: fr-fr
ms.lasthandoff: 09/20/2018

---
# <a name="enable-voting-for-status-reasons"></a>Activer le vote pour des raisons de statut

[!include[dynamics365-portal banner](../../includes/dynamics365-portal.md)]

Actuellement, une idée est activée pour le vote uniquement lorsque la **Raison du statut** est définie sur **Nouveau**. Cette fonctionnalité vous permet d'activer le vote pour une idée pour différentes raisons du statut. Pour permettre le vote pour différentes raisons de statut, vous devez créer le paramètre de site **Ideas/EnableVotingForStatusReasons** et définir sa valeur sur les valeurs de raison de statut requises.
 
Par exemple, si vous souhaitez activer le vote pour les raisons de statut **Nouveau**, **Accepté**, et **Rejeté**. Vous devez créer le paramètre de site et définir sa valeur comme suit :

- **Nom** : Ideas/EnableVotingForStatusReasons

- **Valeur** : 1;100000000;100000002

Pour plus d'informations sur les validations et les étapes à suivre pour obtenir les valeurs de raison du statut, consultez la documentation détaillée : [Activer le vote pour des raisons de statut](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/portals/crowdsource-ideas#enable-voting-for-status-reasons)

<!--
### Who uses this feature
This feature is intended for customizers. A customizer can configure and decide the status reasons, where user can vote.
### License required
NA
### Setup required
No 
## Status
### Development status
Generally available
#### Target timeframe
October 2018
### Availability
Cloud
### Regional availability
This feature will be available globally. 
-->

