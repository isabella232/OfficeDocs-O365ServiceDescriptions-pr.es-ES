---
title: Regulación de mensajes y cumplimiento
ms.author: office365servicedesc
author: pamelaar
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-message-policy-recovery-and-compliance
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5c43c8eb-f8f7-4b5a-a743-b1dab7dc2fc8
ms.openlocfilehash: 5565085472d43230f9059e1dcac115105a2e20d5
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132704"
---
# <a name="message-policy-and-compliance"></a>Regulación de mensajes y cumplimiento

## <a name="archiving-exchange-online-based-mailboxes"></a>Archivado de buzones basados en Exchange Online

Exchange Online mailboxes reside in the cloud, and archiving them requires unique hosting environments. In some cases, Exchange Online can also be used to archive on-premises mailboxes in the cloud. The options for archiving with Exchange Online are described in this section.
  
Exchange Online ofrece capacidades de archivado integradas para buzones basados en la nube, incluido un archivo local que brinda a los usuarios un espacio muy conveniente para almacenar mensajes de correo electrónico antiguos. Un archivo local es un tipo especial de buzón de correo que aparece junto a las carpetas de buzones principales de un usuario en Outlook y Outlook en la Web. Los usuarios pueden tener acceso al archivo y buscar en él de la misma manera en que con sus buzones principales. La funcionalidad disponible depende del cliente en uso:
  
- **Outlook 2016, outlook 2013, outlook 2010 y Outlook en la web** Los usuarios tienen acceso a todas las características del archivo, así como las características de cumplimiento relacionadas, como el control sobre la retención y las directivas de archivo. 
    
- **Outlook 2007** Users have basic support for the In-Place Archive, but not all archiving and compliance features are available. For example, users cannot apply retention or archive policies to mailbox items and must rely on administrator-provisioned policies instead. 
    
Los administradores usan el Centro de administración de Exchange o Windows PowerShell remoto para habilitar la característica de archivo personal para usuarios específicos.
  
Para obtener más información, vea:
  
- [Buzones de archivo en Exchange Online](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-archiving-service-description/archive-features)
    
- [Habilitar o deshabilitar un buzón de archivo en Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)
    
### <a name="archive-sizes"></a>Tamaños de archivo

Solo los datos de mensajería de un usuario pueden almacenarse en cada archivo personal. La asignación de almacenamiento depende del plan de suscripción. Para obtener más información acerca de los tamaños de los buzones de archivo, consulte la sección "límites de almacenamiento de buzones" en [límites de Exchange Online](exchange-online-limits.md).
  
> [!IMPORTANT]
> - Con el registro en diario, el uso de reglas de transporte o reglas de transferencia automática para copiar mensajes en un buzón de Exchange Online con fines de archivado no está permitido. Microsoft se reserva el derecho a denegar el archivado ilimitado en casos en los que no se usa un archivo de buzones de correo en un escenario personal o en otros casos de uso inadecuado.
> - In-Place Archive has specific licensing requirements for Outlook users. Outlook 2007 users must have the Office 2007 Cumulative Update for February 2011 to access the personal archive. 
> - Exchange online no es compatible con el cmdlet _New-MailboxImportRequest_ de Windows PowerShell de Exchange Server 2010 Service Pack 1 o posterior para la importación de archivos. pst controlados por el administrador en un archivo personal. Si un usuario tiene el buzón principal y el archivo en Exchange Online, un administrador puede usar PST Capture, una herramienta gratuita, para importar datos de archivos .pst al buzón principal o archivo del usuario.

## <a name="cloud-based-archiving-of-on-premises-mailboxes"></a>Archivado basado en nube de buzones locales

Using Exchange Online for cloud-based archiving of on-premises Exchange Server 2010 or later mailboxes is possible with Microsoft Exchange Online Archiving, a hosted archiving solution from Microsoft. This requires that the on-premises organization be in Hybrid mode or be set up for Exchange Online Archiving.
  
> [!IMPORTANT]
> Los usuarios que cuentan con un buzón local en un servidor de buzones de Exchange 2010 que tiene una directiva de carpeta administrada aplicada no pueden tener un archivo local o basado en la nube habilitado. 
  
## <a name="retention-tags-and-retention-policies"></a>Etiquetas de retención y directivas de retención

Exchange Online ofrece directivas de retención para ayudar a las organizaciones a reducir las responsabilidades asociadas con el correo electrónico y otras comunicaciones. Con estas políticas, los administradores pueden aplicar configuración de retención a carpetas específicas de los buzones de los usuarios. Los administradores también pueden proporcionar a los usuarios un menú de directivas de retención y permitirles aplicar las directivas a elementos, conversaciones o carpetas específicos mediante Outlook 2010 o versiones posteriores o Outlook en la Web.
  
En Exchange Online, los administradores administran las directivas de retención mediante el Centro de administración de Exchange (EAC) o Windows PowerShell remoto.
  
Exchange Online offers two types of policies: archive policies and delete policies. Both types can be combined on the same item or folder. For example, a user can tag an email message to be automatically moved to the In-Place Archive in a specified number of days and deleted after another span of days.
  
Con Outlook 2010 o versiones posteriores y Outlook en la web, los usuarios pueden aplicar directivas de retención a carpetas, conversaciones o mensajes individuales. También pueden ver las directivas de retención aplicadas y las fechas de eliminación esperadas en los mensajes. Los usuarios de otros clientes de correo electrónico solamente pueden eliminar o archivar mensajes según las directivas de retención del servidor configuradas por el administrador.
  
The retention policy capabilities offered in Exchange Online are the same as those offered in Exchange Server 2010 Service Pack 2 RU4. Administrators can use remote Windows PowerShell to migrate retention policies from on-premises Exchange Server 2010 or later environments to Exchange Online.
  
> [!IMPORTANT]
> Carpetas administradas, un enfoque para la administración de registros de mensajería presentado en Exchange Server 2007, no está disponible en Exchange Online. 
  
Para obtener más información, consulte [Etiquetas de retención y directivas de retención](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/retention-tags-and-policies).
  
## <a name="encryption-of-data-at-rest"></a>Cifrado de datos en reposo

El cifrado de datos de clientes en reposo se proporciona mediante varias tecnologías de servicio, como BitLocker, DKM, el cifrado de servicio de almacenamiento de Azure y el cifrado de servicios en Exchange Online, Skype empresarial, OneDrive para la empresa y SharePoint Online. El cifrado del servicio de Office 365 incluye una opción para usar las claves de cifrado administradas por el cliente que se almacenan en Azure Key Vault. Esta opción de clave administrada por el cliente, denominada [clave de cliente](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key?redirectSourcePath=%252fen-us%252farticle%252fControlling-your-data-in-Office-365-using-Customer-Key-f2cd475a-e592-46cf-80a3-1bfb0fa17697), está disponible para Exchange Online, SharePoint Online y OneDrive para la empresa. 
  
### <a name="bitlocker"></a>BitLocker

Los servidores de Microsoft usan BitLocker para cifrar las unidades de disco que contienen datos de clientes en reposo en el nivel de volumen. El cifrado de BitLocker es una característica de protección de datos que se integra en Windows. BitLocker es una de las tecnologías que se usan para protegerse frente a amenazas en caso de que haya fallos en otros procesos o controles (por ejemplo, el control de acceso o el reciclaje de hardware) que puedan dar lugar a que alguien obtenga acceso físico a los discos que contienen datos de clientes. En este caso, BitLocker elimina el potencial de robo de datos o de exposición debido a la pérdida, robo o desactivación de discos y equipos de forma inadecuada. 
  
### <a name="distributed-key-manager"></a>Administrador de claves distribuidas

Además de BitLocker, usamos una tecnología denominada administrador de claves distribuidas (DKM). DKM es una funcionalidad del lado cliente que usa un conjunto de claves secretas para cifrar y descifrar información. Solo los miembros de un grupo de seguridad específico en los servicios de dominio de Active Directory pueden tener acceso a esas claves para descifrar los datos cifrados por el DKM. En Exchange Online, solo determinadas cuentas de servicio bajo las cuales se ejecutan procesos de Exchange forman parte del grupo de seguridad. Como parte del procedimiento operativo estándar en el centro de datos, ningún humano tiene credenciales que forman parte de este grupo de seguridad y, por lo tanto, nadie tiene acceso a las claves que pueden descifrar la información confidencial.
  
## <a name="customer-key"></a>Clave de cliente

Con la clave de cliente, se controlan las claves de cifrado de la organización y, a continuación, se configuran para cifrar los datos en reposo en los centros de datos de Microsoft. Los datos en reposo incluyen datos de Exchange Online y Skype Empresarial que se almacenan en buzones y archivos en SharePoint Online y OneDrive para la Empresa. Para obtener más información, vea [controlar los datos en usar la clave de cliente](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key) y el [cifrado de servicios con la clave de cliente FAQ](https://docs.microsoft.com/office365/securitycompliance/service-encryption-with-customer-key-faq).
  
## <a name="office-365-message-encryption"></a>Cifrado de mensajes de Office 365

El cifrado de mensajes de Office 365 permite a los usuarios enviar mensajes de correo electrónico cifrados a cualquier persona. Anunciamos nuevas capacidades en el cifrado de mensajes de Office que aprovechan las características de protección de Azure Information Encryption. Estas nuevas funciones ofrecen experiencias de usuario final mejoradas que facilitan el uso compartido y la colaboración en mensajes protegidos con cualquier usuario dentro o fuera de la organización. Las nuevas capacidades de cifrado de mensajes de Office tienen algunos requisitos de configuración. Consulte configurar las nuevas capacidades de cifrado de mensajes de Office 365 basadas en Azure Information Protection. Los clientes en el cifrado de mensajes de Office 365 heredado no obtienen las nuevas funciones sin seguir la guía de configuración que se proporciona más arriba. Consulte las [preguntas más frecuentes](https://support.office.com/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e) para obtener más información sobre lo que se incluye en las funciones de cifrado de mensajes de Office 365 heredado. 

El cifrado de mensajes avanzado de Office 365 proporciona protección adicional al permitir la caducidad y revocación de mensajes.  También puede crear varias plantillas para los mensajes de correo electrónico cifrados que se originan desde su organización.  El cifrado de mensajes avanzado se incluye en Microsoft 365 E5, Office 365 E5, Microsoft 365 E5 (precio del personal sin ánimo de lucro), Office 365 Enterprise E5 (precio del personal sin ánimo de lucro) u Office 365 Education A5. Si su organización tiene una suscripción que no incluye el cifrado avanzado de mensajes de Office 365, puede comprar Microsoft 365 E5 Compliance o el Office 365 Advanced Compliance SKU como un complemento.

## <a name="securemultipurpose-internet-mail-extensions-smime"></a>Extensiones seguras multipropósito al correo de Internet (S/MIME)

S/MIME allows you to help protect sensitive information by sending signed and encrypted email within your organization. Administrators can use remote Windows PowerShell to set up S/MIME after establishing and issuing PKI certificates to users. These certificates must be synchronized from an on-premises Active Directory Certificate Service.
  
S/MIME es compatible con Microsoft Edge e Internet Explorer 11. Actualmente, S/MIME no es compatible con Firefox, Opera y Chrome. Para obtener más información, consulte [S/MIME para la firma y el cifrado de mensajes](https://docs.microsoft.com/Exchange/policy-and-compliance/smime?view=exchserver-2019).
  
## <a name="in-place-hold-and-litigation-hold"></a>Retención local y retención por juicio

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
  
Para obtener más información, vea [Conservación local y retención por juicio](https://docs.microsoft.com/exchange/security-and-compliance/in-place-and-litigation-holds).
  
## <a name="in-place-ediscovery"></a>Exhibición de documentos electrónicos en contexto

Exchange Online permite a los clientes realizar búsquedas en el contenido de los buzones de correo en una organización con una interfaz basada en Web. Los administradores o funcionarios de seguridad y cumplimiento normativo autorizados a realizar búsquedas de Exhibición de documentos electrónicos en contexto (mediante asignación) pueden buscar mensajes de correo electrónico, documentos adjuntos, citas de calendario, tareas, contactos y otros elementos. La Exhibición de documentos electrónicos en contexto permite realizar búsquedas entre los archivos y buzones principales de manera simultánea. Las capacidades de filtrado enriquecidas incluyen remitente, destinatario, tipo de mensaje, fecha de envío/recepción y copia carbón/copia carbón oculta, junto con sintaxis de KQL. Los resultados de búsqueda también incluirán elementos de la carpeta Elementos eliminados, si coinciden con una consulta de búsqueda.
  
Results of In-Place eDiscovery searches can be previewed in the web-based interface, exported to a PST file or copied to a special type of mailbox called a Discovery mailbox. A Discovery mailbox has a 50 GB quota for storing search results. Administrators can also connect Outlook to the Discovery mailbox to access search results, and export the search results to a .pst file.
  
Administrators use either the Exchange admin center or remote Windows PowerShell to perform multi-mailbox searches. The Exchange admin center can provide a read-only preview of the search results, enabling administrators to quickly verify a search and rerun it, if needed, with different parameters. Once a search is optimized, the administrator can copy the results to the Discovery mailbox.
  
By default, one Discovery mailbox is created for each organization, but administrators can create additional Discovery mailboxes using remote Windows PowerShell. Discovery mailboxes cannot be used for any purpose other than storing In-Place eDiscovery search results.
  
Administrators use either the Exchange admin center or remote Windows PowerShell to perform In-Place eDiscovery searches. The Exchange admin center can provide a read-only preview of the search results, enabling administrators to quickly verify a search and rerun it, if needed, with different parameters. Once a search is optimized, the administrator can copy the results to the Discovery mailbox or export search results to a PST file.
  
Los administradores pueden usar el Centro de administración de Exchange o Windows PowerShell remoto para buscar hasta 10 000 buzones de correo a la vez en una búsqueda de exhibición de documentos electrónicos local. 
  
En Exchange Online, los usuarios autorizados pueden realizar una exhibición de documentos electrónicos local y elegir una de las siguientes acciones:
  
- **Cálculo de resultados de búsqueda** Obtenga un cálculo de la cantidad de mensajes que devolverá la búsqueda, incluidas las estadísticas de palabras clave, para determinar la efectividad de las palabras clave que se usan en la búsqueda y limitar los parámetros de búsqueda, si es necesario. 
    
- **Vista previa de los resultados de búsqueda**
    
- Copie los mensajes devueltos en los resultados de la búsqueda en un buzón de detección.
    
Para obtener más información, vea [Exhibición de documentos electrónicos local](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery).
  
## <a name="mail-flow-rules"></a>Reglas de flujo de correo

Puede usar reglas de flujo de correo para buscar condiciones específicas en los mensajes que pasan por su organización y que actúan en ellos. Las reglas de flujo de correo le permiten aplicar directivas de mensajería a mensajes de correo electrónico, proteger mensajes, proteger los sistemas de mensajería y evitar la fuga de información.
  
Many organizations today are required by law, regulatory requirements, or company policies to apply messaging policies that limit the interaction between recipients and senders, both inside and outside the organization. In addition to limiting interactions among individuals, departmental groups inside the organization, and entities outside the organization, some organizations are also subject to the following messaging policy requirements:
  
- Prevenir que contenido inapropiado entre y salga de la organización
    
- Filtrar la información confidencial de la organización
    
- Efectuar el seguimiento de los mensajes que envían o reciben ciertas personas, o copiarlos
    
- Redireccionar los mensajes entrantes y salientes para inspeccionarlos antes entregarlos
    
- Aplicar avisos de declinación de responsabilidades a los mensajes conforme pasan por la organización
    
> [!IMPORTANT]
> Los tipos de archivo de datos adjuntos que requieren la instalación de iFilters de terceros en el servidor de correo electrónico (como Adobe. pdf) no se pueden inspeccionar con reglas de flujo de correo hasta que se instale un iFilter adecuado. Para obtener más información acerca de los tipos de archivo admitidos por las reglas de flujo de correo, consulte [usar reglas de flujo de correo para inspeccionar datos adjuntos de mensajes en Office 365](https://docs.microsoft.com/exchange/security-and-compliance/mail-flow-rules/inspect-message-attachments).
  
Para obtener más información acerca de las reglas de flujo de correo, consulte [reglas de flujo de correo en Exchange 2016](https://docs.microsoft.com/Exchange/policy-and-compliance/mail-flow-rules/mail-flow-rules?view=exchserver-2019).
  
## <a name="data-loss-prevention"></a>Prevención de pérdida de datos

La característica de prevención de pérdida de datos (DLP) le ayudará a identificar, supervisar y proteger la información confidencial de su organización mediante un análisis profundo del contenido. DLP es una característica premium que resulta cada vez más importante para los sistemas de mensajes de las empresas, ya que los correos electrónicos importantes del negocio incluyen datos que deben ser protegidos. La característica DLP de Exchange Online le permite proteger datos confidenciales sin afectar la productividad de los trabajadores.
  
Puede configurar directivas de DLP en la interfaz de administración del Centro de administración de Exchange (EAC), lo que le permite: 
  
- Comenzar con una plantilla de directivas preconfigurada que ayudará a detectar tipos específicos de información confidencial, como datos PCI-DSS, datos de la ley Gramm-Leach-Bliley o incluso información de identificación personal (PII) local específica.
    
- Utilizar todo el poder de las acciones y los criterios de las reglas de transporte existentes y agregar nuevas reglas de transporte.
    
- Probar la eficacia de sus directivas de DLP antes de aplicarlas plenamente.
    
- Incorporar sus propias plantillas de directivas de DLP y sus propios tipos de información confidencial.
    
- Detectar información confidencial en datos adjuntos de mensajes, texto del cuerpo o líneas de asunto y ajustar el nivel de confianza en el que actúa Exchange Online.
    
- Detect sensitive form data by using Document Fingerprinting. Document Fingerprinting helps you easily create custom sensitive information types based on text-based forms that you can use to define transport rules and DLP policies.
    
- Agregar sugerencias de directivas, que pueden ayudar a reducir la pérdida de datos al mostrar un aviso a los usuarios de Outlook 2016, Outlook 2013, Outlook en la web y OWA para dispositivos, y también pueden mejorar la eficacia de las directivas al permitir la creación de informes falsos positivos. 
    
- Revisar los datos de incidentes en informes de DLP o agregar sus propios informes específicos mediante una acción de generación de informes de incidentes.
    
Para obtener más información sobre DLP, consulte [Prevención de pérdida de datos](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention).
  
## <a name="journaling"></a>Registro en diario 

You can configure Exchange Online to journal copies of emails to any external mailbox that can receive messages via SMTP. Journaling can help your organization respond to legal, regulatory, and organizational compliance requirements by recording inbound and outbound email communications. When planning for messaging retention and compliance, it's important to understand journaling and how it fits in with your organization's compliance policies.
  
You can manage journal rules by using the Exchange admin center or remote Windows PowerShell. You can configure journaling on a per-user and per-distribution list basis, and choose to journal only internal messages, only external messages, or both. Journaled messages include not only the original message but also information about the sender, recipients, copies, and blind copies.
  
Para garantizar una solución de registro en diario correcta y fiable, debe completar las siguientes tareas:
  
- Asegúrese de que el destino del registro en diario no sea un buzón de Exchange Online.
    
- Cree en el directorio del cliente un objeto de contacto para la dirección de correo electrónico de destino SMTP, para utilizar en el registro en diario.
    
- Cree un segundo objeto de contacto como buzón de registro en diario alternativo, para capturar los informes de registro en diario cuando el buzón principal no está disponible.
    
- Mantener la administración, la redundancia, la disponibilidad, el rendimiento y los niveles de funcionalidad adecuados del destino SMTP para garantizar siempre la aceptación correcta de correo.
    
- Proporcionar la interoperabilidad respectiva con Exchange Server y el transporte de Exchange, incluidos los formatos de mensajes, la integración de la información del remitente y el destinatario, y la conversión de contenido adecuada.
    
Para más información sobre el registro en diario, consulte [Registro en diario en Exchange Online](https://docs.microsoft.com/exchange/security-and-compliance/journaling/journaling).
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, las opciones independientes y las soluciones locales, consulte [Exchange Online Service Description](exchange-online-service-description.md).
  

