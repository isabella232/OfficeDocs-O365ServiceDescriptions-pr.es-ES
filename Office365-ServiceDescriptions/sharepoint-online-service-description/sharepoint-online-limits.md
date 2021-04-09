---
title: Límites de SharePoint
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Obtenga información sobre los límites de SharePoint para Microsoft 365 y los planes independientes.
ms.openlocfilehash: 08d0f2f69e1f1b096b2dcd2f66cf083fa239a52e
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653412"
---
# <a name="sharepoint-limits"></a>Límites de SharePoint

Obtenga información sobre los límites de servicio en SharePoint para Microsoft 365.
  
## <a name="limits-by-plan"></a>Límites por plan 

| Característica | Microsoft 365 Empresa Basic, Business Standard o Business Premium | Microsoft 365 E3 o E5, Office 365 E1, E3 o E5, o SharePoint Plan 1 o 2 | Microsoft 365 F1 o F3, Office 365 F3 |
|:-----|:-----|:-----|:-----|
|Almacenamiento total por organización<sup>1, 2, 6</sup> <br/> |1 TB más 10 GB por licencia comprada<sup>3</sup>  <br/> |1 TB más 10 GB por licencia comprada<sup>3</sup> <br/> |1 TB<sup>3</sup> <br/> |
|Almacenamiento máximo por sitio (colección de<sup>sitios) 4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|Sitios (colecciones de sitios) por organización  <br/> |2 millones<sup>6</sup> <br/> |2 millones<sup>6</sup> <br/> |2 millones<br/> |
|Número de usuarios  <br/> |Hasta 300  <br/> |1- 500 000<sup>7</sup> <br/> |1- 500 000<sup>7</sup> <br/> |
   
<sup>1</sup> [Obtenga información sobre cómo encontrar el almacenamiento total y disponible para su organización.](/sharepoint/manage-site-collection-storage-limits) Puede comprar una cantidad ilimitada de almacenamiento adicional de SharePoint. Consulte [Agregar espacio de almacenamiento para la suscripción.](/office365/admin/subscriptions-and-billing/add-storage-space) 
<br/><sup>2</sup> Se recomienda supervisar la Papelera de reciclaje y vaciarla periódicamente. El espacio de almacenamiento que usa forma parte del límite de almacenamiento total de la organización. 
<br/> <sup>3</sup> Si tiene una suscripción a Microsoft 365 y un complemento de almacenamiento de archivos adicional de Office 365, se agregan los importes de almacenamiento. 
<br/> <sup>4</sup> Este es el límite *de* almacenamiento de un solo sitio (anteriormente denominado "colección de sitios"), no la cantidad de almacenamiento *proporcionada* para cada sitio. Este límite se aplica a todos los tipos de sitios, incluidos los sitios de grupo conectados a grupos de Office 365 y OneDrive. Los administradores de SharePoint [pueden establecer manualmente límites de almacenamiento inferiores.](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits) 
<br/> <sup>5</sup> Los trabajadores de Firstline no pueden administrar sitios de SharePoint. 
<br/> <sup>6 No</sup> incluye el OneDrive creado para cada usuario con licencia. 
<br/> <sup>7</sup> Si tiene más de 500 000 usuarios, póngase en contacto con un representante de Microsoft. 
  
## <a name="service-limits-for-all-plans"></a>Límites de servicio para todos los planes

### <a name="items-in-lists-and-libraries"></a>Elementos de listas y bibliotecas

Una lista puede tener hasta 30 millones de elementos y una biblioteca puede tener hasta 30 millones de archivos y carpetas. Cuando una lista, biblioteca o carpeta contiene más de 100 000 elementos, no puede interrumpir la herencia de permisos en la lista, biblioteca o carpeta. Tampoco puede volver a heredar permisos en él. Sin embargo, puede interrumpir la herencia en los elementos individuales de esa lista, biblioteca o carpeta, hasta el número máximo de permisos únicos en la lista o biblioteca (vea la sección siguiente). Para obtener más información sobre otras restricciones para ver listas grandes, vea [Manage large lists and libraries in Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784).

### <a name="unique-security-scopes-per-list-or-library"></a>Ámbitos de seguridad únicos por lista o biblioteca

Para listas grandes, el diseño debe tener el menor número de permisos únicos posibles y permanecer por debajo de 5.000 en total.

### <a name="file-size-and-file-path-length"></a>Tamaño de archivo y longitud de ruta de acceso de archivo

250 GB. Para obtener más información sobre las restricciones y los límites al usar la nueva aplicación de sincronización de OneDrive (OneDrive.exe), vea Nombres de archivo y [tipos de archivo no válidos.](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)

### <a name="moving-and-copying-across-sites"></a>Mover y copiar entre sitios

Copiar o mover varios archivos en una sola operación tiene tres requisitos:

- No más de 100 GB de tamaño total de archivo
- No más de 30 000 archivos
- Cada archivo debe tener menos de 15 GB

### <a name="sync"></a>Sincronizar

Para obtener un rendimiento óptimo, se recomienda almacenar no más de 300 000 archivos en una sola biblioteca de sitios de onedrive o de grupo. Aunque SharePoint Online puede almacenar 30 millones de documentos por biblioteca, para un rendimiento óptimo se recomienda sincronizar no más de 300 000 archivos en todas las bibliotecas de documentos. Además, pueden producirse los mismos problemas de rendimiento si tiene 300 000 elementos o más en todas las bibliotecas que está sincronizando, incluso si no está sincronizando todos los elementos de esas bibliotecas. Si usa el cliente de sincronización anterior de OneDrive para la Empresa (Groove.exe), el límite de sincronización por biblioteca es de 20 000 elementos (incluidos 5.000 elementos por sitio de grupo).

### <a name="versions"></a>Versiones

50 000 versiones principales y 511 versiones secundarias.

### <a name="sharepoint-groups"></a>Grupos de SharePoint

Un usuario puede pertenecer a 5.000 grupos por sitio (colección de sitios) y cada grupo puede tener hasta 5.000 usuarios. Puede tener hasta 10 000 grupos por sitio (colección de sitios).

> [!NOTE]
> Para los límites de grupo de Azure AD, consulte Límites y restricciones del servicio [de Azure AD,](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions) ya que estos límites pueden afectar a la administración de pertenencia a sitios de grupo públicos y privados.

### <a name="managed-metadata"></a>Metadatos administrados

200 000 términos en almacén de términos, 1.000 conjuntos de términos globales, 1.000 grupos.

### <a name="overall-site-metadata"></a>Metadatos generales del sitio

1000 GB por sitio (los metadatos rara vez alcanzan este tamaño).

### <a name="subsites"></a>Subsitios

2.000 por sitio (colección de sitios). Se recomienda crear sitios y organizarlos en concentradores en lugar de crear subsitios. Si usa subsitios, le recomendamos que limite su número (especialmente en sitios de gran tráfico).

> [!NOTE]
> Su organización está limitada a 2.000 sitios centrales. Es posible que no necesite un sitio central para todas las funciones y es importante realizar cierta planeación antes de crear concentradores. Para obtener más información, visite [Planning your SharePoint hub sites](/sharepoint/planning-hub-sites).

### <a name="sharepoint-hosted-applications"></a>Aplicaciones hospedadas de SharePoint

20 000 instancias por organización.

### <a name="users"></a>Usuarios

2 millones por colección de sitios.

> [!NOTE]
> No hay ningún límite distinto en el número de invitados que puede invitar a sitios de SharePoint. Para obtener más información sobre el uso compartido externo, vea [External sharing overview](/sharepoint/external-sharing-overview).

## <a name="see-also"></a>Vea también

[Límites de búsqueda para SharePoint](/sharepoint/search-limits)