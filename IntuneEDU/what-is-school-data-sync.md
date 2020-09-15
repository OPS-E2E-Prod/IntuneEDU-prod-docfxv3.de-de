---
title: Importieren von Schul-/ unidatensätzen mit School Data Sync
titleSuffix: Intune for Education
description: Verwendet Datensynchronisierung von Schul-/ UNI-Gruppen und Benutzer in Azure AD zu importieren.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: f9cb6daf-a789-427b-bbfd-fa0a3d36e01f
searchScope:
- IntuneEDU
ms.openlocfilehash: ec80e1b8f8d2851814227420b5026dd3c488277c
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146560"
---
# <a name="microsoft-school-data-sync-and-intune-for-education"></a>Microsoft School Data Sync und Intune for Education

Gruppenrichtlinien-Verwaltungskonsole (Microsoft School Data Sync, SDS) ist ein kostenloser Dienst in Office 365 Education, mit denen Schul-/ unidatensätzen aus Ihrem vorhandenen für Schüler und Studenten Studenteninformationssystem (SIS) importiert werden. Es erstellt online Classrooms und Gruppen für Microsoft Teams, Intune für Bildungseinrichtungen und Drittanbieter-Anwendungen.  

Wechseln Sie in der Dokumentation School Data Sync [erfahren, wie Sie die Bereitstellung von SDS](https://support.office.com/article/Overview-of-School-Data-Sync-and-Classroom-f3d1147b-4ade-4905-8518-508e729f2e91). 

## <a name="create-groups-from-school-roster"></a>Erstellen von Gruppen aus der Liste der "School"
SDS erstellt Kopien der Daten aus dem SIS und speichert sie in Azure Active Directory (Azure AD). SDS erstellt zwei Gruppen in Intune for Education, die auf dem Sie Einstellungen und apps anwenden können:

* Alle Schüler/Studenten
* Alle Lehrer

Weitere Informationen zum Erstellen von Gruppen in Intune for Education finden Sie unter [Erstellen von Gruppen](create-groups.md).  

## <a name="set-up-dynamic-group-properties"></a>Richten Sie dynamischen Gruppe-Eigenschaften
Beim Importieren von Informationen über Schüler aus dem SIS in Intune for Education mit School Data Sync, schließen Sie die folgenden Eigenschaften:
*  Auf Unternehmensniveau 
*  Abschlussjahr  

Diese Eigenschaften sind erforderlich, um erstellen [dynamische Gruppe](create-groups.md#dynamic-groups) Regeln für Schüler/Studenten in Intune for Education-Portals.  Eigenschaften aus der SDS-app konfiguriert ist, und finden Sie im __für Schüler und Studenten Optionen__ > __wählen Sie für Schüler und Studenten Eigenschaften__.

## <a name="what-is-azure-ad"></a>Was ist Azure AD?
Azure AD ist ein Microsoft-Verwaltungssystem, die in Intune integriert und unterstützt Sie beim Organisieren, Schüler/Studenten und Geräte. Sie können z. B. Erstellen von Gruppen aus Ihrer Schüler/Studenten und Lehrkräfte, *4. Zeitraum Biologie* oder *Contoso Bezirk Lehrer*. Gruppen sind erforderlich, um die Verteilung und Benutzer- oder gerätespezifische apps, Einstellungen und Einschränkungen.

## <a name="next-steps"></a>Nächste Schritte   
Nachdem Ihre Studenten und Lehrkräften Informationen für Intune for Education synchronisiert ist, beginnen Sie mit der express-Konfiguration für [Windows](edu-express-config-settings-windows.md) oder [iOS](edu-express-config-settings-ios.md) Geräte.  

Möchten Sie mehr über Microsoft School Data Sync zu erfahren? Besuchen Sie die [Microsoft School Data Sync-Seite](https://sds.microsoft.com) Produktinformationen. 
