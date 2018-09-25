---
title: "Découvrir le fonctionnement de la fonctionnalité Suggérer des incidents similaires dans Dynamics 365 for Customer Service"
description: "Voir comment les informations intelligentes sur des cas similaires permettent aux organisation de service clientèle d'offrir à leurs agents des connaissances et des compétences"
author: vippand
manager: mahesh
ms.date: 7/22/2018
ms.assetid: 0ce32dcb-9752-4e81-be03-7406bba91057
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: Annbe
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: b1a0f1e04786d2daef091fc6f6f9c168f2b005e7
ms.openlocfilehash: 47e3e08ea8c4f6474d6b87a933b8bfc69404d70f
ms.contentlocale: fr-fr
ms.lasthandoff: 09/25/2018

---

#  <a name="suggest-similar-cases"></a><span data-ttu-id="5e438-103">Suggérer des incidents similaires</span><span class="sxs-lookup"><span data-stu-id="5e438-103">Suggest similar cases</span></span>  

[!include[customer-service-core-release-notes banner](../../includes/customer-service-core-release-notes.md)]



<span data-ttu-id="5e438-104">La résolution d'un problème de service clientèle au cours du premier contact et dans un délai minimal aide les organisations à obtenir une meilleure satisfaction client (CSAT) et des coûts d'opérations réduits.</span><span class="sxs-lookup"><span data-stu-id="5e438-104">Resolving a customer service issue during the first contact and within minimal time helps organizations with increased customer satisfaction (CSAT) and reduced operations cost.</span></span>  <span data-ttu-id="5e438-105">Généralement, dans une organisation de service clientèle, les agents du service clientèle expérimentés ou les experts spécialisés résolvent les problèmes plus rapidement en fonction des connaissances ou de l'expérience acquise pendant une période de résolution de problèmes similaires.</span><span class="sxs-lookup"><span data-stu-id="5e438-105">Typically, in a customer service organization, experienced customer service agents or subject matter experts (SMEs) resolve issues faster based on knowledge or experience gained over a period of resolving similar issues.</span></span> <span data-ttu-id="5e438-106">Si des agents traitent un incident étranger à leurs domaines de compétences, le transfert de l'incident à un agent spécialisé ou la consultation d'un expert spécialisé améliore l'effort client et le délai de traitement des appels, ce qui se traduit par une meilleure CSAT.</span><span class="sxs-lookup"><span data-stu-id="5e438-106">If agents get a case outside their areas of expertise, transferring the case to an expert agent or consulting an SME leads to increased customer effort and call handling time, resulting in reduced CSAT.</span></span>  

<span data-ttu-id="5e438-107">Les informations intelligentes sur des incidents similaires permettent aux organisations de service clientèle d'offrir à leurs agents des connaissances et des compétences qui étaient autrement disponibles uniquement avec des agents expérimentés.</span><span class="sxs-lookup"><span data-stu-id="5e438-107">Intelligent insights on similar cases help customer service organizations empower agents with knowledge and expertise that was otherwise available only with experienced agents.</span></span>  <span data-ttu-id="5e438-108">Les suggestions sur des incidents similaires permettent de tirer parti des étapes de résolution dans l'organisation, ce qui rend un agent inexpérimenté aussi productif qu'un agent expérimenté.</span><span class="sxs-lookup"><span data-stu-id="5e438-108">Suggestions on similar cases help in leveraging resolution steps across the organization, thus making an inexperienced agent as productive as an experienced one.</span></span>  

<span data-ttu-id="5e438-109">Cette fonctionnalité s'appuie sur des [API Analyse de texte Microsoft](https://azure.microsoft.com/en-in/services/cognitive-services/text-analytics/) et des informations d'incident issues de différents enregistrements d'entité afin de suggérer des incidents similaires.</span><span class="sxs-lookup"><span data-stu-id="5e438-109">This feature leverages [Microsoft Text Analytics APIs](https://azure.microsoft.com/en-in/services/cognitive-services/text-analytics/) and case information across different entity records to suggest similar cases.</span></span> <span data-ttu-id="5e438-110">Cela permet une résolution d'incident plus rapide et plus efficace, ce qui entraîne une durée moyenne de traitement réduite et une expérience client améliorée.</span><span class="sxs-lookup"><span data-stu-id="5e438-110">This enables faster and better case resolution, resulting in reduced average handling time (AHT) and improved customer experience.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="5e438-111">![](media/similar-cases.png "Exemples d'incidents similaires")</span><span class="sxs-lookup"><span data-stu-id="5e438-111">![](media/similar-cases.png "Example of similar cases")</span></span>

