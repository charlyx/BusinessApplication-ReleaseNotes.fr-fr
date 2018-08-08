---
title: "Restreindre l'accès au portail selon l'adresse IP"
description: "Restreindre l'accès au portail uniquement à un sous-ensemble d'utilisateurs en définissant des plages d'adresses IP autorisées"
author: dileeps
manager: prvenka
ms.date: 07/22/2018
ms.assetid: 143d1e32-f70e-478c-b8c1-d25b37782653
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: dileeps
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 8259579ac1b19d93a71a9bc7db8ae07fb3c6a5cb
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---
# <a name="restrict-portal-access-by-ip-address"></a>Restreindre l'accès au portail selon l'adresse IP

[!include[banner](../../../includes/banner.md)]


La sécurité est l'une des préoccupations principales pour les applications et devient primordiale pour une application externe comme le portail Dynamics 365. Dans le cadre de cette version, nous allons ajouter des fonctionnalités permettant aux clients de limiter l'accès à leurs portails à certaines adresses IP. Cela aidera les organisations souhaitant restreindre leurs portails à des emplacements fixes tels que les réseaux internes de l'entreprise. En outre, ceci permettra aux clients en phase de développement et souhaitant s'assurer que leurs données ne sont pas divulguées en raison d'une configuration incorrecte.

Cette fonctionnalité permet aux administrateurs de définir une liste d'adresses IP autorisées à accéder à votre portail. La liste verte peut inclure des adresses IP individuelles ou une plage d'adresses IP définies par un masque de sous-réseau. Si une demande envoyées au portail provient de n'importe quel utilisateur, l'adresse IP de celui-ci est compare à la liste verte. Si l'adresse IP ne figure pas dans la liste, le portail répond par un code statut HTTP 403.

<!--
### Who uses this feature
This feature is intended for administrators who are managing portals.
## Status
### Development status
Generally available
#### Target timeframe
October 2018
### Availability 
Cloud
### Regional availability
Global
-->

