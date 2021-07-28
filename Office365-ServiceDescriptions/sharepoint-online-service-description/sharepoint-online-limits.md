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
description: Obtenga información sobre los límites de SharePoint para Microsoft 365 y planes independientes.
ms.openlocfilehash: 44571cedf74b2a094231173b87731916d9e26975
ms.sourcegitcommit: 10699cc17ddfed6af78ce1466f478b2bd67ba26a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/08/2021
ms.locfileid: "53338343"
---
# <a name="sharepoint-limits"></a>Límites de SharePoint

Obtenga información sobre los límites de servicio en SharePoint para Microsoft 365.
  
## <a name="limits-by-plan"></a>Límites por plan 

| Característica | Microsoft 365 Empresa Básico, Microsoft 365 Empresa Estándar o Microsoft 365 Empresa Estándar | Microsoft 365 E3 o E5, Office 365 E1, E3 o E5, o SharePoint Plan 1 o 2 | Microsoft 365 F1 o F3, Office 365 F3 |
|:-----|:-----|:-----|:-----|
|Almacenamiento total por organización<sup>1, 2, 6</sup> <br/> |1 TB, además de 10 GB por cada licencia adquirida<sup>3</sup>  <br/> |1 TB, además de 10 GB por cada licencia adquirida<sup>3</sup> <br/> |1 TB<sup>3</sup> <br/> |
|Almacenamiento máximo por sitio (colección de sitios)<sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|Sitios (colecciones de sitios) por organización  <br/> |2 millones<sup>6</sup> <br/> |2 millones<sup>6</sup> <br/> |2 millones<br/> |
|Número de usuarios  <br/> |Hasta 300  <br/> |1- 500 000<sup>7</sup> <br/> |1- 500 000<sup>7</sup> <br/> |
   
<sup>1</sup> [Obtenga información sobre cómo encontrar el almacenamiento total y disponible para su organización](/sharepoint/manage-site-collection-storage-limits). Puede adquirir una cantidad ilimitada de almacenamiento de SharePoint. Vea [Agregar espacio de almacenamiento a la suscripción](/office365/admin/subscriptions-and-billing/add-storage-space) 
<br/><sup>2</sup> Se recomienda supervisar la Papelera de reciclaje y vaciarla periódicamente. El espacio de almacenamiento que se utiliza es parte del límite de almacenamiento total de la organización. 
<br/> <sup>3</sup> Si tiene una suscripción a Microsoft 365 y un complemento de Office 365 Extra File Storage, se agregan las cantidades de almacenamiento. 
<br/> <sup>4</sup> Este es el *límite* de almacenamiento para un único sitio (anteriormente denominado "colección de sitios"), no la cantidad de almacenamiento *proporcionada* para cada sitio. Este límite se aplica a todos los tipos de sitios, incluidos los sitios de grupo conectados a grupos de Office 365 y OneDrive. Los administradores de SharePoint pueden [establecer manualmente límites de almacenamiento inferiores](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits). 
<br/> <sup>5</sup> Los trabajadores de primera línea no pueden administrar sitios de SharePoint. 
<br/> <sup>6</sup> No se incluyen los OneDrive creados para cada usuario con licencia. 
<br/> <sup>7</sup> Si tiene más de 500 000 usuarios, póngase en contacto con un representante de Microsoft. 
  
## <a name="service-limits-for-all-plans"></a>Límites de servicio para todos los planes

### <a name="items-in-lists-and-libraries"></a>Elementos en listas y bibliotecas

Una lista puede contener un máximo de 30 millones de elementos, mientras que una biblioteca puede contener hasta 30 millones de archivos y carpetas. Cuando una lista, biblioteca o carpeta contiene más de 100 000 elementos, no se puede interrumpir la herencia de permisos en la lista, biblioteca o carpeta. Tampoco puede volver a heredar permisos en ellas. Sí puede interrumpir la herencia en los elementos individuales de esa lista, biblioteca o carpeta, hasta el número máximo de permisos únicos en la lista o biblioteca (vea la sección siguiente). Para obtener más información sobre otras restricciones de visualización de listas grandes, consulte [Administración de grandes listas y bibliotecas en Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784).

### <a name="unique-security-scopes-per-list-or-library"></a>Ámbitos de seguridad únicos por lista o biblioteca

Para listas grandes, prevea tener el menor número de permisos únicos posible y permanecer por debajo de 5000 en total.

### <a name="file-size-and-file-path-length"></a>Tamaño de archivo y longitud de la ruta de acceso del archivo

- **Límite de carga de archivos de 250 GB** Rige para cada archivo individual cargado en la pestaña Archivos de Microsoft Teams, bibliotecas de documentos de SharePoint, carpetas de OneDrive y conversaciones de Yammer.

- **Archivo adjunto a un elemento de lista: 250 MB:** Se aplica a Listas Microsoft y listas de SharePoint, ambas basadas en la misma plataforma de listas.

Para obtener más información sobre las restricciones y límites al usar la nueva aplicación Sincronización de OneDrive (OneDrive.exe), vea [Nombres de archivo y tipos de archivo no válidos](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

### <a name="moving-and-copying-across-sites"></a>Mover y copiar entre sitios

Copiar o mover varios archivos en una sola operación tiene tres requisitos:

- No más de 100 GB de tamaño total de archivo
- No más de 30 000 archivos
- Cada archivo debe tener menos de 15 GB.

### <a name="sync"></a>Sincronización

Para obtener un rendimiento óptimo, se recomienda almacenar menos de 300 000 archivos en una única biblioteca de sitio de grupo o de OneDrive. Aunque en SharePoint Online se pueden almacenar 30 millones de documentos por biblioteca, se recomienda no almacenar más de 300 000 archivos entre todas las bibliotecas de documentos para obtener un rendimiento óptimo. Además, pueden producirse los mismos problemas de rendimiento si tiene 300 000 elementos o más en todas las bibliotecas que está sincronizando, aunque no se estén sincronizando todos los elementos de las bibliotecas. Si usa el cliente de sincronización antiguo de OneDrive para la Empresa (Groove.exe), el límite de sincronización por biblioteca es de 20 000 elementos (incluidos 5000 elementos por sitio de equipo).

### <a name="versions"></a>Versiones

50 000 versiones principales y 511 versiones secundarias.

### <a name="sharepoint-groups"></a>Grupos de SharePoint

Un usuario puede pertenecer a 5000 grupos por sitio (colección de sitios) y cada grupo puede tener hasta 5000 usuarios. Se pueden tener hasta 10 000 grupos por sitio (colección de sitios).

> [!NOTE]
> Para los límites de grupo de Azure AD, consulte [Restricciones y límites de servicio de Azure AD](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions), dado que tales límites pueden afectar a la administración de pertenencia a sitios de grupo públicos y privados.

### <a name="managed-metadata"></a>Metadatos administrados

1 millón de términos totales, con un total de 2 millones de etiquetas de términos y 1 millón de propiedades de términos (estos límites son para términos globales y de nivel de sitio combinados). 1000 conjuntos de términos globales, 1000 grupos globales

### <a name="overall-site-metadata"></a>Metadatos generales del sitio

1000 GB por sitio (los metadatos rara vez alcanzan este tamaño).

### <a name="subsites"></a>Subsitios

2000 por sitio (colección de sitios). Se recomienda crear sitios y organizarlos en centros en lugar de crear subsitios. Si usa subsitios, se recomienda limitar su número (especialmente en sitios con mucho tráfico).

> [!NOTE]
> Su organización está limitada a 2000 sitios centrales. Puede que no necesite un sitio central para cada función y es importante realizar una planificación antes de crear centros. Para más información, visite [Planear los sitios centrales de SharePoint](/sharepoint/planning-hub-sites).

### <a name="sharepoint-hosted-applications"></a>Aplicaciones hospedadas por SharePoint

20 000 instancias por organización

### <a name="users"></a>Usuarios

2 millones por colección de sitios

> [!NOTE]
> No hay ningún límite específico para el número de invitados que puede invitar a sitios de SharePoint. Para obtener más información sobre el uso compartido externo, vea [Información general sobre el uso compartido externo](/sharepoint/external-sharing-overview).

## <a name="see-also"></a>Vea también

[Límites de búsqueda en SharePoint](/sharepoint/search-limits)