---
title: Cumplimiento y directivas de mensajería (ServiceDesc)
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: Microsoft Exchange Online Protection (EOP) proporciona la directiva de mensajería y características de cumplimiento que le ayudan a administración los datos de correo electrónico.
ms.openlocfilehash: f88cd016586384f4617cd4899708c811a32af980
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036953"
---
# <a name="messaging-policy-and-complianceservicedesc"></a>Cumplimiento y directivas de mensajería (ServiceDesc)

Microsoft Exchange Online Protection (EOP) proporciona la directiva de mensajería y características de cumplimiento que le ayudan a administración los datos de correo electrónico.
  
¿Busca información sobre todas las características de EOP? Vea [Descripción de servicio Protección en línea de Exchange](exchange-online-protection-service-description.md).
  
## <a name="transport-rules"></a>Reglas de transporte
<a name="BKMK_transportrules"> </a>

Las reglas de transporte permiten aplicar directivas específicas de su compañía al correo. Las reglas de transporte están formadas por criterios flexibles, que permiten definir condiciones y excepciones, y por acciones a llevar a cabo según los criterios. Para obtener más información sobre reglas de transporte en EOP, vea [Reglas de transporte](https://go.microsoft.com/fwlink/p/?LinkId=320399).
  
## <a name="audit-logging"></a>Registro de auditoría
<a name="BKMK_auditlogging"> </a>

El registro de auditoría le permite seguir cambios específicos efectuados por los administradores en la organización. Estos informes le ayudan a cumplir los requisitos normativos, de cumplimiento normativo y de litigio. Para obtener más información, vea [Informes de auditoría en EOP](https://go.microsoft.com/fwlink/p/?LinkId=314258).
  
## <a name="data-loss-prevention-dlp"></a>Prevención de pérdida de datos (DLP)
<a name="BKMK_datalossprevention"> </a>

No está disponible para clientes independientes de EOP. La prevención de pérdida de datos (DLP) le ayuda a identificar, supervisar y proteger datos confidenciales de la organización haciendo un análisis de contenidos más pormenorizado. La DLP es cada vez más importante para los sistemas de mensajes de las empresas, ya que en los correos importantes del negocio se manejan datos que hay que proteger. La característica de DLP permite proteger datos confidenciales sin afectar a la productividad de los trabajadores.
  
Puede configurar directivas de DLP en el EAC, lo que le permite:
  
- Comenzar con una plantilla de directivas preconfigurada que ayudará a detectar tipos específicos de información confidencial, como datos PCI-DSS, datos de la ley Gramm-Leach-Bliley o incluso información de identificación personal (PII) local específica.
    
- Utilizar todo el poder de las acciones y los criterios de las reglas de transporte existentes y agregar nuevas reglas de transporte.
    
- Probar la eficacia de sus directivas de DLP antes de aplicarlas plenamente.
    
- Incorporar sus propias plantillas de directivas de DLP y sus propios tipos de información confidencial.
    
- Detectar información confidencial en datos adjuntos de mensajes, texto del cuerpo o líneas de asuntos y ajustar en nivel de confianza en el que el servicio realiza una acción.
    
- Detectar datos confidenciales mediante las huellas digitales de documentos. Las huellas digitales de documentos ayudan a crear fácilmente tipos de información confidencial personalizada en función de formularios basados en texto que se pueden usar para definir las reglas de transporte y las directivas DLP.
    
- Agregar Sugerencias de directivas, que pueden ayudar a reducir la pérdida de datos al mostrar un aviso a los usuarios de Outlook 2013, Outlook Web App y OWA para dispositivos, y también pueden mejorar la eficacia de las directivas al permitir la creación de informes falsos positivos.
    
- Revisar los datos de incidentes en informes de DLP o agregar sus propios informes específicos mediante una acción de generación de informes de incidentes.
    
> [!NOTE]
> Las directivas de DLP se aplican solo al correo que entra o sale de la organización. El correo transmitido dentro de la organización (interno) no tiene directivas de DLP aplicadas a menos que se ejecute Exchange Server 2013 con DLP local. Esto también se aplica a las sugerencias de directivas de DLP, que informan a los usuarios sobre posibles infracciones de las directivas antes de que los datos confidenciales se envíen por error a destinatarios no autorizados. 
  
Para obtener más información sobre DLP, vea [Prevención de pérdida de datos](https://go.microsoft.com/fwlink/p/?LinkId=320398).
  
## <a name="office-365-message-encryption"></a>Cifrado de mensajes de Office 365
<a name="BKMK_OME_in_EOP"> </a>

Cifrado de mensajes de Office 365, una parte de la protección de la información de Azure, es un servicio en línea que permite a los usuarios de correo electrónico enviar mensajes de correo electrónico cifrado a cualquier persona. Los clientes locales pueden tener acceso a cifrado de mensajes de Office 365 mediante la compra de protección de la información de Azure y uso de Exchange Online Protection para configurar el flujo de correo a través de Exchange Online. Para obtener más información acerca del cifrado de mensajes de Office 365 en Exchange Online, vea [Office 365 Message Encryption](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption) en la descripción del servicio Exchange Online. 
  
## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>Características de cumplimiento y de directivas de mensajería en las opciones de EOP.
<a name="BKMK_OME_in_EOP"> </a>

|**Característica**|**EOP independiente**|**Características de EOP en Exchange Online**|**Exchange Enterprise CAL con servicios**|
|:-----|:-----|:-----|:-----|
|Reglas de transporte  <br/> |Sí<sup>1</sup> <br/> |Sí<sup>1</sup> <br/> |Sí  <br/> |
|Registro de auditoría  <br/> |Sí<sup>2</sup> <br/> |Sí  <br/> |Sí  <br/> |
|Prevención de pérdida de datos (DLP)  <br/> |No  <br/> |Sí  <br/> |Sí<sup>3</sup> <br/> |
|Cifrado de mensajes de Office 365  <br/> |Sí<sup>4</sup> <br/> |Sí  <br/> |Sí<sup>4</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> los criterios disponibles y las acciones difieren de elevación de privilegios y Exchange Online. Para obtener una lista de criterios disponibles y acciones en EOP, vea [Criterios de la regla de transporte](https://go.microsoft.com/fwlink/p/?LinkId=320392) y [Acciones de regla de transporte](https://go.microsoft.com/fwlink/p/?LinkId=320393). Para obtener una lista de criterios disponibles y acciones en Exchange Online, vea [Criterios de la regla de transporte](https://go.microsoft.com/fwlink/p/?LinkId=320394) y [Acciones de regla de transporte](https://go.microsoft.com/fwlink/p/?LinkId=320395). > Informes de auditoría de <sup>2</sup> EOP es un subconjunto de Exchange Online de auditoría informes que excluyen la información acerca de los buzones de correo. > <sup>3</sup> sugerencias de directivas DLP no están disponibles para Exchange Enterprise CAL con los clientes de servicios. > <sup>4</sup> compatibles para los clientes locales que adquieren el complemento de protección de la información de Azure y usar Exchange Online Protection para enrutar el correo electrónico a través de Exchange Online. Para la experiencia de escritorio, además de complemento de protección de la información de Azure, Office 365 ProPlus debe adquirirse. 
  

