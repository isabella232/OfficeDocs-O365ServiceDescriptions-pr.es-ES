---
title: Clientes y dispositivos móviles
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
ms.openlocfilehash: ad19845f7a06cfb01a74507fdb794813091c1c2b
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/19/2018
ms.locfileid: "24037072"
---
# <a name="clients-and-mobile-devices"></a>Clientes y dispositivos móviles

## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook es un programa de correo electrónico que incluye compatibilidad para el calendario, contactos, tareas y las siguientes características principales:
  
- **MAPI sobre HTTP** Interfaz de programa de aplicaciones (MAPI) de mensajería a través de HTTP permite a los usuarios de Outlook para conectarse a buzones de Exchange Online a través de Internet desde fuera de firewall de la organización. MAPI sobre HTTP, la sustitución a largo plazo de Outlook en cualquier lugar. Este método de conectividad ofrece resistencia mejorada de conexión, en Inicio de sesión más seguro, extensibilidad, así como mejoras para TI y soporte técnico. Para obtener más información, vea [RPC sobre HTTP llega a fin de soporte en Office 365](https://go.microsoft.com/fwlink/?linkid=863890) y [MAPI a través de HTTP](https://go.microsoft.com/fwlink/?linkid=393041).
    
- **Detección automática** La característica del servicio Detección automática configura Outlook automáticamente para que funcione con Exchange Online. Los usuarios de Outlook reciben la configuración de perfil requerida directamente de Exchange Online la primera vez que inician sesión con su dirección de correo electrónico y contraseña. Mediante esta configuración se actualiza automáticamente el cliente de Outlook con la información necesaria para crear y mantener el perfil del usuario. Se requiere un certificado SSL para utilizar el servicio Detección automática. Este certificado SSL está limitado a un único dominio SSL principal. 
    
- **Modo caché de Exchange** La característica de modo caché de Exchange permite a los usuarios de Outlook tener acceso a las copias locales de sus buzones de Exchange Online cuando no estén conectados a Internet. El modo caché de Exchange guarda una copia del lado cliente de los buzones de Exchange de los usuarios en Outlook y la sincroniza automáticamente con el servidor de correo electrónico. Se recomienda usar Outlook en modo caché de Exchange porque ofrece acceso sin conexión y permite proporcionar una experiencia de usuario eficiente incluso cuando las condiciones de red entre el cliente y el servidor no sean las más óptimas. 
    
De forma predeterminada, el acceso a Outlook está habilitado para todos los usuarios. Los administradores pueden deshabilitar el acceso para determinados usuarios o grupos a través de Windows PowerShell. Se recomienda usar la última versión de Outlook, con el último Service Pack instalado, para tener acceso a Exchange Online. 
  
Para obtener información sobre qué clientes de Outlook son compatibles con Exchange 2016 y Exchange Online, vea "Clientes compatibles" en [Requisitos del sistema para Exchange 2016](https://go.microsoft.com/fwlink/?LinkID=828972).
  
> [!IMPORTANT]
>  Outlook no se incluye como parte del precio de suscripción de Exchange Online. Microsoft Office Pro Plus (que contiene Microsoft Outlook) se incluye en algunos planes de Office 365 y se puede adquirir como una suscripción independiente. >  Si utiliza POP para conectarse a una cuenta de correo electrónico de Exchange Online, verá las siguientes limitaciones: >  No hay información de calendario >  No hay información de disponibilidad >  No se incluye la lista global de direcciones >  No se incluye correo electrónico de inserción >  Al conectarse a través de POP, todos los mensajes se descargan en el cliente y los diversos equipos o dispositivos no se sincronizan (por ejemplo, entre un teléfono y un portátil). 
  
## <a name="outlook-on-the-web"></a>Outlook en la web

Outlook en la web es una versión basada en web del programa de correo electrónico Outlook que se usa con Exchange Online. Permite a los usuarios tener acceso al correo electrónico, al calendario y a los contactos a través de un explorador web desde donde quiera que se conecten a Internet. Para obtener información sobre los exploradores compatibles, vea [Exploradores compatibles con Outlook en la web para la empresa](https://go.microsoft.com/fwlink/p/?LinkId=287032).
  
Outlook en la web tiene dos versiones de cliente y ambas se pueden usar con Exchange Online:
  
- **Outlook en la web** La versión estándar de Outlook en la web ofrece a los usuarios de Exchange Online una experiencia de mensajería muy similar a la de los usuarios de Outlook. Es compatible con la mayoría de los exploradores web más recientes y está optimizada para su uso en tabletas y smartphones, así como en equipos de escritorio y portátiles. Los usuarios pueden leer y enviar mensajes, organizar contactos y programar citas y reuniones. El tiempo de espera predeterminado basado en actividad se establece en seis horas, pero lo puede [configurar un administrador en Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) de 5 minutos a 8 horas. Este tiempo de espera depende de las interacciones de los usuarios dentro de la aplicación web, como hacer clic en un botón o seleccionar un mensaje. También hay un tiempo de espera distinto orientado a la seguridad, que no es configurable y que se producirá independientemente de la actividad del usuario. Si un usuario tiene una sesión abierta durante 8 horas, Outlook Web App cerrará la sesión del usuario de forma automática y le solicitará que se vuelva a autenticar. 
    
- **Versión ligera de Outlook en la web** La versión ligera de Outlook en la web ofrece a los usuarios de Exchange Online acceso al buzón con prácticamente cualquier explorador web. Los usuarios pueden leer y enviar mensajes, organizar contactos y programar citas y reuniones. El tiempo de espera predeterminado basado en actividad se establece en seis horas, pero lo puede [configurar un administrador en Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) de 5 minutos a 8 horas. Este tiempo de espera depende de las interacciones de los usuarios dentro de la aplicación web, como hacer clic en un botón o seleccionar un mensaje. También hay un tiempo de espera distinto orientado a la seguridad, que no es configurable y que se producirá independientemente de la actividad del usuario. Si un usuario tiene una sesión abierta durante 8 horas, la versión ligera de Outlook Web App cerrará la sesión del usuario de forma automática y le solicitará que se vuelva a autenticar. 
    
Outlook en la web también está disponible en versiones móviles. Para obtener más información, consulte [esta página](http://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409).
  
## <a name="outlook-for-mac"></a>Outlook para Mac

Exchange Online admite Microsoft Outlook para Mac, que proporciona correo electrónico, calendario, una libreta de direcciones, una lista de tareas y una lista de notas.
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>Outlook para Windows Phone, iOS y Android

Exchange Online funciona con aplicaciones de Outlook disponibles para Windows Phone, iOS y Android. En cualquiera de estos dispositivos, utilice la tienda de aplicaciones para encontrar la aplicación de Outlook. Éste es un desglose por sistema operativo móvil.
  
|||||
|:-----|:-----|:-----|:-----|
|Dispositivo  <br/> |Android  <br/> |iOS  <br/> |Windows Phone  <br/> |
|Disponibilidad de la aplicación móvil de Outlook  <br/> |Sí  <br/> [Obtener Outlook para Android](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |Sí  <br/> [Obtener Outlook para iOS](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |Integrado  <br/> |
|Aplicaciones de correo electrónico integrada compatibles con Exchange Online  <br/> |Aplicación de correo electrónico de Gmail aplicación/Samsung  <br/> |aplicación de correo de iOS  <br/> |Correo de Outlook, calendario, contactos  <br/> |
|Más información  <br/> |[Programa de instalación de dispositivos móvil Android](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[programa de instalación iPhone o iPad](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Programa de instalación de Windows Phone](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |
   
También hay opciones para el uso de Exchange Online con dispositivos, incluyendo Blackberry.
  
### <a name="feature-availability"></a>Disponibilidad de características

Outlook proporciona a los usuarios la fast experiencia de correo electrónico y calendario intuitiva que esperan desde una aplicación móvil moderna, mientras que se va a la aplicación solo para proporcionar compatibilidad con las mejores características de Office 365. Es la única aplicación de correo electrónico diseñada específicamente para admitir la experiencia completa de Office 365, dar a los usuarios una experiencia coherente desde el escritorio hasta los dispositivos móviles. Outlook está integrado con Intune, la movilidad de la empresa y seguridad y controles de Exchange para mantener seguros los datos y los usuarios.
  
Outlook permite a los usuarios:
  
- Administrar su día completo desde un dispositivo móvil.
    
- Conectarse a las aplicaciones y servicios que necesitan para ser productivos, manteniendo su trabajo y la información personal independiente y segura.
    
Con Outlook para iOS, Outlook para Android o Outlook para Windows Phone, los usuarios pueden: 
  
- Ese correo electrónico importante de las prioridades de beneficios desde una bandeja de entrada reducido
    
- Personalizar gestos haga pasar el dedo para que coincida con sus hábitos de correo electrónico exclusivo
    
- Crear itinerarios de viajes que se pueden agregar directamente en el calendario, con información de clave de un vistazo
    
- RSVP a las reuniones desde la Bandeja de entrada.
    
- Usar iconos intuitivos en correo electrónico y calendario citas que le ayudan a procesar la información rápidamente
    
- Use una experiencia coherente y familiar de Outlook a través de todos los dispositivos
    
- Iniciar fácilmente y unirse a reuniones de Skype desde el calendario
    
- Leer y responder a IRM cifrada y protegida mensajes de correo electrónico
    
- Compartir archivos almacenados en OneDrive para la empresa
    
- Establecer las respuestas automáticas con llave
    
- Ver y administrar calendarios compartidos y delegados
    
- Buscar la lista global de direcciones de su compañía con unos cuantos toques
    
- Ver la disponibilidad del compañero de trabajo y programar una hora de reunión que funciona para todos los usuarios
    
- Vea los invitados Aceptar, provisional y rechazar estado
    
- Compartir calendarios desde sus teléfonos
    
- Iniciar y unirse a la derecha de las reuniones de Skype de un calendario
    
- Trabajo de acceso y los calendarios personales en un solo lugar, sin cambiar aplicaciones
    
## <a name="exchange-activesync"></a>Exchange ActiveSync

Exchange Online admite el protocolo ActiveSync de Microsoft Exchange, que sincroniza los datos de buzón entre dispositivos móviles y Exchange Online para que los usuarios tengan acceso a su correo electrónico, calendario, contactos y tareas sobre la marcha.
  
Trabajo de una amplia gama de dispositivos móviles con Exchange ActiveSync, incluidos Microsoft Windows Phone, Apple iPhone y iPad y teléfonos Android y tabletas. Además de los teléfonos móviles y dispositivos, la aplicación de correo en Windows Phone usa Exchange ActiveSync para conectarse a Exchange Online. Una lista completa de las licencias de Exchange ActiveSync actuales está disponible en el sitio de licencias de Exchange ActiveSync.
  
Para obtener más información acerca de Exchange ActiveSync, consulte [Exchange ActiveSync](https://go.microsoft.com/fwlink/p/?LinkId=271792).
  
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
  
## <a name="blackberry-devices"></a>Dispositivos de BlackBerry®

Correo electrónico de Office 365 está disponible en dispositivos BlackBerry® a través de Exchange ActiveSync. Para averiguar cuáles son sus opciones, vea estos temas:
  
- [Configurar el correo electrónico en un dispositivo BlackBerry](https://go.microsoft.com/fwlink/?linkid=863394)
    
- [Configurar el correo electrónico en un dispositivo BlackBerry 7.1 OS y versiones anteriores](https://go.microsoft.com/fwlink/?linkid=863403)
    
Para más información, vea [BlackBerry](../office-365-platform-service-description/blackberry.md).
  
> [!NOTE]
> Si usa Office 365 operado por 21Vianet en China, Servicios de BlackBerry Business Cloud no está disponible. No obstante, puede usar dispositivos de Exchange ActiveSync o una oferta de Research In Motion (RIM, la solución de correo electrónico inalámbrico de BlackBerry) para ejecutar Blackberry Enterprise Server (BES). 
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes de Office 365, las opciones independientes y las soluciones locales, consulte [Descripción del servicio Exchange Online](exchange-online-service-description.md).
  

