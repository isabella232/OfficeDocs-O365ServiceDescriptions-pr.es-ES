---
title: Creación de informes y seguimiento de mensajes
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: Microsoft Exchange Online Protection (EOP) ofrece muchos informes distintos que le permitirán averiguar el estado general y el mantenimiento de la organización. Algunos informes están disponibles en el centro de administración de Microsoft 365, mientras que otros están disponibles en el centro de administración de Exchange (EAC).
ms.openlocfilehash: d4e0f1104bfc87f5641cc241d2a526e8d56f0d1a
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/26/2019
ms.locfileid: "39262673"
---
# <a name="reporting-and-message-trace"></a>Creación de informes y seguimiento de mensajes

Microsoft Exchange Online Protection (EOP) ofrece muchos informes distintos que le permitirán averiguar el estado general y el mantenimiento de la organización. Algunos informes están disponibles en el centro de administración de Microsoft 365, mientras que otros están disponibles en el centro de administración de Exchange (EAC).

¿Busca información sobre todas las características de EOP? Vea la [Descripción del servicio de protección en línea de Exchange](exchange-online-protection-service-description.md).

## <a name="microsoft-365-admin-center-reports"></a>Informes del centro de administración de Microsoft 365

La página informes del centro de administración de Microsoft 365 proporciona información sobre el tráfico de mensajes, las detecciones de correo no deseado y malware, y los mensajes afectados por las reglas de flujo de correo (también conocidas como reglas de transporte) o las directivas de prevención de pérdida de datos (DLP). Los informes mejorados para protección, reglas y DLP ofrecen una experiencia interactiva de informes para los administradores de EOP. Estos informes proporcionan datos de resumen y la capacidad de rastrear desagrupando datos en detalles sobre mensajes individuales.

Para obtener información más detallada acerca de estos informes, vea [usar informes de protección de correo en Office 365 para ver datos sobre malware, correo no deseado y detecciones de reglas](https://docs.microsoft.com/exchange/monitoring/use-mail-protection-reports).

## <a name="reporting-using-web-services"></a>Reporting using web services

> [!NOTE]
> Muchas de las características de informes basados en REST y los cmdlets relacionados estuvieron obsoletos en enero de 2018. Para obtener información acerca de los informes de reemplazo disponibles de Microsoft Graph en Office 365, vea los temas secundarios de [trabajar con los informes de uso de office 365 en Microsoft Graph](https://go.microsoft.com/fwlink/p/?LinkID=865135).

No está disponible para clientes independientes de EOP. Puede usar el servicio Web de informes de inquilinos de REST/OData para recopilar mediante programación informes de Resumen y detallados sobre los datos de mensajería, y puede mostrar los datos en una página web en un portal de administración web personalizado.

## <a name="message-trace"></a>Seguimiento de mensajes

La característica de seguimiento de mensajes en el EAC le permite, como administrador, seguir los mensajes de correo electrónico a medida que pasan a través de EOP. Ayuda a determinar si el servicio ha recibido, rechazado, aplazado o entregado un mensaje de correo electrónico dirigido. También muestra qué le ha ocurrido al mensaje antes de alcanzar el estado final. Obtener información detallada sobre un mensaje específico le permite responder de forma eficaz a las preguntas del usuario, solucionar problemas del flujo de correo, validar los cambios en la Directiva y aliviar la necesidad de ponerse en contacto con el soporte técnico para obtener asistencia. Para obtener más información, consulte [ejecutar un seguimiento de mensajes y ver los resultados en el centro de administración de Exchange](https://docs.microsoft.com/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results).

## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes de Office 365, las opciones independientes y las soluciones locales, consulte [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).
