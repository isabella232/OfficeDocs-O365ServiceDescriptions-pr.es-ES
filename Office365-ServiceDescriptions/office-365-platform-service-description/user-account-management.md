---
title: Administración de cuentas de usuario
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-user-account-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: e7616079-5b13-4f1c-99ed-b20174e0808d
description: Microsoft Office 365 admite los siguientes métodos para crear, administrar y autenticar usuarios.
ms.openlocfilehash: 76a47ba99c9b163c98b7370407d3390c20235ed5
ms.sourcegitcommit: a6d9057a955ca220db9e4dbc29cd9ea0053616fc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/10/2019
ms.locfileid: "31764858"
---
# <a name="user-account-management"></a>Administración de cuentas de usuario

Microsoft Office 365 admite los siguientes métodos para crear, administrar y autenticar usuarios. 
  
> [!NOTE]
> En este tema, no se incluye información sobre las características de seguridad que admiten o prohíben el acceso a recursos individuales de Office 365 (por ejemplo, el control de acceso basado en roles en Microsoft Exchange Online o la configuración de la seguridad en Microsoft SharePoint Online). Para obtener detalles relacionados con estas características, vea [Descripción del servicio Exchange Online](../exchange-online-service-description/exchange-online-service-description.md) y [Descripción del servicio SharePoint Online](../sharepoint-online-service-description/sharepoint-online-service-description.md). 
  
Si necesita información sobre las herramientas que pueden ayudarle a realizar las tareas administrativas, consulte [Herramientas para administrar cuentas de Office 365](https://go.microsoft.com/fwlink/?linkid=847777). Para aprender a realizar tareas de administración diarias, consulte [Tareas de administración comunes de Office 365](https://go.microsoft.com/fwlink/?linkid=847778).
  
## <a name="need-help-signing-in-installing-or-uninstalling-or-canceling-your-subscription"></a>¿Necesita ayuda para iniciar sesión, instalar o desinstalar o para cancelar la suscripción?

Obtenga ayuda con el [inicio de sesión en Office 365](http://go.microsoft.com/fwlink/?LinkID=529144&amp;clcid=0x409) | [Instalar o desinstalar Office](http://go.microsoft.com/fwlink/?LinkID=827202&amp;clcid=0x409) | [Cancelar Office 365](https://support.office.com/en-us/article/Cancel-Office-365-for-business-b1bc0bef-4608-4601-813a-cdd9f746709a)
  
Para otros problemas con Office 365, visite el [Centro de soporte técnico de Microsoft](https://go.microsoft.com/fwlink/?LinkID=808783). Para obtener soporte técnico para Office 365 operado por 21Vianet en China, póngase en contacto con el [equipo de soporte técnico de 21Vianet](https://support.office.com/en-US/article/Get-technical-billing-and-subscription-support-for-Office-365-operated-by-21Vianet-671FB12E-F5D8-4CDF-B3E9-E8068A9AA496). Para Office 365 Germany, póngase en contacto con el [equipo de soporte técnico de Office 365 Germany](https://support.office.com/en-us/article/Get-technical-and-billing-support-for-Office-365-Germany-83ef2266-2543-48d7-a41a-1b56b403a8e9?ui=en-US&amp;rs=en-US&amp;ad=US&amp;fromAR=1). 
  
## <a name="sign-in-options"></a>Opciones de inicio de sesión

Office 365 cuenta con dos sistemas que se pueden usar para identidades de usuario:
  
- **Cuenta profesional o educativa (identidad de nube)** Los usuarios reciben las credenciales de la nube de Azure Active Directory, de manera independiente a otras credenciales de escritorio o corporativas, para iniciar sesión en Office 365 y en otros Servicios en la nube de Microsoft. Esta es la identidad predeterminada y se recomienda para poder minimizar la complejidad de la implementación. Las contraseñas de las cuentas profesionales o educativas usan la Azure Active Directory [directiva de contraseñas](http://go.microsoft.com/fwlink/?LinkID=730689&amp;clcid=0x409).
    
- **Cuenta federada (identidad federada)** Para todas las suscripciones en organizaciones con Active Directory local que usan el inicio de sesión único (SSO), los usuarios pueden iniciar sesión en los servicios de Office 365 con sus credenciales de Active Directory. El Active Directory corporativo almacena y controla la directiva de contraseñas. Para obtener información sobre el SSO, vea [Plan de desarrollo del inicio de sesión único](https://go.microsoft.com/fwlink/p/?LinkID=270015).
    
El tipo de identidad influye en la experiencia del usuario y en las opciones de administración de cuentas de usuario, así como en los requisitos de hardware y software y en otras consideraciones de la implementación.
  
### <a name="custom-domains-and-identity-options"></a>Dominios personalizados y opciones de identidad

Al crear un nuevo usuario, el nombre de inicio de sesión y la dirección de correo electrónico del usuario se asignan al dominio predeterminado, tal como se establece en el centro de administración de Microsoft 365. Para obtener más información, vea [Agregar usuarios y dominio a Office 365](https://support.office.com/en-us/article/Add-your-users-and-domain-to-Office-365-6383f56d-3d09-4dcb-9b41-b5f5a5efd611). 
  
De manera predeterminada, la suscripción a Office 365 usa el dominio \< _company name_\> **.onmicrosoft.com** que se ha creado con la cuenta.\* Puede agregar uno o más dominios personalizados a Office 365 en lugar de mantener el dominio onmicrosoft.com, y puede asignar usuarios para que inicien sesión en cualquiera de los dominios validados. Cada dominio asignado al usuario es la dirección de correo electrónico que aparecerá en los mensajes de correo electrónico enviados y recibidos. 
  
Puede hospedar hasta 900 dominios de Internet registrados en Office 365, cada uno de ellos representado por un espacio de nombres diferente. 
  
Para las organizaciones que utilizan el inicio de sesión único, todos los usuarios de un dominio deben usar el mismo sistema de identidad: identidad de nube o identidad federada. Por ejemplo, imagine que tiene un grupo de usuarios que solo necesita una identidad de nube porque no tienen acceso a sistemas locales, y otro grupo que usa Office 365 y sistemas locales. Agregaría dos dominios a Office 365, como contractors.contoso.com y staff.contoso.com, y configurar solo SSO para uno de ellos. Un dominio completo de identidad de nube puede convertirse a identidad federada, o viceversa.
  
Para más información acerca de los dominios en Office 365, vea la descripción del servicio de [Dominios](domains.md). 
  
\* Si usa Office 365 operado por 21Vianet en China, el dominio predeterminado es \<nombreDeEmpresa\> **.onmsChina.cn**. Si está usando Office 365 Germany, el dominio predeterminado es \<nombreDeEmpresa\> **.onmicrosoft.de**
  
## <a name="authentication"></a>Autenticación

A excepción de los sitios de Internet para acceso anónimo creados con SharePoint Online, los usuarios deben autenticarse cuando tengan acceso a los servicios de Office 365. 
  
- **Autenticación moderna** La autenticación moderna lleva el inicio de sesión basado en ADAL para la autenticación de bibliotecas de Active Directory a las aplicaciones de cliente de Office en distintas plataformas. De esta forma se habilitan las características de inicio de sesión, como la autenticación multifactor (MFA), los proveedores de identidad de terceros basada en SAML con aplicaciones de cliente de Office, y la autenticación basada en certificados y la tarjeta inteligente. También elimina la necesidad de que Microsoft Outlook use el protocolo de autenticación básica. Para obtener más información, incluida la disponibilidad de la autenticación moderna en distintas aplicaciones de Office, consulte [Cómo funciona la autenticación moderna para las aplicaciones de cliente de Office 2013 y Office 2016](http://go.microsoft.com/fwlink/?LinkID=717892&amp;clcid=0x409) y [Uso de la autenticación moderna de Office 365 con clientes de Office](http://go.microsoft.com/fwlink/?LinkID=717893&amp;clcid=0x409).
    
    La autenticación moderna no está activada de forma predeterminada para Exchange Online. Para obtener información sobre cómo activarla, consulte [Habilitar Exchange Online para la autenticación moderna](http://go.microsoft.com/fwlink/?LinkID=717894&amp;clcid=0x409).
    
- **Autenticación de identidad de nube** Los usuarios con identidades de nube se autentican mediante el sistema de desafío/respuesta tradicional. El explorador web se redirecciona al servicio de inicio de sesión de Office 365, donde se escribe el nombre de usuario y la contraseña de la cuenta profesional o educativa. El servicio de inicio de sesión autentica las credenciales y genera un token de servicio, que el explorador web publica en el servicio solicitado e inicia su sesión. 
    
- **Autenticación de identidad federada** Los usuarios con identidades federadas se autentican con los servicios de Federación de Active Directory (AD FS) 2,0 u otros servicios de token de seguridad. El explorador Web se redirige al servicio de inicio de sesión de Office 365, donde se escribe el identificador corporativo en el formulario, un nombre principal de usuario (UPN isabel@contoso.com; por ejemplo,). El servicio de inicio de sesión determina si forma parte de un dominio federado y le ofrece la opción de redireccionarle al servidor de federación local para la autenticación. Si ha iniciado sesión en el escritorio (unido a dominio), se le autentica (mediante Kerberos o NTLMv2) y el servicio de token de seguridad local genera un token de inicio de sesión, que el explorador Web envía al servicio de inicio de sesión de Office 365. A través del token de inicio de sesión, el servicio de inicio de sesión genera un token de servicio que el explorador web publica en el servicio pedido e inicia su sesión. Para obtener una lista de los servicios de token de seguridad disponibles, consulte [plan de inicio de sesión único (Single Sign-on](https://go.microsoft.com/fwlink/p/?LinkID=270015)).
    
Office 365 usa la autenticación basada en formularios, y el tráfico de autenticación a través de la red se cifra siempre con TLS/SSL mediante el puerto 443. El tráfico de autenticación utiliza un porcentaje mínimo de ancho de banda para los servicios de Office 365. 
  
### <a name="multi-factor-authentication-for-office-365"></a>Autenticación multifactor para Office 365

Con multi-factor Authentication para Office 365, los usuarios deben confirmar una llamada de teléfono, un mensaje de texto o una notificación de la aplicación en su smartphone después de escribir correctamente su contraseña. Solo después de esta segunda autenticación, el usuario podrá iniciar sesión. Office 365 los administradores pueden inscribir usuarios para la autenticación multifactor en el centro de administración de Microsoft 365. Obtenga más información sobre [Multi-Factor Authentication para Office 365](https://go.microsoft.com/fwlink/p/?LinkId=392429).
  
### <a name="rich-client-authentication"></a>Autenticación de clientes enriquecidos

En los clientes enriquecidos, como las aplicaciones de escritorio de Microsoft Office, la autenticación se puede realizar de dos formas:
  
- **Asistente para el inicio de sesión de Microsoft Online Services** El Ayudante para el inicio de sesión, que se instala mediante Configuración de escritorio de Office 365, contiene un servicio de cliente que obtiene un token de servicio a partir del servicio de inicio de sesión de Office 365 y lo devuelve al cliente enriquecido. 
    
  - Si tiene una identidad de nube, recibe una solicitud para especificar las credenciales, que el servicio de cliente envía al servicio de inicio de sesión de Office 365 para la autenticación (a través de WS-Trust).
    
  - Si tiene una identidad federada, el servicio del cliente se comunica primero con el servidor de AD FS 2.0 para autenticar las credenciales (mediante Kerberos o NTLMv2) y obtener un token de inicio de sesión que se envía al servicio de inicio de sesión de Office 365 (mediante WS-Federation y WS-Trust).
    
- **Autenticación proxy o básica por SSL** El cliente de Outlook pasa las credenciales de autenticación básica por SSL a Exchange Online. Exchange Online pasa la solicitud de autenticación a través de proxy a la plataforma de identidad de Office 365 y, a continuación, a la implementación local de los Servicios de federación de Active Directory (para SSO). 
    
Para garantizar una detección y autenticación correctas de los servicios de Office 365, los administradores necesitan aplicar un conjunto de componentes y de actualizaciones a las estaciones de trabajo que usen clientes avanzados (como Microsoft Office 2010) y que se conecten a Office 365. La configuración de escritorio de Office 365 es una herramienta automatizada para configurar estaciones de trabajo con las actualizaciones necesarias. Para obtener más información, vea [Usar las aplicaciones de escritorio de Office actuales con Office 365](https://go.microsoft.com/fwlink/p/?LinkID=270049).
  
### <a name="sign-in-experience"></a>Experiencia de inicio de sesión

La experiencia de inicio de sesión cambia en función del tipo de identidad de Office 365 en uso:
  
||**Identidad de nube**|**Identidad federada**|
|:-----|:-----|:-----|
|Outlook 2016  <br/> |Iniciar sesión en cada sesión <sup>1</sup> <br/> |Iniciar sesión en cada sesión <sup>2</sup> <br/> |
|Outlook 2013  <br/> |Iniciar sesión en cada sesión <sup>1</sup> <br/> |Iniciar sesión en cada sesión <sup>2</sup> <br/> |
|Outlook 2010 o Office 2007 en Windows 7  <br/> |Iniciar sesión en cada sesión <sup>1</sup> <br/> |Iniciar sesión en cada sesión <sup>2</sup> <br/> |
|Outlook 2010 o Office Outlook 2007 en Windows Vista  <br/> |Iniciar sesión en cada sesión <sup>1</sup> <br/> |Iniciar sesión en cada sesión <sup>2</sup> <br/> |
|Microsoft Exchange ActiveSync  <br/> |Iniciar sesión en cada sesión <sup>1</sup> <br/> |Iniciar sesión en cada sesión <sup>2</sup> <br/> |
|POP, IMAP, Outlook para Mac  <br/> |Iniciar sesión en cada sesión <sup>1</sup> <br/> |Iniciar sesión en cada sesión <sup>2</sup> <br/> |
|Experiencias web: Portal de Office 365/Outlook Web App/SharePoint Online/Office Online  <br/> |Iniciar sesión en cada sesión de explorador <sup>4</sup> <br/> |Iniciar sesión en cada sesión <sup>3</sup> <br/> |
|Office 2010 o Office 2007 mediante SharePoint Online  <br/> |Iniciar sesión en cada sesión de SharePoint Online<sup>4</sup> <br/> |Iniciar sesión en cada sesión de SharePoint Online<sup>3</sup> <br/> |
|Skype Empresarial Online  <br/> |Iniciar sesión en cada sesión <sup>1</sup> <br/> |Ningún aviso  <br/> |
|Outlook para Mac  <br/> |Iniciar sesión en cada sesión <sup>1</sup> <br/> |Iniciar sesión en cada sesión <sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> La primera vez que se le pregunte, puede guardar la contraseña para volverla a usar en el futuro. No recibirá ningún otro aviso hasta que cambie la contraseña. > <sup>2</sup> Debe especificar las credenciales corporativas. Puede guardar la contraseña y no se le volverá a preguntar hasta que la contraseña cambie. > <sup>3</sup> Todas las aplicaciones requieren que escriba su nombre de usuario o haga clic para iniciar sesión. La contraseña no se solicita si el equipo está unido al dominio. Si hace clic en **Mantener la sesión iniciada**, no se le volverá a preguntar hasta que cierre la sesión. > <sup>4</sup> Si hace clic en **Mantener la sesión iniciada**, no se le volverá a preguntar hasta que cierre la sesión. 
  
## <a name="creating-user-accounts"></a>Creación de cuentas de usuario

Existen varias maneras de agregar usuarios a Office 365. Para obtener más información, vea [Agregar usuarios individualmente o de forma masiva a Office 365-ayuda de administración](https://go.microsoft.com/fwlink/p/?linkid=860006) y [Agregar, quitar y administrar usuarios en la vista previa del centro de administración de Microsoft 365](http://go.microsoft.com/fwlink/?LinkID=624101&amp;clcid=0x409). Si usa Office 365 operado por 21Vianet en China, vea [Crear o modificar cuentas de usuario en Office 365 operado por 21Vianet: ayuda para administradores](http://go.microsoft.com/fwlink/?LinkID=730724&amp;clcid=0x409).
  
## <a name="deleting-accounts"></a>Eliminación de cuentas

El modo de eliminación de las cuentas depende si usa o no la sincronización de directorios: 
  
- Si no usa la sincronización de directorios, las cuentas se pueden eliminar a través de la página de administración de Office 365 o de Windows PowerShell.
    
- Si usa la sincronización de directorios, primero debe eliminar usuarios de Active Directory local en lugar de Office 365.
    
Cuando una cuenta se elimina, se vuelve inactiva. Puede restaurar una cuenta durante los 30 días siguientes después de su eliminación. Para obtener más información sobre la eliminación y la restauración de cuentas, vea [Eliminar o restaurar usuarios en Office 365](https://go.microsoft.com/fwlink/p/?LinkID=270053) o, si usa Office 365 ofrecido por 21Vianet en China, vea [Crear o editar cuentas de usuario en Office 365 operado por 21Vianet: Ayuda para administradores](http://go.microsoft.com/fwlink/?LinkID=730724&amp;clcid=0x409).
  
## <a name="password-management"></a>Administración de contraseñas

Las directivas y los procedimientos para la administración de contraseñas dependen del sistema de identidad.
  
 **Administración de contraseñas de identidad de nube:**
  
Al usar identidades de nube, las contraseñas se generan de forma automática cuando se crea la cuenta.
  
- Para obtener más información sobre los requisitos de seguridad de contraseñas de identidad de nube, vea la [directiva de contraseñas](http://go.microsoft.com/fwlink/?LinkID=730689&amp;clcid=0x409).
    
- Para aumentar la seguridad, los usuarios deben cambiar sus contraseñas las primera vez que tengan acceso a Office 365. Debido a esto, para que los usuarios puedan tener acceso a los servicios de Office 365, primero deben iniciar sesión en el portal de Office 365, donde se les solicita que cambien la contraseña.
    
- Los administradores pueden establecer la directiva de caducidad de contraseñas. Para obtener más información, vea [Establecer una directiva de caducidad de contraseña del usuario](https://go.microsoft.com/fwlink/p/?LinkID=285381).
    
Existen varias herramientas para restablecer las contraseñas de los usuarios con las identidades de nube:
  
- **El administrador restablece la contraseña** Si los usuarios pierden u olvidan las contraseñas, los administradores pueden restablecer las contraseñas de los usuarios en el portal de Office 365 o mediante Windows PowerShell. Los usuarios solo pueden cambiar su contraseña si conocen la contraseña existente. 
    
    Para los planes empresariales, si los administradores pierden u olvidan sus contraseñas, un administrador diferente con la función de administrador global puede restablecer las contraseñas de los administradores en el centro de administración de Microsoft 365 o mediante Windows PowerShell. Para obtener más información, vea [Restablecer las contraseñas de los administradores](https://go.microsoft.com/fwlink/p/?LinkID=270062). Si trabaja con Office 365 ofrecido por 21Vianet en China, vea [Cambiar o restablecer contraseñas en Office 365 ofrecido por 21Vianet](http://go.microsoft.com/fwlink/?LinkID=730731&amp;clcid=0x409).
    
- **El usuario cambia la contraseña con Outlook Web App** En la página de opciones de Outlook Web App se incluye un hipervínculo de cambio de contraseña que redirige a los usuarios a la página **Cambiar contraseña**. El usuario necesita conocer la contraseña anterior. Para obtener más información, vea [Cambiar contraseña](https://go.microsoft.com/fwlink/p/?LinkID=270063). Si usa Office 365 ofrecido por 21Vianet en China, vea [Cambiar o restablecer contraseñas en Office 365 ofrecido por 21Vianet](http://go.microsoft.com/fwlink/?LinkID=730731&amp;clcid=0x409).
    
- **Derechos de restablecimiento de contraseñas basados en roles** Para los planes Enterprise, a los usuarios autorizados, como el personal del departamento de soporte técnico, se les puede asignar el derecho de usuario **Restablecer contraseña** y el derecho para cambiar contraseñas mediante los roles personalizados o predefinidos de Office 365 sin convertirse en administradores totales de los servicios. De forma predeterminada en los planes Enterprise, los administradores con el rol Administrador global, Administrador de contraseñas o Administrador de control de usuarios pueden cambiar las contraseñas. Para más información, vea [Asignar roles de administrador](https://go.microsoft.com/fwlink/p/?LinkID=270061).
    
- **Restablecer contraseñas mediante Windows PowerShell** Los administradores de servicio pueden usar Windows PowerShell para restablecer contraseñas. 
    
 **Administración de contraseñas de identidades federadas:**
  
Al utilizar identidades federadas, las contraseñas se administran en Active Directory. El servicio de token de seguridad local negocia la autenticación con la puerta de enlace de federación de Office 365 sin pasar las contraseñas locales de Active Directory de los usuarios a Office 365 a través de Internet. Se utilizan directivas de contraseñas locales o, para los clientes web, la identificación de dos factores. Outlook Web App no incluye un hipervínculo Cambiar contraseña. Los usuarios cambian la contraseña mediante las herramientas locales estándar o a través de las opciones de inicio de sesión de su equipo de escritorio.
  
Si tiene habilitada la [sincronización de directorios con inicio de sesión único (SSO)](https://go.microsoft.com/fwlink/p/?LinkId=509831) en su entorno de Office 365 y hay alguna interrupción que afecte a su proveedor de identidades federadas, la copia de seguridad de sincronización de contraseña para el inicio de sesión federado permite cambiar de forma manual el dominio a la sincronización de contraseña. Si usa la sincronización de contraseña, los usuarios podrán obtener acceso a Office 365 mientras se corrige la interrupción. Obtenga información sobre [cómo cambiar del inicio de sesión único a la sincronización de contraseña](https://go.microsoft.com/fwlink/p/?LinkId=509832).
  
## <a name="license-management"></a>Administración de licencias

Una licencia de Office 365 da al usuario acceso a un conjunto de servicios de Office 365. Un administrador asigna una licencia a cada usuario para el servicio al que necesita tener acceso. Por ejemplo, puede asignar a un usuario acceso a Skype Empresarial Online, pero no a SharePoint Online.
  
Los administradores de facturación de Office 365 pueden realizar cambios en los detalles de la suscripción, como el número de licencias de usuario y el número de servicios adicionales que usa la compañía. Vea [Asignar o quitar licencias en Office 365](https://go.microsoft.com/fwlink/p/?LinkID=270069). Si usa Office 365 ofrecido por 21Vianet, vea [Asignar o quitar licencias en Office 365 operado por 21Vianet](http://go.microsoft.com/fwlink/?LinkID=730747&amp;clcid=0x409).
  
## <a name="group-management"></a>Administración de grupos

Los grupos de seguridad se usan en SharePoint Online para controlar el acceso a los sitios. Se pueden crear grupos de seguridad en el centro de administración de Microsoft 365. Para obtener más información sobre los grupos de seguridad, vea [Crear, editar o eliminar un grupo de seguridad](http://go.microsoft.com/fwlink/?LinkID=733611&amp;clcid=0x409).
  
## <a name="administrator-roles"></a>Funciones de administrador

Office 365 Enterprise sigue el modelo de control de acceso basado en roles (RBAC): los roles de administración definen los permisos y las funciones. La persona que se suscribe a Office 365 para su organización se convierte automáticamente en un administrador global o administrador de nivel superior. Existen cinco roles de administrador: administrador global, administrador de facturación, administrador de contraseñas, administrador de servicios y administrador de control de usuarios. Para más información sobre los roles de administrador en Office 365 Enterprise, incluida la forma en que se aplican a la administración de Exchange Online, SharePoint Online y Skype Empresarial Online, vea [Asignar roles de administrador](https://go.microsoft.com/fwlink/p/?LinkID=282732). Si usa Office 365 ofrecido por 21Vianet en China, vea [Asignar roles de administrador en Office 365 para empresas](https://go.microsoft.com/fwlink/p/?linkid=270061).
  
## <a name="delegated-administration-and-support-for-partners"></a>Soporte y administración delegada para socios

Los socios se pueden autorizar para administrar cuentas en nombre de los clientes. El cliente no necesita ninguna cuenta de usuario para que la usen los socios y no consume ninguna licencia de Office 365 cuando se concede la autoridad de administración delegada. Los socios pueden asignar el acceso completo o limitado a los usuarios de su organización. El acceso limitado incluye los derechos para restablecer contraseñas, administrar solicitudes de servicio y supervisar el estado del servicio. 
  
> [!NOTE]
> La capacidad de usar y especificar un socio como administrador delegado varía según la región. 
  
## <a name="azure-active-directory-services"></a>Servicios de Azure Active Directory

Azure Active Directory (AD) ofrece funciones de administración de identidades y acceso completas a Office 365. Combina los servicios de directorio, gobierno de identidad avanzada, administración de acceso a aplicaciones y una plataforma completa basada en estándares para los desarrolladores. Para obtener más información sobre las características de AD en Office 365, vea el artículo [Personalización de marca de la página de inicio de sesión y autoservicio de restablecimiento de contraseña para usuarios en la nube](https://blogs.office.com/2015/02/17/sign-page-branding-cloud-user-self-service-password-reset-office-365/). Obtenga más información sobre las [ediciones gratuita, básica y premium de Azure Active Directory](https://msdn.microsoft.com/en-us/library/azure/dn532272.aspx). 
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes de Office 365, las opciones independientes y las soluciones locales, consulte [Descripción del servicio de la plataforma de Office 365](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).
  
