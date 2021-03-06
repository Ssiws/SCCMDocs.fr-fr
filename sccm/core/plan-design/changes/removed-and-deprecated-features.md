---
title: "Fonctionnalités dépréciées | Documents Microsoft"
description: "Découvrez les fonctionnalités, produits et systèmes d’exploitation que System Center Configuration Manager ne prend plus en charge."
ms.custom: na
ms.date: 12/29/2016
ms.prod: configuration-manager
ms.reviewer: na
ms.suite: na
ms.technology:
- configmgr-other
ms.tgt_pltfrm: na
ms.topic: get-started-article
ms.assetid: d8c8b44c-1e8a-42b6-bab4-23c72a0a6169
caps.latest.revision: 15
caps.handback.revision: 0
author: Brenduns
ms.author: brenduns
manager: angrobe
translationtype: Human Translation
ms.sourcegitcommit: 16781e281676c8c1092108d16beaf7e0b16d45a7
ms.openlocfilehash: e788a3c54e3620db92f1cc3e8246e5469189a802


---
# <a name="removed-and-deprecated-features-for-system-center-configuration-manager"></a>Fonctionnalités supprimées et déconseillées dans System Center Configuration Manager

*S’applique à : System Center Configuration Manager (Current Branch)*

Cette rubrique décrit les fonctionnalités, produits et systèmes d’exploitation dont la prise en charge est supprimée pour System Center Configuration Manager, ou qui seront supprimés dans une prochaine mise à jour (dépréciés). Elle annonce les changements à venir qui pourraient affecter votre utilisation de Configuration Manager.  

Ces informations peuvent faire l’objet de modifications dans les futures versions et ne pas inclure chaque fonctionnalité, produit ou système d’exploitation déprécié.  

## <a name="how-to-use-this-information"></a>Utilisation de ces informations  
Quand une fonctionnalité ou un système d’exploitation sont répertoriés pour la première fois comme étant dépréciés, leur prise en charge dans Configuration Manager est prévue d’être supprimée dans une version future. Ces informations sont fournies pour vous permettre de planifier des alternatives à l’utilisation de cette fonctionnalité ou de ce système d’exploitation. Cette rubrique est mise à jour quand est publiée la première version de Configuration Manager où la prise en charge est supprimée.  

Quand la prise en charge d’une fonctionnalité ou d’un système d’exploitation est supprimée, la fonctionnalité ou le système d’exploitation continuent d’être pris en charge dans les versions antérieures de Configuration Manager aussi longtemps que celles-ci restent prise en charge. Cependant, quand vous utilisez une version de Configuration Manager publiée après la date ou la version indiquée, cette version de Configuration Manager ne fournit pas de prise en charge.

Par exemple, si la suppression de la prise en charge d’une fonctionnalité a été planifiée dans la première mise à jour publiée après septembre 2016, la prise en charge de cette fonctionnalité n’est plus incluse dans la mise à jour 1610, publiée en octobre 2016.
-  Avec la mise à jour 1610, la fonctionnalité ne serait ainsi plus prise en charge.
-  Cette rubrique serait mise à jour pour indiquer que la prise en charge a été supprimée avec la version 1610.
Cependant, si vous continuez à utiliser une version antérieure qui prend en charge la fonctionnalité, comme la version 1602 ou 1606, vous pouvez continuer à utiliser cette fonctionnalité, jusqu’à ce que la version que vous utilisez supprime la prise en charge.

Pour plus d'informations, voir :
 - Le site web [Politique de support Microsoft](https://support.microsoft.com/lifecycle).
 - [Prise en charge des versions Current Branch de System Center Configuration Manager](/sccm/core/servers/manage/current-branch-versions-supported).

## <a name="deprecated-features"></a>Fonctionnalités dépréciées  

|**Fonctionnalité**|**Première annonce de dépréciation**|**Support supprimé**|  
|-|-|-|  
|Protection d’accès réseau (NAP) : telle que dans System Center 2012 Configuration Manager|10 juillet 2015|Version 1511|  
|Gestion hors bande : telle que dans System Center 2012 Configuration Manager|16 octobre 2015|Version 1511|
|Séquences de tâches : <br /> - Convertir en disque dynamique <br /> - Installer les outils de déploiement |18 novembre 2016|La prise en charge de ces séquences de tâches prend fin avec la première mise à jour publiée après le 1er juin 2017.|
|Le Centre logiciel a été modernisé. Les applications qui seraient apparues uniquement dans le catalogue des applications dépendant de Silverlight (applications accessibles à l’utilisateur) apparaissent désormais dans le Centre logiciel, sous l’onglet **Applications**. Il est toujours possible d’accéder au catalogue des applications via le lien situé sous l’onglet **État de l’installation** du Centre logiciel.<br><br>Dans les prochains mois, la version précédente du Centre logiciel ne sera plus disponible.<br><br>Vous pouvez configurer les clients pour qu’ils utilisent le nouveau Centre logiciel en activant le paramètre client **Agent ordinateur** > **Utiliser le nouveau Centre logiciel**.<br><br>Pour plus d’informations sur le Centre logiciel, consultez [Planifier et configurer la gestion des applications dans System Center Configuration Manager](https://docs.microsoft.com/sccm/apps/plan-design/plan-for-and-configure-application-management).|13 décembre 2016|Annoncé prochainement|


Informations supplémentaires sur les fonctionnalités supprimées avec la version 1511 de System Center Configuration Manager :

###  <a name="a-namebkmkamta-out-of-band-management"></a><a name="bkmk_amt"></a> Gestion hors bande  
 Avec Configuration Manager, la prise en charge native des ordinateurs AMT à partir de la console Configuration Manager est supprimée.  

-   Les ordinateurs AMT restent entièrement gérés quand vous utilisez le [module complémentaire Intel SCS pour Microsoft System Center Configuration Manager](http://www.intel.com/content/www/us/en/software/setup-configuration-software.html). Ce module complémentaire vous permet d’accéder aux dernières fonctionnalités permettant de gérer AMT tout en supprimant les limitations introduites jusqu’à ce que Configuration Manager puisse intégrer ces changements.  

-   La gestion hors bande dans System Center 2012 Configuration Manager n’est pas affectée par cette modification.  

###  <a name="a-namebkmknapa-network-access-protection"></a><a name="bkmk_nap"></a> Protection d’accès au réseau  
 System Center Configuration Manager ne prend pas en charge la protection d’accès réseau. La fonctionnalité est dépréciée dans Windows Server 2012 R2 et a été supprimée dans Windows 10.  

 Pour les solutions de protection d'accès réseau, consultez la section *Fonctionnalités déconseillées* dans [Vue d'ensemble des services de stratégie et d'accès réseau](https://technet.microsoft.com/library/hh831683.aspx).  


## <a name="deprecated-operating-systems"></a>Systèmes d’exploitation dépréciés
### <a name="server-operating-systems"></a>Systèmes d'exploitation serveur  

|**Systèmes d’exploitation**|**Première annonce de dépréciation**|**Support supprimé** |  
|-|-|-|  
|Windows Server 2008|10 juillet 2015|La prise en charge prend fin avec la première mise à jour publiée après le 31 décembre 2016 (voir la remarque 1).|  
|Windows Server 2008 R2|10 juillet 2015|La prise en charge prend fin avec la première mise à jour publiée après le 31 décembre 2016 (voir la remarque 2).|  

-   Remarque 1 : après la fin de la prise en charge, ce système d’exploitation ne sera plus pris en charge pour les serveurs de site ou la plupart des rôles système de site. Cependant, ce système d’exploitation continue d’être pris en charge pour le rôle système de site de point de distribution (dont le point de distribution d’extraction) jusqu’à ce que cette prise en charge soit annoncée comme dépréciée ou que la période étendue de prise en charge de ce système d’exploitation expire.  

-   Remarque 2 : après la fin de la prise en charge, ce système d’exploitation ne sera plus pris en charge pour les serveurs de site ou la plupart des rôles système de site. Cependant, ce système d’exploitation continue d’être pris en charge pour le point de migration d’état et le rôle de système de site de point de distribution (dont les points de distribution d’extraction, ainsi que pour PXE et la multidiffusion) jusqu’à ce que cette prise en charge soit annoncée comme dépréciée ou que la période étendue de prise en charge de ce système d’exploitation expire. Depuis la version 1602, vous pouvez mettre à niveau sur place le système d’exploitation d’un serveur de site à partir de Windows Server 2008 R2 vers Windows Server 2012 R2.  

     Pour plus d’informations sur la mise à niveau sur place d’un système d’exploitation de serveurs de site, consultez la section qui traite de la [mise à niveau sur place du système d’exploitation des serveurs de site qui exécutent Windows Server 2008 R2](../../../core/plan-design/changes/whats-new-in-version-1602.md#bkmk_UpgradeOS) dans [Nouveautés de System Center Configuration Manager](../../../core/plan-design/changes/what-has-changed-from-configuration-manager-2012.md).



### <a name="client-operating-systems"></a>Systèmes d'exploitation client  

 Sauf indication contraire, chaque système d’exploitation pris en charge en tant que client Configuration Manager est pris en charge jusqu’à la date de fin de sa prise en charge étendue. Pour plus d’informations sur les dates de fin de prise en charge étendue, consultez la [Politique de support Microsoft](https://support.microsoft.com/lifecycle). Si la prise en charge de Configuration Manager pour un système d’exploitation se termine avant la date de fin de prise en charge étendue, une date de dépréciation et une date de suppression du support de ce système d’exploitation seront mentionnées ici.  

|**Systèmes d’exploitation**|**Première annonce de dépréciation**|**Support supprimé**|  
|-|-|-|  
|Windows XP|10 juillet 2015|Version 1511|  
|Windows XP Embedded|10 juillet 2015|La prise en charge prend fin avec la première mise à jour publiée après le 31 décembre 2016.|  
|Windows Server 2003|10 juillet 2015|Version 1511|  
|Windows Server 2003 R2|10 juillet 2015|Version 1511|  
|Windows Vista|10 juillet 2015|Version 1511|  
|Mac OS X 10.6 - 10.8|10 juillet 2015|Version 1511|  
|Windows Mobile 6.0 - 6.5|10 juillet 2015|Version 1511|  
|Nokia Symbian Belle|10 juillet 2015|Version 1511|  
|Windows CE 5.0 - 6.0|10 juillet 2015|Version 1511|  


## <a name="deprecated-support-for-sql-server-versions-as-a-site-database"></a>Prise en charge dépréciée pour les versions de SQL Server en tant que base de données de site  

|**Versions de SQL Server**|**Première annonce de dépréciation**|**Support supprimé**|   
|-|-|-|  
|SQL Server 2008|10 juillet 2015|Version 1511|  
|SQL Server 2008 R2|10 juillet 2015|La prise en charge prend fin avec la première mise à jour publiée après le 31 décembre 2016.|  




<!--HONumber=Dec16_HO5-->


