---
title: Office 365 GCC High y DoD
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0821204d-5515-43de-8ed6-ab84bd1693c1
description: Obtenga información sobre los compromisos y diferencias únicos de los entornos Office 365 GCC High y DoD en comparación con el entorno Office 365 comercial.
ms.openlocfilehash: 5446d5d1e6e10649a75f001c92f0d970e2fae842
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653462"
---
# <a name="office-365-gcc-high-and-dod"></a>Office 365 GCC High y DoD

Para cumplir con los requisitos únicos y en evolución del Departamento de Defensa de los Estados Unidos, así como los contratistas que retienen o procesan información sin clasificar controlada por doD (CUI) o sujeta a los Reglamentos de tráfico internacional de armas (ITAR), Microsoft ofrece entornos GCC high y doD. Disponible mediante las licencias por volumen, las organizaciones que estén interesadas pueden participar en un proceso de validación para certificar su idoneidad antes de establecer el entorno. Las pruebas no están disponibles en este momento. 
  
Interactúe con su equipo de cuenta o socio preferido para obtener más información o iniciar el proceso de validación. Para obtener más información sobre cómo comprar, [vea Microsoft 365 Government - How to Buy](./microsoft-365-government-how-to-buy.md).
  
## <a name="how-to-use-this-service-description"></a>Cómo utilizar esta descripción del servicio

La Office 365 de servicio de US Government está diseñada para servir como una superposición a la descripción general Office 365 servicio. Define los compromisos y diferencias únicos en comparación con Office 365 ofertas empresariales.
  
## <a name="compliance"></a>Cumplimiento

GCC High y DoD cumplen los requisitos de cumplimiento para las siguientes certificaciones y acreditaciones: 
  
- El Programa federal de administración de riesgos y autorización en FedRAMP High, incluidos los controles de seguridad y las mejoras de control, tal como se describe en la Publicación especial 800-53 del Instituto Nacional de Estándares y Tecnología (NIST).
    
- Controles de seguridad y mejoras de los controles para la Guía de requisitos de seguridad (SRG) sobre informática en la nube del Departamento de Defensa de Estados Unidos para la información hasta el nivel de impacto 5 (L5).
    
Los suscriptores del Departamento de Defensa Office 365 recibirán servicios proporcionados desde el entorno exclusivo de DOD que cumple con DOD SRG L5. Los suscriptores que no son del Departamento de Defensa recibirán servicios del entorno de defensa del gobierno de Estados Unidos que se evalúa en L5, pero usa la segmentación L4.
  
## <a name="background-screening"></a>Proyección en segundo plano

Office 365 personal no tiene acceso permanente a GCC producción de alta y doD. Cualquier personal que solicite la elevación de permisos temporales que conceda acceso al contenido del cliente debe haber pasado primero las siguientes comprobaciones en segundo plano.<br><br>
  
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

<sup>1</sup> Solo se aplica al personal con acceso temporal o permanente al contenido del cliente hospedado en Office 365 nubes de GCC-High o DOD de Estados Unidos.
## <a name="feature-nuances-based-on-compliant-cloud-architecture"></a>Matices de características basados en la arquitectura de nube compatible

Las suscripciones en los entornos GCC High y DoD incluyen las características Exchange Online, SharePoint y Skype Empresarial. Dada la mayor certificación y acreditación de la infraestructura, existen algunas diferencias de características entre las ofertas de Office 365 comerciales generales y las disponibles en GCC High y DoD.
  
### <a name="exchange-online"></a>Exchange Online

 Exchange Online compatibilidad de mensajería unificada para **IP-PBX** local: la compatibilidad para integrar sistemas IP-PBX locales con la mensajería unificada Exchange Online no se admite en las suscripciones GCC High y DoD. 
  
### <a name="file-sharing"></a>Uso compartido de archivos

Los usuarios tienen varias opciones para compartir archivos y carpetas en SharePoint y OneDrive. Todas las opciones están disponibles en los entornos GCC High y DoD. Para obtener más información acerca de cómo administrar estas opciones, vea [Administrar la configuración de uso compartido.](/sharepoint/turn-external-sharing-on-or-off) Los usuarios de GCC-High podrán compartir solo con otras organizaciones en GCC-High. Además, no se admiten GCC direcciones de correo electrónico secundarias adjuntas a perfiles de usuario y no permitirán el envío de mensajes de correo electrónico de alerta. Por ejemplo, al usuario local A se le asigna una dirección de correo electrónico de Gmail y, a continuación, se sincroniza con una organización de Azure GCC High. El usuario A navega a una biblioteca y crea una alerta para cualquier cambio. La alerta no se enviará a la dirección de Gmail.

> [!NOTE]
> Los usuarios de GCC-High actualmente no pueden compartir con usuarios de organizaciones no GCC High.

[Las solicitudes de](https://support.office.com/article/f54aa7f8-2589-4421-b351-d415fc3b83af) archivo no están disponibles para Office 365 Administración Pública.

### <a name="skype-for-business-online"></a>Skype Empresarial Online

 **Llamadas RTC &amp;** Conferencia RTC: debido al requisito de usar la red telefónica conmutada (RTC) para servicios orientados a telefonía, los servicios de conferencia RTC de llamadas RTC actualmente no están disponibles en GCC High y &amp; DoD.

### <a name="microsoft-teams"></a>Microsoft Teams

**Sistema telefónico y audioconferencia (a** través del enrutamiento directo): Sistema telefónico y audioconferencia para entornos GCC High y DoD se entregan a través del enrutamiento directo. Para obtener más información, vea la documentación del nivel de servicio aquí:

- [Sistema telefónico a través del enrutamiento directo](/microsoftteams/here-s-what-you-get-with-phone-system)
- [Audioconferencia con enrutamiento directo para GCC High y DoD](/microsoftteams/audio-conferencing-with-direct-routing-for-gcch-and-dod)

### <a name="identity"></a>Identity

Multi-Factor Authentication con un modelo de identidad federado permite el uso de tarjetas PIV y CAC.
  
### <a name="yammer"></a>Yammer

Yammer para empresas no está disponible en los entornos GCC High y DoD.
  
## <a name="customer-support"></a>Asistencia al cliente

Microsoft le recuerda que no comparta ninguna información controlada, confidencial o confidencial con el personal de soporte técnico como parte de su incidente de soporte técnico cuando use Office 365 GCC High/DOD, al menos hasta que confirme la autorización del agente de soporte técnico para ver o acceder a dichos datos.

Microsoft se compromete a proteger su [privacidad](https://privacy.microsoft.com/privacystatement)). Sin embargo, Office 365 GCC soporte técnico alto o doD no se incluye en el límite de acreditación del servicio y no proporciona garantías de cumplimiento de fedramp, dod srg, itar, irs 1075 o CJIS.