---
title: Office 365 GCC High and DoD
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0821204d-5515-43de-8ed6-ab84bd1693c1
description: Obtenga información sobre los compromisos y diferencias únicos de los entornos de Office 365 GCC High y DoD en comparación con el entorno comercial de Office 365.
ms.openlocfilehash: c4dfdabde7090a7a0b89975eb329eb92016e22f2
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173965"
---
# <a name="office-365-gcc-high-and-dod"></a>Office 365 GCC High and DoD

Para cumplir con los requisitos únicos y en evolución del Departamento de Defensa de los Estados Unidos, así como los contratistas que retienen o procesan información sin clasificar controlada por doD (CUI) o sujeta al Reglamento de tráfico internacional de armas (ITAR), Microsoft ofrece entornos GCC High y DoD. Disponible mediante las licencias por volumen, las organizaciones que estén interesadas pueden participar en un proceso de validación para certificar su idoneidad antes de establecer el entorno. Las pruebas no están disponibles en este momento. 
  
Interactúe con su equipo de cuenta o socio preferido para obtener más información o iniciar el proceso de validación. Para obtener más información sobre cómo comprar, vea [Microsoft 365 Government - How to Buy](./microsoft-365-government-how-to-buy.md).
  
## <a name="how-to-use-this-service-description"></a>Cómo utilizar esta descripción del servicio

La descripción del servicio de Office 365 US Government está diseñada para servir como una superposición a la descripción general del servicio de Office 365. Define los compromisos y diferencias únicos en comparación con las ofertas de Office 365 para empresas.
  
## <a name="compliance"></a>Cumplimiento

GCC High y DoD cumplen los requisitos de cumplimiento para las siguientes certificaciones y acreditaciones: 
  
- El Programa federal de administración de riesgos y autorización en FedRAMP High, incluidos los controles de seguridad y las mejoras de control, tal como se describe en la Publicación especial 800-53 del Instituto Nacional de Estándares y Tecnología (NIST).
    
- Controles de seguridad y mejoras de los controles para la Guía de requisitos de seguridad (SRG) sobre informática en la nube del Departamento de Defensa de Estados Unidos para la información hasta el nivel de impacto 5 (L5).
    
Los suscriptores del Departamento de Defensa a Office 365 recibirán servicios proporcionados desde el entorno exclusivo de DOD que cumple con DOD SRG L5. Los suscriptores que no son del Departamento de Defensa recibirán servicios del entorno de defensa del gobierno de Estados Unidos que se evalúa en L5, pero usa la segmentación L4.
  
## <a name="background-screening"></a>Proyección en segundo plano

El personal de Office 365 no tiene acceso permanente a la producción de GCC High y DoD. Cualquier personal que solicite la elevación de permisos temporales que conceda acceso al contenido del cliente debe haber pasado primero las siguientes comprobaciones en segundo plano.<br><br>
  
| Examen de personal de Microsoft y comprobaciones de antecedentes<sup>1</sup> | Descripción |
|:-----|:-----|
|EE.UU. Ciudadanía    <br/> |Comprobación de la ciudadanía estadounidense  <br/> |
|Comprobación del historial de empleo  <br/> |Comprobación del historial de empleo (7 años)  <br/> |
|Comprobación de la formación académica  <br/> |Comprobación del grado más alto obtenido  <br/> |
|Búsqueda del número de la seguridad social (SSN)  <br/> |Comprobación de la validez del SSN proporcionado  <br/> |
|Comprobación de los antecedentes penales  <br/> |Una comprobación de los antecedentes penales de los últimos siete años en búsqueda de delitos y delitos menores a nivel local, de condado, estatal y federal.  <br/> |
|Office of Foreign Assets Control List (OFAC)  <br/> |Una comprobación que valida la información según la lista de grupos con los que los ciudadanos estadounidenses pueden realizar transacciones financieras o comerciales que elabora el Departamento del Tesoro.  <br/> |
|Bureau of Industry and Security List (BIS)  <br/> |Una comprobación que valida la información según la lista de individuos y entidades que no pueden realizar actividades de exportación que elabora el Departamento de Comercio.  <br/> |
|Office of Defense Trade Controls Debarred Persons List (DDTC)  <br/> |Una comprobación que valida la información según la lista de individuos y entidades que no pueden realizar actividades de exportación relacionadas con la industria militar que elabora el Departamento de Estado.  <br/> |
|Comprobación de las huellas digitales  <br/> |Una comprobación de antecedentes mediante las huellas digitales consultando las bases de datos del FBI.  <br/> |
|Departamento de Defensa IT-2  <br/> |El personal que solicite permisos elevados para los datos de los clientes o un acceso administrativo privilegiado a las funciones del servicio SRG L5 del Departamento de Defensa debe pasar la adjudicación IT-2 del Departamento de Defensa en función de una investigación correcta de OPM Nivel 3  <br/> |

<sup>1</sup> Solo se aplica al personal con acceso temporal o permanente al contenido del cliente hospedado en las nubes de Office 365 US GCC-High o DOD.
## <a name="feature-nuances-based-on-compliant-cloud-architecture"></a>Matices de características basados en la arquitectura de nube compatible

Las suscripciones en los entornos GCC High y DoD incluyen las características principales de Exchange Online, SharePoint y Skype Empresarial. Dada la mayor certificación y acreditación de la infraestructura, existen algunas diferencias de características entre las ofertas comerciales generales de Office 365 y las disponibles en GCC High y DoD.
  
### <a name="exchange-online"></a>Exchange Online

 Compatibilidad con mensajería unificada de Exchange Online para **IP-PBX** local: la compatibilidad con la integración de sistemas IP-PBX locales con la mensajería unificada de Exchange Online no se admite en las suscripciones de GCC High y DoD. 
  
### <a name="file-sharing"></a>Uso compartido de archivos

Los usuarios tienen varias opciones para compartir archivos y carpetas en SharePoint y OneDrive. Todas las opciones están disponibles en los entornos GCC High y DoD. Para obtener más información acerca de cómo administrar estas opciones, vea [Administrar la configuración de uso compartido.](/sharepoint/turn-external-sharing-on-or-off) Los usuarios GCC-High podrán compartir solo con otras organizaciones en GCC-High. Además, no se admiten las direcciones de correo electrónico high de NON-GCC adjuntas a perfiles de usuario y no permitirán el envío de mensajes de correo electrónico de alerta. Por ejemplo, al usuario local A se le asigna una dirección de correo electrónico de Gmail y, a continuación, se sincroniza con una organización de Azure GCC High. El usuario A navega a una biblioteca y crea una alerta para cualquier cambio. La alerta no se enviará a la dirección de Gmail.

> [!NOTE]
> Los usuarios de GCC-High actualmente no pueden compartir con usuarios de organizaciones que no son GCC High.

[Las solicitudes de](https://support.office.com/article/f54aa7f8-2589-4421-b351-d415fc3b83af) archivo no están disponibles para Office 365 Government.

### <a name="skype-for-business-online"></a>Skype Empresarial Online

 **Llamadas RTC &amp; Conferencia** RTC: debido al requisito de usar la red telefónica conmutada (RTC) para servicios orientados a telefonía, los servicios de conferencia RTC de llamadas RTC actualmente no están disponibles en GCC High y &amp; DoD.

### <a name="microsoft-teams"></a>Microsoft Teams

**Sistema telefónico y audioconferencia (mediante** enrutamiento directo): el sistema telefónico y la audioconferencia para entornos GCC High y DoD se entregan a través del enrutamiento directo. Para obtener más información, vea la documentación del nivel de servicio aquí:

- [Sistema telefónico mediante enrutamiento directo](/microsoftteams/here-s-what-you-get-with-phone-system)
- [Audioconferencia con enrutamiento directo para GCC High y DoD](/microsoftteams/audio-conferencing-with-direct-routing-for-gcch-and-dod)

### <a name="identity"></a>Identidad

Multi-Factor Authentication con un modelo de identidad federado permite el uso de tarjetas PIV y CAC.
  
### <a name="yammer"></a>Yammer

Yammer para empresas no está disponible en los entornos GCC High y DoD.
  
## <a name="customer-support"></a>Soporte al cliente

Microsoft le recuerda que no comparta ninguna información controlada, confidencial o confidencial con el personal de soporte técnico como parte de su incidente de soporte técnico al usar Office 365 GCC High/DOD, al menos hasta que confirme la autorización del agente de soporte técnico para ver o acceder a dichos datos.

Microsoft se compromete a proteger su [privacidad](https://privacy.microsoft.com/privacystatement)). Sin embargo, la compatibilidad con Office 365 GCC High/DoD no se incluye en el límite de acreditación de servicios y no proporciona garantías de cumplimiento de fedramp, dod srg, itar, irs 1075 o CJIS.