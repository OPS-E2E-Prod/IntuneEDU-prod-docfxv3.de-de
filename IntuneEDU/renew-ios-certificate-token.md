---
title: Apple-MDM-Zertifikat erneuern
titleSuffix: Intune for Education
description: Erfahren Sie, wie abgelaufene Zertifikate oder Token in Intune for Education-Portals zu erneuern.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: c884df47-61a9-4799-a407-8cd311d376d1
searchScope:
- IntuneEDU
ms.openlocfilehash: a5989a02466183e4c891851598ffc885588c78fe
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146609"
---
# <a name="renew-ios-certificate-and-tokens"></a><span data-ttu-id="703bc-103">IOS-Zertifikat und Token zu erneuern</span><span class="sxs-lookup"><span data-stu-id="703bc-103">Renew iOS certificate and tokens</span></span>
<span data-ttu-id="703bc-104">Apple-MDM-Push-Zertifikate, MDM-Server-Token und VPP-Token ablaufen 365 Tage nach ihrer Erstellung.</span><span class="sxs-lookup"><span data-stu-id="703bc-104">Apple MDM Push certificates, MDM server tokens, and VPP tokens expire 365 days after you create them.</span></span> <span data-ttu-id="703bc-105">Intune for Education informiert Sie, wenn ein Zertifikat oder das Token ist nahe oder hinter seinem Ablaufdatum.</span><span class="sxs-lookup"><span data-stu-id="703bc-105">Intune for Education will alert you when a certificate or token is close to or past its expiration date.</span></span> 

<span data-ttu-id="703bc-106">Stellen Sie sicher, erneuern, um die Verbindung zwischen Ihrem Intune für Bildungseinrichtungen-Konto und Apple-Konto zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="703bc-106">Make sure to renew them to maintain the connection between your Intune for Education account and Apple account.</span></span>  

## <a name="renew-apple-mdm--certificate"></a><span data-ttu-id="703bc-107">Apple-MDM-Zertifikat erneuern</span><span class="sxs-lookup"><span data-stu-id="703bc-107">Renew Apple MDM  certificate</span></span>  
> [!IMPORTANT]
> <span data-ttu-id="703bc-108">Wenn das Apple-MDM-Zertifikat abläuft oder gelöscht wird, müssen Sie zum Zurücksetzen und Geräte mit einem neuen Zertifikat erneut registrieren.</span><span class="sxs-lookup"><span data-stu-id="703bc-108">If the Apple MDM certificate expires or is deleted, you will need to reset and re-enroll devices with a new certificate.</span></span>  

<span data-ttu-id="703bc-109">Das MDM-Push-Zertifikat, das mit der Apple-ID, die Sie zu ihrer Erstellung verwendet zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="703bc-109">The MDM push certificate is associated with the Apple ID you used to create it.</span></span> <span data-ttu-id="703bc-110">Erneuern Sie das Zertifikat mit diesem gleichen Apple-ID.</span><span class="sxs-lookup"><span data-stu-id="703bc-110">Renew the certificate with this same Apple ID.</span></span>

1. <span data-ttu-id="703bc-111">Intune for Education-Dashboard, klicken Sie auf **Mandanteneinstellungen** > **iOS-Geräteverwaltung**.</span><span class="sxs-lookup"><span data-stu-id="703bc-111">From the Intune for Education dashboard, click **Tenant settings** > **iOS Device Management**.</span></span>
2. <span data-ttu-id="703bc-112">Klicken Sie auf die **MDM-Push-Zertifikat** Registerkarte.</span><span class="sxs-lookup"><span data-stu-id="703bc-112">Click the **MDM Push Certificate** tab.</span></span>
3. <span data-ttu-id="703bc-113">Klicken Sie auf **Zertifikat erneuern**.</span><span class="sxs-lookup"><span data-stu-id="703bc-113">Click **Renew certificate**.</span></span>
4. <span data-ttu-id="703bc-114">Befolgen Sie die Anweisungen auf der **MDM-Push-Zertifikat** Seite.</span><span class="sxs-lookup"><span data-stu-id="703bc-114">Follow the instructions on the **MDM Push Certificate** page.</span></span> <span data-ttu-id="703bc-115">Sie müssen, besuchen das Apple Push Certificates-Portal, um Ihre MDM-Push-Zertifikat zu erneuern.</span><span class="sxs-lookup"><span data-stu-id="703bc-115">You'll be required to visit the Apple Push Certificates portal to renew your MDM push Certificate.</span></span> <span data-ttu-id="703bc-116">Denken Sie daran, melden Sie sich beim Apple Push Certificates-Portal mit der Apple-ID, die Sie verwendet, um das ursprüngliche Zertifikat zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="703bc-116">Remember, sign in to the Apple Push Certificates portal with the Apple ID you used to create your original certificate.</span></span>
5. <span data-ttu-id="703bc-117">Wenn Sie im Apple Push Certificates-Portal sind, klicken Sie auf die Option aus, um das ablaufende Zertifikat zu erneuern.</span><span class="sxs-lookup"><span data-stu-id="703bc-117">When you're in the Apple Push Certificates portal, click the option to renew the expiring certificate.</span></span> 
6. <span data-ttu-id="703bc-118">Führen Sie die Schritte im Apple-Portal.</span><span class="sxs-lookup"><span data-stu-id="703bc-118">Complete the steps in the Apple portal.</span></span> <span data-ttu-id="703bc-119">Wenn das Zertifikat des Status liest **Active** erneut aus, klicken Sie zum Herunterladen und speichern Sie sie.</span><span class="sxs-lookup"><span data-stu-id="703bc-119">When your certificate's status reads **Active** again, click to download and save it.</span></span>
7. <span data-ttu-id="703bc-120">Zurück zu Intune for Education-Portals, und geben Sie die Apple-ID, die Sie zum Anmelden beim Apple Push Certificates-Portal verwendet.</span><span class="sxs-lookup"><span data-stu-id="703bc-120">Return to the Intune for Education portal and enter the Apple ID you used to sign in to the Apple Push Certificates portal.</span></span>
8. <span data-ttu-id="703bc-121">Laden Sie das Zertifikat, das Sie heruntergeladen haben hoch.</span><span class="sxs-lookup"><span data-stu-id="703bc-121">Upload the certificate you downloaded.</span></span>
9. <span data-ttu-id="703bc-122">Klicken Sie auf **Speichern**.</span><span class="sxs-lookup"><span data-stu-id="703bc-122">Click **Save**.</span></span>

## <a name="renew-mdm-server-token"></a><span data-ttu-id="703bc-123">Erneuern Sie Token für MDM-server</span><span class="sxs-lookup"><span data-stu-id="703bc-123">Renew MDM server token</span></span>

<span data-ttu-id="703bc-124">Erneuern Sie die MDM-servertoken jährlich, um sicherzustellen, dass Intune for Education immer eine aktualisierte Liste der iOS-Geräten verfügt.</span><span class="sxs-lookup"><span data-stu-id="703bc-124">Renew the MDM server token annually to make sure that Intune for Education always has an updated list of your iOS devices.</span></span>

<span data-ttu-id="703bc-125">Das MDM-Server-Token bezieht sich auf die Apple-ID, die Sie zum Hinzufügen des Servers verwendet.</span><span class="sxs-lookup"><span data-stu-id="703bc-125">The MDM server token is associated with the Apple ID you used to add the server.</span></span> <span data-ttu-id="703bc-126">Erneuern Sie das Token mit diesem gleichen Apple-ID.</span><span class="sxs-lookup"><span data-stu-id="703bc-126">Renew the token with this same Apple ID.</span></span> 

1. <span data-ttu-id="703bc-127">Intune for Education-Dashboard, klicken Sie auf **Mandanteneinstellungen** > **iOS-Geräteverwaltung**.</span><span class="sxs-lookup"><span data-stu-id="703bc-127">From the Intune for Education dashboard, click **Tenant settings** > **iOS Device Management**.</span></span>
2. <span data-ttu-id="703bc-128">Klicken Sie auf die **MDM Server Token** Registerkarte.</span><span class="sxs-lookup"><span data-stu-id="703bc-128">Click the **MDM Server Tokens** tab.</span></span>
3. <span data-ttu-id="703bc-129">Wählen Sie das Token, das Sie erneuern möchten.</span><span class="sxs-lookup"><span data-stu-id="703bc-129">Select the token that you want to renew.</span></span>
4. <span data-ttu-id="703bc-130">Klicken Sie auf **erneuern Token**.</span><span class="sxs-lookup"><span data-stu-id="703bc-130">Click **Renew token**.</span></span>
5. <span data-ttu-id="703bc-131">Befolgen Sie die Anweisungen auf der **MDM Server Token** Seite.</span><span class="sxs-lookup"><span data-stu-id="703bc-131">Follow the instructions on the **MDM Server Tokens** page.</span></span> <span data-ttu-id="703bc-132">Sie müssen dazu Apple School Manager zum Generieren von einem neuen MDM-Servertoken finden Sie unter.</span><span class="sxs-lookup"><span data-stu-id="703bc-132">You'll be required to visit Apple School Manager to generate a new MDM Server Token.</span></span> <span data-ttu-id="703bc-133">Denken Sie daran, melden Sie sich beim Apple School Manager mit der Apple-ID, die Sie verwendet, um das ursprüngliche Token abzurufen.</span><span class="sxs-lookup"><span data-stu-id="703bc-133">Remember, sign in to Apple School Manager with the Apple ID you used to get your original token.</span></span>
6. <span data-ttu-id="703bc-134">Nachdem Sie herunterladen und speichern Sie das neue Token von Apple School Manager haben, kehren Sie zum Intune for Education-Portals zurück.</span><span class="sxs-lookup"><span data-stu-id="703bc-134">After you download and save the new token from Apple School Manager, return to the Intune for Education portal.</span></span> <span data-ttu-id="703bc-135">Geben Sie in der Apple-ID verwendet, um das ursprüngliche Token zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="703bc-135">Type in the Apple ID used to create the original token.</span></span>
7. <span data-ttu-id="703bc-136">Hochladen der Token, das Sie heruntergeladen haben.</span><span class="sxs-lookup"><span data-stu-id="703bc-136">Upload the token you downloaded.</span></span>
8. <span data-ttu-id="703bc-137">Klicken Sie auf **Speichern**.</span><span class="sxs-lookup"><span data-stu-id="703bc-137">Click **Save**.</span></span>


## <a name="renew-vpp-token"></a><span data-ttu-id="703bc-138">VPP-Token zu erneuern</span><span class="sxs-lookup"><span data-stu-id="703bc-138">Renew VPP token</span></span>
<span data-ttu-id="703bc-139">Erneuern Sie Ihr VPP-Token jährlich Sie sicherstellen, dass Ihre VPP per Volumenlizenz erworbene apps angezeigt und von Intune for Education zugewiesen werden können.</span><span class="sxs-lookup"><span data-stu-id="703bc-139">Renew your VPP tokens annually to make sure your VPP-purchased apps can be viewed and assigned from Intune for Education.</span></span>  

<span data-ttu-id="703bc-140">VPP-Token bezieht sich auf die Apple-ID, die Sie zu ihrer Erstellung verwendet.</span><span class="sxs-lookup"><span data-stu-id="703bc-140">The VPP token is associated with the Apple ID you used to create it.</span></span> <span data-ttu-id="703bc-141">Erneuern Sie das Token mit diesem gleichen Apple-ID.</span><span class="sxs-lookup"><span data-stu-id="703bc-141">Renew the token with this same Apple ID.</span></span>  

1. <span data-ttu-id="703bc-142">Auf der **iOS-Geräteverwaltung** klicken Sie auf die **VPP-Token** Registerkarte.</span><span class="sxs-lookup"><span data-stu-id="703bc-142">On the **iOS Device Management** page, click the **VPP Tokens** tab.</span></span>
2. <span data-ttu-id="703bc-143">Wählen Sie das Token, das Sie erneuern möchten.</span><span class="sxs-lookup"><span data-stu-id="703bc-143">Select the token that you want to renew.</span></span>
3. <span data-ttu-id="703bc-144">Klicken Sie unter **VPP-Token: Microsoft Intune**, klicken Sie auf **erneuern Token**.</span><span class="sxs-lookup"><span data-stu-id="703bc-144">Under **VPP Token: Microsoft Intune**, click **Renew token**.</span></span>
4. <span data-ttu-id="703bc-145">Befolgen Sie die Anweisungen auf der **VPP-Token** Seite.</span><span class="sxs-lookup"><span data-stu-id="703bc-145">Follow the instructions on the **VPP Token** page.</span></span> <span data-ttu-id="703bc-146">Sie werden erforderlich, um Apple School Manager, um ein neues Token abzurufen, finden Sie unter.</span><span class="sxs-lookup"><span data-stu-id="703bc-146">You'll be required to visit Apple School Manager to get a new token.</span></span> <span data-ttu-id="703bc-147">Denken Sie daran, melden Sie sich mit der Apple-ID, die Sie verwendet, um das ursprüngliche Token abzurufen.</span><span class="sxs-lookup"><span data-stu-id="703bc-147">Remember, sign in with the Apple ID you used to get your original token.</span></span>
5. <span data-ttu-id="703bc-148">Führen Sie die Schritte im Apple School Manager erstellen und laden das Token aus.</span><span class="sxs-lookup"><span data-stu-id="703bc-148">Follow the steps in Apple School Manager to create and download the token.</span></span> <span data-ttu-id="703bc-149">Speichern Sie dann das Token auf Ihrem Computer.</span><span class="sxs-lookup"><span data-stu-id="703bc-149">Then save the token to your computer.</span></span>
6. <span data-ttu-id="703bc-150">Zurück zu Intune for Education-Portals.</span><span class="sxs-lookup"><span data-stu-id="703bc-150">Return to the Intune for Education portal.</span></span> <span data-ttu-id="703bc-151">Geben Sie die Apple-ID, die Sie zur Anmeldung beim Apple School Manager verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="703bc-151">Enter the Apple ID that you used to sign in to Apple School Manager.</span></span>
7. <span data-ttu-id="703bc-152">Klicken Sie auf das Ordnersymbol, um Dateien von Ihrem Computer zu durchsuchen.</span><span class="sxs-lookup"><span data-stu-id="703bc-152">Click the folder icon to browse your computer's files.</span></span> <span data-ttu-id="703bc-153">Wählen Sie die token-Datei, die Sie heruntergeladen haben und die zuvor gespeichert haben.</span><span class="sxs-lookup"><span data-stu-id="703bc-153">Select the token file that you downloaded and saved earlier.</span></span>
8. <span data-ttu-id="703bc-154">Wählen Sie den Speicherort der Geräte von Ihrer Schule.</span><span class="sxs-lookup"><span data-stu-id="703bc-154">Choose the location of your school's devices.</span></span>
9. <span data-ttu-id="703bc-155">Wenn Sie keine automatische app-Updates aktivieren möchten, wechseln Sie die Einstellung, um sie zu deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="703bc-155">If you don't want to enable automatic app updates, switch the setting to disable them.</span></span> 
10. <span data-ttu-id="703bc-156">Klicken Sie auf **Speichern**.</span><span class="sxs-lookup"><span data-stu-id="703bc-156">Click **Save**.</span></span>

## <a name="next-steps"></a><span data-ttu-id="703bc-157">Nächste Schritte</span><span class="sxs-lookup"><span data-stu-id="703bc-157">Next steps</span></span>
<span data-ttu-id="703bc-158">Nun, da Ihre Zertifikate und Token erneuert werden, stellen Sie sicher, dass [Ihre gruppeneinstellungen](edit-groups-intune-for-edu.md) auf dem neuesten Stand sind.</span><span class="sxs-lookup"><span data-stu-id="703bc-158">Now that your certificates and tokens are renewed, make sure [your group settings](edit-groups-intune-for-edu.md) are up-to-date.</span></span> <span data-ttu-id="703bc-159">Erfahren Sie, um den aktuellen Status Ihrer Gruppen in Intune finden, wie Sie [Anzeigen von Berichten](what-are-reports.md).</span><span class="sxs-lookup"><span data-stu-id="703bc-159">To see the current status of your groups in Intune, learn how to [view reports](what-are-reports.md).</span></span>  

<span data-ttu-id="703bc-160">Lesen [neuerungen in Intune for Education](whats-new-in-edu.md) Informationen über die neuesten Updates und Features finden.</span><span class="sxs-lookup"><span data-stu-id="703bc-160">Read [What's new in Intune for Education](whats-new-in-edu.md) to find out about the latest updates and features.</span></span>