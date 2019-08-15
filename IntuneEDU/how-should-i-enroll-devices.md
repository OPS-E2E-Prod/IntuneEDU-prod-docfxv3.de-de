---
title: Wie kann ich meine Geräte registrieren?
titleSuffix: Intune for Education
description: Informieren Sie sich über Methoden zum Registrieren Ihrer Geräte in InTune for Education.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 06/18/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 45160df9-126d-4c51-a0d3-0e9fad0fe929
searchScope:
- IntuneEDU
ms.openlocfilehash: 006fa1267566524b86acbf0e5a29235f41eb5ac2
ms.sourcegitcommit: 05576d32cac5cc3998ea579404ce84a2813c9083
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 08/09/2019
ms.locfileid: "68866730"
---
# <a name="how-should-i-enroll-devices"></a><span data-ttu-id="f4997-103">Wie kann ich Geräte registrieren?</span><span class="sxs-lookup"><span data-stu-id="f4997-103">How should I enroll devices?</span></span>

<span data-ttu-id="f4997-104">Erfahren Sie, wie Sie Geräte unter InTune for Education Management registrieren.</span><span class="sxs-lookup"><span data-stu-id="f4997-104">Learn how to enroll devices under Intune for Education management.</span></span> <span data-ttu-id="f4997-105">Um die beste Methode für Ihre Schule auszuwählen, sollten Sie Folgendes beachten:</span><span class="sxs-lookup"><span data-stu-id="f4997-105">To choose the best method for your school, consider the:</span></span>  
* <span data-ttu-id="f4997-106">Größe Ihres Bezirks.</span><span class="sxs-lookup"><span data-stu-id="f4997-106">Size of your district.</span></span>    
* <span data-ttu-id="f4997-107">Typ der Geräte Empfänger.</span><span class="sxs-lookup"><span data-stu-id="f4997-107">Type of device recipients.</span></span>    
* <span data-ttu-id="f4997-108">Anzahl von Mitarbeitern, die zur Unterstützung von verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="f4997-108">Number of staff available to help.</span></span>   
 
<span data-ttu-id="f4997-109">Lesen Sie weiter, um die beste Methode zum Registrieren von Geräten in ihrer Schule zu ermitteln.</span><span class="sxs-lookup"><span data-stu-id="f4997-109">Read on to determine the best way to enroll devices in your school.</span></span>    

## <a name="run-the-set-up-school-pcs-app"></a><span data-ttu-id="f4997-110">Ausführen der APP zum Einrichten von Schul-PCs</span><span class="sxs-lookup"><span data-stu-id="f4997-110">Run the Set up School PCs app</span></span> 
<span data-ttu-id="f4997-111">Hochladen eines einzelnen Satzes von Schul optimierten Einstellungen auf jeden Ihrer Windows 10-PCs.</span><span class="sxs-lookup"><span data-stu-id="f4997-111">Upload a single set of school-optimized settings to each of your Windows 10 PCs.</span></span> <span data-ttu-id="f4997-112">Die [app "Einrichtung von PCs](https://docs.microsoft.com/education/windows/use-set-up-school-pcs-app) " führt Sie durch die Erstellung eines Installationspakets, das für Schulen geeignet ist.</span><span class="sxs-lookup"><span data-stu-id="f4997-112">The [Set up School PCs app](https://docs.microsoft.com/education/windows/use-set-up-school-pcs-app) guides you through how to create an installation package that's appropriate for schools.</span></span> <span data-ttu-id="f4997-113">Nachdem Sie die Einstellungen für das Netzwerk und die Geräte konfiguriert haben, speichert die APP das Paket auf einem USB-Laufwerk.</span><span class="sxs-lookup"><span data-stu-id="f4997-113">After you're done configuring settings for your network and devices, the app saves the package to a USB drive.</span></span> <span data-ttu-id="f4997-114">Legen Sie das USB-Laufwerk direkt in jeden Student-PC ein, um das Gerät für ihre Studenten automatisch einzurichten.</span><span class="sxs-lookup"><span data-stu-id="f4997-114">Insert the USB drive directly in to each student PC to automatically set up the device for your students.</span></span> <span data-ttu-id="f4997-115">Die APP ist auf PCs mit Windows 10, Version 1903 und früher, kompatibel.</span><span class="sxs-lookup"><span data-stu-id="f4997-115">The app is compatible on PCs running Windows 10 version 1903 and earlier.</span></span>

## <a name="give-school-faculty-enrollment-manager-permissions"></a><span data-ttu-id="f4997-116">Erteilt dem Registrierungs-Manager für Schul Lehrkräfte Berechtigungen.</span><span class="sxs-lookup"><span data-stu-id="f4997-116">Give school faculty enrollment manager permissions</span></span>
<span data-ttu-id="f4997-117">Fügen Sie Registrierungs-Manager oder ein Registrierungs-Manager-Konto hinzu, damit Ihr Personal Ihnen beim Registrieren von Geräten behilflich ist.</span><span class="sxs-lookup"><span data-stu-id="f4997-117">Add enrollment managers, or an enrollment manager account, to allow your staff to help you enroll devices.</span></span> <span data-ttu-id="f4997-118">Registrierungs- [Manager](add-enrollment-managers.md) können bis zu 1.000 Geräte registrieren.</span><span class="sxs-lookup"><span data-stu-id="f4997-118">[Enrollment managers](add-enrollment-managers.md) can enroll up to 1,000 devices.</span></span>  

## <a name="allow-users-to-enroll-their-own-devices"></a><span data-ttu-id="f4997-119">Benutzern das Registrieren Ihrer eigenen Geräte gestatten</span><span class="sxs-lookup"><span data-stu-id="f4997-119">Allow users to enroll their own devices</span></span>
<span data-ttu-id="f4997-120">Erlauben Sie vertrauenswürdigen Benutzern, ihre eigenen Geräte zu registrieren.</span><span class="sxs-lookup"><span data-stu-id="f4997-120">Allow trusted users to enroll their own devices.</span></span> <span data-ttu-id="f4997-121">Diese Benutzer können Ihre Geräte automatisch zu Azure AD hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="f4997-121">These users are able to automatically join their devices to Azure AD.</span></span>  

## <a name="next-steps"></a><span data-ttu-id="f4997-122">Nächste Schritte</span><span class="sxs-lookup"><span data-stu-id="f4997-122">Next steps</span></span>  

<span data-ttu-id="f4997-123">Sind Sie bereit, Ihre Geräte zu registrieren?</span><span class="sxs-lookup"><span data-stu-id="f4997-123">Ready to enroll your devices?</span></span> <span data-ttu-id="f4997-124">Erfahren Sie, wie Sie [IOS](add-devices-ios-edu.md) -und [Windows 10](add-devices-windows.md) -Geräte unter InTune for Education Verwaltung hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="f4997-124">Learn how to add [iOS](add-devices-ios-edu.md) and [Windows 10](add-devices-windows.md) devices under Intune for Education management.</span></span>  

* <span data-ttu-id="f4997-125">Weitere Informationen finden Sie in der Dokumentation zum [herunterladen der APP für die **Einrichtung von Schul-PCs** ](https://www.microsoft.com/store/p/set-up-school-pcs/9nblggh4ls40) aus der Microsoft Store.</span><span class="sxs-lookup"><span data-stu-id="f4997-125">See the Store documentation to [download the **Set Up School PCs** app](https://www.microsoft.com/store/p/set-up-school-pcs/9nblggh4ls40) from the Microsoft Store.</span></span> 
* <span data-ttu-id="f4997-126">Weitere Informationen [zum Einrichten von Windows-Geräten in Schulen](https://docs.microsoft.com/education/windows/set-up-windows-10) finden Sie in der Microsoft Education > Windows-Dokumentation.</span><span class="sxs-lookup"><span data-stu-id="f4997-126">Find out more [about setting up Windows devices in schools](https://docs.microsoft.com/education/windows/set-up-windows-10) from the Microsoft Education > Windows documentation.</span></span>

