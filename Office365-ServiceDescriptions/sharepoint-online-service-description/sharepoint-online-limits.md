---
title: Límites de SharePoint
ms.author: sharik
author: skjerland
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Obtenga información sobre los límites de SharePoint para los planes de Microsoft 365 y independientes.
ms.openlocfilehash: 0f8516b92d6d32477c95a4d6bbc894700f607226
ms.sourcegitcommit: 5e181c09b8f7d0946419b2fb39fb700f6168536d
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/17/2020
ms.locfileid: "44768116"
---
# <a name="sharepoint-limits"></a>Límites de SharePoint

Obtenga información sobre los límites de servicio de SharePoint para Microsoft 365.
  
## <a name="limits-by-plan"></a>Límites por plan 

|||||
|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Microsoft 365 Business Basic o Business Premium** <br/> |**Office 365 Enterprise E1, E3 o E5, o SharePoint plan 1 o 2** <br/> | **Office 365 Enterprise F3** <br/> |
|Almacenamiento total por organización<sup>1, 2, 6</sup> <br/> |1 TB más 10 GB por licencia adquirida  <br/> |1 TB más 10 GB por licencia comprado<sup>3</sup> <br/> |10 GB más 2 GB por licencia comprado<sup>3</sup> <br/> |
|Almacenamiento máximo por sitio (colección de sitios)<sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|Sitios (colecciones de sitios) por organización  <br/> |2 millones<sup>6</sup> <br/> |2 millones<sup>6</sup> <br/> |2 millones<br/> |
|Número de usuarios  <br/> |Hasta 300  <br/> |1- 500 000<sup>7</sup> <br/> |1- 500 000<sup>7</sup> <br/> |
   
<sup>1</sup> [obtenga información sobre cómo encontrar el almacenamiento total y disponible para su organización](/sharepoint/manage-site-collection-storage-limits). Puede adquirir una cantidad ilimitada de almacenamiento adicional de SharePoint. Vea [Cambiar el espacio de almacenamiento para la suscripción](/office365/admin/subscriptions-and-billing/add-storage-space). 
<br/><sup>2</sup> Se recomienda supervisar la Papelera de reciclaje y vaciarla periódicamente. El espacio de almacenamiento que usa forma parte del límite de almacenamiento total de la organización. 
<br/> <sup>3</sup> si tiene una suscripción de Microsoft 365 y un complemento de almacenamiento de archivos adicionales de Office 365, se agregan las cantidades de almacenamiento. 
<br/> <sup>4</sup> este es el *límite* de almacenamiento de un solo sitio (anteriormente denominado "colección de sitios"), no la cantidad de almacenamiento que se *proporciona* para cada sitio. Este límite se aplica a todos los tipos de sitios, incluidos los sitios de grupo conectados a Office 365 y OneDrive. Los administradores de SharePoint pueden [establecer manualmente límites de almacenamiento inferiores](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits). 
<br/> <sup>5</sup> los trabajadores de Firstline no pueden administrar los sitios de SharePoint. 
<br/> <sup>6</sup> no se incluye el OneDrive creado para cada usuario con licencia. 
<br/> <sup>7</sup>Si tiene más de 500.000 usuarios, póngase en contacto con un representante de Microsoft. 
  
## <a name="service-limits-for-all-plans"></a>Límites de servicio para todos los planes

### <a name="items-in-lists-and-libraries"></a>Elementos en listas y bibliotecas

Una lista puede tener hasta 30 millones elementos y una biblioteca puede tener hasta 30 millones archivos y carpetas. Cuando una lista, una biblioteca o una carpeta contiene más de 100.000 elementos, no se puede interrumpir la herencia de permisos en la lista, biblioteca o carpeta. Tampoco puede volver a heredar permisos en él. Sin embargo, todavía puede interrumpir la herencia de los elementos individuales dentro de esa lista, biblioteca o carpeta, hasta el número máximo de permisos únicos en la lista o biblioteca (vea la siguiente sección). Para obtener más información sobre otras restricciones para ver listas de gran tamaño, vea [administrar listas y bibliotecas de gran tamaño en Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784). 

> [!NOTE]
> No hay ningún límite en el número de bibliotecas de documentos que puede tener en un sitio.

### <a name="unique-permissions-for-items-in-a-list-or-library"></a>Permisos exclusivos para los elementos de una lista o biblioteca

El límite admitido es 50.000, pero el límite general recomendado es 5.000. Realizar cambios en más de 5.000 elementos con permisos únicos a la vez lleva más tiempo. Para listas de gran tamaño, diseñe para que tenga el menor número de permisos únicos posible.

### <a name="file-size-and-file-path-length"></a>Tamaño de archivo y longitud de la ruta de archivo

15 GB. El tamaño máximo de los archivos adjuntos a los elementos de lista es de 250 MB. Para obtener más información sobre las restricciones y los límites al usar la nueva aplicación de sincronización de OneDrive (OneDrive.exe), consulte [nombres de archivo y tipos de archivo no válidos](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

### <a name="moving-and-copying-across-sites"></a>Mover y copiar entre sitios

100 GB por operación. El explorador Web debe permanecer abierto.

### <a name="sync"></a>Sincronizar

**Nueva aplicación de sincronización de OneDrive** : para obtener un rendimiento óptimo, le recomendamos que no almacene más de 300.000 archivos en todas las bibliotecas de documentos sincronizadas, incluso si usa archivos a petición o si elige solo algunas carpetas de las bibliotecas para sincronizar.

**Aplicación de sincronización anterior de OneDrive para la empresa (Groove.exe)** : puede sincronizar hasta 20.000 elementos en total en todas las bibliotecas sincronizadas. Esto incluye bibliotecas de OneDrive, bibliotecas de sitios de grupo o ambas. Aparte del límite general de sincronización, hay límites en el número de elementos que se pueden sincronizar para cada tipo de biblioteca:

   - Puede sincronizar hasta 20.000 elementos en una biblioteca de OneDrive. Esto incluye carpetas y archivos. 
   - Puede sincronizar hasta 5.000 elementos en una biblioteca de SharePoint. Esto incluye carpetas y archivos. Estas son las bibliotecas que se encuentran en varios sitios de SharePoint, como sitios de grupo y sitios de la comunidad, bibliotecas que otras personas crearon o que ha creado desde la página sitios. Puede sincronizar varias bibliotecas de SharePoint. Los sitios de grupo que sincronice también contarán con el límite global de elementos 20.000 en todas las bibliotecas sincronizadas.

> [!NOTE]
> Si los usuarios necesitan sincronizar archivos de bibliotecas de documentos con cientos de miles de archivos, puede "ocultar" las carpetas de la aplicación de sincronización estableciendo el nivel de permisos de las carpetas como "lectura restringida". 

### <a name="versions"></a>Versiones

50.000 versiones principales y 511 versiones secundarias.

### <a name="sharepoint-groups"></a>Grupos de SharePoint

Un usuario puede pertenecer a 5.000 grupos y cada grupo puede tener hasta 5.000 usuarios. Puede tener hasta 10.000 grupos por sitio (colección de sitios).

> [!NOTE]
> Para los límites de grupo de Azure AD, consulte [límites de servicio y restricciones de Azure ad](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions) dado que estos límites pueden afectar a la administración de pertenencia de los sitios de grupo públicos y privados. 

### <a name="managed-metadata"></a>Metadatos administrados

200.000 términos en el almacén de términos, 1.000 conjuntos de términos globales, 1.000 grupos.

### <a name="overall-site-metadata"></a>Metadatos generales del sitio

1000 GB por sitio (los metadatos raramente alcanzan este tamaño).

### <a name="subsites"></a>Subsitios 

2.000 por sitio (colección de sitios). Le recomendamos que cree sitios y los organice en hubs en lugar de crear subsitios. Si usa subsitios, le recomendamos limitar su número (especialmente en los sitios menor tráfico).

### <a name="sharepoint-hosted-applications"></a>Aplicaciones hospedadas en SharePoint

20.000 instancias por organización.

### <a name="people-editing-a-document-at-the-same-time"></a>Personas que editan un documento al mismo tiempo

99 personas pueden tener un documento abierto para su edición al mismo tiempo. Si más de 10 personas editan un documento simultáneamente, es más probable que se produzcan conflictos en los cambios y la experiencia del usuario se degradará gradualmente.

### <a name="users"></a>Usuarios

2 millones por sitio (colección de sitios).
   
> [!NOTE]
> No hay ningún límite en el número de invitados que puede invitar a los sitios de SharePoint. Para obtener más información sobre el uso compartido externo, vea [external Sharing Overview](/sharepoint/external-sharing-overview).

## <a name="see-also"></a>Vea también

[Límites de búsqueda de SharePoint](/sharepoint/search-limits)
