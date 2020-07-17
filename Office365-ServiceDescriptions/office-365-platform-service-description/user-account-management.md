---
title: User account management
ms.author: office365servicedesc
author: pamelaar
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
ms.openlocfilehash: 38d9c247e54943599554e374bc3c9905f043361b
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131664"
---
# <a name="user-account-management"></a>User account management

Microsoft admite los siguientes métodos para crear, administrar y autenticar usuarios. 
  
> [!NOTE]
> En este tema no se incluye información sobre las características de seguridad que permiten o prohíben el acceso a recursos individuales de Microsoft (por ejemplo, control de acceso basado en roles en Microsoft Exchange online o configurar la seguridad en Microsoft SharePoint Online). Para obtener más información sobre estas características, vea la [Descripción del servicio de Exchange Online](../exchange-online-service-description/exchange-online-service-description.md) y la [Descripción del servicio de SharePoint Online](../sharepoint-online-service-description/sharepoint-online-service-description.md). 
  
Si necesita información sobre las herramientas que pueden ayudarle a realizar tareas administrativas, consulte [herramientas para administrar cuentas de Microsoft](https://docs.microsoft.com/office365/enterprise/manage-office-365-accounts). Para obtener información sobre cómo realizar tareas de administración cotidianas, consulte [Common Management Tasks](https://docs.microsoft.com/office365/admin/manage/manage).
  
## <a name="need-help-signing-in-installing-or-uninstalling-or-canceling-your-subscription"></a>¿Necesita ayuda para iniciar sesión, instalar o desinstalar o para cancelar la suscripción?

Obtener ayuda [para iniciar sesión en](https://support.office.com/article/where-to-sign-in-to-office-365-for-business-e9eb7d51-5430-4929-91ab-6157c5a050b4)la  |  [instalación o desinstalación de Office](https://support.office.com/article/download-and-install-or-reinstall-office-365-or-office-2019-on-a-pc-or-mac-4414eaaf-0478-48be-9c42-23adc4716658)  |  [Cancelar Office 365](https://support.office.com/article/Cancel-Office-365-for-business-b1bc0bef-4608-4601-813a-cdd9f746709a)
  
Para otros problemas, visite el [centro de soporte técnico de Microsoft](https://support.microsoft.com/contactus/). Para obtener soporte técnico para Office 365 operado por 21Vianet en China, póngase en contacto con el [equipo de soporte técnico de 21Vianet](https://support.office.com/article/Get-technical-billing-and-subscription-support-for-Office-365-operated-by-21Vianet-671FB12E-F5D8-4CDF-B3E9-E8068A9AA496). Para Office 365 Germany, póngase en contacto con el [equipo de soporte técnico de Office 365 Germany](https://support.office.com/article/Get-technical-and-billing-support-for-Office-365-Germany-83ef2266-2543-48d7-a41a-1b56b403a8e9?ui=en-US&amp;rs=en-US&amp;ad=US&amp;fromAR=1). 
  
## <a name="sign-in-options"></a>Opciones de inicio de sesión

Microsoft tiene dos sistemas que se pueden usar para identidades de usuario:
  
- **Cuenta profesional o educativa (identidad de nube)** Los usuarios reciben credenciales de nube de Azure Active Directory (independientes de otras credenciales corporativas o de escritorio) para iniciar sesión en los servicios en la nube de Microsoft. Esta es la identidad predeterminada y se recomienda para poder minimizar la complejidad de la implementación. Las contraseñas de las cuentas profesionales o educativas usan la Azure Active Directory [directiva de contraseñas](https://docs.microsoft.com/previous-versions/azure/jj943764(v=azure.100)).
    
- **Cuenta federada (identidad federada)** Para todas las suscripciones de organizaciones con Active Directory local que usan el inicio de sesión único (SSO), los usuarios pueden iniciar sesión en los servicios de Microsoft mediante sus credenciales de Active Directory. El Active Directory corporativo almacena y controla la directiva de contraseñas. Para obtener información sobre el SSO, vea [Plan de desarrollo del inicio de sesión único](https://docs.microsoft.com/previous-versions/azure/azure-services/hh967643(v=azure.100)).
    
El tipo de identidad influye en la experiencia del usuario y en las opciones de administración de cuentas de usuario, así como en los requisitos de hardware y software y en otras consideraciones de la implementación.
  
### <a name="custom-domains-and-identity-options"></a>Dominios personalizados y opciones de identidad

Al crear un nuevo usuario, el nombre de inicio de sesión y la dirección de correo electrónico del usuario se asignan al dominio predeterminado, tal como se establece en el centro de administración de Microsoft 365. Para obtener más información, vea [Agregar usuarios y un dominio](https://support.office.com/article/Add-your-users-and-domain-to-Office-365-6383f56d-3d09-4dcb-9b41-b5f5a5efd611). 
  
De forma predeterminada, la suscripción usa el \< _company name_\> dominio **. onmicrosoft.com** que se creó con la cuenta. \* Puede agregar uno o más dominios personalizados a Microsoft, en lugar de conservar el dominio onmicrosoft.com, y puede asignar usuarios para iniciar sesión con cualquiera de los dominios validados. Cada dominio asignado al usuario es la dirección de correo electrónico que aparecerá en los mensajes de correo electrónico enviados y recibidos. 
  
Puede hospedar hasta 900 dominios de Internet registrados, cada uno de ellos representado por un espacio de nombres diferente. 
  
Para las organizaciones que utilizan el inicio de sesión único, todos los usuarios de un dominio deben usar el mismo sistema de identidad: identidad de nube o identidad federada. Por ejemplo, puede tener un grupo de usuarios que solo necesite una identidad en la nube, ya que no tienen acceso a sistemas locales y otro grupo de usuarios que usan sistemas locales y de Microsoft. Agregaría dos dominios a Office 365, como contractors.contoso.com y staff.contoso.com, y configurar solo SSO para uno de ellos. Un dominio completo de identidad de nube puede convertirse a identidad federada, o viceversa.
  
Para más información acerca de los dominios en Office 365, vea la descripción del servicio de [Dominios](domains.md). 
  
\*Si usa Office 365 operado por 21Vianet en China, el dominio predeterminado es \<companyname\> **. onmsChina.cn**. Si usa Office 365 Germany, el dominio predeterminado es \<companyname\> **. onmicrosoft.de**
  
## <a name="authentication"></a>Autenticación

A excepción de los sitios de Internet para el acceso anónimo creado con SharePoint Online, los usuarios deben autenticarse cuando tengan acceso a los servicios de Microsoft. 
  
- **Autenticación moderna** La autenticación moderna lleva el inicio de sesión basado en ADAL para la autenticación de bibliotecas de Active Directory a las aplicaciones de cliente de Office en distintas plataformas. De esta forma se habilitan las características de inicio de sesión, como la autenticación multifactor (MFA), los proveedores de identidad de terceros basada en SAML con aplicaciones de cliente de Office, y la autenticación basada en certificados y la tarjeta inteligente. También elimina la necesidad de que Microsoft Outlook use el protocolo de autenticación básica. Para obtener más información, incluida la disponibilidad de la autenticación moderna en las aplicaciones de Office, vea [Cómo funciona la autenticación moderna para las aplicaciones cliente de office 2013 y office 2016](https://docs.microsoft.com/office365/enterprise/modern-auth-for-office-2013-and-2016).
    
    La autenticación moderna está activada de forma predeterminada para Exchange Online. Para obtener información sobre cómo activarla o desactivarla, consulte [Habilitar la autenticación moderna en Exchange Online](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/enable-or-disable-modern-authentication-in-exchange-online).
    
- **Autenticación de identidad de nube** Los usuarios con identidades de nube se autentican mediante el sistema de desafío/respuesta tradicional. El explorador Web se redirige al servicio de inicio de sesión de Microsoft, donde se escribe el nombre de usuario y la contraseña de la cuenta profesional o educativa. El servicio de inicio de sesión autentica las credenciales y genera un token de servicio, que el explorador web publica en el servicio solicitado e inicia su sesión. 
    
- **Autenticación de identidad federada** Los usuarios con identidades federadas se autentican con los servicios de Federación de Active Directory (AD FS) 2,0 u otros servicios de token de seguridad. El explorador Web se redirige al servicio de inicio de sesión de Microsoft, donde se escribe el identificador corporativo en el formulario, un nombre principal de usuario (UPN; por ejemplo, isabel@contoso.com). El servicio de inicio de sesión determina si forma parte de un dominio federado y le ofrece la opción de redireccionarle al servidor de federación local para la autenticación. Si ha iniciado sesión en el escritorio (unido a dominio), se le autentica (mediante Kerberos o NTLMv2) y el servicio de token de seguridad local genera un token de inicio de sesión, que el explorador Web envía al servicio de inicio de sesión de Microsoft. A través del token de inicio de sesión, el servicio de inicio de sesión genera un token de servicio que el explorador web publica en el servicio pedido e inicia su sesión. Para obtener una lista de los servicios de token de seguridad disponibles, consulte [plan de inicio de sesión único (Single Sign-on](https://docs.microsoft.com/previous-versions/azure/azure-services/hh967643(v=azure.100))).
    
Microsoft usa la autenticación basada en formularios y el tráfico de autenticación a través de la red siempre se cifra con TLS/SSL mediante el puerto 443. El tráfico de autenticación usa un porcentaje desdeñable de ancho de banda para los servicios Microsoft. 
  
### <a name="multi-factor-authentication"></a>Autenticación multifactor

Con la autenticación multifactor, los usuarios deben confirmar una llamada telefónica, un mensaje de texto o una notificación de la aplicación en su smartphone después de escribir correctamente su contraseña. Solo después de esta segunda autenticación, el usuario podrá iniciar sesión. Los administradores de Microsoft pueden inscribir usuarios para multi-factor Authentication en el centro de administración de Microsoft 365. Obtenga más información sobre [multi-factor Authentication](https://docs.microsoft.com/office365/admin/security-and-compliance/set-up-multi-factor-authentication).
  
### <a name="rich-client-authentication"></a>Autenticación de clientes enriquecidos

En los clientes enriquecidos, como las aplicaciones de escritorio de Microsoft Office, la autenticación se puede realizar de dos formas:
  
- **Ayudante para el inicio de sesión de Microsoft Online Services** El ayudante para el inicio de sesión, que es instalado por el programa de instalación de escritorio, contiene un servicio de cliente que obtiene un token de servicio del servicio de inicio de sesión y lo devuelve al cliente enriquecido. 
    
  - Si tiene una identidad de nube, recibirá un mensaje de solicitud de credenciales, que el servicio de cliente envía al servicio de inicio de sesión para la autenticación (con WS-Trust).
    
  - Si tiene una identidad federada, el servicio de cliente se pone en contacto primero con el servidor de AD FS 2,0 para autenticar las credenciales (mediante Kerberos o NTLMv2) y obtener un token de inicio de sesión que se envía al servicio de inicio de sesión (mediante WS-Federation y WS-Trust).
    
- **Autenticación proxy o básica por SSL** El cliente de Outlook pasa las credenciales de autenticación básica por SSL a Exchange Online. Exchange Online proxy la solicitud de autenticación a la plataforma de identidad y, a continuación, al servidor local de Federación de Active Directory (para SSO). 
    
Para garantizar un descubrimiento y autenticación adecuados de los servicios de Microsoft, los administradores deben aplicar un conjunto de componentes y actualizaciones a cada estación de trabajo que use clientes enriquecidos (como Microsoft Office 2010) y se conecte a Office 365. La configuración de escritorio es una herramienta automatizada para configurar las estaciones de trabajo con las actualizaciones necesarias. Para obtener más información, vea [usar mis aplicaciones de escritorio de Office actuales](https://support.office.com/article/set-up-office-2010-desktop-programs-to-work-with-office-365-for-business-3324b8b8-dceb-45e2-ac24-c642720108f7?ocmsassetID=HA102817827&CorrelationId=8eb1b198-827a-4999-a584-05a05a92d224&ui=en-US&rs=en-US&ad=US).
  
### <a name="sign-in-experience"></a>Experiencia de inicio de sesión

La experiencia de inicio de sesión cambia en función del tipo de identidad en uso:
  
||**Identidad de nube**|**Identidad federada**|
|:-----|:-----|:-----|
|Outlook 2016  <br/> |Iniciar sesión en cada sesión <sup>1</sup> <br/> |Iniciar sesión en cada sesión <sup>2</sup> <br/> |
|Outlook 2013  <br/> |Iniciar sesión en cada sesión <sup>1</sup> <br/> |Iniciar sesión en cada sesión <sup>2</sup> <br/> |
|Outlook 2010 o Office 2007 en Windows 7  <br/> |Iniciar sesión en cada sesión <sup>1</sup> <br/> |Iniciar sesión en cada sesión <sup>2</sup> <br/> |
|Outlook 2010 o Office Outlook 2007 en Windows Vista  <br/> |Iniciar sesión en cada sesión <sup>1</sup> <br/> |Iniciar sesión en cada sesión <sup>2</sup> <br/> |
|Microsoft Exchange ActiveSync  <br/> |Iniciar sesión en cada sesión <sup>1</sup> <br/> |Iniciar sesión en cada sesión <sup>2</sup> <br/> |
|POP, IMAP, Outlook para Mac  <br/> |Iniciar sesión en cada sesión <sup>1</sup> <br/> |Iniciar sesión en cada sesión <sup>2</sup> <br/> |
|Experiencias Web: Centro de administración de Microsoft 365/Outlook en la web/SharePoint Online/Office para la web  <br/> |Iniciar sesión en cada sesión de explorador <sup>4</sup> <br/> |Iniciar sesión en cada sesión <sup>3</sup> <br/> |
|Office 2010 o Office 2007 mediante SharePoint Online  <br/> |Iniciar sesión en cada sesión de SharePoint Online<sup>4</sup> <br/> |Iniciar sesión en cada sesión de SharePoint Online<sup>3</sup> <br/> |
|Skype Empresarial Online  <br/> |Iniciar sesión en cada sesión <sup>1</sup> <br/> |Ningún aviso  <br/> |
|Outlook para Mac  <br/> |Iniciar sesión en cada sesión <sup>1</sup> <br/> |Iniciar sesión en cada sesión <sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> cuando se le pregunte por primera vez, puede guardar la contraseña para usarla en el futuro. No recibirá ningún otro aviso hasta que cambie la contraseña. <br/> 
<sup>2</sup> escriba sus credenciales corporativas. Puede guardar la contraseña y no se le volverá a preguntar hasta que la contraseña cambie. <br/> 
<sup>3</sup> todas las aplicaciones requieren que escriba o seleccione su nombre de usuario para iniciar sesión. La contraseña no se solicita si el equipo está unido al dominio. Si selecciona **mantener la sesión iniciada** , no se le volverá a preguntar hasta que cierre la sesión. <br/> 
<sup>4</sup> si selecciona **mantener la sesión iniciada** , no se le volverá a preguntar hasta que cierre la sesión. 
  
## <a name="creating-user-accounts"></a>Creación de cuentas de usuario

Hay varias formas de agregar usuarios. Para obtener más información, vea [Agregar usuarios individualmente o en la ayuda de administración masiva](https://docs.microsoft.com/office365/admin/add-users/add-users) y [Agregar, quitar y administrar usuarios en la vista previa del centro de administración de Microsoft 365](https://support.office.com/article/add-remove-and-manage-users-in-the-new-office-365-admin-center-6e80db58-c36b-4add-b1c8-cc5135f111f3?amp%3Bclcid=0x409&ui=en-US&rs=en-US&ad=US). Si usa Office 365 operado por 21Vianet en China, vea [Crear o modificar cuentas de usuario en Office 365 operado por 21Vianet: ayuda para administradores](https://docs.microsoft.com/office365/admin/add-users/add-users).
  
## <a name="deleting-accounts"></a>Eliminación de cuentas

El modo de eliminación de las cuentas depende si usa o no la sincronización de directorios: 
  
- Si no usa la sincronización de directorios, las cuentas se pueden eliminar con la página de administración o con Windows PowerShell.
    
- Si usa la sincronización de directorios, primero debe eliminar usuarios de Active Directory local en lugar de Office 365.
    
Cuando una cuenta se elimina, se vuelve inactiva. Puede restaurar una cuenta durante los 30 días siguientes después de su eliminación. Para obtener más información acerca de cómo eliminar y restaurar cuentas, consulte [eliminar usuarios](https://docs.microsoft.com/office365/admin/add-users/delete-a-user) y [restaurar usuarios](https://docs.microsoft.com/office365/admin/add-users/restore-user) o, si usa Office 365 operado por 21Vianet en China, consulte [crear o Editar cuentas de usuario en Office 365 operado por 21Vianet-ayuda para administradores](https://docs.microsoft.com/office365/admin/add-users/add-users).
  
## <a name="password-management"></a>Administración de contraseñas

Las directivas y los procedimientos para la administración de contraseñas dependen del sistema de identidad.
  
 **Administración de contraseñas de identidad de nube:**
  
Al usar identidades de nube, las contraseñas se generan de forma automática cuando se crea la cuenta.
  
- Para obtener más información sobre los requisitos de seguridad de contraseñas de identidad de nube, vea la [directiva de contraseñas](https://docs.microsoft.com/previous-versions/azure/jj943764(v=azure.100)).
    
- Para aumentar la seguridad, los usuarios deben cambiar sus contraseñas la primera vez que tengan acceso a los servicios de Microsoft. Como resultado, antes de que los usuarios puedan tener acceso a los servicios de Microsoft, deben iniciar sesión en el centro de administración de 365 de Microsoft, donde se les pide que cambien sus contraseñas.
    
- Los administradores pueden establecer la directiva de caducidad de contraseñas. Para obtener más información, vea [Establecer una directiva de caducidad de contraseña del usuario](https://docs.microsoft.com/office365/admin/manage/set-password-expiration-policy).
    
Existen varias herramientas para restablecer las contraseñas de los usuarios con las identidades de nube:
  
- El **Administrador restablece la contraseña** Si los usuarios pierden u olvidan sus contraseñas, los administradores pueden restablecer las contraseñas de los usuarios en el centro de administración o mediante Windows PowerShell. Los usuarios solo pueden cambiar su contraseña si conocen la contraseña existente. 
    
    Para los planes empresariales, si los administradores pierden u olvidan sus contraseñas, un administrador diferente con la función de administrador global puede restablecer las contraseñas de los administradores en el centro de administración de Microsoft 365 o mediante Windows PowerShell. Para obtener más información, vea [Restablecer las contraseñas de los administradores](https://docs.microsoft.com/office365/admin/add-users/reset-passwords). Si trabaja con Office 365 ofrecido por 21Vianet en China, vea [Cambiar o restablecer contraseñas en Office 365 ofrecido por 21Vianet](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b).
    
- El **usuario cambia las contraseñas con Outlook en la web** La página Opciones de Outlook en la web incluye un hipervínculo cambiar contraseña, que redirige a los usuarios a la página **Cambiar contraseña** . El usuario necesita conocer la contraseña anterior. Para obtener más información, vea [Cambiar contraseña](https://support.office.com/article/change-password-in-outlook-web-app-50bb1309-6f53-4c24-8bfd-ed24ca9e872c). Si usa Office 365 ofrecido por 21Vianet en China, vea [Cambiar o restablecer contraseñas en Office 365 ofrecido por 21Vianet](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b).
    
- **Derechos de restablecimiento de contraseña basados en roles** Para los planes empresariales, los usuarios autorizados, como el personal del Departamento de soporte técnico, pueden tener asignado el derecho de usuario **Restablecer contraseña** y el derecho de cambiar las contraseñas mediante funciones predefinidas o personalizadas sin llegar a los administradores de servicios completos. De forma predeterminada en los planes Enterprise, los administradores con el rol Administrador global, Administrador de contraseñas o Administrador de control de usuarios pueden cambiar las contraseñas. Para más información, vea [Asignar roles de administrador](https://docs.microsoft.com/office365/admin/add-users/assign-admin-roles).
    
- **Restablecer contraseñas mediante Windows PowerShell** Los administradores de servicio pueden usar Windows PowerShell para restablecer contraseñas. 
    
 **Administración de contraseñas de identidades federadas:**
  
Al utilizar identidades federadas, las contraseñas se administran en Active Directory. El servicio de token de seguridad local negocia la autenticación con la puerta de enlace de Federación sin pasar las contraseñas locales de Active Directory de los usuarios por Internet a Office 365. Se utilizan directivas de contraseñas locales o, para los clientes web, la identificación de dos factores. Outlook en la web no incluye un hipervínculo cambiar contraseña. Los usuarios cambian la contraseña mediante las herramientas locales estándar o a través de las opciones de inicio de sesión de su equipo de escritorio.
  
Si tiene habilitada la [sincronización de directorios con inicio de sesión único (SSO)](https://docs.microsoft.com/previous-versions/azure/azure-services/dn441213(v=azure.100)) en el entorno de la organización y hay una interrupción que afecta al proveedor de identidad federada, la opción de copia de seguridad de la sincronización de contraseña del inicio de sesión federado ofrece la opción de cambiar manualmente el dominio a la sincronización de contraseña. El uso de la sincronización de contraseña permitirá el acceso de los usuarios mientras se soluciona la interrupción. Obtenga información sobre [Cómo cambiar desde el inicio de sesión único a la sincronización de contraseñas](https://go.microsoft.com/fwlink/p/?LinkId=509832).
  
## <a name="license-management"></a>Administración de licencias

Una licencia concede a un usuario acceso a un conjunto de servicios de Microsoft. Un administrador asigna una licencia a cada usuario para el servicio al que necesita tener acceso. Por ejemplo, puede asignar a un usuario acceso a Skype Empresarial Online, pero no a SharePoint Online.
  
Los administradores de facturación de Microsoft pueden realizar cambios en los detalles de la suscripción, como el número de licencias de usuario y el número de servicios adicionales que usa la compañía. Consulte [asignar o quitar una licencia](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users). Si usa Office 365 ofrecido por 21Vianet, vea [Asignar o quitar licencias en Office 365 operado por 21Vianet](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users).
  
## <a name="group-management"></a>Administración de grupos

Los grupos de seguridad se usan en SharePoint Online para controlar el acceso a los sitios. Se pueden crear grupos de seguridad en el centro de administración de Microsoft 365. Para obtener más información sobre los grupos de seguridad, vea [Crear, editar o eliminar un grupo de seguridad](https://docs.microsoft.com/office365/admin/email/create-edit-or-delete-a-security-group).
  
## <a name="administrator-roles"></a>Funciones de administrador

Office 365 Enterprise sigue el modelo de control de acceso basado en roles (RBAC): los roles de administración definen los permisos y las funciones. La persona que se suscribe a Office 365 para su organización se convierte automáticamente en un administrador global o administrador de nivel superior. Existen cinco roles de administrador: administrador global, administrador de facturación, administrador de contraseñas, administrador de servicios y administrador de control de usuarios. Para más información sobre los roles de administrador en Office 365 Enterprise, incluida la forma en que se aplican a la administración de Exchange Online, SharePoint Online y Skype Empresarial Online, vea [Asignar roles de administrador](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/jj878348(v=ws.11)). Si usa Office 365 ofrecido por 21Vianet en China, vea [Asignar roles de administrador en Office 365 para empresas](https://docs.microsoft.com/office365/admin/add-users/assign-admin-roles).
  
## <a name="delegated-administration-and-support-for-partners"></a>Soporte y administración delegada para socios

Los socios se pueden autorizar para administrar cuentas en nombre de los clientes. El cliente no necesita una cuenta de usuario para que los socios usen y no consume una licencia cuando se concede la autoridad de administración delegada. Los socios pueden asignar el acceso completo o limitado a los usuarios de su organización. El acceso limitado incluye los derechos para restablecer contraseñas, administrar solicitudes de servicio y supervisar el estado del servicio. 
  
> [!NOTE]
> La capacidad de usar y especificar un socio como administrador delegado varía según la región. 
  
## <a name="azure-active-directory-services"></a>Servicios de Azure Active Directory

Azure Active Directory (AD) ofrece funciones de administración de identidades y acceso completas a Office 365. Combina los servicios de directorio, gobierno de identidad avanzada, administración de acceso a aplicaciones y una plataforma completa basada en estándares para los desarrolladores. Para obtener más información sobre las características de AD en Office 365, vea el artículo [Personalización de marca de la página de inicio de sesión y autoservicio de restablecimiento de contraseña para usuarios en la nube](https://www.microsoft.com/en-us/microsoft-365/blog/2015/02/17/sign-page-branding-cloud-user-self-service-password-reset-office-365/). Obtenga más información sobre las [ediciones gratuita, básica y premium de Azure Active Directory](https://msdn.microsoft.com/library/azure/dn532272.aspx). 
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, las opciones independientes y las soluciones locales, consulte [Microsoft 365 and Office 365 Platform Service Description](office-365-platform-service-description.md).
  
