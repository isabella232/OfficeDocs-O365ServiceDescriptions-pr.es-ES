---
title: Descripción del servicio Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: obtenga información sobre las características y los requisitos de Exchange Online Protection. Se incluye una lista de planes que proporcionan Exchange Online Protection, así como una comparación de características en esos planes.
ms.openlocfilehash: 172e07db12590e51720c2446974418244f3234e4
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653042"
---
# <a name="exchange-online-protection-service-description"></a>Descripción del servicio Exchange Online Protection

obtenga información sobre las características y los requisitos de Exchange Online Protection. Se incluye una lista de planes que proporcionan Exchange Online Protection, así como una comparación de características en esos planes.

Microsoft Protección de Exchange Online (EOP) es un servicio de filtro de correo electrónico basado en nube que ayuda a proteger su organización contra correo no deseado y malware, e incluye características para proteger a su organización contra incumplimiento de directivas de mensajería. EOP simplifica la administración de un entorno de mensajes y puede aliviar muchas de las cargas asociadas al mantenimiento del hardware y del software local.

En la siguiente lista se describen las formas principales de usar EOP para la protección de mensajería:

- **En un escenario independiente:** EOP proporciona protección de correo electrónico basada en la nube para su entorno de correo electrónico local (Exchange Server otras soluciones de correo electrónico SMTP locales).

- **Como parte de Microsoft Exchange Online:** De forma predeterminada, EOP protege los buzones hospedados en la nube de Exchange Online. Para obtener más información acerca de Exchange Online, vea la [descripción del servicio de Exchange Online](../exchange-online-service-description/exchange-online-service-description.md).

- **En una implementación híbrida:** EOP se puede configurar para proteger el entorno de mensajería y controlar el enrutamiento de correo cuando se tiene una combinación de buzones locales y en la nube.

## <a name="available-plans"></a>Planes disponibles

Para obtener información detallada del plan sobre las suscripciones que permiten a los usuarios para Exchange Online Protection, consulte la tabla de comparación [de suscripciones completa.](https://go.microsoft.com/fwlink/?linkid=2139145)

Para comprar Protección de Exchange Online, vea [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).

> [!NOTE]
> EOP reemplazó a Forefront Online Protection para Exchange (FOPE). Todos los clientes de FOPE se han migrado a EOP.

## <a name="whats-new-in-exchange-online-protection-eop"></a>Novedades de la Exchange Online Protection (EOP)

La [guía básica de Microsoft 365](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx) es un buen recurso para obtener información sobre las próximas nuevas características.

## <a name="exchange-online-protection-eop-plans"></a>Planes de Online Protection (EOP)

EOP está disponible a través de los siguientes planes de suscripción:<br><br>

| Plan | Descripción |
|:-----|:-----|
|[EOP independiente](https://products.office.com/exchange/exchange-email-security-spam-protection)|Un servicio independiente basado en la nube que protege su organización de correo electrónico local.|
|[Características de EOP en Exchange Online](https://products.office.com/exchange/compare-microsoft-exchange-online-plans)|La protección integrada para los buzones hospedados en la nube de Exchange Online.|
|[Exchange Enterprise CAL con servicios](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)|Licencias de complementos que compre para su organización local de Exchange que incluyen EOP y otras características basadas en la nube (vea la siguiente sección para obtener más información).|

### <a name="exchange-enterprise-cal-with-services-features"></a>Características de Exchange Enterprise CAL con servicios

Microsoft Exchange Enterprise CAL with Services proporciona las características de protección de correo electrónico de EOP y las siguientes características adicionales basadas en la nube:

- [Prevención de pérdida de datos (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [Creación de informes mediante servicios web](reporting-and-message-trace.md#reporting-using-web-services)

Para obtener más información acerca de las licencias de Exchange Enterprise CAL con servicios, vea Preguntas frecuentes sobre licencias [de Exchange](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business).

Si tiene licencias de Exchange Enterprise CAL con Servicios y desea aprovisionar EOP, siga las instrucciones de [Configurar el servicio EOP](/microsoft-365/security/office-365-security/set-up-your-eop-service). Los pasos de configuración son los mismos que para configurar EOP independiente.

> [!NOTE]
> Las nuevas características de Exchange Enterprise CAL con servicios se implementan al mismo tiempo que Exchange Online, en lugar de EOP independiente. Le avisamos que las programaciones de implementación para EOP independiente y Exchange Online/Exchange Enterprise CAL con servicios pueden ser ligeramente diferentes.

## <a name="requirements-for-exchange-online-protection-eop"></a>Requisitos de Online Protection (EOP)

EOP se puede usar con cualquier agente de transferencia de correo SMTP, como Microsoft Exchange Server. Para obtener información sobre los sistemas operativos, exploradores web e idiomas compatibles con EOP, vea las secciones "Exploradores compatibles" y "Idiomas admitidos" en el Centro de administración de Exchange en [Exchange Online Protection](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop).

## <a name="limits"></a>Límites

Para obtener información sobre los límites de EOP, [vea Límites de Exchange Online Protection](exchange-online-protection-limits.md).

## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>Disponibilidad de características en los planes de Exchange Online Protection (EOP) 

A continuación, se incluye cada característica. Si desea ver información más detallada sobre las características de EOP, haga clic en los vínculos de la tabla. Cuando se menciona Exchange Online, por lo general se refiere a la familia de servicios de Office 365 Enterprise.<br><br>

| Característica | EOP independiente | Características de EOP en Exchange  Online | Exchange Enterprise CAL con servicios|
|:-----|:-----|:-----|:-----|
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
|[Complemento De mensaje de informe para Outlook](/microsoft-365/security/office-365-security/enable-the-report-message-add-in)|Sí|Sí|Sí|
|[Informes de correo no deseado en Outlook en la web](/microsoft-365/security/office-365-security/report-junk-email-and-phishing-scams-in-outlook-on-the-web-eop)|Sí|Sí|Sí|
|[Enrutamiento de correo electrónico entre Microsoft y sus propios servidores de correo electrónico](mail-flow-eop.md#routing-email-between-microsoft-and-your-own-email-servers)|Sí|Sí|Sí|
|[Mensajería segura con un socio de confianza](mail-flow-eop.md#secure-messaging-with-a-trusted-partner)|Sí|Sí|Sí|
|[Incluir en una lista segura la dirección IP de un socio](mail-flow-eop.md#safe-listing-a-partners-ip-address)|Sí|Sí|Sí|
|[Enrutamiento de correo condicional](mail-flow-eop.md#conditional-mail-routing)|Sí|Sí|Sí|
|[Enrutamiento de correo híbrido](mail-flow-eop.md#hybrid-mail-routing)|Sí|Sí|Sí|
|[Informes del Centro de administración de Microsoft 365](reporting-and-message-trace.md#microsoft-365-admin-center-reports)<br/> |Sí<sup>9</sup>|Sí<sup>10</sup>|Sí <sup>9, 10</sup>|
|[Creación de informes mediante servicios web](reporting-and-message-trace.md#reporting-using-web-services)|No|Sí|Sí|
|[Seguimiento de mensajes](reporting-and-message-trace.md#message-trace)|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí|
|[Acceso al Centro de administración de Microsoft 365](administration-and-management-eop.md#access-to-the-microsoft-365-admin-center)|Sí|Sí|Sí|
|[Acceso al Centro de administración de Exchange](administration-and-management-eop.md#access-to-the-exchange-admin-center (CEF))|Sí|Sí|Sí|
|[Remote Windows PowerShell access](administration-and-management-eop.md#remote-windows-powershell-access)|Sí|Sí|Sí|

<sup>1</sup> Los usuarios de correo se definen como "buzones" y, junto con los contactos de correo externos, pueden agregarse, quitarse y administrarse directamente en el Centro de administración de Exchange (EAC). <br/>
<sup>2</sup> Sin personalización rbac. Únicamente roles de administrador. <br/>
Se pueden ver <sup>3</sup> dominios administrados y los tipos de dominio se pueden editar en el EAC. El resto de la administración de dominios debe realizarse en el Centro de administración de Microsoft 365.<br/>
<sup>4</sup> Las reglas de flujo de correo (también conocidas como reglas de transporte) en EOP se describen en Reglas de flujo de correo (reglas de [transporte) en Exchange Online Protection](/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0). Las condiciones de regla de flujo de correo disponibles, las excepciones y las acciones difieren ligeramente entre EOP y Exchange Online. Estas diferencias se observan en las condiciones y excepciones [](/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions)de reglas de flujo de correo [(predicados) en las](/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) acciones de regla de flujo de correo y Exchange Online.<br/>
<sup>5</sup> Informes de auditoría de EOP son un subconjunto de informes de auditoría de Exchange Online que excluyen información sobre buzones. <br/>
<sup>6 sugerencias</sup> de directivas DLP no están disponibles para clientes de Exchange Enterprise CAL con servicios.  <br/>
<sup>7</sup> La acción predeterminada de filtro de contenido es mover mensajes de correo no deseado a la carpeta de correo no deseado de los destinatarios. Para que esto funcione con buzones de Exchange locales, también debe configurar dos reglas de transporte en la organización local de Exchange para detectar encabezados de correo no deseado agregados por EOP. Para obtener más información, vea [Configure standalone EOP to deliver spam to the Junk Email folder in hybrid environments](/microsoft-365/security/office-365-security/ensure-that-spam-is-routed-to-each-user-s-junk-email-folder). <br/>
<sup>9</sup> informes de EOP son un subconjunto de informes de Exchange Online que excluyen información sobre buzones.<br/>
<sup>10</sup> Incluye informes DLP. <br/>
<sup>12</sup> Compatible con clientes locales que compran Azure Information Protection y usan Exchange Online Protection para enrutar el correo electrónico a través de Exchange Online. <br/>
<sup>13</sup> Examina los mensajes entrantes y salientes, pero no examina los mensajes internos enviados desde un remitente de la organización a un destinatario de la organización. <br/>
<sup>15</sup> La configuración híbrida no está disponible a través del Asistente híbrido, pero se puede configurar manualmente si tiene Exchange SP1.