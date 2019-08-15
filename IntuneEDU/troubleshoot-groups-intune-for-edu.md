---
title: Erstellen von Gruppen in Intune for Education
titleSuffix: Intune for Education
description: Informationen Sie zum Verwalten von Geräten mit Intune for Education.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: doueby
ms.date: 10/08/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 4b570196-a640-4d13-8e01-8e8553ce1468
searchScope:
- IntuneEDU
ms.openlocfilehash: dc0daff52ab3d0348b7cb0fb9256c6cf480def6b
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2019
ms.locfileid: "62147473"
---
# <a name="troubleshooting-group-actions"></a>Problembehandlung für Gruppenaktionen

Dieser Artikel beantwortet häufige gestellte Fragen zu erstellen und Bearbeiten von Gruppen in Intune for Education.

## <a name="why-cant-i-edit-the-default-groups"></a>Warum kann ich die Standardgruppen nicht bearbeiten?

Zum Zeitpunkt, die Sie Ihr Konto zu erstellen, erstellt Intune for Education einen Satz von Standardgruppen, auf Mandantenebene. Diese Gruppen&ndash;**alle Benutzer** und **alle Geräte**&ndash;kann nicht geändert werden. Nach dem Importieren Ihrer Schule und Lehrer Einträge von School Data Sync, erstellt Intune zusätzlicher Gruppen mit dem Namen **alle Lehrer** und **aller Schüler und Studenten**. Diese Gruppen können nicht geändert werden.

In seltenen Fällen können es sich mit der gleichen Untergruppe unter zwei Gruppen kommen. Wenn dieses Problem auftritt, verschieben Sie eine der Gruppen der obersten Ebene über die Untergruppe ".

## <a name="why-cant-i-edit-dynamic-groups"></a>Warum kann ich dynamische Gruppen nicht bearbeiten?

Intune for Education ermöglicht Sie eine Teilmenge von dynamischen Attribute in der vollständigen Intune-Verwaltungsportal auswählen. Wenn das Attribut, das Sie bearbeiten möchten nicht in Intune for Education-Portals angezeigt wird, müssen Sie sie in Intune im Azure-Portal oder Azure Active Directory bearbeiten.

## <a name="why-cant-i-edit-a-specific-group"></a>Warum kann ich eine bestimmte Gruppe nicht bearbeiten?  

Intune for Education dient eine einfache Möglichkeit zum Verwalten von Geräten in Ihrer Schulen sollen. Er verwendet [Intune im Azure-Portal](https://docs.microsoft.com/intune/what-is-intune)&ndash;ein Produkt für Unternehmen&ndash;zum Verwalten von apps und Gruppen. Bestimmte Administratoren in Ihrer Organisation über die Berechtigung, Intune im Azure-Portal und Intune for Education zu verwenden, um besonderen Gruppen zu erstellen. Wenn Sie eine Gruppe nicht bearbeiten können, ist es wahrscheinlich, dass es in Intune im Azure-Portal erstellt wurde, und Sie keine Berechtigungen zum Ändern der Gruppe besitzen.  
