---
title: Características de cumplimiento y seguridad en Archivado de Exchange Online
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- compliance-and-security-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7482322a-39fe-4a99-b29c-63cb1bc3cf1f
ms.openlocfilehash: c54ec8f37c6f881dc934307f7784f79d01c7a878
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036971"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a>Características de cumplimiento y seguridad en Archivado de Exchange Online

## <a name="compliance-features-in-exchange-online-archiving"></a>Características de cumplimiento en Archivado de Exchange Online

En las siguientes secciones se describen las características de cumplimiento de Archivado de Exchange Online (EOP) de Microsoft.
  
### <a name="retention-policies"></a>Directivas de retención
<a name="BKMK_Retentionpolicies"> </a>

Archivado de Exchange Online ofrece directivas de retención para ayudar a las organizaciones a reducir las responsabilidades asociadas con el correo electrónico y otras comunicaciones. Con estas directivas, los administradores pueden aplicar la configuración de retención a carpetas específicas de los buzones de los usuarios. Los administradores también pueden ofrecer a los usuarios un menú de directivas de retención y permitirles aplicarlas a elementos, conversaciones o carpetas específicos de Outlook 2010 o posterior, o bien Outlook Web App. En Archivado de Exchange Online, los administradores administran políticas de retención desde la infraestructura local.
  
Archivado de Exchange Online ofrece dos tipos de directivas: de archivado y de eliminación. Ambos tipos se pueden aplicar en el mismo elemento o carpeta. Por ejemplo, un usuario puede etiquetar un mensaje de correo electrónico para que se transfiera automáticamente a su archivo personal al transcurrir un cierto número de días y se elimine el momento especificado.
  
Con Outlook 2010 y versiones posteriores, y Outlook Web App, los usuarios pueden aplicar las directivas de retención a carpetas, conversaciones y mensajes individuales, así como ver las directivas de retención aplicadas y las fechas de eliminación fijadas para los mensajes. Los usuarios de otros clientes de correo electrónico pueden eliminar o archivar los mensajes conforme a las directivas de retención que les suministren los administradores, aunque no disfrutarán del mismo grado de visibilidad y control.
  
Las capacidades de directivas de retención que se ofrecen en Archivado de Exchange Online son las mismas que se ofrecen en Exchange Server 2010 Service Pack 2 (SP2) y versiones posteriores. Los administradores pueden administrar las directivas de retención desde Exchange Server 2010 local y entornos posteriores. Las carpetas administradas, un enfoque anterior para la administración de registros de mensajería introducido en Exchange 2007, no están disponibles y no son compatibles con el Archivado de Exchange Online. Para obtener más información, vea [Etiquetas de retención y directivas de retención en Exchange 2016](https://go.microsoft.com/fwlink/p/?LinkID=314153).
  
### <a name="in-place-hold-and-litigation-hold"></a>Conservación local y retención por juicio
<a name="BKMK_In_placehold"> </a>

Cuando existen sospechas fundadas de posibles litigios, se solicita a las organizaciones que conserven toda la información almacenada electrónicamente (ESI), incluso el correo electrónico que sea relevante para el caso. Dichas sospechas pueden tener lugar antes de que se conozcan los pormenores del caso, por lo que se suele conservar gran cantidad de material. Las organizaciones pueden conservar todo el correo electrónico relacionado con un tema concreto o el perteneciente a ciertos usuarios.
  
> [!NOTE]
> La conservación local y la retención por juicio no se aplican actualmente a los correos electrónicos enviados mediante clientes POP o IMAP ni mediante aplicaciones personalizadas que usan el protocolo SMTP. 
  
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
  
### <a name="in-place-ediscovery"></a>Exhibición de documentos electrónicos local
<a name="BKMK_In_placehold"> </a>

Archivado de Exchange Online admite In-Place eDiscovery para buscar el contenido de buzones de una organización. Mediante el Centro de administración de Exchange o Windows PowerShell remoto en un servidor de Exchange 2013 local, los administradores o los administradores de detección autorizados pueden buscar diversos elementos del buzón, como, por ejemplo, mensajes de correo electrónico, archivos adjuntos, citas del calendario, tareas y contactos. In-Place eDiscovery permite realizar búsquedas simultáneas en los archivos y buzones principales. Entre las capacidades de filtrado enriquecidas se incluyen remitente, destinatario, tipo de mensaje, fecha de envío, fecha de recepción, copia y copia oculta, junto con la sintaxis del lenguaje de consulta de palabras clave (KQL). Para obtener más información, vea [In-Place eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=314169).
  
Se puede usar el Centro de administración de Exchange y Windows PowerShell remoto para realizar búsquedas en hasta 5000 buzones a la vez en una búsqueda de In-Place eDiscovery. Para obtener información detallada sobre cómo usar Windows PowerShell remoto para ejecutar búsquedas de In-Place eDiscovery, vea [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170). 
  
> [!NOTE]
> En Windows PowerShell remoto, se puede usar el cmdlet  `Search-Mailbox` para buscar en más de 5000 buzones. Para obtener más información sobre cómo realizar búsquedas en gran cantidad de buzones con Windows PowerShell remoto, vea [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171). 
  
Se puede obtener una vista previa de los resultados de las búsquedas de In-Place eDiscovery en el Centro de administración de Exchange; también se pueden exportar a un archivo .pst o copiar a un tipo especial de buzón denominado buzón de detección. Los administradores o los responsables del cumplimiento de normas pueden conectarse al buzón de detección para revisar los mensajes. Para obtener más información, vea [Crear una búsqueda de In-Place eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=314172).
  
> [!NOTE]
> Al copiar los resultados de la búsqueda para una búsqueda de exhibición de documentos electrónicos en contexto realizada en buzones locales y basados en la nube o en archivos, debe seleccionar un buzón de detección local. Los mensajes del buzón primario local y del archivo basado en la nube se copian al buzón de detección local. 
  
Los administradores también pueden buscar y eliminar mensajes de correo electrónico inapropiados enviados a varios buzones de sus organizaciones. Por ejemplo, si por accidente se envía información confidencial de salarios a todos los empleados, un administrador puede eliminar el correo electrónico de los buzones de los usuarios. Este tipo de búsqueda no está disponible en el Centro de administración de Exchange. Se debe realizar por medio de PowerShell remoto. Para obtener más información sobre cómo eliminar mensajes de los buzones de los usuarios, vea [Búsqueda y eliminación de mensajes en Exchange 2016](https://go.microsoft.com/fwlink/p/?LinkId=314173).
  
## <a name="security-features-in-exchange-online-archiving"></a>Características de seguridad de Archivado de Exchange Online

En las siguientes secciones se describen las características de seguridad de Archivado de Exchange Online de Microsoft.
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a>Cifrado entre servidores locales y el Archivado de Exchange Online

Se utiliza TLS para cifrar la conexión entre servidores de correo electrónico a fin de prevenir la suplantación de identidad y proporcionar confidencialidad a los mensajes en tránsito. TLS también se usa para proteger el tráfico de servidores de correo locales a centros de datos de Office 365 para Archivado de Exchange Online.
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a>Cifrado entre clientes y el Archivado de Exchange Online

Las conexiones cliente a Archivado de Exchange Online utilizan los siguientes métodos de cifrado para mejorar la seguridad:
  
- Se utiliza SSL para asegurar el tráfico de Outlook, Outlook Web App y Exchange Web Services con el puerto TCP 443.
    
- Las conexiones cliente a los servidores locales no cambian con la presentación de Archivado de Exchange Online.
    
### <a name="encryption-smime-and-pgp"></a>Cifrado: S/MIME y PGP

Archivado de Exchange Online almacenará mensajes de extensiones seguras multipropósito al correo de Internet (S/MIME). Sin embargo, Archivado de Exchange Online no hospeda funciones S/MIME, no alberga claves públicas ni proporciona repositorio de claves, administración de claves o servicios de directorios de claves porque todos estos servicios están conectados a la infraestructura de Exchange local.
  
De manera similar, Archivado de Exchange Online almacenará mensajes cifrados usando soluciones de terceros del lado cliente, como Pretty Good Privacy (PGP).
  
### <a name="information-rights-management"></a>Information Rights Management

Archivado de Exchange Online no proporciona servicios de Information Rights Management (IRM) hospedados, pero los administradores pueden usar Active Directory Rights Management Services (AD RMS) locales. Si se implementa un servidor AD RMS, Outlook puede comunicarse directamente con ese servidor, lo que permite a los usuarios redactar y leer mensajes protegidos por IRM. Si se configura la interoperabilidad entre el servidor AD RMS y el entorno Exchange local, los usuarios podrán redactar y leer mensajes protegidos por IRM.
  
#### <a name="support-for-irm-in-outlook-web-app"></a>Compatibilidad con IRM en Outlook Web App

Los usuarios pueden leer y crear de forma nativa mensajes protegidos con IRM en Outlook Web App, de igual forma que en Outlook. Es posible acceder a mensajes protegidos con IRM en Outlook Web App con los exploradores Internet Explorer, Firefox, Safari y Chrome (sin necesidad de un complemento). Los mensajes incluyen la búsqueda de texto completo, la vista de conversaciones y el panel de vista previa. La interoperabilidad entre el servidor de Servicios de administración de Active Directory y el entorno Exchange local se debe configurar para habilitar esta posibilidad.
  
#### <a name="irm-search"></a>Búsqueda de IRM

Los mensajes protegidos con IRM están indizados y permiten realizar búsquedas, incluidos los encabezados, el asunto y los datos adjuntos. Los usuarios pueden buscar elementos protegidos con IRM en Outlook y Outlook Web App, y los administradores pueden buscar elementos protegidos con IRM mediante Exhibición de documentos electrónicos local o el cmdlet **Search-Mailbox**. 
  
### <a name="auditing"></a>Auditoría

Archivado de Exchange Online proporciona dos tipos de capacidades de auditoría integradas:
  
- **Registro de auditoría de administradores** El registro de auditoría de administradores permite a los clientes realizar un seguimiento de los cambios realizados por parte de sus administradores en el entorno de Archivado de Exchange Online, incluidos los cambios en los roles de RBAC o en las directivas y la configuración de Exchange. 
    
- **Registro de auditoría de buzones** El registro de auditoría de buzones permite que los clientes lleven un seguimiento del acceso a los buzones por parte de usuarios que no sean el propietario del buzón en cuestión. 
    
Hay disponibles varios informes de auditoría predefinidos en el centro de administración de Exchange, incluidos cambios de rol del administrador, retención por juicio y acceso al buzón de correo de un no propietario. Los administradores pueden filtrar los informes por fecha y rol, y pueden exportar todos los eventos de auditoría para buzones de correo especificados en formato XML a efectos de conservación a largo plazo o informes personalizados.
  
De manera predeterminada, el registro de auditoría de administrador está activado y el registro de auditoría de buzones está desactivado. Los administradores pueden utilizar Windows PowerShell remoto para activar el registro de auditoría de buzones para algunos o todos los buzones de la organización. Para obtener más información, vea [Informes de auditoría de Exchange](https://go.microsoft.com/fwlink/p/?LinkId=314175).
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes de Office 365, las opciones independientes y las soluciones locales, vea [Descripción del servicio de archivado de Exchange Online](exchange-online-archiving-service-description.md).
  

