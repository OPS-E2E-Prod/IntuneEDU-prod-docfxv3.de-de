---
title: Hinzufügen von VPP per Volumenlizenz erworbene apps
titleSuffix: Intune for Education
description: Informationen Sie zum Hinzufügen von erworbenen VPP-apps zu Intune for Education.
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
ms.openlocfilehash: 69af75f14afb144bfed01919b1cba65d34a440f2
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146608"
---
# <a name="add-vpp-purchased-ios-apps-to-intune"></a>Hinzufügen von VPP per Volumenlizenz erworbene iOS-apps zu Intune

Volume Purchase Program (VPP)-iOS-apps über Intune for Education-Portals hinzufügen. In diesem Artikel wird beschrieben, wie Sie VPP per Volumenlizenz erworbene apps verwalten, die in Microsoft Intune synchronisiert wurden.

Kostenlose und kostenpflichtige apps stehen im Volume über den App-Store kaufen. So installieren Sie kostenlose iOS-apps *ohne ein VPP-Token*, finden Sie unter wie [kostenlose iOS-apps in Intune hinzufügen](add-apps-ios.md).  

## <a name="what-is-the-volume-purchase-program"></a>Was ist das Volume Purchase Program?
Das Apple Volume Purchase Program ermöglicht Organisationen, die app-Lizenzen in einem Massenvorgang erwerben und diese über ihre mobilen Geräte-Manager (MDM) verwalten. Mit einer MDM-Lösung wie Intune for Education können Lizenzen verwaltet werden und dann im Hintergrund bereitgestellt drahtlose für Student-Geräte. Eine VPP-/ MDM-Partnerschaft eignet sich ideal, im Unterricht und Organisationen, in denen die gleiche app auf vielen Geräten erforderlich ist. 

## <a name="before-you-begin"></a>Vorbereitung
Zum Anzeigen und Verwalten von Lizenzen von Intune for Education-Portals, müssen Sie zunächst ein:  
* Konfigurieren einer [VPP-Token](setup-ios-device-management.md).
* Apps, die über einen Apple VPP-Anbieter oder über den Apple School Manager erwerben > Apps und Büchern Store.
* Übertragen Sie die vorhandenen Lizenzen mit dem entsprechenden Intune VPP-Token. Finden Sie unter den [Support-Website von Apple Education](https://support.apple.com/education) erfahren, wie Lizenzen zu übertragen. 

## <a name="search-and-add-apps"></a>Suchen und Hinzufügen von apps
Die folgenden Schritte zum Suchen, und fügen kostenpflichtige iOS-apps über Intune for Education-Portals. 

Kostenlose apps sind zum Kauf direkt über das Portal zur Verfügung gestellt. Allerdings sind diese apps zur Verfügung gestellt, damit Benutzer ohne eine VPP-Konto problemlos abrufen können. Wenn Sie kostenlose apps für Geräte von Ihrer Schule automatisch und im Volume bereitstellen möchten, sollten Sie diese über das Apple VPP- oder Apple School Manager-Website erwerben.

1. Melden Sie sich Intune for Education-Portals.
2. Klicken Sie auf **Apps**.
3. Aus der Liste der Apps unter **iOS-Apps**, klicken Sie auf **neue app**.
4. Wählen Sie das Land aus, in dem Sie die app-Käufe sind.
5. Geben Sie in der app Namen für vollständig oder teilweise an. Intune gibt eine Liste mit relevanten Ergebnissen zurück, aus dem App Store. 
6. Wählen Sie die app ein. 
7. Es wird eine Meldung angezeigt, der Sie aufgefordert werden, den Kauf über Apple School Manager abzuschließen. Klicken Sie auf den Link, um Apple School Manager aufzurufen.
8. Führen Sie die Schritte im Apple School Manager, um den Kauf abzuschließen. Sie werden aufgefordert, Ihre Lizenzen an die gewünschte Position.
9. Zurück zu Intune for Education > **Apps**. Ihre app wird angezeigt, der **iOS-Apps** Liste. Wenn Sie es sofort nicht sehen, warten Sie einige Minuten, und aktualisieren Sie die Seite.

### <a name="view-app-details"></a>App-Details anzeigen
Apps unter in der Liste der Apps angezeigt **iOS-Apps**. Klicken Sie auf die app zum Anzeigen der:

* **Übersicht:** Listet auf app-Name, Herausgeber und Datum, die Sie zu Intune hinzugefügt haben. Führt außerdem die Anzahl der Lizenzen verfügbar, zugewiesen.
* **Gruppen**: Listet alle Gruppen, die die app zugewiesen werden. Ändern Sie hier gruppenzuweisungen, oder wechseln Sie zur Detailseite für eine bestimmte Gruppe.
* **Installationsstatus**: Zeigt Details zu der app-Installation, beispielsweise für das Gerät, dem er zugewiesen wurde. Der Status listet auch auf, Zeitpunkt der letzten Eincheckvorgang und bei die Installation ein Erfolg oder Fehler immer noch in Bearbeitung.

## <a name="reassign-vpp-purchased-licenses"></a>VPP-erworbenen Lizenzen zuweisen
VPP per Volumenlizenz erworbene apps können nicht von Intune for Education nicht gelöscht werden. Sie können jedoch einen Benutzer aus einer zugewiesenen Gruppe entfernen, oder entfernen die gesamte Gruppe von Zuweisung.  

