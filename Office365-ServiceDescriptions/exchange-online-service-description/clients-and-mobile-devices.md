---
title: Clientes y dispositivos móviles
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 04/10/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
ms.openlocfilehash: 380f542c6db323d5dac647dc694c0b320bf13be6
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246236"
---
# <a name="clients-and-mobile-devices"></a>Clients and Mobile Devices

## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook es un programa de correo electrónico que incluye soporte para calendario, contactos, tareas y las siguientes características clave:
  
- **MAPI sobre http** La interfaz de programación de aplicaciones de mensajería (MAPI) a través de HTTP permite que los usuarios de Outlook se conecten a los buzones de Exchange Online a través de Internet desde fuera del firewall de su organización. MAPI sobre HTTP, el reemplazo a largo plazo para Outlook en cualquier lugar. Este método de conectividad ofrece una mayor resistencia de conexión, mayor Inicio de sesión seguro, extensibilidad, así como mejoras para ti y soporte técnico. Para obtener más información, consulte [RPC sobre http alcanza el final del soporte técnico en Office 365](https://go.microsoft.com/fwlink/?linkid=863890) y [MAPI sobre http](https://go.microsoft.com/fwlink/?linkid=393041).
    
- **Detección automática** La característica del servicio Detección automática configura Outlook automáticamente para que funcione con Exchange Online. Los usuarios de Outlook reciben la configuración de perfil requerida directamente de Exchange Online la primera vez que inician sesión con su dirección de correo electrónico y contraseña. Mediante esta configuración se actualiza automáticamente el cliente de Outlook con la información necesaria para crear y mantener el perfil del usuario. Se requiere un certificado SSL para utilizar el servicio Detección automática. Este certificado SSL está limitado a un único dominio SSL principal. 
    
- **Modo caché de Exchange** La característica de modo caché de Exchange permite a los usuarios de Outlook tener acceso a las copias locales de sus buzones de Exchange Online cuando no estén conectados a Internet. El modo caché de Exchange guarda una copia del lado cliente de los buzones de Exchange de los usuarios en Outlook y la sincroniza automáticamente con el servidor de correo electrónico. Se recomienda usar Outlook en modo caché de Exchange porque ofrece acceso sin conexión y permite proporcionar una experiencia de usuario eficiente incluso cuando las condiciones de red entre el cliente y el servidor no sean las más óptimas. 
    
De forma predeterminada, el acceso a Outlook está habilitado para todos los usuarios. Los administradores pueden deshabilitar el acceso para determinados usuarios o grupos a través de Windows PowerShell. Se recomienda usar la última versión de Outlook, con el último Service Pack instalado, para tener acceso a Exchange Online. 
  
Para obtener información sobre qué clientes de Outlook son compatibles con Exchange 2016 y Exchange Online, vea "Clientes compatibles" en [Requisitos del sistema para Exchange 2016](https://go.microsoft.com/fwlink/?LinkID=828972).
  
> [!IMPORTANT]
>  Outlook no se incluye como parte del precio de suscripción de Exchange Online. Microsoft Office Pro Plus (que contiene Microsoft Outlook) se incluye en algunos planes de Office 365 y se puede adquirir como una suscripción independiente. Si usa POP para conectarse a una cuenta de correo electrónico de Exchange Online, verá las siguientes limitaciones: > no hay información de calendario > ninguna información de disponibilidad > ninguna lista global de direcciones > no insertar correo electrónico > al conectarse a través de POP, todos los mensajes serán downlo aded al cliente y no habrá sincronización entre varios equipos o dispositivos (por ejemplo, entre un teléfono y un portátil). 
  
## <a name="outlook-on-the-web"></a>Outlook en la Web

Outlook en la web es una versión basada en web del programa de correo electrónico Outlook que se usa con Exchange Online. Permite a los usuarios tener acceso al correo electrónico, al calendario y a los contactos a través de un explorador web desde donde quiera que se conecten a Internet. Para obtener información sobre los exploradores compatibles, vea [Exploradores compatibles con Outlook en la web para la empresa](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006).
  
Outlook en la web tiene dos versiones de cliente y ambas se pueden usar con Exchange Online:
  
- **Outlook en la web** La versión estándar de Outlook en la web ofrece a los usuarios de Exchange Online una experiencia de mensajería muy similar a la de los usuarios de Outlook. Es compatible con la mayoría de los exploradores web más recientes y está optimizada para su uso en tabletas y smartphones, así como en equipos de escritorio y portátiles. Los usuarios pueden leer y enviar mensajes, organizar contactos y programar citas y reuniones. El tiempo de espera predeterminado basado en actividad se establece en seis horas, pero lo puede [configurar un administrador en Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) de 5 minutos a 8 horas. Este tiempo de espera depende de las interacciones de los usuarios dentro de la aplicación web, como hacer clic en un botón o seleccionar un mensaje. También hay un tiempo de espera distinto orientado a la seguridad, que no es configurable y que se producirá independientemente de la actividad del usuario. Si un usuario tiene una sesión abierta durante 8 horas, Outlook Web App cerrará la sesión del usuario de forma automática y le solicitará que se vuelva a autenticar. 
    
- **Versión ligera de Outlook en la web** La versión ligera de Outlook en la web ofrece a los usuarios de Exchange Online acceso al buzón con prácticamente cualquier explorador web. Los usuarios pueden leer y enviar mensajes, organizar contactos y programar citas y reuniones. El tiempo de espera predeterminado basado en actividad se establece en seis horas, pero lo puede [configurar un administrador en Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) de 5 minutos a 8 horas. Este tiempo de espera depende de las interacciones de los usuarios dentro de la aplicación web, como hacer clic en un botón o seleccionar un mensaje. También hay un tiempo de espera distinto orientado a la seguridad, que no es configurable y que se producirá independientemente de la actividad del usuario. Si un usuario tiene una sesión abierta durante 8 horas, la versión ligera de Outlook Web App cerrará la sesión del usuario de forma automática y le solicitará que se vuelva a autenticar. 
    
Outlook en la web también está disponible en versiones móviles. Para obtener más información, consulte [esta página](http://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409).
  
## <a name="outlook-for-mac"></a>Outlook para Mac

Exchange Online admite Microsoft Outlook para Mac, que ofrece correo electrónico, calendario, una libreta de direcciones, una lista de tareas y una lista de notas.
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>Outlook para iOS, Android y Windows Phone

Exchange Online funciona con las aplicaciones de Outlook disponibles para iOS, Android y Windows Phone. En cualquiera de estos dispositivos, use la App Store para encontrar la aplicación de Outlook. Este es un desglose por sistema operativo móvil.
  
|||||
|:-----|:-----|:-----|:-----|
|Device  <br/> |Android  <br/> |iOS  <br/> |Windows Phone  <br/> |
|Disponibilidad de aplicaciones móviles de Outlook  <br/> |Sí  <br/> [Obtener Outlook para Android](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |Sí  <br/> [Obtener Outlook para iOS](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |Integrado  <br/> |
|Aplicaciones de correo electrónico integradas compatibles con Exchange Online  <br/> |Aplicación de gmail/aplicación de correo electrónico de Samsung  <br/> |aplicación de correo de iOS  <br/> |Correo, calendario, contactos de Outlook  <br/> |
|Más información  <br/> |[Configuración móvil de Android](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[instalación de iPhone o iPad](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Configuración de Windows Phone](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |
   
También hay opciones para usar Exchange Online con dispositivos, como BlackBerry.
  
### <a name="feature-availability"></a>Disponibilidad de características

Outlook proporciona a los usuarios la experiencia de calendario y el correo electrónico más rápidas e intuitivas que esperan de una aplicación móvil moderna, a la vez que es la única aplicación que proporciona compatibilidad con las mejores características de Office 365. Es la única aplicación de correo electrónico diseñada específicamente para admitir la experiencia completa de Office 365, lo que proporciona a los usuarios una experiencia coherente de escritorio a móvil. Outlook se integra con Intune, movilidad empresarial y seguridad, así como con controles de Exchange para mantener seguros los datos y los usuarios.
  
Outlook permite a los usuarios:
  
- Administrar todo el día desde un dispositivo móvil.
    
- Conéctese a las aplicaciones y los servicios que necesitan para ser productivos, a la vez que conservan su trabajo y la información personal de forma separada y segura.
    
Con Outlook para iOS, Outlook para Android o Outlook para Windows Phone, los usuarios pueden: 
  
- Benefíciese de una bandeja de entrada prioritarios que priorizan el correo electrónico importante
    
- Personalizar gestos de deslizamiento para que se ajusten a sus hábitos de correo electrónico únicos
    
- Crear itinerarios de viajes que se puedan agregar directamente al calendario, con información clave disponible de un vistazo
    
- RSVP a reuniones desde la bandeja de entrada.
    
- Usar iconos intuitivos en las citas de correo electrónico y calendario que les ayuden a procesar la información rápidamente
    
- Usar una experiencia coherente y familiar de Outlook en todos los dispositivos
    
- Iniciar y unirse fácilmente a reuniones de Skype desde el calendario
    
- Leer y responder a mensajes de correo electrónico cifrados y protegidos por IRM
    
- Compartir archivos almacenados en OneDrive para la empresa
    
- Establecer respuestas automáticas con una pulsación
    
- Ver y administrar calendarios compartidos y delegados
    
- Buscar en la lista global de direcciones de su empresa con unos pocos punteos
    
- Ver la disponibilidad de los compañeros de trabajo y programar una hora de reunión que funcione para todos los usuarios
    
- Ver invitaciones aceptar, provisional y estado de rechazo
    
- Compartir calendarios directamente desde sus teléfonos
    
- Iniciar y unirse a reuniones de Skype directamente desde un calendario
    
- Obtener acceso a los calendarios laborales y personales en un solo punto, sin cambiar de aplicación
    
## <a name="exchange-activesync"></a>Exchange ActiveSync

Exchange Online admite el protocolo ActiveSync de Microsoft Exchange, que sincroniza los datos de buzón entre dispositivos móviles y Exchange Online para que los usuarios tengan acceso a su correo electrónico, calendario, contactos y tareas sobre la marcha.
  
Hay varios dispositivos móviles que funcionan con Exchange ActiveSync, incluidos Microsoft Windows Phone y las tabletas y los teléfonos de Apple iPhone, iPad y Android. Además de los teléfonos móviles y los dispositivos, la aplicación de correo en Windows Phone usa Exchange ActiveSync para conectarse a Exchange Online. Para consultar una lista completa de los licenciatarios de Exchange ActiveSync actuales, visite el sitio de licencias de Exchange ActiveSync.
  
Para obtener más información acerca de Exchange ActiveSync, vea [Exchange ActiveSync](https://go.microsoft.com/fwlink/p/?LinkId=271792).
  
> [!IMPORTANT]
> El número máximo de dispositivos de Exchange ActiveSync por buzón de correo es de 100. 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a>Aplicaciones desarrolladas con servicios Web Exchange (EWS)

 Las aplicaciones que se han desarrollado con los servicios Web Exchange (EWS) o con su API administrada permiten a los administradores acceder a los datos almacenados con Exchange Online desde aplicaciones que se ejecutan localmente, desde Azure o desde otros servicios hospedados. 
  
Para obtener más información sobre las aplicaciones desarrolladas con los servicios Web Exchange, vea [Servicios Web Exchange](https://go.microsoft.com/fwlink/?LinkId=325346).
  
## <a name="pop-and-imap"></a>POP e IMAP

Exchange Online admite el acceso a buzones a través de los protocolos POP3 e IMAP4. Para el acceso POP e IMAP se requiere el cifrado a través de SSL. POP está habilitado de manera predeterminada para todos los usuarios. Los usuarios pueden ver la configuración de la conexión POP e IMAP en Outlook en la web. Los administradores pueden deshabilitar el acceso POP e IMAP por usuario.
  
Para obtener más información sobre la conectividad POP3 e IMAP4, vea [POP3 e IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070).
  
## <a name="smtp"></a>SMTP

El Protocolo simple de transferencia de correo (SMTP) se usa para enviar correo saliente a clientes que se conecten a Exchange Online a través de IMAP o POP. Se trata del protocolo principal de enrutamiento y entrega a través de Exchange Server. Exchange Online admite dos tipos de servicios de retransmisión de SMTP para las aplicaciones de clientes internos autorizados que requieran el envío de correo SMTP:
  
- Envío de mensajes SMTP a usuarios dentro del entorno administrado.
    
- Retransmisión de mensajes SMTP autenticados a direcciones fuera del entorno administrado.
    
> [!IMPORTANT]
> Se requieren direcciones IP para los servidores de origen autorizados para que se admita la retransmisión SMTP. Al usar SMTP para enviar correo electrónico, se requiere la autenticación y el cifrado de Seguridad de la capa de transporte (TLS). 
  
## <a name="blackberry-devices"></a>Dispositivos BlackBerry ®

Office 365 el correo electrónico está disponible en dispositivos BlackBerry ® a través de Exchange ActiveSync. Para saber cuáles son sus opciones, consulte estos temas:
  
- [Configurar el correo electrónico en un dispositivo BlackBerry](https://go.microsoft.com/fwlink/?linkid=863394)
    
- [Configurar el correo electrónico en un dispositivo BlackBerry 7,1 OS y versiones anteriores](https://go.microsoft.com/fwlink/?linkid=863403)
    
Para más información, vea [BlackBerry](../office-365-platform-service-description/blackberry.md).
  
> [!NOTE]
> Si usa Office 365 operado por 21Vianet en China, Servicios de BlackBerry Business Cloud no está disponible. No obstante, puede usar dispositivos de Exchange ActiveSync o una oferta de Research In Motion (RIM, la solución de correo electrónico inalámbrico de BlackBerry) para ejecutar Blackberry Enterprise Server (BES). 
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes de Office 365, las opciones independientes y las soluciones locales, consulte [Descripción del servicio Exchange Online](exchange-online-service-description.md).
  

