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
# <a name="renew-ios-certificate-and-tokens"></a>IOS-Zertifikat und Token zu erneuern
Apple-MDM-Push-Zertifikate, MDM-Server-Token und VPP-Token ablaufen 365 Tage nach ihrer Erstellung. Intune for Education informiert Sie, wenn ein Zertifikat oder das Token ist nahe oder hinter seinem Ablaufdatum. 

Stellen Sie sicher, erneuern, um die Verbindung zwischen Ihrem Intune für Bildungseinrichtungen-Konto und Apple-Konto zu verwalten.  

## <a name="renew-apple-mdm--certificate"></a>Apple-MDM-Zertifikat erneuern  
> [!IMPORTANT]
> Wenn das Apple-MDM-Zertifikat abläuft oder gelöscht wird, müssen Sie zum Zurücksetzen und Geräte mit einem neuen Zertifikat erneut registrieren.  

Das MDM-Push-Zertifikat, das mit der Apple-ID, die Sie zu ihrer Erstellung verwendet zugeordnet ist. Erneuern Sie das Zertifikat mit diesem gleichen Apple-ID.

1. Intune for Education-Dashboard, klicken Sie auf **Mandanteneinstellungen** > **iOS-Geräteverwaltung**.
2. Klicken Sie auf die **MDM-Push-Zertifikat** Registerkarte.
3. Klicken Sie auf **Zertifikat erneuern**.
4. Befolgen Sie die Anweisungen auf der **MDM-Push-Zertifikat** Seite. Sie müssen, besuchen das Apple Push Certificates-Portal, um Ihre MDM-Push-Zertifikat zu erneuern. Denken Sie daran, melden Sie sich beim Apple Push Certificates-Portal mit der Apple-ID, die Sie verwendet, um das ursprüngliche Zertifikat zu erstellen.
5. Wenn Sie im Apple Push Certificates-Portal sind, klicken Sie auf die Option aus, um das ablaufende Zertifikat zu erneuern. 
6. Führen Sie die Schritte im Apple-Portal. Wenn das Zertifikat des Status liest **Active** erneut aus, klicken Sie zum Herunterladen und speichern Sie sie.
7. Zurück zu Intune for Education-Portals, und geben Sie die Apple-ID, die Sie zum Anmelden beim Apple Push Certificates-Portal verwendet.
8. Laden Sie das Zertifikat, das Sie heruntergeladen haben hoch.
9. Klicken Sie auf **Speichern**.

## <a name="renew-mdm-server-token"></a>Erneuern Sie Token für MDM-server

Erneuern Sie die MDM-servertoken jährlich, um sicherzustellen, dass Intune for Education immer eine aktualisierte Liste der iOS-Geräten verfügt.

Das MDM-Server-Token bezieht sich auf die Apple-ID, die Sie zum Hinzufügen des Servers verwendet. Erneuern Sie das Token mit diesem gleichen Apple-ID. 

1. Intune for Education-Dashboard, klicken Sie auf **Mandanteneinstellungen** > **iOS-Geräteverwaltung**.
2. Klicken Sie auf die **MDM Server Token** Registerkarte.
3. Wählen Sie das Token, das Sie erneuern möchten.
4. Klicken Sie auf **erneuern Token**.
5. Befolgen Sie die Anweisungen auf der **MDM Server Token** Seite. Sie müssen dazu Apple School Manager zum Generieren von einem neuen MDM-Servertoken finden Sie unter. Denken Sie daran, melden Sie sich beim Apple School Manager mit der Apple-ID, die Sie verwendet, um das ursprüngliche Token abzurufen.
6. Nachdem Sie herunterladen und speichern Sie das neue Token von Apple School Manager haben, kehren Sie zum Intune for Education-Portals zurück. Geben Sie in der Apple-ID verwendet, um das ursprüngliche Token zu erstellen.
7. Hochladen der Token, das Sie heruntergeladen haben.
8. Klicken Sie auf **Speichern**.


## <a name="renew-vpp-token"></a>VPP-Token zu erneuern
Erneuern Sie Ihr VPP-Token jährlich Sie sicherstellen, dass Ihre VPP per Volumenlizenz erworbene apps angezeigt und von Intune for Education zugewiesen werden können.  

VPP-Token bezieht sich auf die Apple-ID, die Sie zu ihrer Erstellung verwendet. Erneuern Sie das Token mit diesem gleichen Apple-ID.  

1. Auf der **iOS-Geräteverwaltung** klicken Sie auf die **VPP-Token** Registerkarte.
2. Wählen Sie das Token, das Sie erneuern möchten.
3. Klicken Sie unter **VPP-Token: Microsoft Intune**, klicken Sie auf **erneuern Token**.
4. Befolgen Sie die Anweisungen auf der **VPP-Token** Seite. Sie werden erforderlich, um Apple School Manager, um ein neues Token abzurufen, finden Sie unter. Denken Sie daran, melden Sie sich mit der Apple-ID, die Sie verwendet, um das ursprüngliche Token abzurufen.
5. Führen Sie die Schritte im Apple School Manager erstellen und laden das Token aus. Speichern Sie dann das Token auf Ihrem Computer.
6. Zurück zu Intune for Education-Portals. Geben Sie die Apple-ID, die Sie zur Anmeldung beim Apple School Manager verwendet werden soll.
7. Klicken Sie auf das Ordnersymbol, um Dateien von Ihrem Computer zu durchsuchen. Wählen Sie die token-Datei, die Sie heruntergeladen haben und die zuvor gespeichert haben.
8. Wählen Sie den Speicherort der Geräte von Ihrer Schule.
9. Wenn Sie keine automatische app-Updates aktivieren möchten, wechseln Sie die Einstellung, um sie zu deaktivieren. 
10. Klicken Sie auf **Speichern**.

## <a name="next-steps"></a>Nächste Schritte
Nun, da Ihre Zertifikate und Token erneuert werden, stellen Sie sicher, dass [Ihre gruppeneinstellungen](edit-groups-intune-for-edu.md) auf dem neuesten Stand sind. Erfahren Sie, um den aktuellen Status Ihrer Gruppen in Intune finden, wie Sie [Anzeigen von Berichten](what-are-reports.md).  

Lesen [neuerungen in Intune for Education](whats-new-in-edu.md) Informationen über die neuesten Updates und Features finden.