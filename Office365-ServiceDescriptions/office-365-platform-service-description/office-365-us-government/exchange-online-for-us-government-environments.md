---
title: Exchange Online entornos gubernamentales de Estados Unidos
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: En este artículo se proporciona información general sobre las diferencias de características entre la nube del gobierno de Estados Unidos y la nube comercial, tal como se muestra en la Exchange Online de servicio.
ms.openlocfilehash: 2845e26e40552f364d2f8f6a0ec2746d35e13330
ms.sourcegitcommit: 0ef110d0f0a11c1943560373e0f022364053640c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/28/2021
ms.locfileid: "59986136"
---
# <a name="exchange-online-for-us-government-environments"></a>Exchange Online entornos gubernamentales de Estados Unidos

En este artículo se proporciona información general sobre las diferencias de características entre la nube del gobierno de Estados Unidos y la nube [comercial,](../../exchange-online-service-description/exchange-online-service-description.md)tal como se muestra en Exchange Online descripción del servicio . Exchange Online está disponible para los entornos Government Community Cloud (GCC), GCC High y Department of Defense (DoD).

Para obtener más información acerca de la nube gubernamental, incluida la elegibilidad y la compra, vea [Microsoft 365 Government - how to buy](./microsoft-365-government-how-to-buy.md). Para comparar Office 365 Administración Pública planes, [vea Office 365 Administración Pública planes](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements).

Para obtener información sobre los puntos de conexión necesarios al administrar la conectividad de red, vea Office 365 [U.S. Government GCC High endpoints](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) or [Office 365 U.S. Government DoD endpoints](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business).

Además de disfrutar de las características y capacidades de Office 365, las organizaciones se benefician de las siguientes características exclusivas de los entornos en la nube del gobierno de Estados Unidos:

- El contenido de cliente de la organización se separa lógicamente del contenido del cliente en los servicios Office 365 comerciales.

- El contenido del cliente de su organización se almacena en reposo dentro de los Estados Unidos.

- El acceso al contenido del cliente de la organización está restringido a personal específico de Microsoft.

- Los entornos de nube gubernamentales cumplen con las certificaciones y las acreditaciones que suelen ser necesarias para los clientes del sector público de Estados Unidos.

Nuestra intención general es ofrecer todas las Exchange y funcionalidades comerciales al entorno de nube del gobierno. Dicho esto, algunas características no están disponibles debido a los requisitos de los clientes de la nube gubernamental. Otras características están llegando a los entornos gubernamentales, pero aún no están disponibles. Consulte las secciones siguientes para obtener información sobre la disponibilidad de características en los entornos de nube gubernamentales.

## <a name="exchange-online-features"></a>Características de Exchange Online 

En la tabla siguiente se describe si las características Exchange Online están disponibles en los entornos GCC, GCC High y DoD. Cuando hay matices con respecto a la instrucción de soporte (o falta de ella), se proporciona un contexto adicional.<br><br>

| Característica | GCC | GCC High | DoD | Consideraciones clave |
|:-----|:-----|:-----|:-----|:-----|
|**[Planificación e implementación](../../exchange-online-service-description/planning-and-deployment.md)**|||||
|Admite implementación híbrida|Sí|Sí|Sí|Para la coexistencia Exchange Server local, Microsoft requiere instalar al menos Exchange Server servidor de acceso de cliente de 2013 (o Exchange Server 2016). Exchange Server 2010 y versiones anteriores no son compatibles.|
|Admite migración IMAP|Sí|Sí|Sí||
|Admite la migración total|Sí|Sí|Sí||
|Admite migración preconfigurada|Sí|Sí|Sí|La migración de GSuite no se admite GCC High y DoD. Para obtener más información, <a href="/exchange/mailbox-migration/perform-g-suite-migration">vea Perform a GSuite migration</a>.|
|**[Permisos](../../exchange-online-service-description/permissions.md)**|**GCC**|**GCC High**|**DoD**|**Consideraciones clave**|
|Permisos basados en roles|Sí|Sí|Sí||
|Grupos de funciones|Sí|Sí|Sí||
|Directivas de asignación de funciones|Sí|Sí|Sí||
|**[Regulación de mensajes y cumplimiento](../../exchange-online-service-description/message-policy-and-compliance.md)**|**GCC**|**GCC High**|**DoD**|**Consideraciones clave**|
|Archivado de buzones basados en Exchange Online|Sí|Sí|Sí||
|Archivado basado en nube de buzones locales|Sí|Sí|Sí||
|Messaging Records Management (MRM) |Sí|Sí|Sí||
|Directivas de retención manual, etiquetas y etiquetas |Sí|Sí|Sí||
|Cifrado de datos en reposo (BitLocker)|Sí|Sí|Sí||
|IRM con Azure Information Protection|Sí|Sí|Sí|Para obtener más información acerca de las limitaciones de AIP en GCC High y DoD, vea <a href="/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description">Azure Information Protection Premium Government Service Description</a>.<br><br>Azure Information Protection no se incluye en G1/F3, pero se puede comprar como un complemento independiente y habilitará las características compatibles de Information Rights Management (IRM). Algunas características de Azure Information Protection requieren una suscripción a Office 365 ProPlus, que no se incluye con Office 365 Administración Pública G1 o Office 365 Administración Pública F3.|
|IRM con Windows Server AD RMS|Sí|Sí|Sí|Windows Server AD RMS es un servidor local que debe adquirirse y administrarse por separado para habilitar las características de IRM compatibles.|
|Cifrado de mensajes de Office 365|Sí|Sí|Sí|Vea Cifrado de mensajes de Office 365 comportamiento en GCC límite de [alto/doD](#office-365-message-encryptionbehavior-across-gcc-highdod-boundary) en este artículo y Características únicas de Cifrado de mensajes de Office 365 en una implementación de <a href="/microsoft-365/compliance/ome-version-comparison#unique-characteristics-of-office-365-message-encryption-in-a-gcc-high-deployment">GCC High</a>, que documenta los matices de comportamiento de Cifrado de mensajes de Office 365 al enviar mensajes entre GCC high/doD y usuarios no GCC high/doD.|
|Clave de cliente|Sí|Sí|Sí|Requiere un plan de servicio G5.|
|S/MIME|Sí|Sí|Sí||
|Conservación local y retención por juicio|Sí|Sí|Sí|Requiere un plan de servicio G3 o G5.|
|Exhibición de documentos electrónicos en contexto|Sí|Sí|Sí||
|Reglas de flujo de correo|Sí|Sí|Sí||
|Prevención de pérdida de datos|Sí|Sí|Sí|Requiere un plan de servicio G3 o G5.|
|Registro en diario|Sí|Sí|Sí||
|**[Protección contra correo no deseado y malware](../../exchange-online-service-description/anti-spam-and-anti-malware-protection.md)**|**GCC**|**GCC High**|**DoD**|**Consideraciones clave**|
|Protección contra correo no deseado integrada|Sí|Sí|Sí||
|Customize anti-spam policies|Sí|Sí|Sí||
|Protección contra malware integrada|Sí|Sí|Sí||
|Customize anti-malware policies|Sí|Sí|Sí||
|Cuarentena: gestión de administradores|Sí|Sí|Sí||
|Cuarentena: autoadministración de usuarios finales|Sí|Sí|Sí||
|Microsoft Defender para Office 365|Sí|Sí|Sí|Requiere plan de servicio G5 (o compra de complemento).<br><br>La suplantación de identidad de usuarios y dominios y la suplantación de identidad aún no están disponibles en GCC High y DoD.|
|**[Flujo de correo](../../exchange-online-service-description/mail-flow.md)**|**GCC**|**GCC High**|**DoD**|**Consideraciones clave**|
|Enrutamiento personalizado del correo saliente|Sí|Sí|Sí||
|Secure messaging with a trusted partner|Sí|Sí|Sí||
|Conditional mail routing|Sí|Sí|Sí||
|Agregar un partner a una lista segura de entrada|Sí|Sí|Sí||
|Enrutamiento de correo híbrido|Sí|Sí|Sí||
|**[Destinatarios](../../exchange-online-service-description/recipients.md)**|**GCC**|**GCC High**|**DoD**|**Consideraciones clave**|
|Alertas de capacidad|Sí|Sí|Sí||
|Otros correos|Sí|Sí|Sí||
|MailTips|Sí|Sí|Sí||
|Acceso delegado|Sí|Sí|Sí||
|Reglas de la bandeja de entrada|Sí|Sí|Sí||
|Cuentas conectadas|Sí|No|No|Esta característica no se admite en GCC High o DoD debido a restricciones en las conexiones salientes a servicios de terceros. Para obtener más información acerca de las características afectadas, vea [Conectividad con servicios de terceros](#connectivity-with-third-party-services) en este artículo.|
|Buzones de correo inactivos|Sí|Sí|Sí|Requiere un plan de servicio G3 o G5.|
|Libreta de direcciones sin conexión|Sí|Sí|Sí||
|Directivas de la libreta de direcciones|Sí|Sí|Sí||
|Libreta de direcciones jerárquica|Sí|Sí|Sí||
|Listas de direcciones y lista global de direcciones|Sí|Sí|Sí||
|Grupos de Office 365|Sí|Sí|Sí|El acceso de invitado a Office 365 no se admite en GCC entornos High y DoD. Para obtener más información, <a href="/azure/azure-government/documentation-government-services-securityandidentity">vea Azure Government Security + Identity</a>.|
|Grupos de distribución|Sí|Sí|Sí||
|Contactos externos (globales)|Sí|Sí|Sí|Sujeto a limitaciones de colaboración de relaciones de organización GCC entornos High y DoD. |
|Vinculación de contactos con redes sociales|Sí|No|No|Esta característica no se admite en GCC High o DoD.|
|Buzones de recursos|Sí|Sí|Sí||
|Administración de la sala de conferencias|Sí|Sí|Sí||
|Respuestas de fuera de la oficina|Sí|Sí|Sí||
|Uso compartido de calendario de Internet|Sí|No|No|En GCC High, la publicación y el uso compartido de calendarios de Internet funciona para la conexión entrante a calendarios compartidos por usuarios de GCC High, pero no para usuarios de GCC High que conectan salientes a un calendario compartido fuera de GCC High.<br><br>En DoD–Internet Calendar sharing no se admite debido al requisito de la descripción de la descripción de la conexión entrante y saliente en ese entorno.|
|**[Herramientas de resolución de problemas y características de informes](../../exchange-online-service-description/reporting-features-and-troubleshooting-tools.md)**|**GCC**|**GCC High**|**DoD**|**Consideraciones clave**|
|Informes del Centro de administración de Microsoft 365|Sí|Sí|No|Informes no disponibles para DoD. Consulte la sección <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">características de la</a> plataforma de la Office 365 descripción del servicio us government para obtener actualizaciones/disponibilidad actual.|
|Informes de servicios web|Sí|Sí|No|Informes no disponibles para DoD. Consulte la sección <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">características de la</a> plataforma de la Office 365 descripción del servicio us government para obtener actualizaciones/disponibilidad actual.|
|Message trace|Sí|Sí|Sí||
|Informes de auditoría|Sí|Sí|No|Informes no disponibles para DoD. Consulte la sección <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">características de la</a> plataforma de la Office 365 descripción del servicio us government para obtener actualizaciones/disponibilidad actual.|
|Informes de mensajería unificada|Sí|No|No||
|**[Uso compartido y colaboración](../../exchange-online-service-description/sharing-and-collaboration.md)**|**GCC**|**GCC High**|**DoD**|**Consideraciones clave**|
|Uso compartido federado (incluida la publicación de calendario)|Sí|Sí|Sí|Existen limitaciones tanto en GCC High como en DoD. Vea [Federación de disponibilidad](#freebusy-federation) en este artículo.|
|Buzones de sitio|Sí|Sí|Sí||
|Carpetas públicas|Sí|Sí|Sí||
|**[Clientes y dispositivos móviles](../../exchange-online-service-description/clients-and-mobile-devices.md)**|**GCC**|**GCC High**|**DoD**|**Consideraciones clave**|
|To Do en la Web|Sí|No|No||
|Outlook para Windows|Sí|Sí|Sí|Para cumplir GCC de cumplimiento de alto y doD, debe ejecutar al menos la versión 1803 de Office 365 ProPlus. Office 365 ProPlus no se incluye con G1 o F3.|
|Outlook en la Web<sup>1</sup>|Sí|Sí|Sí||
|Outlook para Mac|Sí|Sí|Sí|Para cumplir GCC de cumplimiento de alto y doD, debe ejecutar al menos la versión 1803 de Office 365 ProPlus. Office 365 ProPlus no se incluye con G1 o F3.|
|Outlook para iOS y Android|Sí|Sí|Sí||
|Exchange ActiveSync|Sí|Sí|Sí||
|Movilidad básica y seguridad para Microsoft 365|Sí|No|No||
|POP e IMAP|Sí|Sí|Sí||
|SMTP|Sí|Sí|Sí||
|Compatibilidad con aplicaciones EWS<sup>2</sup>|Sí|Sí|Sí||
|**[Servicios de mensajes de voz](../../exchange-online-service-description/voice-message-services.md)**|**GCC**|**GCC High**|**DoD**|**Consideraciones clave**|
|Correo de voz|No|No|No|No se admite la integración de sistemas IP-PBX locales Exchange Online mensajería unificada.|
|Integración entre correo de voz y FAX de terceros|No|No|No|No se admite la integración de sistemas IP-PBX locales Exchange Online mensajería unificada.|
|Interoperabilidad del correo de voz de terceros|No|No|No|No se admite la integración de sistemas IP-PBX locales Exchange Online mensajería unificada.|
|Skype Empresarial integración|Sí|Sí|Sí||
|**[Alta disponibilidad y continuidad empresarial](../../exchange-online-service-description/high-availability-and-business-continuity.md)**|**GCC**|**GCC High**|**DoD**|**Consideraciones clave**|
|Replicación de buzones en centros de datos|Sí|Sí|Sí||
|Recuperación de buzones eliminados|Sí|Sí|Sí||
|Recuperación de elementos eliminados|Sí|Sí|Sí||
|Recuperación de elementos individuales|Sí|Sí|Sí||
|**[Interoperabilidad, conectividad y compatibilidad](../../exchange-online-service-description/interoperability-connectivity-and-compatibility.md)**|**GCC**|**GCC High**|**DoD**|**Consideraciones clave**|
|Presencia en OWA y Outlook|Sí|Sí|Sí||
|SharePoint interoperabilidad|Sí|Sí|Sí||
|Compatibilidad con conectividad EWS|Sí|Sí|Sí||
|Compatibilidad con retransmisión SMTP|Sí|Sí|Sí||
|**[Administración y configuración de Exchange Online](../../exchange-online-service-description/exchange-online-setup-and-administration.md)**|**GCC**|**GCC High**|**DoD**|**Consideraciones clave**|
|Acceso al portal de Microsoft Office 365|Sí|Sí|No|Informes no disponibles para DoD. Consulte la sección <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">características de la</a> plataforma de la Office 365 descripción del servicio us government para obtener actualizaciones/disponibilidad actual.|
|Centro de administración de Microsoft 365 acceso|Sí|Sí|No|Informes no disponibles para DoD. Consulte la sección <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">características de la</a> plataforma de la Office 365 descripción del servicio us government para obtener actualizaciones/disponibilidad actual.|
|Acceso al Centro de administración de Exchange|Sí|Sí|Sí||
|Acceso a Windows PowerShell remoto|Sí|Sí|Sí||
|Directivas de ActiveSync para dispositivos móviles|Sí|Sí|Sí||
|Informes de uso|Sí|Sí|No|Informes no disponibles para DoD. Consulte la sección <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">características de la</a> plataforma de la Office 365 descripción del servicio us government para obtener actualizaciones/disponibilidad actual.|
|**[Ampliación del servicio: personalización, complementos y recursos](../../exchange-online-service-description/exchange-online-service-description.md)**|**GCC**|**GCC High**|**DoD**|**Consideraciones clave**|
|Outlook complementos y Outlook MAPI|Sí|Sí|Sí|Solo algunos complementos de OWA y Outlook están disponibles en GCC High y DoD. Vea [Complementos en Outlook y Outlook Web App](#add-insin-outlook-and-outlook-web-app) en este artículo.|

<sup>1</sup> Outlook en la Web se puede usar en escenarios en los que Outlook para Windows no puede mostrar los mensajes protegidos de IRM debido a restricciones entre límites (escenarios GCC high /non-GCC high).</br>
<sup>2</sup> Solo se permite la salida a espacios de direcciones específicos que el cliente pueda demostrar que es el propietario, por lo que esto excluye los servicios de terceros y los amplios intervalos IP que usan los dispositivos móviles.

## <a name="feature-nuances-within-gcc-high-and-dod-environments"></a>Matices de características en GCC entornos high y DoD

### <a name="connectivity-with-third-party-services"></a>Conectividad con servicios de terceros  

Tanto GCC high como los entornos DoD son entornos restringidos que requieren aprobación explícita y configuración de conexiones salientes. Además, Microsoft no puede dar cabida a solicitudes para permitir el acceso saliente desde estos entornos a servicios comerciales en la nube (Commercial Office 365, Google GSuite, Amazon Web Services, entre otros).

Debido a estas restricciones, las características que dependen de esta conectividad saliente desde los entornos GCC high/doD generalmente no se admiten, incluidos:

- Cuentas conectadas: los usuarios no pueden agregar ni sincronizar cuentas (Google, POP/IMAP, entre otras).

- Compatibilidad con proveedores de almacenamiento de archivos de terceros: solo se puede acceder OneDrive para la Empresa la cuenta de OneDrive para la Empresa del usuario dentro de *GCC High/DoD* desde los distintos clientes de Outlook con el fin de adjuntar o compartir archivos. No se pueden agregar cuentas de almacenamiento de terceros (Dropbox, Box, Google Drive).

- Conectividad con redes sociales, como Facebook o LinkedIn.

### <a name="azure-active-directory-b2b-collaboration"></a>Azure Active Directory Colaboración B2B

Azure Active Directory Actualmente, la colaboración B2B solo se admite entre organizaciones que están dentro de la nube de Azure US Government y que admiten la colaboración B2B

Además, los usuarios B2B como invitados en Office 365 no se admiten en GCC entornos De alta y doD. 

Para obtener más información y las actualizaciones más recientes, [vea Azure Government Security + Identity](/azure/azure-government/documentation-government-services-securityandidentity).

### <a name="office-365-message-encryption-behavior-across-gcc-highdod-boundary"></a>Cifrado de mensajes de Office 365 comportamiento en GCC límite alto/doD

Si tiene previsto usar Cifrado de mensajes de Office 365 en un entorno GCC High, tenga en cuenta estas características únicas sobre la experiencia del destinatario:  

- Al enviar correo electrónico cifrado desde GCC High o DoD a destinatarios en el mismo entorno:
    
    - Los remitentes pueden cifrar manualmente los correos electrónicos en Outlook para PC y Mac y Outlook en la Web, o bien las organizaciones pueden configurar una directiva para cifrar correos electrónicos mediante Exchange reglas de flujo de correo.
    
    - Los destinatarios de GCC High/DoD reciben la misma experiencia de lectura en línea en Outlook para PC y Mac y Outlook en la Web que el resto de Office 365 usuarios.

<!-- end list -->

- Al enviar correo electrónico cifrado desde GCC High a destinatarios fuera de ese entorno (incluidos DoD, GCC y Commercial):

    - Los remitentes de GCC High pueden enviar correo electrónico cifrado fuera del límite GCC high.
    - Todos los destinatarios fuera de GCC High, incluidos los usuarios de doD, de Office 365 comerciales, de Outlook.com y otros usuarios de otros proveedores de correo electrónico, reciben un correo contenedor. Este correo contenedor redirige al destinatario al Portal de OME, donde el destinatario puede leer y responder a los mensajes.

Para obtener más información y las actualizaciones más recientes, vea [Comparar versiones de OME](/microsoft-365/compliance/ome-version-comparison).

### <a name="freebusy-federation"></a>Federación de disponibilidad

El uso compartido federado, incluida la información de disponibilidad, está sujeto actualmente a varias limitaciones importantes en los entornos doD.

En el GCC high:

- La confianza de federación (incluido el uso compartido bidireccional de disponibilidad) se admite entre los inquilinos de GCC High, los inquilinos de GCC y las nubes comerciales y la coexistencia híbrida (Exchange 2013 o posterior).

En el entorno DoD:

  - Actualmente, la confianza de federación (incluido el uso compartido de disponibilidad) solo se admite entre los inquilinos del entorno doD. No se admite entre inquilinos DoD y GCC, GCC high o inquilinos comerciales.

### <a name="client-configuration"></a>Configuración de clientes

Los pasos adicionales están implicados en la implementación y configuración de Office ProPlus (incluido Outlook). Para obtener una descripción detallada de estos pasos, vea [Guidance for deploying Aplicaciones Microsoft 365 para empresas in a GCC High or DoD environment](/deployoffice/deploy-microsoft-365-apps-gcc-high-dod).

Outlook para iOS y Android también está disponible para entornos GCC High y DoD. Para obtener más información acerca de las limitaciones de características y la administración en esos entornos, consulte [Using Outlook for iOS and Android en el Government Community Cloud](/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud).

### <a name="add-ins-in-outlook-and-outlook-web-app"></a>Complementos en Outlook y Outlook Web App  

Solo algunos complementos de OWA y Outlook están disponibles en GCC High y DoD. Mis plantillas y reuniones sugeridas están disponibles y se espera que funcionen. Solo se admiten los cinco complementos OWA predeterminados. La integración con aplicaciones de terceros es posible, sin embargo, estas integraciones no están cubiertas por las promesas de cumplimiento de Microsoft GCC High o DoD. Los clientes deben familiarizarse con las prácticas de tratamiento de datos de terceros y las promesas de cumplimiento antes de configurar el complemento para su organización.

## <a name="feature-nuances-within-gcc-environments-for-microsoft-to-do"></a>Matices de características en GCC entornos de Microsoft To Do

| Característica | Descripción | WW | Disponibilidad en GCC |
|:-----|:-----|:-----|:-----|
|Plataformas admitidas|Web, Android, iOS, Mac, Windows|Todo|Solo web|
|Compatibilidad con concentradores M365|Integraciones con Outlook, Teams, Planner|Todo|Outlook, Planner (Teams estar disponible con la aplicación Teams tareas)|
|Wunderlist Migración|Permitir que los usuarios de wunderlist migren datos a To Do en la Web|Sí|No|
|Notificaciones push|Enviar notificaciones push a los usuarios finales para avisos, etc.|Sí|No|
|Soporte técnico de Helpshift|Usar la interfaz helpshift para crear una solicitud de soporte técnico|Sí|No|
|Mi día|Planear el día|Sí|Sí|
|Lista planeada|Ver todas las tareas con una fecha de vencimiento|Sí|Sí|
|Asignado a you list|Todas las tareas asignadas en una lista compartida, Planner o WXP (futuro)|Sí|Sí|
|Correo electrónico marcado|Ver correos electrónicos marcados en Outlook como tareas|Sí|Sí|
|Compatibilidad con varias cuentas|Usar una cuenta de hogar y de oficina en un panel|Sí|Sí|
|Uso compartido de listas|Compartir listas con compañeros de la misma organización|Sí|Sí|
|Uso compartido entre inquilinos|Compartir lista de tareas fuera de la organización|Sí|No|
|Avisos y periodicidad|Establecer avisos para la tarea |Sí|Sí|

*Las demás características no mencionadas están disponibles en ambos entornos.