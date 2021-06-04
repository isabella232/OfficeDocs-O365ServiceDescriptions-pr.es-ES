---
title: Clientes y dispositivos móviles
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
description: Exchange Online funciona con versiones de escritorio y móviles de Outlook, así como Outlook en la web.
ms.openlocfilehash: 3aa0c2bbdf9b55b6a3544919143fd9d5e5cfed24
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653122"
---
# <a name="clients-and-mobile-devices"></a>Clientes y dispositivos móviles

## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook es un programa de correo electrónico que incluye compatibilidad con calendario, contactos, tareas y las siguientes características clave:
  
- **MAPI sobre HTTP:** la interfaz de programa de aplicaciones de mensajería (MAPI) sobre HTTP permite a los usuarios de Outlook conectarse Exchange Online buzones de correo a través de Internet desde fuera del firewall de su organización. MAPI sobre HTTP, el reemplazo a largo plazo para Outlook cualquier lugar. Este método de conectividad ofrece una resistencia de conexión mejorada, un inicio de sesión más seguro, extensibilidad, así como mejoras para TI y compatibilidad. Para obtener más información, vea [RPC sobre HTTP llega](/exchange/troubleshoot/administration/rpc-over-http-end-of-support) al final de la compatibilidad en Office 365 y MAPI sobre [HTTP](/exchange/mapi-over-http-exchange-2013-help).

- **Detección automática:** la característica de servicio de detección automática configura automáticamente Outlook para que funcione con Exchange Online. Los usuarios de Outlook reciben la configuración de perfil requerida directamente de Exchange Online la primera vez que inician sesión con su dirección de correo electrónico y contraseña. Mediante esta configuración se actualiza automáticamente el cliente de Outlook con la información necesaria para crear y mantener el perfil del usuario. Se requiere un certificado SSL para utilizar el servicio Detección automática. Este certificado SSL está limitado a un único dominio SSL principal. 

- **Modo Exchange** caché: la característica Modo de Exchange caché permite a los usuarios de Outlook tener acceso a copias locales de sus buzones de Exchange Online cuando no están conectados a Internet. El modo caché de Exchange guarda una copia del lado cliente de los buzones de Exchange de los usuarios en Outlook y la sincroniza automáticamente con el servidor de correo electrónico. Se recomienda usar Outlook en modo caché de Exchange porque ofrece acceso sin conexión y permite proporcionar una experiencia de usuario eficiente incluso cuando las condiciones de red entre el cliente y el servidor no sean las más óptimas. 

De forma predeterminada, el acceso a Outlook está habilitado para todos los usuarios. Los administradores pueden deshabilitar el acceso para determinados usuarios o grupos a través de Windows PowerShell. Se recomienda usar la última versión de Outlook, con el último Service Pack instalado, para tener acceso a Exchange Online. 
  
Para obtener información acerca de Outlook clientes compatibles con Exchange 2016 y Exchange Online, vea [System Requirements for Office](https://products.office.com/office-system-requirements). 

Microsoft 365 está diseñado para funcionar con los últimos exploradores y versiones de Office. Si usas exploradores antiguos y versiones de Office que no están en soporte estándar:

- Microsoft no impedirá deliberadamente que se conecte al servicio, pero la calidad de su experiencia puede disminuir con el tiempo.
- Microsoft no proporcionará actualizaciones de software para resolver problemas no relacionados con la seguridad.

> [!IMPORTANT]
> Outlook no se incluye como parte del precio de suscripción de Exchange Online. Aplicaciones Microsoft 365 para empresas (que incluye Microsoft Outlook) se incluye en algunos planes y se puede comprar como una suscripción independiente. Si utiliza POP para conectarse a una cuenta de correo electrónico de Exchange Online, verá las siguientes limitaciones:
> - No hay información de calendario
>- No hay información de disponibilidad
>- No se incluye la lista global de direcciones
>- No se incluye correo electrónico de inserción
>- Al conectarse a través de POP, todos los mensajes se descargan en el cliente y los diversos equipos o dispositivos no se sincronizan (por ejemplo, entre un teléfono y un portátil). 
  
## <a name="outlook-on-the-web"></a>Outlook en la web

Outlook en la web es una versión basada en web del programa de correo electrónico Outlook que se usa con Exchange Online. Permite a los usuarios acceder a su correo electrónico, calendario y contactos a través de un explorador web desde cualquier lugar que se conecten a Internet. Para obtener información sobre los exploradores compatibles, vea [Exploradores compatibles con Outlook en la web para la empresa](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006).
  
Outlook en la web tiene dos versiones de cliente y ambas se pueden usar con Exchange Online:
  
- **Outlook web:** la versión estándar de Outlook en la web proporciona a los usuarios de Exchange Online una experiencia de mensajería más similar a la de Outlook usuarios. Es compatible con la mayoría de los exploradores web más recientes y está optimizada para su uso en tabletas y smartphones, así como en equipos de escritorio y portátiles. Los usuarios pueden leer y enviar mensajes, organizar contactos y programar citas y reuniones. El tiempo de espera predeterminado basado en actividad se establece en seis horas, pero lo puede [configurar un administrador en Windows PowerShell](/powershell/module/exchange/set-organizationconfig) de 5 minutos a 8 horas. Este tiempo de espera depende de las interacciones del usuario dentro de la aplicación web, como seleccionar un botón o seleccionar un mensaje. También hay un tiempo de espera distinto orientado a la seguridad, que no es configurable y que se producirá independientemente de la actividad del usuario. Si un usuario tiene una sesión abierta durante 8 horas, Outlook Web App cerrará la sesión del usuario de forma automática y le solicitará que se vuelva a autenticar. 

- **La versión ligera** de Outlook en la web: la versión ligera de Outlook en la web proporciona a los usuarios Exchange Online acceso al buzón con casi cualquier explorador web. Los usuarios pueden leer y enviar mensajes, organizar contactos y programar citas y reuniones. El tiempo de espera predeterminado basado en actividad se establece en seis horas, pero lo puede [configurar un administrador en Windows PowerShell](/powershell/module/exchange/set-organizationconfig) de 5 minutos a 8 horas. Este tiempo de espera depende de las interacciones del usuario dentro de la aplicación web, como seleccionar un botón o seleccionar un mensaje. También hay un tiempo de espera distinto orientado a la seguridad, que no es configurable y que se producirá independientemente de la actividad del usuario. Si un usuario tiene una sesión abierta durante 8 horas, la versión ligera de Outlook Web App cerrará la sesión del usuario de forma automática y le solicitará que se vuelva a autenticar. 

Outlook en la web también está disponible en versiones móviles. Para obtener más información, consulte [esta página](https://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409).
  
## <a name="outlook-for-mac"></a>Outlook para Mac

Exchange Online admite Microsoft Outlook para Mac, que proporciona correo electrónico, calendario, libreta de direcciones, lista de tareas y lista de notas.
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>Outlook para iOS, Android y Windows Phone

Exchange Online funciona con Outlook aplicaciones disponibles para iOS, Android y Windows Phone. En cualquiera de estos dispositivos, usa la tienda de aplicaciones para buscar la Outlook aplicación. Este es un desglose por sistema operativo móvil.<br><br>
  
| Dispositivo | Android | iOS | Windows Phone |
|:-----|:-----|:-----|:-----|
|Outlook de aplicaciones móviles  <br/> |Sí  <br/> [Obtener Outlook para Android](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |Sí  <br/> [Obtener Outlook para iOS](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |Integrado  <br/> |
|Aplicaciones de correo electrónico integradas compatibles con Exchange Online  <br/> |Aplicación de Gmail/Aplicación de correo electrónico de Samsung  <br/> |Aplicación de correo de iOS  <br/> |Outlook Correo, calendario, contactos  <br/> |
|Más información  <br/> |[Configuración móvil de Android](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[iPhone o iPad instalación](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Windows Phone configuración](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |

También hay opciones para usar Exchange Online dispositivos, incluido Blackberry.
  
### <a name="feature-availability"></a>Disponibilidad de características

Outlook proporciona a los usuarios la experiencia rápida e intuitiva de correo electrónico y calendario que esperan de una aplicación móvil moderna, al tiempo que es la única aplicación que proporciona soporte para las mejores características. Es la única aplicación de correo electrónico diseñada específicamente para admitir toda la experiencia de Microsoft, lo que ofrece a los usuarios una experiencia coherente desde el escritorio hasta el móvil. Outlook está integrado con Intune, la movilidad empresarial y la seguridad, y Exchange controles para mantener seguros los datos y los usuarios.
  
Con Outlook, los usuarios pueden:
  
- Administrar todo el día desde un dispositivo móvil.

- Conectar a las aplicaciones y servicios que necesitan para ser productivos, a la vez que mantienen su trabajo y su información personal separada y segura.

Con Outlook para iOS, Outlook para Android o Outlook para Windows Phone, los usuarios pueden: 
  
- Benefíciese de una bandeja de entrada centrada que priorizó el correo electrónico importante

- Personalizar gestos de deslizar el dedo para que coincidan con sus hábitos de correo electrónico únicos

- Crear itinerarios de viaje que se puedan agregar directamente al calendario, con información clave disponible de un vistazo

- RSVP a reuniones desde la bandeja de entrada.

- Usar iconos intuitivos en citas de calendario y correo electrónico que les ayuden a procesar información rápidamente

- Usar una experiencia de Outlook coherente y familiar en todos los dispositivos

- Iniciar y unirse fácilmente a Skype reuniones desde el calendario

- Leer y responder a mensajes de correo electrónico cifrados y protegidos de IRM

- Compartir archivos almacenados en OneDrive para la Empresa

- Establecer respuestas automáticas con un toque

- Ver y administrar calendarios compartidos y delegados

- Buscar en la lista global de direcciones de su empresa con unos pocos toques

- Ver la disponibilidad del compañero de trabajo y programar una hora de reunión que funcione para todos los usuarios

- Ver el estado de aceptación, provisional y declinación de invitados

- Compartir calendarios desde sus teléfonos

- Iniciar y unirse Skype reuniones directamente desde un calendario

- Acceder a calendarios personales y de trabajo en un solo lugar, sin cambiar de aplicación
    
## <a name="exchange-activesync"></a>Exchange ActiveSync

Exchange Online admite el protocolo ActiveSync de Microsoft Exchange, que sincroniza los datos de buzón entre dispositivos móviles y Exchange Online para que los usuarios tengan acceso a su correo electrónico, calendario, contactos y tareas sobre la marcha.
  
Hay varios dispositivos móviles que funcionan con Exchange ActiveSync, incluidos Microsoft Windows Phone y las tabletas y los teléfonos de Apple iPhone, iPad y Android. Además de los teléfonos móviles y los dispositivos, la aplicación correo de Windows Phone usa Exchange ActiveSync para conectarse a Exchange Online. Para consultar una lista completa de los licenciatarios de Exchange ActiveSync actuales, visite el sitio de licencias de Exchange ActiveSync.
  
Para obtener más información acerca Exchange ActiveSync, [vea Exchange ActiveSync](/exchange/clients-and-mobile-in-exchange-online/clients-and-mobile-in-exchange-online).
  
> [!IMPORTANT]
> El número máximo de dispositivos de Exchange ActiveSync por buzón de correo es de 100. 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a>Aplicaciones desarrolladas con servicios Web Exchange (EWS)

 Las aplicaciones que se han desarrollado con los servicios Web Exchange (EWS) o con su API administrada permiten a los administradores acceder a los datos almacenados con Exchange Online desde aplicaciones que se ejecutan localmente, desde Azure o desde otros servicios hospedados. 
  
Para obtener más información sobre las aplicaciones desarrolladas con los servicios Web Exchange, vea [Servicios Web Exchange](/exchange/client-developer/exchange-web-services/explore-the-ews-managed-api-ews-and-web-services-in-exchange).
  
## <a name="pop-and-imap"></a>POP e IMAP

Exchange Online admite el acceso a buzones a través de los protocolos POP3 e IMAP4. Para el acceso POP e IMAP se requiere el cifrado a través de SSL. POP está habilitado de manera predeterminada para todos los usuarios. Los usuarios pueden ver la configuración de la conexión POP e IMAP en Outlook en la web. Los administradores pueden deshabilitar el acceso POP e IMAP por usuario.
  
Para obtener más información sobre la conectividad POP3 e IMAP4, vea [POP3 e IMAP4](/exchange/pop3-and-imap4-in-exchange-server-2013-exchange-2013-help).
  
## <a name="smtp"></a>SMTP

El Protocolo simple de transferencia de correo (SMTP) se usa para enviar correo saliente a clientes que se conecten a Exchange Online a través de IMAP o POP. Se trata del protocolo principal de enrutamiento y entrega a través de Exchange Server. Exchange Online admite dos tipos de servicios de retransmisión de SMTP para las aplicaciones de clientes internos autorizados que requieran el envío de correo SMTP:
  
- Envío de mensajes SMTP a usuarios dentro del entorno administrado.

- Retransmisión de mensajes SMTP autenticados a direcciones fuera del entorno administrado.

> [!IMPORTANT]
> Se requieren direcciones IP para los servidores de origen autorizados para que se admita la retransmisión SMTP. Al usar SMTP para enviar correo electrónico, se requiere la autenticación y el cifrado de Seguridad de la capa de transporte (TLS). 
  
## <a name="blackberry-devices"></a>Dispositivos BlackBerry

El correo electrónico está disponible en dispositivos BlackBerry &reg; mediante Exchange ActiveSync. Para averiguar cuáles son sus opciones, consulte estos temas:
  
- [Configurar el correo electrónico en un dispositivo BlackBerry](https://go.microsoft.com/fwlink/?linkid=863394)

- [Configurar el correo electrónico en un sistema operativo BlackBerry 7.1 y versiones anteriores](https://go.microsoft.com/fwlink/?linkid=863403)

Para más información, vea [BlackBerry](../office-365-platform-service-description/blackberry.md).
  
> [!NOTE]
> Si usa Office 365 operado por 21Vianet en China, Servicios de BlackBerry Business Cloud no está disponible. No obstante, puede usar dispositivos de Exchange ActiveSync o una oferta de Research In Motion (RIM, la solución de correo electrónico inalámbrico de BlackBerry) para ejecutar Blackberry Enterprise Server (BES). 
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, opciones independientes y soluciones locales, [consulte Exchange Online descripción del servicio](exchange-online-service-description.md).
