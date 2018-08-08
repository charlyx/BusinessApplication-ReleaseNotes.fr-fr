---
title: "Connectivité hybride de niveau professionnel via la passerelle de données sur site"
description: "Connectivité hybride de qualité professionnelle via la passerelle de données sur site"
author: MargoC
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 5b0c45ea-97e4-4e6f-8555-f2bc05ccb336
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: e4d721713b70d0a9cfeb06d0f795f23d3f0223a5
ms.openlocfilehash: bfe4ab5339acfa70c55d7cf0d2357fc95c47c4de
ms.contentlocale: fr-fr
ms.lasthandoff: 07/27/2018

---
#  <a name="enterprise-grade-hybrid-connectivity-using-the-on-premises-data-gateway"></a><span data-ttu-id="8a593-103">Connectivité hybride de niveau professionnel via la passerelle de données sur site</span><span class="sxs-lookup"><span data-stu-id="8a593-103">Enterprise-grade hybrid connectivity using the on-premises data gateway</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="8a593-104">Cette version comprend plusieurs mises à jour visant à amélioration la passerelle de données sur site.</span><span class="sxs-lookup"><span data-stu-id="8a593-104">This release includes multiple updates around improving the on-premises data gateway.</span></span>

## <a name="certified-custom-connectors-in-power-bi-desktop"></a><span data-ttu-id="8a593-105">Connecteurs personnalisés certifiés dans Power BI Desktop</span><span class="sxs-lookup"><span data-stu-id="8a593-105">Certified custom connectors in Power BI Desktop</span></span>

<span data-ttu-id="8a593-106">En début d'année, nous avons annoncé la prise en charge de connecteurs personnalisés dans Power BI Desktop, en utilisant des fonctionnalités puissantes de langage M permettant aux partenaires d'écrire leurs propres connecteurs et de les distribuer à chaque utilisateur Power BI.</span><span class="sxs-lookup"><span data-stu-id="8a593-106">Earlier this year, we announced support for custom connectors in Power BI Desktop, leveraging the powerful capabilities of the M language allowing partners to write their own connectors and distribute them to every Power BI user.</span></span>

<span data-ttu-id="8a593-107">La prise en charge des connecteurs personnalisés dans la passerelle permet aux utilisateurs d'avoir leurs états générés avec des connecteurs personnalisés tenus à jour dans le service Power BI en actualisant les données via la passerelle de données sur site.</span><span class="sxs-lookup"><span data-stu-id="8a593-107">Custom connectors support in the gateway allows users to have their reports that they built with custom connectors stay up to date on the Power BI service by refreshing the data through the on-premises data gateway.</span></span>

<span data-ttu-id="8a593-108">![Prise en charge des connecteurs personnalisés dans la passerelle de données sur site](media/custom-connectors-support-premises-data-gateway-1.jpg "Prise en charge des connecteurs personnalisés dans la passerelle de données sur site")</span><span class="sxs-lookup"><span data-stu-id="8a593-108">![Custom connectors support in the on-premises data gateway](media/custom-connectors-support-premises-data-gateway-1.jpg "Custom connectors support in the on-premises data gateway")</span></span>

## <a name="gateway-multi-geo-support-for-power-bi-premium"></a><span data-ttu-id="8a593-109">Prise en charge de la passerelle dans plusieurs régions pour Power BI Premium</span><span class="sxs-lookup"><span data-stu-id="8a593-109">Gateway multi-geo support for Power BI Premium</span></span>

<span data-ttu-id="8a593-110">Dans le cadre des travaux de prise en charge du service Power BI dans plusieurs régions, la passerelle de données sur site va permettre aux utilisateurs, pendant la configuration, de choisir une autre région que celle d'origine de leur client.</span><span class="sxs-lookup"><span data-stu-id="8a593-110">As part of the work to support multi-geo in the Power BI service, the on-premises data gateway will allow users during the configuration step to choose a different region from their tenant's home region.</span></span> <span data-ttu-id="8a593-111">Cela garantira que les informations relatives à la source de données et ses informations d'identification soient conservées dans la région choisie conformément aux besoins réglementaires uniques de l'organisation.</span><span class="sxs-lookup"><span data-stu-id="8a593-111">This will ensure that the data source's information and credentials remain in the chosen region to comply with the organization’s unique regulatory requirements.</span></span>

<span data-ttu-id="8a593-112">Les expériences doivent être mises à jour afin que les utilisateurs puissent tirer parti de la passerelle de données sur site dans ces régions.</span><span class="sxs-lookup"><span data-stu-id="8a593-112">Experiences need to be updated so that users can leverage the on-premises data gateway in those regions.</span></span> <span data-ttu-id="8a593-113">Une partie de cet effort implique de s'assurer que les informations sur la source de données (par exemple, les informations d'identification) ne quittent pas la région om se trouve l'espace de travail (conformément à la souveraineté des données).</span><span class="sxs-lookup"><span data-stu-id="8a593-113">Part of that effort includes ensuring the data source information (credentials, for example) does not leave the region the workspace is in (to comply with data sovereignty).</span></span>

<span data-ttu-id="8a593-114">![Prise en charge dans plusieurs régions de la passerelle de données sur site](media/gateway-multi-geo-support-pbi-premium-1.png "Prise en charge dans plusieurs régions de la passerelle de données sur site")</span><span class="sxs-lookup"><span data-stu-id="8a593-114">![Multi-geo support in the on-premises data gateway](media/gateway-multi-geo-support-pbi-premium-1.png "Multi-geo support in the on-premises data gateway")</span></span>

## <a name="guarantee-high-availability-of-gateways-via-clustering"></a><span data-ttu-id="8a593-115">Garantie de haute disponibilité des passerelles à l'aide du clustering</span><span class="sxs-lookup"><span data-stu-id="8a593-115">Guarantee high availability of gateways via clustering</span></span>
<span data-ttu-id="8a593-116">Les fonctionnalités de haute disponibilité dans la passerelle de données sur site que nous avons lancées en novembre 2017 passent de la version préliminaire publique à la disponibilité générale.</span><span class="sxs-lookup"><span data-stu-id="8a593-116">The high availability capabilities in the on-premises data gateway that we released in November 2017 are transitioning from public preview to general availability.</span></span> <span data-ttu-id="8a593-117">Dans le cadre de cet effort, plusieurs améliorations de l'expérience ont été apportées, en particulier une meilleure génération de rapports d'erreurs et une expérience utilisateur améliorée.</span><span class="sxs-lookup"><span data-stu-id="8a593-117">Part of this effort includes multiple experience improvements, especially around better error reporting and improved user experience.</span></span>

## <a name="improved-kerberos-single-sign-on-support"></a><span data-ttu-id="8a593-118">Amélioration de la prise en charge de l'authentification unique Kerberos</span><span class="sxs-lookup"><span data-stu-id="8a593-118">Improved Kerberos single sign-on support</span></span>
<span data-ttu-id="8a593-119">Nous envisageons de prendre en charge plusieurs domaines dans notre mise en œuvre de l'authentification unique, ainsi que de faciliter les tests de connexion SSO et les diagnostics des problèmes.</span><span class="sxs-lookup"><span data-stu-id="8a593-119">We plan to support multiple domains in our SSO implementation as well as make it easier to test the SSO connection and diagnose issues.</span></span>

<span data-ttu-id="8a593-120">![Amélioration de la prise en charge de l'authentification unique Kerberos](media/improved-kerberos-single-sign-support-premises-data-gateway-1.png "Amélioration de la prise en charge de l'authentification unique Kerberos")</span><span class="sxs-lookup"><span data-stu-id="8a593-120">![Improved Kerberos single sign-on support](media/improved-kerberos-single-sign-support-premises-data-gateway-1.png "Improved Kerberos single sign-on support")</span></span>

## <a name="saml-based-single-sign-on-for-supported-data-sources"></a><span data-ttu-id="8a593-121">Authentification unique SAML des sources de données prises en charge</span><span class="sxs-lookup"><span data-stu-id="8a593-121">SAML-based single sign-on for supported data sources</span></span>

<span data-ttu-id="8a593-122">L'an dernier, nous avons ajouté la prise en charge de l'authentification unique Kerberos à la passerelle pour plusieurs sources, notamment SQL Server, SAP HANA et Teradata.</span><span class="sxs-lookup"><span data-stu-id="8a593-122">Last year we added Kerberos single sign-on support to the gateway for multiple sources, including SQL Server, SAP HANA, and Teradata.</span></span>

<span data-ttu-id="8a593-123">Pour cette période, nous envisageons de continuer d'investir dans la prise en charge de l'authentification unique en ajoutant des scénarios d'authentification unique SAML pour les sources de données prises en charge.</span><span class="sxs-lookup"><span data-stu-id="8a593-123">This period we plan to continue investments in single sign-on support by adding support to SAML-based single sign-on scenarios for supported data sources.</span></span>

<a name="additional-cloud-data-refresh-capabilities-for-parity-with-pbi-desktop"></a>  
## <a name="additional-cloud-data-refresh-capabilities-for-parity-with-power-bi-desktop"></a><span data-ttu-id="8a593-124">Fonctionnalités supplémentaires d'actualisation de données cloud pour la parité avec Power BI Desktop</span><span class="sxs-lookup"><span data-stu-id="8a593-124">Additional cloud data refresh capabilities for parity with Power BI Desktop</span></span>

<span data-ttu-id="8a593-125">Il existe des situations où un jeu de données Power BI peut s'actualiser sans problème dans Power BI Desktop mais échoue à s'actualiser dans le service Power BI.</span><span class="sxs-lookup"><span data-stu-id="8a593-125">There are some cases where a Power BI dataset can refresh without issues in Power BI Desktop but fails to refresh in the Power BI service.</span></span> <span data-ttu-id="8a593-126">Cela se produit généralement en raison des paramètres de confidentialité des différentes sources de données utilisées dans ce jeu de données.</span><span class="sxs-lookup"><span data-stu-id="8a593-126">This commonly happens because of the privacy settings of the individual data sources used in this dataset.</span></span>

<span data-ttu-id="8a593-127">Dans Power BI Desktop, les utilisateurs peuvent modifier les paramètres de confidentialité de chaque source de données, ce qui permet l'actualisation du jeu de données.</span><span class="sxs-lookup"><span data-stu-id="8a593-127">In Power BI Desktop, users can change the privacy settings for each data source, allowing the dataset to refresh successfully.</span></span> <span data-ttu-id="8a593-128">Nous prévoyons de permettre aux utilisateurs d'actualiser avec succès ces jeux de données dans le service Power BI.</span><span class="sxs-lookup"><span data-stu-id="8a593-128">We intend to give users the ability to successfully refresh those datasets in the Power BI service.</span></span>

<a name="improved-data-sources-settings-experience"></a>  
## <a name="improved-data-source-settings-experience"></a><span data-ttu-id="8a593-129">Amélioration de l'expérience avec les paramètres de source de données</span><span class="sxs-lookup"><span data-stu-id="8a593-129">Improved data source settings experience</span></span>

<span data-ttu-id="8a593-130">Nous prévoyons d'améliorer l'expérience de création de sources de données sur la page « Gérer les passerelles » du service Power BI en ajoutant certaines fonctionnalités les plus demandées, notamment la possibilité d'ignorer l'étape du test de connexion, de renommer des sources de données et de créer plusieurs sources de données avec des informations d'identification distinctes.</span><span class="sxs-lookup"><span data-stu-id="8a593-130">We plan to improve the data sources creation experience on the "Manage Gateways" page in the Power BI service by adding some of the highly requested capabilities, such as the ability to skip the test connection step, to rename data sources, and to create multiple data sources with different credentials.</span></span>

## <a name="tenant-level-administration-of-on-premises-data-gateway"></a><span data-ttu-id="8a593-131">Administration au niveau du client de la passerelle de données sur site</span><span class="sxs-lookup"><span data-stu-id="8a593-131">Tenant level administration of on-premises data gateway</span></span>
<span data-ttu-id="8a593-132">Nous prévoyons d'ajouter à l'attention des administrateurs de client la fonctionnalité de gérer toutes les passerelles de données sur site dans leur client grâce à une API et à l'interface utilisateur.</span><span class="sxs-lookup"><span data-stu-id="8a593-132">We intend to add the ability for tenant administrators to manage all the on-premises data gateways in their tenant through both an API and the user interface.</span></span>

## <a name="basic-traffic-load-balancing-in-the-on-premises-data-gateway"></a><span data-ttu-id="8a593-133">Équilibrage de charge du trafic de base dans la passerelle de données sur site</span><span class="sxs-lookup"><span data-stu-id="8a593-133">Basic traffic load balancing in the on-premises data gateway</span></span>
<span data-ttu-id="8a593-134">Nous prévoyons de fournir la possibilité de fractionner le trafic des demandes pour un cluster de passerelle donné entre toutes les passerelles de ce cluster.</span><span class="sxs-lookup"><span data-stu-id="8a593-134">We plan to introduce the ability to split the requests traffic for a given gateway cluster across all gateways in that cluster.</span></span>
<span data-ttu-id="8a593-135">L'administrateur de passerelle pourra activer et désactiver cette fonctionnalité en fonction des besoins de son organisation.</span><span class="sxs-lookup"><span data-stu-id="8a593-135">The gateway administrator will be able to turn this capability on and off according to their organization's needs.</span></span>

