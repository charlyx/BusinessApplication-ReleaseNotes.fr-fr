---
title: "Fonctionnalité de déclaration de TVA pour les Émirats arabes unis."
description: "Fonctionnalité de déclaration de TVA pour les Émirats arabes unis."
author: AdamTrukawka
manager: AnnBe
ms.date: 07/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: atrukawk
audience: end-user
ms.translationtype: HT
ms.sourcegitcommit: 7d6f339c1e92c937c47306db6da360eb8fdd5d77
ms.openlocfilehash: 8c7a861abccfc1aa959a4eaa2244148022ed6fb6
ms.contentlocale: fr-fr
ms.lasthandoff: 08/16/2018

---

# <a name="vat-reporting-functionality-for-united-arab-emirates"></a><span data-ttu-id="5e7d3-103">Fonctionnalité de déclaration de TVA pour les Émirats arabes unis.</span><span class="sxs-lookup"><span data-stu-id="5e7d3-103">VAT reporting functionality for United Arab Emirates</span></span>

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="5e7d3-104">La taxe sur la valeur ajoutée (TVA) a été introduite aux Emirats arabes unis le 1er janvier 2018.</span><span class="sxs-lookup"><span data-stu-id="5e7d3-104">Value added tax (VAT) was introduced in the United Arab Emirates on January 1, 2018.</span></span> <span data-ttu-id="5e7d3-105">La loi d'arrêté fédéral publiée</span><span class="sxs-lookup"><span data-stu-id="5e7d3-105">The issued Federal Decree Law No.</span></span> <span data-ttu-id="5e7d3-106">n° (8) de 2017 sur la taxe sur la valeur ajoutée décrit la zone de taxe, le taux, la responsabilité de la taxe et la fourniture de biens et services dans tous les cas.</span><span class="sxs-lookup"><span data-stu-id="5e7d3-106">(8) of 2017 on Value Added Tax outlines the tax scope, rate, responsibility for tax, and supply of goods and services in all cases.</span></span> <span data-ttu-id="5e7d3-107">Pour plus d'informations sur les réglementations régissant la TVA, voir les [Autorités fiscales fédérales des Émirats arabes unis](https://government.ae/en/information-and-services/finance-and-investment/taxation/valueaddedtaxvat).</span><span class="sxs-lookup"><span data-stu-id="5e7d3-107">For more details on VAT regulations, see [Federal Tax Authorities of United Arab Emirates](https://government.ae/en/information-and-services/finance-and-investment/taxation/valueaddedtaxvat).</span></span>

<span data-ttu-id="5e7d3-108">Les clients utilisant la version d'octobre 2018 de Microsoft Dynamics 365 for Finance and Operations pourront configurer l'entité juridique des EAU avec une fonctionnalité spécifique au pays liée à la déclaration de la TVA dans le pays.</span><span class="sxs-lookup"><span data-stu-id="5e7d3-108">Customers using the October '18 release of Microsoft Dynamics 365 for Finance and Operations will be able to configure the UAE legal entity with country-specific functionality related to VAT reporting in the country.</span></span>

<span data-ttu-id="5e7d3-109">Les améliorations spécifiques au pays suivantes ont été apportées à l'emplacement des EAU pour s'aligner sur les exigences en matière de déclaration de la TVA :</span><span class="sxs-lookup"><span data-stu-id="5e7d3-109">The following country-specific enhancements have been added to UAE localization to align with the requirements of VAT reporting:</span></span>

- <span data-ttu-id="5e7d3-110">La configuration de l'entité juridique a été étendue avec des champs supplémentaires requis dans les déclarations de TVA.</span><span class="sxs-lookup"><span data-stu-id="5e7d3-110">Legal entity configuration has been extended with additional fields required in VAT reports.</span></span>
- <span data-ttu-id="5e7d3-111">La fonctionnalité de contrepassation de TVA a été activée conformément au cadre des pays ARE pour enregistrer correctement les opérations locales imposables sur le secteur GCC.</span><span class="sxs-lookup"><span data-stu-id="5e7d3-111">VAT reverse charge functionality has been enabled for ARE country context to properly record taxable domestic operations within GCC territory.</span></span>
- <span data-ttu-id="5e7d3-112">Les dispositions d'impression des factures client et des avoirs spécifiques au pays ont été ajoutées avec des colonnes supplémentaires et des informations récapitulatives sur la TVA.</span><span class="sxs-lookup"><span data-stu-id="5e7d3-112">UAE country-specific sales invoice and credit notes printout layouts have been added with additional columns and VAT summary information.</span></span>
- <span data-ttu-id="5e7d3-113">Les factures client et les avoirs pour les EAU s'impriment dans deux langues, notamment l'arabe ar-AE et la langue de l'interface utilisateur.</span><span class="sxs-lookup"><span data-stu-id="5e7d3-113">Sales invoice and credit notes for UAE are printing in two languages, including ar-AE Arabic and user interface language.</span></span>
- <span data-ttu-id="5e7d3-114">Le rapport de déclaration de retour de TVA est imprimé à un format de fichier électronique prêt à être téléchargé sur le portail FTA e-TAX.</span><span class="sxs-lookup"><span data-stu-id="5e7d3-114">VAT return declaration report is printed to electronic file format ready for uploading to the e-TAX FTA portal.</span></span>
- <span data-ttu-id="5e7d3-115">La fonctionnalité de fichier d'audit standard a été partagée avec la fonctionnalité locale des EAU.</span><span class="sxs-lookup"><span data-stu-id="5e7d3-115">Standard audit file functionality has been shared with UAE local functionality.</span></span> <span data-ttu-id="5e7d3-116">Exigé par les Autorités fiscales fédérales, le fichier d'audit de TVA FTA (FAF) peut ensuite être exporté au format CSV requis.</span><span class="sxs-lookup"><span data-stu-id="5e7d3-116">Required by Federal Tax Authorities, FTA VAT audit file (FAF) can be exported accordingly to required CSV format.</span></span>

<span data-ttu-id="5e7d3-117">Toutes les sociétés des EAU sont responsables de documenter soigneusement leurs revenus commerciaux, coûts et frais de TVA associés, et d'envoyer des déclarations de TVA régulières aux autorités fiscales fédérales.</span><span class="sxs-lookup"><span data-stu-id="5e7d3-117">All companies in UAE are responsible for carefully documenting their business income, costs, and associated VAT charges and sending regular VAT reports to federal tax authorities.</span></span> <span data-ttu-id="5e7d3-118">La fonctionnalité de déclaration de TVA sera adoptée par tous les clients de Dynamics 365 for Finance and Operations.</span><span class="sxs-lookup"><span data-stu-id="5e7d3-118">The VAT reporting functionality will be adopted by all customers of Dynamics 365 for Finance and Operations.</span></span>


