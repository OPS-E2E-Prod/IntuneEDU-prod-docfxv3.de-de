---
title: Registrieren von iOS-Geräte in der Verwaltung
titleSuffix: Intune for Education
description: Informationen Sie zum Einrichten von Windows 10-Geräte für Intune for Education.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 05/16/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: c884df47-61a9-4799-a407-8cd311d376d1
searchScope:
- IntuneEDU
ms.openlocfilehash: 944840d0bfaa05fdcb5e099513fc5b7836068f7b
ms.sourcegitcommit: 370c0b29e905c25204a72fd5877000698ac859a9
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/16/2019
ms.locfileid: "65813873"
---
# <a name="enroll-ios-devices-in-intune-for-education"></a><span data-ttu-id="3ee1d-103">Registrieren von iOS-Geräte in Intune for Education</span><span class="sxs-lookup"><span data-stu-id="3ee1d-103">Enroll iOS devices in Intune for Education</span></span>

<span data-ttu-id="3ee1d-104">Geräte sind bereit für einschalten und nach dem in der Verwaltung zu registrieren:</span><span class="sxs-lookup"><span data-stu-id="3ee1d-104">Devices are ready to power on and enroll in management after you:</span></span>

* <span data-ttu-id="3ee1d-105">Einrichten von Intune for Education [mit School Informationen](what-is-school-data-sync.md) – z. B. Studentendatensätze, apps und Einstellungen für Geräte.</span><span class="sxs-lookup"><span data-stu-id="3ee1d-105">Set up Intune for Education [with school information](what-is-school-data-sync.md) — such as student records, apps, and settings for devices.</span></span>
* <span data-ttu-id="3ee1d-106">Aktivieren Sie für die Verwaltung von iOS-Geräte von Intune [Einrichten der Apple-MDM Push-Zertifikat und ein Token von Apple-MDM-Server](setup-ios-device-management.md#add-an-mdm-push-certificate).</span><span class="sxs-lookup"><span data-stu-id="3ee1d-106">Enable Intune for iOS device management by [setting up the Apple Push MDM certificate and Apple MDM Server tokens](setup-ios-device-management.md#add-an-mdm-push-certificate).</span></span>
* <span data-ttu-id="3ee1d-107">[Synchronisieren Sie Ihre Apple-MDM-Server-Token](setup-ios-device-management.md#sync-managed-devices) mit Intune Education und eine Liste der Geräte kann jetzt registrieren.</span><span class="sxs-lookup"><span data-stu-id="3ee1d-107">[Sync your Apple MDM Server tokens](setup-ios-device-management.md#sync-managed-devices) with Intune for Education and see a list of ready-to-enroll devices.</span></span>  

> [!NOTE]
> <span data-ttu-id="3ee1d-108">Stellen Sie sicher, dass Ihre Geräte mit dem Internet verbunden sind, und Ihr Konto verfügt, genügend Intune for Education-Gerät-Lizenzen, um das Setup abzuschließen.</span><span class="sxs-lookup"><span data-stu-id="3ee1d-108">Make sure your devices are connected to the Internet and your account has enough Intune for Education device licenses to complete setup.</span></span> <span data-ttu-id="3ee1d-109">Erfahren Sie mehr über die Lizenzierung in [Zuweisen von Lizenzen zu Benutzern](https://docs.microsoft.com/intune/get-started/start-with-a-paid-subscription-to-microsoft-intune-step-4).</span><span class="sxs-lookup"><span data-stu-id="3ee1d-109">Find out more about licensing in [Assign licenses to users](https://docs.microsoft.com/intune/get-started/start-with-a-paid-subscription-to-microsoft-intune-step-4).</span></span>

## <a name="preconfigured-enrollment-profile"></a><span data-ttu-id="3ee1d-110">Vorkonfigurierte Anmeldungsprofil erstellen</span><span class="sxs-lookup"><span data-stu-id="3ee1d-110">Preconfigured enrollment profile</span></span>  
<span data-ttu-id="3ee1d-111">Intune for Education erstellt und weist jedes synchronisierten Gerät ein Registrierungsprofil für Schule optimiert.</span><span class="sxs-lookup"><span data-stu-id="3ee1d-111">Intune for Education creates and assigns each synced device a school-optimized enrollment profile.</span></span>  

<span data-ttu-id="3ee1d-112">Registrierungsprofile werden konfiguriert, um dem Gerät mitzuteilen, wie Sie selbst einrichten und registrieren in der Verwaltung.</span><span class="sxs-lookup"><span data-stu-id="3ee1d-112">Enrollment profiles are configured to tell the device how to set itself up and enroll in management.</span></span> <span data-ttu-id="3ee1d-113">Intune konfiguriert die Einstellungen zum Beschleunigen Ihrer Registrierung.</span><span class="sxs-lookup"><span data-stu-id="3ee1d-113">Intune configures the settings to help speed up your enrollment.</span></span>  <span data-ttu-id="3ee1d-114">Wenn Sie auf dem Gerät einschalten, beginnt das Registrierungsprofil sofort die Einrichtung Ihres Geräts.</span><span class="sxs-lookup"><span data-stu-id="3ee1d-114">When you power on the device, the enrollment profile immediately begins setting up your device.</span></span>

## <a name="preconfigured-settings"></a><span data-ttu-id="3ee1d-115">Vorkonfigurierte Einstellungen</span><span class="sxs-lookup"><span data-stu-id="3ee1d-115">Preconfigured settings</span></span>  
<span data-ttu-id="3ee1d-116">Während der Installation des ersten Gerät Registrieren von Geräten mit den folgenden Konfigurationen:</span><span class="sxs-lookup"><span data-stu-id="3ee1d-116">During initial device setup, devices enroll with the following configurations:</span></span>

* <span data-ttu-id="3ee1d-117">Ohne benutzeraffinität</span><span class="sxs-lookup"><span data-stu-id="3ee1d-117">No user affinity</span></span>
* <span data-ttu-id="3ee1d-118">Im überwachten Modus aktiviert</span><span class="sxs-lookup"><span data-stu-id="3ee1d-118">Supervised mode enabled</span></span>
* <span data-ttu-id="3ee1d-119">Synchronisieren oder Kopplung mit anderen Geräten blockiert</span><span class="sxs-lookup"><span data-stu-id="3ee1d-119">Blocked from syncing or pairing with other devices</span></span>
* <span data-ttu-id="3ee1d-120">Gesperrte Registrierung können Benutzer von Bedeutung nicht verwaltungseinstellungen auf ihren Geräten ändern</span><span class="sxs-lookup"><span data-stu-id="3ee1d-120">Locked enrollment, meaning users can't change management settings on their devices</span></span>  

<span data-ttu-id="3ee1d-121">Intune for Education gilt ein Benennungsschema für Geräte, die Sie mit einem MDM-Server-Token zu registrieren.</span><span class="sxs-lookup"><span data-stu-id="3ee1d-121">Intune for Education applies a naming scheme to devices that you enroll with an MDM server token.</span></span> <span data-ttu-id="3ee1d-122">Standardmäßig werden die Geräte mit die Seriennummer des Geräts benannt.</span><span class="sxs-lookup"><span data-stu-id="3ee1d-122">By default, devices are named with their device serial number.</span></span> <span data-ttu-id="3ee1d-123">Sie können auch einen benutzerdefinierten Namen hinzufügen, wenn Sie Ihr MDM-Server-Token einrichten.</span><span class="sxs-lookup"><span data-stu-id="3ee1d-123">You can also add on a custom device name when you set up your MDM server token.</span></span>  

<span data-ttu-id="3ee1d-124">Die folgenden Einstellungen des Setup-Assistenten werden während der Registrierung ausgeblendet:</span><span class="sxs-lookup"><span data-stu-id="3ee1d-124">The following Setup Assistant settings are hidden during enrollment:</span></span>
* <span data-ttu-id="3ee1d-125">Kennung-setup</span><span class="sxs-lookup"><span data-stu-id="3ee1d-125">Passcode setup</span></span>
* <span data-ttu-id="3ee1d-126">Ortungsdienste</span><span class="sxs-lookup"><span data-stu-id="3ee1d-126">Location Services</span></span>
* <span data-ttu-id="3ee1d-127">Gerätewiederherstellung</span><span class="sxs-lookup"><span data-stu-id="3ee1d-127">Device restore</span></span>
* <span data-ttu-id="3ee1d-128">iCloud und Apple-ID</span><span class="sxs-lookup"><span data-stu-id="3ee1d-128">iCloud & Apple ID</span></span>
* <span data-ttu-id="3ee1d-129">Touch ID-Einrichtung</span><span class="sxs-lookup"><span data-stu-id="3ee1d-129">Touch ID setup</span></span>
* <span data-ttu-id="3ee1d-130">Apple Pay-setup</span><span class="sxs-lookup"><span data-stu-id="3ee1d-130">Apple Pay setup</span></span>
* <span data-ttu-id="3ee1d-131">Anzeigeoptionen für Zoom</span><span class="sxs-lookup"><span data-stu-id="3ee1d-131">Display Zoom options</span></span>
* <span data-ttu-id="3ee1d-132">Siri-setup</span><span class="sxs-lookup"><span data-stu-id="3ee1d-132">Siri setup</span></span>
* <span data-ttu-id="3ee1d-133">Optionen des Diagnose-Daten</span><span class="sxs-lookup"><span data-stu-id="3ee1d-133">Diagnostics Data options</span></span>  


<span data-ttu-id="3ee1d-134">Die folgende Einstellung für die Setup-Assistent wird während der Registrierung angezeigt:</span><span class="sxs-lookup"><span data-stu-id="3ee1d-134">The following Setup Assistant setting is shown during enrollment:</span></span>
* <span data-ttu-id="3ee1d-135">Geschäftsbedingungen</span><span class="sxs-lookup"><span data-stu-id="3ee1d-135">Terms and Conditions</span></span>

### <a name="what-is-setup-assistant"></a><span data-ttu-id="3ee1d-136">Was ist die Setup-Assistenten?</span><span class="sxs-lookup"><span data-stu-id="3ee1d-136">What is Setup Assistant?</span></span>
<span data-ttu-id="3ee1d-137">Beim ersten, die Sie auf Ihrem Gerät aktivieren Intune für Bildungseinrichtungen der iOS-Out-of-Box-Oberfläche, startet namens *Setup-Assistenten*.</span><span class="sxs-lookup"><span data-stu-id="3ee1d-137">The first time that you turn on your device, Intune for Education launches the iOS out-of-box experience, called *Setup Assistant*.</span></span> <span data-ttu-id="3ee1d-138">Der Setup-Assistent führt Sie durch eine Reihe von Bildschirmen und bereitet Ihr Gerät für die Verwendung des "School".</span><span class="sxs-lookup"><span data-stu-id="3ee1d-138">Setup Assistant walks you through a series of screens and prepares your device for school use.</span></span>  

## <a name="enroll-a-device"></a><span data-ttu-id="3ee1d-139">Registrieren eines Geräts</span><span class="sxs-lookup"><span data-stu-id="3ee1d-139">Enroll a device</span></span>

<span data-ttu-id="3ee1d-140">Führen Sie durch die folgenden Schritte aus, um vollständige geräteregistrierung.</span><span class="sxs-lookup"><span data-stu-id="3ee1d-140">Walk through the following steps to complete device enrollment.</span></span>

1. <span data-ttu-id="3ee1d-141">Schalten Sie Ihr iOS-Gerät ein.</span><span class="sxs-lookup"><span data-stu-id="3ee1d-141">Turn on your iOS device.</span></span> 
2. <span data-ttu-id="3ee1d-142">Stellen Sie auf Ihrem Gerät eine WLAN-Verbindung her, nachdem Sie Ihre **Sprache** ausgewählt haben.</span><span class="sxs-lookup"><span data-stu-id="3ee1d-142">After you select your **Language**, connect your device to Wi-Fi.</span></span>
3. <span data-ttu-id="3ee1d-143">Auf der **Einrichten der iOS-Gerät** auf Ihre **Land/Region**.</span><span class="sxs-lookup"><span data-stu-id="3ee1d-143">On the **Set up iOS device** screen, select your **Country/Region**.</span></span>
4. <span data-ttu-id="3ee1d-144">Befolgen Sie die Anweisungen auf dem Bildschirm, um automatisch oder manuell für die WLAN-Verbindung ein.</span><span class="sxs-lookup"><span data-stu-id="3ee1d-144">Follow the instructions on screen to automatically or manually connect to Wi-Fi.</span></span> <span data-ttu-id="3ee1d-145">Nach dem Sie verbunden sind, die **Konfiguration** angezeigt wird, mit den Registrierungsdetails.</span><span class="sxs-lookup"><span data-stu-id="3ee1d-145">After you're connected, the **Configuration** screen appears, with enrollment details.</span></span>  
5. <span data-ttu-id="3ee1d-146">Akzeptieren Sie die **Geschäftsbedingungen**.</span><span class="sxs-lookup"><span data-stu-id="3ee1d-146">Agree to the **Terms and Conditions**.</span></span> <span data-ttu-id="3ee1d-147">Klicken Sie dann entscheiden Sie, wenn Sie Diagnoseinformationen an Apple senden möchten.</span><span class="sxs-lookup"><span data-stu-id="3ee1d-147">Then decide if you want to send diagnostic information to Apple.</span></span>  

## <a name="next-steps"></a><span data-ttu-id="3ee1d-148">Nächste Schritte</span><span class="sxs-lookup"><span data-stu-id="3ee1d-148">Next steps</span></span>
<span data-ttu-id="3ee1d-149">Nun, dass Geräte eingerichtet und einsatzbereit für die Verwendung des "School" festgelegt sind, werden Informationen Sie zum Aktualisieren, überwachen und beheben Sie diese.</span><span class="sxs-lookup"><span data-stu-id="3ee1d-149">Now that devices are set up and ready for school use, learn how to update, monitor, and troubleshoot them.</span></span>   
* <span data-ttu-id="3ee1d-150">Fügen Sie weitere [kostenlose](add-apps-ios.md) und [VPP](add-vpp-apps-ios.md) iOS-apps im Laufe des Jahres Schule</span><span class="sxs-lookup"><span data-stu-id="3ee1d-150">Add more [free](add-apps-ios.md) and [VPP](add-vpp-apps-ios.md) iOS apps throughout the school year</span></span>
* <span data-ttu-id="3ee1d-151">Weisen Sie [Gruppe Administratoren](group-admin-delegate.md) helfen Ihnen beim Verwalten von Classroom-Einstellungen innerhalb Ihrer Schule/Universität oder in der Region</span><span class="sxs-lookup"><span data-stu-id="3ee1d-151">Assign [group admins](group-admin-delegate.md) to help you manage classroom settings within your school or across the district</span></span>
* <span data-ttu-id="3ee1d-152">Erfahren Sie, wie [einstellungsvererbung](settings-inheritance.md) wirkt sich auf neue Gruppen</span><span class="sxs-lookup"><span data-stu-id="3ee1d-152">Learn how [settings inheritance](settings-inheritance.md) affects new groups</span></span>
* <span data-ttu-id="3ee1d-153">Überprüfen Sie [Berichte](what-are-reports.md) zu ermitteln, identifizieren und Beheben von Fehlern</span><span class="sxs-lookup"><span data-stu-id="3ee1d-153">Review [reports](what-are-reports.md) to pinpoint and troubleshoot errors</span></span> 
* <span data-ttu-id="3ee1d-154">Erneuern Sie [iOS-Zertifikate und Token](renew-ios-certificate-token.md) jedes Jahr</span><span class="sxs-lookup"><span data-stu-id="3ee1d-154">Renew [iOS certificates and tokens](renew-ios-certificate-token.md) every year</span></span>
