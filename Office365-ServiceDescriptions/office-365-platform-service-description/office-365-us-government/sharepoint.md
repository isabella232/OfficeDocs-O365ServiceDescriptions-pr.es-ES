---
title: Entornos gubernamentales de SharePoint para ESTADOS UNIDOS
ms.author: office365servicedesc
author: pamelaar
ms.reviewer: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Obtenga información sobre la disponibilidad de características de SharePoint para los clientes en la nube del gobierno de Estados Unidos.
ms.openlocfilehash: 69900e2da0040882992677f7db764033ff01308d
ms.sourcegitcommit: ec02d469f5815efa65bdb4f17bd4a6f89af13d3a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/25/2021
ms.locfileid: "51215793"
---
# <a name="sharepoint-for-us-government-environments"></a>Entornos gubernamentales de SharePoint para ESTADOS UNIDOS

En este artículo se proporciona información general sobre las diferencias de características entre la nube del gobierno de Estados Unidos y la nube comercial, tal como se muestra en la descripción del servicio [de SharePoint](../../sharepoint-online-service-description/sharepoint-online-service-description.md). SharePoint está disponible para los entornos de GCC, GCC High y DoD. 

Para obtener más información acerca de la nube gubernamental, incluida la elegibilidad y la compra, vea [Microsoft 365 Government - how to buy](./microsoft-365-government-how-to-buy.md). Para comparar los planes de Office 365 Government, vea [Office 365 Government plans](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements).

Para obtener información sobre los puntos de conexión necesarios al administrar la conectividad de red, vea los puntos de conexión de Office [365 U.S. Government GCC High](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) o los puntos de conexión de [Office 365 U.S. Government DoD](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business).

Además de disfrutar de las características y capacidades de Office 365, las organizaciones se benefician de las siguientes características que son exclusivas de los entornos en la nube del gobierno de Estados Unidos:

-   El contenido de cliente de su organización se separa lógicamente del contenido de los clientes en los servicios comerciales de Office 365 de Microsoft.
-   El contenido del cliente de la organización se almacena dentro de los Estados Unidos.
-   El acceso al contenido del cliente de la organización está restringido a personal específico de Microsoft.
-   Los entornos de nube gubernamentales cumplen con las certificaciones y acreditaciones necesarias para los clientes del sector público de Estados Unidos.

Nuestro objetivo es ofrecer todas las funciones y características comerciales de SharePoint a los entornos de nube gubernamentales. Algunas características no están disponibles debido a los requisitos de los clientes de la nube gubernamental. Otras características están llegando a los entornos gubernamentales, pero aún no están disponibles. Consulte las secciones siguientes para obtener información sobre la disponibilidad de características en los entornos de nube gubernamentales.

## <a name="developer-features"></a>Características de desarrollador

No hay diferencias conocidas entre las características de desarrollador para clientes comerciales y las de los clientes en la nube gubernamentales.

- Las conexiones a aplicaciones externas, como orígenes de datos para complementos, se limitan a orígenes que se encuentran dentro de los límites de seguridad del sistema admitidos por el entorno gubernamental.
- Servicios de conectividad empresarial (BCS) es compatible con escenarios de conectividad en los que los orígenes de datos permanecen accesibles dentro del límite de seguridad del servicio en la nube.

Si usa aplicaciones de terceros en sitios, revise las declaraciones de privacidad y cumplimiento proporcionadas por los terceros al evaluar el uso adecuado de estos servicios para su organización. Las aplicaciones y servicios de terceros pueden implicar almacenar, transmitir y procesar los datos de clientes de su organización en sistemas de terceros que están fuera de la nube gubernamental y, por lo tanto, no están cubiertos por sus compromisos de cumplimiento y protección de datos. 

## <a name="it-admin-features"></a>Características de administración de TI

Estas son las diferencias entre las características de administración de TI para clientes comerciales y las de los clientes de la nube gubernamental.

- Cambiar una dirección de sitio no está disponible para los clientes de GCC High
- SharePoint Server híbrido no está disponible para todos los clientes de la nube gubernamental
- La Herramienta de migración de SharePoint y el Administrador de migración requieren un cambio de configuración. Para obtener información, consulta [SPMT government cloud support](/sharepointmigration/spmt-install-issues#government-cloud-support).
- Mover.io aún no se admite
- Multi-geo no está disponible para todos los clientes de la nube gubernamental

Para obtener información sobre la migración de FastTrack, vea la descripción del servicio [de Office 365 US Government](./office-365-us-government.md#data-migrations-performed-by-fasttrack).

## <a name="security-and-compliance-features"></a>Características de seguridad y cumplimiento

No hay diferencias conocidas entre las características de seguridad y cumplimiento de los clientes comerciales y las de los clientes de la nube gubernamental.

Para obtener información sobre las características de seguridad y cumplimiento, vea [el Centro de seguridad & cumplimiento](../office-365-securitycompliance-center.md).

Para obtener información sobre las características de Azure Active Directory para el gobierno, consulte [Azure Government Security + Identity documentation](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory). 

Para obtener información acerca de las características de Azure Information Protection para el gobierno, consulte la Descripción del servicio de [Azure Information Protection Premium Government](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description). 

## <a name="sites-and-content"></a>Sitios y contenido

Estas son las diferencias entre los sitios y las características de contenido de los clientes comerciales y los de los clientes de la nube gubernamental:

- Los elementos web que dependen de conexiones a servicios de Internet, como los elementos web de Amazon Kindle, Mapas de Bing, Twitter y YouTube, no funcionarán como se esperaba.
- La biblioteca de activos de la organización no está disponible
- Agregar listas y páginas a Teams no está disponible para clientes de GCC High y DoD
- La funcionalidad de Graph en SharePoint Online para GCC High está deshabilitada actualmente. Es posible que cualquier servicio que se base en Microsoft Graph no esté disponible actualmente
- Las características que dependen de las conexiones a servicios de Internet, como la pestaña imágenes de stock, no funcionarán como se esperaba
- Las notificaciones de actividad de archivo y sitio no están disponibles

## <a name="search-features"></a>Características de búsqueda

Estas son las diferencias entre las características de búsqueda de los clientes comerciales y las de los clientes de la nube gubernamental:

- Microsoft Search no está disponible en GCC.

## <a name="sharing-and-sync"></a>Uso compartido y sincronización

Para obtener información sobre las diferencias de características entre la nube comercial y los entornos de nube gubernamentales, vea [Uso compartido de archivos.](./gcc-high-and-dod.md#file-sharing)

## <a name="plan-for-governance"></a>Plan for governance

El paso a la nube ofrece experiencias transformadoras con controles de administración integrados. Determine los requisitos de gobierno y cómo puede cumplirlos. Vaya a [Plan for governance to transform teamwork with Microsoft 365](https://resources.techcommunity.microsoft.com/teamwork-governance/) para obtener más información. Encontrará instrucciones sobre Grupos de Office 365, SharePoint, Teams y mucho más.

## <a name="deploy-sharepoint-for-collaboration"></a>Implementar SharePoint para colaboración

Después de configurar la organización en la nube del gobierno de Microsoft US, siga la ruta de implementación recomendada que se describe en el Centro de recursos de adopción [de SharePoint](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/). Asegúrese de interactuar con sus campeones de adopción y administración de cambios.
También puede trabajar con [FastTrack](https://www.microsoft.com/fasttrack) o su partner elegido para realizar el servicio a los usuarios.
Visite el [Centro de confianza](https://www.microsoft.com/trust-center) de Microsoft para obtener más información sobre cómo Microsoft aborda la seguridad, la privacidad y el cumplimiento, principios básicos de cómo habilitamos a las organizaciones para que sirvan a sus clientes.