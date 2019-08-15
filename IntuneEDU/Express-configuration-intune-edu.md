---
title: Express-Konfiguration
titleSuffix: Intune for Education
description: Verwenden von Express-Konfiguration zum Einrichten von Gruppen in Intune for Education.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: af5d35ee-84f5-4245-a441-671600bcc376
searchScope:
- IntuneEDU
ms.openlocfilehash: eb3b697973d37d5b4697559b3ba87b64ba9afdb3
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2019
ms.locfileid: "62147323"
---
# <a name="express-configuration-in-intune-for-education"></a><span data-ttu-id="18eb7-103">Express-Konfiguration in Intune for Education</span><span class="sxs-lookup"><span data-stu-id="18eb7-103">Express configuration in Intune for Education</span></span>

  ![Die Express-Konfiguration-Kachel, die besagt, dass "Launch Express-Konfiguration, klicken Sie hier, um apps und Einstellungen für eine Gruppe auszuwählen."](./media/express-config-001-launch-tile.png)

<span data-ttu-id="18eb7-105">Express-Konfiguration können Sie Einstellungen und apps für Benutzer und Geräte zuweisen.</span><span class="sxs-lookup"><span data-stu-id="18eb7-105">Express Configuration enables you to assign settings and apps to users and devices.</span></span> <span data-ttu-id="18eb7-106">Die Kachel "Start", für die schrittweise exemplarische Vorgehensweise befindet sich auf der Titelseite des der [Intune for Education-Portals](https://intuneeducation.portal.azure.com).</span><span class="sxs-lookup"><span data-stu-id="18eb7-106">The launch tile for the step-by-step walkthrough is found on the front page of the [Intune for Education portal](https://intuneeducation.portal.azure.com).</span></span> 

<span data-ttu-id="18eb7-107">Wenn Sie durch jeden Schritt klicken, sehen Sie sich, dass die meisten Windows oder iOS-Einstellungen bereits konfiguriert sind.</span><span class="sxs-lookup"><span data-stu-id="18eb7-107">As you click through each step, you'll see that most of the Windows or iOS settings are already configured.</span></span> <span data-ttu-id="18eb7-108">Diese Konfigurationen sind die Standardwerte, und werden als Empfehlungen festgelegt.</span><span class="sxs-lookup"><span data-stu-id="18eb7-108">These configurations are the default values and are set as recommendations.</span></span> <span data-ttu-id="18eb7-109">Empfohlene Betriebssystem-spezifische apps werden auch bereits markiert.</span><span class="sxs-lookup"><span data-stu-id="18eb7-109">Recommended OS-specific apps are also preselected.</span></span> <span data-ttu-id="18eb7-110">Ändern Sie die Standardauswahl für Deine Bildungseinrichtung nach Bedarf.</span><span class="sxs-lookup"><span data-stu-id="18eb7-110">Change the default selections as needed for your school.</span></span> 

<span data-ttu-id="18eb7-111">Express-Konfiguration wiederherstellen Sie, jedes Mal, wenn Sie Einstellungen oder apps von einer Gruppenstatus ändern möchten.</span><span class="sxs-lookup"><span data-stu-id="18eb7-111">Return to express configuration anytime you want to make changes to a group's settings or apps.</span></span> 

## <a name="launch-express-configuration"></a><span data-ttu-id="18eb7-112">Express-Konfiguration starten</span><span class="sxs-lookup"><span data-stu-id="18eb7-112">Launch express configuration</span></span>
<span data-ttu-id="18eb7-113">In diesem Abschnitt wird beschrieben, wie Sie die Schritte im express-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="18eb7-113">This section describes how to complete the steps in express configuration.</span></span> <span data-ttu-id="18eb7-114">Stellen Sie sicher, dass Sie Ihre Schul-/ unidaten synchronisiert oder Gruppen in Azure AD erstellt haben, rufen Sie optimal von express-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="18eb7-114">To get the most out of express configuration, make sure you've synced your school data or created groups in Azure AD.</span></span> 

1. <span data-ttu-id="18eb7-115">Melden Sie sich Intune for Education-Portals.</span><span class="sxs-lookup"><span data-stu-id="18eb7-115">Sign in to the Intune for Education portal.</span></span>
2. <span data-ttu-id="18eb7-116">Klicken Sie auf dem Dashboard auf **Express-Konfiguration starten**.</span><span class="sxs-lookup"><span data-stu-id="18eb7-116">On the dashboard, click **Launch Express Configuration**.</span></span>  

<span data-ttu-id="18eb7-117">Wenn iOS-Konfigurationen deaktiviert sind, wenn Sie die express-Konfiguration starten:</span><span class="sxs-lookup"><span data-stu-id="18eb7-117">If iOS configurations are disabled when you launch express configuration:</span></span>  
1. <span data-ttu-id="18eb7-118">Wählen Sie aus dem Dashboard **alle** > **iOS-Geräteverwaltung**.</span><span class="sxs-lookup"><span data-stu-id="18eb7-118">From the dashboard, select **See all** > **iOS Device Management**.</span></span>
2. <span data-ttu-id="18eb7-119">Hochladen eines Apple-MDM-Push-Zertifikats an.</span><span class="sxs-lookup"><span data-stu-id="18eb7-119">Upload an Apple MDM Push certificate.</span></span>
3. <span data-ttu-id="18eb7-120">Registrieren einer [Token von Apple-MDM-Server](setup-ios-device-management.md).</span><span class="sxs-lookup"><span data-stu-id="18eb7-120">Register an [Apple MDM Server token](setup-ios-device-management.md).</span></span>

## <a name="choose-a-group-to-configure"></a><span data-ttu-id="18eb7-121">Wählen Sie eine Gruppe zu konfigurieren</span><span class="sxs-lookup"><span data-stu-id="18eb7-121">Choose a group to configure</span></span>

<span data-ttu-id="18eb7-122">Einige Gruppen werden erstellt und in Ihre Intune for Education-Abonnement enthalten.</span><span class="sxs-lookup"><span data-stu-id="18eb7-122">Some groups are created and included with your Intune for Education subscription.</span></span> <span data-ttu-id="18eb7-123">Intune for Education füllt die Gruppen mit den Details von Schul-/ unidatensätzen.</span><span class="sxs-lookup"><span data-stu-id="18eb7-123">Intune for Education populates the groups with details from school records.</span></span> <span data-ttu-id="18eb7-124">Diese Gruppen sind:</span><span class="sxs-lookup"><span data-stu-id="18eb7-124">These groups are:</span></span>  

 * <span data-ttu-id="18eb7-125">Alle Geräte</span><span class="sxs-lookup"><span data-stu-id="18eb7-125">All Devices</span></span>  
 * <span data-ttu-id="18eb7-126">Allen Benutzern</span><span class="sxs-lookup"><span data-stu-id="18eb7-126">All Users</span></span>  
 
<span data-ttu-id="18eb7-127">Wenn Sie School Data Sync (SDS) verwenden, um Ihrer Schule Datensätze zu importieren, sehen Sie auch:</span><span class="sxs-lookup"><span data-stu-id="18eb7-127">If you use School Data Sync (SDS) to import your school's records, you'll also see:</span></span>  

 * <span data-ttu-id="18eb7-128">Alle Lehrer</span><span class="sxs-lookup"><span data-stu-id="18eb7-128">All Teachers</span></span>  
 * <span data-ttu-id="18eb7-129">Alle Schüler/Studenten</span><span class="sxs-lookup"><span data-stu-id="18eb7-129">All Students</span></span>  

<span data-ttu-id="18eb7-130">Intune for Education empfiehlt, beginnen Sie mit der **alle Benutzer** Gruppe.</span><span class="sxs-lookup"><span data-stu-id="18eb7-130">Intune for Education recommends that you start with the **All Users** group.</span></span> <span data-ttu-id="18eb7-131">Weisen Sie die Einstellungen, die alle Benutzer benötigen.</span><span class="sxs-lookup"><span data-stu-id="18eb7-131">Assign the settings that all users must have.</span></span> <span data-ttu-id="18eb7-132">Beispielsweise sind kennwortanforderungen und Popup Einschränkungen wahrscheinlich für alle Benutzer identisch.</span><span class="sxs-lookup"><span data-stu-id="18eb7-132">For example, password requirements and pop-up restrictions are likely the same for all users.</span></span>

  ![Wählen Sie Gruppe Bildschirmgröße abfragt, eine Gruppe auszuwählen.](./media/express-config-004-choose-group.png)

<span data-ttu-id="18eb7-134">Klicken Sie auf den Pfeil erweitern/reduzieren, zum Anzeigen oder Ausblenden aller Gruppen.</span><span class="sxs-lookup"><span data-stu-id="18eb7-134">Click the expand/collapse arrow to view or hide all groups.</span></span> <span data-ttu-id="18eb7-135">Denken Sie daran: Wenn Sie eine Gruppe der obersten Ebene konfigurieren, deren Untergruppen erben alle zugehörigen Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="18eb7-135">Remember, when you configure a top-level group, its subgroups inherit all of its settings.</span></span>

## <a name="choose-apps"></a><span data-ttu-id="18eb7-136">Apps auswählen</span><span class="sxs-lookup"><span data-stu-id="18eb7-136">Choose apps</span></span>

<span data-ttu-id="18eb7-137">Sie können die folgenden app-Typen auf Geräten hinzufügen:</span><span class="sxs-lookup"><span data-stu-id="18eb7-137">You can add the following app types to devices:</span></span>
* [<span data-ttu-id="18eb7-138">Web-Apps</span><span class="sxs-lookup"><span data-stu-id="18eb7-138">Web apps</span></span>](add-web-apps-edu.md)
* <span data-ttu-id="18eb7-139">Windows 10-apps</span><span class="sxs-lookup"><span data-stu-id="18eb7-139">Windows 10 apps</span></span>
    * [<span data-ttu-id="18eb7-140">Microsoft Office</span><span class="sxs-lookup"><span data-stu-id="18eb7-140">Microsoft Office</span></span>](install-office.md)
    * [<span data-ttu-id="18eb7-141">Microsoft Store für Bildungseinrichtungen-apps</span><span class="sxs-lookup"><span data-stu-id="18eb7-141">Microsoft Store for Education apps</span></span>](acquire-store-apps.md)
    * [<span data-ttu-id="18eb7-142">Desktop-App</span><span class="sxs-lookup"><span data-stu-id="18eb7-142">Desktop apps</span></span>](add-desktop-apps-edu.md)
* <span data-ttu-id="18eb7-143">iOS-apps</span><span class="sxs-lookup"><span data-stu-id="18eb7-143">iOS apps</span></span>
    * [<span data-ttu-id="18eb7-144">Kostenlose Apps aus dem iOS-App Store</span><span class="sxs-lookup"><span data-stu-id="18eb7-144">Free iOS App Store apps</span></span>](add-apps-ios.md)
    * [<span data-ttu-id="18eb7-145">Über ein volumenprogramm erworbenen Program (VPP-apps)</span><span class="sxs-lookup"><span data-stu-id="18eb7-145">Volume purchased program (VPP) apps</span></span>](add-vpp-apps-ios.md)

<span data-ttu-id="18eb7-146">Wählen Sie eine oder mehrere apps zuweisen.</span><span class="sxs-lookup"><span data-stu-id="18eb7-146">Select one or more apps to assign.</span></span> <span data-ttu-id="18eb7-147">Apps werden sofort Ihrer Gruppe zugewiesen werden, nachdem Sie auf **Weiter**.</span><span class="sxs-lookup"><span data-stu-id="18eb7-147">Apps will immediately be assigned to your group after you click **Next**.</span></span>

  ![Bildschirm der app-Zuweisung.](./media/express-config-005-choose-apps.png)

<span data-ttu-id="18eb7-150">Intune for Education zeigt auch [beliebte apps aus dem Microsoft Store für Bildungseinrichtungen](add-popular-apps-edu.md) aus auf alle Intune for Education-Benutzer.</span><span class="sxs-lookup"><span data-stu-id="18eb7-150">Intune for Education also displays [popular apps from the Microsoft Store for Education](add-popular-apps-edu.md) from across all Intune for Education users.</span></span>


## <a name="choose-settings"></a><span data-ttu-id="18eb7-151">Wählen Sie die Einstellungen</span><span class="sxs-lookup"><span data-stu-id="18eb7-151">Choose settings</span></span>
<span data-ttu-id="18eb7-152">Express-Konfiguration zeigt allgemeine Einstellungen für Geräte und Benutzer in Intune.</span><span class="sxs-lookup"><span data-stu-id="18eb7-152">Express configuration shows you common settings for devices and users in Intune.</span></span> <span data-ttu-id="18eb7-153">Einstellungen werden in betriebssystemspezifischen Kategorien unterteilt: Einstellungen für Windows und iOS-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="18eb7-153">Settings are separated into OS-specific categories: Windows settings and iOS settings.</span></span>

<span data-ttu-id="18eb7-154">Die Standardeinstellungen werden empfohlene Werte voreingestellt.</span><span class="sxs-lookup"><span data-stu-id="18eb7-154">The default settings are preset with recommended values.</span></span> <span data-ttu-id="18eb7-155">Bleiben Sie bei der Empfehlungen und keine Änderungen vornehmen, klicken Sie auf Wunsch **Weiter**.</span><span class="sxs-lookup"><span data-stu-id="18eb7-155">If you want to stick with the recommendations, and not make any changes, click **Next**.</span></span> <span data-ttu-id="18eb7-156">Einstellungen werden sofort auf Ihre Verwaltungsgruppe angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="18eb7-156">Settings will immediately be applied to your group.</span></span> 

  ![Wählen Sie Seite mit den Einstellungen.](./media/express-config-006-choose-settings.png)


<span data-ttu-id="18eb7-159">Express-Konfiguration-Auswahl jederzeit anpassen Ihrer Schule/Universität Ändern der Richtlinien geändert werden.</span><span class="sxs-lookup"><span data-stu-id="18eb7-159">Change express configuration selections at any time to fit your school's changing policies.</span></span> <span data-ttu-id="18eb7-160">Weitere Anpassung in Intune for Education, zeigen Sie die vollständige Liste der [Windows 10](all-edu-settings-windows.md) und [iOS](all-edu-settings-ios.md) geräteeinstellungen.</span><span class="sxs-lookup"><span data-stu-id="18eb7-160">For more customization in Intune for Education, view the full list of [Windows 10](all-edu-settings-windows.md) and [iOS](all-edu-settings-ios.md) device settings.</span></span>

## <a name="review-settings"></a><span data-ttu-id="18eb7-161">Überprüfen Sie die Einstellungen</span><span class="sxs-lookup"><span data-stu-id="18eb7-161">Review settings</span></span>

<span data-ttu-id="18eb7-162">Überprüfen Sie vor dem Speichern Sie Ihre apps und Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="18eb7-162">Before saving, review your apps and settings selections.</span></span> <span data-ttu-id="18eb7-163">Klicken Sie auf **wieder** Änderungen vornehmen.</span><span class="sxs-lookup"><span data-stu-id="18eb7-163">Click **Back** to make changes.</span></span> <span data-ttu-id="18eb7-164">Wenn die Überprüfung abgeschlossen ist, klicken Sie auf **speichern**.</span><span class="sxs-lookup"><span data-stu-id="18eb7-164">When your review is complete, click **Save**.</span></span>

 ![Die Überprüfung Ihren Bildschirm für die Auswahl.](./media/express-config-007-save-changes.png)  

  ![Der letzten Seite.](./media/express-config-008-all-done.png)

## <a name="next-steps"></a><span data-ttu-id="18eb7-170">Nächste Schritte</span><span class="sxs-lookup"><span data-stu-id="18eb7-170">Next steps</span></span>
<span data-ttu-id="18eb7-171">[Weisen Sie Administratoren für](group-admin-delegate.md) können Sie die Gruppe verwalten Sie gerade erstellt haben.</span><span class="sxs-lookup"><span data-stu-id="18eb7-171">[Assign group admins](group-admin-delegate.md) to help you manage the group you just created.</span></span> <span data-ttu-id="18eb7-172">Bearbeiten Sie die Gruppe jederzeit, indem Sie unter neuen Gesichtspunkten express-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="18eb7-172">Edit your group anytime by revisiting express configuration.</span></span> <span data-ttu-id="18eb7-173">Weitere Einstellungen an [finden Sie auf der Registerkarte "Gruppen"](create-groups.md).</span><span class="sxs-lookup"><span data-stu-id="18eb7-173">To view more settings, [visit the Groups tab](create-groups.md).</span></span>

