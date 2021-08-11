---
title: Informes y seguimiento de mensajes en Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: Lea este artículo para obtener información sobre informes y seguimiento de mensajes en Microsoft Exchange Online Protection (EOP).
ms.openlocfilehash: 8b593faea343d742c2f57ce430457e1803ba75b5a135d46f338eaed0e76d2ca6
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/06/2021
ms.locfileid: "54664093"
---
# <a name="reporting-and-message-trace-in-exchange-online-protection"></a>Informes y seguimiento de mensajes en Exchange Online Protection

Microsoft Exchange Online Protection (EOP) ofrece muchos informes distintos que le permitirán averiguar el estado general y el mantenimiento de la organización. Algunos informes están disponibles en el Centro de administración de Microsoft 365, mientras que otros están disponibles en el Centro Exchange administración (EAC).

¿Busca información sobre todas las características de EOP? Vea la [Exchange Online Protection descripción del servicio .](exchange-online-protection-service-description.md)

## <a name="microsoft-365-admin-center-reports"></a>Informes del Centro de administración de Microsoft 365

La página Informes de la Centro de administración de Microsoft 365 proporciona información sobre el tráfico de mensajes, las detecciones de correo no deseado y malware y los mensajes afectados por las reglas de flujo de correo (también conocidas como reglas de transporte) o las directivas de prevención de pérdida de datos (DLP). Los informes mejorados para protección, reglas y DLP ofrecen una experiencia interactiva de informes para los administradores de EOP. Estos informes proporcionan datos de resumen y la capacidad de rastrear desagrupando datos en detalles sobre mensajes individuales.

Para obtener información más detallada acerca de estos informes, vea Usar informes de protección de correo para ver datos sobre malware, correo no deseado [y detecciones de reglas.](/exchange/monitoring/use-mail-protection-reports)

## <a name="reporting-using-web-services"></a>Reporting using web services

> [!NOTE]
> Muchas de las características de informes basadas en REST y los cmdlets relacionados quedaron en desuso en enero de 2018. Para obtener información sobre los informes de reemplazo de Microsoft Graph disponibles en Office 365, vea los subtópópico de Trabajar con informes de [uso en Microsoft Graph](/graph/api/resources/report).

No está disponible para clientes independientes de EOP. Puede usar el servicio web de informes de inquilinos REST/OData para recopilar mediante programación informes de resumen y detallados sobre los datos de mensajería y puede mostrar los datos en una página web en un portal de administración web personalizado.

## <a name="message-trace"></a>Seguimiento de mensajes

La característica de seguimiento de mensajes del EAC le permite, como administrador, seguir los mensajes de correo electrónico a medida que pasan por EOP. Ayuda a determinar si el servicio ha recibido, rechazado, aplazado o entregado un mensaje de correo electrónico dirigido. También muestra qué le ha ocurrido al mensaje antes de alcanzar el estado final. La obtención de información detallada sobre un mensaje específico le permite responder eficazmente a las preguntas del usuario, solucionar problemas de flujo de correo, validar cambios de directiva y aliviar la necesidad de ponerse en contacto con el soporte técnico para obtener asistencia. Para obtener más información, vea Ejecutar un seguimiento de mensajes y ver los resultados en el [centro Exchange administración.](/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results)

## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, opciones independientes y soluciones locales, [vea Exchange Online Protection descripción del servicio](exchange-online-protection-service-description.md).