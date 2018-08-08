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
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 161da5108c31c88f8e0f254abcf0f4b0fa6e950c
ms.contentlocale: fr-fr
ms.lasthandoff: 07/18/2018

---

# <a name="improved-visual-studio-code-al-experience"></a><span data-ttu-id="404d6-103">Amélioration de l'expérience avec le langage AL dans Visual Studio Code</span><span class="sxs-lookup"><span data-stu-id="404d6-103">Improved Visual Studio Code AL experience</span></span>

[!include[banner](../../includes/banner.md)]

<span data-ttu-id="404d6-104">La création d'extensions permet de personnaliser Business Central.</span><span class="sxs-lookup"><span data-stu-id="404d6-104">Creating extensions is the way to customize Business Central.</span></span> <span data-ttu-id="404d6-105">La version d'octobre 2018 apporte des améliorations en termes de productivité à l'expérience de développement, ainsi que la prise en charge de scénarios d'extension supplémentaires.</span><span class="sxs-lookup"><span data-stu-id="404d6-105">The October '18 release adds productivity enhancements to the development experience as well as support for additional extension scenarios.</span></span>

<span data-ttu-id="404d6-106">Avec les améliorations apportées aux outils et aux fonctionnalités d'extension, les développeurs peuvent être plus productifs lors du développement et de la résolution de solutions, et bénéficient d'options supplémentaires pour répondre aux besoins des clients en matière de personnalisation à l'aide d'extensions.</span><span class="sxs-lookup"><span data-stu-id="404d6-106">With the enhancements to the tooling and extension capabilities, developers can be more productive when developing and troubleshooting solutions, and will have more options to meet customers' customization requirements using extensions.</span></span>

## <a name="sandbox-with-production-data"></a><span data-ttu-id="404d6-107">Bac à sable (sandbox) avec données de production</span><span class="sxs-lookup"><span data-stu-id="404d6-107">Sandbox with production data</span></span>
<span data-ttu-id="404d6-108">Un scénario courant lorsque vous utilisez des bacs à sable (sandbox), notamment lors de tests ou de résolution problèmes, consiste à souhaiter disposer de données de production.</span><span class="sxs-lookup"><span data-stu-id="404d6-108">A common scenario when working with sandboxes, especially when testing or troubleshooting, is the wish to have production data available.</span></span> <span data-ttu-id="404d6-109">Avec cette version, nous ajoutons la possibilité de créer un bac à sable (sandbox) basé sur une copie de la dernière sauvegarde sur le cloud des données de production.</span><span class="sxs-lookup"><span data-stu-id="404d6-109">With this release, we add the ability to create a sandbox based on a copy of the latest cloud backup of the production data.</span></span> <span data-ttu-id="404d6-110">Pour réduire l'interférence avec des intégrations installées dans les données de production, ces intégrations seront désactivées lors de la création du bac à sable (sandbox).</span><span class="sxs-lookup"><span data-stu-id="404d6-110">To minimize cross-talk with integrations set up in the production data, these integrations will be disabled when the sandbox is created.</span></span> <span data-ttu-id="404d6-111">En faisant preuve de prudence, les utilisateurs administrateurs peuvent activer ou reconfigurer ces intégrations au besoin pour prendre en charge l'utilisation du bac à sable (sandbox) prévue.</span><span class="sxs-lookup"><span data-stu-id="404d6-111">Using caution, admin users can enable or reconfigure these integrations as required to support the intended sandbox use.</span></span>

## <a name="new-object-extensions"></a><span data-ttu-id="404d6-112">Nouvelles extensions d'objet</span><span class="sxs-lookup"><span data-stu-id="404d6-112">New object extensions</span></span>
<span data-ttu-id="404d6-113">Vous pouvez désormais effectuer des extensions comme suit :</span><span class="sxs-lookup"><span data-stu-id="404d6-113">You can now extend the following:</span></span>

- <span data-ttu-id="404d6-114">Effectuer des énumérations (options) depuis l'application de base ainsi que créer des énumérations extensibles dans vos extensions.</span><span class="sxs-lookup"><span data-stu-id="404d6-114">Enums (options) from the base application as well as create new, extensible enums in your extensions.</span></span>
- <span data-ttu-id="404d6-115">Jeux de données d'états dans les extensions.</span><span class="sxs-lookup"><span data-stu-id="404d6-115">Report data sets in extensions.</span></span> <span data-ttu-id="404d6-116">Les dispositions des données d'états sont toujours une histoire de remplacement.</span><span class="sxs-lookup"><span data-stu-id="404d6-116">Report data layouts are still a replacement story.</span></span>
- <span data-ttu-id="404d6-117">Groupes de champs.</span><span class="sxs-lookup"><span data-stu-id="404d6-117">Field groups.</span></span>

## <a name="event-discoverability"></a><span data-ttu-id="404d6-118">Détectabilité des événements</span><span class="sxs-lookup"><span data-stu-id="404d6-118">Event discoverability</span></span>
<span data-ttu-id="404d6-119">Un des aspects fondamentaux dans la création d'extensions consiste à s'abonner aux événements.</span><span class="sxs-lookup"><span data-stu-id="404d6-119">A core aspect of creating extensions is to subscribe to events.</span></span> <span data-ttu-id="404d6-120">Toutefois, il est compliqué de savoir quels événements sont disponibles dans un flux d'utilisateur donné.</span><span class="sxs-lookup"><span data-stu-id="404d6-120">However, a common challenge is understanding which events are available in a given user flow.</span></span> <span data-ttu-id="404d6-121">Le débogage peut être utile, mais il affiche uniquement les événements auxquels les utilisateurs sont déjà abonnés.</span><span class="sxs-lookup"><span data-stu-id="404d6-121">Debugging can help, but will only show events already being subscribed to.</span></span> <span data-ttu-id="404d6-122">Pour simplifier la détectabilité des événements et des points d'extension, un nouveau traceur d'événements est disponible dans le client.</span><span class="sxs-lookup"><span data-stu-id="404d6-122">To aid in the discoverability of events and extension points, there is a new event tracer in the client.</span></span> <span data-ttu-id="404d6-123">Celui-ci permet d'enregistrer un flux d'utilisateur pour répertorier les événements déclenchés, et le développeur peut obtenir le code d'abonné de l'événement généré afin de le copier facilement dans le code AL.</span><span class="sxs-lookup"><span data-stu-id="404d6-123">With this, a user flow can be recorded to list events that are raised, and the developer can have subscriber code for the event generated for easy copy into AL code.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="404d6-124">![Traceur d'événements](media/Event-tracer.png "Traceur d'événements")</span><span class="sxs-lookup"><span data-stu-id="404d6-124">![Event tracer](media/Event-tracer.png "Event tracer")</span></span>

<span data-ttu-id="404d6-125">En outre, un grand nombre de nouveaux événements a été ajouté, ce qui permet d'effectuer des extensions à des emplacements supplémentaires.</span><span class="sxs-lookup"><span data-stu-id="404d6-125">Furthermore, a large number of new events has been added, making it possible to extend in more places.</span></span>

## <a name="visual-studio-code-al-extension-enhancements"></a><span data-ttu-id="404d6-126">Améliorations des extensions AL de Visual Studio Code</span><span class="sxs-lookup"><span data-stu-id="404d6-126">Visual Studio Code AL Extension enhancements</span></span>
<span data-ttu-id="404d6-127">Avec la vérification et la rétrocompatibilité des versions, vous pouvez désormais installer l'extension AL Language du marché Visual Studio Code et l'utiliser pour développer des solutions depuis différentes plateformes, y compris les bacs à sable (sandbox) sur le cloud, la version d'avril 2018 de Business Central, la version d'octobre 2018 de Business Central et les versions à venir.</span><span class="sxs-lookup"><span data-stu-id="404d6-127">With versioning check and backward compatibility, you can now install the AL Language extension from the Visual Studio Code marketplace and use it to develop solutions for many different platforms, including cloud sandboxes, Business Central April 2018 release, Business Central October 2018 release, and future versions.</span></span> <span data-ttu-id="404d6-128">Le compileur vérifie que le client connecté est compatible, et compile par rapport à la plateforme cible définie dans la nouvelle propriété app.json.</span><span class="sxs-lookup"><span data-stu-id="404d6-128">The compiler will check that the connected tenant is compatible, and compile against the target platform as set in the new app.json property.</span></span>

<span data-ttu-id="404d6-129">En outre, l'extension AL est désormais plus rapide et plus réactive lors de l'utilisation de projets plus volumineux contenant de nombreux fichiers/extensions d'objet.</span><span class="sxs-lookup"><span data-stu-id="404d6-129">Also, the AL extension is now faster and more responsive when working with larger projects containing many object extensions/files.</span></span>

## <a name="debugger-enhancements"></a><span data-ttu-id="404d6-130">Améliorations du débogueur</span><span class="sxs-lookup"><span data-stu-id="404d6-130">Debugger enhancements</span></span>
<span data-ttu-id="404d6-131">Comme dans le débogueur Dynamics NAV hérité, vous pouvez désormais utiliser la fonctionnalité courante Arrêt en cas d'erreur, ainsi que Arrêt en cas d'écriture.</span><span class="sxs-lookup"><span data-stu-id="404d6-131">Just like in the legacy Dynamics NAV debugger, you can now use the common Break on Error, as well as Break on Write.</span></span> <span data-ttu-id="404d6-132">Vous pouvez également atteindre la définition dans le code de l'application de base et y définir des points d'arrêt.</span><span class="sxs-lookup"><span data-stu-id="404d6-132">You can also go to definition in the base application code and set breakpoints there.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="404d6-133">![F12 Atteindre la définition pour le code d'application de base](media/Go-to-definition-F12.gif "F12 Atteindre la définition pour le code d'application de base")</span><span class="sxs-lookup"><span data-stu-id="404d6-133">![F12 Go to Definition for base application code](media/Go-to-definition-F12.gif "F12 Go to Definition for base application code")</span></span>

## <a name="intellisense-enhancements"></a><span data-ttu-id="404d6-134">Améliorations IntelliSense</span><span class="sxs-lookup"><span data-stu-id="404d6-134">IntelliSense enhancements</span></span>
<span data-ttu-id="404d6-135">Dans AL, toutes les propriétés, avec aperçu flottant et dans IntelliSense, disposent désormais des liens d'aide qui vous redirigent vers la documentation en ligne connexe.</span><span class="sxs-lookup"><span data-stu-id="404d6-135">All properties in AL, both on hover and in IntelliSense, now have Help links that redirect you to the related online documentation.</span></span> <span data-ttu-id="404d6-136">En outre, la documentation relative à la construction de langage AL est générée automatiquement et utilisée à la fois pour la documentation de référence en ligne et IntelliSense, afin qu'elle soit à jour et alignée.</span><span class="sxs-lookup"><span data-stu-id="404d6-136">Furthermore, the documentation for AL language constructs is autogenerated and used for both online reference documentation and IntelliSense, ensuring up-to-date and aligned documentation.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="404d6-137">![Lien d'aide dans IntelliSense](media/Help-link-from-IntelliSense.gif "Lien d'aide dans IntelliSense")</span><span class="sxs-lookup"><span data-stu-id="404d6-137">![Help link from IntelliSense](media/Help-link-from-IntelliSense.gif "Help link from IntelliSense")</span></span>

<span data-ttu-id="404d6-138">Les suggestions concernant les propriétés d'image dans une extension proposent désormais uniquement celles pouvant être utilisées dans le contexte donné, avec un avertissement pour les images ne pouvant pas être utilisées dans ce contexte, et vous pouvez afficher un aperçu des images lorsque vous utilisez IntelliSense et l'aperçu flottant.</span><span class="sxs-lookup"><span data-stu-id="404d6-138">Suggestions for Image properties in an extension now only propose the ones that can be used in the current context, displaying a warning for images that cannot be used in the current context, and you can preview images when using IntelliSense and on-hover.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="404d6-139">![Sélectionner et afficher un aperçu des images avec IntelliSense](media/IntelliSense-Preview-Images.gif "Sélectionner et afficher un aperçu des images avec IntelliSense")</span><span class="sxs-lookup"><span data-stu-id="404d6-139">![Select and preview images with IntelliSense](media/IntelliSense-Preview-Images.gif "Select and preview images with IntelliSense")</span></span>

## <a name="working-with-permissions"></a><span data-ttu-id="404d6-140">Utilisation des autorisations</span><span class="sxs-lookup"><span data-stu-id="404d6-140">Working with permissions</span></span>
<span data-ttu-id="404d6-141">Pour simplifier l'utilisation des autorisations, il est désormais possible d'exporter des ensembles d'autorisations depuis l'application, à l'aide du client, et d'importer celles-ci dans l'extension AL de Visual Studio Code.</span><span class="sxs-lookup"><span data-stu-id="404d6-141">To make working with permissions easier, it is now possible to export permission sets from the application, using the client, and import these into the Visual Studio Code AL Extension.</span></span> <span data-ttu-id="404d6-142">Vous pouvez également générer de nouveaux fichiers d'autorisations pour les objets dans une extension depuis le projet AL de Visual Studio Code.</span><span class="sxs-lookup"><span data-stu-id="404d6-142">New permission files for the objects in an extension can also be generated from within the Visual Studio Code AL project.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="404d6-143">![Commande AL de Visual Studio Code pour la génération d'un fichier d'autorisations pour les objets d'extension](media/Permissions-AL-command.png "Commande AL de Visual Studio Code pour la génération d'un fichier d'autorisations pour les objets d'extension")</span><span class="sxs-lookup"><span data-stu-id="404d6-143">![Visual Studio Code AL command for generating permissions file for extension objects](media/Permissions-AL-command.png "Visual Studio Code AL command for generating permissions file for extension objects")</span></span>

## <a name="net-interop"></a><span data-ttu-id="404d6-144">.NET Interop</span><span class="sxs-lookup"><span data-stu-id="404d6-144">.NET Interop</span></span>
<span data-ttu-id="404d6-145">Lorsque vous utilisez des solutions Business Central ciblant les déploiements sur site, vous pouvez désormais ajouter .NET Interop dans le code AL.</span><span class="sxs-lookup"><span data-stu-id="404d6-145">When working with Business Central solutions that target on-premises deployments, you can now add .NET Interop in AL code.</span></span> <span data-ttu-id="404d6-146">Notez que cela implique que la solution ne peut pas être déplacée vers le cloud ultérieurement sans remplacer .NET Interop.</span><span class="sxs-lookup"><span data-stu-id="404d6-146">Note that this implies that the solution cannot be moved to the cloud later without replacing the .NET Interop.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="404d6-147">![.NET Interop sur AL local](media/DotNet-interop.png ".NET Interop sur AL local")</span><span class="sxs-lookup"><span data-stu-id="404d6-147">![.NET Interop in on-premises AL](media/DotNet-interop.png ".NET Interop in on-premises AL")</span></span>

## <a name="translation-enhancements"></a><span data-ttu-id="404d6-148">Améliorations de la traduction</span><span class="sxs-lookup"><span data-stu-id="404d6-148">Translation enhancements</span></span>
<span data-ttu-id="404d6-149">De nouvelles informations contextuelles décrivant l'objet et l'élément auxquels une chaîne donnée s'applique ont été ajoutées aux fichiers de traduction XLIFF générées.</span><span class="sxs-lookup"><span data-stu-id="404d6-149">New contextual information that describes which object and element a given string applies to has been added to the generated XLIFF translation files.</span></span> <span data-ttu-id="404d6-150">Cela permet aux traducteurs d'obtenir un meilleure aperçu de l'emplacement auquel une chaîne est affichée dans l'interface utilisateur, ce qui améliore la qualité de la traduction.</span><span class="sxs-lookup"><span data-stu-id="404d6-150">This helps translators get a better overview of where a string is displayed in the UI, thereby increasing the quality of the translation.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="404d6-151">![Indicateur de note de fichier de traduction XLIFF](media/xliff-note.png "Indicateur de note de fichier de traduction XLIFF")</span><span class="sxs-lookup"><span data-stu-id="404d6-151">![XLIFF translation file note tag](media/xliff-note.png "XLIFF translation file note tag")</span></span>

## <a name="odata-bound-actions-in-al"></a><span data-ttu-id="404d6-152">Actions liées à OData dans AL</span><span class="sxs-lookup"><span data-stu-id="404d6-152">OData-bound actions in AL</span></span>
<span data-ttu-id="404d6-153">Il est désormais possible d'indiquer les actions liées à OData dans AL.</span><span class="sxs-lookup"><span data-stu-id="404d6-153">It is now possible to declare OData bound actions in AL.</span></span> <span data-ttu-id="404d6-154">Un nouvel attribut et un nouveau type d'AL ont été ajoutés pour cela.</span><span class="sxs-lookup"><span data-stu-id="404d6-154">A new attribute and a new AL type have been introduced to achieve this.</span></span>

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

## <a name="tell-us-what-you-think"></a><span data-ttu-id="404d6-155">Donnez-nous votre avis</span><span class="sxs-lookup"><span data-stu-id="404d6-155">Tell us what you think</span></span>
<span data-ttu-id="404d6-156">Aidez-nous à améliorer Dynamics 365 Business Central en proposant des idées, en fournissant des suggestions et en offrant des commentaires.</span><span class="sxs-lookup"><span data-stu-id="404d6-156">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="404d6-157">Utilisez le forum de Business Central à l'adresse [https://aka.ms/businesscentralfeedback](https://aka.ms/businesscentralfeedback).</span><span class="sxs-lookup"><span data-stu-id="404d6-157">Use the Business Central forum at [https://aka.ms/businesscentralfeedback](https://aka.ms/businesscentralfeedback).</span></span>

