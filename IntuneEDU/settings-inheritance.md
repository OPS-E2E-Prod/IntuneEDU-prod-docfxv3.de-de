---
title: Was ist einstellungsvererbung?
titleSuffix: Intune for Education
description: Informationen Sie zum Verwalten der Einstellungen für Gruppen von Geräten mit Intune for Education.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 09/26/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 4b69b884-bed9-43f4-8507-c802228a8804
searchScope:
- IntuneEDU
ms.openlocfilehash: 5a981fb8916dc0318cc1599002ebe9001f1ef41b
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146906"
---
# <a name="what-is-settings-inheritance"></a><span data-ttu-id="520ff-103">Was ist einstellungsvererbung?</span><span class="sxs-lookup"><span data-stu-id="520ff-103">What is settings inheritance?</span></span>

<span data-ttu-id="520ff-104">Einstellungen werden auf Gruppen angewendet.</span><span class="sxs-lookup"><span data-stu-id="520ff-104">Settings are applied to groups.</span></span> <span data-ttu-id="520ff-105">Da Gruppen als Hierarchien mit einer Gruppe über eine andere eingerichtet sind, werden alle Einstellungen, die für eine Gruppe von Untergruppen geerbt.</span><span class="sxs-lookup"><span data-stu-id="520ff-105">Since groups are set up as hierarchies, with one group above another, all settings applied to a group are inherited by its subgroups.</span></span> <span data-ttu-id="520ff-106">Untergruppen schalten Sie automatisch auf die Änderungen, die Sie der Gruppe "übergeordneten" vornehmen.</span><span class="sxs-lookup"><span data-stu-id="520ff-106">Subgroups automatically take on the changes you make to the group above it.</span></span> <span data-ttu-id="520ff-107">Diese Aktion wird aufgerufen, _Vererbung_.</span><span class="sxs-lookup"><span data-stu-id="520ff-107">This action is called _inheritance_.</span></span> <span data-ttu-id="520ff-108">Einstellungsvererbung ia hilfreich, wenn Sie Einstellungen für große Gruppen von Benutzern und Geräten anwenden möchten.</span><span class="sxs-lookup"><span data-stu-id="520ff-108">Settings inheritance ia helpful when you want to apply settings to large groups of users and devices.</span></span>  


  ![Eine Struktur von Gruppen und Untergruppen.](./media/groups-002-inheritance.png)  


## <a name="configure-subgroups-individually"></a><span data-ttu-id="520ff-110">Untergruppen einzeln konfigurieren</span><span class="sxs-lookup"><span data-stu-id="520ff-110">Configure subgroups individually</span></span>  

<span data-ttu-id="520ff-111">Um Sie vor kurzem geerbte Eigenschaften außer Kraft setzen, wechseln Sie direkt mit der Untergruppe.</span><span class="sxs-lookup"><span data-stu-id="520ff-111">To override recently inherited settings, go directly to the subgroup.</span></span> <span data-ttu-id="520ff-112">Konfigurieren sie einzeln durch Entfernen oder Hinzufügen von Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="520ff-112">Configure it individually by removing or adding settings.</span></span> <span data-ttu-id="520ff-113">Klicken Sie dann Ihre Änderungen zu speichern.</span><span class="sxs-lookup"><span data-stu-id="520ff-113">Then save your changes.</span></span>

## <a name="settings-in-conflict"></a><span data-ttu-id="520ff-114">Einstellungen in Konflikt stehende</span><span class="sxs-lookup"><span data-stu-id="520ff-114">Settings in conflict</span></span>  

<span data-ttu-id="520ff-115">Wenn Sie in Konflikt stehenden Einstellungen auf der gleichen Gruppe anwenden, wird Intune jeweils einzeln zu analysieren.</span><span class="sxs-lookup"><span data-stu-id="520ff-115">If you apply conflicting settings to the same group, Intune will analyze each one individually.</span></span> <span data-ttu-id="520ff-116">Intune wählt immer die Einstellungen, die mit Bestimmtheit, School-Richtlinien erfüllt.</span><span class="sxs-lookup"><span data-stu-id="520ff-116">Intune always chooses the settings that, with certainty, complies with school policies.</span></span>

<span data-ttu-id="520ff-117">In anderen Fällen, wenn Intune nicht, den Konflikt auflösen kann, Sie sollten überprüfen, die [Einstellungen in Konflikt stehen](what-are-reports.md) Bericht.</span><span class="sxs-lookup"><span data-stu-id="520ff-117">In other cases, when Intune can't resolve the conflict, you should review the [settings conflict](what-are-reports.md) report.</span></span>

### <a name="example-of-inheritance-conflict"></a><span data-ttu-id="520ff-118">Beispiel für Vererbung Konflikt</span><span class="sxs-lookup"><span data-stu-id="520ff-118">Example of inheritance conflict</span></span>  

<span data-ttu-id="520ff-119">Betrachten Sie beispielsweise die Untergruppe "," *12. auf Unternehmensniveau AP Computer Science*.</span><span class="sxs-lookup"><span data-stu-id="520ff-119">As an example, consider the subgroup, *12th Grade AP Computer Science*.</span></span> <span data-ttu-id="520ff-120">Die Untergruppe "liegt unter der übergeordneten Gruppe, *12. Grade*.</span><span class="sxs-lookup"><span data-stu-id="520ff-120">The subgroup falls under the parent group, *12th grade*.</span></span> <span data-ttu-id="520ff-121">Weisen Sie einer strict Security-Überprüfung erforderlich, alle Dateien und apps heruntergeladen, Geräte in der *12. Grade* Gruppe.</span><span class="sxs-lookup"><span data-stu-id="520ff-121">You assign a strict security scanning requirement to all files and apps downloaded devices in the *12th grade* group.</span></span>

<span data-ttu-id="520ff-122">Sie jedoch wissen, die für eine anstehende Zuordnung *12. auf Unternehmensniveau AP Computer Science* müssen herunterladen JavaScript-Dateien, die nicht überprüft werden müssen.</span><span class="sxs-lookup"><span data-stu-id="520ff-122">However, you know that for an upcoming assignment, *12th Grade AP Computer Science* must download JavaScript files that don't need to be scanned.</span></span> <span data-ttu-id="520ff-123">Wenn Sie nicht, dass die einstellungsvererbung von, die restriktiver überschreiben *zwölfte auf Unternehmensniveau* Einstellung gelten für die Benutzer in *zwölfte auf Unternehmensniveau AP Computer Science*.</span><span class="sxs-lookup"><span data-stu-id="520ff-123">If you don't override settings inheritance, the more restrictive *Twelfth Grade* setting will be applied to the users in *Twelfth Grade AP Computer Science*.</span></span>

## <a name="settings-error-report"></a><span data-ttu-id="520ff-124">Fehlerbericht für Einstellungen</span><span class="sxs-lookup"><span data-stu-id="520ff-124">Settings error report</span></span>

<span data-ttu-id="520ff-125">Wenn eine Einstellung nicht aufgelöst werden kann, wird es in den Bericht über Fehler angezeigt.</span><span class="sxs-lookup"><span data-stu-id="520ff-125">If a setting can't be resolved, it will appear in the Settings error report.</span></span> <span data-ttu-id="520ff-126">Weitere Informationen zu Berichten finden Sie unter [Berichte anzeigen und herunterladen](what-are-reports.md).</span><span class="sxs-lookup"><span data-stu-id="520ff-126">For more information about reports, see [View and download reports](what-are-reports.md).</span></span>  

## <a name="next-steps"></a><span data-ttu-id="520ff-127">Nächste Schritte</span><span class="sxs-lookup"><span data-stu-id="520ff-127">Next steps</span></span>  
<span data-ttu-id="520ff-128">Erfahren Sie mehr über die [vollständige Gruppen in Intune auftreten](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune).</span><span class="sxs-lookup"><span data-stu-id="520ff-128">Find out more about the [full groups experience in Intune](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune).</span></span>
