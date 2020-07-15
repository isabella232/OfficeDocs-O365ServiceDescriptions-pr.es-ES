---
title: Planificación e implementación
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-planning-and-deployment
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: e44e5e61-1f5d-4e68-981d-77a42f0ea0d4
ms.openlocfilehash: e722bec332e67e93647b10bbbf4916e7e059c1b7
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132664"
---
# <a name="planning-and-deployment"></a>Planificación e implementación

## <a name="planning-for-service-changes-and-growth"></a>Planificación para el crecimiento y cambios en el servicio

Las organizaciones deben elegir las opciones de migración en función de sus sistemas de correo electrónico de origen, del estado final deseado (hospedado total o parcialmente), del número de usuarios que se vayan a migrar y de lo rápido que se deba alcanzar el estado final.
  
## <a name="deployment-options"></a>Opciones de implementación

- **Implementación basada solo en la nube** Todos los buzones de usuario de la organización están hospedados en Exchange Online. 
    
- **Implementación híbrida de Exchange** Algunos buzones de usuario de la organización están hospedados en una organización local de Exchange y otros en Exchange Online. 
    
### <a name="cloud-only"></a>Solo de nube

A cloud-only deployment is one where your organization in the Exchange Online service isn't connected with an on-premises Exchange organization. All users and mailboxes are hosted and managed in Exchange Online and Office 365.
  
### <a name="hybrid"></a>Híbrido

Available for Microsoft Exchange 2003, Exchange 2007, Exchange 2010 and Exchange 2013 on-premises organizations, a hybrid deployment offers either a long-term coexistence configuration with some mailboxes hosted on-premises and some mailboxes hosted in Exchange Online or a migration path to hosting all user mailboxes in Exchange Online. A hybrid deployment offers organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. Hybrid deployment features include secure mail transport, shared calendar free/busy information, and message tracking between the on-premises and Exchange Online organizations.
  
For more information about hybrid deployments, see [Exchange Server 2013 Hybrid Deployments](https://go.microsoft.com/fwlink/p/?LinkId=287035). If you are using Office 365 operated by 21Vianet, see [Configuring Exchange hybrid deployment features with Office 365 operated by 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733373&amp;clcid=0x409).
  
> [!IMPORTANT]
> On-premises Exchange 2003 organizations must install at least one Exchange 2010 Client Access/Mailbox server to configure a hybrid deployment with Exchange Online. On-premises Exchange 2007 organizations must install at least one Exchange 2010 or Exchange 2013 Client Access and Mailbox server to configure a hybrid deployment with Exchange Online. On-premises Exchange 2010 and Exchange 2013 organizations natively support hybrid deployments with Exchange Online. For more information about Exchange server compatibility in hybrid deployments, see [Hybrid Deployment Prerequisites](https://go.microsoft.com/fwlink/p/?LinkId=243541)> On-premises Exchange organizations must configure their organization for a hybrid deployment. We strongly recommend that administrators use the Exchange Server Deployment Assistant and the Hybrid Configuration Wizard to configure the hybrid deployment. Learn more at [Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036)
  
## <a name="migration-options"></a>Opciones de migración

Organizations should choose migration options based on their source email systems, the desired end state (fully hosted or partially hosted), the number of users to migrate, and how quickly the end state needs to be reached. Possible migration options are:
  
- **Migración IMAP** Los datos de los buzones se migran desde sistemas de correo electrónico basados en IMAP a Exchange Online. 
    
- **Migración de transferencia de Exchange** Los buzones se migran desde Exchange Server 2003, Exchange Server 2007, Exchange Server 2010, Exchange 2013 y los sistemas hospedados de Exchange a Exchange Online en una sola migración de transferencia. 
    
- **Migración de Exchange por etapas** Se realiza una migración por etapas para migrar los buzones desde Exchange Server 2003 o Exchange Server 2007 con las herramientas de migración basadas en web. Apenas se realizan cambios en la infraestructura local. 
    
- **Remote move migration** Migrate on-premises Exchange mailboxes to Exchange Online in an Exchange hybrid deployment. You must have an Exchange hybrid deployment to use a remote move migration. 
    
Para obtener más información sobre cómo migrar correo electrónico y buzones a Exchange Online, consulte [Migración de buzones a Exchange Online ](https://support.office.com/en-us/article/-a3e3bddb-582e-4133-8670-e61b9f58627e).
  
### <a name="imap-migration"></a>Migración de IMAP

Exchange Online offers a web-based tool for migrating mailbox data from email systems that support IMAP. It guides administrators through the following migration steps: 
  
1. Crear buzones vacíos en la nube para los usuarios de la organización (generalmente, para hacer esto se carga un archivo .csv o se usa Windows PowerShell en remoto).
    
2. Escribir la configuración de conexión del servidor remoto.
    
3. Usar un archivo CSV para especificar los buzones cuyos datos se van a migrar a los buzones de Exchange Online.
    
4. Después de indicar esta información, Exchange Online comienza a migrar el contenido de los buzones a través de IMAP (los elementos de calendario, contactos, tareas y otros elementos que no son de correo no se migran).
    
Para obtener más información sobre la migración de IMAP, consulte [Migración de correo electrónico de un servidor IMAP a buzones de Exchange Online](https://support.office.com/en-ie/article/Migrate-your-IMAP-mailboxes-to-Office-365-3fe19996-29bc-4879-aab9-5a622b2f1481) y [Migrar otros tipos de buzones IMAP](https://support.office.com/en-ie/article/Migrate-other-types-of-IMAP-mailboxes-to-Office-365-58890ccd-ce5e-4d94-be75-560a3b70a706).
  
> [!IMPORTANT]
> Para evitar el uso excesivo de los recursos del servidor remoto y del ancho de banda durante la migración, Exchange Online crea un máximo de 10 conexiones con el servidor IMAP. 
  
### <a name="cutover-exchange-migration"></a>Migración de Exchange de traslado

Exchange Online offers a web-based tool for migrating data from on-premises Exchange Server 2003, Exchange Server 2007, or Exchange Server 2010 environments. It guides an administrator through the following migration steps:
  
1. Mediante el uso de la dirección de correo electrónico y de las credenciales para una cuenta de administrador local, Exchange Online se conecta a la organización de correo electrónico local mediante el servicio Detección automática.
    
2. Exchange Online usa una conexión RPC/HTTP para leer la información de directorios del servidor remoto y crea buzones en Exchange Online.
    
3. Exchange Online synchronizes the mailbox content to the cloud mailboxes. Users remain connected to their original mailboxes while their data is being migrated to Exchange Online.
    
4. Después de completar la migración inicial, los cambios que se produzcan se sincronizan en la nube cada 24 horas hasta que el administrador detenga o elimine el lote de migración.
    
Para cambiar a los usuarios a sus buzones en la nube, los administradores configuran su registro MX para que apunte a Microsoft y vuelva a configurar los perfiles de los usuarios en Outlook. Cuando los usuarios se cambian a los buzones en la nube, las carpetas locales sin conexión (archivos .ost) se vuelven a sincronizar, lo que origina la descarga del correo migrado en la estación de trabajo del cliente. Los usuarios pueden responder a mensajes antiguos de sus buzones después de la migración.
  
Para obtener más información sobre una migración total de Exchange, consulte [Lo que debe saber sobre la migración total de correo electrónico a Office 365](https://support.office.com/en-us/article/What-you-need-to-know-about-a-cutover-email-migration-to-Office-365-961978ef-f434-472d-a811-1801733869da).
  
> [!IMPORTANT]
> An organization can migrate a maximum of 2,000 Exchange 2003, Exchange 2007, Exchange 2010, or Exchange 2013 mailboxes to the cloud using a cutover Exchange migration. > Exchange Online must connect to an on-premises Exchange Server, so the on-premises server must have a certificate issued by a trusted certificate authority and a public IP address. 
  
### <a name="staged-exchange-migration"></a>Migración de Exchange preconfigurada

With a staged migration, users can be migrated to the cloud using the web-based Exchange migration tool and the Directory Synchronization tool. Instead of migrating all users at once, like a cutover Exchange migration, administrators migrate users in batches. This is accomplished by uploading a .csv file to specify a partial list of users to migrate. In a staged migration, all of the users in an organization can share the same email domain name.
  
Staged Exchange migration requires administrators to use the Online Services Directory Synchronization tool. This provides users with a unified Global Address List (GAL) where the online environment is continuously synchronized with the on-premises environment.
  
Para obtener más información sobre las migraciones preconfiguradas de Exchange, consulte [Lo que debe saber sobre la migración preconfigurada de correo electrónico](https://support.office.com/en-ie/article/What-you-need-to-know-about-a-staged-email-migration-to-Office-365-7e2c82be-5f3d-4e36-bc6b-e5b4d411e207).
  
> [!IMPORTANT]
> Organizations can't use a staged Exchange migration to migrate Exchange 2010 and Exchange 2013 mailboxes. If you have fewer than 2,000 Exchange 2010 or Exchange 2013 mailboxes in your organization, you can use a cutover Exchange migration. If you have more than 2,000 Exchange 2010 or Exchange 2013 mailboxes, you can implement a hybrid deployment. > During migration, administrators must use the Online Services Directory Synchronization tool to provide users with a unified Global Address List where the online environment is continuously synchronized with the on-premises environment. 
  
## <a name="migration-tools"></a>Herramientas de migración

Microsoft provides several tools to help migrate an existing email environment to Exchange Online. Which ones are appropriate depends on the organization's current environment and deployment goals:
  
- **Migration dashboard** Administrators can use the Migration dashboard in the Exchange admin center to manage mailbox migration to Exchange Online in a cutover or staged Exchange migration. Administrators can also use the dashboard to migrate the contents of users' mailboxes from an on-premises IMAP server to existing Exchange Online mailboxes. The dashboard gives administrators the following capabilities: 
    
  - **Create and start multiple migration batches** Administrators can create and queue up to 100 migration batches. Only one migration batch runs at a time, but administrators can queue up multiple batches, so when a migration batch is finished running the next batch in the queue starts. 
    
  - **Restart a migration batch with failures** After the initial synchronization for a migration batch, where items are copied from on-premises mailboxes to the cloud mailboxes for each user in the migration batch, some mailboxes may fail synchronization. Administrators can restart that migration batch to try to synchronize the failed mailboxes. 
    
  - **Obtener detalles acerca de los elementos omitidos** Para las migraciones IMAP, por traslado y por fases, el panel de migración muestra información sobre los elementos específicos que se omitieron, incluidos el motivo y la ubicación del elemento en el buzón de correo del usuario. 
    
  - **Abrir informes de migración** Los administradores pueden abrir estadísticas de migración o el informe de errores de migración de un lote de migración directamente desde el panel. 
    
  - **Editar un lote de migración** Si un lote de migración para una migración de Exchange por etapas o una migración IMAP se encuentra en la cola de migración pero no se está ejecutando actualmente, los administradores pueden editarlo. 
    
- **Azure Active Directory Sync tool** The Azure Active Directory Sync tool plays an important role in migration to hybrid email scenarios that utilize both Exchange Online and an on-premises Exchange Server. The tool performs a one-way synchronization from on-premises Active Directory to Exchange Online. After migration is complete, administrators only need to use Exchange Online to manage Active Directory users and groups. The tool also provides users with a unified Global Address List where the online environment is continuously synchronized with the on-premises environment. 
    
    Para obtener más información sobre Herramienta de sincronización de Microsoft Azure Active Directory, vea el [Plan de desarrollo de sincronización de directorios](https://go.microsoft.com/fwlink/p/?LinkId=287034).
    
- **Hybrid Configuration Wizard** The Hybrid Configuration Wizard streamlines the hybrid deployment process by simplifying the on-premises and Exchange Online configuration of features and services. Introduced as part of Exchange Server 2010 Service Pack 2, the Hybrid Configuration Wizard is run only in on-premises organizations and has the following components: 
    
  - Un asistente del Centro de administración de Exchange (EAC) que guía a los administradores por todo el proceso de un extremo a otro para configurar una implementación híbrida.
    
  - Un conjunto de comandos del Shell de administración de Exchange (EMS) que organizan el proceso de configuración.
    
    Para obtener más información sobre el Asistente para la configuración híbrida, vea [Asistente para la configuración híbrida](https://go.microsoft.com/fwlink/p/?LinkId=271734).
    
- **Remote Windows PowerShell** As part of the Exchange Online December 2011 Service Update, remote Windows PowerShell can be used to help troubleshoot migration errors. For instance, administrators can display diagnostic information for migration batches, as well as migration statistics and diagnostic information for users based on their primary SMTP addresses. 
    
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, las opciones independientes y las soluciones locales, consulte [Descripción del servicio Exchange Online](exchange-online-service-description.md).
  

