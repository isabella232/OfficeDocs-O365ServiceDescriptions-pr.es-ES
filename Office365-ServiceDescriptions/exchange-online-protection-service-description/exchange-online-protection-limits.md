---
title: Límites de Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: f866fe3b-a183-4e6d-abd9-bbec0a0c7fae
description: Los siguientes límites existen actualmente para Exchange Online Protection. Estos límites no se pueden configurar a menos que se especifique lo contrario.
ms.openlocfilehash: 3c5a8e0c5f9a19c9cae81b3bc1e39bb153af0137
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/14/2020
ms.locfileid: "45133014"
---
# <a name="exchange-online-protection-limits"></a>Límites de Exchange Online Protection

Los siguientes límites existen actualmente para Exchange Online Protection. Estos límites no se pueden configurar a menos que se especifique lo contrario. 
  
> [!TIP]
> Para obtener más información acerca de los límites de Exchange Online, vea [límites de Exchange Online](../exchange-online-service-description/exchange-online-limits.md). Los límites de la regla de transporte se aplican también a los clientes de EOP independiente. Los límites de tasa de destinatarios y tasa de mensajes de Exchange Online no se aplican a los clientes de EOP independiente. 
  
- **Domain limit** You can add up to 900 domains per tenant. Subdomains can be included in this 900 limit, or if necessary, as part of a catch-all option, match subdomains. For more information, see [Manage Accepted Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).
    
- **Límite de tamaño de mensajes** El tamaño máximo de un mensaje para clientes de EOP independiente, con archivos adjuntos, es de 150 MB. 
    
- **Number of outbound messages sent** The limit for the number of outbound messages sent through EOP is high enough to ensure that normal email communication is not treated as spam. If you want to send commercial bulk email messages, rather than sending outbound messages through EOP, we recommend that you either use a third-party email service provider (ESP) or send them through your on-premises email servers. 
    
- **Recipient limit** As long as the sending host can split the message into "chunks" of fewer than 500 recipients, no explicit limit is defined. However, each "chunk" is effectively treated as a new message. Too many messages in a short period, messages from a host with a poor reputation, or messages with questionable content could be throttled or blocked. 
    
- **Límite de listas de direcciones IP permitidas o bloqueadas** Cuando configure una lista de direcciones IP permitidas o una lista de direcciones IP bloqueadas en el filtro de conexión, puede especificar un máximo de 1.273 entradas, donde una entrada es una dirección IP única o una rango CIDR de direcciones IP de /24 a /32. 
    
- **Límite de aplazamiento de mensajes** Los mensajes en aplazamientos permanecerán en nuestras colas durante 24 horas. Los reintentos de envío de mensajes se basan en el tipo de error que se recibe del sistema de correo del destinatario. Los mensajes se vuelven a intentar cada 15 minutos. 
    
- **Período de retención de cuarentena de correo no deseado** De forma predeterminada, los mensajes de correo no deseado que se envían a la cuarentena se conservan durante 30 días. Los administradores pueden reducir este valor por medio de las directivas de filtro de contenido. 
    
- **End-user spam quarantine notifications** By default, if enabled, end-user spam quarantine notifications are sent every 3 days. They can be configured to be sent every 1 to 15 days. 
    
- **Límites de seguimiento de mensajes y informes** Para obtener los informes y los límites de seguimiento de mensajes, consulte la sección "informes, disponibilidad y latencia de los datos de seguimiento de mensajes" en [Reporting and Message Trace in Exchange Online Protection](https://go.microsoft.com/fwlink/?LinkId=394248).
    
### <a name="limits-across-eop-options"></a>Límites entre las opciones de EOP

|**Característica**|****EOP independiente****|****Características de EOP en Exchange Online****|****Exchange Enterprise CAL con servicios****|
|:-----|:-----|:-----|:-----|
|Límite de dominio  <br/> |900  <br/> |900  <br/> |900  <br/> |
|Límite de tamaño de mensaje (incluidos datos adjuntos)  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Límite de destinatarios  <br/> |Consulte "Límite de destinatarios" en la sección anterior  <br/> |500 destinatarios al enviar desde un buzón de correo hospedado; consulte "Límite de destinatarios" en la sección anterior para ver otros escenarios  <br/> |Consulte "Límite de destinatarios" en la sección anterior  <br/> |
|Límite de remitentes seguros  <br/> |1024 entradas  <br/> |1024 entradas  <br/> ||
|Límite de remitentes bloqueados por directiva  <br/> |1024 entradas  <br/> |1024 entradas  <br/> ||
|Límite de listas de direcciones IP permitidas o bloqueadas  <br/> |1.273 entradas  <br/> |1.273 entradas  <br/> |1.273 entradas  <br/> |
|Límite de aplazamiento de mensajes  <br/> |1 día, reintentando cada 15 minutos  <br/> |1 día, reintentando cada 15 minutos  <br/> |1 día, reintentando cada 15 minutos  <br/> |
|Período de retención en cuarentena de correo no deseado  <br/> |30 días de forma predeterminada, pero se puede reducir  <br/> |30 días de forma predeterminada, pero se puede reducir  <br/> |30 días de forma predeterminada, pero se puede reducir  <br/> |
|Notificaciones de cuarentena de correo no deseado de usuario final  <br/> |3 días de manera predeterminada, configurable de 1 a 15 días  <br/> |3 días de manera predeterminada, configurable de 1 a 15 días  <br/> |3 días de manera predeterminada, configurable de 1 a 15 días  <br/> |
   

