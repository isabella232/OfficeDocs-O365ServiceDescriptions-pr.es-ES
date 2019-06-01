---
title: Límites de SharePoint Online
ms.author: sharik
author: skjerland
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Busque los límites de SharePoint Online para planes de Office 365 Enterprise e independientes.
ms.openlocfilehash: 8e678bf7fc2373b5e8f97341d2c167548b36322b
ms.sourcegitcommit: 178a0c81d51a48562b9433c47642ce78c51651a3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/01/2019
ms.locfileid: "34669689"
---
# <a name="sharepoint-online-limits"></a>Límites de SharePoint Online

Busque los límites de SharePoint para los planes de Office 365 y los planes independientes de SharePoint Online.
  
## <a name="limits-by-plan"></a>Límites por plan

|||||
|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Office 365 empresa Essentials o empresa Premium** <br/> |**Office 365 Enterprise E1, E3 o E5, o SharePoint Online plan 1 o 2** <br/> | **Office 365 Enterprise F1** <br/> |
|Almacenamiento<sup>1, 2</sup> <br/> |1 TB por organización más 10 GB por licencia adquirida  <br/> |1 TB por organización más 10 GB por licencia comprado<sup>3</sup> <br/> |1 TB por organización <sup>3</sup> <br/> |
|Almacenamiento para colecciones de sitios  <br/> |Hasta 25 TB por colección de sitios o grupo<sup>4</sup> <br/> |Hasta 25 TB por colección de sitios o grupo<sup>4</sup> <br/> |Hasta 25 TB por colección de sitios o grupo<sup>5</sup> <br/> |
|Colecciones de sitios por organización  <br/> |500.000<sup>6</sup> <br/> |500.000<sup>6</sup> <br/> |500 000<br/> |
|Número de usuarios  <br/> |Hasta 300  <br/> |1- 500 000<sup>7</sup> <br/> |1- 500 000<sup>7</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> Puede adquirir una cantidad ilimitada de almacenamiento de SharePoint Online. Vea [Cambiar el espacio de almacenamiento para la suscripción](https://support.office.com/article/96EA3533-DE64-4B01-839A-C560875A662C). 
<br/><sup>2</sup> Se recomienda supervisar la Papelera de reciclaje y vaciarla periódicamente. El espacio de almacenamiento que se utiliza es parte del límite de almacenamiento de archivos total de la organización. 
<br/> <sup>3</sup> Si tiene una suscripción a Office 365 y un plan independiente SharePoint Online, las cantidades de almacenamiento se suman. 
<br/><sup>4</sup> los administradores de SharePoint Online pueden establecer límites de almacenamiento para sitios y colecciones de sitios.
<br/> <sup>5</sup> Los trabajadores de quiosco no pueden administrar colecciones de sitios de SharePoint Online. Necesita al menos una licencia de usuario de empresa para administrar colecciones de sitios de quiosco. 
<br/> <sup>6</sup> No se incluyen las colecciones de sitios de OneDrive para la Empresa creadas para cada licencia de usuario. 
<br/><sup>7</sup>Si tiene más de 500.000 usuarios, póngase en contacto con un representante de Microsoft. 
  

  
## <a name="service-limits-for-all-plans"></a>Límites de servicio para todos los planes

- **Elementos en listas y bibliotecas** : una lista puede tener hasta 30 millones elementos y una biblioteca puede tener hasta 30 millones archivos y carpetas. Una vez agregados 100.000 elementos a una lista, biblioteca o carpeta, no se puede cambiar la herencia de permisos para la lista, biblioteca o carpeta. Para obtener más información sobre otras restricciones para ver listas de gran tamaño, vea [administrar listas y bibliotecas de gran tamaño en Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784). Para obtener información sobre los caracteres que no se pueden usar en los nombres de archivo, vea [caracteres no válidos en los nombres de archivos y carpetas](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Tamaño de archivo y longitud de ruta de acceso de archivo** : 15 GB. Para obtener más información sobre las restricciones y los límites al usar el nuevo cliente de sincronización de OneDrive (OneDrive. exe), vea [nombres de archivo y tipos de archivo no válidos en onedrive, onedrive para la empresa y SharePoint](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Mover y copiar entre colecciones de sitios** : 100 GB por operación. El explorador Web debe permanecer abierto.

- **Sincronización** : para obtener un rendimiento óptimo, se recomienda no almacenar más de 300.000 archivos en una sola biblioteca de sitio de grupo o OneDrive. Aunque SharePoint Online puede almacenar 30 millones documentos por biblioteca, para obtener un rendimiento óptimo, se recomienda sincronizar un máximo de 300.000 archivos en todas las bibliotecas de documentos. Además, pueden producirse los mismos problemas de rendimiento si tiene 300.000 elementos o más en todas las bibliotecas que va a sincronizar, incluso si no está sincronizando todos los elementos de esas bibliotecas. Si usa el anterior cliente de sincronización de OneDrive para la empresa (Groove. exe), el límite de sincronización por biblioteca es de 20.000 elementos (incluidos 5.000 elementos por sitio de grupo).

- Versiones principales y 50.000 de 511 versiones secundarias.

- **Grupos de SharePoint** : un usuario puede pertenecer a 5.000 grupos y cada grupo puede tener hasta 5.000 usuarios. Puede tener hasta 10.000 grupos por colección de sitios.

- **Metadata Managed Metadata** -200.000 términos en el almacén de términos, 1.000 conjuntos de términos globales, 1.000 grupos.

- **** Subsitios: hasta 2.000 por colección de sitios.

- **Aplicaciones hospedadas en SharePoint** : 20.000 instancias por organización.

- **Ámbitos de seguridad únicos por lista o biblioteca** -5.000. Para listas de gran tamaño, diseñe para que tenga el menor número de permisos únicos posible.

- **Users** -2 millones por colección de sitios.

> [!NOTE]
> No hay ningún límite en el número de usuarios externos que puede invitar a las colecciones de sitios de SharePoint Online. Para más información, vea [Administrar el uso compartido externo en su entorno de SharePoint Online](/sharepoint/external-sharing-overview)

## <a name="see-also"></a>Vea también

[Límites de búsqueda para SharePoint Online](/sharepoint/search-limits)
