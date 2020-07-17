---
title: Exchange Online para entornos gubernamentales de Estados Unidos
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: En este artículo se proporciona información general sobre las diferencias de características entre la nube del gobierno de Estados Unidos y la nube comercial, tal como se muestra en la descripción del servicio Exchange Online.
ms.openlocfilehash: 5081dbdb563a9047fbf6759fc7413584408d56b4
ms.sourcegitcommit: c04cc8422d648df216d6c4f8b869736c97fc861f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/16/2020
ms.locfileid: "45154418"
---
# <a name="exchange-online-for-us-government-environments"></a>Exchange Online para entornos gubernamentales de Estados Unidos

En este artículo se proporciona información general sobre las diferencias de características entre la nube del gobierno de Estados Unidos y la nube comercial, tal como se muestra en la [Descripción del servicio Exchange Online](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-service-description). Exchange Online está disponible para los entornos de la nube de la comunidad de administración pública (GCC), GCC High y Department of Defense (DoD).

Para obtener más información acerca de la nube gubernamental, incluida la idoneidad y la compra, consulte [Microsoft 365 Government: How to Buy](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy). Para comparar los planes de Office 365 administración pública, vea [office 365 planes gubernamentales](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements).

Para obtener información sobre los puntos de conexión necesarios al administrar la conectividad de red, vea los puntos de conexión de [office 365 U.s. Government GCC GCC High endpoints](https://docs.microsoft.com/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business)   o [Office 365 u.s. Government DoD](https://docs.microsoft.com/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business).

Además de disfrutar de las características y capacidades de Office 365, las organizaciones se benefician de las siguientes características exclusivas de los entornos de la nube del gobierno de Estados Unidos:

- El contenido del cliente de la organización se separa lógicamente del contenido del cliente en los servicios comerciales de Office 365.

- El contenido del cliente de la organización se almacena en reposo dentro de los Estados Unidos.

- El acceso al contenido del cliente de la organización está restringido a personal específico de Microsoft.

- Los entornos de nube de gobierno cumplen con las certificaciones y acreditaciones que a menudo requieren los clientes del sector público de los Estados Unidos.

Nuestra intención general es ofrecer todas las características y funciones comerciales de Exchange en el entorno de nube de administración pública. Dicho esto, algunas características no están disponibles debido a los requisitos de los clientes de la nube de administración pública. Otras características están llegando a los entornos gubernamentales, pero aún no están disponibles. Consulte las siguientes secciones para obtener información sobre la disponibilidad de características en los entornos de nube de administración pública.

## <a name="exchange-online-features"></a>Características de Exchange Online 

En la tabla siguiente se indica si las características de Exchange Online especificadas están disponibles en los entornos GCC, GCC High y DoD. Cuando hay matices sobre la declaración de soporte (o la falta), se proporciona contexto adicional.

|**Área de característica**|**GCC**|**GCC High**|**Requisito**|**Consideraciones clave**|
|:-----|:-----|:-----|:-----|:-----|
|**[Planificación e implementación](../../exchange-online-service-description/planning-and-deployment.md)**|||||
|Admite implementación híbrida|Sí|Sí|Sí|Para coexistir con Exchange Server local, Microsoft requiere instalar al menos un servidor de acceso de cliente de Exchange Server 2013 (o Exchange Server 2016). Exchange Server 2010 y versiones anteriores no son compatibles.|
|Admite migración IMAP|Sí|Sí|Sí||
|Admite la migración total|Sí|Sí|Sí||
|Admite migración preconfigurada|Sí|Sí|Sí|La migración de GSuite no es compatible con GCC High y DoD. Para obtener más información, vea <a href="https://docs.microsoft.com/exchange/mailbox-migration/perform-g-suite-migration">realizar una migración de GSuite</a>.|
|**[Permisos](../../exchange-online-service-description/permissions.md)**|**GCC**|**GCC High**|**Requisito**|**Consideraciones clave**|
|Permisos basados en roles|Sí|Sí|Sí||
|Grupos de funciones|Sí|Sí|Sí||
|Directivas de asignación de funciones|Sí|Sí|Sí||
|**[Regulación de mensajes y cumplimiento](../../exchange-online-service-description/message-policy-and-compliance.md)**|**GCC**|**GCC High**|**Requisito**|**Consideraciones clave**|
|Archivado de buzones basados en Exchange Online|Sí|Sí|Sí||
|Archivado basado en nube de buzones locales|Sí|Sí|Sí||
|Messaging Records Management (MRM) |Sí|Sí|Sí||
|Directivas, etiquetas y etiquetas de retención manuales |Sí|Sí|Sí||
|Cifrado de datos en reposo (BitLocker)|Sí|Sí|Sí||
|IRM con Azure Information Protection|Sí|Sí|Sí|Para obtener más información acerca de las limitaciones de AIP en GCC High y DoD, consulte <a href="https://docs.microsoft.com/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description">Azure Information Protection Premium Government Service Description</a>.<br><br>Azure Information Protection no se incluye en G1/F3, pero puede adquirirse como complemento independiente y habilitará las características de Information Rights Management (IRM) compatibles. Algunas características de Azure Information Protection requieren una suscripción a Office 365 ProPlus, que no se incluye con Office 365 el gobierno G1 o Office 365 Government F3.|
|IRM con Windows Server AD RMS|Sí|Sí|Sí|Windows Server AD RMS es un servidor local que debe adquirirse y administrarse por separado para habilitar las características de IRM admitidas.|
|Cifrado de mensajes de Office 365|Sí|Sí|Sí|Vea [office 365 el comportamiento de cifrado de mensajes en el límite alto/DoD de GCC](#office-365-message-encryptionbehavior-across-gcc-highdod-boundary) en este artículo y <a href="https://docs.microsoft.com/microsoft-365/compliance/ome-version-comparison?view=o365-worldwide#unique-characteristics-of-office-365-message-encryption-in-a-gcc-high-deployment">características únicas de Office 365 Message Encryption en una implementación alta de GCC</a>, que documenta el comportamiento del cifrado de mensajes de Office 365 al enviar mensajes entre los usuarios de GCC High/DoD y los usuarios de alto/DoD no de GCC.|
|Clave de cliente|Sí|Sí|Sí|Requiere el plan de servicio G5.|
|S/MIME|Sí|Sí|Sí||
|Conservación local y retención por juicio|Sí|Sí|Sí|Requiere el plan de servicio G3 o G5.|
|Exhibición de documentos electrónicos en contexto|Sí|Sí|Sí||
|Reglas de flujo de correo|Sí|Sí|Sí||
|Prevención de pérdida de datos|Sí|Sí|Sí|Requiere el plan de servicio G3 o G5.|
|Registro en diario|Sí|Sí|Sí||
|**[Protección contra correo electrónico no deseado y antimalware](../../exchange-online-service-description/anti-spam-and-anti-malware-protection.md)**|**GCC**|**GCC High**|**Requisito**|**Consideraciones clave**|
|Protección contra correo no deseado integrada|Sí|Sí|Sí||
|Customize anti-spam policies|Sí|Sí|Sí||
|Protección contra malware integrada|Sí|Sí|Sí||
|Customize anti-malware policies|Sí|Sí|Sí||
|Cuarentena: gestión de administradores|Sí|Sí|Sí||
|Cuarentena: autoadministración de usuarios finales|Sí|Sí|Sí||
|Protección contra amenazas avanzada|Sí|Sí|Sí|Requiere el plan de servicio G5 (o la compra del complemento).<br><br>La suplantación de identidad (phishing) para la suplantación de usuarios y dominios y la inteligencia de suplantación todavía no están disponibles en GCC High y DoD.|
|**[Flujo de correo](../../exchange-online-service-description/mail-flow.md)**|**GCC**|**GCC High**|**Requisito**|**Consideraciones clave**|
|Enrutamiento personalizado de correo saliente|Sí|Sí|Sí||
|Secure messaging with a trusted partner|Sí|Sí|Sí||
|Conditional mail routing|Sí|Sí|Sí||
|Adición de un Partner a una lista segura de entrada|Sí|Sí|Sí||
|Enrutamiento de correo híbrido|Sí|Sí|Sí||
|**[Destinatarios](../../exchange-online-service-description/recipients.md)**|**GCC**|**GCC High**|**Requisito**|**Consideraciones clave**|
|Alertas de capacidad|Sí|Sí|Sí||
|Otros correos|Sí|Sí|Sí||
|MailTips|Sí|Sí|Sí||
|Acceso delegado|Sí|Sí|Sí||
|Reglas de la bandeja de entrada|Sí|Sí|Sí||
|Cuentas conectadas|Sí|No|No|Esta característica no es compatible con GCC High o DoD debido a restricciones en las conexiones salientes a servicios de terceros. Para obtener más información acerca de las características afectadas, vea [conectividad con servicios de terceros](#connectivity-with-third-party-services) en este artículo.|
|Buzones de correo inactivos|Sí|Sí|Sí|Requiere el plan de servicio G3 o G5.|
|Libreta de direcciones sin conexión|Sí|Sí|Sí||
|Directivas de la libreta de direcciones|Sí|Sí|Sí||
|Libreta de direcciones jerárquica|Sí|Sí|Sí||
|Listas de direcciones y lista global de direcciones|Sí|Sí|Sí||
|Grupos de Office 365|Sí|Sí|Sí|El acceso de invitado a Office 365 grupos no se admite en los entornos altos y DoD de GCC. Para obtener más información, consulte <a href="https://docs.microsoft.com/azure/azure-government/documentation-government-services-securityandidentity">Azure Government Security + Identity</a>.|
|Grupos de distribución|Sí|Sí|Sí||
|Contactos externos (globales)|Sí|Sí|Sí|Sujeto a las limitaciones de colaboración de la relación de organización en los entornos de GCC altos y DoD. |
|Vinculación de contactos con redes sociales|Sí|No|No|Esta característica no es compatible con GCC High o DoD.|
|Buzones de recursos|Sí|Sí|Sí||
|Administración de la sala de conferencias|Sí|Sí|Sí||
|Respuestas de fuera de la oficina|Sí|Sí|Sí||
|Uso compartido de calendarios de Internet|Sí|No|No|En GCC High, la publicación/uso compartido de calendarios de Internet funciona para las conexiones entrantes con los calendarios compartidos por los usuarios de GCC High, pero no para los usuarios de GCC High que se conectan salientes a un calendario compartido fuera de GCC High.<br><br>En DoD: el uso compartido de calendarios de Internet no se admite debido a los requisitos para la inscripción entrante y saliente permite incluir en ese entorno.|
|**[Herramientas de resolución de problemas y características de informes](../../exchange-online-service-description/reporting-features-and-troubleshooting-tools.md)**|**GCC**|**GCC High**|**Requisito**|**Consideraciones clave**|
|Informes del centro de administración de Microsoft 365|Sí|Sí|No|Informes no disponibles para DoD. Consulte la sección <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">características</a> de la plataforma de la descripción del servicio Office 365 US Government para las actualizaciones/disponibilidad actual.|
|Informes de servicios Web|Sí|Sí|No|Informes no disponibles para DoD. Consulte la sección <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">características</a> de la plataforma de la descripción del servicio Office 365 US Government para las actualizaciones/disponibilidad actual.|
|Message trace|Sí|Sí|Sí||
|Informes de auditoría|Sí|Sí|No|Informes no disponibles para DoD. Consulte la sección <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">características</a> de la plataforma de la descripción del servicio Office 365 US Government para las actualizaciones/disponibilidad actual.|
|Informes de mensajería unificada|Sí|No|No||
|**[Uso compartido y colaboración](../../exchange-online-service-description/sharing-and-collaboration.md)**|**GCC**|**GCC High**|**Requisito**|**Consideraciones clave**|
|Uso compartido federado (incluida la publicación de calendario)|Sí|Sí|Sí|Existen limitaciones en GCC High y DoD. Vea [Federación](#freebusy-federation) de disponibilidad en este artículo.|
|Buzones de sitio|Sí|Sí|Sí||
|Carpetas públicas|Sí|Sí|Sí||
|**[Clientes y dispositivos móviles](../../exchange-online-service-description/clients-and-mobile-devices.md)**|**GCC**|**GCC High**|**Requisito**|**Consideraciones clave**|
|Outlook para Windows|Sí|Sí|Sí|Para cumplir con los requisitos de cumplimiento de GCC High y DoD, debe ejecutar al menos la versión 1803 de Office 365 ProPlus. Office 365 ProPlus no se incluye con G1 o F3.|
|Outlook en la Web|Sí|Sí|Sí||
|Outlook para Mac|Sí|Sí|Sí|Para cumplir con los requisitos de cumplimiento de GCC High y DoD, debe ejecutar al menos la versión 1803 de Office 365 ProPlus. Office 365 ProPlus no se incluye con G1 o F3.|
|Outlook para iOS y Android|Sí|Sí|Sí||
|Exchange ActiveSync|Sí|Sí|Sí||
|Basic Mobility and Security para Microsoft 365|Sí|No|No||
|POP e IMAP|Sí|Sí|Sí||
|SMTP|Sí|Sí|Sí||
|Compatibilidad con la aplicación EWS|Sí|Sí|Sí||
|**[Servicios de mensajes de voz](../../exchange-online-service-description/voice-message-services.md)**|**GCC**|**GCC High**|**Requisito**|**Consideraciones clave**|
|Correo de voz|No|No|No|No se admite la integración de sistemas de IP-PBX local con mensajería unificada de Exchange Online.|
|Integración entre correo de voz y FAX de terceros|No|No|No|No se admite la integración de sistemas de IP-PBX local con mensajería unificada de Exchange Online.|
|Interoperabilidad del correo de voz de terceros|No|No|No|No se admite la integración de sistemas de IP-PBX local con mensajería unificada de Exchange Online.|
|Integración de Skype empresarial|Sí|Sí|Sí||
|**[Alta disponibilidad y continuidad empresarial](../../exchange-online-service-description/high-availability-and-business-continuity.md)**|**GCC**|**GCC High**|**Requisito**|**Consideraciones clave**|
|Replicación de buzones en centros de recursos|Sí|Sí|Sí||
|Recuperación de buzones eliminados|Sí|Sí|Sí||
|Recuperación de elementos eliminados|Sí|Sí|Sí||
|Recuperación de elementos individuales|Sí|Sí|Sí||
|**[Interoperabilidad, conectividad y compatibilidad](../../exchange-online-service-description/interoperability-connectivity-and-compatibility.md)**|**GCC**|**GCC High**|**Requisito**|**Consideraciones clave**|
|Presencia en OWA y Outlook|Sí|Sí|Sí||
|Interoperabilidad de SharePoint|Sí|Sí|Sí||
|Compatibilidad con la conectividad de EWS|Sí|Sí|Sí||
|Compatibilidad con retransmisión SMTP|Sí|Sí|Sí||
|**[Administración y configuración de Exchange Online](../../exchange-online-service-description/exchange-online-setup-and-administration.md)**|**GCC**|**GCC High**|**Requisito**|**Consideraciones clave**|
|Acceso al portal de Microsoft Office 365|Sí|Sí|No|Informes no disponibles para DoD. Consulte la sección <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">características</a> de la plataforma de la descripción del servicio Office 365 US Government para las actualizaciones/disponibilidad actual.|
|Acceso al centro de administración de Microsoft 365|Sí|Sí|No|Informes no disponibles para DoD. Consulte la sección <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">características</a> de la plataforma de la descripción del servicio Office 365 US Government para las actualizaciones/disponibilidad actual.|
|Acceso al Centro de administración de Exchange|Sí|Sí|Sí||
|Acceso a Windows PowerShell remoto|Sí|Sí|Sí||
|Directivas de ActiveSync para dispositivos móviles|Sí|Sí|Sí||
|Informes de uso|Sí|Sí|No|Informes no disponibles para DoD. Consulte la sección <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">características</a> de la plataforma de la descripción del servicio Office 365 US Government para las actualizaciones/disponibilidad actual.|
|**[Extensión de la personalización del servicio, los complementos y los recursos](../../exchange-online-service-description/exchange-online-service-description.md)**|**GCC**|**GCC High**|**Requisito**|**Consideraciones clave**|
|Complementos de Outlook y MAPI de Outlook|Sí|Sí|Sí|Solo algunos complementos de OWA y Outlook están disponibles en GCC High y DoD. Consulte [Complementos en Outlook y Outlook Web App](#add-insin-outlook-and-outlook-web-app) en este artículo.|

## <a name="feature-nuances-within-gcc-high-and-dod-environment"></a>Características de matices de GCC en un entorno alto y DoD de GCC

### <a name="connectivity-with-third-party-services"></a>Conectividad con los servicios de terceros  

Los entornos tanto altos como DoD de GCC son entornos restringidos que requieren la aprobación y configuración explícita de las conexiones salientes. Además, Microsoft no puede acomodar solicitudes para permitir el acceso saliente desde estos entornos a servicios en la nube comercial (Commercial Office 365, Google GSuite, servicios Web de Amazon, etc.).     

Debido a estas restricciones, las características que se basan en esta conectividad saliente de los entornos altos/DoD de GCC no suelen ser compatibles, como: 

- Cuentas conectadas &mdash; los usuarios no pueden agregar ni sincronizar cuentas (Google, POP/IMAP, etc.). 

- Compatibilidad con proveedores de almacenamiento de archivos de terceros &mdash; solo se puede tener acceso a la cuenta de OneDrive para la empresa del usuario *dentro de GCC/DoD*   desde dentro de los diversos clientes de Outlook con el propósito de adjuntar o compartir archivos. No se pueden agregar cuentas de almacenamiento de terceros (Dropbox, Box, Google Drive). 

- Conectividad con redes sociales, como Facebook o LinkedIn. 

### <a name="azure-active-directoryb2b-collaboration"></a>Colaboración B2B de Azure Active Directory 

La colaboración B2B de Azure Active Directory actualmente es compatible solo entre organizaciones que están dentro de la nube de Azure US Government y que ambos admiten la colaboración B2B.

Además, los usuarios de B2B como invitados en los grupos de Office 365 no se admiten en los entornos de GCC altos y DoD. 

Para obtener más información y las actualizaciones más recientes, consulte [Azure Government Security + Identity](https://docs.microsoft.com/azure/azure-government/documentation-government-services-securityandidentity). 

### <a name="office-365-message-encryptionbehavior-across-gcc-highdod-boundary"></a>Comportamiento de cifrado de mensajes de Office 365 en límite alto/DoD de GCC 

Si va a usar el cifrado de mensajes de Office 365 en un entorno de GCC High, tenga en cuenta estas características únicas sobre la experiencia de los destinatarios:  

- Al enviar correo electrónico cifrado desde GCC High o DoD a destinatarios en el mismo entorno:
    
    - Los remitentes pueden cifrar mensajes de correo electrónico manualmente en Outlook para PC y Mac y Outlook en la web, o las organizaciones pueden configurar una directiva para cifrar correos electrónicos con las reglas de flujo de correo de Exchange. 
    
    - Los destinatarios incluidos en GCC High/DoD reciben la misma experiencia de lectura en línea en Outlook para PC y Mac y Outlook en la web como todos los demás usuarios de Office 365. 

<!-- end list -->

- Al enviar correo electrónico cifrado desde GCC High o DoD a destinatarios fuera de ese entorno (incluido GCC y Commercial):
    
    - Los remitentes que se encuentran en GCC High/DoD pueden enviar correo electrónico cifrado fuera del límite alto/DoD de GCC. 
    
    - Todos los destinatarios externos a GCC/DoD, incluidos los usuarios comerciales de Office 365, los usuarios de Outlook.com y otros usuarios de otros proveedores de correo electrónico, reciben un correo de contenedor. Este correo de contenedor redirige al destinatario al portal de OME donde el destinatario puede leer y responder al mensaje. 

Para obtener más información y las actualizaciones más recientes, vea [Comparar versiones de OME](https://docs.microsoft.com/microsoft-365/compliance/ome-version-comparison?view=o365-worldwide).

### <a name="freebusy-federation"></a>Federación de disponibilidad

El uso compartido federado, incluida la información de disponibilidad, está actualmente sujeto a varias limitaciones importantes en los entornos altos y DoD de GCC.

En el entorno de GCC High:

- La confianza de Federación (incluido el uso compartido de disponibilidad bidireccional) se admite entre los inquilinos de GCC High y a través de la coexistencia híbrida (Exchange 2013 o posterior).

- No se admite el uso compartido federado entre los inquilinos en GCC High y GCC u Office 365 Commercial. No se permiten las conexiones salientes desde el entorno alto de GCC a las nubes comerciales (incluido GCC y Office 365 Commercial) en este momento. Como resultado, los usuarios de GCC High no pueden realizar la solicitud saliente requerida en GCC/Commercial para acceder a la información de calendario compartida.

En el entorno de DoD:

  - Actualmente, la confianza de Federación (incluido el uso compartido de información de disponibilidad) solo se admite entre los inquilinos del entorno DoD. No se admite entre los inquilinos de DoD y GCC o los inquilinos comerciales.

### <a name="client-configuration"></a>Configuración de clientes 

Los pasos adicionales están relacionados con la implementación y configuración de Office ProPlus (incluido Outlook). Para obtener una descripción detallada de estos pasos, consulte [Guidance for Deploying Microsoft 365 apps for Enterprise in an GCC High or DoD Environment ](https://docs.microsoft.com/deployoffice/deploy-microsoft-365-apps-gcc-high-dod).

Outlook para iOS y Android también está disponible para los entornos de GCC altos y DoD. Para obtener más información acerca de las limitaciones y la administración de características en estos entornos, consulte [uso de Outlook para iOS y Android en la nube de la comunidad de administración pública](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud).

### <a name="add-insin-outlook-and-outlook-web-app"></a>Complementos en Outlook y Outlook Web App  

Solo algunos complementos de OWA y Outlook están disponibles en GCC High y DoD. Mis plantillas y las reuniones sugeridas están disponibles y se espera que funcionen. Solo se admiten los cinco complementos predeterminados de OWA. La integración con aplicaciones de terceros es posible, pero estas integraciones no están cubiertas por las promesas de cumplimiento de Microsoft para GCC High o DoD. Los clientes deben familiarizarse con prácticas de administración de datos de terceros y las promesas de cumplimiento antes de configurar el complemento para su organización.
