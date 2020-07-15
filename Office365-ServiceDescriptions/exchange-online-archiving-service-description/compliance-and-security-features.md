---
title: Características de cumplimiento y seguridad en archivado de Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- compliance-and-security-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7482322a-39fe-4a99-b29c-63cb1bc3cf1f
ms.openlocfilehash: b03c74e0c760cf22c12e6973a544553d119471fe
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132744"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a>Características de cumplimiento y seguridad en archivado de Exchange Online

## <a name="compliance-features-in-exchange-online-archiving"></a>Características de cumplimiento en Archivado de Exchange Online

En las siguientes secciones se describen las características de cumplimiento de Archivado de Exchange Online (EOP) de Microsoft.
  
### <a name="retention-policies"></a>Directivas de retención

Archivado de Exchange Online ofrece directivas de retención para ayudar a las organizaciones a reducir las responsabilidades asociadas con el correo electrónico y otras comunicaciones. Con estas directivas, los administradores pueden aplicar la configuración de retención a carpetas específicas de los buzones de los usuarios. Los administradores también pueden proporcionar a los usuarios un menú de directivas de retención y permitirles aplicar las directivas a elementos, conversaciones o carpetas específicos mediante Outlook 2010 o versiones posteriores o Outlook en la Web. En Archivado de Exchange Online, los administradores administran políticas de retención desde la infraestructura local.
  
Exchange Online Archiving offers two types of policies: archive and delete. Both types can be applied to the same item or folder. For example, a user can tag an email message so that it is automatically moved to the personal archive in a specified number of days and deleted after another span of days.
  
Con Outlook 2010 y versiones posteriores y Outlook en la web, los usuarios pueden aplicar directivas de retención a carpetas, conversaciones o mensajes individuales y también pueden ver las directivas de retención aplicadas y las fechas de eliminación esperadas en los mensajes. Los usuarios de otros clientes de correo electrónico pueden eliminar o archivar los mensajes conforme a las directivas de retención que les suministren los administradores, aunque no disfrutarán del mismo grado de visibilidad y control.
  
The retention policy capabilities offered in Exchange Online Archiving are the same as those offered in Exchange Server 2010 Service Pack 2 (SP2) and later. Administrators can manage retention policies from on-premises Exchange Server 2010 and later environments. Managed Folders, an older approach to messaging records management that was introduced in Exchange 2007, are not available in and not compatible with Exchange Online Archiving. For more details, see [Retention Tags and Retention Policies](https://go.microsoft.com/fwlink/p/?LinkID=314153).
  
### <a name="in-place-hold-and-litigation-hold"></a>Retención local y retención por juicio

When a reasonable expectation of litigation exists, organizations are required to preserve electronically stored information (ESI), including email that's relevant to the case. This expectation can occur before the specifics of the case are known, and preservation is often broad. Organizations may preserve all email related to a specific topic, or all email for certain individuals.
  
En Exchange Online, puede usar la retención local o por juicio para realizar las tareas siguientes:
  
- Permitir que los usuarios se marquen como suspendidos y preservar los elementos del buzón inalterados.
    
- Preservar los elementos de buzón eliminados por los usuarios o por procesos de supresión automática como MRM.
    
- Guardar una copia de los elementos originales de un buzón para protegerlos frente a alteraciones, cambios de los usuarios o procesos automáticos.
    
- Preservar elementos indefinidamente o durante un tiempo concreto.
    
- Mantener activa la administración MRM de modo que las retenciones resulten transparentes para el usuario.
    
- Usar la exhibición de documentos electrónicos local para buscar elementos del buzón, incluidos los que se encuentran en retención.
    
También puede usar la retención local para:
  
- Buscar y retener elementos que cumplan los criterios especificados.
    
- Establecer varias retenciones locales para un usuario conforme a distintos casos o investigaciones.
    
> [!NOTE]
> Si coloca un buzón en Conservación local o retención por juicio, la conservación o retención se aplica al buzón principal y al buzón de archivo. 
  
Para obtener más información, vea [Conservación local y retención por juicio](https://go.microsoft.com/fwlink/p/?LinkId=271746).
  
> [!NOTE]
> La cuota predeterminada de la carpeta Elementos recuperables es de 100 GB para los usuarios de Archivado de Exchange Online. 
  
### <a name="in-place-ediscovery"></a>Exhibición de documentos electrónicos en contexto

Exchange Online Archiving supports In-Place eDiscovery for searching the contents of mailboxes in an organization. Using the Exchange admin center or remote Windows PowerShell from an on-premises Exchange 2013 server, administrators or authorized Discovery managers can search a variety of mailbox items - including email messages, attachments, calendar appointments, tasks, and contacts. In-Place eDiscovery can search simultaneously across primary mailboxes and archives. Rich filtering capabilities include sender, receiver, message types, sent date, received date, carbon copy, and blind carbon copy, along with Keyword Query Language (KQL) syntax. For more details, see [In-Place eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=314169).
  
The Exchange admin center and remote Windows PowerShell can be used to search up to 5,000 mailboxes at a time in an In-Place eDiscovery search. For details about using remote Windows PowerShell to run In-Place eDiscovery searches, see [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170). 
  
> [!NOTE]
> In remote Windows PowerShell, the  `Search-Mailbox` cmdlet can be used to search more than 5,000 mailboxes. For details about searching large numbers of mailboxes using remote Windows PowerShell, see [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171). 
  
Results of an In-Place eDiscovery search can be previewed in the Exchange admin center, exported to a .pst file, or copied to a special type of mailbox, called a discovery mailbox. Administrators or compliance officers can connect to the discovery mailbox to review messages. For details, see [Create an In-Place eDiscovery Search](https://go.microsoft.com/fwlink/p/?LinkId=314172).
  
> [!NOTE]
> When copying search results for an In-Place eDiscovery search performed across on-premises and cloud-based mailboxes or archives, you must select an on-premises discovery mailbox. Messages from the on-premises primary mailbox and the cloud-based archive are copied to the on-premises discovery mailbox. 
  
Administrators can also search for and delete inappropriate email messages sent to multiple mailboxes across their organizations. For example, if confidential salary information was accidentally sent to all employees, an administrator can delete the email from the users' mailboxes. This type of search is not available in the Exchange admin center. It must be performed using Remote PowerShell. For details on how to delete messages from users' mailboxes, see [Search and Delete Messages](https://go.microsoft.com/fwlink/p/?LinkId=314173).
  
## <a name="security-features-in-exchange-online-archiving"></a>Características de seguridad de Archivado de Exchange Online

En las siguientes secciones se describen las características de seguridad de Archivado de Exchange Online de Microsoft.
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a>Cifrado entre servidores locales y el Archivado de Exchange Online

Se utiliza TLS para cifrar la conexión entre servidores de correo electrónico a fin de prevenir la suplantación de identidad y proporcionar confidencialidad a los mensajes en tránsito. TLS también se usa para proteger el tráfico del servidor de correo local a los centros de recursos de Microsoft para el archivado de Exchange Online.
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a>Cifrado entre clientes y el Archivado de Exchange Online

Las conexiones cliente a Archivado de Exchange Online utilizan los siguientes métodos de cifrado para mejorar la seguridad:
  
- SSL se usa para proteger Outlook, Outlook en la web y el tráfico de los servicios Web de Exchange mediante el puerto TCP 443.
    
- Las conexiones cliente a los servidores locales no cambian con la presentación de Archivado de Exchange Online.
    
### <a name="encryption-smime-and-pgp"></a>Cifrado: S/MIME y PGP

Exchange Online Archiving will store Secure/Multipurpose Internet Mail Extensions (S/MIME) messages. However, Exchange Online Archiving does not host S/MIME functions or host the public keys, nor does it provide key repository, key management, or key directory services because all of these services attach to the on-premises Exchange infrastructure.
  
De manera similar, Archivado de Exchange Online almacenará mensajes cifrados usando soluciones de terceros del lado cliente, como Pretty Good Privacy (PGP).
  
### <a name="information-rights-management"></a>Information Rights Management

Exchange Online Archiving does not provide hosted Information Rights Management (IRM) services, but administrators can use on-premises Active Directory Rights Management Services (AD RMS). If an AD RMS server is deployed, Outlook can communicate directly with that server, enabling users to compose and read IRM-protected messages. If interoperability between the AD RMS server and the on-premises Exchange environment is configured, users will be able to compose and read IRM-protected messages.
  
#### <a name="support-for-irm-in-outlook-on-the-web"></a>Compatibilidad con IRM en Outlook en la web

Los usuarios pueden leer y crear mensajes protegidos con IRM de forma nativa en Outlook en la web, tal y como pueden hacerlo en Outlook. Se puede tener acceso a los mensajes protegidos con IRM en Outlook en la web a través de Internet Explorer, Firefox, Safari y Chrome (sin necesidad de un complemento). Los mensajes incluyen la búsqueda de texto completo, la vista de conversaciones y el panel de vista previa. La interoperabilidad entre el servidor de Servicios de administración de Active Directory y el entorno Exchange local se debe configurar para habilitar esta posibilidad.
  
#### <a name="irm-search"></a>Búsqueda de IRM

Los mensajes protegidos con IRM están indizados y permiten realizar búsquedas, incluidos los encabezados, el asunto y los datos adjuntos. Los usuarios pueden buscar elementos protegidos por IRM en Outlook y Outlook en la web, y los administradores pueden buscar elementos protegidos con IRM mediante la exhibición de documentos electrónicos local o el cmdlet **Search-Mailbox** .
  
### <a name="auditing"></a>Auditoría

Archivado de Exchange Online proporciona dos tipos de capacidades de auditoría integradas:
  
- **Registro de auditoría de administradores** El registro de auditoría de administradores permite a los clientes realizar un seguimiento de los cambios realizados por parte de sus administradores en el entorno de Archivado de Exchange Online, incluidos los cambios en los roles de RBAC o en las directivas y la configuración de Exchange. 
    
- **Registro de auditoría de buzones** El registro de auditoría de buzones permite que los clientes lleven un seguimiento del acceso a los buzones por parte de usuarios que no sean el propietario del buzón en cuestión. 
    
Several predefined audit reports are available in the Exchange admin center, including Administrator Role Changes, Litigation Hold, and Non-Owner Mailbox Access. Administrators can filter reports by date and role, and they can export all audit events for specified mailboxes in XML format for long-term retention or custom reporting.
  
Administrator audit logging is on by default, and mailbox audit logging is off by default. Administrators can use remote Windows PowerShell to enable mailbox audit logging for some or all mailboxes in their organization. For more information, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=314175).
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, las opciones independientes y las soluciones locales, consulte [Descripción del servicio de archivado de Exchange Online](exchange-online-archiving-service-description.md).
  

