---
title: Descripción de servicio Protección en línea de Exchange
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: obtenga información sobre las características y los requisitos de Exchange Online Protection. Se incluye una lista de los planes que ofrecen Exchange Online Protection, así como una comparación de las características entre dichos planes.
ms.openlocfilehash: 6e7ffd6a2248acfc763a71e35ce0daba0f9b0308
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/19/2018
ms.locfileid: "24037022"
---
# <a name="exchange-online-protection-service-description"></a>Descripción de servicio Protección en línea de Exchange

obtenga información sobre las características y los requisitos de Exchange Online Protection. Se incluye una lista de los planes que ofrecen Exchange Online Protection, así como una comparación de las características entre dichos planes.
  
Microsoft Protección de Exchange Online (EOP) es un servicio de filtro de correo electrónico basado en nube que ayuda a proteger su organización contra correo no deseado y malware, e incluye características para proteger a su organización contra incumplimiento de directivas de mensajería. EOP simplifica la administración de un entorno de mensajes y puede aliviar muchas de las cargas asociadas al mantenimiento del hardware y del software local.
  
Estas son las principales formas en las que se puede usar EOP para la protección de mensajes:
  
- **En un escenario independiente** EOP ofrece protección de correo electrónico basada en la nube para su entorno de Exchange Server 2013 local, versiones heredadas de Exchange Server, o cualquier otro local solución de correo electrónico SMTP. 
    
- **Como parte de Microsoft Exchange Online** De manera predeterminada, EOP protege los buzones de Exchange Online hospedados en la nube. Para obtener más información sobre Exchange Online, vea [Descripción del servicio Exchange Online](../exchange-online-service-description/exchange-online-service-description.md).
    
- **En una implementación híbrida**: EOP se puede configurar para que proteja el entorno de mensajería y controle el enrutamiento del correo cuando se tiene una mezcla de buzones locales y en la nube. 
    
Para comparar las características de los diferentes planes, consulte [Comparar los planes de Office 365 para empresas](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409).
  
Para comprar Protección de Exchange Online, vea [Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=294201).
  
Puede exportar, guardar e imprimir páginas en las descripciones de los servicios de Office 365. Obtenga más información sobre cómo [exportar varias páginas](https://go.microsoft.com/fwlink/?LinkId=403349).
  
> [!IMPORTANT]
> EOP sustituye a Forefront Online Protection para Exchange (FOPE). Todos los clientes de FOPE se van a migrar a EOP. Además de protección y el control que proporciona FOPE, EOP también incluye características adicionales. Si desea más información sobre la transición de FOPE a EOP, visite el [Centro de transición [Migración] de Forefront Online Protection para Exchange (FOPE)](http://www.movetoeop.com). 
  
## <a name="whats-new-in-exchange-online-protection-eop"></a>Novedades de la Exchange Online Protection (EOP)

Para obtener información sobre las nuevas características de EOP, vea [Novedades de Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=320390). Para ver una comparación de características entre FOPE y EOP, vea [Comparación de las características de FOPE y EOP](https://go.microsoft.com/fwlink/p/?LinkId=320391).
  
## <a name="exchange-online-protection-eop-plans"></a>Planes de Online Protection (EOP)

EOP está disponible a través de los siguientes planes de suscripción:
  
|**Plan**|**Descripción**|
|:-----|:-----|
|[EOP independiente](https://go.microsoft.com/fwlink/p/?LinkId=294201) <br/> |Cuando EOP protege los buzones locales.  <br/> |
|[Características de EOP en Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=294197) <br/> |Cuando EOP protege sus buzones de Exchange Online hospedados en la nube.  <br/> |
|[Exchange Enterprise CAL con Servicios](https://go.microsoft.com/fwlink/p/?LinkId=293699) <br/> |Cuando EOP protege los buzones locales, como EOP independiente, e incluye la prevención de pérdida de datos (DLP) y creación de informes mediante el uso de servicios web.  <br/> |
   
### <a name="exchange-enterprise-cal-with-services-features"></a>Características de Exchange Enterprise CAL con servicios

Microsoft Exchange Enterprise CAL con servicios ofrece las características de protección de correo de EOP para el entorno de mensajería local, junto con las siguientes características:
  
- [Prevención de pérdida de datos (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)
    
- [Creación de informes mediante servicios web](reporting-and-message-trace.md#reporting-using-web-services)
    
Para obtener más información sobre las licencias de Exchange Enterprise CAL con servicios, vea [Licencias de Exchange Server 2013](https://go.microsoft.com/fwlink/p/?LinkId=293699).
  
Si tiene licencias de Exchange Enterprise CAL con Servicios y quiere aprovisionar el servicio, siga las instrucciones que encontrará en [Configurar un servicio EOP](https://go.microsoft.com/fwlink/p/?LinkId=320397). Los pasos de configuración son los mismos que para configurar EOP independiente.
  
> [!NOTE]
> Las nuevas características de Exchange Enterprise CAL con servicios se implementan al mismo tiempo que Exchange Online, en lugar de EOP independiente. Le avisamos que las programaciones de implementación para EOP independiente y Exchange Online/Exchange Enterprise CAL con servicios pueden ser ligeramente diferentes. 
  
## <a name="requirements-for-exchange-online-protection-eop"></a>Requisitos de Online Protection (EOP)

Se puede usar EOP con cualquier agente de transferencia de correo SMTP, como Microsoft Exchange Server 2013. Para obtener información sobre los sistemas operativos, los exploradores web y los idiomas admitidos en EOP, vea las secciones "Exploradores compatibles" e "Idiomas admitidos" en [Centro de administración de Exchange en Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).
  
## <a name="limits"></a>Límites

Para límites en EOP, vea [Límites de Exchange Online Protection](exchange-online-protection-limits.md).
  
## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>Disponibilidad de características en los planes de Exchange Online Protection (EOP)

A continuación, se incluye cada característica. Si desea ver información más detallada sobre las características de EOP, haga clic en los vínculos de la tabla. Cuando se menciona Exchange Online, por lo general se refiere a la familia de servicios de Office 365 Enterprise.
  
|||||
|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**EOP independiente** <br/> |**Características de EOP en Exchange Online** <br/> |**Exchange Enterprise CAL con servicios** <br/> |
|[Destinatarios de correo](recipient-domain-and-company-management.md#mail-recipients) <br/> |Sí<sup>1</sup> <br/> |Sí<sup>1</sup> <br/> |Sí  <br/> |
|[Permisos de grupo de roles administrativos](recipient-domain-and-company-management.md#admin-role-group-permissions) <br/> |Sí<sup>2</sup> <br/> |Sí  <br/> |Sí  <br/> |
|[Administración de dominios](recipient-domain-and-company-management.md#domain-management) <br/> |Sí<sup>3</sup> <br/> |Sí<sup>3</sup> <br/> |Sí<sup>3</sup> <br/> |
|[Subdominios coincidentes](recipient-domain-and-company-management.md#match-subdomains) <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|[Bloqueo perimetral basado en directorios (DBEB)](recipient-domain-and-company-management.md#directory-based-edge-blocking-dbeb) <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|[Reglas de transporte](messaging-policy-and-compliance-servicedesc.md#transport-rules) <br/> |Sí<sup>3, 4, 14</sup> <br/> |Sí<sup>3, 4, 14</sup> <br/> |Sí  <br/> |
|[Registro de auditoría](messaging-policy-and-compliance-servicedesc.md#audit-logging) <br/> |Sí<sup>5</sup> <br/> |Sí  <br/> |Sí  <br/> |
|[Prevención de pérdida de datos (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp) <br/> |No  <br/> |Sí  <br/> |Sí<sup>6</sup> <br/> |
|[Cifrado de mensajes de Office 365](messaging-policy-and-compliance-servicedesc.md#office-365-message-encryption) <br/> |Sí<sup>12</sup> <br/> |Sí  <br/> |Sí<sup>12</sup> <br/> |
|[Protección contra correo no deseado](anti-spam-and-anti-malware-protection-eop.md#anti-spam-protection) (integrado)  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|[Personalizar directivas contra correo no deseado](anti-spam-and-anti-malware-protection-eop.md#customize-anti-spam-policies) <br/> |Sí<sup>7</sup> <br/> |Sí  <br/> |Sí  <br/> |
|[Protección antimalware](anti-spam-and-anti-malware-protection-eop.md#anti-malware-protection) (incorporado)  <br/> |Sí<sup>13</sup> <br/> |Sí  <br/> |Sí  <br/> |
|[Personalizar directivas antimalware](anti-spam-and-anti-malware-protection-eop.md#customize-anti-malware-policies) <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|[Cuarentena](anti-spam-and-anti-malware-protection-eop.md#quarantine): administración del administrador  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|[Cuarentena](anti-spam-and-anti-malware-protection-eop.md#quarantine): autoadministración de usuarios finales  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|[Complemento de notificación de correo no deseado de Microsoft Office Outlook](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-add-in-for-microsoft-office-outlook) <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|[Notificación de correo no deseado en Outlook Web App](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-in-outlook-web-app) <br/> |Sí<sup>8</sup> <br/> |No hay<sup>8</sup> <br/> |No hay<sup>8</sup> <br/> |
|[Enrutar correo electrónico entre Office 365 y sus servidores de correo electrónico propios](mail-flow-eop.md#routing-email-between-office-365-and-your-own-email-servers) <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|[Mensajería segura con un socio de confianza](mail-flow-eop.md#secure-messaging-with-a-trusted-partner) <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|[Incluir en una lista segura la dirección IP de un socio](mail-flow-eop.md#safe-listing-a-partners-ip-address) <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|[Enrutamiento de correo condicional](mail-flow-eop.md#conditional-mail-routing) <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|[Enrutamiento de correo híbrido](mail-flow-eop.md#hybrid-mail-routing) <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|[Informes del Centro de administración de Office 365](reporting-and-message-trace.md#office-365-admin-center-reports) <br/> |Sí<sup>9</sup> <br/> |Sí<sup>10</sup> <br/> |Sí <sup>9, 10</sup> <br/> |
|[Informes de aplicaciones de descarga de Excel](reporting-and-message-trace.md#excel-download-application-reports) <br/> |Sí  <br/> |Sí  <br/> |Sí<sup>11</sup> <br/> |
|[Creación de informes mediante servicios web](reporting-and-message-trace.md#reporting-using-web-services) <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |
|[Seguimiento de mensajes](reporting-and-message-trace.md#message-trace) <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí  <br/> |
|[Acceder al Centro de administración de Office 365](administration-and-management-eop.md#access-to-the-office-365-admin-center) <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|[Acceso al Centro de administración de Exchange](administration-and-management-eop.md#access-to-the-exchange-admin-center) (EAC)  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|[Acceso a Windows PowerShell remoto](administration-and-management-eop.md#remote-windows-powershell-access) <br/> |Sí<sup>2</sup> <br/> |Sí  <br/> |Sí  <br/> |
   
> [!NOTE]
> <sup>1</sup> correo a los usuarios se definen como "Buzones" y, junto con los contactos de correo externo, se pueden agregar, quita y o administra directamente en el centro de administración de Exchange (EAC). <br/>Personalización de RBAC No <sup>2</sup> . Roles de administrador. <br/> <sup>3</sup> dominios administrados pueden verse y tipos de dominio se pueden editar en el EAC. Todos los demás administración de dominio debe realizarse en el centro de administración de Office 365. <br/><sup>4</sup> los criterios flexibles disponibles y las acciones difieren de elevación de privilegios y Exchange Online. Para obtener una lista de criterios disponibles y acciones en EOP, vea [Criterios de la regla de transporte](https://go.microsoft.com/fwlink/p/?LinkId=320392) y [Acciones de regla de transporte](https://go.microsoft.com/fwlink/p/?LinkId=320393). Para obtener una lista de criterios disponibles y acciones en Exchange Online, vea [Criterios de la regla de transporte](https://go.microsoft.com/fwlink/p/?LinkId=320394) y [Acciones de regla de transporte](https://go.microsoft.com/fwlink/p/?LinkId=320395). <br/><sup>5</sup> informes de auditoría de EOP son un subconjunto de los informes de auditoría Exchange Online que excluyen la información acerca de los buzones de correo. <br/> <sup>6</sup> sugerencias de directivas DLP no están disponibles para Exchange Enterprise CAL con los clientes de servicios.<br/><sup>7</sup> la acción de filtro de contenido predeterminado es mover mensajes seguros a la carpeta de correo no deseado de los destinatarios. Para que funcione con buzones locales, también debe configurar dos reglas de transporte de Exchange en los servidores locales para detectar los encabezados de spam agregados por elevación de privilegios. Para obtener más información, vea [Asegúrese de que el correo no deseado se enrute a la carpeta de correo electrónico no deseado de cada usuario](https://go.microsoft.com/fwlink/p/?LinkId=320396). <br/><sup>8</sup> esta característica está disponible para los clientes de Exchange Server 2013 Service Pack 1 (SP1) cuyos buzones de correo se están filtrando por elevación de privilegios y pronto estará disponible para los clientes de Exchange Online. <br/><sup>9</sup> informes de EOP son un subconjunto de los informes de Exchange Online que excluyen la información acerca de los buzones de correo. <br/>Informes de DLP incluye <sup>10</sup> . <br/><sup>11</sup> de Exchange Enterprise CAL con los clientes de servicios debe instalar el libro seleccionando el servicio **Exchange Online** en lugar del servicio **Exchange Online Protection** . <br/><sup>12</sup> compatibles para los clientes locales que adquieren la protección de la información de Azure y usar Exchange Online Protection para redirigir el correo electrónico a través de Exchange Online. <br/> <sup>13</sup> analiza los mensajes entrantes y salientes, pero no analiza los mensajes internos que envía un remitente en su organización a un destinatario de la organización. <br/><sup>14</sup> las acciones y predicados disponibles difieren de elevación de privilegios y Exchange Online. <br/> <sup>15</sup> el programa de instalación híbrida no está disponible a través de asistente híbrida, pero se puede configurar manualmente si tiene el SP1 de Exchange. 