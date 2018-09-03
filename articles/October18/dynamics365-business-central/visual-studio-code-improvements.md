---
title: "Amélioration de l'expérience avec le langage AL dans Visual Studio Code"
description: "Améliorations apportées à l'expérience avec le langage AL dans Visual Studio Code"
author: pborring
manager: edupont04
ms.date: 07/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: pborring
audience: developer, customizer
ms.translationtype: HT
ms.sourcegitcommit: 7d6f339c1e92c937c47306db6da360eb8fdd5d77
ms.openlocfilehash: 5b1d5c818fb0fafa973ed0e337cd9bb67ad9b137
ms.contentlocale: fr-fr
ms.lasthandoff: 08/16/2018

---

# <a name="improved-visual-studio-code-al-experience"></a><span data-ttu-id="204b6-103">Amélioration de l'expérience avec le langage AL dans Visual Studio Code</span><span class="sxs-lookup"><span data-stu-id="204b6-103">Improved Visual Studio Code AL experience</span></span>

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

<span data-ttu-id="204b6-104">La création d'extensions permet de personnaliser Business Central.</span><span class="sxs-lookup"><span data-stu-id="204b6-104">Creating extensions is the way to customize Business Central.</span></span> <span data-ttu-id="204b6-105">La version d'octobre 2018 apporte des améliorations en termes de productivité à l'expérience de développement, ainsi que la prise en charge de scénarios d'extension supplémentaires.</span><span class="sxs-lookup"><span data-stu-id="204b6-105">The October '18 release adds productivity enhancements to the development experience as well as support for additional extension scenarios.</span></span>

<span data-ttu-id="204b6-106">Avec les améliorations apportées aux outils et aux fonctionnalités d'extension, les développeurs peuvent être plus productifs lors du développement et de la résolution de solutions, et bénéficient d'options supplémentaires pour répondre aux besoins des clients en matière de personnalisation à l'aide d'extensions.</span><span class="sxs-lookup"><span data-stu-id="204b6-106">With the enhancements to the tooling and extension capabilities, developers can be more productive when developing and troubleshooting solutions, and will have more options to meet customers' customization requirements using extensions.</span></span>

## <a name="cloud-sandbox-with-production-data"></a><span data-ttu-id="204b6-107">Bac à sable (sandbox) dans le cloud avec des données de production</span><span class="sxs-lookup"><span data-stu-id="204b6-107">Cloud sandbox with production data</span></span>
<span data-ttu-id="204b6-108">Lors de l'utilisation des bacs à sable (sandbox) dans le cloud, en particulier lors de tests ou de résolution de problèmes, les utilisateurs souhaitent généralement disposer de données de production.</span><span class="sxs-lookup"><span data-stu-id="204b6-108">A common scenario when working with cloud sandboxes, especially when testing or troubleshooting, is the wish to have production data available.</span></span> <span data-ttu-id="204b6-109">Avec cette version, il est désormais possible de créer un bac à sable (sandbox) dans le cloud basé sur une copie de la dernière sauvegarde dans le cloud des données de production.</span><span class="sxs-lookup"><span data-stu-id="204b6-109">With this release, we add the ability to create a cloud sandbox based on a copy of the latest cloud backup of the production data.</span></span> <span data-ttu-id="204b6-110">Pour réduire l'interférence avec des intégrations installées dans les données de production, ces intégrations seront désactivées lors de la création du bac à sable (sandbox).</span><span class="sxs-lookup"><span data-stu-id="204b6-110">To minimize cross-talk with integrations set up in the production data, these integrations will be disabled when the sandbox is created.</span></span> <span data-ttu-id="204b6-111">En faisant preuve de prudence, les utilisateurs administrateurs peuvent activer ou reconfigurer ces intégrations au besoin pour prendre en charge l'utilisation du bac à sable (sandbox) dans le cloud prévue.</span><span class="sxs-lookup"><span data-stu-id="204b6-111">Using caution, admin users can enable or reconfigure these integrations as required to support the intended cloud sandbox use.</span></span>

## <a name="event-discoverability"></a><span data-ttu-id="204b6-112">Détectabilité des événements</span><span class="sxs-lookup"><span data-stu-id="204b6-112">Event discoverability</span></span>
<span data-ttu-id="204b6-113">Un des aspects fondamentaux dans la création d'extensions consiste à s'abonner aux événements.</span><span class="sxs-lookup"><span data-stu-id="204b6-113">A core aspect of creating extensions is to subscribe to events.</span></span> <span data-ttu-id="204b6-114">Toutefois, il est compliqué de savoir quels événements sont disponibles dans un flux d'utilisateur donné.</span><span class="sxs-lookup"><span data-stu-id="204b6-114">However, a common challenge is understanding which events are available in a given user flow.</span></span> <span data-ttu-id="204b6-115">Le débogage peut être utile, mais il affiche uniquement les événements auxquels les utilisateurs sont déjà abonnés.</span><span class="sxs-lookup"><span data-stu-id="204b6-115">Debugging can help, but will only show events already being subscribed to.</span></span> <span data-ttu-id="204b6-116">Pour simplifier la détectabilité des événements et des points d'extension, un nouveau traceur d'événements est disponible dans le client.</span><span class="sxs-lookup"><span data-stu-id="204b6-116">To aid in the discoverability of events and extension points, there is a new event tracer in the client.</span></span> <span data-ttu-id="204b6-117">Celui-ci permet d'enregistrer un flux d'utilisateur pour répertorier les événements déclenchés, et le développeur peut obtenir le code d'abonné de l'événement généré afin de le copier facilement dans le code AL.</span><span class="sxs-lookup"><span data-stu-id="204b6-117">With this, a user flow can be recorded to list events that are raised, and the developer can have subscriber code for the event generated for easy copy into AL code.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="204b6-118">![Traceur d'événements](media/Event-tracer.png "Traceur d'événements")</span><span class="sxs-lookup"><span data-stu-id="204b6-118">![Event tracer](media/Event-tracer.png "Event tracer")</span></span>

<span data-ttu-id="204b6-119">En outre, un grand nombre de nouveaux événements a été ajouté, ce qui permet d'effectuer des extensions à des emplacements supplémentaires.</span><span class="sxs-lookup"><span data-stu-id="204b6-119">Furthermore, a large number of new events has been added, making it possible to extend in more places.</span></span>

## <a name="visual-studio-code-al-extension-enhancements"></a><span data-ttu-id="204b6-120">Améliorations des extensions AL de Visual Studio Code</span><span class="sxs-lookup"><span data-stu-id="204b6-120">Visual Studio Code AL Extension enhancements</span></span>
<span data-ttu-id="204b6-121">Avec la vérification et la rétrocompatibilité des versions, vous pouvez désormais installer l'extension AL Language du marché Visual Studio Code et l'utiliser pour développer des solutions depuis différentes plateformes, y compris les bacs à sable (sandbox) sur le cloud, la version d'avril 2018 de Business Central, la version d'octobre 2018 de Business Central et les versions à venir.</span><span class="sxs-lookup"><span data-stu-id="204b6-121">With versioning check and backward compatibility, you can now install the AL Language extension from the Visual Studio Code marketplace and use it to develop solutions for many different platforms, including cloud sandboxes, Business Central April 2018 release, Business Central October 2018 release, and future versions.</span></span> <span data-ttu-id="204b6-122">Le compileur vérifie que le client connecté est compatible, et compile par rapport à la plateforme cible définie dans la nouvelle propriété app.json.</span><span class="sxs-lookup"><span data-stu-id="204b6-122">The compiler will check that the connected tenant is compatible, and compile against the target platform as set in the new app.json property.</span></span>

<span data-ttu-id="204b6-123">En outre, l'extension AL est désormais plus rapide et plus réactive lors de l'utilisation de projets plus volumineux contenant de nombreux fichiers/extensions d'objet.</span><span class="sxs-lookup"><span data-stu-id="204b6-123">Also, the AL extension is now faster and more responsive when working with larger projects containing many object extensions/files.</span></span>

## <a name="debugger-enhancements"></a><span data-ttu-id="204b6-124">Améliorations du débogueur</span><span class="sxs-lookup"><span data-stu-id="204b6-124">Debugger enhancements</span></span>
<span data-ttu-id="204b6-125">Comme dans le débogueur Dynamics NAV hérité, vous pouvez désormais utiliser la fonctionnalité courante Arrêt en cas d'erreur, ainsi que Arrêt en cas d'écriture.</span><span class="sxs-lookup"><span data-stu-id="204b6-125">Just like in the legacy Dynamics NAV debugger, you can now use the common Break on Error, as well as Break on Write.</span></span> <span data-ttu-id="204b6-126">Vous pouvez également atteindre la définition dans le code de l'application de base et y définir des points d'arrêt.</span><span class="sxs-lookup"><span data-stu-id="204b6-126">You can also go to definition in the base application code and set breakpoints there.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="204b6-127">![F12 Atteindre la définition pour le code d'application de base](media/Go-to-definition-F12.gif "F12 Atteindre la définition pour le code d'application de base")</span><span class="sxs-lookup"><span data-stu-id="204b6-127">![F12 Go to Definition for base application code](media/Go-to-definition-F12.gif "F12 Go to Definition for base application code")</span></span>

## <a name="intellisense-enhancements"></a><span data-ttu-id="204b6-128">Améliorations IntelliSense</span><span class="sxs-lookup"><span data-stu-id="204b6-128">IntelliSense enhancements</span></span>
<span data-ttu-id="204b6-129">Dans AL, toutes les propriétés, avec aperçu flottant et dans IntelliSense, disposent désormais des liens d'aide qui vous redirigent vers la documentation en ligne connexe.</span><span class="sxs-lookup"><span data-stu-id="204b6-129">All properties in AL, both on hover and in IntelliSense, now have Help links that redirect you to the related online documentation.</span></span> <span data-ttu-id="204b6-130">En outre, la documentation relative à la construction de langage AL est générée automatiquement et utilisée à la fois pour la documentation de référence en ligne et IntelliSense, afin qu'elle soit à jour et alignée.</span><span class="sxs-lookup"><span data-stu-id="204b6-130">Furthermore, the documentation for AL language constructs is autogenerated and used for both online reference documentation and IntelliSense, ensuring up-to-date and aligned documentation.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="204b6-131">![Lien d'aide dans IntelliSense](media/Help-link-from-IntelliSense.gif "Lien d'aide dans IntelliSense")</span><span class="sxs-lookup"><span data-stu-id="204b6-131">![Help link from IntelliSense](media/Help-link-from-IntelliSense.gif "Help link from IntelliSense")</span></span>

<span data-ttu-id="204b6-132">Les suggestions concernant les propriétés d'image dans une extension proposent désormais uniquement celles pouvant être utilisées dans le contexte donné, avec un avertissement pour les images ne pouvant pas être utilisées dans ce contexte, et vous pouvez afficher un aperçu des images lorsque vous utilisez IntelliSense et l'aperçu flottant.</span><span class="sxs-lookup"><span data-stu-id="204b6-132">Suggestions for Image properties in an extension now only propose the ones that can be used in the current context, displaying a warning for images that cannot be used in the current context, and you can preview images when using IntelliSense and on-hover.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="204b6-133">![Sélectionner et afficher un aperçu des images avec IntelliSense](media/IntelliSense-Preview-Images.gif "Sélectionner et afficher un aperçu des images avec IntelliSense")</span><span class="sxs-lookup"><span data-stu-id="204b6-133">![Select and preview images with IntelliSense](media/IntelliSense-Preview-Images.gif "Select and preview images with IntelliSense")</span></span>

## <a name="working-with-permissions"></a><span data-ttu-id="204b6-134">Utilisation des autorisations</span><span class="sxs-lookup"><span data-stu-id="204b6-134">Working with permissions</span></span>
<span data-ttu-id="204b6-135">Pour simplifier l'utilisation des autorisations, il est désormais possible d'exporter des ensembles d'autorisations depuis l'application, à l'aide du client, et d'importer celles-ci dans l'extension AL de Visual Studio Code.</span><span class="sxs-lookup"><span data-stu-id="204b6-135">To make working with permissions easier, it is now possible to export permission sets from the application, using the client, and import these into the Visual Studio Code AL Extension.</span></span> <span data-ttu-id="204b6-136">Vous pouvez également générer de nouveaux fichiers d'autorisations pour les objets dans une extension depuis le projet AL de Visual Studio Code.</span><span class="sxs-lookup"><span data-stu-id="204b6-136">New permission files for the objects in an extension can also be generated from within the Visual Studio Code AL project.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="204b6-137">![Commande AL de Visual Studio Code pour la génération d'un fichier d'autorisations pour les objets d'extension](media/Permissions-AL-command.png "Commande AL de Visual Studio Code pour la génération d'un fichier d'autorisations pour les objets d'extension")</span><span class="sxs-lookup"><span data-stu-id="204b6-137">![Visual Studio Code AL command for generating permissions file for extension objects](media/Permissions-AL-command.png "Visual Studio Code AL command for generating permissions file for extension objects")</span></span>

## <a name="net-interop"></a><span data-ttu-id="204b6-138">.NET Interop</span><span class="sxs-lookup"><span data-stu-id="204b6-138">.NET Interop</span></span>
<span data-ttu-id="204b6-139">Lorsque vous utilisez des solutions Business Central ciblant les déploiements sur site, vous pouvez désormais ajouter .NET Interop dans le code AL.</span><span class="sxs-lookup"><span data-stu-id="204b6-139">When working with Business Central solutions that target on-premises deployments, you can now add .NET Interop in AL code.</span></span> <span data-ttu-id="204b6-140">Notez que cela implique que la solution ne peut pas être déplacée vers le cloud ultérieurement sans remplacer .NET Interop.</span><span class="sxs-lookup"><span data-stu-id="204b6-140">Note that this implies that the solution cannot be moved to the cloud later without replacing the .NET Interop.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="204b6-141">![.NET Interop sur AL local](media/DotNet-interop.png ".NET Interop sur AL local")</span><span class="sxs-lookup"><span data-stu-id="204b6-141">![.NET Interop in on-premises AL](media/DotNet-interop.png ".NET Interop in on-premises AL")</span></span>

## <a name="translation-enhancements"></a><span data-ttu-id="204b6-142">Améliorations de la traduction</span><span class="sxs-lookup"><span data-stu-id="204b6-142">Translation enhancements</span></span>
<span data-ttu-id="204b6-143">De nouvelles informations contextuelles décrivant l'objet et l'élément auxquels une chaîne donnée s'applique ont été ajoutées aux fichiers de traduction XLIFF générées.</span><span class="sxs-lookup"><span data-stu-id="204b6-143">New contextual information that describes which object and element a given string applies to has been added to the generated XLIFF translation files.</span></span> <span data-ttu-id="204b6-144">Cela permet aux traducteurs d'obtenir un meilleure aperçu de l'emplacement auquel une chaîne est affichée dans l'interface utilisateur, ce qui améliore la qualité de la traduction.</span><span class="sxs-lookup"><span data-stu-id="204b6-144">This helps translators get a better overview of where a string is displayed in the UI, thereby increasing the quality of the translation.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="204b6-145">![Indicateur de note de fichier de traduction XLIFF](media/xliff-note.png "Indicateur de note de fichier de traduction XLIFF")</span><span class="sxs-lookup"><span data-stu-id="204b6-145">![XLIFF translation file note tag](media/xliff-note.png "XLIFF translation file note tag")</span></span>

## <a name="odata-bound-actions-in-al"></a><span data-ttu-id="204b6-146">Actions liées à OData dans AL</span><span class="sxs-lookup"><span data-stu-id="204b6-146">OData-bound actions in AL</span></span>
<span data-ttu-id="204b6-147">Il est désormais possible d'indiquer les actions liées à OData dans AL.</span><span class="sxs-lookup"><span data-stu-id="204b6-147">It is now possible to declare OData bound actions in AL.</span></span> <span data-ttu-id="204b6-148">Un nouvel attribut et un nouveau type d'AL ont été ajoutés pour cela.</span><span class="sxs-lookup"><span data-stu-id="204b6-148">A new attribute and a new AL type have been introduced to achieve this.</span></span>

```
[ServiceEnabled]
procedure CreateCustomerCopy(var actionContext : WebServiceActionContext)
var
createdCustomerGuid : Guid;
customer : Record Customer;
begin
actionContext.SetObjectType(ObjectType::Page);
actionContext.SetObjectId(Pages::Customer);
actionContext.AddEntityKey(customer.fieldNo(Id), createdCustomerGuid);
actionContext.SetResultCode(WebServiceActionResultCode::Created);
end;
```
<!--
### Who uses this feature
These features are intended for ISV and VAR developers.
## Status
### Availability
Cloud, On-premises
### Regional availability
Globally
-->

## <a name="tell-us-what-you-think"></a><span data-ttu-id="204b6-149">Donnez-nous votre avis</span><span class="sxs-lookup"><span data-stu-id="204b6-149">Tell us what you think</span></span>
<span data-ttu-id="204b6-150">Aidez-nous à améliorer Dynamics 365 Business Central en proposant des idées, en fournissant des suggestions et en offrant des commentaires.</span><span class="sxs-lookup"><span data-stu-id="204b6-150">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="204b6-151">Utilisez le forum de Business Central à l'adresse [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span><span class="sxs-lookup"><span data-stu-id="204b6-151">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>

