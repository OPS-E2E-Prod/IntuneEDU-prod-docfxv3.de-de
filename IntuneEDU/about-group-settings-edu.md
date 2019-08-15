---
title: Was sind Einstellungen?
titleSuffix: Intune for Education
description: Informationen Sie zum Verwalten von Einstellungen, die über Intune for Education-Richtlinien.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 91d004c0-8d06-4307-8868-46ac7b119101
searchScope:
- IntuneEDU
ms.openlocfilehash: 998b207bdfc0f8d48cd7eddff3020d00673377a2
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2019
ms.locfileid: "62145971"
---
# <a name="what-are-group-settings"></a><span data-ttu-id="0de8f-103">Was sind Einstellungen?</span><span class="sxs-lookup"><span data-stu-id="0de8f-103">What are group settings?</span></span>

<span data-ttu-id="0de8f-104">Konfigurieren Sie die Einstellungen, um die Funktionsweise von Schüler/Studenten, Lehrkräfte und Geräte in Ihrer Schule/Universität zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="0de8f-104">Configure group settings to manage how students, teachers, and devices work in your school.</span></span>

<span data-ttu-id="0de8f-105">Einstellungen, die Sie Benutzern zuweisen, wird der Benutzer unabhängig davon, welche Geräte sie verwenden folgen.</span><span class="sxs-lookup"><span data-stu-id="0de8f-105">Settings that you assign to users, will follow the users no matter what devices they use.</span></span> <span data-ttu-id="0de8f-106">Auf ähnliche Weise Einstellungen, die Geräten zugewiesen werden führen Sie die Geräte, unabhängig davon, wer sie verwendet.</span><span class="sxs-lookup"><span data-stu-id="0de8f-106">Similarly, settings that you assign to devices,will follow the devices, no matter who uses them.</span></span>

<span data-ttu-id="0de8f-107">Einstellungen werden auf Gruppen angewendet.</span><span class="sxs-lookup"><span data-stu-id="0de8f-107">Settings are applied to groups.</span></span> <span data-ttu-id="0de8f-108">Da Gruppen als Hierarchien mit einer Gruppe über eine andere eine eingerichtet sind [werden Einstellungen für eine Gruppe von allen Untergruppen geerbt](settings-inheritance.md).</span><span class="sxs-lookup"><span data-stu-id="0de8f-108">Since groups are set up as hierarchies, with one group above another, any [settings applied to a group are inherited by all of its subgroups](settings-inheritance.md).</span></span> <span data-ttu-id="0de8f-109">Vererbung erleichtert die Einstellungen gelten für große Gruppen von Benutzern, apps und Geräten.</span><span class="sxs-lookup"><span data-stu-id="0de8f-109">Inheritance makes it easier to apply settings to large groups of users, apps, and devices.</span></span>  

<span data-ttu-id="0de8f-110">Es gibt zwei Möglichkeiten zum Verwalten von Einstellungen in Intune for Education:</span><span class="sxs-lookup"><span data-stu-id="0de8f-110">There are two ways to manage group settings in Intune for Education:</span></span>  

* <span data-ttu-id="0de8f-111">__Express-Konfiguration__: Konfigurieren Sie eine Auswahl der am häufigsten verwendeten School-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="0de8f-111">__Express configuration__: Configure a selection of the most commonly used school settings.</span></span> <span data-ttu-id="0de8f-112">[Express-Konfiguration](Express-configuration-intune-edu.md) ist eine exemplarische Vorgehensweise-Stil-Einrichtung, mit dem Sie auswählen und Zuordnen von gruppeneinstellungen, schnell.</span><span class="sxs-lookup"><span data-stu-id="0de8f-112">[Express configuration](Express-configuration-intune-edu.md) is a walkthrough-style setup that helps you select and assign group settings quickly.</span></span> <span data-ttu-id="0de8f-113">Einstellungen sind vorkonfiguriert, die von Microsoft empfohlene Werte jedoch zum Anpassen Ihrer Schule Richtlinien geändert werden können.</span><span class="sxs-lookup"><span data-stu-id="0de8f-113">Settings are preconfigured to Microsoft-recommended values but can be changed to fit your school's policies.</span></span> 

* <span data-ttu-id="0de8f-114">__Gruppen__: Konfigurieren Sie alle Einstellungen für eine Gruppe von Geräten oder Benutzern.</span><span class="sxs-lookup"><span data-stu-id="0de8f-114">__Groups__: Configure all settings for any group of devices or users.</span></span> <span data-ttu-id="0de8f-115">In der **Gruppen** Registerkarte sehen Sie die vollständige Liste der Einstellungen im Portal verfügbar.</span><span class="sxs-lookup"><span data-stu-id="0de8f-115">In the **Groups** tab, you'll see the full list of settings available in the portal.</span></span> <span data-ttu-id="0de8f-116">Finden Sie unter werden die Einstellungen zur [Windows](all-edu-settings-windows.md) und [iOS](all-edu-settings-ios.md) Gruppen.</span><span class="sxs-lookup"><span data-stu-id="0de8f-116">See are the settings available for [Windows](all-edu-settings-windows.md) and for [iOS](all-edu-settings-ios.md) groups.</span></span>  

## <a name="configure-express-configuration-settings"></a><span data-ttu-id="0de8f-117">Konfigurieren von Einstellungen für express-Konfiguration</span><span class="sxs-lookup"><span data-stu-id="0de8f-117">Configure express configuration settings</span></span>  

<span data-ttu-id="0de8f-118">Express-Konfiguration kann werden verwendet, wenn:</span><span class="sxs-lookup"><span data-stu-id="0de8f-118">Express configuration can be used when:</span></span>
* <span data-ttu-id="0de8f-119">Sie werden erst im Portal der Anfang.</span><span class="sxs-lookup"><span data-stu-id="0de8f-119">You're just getting started in the portal.</span></span>
* <span data-ttu-id="0de8f-120">Sie verwendet haben sie eine Weile und schnelle Änderungen vornehmen möchten.</span><span class="sxs-lookup"><span data-stu-id="0de8f-120">You've been using it for a while and want to make quick changes.</span></span>   

<span data-ttu-id="0de8f-121">Eine ausführliche Übersicht über die Schritte für die express-Konfiguration werden soll, finden Sie unter [Express-Konfiguration in Intune for Education](Express-configuration-intune-edu.md).</span><span class="sxs-lookup"><span data-stu-id="0de8f-121">For a detailed look at the express configuration steps, see [Express configuration in Intune for Education](Express-configuration-intune-edu.md).</span></span>

  ![Express-Einstellungen: beheben Konfiguration](./media/express-config-006-choose-settings.png)  

## <a name="configure-settings-in-groups"></a><span data-ttu-id="0de8f-123">Konfigurieren von Einstellungen in Gruppen</span><span class="sxs-lookup"><span data-stu-id="0de8f-123">Configure settings in Groups</span></span>

<span data-ttu-id="0de8f-124">Die folgenden Schritte beschreiben das Zuweisen von Einstellungen aus der **Gruppen** Seite in Intune for Education.</span><span class="sxs-lookup"><span data-stu-id="0de8f-124">The following steps describe how to assign settings from the **Groups** page in Intune for Education.</span></span> <span data-ttu-id="0de8f-125">Auf dieser Seite sehen Sie die vollständige Liste der geräteeinschränkungen und Funktionen.</span><span class="sxs-lookup"><span data-stu-id="0de8f-125">From this page, you'll see the complete list of device restrictions and features.</span></span>  
1. <span data-ttu-id="0de8f-126">Intune for Education-Dashboard, klicken Sie auf **Gruppen**.</span><span class="sxs-lookup"><span data-stu-id="0de8f-126">From the Intune for Education dashboard, click **Groups**.</span></span>
2. <span data-ttu-id="0de8f-127">Wählen Sie die Gruppe, die Sie konfigurieren möchten.</span><span class="sxs-lookup"><span data-stu-id="0de8f-127">Select the group you want to configure.</span></span>
3. <span data-ttu-id="0de8f-128">Klicken Sie auf **Einstellungen** um die vollständige Liste der verfügbaren Einstellungen anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="0de8f-128">Click **Settings** to view the full list of available settings.</span></span>
4. <span data-ttu-id="0de8f-129">Erweitern Sie jede Kategorie zum Ändern der einzelnen Einstellungen für die ausgewählte Gruppe aus.</span><span class="sxs-lookup"><span data-stu-id="0de8f-129">Expand each category to modify individual settings for the selected group.</span></span>
5. <span data-ttu-id="0de8f-130">Klicken Sie auf **Speichern**, wenn Sie fertig sind.</span><span class="sxs-lookup"><span data-stu-id="0de8f-130">When you're done, click **Save**.</span></span> <span data-ttu-id="0de8f-131">Einstellungen werden auf allen Geräten in der Gruppe automatisch aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="0de8f-131">Settings are automatically updated on all devices in the group.</span></span>  

## <a name="can-i-ever-have-settings-that-dont-work-together"></a><span data-ttu-id="0de8f-132">Kann ich jemals Einstellungen verwenden, die nicht gemeinsam funktionieren?</span><span class="sxs-lookup"><span data-stu-id="0de8f-132">Can I ever have settings that don't work together?</span></span>

<span data-ttu-id="0de8f-133">Es ist möglich, dass nicht kompatible Einstellungen auf der gleichen Gruppe angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="0de8f-133">It is possible for incompatible settings to be applied to the same group.</span></span> <span data-ttu-id="0de8f-134">Diese Inkonsistenzen führen zu Fehlern, wenn ein Benutzer oder Gerät mit unterschiedlichen Einstellungen an mehreren Orten eingerichtet wird.</span><span class="sxs-lookup"><span data-stu-id="0de8f-134">These inconsistences result in errors, when a user or device is being set up with different settings in multiple places.</span></span> <span data-ttu-id="0de8f-135">Konflikte auftreten, wenn der Benutzer oder gerätemitglieder zu mehr als einer Gruppe gehören.</span><span class="sxs-lookup"><span data-stu-id="0de8f-135">Conflicts happen when user or device members belong to more than one group.</span></span>

<span data-ttu-id="0de8f-136">Esperanza ist z. B. ein Mitglied der *6. Grade* gruppieren und ist auch Mitglied der Gruppe mit dem Namen *Earth Science*.</span><span class="sxs-lookup"><span data-stu-id="0de8f-136">For example, Esperanza is a member of the *6th Grade* group and is also a member of group called *Earth Science*.</span></span> <span data-ttu-id="0de8f-137">Wenn Sie eine Einstellung für die Startseite konfigurieren und Zuweisen *6. Grade*, und Sie eine andere Homepage-Einstellung konfigurieren, und weisen Sie ihn *Earth Science*, Esperanza verfügt jetzt über zwei in Konflikt stehenden Homepage Einstellungen zugewiesen Zu ihr.</span><span class="sxs-lookup"><span data-stu-id="0de8f-137">If you configure a homepage setting and assign to *6th Grade*, and you configure a different homepage setting and assign it to *Earth Science*, Esperanza now has two conflicting homepage settings assigned to her.</span></span> <span data-ttu-id="0de8f-138">Die Zuweisung von inkonsistenten Einstellung führt zu einem Fehler.</span><span class="sxs-lookup"><span data-stu-id="0de8f-138">The inconsistent setting assignment leads to an error.</span></span> <span data-ttu-id="0de8f-139">Um dieses Problem zu beheben, sollten der Gruppe ansehen [Bericht über Fehler](what-are-reports.md).</span><span class="sxs-lookup"><span data-stu-id="0de8f-139">To fix this, you'd want to look at the group [settings errors report](what-are-reports.md).</span></span>  

## <a name="next-steps"></a><span data-ttu-id="0de8f-140">Nächste Schritte</span><span class="sxs-lookup"><span data-stu-id="0de8f-140">Next steps</span></span>
<span data-ttu-id="0de8f-141">[Erstellen von Benutzer- und Gerätegruppen](what-are-groups.md) in Intune for Education, damit Sie ihre Einstellungen konfigurieren können.</span><span class="sxs-lookup"><span data-stu-id="0de8f-141">[Create user and device groups](what-are-groups.md) in Intune for Education so that you can start configuring their settings.</span></span>  

[<span data-ttu-id="0de8f-142">Erfahren Sie mehr über das Schützen von apps und Daten mit der vollständigen Verwaltungsfunktionen in Intune</span><span class="sxs-lookup"><span data-stu-id="0de8f-142">Find out more about how to protect apps and data with the full management experience in Intune</span></span>](https://docs.microsoft.com/intune/deploy-use/protect-apps-and-data-with-microsoft-intune)
