---
title: User account management
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-user-account-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: e7616079-5b13-4f1c-99ed-b20174e0808d
description: Microsoft admite los siguientes métodos para crear, administrar y autenticar usuarios.
ms.openlocfilehash: 5a4b242046503df691587919284454a670f817821eab1b3a6692f542bdcefadb
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/06/2021
ms.locfileid: "54702049"
---
# <a name="user-account-management"></a>User account management

Microsoft admite los siguientes métodos para crear, administrar y autenticar usuarios. 
  
> [!NOTE]
> En este tema no se incluye información sobre características de seguridad que permiten o prohíben el acceso a recursos individuales de Microsoft (por ejemplo, control de acceso basado en roles en Microsoft Exchange Online o configuración de la seguridad en Microsoft Office SharePoint Online). Para obtener más información acerca de estas características, [vea Exchange Online descripción del](../exchange-online-service-description/exchange-online-service-description.md) servicio y la SharePoint del servicio en [línea](../sharepoint-online-service-description/sharepoint-online-service-description.md). 
  
Si necesita información sobre las herramientas que pueden ayudarle a realizar tareas administrativas, vea [Herramientas para administrar cuentas de Microsoft](/office365/enterprise/manage-office-365-accounts). Para obtener información sobre cómo realizar tareas de administración diarias, vea [Tareas de administración comunes](/office365/admin/manage/manage).
  
## <a name="need-help-with-signing-in-installing-or-uninstalling-or-canceling-your-subscription"></a>¿Necesita ayuda para iniciar sesión, instalar o desinstalar o cancelar la suscripción?

Obtenga ayuda con: [iniciar sesión en](https://support.office.com/article/where-to-sign-in-to-office-365-for-business-e9eb7d51-5430-4929-91ab-6157c5a050b4)Instalación o  |  [desinstalación de Office](https://support.office.com/article/download-and-install-or-reinstall-office-365-or-office-2019-on-a-pc-or-mac-4414eaaf-0478-48be-9c42-23adc4716658)Cancelar  |  [Office 365](https://support.office.com/article/Cancel-Office-365-for-business-b1bc0bef-4608-4601-813a-cdd9f746709a)
  
Para otros problemas, visite el Centro [de soporte técnico de Microsoft](https://support.microsoft.com/contactus/). Para obtener soporte técnico para Office 365 operado por 21Vianet en China, póngase en contacto con el [equipo de soporte técnico de 21Vianet](https://support.office.com/article/Get-technical-billing-and-subscription-support-for-Office-365-operated-by-21Vianet-671FB12E-F5D8-4CDF-B3E9-E8068A9AA496). Para Office 365 Germany, póngase en contacto con el [equipo de soporte técnico de Office 365 Germany](https://support.office.com/article/83ef2266-2543-48d7-a41a-1b56b403a8e9). 
  
## <a name="sign-in-options"></a>Opciones de inicio de sesión

Microsoft tiene dos sistemas que se pueden usar para identidades de usuario:
  
- Cuenta laboral o **educativa (identidad** en la nube): los usuarios reciben Azure Active Directory credenciales de la nube , independientes de otras credenciales de escritorio o corporativas, para iniciar sesión en los servicios en la nube de Microsoft. Esta es la identidad predeterminada y se recomienda para poder minimizar la complejidad de la implementación. Las contraseñas de las cuentas profesionales o educativas usan la Azure Active Directory [directiva de contraseñas](/previous-versions/azure/jj943764(v=azure.100)).
    
- **Cuenta federada (identidad federada):** para todas las suscripciones de organizaciones con Active Directory local que usan el inicio de sesión único (SSO), los usuarios pueden iniciar sesión en servicios Microsoft con sus credenciales de Active Directory. El Active Directory corporativo almacena y controla la directiva de contraseñas. Para obtener información sobre el SSO, vea [Plan de desarrollo del inicio de sesión único](/previous-versions/azure/azure-services/hh967643(v=azure.100)).
    
El tipo de identidad influye en la experiencia del usuario y en las opciones de administración de cuentas de usuario, así como en los requisitos de hardware y software y en otras consideraciones de la implementación.
  
### <a name="custom-domains-and-identity-options"></a>Dominios personalizados y opciones de identidad

Al crear un nuevo usuario, el nombre de inicio de sesión y la dirección de correo electrónico del usuario se asignan al dominio predeterminado, tal como se establece en el Centro de administración de Microsoft 365. Para obtener más información, vea [Agregar los usuarios y el dominio](https://support.office.com/article/Add-your-users-and-domain-to-Office-365-6383f56d-3d09-4dcb-9b41-b5f5a5efd611). 
  
De forma predeterminada, la suscripción usa el <de empresa > **.onmicrosoft.com** que se creó con la cuenta. Si está usando Office 365 operado por 21Vianet en China, el dominio predeterminado es <nombre *de* empresa > **.onmsChina.cn**. Si usa Office 365 Alemania, el dominio predeterminado <nombre *de empresa* > **.onmicrosoft.de**. Puede agregar uno o varios dominios personalizados **a** Microsoft en lugar de conservar el dominio onmicrosoft.com y puede asignar a los usuarios que inicien sesión con cualquiera de los dominios validados. Cada dominio asignado al usuario es la dirección de correo electrónico que aparecerá en los mensajes de correo electrónico enviados y recibidos. 
  
Puede hospedar hasta 900 dominios de Internet registrados, cada uno representado por un espacio de nombres diferente. 
  
Para las organizaciones que utilizan el inicio de sesión único, todos los usuarios de un dominio deben usar el mismo sistema de identidad: identidad de nube o identidad federada. Por ejemplo, puede tener un grupo de usuarios que solo necesite una identidad en la nube porque no tienen acceso a los sistemas locales y otro grupo de usuarios que usan Microsoft y sistemas locales. Agregaría dos dominios a Office 365, como **contractors.contoso.com** y **staff.contoso.com**, y solo configuraría SSO para uno de ellos. Un dominio completo de identidad de nube puede convertirse a identidad federada, o viceversa.
  
Para más información acerca de los dominios en Office 365, vea la descripción del servicio de [Dominios](domains.md). 
  
## <a name="authentication"></a>Autenticación

A excepción de los sitios de Internet para el acceso anónimo creados con SharePoint Online, los usuarios deben autenticarse al acceder a servicios Microsoft. 
  
- **Autenticación moderna:** la autenticación moderna lleva el inicio de sesión basado en biblioteca de autenticación de Microsoft a Office aplicaciones cliente en todas las plataformas. De esta forma se habilitan las características de inicio de sesión, como la autenticación multifactor (MFA), los proveedores de identidad de terceros basada en SAML con aplicaciones de cliente de Office, y la autenticación basada en certificados y la tarjeta inteligente. También elimina la necesidad de que Microsoft Outlook use el protocolo de autenticación básica. Para obtener más información, incluida la disponibilidad de la autenticación moderna en todas las aplicaciones de Office, vea How [modern authentication works for Office 2013 and Office 2016 client apps](/office365/enterprise/modern-auth-for-office-2013-and-2016).
    
    La autenticación moderna está activada de forma predeterminada para Exchange Online. Para obtener información sobre cómo activarlo o desactivarlo, vea [Habilitar la autenticación moderna en Exchange Online](/exchange/clients-and-mobile-in-exchange-online/enable-or-disable-modern-authentication-in-exchange-online).
    
- **Autenticación de identidad en la** nube: los usuarios con identidades en la nube se autentican mediante desafíos y respuestas tradicionales. El explorador web se redirige al servicio de inicio de sesión de Microsoft, donde escribe el nombre de usuario y la contraseña de su cuenta profesional o educativa. El servicio de inicio de sesión autentica las credenciales y genera un token de servicio, que el explorador web publica en el servicio solicitado e inicia su sesión. 
    
- **Autenticación de** identidad federada: los usuarios con identidades federadas se autentican mediante Servicios de federación de Active Directory (AD FS) 2.0 u otros servicios de token de seguridad. El explorador web se redirige al servicio de inicio de sesión de Microsoft, donde escribe el identificador corporativo con el formato de un nombre principal de usuario (UPN), por ejemplo: *isabel@contoso.com*. El servicio de inicio de sesión determina si forma parte de un dominio federado y le ofrece la opción de redireccionarle al servidor de federación local para la autenticación. Si ha iniciado sesión en el escritorio (unido al dominio), se autentica (con Kerberos o NTLMv2) y el servicio de token de seguridad local genera un token de inicio de sesión, que el explorador web publica en el servicio de inicio de sesión de Microsoft. A través del token de inicio de sesión, el servicio de inicio de sesión genera un token de servicio que el explorador web publica en el servicio pedido e inicia su sesión. Para obtener una lista de los Servicios de token de seguridad disponibles, consulte [Guía básica de inicio de sesión único.](/previous-versions/azure/azure-services/hh967643(v=azure.100))
    
Microsoft usa la autenticación basada en formularios y el tráfico de autenticación a través de la red siempre se cifra con TLS/SSL mediante el puerto 443. El tráfico de autenticación usa un porcentaje insignificante de ancho de banda para servicios Microsoft. 
  
### <a name="multi-factor-authentication"></a>Autenticación multifactor

Con la autenticación multifactor, los usuarios deben confirmar una llamada telefónica, un mensaje de texto o una notificación de aplicación en su smartphone después de escribir correctamente su contraseña. Solo después de esta segunda autenticación, el usuario podrá iniciar sesión. Los administradores de Microsoft pueden inscribir usuarios para la autenticación multifactor en el Centro de administración de Microsoft 365. Obtenga más información [sobre la autenticación multifactor](/office365/admin/security-and-compliance/set-up-multi-factor-authentication).
  
### <a name="rich-client-authentication"></a>Autenticación de clientes enriquecidos

En los clientes enriquecidos, como las aplicaciones de escritorio de Microsoft Office, la autenticación se puede realizar de dos formas:
  
- **Microsoft Online Services Sign-In asistente de** inicio de sesión, que se instala mediante la instalación de escritorio, contiene un servicio de cliente que obtiene un token de servicio del servicio de inicio de sesión y lo devuelve al cliente enriquecido. 
    
  - Si tiene una identidad de nube, recibirá una solicitud de credenciales, que el servicio cliente envía al servicio de inicio de sesión para la autenticación (mediante WS-Trust).
    
  - Si tiene una identidad federada, el servicio cliente primero se pone en contacto con el servidor de AD FS 2.0 para autenticar las credenciales (con Kerberos o NTLMv2) y obtener un token de inicio de sesión que se envía al servicio de inicio de sesión (mediante WS-Federation y WS-Trust).
    
- **Autenticación básica/proxy sobre SSL:** el Outlook pasa las credenciales de autenticación básicas a través de SSL a Exchange Online. Exchange Online la solicitud de autenticación a la plataforma de identidad y, a continuación, al servidor de federación de Active Directory local (para SSO). 
    
Para garantizar la correcta detección y autenticación de servicios Microsoft, los administradores deben aplicar un conjunto de componentes y actualizaciones a cada estación de trabajo que usa clientes enriquecidos (como Microsoft Office 2010) y se conecta a Office 365. La configuración de escritorio es una herramienta automatizada para configurar las estaciones de trabajo con las actualizaciones necesarias. Para obtener más información, consulta [Usar mis aplicaciones Office escritorio actuales.](https://support.office.com/article/3324b8b8-dceb-45e2-ac24-c642720108f7)
  
### <a name="sign-in-experience"></a>Experiencia de inicio de sesión

La experiencia de inicio de sesión cambia según el tipo de identidad en uso:<br><br>
  
| Servicio | Identidad de la nube | Identidad federada |
|:-----|:-----|:-----|
|Outlook 2016  <br/> |Iniciar sesión en cada sesión <sup>1</sup> <br/> |Iniciar sesión en cada sesión <sup>2</sup> <br/> |
|Outlook 2013  <br/> |Iniciar sesión en cada sesión <sup>1</sup> <br/> |Iniciar sesión en cada sesión <sup>2</sup> <br/> |
|Outlook 2010 o Office 2007 en Windows 7  <br/> |Iniciar sesión en cada sesión <sup>1</sup> <br/> |Iniciar sesión en cada sesión <sup>2</sup> <br/> |
|Outlook 2010 o Office Outlook 2007 en Windows Vista  <br/> |Iniciar sesión en cada sesión <sup>1</sup> <br/> |Iniciar sesión en cada sesión <sup>2</sup> <br/> |
|Microsoft Exchange ActiveSync  <br/> |Iniciar sesión en cada sesión <sup>1</sup> <br/> |Iniciar sesión en cada sesión <sup>2</sup> <br/> |
|POP, IMAP, Outlook para Mac  <br/> |Iniciar sesión en cada sesión <sup>1</sup> <br/> |Iniciar sesión en cada sesión <sup>2</sup> <br/> |
|Experiencias web: Centro de administración de Microsoft 365 / Outlook en la Web/ SharePoint Online / Office para la Web  <br/> |Iniciar sesión en cada sesión de explorador <sup>4</sup> <br/> |Iniciar sesión en cada sesión <sup>3</sup> <br/> |
|Office 2010 o Office 2007 mediante SharePoint Online  <br/> |Iniciar sesión en cada sesión de SharePoint Online<sup>4</sup> <br/> |Iniciar sesión en cada sesión de SharePoint Online<sup>3</sup> <br/> |
|Skype Empresarial Online  <br/> |Iniciar sesión en cada sesión <sup>1</sup> <br/> |Ningún aviso  <br/> |
|Outlook para Mac  <br/> |Iniciar sesión en cada sesión <sup>1</sup> <br/> |Iniciar sesión en cada sesión <sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> Cuando se le pida por primera vez, puede guardar la contraseña para su uso futuro. No recibirá ningún otro aviso hasta que cambie la contraseña. <br/> 
<sup>2</sup> Escriba sus credenciales corporativas. Puede guardar la contraseña y no se le volverá a preguntar hasta que la contraseña cambie. <br/> 
<sup>3</sup> Todas las aplicaciones requieren que escribas o selecciones tu nombre de usuario para iniciar sesión. La contraseña no se solicita si el equipo está unido al dominio. Si selecciona **Mantenerme iniciado sesión,** no se le pedirá de nuevo hasta que salga de sesión. <br/> 
<sup>4</sup> Si selecciona **Mantenerme iniciado sesión,** no se le pedirá de nuevo hasta que salga de sesión. 
  
## <a name="create-user-accounts"></a>Crear cuentas de usuario

Hay varias maneras de agregar usuarios. Para obtener más información, vea Agregar usuarios individualmente o de forma [masiva:](/office365/admin/add-users/add-users) Ayuda para administradores y [Agregar,](https://support.office.com/article/6e80db58-c36b-4add-b1c8-cc5135f111f3)quitar y administrar usuarios en Centro de administración de Microsoft 365 vista previa . Si usa Office 365 operado por 21Vianet en China, vea [Crear o modificar cuentas de usuario en Office 365 operado por 21Vianet: ayuda para administradores](/office365/admin/add-users/add-users).
  
## <a name="delete-user-accounts"></a>Eliminar cuentas de usuario

El modo de eliminación de las cuentas depende si usa o no la sincronización de directorios: 
  
- Si no usa la sincronización de directorios, las cuentas se pueden eliminar mediante la página de administración o mediante Windows PowerShell.
    
- Si usa la sincronización de directorios, primero debe eliminar usuarios de Active Directory local en lugar de Office 365.
    
Cuando una cuenta se elimina, se vuelve inactiva. Puede restaurar una cuenta durante los 30 días siguientes después de su eliminación. Para obtener más información acerca de [](/office365/admin/add-users/delete-a-user) cómo eliminar [](/office365/admin/add-users/restore-user) y restaurar cuentas, vea Eliminar usuarios y restaurar usuarios o, si usa Office 365 operado por 21Vianet en China, vea Crear o editar cuentas de usuario en Office 365 operado por [21Vianet - Ayuda](/office365/admin/add-users/add-users)para administradores .
  
## <a name="password-management"></a>Administración de contraseñas

Las directivas y los procedimientos para la administración de contraseñas dependen del sistema de identidad.
  
### <a name="cloud-identity-password-management"></a>Administración de contraseñas de identidad en la nube
  
Al usar identidades de nube, las contraseñas se generan de forma automática cuando se crea la cuenta.
  
- Para obtener más información sobre los requisitos de seguridad de contraseñas de identidad de nube, vea la [directiva de contraseñas](/previous-versions/azure/jj943764(v=azure.100)).
    
- Para aumentar la seguridad, los usuarios deben cambiar sus contraseñas cuando acceden por primera vez a servicios Microsoft. Como resultado, para que los usuarios puedan acceder a servicios Microsoft, deben iniciar sesión en el Centro de administración de Microsoft 365, donde se les pedirá que cambien sus contraseñas.
    
- Los administradores pueden establecer la directiva de caducidad de contraseñas. Para obtener más información, vea [Establecer una directiva de caducidad de contraseña del usuario](/office365/admin/manage/set-password-expiration-policy).
    
Existen varias herramientas para restablecer las contraseñas de los usuarios con las identidades de nube:
  
- **El administrador restablece la contraseña:** si los usuarios pierden u olvidan sus contraseñas, los administradores pueden restablecer las contraseñas de los usuarios en el centro de administración o mediante Windows PowerShell. Los usuarios solo pueden cambiar su contraseña si conocen la contraseña existente. 
    
    Para los planes de empresa, si los administradores pierden u olvidan sus contraseñas, un administrador diferente con el rol De administrador global puede restablecer las contraseñas de los administradores en el Centro de administración de Microsoft 365 o mediante Windows PowerShell. Para obtener más información, vea [Restablecer las contraseñas de los administradores](/office365/admin/add-users/reset-passwords). Si trabaja con Office 365 ofrecido por 21Vianet en China, vea [Cambiar o restablecer contraseñas en Office 365 ofrecido por 21Vianet](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b).
    
- **El usuario cambia las contraseñas con Outlook en la Web:** la página Outlook en la Web opciones incluye un hipervínculo Cambiar contraseña, que redirige a los usuarios a la **página Cambiar** contraseña. El usuario necesita conocer la contraseña anterior. Para obtener más información, vea [Cambiar contraseña](https://support.office.com/article/change-password-in-outlook-web-app-50bb1309-6f53-4c24-8bfd-ed24ca9e872c). Si usa Office 365 ofrecido por 21Vianet en China, vea [Cambiar o restablecer contraseñas en Office 365 ofrecido por 21Vianet](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b).
    
- **Derechos** de contraseña de restablecimiento basados en roles: para los  planes de empresa, los usuarios autorizados, como el personal del departamento de soporte técnico, pueden tener asignado el derecho de restablecer la contraseña y el derecho a cambiar las contraseñas mediante roles predefinidos o personalizados sin convertirse en administradores de servicios completos. De forma predeterminada, en los planes de empresa, los administradores con el rol Administrador global, Administrador de contraseñas o Administrador de administración de usuarios pueden cambiar las contraseñas. Para más información, vea [Asignar roles de administrador](/office365/admin/add-users/assign-admin-roles).
    
- **Restablecer contraseñas mediante Windows PowerShell:** los administradores de servicios pueden usar Windows PowerShell para restablecer las contraseñas. 
    
### <a name="federated-identity-password-management"></a>Administración de contraseñas de identidad federada
  
Al utilizar identidades federadas, las contraseñas se administran en Active Directory. El servicio de token de seguridad local negocia la autenticación con Federation Gateway sin pasar las contraseñas locales de Active Directory de los usuarios a través de Internet para Office 365. Se utilizan directivas de contraseñas locales o, para los clientes web, la identificación de dos factores. Outlook en la Web incluye un hipervínculo Cambiar contraseña. Los usuarios cambian la contraseña mediante las herramientas locales estándar o a través de las opciones de inicio de sesión de su equipo de escritorio.
  
Si la sincronización de directorios con inicio de sesión único [(SSO)](/previous-versions/azure/azure-services/dn441213(v=azure.100)) está habilitada en el entorno de la organización y hay una interrupción que afecta al proveedor de identidades federadas, la copia de seguridad de sincronización de contraseñas para el inicio de sesión federado ofrece la opción de cambiar manualmente el dominio a Sincronización de contraseñas. El uso de la sincronización de contraseñas permitirá a los usuarios acceder mientras se soluciona la interrupción. Obtenga [información sobre cómo cambiar de single Sign-On a Password Sync](https://go.microsoft.com/fwlink/p/?LinkId=509832).
  
## <a name="license-management"></a>Administración de licencias

Una licencia proporciona a un usuario acceso a un conjunto de servicios Microsoft. Un administrador asigna una licencia a cada usuario para el servicio al que necesita tener acceso. Por ejemplo, puede asignar a un usuario acceso a Skype Empresarial Online, pero no a SharePoint Online.
  
Los administradores de facturación de Microsoft pueden realizar cambios en los detalles de la suscripción, como el número de licencias de usuario y el número de servicios adicionales que usa su empresa. Consulte [Asignar o quitar una licencia](/office365/admin/subscriptions-and-billing/assign-licenses-to-users). Si usa Office 365 ofrecido por 21Vianet, vea [Asignar o quitar licencias en Office 365 operado por 21Vianet](/office365/admin/subscriptions-and-billing/assign-licenses-to-users).
  
## <a name="group-management"></a>Administración de grupos

Los grupos de seguridad se usan en SharePoint Online para controlar el acceso a los sitios. Los grupos de seguridad se pueden crear en el Centro de administración de Microsoft 365. Para obtener más información sobre los grupos de seguridad, vea [Crear, editar o eliminar un grupo de seguridad](/office365/admin/email/create-edit-or-delete-a-security-group).
  
## <a name="administrator-roles"></a>Roles de administrador

Office 365 para empresas sigue un modelo de control de acceso basado en roles (RBAC): los permisos y las capacidades se definen mediante roles de administración. La persona que se suscribe a Office 365 para su organización se convierte automáticamente en un administrador global o administrador de nivel superior. Existen cinco roles de administrador: administrador global, administrador de facturación, administrador de contraseñas, administrador de servicios y administrador de control de usuarios. Para obtener más información acerca de los roles de administrador en Office 365 para empresas, incluido cómo se aplican a Exchange Online, SharePoint Online y administración de Skype Empresarial Online, vea [Assigning administrator roles](/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/jj878348(v=ws.11)). Si usa Office 365 ofrecido por 21Vianet en China, vea [Asignar roles de administrador en Office 365 para empresas](/office365/admin/add-users/assign-admin-roles).
  
## <a name="delegated-administration-and-support-for-partners"></a>Soporte y administración delegada para socios

Los socios se pueden autorizar para administrar cuentas en nombre de los clientes. El cliente no requiere una cuenta de usuario para el uso de partners y no consume una licencia al conceder autoridad de administración delegada. Los socios pueden asignar el acceso completo o limitado a los usuarios de su organización. El acceso limitado incluye los derechos para restablecer contraseñas, administrar solicitudes de servicio y supervisar el estado del servicio. 
  
> [!NOTE]
> La capacidad de usar y especificar un socio como administrador delegado varía según la región. 
  
## <a name="azure-active-directory-services"></a>Servicios de Azure Active Directory

Azure Active Directory (AD) ofrece funciones de administración de identidades y acceso completas a Office 365. Combina los servicios de directorio, gobierno de identidad avanzada, administración de acceso a aplicaciones y una plataforma completa basada en estándares para los desarrolladores. Para obtener más información sobre las características de AD en Office 365, vea Iniciar sesión en la personalidad de marca de página y restablecimiento de contraseña de autoservicio del usuario [en la nube.]() https://go.microsoft.com/fwlink/?linkid=2144147 Obtenga más información sobre las [ediciones gratuita, básica y premium de Azure Active Directory](/previous-versions/azure/dn532272(v=azure.100)). 
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, opciones independientes y soluciones locales, vea Microsoft 365 y Office 365 descripción del servicio [de plataforma.](office-365-platform-service-description.md)
