---
title: Características de archivo de archivado de Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- archive-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 38abfbd2-5aaa-444a-a431-5e71c566f3e4
description: En las siguientes secciones se describen las características de archivo de archivado de Microsoft Exchange Online.
ms.openlocfilehash: 7f6b5863d94862644fb90d1d0d85c3765ad05e9b
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131534"
---
# <a name="archive-features-in-exchange-online-archiving"></a>Características de archivo de archivado de Exchange Online

En las siguientes secciones se describen las características de archivo de archivado de Microsoft Exchange Online.
  
## <a name="archive-mailbox"></a>Buzón de archivo

Archivado de Exchange Online ofrece capacidades avanzadas de archivado para los usuarios con la característica de buzón de archivo. Un buzón de archivo es un buzón especializado que aparece junto a las carpetas de buzones principales de los usuarios en Outlook o en Outlook en la Web. Los usuarios pueden tener acceso al archivo de la misma forma que tienen acceso a sus buzones principales. Además, pueden buscar en sus archivos y en los buzones de correo principales.
  
Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes).
  
> [!IMPORTANT]
>  No se permite copiar mensajes en Archivado de Exchange Online para su archivo con el registro en diario, o mediante reglas de transporte o reenvío automático. <br/>
>  El buzón de archivo de un usuario está diseñado exclusivamente para dicho usuario. Microsoft se reserva el derecho a denegar el archivado ilimitado en los casos en que el buzón de archivo de un usuario se usa para almacenar datos de archivo para otros usuarios o en otros casos de uso inadecuado.
  
### <a name="move-messages-to-exchange-online-archiving"></a>Mover mensajes a Exchange Online Archiving

Los usuarios pueden arrastrar y soltar mensajes de archivos. pst en el archivo para facilitar el acceso en línea. Los usuarios también pueden mover elementos de correo electrónico desde el buzón principal al buzón de archivo automáticamente, mediante directivas de archivo, para reducir el tamaño y mejorar el rendimiento del buzón principal. 
  
### <a name="import-data-to-the-archive"></a>Importar datos al archivo

Para importar datos al archivo, los usuarios pueden:
  
- Importar datos desde un archivo .pst con el Asistente para importar y exportar de Outlook.
    
- Arrastrar mensajes de correo desde archivos .pst hasta el archivo.
    
- Arrastrar mensajes de correo desde el buzón principal hasta el archivo.
    
- Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).
    
> [!NOTE]
> Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files). 
  
## <a name="deleted-item-recovery"></a>Recuperación de elementos eliminados

Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.
  
Cuando el elemento se quita de la carpeta Elementos eliminados del archivo, se conserva en la carpeta Elementos recuperables del archivo durante 14 días, antes de eliminarse de forma permanente. Los usuarios pueden recuperar estos elementos mediante la característica **recuperar elementos eliminados** de Microsoft Outlook o Outlook en la Web. 
  
If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).
  
> [!NOTE]
>  El período predeterminado de recuperación de un único elemento es de 14 días, pero se puede personalizar en situaciones determinadas. <br/>
>  Si un administrador ha colocado el buzón de un usuario en conservación local o retención por juicio, los elementos purgados se conservan de manera indefinida y no se aplica el período de 14 días. 
  
## <a name="deleted-mailbox-recovery"></a>Recuperación de buzones eliminados

Cuando los administradores eliminan usuarios de una implementación local de Exchange Server, también se eliminan los archivos correspondientes. Si los buzones de archivo eliminados deben recuperarse, el equipo de soporte técnico de Microsoft puede llevar a cabo esta recuperación. Los archivos recuperados conservarán todo el correo que contenían almacenado en el momento de su eliminación.
  
> [!IMPORTANT]
> Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable. 
  
## <a name="mailbox-service-redundancy"></a>Redundancia de servicios de buzón

Los buzones de archivo de Exchange Online archiving se replican en varias copias de bases de datos, en centros de datos de Microsoft dispersos geográficamente, para proporcionar la capacidad de restauración de datos en caso de que se produzca un error en la infraestructura de mensajería. Para los errores a gran escala, se inicia la administración de la continuidad empresarial. 
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, las opciones independientes y las soluciones locales, consulte [Descripción del servicio de archivado de Exchange Online](exchange-online-archiving-service-description.md).
  
