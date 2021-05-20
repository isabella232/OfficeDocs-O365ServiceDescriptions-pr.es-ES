---
title: Microsoft 365 orientación sobre licencias para el cumplimiento de & de seguridad
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.reviewer: v-trscho
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Este artículo proporciona instrucciones de licencia para Microsoft 365 cumplimiento para ayudar a evitar posibles interrupciones en el servicio debido al acceso sin licencia.
ms.openlocfilehash: d4ddb9c492cccef13c86e450c64a2eb6efe61eaa
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52546017"
---
# <a name="microsoft-365-licensing-guidance-for-security-amp-compliance"></a>Microsoft 365 orientación sobre licencias para el cumplimiento de la seguridad &amp;

A los efectos de este artículo, un servicio de nivel de inquilino es un servicio en línea que &mdash; cuando se compra para cualquier usuario del inquilino (independiente o como parte de Office 365 o planes de Microsoft 365) se activa en parte o en su totalidad para todos los usuarios del &mdash; inquilino. Aunque algunos usuarios sin licencia pueden acceder técnicamente al servicio, se requiere una licencia para cualquier usuario que tenga la intención de beneficiarse del servicio.

> [!NOTE]
> Algunos servicios de inquilino no son actualmente capaces de limitar las ventajas a usuarios específicos. Se deben realizar esfuerzos para limitar los beneficios del servicio a los usuarios con licencia. Esto ayudará a evitar posibles interrupciones del servicio en su organización una vez que las capacidades de segmentación estén disponibles.

Para ver las opciones para conceder licencias a los usuarios para que se beneficien de Microsoft 365 características de cumplimiento, descargue la comparación detallada de licencias de cumplimiento de Microsoft 365. [(PDF)](https://www.microsoft.com/download/details.aspx?id=103010)  |  [(Excel)](https://www.microsoft.com/download/details.aspx?id=103006)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory Identity Protection es una característica del plan P2 Azure Active Directory Premium que le permite detectar vulnerabilidades potenciales que afectan a las identidades de su organización, configurar respuestas automatizadas a acciones sospechosas detectadas relacionadas con las identidades de su organización e investigar incidentes sospechosos y tomar las medidas adecuadas para resolverlas.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los analistas y profesionales de seguridad de SecOps se benefician de tener vistas consolidadas de usuarios marcados y eventos de riesgo basados en algoritmos de aprendizaje automático. Los usuarios finales se benefician de la protección automática proporcionada a través del acceso condicional basado en riesgos y la seguridad mejorada proporcionada por la acción de vulnerabilidades.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, seguridad Microsoft 365 E5/A5 y plan Azure Active Directory Premium 2 proporcionan los derechos para que un usuario se beneficie de Azure Active Directory protección de identidad.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

De forma predeterminada, las características de Azure AD Identity Protection están habilitadas en el nivel de inquilino para todos los usuarios del inquilino. Para obtener información acerca de Azure AD Identity Protection, consulte [¿Qué es Identity Protection?](/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los administradores pueden crear un ámbito de Azure AD Identity Protection asignando directivas de riesgo que definen el nivel para los restablecimientos de contraseña y permitiendo el acceso solo para usuarios con licencia. Para obtener instrucciones sobre cómo crear un ámbito de las implementaciones de Azure AD Identity Protection, consulte [Cómo configurar y habilitar directivas de riesgo.](/azure/active-directory/identity-protection/howto-sign-in-risk-policy)

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory Gobernanza de la identidad

Azure Active Directory El gobierno de identidad le permite equilibrar la necesidad de seguridad y productividad de los empleados de su organización con los procesos y la visibilidad adecuados. Utiliza la administración de derechos, las revisiones de acceso, la administración de identidades con privilegios y las políticas de términos de uso para garantizar que las personas adecuadas tengan el acceso correcto a los recursos adecuados.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Azure Active Directory Identity Governance aumenta la productividad de los usuarios al facilitar el acceso a aplicaciones, grupos y Microsoft Teams en un solo paquete de acceso. Los usuarios también se pueden configurar como aprobadores, sin involucrar a los administradores. Para las revisiones de acceso, los usuarios pueden revisar las pertenencias de grupos con recomendaciones inteligentes para tomar medidas a intervalos regulares.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, seguridad Microsoft 365 E5/A5 y plan de Azure Active Directory Premium 2 proporcionan los derechos para que un usuario se beneficie de Azure Active Directory gobierno de identidad.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

Las características de Azure AD Identity Governance están habilitadas en el nivel de inquilino, pero se implementan por usuario. Para obtener información acerca de Azure AD Identity Governance, consulte [¿Qué es Azure AD Identity Governance?](/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los administradores pueden tener acceso a Azure AD Identity Governance asignando paquetes de acceso, revisiones de acceso o administración de identidades con privilegios solo para usuarios con licencia. Para obtener instrucciones sobre cómo crear un ámbito de las implementaciones de Azure AD Identity Governance, consulte:

- [Requisitos de licencia de administración de derechos de Azure AD](/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Requisitos de licencia de revisión de acceso de Azure AD](/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [Requisitos de licencia para usar Privileged Identity Management](/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender for Identity

Microsoft Defender for Identity (anteriormente Azure Advanced Threat Protection) es un servicio en la nube que ayuda a proteger los entornos híbridos empresariales de varios tipos de ciberataques dirigidos avanzados y amenazas internas.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los analistas y profesionales de seguridad de SecOp se benefician de la capacidad de Microsoft Defender for Identity para detectar e investigar amenazas avanzadas, identidades comprometidas y acciones maliciosas de información privilegiada. Los usuarios finales se benefician al tener sus datos supervisados por Microsoft Defender for Identity.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5/G5, seguridad Microsoft 365 E5/A5/G5 y Microsoft Defender para la identidad de los usuarios proporcionan los derechos para beneficiarse de Microsoft Defender for Identity.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

De forma predeterminada, las características de Microsoft Defender for Identity están habilitadas en el nivel de inquilino para todos los usuarios dentro del inquilino. Para obtener información sobre cómo configurar ATP de Azure, consulte [Crear la instancia de Microsoft Defender for Identity](/defender-for-identity/install-step1).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los servicios de Microsoft Defender for Identity no son actualmente capaces de limitar las capacidades a usuarios específicos. Debe licenciar a todos los usuarios a los que tenga la intención de beneficiarse.

## <a name="microsoft-defender-for-office-365"></a>Microsoft Defender para Office 365

Microsoft Defender for Office 365 (anteriormente Office 365 Advanced Threat Protection) ayuda a proteger a las organizaciones contra ataques sofisticados como phishing y malware de día cero. Microsoft Defender for Office 365 también proporciona información procesable mediante la correlación de señales de una amplia gama de datos para ayudar a identificar, priorizar y proporcionar recomendaciones sobre cómo abordar posibles amenazas.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Microsoft Defender for Office 365 protege a los usuarios de ataques sofisticados como phishing y malware de día cero. Para obtener la lista completa de los servicios proporcionados en el Plan 1 y el Plan 2, consulte [Microsoft Defender para obtener Office 365](/microsoft-365/security/office-365-security/office-365-atp).

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio? 

Microsoft Defender para planes de Office 365 1 y 2, Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, seguridad Microsoft 365 E5/A5/G5 y Microsoft 365 Empresa Premium proporcionar los derechos para que un usuario se beneficie de Microsoft Defender durante Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

De forma predeterminada, Las características de Microsoft Defender para Office 365 están habilitadas en el nivel de inquilino para todos los usuarios dentro del inquilino. Para obtener información sobre cómo configurar Microsoft Defender para directivas de Office 365 para usuarios con licencia, consulte [Microsoft Defender para obtener Office 365](/microsoft-365/security/office-365-security/office-365-atp).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Para crear un ámbito a Microsoft Defender para Office 365, siga las directivas Caja fuerte de implementación vínculos y Caja fuerte de Caja fuerte adjuntos:

- Para obtener información sobre cómo configurar vínculos de Caja fuerte para usuarios con licencia, consulte [vínculos Caja fuerte en Microsoft Defender para obtener Office 365](/microsoft-365/security/office-365-security/atp-safe-links).

- Para obtener información sobre cómo configurar datos adjuntos de Caja fuerte para usuarios con licencia, consulte [Caja fuerte adjuntos en Microsoft Defender para obtener Office 365](/microsoft-365/security/office-365-security/atp-safe-attachments).

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS) es un subconjunto de Microsoft Cloud App Security, con características limitadas a Office 365 y sin seguridad adicional para aplicaciones en la nube de terceros y servicios de IaaS.

OCAS ofrece a las organizaciones visibilidad de sus aplicaciones y servicios en la nube de productividad, proporciona análisis sofisticados para identificar y combatir las amenazas cibernéticas y les permite controlar cómo viajan los datos &mdash; a través de Office 365.

Para comparar operaciones, consulte [Diferencias entre Microsoft Cloud App Security y Office 365 Cloud App Security](/cloud-app-security/editions-cloud-app-security-o365).

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

OCAS descubre Shadow IT, proporciona protección contra amenazas en todas Office 365 y puede controlar qué aplicaciones tienen permiso para acceder a los datos.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Office 365 E5/A3/A5/G5 proporcionan los derechos para que un usuario se beneficie de OCAS.
Para obtener más información, consulte la [hoja de datos de licencias de Microsoft Cloud App Security](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

De forma predeterminada, las características de OCAS están habilitadas en el nivel de inquilino para todos los usuarios dentro del inquilino.

Para obtener información sobre cómo configurar el servicio, consulte [Configuración básica para Cloud App Security](/cloud-app-security/general-setup).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los administradores pueden crear un ámbito en las implementaciones de OCAS para aplicar cómo se accede a ciertas aplicaciones y limitar los grupos de usuarios supervisados por Office 365 Cloud App Security. Para obtener más información, consulte [Implementación de ámbito.](/cloud-app-security/scoped-deployment)

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) es una solución de Cloud Access Security Broker (CASB) que proporciona a las organizaciones visibilidad de sus aplicaciones y servicios en la nube, proporciona análisis sofisticados para identificar y combatir las amenazas cibernéticas y les permite controlar cómo viajan los datos &mdash; a través de cualquier aplicación en la nube.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

MCAS descubre y evalúa Shadow IT, proporciona protección contra amenazas en aplicaciones en la nube de primera y de terceros y protege la información en aplicaciones en la nube de primera y de terceros.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

MCAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, seguridad Microsoft 365 E5/A5/G5, cumplimiento de Microsoft 365 E5/A5/G5 y Microsoft 365 protección y gobernanza de la información proporcionan los derechos para que un usuario se beneficie de MCAS.

Azure AD P1 proporciona los derechos para que un usuario se beneficie de las capacidades de detección en MCAS.

Para beneficiarse de las capacidades de Control de aplicaciones de acceso condicional en MCAS, los usuarios también deben tener licencia para Azure Active Directory P1, que se incluye en Enterprise Mobility + Security E3/A3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5 y seguridad Microsoft 365 E5/A5/G5.

Para beneficiarse del etiquetado automático del lado cliente, los usuarios deben tener licencia para Azure Information Protection P2, que se incluye en Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, cumplimiento de Microsoft 365 E5/A5/G5 y Microsoft 365 Protección y gobernanza de la información.

> [!NOTE]
> El etiquetado automático del lado del servidor requiere protección de la información para Office 365 - licencias de Premium ( `MIP_S_CLP2` o `efb0351d-3b08-4503-993d-383af8de41e3` ). Como referencia, consulte [Nombres de productos e identificadores de plan de servicio para obtener licencias.](/azure/active-directory/enterprise-users/licensing-service-plan-reference)

Para obtener más información, consulte la [hoja de datos de licencias de Microsoft Cloud App Security](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

De forma predeterminada, las características mcas están habilitadas en el nivel de inquilino para todos los usuarios dentro del inquilino.

Para obtener información sobre cómo configurar directivas de Microsoft Cloud App Security para usuarios con licencia, consulte [información general sobre Microsoft Cloud App Security](/cloud-app-security/what-is-cloud-app-security).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los administradores pueden realizar un ámbito de las implementaciones de MCAS a los usuarios con licencia mediante las capacidades de implementación de ámbito disponibles en el servicio. Para obtener más información, consulte [Implementación de ámbito.](/cloud-app-security/scoped-deployment)

## <a name="compliance-manager"></a>Administrador de cumplimiento

Simplifique el cumplimiento y ayude a reducir el riesgo con Compliance Manager. Compliance Manager ayuda a las organizaciones a cumplir con los requisitos de regulaciones, estándares, directivas de empresa u otros marcos de control deseados.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

A continuación se presentan las ventajas para los usuarios del servicio Compliance Manager:

- Traduce regulaciones complicadas, estándares, políticas de la empresa u otros marcos de control deseados en un lenguaje simple
- Proporciona acceso a una vasta biblioteca de evaluaciones listas para usar y evaluaciones personalizadas para satisfacer necesidades únicas de cumplimiento
- Mapas controles regulatorios a las acciones de mejora recomendadas
- Proporciona orientación paso a paso sobre cómo implementar las soluciones para cumplir con los requisitos reglamentarios
- Ayuda a los usuarios a priorizar acciones que tendrán el mayor impacto en su cumplimiento organizativo mediante la asociación de una puntuación con cada acción

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Los clientes con licencias E1 y E3/G3 solo podrán acceder a la evaluación predeterminada de Data Protection Baseline. Los clientes con licencias de Office 365 E5/A5 y Microsoft 365 E5/A5 (cumplimiento, gobierno de & de protección de la información y SKU de exhibición y auditoría electrónica incluidas) podrán acceder a evaluaciones de línea base, RGPD, NIST 800-53 e ISO 27001 listas para usar. Los clientes con Office 365 G5 y Microsoft 365 G5 podrán acceder a los niveles 1 a 5 evaluaciones de nivel 1 a 5 de data protection baseline, GDPR, NIST 800-53, ISO 27001 y Cybersecurity Maturity Model Certification (CMMC). La función de evaluación personalizada y las evaluaciones premium están reservadas para clientes de Office 365 E5/A5/G5 y Microsoft 365 E5/A5/G5. Premium evaluaciones, como FedRAMP Moderate, FedRAMP High y otros, estarán disponibles para su compra a clientes con licencias E5/A5/G5 durante el primer semestre de 2021 a través de VL, CSP y WebDirect. Póngase en contacto con su vendedor de Microsoft o socio de Microsoft para comprar a través de canales VL o CSP, respectivamente. Para comprar a través de WebDirect, consulte [WebDirect](https://aka.ms/ComplianceManager/WebDirect).

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

Compliance Manager se aprovisiona de forma predeterminada para el inquilino. Los administradores establecen permisos de usuario y asignan roles para que los usuarios que no son administradores de la organización puedan empezar a usar Compliance Manager. Para obtener más información, consulte [Introducción al Administrador de cumplimiento: establezca permisos de usuario y asigne roles.](/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)

## <a name="microsoft-defender-for-endpoint"></a>Microsoft Defender para punto de conexión

Microsoft Defender for Endpoint (anteriormente ATP de Microsoft Defender) es una solución de seguridad de punto de conexión que incluye administración de vulnerabilidades y evaluación basadas en riesgos; capacidades de reducción de superficie de ataque; protección de próxima generación basada en el comportamiento y basada en la nube; detección y respuesta de puntos de conexión (EDR); investigación y reparación automáticas; y servicios de caza gestionados. Consulte la página [Microsoft Defender for Endpoint](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) para obtener más información.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Windows 10 Enterprise E5, Windows 10 Education A5, Microsoft 365 E5/G5, que incluye Windows 10 Enterprise E5, seguridad Microsoft 365 E5/A5/G5, pueden beneficiarse de Microsoft Defender para endpoint.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los analistas y profesionales de seguridad de SecOps se benefician de las capacidades de seguridad de punto final de Microsoft Defender para Endpoint para realizar protección preventiva, detección posterior a la infracción, investigación automatizada y respuesta a amenazas avanzadas. Los usuarios finales se benefician al tener eventos malintencionados supervisados por Microsoft Defender para Endpoint.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

De forma predeterminada, las características de Microsoft Defender para endpoints están habilitadas en el nivel de inquilino para todos los usuarios dentro del inquilino. Para obtener información sobre la implementación, consulte [Fases de implementación.](/windows/security/threat-protection/microsoft-defender-atp/deployment-phases)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los administradores de Microsoft Defender for Endpoint pueden usar el control de acceso basado en roles (RBAC) para crear roles y grupos dentro del equipo de operaciones de seguridad para conceder acceso adecuado a la Centro de seguridad de Microsoft Defender. Para obtener más información, consulte [Administrar el acceso al portal mediante el control de acceso basado en roles.](/windows/security/threat-protection/microsoft-defender-atp/rbac)

## <a name="microsoft-365-data-classification-analytics-overview-content-amp-activity-explorer"></a>Análisis de clasificación de datos Microsoft 365: Descripción general &amp; del Explorador de actividades de contenido

Las capacidades analíticas de clasificación de datos están disponibles dentro de Microsoft 365 experiencia del centro de cumplimiento. La visión general muestra las ubicaciones de contenido digital y los tipos y etiquetas de información confidencial más comunes presentes. El Explorador de contenido proporciona visibilidad de la cantidad y los tipos de datos confidenciales y permite a los usuarios filtrar por etiqueta o tipo de sensibilidad para obtener una vista detallada de las ubicaciones donde se almacenan los datos confidenciales. El Explorador de actividades muestra actividades relacionadas con datos y etiquetas confidenciales, como degradaciones de etiquetas o uso compartido externo que podrían exponer el contenido al riesgo.

El Explorador de actividades proporciona un único panel de cristal para que los administradores obtengan visibilidad sobre las actividades relacionadas con la información confidencial que usan los usuarios finales. Estos datos incluyen actividades de etiquetas, registros de prevención de pérdida de datos (DLP), etiquetado automático, DLP de punto final y mucho más.

El Explorador de contenido proporciona a los administradores la capacidad de indexar los documentos confidenciales que se almacenan dentro de las cargas de trabajo Microsoft 365 admitidas e identificar la información confidencial que almacenan. Además, el Explorador de contenido ayuda a identificar documentos clasificados con etiquetas de sensibilidad y retención.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los administradores de protección de la información y cumplimiento pueden acceder al servicio para obtener acceso a estos registros y datos indexados para comprender dónde se almacenan los datos confidenciales y qué actividades están relacionadas con estos datos y las realizan los usuarios finales.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Los usuarios con licencia de Microsoft 365 E5/A5/G5, cumplimiento de Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Information Protection &amp; Governance y Office 365 E5 pueden beneficiarse de Microsoft 365 análisis de clasificación de datos. 

Microsoft 365 E3/A3/G3 y Office 365 E3/A3/G3 permiten a los usuarios beneficiarse únicamente de la agregación de datos de Content Explorer.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

De forma predeterminada, las características del Explorador de contenido y actividad de Información general están habilitadas en el nivel de inquilino para todos los usuarios del inquilino. Para obtener información sobre cómo configurar el análisis de clasificación de datos para usuarios con licencia, consulte:

- **Explorador de contenido**: [Introducción al explorador de contenido : Microsoft 365 cumplimiento | Microsoft Docs](/microsoft-365/compliance/data-classification-content-explorer).
- **Explorador de actividades:** [comience con el explorador de actividades: Microsoft 365 cumplimiento | Microsoft Docs](/microsoft-365/compliance/data-classification-activity-explorer).
- **Notas de la versión de clasificación de** datos : Notas de la versión de clasificación de datos - Microsoft 365 cumplimiento [| Microsoft Docs](/microsoft-365/compliance/data-classification-pub-preview-relnotes).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Esta característica debe tener el acceso a los usuarios que utilizan activamente la solución dentro Microsoft 365 portal de cumplimiento.

## <a name="information-protection"></a>Protección de la información

Information Protection ayuda a las organizaciones a descubrir, clasificar, etiquetar y proteger documentos y correos electrónicos confidenciales. Los administradores pueden definir reglas y condiciones para aplicar etiquetas automáticamente, los usuarios pueden aplicar etiquetas manualmente o se puede usar una combinación de las dos, donde los usuarios reciben recomendaciones sobre la aplicación de etiquetas.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician al tener la capacidad de aplicar manualmente etiquetas de sensibilidad a su contenido o al tener su contenido clasificado automáticamente.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, Office 365 E5/A5/E3/A3/F3, AIP Plan 1 y AIP Plan 2 proporcionan los derechos para que el usuario se beneficie del etiquetado de sensibilidad manual.

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, AIP Plan 1 y AIP Plan 2 proporcionan los derechos para que un usuario se beneficie de la aplicación y visualización de etiquetas de sensibilidad en Power BI y para proteger los datos cuando se exporta de Power BI a Excel, PowerPoint o PDF. 

> [!NOTE]
> Power BI incluye Microsoft 365 E5/A5/G5; en todos los demás planes, Power BI deben tener licencia por separado.

Microsoft 365 E5/A5/G5, cumplimiento de Microsoft 365 E5/A5/G5, protección de la información Microsoft 365 E5/A5/G5 y gobernanza, Office 365 E5, Enterprise Mobility + Security E5/A5/G5 y plan 2 de AIP proporcionan los derechos para que un usuario se beneficie del etiquetado automático de sensibilidad.

Para conocer los derechos específicos por licencia, consulte la comparación detallada de licencias de cumplimiento Microsoft 365. [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx) No incluye derechos de clasificación automática basados en Machine Learning (clasificadores entrenables).

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

De forma predeterminada, las características de protección de la información están habilitadas en el nivel de inquilino para todos los usuarios dentro del inquilino. Para obtener información sobre cómo configurar directivas para usuarios con licencia, consulte Activación de Azure Rights Management.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Excepto cuando se utiliza la característica del analizador AIP, las directivas se pueden aplicar al ámbito de grupos o usuarios y registros específicos se pueden editar para evitar que los usuarios sin licencia ejecuten características de clasificación o etiquetado. Para obtener instrucciones sobre cómo crear el ámbito de las implementaciones de AIP, consulte [Configuración de la directiva de Azure Information Protection](/azure/information-protection/configure-policy).

Para la característica del analizador AIP, Microsoft no se compromete a proporcionar capacidades de clasificación, etiquetado o protección de archivos a los usuarios que no tienen licencia.

## <a name="information-governance"></a>Gobernanza de la información

Information Governance ayuda a las organizaciones a gestionar su riesgo mediante el descubrimiento, clasificación, etiquetado y administración de sus datos. Information Governance permite a las organizaciones cumplir con los requisitos empresariales y reglamentarios, así como reducir su superficie de ataque al proporcionar capacidades de retención y eliminación en sus datos de Microsoft 365 y de terceros.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician al poder clasificar los datos con fines de retención para mantener políticas y regulaciones específicas.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 F3/Business Premium, Office 365 E1/A1/F3 y planes de Exchange independientes proporcionan los derechos para que un usuario se beneficie de aplicar manualmente etiquetas de retención que no sean de registro a los datos de buzón de correo.

Microsoft 365 F3/F1/Business Premium, Office 365 E1/A1/F3 y planes de SharePoint independientes proporcionan los derechos para que un usuario se beneficie de la aplicación manual de etiquetas de retención que no son de registro a archivos en SharePoint o OneDrive. 

Microsoft 365 E5/A5/G5/E3/A3/Business Premium, Office 365 E5/A5/G5/E3/A3, Exchange Plan 2 y Archivado de Exchange Online proporcionar los derechos para que un usuario se beneficie de una directiva básica de retención de buzones de correo en toda la organización o en toda la ubicación y/o para aplicar manualmente un etiquetado de retención sin registros a los datos de buzón de correo.

Microsoft 365 E5/A5/G5/E3/A3, Office 365 E5/A5/G5/E3/A3 y SharePoint Plan 2 proporcionan los derechos para que un usuario se beneficie de una política básica de retención de SharePoint o OneDrive y/o aplique manualmente una etiqueta de retención sin registro a los archivos de SharePoint o OneDrive.

Microsoft 365 E5/A5/G5/E3/A3 y Office 365 E5/A5/G5/E3/A3 proporcionan los derechos para que un usuario se beneficie de una política de retención Teams.

Microsoft 365 E5/A5/G5, cumplimiento Microsoft 365 E5/A5/G5, protección de la información Microsoft 365 y gobernanza E5/A5/G5, y Office 365 E5/A5 proporcionan los derechos para que un usuario se beneficie de la aplicación automática de etiquetas o directivas de retención, la aplicación de etiquetas o directivas de retención predeterminadas, el inicio del período de retención de una etiqueta de retención basada en un evento personalizado, la activación de una revisión manual de la disposición al final del período de retención de la etiqueta, la importación de datos de terceros a través de conectores de datos nativos, la declaración de un archivo un registro, la detección de contenido etiquetado y la supervisión de la actividad de etiquetado.

Microsoft 365 E5/A5/G5, cumplimiento de Microsoft 365 E5/A5/G5, protección de la información Microsoft 365 E5/A5/G5 y gobernanza proporcionan los derechos para que un usuario se beneficie de la aplicación automática de etiquetas de retención basadas en clasificadores formables.

Para conocer los derechos específicos por licencia, consulte la comparación detallada de licencias de cumplimiento Microsoft 365. [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

De forma predeterminada, las características de Gobierno de la información están habilitadas en el nivel de inquilino para todos los usuarios dentro del inquilino. Para obtener información sobre cómo configurar information governance para aplicar etiquetas automáticas y directivas para usuarios con licencia, consulte [Gobierno de información de Microsoft en Microsoft 365](/microsoft-365/compliance/manage-information-governance).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Las funciones de gobierno de la información se pueden aplicar a los usuarios con licencia en ubicaciones específicas (sitios de equipo, sitios de grupo, etc.). Para obtener información sobre cómo configurar information governance para aplicar etiquetas automáticas y directivas para usuarios con licencia, consulte [Gobierno de información de Microsoft en Microsoft 365](/microsoft-365/compliance/manage-information-governance).

## <a name="records-management"></a>Records Management

La administración de registros ayuda a las organizaciones a cumplir con sus obligaciones de mantenimiento de registros empresariales y reglamentarios mediante el descubrimiento, clasificación, etiquetado, retención y capacidades de eliminación defendibles en sus datos de Microsoft 365 y de terceros.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E5/A5/G5, cumplimiento Microsoft 365 E5/A5/G5, protección de la información y gobernanza de Microsoft 365 E5/A5/G5, y Office 365 E5/A5/G5 proporcionan los derechos para que un usuario se beneficie de la Administración de registros, incluida la declaración de artículos como registros o registros reglamentarios, la aplicación automática de etiquetas de retención o registro y la ejecución de procesos de revisión de disposición (excluyendo la aplicación automática de una etiqueta de retención basada en clasificadores formables).

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance y Microsoft 365 Information Protection and Governance proporcionan los derechos para que un usuario se beneficie de la aplicación automática de etiquetas de retención o registro basadas en clasificadores formables.

Para conocer los derechos específicos por licencia, consulte la comparación detallada de licencias de cumplimiento Microsoft 365. [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician al poder declarar contenido como un registro y administrar su proceso de registros completos desde la definición y declaración de políticas a través de la eliminación defendible.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

De forma predeterminada, las características de administración de registros están habilitadas en el nivel de inquilino para todos los usuarios dentro del inquilino. Para obtener información sobre cómo configurar la administración de registros para que se aplique a los usuarios con licencia, consulte [Información sobre administración de registros en Microsoft 365](/microsoft-365/compliance/records-management).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Las características de administración de registros se pueden aplicar a usuarios con licencia en ubicaciones específicas (sitios de grupo, sitios de grupo, etc.). Para obtener información sobre cómo configurar la administración de registros para que se aplique a los usuarios con licencia, consulte [Información sobre administración de registros en Microsoft 365](/microsoft-365/compliance/records-management).

## <a name="data-connectors"></a>Conectores de datos 

Microsoft proporciona conectores de datos de terceros que se pueden configurar en el centro de cumplimiento de Microsoft 365. Para obtener una lista de los conectores de datos proporcionados por Microsoft, consulte la tabla [Conectores de datos de](/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) terceros. En esta tabla también se resumen las soluciones de cumplimiento que puede aplicar a los datos de terceros después de importar y archivar datos en Microsoft 365 y vínculos a las instrucciones paso a paso para cada conector.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

La principal ventaja de usar conectores de datos para importar y archivar datos de terceros en Microsoft 365 es que puede aplicar varias soluciones de cumplimiento Microsoft 365 a los datos después de importarlos. Esto ayuda a garantizar que los datos que no son de Microsoft de su organización cumplan con las regulaciones y estándares que afectan a su organización.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Las siguientes licencias proporcionan los derechos para que un usuario se beneficie de data connectors:

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 Info Protection &amp; Governance
- cumplimiento de Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 Gestión de Riesgos Internos
- Microsoft 365 E5/A5/G5 eDiscovery y Auditoría
- Office 365 E5/A5/G5

Para los conectores de datos del Centro de cumplimiento de seguridad Microsoft 365 &amp; proporcionados por un asociado de Microsoft, la organización necesitará una relación comercial con el asociado antes de poder implementar esos conectores.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

Los conectores se configuran mediante security &amp; compliance center y connector catalog.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los servicios de conectores de datos son un valor de nivel de inquilino. Todos los usuarios destinados a beneficiarse de este servicio deben tener licencia.

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp"></a>Las API de Microsoft Graph para la prevención de pérdida de datos Teams (DLP)

A principios de este año [anunciamos la versión preliminar pública de la API de notificación de cambios de Microsoft Graph para los mensajes en Teams](https://go.microsoft.com/fwlink/?linkid=2143888). Esta API permite a los desarrolladores crear aplicaciones que pueden escuchar mensajes Microsoft Teams en tiempo casi real y habilitar implementaciones de escenarios DLP tanto para clientes como para ISV. Además, Microsoft Graph Api de parches permite aplicar acciones DLP a Teams mensajes.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Las capacidades de [prevención de pérdida de datos (DLP)](/microsoft-365/compliance/dlp-microsoft-teams) se utilizan ampliamente en Microsoft Teams, particularmente a medida que las organizaciones han cambiado al trabajo remoto. Si su organización tiene DLP, ahora puede definir directivas que impidan a las personas compartir información confidencial en una sesión de canal o chat Microsoft Teams.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Necesitará una de las siguientes licencias para obtener soporte para la protección DLP en Teams Chat:

- Microsoft 365 E5/A5/G5
- cumplimiento de Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 Protección y gobernanza de la información
- Office 365 E5/A5/G5 

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

El acceso a la API se configura en el nivel de inquilino.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Microsoft Graph API para Teams DLP es un valor de nivel de inquilino. Todos los usuarios destinados a beneficiarse de este servicio deben tener licencia.

## <a name="ediscovery"></a>eDiscovery

eDiscovery proporciona soluciones de investigación y exhibición de documentos electrónicos para que los departamentos de TI y legales dentro de las corporaciones identifiquen, recojan, conserven, reduzcan y revisen contenido relacionado con una investigación o litigio antes de exportar fuera del sistema de Microsoft 365.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Un usuario se beneficia de Advanced eDiscovery cuando se selecciona al usuario como custodio de datos (una persona que tiene el control administrativo de un documento o archivo electrónico) para un caso.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E5/A5/G5/E3/A3/G3, Office 365 E5/A5/G5/E3/A3/G3 proporcionan los derechos para que un usuario se beneficie de la exhibición electrónica principal.

Microsoft 365 E5/A5/G5, cumplimiento de Microsoft 365 E5/A5/G5, exhibición y auditoría electrónica Microsoft 365 E5/A5/G5, y Office 365 E5/A5/G5 proporcionan los derechos para que un usuario se beneficie de Advanced eDiscovery.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

De forma predeterminada, Advanced eDiscovery características están habilitadas en el nivel de inquilino para todos los usuarios dentro del inquilino cuando los administradores asignan permisos de exhibición de documentos electrónicos en el &amp; Centro de cumplimiento de seguridad.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los administradores de exhibición de documentos electrónicos pueden seleccionar usuarios específicos como custodios de datos para un caso mediante la herramienta de administración de custodios integrada en Advanced eDiscovery como se describe en [Agregar custodios a un caso de Advanced eDiscovery.](/microsoft-365/compliance/add-custodians-to-case)

## <a name="customer-key-for-microsoft-365"></a>Clave de cliente para Microsoft 365

Con Customer Key, controlará las claves de cifrado de su organización y configurará Microsoft 365 para usarlas para cifrar los datos en reposo en los centros de datos de Microsoft. En otras palabras, Customer Key le permite agregar una capa de cifrado que le pertenece, utilizando sus propias claves. Los datos en reposo incluyen datos de Exchange Online y Skype Empresarial que se almacenan en buzones y archivos dentro de SharePoint en línea y OneDrive para la Empresa.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician de customer key al tener sus datos en reposo cifrados en la capa de aplicación mediante claves de cifrado proporcionadas, controladas y administradas por su propia organización.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E5/A5/G5, cumplimiento de Microsoft 365 E5/A5/G5, protección y gobernanza de la información Microsoft 365 E5/A5/G5 y Office 365 E5/A5/G5 proporcionan los derechos para que un usuario se beneficie de la Clave del Cliente. Para obtener la ventaja completa de Customer Key, también debe tener una suscripción para Azure Key Vault.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

La clave de cliente para Microsoft 365 claves de cifrado se puede habilitar para todos los datos almacenados en buzones de Exchange Online y Skype Empresarial, y SharePoint archivos en línea, OneDrive para la Empresa y Teams. Para obtener más información acerca de la clave de cliente, incluida la forma de empezar, consulte [Cifrado de servicio con clave de cliente](/microsoft-365/compliance/customer-key-overview).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Para Exchange Online y Skype Empresarial, los buzones se pueden cifrar mediante la clave de cliente. Debe configurar Azure para poder usar la clave de cliente para Microsoft 365. Consulte [Configurar clave de cliente](/microsoft-365/compliance/customer-key-set-up) para ver los pasos que debe seguir para crear y configurar los recursos de Azure necesarios y los pasos para configurar la clave de cliente en Microsoft 365. Después de completar la instalación de Azure, determine qué directiva y, por lo tanto, qué claves asignar a los buzones y archivos de la organización. Para obtener más información acerca de la clave del cliente y el contenido relacionado con los datos de Exchange Online, Skype Empresarial, SharePoint en línea, OneDrive para la Empresa y Teams, consulte [Cifrado de servicio con clave de cliente](/microsoft-365/compliance/customer-key-overview).

## <a name="office-365-customer-lockbox"></a>Caja de seguridad del cliente de Office 365

Customer Lockbox proporciona una capa adicional de control al ofrecer a los clientes la capacidad de conceder autorización de acceso explícito para las operaciones de servicio. Al demostrar que existen procedimientos para la autorización explícita de acceso a datos, Customer Lockbox también puede ayudar a las organizaciones a cumplir con ciertas obligaciones de cumplimiento como HIPAA y FedRAMP.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Customer Lockbox garantiza que nadie en Microsoft pueda acceder al contenido del cliente para realizar una operación de servicio sin la aprobación explícita del cliente. Customer Lockbox lleva al cliente al flujo de trabajo de aprobación para que las solicitudes accedan a su contenido. En ocasiones, los ingenieros de Microsoft participan durante el proceso de soporte técnico para solucionar problemas notificados por el cliente y solucionar problemas notificados por el cliente. En la mayoría de los casos, los problemas se corrigen a través de amplias herramientas de telemetría y depuración que Microsoft tiene en su lugar para sus servicios. Sin embargo, puede haber casos que requieren que un ingeniero de Microsoft acceda al contenido del cliente para determinar la causa raíz y solucionar el problema. La Caja de seguridad del cliente requiere que el ingeniero solicite acceso al cliente como un último paso en el flujo de trabajo de aprobación. Esto ofrece a las organizaciones la opción de aprobar o denegar estas solicitudes, lo que les da control directo sobre si un ingeniero de Microsoft puede tener acceso a los datos del usuario final de las organizaciones.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, cumplimiento de Microsoft 365 E5/A5/G5 y gestión de riesgos internos Microsoft 365 E5/A5/G5 proporcionan los derechos para que un usuario se beneficie de Customer Lockbox.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

Los administradores pueden activar el cuadro de bloqueo de cliente en el centro de administración de Microsoft 365. Para obtener más información, consulte [Customer Lockbox en Office 365](/microsoft-365/compliance/customer-lockbox-requests). Cuando el lockbox del cliente está activado, Microsoft debe obtener la aprobación de una organización antes de acceder a cualquiera de sus contenidos.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Actualmente, el servicio Customer Lockbox no se puede limitar a usuarios específicos. Debe licenciar a todos los usuarios a los que tenga la intención de beneficiarse.

## <a name="privileged-access-management-in-office-365"></a>Administración de acceso privilegiado en Office 365

[La administración de acceso con privilegios (PAM)](/microsoft-365/compliance/privileged-access-management-configuration) proporciona un control de acceso granular sobre las tareas de administración con privilegios en Office 365. Después de habilitar PAM, para completar tareas elevadas y con privilegios, los usuarios tendrán que solicitar acceso just-in-time a través de un flujo de trabajo de aprobación de gran alcance y con límite de tiempo.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Habilitar PAM permite a las organizaciones operar con privilegios de cero posiciones. Los usuarios se benefician de la capa adicional de defensa contra vulnerabilidades derivadas del acceso administrativo permanente que proporciona acceso sin restricciones a sus datos.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio? 

Office 365 E5/A5, Microsoft 365 E5/A5, cumplimiento Microsoft 365 E5/A5 y Microsoft 365 E5/A5 Information Protection and Governance proporcionan los derechos para que un usuario se beneficie de PAM.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

De forma predeterminada, las características PAM están habilitadas en el nivel de inquilino para todos los usuarios dentro del inquilino. Para obtener información sobre cómo configurar directivas PAM, consulte [Introducción a la administración de acceso con privilegios.](/microsoft-365/compliance/privileged-access-management-configuration)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los clientes pueden administrar PAM por usuario a través del grupo aprobador y las directivas de acceso, que se pueden aplicar a los usuarios con licencia. Para obtener más información, consulte [Administración de acceso con privilegios en Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751).

## <a name="double-key-encryption-for-microsoft-365"></a>Cifrado de doble clave para Microsoft 365 

El cifrado de doble clave para Microsoft 365 le permite proteger sus datos altamente confidenciales para satisfacer requisitos especializados y mantener el control total de su clave de cifrado. Double Key Encryption utiliza dos claves para proteger los datos, con una clave en el control y la segunda clave almacenada de forma segura por Microsoft Azure. Para ver los datos, debe tener acceso a ambas claves. Dado que Microsoft solo puede acceder a una clave, la clave y también los datos no están disponibles para Microsoft, lo que garantiza que tenga control total sobre la privacidad y la seguridad de los datos.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician del cifrado de doble clave al poder migrar sus datos cifrados a la nube, lo que impide el acceso de terceros siempre y cuando la clave permanezca en control de los usuarios. Los usuarios pueden proteger y consumir contenido cifrado de doble clave similar a cualquier otro contenido protegido por etiquetas de sensibilidad.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E5/A5/G5, cumplimiento de Microsoft 365 E5/A5/G5, protección y gobernanza de la información Microsoft 365 E5/A5/G5 y Office 365 E5/A5/G5 proporcionan los derechos para que un usuario se beneficie del cifrado de doble clave.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

El cifrado de doble clave es compatible con la versión de escritorio de Microsoft Office para Windows.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Para asignar claves de cifrado a los datos dentro de una organización Office 365 y/o Microsoft 365 para usuarios con licencia, siga las instrucciones de implementación de cifrado de doble clave.

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Office 365 prevención de pérdida de datos para Exchange Online, SharePoint en línea y OneDrive para la Empresa

Con Office 365 prevención de pérdida de datos (DLP) para Exchange Online, SharePoint en línea y OneDrive para la Empresa, las organizaciones pueden identificar, supervisar y proteger automáticamente la información confidencial entre correos electrónicos y archivos (incluidos los archivos almacenados en repositorios de archivos Microsoft Teams).

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician de DLP para Exchange Online, SharePoint en línea y OneDrive para la Empresa cuando sus correos electrónicos y archivos están siendo inspeccionados para obtener información confidencial, según lo configurado en la directiva DLP de la organización.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E3/A3/Business Premium, Office 365 E3/A3 y Office 365 Data Loss Prevention proporcionan los derechos para que un usuario se beneficie de Office 365 DLP para Exchange Online, SharePoint en línea y OneDrive para la Empresa.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

De forma predeterminada, Exchange Online correos electrónicos, sitios de SharePoint y cuentas de OneDrive están *habilitadas ubicaciones (cargas de trabajo)* para estas características de DLP para todos los usuarios dentro del inquilino. Para obtener más información sobre el uso [de directivas](/microsoft-365/compliance/data-loss-prevention-policies)DLP, consulte Información general sobre la prevención de pérdida de datos .

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los administradores pueden personalizar ubicaciones (cargas de trabajo), usuarios incluidos y usuarios excluidos en el &amp; Centro de cumplimiento de seguridad, en Ubicaciones de prevención de pérdida de   >  **datos.**

## <a name="communication-data-loss-prevention-for-teams"></a>Prevención de pérdida de datos de comunicación para Teams

Con la Comunicación DLP para Teams, las organizaciones pueden bloquear chats y mensajes de canal que contienen información confidencial, como información financiera, información de identificación personal, información relacionada con la salud u otra información confidencial.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5 y Microsoft 365 E5/A5/G5 Information Protection and Governance pueden beneficiarse de la Comunicación DLP para Teams.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los remitentes se benefician al tener información confidencial en sus mensajes de chat y canal salientes inspeccionados en busca de información confidencial, según lo configurado en la directiva DLP de la organización.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

De forma predeterminada, Teams mensajes de chat y canal son una *ubicación habilitada (carga de trabajo)* para estas características DLP para todos los usuarios dentro del inquilino. Para obtener más información sobre el uso [de directivas](/office365/securitycompliance/data-loss-prevention-policies)DLP, consulte Información general sobre la prevención de pérdida de datos .

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los administradores pueden personalizar ubicaciones (cargas de trabajo), usuarios incluidos y usuarios excluidos en el &amp; Centro de cumplimiento de seguridad, en Ubicaciones de prevención de pérdida de   >  **datos.**

## <a name="information-barriers"></a>Barreras de información

Las barreras de información son directivas que un administrador puede configurar para evitar que individuos o grupos se comuniquen entre sí. Esto es útil si, por ejemplo, un departamento controla información que no debe compartirse con otros departamentos, o se debe impedir que un grupo se comunique con contactos externos. Las directivas de barrera de información también impiden búsquedas y descubrimientos. Esto significa que si intenta comunicarse con alguien con quien no debe comunicarse, no encontrará a ese usuario en el selector de personas.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician de las capacidades avanzadas de cumplimiento de las barreras de información cuando se les restringe la comunicación con otros usuarios. Las directivas de barreras de información se pueden definir para evitar que determinado segmento de usuarios se comunique con cada uno o permitir que segmentos específicos se comuniquen solo con otros segmentos. Para obtener más información sobre cómo definir directivas de barrera de información, consulte [Definir directivas de barrera de información.](/microsoft-365/compliance/information-barriers-policies) Para escenarios en los que dos grupos no pueden comunicarse entre sí, los usuarios de ambos grupos requieren una licencia para beneficiarse del servicio (véase el ejemplo siguiente).<br><br>

| Escenario | Quién requiere una licencia? |
|:------|:------|
| Dos grupos (Grupo &nbsp; 1 y Grupo &nbsp; 2) no pueden comunicarse entre sí (es decir, los usuarios del Grupo &nbsp; 1 tienen restringido la comunicación con los usuarios del Grupo &nbsp; 2 y los usuarios del Grupo &nbsp; 2 tienen restringido la comunicación con los usuarios del Grupo &nbsp; 1. | Usuarios tanto del Grupo 1 como &nbsp; del Grupo &nbsp; 2 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E5/A5/G5, cumplimiento de Microsoft 365 E5/A5/G5, gestión de riesgos internos Microsoft 365 E5/A5/G5 y Office 365 E5/A5/G5, proporcionan los derechos para que un usuario se beneficie de las barreras de información.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

Los administradores crean y administran directivas de barrera de información mediante cmdlets de PowerShell en el &amp; Centro de cumplimiento de seguridad. A los administradores se les debe asignar el Microsoft 365 Enterprise administrador global, Office 365 administrador global o el rol de administrador de cumplimiento para crear una directiva de barrera de información. De forma predeterminada, estas directivas se aplican a todos los usuarios del inquilino. Para obtener más información acerca de las barreras de información, consulte [Barreras de información en Microsoft Teams](/MicrosoftTeams/information-barriers-in-teams).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los administradores pueden personalizar ubicaciones (cargas de trabajo), usuarios incluidos y usuarios excluidos en el &amp; Centro de cumplimiento de seguridad. Por ejemplo, si todos los usuarios tienen licencia para Office 365 E3 y ninguno tiene licencia para Cumplimiento avanzado de Office 365/E5, no necesitaría crear ninguna directiva de barrera de información para la organización. Para más información, vea [Barreras de información en Microsoft Teams](/MicrosoftTeams/information-barriers-in-teams).

## <a name="office-365-message-encryption"></a>Cifrado de mensajes de Office 365

El cifrado de mensajes de Office 365 (OME) es un servicio basado en Azure Rights Management (Azure RMS) que permite enviar correo electrónico cifrado a otras personas dentro o fuera de la organización, independientemente de la dirección de correo electrónico de destino (Gmail, Yahoo! Mail, Outlook.com, etc.).

Para ver los mensajes cifrados, los destinatarios pueden obtener un código de acceso único, iniciar sesión con una cuenta de Microsoft, o iniciar sesión con una cuenta profesional o educativa asociada a Office 365. Los destinatarios también pueden enviar respuestas cifradas. No necesitan una suscripción para ver mensajes cifrados o enviar respuestas cifradas.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los remitentes de mensajes se benefician del control adicional sobre los correos electrónicos confidenciales proporcionados por Cifrado de mensajes de Office 365.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E3/A3/G3, Office 365 E3/A3/G3 y Azure Information Protection Plan 1 proporcionan los derechos para que un usuario se beneficie de Cifrado de mensajes de Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

Los administradores crean y administran directivas de Cifrado de mensajes de Office 365 en el centro de administración de Exchange en Reglas **de flujo de correo.**  >   De forma predeterminada, estas reglas se aplican a todos los usuarios del inquilino. Para obtener más información acerca de cómo configurar nuevas capacidades de Cifrado de mensajes de Office 365, consulte [Configurar nuevas capacidades de cifrado de mensajes.](/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los administradores deben aplicar reglas de flujo de correo para Cifrado de mensajes de Office 365 solo a usuarios con licencia. Para obtener más información acerca de cómo definir reglas de flujo de correo, vea [Definir reglas de flujo de correo para cifrar mensajes de correo electrónico.](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="office-365-advanced-message-encryption"></a>Cifrado de mensajes avanzado de Office 365

Cifrado de mensajes avanzado de Office 365 ayuda a los clientes a cumplir con las obligaciones de cumplimiento que requieren controles más flexibles sobre los destinatarios externos y su acceso a correos electrónicos cifrados. Con el cifrado de mensajes avanzados, los administradores pueden controlar los correos electrónicos confidenciales compartidos fuera de la organización mediante directivas automáticas que pueden detectar tipos de información confidencial (por ejemplo, información de identificación personal o identificadores financieros o de estado), o pueden usar palabras clave para mejorar la protección mediante la aplicación de plantillas de correo electrónico personalizadas y el acceso de expiración a correos electrónicos cifrados a través de un portal web seguro. Además, los administradores pueden controlar aún más los correos electrónicos cifrados a los que se accede externamente a través de un portal web seguro mediante la revocación del acceso en cualquier momento.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los remitentes de mensajes se benefician del control adicional sobre los correos electrónicos confidenciales proporcionados por el cifrado de mensajes avanzados.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, cumplimiento de Microsoft 365 E5/A5/G5 y Microsoft 365 E5/A5/G5 Information Protection and Governance proporcionan los derechos para que un usuario se beneficie del cifrado avanzado de mensajes.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

Los administradores crean y administran directivas avanzadas de cifrado de mensajes en el centro de administración de Exchange en Reglas **de flujo de correo.**  >   De forma predeterminada, estas reglas se aplican a todos los usuarios del inquilino. Para obtener más información acerca de cómo configurar nuevas capacidades de cifrado de mensajes, consulte [Configurar nuevas capacidades de Cifrado de mensajes de Office 365.](/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los administradores deben aplicar reglas de flujo de correo para el cifrado de mensajes avanzados solo a los usuarios con licencia. Para obtener más información acerca de cómo definir reglas de flujo de correo, vea [Definir reglas de flujo de correo para cifrar mensajes de correo electrónico en Office 365](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="communication-compliance"></a>Cumplimiento de la comunicación

El cumplimiento de la comunicación en Microsoft 365 ayuda a minimizar los riesgos de comunicación al ayudarle a detectar, capturar y tomar medidas de corrección para mensajes inapropiados en su organización. Puede definir directivas específicas que capturen comunicaciones internas y externas de correo electrónico, Microsoft Teams o de terceros en su organización. Los revisores pueden realizar las acciones de corrección adecuadas para asegurarse de que cumplen con los estándares de mensajes de su organización.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los especialistas en cumplimiento se benefician del servicio al tener comunicaciones de la organización supervisadas por las directivas de cumplimiento de la comunicación.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, cumplimiento de Microsoft 365 E5/A5/G5 y gestión de riesgos internos Microsoft 365 E5/A5/G5 proporcionan los derechos para que un usuario se beneficie del cumplimiento de la comunicación.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

Los administradores y especialistas en cumplimiento crean directivas de cumplimiento de la comunicación en el centro de cumplimiento de Microsoft 365. Estas directivas definen qué comunicaciones y usuarios están sujetos a revisión en la organización, definen las condiciones personalizadas que deben cumplir las comunicaciones y especifican quién debe realizar revisiones.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Los administradores eligen usuarios o grupos específicos para incluir en una directiva de cumplimiento de comunicación. Al elegir un grupo, también pueden seleccionar usuarios específicos del grupo para excluirlos de la directiva de cumplimiento de comunicaciones. Para obtener más información acerca de las directivas de cumplimiento de comunicaciones, consulte [Introducción al cumplimiento de la comunicación en Microsoft 365](/microsoft-365/compliance/communication-compliance-configure).

## <a name="insider-risk-management"></a>Administración de riesgos de Insider

La gestión de riesgos internos es una solución en Microsoft 365 que ayuda a minimizar los riesgos internos al permitirle detectar, investigar y tomar medidas sobre actividades de riesgo en su organización.

Las directivas personalizadas le permiten detectar y tomar medidas sobre actividades maliciosas e inadvertidamente arriesgadas en su organización, incluida la escalada de casos en Microsoft Advanced eDiscovery, si es necesario. Los analistas de riesgos de su organización pueden tomar rápidamente las medidas adecuadas para asegurarse de que los usuarios cumplen con los estándares de cumplimiento de su organización.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician haciendo que sus actividades se supervisen para detectar riesgos.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E5/A5/G5, cumplimiento de Microsoft 365 E5/A5/G5 y gestión de riesgos de información privilegiada Microsoft 365 E5/A5/G5 proporcionan los derechos para que un usuario se beneficie de insider risk management.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

Las directivas de gestión de riesgos internos deben crearse en el centro de cumplimiento de Microsoft 365 y asignarse a los usuarios.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Al crear una directiva en el centro de cumplimiento de Microsoft 365, en la página **Elegir usuarios y grupos,** seleccione **Elegir usuarios o grupos** para seleccionar solo usuarios con licencia o, si todos los usuarios tienen licencia, puede activar la casilla Todos los usuarios y **grupos habilitados para correo.** Para obtener más información, consulte [Introducción a la gestión de riesgos de información privilegiada.](/microsoft-365/compliance/insider-risk-management-configure)

## <a name="conditional-access-policies"></a>Directivas de acceso condicional

El Acceso condicional es la herramienta que utiliza Azure Active Directory para reunir señales, tomar decisiones y aplicar directivas de la organización. El acceso condicional está en el corazón del control basado en identidad. Las directivas de acceso condicional, en su forma más sencilla, son instrucciones if-then. Si un usuario desea tener acceso a un recurso, debe completar una acción. Ejemplo: Un administrador de nóminas desea acceder a la aplicación de nómina y es necesario para realizar la autenticación multifactor para acceder a ella.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Enterprise Mobility + Security E3/A3, Microsoft 365 F3/E3/A3/Business Premium y Azure Active Directory Premium Plan 1 pueden beneficiarse de las directivas de acceso condicional. Los usuarios con licencia de Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft E5/G5 Security y Azure Active Directory Premium Plan 2 pueden beneficiarse de la protección de identidades (directivas de acceso condicional basadas en riesgos).

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los analistas de operaciones de seguridad y los profesionales de la seguridad se benefician al tener la capacidad de aplicar políticas organizativas a los usuarios, exigiéndoles que cumplan ciertos criterios antes de conceder acceso a contenido corporativo. Los usuarios finales se benefician al poder acceder a su trabajo donde y cuando lo elijan, al tiempo que protegen los activos de la organización.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

De forma predeterminada, las características de acceso condicional están habilitadas en el nivel de inquilino para todos los usuarios dentro del inquilino.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

Para protección de identidades y acceso condicional específicamente, un usuario debe incluirse en un grupo o agregarse a una directiva de acceso condicional. La condición de usuarios y grupos es obligatoria en una directiva de acceso condicional. En la directiva, puede seleccionar **Todos los usuarios** o usuarios y grupos específicos. Debe seleccionar solo los usuarios y grupos con licencia adecuada. Para obtener más información, consulte [Acceso condicional: Condiciones](/azure/active-directory/conditional-access/conditions).

## <a name="advanced-audit"></a>Auditoría avanzada

Advanced Audit en Microsoft 365 proporciona retención de un año de registros de auditoría para actividades de usuario y administración y proporciona la capacidad de crear directivas de retención de registros de auditoría personalizadas para administrar la retención de registros de auditoría para otros servicios de Microsoft 365. También proporciona acceso a eventos cruciales para investigaciones y acceso de alto ancho de banda a la API de actividad de administración de Office 365. Para obtener más información, consulte [Auditoría avanzada en Microsoft 365](/microsoft-365/compliance/advanced-audit).

También puede habilitar un período de retención de 10 años con una SKU de complemento. La SKU adicional será necesaria a partir de principios de 2021.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, cumplimiento de Microsoft 365 E5/A5/G5 y Microsoft 365 E5/A5/G5 eDiscovery and Audit pueden beneficiarse de la Auditoría Avanzada.

Los usuarios con licencia con auditoría avanzada y el complemento retención de registros de auditoría de 10 años pueden beneficiarse de la retención de registros de auditoría de 10 años.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician de la auditoría avanzada porque los registros de auditoría relacionados con la actividad del usuario en Microsoft 365 servicios se pueden conservar durante un año. Además, se registran eventos de auditoría de alto valor, como cuando se tiene acceso o se lee a los elementos del buzón de un usuario. Para obtener más información, consulte [Auditoría avanzada en Microsoft 365](/microsoft-365/compliance/advanced-audit).

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona/implementa el servicio?

De forma predeterminada, la auditoría avanzada está habilitada en el nivel de inquilino para todas las organizaciones que tienen una suscripción Office 365 o Microsoft 365 E5/A5/G5 y proporciona automáticamente la retención de un año de registros de auditoría para actividades (realizadas por los usuarios con la licencia adecuada) en Azure Active Directory, Exchange y SharePoint. Además, las organizaciones pueden usar directivas de retención de registros de auditoría para administrar el período de retención de los registros de auditoría generados por la actividad en otros servicios de Microsoft 365. La funcionalidad de retención de registros de auditoría de 10 años también está habilitada mediante las mismas directivas de retención. Para obtener más información, vea [administrar directivas de retención de los registros de auditoría](/microsoft-365/compliance/audit-log-retention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del inquilino con licencia para el servicio?

La retención de registros de auditoría de un año y la auditoría de eventos cruciales solo se aplican a los usuarios con la licencia adecuada. Además, los administradores pueden usar directivas de retención de registros de auditoría para especificar duraciones de retención más cortas para los registros de auditoría de usuarios específicos.

La retención de registros de auditoría de 10 años solo se aplica a los usuarios con la licencia de complemento adecuada. La SKU del complemento será necesaria a partir de principios de 2021.