---
title: Office 365 GCC High y DoD
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0821204d-5515-43de-8ed6-ab84bd1693c1
description: Obtenga información sobre los compromisos exclusivos y las diferencias de los entornos altos y DoD de Office 365 GCC en comparación con el entorno comercial de Office 365.
ms.openlocfilehash: 44d66557f426ab236460affd61fbf1970c7f25e6
ms.sourcegitcommit: 8d17d5df1427a817df15d45eae5f2f3e48d7b12d
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/23/2020
ms.locfileid: "48214339"
---
# <a name="office-365-gcc-high-and-dod"></a>Office 365 GCC High y DoD

Para cumplir con los requisitos exclusivos y en constante evolución del Departamento de defensa de los Estados Unidos, así como los contratistas que retienen o procesan información sin clasificar (CUI) o en el tráfico internacional en las regulaciones de brazos (ITAR), Microsoft ofrece los entornos altos y DoD de GCC. Disponible mediante las licencias por volumen, las organizaciones que estén interesadas pueden participar en un proceso de validación para certificar su idoneidad antes de establecer el entorno. Las pruebas no están disponibles en este momento. 
  
Póngase en su equipo de cuentas o en su socio preferido para obtener más información o iniciar el proceso de validación. Para obtener más información sobre cómo comprar, consulte [Microsoft 365 Government: How to Buy](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy).
  
## <a name="how-to-use-this-service-description-section"></a>Cómo usar esta sección de Descripción del servicio

La descripción del servicio Office 365 US Government está diseñada para servir como una superposición a la descripción del servicio Office 365 general. Define los compromisos y diferencias únicos con respecto a las ofertas de Office 365 Enterprise.
  
## <a name="compliance"></a>Cumplimiento

GCC High y DoD cumplen los requisitos de cumplimiento para las siguientes certificaciones y acreditaciones: 
  
- El programa federal de administración de riesgos y autorización en FedRAMP High, incluidos los controles de seguridad y las mejoras de control descritas en la publicación especial del Instituto Nacional de normas y tecnología (NIST) 800-53.
    
- Controles de seguridad y mejoras de los controles para la Guía de requisitos de seguridad (SRG) sobre informática en la nube del Departamento de Defensa de Estados Unidos para la información hasta el nivel de impacto 5 (L5).
    
Los suscriptores de Departamento de defensa de Office 365 recibirán los servicios proporcionados desde el entorno exclusivo de DOD que cumpla con DOD SRG L5. Los suscriptores que no son de Departamento de defensa recibirán servicios del entorno de la defensa del gobierno estadounidense que se evalúa en el L5, pero usa la segmentación L4.
  
## <a name="background-screening"></a>Detección en segundo plano

El personal de Office 365 no tiene acceso permanente a la producción de GCC alta y DoD. Cualquier personal que solicite la elevación de permisos temporales que concedería el acceso al contenido del cliente debe haber aprobado primero las siguientes comprobaciones de antecedentes.
  
|||
|:-----|:-----|
|**Comprobaciones de antecedentes y examen del personal de Microsoft**<sup>1</sup> <br/> |**Descripción** <br/> |
|EE.UU. Ciudadanía  <br/> |Comprobación de la ciudadanía estadounidense  <br/> |
|Comprobación del historial de empleo  <br/> |Comprobación del historial de empleo (7 años)  <br/> |
|Comprobación de la formación académica  <br/> |Comprobación del grado más alto obtenido  <br/> |
|Búsqueda del número de la seguridad social (SSN)  <br/> |Comprobación de la validez del SSN proporcionado  <br/> |
|Comprobación de los antecedentes penales  <br/> |Una comprobación de los antecedentes penales de los últimos siete años en búsqueda de delitos y delitos menores a nivel local, de condado, estatal y federal.  <br/> |
|Office of Foreign Assets Control List (OFAC)  <br/> |Una comprobación que valida la información según la lista de grupos con los que los ciudadanos estadounidenses pueden realizar transacciones financieras o comerciales que elabora el Departamento del Tesoro.  <br/> |
|Bureau of Industry and Security List (BIS)  <br/> |Una comprobación que valida la información según la lista de individuos y entidades que no pueden realizar actividades de exportación que elabora el Departamento de Comercio.  <br/> |
|Office of Defense Trade Controls Debarred Persons List (DDTC)  <br/> |Una comprobación que valida la información según la lista de individuos y entidades que no pueden realizar actividades de exportación relacionadas con la industria militar que elabora el Departamento de Estado.  <br/> |
|Comprobación de las huellas digitales  <br/> |Una comprobación de antecedentes mediante las huellas digitales consultando las bases de datos del FBI.  <br/> |
|Departamento de Defensa IT-2  <br/> |El personal que solicite permisos elevados para los datos de los clientes o un acceso administrativo privilegiado a las funciones del servicio SRG L5 del Departamento de Defensa debe pasar la adjudicación IT-2 del Departamento de Defensa en función de una investigación correcta de OPM Nivel 3  <br/> |

<sup>1</sup> solo se aplica al personal con acceso temporal o permanente al contenido de cliente hospedado en Office 365 US GCC-nubes de alto o DoD.
## <a name="feature-nuances-based-on-compliant-cloud-architecture"></a>Características de matices basadas en la arquitectura de nube compatible

Las suscripciones de los entornos altos y DoD de GCC incluyen las características principales de Exchange Online, SharePoint y Skype empresarial. Dada la mayor certificación y acreditación de la infraestructura, existen algunas diferencias de características entre las ofertas de Office Commercial Office 365 y las que están disponibles en GCC High y DoD.
  
### <a name="exchange-online"></a>Exchange en línea

 La **compatibilidad de mensajería unificada de Exchange Online con IP-PBX local** es compatible con la integración de sistemas de IP-PBX local con mensajería unificada de Exchange online no se admite en las suscripciones alta y DoD de GCC. 
  
### <a name="file-sharing"></a>Uso compartido de archivos

Los usuarios tienen varias opciones para compartir archivos y carpetas en SharePoint y OneDrive. Todas las opciones están disponibles en los entornos de GCC High y DoD. Para obtener más información acerca de cómo administrar estas opciones, consulte [administrar la configuración de uso compartido](/sharepoint/turn-external-sharing-on-or-off). Los usuarios de GCC-High podrán compartir solo con otras organizaciones en GCC-High. Además, no se admiten las direcciones de correo electrónico de alta disponibilidad que no sean de GCC adjuntas a perfiles de usuario y no permitirá el envío de mensajes de alerta. Por ejemplo, en el caso del usuario A local se le asigna una dirección de correo electrónico de gmail y, a continuación, se sincroniza con una organización alta de Azure GCC. El usuario A visita una biblioteca y crea una alerta para los cambios. La alerta no se enviará a la dirección de gmail.

> [!NOTE]
> Los usuarios de GCC-High actualmente no pueden compartir con usuarios de grandes organizaciones que no sean GCC.

[Las solicitudes de archivo](https://support.office.com/article/f54aa7f8-2589-4421-b351-d415fc3b83af) no están disponibles para Office 365 Government.

### <a name="skype-for-business-online"></a>Skype Empresarial Online

 **Llamadas &amp; RTC Conferencias RTC** : debido a la necesidad de usar la red telefónica conmutada (RTC) para los servicios orientados a la telefonía, los &amp; servicios de conferencia RTC de llamadas RTC no están disponibles actualmente en gcc High y DoD.

### <a name="microsoft-teams"></a>Microsoft Teams

**Sistema telefónico y audioconferencia (mediante enrutamiento directo)**: el sistema telefónico y las conferencias de audio para los entornos altos y DoD de GCC se proporcionan a través del enrutamiento directo. Para obtener más información, vea la documentación del nivel de servicio aquí:

- [Sistema telefónico a través del enrutamiento directo](https://docs.microsoft.com/microsoftteams/here-s-what-you-get-with-phone-system)
- [Audioconferencia con enrutamiento directo para GCC High y DoD](https://docs.microsoft.com/microsoftteams/audio-conferencing-with-direct-routing-for-gcch-and-dod)

### <a name="identity"></a>Identidad

Multi-Factor Authentication con un modelo de identidad federado permite el uso de tarjetas PIV y CAC.
  
### <a name="yammer"></a>Yammer

Yammer Enterprise no está disponible en los entornos de GCC alto y DoD.
  
## <a name="customer-support"></a>Soporte al cliente

Microsoft le recuerda que no debe compartir ninguna información controlada, confidencial o confidencial con el personal de soporte técnico al cliente como parte de su incidente de soporte técnico cuando use Office 365 GCC High/DOD, como mínimo, hasta que confirme la autorización del agente de soporte para ver o acceder a dichos datos.

Microsoft se compromete a proteger su [privacidad](https://privacy.microsoft.com/privacystatement)). Sin embargo, la compatibilidad con Office 365 GCC High/DoD no se incluye en el límite de la acreditación de servicios y no proporciona garantías de cumplimiento normativo de administración de datos de FedRAMP, DOD SRG, ITAR, IRS 1075 o CJIS.
