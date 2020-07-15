---
title: Destinatarios
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-recipients
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: da22b03a-c981-49c6-9928-4312c2c5e2ee
description: En este tema, se describen las características relacionadas con los destinatarios que se incluyen con Microsoft Exchange Online. Incluye correo electrónico, contactos, grupos de distribución, calendarios y capacidades de programación.
ms.openlocfilehash: a2d1f37bf4f86399522573d18177f6c397fd761c
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132644"
---
# <a name="recipients"></a>Destinatarios

This topic describes recipient-related features included with Microsoft Exchange Online. This includes email, contacts, distribution groups, and calendar and scheduling capabilities.
  
## <a name="email"></a>Correo electrónico

Every Microsoft Exchange Online subscriber receives a mailbox, and specialty mailboxes are available for scheduling facilities resources (such as conference rooms) and for multiuser access to shared email addresses. Maximum storage limits apply to most mailboxes, and administrators can control allowable mailbox sizes. Automated notifications and restrictions can alert users when their mailboxes are nearing, or at, capacity. Exchange Online also has several types of message limitations—message size, message rate, and recipient list limits. Details of all these features and limits are provided below.
  
> [!NOTE]
> Las direcciones catchall ya no son compatibles con Exchange Online. Debido al filtrado de destinatarios para proteger contra posibles mensajes de correo no deseado, se rechazarán las direcciones de correo electrónico que no existan en la organización. 
  
### <a name="mailbox-types-storage-limits-and-capacity-alerts"></a>Tipos de buzones, límites de almacenamiento y alertas de capacidad

The amount of mailbox storage available to a user and the default mailbox size are determined by the mailbox type and the user's subscription license. Administrators can reduce maximum mailbox sizes per user or globally. Exchange Online also provides notifications when a user's mailbox is nearing, or at, capacity.
  
Para obtener más información, consulte las secciones "límites de almacenamiento de buzones" y "alertas de capacidad" en el tema [Exchange Online limits](exchange-online-limits.md).
  
### <a name="mailtips"></a>MailTips

MailTips are automated, informative messages that appear above the To: line while users are composing or addressing a message. They are designed to help prevent accidental delivery, policy violations, or unnecessary non-delivery reports (NDRs). For example, MailTips can generate an alert if senders try to send messages to overly large groups, to groups that contain external recipients, or to a distribution group that is moderated or restricted. For more information, see [MailTips](https://go.microsoft.com/fwlink/p/?LinkId=401472).
  
### <a name="delegate-access"></a>Acceso delegado

Exchange Online admite el acceso delegado, es decir, la posibilidad de que los usuarios puedan administrar su correo electrónico y sus calendarios. El acceso delegado se suele usar entre un administrador y un asistente, donde el asistente procesa los mensajes de correo electrónico entrantes del administrador y coordina la programación del administrador. Los usuarios de Exchange online pueden habilitar el acceso de delegado en Outlook o Outlook en la web, o los administradores en el centro de administración de Exchange. 
  
Los delegados pueden tener dos tipos de acceso:
  
- **Permisos para enviar en nombre de** El delegado escribe mensajes de correo electrónico y escribe el nombre de otra persona en el campo De, que se mostrará como "[nombre del delegado] en nombre de [nombre de la persona]." 
    
- **Send As permissions** The delegate can send messages from the other person's mailbox as if the delegate were the mailbox owner. This scenario is common where there is a shared mailbox and several employees send email messages from that shared mailbox instead of from their Exchange Online accounts. 
    
Para obtener más información sobre cómo delegar acceso, consulte [Administrar permisos para destinatarios](https://technet.microsoft.com/library/jj919240%28v=exchg.160%29.aspx).
  
### <a name="inbox-rules"></a>Reglas de la bandeja de entrada

Exchange Online permite a los usuarios crear reglas de bandeja de entrada que realicen automáticamente acciones concretas basadas en criterios en mensajes a medida que lleguen. Por ejemplo, pueden crear una regla para mover automáticamente todo el correo a una carpeta concreta si el correo se envió a un grupo de distribución concreto. Los usuarios administran las reglas de la bandeja de entrada desde Outlook o Outlook en la Web. Los administradores pueden bloquear ciertos tipos de reglas de bandeja de entrada deshabilitando el reenvío desde el servidor o las respuestas automáticas desde el servidor. Por ejemplo, deshabilitar el reenvío de correo electrónico desde el servidor puede evitar que los usuarios reenvíen automáticamente correo electrónico a sus cuentas personales. De manera similar, deshabilitar las respuestas automáticas desde el servidor puede evitar que las partes externas usen estas respuestas para identificar una dirección electrónica válida. Estos cambios se realizan a través de Windows PowerShell remoto.
  
### <a name="clutter"></a>Otros correos

Clutter is designed to help you focus on the most important messages in your inbox. It uses machine learning to de-clutter your inbox by moving lower priority messages out of your way and into a new Clutter folder. Clutter respects your existing email rules, so if you have created rules to organize your email those rules continue to be applied and Clutter won't act on those messages. Clutter is disabled by default for your inbox. To learn more, see [De-clutter your inbox in Office 365](https://www.microsoft.com/en-us/microsoft-365/blog/2014/11/11/de-clutter-inbox-office-365/).
  
### <a name="connected-accounts"></a>Cuentas conectadas

La característica cuentas conectadas permite a los usuarios de Exchange Online conectar cuentas de correo electrónico externas (como cuentas personales) a sus cuentas de correo electrónico internas en Exchange Online y, a continuación, usar Outlook en la web para interactuar con todos sus mensajes en un solo sitio. Las cuentas conectadas se sincronizan automáticamente al iniciar sesión en Outlook en la web; los usuarios también pueden sincronizar manualmente las cuentas desde Outlook en la Web. Los administradores pueden habilitar y deshabilitar esta característica para usuarios específicos o para todos los usuarios a través del [Centro de administración de Exchange](https://go.microsoft.com/fwlink/?LinkID=785297&amp;clcid=0x409).
  
### <a name="inactive-mailboxes"></a>Buzones de correo inactivos

Exchange Online provides the capability to preserve the contents of deleted mailboxes indefinitely. This feature is called inactive mailboxes. A mailbox becomes inactive when an In-Place Hold or a Litigation Hold is placed on the mailbox before it's deleted. This results in the contents of the mailbox being preserved indefinitely. Administrators, compliance officers, or record managers can use the In-Place eDiscovery feature in Exchange Online to access the contents of an inactive mailbox.
  
La habilitación de un buzón inactivo requiere que el buzón tenga asignada una licencia de Exchange Online (Plan 2) o tenga una suscripción de Archivado de Exchange Online de manera que se pueda imponer una retención local o una retención por juicio en el buzón antes de eliminarlo.
  
> [!IMPORTANT]
> If a hold isn't placed on a mailbox before it's deleted, the contents of the mailbox will not be preserved or discoverable. The mailbox can be recovered within 30 days of deletion, but the mailbox and its contents will be permanently deleted after 30 days if it isn't recovered. 
  
Para obtener más información, vea:
  
- [Administrar buzones inactivos en Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=286991)
    
- [Conservación local y retención por juicio](https://go.microsoft.com/fwlink/p/?LinkId=271746)
    
- [Exhibición de documentos electrónicos en contexto](https://go.microsoft.com/fwlink/p/?LinkId=271747)
    
## <a name="contacts-and-distribution-groups"></a>Contactos y grupos de distribución

### <a name="offline-address-book"></a>Libreta de direcciones sin conexión

La característica libreta de direcciones sin conexión proporciona una instantánea de la información de Active Directory disponible en la lista global de direcciones (GAL) de Outlook. Está en caché localmente en Outlook para que esté disponible cuando el usuario trabaje sin conexión.
  
### <a name="address-book-policies"></a>Directivas de la libreta de direcciones

Exchange Online admite directivas de libreta de direcciones. Las directivas de libreta de direcciones (ABP) permiten clasificar a los usuarios en grupos específicos para proporcionar vistas personalizadas de la lista global de direcciones (LGD) de una organización. Al crear una ABP, asigna una GAL, una libreta de direcciones sin conexión (OAB), una lista de sala y una o varias listas de direcciones a la directiva. A continuación, puede asignar la ABP a los usuarios de buzones de correo, proporcionándoles acceso a una GAL personalizada en Outlook y Outlook en la Web. Los administradores pueden configurar directivas de libreta de direcciones con Windows PowerShell remoto. Para obtener más información sobre las directivas de libreta de direcciones, vea [Libretas de direcciones en Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=394203).
  
### <a name="address-lists"></a>Listas de direcciones

Exchange Online admite la personalización de listas de direcciones y Gal. Una GAL es un directorio de toda la organización de todos los usuarios habilitados para correo, grupos de distribución y contactos externos. Los administradores pueden ocultar usuarios, grupos de distribución y contactos de la GAL mediante la herramienta de sincronización de directorios o Windows PowerShell remoto.
  
### <a name="hierarchical-address-books"></a>Libretas de direcciones jerárquicas

 Hierarchical address books allow end users to browse for recipients in their Exchange organization using an organizational hierarchy. Administrators can customize the address book by seniority and rank rather than alphabetical listings. 
  
### <a name="distribution-groups-global"></a>Grupos de distribución (globales)

Un grupo de distribución (o una lista de distribución) es una recopilación de usuarios, contactos y otros grupos de distribución disponibles para todos los usuarios de una empresa. Los usuarios dirigen el correo electrónico al alias de un grupo de distribución para enviar mensajes a las personas del grupo. Los grupos de distribución son similares a los grupos de distribución personales que las personas crean en Outlook, sólo que sus listas de miembros están disponibles globalmente en la empresa. Los administradores crean grupos de distribución en el Centro de administración de Exchange. Los grupos también se pueden sincronizar con Exchange Online desde Active Directory local. Aparecen en la GAL de Outlook. Exchange Online admite capacidades de grupo de distribución avanzadas, incluyendo las descritas a continuación:
  
- **Restricted distribution groups** By default, anyone can send emails to any distribution group. Administrators can change permissions to allow only specific individuals to send emails to a particular group—for example, to discourage inappropriate use of large distribution lists. Administrators can also block external sources from sending email to distribution groups to help prevent spam. For distribution groups that are synchronized from on-premises Active Directory using the Directory Synchronization tool, the attributes for restriction are synchronized to the cloud automatically. For more information, see [Manage Distribution Groups](https://technet.microsoft.com/library/mt577270%28v=exchg.160%29.aspx).
    
- **Dynamic distribution groups** The membership list for a dynamic distribution group (also known as a dynamic distribution list, or query-based distribution list) is calculated every time a message is sent to the group. This calculation is based on filters and conditions that the administrator defines. They are managed in Exchange Online through remote Windows PowerShell. For more information about dynamic distribution groups, see [Manage Dynamic Distribution Groups](https://technet.microsoft.com/library/bb123722%28v=exchg.160%29.aspx).
    
    > [!IMPORTANT]
    > The Office 365 Directory Synchronization tool ignores dynamic distribution groups in on-premises Active Directory, and does not synchronize these to Exchange Online. Organizations that use the Directory Synchronization tool should use a naming convention that avoids conflicts between the regular distribution groups that are managed on-premises and the dynamic distribution groups that are managed in Exchange Online. 
  
- **Moderated distribution groups** Administrators can select a moderator to regulate the flow of messages to a distribution group. With moderated distribution groups, anyone can email the distribution group alias, but before the message is delivered to the members of the group, a moderator must review and approve it. For more information about moderation, see the Message Approval section in [Manage Distribution Groups](https://technet.microsoft.com/library/mt577270%28v=exchg.160%29.aspx).
    
- **Self-Service distribution groups** Administrators can give users the ability to manage their own distribution group membership from a web-based interface. Users can be given permissions to create, delete, join, or leave distribution groups. These capabilities are enabled by default for all Exchange Online users. Administrators can disable them so that only the IT department can manage distribution groups, if desired. They can also create naming policies to standardize and manage the names of distribution groups that their users create. For example, they can add a specific prefix or suffix to the distribution group name when it is created, or block specific words from being used in the group's name. 
    
    > [!IMPORTANT]
    > Self-service capabilities are not available for distribution groups that are synchronized from on-premises Active Directory to Exchange Online. Organizations that use Directory Synchronization should use a naming convention that avoids conflicts between distribution groups that are managed on-premises and distribution groups that are managed in the cloud. 
  
### <a name="external-contacts-global"></a>Contactos externos (globales)

Un contacto externo es un registro con información acerca de una persona que trabaja fuera de una organización concreta. Los contactos externos son similares a los grupos personales que las personas crean en Outlook, sólo que están disponibles globalmente en la empresa. Los administradores crean contactos externos con el Centro de administración de Exchange o Windows PowerShell remoto. Estos contactos también se pueden sincronizar con Exchange Online desde Active Directory local. Aparecen en la GAL de Outlook.
  
Para obtener más información sobre contactos externos, consulte [Crear una relación de organización en Exchange Online](https://technet.microsoft.com/library/jj916671%28v=exchg.150%29.aspx).
  
## <a name="calendar-and-scheduling"></a>Calendario y programación

### <a name="resource-mailboxes"></a>Buzones de recursos

Los buzones de recursos (como las salas de conferencias y los equipamientos físicos) representan las salas de reunión de una empresa u otras instalaciones o recursos. Los usuarios pueden reservar salas o recursos agregando el alias de correo electrónico del recurso a las convocatorias de reunión en Outlook o en Outlook en la Web. Las salas de conferencias y los recursos aparecen en la GAL de Outlook y Outlook en la Web.
  
Administrators create resource mailboxes using the Exchange admin center or remote Windows PowerShell. The mailboxes can also be synchronized with Exchange Online from on-premises Active Directory.
  
Para obtener más información acerca de buzones de recursos, consulte:
  
- [Creación y administración de buzones de sala](https://go.microsoft.com/fwlink/?LinkId=717533&amp;clcid=0x409)
    
- [Administrar buzones de equipamiento](https://go.microsoft.com/fwlink/?LinkId=717534)
    
### <a name="conference-room-management"></a>Administración de la sala de conferencias

Exchange Online includes the Resource Booking Attendant (RBA), which automates scheduling of conference rooms and other resources. A resource mailbox that is RBA-configured accepts, declines, or acknowledges meeting requests from a meeting organizer based on the resource's calendar availability. 
  
Los administradores pueden personalizar las respuestas automatizadas de las salas de conferencias y configurar las directivas de reserva en Outlook en la Web. Estas directivas incluyen quién puede programar el recurso, cuándo se puede programar, la información de la reunión que es visible en el calendario de recursos y el porcentaje de conflictos de programación que se permite. Los administradores pueden deshabilitar el Operador para reserva de recursos y asignar usuarios específicos para que administren manualmente las solicitudes de las salas de conferencias.
  
Los administradores deben definir y administrar la configuración de RBA a través de Windows PowerShell remoto.
  
### <a name="out-of-office-replies"></a>Respuestas de fuera de la oficina

Out-of-office messages are automatic replies to incoming messages that Exchange Online sends on behalf of a user. Users can schedule out-of-office messages in advance, with specific start and end times, and can configure separate out-of-office messages for internal and external recipients. They can also set out-of-office messages from mobile devices that support this Exchange ActiveSync feature. Junk-email and mailing-list awareness within Exchange Online prevents users from sending external out-of-office messages to extended mailing lists and potential spammers. Administrators can also prevent users from sending out-of-office messages to external users using remote Windows PowerShell.
  
### <a name="calendar-sharing"></a>Uso compartido de calendarios

Los usuarios pueden compartir su calendario personal de dos maneras:
  
- **Uso compartido de calendario federado** La federación hace referencia a la infraestructura de confianza subyacente que es compatible con el uso compartido federado, un método sencillo para que los usuarios de Exchange compartan la información de disponibilidad de datos de calendario y de contactos con los destinatarios en otras organizaciones federadas externas. Esto incluye organizaciones de Exchange Online u organizaciones que ejecuten Exchange Server 2010 o Exchange Server 2013 local. Los administradores de Exchange online no necesitan configurar una confianza con Microsoft Federation Gateway porque esta confianza está preconfigurada para todos los clientes de Exchange Online cuando se crea el servicio de Microsoft. Una directiva de uso compartido predeterminada permite a los usuarios enviar invitaciones de uso compartido de calendarios desde Outlook en la web o Outlook 2010. Los administradores usan Windows PowerShell remoto para deshabilitar esta directiva o para configurar el nivel de información de disponibilidad del calendario que los usuarios pueden compartir. Los administradores también pueden crear una relación entre organizaciones con otras organizaciones federadas, que permita el nivel deseado de información de confidencialidad de cada usuario que sea visible a través de la organización sin la necesidad de que el usuario comparta la invitación. En el ámbito de las directivas de uso compartido definidas por el administrador, los usuarios pueden limitar individualmente el detalle de su uso compartido. 
    
- **Uso compartido de calendario de Internet** Exchange Online permite a los usuarios publicar sus calendarios con el formato iCal para el acceso anónimo de cualquier persona dentro y fuera de la organización. Los destinatarios pueden utilizar Exchange, otra plataforma o simplemente un explorador web. Los usuarios de Exchange Online también pueden suscribirse a calendarios que otros usuarios han publicado en ubicaciones de Internet a través de iCal. Este uso compartido de calendarios personal es diferente al uso compartido del calendario federado, que lo configura un administrador y proporciona el uso compartido de disponibilidad entre organizaciones. Ningún usuario puede publicar datos de calendario en formato de iCal hasta que el administrador haya establecido y aplicado una directiva de uso compartido que la permita. Los administradores pueden deshabilitar la publicación de y las suscripciones de iCal para los usuarios de la organización usando un Windows PowerShell remoto.
    
Para obtener más información sobre el uso compartido federado, vea [Uso compartido en Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271774).
  
### <a name="outlook-2010-room-finder"></a>Buscador de salas de Outlook 2010

Exchange Online supports the Room Finder feature of Outlook 2010, which arranges rooms into lists (for example, a list called "Building 5 rooms") to make it easier to find a nearby room when scheduling a meeting. To appear in the room list, a distribution group must be specially marked using one of two methods: 
  
- Una nueva lista de salas se puede crear mediante Windows PowerShell remoto. 
    
- Cualquier grupo de distribución que sólo contenga salas se puede convertir en una lista de salas mediante el Windows PowerShell remoto.
    
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, las opciones independientes y las soluciones locales, consulte [Exchange Online Service Description](exchange-online-service-description.md).
  