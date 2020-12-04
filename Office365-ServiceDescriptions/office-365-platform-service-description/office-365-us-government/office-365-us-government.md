---
title: Office 365 Administración Pública
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 3f482abc-993f-41bf-8754-0f489a7e4861
description: En respuesta a los requisitos exclusivos y en constante evolución del sector público de los Estados Unidos, Microsoft ha creado Office 365 US Government Plans (o Office 365 Government). En este artículo se proporciona información general sobre las características específicas de los entornos de Office 365 Government US.
ms.openlocfilehash: 63cef3dfac77ae22bc413deab9d375c1cd110b46
ms.sourcegitcommit: 04f9191b177e714a8dbdd50e7a891ff295483dbe
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/03/2020
ms.locfileid: "49566682"
---
# <a name="office-365-government"></a>Office 365 Administración Pública

> [!IMPORTANT]
> Microsoft Teams está experimentando un gran aumento en las llamadas en línea y las conferencias de audio y vídeo debido al coronavirus (COVID-19) Pandemic.<br/>
>
>En respuesta al aumento sin precedentes de las llamadas y para garantizar la continuidad y la disponibilidad, Microsoft permite a los servidores de audio y vídeo GCC de Microsoft Teams aprovechar la capacidad de procesamiento en nuestros centros de recursos comerciales, así como en nuestros centros de administración de ti.<br/>
>
>Estos servidores de audio y vídeo residen en los servidores de límite alta acreditación de Microsoft Azure FedRAMP en los Estados Unidos y no almacenan ningún contenido de cliente. Sin embargo, estos servidores están procesando audio y vídeo para llamadas y conferencias y están operando bajo nuestro personal comercial durante este período provisional.<br/>
>
>El personal con pantalla cualificada está supervisando estos servidores para obtener posible acceso a los datos de los clientes mediante la revisión de los inicios de sesión interactivos en estos servidores. Personal cualificado cumplir con los requisitos de GCC para obtener acceso al contenido del cliente. Para obtener más información sobre los requisitos de filtrado, consulte la [Descripción del servicio GCC](gcc.md).<br/>
>
>Gracias por su apoyo mientras tomamos los pasos para garantizar que nuestros servicios sigan estando disponibles y sean confiables en estas extraordinarias horas.<br/>

En respuesta a los requisitos exclusivos y en constante evolución del sector público de los Estados Unidos, Microsoft ha creado Office 365 Government Plans (o Office 365 Government). Esta descripción de servicio proporciona una visión general de las características específicas de los entornos Office 365 Government US. Le recomendamos que lea esta descripción del servicio junto con otras [descripciones de servicio de Microsoft 365 y Office 365](../../office-365-service-descriptions-technet-library.md).

## <a name="how-to-use-this-service-description"></a>Cómo utilizar esta descripción del servicio

La descripción del servicio Office 365 Government está diseñada para servir como una superposición a la descripción del servicio Office 365 general. Define los compromisos y diferencias únicos con respecto a las ofertas de Office 365 Enterprise.

## <a name="about-office-365-government-environments"></a>Acerca de los entornos gubernamentales de Office 365

Los planes de Office 365 administración pública son suscripciones mensuales y se pueden conceder licencia a un número de usuarios ilimitado.

- El entorno de **Office 365 GCC** ofrece el cumplimiento de los requisitos federales para los servicios en la nube, incluido el FedRAMP alto, y los requisitos de la justicia penal y los sistemas de información fiscal federal (tipos de datos CJI y FTI).

- Los entornos **alto y DoD de Office 365 GCC** proporcionan el cumplimiento de las directrices de requisitos de seguridad del Departamento de defensa, el suplemento de las regulaciones de adquisición federal de defensa (DFARS) y el tráfico internacional en las regulaciones de brazos (ITAR).

Además de las características y capacidades de Office 365, las organizaciones que usan Office 365 administración pública se benefician de las siguientes características exclusivas de Office 365 Government:

- El contenido del cliente de su organización se separa de forma lógica del contenido del cliente en los servicios comerciales de Office 365 de Microsoft.

- El contenido del cliente de la organización se almacena dentro de los Estados Unidos.

- El acceso al contenido del cliente de la organización está restringido a personal específico de Microsoft.

- Office 365 Government cumple con las certificaciones y acreditaciones necesarias para los clientes del sector público de los Estados Unidos.

## <a name="customer-eligibility"></a>Idoneidad del cliente

Office 365 Government está disponible para (1) entidades de administración federal, estatal, local, tribal y territorial de Estados Unidos, y (2) otras entidades que administran datos sujetos a las regulaciones y los requisitos gubernamentales y en las que el uso de Office 365 Government es adecuado para cumplir estos requisitos, sujeto a la validación de elegibilidad. La validación de la idoneidad por parte de Microsoft incluirá la confirmación del tratamiento de datos de conformidad con el Reglamento internacional de tráfico de armas (ITAR), datos de cumplimiento de la ley de conformidad con la directiva de los Servicios de Información de Justicia Criminal (CJIS) del FBI u otros datos regulados o controlados por el gobierno. La validación puede requerir una prueba del registro en el Departamento de Estado de los Estados Unidos en el caso de los datos de ITAR o del patrocinio por un ente gubernamental con requisitos específicos para el tratamiento de los datos. El entorno de Office 365 DoD es para uso exclusivo del Departamento de defensa de los Estados Unidos.

Aunque los criterios de elegibilidad son coherentes en las ofertas de Office 365 Government, Microsoft solo aceptará DFARS y ITAR para el entorno alto de GCC.

Las entidades con preguntas sobre elegibilidad para Office 365 Government deben consultar a su equipo de cuentas.

Tras la renovación del contrato de un cliente para Office 365 Government, es necesario revalidar su elegibilidad.

## <a name="customer-content-located-within-the-united-states"></a>Contenido de cliente ubicado dentro de los Estados Unidos

Los servicios gubernamentales de Office 365 se proporcionan a partir de centros de recursos ubicados físicamente en los Estados Unidos. El siguiente contenido de cliente se almacena inactivo en centros de datos ubicados físicamente solo en los Estados Unidos:

- Contenido de los buzones de Exchange Online (cuerpos de correo electrónico, entradas de calendario y contenido de los datos adjuntos de correo electrónico)

- Contenido del sitio de SharePoint Online y los archivos almacenados en ese sitio

- Conversaciones archivadas, documentos cargados y sesiones de pizarra de Skype empresarial

- Conversaciones de chat persistente de Microsoft Teams

> [!NOTE]
> Con el uso normal, Skype Empresarial no almacena contenido de cliente, pero si se produce dicho almacenamiento, estará en centros de datos ubicados en los Estados Unidos.

Si los usuarios se encuentran en Estados Unidos mientras usan Office para la web (anteriormente conocido como Office Web Apps) o si adoptamos el uso de los servicios de Federación de Active Directory (AD FS) 2,0 y configuramos directivas para garantizar que los usuarios se conecten a los servicios a través del inicio de sesión único, el contenido de los clientes que se almacenen temporalmente en la web

La página de uso del sitio para los sitios de SharePoint está disponible para los planes gubernamentales, aunque por cumplimiento, hay algunas características de esta página que solo están disponibles para los clientes comerciales. Para obtener más información, vea [Página de uso del sitio para los sitios de SharePoint en Microsoft 365](https://support.microsoft.com/office/2fa8ddc2-c4b3-4268-8d26-a772dc55779e).

## <a name="office-365-government-and-third-party-services"></a>Office 365 administración pública y servicios de terceros

Office 365 ofrece la capacidad de integrar aplicaciones de terceros en sitios de SharePoint Online, Skype empresarial, aplicaciones de Office incluidas en Microsoft 365 apps for Enterprise (como Word, Excel, PowerPoint y Outlook) y Outlook Web App. Además, Office 365 admite la integración con proveedores de servicios de terceros. Estos servicios y aplicaciones de terceros pueden incluir el almacenamiento, la transmisión y el procesamiento de los datos de clientes de la organización en sistemas de terceros que se encuentren fuera de la infraestructura de Office 365 y, por tanto, no se encuentran protegidos por los compromisos de protección de datos y cumplimiento de Office 365. Le recomendamos que revise las declaraciones de privacidad y de cumplimiento proporcionadas por los terceros para evaluar el uso apropiado de estos servicios en su organización.

## <a name="restricted-data-access-by-administrators"></a>Acceso a datos restringido por los administradores

El acceso al contenido del cliente de Office 365 Government para los administradores de Microsoft está restringido al personal de la pantalla. Para obtener información sobre los niveles de filtrado, consulte la página de Descripción del servicio para cada entorno respectivo (GCC o GCC High y DoD).

## <a name="fasttrack-center-onboarding-assistance"></a>Asistencia para la incorporación del centro de FastTrack

Con el beneficio del centro FastTrack para Office 365<sup>1</sup>, trabaja de forma remota con los especialistas de FastTrack para obtener el entorno de Office 365 listo para su uso y planear la implementación y el uso en la organización. El proceso de FastTrack presta servicios relacionados con la incorporación y aceptación por parte de los usuarios.

La incorporación consiste en lo siguiente:

- Incorporación principal: son tareas necesarias para la configuración de los inquilinos y la integración con Azure Active Directory (Azure AD), si es necesario. La incorporación principal también proporciona la línea base para incorporar otros servicios pertinentes.

- Tareas de incorporación y migración de servicios: las tareas de incorporación de servicios habilitan escenarios en el espacio empresarial. La migración de datos (incluidos el correo electrónico y los archivos) se describe en la [migración de datos](https://aka.ms/whatcanmigrate). <sup>2</sup>

Los servicios de adopción de usuarios están formados por tareas que le ayudarán a asegurarse de que los usuarios tienen constancia de los servicios elegibles y pueden usarlos para impulsar el valor empresarial. Esta asistencia se presta en paralelo a las actividades de incorporación.

[Aquí](https://aka.ms/whatistheprocess)puede encontrar información específica sobre el proceso del centro FastTrack. Para obtener un desglose de los roles y las responsabilidades de negociación, revise las [responsabilidades de FastTrack](https://aka.ms/whatdoesftcdo) y [sus responsabilidades](https://aka.ms/whatdowedo).

> <sup>1</sup> debe comprar al menos 50 licencias en la lista de [planes elegibles](https://aka.ms/whocanbenefit) para recibir los servicios de FastTrack.
<br/><sup>2</sup> los servicios de migración de datos están disponibles para los inquilinos de Office 365 con 500 o más licencias.

## <a name="data-migrations-performed-by-fasttrack"></a>Migraciones de datos realizadas por FastTrack

Los clientes que elijan la ventaja de migración de [FastTrack](https://fasttrack.microsoft.com/) deberán conceder acceso al equipo que administra sus migraciones de datos. Este personal es ciudadano estadounidense y se somete a las siguientes comprobaciones de antecedentes antes de realizar las migraciones para los clientes de Office 365 US Government Services.<br><br>

|Detección en segundo plano|GCC|GCC High y DoD|
|---|---|---|
|Comprobación de la ciudadanía estadounidense|Sí|Sí|
|Comprobación del historial de empleo|Sí|Sí|
|Verificación de educación|Sí|Sí|
|Búsqueda en el número de la seguridad social (SSN)|Sí|Sí|
|Comprobación de los antecedentes penales (7 años)|Sí|Sí|

## <a name="office-365-us-government-and-azure-government-expressroute"></a>Office 365 Administración Pública y Azure Government ExpressRoute

Office 365 US Government customers pueden usar los servicios de Azure Government ExpressRoute para conectarse de forma privada a los servicios de Office 365 compatibles en lugar de conectarse a través de Internet público.

Para obtener más información, como los proveedores admitidos, los modelos de precios y mucho más, revise la [información de Azure ExpressRoute](https://go.microsoft.com/fwlink/?LinkID=798220&amp;clcid=0x409).

Para obtener más información sobre el soporte técnico de Office 365 para Azure ExpressRoute, consulte [Azure expressroute para office 365](https://go.microsoft.com/fwlink/?LinkID=798216&amp;clcid=0x409)

## <a name="system-requirements"></a>Requisitos del sistema

Para obtener información sobre los requisitos del sistema para los planes de Office 365 Administración Pública, vea [Requisitos del sistema para Office](https://go.microsoft.com/fwlink/?LinkID=626095&amp;clcid=0x409) en el sitio de productos de [office.com](https://go.microsoft.com/fwlink/?LinkID=509817&amp;clcid=0x409).

## <a name="security-amp-compliance-center"></a>Security &amp; Compliance Center

Para obtener información acerca del &amp; centro de seguridad y cumplimiento, así como vínculos a información adicional y disponibilidad, consulte [Security &amp; Compliance Center](../../office-365-platform-service-description/office-365-securitycompliance-center.md).

## <a name="service-availability-for-each-plan"></a>Disponibilidad del servicio para cada plan

Cada plan de Office 365 incluye varios servicios individuales, como Exchange Online y SharePoint Online. En la siguiente tabla se muestran los servicios disponibles en cada plan de Office 365 Administración Pública.<br><br>

|Servicio de Office 365|Office 365 Administración Pública G1|Office 365 Administración Pública G3|Office 365 Administración Pública G5|Office 365 administración pública F3|
|---|---|---|---|---|
|Office para la web|Sí|Sí|Sí|Sí|
|Aplicaciones de Microsoft 365 para empresas|No|Sí|Sí|No|
|Exchange Online|Sí|Sí|Sí|Sí|
|Protección de Exchange Online|Sí|Sí|Sí|Sí|
|SharePoint Online|Sí|Sí|Sí|Sí|
|OneDrive para la Empresa|Sí|Sí|Sí|Sí|
|Skype for Business (Instant Messaging &amp; Presence)|Sí<sup>1</sup>|Sí|Sí|Sí<sup>1</sup>|
|Sistema de telefonía por voz, audioconferencia|No<sup>2</sup>|No<sup>2</sup>|Sí<sup>5</sup>|No|
|Power BI Pro|No<sup>2</sup>|No<sup>2</sup>|Sí|No<sup>2</sup>|
|Project Online|No<sup>2</sup>|No<sup>2</sup>|No<sup>2</sup>|No<sup>2</sup>|
|Visio para la web|No<sup>6</sup>|No<sup>6</sup>|No<sup>6</sup>|No<sup>6</sup>|
|Yammer Enterprise|No<sup>4</sup>|No<sup>4</sup>|No<sup>4</sup>|No<sup>4</sup>|

> <sup>1</sup> Skype empresarial Basic está disponible para todos los clientes. El cliente de escritorio de Skype Empresarial es una aplicación instalada localmente que proporciona funciones de presencia, de mensajería instantánea y de conferencias para los planes de Office 365 que incluyen Skype Empresarial Online. Las aplicaciones de Microsoft 365 para Enterprise, G3 y G5 incluyen la aplicación de Skype completa, que incluye características adicionales, como la compatibilidad avanzada con telefonía, el archivado y las características de cumplimiento. A Skype for Business Online license must be assigned for each user.
<br/><sup>2</sup> no se incluye, pero puede adquirirse como un complemento independiente. Project online incluye el cliente de escritorio de Project online como parte de la suscripción.
<br/> <sup>3</sup> todavía no está disponible en los planes de GCC High o DOD, pero lo estará próximamente.
<br/><sup>4</sup> Yammer Enterprise no es un componente de Office 365 US Government, pero puede adquirirse sin costo como una oferta independiente para cada usuario con licencia para Office 365 en gcc. Esta oferta actualmente está limitada a los clientes que adquieren Office 365 GCC en Enterprise Agreements and Enterprise subscription agreements. Yammer no está disponible en GCC High o DoD.
<br/><sup>5</sup> plan de llamadas es un complemento.
<br/><sup>6</sup> no se incluye, pero puede adquirirse como un complemento independiente. Visio para la web incluye la aplicación de escritorio de Visio como parte de la suscripción.

## <a name="platform-features"></a>Características de plataforma 

En la siguiente tabla se enumeran las características de la plataforma y los servicios que están disponibles en los planes de Office 365 Administración Pública.<br><br>

|Característica|Office 365 Administración Pública G1|Office 365 Administración Pública G3|Office 365 Administración Pública G5|Office 365 administración pública F3|
|---|---|---|---|---|
|**Administración de Office 365**|||||
|Usar el centro de administración de Microsoft 365 para administrar Office 365|Sí<sup>16</sup>|Sí<sup>16</sup>|Sí|Sí<sup>16</sup>|
|Administrar la configuración principal del servicio desde Office 365|Sí|Sí|Sí|Sí|
|Uso de Windows PowerShell para administrar Office 365|Sí|Sí|Sí|Sí|
|Proteger el contenido con Azure Information Protection|No<sup>1</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|No<sup>1</sup>|
|**[Características del conjunto de aplicaciones de Office 365](../../office-365-platform-service-description/office-365-suite-features.md)**|**Office 365 Administración Pública G1**|**Office 365 Administración Pública G3**|**Office 365 Administración Pública G5**|**Office 365 administración pública F3**|
|Reservas de Microsoft|No|Sí<sup>21</sup>|Sí<sup>21</sup>|No|
|Correo electrónico de Microsoft briefing|No|No|No|No|
|Microsoft Power Automate|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|
|Microsoft Forms|Sí|Sí|Sí<br/>|Sí</sup>|
|API de Microsoft Graph|Sí|Sí|Sí|Sí|
|Microsoft MyAnalytics|No|No|Sí<sup>17</sup>|No|
|Microsoft Planner|Sí|Sí|Sí|Sí|
|Microsoft PowerApps|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|
|Microsoft StaffHub|No|No|No|No<br/>|
|Microsoft Stream|Sí<sup>9, 15</sup>|Sí<sup>9, 15</sup>|Sí<sup>9, 15</sup>|Sí<sup>9, 15, 20</sup>|
|Microsoft Sway|No|No|No|No|
|Microsoft Teams|Sí|Sí|Sí|Sí|
|Office Delve|Sí<sup>17</sup>|Sí<sup>17</sup>|Sí|Sí<sup>17</sup>|
|Grupos de Office 365|Sí|Sí|Sí|Sí|
|**[Administración de cuentas de usuario](../../office-365-platform-service-description/user-account-management.md)**|**Office 365 Administración Pública G1**|**Office 365 Administración Pública G3**|**Office 365 Administración Pública G5**|**Office 365 administración pública F3**|
|Identidad de la nube|Sí|Sí|Sí|Sí|
|Identidad federada (inicio de sesión único)|Sí|Sí|Sí|Sí|
|Autenticación multifactor|Sí|Sí|Sí|Sí|
|Autenticación de factor de teléfono|Sí<sup>9</sup>|Sí<sup>9</sup>|Sí|Sí<sup>9</sup>|
|Configuración de escritorio de Office 365|Sí|Sí|Sí|Sí|
|Administrar usuarios con Office 365|Sí|Sí|Sí|Sí|
|Carga masiva con archivos. csv|Sí<sup>9</sup>|Sí<sup>9</sup>|Sí|Sí<sup>9</sup>|
|Herramienta de sincronización de directorios|Sí|Sí|Sí|Sí|
|Migración sencilla (transferencia) de Exchange|Sí|Sí|Sí|Sí|
|Eliminar cuentas mediante Office 365|Sí<sup>3</sup>|Sí<sup>3</sup>|Sí<sup>3</sup>|Sí<sup>3</sup>|
|El administrador puede restablecer la contraseña de usuario desde Office 365 o mediante Windows PowerShell|Sí<sup>4</sup>|Sí<sup>4</sup>|Sí<sup>4</sup>|Sí<sup>4</sup>|
|Los usuarios pueden cambiar su propia contraseña|Sí<sup>5</sup>|Sí<sup>5</sup>|Sí<sup>5</sup>|Sí<sup>5</sup>|
|Administrar licencias|Sí<sup>7, 8</sup>|Sí<sup>7, 8</sup>|Sí<sup>7, 8</sup>|Sí<sup>7,8</sup>|
|Administrar grupos de seguridad desde Office 365|Sí|Sí|Sí|Sí|
|Varios roles de administrador disponibles|Sí|Sí|Sí|Sí|
|Permitir que un socio administre Office 365 por usted|Sí<sup>11</sup>|Sí<sup>11</sup>|Sí<sup>11</sup>|Sí<sup>11</sup>|
|Servicios de Azure Active Directory|Sí|Sí|Sí|Sí|
|**[Dominios](../../office-365-platform-service-description/domains.md)**|**Office 365 Administración Pública G1**|**Office 365 Administración Pública G3**|**Office 365 Administración Pública G5**|**Office 365 administración pública F3**|
|Agregar dominios de segundo nivel personalizados, como fourthcoffee.com|Sí|Sí|Sí|Sí|
|Agregar dominios de tercer nivel personalizados, como marketing.fourthcoffee.com|Sí|Sí|Sí|Sí|
|Agregar hasta 900 dominios personalizados|Sí|Sí|Sí|Sí|
|Verificación de propiedad de dominio necesaria para dominios personalizados|Sí|Sí|Sí|Sí|
|**[Continuidad y estado del servicio](../../office-365-platform-service-description/service-health-and-continuity.md)**|**Office 365 Administración Pública G1**|**Office 365 Administración Pública G3**|**Office 365 Administración Pública G5**|**Office 365 administración pública F3**|
|Información de estado disponible en la página **Mantenimiento del servicio** o **Estado del servicio**|Sí<sup>9, 15</sup>|Sí<sup>9, 15</sup>|Sí<sup>9, 15</sup>|Sí<sup>9, 15</sup>|
|Estado de alertas individuales disponibles en el panel del centro de administración de Microsoft 365|Sí<sup>9, 15</sup>|Sí<sup>9, 15</sup>|Sí<sup>9, 15</sup>|Sí<sup>9, 15</sup>|
|Fuente RSS de **Mantenimiento del servicio**|Sí|Sí|Sí|Sí|
|**[Informes](../../office-365-platform-service-description/reports.md)**|**Office 365 Administración Pública G1**|**Office 365 Administración Pública G3**|**Office 365 Administración Pública G5**|**Office 365 administración pública F3**|
|Buzones activos e inactivos|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|
|Buzones eliminados y nuevos|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|
|Grupos nuevos y eliminados|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|
|Uso del buzón de correo|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|
|Tipos de conexiones de buzones|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|
|Correo enviado y recibido|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|
|Destinatarios y remitentes principales|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|
|Detecciones de correo no deseado|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|
|Detecciones de malware|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|
|Malware principal para correo|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|
|Coincidencias con reglas para correo|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|
|Coincidencias de reglas principales para correo|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|
|Coincidencias de directivas de DLP principales para correo|No|Sí<sup>15</sup>|Sí<sup>15</sup>|No|
|Coincidencias de directivas de DLP por gravedad para correo|No|Sí<sup>15</sup>|Sí<sup>15</sup>|No|
|Coincidencias de directivas de DLP, invalidaciones y falsos positivos para correo|No|Sí<sup>15</sup>|Sí<sup>15</sup>|No|
|Principales coincidencias de reglas de DLP para correo|No|Sí<sup>15</sup>|Sí<sup>15</sup>|No|
|Mensajería instantánea y sesiones de audio|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|
|Uso compartido de aplicaciones, web y conferencias de acceso telefónico local|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|
|Vídeo, uso compartido de aplicaciones y sesiones de transferencia de archivos|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|
|Mensajería instantánea y conferencias de audio y vídeo|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|
|Informes de protección de correo descargables|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|
|Explorador utilizado|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|
|Sistema operativo utilizado|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|
|Cree sus propios informes con los servicios Web de informes de Microsoft 365|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|
|**[Actualizaciones del servicio](../../office-365-platform-service-description/service-updates.md)**|**Office 365 Administración Pública G1**|**Office 365 Administración Pública G3**|**Office 365 Administración Pública G5**|**Office 365 administración pública F3**|
|Actualizaciones habituales para todos los clientes|Sí|Sí|Sí|Sí|
|Las notificaciones se envían a Centro de mensajes cuando la acción es necesaria|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|Sí<sup>15</sup>|
|Roadmap.office.com para algún servicio actualizaciones|No<sup>10, 13</sup>|No<sup>10, 13</sup>|No<sup>10, 13</sup>|No<sup>10, 13</sup>|
|Opción para activar la versión dirigida|Sí<sup>10</sup>|Sí<sup>10</sup>|Sí<sup>10</sup>|Sí<sup>10</sup>|
|**[Ayuda y formación](../../office-365-platform-service-description/help-and-training.md)**|**Office 365 Administración Pública G1**|**Office 365 Administración Pública G3**|**Office 365 Administración Pública G5**|**Office 365 administración pública F3**|
|Ayuda en línea|Sí|Sí|Sí|Sí|
|Comunidad|Sí|Sí|Sí|Sí|
|Otros recursos de autoayuda|Sí|Sí|Sí|Sí|
|Formación a ritmo propio|Sí|Sí|Sí|Sí|
|**[Conexión de red](../../office-365-platform-service-description/networking.md)**|**Office 365 Administración Pública G1**|**Office 365 Administración Pública G3**|**Office 365 Administración Pública G5**|**Office 365 administración pública F3**|
|Protocolos IPv4 e IPv6|Sí|Sí|Sí|Sí|
|**Confianza**|**Office 365 Administración Pública G1**|**Office 365 Administración Pública G3**|**Office 365 Administración Pública G5**|**Office 365 administración pública F3**|
|**[Privacidad, seguridad y transparencia](../../office-365-platform-service-description/privacy-security-and-transparency.md)**|||||
|Gobierno de datos avanzado|No<sup>12</sup>|No<sup>12</sup>|Sí|No<sup>12</sup>|
|Cloud App Security|No<sup>12, 15, 19</sup>|No<sup>12, 15, 19</sup>|Sí<sup>15, 19</sup>|No<sup>12, 15, 19</sup>|
|Microsoft defender para Office 365|No<sup>12, 18</sup>|No<sup>12, 18</sup>|Sí<sup>18</sup>|No<sup>12, 18</sup>|
|Caja de seguridad del cliente|No<sup>12</sup>|No<sup>12</sup>|Sí|No<sup>12</sup>|
|eDiscovery avanzado|No<sup>12</sup>|No<sup>12</sup>|Sí|No<sup>12</sup>|
|Puntuación segura<sup>14</sup>|Sí<sup>9, 15</sup>|Sí<sup>9</sup>|Sí<sup>9, 15</sup>|Sí<sup>9, 15</sup>|
|Cifrado de mensajes de Office|No|Sí|Sí|No|
|Inteligencia de amenazas|No<sup>12</sup>|No<sup>12</sup>|Sí|No<sup>12</sup>|
|**[Cumplimiento](https://docs.microsoft.com/microsoft-365/compliance/offering-home)**|||||
|Evaluaciones SAS 70 / SSAE16|Sí|Sí|Sí|Sí|
|Certificación ISO 27001|Sí|Sí|Sí|Sí|
|Cláusulas del modelo de UE|Sí|Sí|Sí|Sí|
|Acuerdo "Puerto seguro" de EE. UU.|Sí|Sí|Sí|Sí|
|Acuerdo de asociados de negocios HIPAA|Sí|Sí|Sí|Sí|
|Autoridad FISMA para operar|Sí|Sí|Sí|Sí|
|Acuerdo de procesamiento de datos de Microsoft|Sí|Sí|Sí|Sí|
|PCI DSS Nivel Uno|Sí|Sí|Sí|Sí|
|Datos PAN regidos por PCI|No|No|No|No|
|**[Continuidad del servicio](../../office-365-platform-service-description/service-health-and-continuity.md)**|Sí|Sí|Sí|Sí|
|**[BlackBerry](../../office-365-platform-service-description/blackberry.md)**|**Office 365 Administración Pública G1**|**Office 365 Administración Pública G3**|**Office 365 Administración Pública G5**|**Office 365 administración pública F3**|
|Uso del Servicio Internet BlackBerry (BIS)|No<sup>2</sup>|No<sup>2</sup>|No<sup>2</sup>|No<sup>2</sup>|
|**[Asociados](../../office-365-platform-service-description/partners.md)**|||||
|Creación de invitaciones y pedidos de compra de prueba para un cliente que utiliza el plan especificado|N°<sup>11</sup>|N°<sup>11</sup>|N°<sup>11</sup>|N°<sup>11</sup>|
|Proporcionar administración delegada|N°<sup>11</sup>|N°<sup>11</sup>|N°<sup>11</sup>|N°<sup>11</sup>|
|**[Contrato de nivel de servicio](../../office-365-platform-service-description/service-level-agreement.md)**|Sí|Sí|Sí|Sí|
|**[Derechos de uso de producto](../../office-365-platform-service-description/product-use-rights.md)**|Sí|Sí|Sí|Sí|

> <sup>1</sup> Azure Information Protection no se incluye, pero puede adquirirse como un complemento independiente y habilitará las características de Information Rights Management (IRM) compatibles. Algunas características de Azure Information Protection requieren una suscripción a las aplicaciones de Microsoft 365 para empresas, que no se incluye con Office 365 el gobierno G1 o Office 365 Government F3. >
<br/><sup>2</sup> los clientes de BBCS y bis existentes pueden seguir usando el servicio. No se aceptan nuevos clientes.
<br/><sup>3</sup> si se usa la sincronización de directorios, debe eliminar las cuentas o cambiar las contraseñas con Active Directory, en lugar del portal de Office 365 o mediante el módulo Azure Active Directory para Windows PowerShell.
<br/><sup>4</sup> si se usa la sincronización de contraseñas, los usuarios deben cambiar sus contraseñas en Active Directory local.
<br/><sup>5</sup> para aprender a establecer directivas de administración de contraseñas de autoservicio para los usuarios, consulte [Administrar contraseñas en Azure ad](https://azure.microsoft.com/documentation/articles/active-directory-manage-passwords/).
<br/><sup>6</sup> solo puede tener un sitio web público con Office 365, a menos que haya actualizado desde una versión anterior de Office 365. En ese caso, tiene dos sitios web públicos, pero solo se puede hospedar uno de ellos con un nombre de dominio personalizado. Para obtener más información sobre cómo trabajar con los dos sitios web de suscripciones empresariales, vea [trabajar con los dos sitios web públicos de Office 365](https://go.microsoft.com/fwlink/p/?LinkID=271589). Si tiene una suscripción diferente, obtenga más información sobre los sitios web públicos en [información sobre hospedaje de sitios web de asociados y sitios web públicos en Office 365](https://go.microsoft.com/fwlink/p/?LinkID=325009).
<br/><sup>7</sup> reducir los puestos que se compraron con un descuento de términos puede estar sujeto a una cuota de finalización anticipada. Esto no se aplica a las suscripciones pagadas con carácter mensual.
<br/><sup>8</sup> los siguientes planes no admiten cambios de licencia por puesto desde el centro de administración de Microsoft 365: Office 365 el gobierno G1, Office 365 Government G3, Office 365 Government F3.
<br/><sup>9</sup> todavía no está disponible en gcc High, pero lo estará próximamente.
<br/><sup>10</sup> para Office 365 Government G1, G3 y F3, versión dirigida y el plan de desarrollo de Office 365 para empresas; sin embargo, puede haber algunas diferencias o retrasos para actualizaciones de servicio específicas debido a [los requisitos de cumplimiento](https://www.microsoft.com/trust-center).
<br/><sup>11</sup> todavía no está disponible en las ofertas de Office 365 Government, pero lo estará próximamente.
<br/><sup>12</sup> no se incluye, pero puede adquirirse como un complemento independiente en gcc.
<br/><sup>13</sup> no es compatible con las ofertas de Office 365 Government.
<br/><sup>14</sup> disponible en [https://securescore.office.com](https://securescore.office.com) . Requiere permisos de administrador. Para obtener más información, vea [Introducción a la puntuación segura de Office 365](https://docs.microsoft.com/microsoft-365/security/mtp/microsoft-secure-score).
).
<br/><sup>15</sup> todavía no está disponible en el entorno de DoD, pero lo estará próximamente.
<br/><sup>16</sup> el centro de administración no incluye análisis de uso en entornos altos DoD o gcc.
<br/><sup>17</sup> no es compatible con los entornos GCC altos o DoD.
<br/><sup>18</sup> el antiphishing para la suplantación de usuarios y dominios y la inteligencia de suplantación todavía no están disponibles en gcc High y DoD.
<br/><sup>19</sup> todavía no está disponible en el entorno GCC, pero lo estará próximamente.
<br/><sup>20</sup> consumo solo para Microsoft Stream: sin publicación ni uso compartido.
<br/><sup>21</sup> no está disponible para la API de Microsoft Graph o Microsoft Teams.

## <a name="office-application-availability-and-enterprise-value"></a>Disponibilidad de las aplicaciones de Office y valor empresarial

En la siguiente tabla se muestran las características de aplicaciones de Office que están disponibles en los planes de Office 365 Administración Pública.<br><br>

|Aplicación/característica|Office 365 Administración Pública G1|Office 365 Administración Pública G3|Office 365 Administración Pública G5|Office 365 administración pública F3|
|---|---|---|---|---|
|**Aplicaciones de Office**|||||
|[Microsoft Word](../../office-applications-service-description/office-applications.md#microsoft-word)<sup>7</sup>|No|Sí|Sí|No|
|[Microsoft Excel](../../office-applications-service-description/office-applications.md#microsoft-excel)<sup>7</sup>|No|Sí|Sí|No|
|[Microsoft PowerPoint](../../office-applications-service-description/office-applications.md#microsoft-powerpoint)<sup>7</sup>|No|Sí|Sí|No|
|[Microsoft OneNote](../../office-applications-service-description/office-applications.md#microsoft-onenote)<sup>7</sup>|No|Sí|Sí|No|
|[Microsoft Outlook](../../office-applications-service-description/office-applications.md#microsoft-outlook)<sup>7</sup>|No|Sí|Sí|No|
|Microsoft Forms<sup>7</sup>|Sí|Sí <br/>|Sí|No|
|Pizarra de Microsoft<sup>7</sup>|No|Sí|Sí|No|
|[Microsoft Publisher](../../office-applications-service-description/office-applications.md#microsoft-publisher)|No|Sí|Sí|No|
|[Microsoft Access](../../office-applications-service-description/office-applications.md#microsoft-access)|No|Sí|Sí|No|
|[Skype Empresarial](../../office-applications-service-description/office-applications.md#skype-for-business)|Sí<sup>3</sup>|Sí|Sí|Sí<sup>3</sup>|
|[Office para Mac para Office 365](https://support.office.com/article/General-requirements-for-Outlook-2016-for-Mac-A07A593D-B383-4906-A6C1-962D5543ED57)|No|Sí|Sí|No|
|[Office Mobile para iPhone o iPad](../../office-applications-service-description/office-applications.md#office-mobile-for-ipadiphone)|Sí|Sí<sup></sup>|Sí<sup></sup>|Sí|
|[Office Mobile para Android](../../office-applications-service-description/office-applications.md#office-mobile-for-android)|Sí|Sí<sup></sup>|Sí<sup></sup>|Sí|
|[Office Mobile para Windows Phone](../../office-applications-service-description/office-applications.md#office-mobile-for-windows-phone)|Sí|Sí<sup>4</sup>|Sí<sup>4</sup>|Sí|
|Office Mobile for Windows 10 tablets|Sí|Sí<sup></sup>|Sí<sup></sup>|Sí|
|Outlook para iOS y Android<sup>5, 4</sup>|Sí|Sí|Sí|Sí|
|**Valor empresarial**|**Office 365 Administración Pública G1**|**Office 365 Administración Pública G3**|**Office 365 Administración Pública G5**|**Office 365 administración pública F3**|
|Cinco instalaciones por usuario en PC o Mac|No|Sí|Sí|No|
|Aprovisionamiento de cuentas de usuario automatizado|Sí|Sí|Sí|Sí|
|Interfaz de usuario multilingüe|No|Sí|Sí|No|
|Implementación de comandos de cliente|No|Sí<sup>4</sup>|Sí<sup>4</sup>|No|
|Soporte para clientes sobre Exchange local|No|Sí|Sí|No|
|Soporte para clientes sobre SharePoint local|No|Sí|Sí|No|
|Control de las actualizaciones del software|No|Sí|Sí|No|
|Comparación de bases de datos|No|Sí|Sí|No|
|Virtualización de escritorio|No|Sí|Sí|No|
|Comparación de hojas de cálculo de Excel|No|Sí|Sí|No|
|Consulta de hojas de cálculo de Excel|No|Sí|Sí|No|
|Archivado y cumplimiento de Exchange Online y SharePoint Online|No|Sí|Sí|No|
|Soporte para directivas de grupos|No|Sí|Sí|No|
|Information Rights Management con Azure Information Protection|No<sup>1</sup>|Sí<sup>6</sup>|Sí<sup>6</sup>|No<sup>1</sup>|
|Information Rights Management mediante Windows Server AD RMS|Sí<sup>2</sup>|Sí<sup>2</sup>|Sí<sup>2</sup>|Sí<sup>2</sup>|
|Complemento de Office, ActiveX y soporte de BHO|No|Sí|Sí|No|
|Acceso de cliente de OneNote a blocs de notas en SharePoint Server, SharePoint Online, OneDrive para la Empresa y Office 365|No|Sí|Sí|No|
|Office Lens|No|No|No|No|
|Telemetría de Office|No|Sí<sup>4</sup>|Sí<sup>4</sup>|No|
|Soporte sin conexión para aplicaciones cliente|No|Sí|Sí|No|
|Instalación de cliente en paralelo optimizada|No|Sí|Sí|No|
|Power Map para Excel|No|Sí<sup>4</sup>|Sí<sup>4</sup>|No|
|Power Pivot para Excel|No|Sí<sup>4</sup>|Sí<sup>4</sup>|No|
|Power Query para Excel|No|Sí<sup>4</sup>|Sí<sup>4</sup>|No|
|Power View para Excel|No|Sí<sup>4</sup>|Sí<sup>4</sup>|No|
|Configuración de movilidad|No|Sí<sup></sup>|Sí<sup></sup>|No|
|Activación en equipos compartidos|No|Sí|Sí|No|
|Soporte para bloquear el almacenamiento de archivos basados en la nube|No|Sí|Sí|No|
|Actualizaciones de versión|No|Sí<sup>4</sup>|Sí<sup>4</sup>|No|
|Volume activation (KMS/MAK)|No|No|No|No|

> <sup>1</sup> Azure Information Protection no se incluye, pero puede adquirirse como un complemento independiente y habilitará las características de Information Rights Management (IRM) compatibles. Algunas características de Azure Information Protection requieren una suscripción a las aplicaciones de Microsoft 365 para empresas, que no se incluye con Office 365 el gobierno G1 o Office 365 Government F3.
<br/><sup>2</sup> Windows Server AD RMS es un servidor local que debe adquirirse y administrarse por separado para habilitar las características de IRM admitidas.
<br/><sup>3</sup> Skype empresarial Basic está disponible para todos los clientes. El cliente de escritorio de Skype Empresarial es una aplicación instalada localmente que proporciona funciones de presencia, de mensajería instantánea y de conferencias para los planes de Office 365 que incluyen Skype Empresarial Online. Microsoft 365 apps for Enterprise y Office 365 Enterprise E3 incluyen la aplicación de Skype completa, que incluye características adicionales, como la compatibilidad avanzada con telefonía, el archivado y las características de cumplimiento. A Skype for Business Online license must be assigned for each user. For more information on Lync Basic features, see [Skype for Business Online client comparison tables](https://docs.microsoft.com/lyncserver/lync-server-2013-desktop-client-comparison-tables).
<br/><sup>4</sup> todavía no está disponible en los entornos altos o DoD de GCC, pero lo estará próximamente.
<br/><sup>5</sup> consulte [uso de Outlook para iOS y Android en la nube de la comunidad de administración pública](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud) para obtener más información.
<br/><sup>6</sup> todavía no está disponible en el entorno de Office 365 DOD, pero lo estará próximamente.
<br/><sup>7</sup> las aplicaciones están completamente disponibles en las nubes gubernamentales, con la excepción de las características específicas que no están disponibles en este momento. Consulte [disponibilidad](#office-application-and-feature-availability-in-government-plans) de las características de las aplicaciones de Office para obtener más información.

## <a name="office-application-and-feature-availability-in-government-plans"></a>Disponibilidad de características y aplicaciones de Office en los planes gubernamentales

Las siguientes aplicaciones de Office están disponibles en las nubes gubernamentales; sin embargo, es posible que algunas funciones basadas en la nube no estén disponibles actualmente, como se indica en la tabla.<br><br>

|Aplicación/característica|GCC|GCC High|DOD|
|---|---|---|---|
|[**Microsoft Excel**](../../office-applications-service-description/office-applications.md#microsoft-excel) está completamente disponible en las nubes gubernamentales excepto en las siguientes características, que **no están** disponibles en este momento:||||
|animaciones 3D incrustadas y modelos 3D|No|No|No|
|Tipos de datos|No|No|No|
|Relleno rápido|No|No|No|
|Ideas (servicios de conocimientos)|No|No|No|
|Integración mejorada con Power BI (objetos visuales personalizados, crear gráficos PBI directamente desde Excel)|No|No|No|
|Tinta digital inteligente|No|No|No|
|Grupos de Office 365|No|No|No|
|Datos de gráficos dinámicos conectados a tablas dinámicas|No|No|No|
|PowerPivot|No|No|No|
|Publicación en Power BI|No|No|No|
|Colaboración en tiempo real (presencia, coautoría normal, chat dentro del documento)|No|No|No|
|Shared with Me|No|No|No|
|Búsqueda inteligente|No|No|No|
|Gráficos: Treemap sol, cascada, histograma, mapas, escala de tiempo, embudo|No|No|No|
|Historial de versiones|No|No|No|
|[**Microsoft Forms**](https://support.office.com/article/5cbd407a-eef7-431e-8e3a-eb666eab4b4c) está completamente disponible en las nubes gubernamentales excepto en las siguientes características, que **no están** disponibles en este momento:|**GCC**|**GCC High**|**REQUISITO**|
|Notificación de correo electrónico|No<sup>1</sup>|No<sup>1</sup>|No|
|Insertar una imagen|No<sup>1</sup>|No<sup>1</sup>|No|
|Insertar un vídeo|No<sup>1</sup>|No<sup>1</sup>|No|
|Matemáticas|No<sup>1</sup>|No<sup>1</sup>|No|
|Integración con Office|No<sup>1</sup>|No<sup>1</sup>|No|
|Formularios de grupo más recientes|No<sup>4</sup>|Sí|Sí|
|Uso compartido externo<sup>3</sup>|Sí|No|No|
|Forms Pro|No|No|No|
|[**Microsoft OneNote**](../../office-applications-service-description/office-applications.md#microsoft-onenote) está completamente disponible en las nubes gubernamentales, excepto en las siguientes características, que **no están** disponibles en este momento:|**GCC**|**GCC High**|**REQUISITO**|
|Investigador|No|No|No|
|Tinta digital inteligente|No|No|No|
|[**Microsoft Outlook**](../../office-applications-service-description/office-applications.md#microsoft-outlook) está completamente disponible en las nubes gubernamentales, excepto en las siguientes características, que **no están** disponibles en este momento:|**GCC**|**GCC High**|**REQUISITO**|
|Sonidos de Office (algunos)|No|No|No|
|Intercambio dinámico de datos (DDE) deshabilitado de forma predeterminada|No|No|No|
|Dictado|No<sup>1</sup>|No<sup>1</sup>|No<sup>1</sup>|
|[**Microsoft PowerPoint**](../../office-applications-service-description/office-applications.md#microsoft-powerpoint) está completamente disponible en las nubes gubernamentales, excepto en las siguientes características, que **no están** disponibles en este momento:|**GCC**|**GCC High**|**REQUISITO**|
|Búsqueda inteligente|No|No|No|
|Sonidos de Office (algunos)|No|No|No|
|modelos 3D y animaciones incrustadas en 3D|No|No|No|
|Gráficos: mapas|No|No|No|
|Tinta digital inteligente|No|No|No|
|Títulos en directo y subtítulos en PowerPoint|No|No|No|
|Autocar del moderador|No|No|No|
|Shared with Me|No|No|No|
|Integración de Skype empresarial con uso compartido|No|No|No|
|Historial de versiones|No|No|No|
|Grupos de Office 365|No|No|No|
|Colaboración en tiempo real (presencia, coautoría normal, chat dentro del documento)|No|No|No|
|Dictado|No<sup>1</sup>|No<sup>1</sup>|No<sup>1</sup>|
|Volver a usar diapositivas|No|No|No|
|La **pizarra de Microsoft** en nubes gubernamentales solo está disponible actualmente en los clientes concentradores y no en el escritorio.|**GCC**<sup>2</sup>|**GCC**<sup>2</sup> superior|**DoD**<sup>2</sup>|
|Insertar notas rápidas, texto e imágenes|Sí<sup>2</sup> <br/>|Sí<sup>2</sup> <br/>|Sí<sup>2</sup> <br/>|
|Entrada de lápiz a forma y de entrada de lápiz a tabla|Sí<sup>2</sup> <br/>|Sí<sup>2</sup> <br/>|Sí<sup>2</sup> <br/>|
|Beautification de entrada de lápiz|Sí<sup>2</sup> <br/>|Sí<sup>2</sup> <br/>|Sí<sup>2</sup> <br/>|
|Convertir la imagen en tinta|Sí<sup>2</sup> <br/>|Sí<sup>2</sup> <br/>|Sí<sup>2</sup> <br/>|
|Comprobador de accesibilidad|Sí<sup>2</sup> <br/>|Sí<sup>2</sup> <br/>|Sí<sup>2</sup> <br/>|
|Plantillas dinámicas (KANBAN, DAFO, etc.)|No|No|No|
|Colaboración en tiempo real|No|No|No|
|Presencia en tiempo real|No|No|No|
|Reacciones sobre el contenido|No|No|No|
|Galería de pizarras, incluidos los compartidos|No|No|No|
|[**Microsoft Word**](../../office-applications-service-description/office-applications.md#microsoft-word) está completamente disponible en las nubes gubernamentales excepto en las siguientes características, que **no están** disponibles en este momento:|**GCC**|**GCC High**|**REQUISITO**|
|Búsqueda inteligente|No|No|No|
|Investigador|No|No|No|
|Sonidos de Office|No|No|No|
|modelos 3D|No|No|No|
|animaciones incrustadas en 3D|No|No|No|
|Pulsar|No|No|No|
|Asistente para currículum vítae|No|No|No|
|Gráficos de mapa|No|No|No|
|Tinta digital inteligente|No|No|No|
|Shared with Me|No|No|No|
|Translation|No|No|No|
|Integración de Skype empresarial con uso compartido|No|No|No|
|Historial de versiones|No|No|No|
|Grupos de Office 365|No|No|No|
|Chat contextual con coautores: charle con coautores en el documento|No|No|No|
|Dictado|No<sup>1</sup>|No<sup>1</sup>|No<sup>1</sup>|

Para obtener la disponibilidad de las características de Microsoft Teams en GCC/GCC High/DoD, visite la [Descripción del servicio Microsoft Teams](https://docs.microsoft.com/office365/servicedescriptions/teams-service-description).
> <sup>1</sup> disponibilidad próximamente.
<br/><sup>2</sup> disponibilidad en Surface Hub local (no iniciada).
<br/><sup>3</sup> el uso compartido externo está disponible para el entorno gcc. Obtenga más información sobre cómo [activar o desactivar Microsoft Forms](https://support.office.com/article/cc52287a-4550-464d-9a1b-457bf9df2240#PickTab=Configure) para su organización. El uso compartido externo está deshabilitado para los entornos de GCC altos y DOD; los usuarios de la organización pueden hacer lo siguiente: completar un formulario y enviar respuestas, [duplicar y compartir un formulario como una plantilla](https://support.office.com/article/82ea9d8a-260a-47a0-afdb-497f3d746e3f), [trabajar en co-autoría o colaborar en un formulario](https://support.office.com/article/d5bb5cf0-8401-4c15-bb8c-8e108cd7e69b), y [obtener acceso a los resultados del formulario](https://support.office.com/article/02859424-341d-406f-b32a-9a0fbaf357af).
<br/><sup>4</sup> la característica de formularios de grupo recientes está deshabilitada para el entorno gcc. Sin embargo, los usuarios aún pueden tener acceso a los formularios de grupo seleccionando un grupo específico en la pestaña formularios de grupo.
