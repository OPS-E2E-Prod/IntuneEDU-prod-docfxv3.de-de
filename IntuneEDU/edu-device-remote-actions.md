---
title: Remotegeräteaktionen in Intune for Education
titleSuffix: Intune for Education
description: Erfahren Sie, wie Sie behandeln und Verwalten von Geräten mit entfernten Remoteaktionen mit.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 01/30/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: df7cabf2-1723-4817-b16c-800407a0c753
searchScope:
- IntuneEDU
ms.openlocfilehash: f19a24c78ad3a155b33ccc05bc266160fce7387e
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146770"
---
# <a name="manage-devices-remotely"></a><span data-ttu-id="ca14e-103">Verwalten von Geräten per Remotezugriff</span><span class="sxs-lookup"><span data-stu-id="ca14e-103">Manage devices remotely</span></span>  

<span data-ttu-id="ca14e-104">Wenn Sie einen anderen Speicherort als ein Gerät oder der Benutzer angemeldet und sie die Problembehandlung zu unterstützen müssen, verwenden Sie die Remoteaktionen in Intune for Education.</span><span class="sxs-lookup"><span data-stu-id="ca14e-104">If you're in a different location than a device or its user, and need to help them troubleshoot, use the remote actions in Intune for Education.</span></span>  


## <a name="remote-actions-for-devices"></a><span data-ttu-id="ca14e-105">Remoteaktionen für Geräte</span><span class="sxs-lookup"><span data-stu-id="ca14e-105">Remote actions for devices</span></span>  

![Beispielscreenshot mit Intune Education 7 Remoteaktionen.](./media/1812_Intune_EDU_Manage_Remote.png)  

<span data-ttu-id="ca14e-107">Navigieren Sie zu dem Dashboard **Geräte**.</span><span class="sxs-lookup"><span data-stu-id="ca14e-107">From the dashboard, go to **Devices**.</span></span> <span data-ttu-id="ca14e-108">Wählen Sie das Gerät, das Sie verwalten möchten.</span><span class="sxs-lookup"><span data-stu-id="ca14e-108">Select the device that you want to manage.</span></span> <span data-ttu-id="ca14e-109">Wählen Sie am unteren Rand der Seite die folgenden Aktionen aus:</span><span class="sxs-lookup"><span data-stu-id="ca14e-109">At the bottom of the page, select any of the following actions:</span></span>

- <span data-ttu-id="ca14e-110">**Starten Sie neu**: Schaltet das Gerät aus, und startet ihn neu.</span><span class="sxs-lookup"><span data-stu-id="ca14e-110">**Restart**: Powers off the device and restarts it.</span></span>
- <span data-ttu-id="ca14e-111">**Auf Werkseinstellungen zurücksetzen:** Das Gerät aus Intune-Verwaltung entfernt, und alle Daten und Einstellungen vom Gerät entfernt.</span><span class="sxs-lookup"><span data-stu-id="ca14e-111">**Factory reset**: Removes the device from Intune management and removes all data and settings from the device.</span></span> 
- <span data-ttu-id="ca14e-112">**Gerät synchronisieren**: Stellt sicher, dass das Gerät auf dem neuesten Stand Einstellungen, app-Zuweisungen und Gruppenmitgliedschaften verfügt.</span><span class="sxs-lookup"><span data-stu-id="ca14e-112">**Sync device**: Ensures that device has up-to-date settings, app assignments, and group memberships.</span></span> <span data-ttu-id="ca14e-113">Diese Aktion kann helfen, wenn Sie versuchen, ein Gerät zu beheben.</span><span class="sxs-lookup"><span data-stu-id="ca14e-113">This action can help if you're trying to troubleshoot a device.</span></span>  
- <span data-ttu-id="ca14e-114">**Zurücksetzen des AutoPilot**: Entfernt alle Benutzerdaten&ndash;z. B. Benutzer installierten apps und persönlichen Einstellungen&ndash;und Windows 10-Geräts bei Intune registriert sind.</span><span class="sxs-lookup"><span data-stu-id="ca14e-114">**Autopilot Reset**: Removes all user data&ndash;including user-installed apps and personal settings&ndash;and keeps the Windows 10 device enrolled in Intune.</span></span> <span data-ttu-id="ca14e-115">Das Gerät wird auf dem neuesten Stand mit den neuesten apps, Richtlinien und Einstellungen beibehalten.</span><span class="sxs-lookup"><span data-stu-id="ca14e-115">The device is kept up-to-date with the latest apps, policies, and settings.</span></span> <span data-ttu-id="ca14e-116">Eine Benachrichtigung angezeigt wird, wenn das Zurücksetzen initiiert wird.</span><span class="sxs-lookup"><span data-stu-id="ca14e-116">A notification appears when the reset is initiated.</span></span> <span data-ttu-id="ca14e-117">Das Gerät wird beim nächsten Herstellen einer Verbindung mit dem Internet zurückgesetzt.</span><span class="sxs-lookup"><span data-stu-id="ca14e-117">The device resets the next time it connects to the internet.</span></span>  
- <span data-ttu-id="ca14e-118">**Gerät umbenennen**: Gibt dem Gerät einen neuen Namen an.</span><span class="sxs-lookup"><span data-stu-id="ca14e-118">**Rename device**: Gives the device a new name.</span></span> <span data-ttu-id="ca14e-119">Der neue Name Updates in Intune und lokal auf dem Gerät.</span><span class="sxs-lookup"><span data-stu-id="ca14e-119">The new name updates in Intune and locally, on the device.</span></span> <span data-ttu-id="ca14e-120">Sie müssen das Windows-Gerät für den neuen Namen wirksam neu starten.</span><span class="sxs-lookup"><span data-stu-id="ca14e-120">You must restart your Windows device for the new name to take effect.</span></span>  
- <span data-ttu-id="ca14e-121">**Löschen von Gerät**: Hebt die Registrierung des Geräts bei Intune für Bildungseinrichtungen, und das Gerät aus Azure Active Directory entfernt.</span><span class="sxs-lookup"><span data-stu-id="ca14e-121">**Delete device**: Unenrolls the device from Intune for Education and removes the device from Azure Active Directory.</span></span> <span data-ttu-id="ca14e-122">Ein gelöschtes Gerät kann nicht mehr Ihrer Schule-Ressourcen zugreifen.</span><span class="sxs-lookup"><span data-stu-id="ca14e-122">A deleted device can no longer access your school's resources.</span></span> 

## <a name="remote-actions-for-users"></a><span data-ttu-id="ca14e-123">Remoteaktionen für Benutzer</span><span class="sxs-lookup"><span data-stu-id="ca14e-123">Remote actions for users</span></span>  

<span data-ttu-id="ca14e-124">Navigieren Sie zu dem Dashboard **Benutzer**.</span><span class="sxs-lookup"><span data-stu-id="ca14e-124">From the dashboard, go to **Users**.</span></span> <span data-ttu-id="ca14e-125">Wählen Sie den Benutzer, den Sie verwalten möchten.</span><span class="sxs-lookup"><span data-stu-id="ca14e-125">Select the user that you want to manage.</span></span> <span data-ttu-id="ca14e-126">Wählen Sie am unteren Rand der Seite, **Zurücksetzen des Kennworts**.</span><span class="sxs-lookup"><span data-stu-id="ca14e-126">At the bottom of the page, select **Reset password**.</span></span> <span data-ttu-id="ca14e-127">Diese Aktion setzt ein Kennwort alte, verloren oder vergessen haben, auf dem Gerät des Benutzers zurück.</span><span class="sxs-lookup"><span data-stu-id="ca14e-127">This action resets an old, lost, or forgotten password on the user's device.</span></span>  
