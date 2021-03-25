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
description: Obtenga información sobre la planeación y la implementación en Microsoft Exchange Online.
ms.openlocfilehash: fb9a63fecd0a64e8b896fb63acfffeb873a56281
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173345"
---
# <a name="planning-and-deployment"></a>Planificación e implementación

## <a name="planning-for-service-changes-and-growth"></a>Planificación para el crecimiento y cambios en el servicio

Las organizaciones deben elegir las opciones de migración en función de sus sistemas de correo electrónico de origen, del estado final deseado (hospedado total o parcialmente), del número de usuarios que se vayan a migrar y de lo rápido que se deba alcanzar el estado final.
  
## <a name="deployment-options"></a>Opciones de implementación

- **Implementación solo en la nube:** la organización tiene todos los buzones de usuario hospedados en Exchange Online. 
    
- **Implementación híbrida de Exchange:** la organización tiene algunos buzones de usuario hospedados en una organización local de Exchange y algunos buzones de usuario hospedados en Exchange Online. 
    
### <a name="cloud-only"></a>Solo de nube

Una implementación basada solo en la nube es aquella en la que la organización del servicio de Exchange Online no está conectada a ninguna organización local de Exchange. Todos los usuarios y los buzones se hospedan y administran en Exchange Online y en Office 365.
  
### <a name="hybrid"></a>Híbrido

Disponible para las organizaciones locales de Microsoft Exchange 2003, Exchange 2007, Exchange 2010 y Exchange 2013, una implementación híbrida ofrece una configuración de coexistencia a largo plazo con algunos buzones hospedados de forma local y otros en Exchange Online o una ruta de acceso de migración para hospedar todos los buzones de usuario en Exchange Online. Las implementaciones híbridas proporcionan a las organizaciones la capacidad para ampliar su experiencia con múltiples características y expandir el control administrativo que poseen con su organización local existente de Microsoft Exchange en la nube. Entre las características de la implementación híbrida se incluye el transporte de correo seguro, la información de disponibilidad de calendario compartida y el seguimiento de mensajes entre las organizaciones locales y de Exchange Online.
  
Para obtener más información sobre las implementaciones híbridas, vea [Implementaciones híbridas de Exchange Server 2013](/exchange/exchange-hybrid). Si usa Office 365 ofrecido por 21Vianet, vea [Configurar las características de una implementación híbrida de Exchange con Office 365 ofrecido por 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733373&amp;clcid=0x409).
  
> [!IMPORTANT]
> En las organizaciones locales de Exchange 2003 es necesario instalar como mínimo un servidor de buzones o de acceso de clientes de Exchange 2010 para configurar una implementación híbrida en Exchange Online. En las organizaciones locales de Exchange 2007 es necesario instalar como mínimo un servidor de buzones y de acceso de clientes de Exchange 2010 o Exchange 2013 para configurar una implementación híbrida en Exchange Online. Las organizaciones locales de Exchange 2010 y Exchange 2013 admiten las implementaciones híbridas de forma nativa con Exchange Online. Para obtener más información sobre la compatibilidad de Exchange Server en implementaciones híbridas, vea [Requisitos previos de la implementación híbrida](/exchange/hybrid-deployment-prerequisites)> Es necesario configurar las organizaciones locales de Exchange para realizar una implementación híbrida. Recomendamos a los administradores que usen el asistente para la implementación de Exchange Server y el Asistente para la configuración híbrida para configurar la implementación híbrida. Para obtener más información, vea [Asistente para la implementación de Exchange Server](/exchange/exchange-deployment-assistant)
  
## <a name="migration-options"></a>Opciones de migración

Las organizaciones deben elegir las opciones de migración en función de sus sistemas de correo electrónico de origen, del estado final deseado (hospedado total o parcialmente), del número de usuarios que se vayan a migrar y de lo rápido que se deba alcanzar el estado final. Entre las opciones de migración posibles se incluyen:
  
- **Migración de IMAP:** migre los datos de buzones de correo de sistemas de correo electrónico basados en IMAP a Exchange Online. 
    
- Migración de **Exchange** de escala: migre los buzones de Exchange Server 2003, Exchange Server 2007, Exchange Server 2010, Exchange 2013 y sistemas hospedados de Exchange a Exchange Online en una única migración de escala. 
    
- **Migración de Exchange** por fases: realice una migración por fases para migrar buzones de correo de Exchange Server 2003 o Exchange Server 2007 con herramientas de migración basadas en web y cambios mínimos en la infraestructura local. 
    
- **Migración de movimiento remoto:** migrar buzones de Exchange locales a Exchange Online en una implementación híbrida de Exchange. Debe tener una implementación híbrida de Exchange para poder usar una migración de movimiento remoto. 
    
Para obtener más información sobre cómo migrar correo electrónico y buzones a Exchange Online, consulte [Migración de buzones a Exchange Online ](https://support.office.com/article/-a3e3bddb-582e-4133-8670-e61b9f58627e).
  
### <a name="imap-migration"></a>Migración de IMAP

Exchange Online ofrece una herramienta basada en web para migrar datos de buzones desde sistemas de correo electrónico que admitan IMAP y guía a los administradores a través de los siguientes pasos de migración: 
  
1. Crear buzones vacíos en la nube para los usuarios de la organización (generalmente, para hacer esto se carga un archivo .csv o se usa Windows PowerShell en remoto).
    
2. Escribir la configuración de conexión del servidor remoto.
    
3. Usar un archivo CSV para especificar los buzones cuyos datos se van a migrar a los buzones de Exchange Online.
    
4. Después de indicar esta información, Exchange Online comienza a migrar el contenido de los buzones a través de IMAP (los elementos de calendario, contactos, tareas y otros elementos que no son de correo no se migran).
    
Para obtener más información sobre la migración de IMAP, consulte [Migración de correo electrónico de un servidor IMAP a buzones de Exchange Online](https://support.office.com/en-ie/article/Migrate-your-IMAP-mailboxes-to-Office-365-3fe19996-29bc-4879-aab9-5a622b2f1481) y [Migrar otros tipos de buzones IMAP](https://support.office.com/en-ie/article/Migrate-other-types-of-IMAP-mailboxes-to-Office-365-58890ccd-ce5e-4d94-be75-560a3b70a706).
  
> [!IMPORTANT]
> Para evitar el uso excesivo de los recursos del servidor remoto y del ancho de banda durante la migración, Exchange Online crea un máximo de 10 conexiones con el servidor IMAP. 
  
### <a name="cutover-exchange-migration"></a>Migración de Exchange de traslado

Exchange Online ofrece una herramienta basada en web para migrar datos desde entornos locales de Exchange Server 2003, Exchange Server 2007 o Exchange Server 2010 y guía a los administradores a través de los siguientes pasos de migración:
  
1. Mediante el uso de la dirección de correo electrónico y de las credenciales para una cuenta de administrador local, Exchange Online se conecta a la organización de correo electrónico local mediante el servicio Detección automática.
    
2. Exchange Online usa una conexión RPC/HTTP para leer la información de directorios del servidor remoto y crea buzones en Exchange Online.
    
3. Exchange Online sincroniza el contenido del buzón en los buzones de la nube. Los usuarios permanecen conectados a sus buzones originales mientras los datos se migran a Exchange Online.
    
4. Después de completar la migración inicial, los cambios que se produzcan se sincronizan en la nube cada 24 horas hasta que el administrador detenga o elimine el lote de migración.
    
Para cambiar los usuarios a sus buzones de correo en la nube, los administradores configuran su registro MX para que apunten a Microsoft y vuelvan a configurar los perfiles de los usuarios en Outlook. Cuando los usuarios se cambian a los buzones en la nube, las carpetas locales sin conexión (archivos .ost) se vuelven a sincronizar, lo que origina la descarga del correo migrado en la estación de trabajo del cliente. Los usuarios pueden responder a mensajes antiguos de sus buzones después de la migración.
  
Para obtener más información sobre una migración total de Exchange, consulte [Lo que debe saber sobre la migración total de correo electrónico a Office 365](https://support.office.com/article/365-961978ef-f434-472d-a811-1801733869da).
  
> [!IMPORTANT]
> Una organización puede migrar un máximo de 2.000 buzones de correo de Exchange 2003, Exchange 2007, Exchange 2010 o Exchange 2013 a la nube usando una migración total de Exchange. > Exchange Online debe conectar con un servidor Exchange local. Para ello, el servidor local debe tener un certificado emitido por una entidad de certificación de confianza y una dirección IP pública. 
  
### <a name="staged-exchange-migration"></a>Migración de Exchange preconfigurada

La migración por etapas permite que los usuarios se migren a la nube mediante la herramienta de migración de Exchange basada en web y la herramienta Sincronización de directorios. En lugar de migrar todos los usuarios a la vez, como en una migración de transferencia de Exchange, los administradores migran a los usuarios por lotes. Para ello, se carga un archivo .csv para especificar una lista parcial de los usuarios que se van a migrar. En una migración por etapas, todos los usuarios de la organización pueden compartir el mismo nombre de dominio de correo electrónico.
  
En la migración por etapas de Exchange se requiere que los administradores usen la herramienta de sincronización de directorios de Online Services. Esto proporciona a los usuarios una lista global de direcciones (LGD) unificada en la que el entorno en línea se sincroniza de manera constante con el entorno local.
  
Para obtener más información sobre las migraciones preconfiguradas de Exchange, consulte [Lo que debe saber sobre la migración preconfigurada de correo electrónico](https://support.office.com/en-ie/article/365-7e2c82be-5f3d-4e36-bc6b-e5b4d411e207).
  
> [!IMPORTANT]
> Las organizaciones no pueden usar una migración de Exchange por fases para migrar buzones de correo de Exchange 2010 y Exchange 2013. Si tiene menos de 2.000 buzones de correo de Exchange 2010 o Exchange 2013 en la organización, puede usar una migración total de Exchange. Si tiene más de 2.000 buzones de correo de Exchange 2010 o Exchange 2013, puede implementar una implementación híbrida. > Durante la migración, los administradores deben usar la herramienta de sincronización de directorios de Online Services para proporcionar a los usuarios una lista global de direcciones unificada en la que el entorno en línea se sincronice de manera constante con el entorno local. 
  
## <a name="migration-tools"></a>Herramientas de migración

Microsoft ofrece varias herramientas para la migración de un entorno de correo electrónico existente a Exchange Online. La elección de la herramienta adecuada dependerá del entorno actual de la organización y de los objetivos de la implementación:
  
- **Panel de migración:** los administradores pueden usar el panel de migración en el Centro de administración de Exchange para administrar la migración de buzones de correo a Exchange Online en una migración de Exchange por fases o por fases. También pueden usar el panel para migrar los contenidos de los buzones de correo de usuarios desde un servidor IMAP local a buzones de correo existentes de Exchange Online. El panel proporciona a los administradores las siguientes capacidades: 
    
  - **Crear e iniciar varios lotes de migración:** los administradores pueden crear y poner en cola hasta 100 lotes de migración. Solo se ejecuta un lote de migración a la vez, aunque los administradores pueden poner en cola varios lotes, para que cuando se finalice la ejecución de uno, se inicie la del próximo que está en la cola. 
    
  - Reiniciar un lote de migración con errores: después de la sincronización inicial de un lote de migración, donde los elementos se copian de buzones locales a los **buzones** de correo en la nube para cada usuario del lote de migración, algunos buzones pueden producir errores de sincronización. Los administradores pueden reiniciar ese lote de migración para intentar sincronizar los buzones erróneos. 
    
  -  Obtenga detalles sobre los elementos omitido: para las migraciones IMAP, las migraciones de recorte y las migraciones por fases, el panel de migración muestra información sobre los elementos específicos que se omitieron, incluido el motivo por el que y dónde se encuentra el elemento en el buzón del usuario. 
    
  - **Abrir informes de migración:** los administradores pueden abrir estadísticas de migración o el informe de errores de migración de un lote de migración directamente desde el panel. 
    
  - **Editar un** lote de migración: si un lote de migración para una migración de Exchange por fases o una migración IMAP está en la cola de migración pero no se está ejecutando actualmente, los administradores pueden editar el lote de migración. 
    
- **Herramienta de sincronización de Azure Active Directory:** la herramienta de sincronización de Azure Active Directory desempeña un papel importante en la migración a escenarios de correo electrónico híbrido que usan Exchange Online y un entorno Exchange Server. La herramienta realiza una sincronización unidireccional desde Active Directory local a Exchange Online. Una vez completada la migración, los administradores solo tienen que usar Exchange Online para administrar los usuarios y grupos de Active Directory. La herramienta también proporciona a los usuarios una lista global de direcciones (GAL) unificada en la que el entorno en línea se sincroniza de manera constante con el entorno local. 
    
    Para obtener más información sobre Herramienta de sincronización de Microsoft Azure Active Directory, vea el [Plan de desarrollo de sincronización de directorios](/azure/active-directory/hybrid/whatis-hybrid-identity).
    
- **Asistente para la** configuración híbrida: el Asistente para la configuración híbrida simplifica el proceso de implementación híbrida simplificando la configuración local y de Exchange Online de características y servicios. Incluido en el Service Pack 2 de Exchange Server 2010, el asistente de configuración híbrida se ejecuta solo en las organizaciones locales y tiene los siguientes componentes: 
    
  - Un asistente del Centro de administración de Exchange (EAC) que guía a los administradores por todo el proceso de un extremo a otro para configurar una implementación híbrida.
    
  - Un conjunto de comandos del Shell de administración de Exchange (EMS) que organizan el proceso de configuración.
    
    Para obtener más información sobre el Asistente para la configuración híbrida, vea [Asistente para la configuración híbrida](/exchange/hybrid-configuration-wizard).
    
- **Windows PowerShell** remoto: como parte de la actualización de servicio de diciembre de 2011 de Exchange Online, se puede usar Windows PowerShell remoto para ayudar a solucionar errores de migración. Por ejemplo, los administradores pueden mostrar información de diagnóstico de los lotes de migración, así como estadísticas e información de migración para los usuarios en función de sus direcciones SMTP principales. 
    
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, opciones independientes y soluciones locales, vea, [Descripción del servicio de Exchange Online](exchange-online-service-description.md).
