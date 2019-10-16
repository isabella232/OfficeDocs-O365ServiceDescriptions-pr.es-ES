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
ms.openlocfilehash: f111729e829c0886c38141915fa7225f7633a578
ms.sourcegitcommit: 4d1cc432b4ce292abeb926f88108937695ce619b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/15/2019
ms.locfileid: "37523218"
---
# <a name="sharepoint-online-limits"></a>Límites de SharePoint Online 

Busque los límites de SharePoint para los planes de Office 365 y los planes independientes de SharePoint Online.
  
## <a name="limits-by-plan"></a>Límites por plan 

|||||
|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Office 365 empresa Essentials o empresa Premium** <br/> |**Office 365 Enterprise E1, E3 o E5, o SharePoint Online plan 1 o 2** <br/> | **Office 365 Enterprise F1** <br/> |
|Almacenamiento total por organización<sup>1, 2</sup> <br/> |1 TB más 10 GB por licencia adquirida  <br/> |1 TB más 10 GB por licencia comprado<sup>3</sup> <br/> |1 TB<sup>3</sup> <br/> |
|Almacenamiento máximo por colección de sitios<sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|Colecciones de sitios por organización  <br/> |1 millón<sup>6</sup> <br/> |1 millón<sup>6</sup> <br/> |1 millón<br/> |
|Número de usuarios  <br/> |Hasta 300  <br/> |1- 500 000<sup>7</sup> <br/> |1- 500 000<sup>7</sup> <br/> |
   
<sup>1</sup> [obtenga información sobre cómo encontrar el almacenamiento total y disponible para su organización](/sharepoint/manage-site-collection-storage-limits). Puede adquirir una cantidad ilimitada de almacenamiento adicional de SharePoint. Vea [Cambiar el espacio de almacenamiento para la suscripción](/office365/admin/subscriptions-and-billing/add-storage-space). 
<br/><sup>2</sup> Se recomienda supervisar la Papelera de reciclaje y vaciarla periódicamente. El espacio de almacenamiento que usa forma parte del límite de almacenamiento total de la organización. 
<br/> <sup>3</sup> si tiene una suscripción de Office 365 y un complemento de almacenamiento de archivos adicionales de Office 365, se agregan las cantidades de almacenamiento. 
<br/> <sup>4</sup> este es el límite de almacenamiento de una sola colección de sitios, no la cantidad de almacenamiento que se proporciona para cada colección de sitios. Este límite se aplica a todos los tipos de colecciones de sitios, incluidos los sitios de grupo conectados a Office 365 y OneDrive. Los administradores de SharePoint pueden [establecer manualmente límites de almacenamiento inferiores](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits). 
<br/> <sup>5</sup> los trabajadores de Firstline no pueden administrar colecciones de sitios de SharePoint. 
<br/> <sup>6</sup> no se incluye el OneDrive creado para cada usuario con licencia. 
<br/> <sup>7</sup>Si tiene más de 500.000 usuarios, póngase en contacto con un representante de Microsoft. 
  
## <a name="service-limits-for-all-plans"></a>Límites de servicio para todos los planes

- **Elementos en listas y bibliotecas** : una lista puede tener hasta 30 millones elementos y una biblioteca puede tener hasta 30 millones archivos y carpetas. Una vez agregados 100.000 elementos a una lista, biblioteca o carpeta, no se puede cambiar la herencia de permisos para la lista, biblioteca o carpeta. Para obtener más información sobre otras restricciones para ver listas de gran tamaño, vea [administrar listas y bibliotecas de gran tamaño en Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784). 

- **Tamaño de archivo y longitud de ruta de acceso de archivo** : 15 GB. El tamaño máximo de los archivos adjuntos a los elementos de lista es de 250 MB. Para obtener más información sobre las restricciones y los límites al usar el nuevo cliente de sincronización de OneDrive (OneDrive. exe), vea [nombres de archivo y tipos de archivo no válidos](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Mover y copiar entre colecciones de sitios** : 100 GB por operación. El explorador Web debe permanecer abierto.

- **Sincronización** : para obtener un rendimiento óptimo, le recomendamos que no almacene más de 300.000 archivos en todas las bibliotecas de documentos sincronizadas, incluso si está usando los archivos a la petición o si elige solo algunas carpetas de las bibliotecas para sincronizar.

    Si usa el cliente de sincronización de OneDrive para la empresa anterior (Groove. exe), puede sincronizar hasta 20.000 elementos en total en todas las bibliotecas sincronizadas. Esto incluye bibliotecas de OneDrive para la empresa, bibliotecas de sitios de grupo o ambas. Aparte del límite general de sincronización, hay límites en el número de elementos que se pueden sincronizar para cada tipo de biblioteca:
    - Puede sincronizar hasta 20.000 elementos en una biblioteca de OneDrive para la empresa. Esto incluye carpetas y archivos. 
    - Puede sincronizar hasta 5.000 elementos en una biblioteca de SharePoint. Esto incluye carpetas y archivos. Estas son las bibliotecas que se encuentran en varios sitios de SharePoint, como sitios de grupo y sitios de la comunidad, bibliotecas que otras personas crearon o que ha creado desde la página sitios. Puede sincronizar varias bibliotecas de SharePoint. Los sitios de grupo que sincronice también contarán con el límite global de elementos 20.000 en todas las bibliotecas sincronizadas.

    > [!NOTE]
    > Si los usuarios necesitan sincronizar archivos de bibliotecas de documentos con cientos de miles de archivos, puede "ocultar" las carpetas del cliente de sincronización estableciendo el nivel de permisos de las carpetas como "lectura restringida". 

- **Versiones principales y 50.000 de 511** versiones secundarias.

- **Grupos de SharePoint** : un usuario puede pertenecer a 5.000 grupos y cada grupo puede tener hasta 5.000 usuarios. Puede tener hasta 10.000 grupos por colección de sitios.
    > [!NOTE]
    > Para los límites de grupo de Azure AD, consulte [límites de servicio y restricciones de Azure ad](https://docs.microsoft.com/azure/active-directory/users-groups-roles/directory-service-limits-restrictions) dado que estos límites pueden afectar a la administración de pertenencia de los sitios de grupo públicos y privados. 
- **Metadata Managed Metadata** -200.000 términos en el almacén de términos, 1.000 conjuntos de términos globales, 1.000 grupos.

- **Subsites** -2.000 por colección de sitios.

- **Aplicaciones hospedadas en SharePoint** : 20.000 instancias por organización.

- **Ámbitos de seguridad únicos por lista o biblioteca** -5.000. Para listas de gran tamaño, diseñe para que tenga el menor número de permisos únicos posible.

- **Users** -2 millones por colección de sitios.
    > [!NOTE]
    > No hay ningún límite en el número de invitados que puede invitar a las colecciones de sitios de SharePoint. Para obtener más información sobre el uso compartido externo, vea [external Sharing Overview](https://docs.microsoft.com/sharepoint/external-sharing-overview).
## <a name="see-also"></a>Vea también

[Límites de búsqueda para SharePoint Online](https://docs.microsoft.com/sharepoint/search-limits)
