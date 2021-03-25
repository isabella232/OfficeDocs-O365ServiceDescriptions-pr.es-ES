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
description: Obtenga información sobre la directiva de mensajes y el cumplimiento en Exchange Online.
ms.openlocfilehash: b92c129601b4de67b03638f505cbf507e7ac77d7
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173385"
---
# <a name="message-policy-and-compliance"></a>Regulación de mensajes y cumplimiento

## <a name="archiving-exchange-online-based-mailboxes"></a>Archivado de buzones basados en Exchange Online

Los buzones de Exchange Online residen en la nube y su archivado requiere entornos de hospedaje únicos. En algunos casos, Exchange Online también puede ser utilizado para archivar buzones locales en la nube. En esta sección, se describen las opciones de archivado con Exchange Online.
  
Exchange Online ofrece capacidades de archivado integradas para buzones basados en la nube, incluido un archivo local que brinda a los usuarios un espacio muy conveniente para almacenar mensajes de correo electrónico antiguos. Un archivo In-Place es un tipo especial de buzón que aparece junto con las carpetas de buzones principales de un usuario en Outlook y Outlook en la web. Los usuarios pueden tener acceso al archivo y buscar en él de la misma manera en que con sus buzones principales. La funcionalidad disponible depende del cliente en uso:
  
- **Outlook 2016, Outlook 2013, Outlook 2010 y Outlook en la web** Los usuarios tienen acceso a todas las características del archivo, así como a las características de cumplimiento relacionadas, como el control sobre las directivas de retención y archivo. 
    
- **Outlook 2007** Los usuarios tienen soporte básico para el archivo local, pero no todas las características de archivo y cumplimiento están disponibles. Por ejemplo, los usuarios no pueden aplicar directivas de retención o archivo a elementos del buzón, en cambio, deben confiar en las directivas provistas por el administrador. 
    
Los administradores usan el Centro de administración de Exchange o Windows PowerShell remoto para habilitar la característica de archivo personal para usuarios específicos.
  
Para obtener más información, vea:
  
- [Buzones de archivo en Exchange Online](../exchange-online-archiving-service-description/archive-features.md)
    
- [Habilitar o deshabilitar un buzón de archivo en Exchange Online](/office365/securitycompliance/enable-archive-mailboxes)
    
### <a name="archive-sizes"></a>Tamaños de archivo

Solo los datos de mensajería de un usuario pueden almacenarse en cada archivo personal. La asignación de almacenamiento depende del plan de suscripción. Para obtener más información acerca de los tamaños de los buzones de archivo, vea la sección "Límites de almacenamiento de buzones" en [Límites de Exchange Online](exchange-online-limits.md).
  
> [!IMPORTANT]
> - Con el registro en diario, el uso de reglas de transporte o reglas de transferencia automática para copiar mensajes en un buzón de Exchange Online con fines de archivado no está permitido. Microsoft se reserva el derecho de denegar el archivado ilimitado en casos en los que no se esté utilizando un archivo de buzón en un escenario personal o en otros casos de uso inadecuado.
> - El archivo local tiene requisitos de licencia específicos para usuarios de Outlook. Los usuarios de Outlook 2007 deberán tener actualización acumulada de Office 2007 para febrero de 2011 para poder acceder al archivo personal. 
> - Exchange Online no admite el cmdlet  _New-MailboxImportRequest_ Windows PowerShell de Exchange Server 2010 Service Pack 1 o posterior para la importación controlada por el administrador de archivos .pst en un archivo personal. Si un usuario tiene el buzón principal y el archivo en Exchange Online, un administrador puede usar PST Capture, una herramienta gratuita, para importar datos de archivos .pst al buzón principal o archivo del usuario.

## <a name="cloud-based-archiving-of-on-premises-mailboxes"></a>Archivado basado en nube de buzones locales

El uso de Exchange Online para el archivo basado en la nube de buzones de Exchange Server 2010 local o posteriores es posible mediante el Archivado de Microsoft Exchange Online, una solución de archivado hospedada de Microsoft. Esto requiere que la organización local esté en modo híbrido o esté configurada para Archivado de Exchange Online.
  
> [!IMPORTANT]
> Los usuarios que cuentan con un buzón local en un servidor de buzones de Exchange 2010 que tiene una directiva de carpeta administrada aplicada no pueden tener un archivo local o basado en la nube habilitado. 
  
## <a name="retention-tags-and-retention-policies"></a>Etiquetas de retención y directivas de retención

Exchange Online ofrece directivas de retención para ayudar a las organizaciones a reducir las responsabilidades asociadas con el correo electrónico y otras comunicaciones. Con estas políticas, los administradores pueden aplicar configuración de retención a carpetas específicas de los buzones de los usuarios. Los administradores también pueden proporcionar a los usuarios un menú de directivas de retención y permitir que apliquen las directivas a elementos, conversaciones o carpetas específicos con Outlook 2010 o versiones posteriores o Outlook en la web.
  
En Exchange Online, los administradores administran las directivas de retención mediante el Centro de administración de Exchange (EAC) o Windows PowerShell remoto.
  
Exchange Online ofrece dos tipos de directivas: directivas de archivado y directivas de eliminación. Ambos tipos pueden combinarse en el mismo elemento o carpeta. Por ejemplo, un usuario puede marcar un mensaje de correo electrónico para que sea movido automáticamente al archivo local transcurrida una cantidad específica de días y eliminado después de otra cantidad de días.
  
Con Outlook 2010 o posterior y Outlook en la web, los usuarios pueden aplicar directivas de retención a carpetas, conversaciones o mensajes individuales. También pueden ver las directivas de retención aplicadas y las fechas de eliminación esperadas en los mensajes. Los usuarios de otros clientes de correo electrónico solamente pueden eliminar o archivar mensajes según las directivas de retención del servidor configuradas por el administrador.
  
Las capacidades de directivas de retención ofrecidas en Exchange Online son las mismas que las ofrecidas en Exchange Server 2010 Service Pack 2 RU4. Los administradores pueden usar Windows PowerShell remoto para migrar directivas de retención de entornos Exchange Server 2010 o posteriores locales a Exchange Online.
  
> [!IMPORTANT]
> Carpetas administradas, un enfoque para la administración de registros de mensajería presentado en Exchange Server 2007, no está disponible en Exchange Online. 
  
Para obtener más información, consulte [Etiquetas de retención y directivas de retención](/exchange/security-and-compliance/messaging-records-management/retention-tags-and-policies).
  
## <a name="encryption-of-data-at-rest"></a>Cifrado de datos en reposo

El cifrado de los datos de los clientes en reposo se proporciona mediante varias tecnologías del lado del servicio, como BitLocker, DKM, cifrado de servicio de almacenamiento de Azure y cifrado de servicio en Exchange Online, Skype Empresarial, OneDrive para la Empresa y SharePoint Online. El cifrado de servicio de Office 365 incluye una opción para usar claves de cifrado administradas por el cliente almacenadas en Azure Key Vault. Esta opción de clave administrada por el cliente, denominada [Clave](/microsoft-365/compliance/customer-key-overview)de cliente, está disponible para Exchange Online, SharePoint Online y OneDrive para la Empresa. 
  
### <a name="bitlocker"></a>BitLocker

Los servidores de Microsoft usan BitLocker para cifrar las unidades de disco que contienen datos de clientes en reposo en el nivel de volumen. El cifrado de BitLocker es una característica de protección de datos integrada en Windows. BitLocker es una de las tecnologías usadas para protegerse contra amenazas en caso de que haya lapsos en otros procesos o controles (por ejemplo, control de acceso o reciclaje de hardware) que podrían llevar a alguien a obtener acceso físico a discos que contienen datos de clientes. En este caso, BitLocker elimina la posibilidad de robo o exposición de datos debido a equipos y discos perdidos, robados o desmantelados de forma inapropiada. 
  
### <a name="distributed-key-manager"></a>Administrador de claves distribuidas

Además de BitLocker, usamos una tecnología denominada Administrador de claves distribuidas (DKM). DKM es una funcionalidad del lado cliente que usa un conjunto de claves secretas para cifrar y descifrar información. Solo los miembros de un grupo de seguridad específico en Servicios de dominio de Active Directory pueden acceder a esas claves para descifrar los datos cifrados por DKM. En Exchange Online, solo determinadas cuentas de servicio bajo las cuales se ejecutan procesos de Exchange forman parte del grupo de seguridad. Como parte del procedimiento operativo estándar en el centro de datos, ningún humano tiene credenciales que forman parte de este grupo de seguridad y, por lo tanto, nadie tiene acceso a las claves que pueden descifrar la información confidencial.
  
## <a name="customer-key"></a>Clave de cliente

Con clave de cliente, controla las claves de cifrado de su organización y, a continuación, las configura para cifrar los datos en reposo en los centros de datos de Microsoft. Los datos en reposo incluyen datos de Exchange Online y Skype Empresarial que se almacenan en buzones y archivos en SharePoint Online y OneDrive para la Empresa. Para obtener más información, vea [Controlar los datos con](/office365/securitycompliance/controlling-your-data-using-customer-key) las preguntas más frecuentes sobre clave de cliente y cifrado de servicio con clave de [cliente.](/office365/securitycompliance/service-encryption-with-customer-key-faq)
  
## <a name="office-365-message-encryption"></a>Cifrado de mensajes de Office 365

El cifrado de mensajes de Office 365 permite a los usuarios de correo electrónico enviar mensajes de correo electrónico cifrados a cualquier persona. Anunciamos nuevas funcionalidades en El cifrado de mensajes de Office que aprovechan las características de protección de Azure Information Encryption. Estas nuevas funcionalidades proporcionaron experiencias mejoradas del usuario final que facilitan compartir y colaborar en mensajes protegidos con cualquier persona dentro o fuera de la organización. Las nuevas funcionalidades de cifrado de mensajes de Office tienen algunos requisitos de configuración. Consulte Configurar nuevas funcionalidades de cifrado de mensajes de Office 365 integradas en Azure Information Protection. Los clientes del cifrado de mensajes heredado de Office 365 no obtienen las nuevas funcionalidades sin seguir las instrucciones de configuración proporcionadas anteriormente. Lea las preguntas más [frecuentes](https://support.office.com/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e) para obtener más información sobre lo que se incluye en las nuevas funcionalidades de cifrado de mensajes de Office 365 heredadas. 

El cifrado avanzado de mensajes de Office 365 proporciona protección adicional al permitir la expiración y revocación de mensajes.  También puede crear varias plantillas para correos electrónicos cifrados procedentes de su organización.  El cifrado de mensajes avanzado se incluye en Microsoft 365 E5, Office 365 E5, Microsoft 365 E5 (precios de personal sin ánimo de lucro), Office 365 Enterprise E5 (precios de personal sin ánimo de lucro) u Office 365 Educación A5. Si su organización tiene una suscripción que no incluye el cifrado avanzado de mensajes de Office 365, puede comprar el cumplimiento de Microsoft 365 E5 o la SKU de cumplimiento avanzado de Office 365 como complemento.

## <a name="securemultipurpose-internet-mail-extensions-smime"></a>Extensiones seguras multipropósito al correo de Internet (S/MIME)

S/MIME le ayuda a proteger información confidencial enviando correo electrónico firmado y cifrado dentro de su organización. Los administradores pueden usar Windows PowerShell remoto para configurar S/MIME tras establecer y emitir certificados PKI para los usuarios. Estos certificados deben sincronizarse desde un servicio de certificados de Active Directory local.
  
S/MIME se admite en Microsoft Edge e Internet Explorer 11. Actualmente, S/MIME no es compatible con Firefox, Opera y Chrome. Para obtener más información, consulte [S/MIME para la firma y el cifrado de mensajes](/Exchange/policy-and-compliance/smime?preserve-view=true&view=exchserver-2019).
  
## <a name="in-place-hold-and-litigation-hold"></a>Retención local y retención por juicio

Cuando existen sospechas fundadas de posibles litigios, se solicita a las organizaciones que conserven toda la información almacenada electrónicamente (ESI), incluso el correo electrónico que sea relevante para el caso. Dichas sospechas pueden tener lugar antes de que se conozcan los pormenores del caso, por lo que se suele conservar gran cantidad de material. Las organizaciones pueden conservar todo el correo electrónico relacionado con un tema concreto o el perteneciente a ciertos usuarios.
  
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
  
Para obtener más información, vea [Conservación local y retención por juicio](/exchange/security-and-compliance/in-place-and-litigation-holds).
  
## <a name="in-place-ediscovery"></a>Exhibición de documentos electrónicos en contexto

Exchange Online permite a los clientes buscar en el contenido de los buzones de una organización mediante una interfaz basada en web. Los administradores o funcionarios de seguridad y cumplimiento normativo autorizados a realizar búsquedas de Exhibición de documentos electrónicos en contexto (mediante asignación) pueden buscar mensajes de correo electrónico, documentos adjuntos, citas de calendario, tareas, contactos y otros elementos. La Exhibición de documentos electrónicos en contexto permite realizar búsquedas entre los archivos y buzones principales de manera simultánea. Las capacidades de filtrado enriquecidas incluyen remitente, destinatario, tipo de mensaje, fecha de envío/recepción y copia carbón/copia carbón oculta, junto con sintaxis de KQL. Los resultados de búsqueda también incluirán elementos de la carpeta Elementos eliminados, si coinciden con una consulta de búsqueda.
  
Se puede obtener una vista previa de los resultados de las búsquedas de Exhibición de documentos electrónicos en contexto en la interfaz basada en web; también se pueden exportar a un archivo PST o copiar a un tipo especial de buzón denominado buzón de detección. Un buzón de detección tiene una cuota de 50 GB para almacenar los resultados de la búsqueda. Los administradores también pueden conectar Outlook al buzón de detección para acceder a los resultados de búsqueda y para exportarlos a un archivo .pst.
  
Los administradores pueden usar el Centro de administración de Exchange (EAC) o Windows PowerShell remoto para realizar búsquedas en varios buzones. El Centro de administración de Exchange puede proporcionar una vista previa de solo lectura de los resultados de búsqueda, lo que permite a los administradores revisar rápidamente una búsqueda y volver a ejecutarla, si es necesario, con parámetros diferentes. Una vez optimizada la búsqueda, el administrador puede copiar los resultados en el buzón de detección.
  
De forma predeterminada, se crea un buzón de detección para cada organización, pero los administradores pueden crear buzones de detección adicionales con Windows PowerShell remoto. Los buzones de detección no pueden ser utilizados con otro fin que no sea almacenar los resultados de búsqueda de Exhibición de documentos electrónicos en contexto.
  
Los administradores pueden usar el Centro de administración de Exchange (EAC) o Windows PowerShell remoto para realizar búsquedas de Exhibición de documentos electrónicos en contexto. El Centro de administración de Exchange puede proporcionar una vista previa de solo lectura de los resultados de búsqueda, lo que permite a los administradores revisar rápidamente una búsqueda y volver a ejecutarla, si es necesario, con parámetros diferentes. Una vez optimizada la búsqueda, el administrador puede copiar los resultados en el buzón de detección o exportarlos a un archivo PST.
  
Los administradores pueden usar el Centro de administración de Exchange o Windows PowerShell remoto para buscar hasta 10 000 buzones de correo a la vez en una búsqueda de exhibición de documentos electrónicos local. 
  
En Exchange Online, los usuarios autorizados pueden realizar una exhibición de documentos electrónicos local y elegir una de las siguientes acciones:
  
- **Cálculo de resultados de búsqueda** Obtenga un cálculo de la cantidad de mensajes que devolverá la búsqueda, incluidas las estadísticas de palabras clave, para determinar la efectividad de las palabras clave que se usan en la búsqueda y limitar los parámetros de búsqueda, si es necesario. 
    
- **Vista previa de los resultados de búsqueda**
    
- Copie los mensajes devueltos en los resultados de la búsqueda en un buzón de detección.
    
Para obtener más información, vea [Exhibición de documentos electrónicos local](/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery).
  
## <a name="mail-flow-rules"></a>Reglas de flujo de correo

Puede usar reglas de flujo de correo para buscar condiciones específicas en los mensajes que pasan por su organización y actuar en ellos. Las reglas de flujo de correo le permiten aplicar directivas de mensajería a mensajes de correo electrónico, proteger mensajes, proteger sistemas de mensajería y evitar la fuga de información.
  
Hoy en día, muchas organizaciones son obligadas por ley, requisitos legales o directivas de la compañía, a aplicar directivas de mensajería para limitar la interacción entre destinatarios y remitentes, tanto dentro como fuera de la organización. Además de limitar las interacciones entre personas, departamentos de la misma organización y entidades fuera de la organización, algunas organizaciones están, asimismo, sujetas a los siguientes requisitos de directivas de mensajería:
  
- Prevenir que contenido inapropiado entre y salga de la organización
    
- Filtrar la información confidencial de la organización
    
- Efectuar el seguimiento de los mensajes que envían o reciben ciertas personas, o copiarlos
    
- Redireccionar los mensajes entrantes y salientes para inspeccionarlos antes entregarlos
    
- Aplicar avisos de declinación de responsabilidades a los mensajes conforme pasan por la organización
    
> [!IMPORTANT]
> Los tipos de archivos adjuntos que requieren la instalación de iFilters de terceros en el servidor de correo electrónico (como Adobe .pdf) no se pueden inspeccionar mediante reglas de flujo de correo hasta después de instalar un iFilter adecuado. Para obtener más información acerca de los tipos de archivo compatibles con las reglas de flujo de correo, vea Usar reglas de flujo de correo para inspeccionar datos adjuntos de mensajes [en Office 365](/exchange/security-and-compliance/mail-flow-rules/inspect-message-attachments).
  
Para obtener más información acerca de las reglas de flujo de correo, vea [Reglas de flujo de correo en Exchange 2016](/Exchange/policy-and-compliance/mail-flow-rules/mail-flow-rules?preserve-view=true&view=exchserver-2019).
  
## <a name="data-loss-prevention"></a>Prevención de pérdida de datos

La característica de prevención de pérdida de datos (DLP) le ayudará a identificar, supervisar y proteger la información confidencial de su organización mediante un análisis profundo del contenido. DLP es una característica premium que resulta cada vez más importante para los sistemas de mensajes de las empresas, ya que los correos electrónicos importantes del negocio incluyen datos que deben ser protegidos. La característica DLP de Exchange Online le permite proteger datos confidenciales sin afectar a la productividad de los trabajadores.
  
Puede configurar directivas de DLP en la interfaz de administración del Centro de administración de Exchange (EAC), lo que le permite: 
  
- Comenzar con una plantilla de directivas preconfigurada que ayudará a detectar tipos específicos de información confidencial, como datos PCI-DSS, datos de la ley Gramm-Leach-Bliley o incluso información de identificación personal (PII) local específica.
    
- Utilizar todo el poder de las acciones y los criterios de las reglas de transporte existentes y agregar nuevas reglas de transporte.
    
- Probar la eficacia de sus directivas de DLP antes de aplicarlas plenamente.
    
- Incorporar sus propias plantillas de directivas de DLP y sus propios tipos de información confidencial.
    
- Detecte información confidencial en datos adjuntos de mensajes, texto del cuerpo o líneas de asunto y ajuste el nivel de confianza en el que actúa Exchange Online.
    
- Detectar datos confidenciales mediante las huellas digitales de documentos. Las huellas digitales de documentos ayudan a crear fácilmente tipos de información confidencial personalizada en función de formularios basados en texto que se pueden usar para definir las reglas de transporte y las directivas DLP.
    
- Agregue sugerencias de directiva, que pueden ayudar a reducir la pérdida de datos mostrando un aviso a los usuarios de Outlook 2016, Outlook 2013, Outlook en la web y OWA para dispositivos, y también puede mejorar la eficacia de las directivas al permitir informes falsos positivos. 
    
- Revisar los datos de incidentes en informes de DLP o agregar sus propios informes específicos mediante una acción de generación de informes de incidentes.
    
Para obtener más información sobre DLP, consulte [Prevención de pérdida de datos](/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention).
  
## <a name="journaling"></a>Registro en diario 

Puede configurar Exchange Online para registrar en diario copias de correos electrónicos en cualquier buzón externo que pueda recibir mensajes vía SMTP. El registro en diario puede ayudar a la organización a responder a los requisitos de cumplimiento legal, normativo y organizativo mediante el registro de las comunicaciones de correo electrónico entrantes y salientes. Al planear la retención y el cumplimento normativo de mensajes, es importante comprender el registro en diario, cómo se ajusta a las directivas de cumplimiento de la organización.
  
Puede administrar reglas de diario con el Centro de administración de Exchange (EAC) o Windows PowerShell remoto. Puede configurar el registro en diario por usuario y por lista de distribución, y elegir registrar en diario mensajes internos, mensajes externos solamente o ambos. Los mensajes registrados en diario incluyen el mensaje original y también información acerca del remitente, los destinatarios, copias y copias ocultas.
  
Para garantizar una solución de registro en diario correcta y confiable, debe completar las siguientes tareas:
  
- Asegúrese de que el destino de registro en diario no sea un buzón de Exchange Online.
    
- Cree en el directorio del cliente un objeto de contacto para la dirección de correo electrónico de destino SMTP, para utilizar en el registro en diario.
    
- Cree un segundo objeto de contacto como buzón de registro en diario alternativo, para capturar los informes de registro en diario cuando el buzón principal no está disponible.
    
- Mantenga los niveles de administración, redundancia, disponibilidad, rendimiento y funcionalidad adecuados del destino SMTP para garantizar la aceptación correcta del correo siempre.
    
- Proporcionar la interoperabilidad respectiva con Exchange Server y el transporte de Exchange, incluidos los formatos de mensajes, la integración de la información del remitente y el destinatario, y la conversión de contenido adecuada.
    
Para más información sobre el registro en diario, consulte [Registro en diario en Exchange Online](/exchange/security-and-compliance/journaling/journaling).
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, opciones independientes y soluciones locales, vea [Descripción del servicio de Exchange Online](exchange-online-service-description.md).
