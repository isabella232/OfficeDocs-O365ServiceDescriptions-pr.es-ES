---
title: Alta disponibilidad y continuidad empresarial
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-high-availability-and-business-continuity
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7b03465e-3b9c-4500-8956-a83377f4c2c3
description: Microsoft Exchange Online ofrece un amplio soporte de retención y recuperación para la infraestructura de correo electrónico de una organización. Este servicio incluye replicación de buzón en centros de datos y la capacidad de recuperar buzones y elementos eliminados.
ms.openlocfilehash: 395977f77d4293d18c5cf53e02d43566ca9f7313
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131974"
---
# <a name="high-availability-and-business-continuity"></a>Alta disponibilidad y continuidad empresarial

Microsoft Exchange Online ofrece un amplio soporte de retención y recuperación para la infraestructura de correo electrónico de una organización. Este servicio incluye replicación de buzón en centros de datos y la capacidad de recuperar buzones y elementos eliminados.
  
## <a name="mailbox-replication-at-data-centers"></a>Replicación de buzón en centros de datos

Los buzones de Exchange Online son replicados continuamente en copias de bases de datos múltiples, en centros de datos de Microsoft geográficamente dispersos, para brindar una capacidad de recuperación de datos en caso de fallos en la infraestructura de mensajería local. Para fallos a gran escala, se inician los procedimientos de gestión de continuidad de servicio.
  
Para obtener más información sobre cómo protege Microsoft sus datos, vea [Centro de confianza de Office 365](https://go.microsoft.com/fwlink/p/?LinkId=299135). Si usa Office 365 ofrecido por 21Vianet, vea el [Centro de confianza de 21Vianet](https://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl).
  
## <a name="deleted-mailbox-recovery"></a>Recuperación de buzones eliminados

Los administradores pueden eliminar buzones de Exchange online mediante el centro de administración de Microsoft 365 para eliminar la cuenta de usuario correspondiente o quitar la licencia de Exchange Online, o mediante el cmdlet **Remove-Mailbox** en Windows PowerShell remoto. Cuando se elimina un buzón, Exchange Online conserva el buzón y su contenido durante 30 días de forma predeterminada. Transcurrido el plazo de 30 días, el buzón no es recuperable. Un buzón de correo recuperado contiene todos los datos almacenados en el momento en que se eliminó. Los administradores pueden recuperar un buzón de correo eliminado dentro del período de retención a través del centro de administración 365 de Microsoft. Para recuperar un buzón de correo eliminado, los administradores deben restaurar la cuenta de usuario correspondiente o volver a asignar una licencia de Exchange Online a la cuenta de usuario. Para obtener más información, vea [Eliminar o restaurar buzones de usuario en Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=286992).
  
## <a name="deleted-item-recovery"></a>Recuperación de elementos eliminados

Exchange Online permite a los usuarios restaurar elementos que han eliminado de cualquier carpeta de correo electrónico, incluida la carpeta elementos eliminados. Los elementos que se eliminan se conservan en la carpeta Elementos eliminados del usuario. Aquí permanecen hasta que el usuario los elimina manualmente o hasta que las directivas de retención los eliminan automáticamente. Los administradores pueden personalizar las directivas de retención en EAC o usando el Windows PowerShell remoto.
  
Después de eliminar un elemento de la carpeta Elementos eliminados, este permanecerá en la carpeta Elementos recuperables durante 14 días antes de ser eliminado de forma permanente, pero los administradores pueden aumentar este límite hasta un máximo de 30 días con el Windows PowerShell remoto. Los usuarios pueden recuperar el elemento durante este período de tiempo mediante la característica recuperar elementos eliminados en Outlook en la web o en Outlook. Obtenga información sobre cómo [cambiar el período de retención de elementos eliminados](https://go.microsoft.com/fwlink/p/?LinkId=286940).
  
Si un usuario eliminó de forma manual un elemento de la carpeta Elementos recuperables, un administrador puede recuperarlo en este período de tiempo con la característica de recuperación de elementos individuales con el Windows PowerShell remoto. De forma predeterminada, la recuperación de elementos individuales se habilita cuando se crea un buzón. Para obtener más información, vea [Habilitar o deshabilitar la recuperación de elementos individuales de un buzón de correo](https://go.microsoft.com/fwlink/p/?LinkID=286941).
  
Para conservar los mensajes más de 30 días en la carpeta Elementos recuperables, las organizaciones pueden implementar un período de conservación de correos electrónicos más prolongado o conservaciones locales de duración definida. Obtenga más información sobre la [colocación de un buzón en Conservación local](https://go.microsoft.com/fwlink/p/?LinkId=271746).
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, las opciones independientes y las soluciones locales, consulte [Exchange Online Service Description](exchange-online-service-description.md).
  