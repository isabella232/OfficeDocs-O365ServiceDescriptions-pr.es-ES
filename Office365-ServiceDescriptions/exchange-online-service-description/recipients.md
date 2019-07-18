---
title: Destinatarios
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-recipients
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: da22b03a-c981-49c6-9928-4312c2c5e2ee
description: En este tema, se describen las características relacionadas con los destinatarios que se incluyen con Microsoft Exchange Online. Incluye correo electrónico, contactos, grupos de distribución, calendarios y capacidades de programación.
ms.openlocfilehash: c4bac85f6a3610152cd8cb0767c7344c2e88d1f2
ms.sourcegitcommit: 96dc758c790ddaf05f5c2b836451b417729cf119
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/18/2019
ms.locfileid: "35776891"
---
# <a name="recipients"></a>Destinatarios

En este tema, se describen las características relacionadas con los destinatarios que se incluyen con Microsoft Exchange Online. Incluye correo electrónico, contactos, grupos de distribución, calendarios y capacidades de programación.
  
## <a name="email"></a>Correo electrónico

Cada suscritor a Microsoft Exchange Online recibe un buzón de correo y existen buzones de correo especializados para programar recursos de instalaciones (como salas de conferencia) y para el acceso multiusuario a las direcciones electrónicas. Los límites de almacenamiento máximo se aplican a la mayoría de buzones de correo y los administradores pueden controlar los tamaños de buzón de correo permitidos. Las notificaciones y restricciones automatizadas pueden advertir a los usuarios cuando sus buzones de correo se acercan o alcanzan su máxima capacidad. Exchange Online también dispone de varios tipos de limitaciones de mensajes: limites de tamaño de mensaje, frecuencia de mensajes y listas de destinatarios. A continuación figuran los detalles de todas estas características y límites.
  
> [!NOTE]
> Las direcciones catchall ya no son compatibles con Exchange Online. Debido al filtrado de destinatarios in situ para proteger contra posibles mensajes de correo no deseado, se rechazarán las direcciones de correo electrónico que no existan en el inquilino de Office 365. 
  
### <a name="mailbox-types-storage-limits-and-capacity-alerts"></a>Tipos de buzones, límites de almacenamiento y alertas de capacidad

La cantidad de almacenamiento de buzones de correo disponible para un usuario y el tamaño del buzón de correo predeterminado los determinan el tipo de buzón y la licencia de suscripción del usuario. Los administradores pueden reducir el tamaño máximo del buzón de correo por usuario o de forma global. Exchange Online también proporciona notificaciones cuando el buzón de usuario está alcanzando el límite de capacidad.
  
Para obtener más información, consulte las secciones "Límites de almacenamiento de buzones" y "Alertas de capacidad" en el tema [Límites de Exchange Online](exchange-online-limits.md).
  
### <a name="mailtips"></a>MailTips

Las sugerencias de correo electrónico son mensajes informativos automatizados que aparecen encima de la línea Para mientras los usuarios redactan el mensaje o escriben la dirección de un mensaje. Están diseñados para ayudar a evitar entregas por error, infracciones de directivas o informes de no entrega (NDR) innecesarios. Por ejemplo, las sugerencias de correo electrónico pueden generar una alerta si los remitentes intentan enviar mensajes a grupos muy grandes, grupos que contienen destinatarios externos o a un grupo de distribución moderado o restringido. Para obtener más información, vea [Sugerencias de correo electrónico](https://go.microsoft.com/fwlink/p/?LinkId=401472).
  
### <a name="delegate-access"></a>Acceso delegado

Exchange Online admite el acceso delegado: la capacidad de los usuarios de permitir que otros administren su correo electrónico y sus calendarios. El acceso delegado normalmente se usa entre un director y su asistente, donde el asistente procesa los mensajes de correo electrónico del director y coordina su agenda. Los usuarios de Exchange Online pueden habilitar el acceso delegado en Outlook o Outlook Web App. Los administradores pueden hacerlo en el Centro de administración de Exchange. 
  
Los delegados pueden tener dos tipos de acceso:
  
- **Permisos para enviar en nombre de** El delegado escribe mensajes de correo electrónico y escribe el nombre de otra persona en el campo De, que se mostrará como "[nombre del delegado] en nombre de [nombre de la persona]." 
    
- **Permisos de Enviar como** El delegado puede enviar mensajes del buzón de correo de la otra persona como si fuera el propietario del buzón de correo. Este escenario es habitual cuando hay un buzón de correo compartido y varios empleados envían mensajes de correo electrónico desde dicho buzón de correo compartido en vez de hacerlo desde sus propias cuentas de Exchange Online. 
    
Para obtener más información sobre cómo delegar acceso, consulte [Administrar permisos para destinatarios](https://technet.microsoft.com/en-us/library/jj919240%28v=exchg.160%29.aspx).
  
### <a name="inbox-rules"></a>Reglas de la bandeja de entrada

Exchange Online permite a los usuarios crear reglas de bandeja de entrada que realicen automáticamente acciones concretas basadas en criterios en mensajes a medida que lleguen. Por ejemplo, pueden crear una regla para mover automáticamente todo el correo a una carpeta concreta si el correo se envió a un grupo de distribución concreto. Los usuarios administran las reglas de bandeja de entrada desde Outlook o Outlook Web App. Los administradores pueden bloquear ciertos tipos de reglas de bandeja de entrada deshabilitando el reenvío desde el servidor o las respuestas automáticas desde el servidor. Por ejemplo, deshabilitar el reenvío de correo electrónico desde el servidor puede evitar que los usuarios reenvíen automáticamente correo electrónico a sus cuentas personales. De manera similar, deshabilitar las respuestas automáticas desde el servidor puede evitar que las partes externas usen estas respuestas para identificar una dirección electrónica válida. Estos cambios se realizan a través de Windows PowerShell remoto.
  
### <a name="clutter"></a>Otros correos

La característica Otros correos permite centrarse en los mensajes más importantes de la Bandeja de entrada. Usa el aprendizaje automático para clasificar la Bandeja de entrada al mover los mensajes con prioridad inferior a la nueva carpeta Otros correos. Otros correos respeta las reglas de correo electrónico existentes. Por lo tanto, si creó reglas para organizar el correo electrónico, esas reglas siguen aplicándose y Otros correos no actuará en dichos mensajes. Otros correos está deshabilitado de forma predeterminada en la Bandeja de entrada. Para obtener más información, vea cómo [ordenar la Bandeja de entrada en Office 365]( https://blogs.office.com/2014/11/11/de-clutter-inbox-office-365/).
  
### <a name="connected-accounts"></a>Cuentas conectadas

La característica Cuentas conectadas permite a los usuarios de Exchange Online conectar cuentas de correo electrónico externo (como las cuentas personales) a sus cuentas de correo electrónico interno en Exchange Online, y usar Outlook Web App para interactuar con sus mensajes en un sitio. Las cuentas conectadas se sincronizan automáticamente al iniciar sesión en Outlook Web App; los usuarios también pueden sincronizar manualmente las cuentas desde Outlook Web App. Los administradores pueden habilitar y deshabilitar esta característica para usuarios específicos o para todos los usuarios a través del [Centro de administración de Exchange](http://go.microsoft.com/fwlink/?LinkID=785297&amp;clcid=0x409).
  
### <a name="inactive-mailboxes"></a>Buzones de correo inactivos

Exchange Online proporciona la capacidad para conservar el contenido de los buzones eliminados indefinidamente. Esta característica se denomina buzones inactivos. Un buzón se vuelve inactivo cuando se impone una retención local o una retención por juicio en el buzón antes de eliminarlo. Esto resulta en la conservación indefinida del contenido del buzón. Los administradores, responsables de cumplimiento normativo o administradores de registros pueden utilizar la característica Exhibición de documentos electrónicos local en Exchange Online para obtener acceso al contenido de un buzón inactivo.
  
La habilitación de un buzón inactivo requiere que el buzón tenga asignada una licencia de Exchange Online (Plan 2) o tenga una suscripción de Archivado de Exchange Online de manera que se pueda imponer una retención local o una retención por juicio en el buzón antes de eliminarlo.
  
> [!IMPORTANT]
> Si no se impone una conservación en un buzón antes de eliminarlo, el contenido del buzón no se conservará y no será reconocible. El buzón se puede recuperar dentro de los 30 días de eliminación, pero el buzón junto con su contenido se eliminará permanentemente transcurrido dicho plazo, si no se recupera. 
  
Para obtener más información, vea:
  
- [Administrar buzones inactivos en Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=286991)
    
- [Conservación local y retención por juicio](https://go.microsoft.com/fwlink/p/?LinkId=271746)
    
- [Exhibición de documentos electrónicos en contexto](http://go.microsoft.com/fwlink/p/?LinkId=271747)
    
## <a name="contacts-and-distribution-groups"></a>Contactos y grupos de distribución

### <a name="offline-address-book"></a>Libreta de direcciones sin conexión

La característica libreta de direcciones sin conexión ofrece una instantánea de la información de Active Directory disponible en la lista global de direcciones global de Outlook. Está en caché localmente en Outlook para que esté disponible cuando el usuario trabaje sin conexión.
  
### <a name="address-book-policies"></a>Directivas de la libreta de direcciones

Exchange Online admite directivas de libreta de direcciones. Las directivas de libreta de direcciones (ABP) permiten clasificar a los usuarios en grupos específicos para proporcionar vistas personalizadas de la lista global de direcciones (LGD) de una organización. Al crear una ABP, asigna una LGD, una libreta de direcciones sin conexión (OAB), una lista de sala y una o varias listas de direcciones a la directiva. Después, puede asignar la ABP a usuarios de los buzones y proporcionarles acceso a una LGD personalizada en Outlook y Outlook Web App. Los administradores pueden configurar directivas de libreta de direcciones con Windows PowerShell remoto. Para obtener más información sobre las directivas de libreta de direcciones, vea [Libretas de direcciones en Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=394203).
  
### <a name="address-lists"></a>Listas de direcciones

Exchange Online admite la personalización de las listas de direcciones y la lista global de direcciones, un directorio de toda la organización de los usuarios con correo habilitado, grupos de distribución y contactos externos. Los administradores pueden ocultar usuarios, grupos de distribución y contactos de la lista global de direcciones usando la herramienta de sincronización de directorios o el Windows PowerShell remoto.
  
### <a name="hierarchical-address-books"></a>Libretas de direcciones jerárquicas

 Las libretas de direcciones jerárquicas permiten a los usuarios finales explorar los destinatarios en la organización de Exchange mediante el uso de la jerarquía organizativa. Los administradores pueden personalizar la libreta de direcciones por antigüedad y rango en lugar de listas alfabéticas. 
  
### <a name="distribution-groups-global"></a>Grupos de distribución (globales)

Un grupo de distribución (o una lista de distribución) es una recopilación de usuarios, contactos y otros grupos de distribución disponibles para todos los usuarios de una empresa. Los usuarios dirigen el correo electrónico al alias de un grupo de distribución para enviar mensajes a las personas del grupo. Los grupos de distribución son similares a los grupos de distribución personales que las personas crean en Outlook, sólo que sus listas de miembros están disponibles globalmente en la empresa. Los administradores crean grupos de distribución en el Centro de administración de Exchange. Los grupos también se pueden sincronizar con Exchange Online desde Active Directory local. Aparecen en la lista global de direcciones en Outlook. Exchange Online admite capacidades de grupo de distribución avanzadas, incluyendo las descritas a continuación:
  
- **Grupos de distribución restringidos** De forma predeterminada, todos los usuarios pueden enviar correos electrónicos a cualquier grupo de distribución. Los administradores pueden cambiar los permisos para permitir que personas concretas envíen correos electrónicos a un grupo concreto: por ejemplo, para disuadir de un uso inadecuado de listas de distribución grandes. Los administradores también pueden bloquear recursos externos para que no envíen correo electrónico a grupos de distribución para evitar el correo no deseado. Para los grupos de distribución que están sincronizados desde Active Directory local con la herramienta de sincronización de directorios, los atributos de la restricción se sincronizan automáticamente con la nube. Para obtener más información, consulte [Administrar grupos de distribución](https://technet.microsoft.com/EN-US/library/mt577270%28v=exchg.160%29.aspx).
    
- **Grupos de distribución dinámicos** La pertenencia a un grupo de distribución dinámico (también denominado lista de distribución dinámica o lista de distribución basada en consultas) se calcula cada vez que se envía un mensaje al grupo. Este cálculo se basa en filtros y en condiciones que define el administrador. Se administran en Exchange Online a través de Windows PowerShell remoto. Para obtener más información sobre grupos de distribución dinámica, consulte [Administrar grupos de distribución dinámica](https://technet.microsoft.com/EN-US/library/bb123722%28v=exchg.160%29.aspx).
    
    > [!IMPORTANT]
    > La herramienta de sincronización de directorios de Office 365 ignora los grupos de distribución dinámica en Active Directory local y no los sincroniza con Exchange Online. Las organizaciones que usen la herramienta de sincronización de directorios deberían usar una convención de nomenclatura que evite conflictos entre los grupos de distribución regular administrados localmente y los grupos de distribución dinámica administrados en Exchange Online. 
  
- **Grupos de distribución moderados** Los administradores pueden seleccionar un moderador para regular el flujo de los mensajes a un grupo de distribución. Con los grupos de distribución moderados, todo el mundo puede enviar correo electrónico al alias del grupo de distribución, pero antes de que el mensaje se entregue a los miembros del grupo, un moderador debe revisarlo y aprobarlo. Para obtener más información sobre la moderación, consulte la sección Aprobación de mensajes en [Administrar grupos de distribución](https://technet.microsoft.com/EN-US/library/mt577270%28v=exchg.160%29.aspx).
    
- **Grupos de distribución de autoservicio** Los administradores pueden otorgar a los usuarios la capacidad de administrar su propia pertenencia al grupo de distribución desde una interfaz basada en web. Los usuarios pueden dar permisos para crear, eliminar, unirse o dejar los grupos de distribución. Estas funcionalidades están habilitadas de forma predeterminada para todos los usuarios de Exchange Online. Los administradores pueden deshabilitarlas para que solo el departamento de TI pueda administrar los grupos de distribución, si le interesa. También pueden crear directivas de nomenclatura para estandarizar y administrar los nombres de los grupos de distribución que creen sus usuarios. Por ejemplo, pueden agregar un prefijo o sufijo concreto al nombre del grupo de distribución cuando se crea o bloquear el uso de palabras concretas en el nombre del grupo. 
    
    > [!IMPORTANT]
    > Las capacidades de autoservicio no están disponibles para los grupos de distribución sincronizados desde Active Directory local con Exchange Online. Las organizaciones que usen la herramienta de sincronización de directorios deberían usar una convención de nomenclatura que evite conflictos entre los grupos de distribución que estén administrados localmente y los grupos de distribución administrados en la nube. 
  
### <a name="external-contacts-global"></a>Contactos externos (globales)

Un contacto externo es un registro con información acerca de una persona que trabaja fuera de una organización concreta. Los contactos externos son similares a los grupos personales que las personas crean en Outlook, sólo que están disponibles globalmente en la empresa. Los administradores crean contactos externos con el Centro de administración de Exchange o Windows PowerShell remoto. Estos contactos también se pueden sincronizar con Exchange Online desde Active Directory local. Aparecen en la lista global de direcciones en Outlook.
  
Para obtener más información sobre contactos externos, consulte [Crear una relación de organización en Exchange Online](https://technet.microsoft.com/EN-US/library/jj916671%28v=exchg.150%29.aspx).
  
## <a name="calendar-and-scheduling"></a>Calendario y programación

### <a name="resource-mailboxes"></a>Buzones de recursos

Los buzones de recursos (como las salas de conferencias y los equipamientos físicos) representan las salas de reunión de una empresa u otras instalaciones o recursos. Los usuarios pueden reservar salas o recursos agregando el alias del correo electrónico del recurso a las solicitudes de reuniones en Outlook o Outlook Web App. Las salas de conferencias y los recursos aparecen en la lista global de direcciones en Outlook y Outlook Web App.
  
Los administradores crean buzones de correo de recursos mediante el Centro de administración de Exchange para Windows PowerShell remoto. Los buzones de correo también se pueden sincronizar con Exchange Online desde Active Directory local.
  
Para obtener más información acerca de buzones de recursos, consulte:
  
- [Crear y administrar buzones de sala](http://go.microsoft.com/fwlink/?LinkId=717533&amp;clcid=0x409)
    
- [Administrar buzones de equipo](https://go.microsoft.com/fwlink/?LinkId=717534)
    
### <a name="conference-room-management"></a>Administración de la sala de conferencias

Exchange Online incluye el Operador para reserva de recursos (RBA), que automatiza la programación de las salas de conferencias y otros recursos. Un buzón de recursos configurado por RBA acepta, rechaza o admite solicitudes de reuniones de un organizador de reuniones según la disponibilidad del calendario del recurso. 
  
Los administradores pueden personalizar las respuestas automatizadas de la sala de conferencias y configurar directivas de reservas en Outlook Web App. Estas directivas incluyen quién puede programar el recurso, cuándo se puede programar, la información de la reunión que es visible en el calendario de recursos y el porcentaje de conflictos de programación que se permite. Los administradores pueden deshabilitar el Operador para reserva de recursos y asignar usuarios específicos para que administren manualmente las solicitudes de las salas de conferencias.
  
Los administradores deben definir y administrar la configuración de RBA a través de Windows PowerShell remoto.
  
### <a name="out-of-office-replies"></a>Respuestas de fuera de la oficina

Los mensajes de fuera de la oficina son respuestas automáticas a mensajes entrantes que Exchange Online envía en nombre de un usuario. Los usuarios pueden programar los mensajes de fuera de la oficina por avanzado, con horas de inicio y fin específicas y pueden configurar mensajes de fuera de la oficina independientes para destinatarios internos y externos. También pueden establecer mensajes de fuera de la oficina desde dispositivos móviles compatibles con esta característica de Exchange ActiveSync. El reconocimiento de correo electrónico no deseado y de listas de distribución de correo en Exchange Online evita que los usuarios envíen mensajes de fuera de la oficina externos a listas de distribución de correo y spammers potenciales. Los administradores también pueden evitar que los usuarios envíen mensajes de fuera de la oficina a usuarios externos con Windows PowerShell remoto.
  
### <a name="calendar-sharing"></a>Uso compartido de calendarios

Los usuarios pueden compartir su calendario personal de dos maneras:
  
- **Uso compartido de calendario federado** La federación hace referencia a la infraestructura de confianza subyacente que es compatible con el uso compartido federado, un método sencillo para que los usuarios de Exchange compartan la información de disponibilidad de datos de calendario y de contactos con los destinatarios en otras organizaciones federadas externas. Esto incluye organizaciones de Exchange Online u organizaciones que ejecuten Exchange Server 2010 o Exchange Server 2013 local. Los administradores de Exchange Online no tienen que establecer una confianza con Microsoft Federation Gateway ya que esta confianza está preconfigurada para todos los clientes de Exchange Online cuando se crea el servicio de inquilinos de Office 365. Una directiva de uso compartido predeterminada permite a los usuarios enviar invitaciones de uso compartido de calendarios desde Outlook Web App o Outlook 2010. Los administradores usan Windows PowerShell remoto para deshabilitar esta directiva o para configurar el nivel de información de disponibilidad del calendario que los usuarios pueden compartir. Los administradores también pueden crear una relación entre organizaciones con otras organizaciones federadas, que permita el nivel deseado de información de confidencialidad de cada usuario que sea visible a través de la organización sin la necesidad de que el usuario comparta la invitación. En el ámbito de las directivas de uso compartido definidas por el administrador, los usuarios pueden limitar individualmente el detalle de su uso compartido. 
    
- **Uso compartido de calendario de Internet** Exchange Online permite a los usuarios publicar sus calendarios con el formato iCal para el acceso anónimo de cualquier persona dentro y fuera de la organización. Los destinatarios pueden utilizar Exchange, otra plataforma o simplemente un explorador web. Los usuarios de Exchange Online también pueden suscribirse a calendarios que otros usuarios hayan publicado en ubicaciones de Internet mediante iCal. Este uso compartido de calendarios personal es diferente al uso compartido del calendario federado, que lo configura un administrador y proporciona el uso compartido de disponibilidad entre organizaciones. Ningún usuario puede publicar datos de calendarios en formato iCal hasta que el administrador haya establecido y aplicado una directiva de uso compartido que lo permita. Los administradores pueden deshabilitar la publicación de y las suscripciones de iCal para los usuarios de la organización usando un Windows PowerShell remoto. 
    
Para obtener más información sobre el uso compartido federado, vea [Uso compartido en Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271774).
  
### <a name="outlook-2010-room-finder"></a>Buscador de salas de Outlook 2010

Exchange Online es compatible con la característica Buscador de salas de Outlook 2010, que organiza las salas en listas (por ejemplo, una lista denominada "Salas del edificio 5") para que sea más fácil encontrar una sala próxima al programar una reunión. Para que aparezca en una lista de salas, un grupo de distribución se debe marcar específicamente mediante uno de estos dos métodos: 
  
- Una nueva lista de salas se puede crear mediante Windows PowerShell remoto. 
    
- Cualquier grupo de distribución que sólo contenga salas se puede convertir en una lista de salas mediante el Windows PowerShell remoto.
    
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes de Office 365, las opciones independientes y las soluciones locales, consulte [Descripción del servicio Exchange Online](exchange-online-service-description.md).
  

