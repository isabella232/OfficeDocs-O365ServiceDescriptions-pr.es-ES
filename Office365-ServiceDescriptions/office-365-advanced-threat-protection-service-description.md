---
title: Descripción del servicio de Protección contra amenazas avanzada de Office 365
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 avanzada amenaza protección (ATP) es un correo electrónico basada en la nube de servicio que ayuda a proteger su organización contra malware desconocido y virus proporcionando sólida protección de día cero e incluye características como medida de seguridad de filtrado su organización de vínculos dañinos en tiempo real. ATP tiene informes enriquecidos y capacidades de seguimiento de dirección URL que proporcionan a los administradores de idea en el tipo de ataques ocurre en su organización.
ms.openlocfilehash: 6c7ce44932312b82293b19d85ebac07137716617
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/19/2018
ms.locfileid: "24037037"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Descripción del servicio de Protección contra amenazas avanzada de Office 365

Microsoft Office 365 avanzada amenaza protección (ATP) es un correo electrónico basada en la nube de servicio que ayuda a proteger su organización contra malware desconocido y virus proporcionando sólida protección de día cero e incluye características como medida de seguridad de filtrado su organización de vínculos dañinos en tiempo real. ATP tiene informes enriquecidos y capacidades de seguimiento de dirección URL que proporcionan a los administradores de idea en el tipo de ataques ocurre en su organización.
  
Estas son las principales formas en las que se puede usar ATP para la protección de mensajes:
  
- En un escenario de filtrado sólo Office 365 ATP, ATP ofrece protección de correo electrónico basada en la nube para su entorno de Exchange Server 2013 local, versiones heredadas de Exchange Server o cualquier otra solución de correo electrónico SMTP de local.
    
- Office 365 ATP puede habilitarse para proteger los buzones de correo Exchange Online hospedada en la nube. Para obtener más información acerca de Exchange Online, vea la [Descripción del servicio en línea de Exchange](https://technet.microsoft.com/en-us/library/exchange-online-service-description.aspx).
    
- En una implementación híbrida, ATP puede configurarse para proteger el entorno de mensajería y controlar el enrutamiento de correo cuando tiene una mezcla de local y en la nube de buzones de correo con Exchange Online Protection para el filtrado de correo electrónico entrante.
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a>Disponibilidad de protección avanzada de amenaza (ATP) de Office 365

ATP se incluye en Office 365 Enterprise E5, Office 365 educación A5 y Microsoft 365 empresarial. 
  
> [!NOTE]
> Características de cliente dependiente ATP en Microsoft 365 Business estará disponible 2018 verano. 
  
Puede agregar ATP en los siguientes planes de suscripción de Exchange y Office 365: 
  
- Plan 1 de Exchange Online
    
- Plan 2 de Exchange Online
    
- Quiosco de Exchange Online
    
- Exchange Online Protection
    
- Office 365 Empresa Essentials
    
- Office 365 Empresa Premium
    
- Office 365 Enterprise E1
    
- Office 365 Enterprise E3
    
- Office 365 Enterprise F1
    
- Office 365 A1
    
- Office 365 A3
    
Para adquirir la protección de amenaza avanzada de Office 365, consulte [Protección de amenaza avanzada de Office 365](https://go.microsoft.com/fwlink/p/?LinkId=294201).
  
Para comparar las características de los diferentes planes, consulte [Comparar los planes de Office 365 para empresas](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409).
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>¿Qué es nuevo en 365 avanzada amenaza protección (ATP) de Office

Para obtener información acerca de las nuevas características de ATP, consulte [vínculos seguros de ATP en Office 365](https://go.microsoft.com/fwlink/?linkid=846016).
  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Requisitos para Office 365 protección avanzada (ATP)

La ATP puede usarse con cualquier agente de transferencia de correo SMTP, como Microsoft Exchange Server 2013. Para obtener información sobre los sistemas operativos, los exploradores web y los idiomas compatibles con ATP, vea las secciones "Exploradores compatibles" e "Idiomas admitidos en EOP" en el [Centro de administración de Exchange en Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Disponibilidad de características en los planes de protección avanzada de amenaza (ATP)

A continuación, se incluye cada característica. Cuando se menciona Exchange Online, por lo general se refiere a la familia de servicios de Office 365 Enterprise.
  
|**Característica**|**ATP independiente**|**Exchange Online Protection**|
|:-----|:-----|:-----|
|Vínculos seguros  <br/> |Sí  <br/> |No  <br/> |
|Datos adjuntos seguros  <br/> |Sí  <br/> |No  <br/> |
|Suplantación de la inteligencia  <br/> |Sí  <br/> |No  <br/> |
|Cuarentena  <br/> |Sí  <br/> |Sí  <br/> |
|Capacidades avanzadas de contra suplantación de identidad  <br/> |Sí  <br/> |No  <br/> |
   
## <a name="advanced-threat-protection-atp-capabilities"></a>Funcionalidades de protección (ATP) de amenaza avanzadas

### <a name="safe-links"></a>Vínculos seguros

La característica vínculos seguros ATP protege de forma preventiva los usuarios de los hipervínculos malintencionados en un mensaje. La protección permanece cada vez haga clic en el vínculo, como vínculos malintencionados se bloquean dinámicamente mientras se pueden tener acceso a vínculos buena.
  
### <a name="safe-attachments"></a>Datos adjuntos seguros

Los datos adjuntos seguros protegen contra los virus y códigos dañinos y proporcionan protección de día cero para proteger el sistema de mensajería. Todos los mensajes y datos adjuntos que no tienen una firma de virus/código dañino conocida se enrutan a un entorno especial donde ATP usa diversas técnicas de análisis y aprendizaje automático para detectar intentos malintencionados. Si no se detecta ninguna actividad sospechosa, se libera el mensaje para su entrega al buzón de correo. 
  
### <a name="spoof-intelligence"></a>Suplantación de la inteligencia

Suplantación de la inteligencia detecta cuando un remitente parece ser enviar correo en nombre de una o más cuentas de usuario dentro de uno de los dominios de la organización. Permite revisar todos los remitentes que son suplantación de su dominio y, a continuación, elija Permitir que el remitente continuar o bloquear al remitente. Suplantación de la inteligencia está disponible en la seguridad &amp; centro de cumplimiento en la página de configuración contra correo no deseado.
  
### <a name="quarantine"></a>Cuarentena

Los mensajes identificados por el servicio Office 365 como correo no deseado, correo masivo, correo de suplantación de identidad, que contiene el malware, o porque coincide con una regla de flujo de correo se puede enviar a cuarentena. De forma predeterminada, Office 365 envía los mensajes de suplantación de identidad y mensajes que contengan malware directamente en cuarentena. Los usuarios autorizados pueden revisar, eliminar o administrar los mensajes de correo electrónico que se envían a cuarentena.
  
### <a name="advanced-anti-phishing-capabilities"></a>Capacidades avanzadas de contra suplantación de identidad

Esta característica utiliza modelos de aprendizaje de máquina para detectar los mensajes de suplantación de identidad. 
  
