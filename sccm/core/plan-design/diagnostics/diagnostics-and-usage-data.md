---
title: "Données d’utilisation et de diagnostic | System Center Configuration Manager"
description: "Découvrez quelles données d’utilisation et de diagnostic System Center Configuration Manager collecte à son sujet."
ms.custom: na
ms.date: 10/06/2016
ms.prod: configuration-manager
ms.reviewer: na
ms.suite: na
ms.technology:
- configmgr-other
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 88ac4e55-d47b-4c94-b9c3-704c6a48b845
caps.latest.revision: 9
caps.handback.revision: 0
author: Brenduns
ms.author: brenduns
manager: angrobe
translationtype: Human Translation
ms.sourcegitcommit: 1134bb2f04152288e72d40b1b1083f415cb4e900
ms.openlocfilehash: 996efaeb89926b04d2f071cf600dcf45bd2edc89


---
# <a name="diagnostics-and-usage-data-for-system-center-configuration-manager"></a>Données d’utilisation et de diagnostic pour System Center Configuration Manager

*S’applique à : System Center Configuration Manager (Current Branch)*

System Center Configuration Manager collecte les données d’utilisation et de diagnostic qui le concernent. Microsoft utilise ensuite ces données pour améliorer le processus d’installation, la qualité et la sécurité des versions ultérieures.  

 Les données d’utilisation et de diagnostic sont collectées pour chaque hiérarchie System Center Configuration Manager. Elle consistent en requêtes SQL Server qui s’exécutent chaque semaine sur chaque site principal et sur le site d’administration centrale. Quand la hiérarchie utilise un site d’administration centrale, les données provenant des sites principaux sont répliquées sur ce site. Sur le site de niveau supérieur de votre hiérarchie, le point de connexion de service soumet ces informations quand il recherche des mises à jour. Si le point de connexion de service est en mode hors connexion, les informations sont transférées à l’aide de l’outil de connexion de service.  

> [!NOTE]  
>  Configuration Manager collecte uniquement les données de la base de données SQL Server des sites. Il ne collecte pas de données directement à partir des clients ni des serveurs de site.  

 Pour plus d’informations, consultez [Déclaration de confidentialité de System Center Configuration Manager](http://go.microsoft.com/fwlink/?LinkID=626527).  

 Pour en savoir plus sur les données d’utilisation et de diagnostic de System Center Configuration Manager, consultez les rubriques suivantes :  

-   [Utilisation des données d’utilisation et de diagnostic pour System Center Configuration Manager](../../../core/plan-design/diagnostics/how-diagnostics-and-usage-data-is-used.md)  

-   Niveaux de collecte des données d’utilisation et de diagnostic :
    - [Données de diagnostic pour la version 1511](/sccm/core/plan-design/diagnostics/levels-of-diagnostic-usage-data-collection-1511)
    - [Données de diagnostic pour 1602](/sccm/core/plan-design/diagnostics/levels-of-diagnostic-usage-data-collection-1602)
    - [Données de diagnostic pour la version 1606](/sccm/core/plan-design/diagnostics/levels-of-diagnostic-usage-data-collection-1606)  
    

-   [Collecte des données d’utilisation et de diagnostic par System Center Configuration Manager](../../../core/plan-design/diagnostics/how-diagnostics-and-usage-data-is-collected.md)  

-   [Guide pratique pour afficher les données d’utilisation et de diagnostic de System Center Configuration Manager](../../../core/plan-design/diagnostics/view-diagnostics-and-usage-data.md)  

-   [Programme d’amélioration des services (CEIP) pour System Center Configuration Manager](../../../core/plan-design/diagnostics/customer-experience-improvement-program-ceip.md)  

-   [Questions fréquemment posées sur les données d’utilisation et de diagnostic pour System Center Configuration Manager](../../../core/understand/frequently-asked-questions-about-diagnostics-and-usage-data.md)  

## <a name="see-also"></a>Voir aussi  
 [À propos du point de connexion de service dans System Center Configuration Manager](../../../core/servers/deploy/configure/about-the-service-connection-point.md)



<!--HONumber=Nov16_HO1-->


