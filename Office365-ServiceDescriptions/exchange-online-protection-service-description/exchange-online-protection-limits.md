---
title: Límites de Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: f866fe3b-a183-4e6d-abd9-bbec0a0c7fae
description: Actualmente existen los siguientes límites para Exchange Online Protection. Estos límites no se pueden configurar a menos que se especifique lo contrario.
ms.openlocfilehash: f573f73bf69944ecb400347978140e45a4c8700f74ac214572228ae83fc3c7fb
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/06/2021
ms.locfileid: "54664503"
---
# <a name="exchange-online-protection-limits"></a>Límites de Exchange Online Protection

Actualmente existen los siguientes límites para Exchange Online Protection. Estos límites no se pueden configurar a menos que se especifique lo contrario. 
  
> [!TIP]
> Para obtener más información acerca de los límites Exchange Online, [vea Exchange Online limits](../exchange-online-service-description/exchange-online-limits.md). Los límites de la regla de transporte se aplican también a los clientes de EOP independiente. Los límites de tasa de destinatarios y tasa de mensajes de Exchange Online no se aplican a los clientes de EOP independiente. 
  
- **Límite de** dominio: puede agregar hasta 900 dominios por inquilino. Los subdominios pueden incluirse en este límite de 900, o bien, si es necesario, como parte de una opción global de subdominios coincidentes. Para obtener más información, vea [Administrar dominios aceptados en EOP](/microsoft-365/security/office-365-security/exchange-online-protection-overview).

- **Límite de dominio remoto:** puede agregar hasta 200 dominios remotos por inquilino.
    
- **Límite de tamaño de mensaje:** el tamaño máximo del mensaje para los clientes independientes de EOP, incluidos los datos adjuntos, es de 150 MB. 
    
- **Número de mensajes salientes** enviados: el límite para el número de mensajes salientes enviados a través de EOP es lo suficientemente alto como para garantizar que la comunicación de correo electrónico normal no se trate como correo no deseado. Si desea enviar mensajes de correo electrónico comerciales en grandes cantidades, en lugar de enviar mensajes salientes a través de EOP, le recomendamos que utilice un proveedor de servicios de correo electrónico de terceros o que los envíe a través de sus servidores de correo electrónico locales. 
    
- **Límite de** destinatarios: siempre que el host de envío pueda dividir el mensaje en "fragmentos" de menos de 500 destinatarios, no se define ningún límite explícito. Sin embargo, cada "fragmento" se trata realmente como un mensaje nuevo. Demasiados mensajes en un breve período, mensajes desde un host con mala reputación o mensajes con contenido dudoso podrían bloquearse o limitarse. 
    
- Límite de lista de direcciones **IP** permitidos o ip bloqueados: al configurar una lista de direcciones IP permitidos o una lista de direcciones IP bloqueados en el filtro de conexión, puede especificar un máximo de 1273 entradas, donde una entrada es una sola dirección IP o un intervalo CIDR de direcciones IP de /24 a /32. 
    
- **Límite de aplazamiento de** mensajes: los mensajes en aplazamiento permanecerán en nuestras colas durante 24 horas. Los reintentos de envío de mensajes se basan en el tipo de error que se recibe del sistema de correo del destinatario. Los mensajes se vuelven a intentar cada 15 minutos. 
    
- **Período de retención de cuarentena de correo no** deseado: de forma predeterminada, los mensajes de correo no deseado enviados a la cuarentena se conservan durante 30 días. Los administradores pueden reducir este valor por medio de las directivas de filtro de contenido. 
    
- **Notificaciones de cuarentena de correo no** deseado del usuario final: de forma predeterminada, si está habilitada, las notificaciones de cuarentena de correo no deseado del usuario final se envían cada 3 días. Se pueden configurar para que se envíen cada 1 a 15 días. 
    
- **Límites** de seguimiento de mensajes y informes: para obtener informes y límites de seguimiento de mensajes, vea la sección "Disponibilidad y latencia de datos de seguimiento de mensajes y informes" en Informes y seguimiento de [mensajes en Exchange Online Protection](/microsoft-365/security/office-365-security/reporting-and-message-trace-in-exchange-online-protection).
    
### <a name="limits-across-eop-options"></a>Límites entre las opciones de EOP

| Característica | EOP independiente | Características de EOP en Exchange  Online | Exchange Enterprise CAL con servicios |
|:-----|:-----|:-----|:-----|
|Límite de dominio  <br/> |900  <br/> |900  <br/> |900  <br/> |
|Límite de dominio remoto  <br/> |200  <br/> |200  <br/> |200  <br/> |
|Límite de tamaño de mensaje (incluidos datos adjuntos)  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Límite de destinatarios  <br/> |Consulte "Límite de destinatarios" en la sección anterior  <br/> |500 destinatarios al enviar desde un buzón de correo hospedado; consulte "Límite de destinatarios" en la sección anterior para ver otros escenarios  <br/> |Consulte "Límite de destinatarios" en la sección anterior  <br/> |
|Límite de remitentes seguros  <br/> |1024 entradas  <br/> |1024 entradas  <br/> ||
|Límite de remitente bloqueado por directiva  <br/> |1024 entradas  <br/> |1024 entradas  <br/> ||
|Límite de listas de direcciones IP permitidas o bloqueadas  <br/> |1.273 entradas  <br/> |1.273 entradas  <br/> |1.273 entradas  <br/> |
|Límite de aplazamiento de mensajes  <br/> |1 día, retried cada 15 minutos  <br/> |1 día, retried cada 15 minutos  <br/> |1 día, retried cada 15 minutos  <br/> |
|Período de retención en cuarentena de correo no deseado  <br/> |30 días de forma predeterminada, pero se puede bajar  <br/> |30 días de forma predeterminada, pero se puede bajar  <br/> |30 días de forma predeterminada, pero se puede bajar  <br/> |
|Notificaciones de cuarentena de correo no deseado de usuario final  <br/> |3 días de manera predeterminada, configurable de 1 a 15 días  <br/> |3 días de manera predeterminada, configurable de 1 a 15 días  <br/> |3 días de manera predeterminada, configurable de 1 a 15 días  <br/> |
