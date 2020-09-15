---
title: Erstellen von Gruppen in Intune for Education
titleSuffix: Intune for Education
description: Informationen Sie zum Verwalten von Geräten mit Intune for Education.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: doueby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 4b570196-a640-4d13-8e01-8e8553ce1468
searchScope:
- IntuneEDU
ms.openlocfilehash: 1008314a0c9737736ce6e7768f704cd316c252fe
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146733"
---
# <a name="create-groups-in-intune"></a>Erstellen von Gruppen in Intune

Das Feature "" in Intune können Sie verwalten werden, Benutzer, apps und Geräte, auf denen ähnliche Anforderungen. Mit Gruppen können Sie die Zeit reduzieren, die Sie investieren einzeln verwalten und Behandeln von Problemen Geräten. 

## <a name="default-groups"></a>Standardgruppen  
Out-of-the-Box, im Lieferumfang von Intune for Education Standardgruppen, die Sie verwalten können:  
* Alle Geräte
* Alle Benutzer

Bei Verwendung von School Data Sync, um Ihre Schul-/ unidatensätzen zu importieren, werden zwei zusätzliche Standardgruppen erstellt. Sie ermöglichen Ihnen, zu verwalten:  
* Alle Lehrer
* Alle Schüler/Studenten

Diesen Standardgruppen können nicht die allgemeinsten Kategorien von Benutzern und Geräten in Ihrer Schule/Universität darstellen und geändert oder entfernt werden.

## <a name="custom-groups"></a>Benutzerdefinierte Gruppen  

Bestimmte oder auf Szenarien basierende-Konfigurationen zu benutzerdefinierten Gruppen anwenden. Wenn Sie Windows 10 und iOS-Geräte in Ihrer Schule/Universität haben, erstellen Sie Gruppen, z. B. alle iPads und alle Windows 10-PCs. Auf diese Weise werden Sie möglicherweise leichter erkennen, Gruppen und Einstellungen verteilen. 

Sie können auch bestimmte Gruppen von Schüler/Studenten-apps und Einstellungen zuweisen. Unter Umständen eine 8. auf Unternehmensniveau Lehrplan z. B. verschiedene apps als einen Lehrplan für 6. auf Unternehmensniveau. Erstellen Sie zwei, Grade-spezifische Gruppen und Zuweisen von apps und Einstellungen, die für jeden Schüler/Studenten geeignet sind.  
## <a name="group-types"></a>Gruppentypen  

Es gibt zwei Arten von Gruppen, die Sie, zum Organisieren von Benutzern und Geräten in Intune for Education verwenden können: Gruppen und dynamische Gruppen zugewiesen.

### <a name="assigned-groups"></a>Zugewiesene Gruppen  

Zugewiesene Gruppen werden verwendet, wenn Sie Benutzer oder Geräte einer Gruppe manuell hinzufügen möchten.  Betrachten Sie sie wie zusammenstellen Ablagesystem: Sie müssen bestimmte Dokumente einreichen, in einen bestimmten Ordner, die mit Ihrer eigenen Logik oder die Methode der Gruppierung. Wenn Sie diesen Artikel benötigen, wissen Sie den genauen Ordnernamen, um aufzurufen. 

Auf ähnliche Weise können Sie Ordner in Ordnern erstellen oder *Untergruppen*, um eine größere Gruppe weiter in eine verwaltbare Größe zu organisieren.

Erfahren Sie, wie manuell zuweisen oder Entfernen von Mitgliedern, finden Sie unter [Gruppen bearbeiten](edit-groups-intune-for-edu.md).


### <a name="dynamic-groups"></a>Dynamische Gruppen  
Dynamische Gruppen verweisen auf Regeln, um die Zuweisung von Schüler/Studenten oder Geräten zu Gruppen zu erstellen. Die Kriterien für Regeln, die während der Erstellung der ersten Gruppe angegeben ist, und können bearbeitet werden, nachdem eine Gruppe erstellt wurde.

Beispielsweise können Sie eine Gruppe für Schüler/Studenten, die Migration von Contoso hohe am Ende des Jahres School 2019 erstellen. Stattdessen wird durchlaufen, und weisen jedem Teilnehmer manuell, Intune for Education der Schüler/Studenten in die Gruppe basierend auf dem Schul-/ Jahrgangs- und Abschlussdaten Datum gefiltert.

Schüler/Student in der Gruppe aus Contoso hoch und in einem anderen "School" in Ihrer Region übertragen werden, würden Sie nicht manuell aus einer dynamischen Gruppe entfernen können. Sie müssten stattdessen die Student Namen aktualisieren, damit Intune weiß, dass sie, länger erfüllt die Kriterien für die Mitgliedschaft wissen.

Da dynamische Gruppen nur enthalten können was ihre Regeln definieren, erstellen keine Untergruppen unter diesen.

Gewusst wie: Bearbeiten von Regeln finden Sie unter [Gruppen bearbeiten](edit-groups-intune-for-edu.md).

> [!TIP]
> Verwenden Sie die dynamische Regeln, durch Gruppen von ähnlichen Namen oder vor kurzem integrierten Gruppen von Geräten, z. B. Filterkriterien wie *DeviceType_School_Grade_0001*. Dynamische Gruppen sind ideal für große Gruppen von Geräten oder Benutzern in großen Schulbezirke zu verwalten. Sie reduzieren die Zeit und Kosten für die Hardwareinventur oder zur Belegschaft einer Schule manuell durchlaufen.  


## <a name="plan-your-groups"></a>Planen von Gerätegruppen
Planen Sie zunächst die Einstellungen und apps, die für Ihre Schulbezirk, Schüler und Studenten, Lehrkräfte und Geräte erforderlich sind. Einstellungen für Gruppen zugewiesen sind, und einige Gruppen müssen bestimmte Einstellungen und apps.   

Zum Beispiel:  
* Blockieren Sie für alle Geräte apps mithilfe von ortungsdiensten. 
* Für AP Computer Science, Zuweisen von Schüler/Studenten-apps, Code zu bearbeiten.
* Aktivieren Sie für 12. auf Unternehmensniveau Verlauf Schüler/Studenten Browsen im Web, damit sie die wissenschaftliche Artikel zugreifen können.
* Aktivieren Sie für Schüler/Studenten Fotografie Kamera des Geräts ein.


## <a name="create-a-group"></a>Erstellen einer Gruppe  
Gruppen müssen erstellt werden, eine zeilenweise. Während des Setups müssen Sie auswählen, um eine Gruppe für entweder Benutzer oder Geräte erstellen.

1. Intune for Education-Dashboard, klicken Sie auf **Gruppen** > **gruppenerstellungs**.
2. Geben Sie einen beschreibenden Namen ein.
3. Wählen Sie einen Gruppentyp an. Weitere Informationen über zugewiesene und dynamische Gruppen finden Sie [Gruppentypen](## Group types)   
    a. Zugewiesen: Manuelles fügen Sie hinzu und entfernen Sie Benutzer und Gerät in diesen Gruppen. Wenn Sie diese Option auswählen, wechseln Sie mit Schritt 5 fort.
   b. Dynamisch: Regeln werden implementiert, für das automatische hinzufügen und Entfernen von Benutzern und Geräten. Wenn Sie diese Option auswählen, wechseln Sie mit Schritt 4 fort.
4. Wählen Sie zum Verwalten von Geräten oder Schüler/Studenten.
    a. Geräte: Wenn Sie dies auswählen, wird eine Benennungsregel angezeigt. Erstellen Sie eine Regel zum automatischen Zuweisen von Geräten, die gestartet oder den eingegebenen Text enthalten. Während der Eingabe wird eine Vorschau der Mitglieder aufgefüllt. am unteren Rand der Seite.
    b. Schüler/Studenten: Wenn Sie die Schüler/Studenten auswählen, wird eine Position und ID-Regel angezeigt. Erstellen Sie eine Regel zum automatischen Zuweisen von Schüler/Studenten, die auf eine bestimmte Schule in Ihrem Mandanten zu wechseln. Wählen Sie dann nach Jahr für professionelle oder Abschlussvorgang für Gruppe Schüler/Studenten. Nachdem Sie alle Felder eingeben, wird eine Vorschau der Mitglieder aufgefüllt. am unteren Rand der Seite.
5. Klicken Sie am unteren Rand der Seite, auf **gruppenerstellungs**.

## <a name="create-a-subgroup"></a>Erstellen Sie eine Untergruppe  
Gruppen werden in Intune als Hierarchien eingerichtet. Die übergeordnete Gruppe stellt die oberste Ebene der Hierarchie und [auf diese Gruppe angewendeten Einstellungen werden geerbt, indem Sie die Gruppen darunter](settings-inheritance.md). Dieses Konzept wird als bezeichnet *einstellungsvererbung*.  Festlegen der Vererbung von erleichtert die Einstellungen gelten für eine große Gruppe von Benutzern und Geräten. 

Untergruppen können nur erstellt werden *unter* Gruppen zugewiesen. 

 ![Die Seite "erstellen Untergruppe", mit den beiden Standorten für die Erstellung von Untergruppe – am oberen Rand der Gruppenname und der Randleiste – rot eingekreist](./media/groups-007-create-subgroup.png)

1. Wechseln Sie zu **Gruppen** , und wählen Sie eine Gruppe. Diese Gruppe wird das übergeordnete Element zu Ihrem Untergruppe sein.
2. Klicken Sie auf **Untergruppe erstellen**.
3. Geben Sie die **Gruppenname**. 
4. Wählen Sie Ihre Gruppe. Weitere Informationen zu den Arten von Gruppen, finden Sie die Schritte zum [erstellen Sie eine Gruppe](#create-a-group) oben.
5. Klicken Sie auf **gruppenerstellungs**.  

## <a name="next-steps"></a>Nächste Schritte 
[Delegieren Sie die Berechtigung](group-admin-delegate.md) zum ermöglichen von Gruppen zum Verwalten der übergeordneten Ebene Gruppen und Untergruppen.  

[Erfahren Sie mehr über die vollständige](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune)gruppiert Verwaltungsfunktionen in Intune.
