---
title: Herramientas de resolución de problemas y características de informes
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online ofrece una variedad de características y cerrar el centro de administración de Exchange (EAC) de informes.
ms.openlocfilehash: b95ab58d2ec09f5e6bae32a3902e92deb75d789f
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036970"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>Herramientas de resolución de problemas y características de informes

Microsoft Exchange Online ofrece una variedad de características y cerrar el centro de administración de Exchange (EAC) de informes.
  
## <a name="reporting-features"></a>Características de presentación de informes

Los clientes de Exchange Online pueden acceder a los informes en el Centro de administración de Office 365; para ello, deben descargar un libro de informes de Excel o utilizar los servicios web.
  
### <a name="reporting-in-the-office-365-admin-center"></a>Generación de informes en el Centro de administración de Office 365

En la página Informes del Centro de administración de Microsoft Office 365, hay informes que brindan información resumida sobre buzones de correo y grupos. Por ejemplo, en un informe se enumeran los grupos creados y eliminados por día, semana, mes o año. También hay informes resumidos sobre buzones nuevos y eliminados, y sobre buzones activos e inactivos. 
  
Además, la página Informes del Centro de administración de Microsoft Office 365 incluye informes sobre datos de mensajería, los cuales brindan información sobre el tráfico de mensajes, detecciones de correo no deseado y malware, y mensajes afectados por las directivas de las reglas de transporte de Exchange o de prevención de pérdida de datos (DLP). Los informes mejorados para protección, reglas y DLP ofrecen una experiencia interactiva de informes para los administradores de Exchange Online. Estos informes proporcionan datos de resumen y la capacidad de rastrear desagrupando datos en detalles sobre mensajes individuales.
  
Para obtener más información sobre los tipos de informes que están disponibles con cada suscripción de Office 365, vea [Informes](../office-365-platform-service-description/reports.md). Para obtener más información sobre la página Informes del Centro de administración de Office 365, vea el tema [Ver y descargar informes sobre el uso de los servicios en Office 365](https://go.microsoft.com/fwlink/p/?LinkId=401187) y el artículo [Uso de informes de protección de correo en Office 365 para ver datos sobre malware, correo no deseado y detecciones de reglas](https://go.microsoft.com/fwlink/p/?LinkID=401102).
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>Generación de informes mediante el libro de informes de Excel

También puede usar el libro de informes de Excel 2013 para ver informes resumidos con funciones de exploración en profundidad. Pero, en su lugar, le recomendamos que use los informes mejorados del Centro de administración de Office 365. Está previsto que el libro de informes de Excel 2013 quede en desuso en el futuro. Para obtener información general y vínculos para descargar e instalar el libro, vea la siguiente [página de descarga](https://go.microsoft.com/fwlink/p/?LinkId=271776). Para obtener información sobre cómo usar el libro, vea [Informes de protección de correo con el libro de informes de Excel](https://go.microsoft.com/fwlink/p/?LinkId=285211). 
  
### <a name="reporting-using-web-services"></a>Informes mediante servicios web

El acceso a informes resumidos y detallados sobre buzones, grupos y datos de mensajes está disponible con el servicio web Informes de espacio empresarial de REST/OData, que es una interfaz de programación que permite crear informes personalizados. Para obtener más información, vea [Servicios web de informes de Office 365](https://go.microsoft.com/fwlink/p/?LinkId=287041).
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>Características de presentación de informes y herramientas para solucionar problemas en el EAC

Las siguientes características de generación de informes y herramientas para la solución de problemas están disponibles en el Centro de admin. de Exchange.
  
### <a name="trace-an-email-message"></a>Seguimiento de un mensaje de correo electrónico

La característica de seguimiento de mensaje le permite seguir los mensajes de correo electrónico a medida que pasan por el servicio Exchange Online. Ayuda a determinar si el servicio ha recibido, rechazado, aplazado o entregado un mensaje de correo electrónico dirigido. Le permite responder las preguntas de los usuarios y resolver problemas con el flujo de correo de forma eficaz, y elimina la necesidad de comunicarse con el soporte técnico para recibir asistencia.
  
> [!IMPORTANT]
> Para resolver problemas y tendencias generales, use las herramientas de informe a fin de obtener dichos datos. Para obtener información específica de un único punto donde se necesiten detalles en cuanto a algún mensaje, utilice la herramienta de seguimiento de mensaje. 
  
Para obtener más información sobre la característica de seguimiento de mensajes, vea [Seguir un mensaje de correo electrónico](https://go.microsoft.com/fwlink/p/?LinkId=271777).
  
### <a name="auditing-reports"></a>Informes de auditoría

Puede usar el registro de auditoría para solucionar los problemas de configuración mediante el seguimiento de cambios específicos efectuados por los administradores y como ayuda para cumplir los requisitos normativos, de cumplimiento normativo y de litigio. Exchange Online proporciona dos tipos de registro de auditoría:
  
- El Registro de auditoría de administrador registra cualquier acción realizada por un administrador. Esto puede ayudar a solucionar problemas de configuración o a identificar la causa de problemas relacionados con la seguridad o el cumplimiento normativo. 
    
- En el registro de auditoría de buzones de correo se indica cada vez que otro usuario que no es el propietario obtiene acceso al buzón. Esto puede ayudar a determinar quién ha tenido acceso a un buzón y lo que ha hecho. 
    
Para obtener más información sobre los registros de auditoría, vea [Informes de auditoría](https://go.microsoft.com/fwlink/p/?LinkId=271779).
  
### <a name="unified-messaging-reports"></a>Informes de mensajería unificada

Puede usar estos informes para supervisar y solucionar problemas de Mensajería Unificada (MU) en la organización de Exchange Online. Para obtener más información, vea [Ejecutar informes para llamadas de correo de voz](https://go.microsoft.com/fwlink/p/?LinkId=287042).
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes de Office 365, las opciones independientes y las soluciones locales, consulte [Descripción del servicio Exchange Online](exchange-online-service-description.md).
  

