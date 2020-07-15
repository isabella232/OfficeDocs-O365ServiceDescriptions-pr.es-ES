---
title: Descripción del servicio Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: obtenga información sobre las características y los requisitos de Exchange Online Protection. Se incluye una lista de los planes que proporcionan protección en línea de Exchange, así como una comparación de las características en los planes.
ms.openlocfilehash: 74a2d3a1af3e369e51e1f9b3b4e1cf5cc981c0d8
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132844"
---
# <a name="exchange-online-protection-service-description"></a>Descripción del servicio Exchange Online Protection

obtenga información sobre las características y los requisitos de Exchange Online Protection. Se incluye una lista de los planes que proporcionan protección en línea de Exchange, así como una comparación de las características en los planes.

Microsoft Exchange Online Protection (EOP) is a cloud-based email filtering service that helps protect your organization against spam and malware, and includes features to safeguard your organization from messaging-policy violations. EOP can simplify the management of your messaging environment and alleviate many of the burdens that come with maintaining on-premises hardware and software.

En la siguiente lista se describen las formas principales en las que puede usar EOP para la protección de la mensajería:

- **En un escenario independiente**: EOP proporciona protección de correo electrónico basada en la nube para su entorno de correo electrónico local (Exchange Server u otras soluciones de correo electrónico SMTP locales).

- **Como parte de Microsoft Exchange Online: de**forma predeterminada, EOP protege los buzones de Exchange Online hospedados en la nube. Para obtener más información acerca de Exchange Online, vea la [Descripción del servicio de Exchange Online](../exchange-online-service-description/exchange-online-service-description.md).

- **En una implementación híbrida**: EOP se puede configurar para que proteja el entorno de mensajería y controle el enrutamiento del correo cuando se tiene una mezcla de buzones locales y en la nube.

Para comparar las características de los planes, consulte [herramientas eficaces para apoyar a su empresa](https://products.office.com/business/compare-more-office-365-for-business-plans).

Para comprar Protección de Exchange Online, vea [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).

> [!NOTE]
> EOP ha reemplazado Forefront online Protection para Exchange (FOPE). Todos los clientes de FOPE se han migrado a EOP.

## <a name="whats-new-in-exchange-online-protection-eop"></a>Novedades de la Exchange Online Protection (EOP)

El [plan de desarrollo de Microsoft 365](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx) es un buen recurso para encontrar información acerca de las nuevas y próximas características.

## <a name="exchange-online-protection-eop-plans"></a>Planes de Online Protection (EOP)

EOP está disponible a través de los siguientes planes de suscripción:

|**Plan**|**Descripción**|
|:-----|:-----|
|[EOP independiente](https://products.office.com/exchange/exchange-email-security-spam-protection)|Un servicio independiente basado en la nube que protege su organización de correo electrónico local.|
|[Características de EOP en Exchange Online](https://products.office.com/exchange/compare-microsoft-exchange-online-plans)|La protección integrada para sus buzones de Exchange Online hospedados en la nube.|
|[Exchange Enterprise CAL con servicios](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)|Las licencias de complemento que compre a su organización de Exchange local que incluyan EOP y otras características basadas en la nube (consulte la siguiente sección para obtener más información).|

### <a name="exchange-enterprise-cal-with-services-features"></a>Características de Exchange Enterprise CAL con servicios

Microsoft Exchange Enterprise CAL con servicios proporciona las características de protección de correo electrónico de EOP y las siguientes características adicionales basadas en la nube:

- [Data loss prevention (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [Creación de informes mediante servicios web](reporting-and-message-trace.md#reporting-using-web-services)

Para obtener más información acerca de las licencias de Exchange Enterprise CAL con servicios, vea [preguntas más frecuentes sobre licencias de Exchange](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business).

Si tiene licencias de Exchange Enterprise CAL con servicios y desea aprovisionar EOP, siga las instrucciones que se indican en [configurar el servicio de EOP](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-your-eop-service). Los pasos de configuración son los mismos que para configurar EOP independiente.

> [!NOTE]
> New features for Exchange Enterprise CAL with Services are deployed at the same time as Exchange Online, not EOP standalone. Be advised that the deployment schedules for EOP standalone and Exchange Online/Exchange Enterprise CAL with Services may be slightly different.

## <a name="requirements-for-exchange-online-protection-eop"></a>Requisitos de Online Protection (EOP)

EOP se puede usar con cualquier agente de transferencia de correo SMTP, como Microsoft Exchange Server. Para obtener información sobre los sistemas operativos, exploradores Web e idiomas compatibles con EOP, consulte las secciones "exploradores compatibles" y "idiomas compatibles" en [centro de administración de Exchange en Exchange Online Protection](https://docs.microsoft.com/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop).

## <a name="limits"></a>Límites

Para obtener más límites en EOP, consulte [límites de Exchange Online Protection](exchange-online-protection-limits.md).

## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>Disponibilidad de características en los planes de Exchange Online Protection (EOP) 

Each feature is listed below. For more detailed information about EOP features, click the links in the table. When Exchange Online is mentioned, it typically refers to the Office 365 Enterprise service family.

|||||
|:-----|:-----|:-----|:-----|
|**Característica**|**EOP independiente**|**Características de EOP en <br/> Exchange Online**|**Exchange Enterprise <br/> cal con servicios**|
|[Destinatarios de correo](recipient-domain-and-company-management.md#mail-recipients)|Sí<sup>1</sup>|Sí<sup>1</sup>|Sí|
|[Permisos de grupo de roles administrativos](recipient-domain-and-company-management.md#admin-role-group-permissions)|Sí<sup>2</sup>|Sí|Sí|
|[Administración de dominios](recipient-domain-and-company-management.md#domain-management)|Sí<sup>3</sup>|Sí<sup>3</sup>|Sí<sup>3</sup>|
|[Subdominios coincidentes](recipient-domain-and-company-management.md#match-subdomains)|Sí|Sí|No|
|[Bloqueo perimetral basado en directorios (DBEB)](recipient-domain-and-company-management.md#directory-based-edge-blocking-dbeb)|Sí|Sí|Sí|
|[Reglas de flujo de correo](../exchange-online-service-description/message-policy-and-compliance.md#mail-flow-rules)|Sí<sup>4</sup>|Sí<sup>4, 6</sup>|Sí|
|[Registro de auditoría](messaging-policy-and-compliance-servicedesc.md#audit-logging)|Sí<sup>5</sup>|Sí|Sí|
|[Prevención de pérdida de datos (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)|No|Sí|Sí<sup>6</sup>|
|[Cifrado de mensajes de Office 365](messaging-policy-and-compliance-servicedesc.md#office-365-message-encryption)|Sí<sup>12</sup>|Sí|Sí<sup>12</sup>|
|[Protección contra correo no deseado](anti-spam-and-anti-malware-protection-eop.md#anti-spam-protection) (integrado)|Sí|Sí|Sí|
|[Personalizar directivas contra correo no deseado](anti-spam-and-anti-malware-protection-eop.md#customize-anti-spam-policies)|Sí<sup>7</sup>|Sí|Sí|
|[Protección antimalware](anti-spam-and-anti-malware-protection-eop.md#anti-malware-protection) (incorporado)|Sí<sup>13</sup>|Sí|Sí|
|[Personalizar directivas antimalware](anti-spam-and-anti-malware-protection-eop.md#customize-anti-malware-policies)|Sí|Sí|Sí|
|[Cuarentena](anti-spam-and-anti-malware-protection-eop.md#quarantine): administración del administrador|Sí|Sí|Sí|
|[Cuarentena](anti-spam-and-anti-malware-protection-eop.md#quarantine): autoadministración de usuarios finales|Sí|Sí|Sí|
|[Envío](anti-spam-and-anti-malware-protection-eop.md#report-messages-to-microsoft-for-analysis)|No|Sí|No|
|[Complemento de mensajes de informe para Outlook](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in)|Sí|Sí|Sí|
|[Notificación de correo no deseado en Outlook en la web](https://docs.microsoft.com/microsoft-365/security/office-365-security/report-junk-email-and-phishing-scams-in-outlook-on-the-web-eop)|Sí|Sí|Sí|
|[Enrutamiento de correo electrónico entre Microsoft y sus propios servidores de correo electrónico](mail-flow-eop.md#routing-email-between-microsoft-and-your-own-email-servers)|Sí|Sí|Sí|
|[Mensajería segura con un socio de confianza](mail-flow-eop.md#secure-messaging-with-a-trusted-partner)|Sí|Sí|Sí|
|[Incluir en una lista segura la dirección IP de un socio](mail-flow-eop.md#safe-listing-a-partners-ip-address)|Sí|Sí|Sí|
|[Enrutamiento de correo condicional](mail-flow-eop.md#conditional-mail-routing)|Sí|Sí|Sí|
|[Enrutamiento de correo híbrido](mail-flow-eop.md#hybrid-mail-routing)|Sí|Sí|Sí|
|[Informes del centro de administración de Microsoft 365](reporting-and-message-trace.md#microsoft-365-admin-center-reports)<br/> |Sí<sup>9</sup>|Sí<sup>10</sup>|Sí <sup>9, 10</sup>|
|[Creación de informes mediante servicios web](reporting-and-message-trace.md#reporting-using-web-services)|No|Sí|Sí|
|[Seguimiento de mensajes](reporting-and-message-trace.md#message-trace)|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí|
|[Acceso al centro de administración de Microsoft 365](administration-and-management-eop.md#access-to-the-microsoft-365-admin-center)|Sí|Sí|Sí|
|[Acceso al centro de administración de Exchange](administration-and-management-eop.md#access-to-the-exchange-admin-center (CEF))|Sí|Sí|Sí|
|[Remote Windows PowerShell access](administration-and-management-eop.md#remote-windows-powershell-access)|Sí|Sí|Sí|

<sup>1</sup> los usuarios de correo se definen como "buzones" y, junto con los contactos de correo externos, se pueden agregar, quitar o administrar directamente en el centro de administración de Exchange (EAC). <br/>
<sup>2</sup> sin personalización de RBAC. Únicamente roles de administrador. <br/>
se pueden ver <sup>3</sup> dominios administrados y los tipos de dominio se pueden editar en el EAC. El resto de la administración de dominios debe realizarse en el centro de administración de Microsoft 365.<br/>
<sup>4</sup> las reglas de flujo de correo (también conocidas como reglas de transporte) en EOP se describen en [reglas de flujo de correo (reglas de transporte) en Exchange Online Protection](https://docs.microsoft.com/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0). Las condiciones, excepciones y acciones de la regla de flujo de correo disponibles difieren ligeramente entre EOP y Exchange Online. Estas diferencias se indican en [excepciones (predicados) y condiciones de reglas de flujo de correo en Exchange Online](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) y [las acciones de las reglas de flujo de correo en Exchange Online](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions).<br/>
<sup>5</sup> los informes de auditoría de EOP son un subconjunto de informes de auditoría de Exchange online que excluyen la información acerca de los buzones. <br/>
<sup>6</sup> las sugerencias de directiva DLP no están disponibles para los clientes de Exchange Enterprise cal con servicios.  <br/>
<sup>7</sup> la acción de filtrado de contenido predeterminada es mover mensajes de correo no deseado a la carpeta de correo no deseado de los destinatarios. Para que esto funcione con buzones de Exchange locales, también debe configurar dos reglas de transporte en la organización de Exchange local para detectar los encabezados de correo no deseado agregados por EOP. Para obtener más información, vea [configurar un EOP independiente para entregar el correo no deseado en la carpeta de correo no deseado en entornos híbridos](https://docs.microsoft.com/microsoft-365/security/office-365-security/ensure-that-spam-is-routed-to-each-user-s-junk-email-folder). <br/>
<sup>9</sup> los informes de EOP son un subconjunto de informes de Exchange online que excluyen la información acerca de los buzones.<br/>
<sup>10</sup> incluye informes de DLP. <br/>
<sup>12</sup> se admite para los clientes locales que adquieren Azure Information Protection y usan Exchange Online Protection para enrutar el correo electrónico a través de Exchange Online. <br/>
<sup>13</sup> examina los mensajes entrantes y salientes, pero no analiza los mensajes internos que envía un remitente a un destinatario de la organización. <br/>
<sup>15</sup> la configuración híbrida no está disponible a través del Asistente para la implementación híbrida, pero puede configurarse manualmente si tiene Exchange SP1.
