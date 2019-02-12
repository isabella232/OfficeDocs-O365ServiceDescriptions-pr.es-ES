---
title: Límites de SharePoint Online
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Busque los límites de SharePoint Online para planes de Office 365 Enterprise e independientes.
ms.openlocfilehash: 9d960aa50bef0b200fef2afe63ac1732cf201582
ms.sourcegitcommit: 30a452b9b9a0d8fc288e5911235454cc8f1907be
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/12/2019
ms.locfileid: "25848695"
---
# <a name="sharepoint-online-limits"></a>Límites de SharePoint Online

Busque los límites de SharePoint para los planes de Office 365 y los planes independientes de SharePoint Online.
  
## <a name="limits-by-plan"></a>Límites por plan

|||||
|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Office 365 para el negocio o empresa Premium** <br/> |**Office 365 Enterprise E1, E3, o E5 o SharePoint Online Plan 1 o 2** <br/> | **Office 365 Enterprise F1** <br/> |
|Almacenamiento<sup>1, 2</sup> <br/> |1 TB por organización más de 10 GB por cada licencia adquirida  <br/> |1 TB por organización más de 10 GB por licencia adquirieron<sup>3</sup> <br/> |1 TB por organización <sup>3</sup> <br/> |
|Almacenamiento para colecciones de sitios  <br/> |Hasta 25 TB por colección de sitios o grupo<sup>4</sup> <br/> |Hasta 25 TB por colección de sitios o grupo<sup>4</sup> <br/> |Hasta 25 TB por colección de sitios o grupo<sup>5</sup> <br/> |
|Colecciones de sitios por organización  <br/> |500.000<sup>6</sup> <br/> |500.000<sup>6</sup> <br/> |500,000<br/> |
|Número de usuarios  <br/> |Hasta 300  <br/> |1- 500 000<sup>7</sup> <br/> |1- 500 000<sup>7</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> puede comprar una cantidad ilimitada de almacenamiento adicional de SharePoint Online. Vea [cambiar el espacio de almacenamiento para la suscripción](https://support.office.com/article/96EA3533-DE64-4B01-839A-C560875A662C).<br/><sup>2</sup> se recomienda supervisar la Papelera de reciclaje y se vacían regularmente. El espacio de almacenamiento que utiliza es parte del límite de almacenamiento total del archivo de la organización.<br/> <sup>3</sup> Si tiene una suscripción a Office 365 y un plan independiente SharePoint Online, las cantidades de almacenamiento se suman.<br/><sup>4</sup> los administradores de SharePoint Online pueden establecer límites de almacenamiento para sitios y colecciones de sitios.<br/> <sup>5</sup> los trabajadores de Quiosco no pueden administrar colecciones de sitios de SharePoint Online. Necesita al menos una licencia de usuario de empresa para administrar colecciones de sitios de quiosco.<br/> <sup>6</sup> No se incluyen las colecciones de sitios de OneDrive para la Empresa creadas para cada licencia de usuario.<br/><sup>7</sup>Si tiene más de 500.000 usuarios, póngase en contacto con un representante de Microsoft. 
  

  
## <a name="service-limits-for-all-plans"></a>Límites del servicio para todos los planes

- **Elementos en listas y bibliotecas** : una lista puede tener hasta 30 millones de elementos y puede tener una biblioteca de archivos y carpetas de hasta 30 millones. Las vistas pueden tener hasta 12 columnas de búsqueda. Para obtener más información acerca de otras restricciones para ver listas de gran tamaño, vea [administrar grandes listas y bibliotecas en Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784). Para obtener información acerca de los caracteres que no se puede usar en los nombres de archivo, consulte [caracteres no válidos en los nombres de archivo y carpeta](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Tamaño de archivo y longitud de ruta de acceso de archivo** - 15 GB. Para obtener más información acerca de las restricciones y límites cuando se usa al nuevo cliente de sincronización de OneDrive (OneDrive.exe), vea [tipos de archivo en OneDrive, OneDrive para la empresa y SharePoint y los nombres de archivo no válido](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Sincronización** : para lograr un rendimiento óptimo, se recomienda almacenar los archivos de no más de 300.000 en una única biblioteca OneDrive o equipo en el sitio. Aunque puede almacenar 30 millones de documentos por biblioteca de SharePoint Online, para lograr un rendimiento óptimo se recomienda la sincronización de archivos no más de 300.000 a través de todas las bibliotecas de documentos. Además, los mismos problemas de rendimiento pueden producirse si tiene 300.000 elementos o más a través de todas las bibliotecas que se están sincronizando, incluso si no están sincronizando todos los elementos de dichas bibliotecas. Si usa el OneDrive anterior para el cliente de sincronización de negocio (Groove.exe), el límite de sincronización por biblioteca es 20.000 elementos (incluidos los 5.000 elementos por sitio de grupo).

- **Versiones** - 50.000 versiones principales y versiones secundarias 511.

- **Los grupos de SharePoint** : un usuario puede pertenecer a los grupos de 5.000 y cada grupo puede tener hasta 5.000 usuarios. Puede tener grupos de hasta 10.000 por colección de sitios.

- **Managed metadata** - 200.000 términos en el almacén de términos, conjuntos de términos globales 1.000, 1.000 grupos.

- **Subsitios** - hasta 2.000 por colección de sitios.

- **Aplicaciones hospedadas de SharePoint** - 20.000 instancias por la organización.

- **Los ámbitos de seguridad único por la lista o biblioteca** - 5.000. Para listas de gran tamaño, diseño tengan permisos únicos tan pocos como sea posible.

- **Los usuarios** - 2 millones por colección de sitios.

> [!NOTE]
> No hay ningún límite en el número de usuarios externos que se pueden invitar a las colecciones de sitios de SharePoint Online. Para obtener más información, consulte [Administrar el uso compartido externo en su entorno de SharePoint Online](/sharepoint/external-sharing-overview).

## <a name="see-also"></a>Vea también

[Límites de búsqueda de SharePoint Online](/sharepoint/search-limits)