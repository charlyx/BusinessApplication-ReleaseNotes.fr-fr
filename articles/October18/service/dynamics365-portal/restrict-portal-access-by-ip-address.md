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
# <a name="restrict-portal-access-by-ip-address"></a><span data-ttu-id="40bc6-103">Restreindre l'accès au portail selon l'adresse IP</span><span class="sxs-lookup"><span data-stu-id="40bc6-103">Restrict portal access by IP address</span></span>

[!include[banner](../../../includes/banner.md)]


<span data-ttu-id="40bc6-104">La sécurité est l'une des préoccupations principales pour les applications et devient primordiale pour une application externe comme le portail Dynamics 365.</span><span class="sxs-lookup"><span data-stu-id="40bc6-104">Security is a key concern for applications and it becomes more paramount for an external-facing application like Dynamics 365 Portal.</span></span> <span data-ttu-id="40bc6-105">Dans le cadre de cette version, nous allons ajouter des fonctionnalités permettant aux clients de limiter l'accès à leurs portails à certaines adresses IP.</span><span class="sxs-lookup"><span data-stu-id="40bc6-105">As part of this release, we will add capabilities for customers to be able to restrict access to their portals from certain IP addresses.</span></span> <span data-ttu-id="40bc6-106">Cela aidera les organisations souhaitant restreindre leurs portails à des emplacements fixes tels que les réseaux internes de l'entreprise.</span><span class="sxs-lookup"><span data-stu-id="40bc6-106">This will help organizations that are looking to restrict their portals from fixed locations like internal company networks.</span></span> <span data-ttu-id="40bc6-107">En outre, ceci permettra aux clients en phase de développement et souhaitant s'assurer que leurs données ne sont pas divulguées en raison d'une configuration incorrecte.</span><span class="sxs-lookup"><span data-stu-id="40bc6-107">Also, this will help customers who are in a development phase and want to make sure their data doesn't get leaked because of a bad configuration.</span></span>

<span data-ttu-id="40bc6-108">Cette fonctionnalité permet aux administrateurs de définir une liste d'adresses IP autorisées à accéder à votre portail.</span><span class="sxs-lookup"><span data-stu-id="40bc6-108">This feature would allow administrators to define a list of IP addresses that are allowed to access your portal.</span></span> <span data-ttu-id="40bc6-109">La liste verte peut inclure des adresses IP individuelles ou une plage d'adresses IP définies par un masque de sous-réseau.</span><span class="sxs-lookup"><span data-stu-id="40bc6-109">The allow list can include individual IP addresses or a range of IP addresses defined by a subnet mask.</span></span> <span data-ttu-id="40bc6-110">Si une demande envoyées au portail provient de n'importe quel utilisateur, l'adresse IP de celui-ci est compare à la liste verte.</span><span class="sxs-lookup"><span data-stu-id="40bc6-110">When a request to the portal is generated from any user, their IP address is evaluated against the allow list.</span></span> <span data-ttu-id="40bc6-111">Si l'adresse IP ne figure pas dans la liste, le portail répond par un code statut HTTP 403.</span><span class="sxs-lookup"><span data-stu-id="40bc6-111">If the IP address is not in the list, the portal replies with an HTTP 403 status code.</span></span>

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

