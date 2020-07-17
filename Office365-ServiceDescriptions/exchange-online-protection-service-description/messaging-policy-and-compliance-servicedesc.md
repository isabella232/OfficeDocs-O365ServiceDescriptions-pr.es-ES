---
title: Directiva de mensajería y conformidad
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: Microsoft Exchange Online Protection (EOP) proporciona características de cumplimiento y de directivas de mensajería que pueden ayudarle a administrar los datos de correo electrónico.
ms.openlocfilehash: 53997df9a3e5de8b8b2e319f6e4c36382e4db412
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132794"
---
# <a name="messaging-policy-and-compliance"></a>Directiva de mensajería y cumplimiento

Microsoft Exchange Online Protection (EOP) proporciona características de cumplimiento y de directivas de mensajería que pueden ayudarle a administrar los datos de correo electrónico.

¿Busca información sobre todas las características de EOP? Vea la [Descripción del servicio de protección en línea de Exchange](exchange-online-protection-service-description.md).

## <a name="mail-flow-rules"></a>Reglas de flujo de correo

Las reglas de flujo de correo (también conocidas como reglas de transporte) le proporcionan la flexibilidad para aplicar sus propias directivas específicas de la empresa para el correo electrónico. Las reglas de flujo de correo se componen de criterios flexibles, que permiten definir las condiciones, excepciones y acciones que se deben realizar en función de los criterios. Para obtener más información, vea [reglas de flujo de correo (reglas de transporte) en Exchange Online Protection](https://docs.microsoft.com/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0).

## <a name="audit-logging"></a>Registro de auditoría

El registro de auditoría le permite seguir cambios específicos efectuados por los administradores en la organización. Estos informes le ayudan a cumplir los requisitos normativos, de cumplimiento normativo y de litigio. Para obtener más información, vea [Informes de auditoría en EOP](https://docs.microsoft.com/microsoft-365/security/office-365-security/auditing-reports-in-eop).

## <a name="data-loss-prevention-dlp"></a>Prevención de pérdida de datos (DLP)

No está disponible para clientes independientes de EOP. La prevención de pérdida de datos (DLP) le ayuda a identificar, supervisar y proteger datos confidenciales de la organización haciendo un análisis de contenidos más pormenorizado. La DLP es cada vez más importante para los sistemas de mensajes de las empresas, ya que en los correos importantes del negocio se manejan datos que hay que proteger. La característica DLP permite proteger datos confidenciales sin que ello afecte a la productividad de los trabajadores.

Puede configurar directivas de DLP en el EAC, lo que le permite:

- Comenzar con una plantilla de directivas preconfigurada que ayudará a detectar tipos específicos de información confidencial, como datos PCI-DSS, datos de la ley Gramm-Leach-Bliley o incluso información de identificación personal (PII) local específica.

- Usar toda la potencia de las acciones y los criterios de reglas de flujo de correo existentes y agregar nuevas reglas de flujo de correo.

- Probar la eficacia de sus directivas de DLP antes de aplicarlas plenamente.

- Incorporar sus propias plantillas de directivas de DLP y sus propios tipos de información confidencial.

- Detectar información confidencial en datos adjuntos de mensajes, texto del cuerpo o líneas de asuntos y ajustar en nivel de confianza en el que el servicio realiza una acción.

- Detectar datos confidenciales mediante las huellas digitales de documentos. La creación de huellas digitales de documentos le ayuda a crear fácilmente tipos personalizados de información confidencial basados en formularios de texto que puede usar para definir reglas de flujo de correo y directivas de DLP.

- Agregar sugerencias de directivas, que pueden ayudar a reducir la pérdida de datos al mostrar un aviso a los usuarios de Outlook 2013, Outlook en la web y OWA para dispositivos, y también pueden mejorar la eficacia de las directivas al permitir la creación de informes falsos positivos.

- Revisar los datos de incidentes en informes de DLP o agregar sus propios informes específicos mediante una acción de generación de informes de incidentes.

> [!NOTE]
> Las directivas de DLP se aplican solo al correo que entra o sale de la organización. El correo transmitido dentro de la organización (interno) no tiene directivas de DLP aplicadas a menos que se ejecute Exchange Server 2013 con DLP local. Esto también se aplica a las sugerencias de directivas de DLP, que informan a los usuarios sobre posibles infracciones de las directivas antes de que los datos confidenciales se envíen por error a destinatarios no autorizados.

Para obtener más información sobre DLP, vea [prevención de pérdida de datos en Exchange Online](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention).

## <a name="office-365-message-encryption"></a>Cifrado de mensajes de Office 365

El cifrado de mensajes de Office 365, una parte de Azure Information Protection, es un servicio en línea que permite a los usuarios de correo electrónico enviar mensajes de correo electrónico cifrados a cualquier persona. Los clientes locales pueden obtener acceso al cifrado de mensajes de Office 365 mediante la compra de Azure Information Protection y el uso de Exchange Online Protection para configurar el flujo de correo a través de Exchange Online. Para obtener más información sobre el cifrado de mensajes de Office 365 en Exchange Online, consulte [office 365 Message Encryption](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption) en la descripción del servicio de Exchange Online.

## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>Características de cumplimiento y de directivas de mensajería en las opciones de EOP.

|**Característica**|**EOP independiente**|**Características de EOP en <br/> Exchange Online**|**Exchange Enterprise <br/> cal con servicios**|
|:-----|:-----|:-----|:-----|
|Reglas de flujo de correo|Sí<sup>1</sup>|Sí<sup>1</sup>|Sí<sup>, 1, 3</sup>|
|Registro de auditoría|Sí<sup>2</sup>|Sí|Sí|
|Prevención de pérdida de datos (DLP)|No|Sí|Sí<sup>3</sup>|
|Cifrado de mensajes de Office 365|Sí<sup>4</sup>|Sí|Sí<sup>4</sup>|

> [!NOTE]
> <sup>1</sup> las condiciones, excepciones y acciones de la regla de flujo de correo disponibles difieren ligeramente entre EOP y Exchange Online. Estas diferencias se indican en [excepciones (predicados) y condiciones de reglas de flujo de correo en Exchange Online](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) y [las acciones de las reglas de flujo de correo en Exchange Online](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions). <br/>
> <sup>2</sup> Los informes de auditoría de EOP son un subconjunto de informes de auditoría de Exchange Online que excluyen información sobre los buzones. <br/>
> <sup>3</sup> Las sugerencias de directiva DLP no están disponibles para los clientes de Exchange Enterprise CAL con servicios. <br/>
> <sup>4</sup> se admite para los clientes locales que adquieren el complemento Azure Information Protection y usan Exchange Online Protection para redirigir el correo electrónico a través de Exchange Online. Para la experiencia de escritorio, además del complemento de Azure Information Protection, es necesario adquirir las aplicaciones de Microsoft 365 para empresas. <br/>
