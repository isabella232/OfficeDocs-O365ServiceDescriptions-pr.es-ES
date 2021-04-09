---
title: Características de archivo en Archivado de Exchange Online
ms.author: office365servicedesc
author: pamelaar
manager: gailw
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
description: Obtenga información sobre las características de archivo disponibles en Microsoft Exchange Online archivado.
ms.openlocfilehash: cfc5832e3167f29465f387253694e56b66b932fd
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653102"
---
# <a name="archive-features-in-exchange-online-archiving"></a>Características de archivo en Archivado de Exchange Online

En las secciones siguientes se describen las características de archivo de Microsoft Exchange Online archivado.
  
## <a name="archive-mailbox"></a>Buzón de archivo

Archivado de Exchange Online ofrece a los usuarios capacidades avanzadas de archivado con la característica de buzón de archivo. Un buzón de archivo es un buzón especializado que aparece junto con las carpetas de buzones principales de los usuarios en Outlook o Outlook en la web. Los usuarios pueden acceder al archivo de la misma manera que tienen acceso a sus buzones principales. Además, pueden buscar en sus archivos y buzones principales.
  
Los administradores pueden habilitar la característica de archivo para usuarios específicos desde el Centro de administración de Exchange (EAC) o desde Windows PowerShell remoto. Para obtener más información, vea [Habilitar o deshabilitar un buzón de archivo en Exchange Online](/office365/securitycompliance/enable-archive-mailboxes).
  
> [!IMPORTANT]
>  No se permite copiar mensajes en Archivado de Exchange Online para su archivo con el registro en diario, o mediante reglas de transporte o reenvío automático. <br/>
>  El buzón de archivo de un usuario está diseñado exclusivamente para dicho usuario. Microsoft se reserva el derecho a denegar el archivado ilimitado en los casos en que el buzón de archivo de un usuario se utilice para almacenar datos de archivo para otros usuarios o en otros casos de uso inadecuado.
  
### <a name="move-messages-to-exchange-online-archiving"></a>Mover mensajes a Exchange Online Archiving

Los usuarios pueden arrastrar y colocar mensajes de archivos .pst en el archivo, para facilitar el acceso en línea. Los usuarios también pueden mover automáticamente elementos de correo electrónico desde el buzón principal al buzón de archivo, mediante Las policías de archivo, para reducir el tamaño y mejorar el rendimiento del buzón principal. 
  
### <a name="import-data-to-the-archive"></a>Importar datos al archivo

Para importar datos al archivo, los usuarios pueden:
  
- Importar datos desde un archivo .pst con el Asistente para importar y exportar de Outlook.
    
- Arrastrar mensajes de correo desde archivos .pst hasta el archivo.
    
- Arrastrar mensajes de correo desde el buzón principal hasta el archivo.
    
- Permitir que las directivas de archivo muevan de manera automática los mensajes de correo desde el buzón principal, en función de la antigüedad de los mensajes. Para obtener más información, vea [Etiquetas de retención y directivas de retención](/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).
    
> [!NOTE]
> Los administradores también pueden usar el servicio de importación de Office 365 para importar archivos .pst a los buzones de archivos basados en la nube de los usuarios. Para obtener más información, vea [Usar la carga en la red para importar archivos PST en Office 365](/office365/securitycompliance/use-network-upload-to-import-pst-files). 
  
## <a name="deleted-item-recovery"></a>Recuperación de elementos eliminados

Los usuarios pueden restaurar elementos que han eliminado con anterioridad desde cualquier carpeta de correo de su archivo. Cuando se elimina un elemento, permanece en la carpeta Elementos eliminados del archivo. El elemento permanece ahí hasta que el usuario lo elimina de forma manual o hasta que las directivas de retención lo quitan de forma automática.
  
Cuando el elemento se quita de la carpeta Elementos eliminados del archivo, se conserva en la carpeta Elementos recuperables del archivo durante 14 días, antes de eliminarse de forma permanente. Los usuarios pueden recuperar estos elementos mediante **la característica Recuperar elementos** eliminados en Microsoft Outlook o Outlook en la web. 
  
Si un usuario purga de manera manual un elemento de la carpeta Elementos recuperables, los administradores pueden recuperarlo a lo largo de los 14 días siguientes con la característica Recuperación de un único elemento. Esta característica permite a los administradores realizar una búsqueda en varios buzones para buscar los elementos que se han purgado y, después, transferirlos desde el buzón de correo de detección hasta los buzones de los usuarios con el cmdlet  `Search-Mailbox` de Windows PowerShell. Para obtener más información, vea [Habilitar o deshabilitar la recuperación de elementos individuales de un buzón de correo](/office365/securitycompliance/use-network-upload-to-import-pst-files).
  
> [!NOTE]
>  El período predeterminado de recuperación de un único elemento es de 14 días, pero se puede personalizar en situaciones determinadas. <br/>
>  Si un administrador ha colocado el buzón de un usuario en una retención In-Place o retención por juicio, los elementos purgados se conservan indefinidamente y la ventana de 14 días no se aplica. 
  
## <a name="deleted-mailbox-recovery"></a>Recuperación de buzones eliminados

Cuando los administradores eliminan usuarios de una implementación local de Exchange Server, también se eliminan los archivos correspondientes. Si es necesario recuperar los buzones de archivo eliminados, el equipo de soporte técnico de Microsoft puede realizar esta recuperación. Los archivos recuperados conservarán todo el correo que contenían almacenado en el momento de su eliminación.
  
> [!IMPORTANT]
> A partir del momento en que se elimina el buzón de un usuario, los administradores tienen 30 días para solicitar la recuperación del buzón de archivo. Transcurrido este período, los buzones de archivo ya no pueden recuperarse. 
  
## <a name="mailbox-service-redundancy"></a>Redundancia de servicios de buzón

Los buzones de archivo de Archivado de Exchange Online se replican en varias copias de bases de datos, en centros de datos de Microsoft dispersos geográficamente, para proporcionar la funcionalidad de restauración de datos en caso de error en la infraestructura de mensajería. Para los errores a gran escala, se inicia la administración de continuidad empresarial. 
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, opciones independientes y soluciones locales, [consulte Archivado de Exchange Online descripción del servicio](exchange-online-archiving-service-description.md).
