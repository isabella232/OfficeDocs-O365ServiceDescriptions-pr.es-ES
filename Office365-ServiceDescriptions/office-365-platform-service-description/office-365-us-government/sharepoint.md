---
title: SharePoint para entornos gubernamentales de Estados Unidos
ms.author: mkashman
author: kaarins
manager: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Obtenga información sobre la disponibilidad de características de SharePoint para los clientes de la nube de US Government.
ms.openlocfilehash: 310aa1589aed1156de223bed229ce99ef2f5b69a
ms.sourcegitcommit: ace6cd97a0d3823959e1629929be77489f79b520
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/25/2020
ms.locfileid: "49411609"
---
# <a name="sharepoint-for-us-government-environments"></a>SharePoint para entornos gubernamentales de Estados Unidos

En este artículo se proporciona información general sobre las diferencias de características entre la nube de los Estados Unidos y la nube comercial, tal como se muestra en la [Descripción del servicio de SharePoint](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-service-description). SharePoint está disponible para los entornos de la nube de la comunidad de administración pública (GCC), GCC High y DoD. 

Para obtener más información sobre la nube de administración pública, incluida la idoneidad y la compra, consulte [Microsoft 365 Government: How to Buy](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy). Para comparar los planes de Office 365 administración pública, vea [office 365 planes gubernamentales](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements).

Para obtener información sobre los puntos de conexión necesarios al administrar la conectividad de red, vea los puntos de conexión de [office 365 U.s. Government GCC GCC High endpoints](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) o [Office 365 u.s. Government DoD](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business).

Además de disfrutar de las características y capacidades de Office 365, las organizaciones se benefician de las siguientes características que son exclusivas de los entornos de la nube del gobierno de Estados Unidos:

-   El contenido del cliente de la organización se separa lógicamente del contenido del cliente en los servicios comerciales de Office 365 de Microsoft.
-   El contenido del cliente de la organización se almacena dentro de los Estados Unidos.
-   El acceso al contenido del cliente de la organización está restringido a personal específico de Microsoft.
-   Los entornos de nube de administración cumplen con las certificaciones y acreditaciones necesarias para los clientes del sector público de los Estados Unidos.

Nuestro objetivo es entregar todas las características y funciones comerciales de SharePoint a los entornos de nube de administración pública. Algunas características no están disponibles debido a los requisitos de los clientes de la nube gubernamental. Otras características están llegando a los entornos gubernamentales, pero aún no están disponibles. Consulte las siguientes secciones para obtener información sobre la disponibilidad de características en los entornos de nube de administración pública.

## <a name="developer-features"></a>Características de desarrollador

No existen diferencias conocidas entre las características de desarrollador para los clientes comerciales y las de los clientes de la nube de administración pública.

- Las conexiones a aplicaciones externas como orígenes de datos para complementos están limitadas a los orígenes que se encuentran dentro de los límites de seguridad del sistema admitidos por el entorno gubernamental.
- La funcionalidad de servicios de conectividad empresarial (BCS) se admite en escenarios de conectividad en los que los orígenes de datos permanecen accesibles dentro del límite de seguridad del servicio de nube.

Si usa aplicaciones de terceros en los sitios, revise las declaraciones de privacidad y cumplimiento que ofrecen los terceros para evaluar el uso adecuado de estos servicios en su organización. Las aplicaciones y servicios de terceros pueden implicar el almacenamiento, la transmisión y el procesamiento de los datos de los clientes de su organización en sistemas de terceros que están fuera de la nube pública y que, por lo tanto, no están cubiertos por los compromisos de protección y protección de datos. 

## <a name="it-admin-features"></a>Características de administración de ti

Estas son las diferencias entre las características de administración de TI para los clientes comerciales y las de los clientes de la nube de administración pública.

- El cambio de la dirección de un sitio no está disponible para los clientes de GCC High
- El servidor híbrido de SharePoint no está disponible para todos los clientes de la nube de administración pública
- La herramienta de migración de SharePoint y el administrador de migración requieren un cambio en la configuración. Para obtener información, vea [SPMT Government Cloud support](/sharepointmigration/spmt-install-issues#government-cloud-support).
- Mover.io todavía no se admite
- Multigeográfico no está disponible para todos los clientes de la nube de administración pública

Para obtener información acerca de la migración de FastTrack, vea la [Descripción del servicio Office 365 US Government](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#data-migrations-performed-by-fasttrack).

## <a name="security-and-compliance-features"></a>Características de seguridad y cumplimiento

No existen diferencias conocidas entre las características de seguridad y cumplimiento para los clientes comerciales y para los clientes de la nube de administración pública.

Para obtener información acerca de las características de seguridad y cumplimiento, consulte el [centro de seguridad & cumplimiento](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-securitycompliance-center).

Para obtener información acerca de las características de Azure Active Directory para el gobierno, consulte [Azure Government Security + Identity Documentation](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory). 

Para obtener información acerca de las características de Azure Information Protection para administración pública, vea la [Descripción del servicio de administración pública de Azure Information Protection](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description). 

## <a name="sites-and-content"></a>Sitios y contenido

Estas son las diferencias entre los sitios y las características de contenido para clientes comerciales y para los clientes de la nube de administración pública:

- Los elementos Web que se basan en conexiones a servicios de Internet, como los elementos Web de Amazon Kindle, mapas de Bing, Twitter y YouTube, no funcionarán según lo esperado
- La biblioteca de activos de la organización no está disponible
- La adición de listas y páginas a teams no está disponible para los clientes de GCC High y DoD

## <a name="search-features"></a>Características de búsqueda

Estas son las diferencias entre las características de búsqueda para los clientes comerciales y las de los clientes de la nube de administración pública:

- La integración de Microsoft Search no está disponible.

## <a name="sharing-and-sync"></a>Uso compartido y sincronización

Para obtener las diferencias de características entre la nube comercial y los entornos de nube de administración, consulte [uso compartido de archivos](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/gcc-high-and-dod#file-sharing).

## <a name="plan-for-governance"></a>Planeación del gobierno

Su traslado a la nube ofrece experiencias de transformación con controles de administración integrados. Determine los requisitos para el gobierno y la manera en que puede darles a conocerlos. Vaya a [Plan for Governance to Transform trabajo en equipo con Microsoft 365](https://resources.techcommunity.microsoft.com/teamwork-governance/) para obtener más información. Encontrará orientación sobre los grupos de Office 365, SharePoint, Teams y mucho más.

## <a name="deploy-sharepoint-for-collaboration"></a>Implementación de SharePoint para colaboración

Después de configurar la organización en la nube de Microsoft US Government Cloud, siga la ruta de implementación recomendada que se describe en el centro de recursos para la [adopción de SharePoint](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/). Asegúrese de participar con los expertos en administración de cambios y la adopción.
También puede trabajar con [FastTrack](https://www.microsoft.com/fasttrack) o con su partner elegido para implementar el servicio para sus usuarios.
Visite el [centro de confianza de Microsoft](https://www.microsoft.com/trust-center) para obtener más información sobre la forma en que Microsoft se acerca a la seguridad, la privacidad y el cumplimiento, los principios básicos sobre cómo permite que las organizaciones atiendan a sus clientes.
