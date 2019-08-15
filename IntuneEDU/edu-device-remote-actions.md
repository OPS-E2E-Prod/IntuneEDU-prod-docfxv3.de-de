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
# <a name="manage-devices-remotely"></a>Verwalten von Geräten per Remotezugriff  

Wenn Sie einen anderen Speicherort als ein Gerät oder der Benutzer angemeldet und sie die Problembehandlung zu unterstützen müssen, verwenden Sie die Remoteaktionen in Intune for Education.  


## <a name="remote-actions-for-devices"></a>Remoteaktionen für Geräte  

![Beispielscreenshot mit Intune Education 7 Remoteaktionen.](./media/1812_Intune_EDU_Manage_Remote.png)  

Navigieren Sie zu dem Dashboard **Geräte**. Wählen Sie das Gerät, das Sie verwalten möchten. Wählen Sie am unteren Rand der Seite die folgenden Aktionen aus:

- **Starten Sie neu**: Schaltet das Gerät aus, und startet ihn neu.
- **Auf Werkseinstellungen zurücksetzen:** Das Gerät aus Intune-Verwaltung entfernt, und alle Daten und Einstellungen vom Gerät entfernt. 
- **Gerät synchronisieren**: Stellt sicher, dass das Gerät auf dem neuesten Stand Einstellungen, app-Zuweisungen und Gruppenmitgliedschaften verfügt. Diese Aktion kann helfen, wenn Sie versuchen, ein Gerät zu beheben.  
- **Zurücksetzen des AutoPilot**: Entfernt alle Benutzerdaten&ndash;z. B. Benutzer installierten apps und persönlichen Einstellungen&ndash;und Windows 10-Geräts bei Intune registriert sind. Das Gerät wird auf dem neuesten Stand mit den neuesten apps, Richtlinien und Einstellungen beibehalten. Eine Benachrichtigung angezeigt wird, wenn das Zurücksetzen initiiert wird. Das Gerät wird beim nächsten Herstellen einer Verbindung mit dem Internet zurückgesetzt.  
- **Gerät umbenennen**: Gibt dem Gerät einen neuen Namen an. Der neue Name Updates in Intune und lokal auf dem Gerät. Sie müssen das Windows-Gerät für den neuen Namen wirksam neu starten.  
- **Löschen von Gerät**: Hebt die Registrierung des Geräts bei Intune für Bildungseinrichtungen, und das Gerät aus Azure Active Directory entfernt. Ein gelöschtes Gerät kann nicht mehr Ihrer Schule-Ressourcen zugreifen. 

## <a name="remote-actions-for-users"></a>Remoteaktionen für Benutzer  

Navigieren Sie zu dem Dashboard **Benutzer**. Wählen Sie den Benutzer, den Sie verwalten möchten. Wählen Sie am unteren Rand der Seite, **Zurücksetzen des Kennworts**. Diese Aktion setzt ein Kennwort alte, verloren oder vergessen haben, auf dem Gerät des Benutzers zurück.  
