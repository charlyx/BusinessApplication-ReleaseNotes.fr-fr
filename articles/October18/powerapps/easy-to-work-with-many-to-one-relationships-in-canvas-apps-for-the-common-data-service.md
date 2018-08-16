---
title: "Utilisation simple des relations plusieurs-à-une dans des applications de canevas pour Common Data Service pour les applications"
description: "Plus besoin d'associer ou d'effectuer des recherches manuellement. PowerApps développe automatiquement les relations plusieurs-à-une, ainsi les informations sont à portée de main."
author: gregli-msft
manager: AnnBe
ms.date: 8/10/2018
ms.assetid: 421c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: b6df0f68e3460358864533346e69a712684da551
ms.openlocfilehash: e930566a1ea39365f2ba2ab649585879eb7b5cd8
ms.contentlocale: fr-fr
ms.lasthandoff: 08/16/2018

---
# <a name="easy-to-work-with-many-to-one-relationships-in-canvas-apps-for-common-data-service-for-apps"></a><span data-ttu-id="7604b-104">Utilisation simple des relations plusieurs-à-une dans des applications de canevas pour Common Data Service pour les applications</span><span class="sxs-lookup"><span data-stu-id="7604b-104">Easy to work with many-to-one relationships in canvas apps for Common Data Service for Apps</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="7604b-105">L'utilisation des données relationnelles est essentielle pour de nombreuses applications de gestion.</span><span class="sxs-lookup"><span data-stu-id="7604b-105">Working with relational data is key to most business applications.</span></span> <span data-ttu-id="7604b-106">Il peut en effet être fastidieux d'écrire des requêtes pour récupérer les informations requises, joindre des clés étrangères, et contrôler la prévision.</span><span class="sxs-lookup"><span data-stu-id="7604b-106">Yet it can be tedious to write queries that pull in the necessary information, join on foreign keys, and control the projection.</span></span>

<span data-ttu-id="7604b-107">Avec cette fonctionnalité, tout devient plus facile pour les créateurs d'application de canevas lorsqu'ils utilisent Common Data Service pour les applications.</span><span class="sxs-lookup"><span data-stu-id="7604b-107">With this feature, it all becomes a lot easier for canvas app makers when they use Common Data Service for Apps.</span></span> <span data-ttu-id="7604b-108">Par exemple, dans le modèle standard CDS pour les applications, il existe une entité Compte avec un champ de recherche pour PrimaryContact qui pointe vers l'entité Contacts.</span><span class="sxs-lookup"><span data-stu-id="7604b-108">For example, in the CDS for Apps standard model, there is an Account entity with a lookup for PrimaryContact that points to the Contacts entity.</span></span> <span data-ttu-id="7604b-109">Imaginons que vous ayez besoin d'afficher le nom du contact principal dans un contrôle de galerie.</span><span class="sxs-lookup"><span data-stu-id="7604b-109">Let's say you need to display the last name of the primary contact in a gallery control.</span></span> <span data-ttu-id="7604b-110">Tout ce que vous devez entrer c'est **ThisItem.PrimaryContact.LastName**.</span><span class="sxs-lookup"><span data-stu-id="7604b-110">All you need to write is **ThisItem.PrimaryContact.LastName**.</span></span> <span data-ttu-id="7604b-111">La source de données Contacts n'a même pas besoin d'être chargée.</span><span class="sxs-lookup"><span data-stu-id="7604b-111">The Contacts data source doesn't even need to be loaded.</span></span> <span data-ttu-id="7604b-112">PowerApps analyse l'application pour déterminer les informations souhaitées et importer uniquement les champs requis pour la prévision.</span><span class="sxs-lookup"><span data-stu-id="7604b-112">PowerApps analyzes the app to determine which lookups are desired and to bring in only the fields that are required for the projection.</span></span>

