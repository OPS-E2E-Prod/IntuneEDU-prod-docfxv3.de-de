---
title: Wie installiere ich apps?
titleSuffix: Intune for Education
description: Erfahren Sie, wie Sie apps für Intune for Education verwalten.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 635a5cc7-7dd4-45f9-9b18-3eddb76d0c74
searchScope:
- IntuneEDU
ms.openlocfilehash: 260679748d8ddb891d042abd6e0d7d0f5f698b34
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146536"
---
# <a name="installing-apps-on-school-devices"></a>Installieren von apps auf School-Geräte

Um eine app auf einem Gerät "School" zu installieren, müssen Sie sie zuerst eine Gruppe zuweisen. Dieser Artikel beschreibt die drei Möglichkeiten zum Zuweisen von apps zu Schüler-Lehrer.  

Nachdem Sie eine app zugewiesen haben, wird die app an das entsprechende Gerät gesendet. App-Installation wird initiiert, wenn das Gerät zu Intune for Education eincheckt. 

## <a name="add-apps-to-intune-for-education-inventory"></a>Hinzufügen von apps in Intune für Bildungseinrichtungen-Inventur
Standardmäßig sind beliebte apps in Intune for Education für sofortige Zuweisung verfügbar sind. Wenn die app, die Sie zuweisen möchten, in Ihrem Bestand nicht ist, erfahren Sie, wie sie zu Intune for Education mit den folgenden Artikeln hinzuzufügen:
* [Microsoft Store für Bildungseinrichtungen-apps](acquire-store-apps.md)
* [Kostenlose Apps aus dem iOS-App Store](add-apps-ios.md)
* [VPP-Apps für iOS](add-vpp-apps-ios.md)
* [Windows 10-desktop-apps](add-desktop-apps-edu.md)
* [Web-Apps](add-web-apps-edu.md)  

## <a name="assign-apps-with-express-configuration"></a>Zuweisen von apps mit Express-Konfiguration
Wechseln Sie zu [express-Konfiguration](Express-configuration-intune-edu.md) Zuweisen von mehreren apps auf eine einzelne Gruppe. 

1. Intune for Education-Dashboard, klicken Sie auf **Express-Konfiguration**.  
2. Wählen Sie die Gruppe, die apps hinzugefügt werden soll. Klicken Sie dann auf **Weiter**.
3. Wählen Sie eine oder mehrere apps für Ihre Gruppe bereitstellen. Klicken Sie dann auf **Weiter**. 
4. Die apps werden automatisch der Gruppe zugewiesen werden. Fahren Sie mit der express-Konfiguration fort.

##  <a name="assign-apps-to-a-single-group"></a>Zuweisen von apps für eine einzelne Gruppe
Wählen Sie eine Gruppe aus, und installieren Sie eine oder mehrere apps für die Geräte in dieser Gruppe.

1. Intune for Education-Dashboard, klicken Sie auf **Gruppen**.
2. Wählen Sie die Gruppen, denen Sie die apps bereitstellen möchten.
3. Wechseln Sie zu der Symbolleiste am oberen Rand, und klicken Sie auf **Apps** um eine Liste der verfügbaren apps anzuzeigen.  
4. Wählen Sie eine oder mehrere apps für Ihre Gruppe bereitstellen. 
5. Wählen Sie **speichern** für die ausgewählten apps in dieser Gruppe. Installation wird automatisch das nächste Mal gestartet, das die Geräte zu Intune for Education checkt.  

## <a name="asign-apps-to-multiple-groups"></a>Möchten apps für mehrere Gruppen
Wählen Sie eine app, und weisen Sie eine oder mehrere Gruppen für die Installation.

1. Intune for Education-Dashboard, klicken Sie auf **Apps**.
2. Wählen Sie aus der Liste der apps auf der linken Seite die app, die Sie zuweisen möchten.
3. Wechseln Sie zu der Symbolleiste am oberen Rand, und klicken Sie auf **Gruppen** > **gruppenzuweisungen ändern**. 
4. Wählen Sie die Gruppen, denen Sie die app zuweisen möchten.  
