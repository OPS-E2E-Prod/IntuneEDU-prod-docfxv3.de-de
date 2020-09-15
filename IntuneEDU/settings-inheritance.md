---
title: Was ist einstellungsvererbung?
titleSuffix: Intune for Education
description: Informationen Sie zum Verwalten der Einstellungen für Gruppen von Geräten mit Intune for Education.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 09/26/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 4b69b884-bed9-43f4-8507-c802228a8804
searchScope:
- IntuneEDU
ms.openlocfilehash: 5a981fb8916dc0318cc1599002ebe9001f1ef41b
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146906"
---
# <a name="what-is-settings-inheritance"></a>Was ist einstellungsvererbung?

Einstellungen werden auf Gruppen angewendet. Da Gruppen als Hierarchien mit einer Gruppe über eine andere eingerichtet sind, werden alle Einstellungen, die für eine Gruppe von Untergruppen geerbt. Untergruppen schalten Sie automatisch auf die Änderungen, die Sie der Gruppe "übergeordneten" vornehmen. Diese Aktion wird aufgerufen, _Vererbung_. Einstellungsvererbung ia hilfreich, wenn Sie Einstellungen für große Gruppen von Benutzern und Geräten anwenden möchten.  


  ![Eine Struktur von Gruppen und Untergruppen.](./media/groups-002-inheritance.png)  


## <a name="configure-subgroups-individually"></a>Untergruppen einzeln konfigurieren  

Um Sie vor kurzem geerbte Eigenschaften außer Kraft setzen, wechseln Sie direkt mit der Untergruppe. Konfigurieren sie einzeln durch Entfernen oder Hinzufügen von Einstellungen. Klicken Sie dann Ihre Änderungen zu speichern.

## <a name="settings-in-conflict"></a>Einstellungen in Konflikt stehende  

Wenn Sie in Konflikt stehenden Einstellungen auf der gleichen Gruppe anwenden, wird Intune jeweils einzeln zu analysieren. Intune wählt immer die Einstellungen, die mit Bestimmtheit, School-Richtlinien erfüllt.

In anderen Fällen, wenn Intune nicht, den Konflikt auflösen kann, Sie sollten überprüfen, die [Einstellungen in Konflikt stehen](what-are-reports.md) Bericht.

### <a name="example-of-inheritance-conflict"></a>Beispiel für Vererbung Konflikt  

Betrachten Sie beispielsweise die Untergruppe "," *12. auf Unternehmensniveau AP Computer Science*. Die Untergruppe "liegt unter der übergeordneten Gruppe, *12. Grade*. Weisen Sie einer strict Security-Überprüfung erforderlich, alle Dateien und apps heruntergeladen, Geräte in der *12. Grade* Gruppe.

Sie jedoch wissen, die für eine anstehende Zuordnung *12. auf Unternehmensniveau AP Computer Science* müssen herunterladen JavaScript-Dateien, die nicht überprüft werden müssen. Wenn Sie nicht, dass die einstellungsvererbung von, die restriktiver überschreiben *zwölfte auf Unternehmensniveau* Einstellung gelten für die Benutzer in *zwölfte auf Unternehmensniveau AP Computer Science*.

## <a name="settings-error-report"></a>Fehlerbericht für Einstellungen

Wenn eine Einstellung nicht aufgelöst werden kann, wird es in den Bericht über Fehler angezeigt. Weitere Informationen zu Berichten finden Sie unter [Berichte anzeigen und herunterladen](what-are-reports.md).  

## <a name="next-steps"></a>Nächste Schritte  
Erfahren Sie mehr über die [vollständige Gruppen in Intune auftreten](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune).
