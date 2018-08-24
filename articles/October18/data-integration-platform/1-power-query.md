---
title: "Transformation et intégration plus simples et plus efficaces des données d'entreprise avec Power Query et la plateforme d'intégration de données"
description: "Transformation et intégration plus simples et plus efficaces des données d'entreprise avec Power Query et la plateforme d'intégration de données"
author: shellyhaverkamp
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 4870e3a2-ac78-4f21-be77-0ddf0ce91282
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: tpalmer
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 94765585de94995c31436ad1b6b801aefa0389ce
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---
#  <a name="simpler-smarter-transformation-and-integration-of-enterprise-data-with-power-query-and-data-integration-platform"></a>Transformation et intégration plus simples et plus efficaces des données d'entreprise avec Power Query et la plateforme d'intégration de données

[!include[data-integration-platform banner](../includes/data-integration-platform.md)]




Nous avons simplifié les problèmes d'intégration de données courants dans les entreprises en innovant :

- De nouvelles fonctionnalités de préparation des données Power Query.
- Les connecteurs de qualité professionnelle.
- Améliorations apportées à l'intégration de données Common Data Service.

## <a name="new-power-query-data-preparation-capabilities"></a>Nouvelles fonctionnalités de préparation des données Power Query

Power Query est actuellement considérablement amélioré par des expériences de *Préparation des données intelligente* leaders sur le marché, notamment :

-   L'extraction de données à partir de sources semi-structurées comme les fichiers PDF.
-   Les pages HTML.
-   Des algorithmes de correspondance approximative pour rationaliser et normaliser les données selon des modèles de similarité.
-   Des fonctionnalités de profilage des données.

Ces fonctionnalités permettent d'identifier facilement les erreurs et les valeurs hors norme dans le cadre de la charge de travail de préparation des données dans l'éditeur de Power Query.

![](media/power-query-becomes-more-powerful-smarter-1.jpg "Power Query devient plus intelligent et plus puissant")
<!-- picture -->


Forte de ses nombreuses années d'investissement dans plusieurs projets Microsoft Research, Microsoft profite de sa notoriété dans le domaine de l'intelligence artificielle pour rendre ces fonctionnalités de préparation des données intelligente dans Power Query facilement accessibles aux millions d'utilisateurs professionnels des différents produits et services Microsoft (Excel, Power BI, Common Data Service pour les applications et Microsoft Flow).

### <a name="intelligent-transforms-and-ai-support-in-power-query"></a>Transformations intelligentes et support d'IA dans Power Query 

Les analystes d'entreprise peuvent facilement intégrer les informations obtenues par l'IA en accédant en un seul clic aux transformations basées sur l'IA. Les fonctionnalités initiales dans cette domaine incluent l'analyse de sentiment et l'extraction de mots clés dans un texte dans un langage normal. Les fonctionnalités supplémentaires telles que l'OCR et l'analyse d'image peuvent être ajoutées au fil du temps.

Les analystes et les professionnels BI auront accès aux nouvelles fonctions et API prêtes à l'emploi pour les transformations basées sur l'IA. Cela facilite les transformations de colonnes pour l'analyse de sentiment et l'extraction de mots clés en un seul clic, ou avec une seule ligne de script, par exemple « ApplySentimentIndex([textResponse]) ».

L'utilisation des API Power Query sera également prise en charge au cours de l'installation et de la configuration des applications Power BI se servant de flux de données. Dans ce cas, le processus de traitement par lots des transformations de colonnes sera dirigé de manière homogène vers un conteneur Cognitive Services s'exécutant dans le cadre de la capacité Power BI Premium d'un client.

### <a name="analytic-and-ml-extensibility-with-scripting"></a>Analyse et extensibilité du ML avec la création de scripts

Nous prenons actuellement en charge l'utilisation de scripts R pour une modélisation et une visualisation personnalisées dans Power BI. Ces scripts R peuvent également être exécutés dans le cadre de l'actualisation des données dans le service Power BI à l'aide de la passerelle de données sur site (mode personnel) avec la possibilité d'attacher des bibliothèques R personnalisées.

Python a été largement adopté par les développeurs et les chercheurs de données.
Il est devenu la norme de fait pour les analyses de données et les travaux liés à l'IA en raison de grande capacité de prise en charge de bibliothèques utiles. Comme étape suivante, Power BI Desktop ajoute la prise en charge de la création de scripts Python.

### <a name="intellisense-support-for-the-m-formula-language"></a>Prise en charge d'IntelliSense pour le langage de formule M

La prise en charge IntelliSense des expériences de modification du langage M (éditeur de requêtes avancé, ajout d'une colonne personnalisée et barre de formule) est ajoutée à l'éditeur de Power Query afin que les utilisateurs puissent effectuer des modifications du code M directement, trouver aisément des erreurs, découvrir les fonctions de la bibliothèque M et connaître les paramètres nécessaires. La prise en charge IntelliSense M est parmi les fonctionnalités les plus demandées par les utilisateurs Power Query de niveau intermédiaire à avancé au cours des dernières années et reste la fonctionnalité la plus recherchée pour Power Query dans les forums de suggestions de fonctionnalités Power BI et Excel.

![](media/power-query-becomes-more-powerful-smarter-4.png "")
<!-- picture -->


En plus de nouvelles fonctionnalités de base dans Power Query, Microsoft étend également la variété de services et produits s'appuyant sur Power Query. Au cours des six derniers mois, Power Query Online a été intégré à Microsoft Flow.

<a name="flow-support-for-data-filtering--mashup"></a>  
### <a name="flow-support-for-data-filtering-and-mashup"></a>Prise en charge de Flow pour le filtrage et le mashup de données

Microsoft Flow s'intègre désormais à Power Query Online, ce qui permet aux utilisateurs d'« Obtenir des lignes à l'aide de Power Query » afin d'autoriser le filtrage et le mashup de données dans le cadre de l'action « Get Rows » sur des connecteurs spécifiques, tels que SQL Server.

### <a name="power-query-community-website"></a>Site web de la communauté Power Query

Un nouveau site web de la communauté Power Query a été lancé. Il comprend un aperçu des technologies Power Query et des articles approfondis, ainsi que des forums, UserVoice et du contenu de la communauté (billets de blog, webinaires). Cette nouvelle communauté est axée sur les aspects technologiques de base de Power Query qui permettent aux partenaires de créer des connecteurs et des transformations de données basés sur la plateforme, et de compléter les ressources basées sur les produits existants précédemment (Excel, Power BI, PowerApps, etc.) qui couvrent des intégrations Power Query spécifiques du point de vue d'un utilisateur final.

##  <a name="enterprise-grade-connectors"></a>Connecteurs de qualité professionnelle

L'équipe d'intégration de données continue de contribuer aux connecteurs de niveau professionnel dans Power BI, Common Data Service pour les applications, PowerApps Microsoft Flow et Logic Apps.

Pour Power BI, Microsoft publie des améliorations importantes pour ses connecteurs SAP Business Warehouse (Serveur d'application et Serveur de messages), ce qui place Microsoft Power BI à égalité, sinon au-dessus de tout autre fournisseurs de BI tiers en termes de connectivité avec SAP Business Warehouse (BW).

SAP a **certifié les connecteurs de Microsoft pour SAP HANA et SAP BW.** En outre, le connecteur SAP HANA a été amélioré pour autoriser des fonctionnalités pour les grandes entreprises, comme le langage SAML (Security Assertion Markup Language) basé sur l'authentification unique et la validation de certificat SSL. Le connecteur SAP BW fait l'objet d'une amélioration importante avec une nouvelle mise en œuvre fournissant de meilleures performances aux ordres d'importance, ainsi que des fonctionnalités supplémentaires.

D'autres améliorations apportées aux connecteurs incluront la prise en charge de l'authentification unique via Kerberos for Spark locale et le lancement des connecteurs existants généralement disponibles, notamment **HDInsight Spark, Google BigQuery, Spark (non HDInsight)**, etc.

Des améliorations ont également été apportées aux connecteurs PowerApps, Microsoft Flow et Logic Apps, comme le lancement de fonctionnalités d'écriture Azure SQL Data Warehouse. De nombreuses mises à jour ont été effectuées dans Visual Studio Team Services, telles que de meilleurs déclencheurs et une meilleure prise en charge des champs personnalisés. Et enfin, des fonctionnalités supplémentaires ont été ajoutées au connecteur Oracle et bien plus encore.

La plateforme continue d'évoluer et a ajouté de nouveaux connecteurs qui fonctionnent de manière à cohérente entre Common Data Service pour les applications, Power BI, PowerApps, Microsoft Flow et Logic Apps, dans le cadre d'un effort d'un meilleur alignement des expériences de nos clients dans la suite complète de produits.

##  <a name="improved-connectors-and-import-experiences-for-cds-data-integration"></a>Connecteurs et expériences d'importation améliorés pour l'intégration de données CDS 

En avril 2018, Microsoft a dévoilé une version préliminaire publique de Common Data Service pour les applications. Dans le cadre de cette version préliminaire, des fonctionnalités intégrées permettaient aux utilisateurs professionnels d'importer des données auprès d'un large éventail de sources de données de Microsoft et de tiers dans le cloud et localement, grâce une expérience Power Query basée sur le web et « low-code no-code », auxquels les utilisateurs sont familiarisés dans Excel et Power BI Desktop.

Dans les six mois à venir, Microsoft continuera de développer la prise en charge des connecteurs de données et des transformations de données dans cette expérience Power Query sur le web, notamment la prise en charge de sources de données critiques pour l'entreprise (locales et sur le cloud), comme Oracle, Amazon RedShift, Google BigQuery, Impala et autres.

Microsoft ajoute également la prise en charge de connecteurs personnalisés (basés sur le kit de développement logiciel du connecteur de données) dans Power Query Online, afin que les connecteurs personnalisés existants créés par les partenaires puissent également être utilisés pour l'intégration de données avec Common Data Service pour les applications et les flux de données Power BI.

L'expérience utilisateur pour l'importation de données depuis des fichiers Power Query Online est également en cours d'amélioration en permettant aux utilisateurs de télécharger des fichiers locaux, ce qui est une demande courante.

![](media/4-1.png "")
<!-- Get Data 5.png -->

De même, Microsoft va activer la recherche dans Power Query de fichiers dans les services de stockage de fichiers basés sur le cloud populaires, tels que OneDrive Business/Personal et les sites d'équipes SharePoint. 

##  <a name="certified-custom-connectors-in-power-bi-desktop"></a>Connecteurs personnalisés certifiés dans Power BI Desktop

En avril 2018, Microsoft a lancé les premiers connecteurs personnalisés dans Power BI, en utilisant des fonctionnalités puissantes de langage M pour permettre aux partenaires d'écrire leurs propres connecteurs et de les distribuer à chaque utilisateur Power BI. Désormais, tous les utilisateurs peuvent facilement accéder aux connecteurs à partir de leurs sources de données, et les fournisseurs peuvent facilement écrire de nouveaux connecteurs lorsque leurs propres clients en demandent, ce qui améliorant le rôle de Power BI comme meilleure plateforme BI pour les fournisseurs et les utilisateurs finaux.

En mai 2018, cela a été aligné sur l'expérience d'obtention de données existante afin de rendre l'expérience plus transparente avec des connecteurs existants prêts à l'emploi, et permettre d'activer le nombre de connecteurs disponibles en un seul clic pour l'augmenter considérablement.



