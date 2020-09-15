---
title: Kostenlose apps aus dem iOS-Store hinzufügen
titleSuffix: Intune for Education
description: Erfahren Sie, wie Sie kostenlose apps aus dem iOS-Store zu Intune for Education hinzufügen.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 24ab6547-aa65-428a-b184-06b806e95bd1
searchScope:
- IntuneEDU
ms.openlocfilehash: 4d17b0d12758dc781fa89f522f07ace5247cdc2e
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2019
ms.locfileid: "62145899"
---
# <a name="add-free-ios-apps-to-intune-for-education"></a>Kostenlose iOS-apps zu Intune for Education hinzufügen  
Suchen Sie nach, und fügen Sie kostenlose apps aus dem iOS App Store auf Ihre app-Bestand. Dieser Artikel beschreibt, wie Sie kostenlose iOS-apps zu erwerben, damit Sie anzeigen können, und sie in Intune for Education-Portals weisen.
 
Anweisungen gelten nur für apps, die als aufgelistet sind **Free** in den App Store. Zum Hinzufügen einer app kostenpflichtiges finden im Artikel [hinzufügen VPP per Volumenlizenz erworbenen iOS-apps zu Intune](add-vpp-apps-ios.md).

## <a name="recommendation-set-up-vpp-token"></a>Empfehlung: VPP-Token einrichten

Ein VPP-Token zum Installieren von kostenlosen apps ist nicht erforderlich, aber sie sollten. Ein VPP-Token können Sie alle apps – kostenlose und kostenpflichtige – über den VPP-Store kaufen. Intune wird im Hintergrund VPP per Volumenlizenz erworbene apps auf Geräten installiert und erfordert keine Apple-ID authentifizieren.  

Wenn Sie keinen VPP-Token verwenden, um Ihre app zu erwerben, werden Sie nur kostenlose apps in Intune for Education verwalten können. Benutzer des Geräts müssen auch die Anmeldung mit einer Apple-ID zu installieren, die zugewiesen von apps.

## <a name="add-new-ios-app"></a>Hinzufügen von neuen iOS-app
Führen Sie die folgenden Schritte aus, um eine iOS-app zu Intune for Education hinzuzufügen.
1. Melden Sie sich Intune for Education-Portals.
2. Klicken Sie auf **Apps**.
3. Klicken Sie im linken Bereich unter **IOS-APPS**, klicken Sie auf **neue app**.
5. Geben Sie in das Suchfeld den Namen vollständigen oder teilweise einer App aus.
6. Wählen Sie die app, und klicken Sie auf **speichern** um die app zu Ihrem Intune-Inventar hinzuzufügen.

## <a name="view-app-details-in-intune-for-education"></a>App-Details anzeigen, in Intune for Education
Hinzugefügt von apps unter in der Liste der Apps angezeigt **iOS-Store**. Klicken Sie auf die app zum Anzeigen der:

* **Übersicht:** Listet auf app-Name, Herausgeber und Datum, die Sie zu Intune hinzugefügt haben. Klicken Sie auf den Namen der app, um die app in iTunes anzuzeigen.
* **Gruppen**: Listet alle Gruppen, die die app zugewiesen werden. Ändern Sie hier gruppenzuweisungen, oder wechseln Sie zur Detailseite für eine bestimmte Gruppe.
* **Installationsstatus**: Zeigt Details zu der app-Installation, beispielsweise für das Gerät, dem er zugewiesen wurde. Der Status listet auch auf, Zeitpunkt der letzten Eincheckvorgang und bei die Installation ein Erfolg oder Fehler immer noch in Bearbeitung.  
