---
title: Office 365 Administración Pública
ms.author: danarl
author: danarl
manager: dianap
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 3f482abc-993f-41bf-8754-0f489a7e4861
description: En respuesta a los requisitos exclusivos y en constante evolución del sector público de los Estados Unidos, Microsoft ha creado Office 365 US Government Plans (o Office 365 Government). En esta sección se proporciona una introducción a las características específicas de los entornos de Office 365 Government US. Le recomendamos que lea esta sección complementaria junto con las descripciones de servicio de Office 365.
ms.openlocfilehash: be73b616012d37c2bd58df63587201675962ae11
ms.sourcegitcommit: d6b4bac54d41be873dcd2dbfd44463c8f3d49101
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/17/2020
ms.locfileid: "41216745"
---
# <a name="office-365-us-government"></a>Office 365 Administración Pública

En respuesta a los requisitos exclusivos y en constante evolución del sector público de los Estados Unidos, Microsoft ha creado Office 365 US Government Plans (o Office 365 Government). En esta sección se proporciona una introducción a las características específicas de los entornos de Office 365 Government US. Le recomendamos que lea esta sección complementaria junto con las [descripciones de servicio de Office 365 ](../../office-365-service-descriptions-technet-library.md).
  
## <a name="how-to-use-this-service-description-section"></a>Cómo utilizar esta sección de descripción del servicio

La descripción del servicio Office 365 Administración Pública está diseñada para servir como una superposición a la descripción general de servicios de Office 365. Define los compromisos y diferencias únicos con respecto a las ofertas de Office 365 Enterprise.
  
## <a name="about-office-365-us-government-environments"></a>Información sobre los entornos gubernamentales de Office 365 US

Los planes de Office 365 Administración Pública son suscripciones mensuales que pueden proporcionarse mediante licencia a un número de usuarios ilimitado. 
  
- El entorno de **Office 365 GCC** ofrece el cumplimiento de los requisitos federales para los servicios en la nube, incluido el FedRAMP moderado, y los requisitos de la justicia penal y los sistemas de información fiscal federal (tipos de datos CJI y FTI). 
    
- Los entornos **alto y DoD de Office 365 GCC** proporcionan el cumplimiento de las directrices de requisitos de seguridad del Departamento de defensa, el suplemento de las regulaciones de adquisición federal de defensa (DFARS) y el tráfico internacional en las regulaciones de brazos (ITAR). 
    
Además de las características y funcionalidades de Office 365, las organizaciones que usan Office 365 Administración Pública se pueden beneficiar de las siguientes características exclusivas de Office 365 Administración Pública:
  
- El contenido del cliente de su organización se separa de forma lógica del contenido del cliente en los servicios comerciales de Office 365 de Microsoft.
    
- El contenido del cliente de la organización se almacena dentro de los Estados Unidos.
    
- El acceso al contenido del cliente de la organización está restringido a personal específico de Microsoft.
    
- Office 365 Administración Pública cumple con las certificaciones y acreditaciones necesarias para los clientes del sector público de los Estados Unidos.
    
[Cómo usar esta sección de Descripción del servicio](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="customer-eligibility"></a>Idoneidad del cliente

Office 365 Administración Pública está disponible para (1) las entidades gubernamentales federales, estatales, locales, tribales y territoriales de los Estados Unidos y (2) otras entidades que gestionan datos de acuerdo con regulaciones y requisitos gubernamentales, en cuyo caso el uso de Office 365 Administración Pública es adecuado para cumplir dichos requisitos, sujetas a la validación de su idoneidad. La validación de la idoneidad por parte de Microsoft incluirá la confirmación del tratamiento de datos de conformidad con el Reglamento internacional de tráfico de armas (ITAR), datos de cumplimiento de la ley de conformidad con la directiva de los Servicios de Información de Justicia Criminal (CJIS) del FBI u otros datos regulados o controlados por el gobierno. La validación puede requerir una prueba del registro en el Departamento de Estado de los Estados Unidos en el caso de los datos de ITAR o del patrocinio por un ente gubernamental con requisitos específicos para el tratamiento de los datos. Office 365 DoD-Environment es para uso exclusivo del Departamento de defensa de los Estados Unidos.
  
Aunque los criterios de elegibilidad son coherentes en las ofertas de Office 365 Government, Microsoft solo aceptará DFARS y ITAR para el entorno alto de GCC.
  
Las entidades que tengan preguntas sobre su idoneidad para obtener Office 365 Administración Pública deben consultar con su equipo de cuentas.
  
Cuando se renueva el contrato de Office 365 Administración Pública del cliente, es necesario volver a validar la idoneidad.
  
[Cómo usar esta sección de Descripción del servicio](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="customer-content-located-within-the-united-states"></a>Contenido de cliente ubicado dentro de los Estados Unidos

Office 365 Administración Pública proporciona sus servicios desde centros de datos ubicados físicamente en los Estados Unidos. El siguiente contenido de cliente se almacena inactivo en centros de datos ubicados físicamente solo en los Estados Unidos: 
  
- Contenido de los buzones de Exchange Online (cuerpos de correo electrónico, entradas de calendario y contenido de los datos adjuntos de correo electrónico)
    
- Contenido del sitio de SharePoint Online y los archivos almacenados en ese sitio
    
- Conversaciones archivadas, documentos cargados y sesiones de pizarra de Skype empresarial

- Conversaciones de chat persistente de Microsoft Teams
    
> [!NOTE]
> Con el uso normal, Skype Empresarial no almacena contenido de cliente, pero si se produce dicho almacenamiento, estará en centros de datos ubicados en los Estados Unidos. 
  
Si los usuarios se encuentran en Estados Unidos mientras usan Office para la web (anteriormente conocido como Office Web Apps) o si adoptamos el uso de los servicios de Federación de Active Directory (AD FS) 2,0 y configuramos directivas para garantizar que los usuarios se conecten a los servicios a través de un solo si GN-on, cualquier contenido de cliente que se almacene en caché temporalmente en Office para la web estará ubicado en los Estados Unidos.
  
[Cómo usar esta sección de Descripción del servicio](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-365-us-government-and-third-party-services"></a>Office 365 Administración Pública y servicios de otros fabricantes

Office 365 proporciona la capacidad de integrar aplicaciones de terceros en sitios de SharePoint Online, Skype Empresarial, aplicaciones de Office incluidas en Office 365 ProPlus (como Word, Excel, PowerPoint y Outlook) y Outlook Web App. Además, Office 365 admite la integración con proveedores de servicios de terceros. Estos servicios y aplicaciones de terceros pueden incluir el almacenamiento, la transmisión y el procesamiento de los datos de clientes de la organización en sistemas de terceros que se encuentren fuera de la infraestructura de Office 365 y, por tanto, no se encuentran protegidos por los compromisos de protección de datos y cumplimiento de Office 365. Le recomendamos que revise las declaraciones de privacidad y de cumplimiento proporcionadas por los terceros para evaluar el uso apropiado de estos servicios en su organización.
  
[Cómo usar esta sección de Descripción del servicio](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="restricted-data-access-by-administrators"></a>Acceso a datos restringido por los administradores

Acceso a Office 365 US Government el contenido del cliente por parte de los administradores de Microsoft está restringido al personal de la pantalla. Para obtener más información sobre los niveles de filtrado, consulte la página de Descripción del servicio para cada entorno respectivo (GCC o GCC High y DoD). 

  
## <a name="fasttrack-center-onboarding-assistance"></a>Asistencia para la incorporación del centro de FastTrack

Con el beneficio del centro FastTrack para Office 365<sup>1</sup>, trabaja de forma remota con los especialistas de FastTrack para obtener el entorno de Office 365 listo para su uso y planear la implementación y el uso en la organización. El proceso de FastTrack presta servicios relacionados con la incorporación y aceptación por parte de los usuarios. 
  
La incorporación consiste en lo siguiente:
  
- Incorporación principal: son tareas necesarias para la configuración de los inquilinos y la integración con Azure Active Directory (Azure AD), si es necesario. La incorporación principal también proporciona la línea base para incorporar otros servicios pertinentes.
    
- Tareas de incorporación y migración de servicios: las tareas de incorporación de servicios habilitan escenarios en el espacio empresarial. La migración de datos (incluidos el correo electrónico y los archivos) se describe en la [migración de datos](https://aka.ms/whatcanmigrate). <sup>2</sup>
    
Los servicios de aceptación por parte de los usuarios constan de tareas que le ayudarán a garantizar que los usuarios conozcan los servicios elegibles y puedan usarlos para impulsar el valor empresarial. Esta asistencia se presta en paralelo a las actividades de incorporación.
  
[Aquí](https://aka.ms/whatistheprocess)puede encontrar información específica sobre el proceso del centro FastTrack. Para un desglose de los roles y las responsabilidades del acuerdo, revise las [responsabilidades de FastTrack](https://aka.ms/whatdoesftcdo) , así como [sus responsabilidades](https://aka.ms/whatdowedo).
  
<sup>1</sup> debe comprar al menos 50 licencias en la lista de [planes elegibles](https://aka.ms/whocanbenefit) para recibir los servicios de FastTrack. 
  
<sup>2</sup> los servicios de migración de datos están disponibles para los inquilinos de Office 365 con 500 o más licencias. 
  
## <a name="data-migrations-performed-by-fasttrack"></a>Migraciones de datos realizadas por FastTrack

Los clientes que elijan la ventaja de migración de [FastTrack](https://fasttrack.microsoft.com/) deberán conceder acceso al equipo que administra sus migraciones de datos. Este personal es ciudadano estadounidense y se somete a las siguientes comprobaciones de antecedentes antes de realizar las migraciones para los clientes de Office 365 US Government Services. 
  
||||
|:-----|:-----|:-----|
|**Investigación de antecedentes** <br/> |**GCC** <br/> |**GCC High y DoD** <br/> |
|Comprobación de la ciudadanía estadounidense  <br/> |Sí  <br/> |Sí  <br/> |
|Comprobación del historial de empleo  <br/> |Sí  <br/> |Sí  <br/> |
|Comprobación de la formación académica  <br/> |Sí  <br/> |Sí  <br/> |
|Búsqueda en el número de la seguridad social (SSN)  <br/> |Sí  <br/> |Sí  <br/> |
|Comprobación de los antecedentes penales (7 años)  <br/> |Sí  <br/> |Sí  <br/> |
   
[Cómo usar esta sección de Descripción del servicio](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-365-us-government-and-azure-government-expressroute"></a>Office 365 Administración Pública y Azure Government ExpressRoute

Office 365 US Government customers pueden usar los servicios de Azure Government ExpressRoute para conectarse de forma privada a los servicios de Office 365 compatibles en lugar de conectarse a través de Internet público.
  
Para obtener información sobre los proveedores compatibles, los modelos de precios y mucho más, revise la [información de Azure ExpressRoute](https://go.microsoft.com/fwlink/?LinkID=798220&amp;clcid=0x409).
  
Para obtener información sobre la compatibilidad de Office 365 con Azure ExpressRoute, consulte [Azure ExpressRoute for Office 365](https://go.microsoft.com/fwlink/?LinkID=798216&amp;clcid=0x409) (Azure ExpressRoute para Office 365).
  
[Cómo usar esta sección de Descripción del servicio](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="system-requirements"></a>Requisitos del sistema

Para obtener información sobre los requisitos del sistema para los planes de Office 365 Administración Pública, vea [Requisitos del sistema para Office](https://go.microsoft.com/fwlink/?LinkID=626095&amp;clcid=0x409) en el sitio de productos de [office.com](https://go.microsoft.com/fwlink/?LinkID=509817&amp;clcid=0x409). 
  
[Cómo usar esta sección de Descripción del servicio](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="security-amp-compliance-center"></a>Security &amp; Compliance Center

Para obtener información acerca del &amp; centro de seguridad y cumplimiento, así como vínculos a información adicional y disponibilidad, consulte [Office 365 Security &amp; Compliance Center](../../office-365-platform-service-description/office-365-securitycompliance-center.md).
  
## <a name="service-availability-for-each-plan"></a>Disponibilidad del servicio para cada plan

Cada plan de Office 365 incluye varios servicios individuales, como Exchange Online y SharePoint Online. En la siguiente tabla se muestran los servicios disponibles en cada plan de Office 365 Administración Pública.
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**Servicios de Office 365** <br/> |**Office 365 Administración Pública G1** <br/> |**Office 365 Administración Pública G3** <br/> |**Office 365 Administración Pública G5** <br/> |**Office 365 administración pública F1** <br/> |
|Office para la Web  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Office 365 ProPlus  <br/> |No <br/> |Sí <br/> |Sí <br/> |No  <br/> |
|Exchange Online  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Protección de Exchange Online  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|SharePoint Online  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|OneDrive para la Empresa  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Skype for Business (Instant Messaging &amp; Presence)  <br/> |Sí<sup>1</sup> <br/> |Sí  <br/> |Sí  <br/> |Sí<sup>1</sup> <br/> |
| Sistema de telefonía por voz, audioconferencia  <br/> |No<sup>2, 3</sup> <br/> |No<sup>2, 3</sup> <br/> |Sí <sup>3, 5</sup> <br/> |No  <br/> |
|Power BI Pro  <br/> |No<sup>2</sup> <br/> |No<sup>2</sup> <br/> |Sí  <br/> |No<sup>2</sup> <br/> |
|Project Online  <br/> |No<sup>2</sup> <br/> |No<sup>2</sup> <br/> |No<sup>2</sup> <br/> |No<sup>2</sup> <br/> |
|Visio para la web  <br/> |No<sup>6</sup> <br/> |No<sup>6</sup> <br/> |No<sup>6</sup> <br/> |No<sup>6</sup> <br/> |
|Yammer Enterprise  <br/> |No<sup>4</sup> <br/> |No<sup>4</sup> <br/> |No<sup>4</sup> <br/> |No<sup>4</sup> <br/> |
   
> <sup>1</sup> Skype empresarial Basic está disponible para todos los clientes. El cliente de escritorio de Skype Empresarial es una aplicación instalada localmente que proporciona funciones de presencia, de mensajería instantánea y de conferencias para los planes de Office 365 que incluyen Skype Empresarial Online. Office 365 ProPlus, G3 y G5 incluyen la aplicación de Skype completa, que incluye características adicionales, como la compatibilidad avanzada con telefonía, el archivado y las características de cumplimiento. A Skype for Business Online license must be assigned for each user.
<br/><sup>2</sup> no se incluye, pero puede adquirirse como un complemento independiente. Project online incluye el cliente de escritorio de Project online como parte de la suscripción.
<br/> <sup>3</sup> todavía no está disponible en los planes de GCC High o DOD, pero lo estará próximamente. 
<br/><sup>4</sup> Yammer Enterprise no es un componente de Office 365 US Government, pero puede adquirirse sin costo como una oferta independiente para cada usuario con licencia para Office 365 en gcc. Esta oferta actualmente está limitada a los clientes que adquieren Office 365 GCC en Enterprise Agreements and Enterprise subscription agreements. Yammer no está disponible en GCC High o DoD.
<br/><sup>5</sup> plan de llamadas es un complemento. 
<br/><sup>6</sup> no se incluye, pero puede adquirirse como un complemento independiente. Visio para la web incluye la aplicación de escritorio de Visio como parte de la suscripción.

## <a name="platform-features"></a>Características de plataforma 

En la siguiente tabla se enumeran las características de la plataforma y los servicios que están disponibles en los planes de Office 365 Administración Pública.
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Office 365 Administración Pública G1** <br/> |**Office 365 Administración Pública G3** <br/> |**Office 365 Administración Pública G5** <br/> |**Office 365 administración pública F1** <br/> |
|**Administración de Office 365** <br/> |||||
|Usar el centro de administración de Microsoft 365 para administrar Office 365  <br/> |Sí<sup>16</sup> <br/> |Sí<sup>16</sup> <br/> |Sí  <br/> |Sí<sup>16</sup> <br/> |
|Administrar la configuración principal del servicio desde Office 365  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Uso de Windows PowerShell para administrar Office 365  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Proteger el contenido con Azure Information Protection  <br/> |No<sup>1</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup>  <br/> |No<sup>1</sup> <br/> |
|**[Características del conjunto de aplicaciones de Office 365](../../office-365-platform-service-description/office-365-suite-features.md)** <br/> |**Office 365 Administración Pública G1** <br/> |**Office 365 Administración Pública G3** <br/> |**Office 365 Administración Pública G5** <br/> |**Office 365 administración pública F1** <br/> |
|Reservas de Microsoft  <br/> |No  <br/> |No  <br/> |No  <br/> |No  <br/> |
|Correo electrónico de Microsoft briefing  <br/> |No  <br/> |No  <br/> |No  <br/> |No  <br/> |
|Automatización de Microsoft Power  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Microsoft Forms  <br/> |Sí <br/> |Sí <br/> |Sí<br/> |Sí</sup> <br/> |
|API de Microsoft Graph  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Microsoft MyAnalytics  <br/> |No <br/> |No <br/> |Sí<sup>17</sup> <br/> |No <br/> |
|Microsoft Planner  <br/> |Sí <br/> |Sí <br/> |Sí <br/> |Sí <br/> |
|Microsoft PowerApps  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Microsoft StaffHub  <br/> |No <br/> |No <br/> |No <br/> |No<br/> |
|Microsoft Stream  <br/> |Sí<sup>9, 15</sup> <br/> |Sí<sup>9, 15</sup> <br/> |Sí<sup>9, 15</sup> <br/> |No  <br/> |
|Microsoft Sway  <br/> |No <br/> |No <br/> |No <br/> |No <br/> |
|Microsoft Teams  <br/> |Sí <br/> |Sí <br/> |Sí <br/> |Sí <br/> |
|Office Delve  <br/> |Sí<sup>17</sup> <br/> |Sí<sup>17</sup> <br/> |Sí  <br/> |Sí<sup>17</sup> <br/> |
|Grupos de Office 365  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|**[Administración de cuentas de usuario](../../office-365-platform-service-description/user-account-management.md)** <br/> |**Office 365 Administración Pública G1** <br/> |**Office 365 Administración Pública G3** <br/> |**Office 365 Administración Pública G5** <br/> |**Office 365 administración pública F1** <br/> |
|Identidad de la nube  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Identidad federada (inicio de sesión único)  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Autenticación multifactor  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Autenticación de factor de teléfono  <br/> |Sí<sup>9</sup> <br/> |Sí<sup>9</sup> <br/> |Sí  <br/> |Sí<sup>9</sup> <br/> |
|Configuración de escritorio de Office 365  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Administrar usuarios con Office 365  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Carga masiva con archivos. csv  <br/> |Sí<sup>9</sup> <br/> |Sí<sup>9</sup> <br/> |Sí  <br/> |Sí<sup>9</sup> <br/> |
|Herramienta de sincronización de directorios  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Migración sencilla (transferencia) de Exchange  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Eliminar cuentas mediante Office 365  <br/> |Sí <sup>3</sup> <br/> |Sí<sup>3</sup> <br/> |Sí<sup>3</sup> <br/> |Sí<sup>3</sup> <br/> |
|El administrador puede restablecer la contraseña de usuario desde Office 365 o mediante Windows PowerShell  <br/> |Sí <sup>4</sup> <br/> |Sí <sup>4</sup> <br/> |Sí <sup>4</sup> <br/> |Sí <sup>4</sup> <br/> |
|Los usuarios pueden cambiar su propia contraseña  <br/> |Sí <sup>5</sup> <br/> |Sí<sup>5</sup> <br/> |Sí<sup>5</sup> <br/> |Sí<sup>5</sup> <br/> |
|Administrar licencias  <br/> |Sí<sup>7, 8</sup> <br/> |Sí<sup>7, 8</sup> <br/> |Sí<sup>7, 8</sup> <br/> |Sí<sup>7,8</sup> <br/> |
|Administrar grupos de seguridad desde Office 365  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Varios roles de administrador disponibles  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Permitir que un socio administre Office 365 por usted  <br/> |Sí<sup>11</sup> <br/> |Sí<sup>11</sup> <br/> |Sí<sup>11</sup> <br/> |Sí<sup>11</sup> <br/> |
|Servicios de Azure Active Directory  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|**[Dominios](../../office-365-platform-service-description/domains.md)** <br/> |**Office 365 Administración Pública G1** <br/> |**Office 365 Administración Pública G3** <br/> |**Office 365 Administración Pública G5** <br/> |**Office 365 administración pública F1** <br/> |
|Agregar dominios de segundo nivel personalizados, como fourthcoffee.com  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Agregar dominios de tercer nivel personalizados, como marketing.fourthcoffee.com  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Agregar hasta 900 dominios personalizados  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Verificación de propiedad de dominio necesaria para dominios personalizados  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|**[Continuidad y estado del servicio](../../office-365-platform-service-description/service-health-and-continuity.md)** <br/> |**Office 365 Administración Pública G1** <br/> |**Office 365 Administración Pública G3** <br/> |**Office 365 Administración Pública G5** <br/> |**Office 365 administración pública F1** <br/> |
|Información de estado disponible en la página **Mantenimiento del servicio** o **Estado del servicio**  <br/> |Sí<sup>9, 15</sup> <br/> |Sí<sup>9, 15</sup> <br/> |Sí<sup>9, 15</sup> <br/> |Sí<sup>9, 15</sup> <br/> |
|Estado de alertas individuales disponibles en el panel del centro de administración de Microsoft 365  <br/> |Sí<sup>9, 15</sup> <br/> |Sí<sup>9, 15</sup> <br/> |Sí<sup>9, 15</sup> <br/> |Sí<sup>9, 15</sup> <br/> |
|Fuente RSS de **Mantenimiento del servicio**  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|**[Informes](../../office-365-platform-service-description/reports.md)** <br/> |**Office 365 Administración Pública G1** <br/> |**Office 365 Administración Pública G3** <br/> |**Office 365 Administración Pública G5** <br/> |**Office 365 administración pública F1** <br/> |
|Buzones activos e inactivos  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Buzones eliminados y nuevos  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Grupos nuevos y eliminados  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Uso del buzón de correo  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Tipos de conexiones de buzones  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Correo enviado y recibido  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Destinatarios y remitentes principales  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Detecciones de correo no deseado  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Detecciones de malware  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Malware principal para correo  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Coincidencias con reglas para correo  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Coincidencias de reglas principales para correo  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Coincidencias de directivas de DLP principales para correo  <br/> |No  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Coincidencias de directivas de DLP por gravedad para correo  <br/> |No  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Coincidencias de directivas de DLP, invalidaciones y falsos positivos para correo  <br/> |No  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Principales coincidencias de reglas de DLP para correo  <br/> |No  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Mensajería instantánea y sesiones de audio  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Uso compartido de aplicaciones, web y conferencias de acceso telefónico local  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Vídeo, uso compartido de aplicaciones y sesiones de transferencia de archivos  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Mensajería instantánea y conferencias de audio y vídeo  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Informes de protección de correo descargables  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Explorador utilizado  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Sistema operativo utilizado  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Creación de sus propios informes con los servicios web de creación de informes de Office 365  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|**[Actualizaciones de servicio](../../office-365-platform-service-description/service-updates.md)** <br/> |**Office 365 Administración Pública G1** <br/> |**Office 365 Administración Pública G3** <br/> |**Office 365 Administración Pública G5** <br/> |**Office 365 administración pública F1** <br/> |
|Actualizaciones habituales para todos los clientes  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Las notificaciones se envían a Centro de mensajes cuando la acción es necesaria  <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |Sí<sup>15</sup> <br/> |
|Roadmap.office.com para algún servicio actualizaciones  <br/> |No<sup>10, 13</sup> <br/> |No<sup>10, 13</sup> <br/> |No<sup>10, 13</sup> <br/> |No<sup>10, 13</sup> <br/> |
|Opción para activar la versión dirigida  <br/> |Sí<sup>10</sup> <br/> |Sí<sup>10</sup> <br/> |Sí<sup>10</sup> <br/> |Sí<sup>10</sup> <br/> |
|**[Ayuda y formación](../../office-365-platform-service-description/help-and-training.md)** <br/> |**Office 365 Administración Pública G1** <br/> |**Office 365 Administración Pública G3** <br/> |**Office 365 Administración Pública G5** <br/> |**Office 365 administración pública F1** <br/> |
|Ayuda en línea  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Comunidad  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Otros recursos de autoayuda  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Formación a ritmo propio  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|**[Conexión de red](../../office-365-platform-service-description/networking.md)** <br/> |**Office 365 Administración Pública G1** <br/> |**Office 365 Administración Pública G3** <br/> |**Office 365 Administración Pública G5** <br/> |**Office 365 administración pública F1** <br/> |
|Protocolos IPv4 e IPv6  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|**Confianza** <br/> |**Office 365 Administración Pública G1** <br/> |**Office 365 Administración Pública G3** <br/> |**Office 365 Administración Pública G5** <br/> |**Office 365 administración pública F1** <br/> |
|**[Privacidad, seguridad y transparencia](../../office-365-platform-service-description/privacy-security-and-transparency.md)** <br/> |||||
|Gobierno de datos avanzado  <br/> |No<sup>12</sup> <br/> |No<sup>12</sup> <br/> |Sí <br/> |No<sup>12</sup> <br/> |
|Cloud App Security  <br/> |No<sup>12, 15, 19</sup> <br/> |No<sup>12, 15, 19</sup> <br/> |Sí<sup>15, 19</sup> <br/> |No<sup>12, 15, 19</sup> <br/> |
|Protección contra amenazas avanzada  <br/> |No<sup>12, 18</sup> <br/> |No<sup>12, 18</sup> <br/> |Sí<sup>18</sup>  <br/> |No<sup>12, 18</sup> <br/> |
|Caja de seguridad del cliente  <br/> |No<sup>12</sup> <br/> |No<sup>12</sup> <br/> |Sí <br/> |No<sup>12</sup> <br/> |
|eDiscovery avanzado de Office 365  <br/> |No<sup>12</sup> <br/> |No<sup>12</sup> <br/> |Sí  <br/> |No<sup>12</sup> <br/> |
|Puntuación segura<sup>14</sup> <br/> |Sí<sup>9, 15</sup> <br/> |Sí<sup>9</sup> <br/> |Sí<sup>9, 15</sup> <br/> |Sí<sup>9, 15</sup> <br/> |
|Cifrado de mensajes de Office  <br/> |No  <br/> |Sí <br/> |Sí <br/> |No  <br/> |
|Inteligencia de amenazas  <br/> |No<sup>12</sup> <br/> |No<sup>12</sup> <br/> |Sí <br/> |No<sup>12</sup> <br/> |
|**[Cumplimiento](../../office-365-platform-service-description/compliance-servicedesc.md)** <br/> |||||
|Evaluaciones SAS 70 / SSAE16  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Certificación ISO 27001  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Cláusulas del modelo de UE  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Acuerdo "Puerto seguro" de EE. UU.  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Acuerdo de asociados de negocios HIPAA  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Autoridad FISMA para operar  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Acuerdo de procesamiento de datos de Microsoft  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|PCI DSS Nivel Uno  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Datos PAN regidos por PCI  <br/> |No  <br/> |No  <br/> |No  <br/> |No  <br/> |
|**[Continuidad del servicio](../../office-365-platform-service-description/service-health-and-continuity.md)** <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|**[BlackBerry](../../office-365-platform-service-description/blackberry.md)** <br/> |**Office 365 Administración Pública G1** <br/> |**Office 365 Administración Pública G3** <br/> |**Office 365 Administración Pública G5** <br/> |**Office 365 administración pública F1** <br/> |
|Uso del Servicio Internet BlackBerry (BIS)  <br/> |No<sup>2</sup> <br/> |No<sup>2</sup> <br/> |No<sup>2</sup> <br/> |No<sup>2</sup> <br/> |
|**[Asociados](../../office-365-platform-service-description/partners.md)** <br/> |||||
|Creación de invitaciones y pedidos de compra de prueba para un cliente que utiliza el plan especificado  <br/> |N°<sup>11</sup> <br/> |N°<sup>11</sup> <br/> |N°<sup>11</sup> <br/> |N°<sup>11</sup> <br/> |
|Proporcionar administración delegada  <br/> |N°<sup>11</sup> <br/> |N°<sup>11</sup> <br/> |N°<sup>11</sup> <br/> |N°<sup>11</sup> <br/> |
|**[Contrato de nivel de servicio](../../office-365-platform-service-description/service-level-agreement.md)** <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|**[Derechos de uso de producto](../../office-365-platform-service-description/product-use-rights.md)** <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
   
> <sup>1</sup> Azure Information Protection no se incluye, pero puede adquirirse como un complemento independiente y habilitará las características de Information Rights Management (IRM) compatibles. Algunas características de Azure Information Protection requieren una suscripción a Office 365 ProPlus, que no se incluye en Office 365 Government G1 ni Office 365 Government (F1). > 
<br/><sup>2</sup> los clientes de BBCS y bis existentes pueden seguir usando el servicio. No se aceptan nuevos clientes. 
<br/><sup>3</sup> si se usa la sincronización de directorios, debe eliminar las cuentas o cambiar las contraseñas con Active Directory, en lugar del portal de Office 365 o mediante el módulo Azure Active Directory para Windows PowerShell. 
<br/><sup>4</sup> si se usa la sincronización de contraseñas, los usuarios deben cambiar sus contraseñas en Active Directory local. 
<br/><sup>5</sup> para aprender a establecer directivas de administración de contraseñas de autoservicio para los usuarios, consulte [Administrar contraseñas en Azure ad](https://azure.microsoft.com/documentation/articles/active-directory-manage-passwords/). 
<br/><sup>6</sup> solo puede tener un sitio web público con Office 365, a menos que haya actualizado desde una versión anterior de Office 365. En ese caso, tiene dos sitios web públicos, pero solo se puede hospedar uno de ellos con un nombre de dominio personalizado. Para obtener más información sobre cómo trabajar con los dos sitios web de suscripciones empresariales, vea [trabajar con los dos sitios web públicos de Office 365](https://go.microsoft.com/fwlink/p/?LinkID=271589). Si tiene una suscripción diferente, obtenga más información sobre los sitios web públicos en [información sobre hospedaje de sitios web de asociados y sitios web públicos en Office 365](https://go.microsoft.com/fwlink/p/?LinkID=325009). 
<br/><sup>7</sup> reducir los puestos que se compraron con un descuento de términos puede estar sujeto a una cuota de finalización anticipada. Esto no se aplica a las suscripciones pagadas con carácter mensual. 
<br/><sup>8</sup> los siguientes planes no admiten cambios de licencia por puesto desde el centro de administración de Microsoft 365: Office 365 el gobierno G1, Office 365 Government G3, Office 365 Government, F1. 
<br/><sup>9</sup> todavía no está disponible en gcc High, pero lo estará próximamente.
<br/><sup>10</sup> para Office 365 Government G1, G3 y F1, se aplica la versión dirigida y el plan de desarrollo de Office 365 para empresas; sin embargo, puede haber algunas diferencias o retrasos para actualizaciones de servicio específicas debido a [los requisitos de cumplimiento](https://www.microsoft.com/trust-center).
<br/><sup>11</sup> todavía no está disponible en las ofertas de Office 365 Government, pero lo estará próximamente. 
<br/><sup>12</sup> no se incluye, pero puede adquirirse como un complemento independiente en gcc. 
<br/><sup>13</sup> no es compatible con las ofertas de Office 365 Government. 
<br/><sup>14</sup> disponible en [https://securescore.office.com](https://securescore.office.com). Requiere permisos de administrador. Para obtener más información, vea [Introducción a la puntuación segura de Office 365](https://go.microsoft.com/fwlink/?linkid=836894). 
<br/><sup>15</sup> todavía no está disponible en el entorno de DoD, pero lo estará próximamente. 
<br/><sup>16</sup> el centro de administración no incluye análisis de uso en entornos altos DoD o gcc.
<br/><sup>17</sup> no es compatible con los entornos GCC altos o DoD.
<br/><sup>18</sup> el antiphishing para la suplantación de usuarios y dominios y la inteligencia de suplantación todavía no están disponibles en gcc High y DoD.
<br/><sup>19</sup> todavía no está disponible en el entorno GCC, pero lo estará próximamente.
  
[Cómo usar esta sección de Descripción del servicio](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-application-availability-and-enterprise-value"></a>Disponibilidad de las aplicaciones de Office y valor empresarial

En la siguiente tabla se muestran las características de aplicaciones de Office que están disponibles en los planes de Office 365 Administración Pública.
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**Característica** <br/> |**Office 365 Administración Pública G1** <br/> |**Office 365 Administración Pública G3** <br/> |**Office 365 Administración Pública G5** <br/> |**Office 365 administración pública F1** <br/> |
|**Aplicaciones de Office** <br/> |||||
|[Microsoft Word](../../office-applications-service-description/office-applications.md#microsoft-word)<sup>7</sup> <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|[Microsoft Excel](../../office-applications-service-description/office-applications.md#microsoft-excel)<sup>7</sup> <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|[Microsoft PowerPoint](../../office-applications-service-description/office-applications.md#microsoft-powerpoint)<sup>7</sup> <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|[Microsoft OneNote](../../office-applications-service-description/office-applications.md#microsoft-onenote)<sup>7</sup> <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|[Microsoft Outlook](../../office-applications-service-description/office-applications.md#microsoft-outlook)<sup>7</sup> <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|Microsoft Forms<sup>7</sup>| Sí <br/> | Sí <br/>| Sí <br/> | No <br/> |
|Pizarra de Microsoft<sup>7</sup>| No <br/> | Sí <br/> | Sí <br/> | No <br/> |
|[Microsoft Publisher](../../office-applications-service-description/office-applications.md#microsoft-publisher) <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|[Microsoft Access](../../office-applications-service-description/office-applications.md#microsoft-access) <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|[Skype Empresarial](../../office-applications-service-description/office-applications.md#skype-for-business) <br/> |Sí<sup>3</sup> <br/> |Sí  <br/> |Sí  <br/> |Sí<sup>3</sup> <br/> |
|[Office para Mac para Office 365](https://support.office.com/article/General-requirements-for-Outlook-2016-for-Mac-A07A593D-B383-4906-A6C1-962D5543ED57) <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|[Office Mobile para iPhone o iPad](../../office-applications-service-description/office-applications.md#office-mobile-for-ipadiphone) <br/> |Sí  <br/> |Sí<sup></sup> <br/> |Sí<sup></sup> <br/> |Sí  <br/> |
|[Office Mobile para Android](../../office-applications-service-description/office-applications.md#office-mobile-for-android) <br/> |Sí  <br/> |Sí<sup></sup> <br/> |Sí<sup></sup> <br/> |Sí  <br/> |
|[Office Mobile para Windows Phone](../../office-applications-service-description/office-applications.md#office-mobile-for-windows-phone) <br/> |Sí  <br/> |Sí<sup>4</sup> <br/> |Sí<sup>4</sup> <br/> |Sí  <br/> |
|Office Mobile for Windows 10 tablets <br/> |Sí  <br/> |Sí<sup></sup> <br/> |Sí<sup></sup> <br/> |Sí  <br/> |
|Outlook para iOS y Android<sup>5, 4</sup>  <br/> |Sí <br/> |Sí <br/> |Sí <br/> |Sí <br/> |
|**Valor empresarial** <br/> |**Office 365 Administración Pública G1** <br/> |**Office 365 Administración Pública G3** <br/> |**Office 365 Administración Pública G5** <br/> |**Office 365 administración pública F1** <br/> |
|Cinco instalaciones por usuario en PC o Mac  <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|Aprovisionamiento de cuentas de usuario automatizado  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Interfaz de usuario multilingüe  <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|Implementación de comandos de cliente  <br/> |No  <br/> |Sí<sup>4</sup> <br/> |Sí<sup>4</sup> <br/> |No  <br/> |
|Soporte para clientes sobre Exchange local  <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|Soporte para clientes sobre SharePoint local  <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|Control de las actualizaciones del software  <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|Comparación de bases de datos  <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|Virtualización de escritorio  <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|Comparación de hojas de cálculo de Excel  <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|Consulta de hojas de cálculo de Excel  <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|Archivado y cumplimiento de Exchange Online y SharePoint Online  <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|Soporte para directivas de grupos  <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|Information Rights Management con Azure Information Protection  <br/> |No<sup>1</sup> <br/> |Sí<sup>6</sup> <br/> |Sí<sup>6</sup> <br/> |No<sup>1</sup> <br/> |
|Information Rights Management mediante Windows Server AD RMS  <br/> |Sí<sup>2</sup> <br/> |Sí<sup>2</sup> <br/> |Sí<sup>2</sup> <br/> |Sí<sup>2</sup> <br/> |
|Complemento de Office, ActiveX y soporte de BHO  <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|Acceso de cliente de OneNote a blocs de notas en SharePoint Server, SharePoint Online, OneDrive para la Empresa y Office 365  <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|Office Lens  <br/> |No  <br/> |No  <br/> |No  <br/> |No  <br/> |
|Telemetría de Office  <br/> |No  <br/> |Sí<sup>4</sup> <br/> |Sí<sup>4</sup> <br/> |No  <br/> |
|Soporte sin conexión para aplicaciones cliente  <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|Instalación de cliente en paralelo optimizada  <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|Power Map para Excel  <br/> |No  <br/> |Sí<sup>4</sup> <br/> |Sí<sup>4</sup> <br/> |No  <br/> |
|Power Pivot para Excel  <br/> |No  <br/> |Sí<sup>4</sup> <br/> |Sí<sup>4</sup> <br/> |No  <br/> |
|Power Query para Excel  <br/> |No  <br/> |Sí<sup>4</sup> <br/> |Sí<sup>4</sup> <br/> |No  <br/> |
|Power View para Excel  <br/> |No  <br/> |Sí<sup>4</sup> <br/> |Sí<sup>4</sup> <br/> |No  <br/> |
|Configuración de movilidad  <br/> |No  <br/> |Sí<sup></sup> <br/> |Sí<sup></sup> <br/> |No  <br/> |
|Activación en equipos compartidos  <br/> |No  <br/> |Sí <br/> |Sí <br/> |No  <br/> |
|Soporte para bloquear el almacenamiento de archivos basados en la nube  <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No  <br/> |
|Actualizaciones de versión  <br/> |No  <br/> |Sí<sup>4</sup> <br/> |Sí<sup>4</sup> <br/> |No  <br/> |
|Volume activation (KMS/MAK)  <br/> |No  <br/> |No  <br/> |No  <br/> |No  <br/> |
   
> <sup>1</sup> Azure Information Protection no se incluye, pero puede adquirirse como un complemento independiente y habilitará las características de Information Rights Management (IRM) compatibles. Algunas características de Azure Information Protection requieren una suscripción a Office 365 ProPlus, que no se incluye en Office 365 Government G1 ni Office 365 Government (F1). 
<br/><sup>2</sup> Windows Server AD RMS es un servidor local que debe adquirirse y administrarse por separado para habilitar las características de IRM admitidas. 
<br/><sup>3</sup> Skype empresarial Basic está disponible para todos los clientes. El cliente de escritorio de Skype Empresarial es una aplicación instalada localmente que proporciona funciones de presencia, de mensajería instantánea y de conferencias para los planes de Office 365 que incluyen Skype Empresarial Online. Office 365 ProPlus y Office 365 Enterprise E3 incluyen la aplicación de Skype completa, que incluye características adicionales, como la compatibilidad avanzada con telefonía, el archivado y las características de cumplimiento. A Skype for Business Online license must be assigned for each user. For more information on Lync Basic features, see [Skype for Business Online client comparison tables](https://docs.microsoft.com/lyncserver/lync-server-2013-desktop-client-comparison-tables). 
<br/><sup>4</sup> todavía no está disponible en los entornos altos o DoD de GCC, pero lo estará próximamente.
<br/><sup>5</sup> consulte [uso de Outlook para iOS y Android en la nube de la comunidad de administración pública](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud) para obtener más información.
<br/><sup>6</sup> todavía no está disponible en el entorno de Office 365 DOD, pero lo estará próximamente.
<br/><sup>7</sup> las aplicaciones están completamente disponibles en las nubes gubernamentales, con la excepción de las características específicas que no están disponibles en este momento. Consulte [disponibilidad](#office-application-and-feature-availability-in-government-plans) de las características de las aplicaciones de Office para obtener más información.
<br/><br/>[Cómo usar esta sección de Descripción del servicio](office-365-us-government.md#how-to-use-this-service-description-section)

## <a name="office-application-and-feature-availability-in-government-plans"></a>Disponibilidad de características y aplicaciones de Office en los planes gubernamentales

Las siguientes aplicaciones de Office están disponibles en las nubes gubernamentales; sin embargo, es posible que algunas funciones basadas en la nube no estén disponibles actualmente, como se indica en la tabla.

|||||
|-----|-----|-----|-----|
|[**Microsoft Excel**](../../office-applications-service-description/office-applications.md#microsoft-excel) está completamente disponible en las nubes gubernamentales excepto en las siguientes características, que no están disponibles en este momento: | **GCC** <br/> | **GCC High** <br/> | **REQUISITO** <br/> |
|animaciones 3D incrustadas y modelos 3D | No <br/> | No <br/> | No <br/> |
|Tipos de datos | No <br/> | No <br/> | No <br/> |
|Relleno rápido | No <br/> | No <br/> | No <br/> |
|Ideas (servicios de conocimientos) | No <br/> | No <br/> | No <br/> |
|Integración mejorada con PowerBI (objetos visuales personalizados, crear gráficos PBI directamente desde Excel) | No <br/> | No <br/> | No <br/> |
|Tinta digital inteligente | No <br/> | No <br/> | No <br/> |
|Grupos de Office 365 | No <br/> | No <br/> | No <br/> |
|Datos de gráficos dinámicos conectados a tablas dinámicas | No <br/> | No <br/> | No <br/> |
|PowerPivot | No <br/> | No <br/> | No <br/> |
|Publicar en PowerBI | No <br/> | No <br/> | No <br/> |
|Colaboración en tiempo real (presencia, coautoría normal, chat dentro del documento) | No <br/> | No <br/> | No <br/> |
|Shared with Me | No <br/> | No <br/> | No <br/> |
|Búsqueda inteligente | No <br/> | No <br/> | No <br/> |
|Gráficos: Treemap sol, cascada, histograma, mapas, escala de tiempo, embudo | No <br/> | No <br/> | No <br/> |
|Historial de versiones | No <br/> | No <br/> | No <br/> |
|[**Microsoft Forms**](https://support.office.com/article/5cbd407a-eef7-431e-8e3a-eb666eab4b4c) está completamente disponible en las nubes gubernamentales excepto en las siguientes características, que no están disponibles en este momento: | **GCC** <br/> | **GCC High** <br/> | **DoD**<sup>3</sup> <br/> |
|Notificación de correo electrónico | No<sup>1</sup> <br/> | No<sup>1</sup> <br/> | No <br/> | 
|Insertar una imagen | No<sup>1</sup> <br/> | No<sup>1</sup> <br/> | No <br/> |
|Insertar un vídeo | No<sup>1</sup> <br/> | No<sup>1</sup> <br/> | No <br/> |
|Matemáticas | No<sup>1</sup> <br/> | No<sup>1</sup> <br/> | No <br/> |
|Integración con Office | No<sup>1</sup> <br/> | No<sup>1</sup> <br/> | No <br/> |
|Formularios de grupo más recientes | Sí <br/> | Sí <br/> | No <br/> |
|Uso compartido externo <sup>4</sup> | Sí <br/> | No <br/> | No <br/> |
|Forms Pro | No | No | No |
|[**Microsoft OneNote**](../../office-applications-service-description/office-applications.md#microsoft-onenote) está completamente disponible en las nubes gubernamentales, excepto en las siguientes características, que no están disponibles en este momento: | **GCC** <br/> | **GCC High** <br/> | **REQUISITO** <br/> |
|Investigador | No <br/> | No <br/> | No <br/> |
|Tinta digital inteligente | No <br/> | No <br/> | No <br/> |
|[**Microsoft Outlook**](../../office-applications-service-description/office-applications.md#microsoft-outlook) está completamente disponible en las nubes gubernamentales, excepto en las siguientes características, que no están disponibles en este momento: | **GCC** <br/> | **GCC High** <br/> | **REQUISITO** <br/> |
|Sonidos de Office (algunos) | No <br/> | No <br/> | No <br/> |
|Intercambio dinámico de datos (DDE) deshabilitado de forma predeterminada | No <br/> | No <br/> | No <br/> |
|Dictado | No<sup>1</sup> <br/> | No<sup>1</sup> <br/> | No<sup>1</sup> <br/> |
|[**Microsoft PowerPoint**](../../office-applications-service-description/office-applications.md#microsoft-powerpoint) está completamente disponible en las nubes gubernamentales, excepto en las siguientes características, que no están disponibles en este momento: | **GCC** <br/> | **GCC High** <br/> | **REQUISITO** <br/> |
|Búsqueda inteligente | No <br/> | No <br/> | No <br/> |
|Sonidos de Office (algunos) | No <br/> | No <br/> | No <br/> |
|modelos 3D y animaciones incrustadas en 3D | No <br/> | No <br/> | No <br/> |
|Gráficos: mapas | No <br/> | No <br/> | No <br/> |
|Tinta digital inteligente | No <br/> | No <br/> | No <br/> |
|Títulos en directo y subtítulos en PowerPoint | No <br/> | No <br/> | No <br/> |
|Autocar del moderador | No <br/> | No <br/> | No <br/> |
|Shared with Me | No <br/> | No <br/> | No <br/> |
|Integración de Skype empresarial con uso compartido | No <br/> | No <br/> | No <br/> |
|Historial de versiones | No <br/> | No <br/> | No <br/> |
|Grupos de Office 365 | No <br/> | No <br/> | No <br/> |
|Colaboración en tiempo real (presencia, coautoría normal, chat dentro del documento) | No <br/> | No <br/> | No <br/> |
|Dictado | No<sup>1</sup> <br/> | No<sup>1</sup> <br/> | No<sup>1</sup> <br/> |
|Volver a usar diapositivas | No <br/> | No <br/> | No <br/> |
|La **pizarra de Microsoft** en nubes gubernamentales solo está disponible actualmente en los clientes concentradores y no en el escritorio. | **GCC**<sup>2</sup> <br/> | **GCC**<sup>2</sup> superior <br/> | **DoD**<sup>2</sup> <br/> |
|Insertar notas rápidas, texto e imágenes | Sí<sup>2</sup> <br/>| Sí<sup>2</sup> <br/>| Sí<sup>2</sup> <br/>|
|Entrada de lápiz a forma y de entrada de lápiz a tabla | Sí<sup>2</sup> <br/>| Sí<sup>2</sup> <br/>| Sí<sup>2</sup> <br/>|
|Beautification de entrada de lápiz | Sí<sup>2</sup> <br/>| Sí<sup>2</sup> <br/>| Sí<sup>2</sup> <br/>|
|Convertir la imagen en tinta | Sí<sup>2</sup> <br/>| Sí<sup>2</sup> <br/>| Sí<sup>2</sup> <br/>|
|Comprobador de accesibilidad | Sí<sup>2</sup> <br/>| Sí<sup>2</sup> <br/>| Sí<sup>2</sup> <br/>|
|Plantillas dinámicas (KANBAN, DAFO, etc.) | No <br/> | No <br/> | No <br/> |
|Colaboración en tiempo real | No <br/> | No <br/> | No <br/> |
|Presencia en tiempo real | No <br/> | No <br/> | No <br/> |
|Reacciones sobre el contenido | No <br/> | No <br/> | No <br/> |
|Galería de pizarras, incluidos los compartidos | No <br/> | No <br/> | No <br/> |
|[**Microsoft Word**](../../office-applications-service-description/office-applications.md#microsoft-word) está completamente disponible en las nubes gubernamentales excepto en las siguientes características, que no están disponibles en este momento: | **GCC** <br/> | **GCC High** <br/> | **REQUISITO** <br/> |
|Búsqueda inteligente | No <br/> | No <br/> | No <br/> |
|Investigador | No <br/> | No <br/> | No <br/> |
|Sonidos de Office  | No <br/> | No <br/> | No <br/> |
|modelos 3D | No <br/> | No <br/> | No <br/> |
|animaciones incrustadas en 3D  | No <br/> | No <br/> | No <br/> |
|Pulsar  | No <br/> | No <br/> | No <br/> |
|Asistente para currículum vítae | No <br/> | No <br/> | No <br/> |
|Gráficos de mapa | No <br/> | No <br/> | No <br/> |
|Tinta digital inteligente | No <br/> | No <br/> | No <br/> |
|Shared with Me | No <br/> | No <br/> | No <br/> |
|Translation | No <br/> | No <br/> | No <br/> |
|Integración de Skype empresarial con uso compartido | No <br/> | No <br/> | No <br/> |
|Historial de versiones | No <br/> | No <br/> | No <br/> |
|Grupos de Office 365 | No <br/> | No <br/> | No <br/> |
|Chat contextual con coautores: charle con coautores en el documento | No <br/> | No <br/> | No <br/> |
|Dictado | No<sup>1</sup> <br/> | No<sup>1</sup> <br/> | No<sup>1</sup> <br/> |

<sup>1</sup> disponibilidad próximamente.<br/>
<sup>2</sup> disponibilidad en Surface Hub local (no iniciada).<br/>
<sup>3</sup> la aplicación actualmente no está disponible en la nube DoD.<br/>
<sup>4</sup> el uso compartido externo está disponible para el entorno gcc. Obtenga más información sobre cómo [activar o desactivar Microsoft Forms](https://support.office.com/article/cc52287a-4550-464d-9a1b-457bf9df2240#PickTab=Configure) para su organización. El uso compartido externo está deshabilitado para los entornos de GCC altos y DOD; los usuarios de la organización pueden hacer lo siguiente: completar un formulario y enviar respuestas, [duplicar y compartir un formulario como una plantilla](https://support.office.com/article/82ea9d8a-260a-47a0-afdb-497f3d746e3f), [trabajar en co-autoría o colaborar en un formulario](https://support.office.com/article/d5bb5cf0-8401-4c15-bb8c-8e108cd7e69b), y [obtener acceso a los resultados del formulario](https://support.office.com/article/02859424-341d-406f-b32a-9a0fbaf357af).<br/>
