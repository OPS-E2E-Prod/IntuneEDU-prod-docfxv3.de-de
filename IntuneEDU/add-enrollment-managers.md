---
title: Fügen Sie geräteregistrierungs-Manager hinzu.
titleSuffix: Intune for Education
description: Erfahren Sie, wie Sie Geräteregistrierungs-Manager in Intune für Bildungseinrichtungen hinzufügen.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 08/30/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: b496bc02-714e-4391-b533-4c9bdcf57483
searchScope:
- IntuneEDU
ms.openlocfilehash: 26b9a9c6eaabe85dbe77acd9a52f7b86b8a99d4d
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146974"
---
# <a name="add-enrollment-managers"></a><span data-ttu-id="f9d7a-103">Fügen Sie geräteregistrierungs-Manager hinzu.</span><span class="sxs-lookup"><span data-stu-id="f9d7a-103">Add enrollment managers</span></span>  

<span data-ttu-id="f9d7a-104">Geben Sie an Ihre vorhandenen Benutzer Gerät-Registrierungsberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="f9d7a-104">Give device enrollment permissions to your existing users.</span></span> <span data-ttu-id="f9d7a-105">Benutzer mit Konten für geräteregistrierungs-Manager können bis zu 1000 Windows 10-Geräten in Intune for Education registrieren.</span><span class="sxs-lookup"><span data-stu-id="f9d7a-105">Users with device enrollment manager accounts can enroll up to 1000 Windows 10 devices in Intune for Education.</span></span>

 <span data-ttu-id="f9d7a-106">Konten für geräteregistrierungs-Manager sind hilfreich in großen Organisationen, die Tausende von freigegebenen Windows 10-Geräte zu registrieren.</span><span class="sxs-lookup"><span data-stu-id="f9d7a-106">Enrollment manager accounts are helpful in large organizations that have thousands of shared Windows 10 devices to enroll.</span></span>  

## <a name="requirements"></a><span data-ttu-id="f9d7a-107">Anforderungen</span><span class="sxs-lookup"><span data-stu-id="f9d7a-107">Requirements</span></span>  

<span data-ttu-id="f9d7a-108">Es müssen Benutzer im Azure-Portal vorhanden sein, damit sie als Geräteregistrierungs-Manager hinzugefügt werden können.</span><span class="sxs-lookup"><span data-stu-id="f9d7a-108">Users must exist in the Azure portal to be added as device enrollment managers.</span></span>

<span data-ttu-id="f9d7a-109">Registrierungsberechtigungen Gerät können nicht mit folgenden anderen Registrierungsmethoden verwendet werden: Apple Configurator mit Setup-Assistenten, mit Apple Configurator mit direkter Registrierung, Apple School Manager (ASM) oder (Device Enrollment Program, DEP).</span><span class="sxs-lookup"><span data-stu-id="f9d7a-109">Device enrollment permissions cannot be used with these other enrollment methods: Apple Configurator with Setup Assistant, Apple Configurator with direct enrollment, Apple School Manager (ASM), or Device Enrollment Program (DEP).</span></span>  

## <a name="assign-enrollment-permissions"></a><span data-ttu-id="f9d7a-110">Neue Registrierungsberechtigungen zuweisen</span><span class="sxs-lookup"><span data-stu-id="f9d7a-110">Assign enrollment permissions</span></span>  

1. <span data-ttu-id="f9d7a-111">Intune for Education-Dashboard, klicken Sie auf **Geräteregistrierungs-Manager**.</span><span class="sxs-lookup"><span data-stu-id="f9d7a-111">From the Intune for Education dashboard, click **Enrollment Managers**.</span></span>
2. <span data-ttu-id="f9d7a-112">**Klicken Sie auf Registrierungsberechtigungen zuweisen**.</span><span class="sxs-lookup"><span data-stu-id="f9d7a-112">**Click Assign enrollment permissions**.</span></span>
3. <span data-ttu-id="f9d7a-113">Wählen Sie den Benutzer, dem Sie Berechtigungen zuweisen möchten.</span><span class="sxs-lookup"><span data-stu-id="f9d7a-113">Choose the user that you want to assign permissions to.</span></span> <span data-ttu-id="f9d7a-114">Wenn Sie den Namen des Benutzers kennen, können Sie Sie in das Suchfeld suchen.</span><span class="sxs-lookup"><span data-stu-id="f9d7a-114">If you know the name of the user, you can search for them in the search field.</span></span>
4. <span data-ttu-id="f9d7a-115">Klicken Sie auf **Speichern**.</span><span class="sxs-lookup"><span data-stu-id="f9d7a-115">Click **Save**.</span></span>

## <a name="remove-enrollment-permissions"></a><span data-ttu-id="f9d7a-116">Registrierungsberechtigungen entfernen</span><span class="sxs-lookup"><span data-stu-id="f9d7a-116">Remove enrollment permissions</span></span>  
1. <span data-ttu-id="f9d7a-117">Von **Geräteregistrierungs-Manager**, fahren Sie mit der linken Seite des Bildschirms, und wählen Sie einen Benutzer.</span><span class="sxs-lookup"><span data-stu-id="f9d7a-117">From **Enrollment Managers**, go to the left side of the screen and choose a user.</span></span> 
2. <span data-ttu-id="f9d7a-118">Klicken Sie auf **Registrierungsberechtigungen entfernen**.</span><span class="sxs-lookup"><span data-stu-id="f9d7a-118">Click **Remove enrollment permissions**.</span></span>
3. <span data-ttu-id="f9d7a-119">Klicken Sie auf **entfernen** Aktion zu bestätigen.</span><span class="sxs-lookup"><span data-stu-id="f9d7a-119">Click **Remove** to confirm your action.</span></span> <span data-ttu-id="f9d7a-120">Wenn Sie einen Geräteregistrierungs-Manager entfernen, wirkt sich dies nicht auf registrierte Geräte aus.</span><span class="sxs-lookup"><span data-stu-id="f9d7a-120">Removing a device enrollment manager does not affect enrolled devices.</span></span>
  <span data-ttu-id="f9d7a-121">![Entfernen Sie die Registrierung Schaltfläche "Berechtigungen" beim Anzeigen einer einzelnen Geräteregistrierungs-Manager-Seite aktiviert wurde.](./media/enroll-mgrs-003-remove-enrollment-permissions.png)</span><span class="sxs-lookup"><span data-stu-id="f9d7a-121">![Remove enrollment permissions button selected while viewing an individual Enrollment Manager's page](./media/enroll-mgrs-003-remove-enrollment-permissions.png)</span></span>
