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
ms.sourcegitcommit: b1a0f1e04786d2daef091fc6f6f9c168f2b005e7
ms.openlocfilehash: c1bd196d6aab4e5f130453c32f9e05ca7f757b32
ms.contentlocale: fr-fr
ms.lasthandoff: 09/25/2018

---
#  <a name="customer-service-admin-settings"></a><span data-ttu-id="afc86-103">Paramètres d'administration de Customer Service</span><span class="sxs-lookup"><span data-stu-id="afc86-103">Customer Service admin settings</span></span> 

[!include[customer-service-core-release-notes banner](../../includes/customer-service-core-release-notes.md)]

<span data-ttu-id="afc86-104">L'un des objectifs principaux des clients de Dynamics 365 est de déployer rapidement leurs processus d'entreprise.</span><span class="sxs-lookup"><span data-stu-id="afc86-104">One of the key goals for Dynamics 365 customers is quick deployment of their business processes.</span></span> <span data-ttu-id="afc86-105">Le module Gestionnaire de services aide les responsables du service clientèle à automatiser différents processus, à améliorer le temps de réponse des agents et à optimiser la satisfaction des clients.</span><span class="sxs-lookup"><span data-stu-id="afc86-105">The Service Management module helps customer service managers automate various customer service processes, improve agent turn-around time, and lead toward optimum customer satisfaction.</span></span> <span data-ttu-id="afc86-106">Le Gestionnaire de services permet de configurer et de gérer des tâches de service clientèle (comme configurer des files d'attente publiques ou privées, définir des paramètres d'incidents parent-enfant, configurer des règles d'acheminement, configurer des règles de mise à jour et de création d'enregistrements automatiques et configurer des accords de niveau de service (SLA), etc.).</span><span class="sxs-lookup"><span data-stu-id="afc86-106">Service Management provides an admin the ability to configure and manage customer service tasks such as configuring public or private queues, setting up parent-child case settings, configuring routing rules, configuring automatic record creation and update rules, and setting up service level agreements (SLAs), among other capabilities.</span></span>

<span data-ttu-id="afc86-107">Avec la dernière version, le Gestionnaire de services passe sous le concentrateur du service client et permet aux responsables d'accéder aux fonctions à partir de l'application.</span><span class="sxs-lookup"><span data-stu-id="afc86-107">With the latest release, Service Management moves under the Customer Service Hub, enabling customer service managers to access the configurations from inside the application.</span></span> <span data-ttu-id="afc86-108">Le nouveau Gestionnaire de services repose sur Unified Interface et aide à configurer facilement les tâches, ce qui offre une meilleure productivité.</span><span class="sxs-lookup"><span data-stu-id="afc86-108">Built on the Unified Interface, the new Service Management helps to easily configure service tasks, enabling increased productivity.</span></span> 

<span data-ttu-id="afc86-109">Vous pouvez accéder au Gestionnaire de services via le plan de site dans le concentrateur du service client :</span><span class="sxs-lookup"><span data-stu-id="afc86-109">You can access Service Management through the sitemap in the Customer Service Hub:</span></span> 

<span data-ttu-id="afc86-110">![Accès au Gestionnaire de services via le plan du site](media/csh-sitemap-service-management.png "Accès au Gestionnaire de services via le plan du site")</span><span class="sxs-lookup"><span data-stu-id="afc86-110">![Accessing Service Management through the sitemap](media/csh-sitemap-service-management.png "Accessing Service Management through the sitemap")</span></span>

> [!NOTE]
> <span data-ttu-id="afc86-111">Dans la version d'octobre 2018, vous pouvez accéder à tous les paramètres d'administration et les gérer à partir du plan de site du concentrateur de service client, sauf pour les **ensembles de règles d'acheminement**, la **création automatique d'enregistrements** et les **contrats de niveau de service**.</span><span class="sxs-lookup"><span data-stu-id="afc86-111">With the October '18 release, you can access and manage all admin settings from the Customer Service Hub sitemap except for **Routing Rule sets**, **Automatic Record Creation**, and **Service Level Agreements**.</span></span> <span data-ttu-id="afc86-112">Pour accéder et gérer ces trois paramètres d'administration, accédez à **Paramètres** > **Gestionnaire de services** dans l'application Web.</span><span class="sxs-lookup"><span data-stu-id="afc86-112">To access and manage these three admin settings, go to **Settings** > **Service Management** in the web application.</span></span> </br>
> <span data-ttu-id="afc86-113">Ces trois paramètres d'administration (les ensembles de règles d'acheminement, la création automatique d'enregistrements et les contrats de niveau de service) seront disponibles dans le plan de site du concentrateur de service client à compter de la version de janvier 2019.</span><span class="sxs-lookup"><span data-stu-id="afc86-113">These three admin settings (Routing Rule sets, Automatic Record Creation, and Service Level Agreements) will be available in the Customer Service Hub sitemap beginning with the January '19 release.</span></span>

<span data-ttu-id="afc86-114">Vous pouvez personnaliser différentes fonctionnalités du Gestionnaire de services.</span><span class="sxs-lookup"><span data-stu-id="afc86-114">Within Service Management, you can customize various features.</span></span> <span data-ttu-id="afc86-115">Notamment :</span><span class="sxs-lookup"><span data-stu-id="afc86-115">These include:</span></span>  

- <span data-ttu-id="afc86-116">**Files d'attente** : Les files d'attente du Gestionnaire de services ont été repensées, et aide à classer par priorité et à surveiller la progression des tâches attribuées.</span><span class="sxs-lookup"><span data-stu-id="afc86-116">**Queues**: Queues in Service Management come with a redesigned experience that helps to appropriately prioritize and monitor the progress of the assigned work.</span></span>

  <span data-ttu-id="afc86-117">![Utilisation des files d'attente dans le Gestionnaire de services](media/service-management-queues.png "Utilisation des files d'attente dans le Gestionnaire de services")</span><span class="sxs-lookup"><span data-stu-id="afc86-117">![Using queues in Service Management](media/service-management-queues.png "Using queues in Service Management")</span></span>

- <span data-ttu-id="afc86-118">**Sujets** : Les sujets sont un mécanisme puissant pour classer les incidents, les articles de la base de connaissances, les produits et la documentation commerciale, ce qui de ce fait responsabilise les agents et permet de répondre rapidement aux clients.</span><span class="sxs-lookup"><span data-stu-id="afc86-118">**Subjects**: Subjects are a powerful mechanism to classify cases, knowledge base articles, products, and sales literature, thereby empowering agents and facilitating quick responses to customers.</span></span>  

  <span data-ttu-id="afc86-119">![Utilisation des sujets dans le Gestionnaire de services](media/service-management-subjects.png "Utilisation des sujets dans le Gestionnaire de services")</span><span class="sxs-lookup"><span data-stu-id="afc86-119">![Using subjects in Service Management](media/service-management-subjects.png "Using subjects in Service Management")</span></span>

- <span data-ttu-id="afc86-120">**Paramètres des incidents** : Avec les paramètres des incidents parents et enfants, les incidents peuvent être associés ensemble, ce qui permet d'offrir de meilleures réponses et un meilleur suivi des problèmes courants.</span><span class="sxs-lookup"><span data-stu-id="afc86-120">**Case settings**: With the Parent-Child case settings, cases can be linked together, enabling better response and tracking for common issues.</span></span>  

- <span data-ttu-id="afc86-121">**Règles d'acheminement** : Les règles d'acheminement aident à acheminer automatiquement les incidents vers la file d'attente, l'utilisateur, ou l'équipe correcte sans intervention manuelle.</span><span class="sxs-lookup"><span data-stu-id="afc86-121">**Routing rules**: Routing rules help automatic routing of cases to the right queue, user, or team without any manual intervention.</span></span> 

- <span data-ttu-id="afc86-122">**Règles de mise à jour et de création d'enregistrements automatiques** : Ces règles autorisent la création ou la mise à jour automatique d'un incident ou d'un enregistrement associé basé sur des activités entrantes, comme un courrier électronique, l'activité sociale, ou d'autres catégories d'activités.</span><span class="sxs-lookup"><span data-stu-id="afc86-122">**Automatic record creation and update rules**: These rules allow automatic creation or update of a case or related record based on incoming activities like email, social activity, or other categories of activities.</span></span> 

- <span data-ttu-id="afc86-123">**Droit** : Les droits permettent de définir et de mesurer le support auquel un client est éligible.</span><span class="sxs-lookup"><span data-stu-id="afc86-123">**Entitlement**: Entitlements help define and quantify the support for which a customer is eligible.</span></span> <span data-ttu-id="afc86-124">Il est possible de spécifier les conditions du support selon un nombre d'heures spécifique ou un certain nombre d'incidents.</span><span class="sxs-lookup"><span data-stu-id="afc86-124">The support terms can be specified based on number of hours or number of cases.</span></span> 

  <span data-ttu-id="afc86-125">![Utilisation des droits](media/service-management-entitlements.png "Utilisation des droits")</span><span class="sxs-lookup"><span data-stu-id="afc86-125">![Using entitlements](media/service-management-entitlements.png "Using entitlements")</span></span>

- <span data-ttu-id="afc86-126">**Modèles de droit** : Les modèles de droit offrent une expérience de configuration rapide car ils fournissent les modèles réutilisables pour configurer des droits.</span><span class="sxs-lookup"><span data-stu-id="afc86-126">**Entitlement templates**: Entitlement templates enable a quick configuration experience by allowing reusable templates for setting up entitlements.</span></span>  

- <span data-ttu-id="afc86-127">**Calendrier des jours non ouvrés** : La calendrier des jours non ouvrés permet de s'adapter aux fermetures afin que le contrat SLA ne soit pas impacté.</span><span class="sxs-lookup"><span data-stu-id="afc86-127">**Holiday schedule**: Holiday schedule lets you accommodate holiday closures so that the SLA is not impacted.</span></span> 

  <span data-ttu-id="afc86-128">![Planification des vacances](media/service-management-holiday-schedule.png "Planification des vacances")</span><span class="sxs-lookup"><span data-stu-id="afc86-128">![Scheduling holidays](media/service-management-holiday-schedule.png "Scheduling holidays")</span></span>

- <span data-ttu-id="afc86-129">**Planification du service clientèle** : La planification du service clientèle peut être utilisée pour définir les heures de travail pour votre équipe.</span><span class="sxs-lookup"><span data-stu-id="afc86-129">**Customer service schedule**: Customer service schedule can be used to define the business hours for your team.</span></span>  

  <span data-ttu-id="afc86-130">![Définition du calendrier de service clientèle](media/service-management-customer-service-schedule.png "Définition du calendrier de service clientèle")</span><span class="sxs-lookup"><span data-stu-id="afc86-130">![Setting customer service schedule](media/service-management-customer-service-schedule.png "Setting customer service schedule")</span></span>

- <span data-ttu-id="afc86-131">**Contrats de niveau de service** : Les contrats de niveau de service sont utilisés pour les contrats sur les jalons des tâches de service.</span><span class="sxs-lookup"><span data-stu-id="afc86-131">**Service level agreements**: Service level agreements are used for agreement on milestones of the service tasks.</span></span> <span data-ttu-id="afc86-132">Les contrats de niveau de service adhèrent aux configurations définies dans le calendrier des jours non ouvrés et le calendrier de service clientèle.</span><span class="sxs-lookup"><span data-stu-id="afc86-132">Service level agreements adhere to the configurations defined in the holiday schedule and customer service schedule.</span></span>  

- <span data-ttu-id="afc86-133">**Paramètres de gestion des connaissances** : Les paramètres de gestion des connaissances sont utilisés pour activer les entités pour la gestion des connaissances et les analyses de texte.</span><span class="sxs-lookup"><span data-stu-id="afc86-133">**Knowledge management settings**: Knowledge management settings are used to enable entities for knowledge management and text analytics.</span></span> 






