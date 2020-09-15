---
title: Was sind Einstellungen?
titleSuffix: Intune for Education
description: Informationen Sie zum Verwalten von Einstellungen, die über Intune for Education-Richtlinien.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 91d004c0-8d06-4307-8868-46ac7b119101
searchScope:
- IntuneEDU
ms.openlocfilehash: 998b207bdfc0f8d48cd7eddff3020d00673377a2
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2019
ms.locfileid: "62145971"
---
# <a name="what-are-group-settings"></a>Was sind Einstellungen?

Konfigurieren Sie die Einstellungen, um die Funktionsweise von Schüler/Studenten, Lehrkräfte und Geräte in Ihrer Schule/Universität zu verwalten.

Einstellungen, die Sie Benutzern zuweisen, wird der Benutzer unabhängig davon, welche Geräte sie verwenden folgen. Auf ähnliche Weise Einstellungen, die Geräten zugewiesen werden führen Sie die Geräte, unabhängig davon, wer sie verwendet.

Einstellungen werden auf Gruppen angewendet. Da Gruppen als Hierarchien mit einer Gruppe über eine andere eine eingerichtet sind [werden Einstellungen für eine Gruppe von allen Untergruppen geerbt](settings-inheritance.md). Vererbung erleichtert die Einstellungen gelten für große Gruppen von Benutzern, apps und Geräten.  

Es gibt zwei Möglichkeiten zum Verwalten von Einstellungen in Intune for Education:  

* __Express-Konfiguration__: Konfigurieren Sie eine Auswahl der am häufigsten verwendeten School-Einstellungen. [Express-Konfiguration](Express-configuration-intune-edu.md) ist eine exemplarische Vorgehensweise-Stil-Einrichtung, mit dem Sie auswählen und Zuordnen von gruppeneinstellungen, schnell. Einstellungen sind vorkonfiguriert, die von Microsoft empfohlene Werte jedoch zum Anpassen Ihrer Schule Richtlinien geändert werden können. 

* __Gruppen__: Konfigurieren Sie alle Einstellungen für eine Gruppe von Geräten oder Benutzern. In der **Gruppen** Registerkarte sehen Sie die vollständige Liste der Einstellungen im Portal verfügbar. Finden Sie unter werden die Einstellungen zur [Windows](all-edu-settings-windows.md) und [iOS](all-edu-settings-ios.md) Gruppen.  

## <a name="configure-express-configuration-settings"></a>Konfigurieren von Einstellungen für express-Konfiguration  

Express-Konfiguration kann werden verwendet, wenn:
* Sie werden erst im Portal der Anfang.
* Sie verwendet haben sie eine Weile und schnelle Änderungen vornehmen möchten.   

Eine ausführliche Übersicht über die Schritte für die express-Konfiguration werden soll, finden Sie unter [Express-Konfiguration in Intune for Education](Express-configuration-intune-edu.md).

  ![Express-Einstellungen: beheben Konfiguration](./media/express-config-006-choose-settings.png)  

## <a name="configure-settings-in-groups"></a>Konfigurieren von Einstellungen in Gruppen

Die folgenden Schritte beschreiben das Zuweisen von Einstellungen aus der **Gruppen** Seite in Intune for Education. Auf dieser Seite sehen Sie die vollständige Liste der geräteeinschränkungen und Funktionen.  
1. Intune for Education-Dashboard, klicken Sie auf **Gruppen**.
2. Wählen Sie die Gruppe, die Sie konfigurieren möchten.
3. Klicken Sie auf **Einstellungen** um die vollständige Liste der verfügbaren Einstellungen anzuzeigen.
4. Erweitern Sie jede Kategorie zum Ändern der einzelnen Einstellungen für die ausgewählte Gruppe aus.
5. Klicken Sie auf **Speichern**, wenn Sie fertig sind. Einstellungen werden auf allen Geräten in der Gruppe automatisch aktualisiert.  

## <a name="can-i-ever-have-settings-that-dont-work-together"></a>Kann ich jemals Einstellungen verwenden, die nicht gemeinsam funktionieren?

Es ist möglich, dass nicht kompatible Einstellungen auf der gleichen Gruppe angewendet werden. Diese Inkonsistenzen führen zu Fehlern, wenn ein Benutzer oder Gerät mit unterschiedlichen Einstellungen an mehreren Orten eingerichtet wird. Konflikte auftreten, wenn der Benutzer oder gerätemitglieder zu mehr als einer Gruppe gehören.

Esperanza ist z. B. ein Mitglied der *6. Grade* gruppieren und ist auch Mitglied der Gruppe mit dem Namen *Earth Science*. Wenn Sie eine Einstellung für die Startseite konfigurieren und Zuweisen *6. Grade*, und Sie eine andere Homepage-Einstellung konfigurieren, und weisen Sie ihn *Earth Science*, Esperanza verfügt jetzt über zwei in Konflikt stehenden Homepage Einstellungen zugewiesen Zu ihr. Die Zuweisung von inkonsistenten Einstellung führt zu einem Fehler. Um dieses Problem zu beheben, sollten der Gruppe ansehen [Bericht über Fehler](what-are-reports.md).  

## <a name="next-steps"></a>Nächste Schritte
[Erstellen von Benutzer- und Gerätegruppen](what-are-groups.md) in Intune for Education, damit Sie ihre Einstellungen konfigurieren können.  

[Erfahren Sie mehr über das Schützen von apps und Daten mit der vollständigen Verwaltungsfunktionen in Intune](https://docs.microsoft.com/intune/deploy-use/protect-apps-and-data-with-microsoft-intune)
