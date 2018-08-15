---
title: "Comprendre les paramètres d'administration de Customer Service dans Dynamics 365 for Customer Service"
description: "Découvrir les nouvelles fonctionnalités des paramètres d'administration pour Dynamics 365 for Customer Service"
author: vippand
manager: mahesh
ms.date: 7/22/2018
ms.assetid: 516afbde-61a3-4718-8ce1-a4007ada5960
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 6854d6a0ca5d97ae26bf8a522e2249a11a82716c
ms.contentlocale: fr-fr
ms.lasthandoff: 08/15/2018

---
#  <a name="customer-service-admin-settings"></a><span data-ttu-id="3c6df-103">Paramètres d'administration de Customer Service</span><span class="sxs-lookup"><span data-stu-id="3c6df-103">Customer Service admin settings</span></span> 

[!include[customer-service-core-release-notes banner](../../includes/customer-service-core-release-notes.md)]




<span data-ttu-id="3c6df-104">L'un des objectifs principaux des clients de Dynamics 365 est de déployer rapidement leurs processus d'entreprise.</span><span class="sxs-lookup"><span data-stu-id="3c6df-104">One of the key goals for Dynamics 365 customers is quick deployment of their business processes.</span></span> <span data-ttu-id="3c6df-105">Le module Gestionnaire de services aide les responsables du service clientèle à automatiser différents processus, à améliorer le temps de réponse des agents et à optimiser la satisfaction des clients.</span><span class="sxs-lookup"><span data-stu-id="3c6df-105">The Service Management module helps customer service managers automate various customer service processes, improve agent turn-around time, and lead toward optimum customer satisfaction.</span></span> <span data-ttu-id="3c6df-106">Le Gestionnaire de services permet de configurer et de gérer des tâches de service clientèle (comme configurer des files d'attente publiques ou privées, définir des paramètres d'incidents parent-enfant, configurer des règles d'acheminement, configurer des règles de mise à jour et de création d'enregistrements automatiques et configurer des accords de niveau de service (SLA), etc).</span><span class="sxs-lookup"><span data-stu-id="3c6df-106">Service Management provides an admin the ability to configure and manage customer service tasks such as configuring public or private queues, setting up parent-child case settings, configuring routing rules, configuring automatic record creation and update rules, and setting up service level agreements (SLAs), among other capabilities.</span></span>

<span data-ttu-id="3c6df-107">Avec la dernière version, le Gestionnaire de services passe sous le concentrateur du service client et permet aux responsables d'accéder aux fonctions à partir de l'application.</span><span class="sxs-lookup"><span data-stu-id="3c6df-107">With the latest release, Service Management moves under the Customer Service Hub, enabling customer service managers to access the configurations from inside the application.</span></span> <span data-ttu-id="3c6df-108">Le nouveau Gestionnaire de services repose sur Unified Interface et aide à configurer facilement les tâches, ce qui offre une meilleure productivité.</span><span class="sxs-lookup"><span data-stu-id="3c6df-108">Built on the Unified Interface, the new Service Management helps to easily configure service tasks, enabling increased productivity.</span></span> 

<span data-ttu-id="3c6df-109">Vous pouvez accéder au Gestionnaire de services via le plan de site dans le concentrateur du service client :</span><span class="sxs-lookup"><span data-stu-id="3c6df-109">You can access Service Management through the sitemap in the Customer Service Hub:</span></span> 

<span data-ttu-id="3c6df-110">![](media/csh-sitemap-service-management.png "Accès au Gestionnaire de services via le plan du site")</span><span class="sxs-lookup"><span data-stu-id="3c6df-110">![](media/csh-sitemap-service-management.png "Accessing Service Management through the sitemap")</span></span>

<span data-ttu-id="3c6df-111">Vous pouvez personnaliser différentes fonctionnalités du Gestionnaire de services.</span><span class="sxs-lookup"><span data-stu-id="3c6df-111">Within Service Management, you can customize various features.</span></span> <span data-ttu-id="3c6df-112">Notamment :</span><span class="sxs-lookup"><span data-stu-id="3c6df-112">These include:</span></span>  

- <span data-ttu-id="3c6df-113">**Files d'attente** : Les files d'attente du Gestionnaire de services ont été repensées, et aide à classer par priorité et à surveiller la progression des tâches attribuées.</span><span class="sxs-lookup"><span data-stu-id="3c6df-113">**Queues**: Queues in Service Management come with a redesigned experience that helps to appropriately prioritize and monitor the progress of the assigned work.</span></span>

  <span data-ttu-id="3c6df-114">![](media/service-management-queues.png "Utilisation des files d'attente dans le Gestionnaire de services")</span><span class="sxs-lookup"><span data-stu-id="3c6df-114">![](media/service-management-queues.png "Using queues in Service Management")</span></span>

- <span data-ttu-id="3c6df-115">**Sujets** : Les sujets sont un mécanisme puissant pour classer les incidents, les articles de la base de connaissances, les produits et la documentation commerciale, ce qui de ce fait responsabilise les agents et permet de répondre rapidement aux clients.</span><span class="sxs-lookup"><span data-stu-id="3c6df-115">**Subjects**: Subjects are a powerful mechanism to classify cases, knowledge base articles, products, and sales literature, thereby empowering agents and facilitating quick responses to customers.</span></span>  

  <span data-ttu-id="3c6df-116">![](media/service-management-subjects.png "Utilisation des sujets dans le Gestionnaire de services")</span><span class="sxs-lookup"><span data-stu-id="3c6df-116">![](media/service-management-subjects.png "Using subjects in Service Management")</span></span>

- <span data-ttu-id="3c6df-117">**Paramètres des incidents** : Avec les paramètres des incidents parents et enfants, les incidents peuvent être associés ensemble, ce qui permet d'offrir de meilleures réponses et un meilleur suivi des problèmes courants.</span><span class="sxs-lookup"><span data-stu-id="3c6df-117">**Case settings**: With the Parent-Child case settings, cases can be linked together, enabling better response and tracking for common issues.</span></span>  

- <span data-ttu-id="3c6df-118">**Règles d'acheminement** : Les règles d'acheminement aident à acheminer automatiquement les incidents vers la file d'attente, l'utilisateur, ou l'équipe correcte sans intervention manuelle.</span><span class="sxs-lookup"><span data-stu-id="3c6df-118">**Routing rules**: Routing rules help automatic routing of cases to the right queue, user, or team without any manual intervention.</span></span> 

- <span data-ttu-id="3c6df-119">**Règles de mise à jour et de création d'enregistrements automatiques** : Ces règles autorisent la création ou la mise à jour automatique d'un incident ou d'un enregistrement associé basé sur des activités entrantes, comme un courrier électronique, l'activité sociale, ou d'autres catégories d'activités.</span><span class="sxs-lookup"><span data-stu-id="3c6df-119">**Automatic record creation and update rules**: These rules allow automatic creation or update of a case or related record based on incoming activities like email, social activity, or other categories of activities.</span></span> 

- <span data-ttu-id="3c6df-120">**Droit** : Les droits permettent de définir et de mesurer le support auquel un client est éligible.</span><span class="sxs-lookup"><span data-stu-id="3c6df-120">**Entitlement**: Entitlements help define and quantify the support for which a customer is eligible.</span></span> <span data-ttu-id="3c6df-121">Il est possible de spécifier les conditions du support selon un nombre d'heures spécifique ou un certain nombre d'incidents.</span><span class="sxs-lookup"><span data-stu-id="3c6df-121">The support terms can be specified based on number of hours or number of cases.</span></span> 

  <span data-ttu-id="3c6df-122">![](media/service-management-entitlements.png "Utilisation des droits")</span><span class="sxs-lookup"><span data-stu-id="3c6df-122">![](media/service-management-entitlements.png "Using entitlements")</span></span>

- <span data-ttu-id="3c6df-123">**Modèles de droit** : Les modèles de droit offrent une expérience de configuration rapide car ils fournissent les modèles réutilisables pour configurer des droits.</span><span class="sxs-lookup"><span data-stu-id="3c6df-123">**Entitlement templates**: Entitlement templates enable a quick configuration experience by allowing reusable templates for setting up entitlements.</span></span>  

- <span data-ttu-id="3c6df-124">**Calendrier des jours non ouvrés** : La calendrier des jours non ouvrés permet de s'adapter aux fermetures afin que le contrat SLA ne soit pas impacté.</span><span class="sxs-lookup"><span data-stu-id="3c6df-124">**Holiday schedule**: Holiday schedule lets you accommodate holiday closures so that the SLA is not impacted.</span></span> 

  <span data-ttu-id="3c6df-125">![](media/service-management-holiday-schedule.png "Planification des vacances")</span><span class="sxs-lookup"><span data-stu-id="3c6df-125">![](media/service-management-holiday-schedule.png "Scheduling holidays")</span></span>

- <span data-ttu-id="3c6df-126">**Planification du service clientèle** : La planification du service clientèle peut être utilisée pour définir les heures de travail pour votre équipe.</span><span class="sxs-lookup"><span data-stu-id="3c6df-126">**Customer service schedule**: Customer service schedule can be used to define the business hours for your team.</span></span>  

  <span data-ttu-id="3c6df-127">![](media/service-management-customer-service-schedule.png "Définition du calendrier de service clientèle")</span><span class="sxs-lookup"><span data-stu-id="3c6df-127">![](media/service-management-customer-service-schedule.png "Setting customer service schedule")</span></span>

- <span data-ttu-id="3c6df-128">**Contrats de niveau de service** : Les contrats de niveau de service sont utilisés pour les contrats sur les jalons des tâches de service.</span><span class="sxs-lookup"><span data-stu-id="3c6df-128">**Service level agreements**: Service level agreements are used for agreement on milestones of the service tasks.</span></span> <span data-ttu-id="3c6df-129">Les contrats de niveau de service adhèrent aux configurations définies dans le calendrier des jours non ouvrés et le calendrier de service clientèle.</span><span class="sxs-lookup"><span data-stu-id="3c6df-129">Service level agreements adhere to the configurations defined in the holiday schedule and customer service schedule.</span></span>  

- <span data-ttu-id="3c6df-130">**Paramètres de gestion des connaissances** : Les paramètres de gestion des connaissances sont utilisés pour activer les entités pour la gestion des connaissances et les analyses de texte.</span><span class="sxs-lookup"><span data-stu-id="3c6df-130">**Knowledge management settings**: Knowledge management settings are used to enable entities for knowledge management and text analytics.</span></span> 






