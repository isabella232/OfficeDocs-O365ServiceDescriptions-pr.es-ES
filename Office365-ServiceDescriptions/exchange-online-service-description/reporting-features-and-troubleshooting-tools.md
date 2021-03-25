---
title: Herramientas de resolución de problemas y características de informes
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online ofrece una variedad de características de informes tanto dentro como fuera del Centro de administración de Exchange (EAC).
ms.openlocfilehash: 45eab90643f2abcbed7a2a791845284aa599e044
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173365"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>Herramientas de resolución de problemas y características de informes

Microsoft Exchange Online ofrece una variedad de características de informes tanto dentro como fuera del Centro de administración de Exchange (EAC).
  
## <a name="reporting-features"></a>Características de creación de informes

Los clientes de Exchange Online pueden acceder a informes en el Centro de administración de Microsoft 365, descargando un libro de informes de Excel o usando servicios web.
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a>Informes en el Centro de administración de Microsoft 365

Hay informes en la página Informes del Centro de administración de Microsoft 365 que proporcionan información resumida sobre buzones y grupos. Por ejemplo, en un informe se enumeran los grupos creados y eliminados por día, semana, mes o año. También hay informes resumidos sobre buzones nuevos y eliminados, y sobre buzones activos e inactivos. 
  
Además, la página Informes del Centro de administración de Microsoft 365 contiene informes de datos de mensajería, que proporcionan información sobre el tráfico de mensajes, las detecciones de correo no deseado y malware, y los mensajes afectados por las directivas de prevención de pérdida de datos (DLP) o reglas de transporte de Exchange. Los informes mejorados para protección, reglas y DLP ofrecen una experiencia interactiva de informes para los administradores de Exchange Online. Estos informes proporcionan datos de resumen y la capacidad de rastrear desagrupando datos en detalles sobre mensajes individuales.
  
Para obtener más información acerca de los informes disponibles con cada suscripción, vea [Informes](../office-365-platform-service-description/reports.md). Para obtener información más detallada sobre la página Informes en el Centro de administración de Microsoft 365, vea Ver y descargar informes sobre el uso del servicio en [Office 365](/microsoft-365/admin/activity-reports/activity-reports) y Usar informes de protección de correo para ver datos sobre [malware, correo](/exchange/monitoring/use-mail-protection-reports)no deseado y detecciones de reglas.
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>Generación de informes mediante el libro de informes de Excel

También puede usar el libro de informes de Excel 2013 para ver informes resumidos con funciones de exploración en profundidad. Sin embargo, se recomienda usar los informes mejorados del Centro de administración de Microsoft 365 en su lugar. Está previsto que el libro de informes de Excel 2013 quede en desuso en el futuro. Para obtener información general y vínculos para descargar e instalar el libro, vea la siguiente [página de descarga](https://go.microsoft.com/fwlink/p/?LinkId=271776). Para obtener información sobre cómo usar el libro, vea [Informes de protección de correo con el libro de informes de Excel](/previous-versions/exchange-server/exchange-150/jj945734(v=exchg.150)). 
  
### <a name="reporting-using-web-services"></a>Reporting using web services

El acceso a informes detallados y de resumen sobre buzones de correo, grupos y datos de mensajería está disponible mediante el servicio web REST/OData Tenant Reporting, que es una interfaz de programación que le permite crear informes personalizados. Para obtener más información, vea [Office 365 Reporting web services](/previous-versions/office/developer/o365-enterprise-developers/jj984325(v=office.15)).
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>Características de presentación de informes y herramientas para solucionar problemas en el EAC

Las siguientes características de generación de informes y herramientas para la solución de problemas están disponibles en el Centro de admin. de Exchange.
  
### <a name="trace-an-email-message"></a>Seguimiento de un mensaje de correo electrónico

La característica de seguimiento de mensajes le permite, como administrador, seguir los mensajes de correo electrónico a medida que pasan por el servicio de Exchange Online. Ayuda a determinar si el servicio ha recibido, rechazado, aplazado o entregado un mensaje de correo electrónico dirigido. Le permite responder las preguntas de los usuarios y resolver problemas con el flujo de correo de forma eficaz, y elimina la necesidad de comunicarse con el soporte técnico para recibir asistencia.
  
> [!IMPORTANT]
> Para resolver problemas y tendencias generales, use las herramientas de informe a fin de obtener dichos datos. Para obtener información específica de un único punto donde se necesiten detalles en cuanto a algún mensaje, utilice la herramienta de seguimiento de mensaje. 
  
Para obtener más información sobre la característica de seguimiento de mensajes, vea [Seguir un mensaje de correo electrónico](/exchange/monitoring/trace-an-email-message/trace-an-email-message).
  
### <a name="auditing-reports"></a>Informes de auditoría

Puede usar el registro de auditoría para solucionar los problemas de configuración mediante el seguimiento de cambios específicos efectuados por los administradores y como ayuda para cumplir los requisitos normativos, de cumplimiento normativo y de litigio. Exchange Online proporciona dos tipos de registro de auditoría:
  
- El Registro de auditoría de administrador registra cualquier acción realizada por un administrador. Esto puede ayudar a solucionar problemas de configuración o a identificar la causa de problemas relacionados con la seguridad o el cumplimiento normativo. 
    
- En el registro de auditoría de buzones de correo se indica cada vez que otro usuario que no es el propietario obtiene acceso al buzón. Esto puede ayudar a determinar quién ha tenido acceso a un buzón y lo que ha hecho. 
    
Para obtener más información sobre los registros de auditoría, vea [Informes de auditoría](/exchange/security-and-compliance/exchange-auditing-reports/exchange-auditing-reports).
  
### <a name="unified-messaging-reports"></a>Informes de mensajería unificada

Puede usar estos informes para supervisar y solucionar problemas de Mensajería Unificada (MU) en la organización de Exchange Online. Para obtener más información, vea [Ejecutar informes para llamadas de correo de voz](/exchange/voice-mail-unified-messaging/run-voice-mail-call-reports/run-voice-mail-call-reports).
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, opciones independientes y soluciones locales, vea [Descripción del servicio de Exchange Online](exchange-online-service-description.md).
