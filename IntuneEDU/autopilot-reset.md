---
title: Verwenden von Autopilot Reset zum Neukonfigurieren von Geräten mit InTune for Education
titleSuffix: Intune for Education
description: Erfahren Sie, wie Sie Autopilot in InTune for Education zurücksetzen.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/17/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: ''
searchScope:
- IntuneEDU
ms.openlocfilehash: 23430e2902eeb5673f1915b1a9e547bdde1e17dd
ms.sourcegitcommit: 05576d32cac5cc3998ea579404ce84a2813c9083
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 08/09/2019
ms.locfileid: "68866715"
---
# <a name="autopilot-reset"></a><span data-ttu-id="010a4-103">Autopilot zurücksetzen</span><span class="sxs-lookup"><span data-stu-id="010a4-103">Autopilot Reset</span></span>
<span data-ttu-id="010a4-104">Sie können Autopilot Reset verwenden, um persönliche Dateien, Apps und Einstellungen von ihren Geräten zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="010a4-104">You can use Autopilot Reset to remove personal files, apps, and settings from your devices.</span></span> <span data-ttu-id="010a4-105">Die Geräte bleiben in InTune registriert und werden wieder in einen vollständig konfigurierten oder bekannten, von ihm genehmigten Zustand versetzt.</span><span class="sxs-lookup"><span data-stu-id="010a4-105">The devices remain enrolled in Intune and are returned to a fully-configured or known IT-approved state.</span></span>
<span data-ttu-id="010a4-106">Sie können Autopilot ein Gerät lokal oder Remote über das InTune for Education-Portal zurücksetzen.</span><span class="sxs-lookup"><span data-stu-id="010a4-106">You can Autopilot Reset a device locally or remotely from the Intune for Education portal.</span></span>  

<span data-ttu-id="010a4-107">Wenn Sie das InTune for Education-Portal verwenden, vermeiden Sie, dass IT-Mitarbeiter jedes Gerät besuchen müssen, um den Prozess zu starten.</span><span class="sxs-lookup"><span data-stu-id="010a4-107">Using the Intune for Education portal, you avoid the need for IT staff to visit each device to start the process.</span></span> <span data-ttu-id="010a4-108">Im Portal können Sie ein einzelnes Gerät zurücksetzen oder eine Massen Zurücksetzung für alle Geräte in einer Gruppe ausführen.</span><span class="sxs-lookup"><span data-stu-id="010a4-108">From the portal, you can reset a single device or do a bulk reset for all devices in a group.</span></span> <span data-ttu-id="010a4-109">Durch das Zurücksetzen aller Geräte in einer Gruppe können Sie Student-Geräte schnell zurücksetzen und neu konfigurieren, um Sie auf das neue Schul Jahr vorzubereiten.</span><span class="sxs-lookup"><span data-stu-id="010a4-109">Resetting all devices in a group lets you quickly wipe and reconfigure student devices to prepare them for the new school year.</span></span>  

<span data-ttu-id="010a4-110">Nach dem Zurücksetzen werden die ursprünglichen Einstellungen auf das Gerät angewendet und dann mit InTune synchronisiert, um die neuesten Richtlinien zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="010a4-110">After a reset, the original settings are applied to the device and then it syncs with Intune to get the latest policies.</span></span> <span data-ttu-id="010a4-111">Bei der Verwendung der Autopilot-Zurücksetzung auf einem Gerät, wird dessen primäre Benutzer entfernt.</span><span class="sxs-lookup"><span data-stu-id="010a4-111">When Autopilot reset is used on a device, the device's primary user will be removed.</span></span> <span data-ttu-id="010a4-112">Der nächste Benutzer, der sich nach dem Zurücksetzen anmeldet, wird als primärer Benutzer festgelegt.</span><span class="sxs-lookup"><span data-stu-id="010a4-112">The next user who signs in after the reset will be set as the primary user.</span></span>   

## <a name="requirements"></a><span data-ttu-id="010a4-113">Anforderungen</span><span class="sxs-lookup"><span data-stu-id="010a4-113">Requirements</span></span>
<span data-ttu-id="010a4-114">Die Verwendung von Autopilot Reset lokal steht nur für Geräte mit Windows 10, Version 1709 oder höher, zur Verfügung.</span><span class="sxs-lookup"><span data-stu-id="010a4-114">Using Autopilot Reset locally is only available for devices running Windows 10 version 1709 or later.</span></span>
<span data-ttu-id="010a4-115">Die Verwendung von Autopilot Remote Reset ist nur für Geräte verfügbar, auf denen Windows 10 Build 17672 oder höher ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="010a4-115">Using Autopilot Reset remotely is only available for devices running Windows 10 build 17672 or later.</span></span>

## <a name="use-autopilot-reset-locally"></a><span data-ttu-id="010a4-116">Verwenden von Autopilot Reset lokal</span><span class="sxs-lookup"><span data-stu-id="010a4-116">Use Autopilot Reset locally</span></span>
<span data-ttu-id="010a4-117">Wenn Sie ein einzelnes Gerät löschen müssen, können Sie dies direkt auf dem Gerät durchführen.</span><span class="sxs-lookup"><span data-stu-id="010a4-117">If you need to wipe a single device, you can do so directly on the device.</span></span> <span data-ttu-id="010a4-118">Drücken Sie auf dem Gerät STRG + Win + R.</span><span class="sxs-lookup"><span data-stu-id="010a4-118">On the device, press CTRL+WIN+R.</span></span> <span data-ttu-id="010a4-119">Nach dem Drücken von STRG + Win + R müssen Sie sich mit Administrator Anmelde Informationen authentifizieren, um die zurück Setzung zu initiieren.</span><span class="sxs-lookup"><span data-stu-id="010a4-119">After pressing Ctrl+WIN+R, you’ll have to authenticate with admin credentials in order to trigger the reset.</span></span>

## <a name="use-autopilot-reset-remotely-for-a-single-device"></a><span data-ttu-id="010a4-120">Verwenden der Autopilot-zurück setzung für ein einzelnes Gerät</span><span class="sxs-lookup"><span data-stu-id="010a4-120">Use Autopilot Reset remotely for a single device</span></span>
1. <span data-ttu-id="010a4-121">Wählen Sie in InTune for Education **Gruppen** aus, > Sie eine Gerätegruppe auswählen.</span><span class="sxs-lookup"><span data-stu-id="010a4-121">In Intune for Education, choose **Groups** > choose a device group.</span></span>
2. <span data-ttu-id="010a4-122">Wählen Sie ein Gerät > **Autopilot Reset**aus.</span><span class="sxs-lookup"><span data-stu-id="010a4-122">Select a device > **Autopilot Reset**.</span></span> <span data-ttu-id="010a4-123">Um das Zurücksetzen zu bestätigen, wählen Sie erneut **Autopilot Reset** aus.</span><span class="sxs-lookup"><span data-stu-id="010a4-123">To confirm the reset, select **Autopilot Reset** again.</span></span>
2.  <span data-ttu-id="010a4-124">Wenn die zurück Setzung initiiert wird, wird eine Meldung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="010a4-124">A message appears when the reset is initiated.</span></span> <span data-ttu-id="010a4-125">Das Gerät wird zurückgesetzt, wenn es das nächste Mal eine Verbindung mit dem Internet herstellt.</span><span class="sxs-lookup"><span data-stu-id="010a4-125">The device will reset the next time it connects to the Internet.</span></span>  

## <a name="use-autopilot-reset-remotely-for-devices-in-bulk"></a><span data-ttu-id="010a4-126">Remote Zurücksetzung von Autopilot für Geräte per Massen Vorgang verwenden</span><span class="sxs-lookup"><span data-stu-id="010a4-126">Use Autopilot Reset remotely for devices in bulk</span></span>  
1.  <span data-ttu-id="010a4-127">Wählen Sie in InTune for Education **Gruppen** aus, > Wählen Sie die Gruppe aus.</span><span class="sxs-lookup"><span data-stu-id="010a4-127">In Intune for Education, choose **Groups** > choose the group.</span></span>
2. <span data-ttu-id="010a4-128">Wählen Sie **Autopilot alle Geräte zurücksetzen**aus.</span><span class="sxs-lookup"><span data-stu-id="010a4-128">Select **Autopilot Reset all devices**.</span></span>
2. <span data-ttu-id="010a4-129">Geben Sie im **Gruppenfeld Autopilot Reset** den Namen der aktuellen Gruppe ein.</span><span class="sxs-lookup"><span data-stu-id="010a4-129">In the **Autopilot Reset group** box, type the name of the current group.</span></span> <span data-ttu-id="010a4-130">Wählen Sie dann **Autopilot Reset** aus, um dies zu bestätigen.</span><span class="sxs-lookup"><span data-stu-id="010a4-130">Then select **Autopilot Reset** to confirm.</span></span>
3.  <span data-ttu-id="010a4-131">Jedes Gerät wird zurückgesetzt, wenn es das nächste Mal eine Verbindung mit dem Internet herstellt.</span><span class="sxs-lookup"><span data-stu-id="010a4-131">Each device will be reset the next time that it connects to the Internet.</span></span> <span data-ttu-id="010a4-132">Wenn eines der Geräte das Zurücksetzen des Remote Autopilot-Geräts nicht unterstützt, wird eine Tabelle mit dem Namen " **Geräte" nicht zurückgesetzt**.</span><span class="sxs-lookup"><span data-stu-id="010a4-132">If any of the devices don’t support remote Autopilot Reset, you'll see a table named **Devices failed to reset**.</span></span> <span data-ttu-id="010a4-133">In der Tabelle werden die einzelnen Geräte und der Grund aufgeführt, warum Sie nicht zurückgesetzt werden konnten.</span><span class="sxs-lookup"><span data-stu-id="010a4-133">The table lists each device and the reason that it couldn't be reset.</span></span>  

## <a name="next-steps"></a><span data-ttu-id="010a4-134">Nächste Schritte</span><span class="sxs-lookup"><span data-stu-id="010a4-134">Next steps</span></span>
[<span data-ttu-id="010a4-135">Verwalten von Geräten mit Remoteaktionen</span><span class="sxs-lookup"><span data-stu-id="010a4-135">Manage devices with remote actions</span></span>](edu-device-remote-actions.md)



