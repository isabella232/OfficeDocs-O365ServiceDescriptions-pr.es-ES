---
title: Entornos gubernamentales de SharePoint para EE. UU.
ms.author: office365servicedesc
author: pamelaar
ms.reviewer: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Obtenga información sobre la disponibilidad de características de SharePoint para los clientes de la nube del gobierno de Estados Unidos.
ms.openlocfilehash: 505be0509dbef718e64983377c8dc75a23adfd26
ms.sourcegitcommit: bf25a64ef2b5c1a1c1e5b94babbebf8d2eb7a1a1
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/08/2021
ms.locfileid: "50145987"
---
# <a name="sharepoint-for-us-government-environments"></a>Entornos gubernamentales de SharePoint para EE. UU.

En este artículo se proporciona información general sobre las diferencias de características entre la nube del gobierno de Estados Unidos y la nube comercial, como se muestra en la descripción del servicio [de SharePoint.](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-service-description) SharePoint está disponible para los entornos de Government Community Cloud (GCC), GCC High y DoD. 

Para obtener más información sobre la nube de administración pública, incluida la elegibilidad y las compras, vea [Microsoft 365 Administración Pública: cómo comprar.](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy) Para comparar los planes de Office 365 Administración Gubernamental, vea [los planes de Office 365 Administración Gubernamental.](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)

Para obtener información sobre los puntos de conexión necesarios al administrar la conectividad de red, vea los puntos de conexión [de Office 365 U.S. Government GCC High](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) o los puntos de conexión doD de Office [365 U.S. Government.](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)

Además de disfrutar de las características y capacidades de Office 365, las organizaciones se benefician de las siguientes características que son exclusivas de los entornos en la nube del gobierno de Estados Unidos:

-   El contenido del cliente de su organización se separa lógicamente del contenido del cliente en los servicios comerciales de Office 365 de Microsoft.
-   El contenido del cliente de la organización se almacena dentro de los Estados Unidos.
-   El acceso al contenido del cliente de la organización está restringido a personal específico de Microsoft.
-   Los entornos de nube de administración pública cumplen con las certificaciones y acreditaciones necesarias para los clientes del sector público de Estados Unidos.

Nuestro objetivo es ofrecer todas las funciones y características comerciales de SharePoint a los entornos de nube de administración pública. Algunas características no están disponibles debido a los requisitos de los clientes de la nube de administración pública. Otras características llegan a los entornos gubernamentales, pero aún no están disponibles. Consulte las siguientes secciones para obtener información sobre la disponibilidad de características en los entornos de nube de administración pública.

## <a name="developer-features"></a>Características de desarrollador

No hay diferencias conocidas entre las características de desarrollador para los clientes comerciales y las de los clientes de la nube de administración pública.

- Las conexiones a aplicaciones externas, como orígenes de datos para complementos, están limitadas a orígenes que se encuentran dentro de los límites de seguridad del sistema admitidos por su entorno de administración pública.
- Servicios de conectividad empresarial (BCS) es compatible con escenarios de conectividad en los que los orígenes de datos permanecen accesibles dentro del límite de seguridad del servicio en la nube.

Si usa aplicaciones de terceros en sitios, revise las declaraciones de privacidad y cumplimiento proporcionadas por los terceros al evaluar el uso adecuado de estos servicios para su organización. Las aplicaciones y los servicios de terceros pueden implicar almacenar, transmitir y procesar datos de clientes de su organización en sistemas de terceros que están fuera de la nube gubernamental y, por lo tanto, no están cubiertos por sus compromisos de cumplimiento y protección de datos. 

## <a name="it-admin-features"></a>Características de administración de TI

Estas son las diferencias entre las características de administración de TI para los clientes comerciales y las de los clientes de la nube de administración pública.

- Cambiar una dirección de sitio no está disponible para los clientes de GCC High
- SharePoint Server híbrido no está disponible para todos los clientes de la nube de administración pública
- La Herramienta de migración de SharePoint y el Administrador de migración requieren un cambio en la configuración. Para obtener información, consulta el soporte [técnico de la nube de administración pública de SPMT.](/sharepointmigration/spmt-install-issues#government-cloud-support)
- Mover.io aún no se admite
- Multi-geo no está disponible para todos los clientes de la nube de administración pública

Para obtener información sobre la migración de FastTrack, vea la descripción del servicio [office 365 ADMINISTRACIÓN PÚBLICA.](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#data-migrations-performed-by-fasttrack)

## <a name="security-and-compliance-features"></a>Características de seguridad y cumplimiento

No hay diferencias conocidas entre las características de seguridad y cumplimiento para los clientes comerciales y las de los clientes de la nube de administración pública.

Para obtener información acerca de las características de seguridad y cumplimiento, consulte el [Centro de & cumplimiento.](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-securitycompliance-center)

Para obtener información sobre las características de Azure Active Directory para la administración pública, consulte [la documentación de Azure Government Security + Identity.](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory) 

Para obtener información sobre las características de Azure Information Protection para el gobierno, vea la descripción del servicio de Administración Pública de [Azure Information Protection Premium.](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description) 

## <a name="sites-and-content"></a>Sitios y contenido

Estas son las diferencias entre los sitios y las características de contenido para los clientes comerciales y los de los clientes de la nube de administración pública:

- Los elementos web que dependen de conexiones a servicios de Internet, como Amazon Amazon Amazon, Mapas de Bing, Twitter y Elementos web de YouTube, no funcionarán como se esperaba
- La biblioteca de activos de la organización no está disponible
- Agregar listas y páginas a Teams no está disponible para los clientes de GCC High y DoD
- La funcionalidad de Graph en SharePoint Online para GCC High está deshabilitada actualmente. Es posible que cualquier servicio que se base en Microsoft Graph no esté disponible actualmente
- Las características que dependen de las conexiones a los servicios de Internet, como la pestaña de imágenes de bolsa, no funcionarán como se esperaba

## <a name="search-features"></a>Características de búsqueda

Estas son las diferencias entre las características de búsqueda para los clientes comerciales y las de los clientes de la nube de administración pública:

- La integración de Microsoft Search no está disponible.

## <a name="sharing-and-sync"></a>Uso compartido y sincronización

Para obtener información sobre las diferencias de características entre la nube comercial y los entornos de nube de administración pública, consulte Uso compartido [de archivos.](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/gcc-high-and-dod#file-sharing)

## <a name="plan-for-governance"></a>Planeación del gobierno

El movimiento a la nube ofrece experiencias transformacionivas con controles de administración integrados. Determine los requisitos de gobierno y cómo puede cumplirlos. Go to [Plan for governance to transform teamwork with Microsoft 365](https://resources.techcommunity.microsoft.com/teamwork-governance/) for more information. Encontrará instrucciones sobre Grupos de Office 365, SharePoint, Teams y mucho más.

## <a name="deploy-sharepoint-for-collaboration"></a>Implementar SharePoint para la colaboración

Después de configurar su organización en la nube de Microsoft US Government, siga la ruta de implementación recomendada que se describe en el Centro de recursos de [adopción de SharePoint.](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/) Asegúrese de colaborar con los campeones de adopción y administración de cambios.
También puede trabajar con [FastTrack](https://www.microsoft.com/fasttrack) o su partner elegido para implantar el servicio a los usuarios.
Visite el [Centro de confianza](https://www.microsoft.com/trust-center) de Microsoft para obtener más información sobre cómo Microsoft aborda la seguridad, la privacidad y el cumplimiento, principios básicos para saber cómo podemos ayudar a las organizaciones a servir a sus clientes.
