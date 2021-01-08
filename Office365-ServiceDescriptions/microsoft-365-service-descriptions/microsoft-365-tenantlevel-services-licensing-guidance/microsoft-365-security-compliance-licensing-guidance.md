---
title: Guía de licencias de Microsoft 365 para el cumplimiento de & seguridad
ms.author: office365servicedesc
author: pamelaar
ms.reviewer: v-trscho
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: En este artículo se proporcionan instrucciones de licencia para el cumplimiento de Microsoft 365 para ayudar a evitar posibles interrupciones en el servicio debido al acceso sin licencia.
ms.openlocfilehash: 04ff448cd45ed81b17ed230547462c80d8c47669
ms.sourcegitcommit: bab0eaae59d5c801f88eadbd29fd0d16de387c82
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/07/2021
ms.locfileid: "49779994"
---
# <a name="microsoft-365-licensing-guidance-for-security--compliance"></a>Guía de licencias de Microsoft 365 para el cumplimiento de & seguridad

Para los fines de este artículo, un servicio de nivel de inquilino es un servicio en línea que cuando se adquiere para cualquier usuario del inquilino (independiente o como parte de los planes de &mdash; Office 365 o Microsoft 365) se activa parcial o completamente para todos los usuarios del &mdash; inquilino. Aunque algunos usuarios sin licencia técnicamente pueden tener acceso al servicio, se requiere una licencia para cualquier usuario que tenga intención de beneficiarse del servicio.

> [!NOTE]
> Algunos servicios de inquilino no son capaces actualmente de limitar las ventajas a usuarios específicos. Se deben realizar esfuerzos para limitar los beneficios del servicio a los usuarios con licencia. Esto le ayudará a evitar posibles interrupciones del servicio en su organización una vez que las capacidades de destino estén disponibles.

Para ver las opciones para que los usuarios puedan beneficiarse de las características de cumplimiento de Microsoft 365 a partir del 1 de abril de 2020, descargue la comparación detallada de licencias de cumplimiento de Microsoft 365. [(PDF)](https://www.microsoft.com/download/details.aspx?id=102403)  |  [(Excel)](https://www.microsoft.com/download/details.aspx?id=102427)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory Identity Protection es una característica del plan Azure Active Directory Premium P2 que le permite detectar posibles vulnerabilidades que afectan a las identidades de su organización, configurar respuestas automatizadas para detectar acciones sospechosas relacionadas con las identidades de su organización e investigar incidentes sospechosos y tomar las medidas adecuadas para resolverlos.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los analistas y profesionales de seguridad de SecOps se benefician de tener vistas consolidadas de usuarios marcados y eventos de riesgo basados en algoritmos de aprendizaje automático. Los usuarios finales se benefician de la protección automática proporcionada a través del acceso condicional basado en riesgos y la seguridad mejorada proporcionada al actuar en vulnerabilidades.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Los clientes con licencias E1 y E3 solo podrán acceder a la evaluación de línea base de protección de datos predeterminada. Los clientes con licencias de Office 365 E5/A5 y Microsoft 365 E5/A5 (cumplimiento, gobierno de protección de información y SKU de exhibición de documentos electrónicos y auditoría incluidos) podrán acceder a las evaluaciones predefinidas de línea base de protección de &amp; datos, RGPD, NIST 800-53 e ISO 27001. La característica de evaluación personalizada y las evaluaciones premium están reservadas para los clientes de Office 365 E5/A5 y Microsoft 365 E5/A5. Las evaluaciones premium estarán disponibles para su compra durante la primera mitad de 2021 a través de VL, CSP y WebDirect.  

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, las características de Azure AD Identity Protection están habilitadas en el nivel de inquilino para todos los usuarios del inquilino. Para obtener información sobre Azure AD Identity Protection, consulte [¿Qué es Identity Protection?](https://docs.microsoft.com/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

Los administradores pueden definir el ámbito de Azure AD Identity Protection asignando directivas de riesgo que definen el nivel de restablecimiento de contraseña y permiten el acceso solo a los usuarios con licencia. Para obtener instrucciones sobre cómo establecer el ámbito de las implementaciones de Azure AD Identity Protection, consulte Cómo configurar y habilitar [directivas de riesgo.](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy)

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory Identity Governance

Azure Active Directory Identity Governance le permite equilibrar la necesidad de seguridad y productividad de los empleados de su organización con los procesos y visibilidad adecuados. Usa la administración de derechos, revisiones de acceso, administración de identidades con privilegios y directivas de términos de uso para garantizar que las personas adecuadas tienen el acceso adecuado a los recursos adecuados.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Azure Active Directory Identity Governance aumenta la productividad de los usuarios al facilitar la solicitud de acceso a aplicaciones, grupos y Microsoft Teams en un único paquete de acceso. Los usuarios también se pueden configurar como aprobadores, sin la intervención de los administradores. Para las revisiones de acceso, los usuarios pueden revisar las pertenencias a grupos con recomendaciones inteligentes para tomar medidas en intervalos regulares.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security y Azure Active Directory Premium Plan 2 proporcionan los derechos para que un usuario se beneficie de Azure Active Directory Identity Governance.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

Las características de Gobierno de identidad de Azure AD están habilitadas en el nivel de inquilino, pero se implementan por usuario. Para obtener información acerca de Azure AD Identity Governance, consulte [¿Qué es Azure AD Identity Governance?](https://docs.microsoft.com/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

Los administradores pueden establecer el ámbito de Azure AD Identity Governance asignando paquetes de acceso, revisiones de acceso o administración de identidades con privilegios solo para usuarios con licencia. Para obtener instrucciones sobre cómo dar ámbito a las implementaciones de Azure AD Identity Governance, vea:

- [Requisitos de licencia de administración de derechos de Azure AD](https://docs.microsoft.com/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Requisitos de licencia de revisión de acceso de Azure AD](https://docs.microsoft.com/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [Requisitos de licencia para usar Privileged Identity Management](https://docs.microsoft.com/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender for Identity

Microsoft Defender for Identity (anteriormente Azure Advanced Threat Protection) es un servicio en la nube que ayuda a proteger los entornos híbridos empresariales de varios tipos de ataques cibernéticos dirigidos avanzados y amenazas internas.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los analistas y profesionales de seguridad de SecOp se benefician de la capacidad de Microsoft Defender para Identity para detectar e investigar amenazas avanzadas, identidades comprometidas y acciones malintencionadas de Insider. Los usuarios finales se benefician de que Microsoft Defender supervise sus datos para la identidad.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security y Microsoft Defender for Identity para usuarios proporcionan los derechos para beneficiarse de Microsoft Defender for Identity.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, las características de Microsoft Defender para Identidad están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre cómo configurar Azure ATP, vea Crear la instancia de [Microsoft Defender para Identidad.](https://docs.microsoft.com/defender-for-identity/install-step1)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

Microsoft Defender para servicios de identidad no es capaz actualmente de limitar las capacidades a usuarios específicos. Debe licenciar a todos los usuarios a los que desea beneficiarse.

## <a name="microsoft-defender-for-office-365"></a>Microsoft Defender para Office 365

Microsoft Defender para Office 365 (anteriormente Protección contra amenazas avanzada de Office 365) ayuda a proteger a las organizaciones contra ataques sofisticados como suplantación de identidad (phishing) y malware de día cero. Microsoft Defender para Office 365 también proporciona información útil al correlacionar señales de una amplia gama de datos para ayudar a identificar, priorizar y proporcionar recomendaciones sobre cómo abordar posibles amenazas.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Microsoft Defender para Office 365 protege a los usuarios de ataques sofisticados como suplantación de identidad (phishing) y malware de día cero. Para obtener la lista completa de los servicios proporcionados en el Plan 1 y el Plan 2, vea [Microsoft Defender para Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp)

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio? 

Los planes 1 y 2 de Microsoft Defender para Office 365, Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security y Microsoft 365 Empresa Premium proporcionan los derechos para que un usuario se beneficie de Microsoft Defender para Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, las características de Microsoft Defender para Office 365 están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre la configuración de directivas de Microsoft Defender para Office 365 para usuarios con licencia, vea [Microsoft Defender para Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp)


### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

Para ámbito de Microsoft Defender para Office 365, siga las directivas de implementación de vínculos seguros y datos adjuntos seguros:

- Para obtener información sobre cómo configurar vínculos seguros para usuarios con licencia, vea Vínculos seguros en [Microsoft Defender para Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)

- Para obtener información sobre cómo configurar datos adjuntos seguros para usuarios con licencia, vea Datos adjuntos seguros en [Microsoft Defender para Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments)

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS) es un subconjunto de Microsoft Cloud App Security, con características limitadas a Office 365 y sin seguridad adicional para aplicaciones en la nube de terceros y servicios iaaS.

OCAS ofrece a las organizaciones visibilidad de sus servicios y aplicaciones en la nube de productividad, ofrece análisis sofisticados para identificar y combatir las ciberamenazas y les permite controlar cómo viajan los datos a través de &mdash; Office 365.

Para comparar características, vea [Diferencias entre Microsoft Cloud App Security y Office 365 Cloud App Security.](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365)

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

OCAS detecta Shadow IT, proporciona protección contra amenazas en Office 365 y puede controlar qué aplicaciones tienen permiso para acceder a los datos.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Office 365 E5/A3/A5/G5 proporciona los derechos para que un usuario se beneficie de OCAS.
Para obtener más información, vea la hoja [de datos de licencias de Microsoft Cloud App Security.](https://www.aka.ms/mcaslicensing)

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, las características de OCAS están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial.

Para obtener información sobre cómo configurar el servicio, consulte [Configuración básica de Cloud App Security.](https://docs.microsoft.com/cloud-app-security/general-setup)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

Los administradores pueden establecer el ámbito de las implementaciones de OCAS para exigir el acceso a determinadas aplicaciones y limitar los grupos de usuarios supervisados por Office 365 Cloud App Security. Para obtener más información, vea [Implementación con ámbito.](https://docs.microsoft.com/cloud-app-security/scoped-deployment)

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) es una solución de Agente de seguridad de acceso a la nube (CASB) que ofrece a las organizaciones visibilidad de sus servicios y aplicaciones en la nube, proporciona análisis sofisticados para identificar y combatir las ciberamenazas y les permite controlar cómo viajan los datos a través de cualquier aplicación en la &mdash; nube.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

MCAS detecta y evalúa Shadow IT, proporciona protección contra amenazas en aplicaciones en la nube de primera y de terceros, y protege la información en aplicaciones en la nube de primera y de terceros.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

MCAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security, Microsoft 365 E5/A5/G5 Compliance, and Microsoft 365 Information Protection and Governance provide the rights for a user to benefit from MCAS.

Azure AD P1 proporciona los derechos para que un usuario se beneficie de las funcionalidades de detección en MCAS.

Para beneficiarse de las capacidades de control de aplicaciones de acceso condicional en MCAS, los usuarios también deben tener licencia para Azure Active Directory P1, que se incluye en Enterprise Mobility + Security E3/A3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5 y Microsoft 365 E5/A5/G5 Security.

Para beneficiarse del etiquetado automático, los usuarios deben tener una licencia para Azure Information Protection P2, que se incluye en Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance y Microsoft 365 Information Protection and Governance.

Para obtener más información, vea la hoja [de datos de licencias de Microsoft Cloud App Security.](https://www.aka.ms/mcaslicensing)

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, las características de MCAS están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial.

Para obtener información sobre cómo configurar las directivas de Microsoft Cloud App Security para los usuarios con licencia, consulte Introducción a [Microsoft Cloud App Security.](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

Los administradores pueden establecer el ámbito de las implementaciones de MCAS para los usuarios con licencia mediante las capacidades de implementación con ámbito disponibles en el servicio. Para obtener más información, vea [Implementación con ámbito.](https://docs.microsoft.com/cloud-app-security/scoped-deployment)

## <a name="compliance-manager"></a>Administrador de cumplimiento

Simplificar el cumplimiento y reducir los riesgos con el Administrador de cumplimiento. El Administrador de cumplimiento ayuda a las organizaciones a cumplir los requisitos de normativas, estándares, directivas de la empresa u otros marcos de control deseados.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

A continuación se incluyen las ventajas para los usuarios del servicio administrador de cumplimiento:

- Traduce normativas, estándares, directivas de empresa u otros marcos de control deseados a lenguaje sencillo
- Proporciona acceso a una amplia biblioteca de evaluaciones rápidas y evaluaciones personalizadas para satisfacer las necesidades de cumplimiento únicas.
- Asigna controles reglamentarios a acciones de mejora recomendadas
- Proporciona instrucciones paso a paso sobre cómo implementar las soluciones para cumplir los requisitos normativos
- Ayuda a los usuarios a dar prioridad a las acciones que tendrán el mayor impacto en el cumplimiento de la organización mediante la asociación de una puntuación con cada acción

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Los clientes con licencias de Office 365 E5/A5 y Microsoft 365 E5/A5 podrán acceder a las evaluaciones predefinidas de línea base de protección de datos, RGPD, NIST 800-53 e ISO 27001, así como usar la característica de evaluación personalizada. Las evaluaciones premium estarán disponibles para su compra para los clientes de Office 365 E5/A5 y Microsoft 365 E5/A5 durante la primera mitad de 2021. Estarán disponibles para su compra a través de VL, CSP y WebDirect.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

El Administrador de cumplimiento se aprovisiona de forma predeterminada para su espacio empresarial. Los administradores establecen permisos de usuario y asignan roles para que los usuarios que no son administradores de su organización puedan empezar a usar el Administrador de cumplimiento. Para obtener más información, vea [Introducción al Administrador de cumplimiento: Establecer permisos de usuario y asignar roles.](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

El acceso al Administrador de cumplimiento se controla estableciendo los permisos de usuario y asignando roles. Para obtener más información, vea [Introducción al Administrador de cumplimiento: Establecer permisos de usuario y asignar roles.](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)

## <a name="microsoft-defender-for-endpoint"></a>Microsoft Defender para punto de conexión

Microsoft Defender para puntos de conexión (anteriormente ATP de Microsoft Defender) es una solución de seguridad de puntos de conexión que incluye la administración y evaluación de vulnerabilidades basadas en riesgos; capacidades de reducción de superficie de ataque; protección de próxima generación basada en comportamiento y basada en la nube; detección y respuesta de puntos de conexión (EDR); investigación y corrección automáticas; y servicios de búsqueda administrada. Consulta [la página De punto de](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) conexión de Microsoft Defender para obtener más información.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Windows 10 Enterprise E5, Windows 10 Education A5, Microsoft 365 E5 (M365 E5), que incluye Windows 10 Enterprise E5, Microsoft 365 E5 Security, Microsoft 365 A5 (M365 A5) pueden beneficiarse de Microsoft Defender para Endpoint.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los analistas y profesionales de seguridad de SecOps se benefician de las capacidades de seguridad de puntos de conexión de Microsoft Defender para Endpoint para realizar protección preventiva, detección posterior a la infracción, investigación automatizada y respuesta a amenazas avanzadas. Los usuarios finales se benefician al tener eventos malintencionados supervisados por Microsoft Defender para Endpoint.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, las características de Microsoft Defender para puntos de conexión están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre la implementación, consulte [Fases de implementación.](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/deployment-phases)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

Los administradores de Microsoft Defender para puntos de conexión pueden usar el control de acceso basado en roles (RBAC) para crear roles y grupos dentro del equipo de operaciones de seguridad para conceder acceso adecuado al Centro de seguridad de Microsoft Defender. Para obtener más información, vea [Administrar el acceso al portal mediante el control de acceso basado en roles.](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/rbac)

## <a name="information-protection"></a>Protección de la información

Information Protection ayuda a las organizaciones a descubrir, clasificar, etiquetar y proteger correos electrónicos y documentos confidenciales. Los administradores pueden definir reglas y condiciones para aplicar etiquetas automáticamente, los usuarios pueden aplicar etiquetas manualmente o se puede usar una combinación de las dos, donde los usuarios reciben recomendaciones sobre la aplicación de etiquetas.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician al tener la capacidad de aplicar manualmente etiquetas de confidencialidad a su contenido o al clasificar su contenido automáticamente.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, Office 365 E5/A5/E3/A3/F3, AIP Plan 1 y AIP Plan 2 proporcionan los derechos para que un usuario se beneficie del etiquetado manual de confidencialidad.

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, AIP Plan 1 y AIP Plan 2 proporcionan los derechos para que un usuario se beneficie de la aplicación y visualización de etiquetas de confidencialidad en Power BI y para proteger los datos cuando se exportan de Power BI a Excel, PowerPoint o PDF. 

> [!NOTE]
> Power BI se incluye con Microsoft 365 E5/A5/G5; en todos los demás planes, Power BI debe tener una licencia por separado.

Microsoft 365 E5/A5/G5, Cumplimiento de Microsoft 365 E5/A5/G5, Protección de la información de Microsoft 365 y Gobierno, Office 365 E5, Cumplimiento avanzado de Office 365, Enterprise Mobility + Security E5 y Plan 2 de AIP proporcionan los derechos para que un usuario se beneficie del etiquetado de confidencialidad automático.

Para obtener derechos específicos por licencia, consulte la comparación detallada de licencias de cumplimiento de Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx) No incluye derechos para la clasificación automática basada en aprendizaje automático (clasificadores que se pueden entrenar).

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, las características de protección de la información están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre cómo configurar directivas para usuarios con licencia, vea Activar Azure Rights Management.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

Excepto cuando se usa la característica de escáner AIP, las directivas se pueden dirigir a grupos específicos o se pueden editar usuarios y registros para evitar que los usuarios sin licencia ejecuten características de clasificación o etiquetado. Para obtener instrucciones sobre cómo definir el ámbito de las implementaciones de AIP, consulte [Configuración de la directiva de Azure Information Protection](https://docs.microsoft.com/azure/information-protection/configure-policy).

Para la característica de escáner AIP, Microsoft no se compromete a proporcionar funciones de clasificación, etiquetado o protección de archivos a los usuarios que no tienen licencia.

## <a name="information-governance"></a>Gobierno de la información

El gobierno de la información ayuda a las organizaciones a administrar sus riesgos mediante la des detectar, clasificar, etiquetar y controlar sus datos. El gobierno de la información permite a las organizaciones cumplir los requisitos normativos y empresariales, así como reducir su superficie de ataque al proporcionar capacidades de retención y eliminación en sus datos de Microsoft 365 y de terceros.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician al poder clasificar datos con fines de retención para defender directivas y normativas específicas.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Los planes de Microsoft 365 F3/Empresa Premium, Office 365 E1/A1/F3 e independientes de Exchange proporcionan los derechos para que un usuario se beneficie de la aplicación manual de etiquetas de retención sin registros a los datos del buzón.

Los planes de Microsoft 365 F3/F1/Empresa Premium, Office 365 E1/A1/F3 e independientes de SharePoint proporcionan los derechos para que un usuario se beneficie de la aplicación manual de etiquetas de retención que no son de registro a los archivos de SharePoint o OneDrive. 

Microsoft 365 E5/A5/E3/A3/Business Premium, Office 365 E5/A5/E3/A3, Exchange Plan 2 y Archivado de Exchange Online proporcionan los derechos para que un usuario se beneficie de una directiva de retención de buzones básica para toda la organización o para toda la ubicación o para aplicar manualmente un etiquetado de retención sin registros a los datos del buzón.

Microsoft 365 E5/A5/E3/A3, Office 365 E5/A5/E3/A3 y SharePoint Plan 2 proporcionan los derechos para que un usuario se beneficie de una directiva de retención básica de SharePoint o OneDrive o para aplicar manualmente una etiqueta de retención que no es de registro a los archivos de SharePoint o OneDrive.

Microsoft 365 E5/A5/E3/A3 y Office 365 E5/A5/E3/A3 proporcionan los derechos para que un usuario se beneficie de una directiva de retención de Teams.

Microsoft 365 E5/A5, Cumplimiento de Microsoft 365 E5/A5, Protección y gobierno de la información de Microsoft 365, Office 365 E5/A5, y el Cumplimiento avanzado de Office 365 proporciona los derechos para que un usuario se beneficie de aplicar automáticamente etiquetas o directivas de retención, aplicar directivas o etiquetas de retención predeterminadas, iniciar el período de retención de una etiqueta de retención basada en un evento personalizado, desencadenar una revisión manual de disposición al final del período de retención de la etiqueta, importar datos de terceros a través de conectores de datos nativos, declarar un registro a un archivo, detectar contenido etiquetado y supervisar la actividad de etiquetado.

Microsoft 365 E5/A5, Cumplimiento de Microsoft 365 E5/A5, Protección de la información de Microsoft 365 y Gobierno proporcionan los derechos para que un usuario se beneficie de aplicar automáticamente etiquetas de retención basadas en clasificadores que se pueden entrenar.

Para obtener derechos específicos por licencia, consulte la comparación detallada de licencias de cumplimiento de Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, las características de Gobierno de información están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre cómo configurar El gobierno de la información para aplicar la etiqueta automática y las directivas para los usuarios con licencia, consulte Gobierno de información de [Microsoft en Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

Las características de gobierno de la información se pueden aplicar a los usuarios con licencia en ubicaciones específicas (sitios de grupo, sitios de grupo, etc.). Para obtener información sobre cómo configurar El gobierno de la información para aplicar la etiqueta automática y las directivas para los usuarios con licencia, consulte Gobierno de información de [Microsoft en Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance)

## <a name="records-management"></a>Records Management

La administración de registros ayuda a las organizaciones a cumplir con sus obligaciones de mantenimiento de registros normativos y empresariales mediante la detección, clasificación, etiquetado, retención y eliminación de contenido a través de sus datos de Microsoft 365 y de terceros.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E5/A5, Cumplimiento de Microsoft 365 E5/A5, Protección y gobierno de la información de Microsoft 365, Office 365 E5/A5, Cumplimiento avanzado de Office 365 proporcionan los derechos para que un usuario se beneficie de la administración de registros, incluida la declaración de elementos como registros, la aplicación automática de etiquetas de retención o registro y la ejecución de procesos de revisión de eliminación (excluyendo aplicar automáticamente una etiqueta de retención basada en clasificadores que se pueden entrenar).

Microsoft 365 E5/A5, Cumplimiento de Microsoft 365 E5/A5, Protección de la información de Microsoft 365 y Gobierno proporcionan los derechos para que un usuario se beneficie de aplicar automáticamente etiquetas de retención o registro basadas en clasificadores que se pueden entrenar.

Para obtener derechos específicos por licencia, consulte la comparación detallada de licencias de cumplimiento de Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician al poder declarar el contenido como un registro y administrar su proceso de registros completos desde la definición de directiva y la declaración a través de la eliminación defensible.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, las características de administración de registros están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre cómo configurar la administración de registros para que se aplique a los usuarios con licencia, vea Más información sobre la administración de [registros en Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/records-management)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

Las características de administración de registros se pueden aplicar a los usuarios con licencia en ubicaciones específicas (sitios de grupo, sitios de grupo, etc.). Para obtener información sobre cómo configurar la administración de registros para que se aplique a los usuarios con licencia, vea Más información sobre la administración de [registros en Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/records-management)

## <a name="data-connectors"></a>Conectores de datos 

Microsoft proporciona conectores de datos de terceros que se pueden configurar en el Centro de cumplimiento de Microsoft 365. Para obtener una lista de conectores de datos proporcionados por Microsoft, consulte la [tabla conectores](https://docs.microsoft.com/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) de datos de terceros. En esta tabla también se resumen las soluciones de cumplimiento que puede aplicar a datos de terceros después de importar y archivar datos en Microsoft 365 y vínculos a las instrucciones paso a paso para cada conector.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

La principal ventaja de usar conectores de datos para importar y archivar datos de terceros en Microsoft 365 es que puede aplicar varias soluciones de cumplimiento de Microsoft 365 a los datos después de importarlos. Esto ayuda a garantizar que los datos que no son de Microsoft de su organización cumplen con las normativas y estándares que afectan a su organización.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Las siguientes licencias proporcionan los derechos para que un usuario se beneficie de los conectores de datos:

- Microsoft 365 E5/A5
- Gobernanza y protección de la información de Microsoft 365 E5/A5
- Cumplimiento de Microsoft 365 E5/A5 
- Administración de riesgos de Insider de Microsoft 365 E5/A5
- Exhibición de documentos electrónicos y auditoría de Microsoft 365 E5/A5
- Office 365 E5/A5
- Cumplimiento avanzado de Office 365

Para los conectores de datos del Centro de seguridad & de M365 proporcionados por un partner de Microsoft, la organización necesitará una relación comercial con el partner antes de poder implementar dichos conectores.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

Los conectores se configuran mediante el Centro de & cumplimiento y el Catálogo de conectores.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

Los servicios de conectores de datos son un valor de nivel de inquilino. Todos los usuarios destinados a beneficiarse de este servicio deben tener una licencia.

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp"></a>API de Microsoft Graph para la prevención de pérdida de datos (DLP) de Teams

A principios de este año anunciamos la versión preliminar pública de la API de notificación de cambios [de Microsoft Graph para los mensajes en Teams.](https://go.microsoft.com/fwlink/?linkid=2143888) Esta API permite a los desarrolladores crear aplicaciones que puedan escuchar mensajes de Microsoft Teams en tiempo casi real y habilitar implementaciones de escenario DLP para clientes e ISV. Además, la API de revisión de Microsoft Graph permite aplicar acciones DLP a los mensajes de Teams.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

[Las capacidades de prevención](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams) de pérdida de datos (DLP) se usan ampliamente en Microsoft Teams, especialmente a medida que las organizaciones se desplazan al trabajo remoto. Si su organización tiene DLP, ahora puede definir directivas que impidan que los usuarios compartan información confidencial en un canal o sesión de chat de Microsoft Teams.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Necesitará una de las siguientes licencias de E5 para obtener soporte técnico para la protección DLP en el chat de Teams:

- Microsoft 365 E5/A5
- Cumplimiento de Microsoft 365 E5/A5 
- Gobierno y protección de la información de Microsoft 365 E5/A5
- Office 365 E5/A5 

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

El acceso a la API se configura en el nivel de inquilino.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

La API de Microsoft Graph para DLP de Teams es un valor de nivel de inquilino. Todos los usuarios destinados a beneficiarse de este servicio deben tener una licencia.

## <a name="ediscovery"></a>eDiscovery

eDiscovery proporciona soluciones de investigación y exhibición de documentos electrónicos para departamentos legales y de TI dentro de las corporaciones para identificar, recopilar, conservar, reducir y revisar el contenido relacionado con una investigación o litigio antes de exportar fuera del sistema de Microsoft 365.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Un usuario se beneficia de la exhibición avanzada de documentos electrónicos cuando el usuario se selecciona como administrador de datos (una persona que tiene control administrativo de un documento o archivo electrónico) para un caso.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E5/A5/G5/E3/A3/G3, Office 365 E5/A5/G5/E3/A3/G3 y Cumplimiento avanzado de Office 365 proporcionan los derechos para que un usuario se beneficie de la exhibición de documentos electrónicos principal.

Microsoft 365 E5/A5/G5, Cumplimiento de Microsoft 365 E5/A5/G5, Exhibición de documentos electrónicos y auditoría de Microsoft 365 E5/A5, Office 365 E5/A5/G5 y Cumplimiento avanzado de Office 365 proporcionan los derechos para que un usuario se beneficie de eDiscovery avanzado.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, las características avanzadas de eDiscovery están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial cuando los administradores asignan permisos de exhibición de documentos electrónicos en el Centro de seguridad & cumplimiento.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

Los administradores de exhibición de documentos electrónicos pueden seleccionar usuarios específicos como administradores de datos para un caso mediante la herramienta de administración de administradores integrada en eDiscovery avanzado, tal como se describe en Agregar administradores a un caso de [eDiscovery](https://docs.microsoft.com/microsoft-365/compliance/add-custodians-to-case)avanzado.

## <a name="office-365-customer-key"></a>Clave de cliente de Office 365

Con la clave de cliente, puede controlar las claves de cifrado de su organización y configurar Office 365 para usarlas para cifrar los datos en reposo en los centros de datos de Microsoft. En otras palabras, la clave de cliente le permite agregar una capa de cifrado que le pertenece, con sus propias claves. Los datos en reposo incluyen datos de Exchange Online y Skype Empresarial que se almacenan en buzones y archivos dentro de SharePoint Online y OneDrive para la Empresa.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician de la clave de cliente al tener sus datos cifrados en reposo en el nivel de la aplicación mediante claves de cifrado proporcionadas, controladas y administradas por su propia organización.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E5/A5, Cumplimiento de Microsoft 365 E5/A5, Protección y gobierno de la información de Microsoft 365, Office 365 E5/A5 y Cumplimiento avanzado de Office 365 proporcionan los derechos para que un usuario se beneficie de la clave de cliente. Para obtener todas las ventajas de la clave de cliente, también debe tener una suscripción a Azure Key Vault.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

Las claves de cifrado de clave de cliente de Office 365 se pueden habilitar para todos los datos almacenados en buzones de Exchange Online y Skype Empresarial, y archivos de SharePoint Online, OneDrive para la Empresa y Teams. Para obtener más información acerca de la clave de cliente de Office 365, incluido cómo empezar, vea cifrado de [servicio con clave de cliente.](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

Para Exchange Online y Skype Empresarial, los buzones se pueden cifrar con la clave de cliente. Debe configurar Azure para poder usar la clave de cliente para Office 365. Consulte [Configurar la clave](https://docs.microsoft.com/microsoft-365/compliance/customer-key-set-up) de cliente para ver los pasos que debe seguir para crear y configurar los recursos de Azure necesarios y los pasos para configurar la clave de cliente en Office 365. Después de completar la configuración de Azure, determine qué directiva y, por lo tanto, qué claves asignar a buzones y archivos de su organización. Los buzones y archivos a los que no asigne una directiva usarán directivas de cifrado controladas y administradas por Microsoft. Para obtener más información acerca de la clave de cliente o para obtener información general, consulte Cifrado [de servicio con clave de cliente.](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview)

## <a name="office-365-customer-lockbox"></a>Caja de seguridad del cliente de Office 365

La Caja de seguridad del cliente proporciona un nivel adicional de control al ofrecer a los clientes la capacidad de dar autorización de acceso explícita para las operaciones de servicio. Al demostrar que hay procedimientos para la autorización explícita de acceso a datos, la Caja de seguridad del cliente también puede ayudar a las organizaciones a cumplir determinadas obligaciones de cumplimiento, como HIPAA y FEDRAMP.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

La Caja de seguridad del cliente garantiza que nadie de Microsoft pueda acceder al contenido del cliente para realizar una operación de servicio sin la aprobación explícita del cliente. La Caja de seguridad del cliente lleva al cliente al flujo de trabajo de aprobación para solicitudes de acceso a su contenido. En ocasiones, los ingenieros de Microsoft participan durante el proceso de soporte técnico para solucionar problemas notificados por el cliente. En la mayoría de los casos, los problemas se solucionan a través de extensas herramientas de telemetría y depuración que Microsoft tiene para sus servicios. Sin embargo, puede haber casos que requieran que un ingeniero de Microsoft acceda al contenido del cliente para determinar la causa raíz y solucionar el problema. Caja de seguridad del cliente requiere que el ingeniero solicite acceso al cliente como paso final en el flujo de trabajo de aprobación. Esto ofrece a las organizaciones la opción de aprobar o denegar estas solicitudes, lo que les da control directo sobre si un ingeniero de Microsoft puede acceder a los datos del usuario final de la organización.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Cumplimiento de Microsoft 365 E5/A5/G5, Administración de riesgos de Microsoft 365 Insider y Cumplimiento avanzado de Office 365 proporcionan los derechos para que un usuario se beneficie de la Caja de seguridad del cliente.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

Los administradores pueden activar la Caja de seguridad del cliente en el Centro de administración de Microsoft 365. Para obtener más información, vea [Caja de seguridad del cliente en Office 365.](https://docs.microsoft.com/microsoft-365/compliance/customer-lockbox-requests) Cuando la Caja de seguridad del cliente está activada, Microsoft debe obtener la aprobación de una organización antes de acceder a cualquiera de sus contenidos.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

Actualmente, el servicio de caja de seguridad del cliente no puede limitarse a usuarios específicos. Debe licenciar a todos los usuarios a los que desea beneficiarse.

## <a name="privileged-access-management-in-office-365"></a>Administración de acceso privilegiado en Office 365

[La administración de acceso con privilegios (PAM)](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration) proporciona control de acceso granular sobre las tareas de administración con privilegios en Office 365. Después de habilitar PAM, para completar tareas con privilegios elevados y con privilegios, los usuarios tendrán que solicitar acceso just-in-time a través de un flujo de trabajo de aprobación que tenga un ámbito alto y un límite de tiempo.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

La habilitación de PAM permite que las organizaciones funcionen sin privilegios permanentes. Los usuarios se benefician de la capa adicional de defensa contra las vulnerabilidades derivadas del acceso administrativo permanente que proporciona acceso sin límite a sus datos.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio? 

Office 365 E5/A5, Microsoft 365 E5/A5, Cumplimiento de Microsoft 365 E5/A5 y Microsoft 365 E5/A5 Information Protection and Governance proporcionan los derechos para que un usuario se beneficie de PAM.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, las características de PAM están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial. Para obtener información sobre cómo configurar directivas de PAM, consulte [Introducción a la administración de acceso con privilegios.](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

Los clientes pueden administrar PAM por usuario a través de directivas de acceso y grupo de aprobadores, que se pueden aplicar a los usuarios con licencia. Para obtener más información, vea [privileged access management in Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751).

## <a name="double-key-encryption-for-microsoft-365"></a>Cifrado de doble clave para Microsoft 365 

Cifrado de doble clave para Microsoft 365 le permite proteger los datos altamente confidenciales para cumplir requisitos especializados y mantener el control total de la clave de cifrado. El cifrado de doble clave usa dos claves para proteger los datos, con una clave en el control y la segunda clave almacenada de forma segura por Microsoft Azure. Para ver los datos, debe tener acceso a ambas teclas. Dado que Microsoft solo puede acceder a una clave, su clave y sus datos no están disponibles para Microsoft, lo que garantiza que tiene control total sobre la privacidad y seguridad de los datos.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician del cifrado de doble clave al poder migrar sus datos cifrados a la nube, lo que impide el acceso de terceros mientras la clave permanezca bajo control de los usuarios. Los usuarios pueden proteger y consumir contenido cifrado de doble clave similar a cualquier otro contenido protegido con etiqueta de confidencialidad.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E5/A5, Cumplimiento de Microsoft 365 E5/A5, Protección y gobierno de la información de Microsoft 365, Office 365 E5/A5 y Cumplimiento avanzado de Office 365 proporcionan los derechos para que un usuario se beneficie del cifrado de doble clave.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

Cifrado de doble clave admite la versión de escritorio de Microsoft Office para Windows.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

Para asignar claves de cifrado a datos de una organización de Office 365 o Microsoft 365 para usuarios con licencia, siga las instrucciones de implementación de cifrado de doble clave.

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Prevención de pérdida de datos de Office 365 para Exchange Online, SharePoint Online y OneDrive para la Empresa

Con la prevención de pérdida de datos (DLP) de Office 365 para Exchange Online, SharePoint Online y OneDrive para la Empresa, las organizaciones pueden identificar, supervisar y proteger automáticamente información confidencial entre correos electrónicos y archivos (incluidos los archivos almacenados en repositorios de archivos de Microsoft Teams).

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician de DLP para Exchange Online, SharePoint Online y OneDrive para la Empresa cuando se inspeccionan sus correos electrónicos y archivos en busca de información confidencial, tal como se configura en la directiva DLP de la organización.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

La prevención de pérdida de datos de Microsoft 365 A1/E3/A3/Business, Office 365 E3/A3 y Office 365 proporciona los derechos para que un usuario se beneficie de DLP de Office 365 para Exchange Online, SharePoint Online y OneDrive para la Empresa.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, los correos electrónicos de Exchange Online, los sitios de SharePoint y las cuentas de OneDrive son ubicaciones *habilitadas (cargas* de trabajo) para estas características dlp para todos los usuarios del espacio empresarial. Para obtener más información acerca del uso de directivas DLP, vea [Información general sobre la prevención de pérdida de datos.](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

Los administradores pueden personalizar ubicaciones (cargas de trabajo), usuarios incluidos y usuarios excluidos en el Centro de seguridad & Cumplimiento, en Ubicaciones de prevención de pérdida **de**  >  **datos.**

## <a name="communication-data-loss-prevention-for-teams"></a>Prevención de pérdida de datos de comunicación para Teams

Con DLP de comunicación para Teams, las organizaciones pueden bloquear chats y mensajes de canal que contienen información confidencial, como información financiera, información de identificación personal, información relacionada con el estado u otra información confidencial.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Office 365 E5/A5, Microsoft 365 E5/A5, Protección y gobierno de la información de Microsoft 365 y Cumplimiento avanzado de Office 365 pueden beneficiarse de DLP de comunicación para Teams.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los remitentes se benefician al tener información confidencial en los mensajes de chat y canal salientes inspeccionados para obtener información confidencial, tal como se configura en la directiva DLP de la organización.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, los mensajes de canal y chat de Teams son una ubicación *habilitada (carga* de trabajo) para estas características dlp para todos los usuarios del espacio empresarial. Para obtener más información acerca del uso de directivas DLP, vea [Información general sobre la prevención de pérdida de datos.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

Los administradores pueden personalizar ubicaciones (cargas de trabajo), usuarios incluidos y usuarios excluidos en el Centro de seguridad & Cumplimiento, en Ubicaciones de prevención de pérdida **de**  >  **datos.**

## <a name="information-barriers"></a>Barreras de información

Las barreras de información son directivas que un administrador puede configurar para impedir que personas o grupos se comuniquen entre sí. Esto resulta útil si, por ejemplo, un departamento administra información que no se debe compartir con otros departamentos o si es necesario impedir que un grupo se comunique con contactos externos. Las directivas de barreras de información también impiden búsquedas y detección. Esto significa que si intenta comunicarse con alguien con quien no debería comunicarse, no encontrará ese usuario en el selector de personas.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician de las capacidades avanzadas de cumplimiento de las barreras de información cuando tienen restricciones para comunicarse con otras personas. Por ejemplo:<br><br>

| Escenario | ¿Quién necesita una licencia? |
|:------|:------|:------|
| Dos grupos (grupo 1 y grupo 2) no se pueden comunicar entre sí (es decir, los usuarios del grupo 1 tienen restricciones para comunicarse con los usuarios del grupo 2 y los usuarios del grupo 2 tienen restricciones para comunicarse con los usuarios del grupo &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 1. | Usuarios del grupo &nbsp; 1 y del &nbsp; grupo 2 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E5/A5, Cumplimiento de Microsoft 365 E5/A5, Administración de riesgos de Microsoft 365 Insider, Office 365 E5/A5 y Cumplimiento avanzado de Office 365 proporcionan los derechos para que un usuario se beneficie de las barreras de información.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

Los administradores crean y administran directivas de barreras de información mediante cmdlets de PowerShell en el Centro de & cumplimiento. Los administradores deben tener asignado el rol de administrador global de Microsoft 365 Enterprise, administrador global de Office 365 o administrador de cumplimiento para crear una directiva de barreras de información. De forma predeterminada, estas directivas se aplican a todos los usuarios del espacio empresarial. Para obtener más información acerca de las barreras de información, vea [Barreras de información en Microsoft Teams.](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

Los administradores pueden personalizar ubicaciones (cargas de trabajo), usuarios incluidos y usuarios excluidos en el Centro de & cumplimiento. Por ejemplo, si todos los usuarios tienen licencia para Office 365 E3 y ninguno tiene licencia para Cumplimiento avanzado de Office 365/E5, no necesitarán crear directivas de barreras de información para la organización. Para obtener más información, vea [Barreras de información en Microsoft Teams.](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)

## <a name="office-365-message-encryption"></a>Cifrado de mensajes de Office 365

El cifrado de mensajes de Office 365 (OME) es un servicio basado en Azure Rights Management (Azure RMS) que permite enviar correo electrónico cifrado a otras personas dentro o fuera de la organización, independientemente de la dirección de correo electrónico de destino (Gmail, Yahoo! Mail, Outlook.com, etc.).

Para ver los mensajes cifrados, los destinatarios pueden obtener un código de acceso único, iniciar sesión con una cuenta de Microsoft, o iniciar sesión con una cuenta profesional o educativa asociada a Office 365. Los destinatarios también pueden enviar respuestas cifradas. No necesitan una suscripción para ver mensajes cifrados o enviar respuestas cifradas.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los remitentes de mensajes se benefician del control agregado sobre los correos electrónicos confidenciales proporcionados por el cifrado de mensajes de Office 365.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Microsoft 365 E3/A3, Office 365 E3/A3 y Azure Information Protection Plan 1 proporcionan los derechos para que un usuario se beneficie del cifrado de mensajes de Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

Los administradores crean y administran directivas de cifrado de mensajes de Office 365 en el Centro de administración de Exchange en **Reglas de flujo de**  >  **correo.** De forma predeterminada, estas reglas se aplican a todos los usuarios del espacio empresarial. Para obtener más información acerca de cómo configurar nuevas capacidades de cifrado de mensajes de Office 365, vea [Configurar nuevas capacidades de cifrado de mensajes.](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

Los administradores deben aplicar reglas de flujo de correo para el cifrado de mensajes de Office 365 solo a los usuarios con licencia. Para obtener más información acerca de la definición de reglas de flujo de correo, vea [Definir reglas de flujo de correo para cifrar mensajes de correo electrónico.](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="office-365-advanced-message-encryption"></a>Cifrado de mensajes avanzado de Office 365

El cifrado avanzado de mensajes de Office 365 ayuda a los clientes a cumplir las obligaciones de cumplimiento que requieren controles más flexibles sobre los destinatarios externos y su acceso a los correos electrónicos cifrados. Con el cifrado avanzado de mensajes, los administradores pueden controlar los correos electrónicos confidenciales compartidos fuera de la organización mediante directivas automáticas que pueden detectar tipos de información confidencial (por ejemplo, identificación personal o identificadores financieros o de estado), o pueden usar palabras clave para mejorar la protección aplicando plantillas de correo electrónico personalizadas y expirando el acceso a los correos electrónicos cifrados a través de un portal web seguro. Además, los administradores pueden controlar aún más los correos electrónicos cifrados a los que se accede externamente a través de un portal web seguro al revocar el acceso en cualquier momento.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los remitentes de mensajes se benefician del control agregado sobre los correos electrónicos confidenciales proporcionados por el cifrado avanzado de mensajes.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Office 365 E5/A5, Microsoft 365 E5/A5, Cumplimiento de Microsoft 365 E5/A5, Protección y gobierno de la información de Microsoft 365 y Cumplimiento avanzado de Office 365 proporcionan los derechos para que un usuario se beneficie del cifrado avanzado de mensajes.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

Los administradores crean y administran directivas de cifrado de mensajes avanzado en el Centro de administración de Exchange en **Reglas de flujo de**  >  **correo.** De forma predeterminada, estas reglas se aplican a todos los usuarios del espacio empresarial. Para obtener más información acerca de cómo configurar nuevas capacidades de cifrado de mensajes, vea Configurar nuevas capacidades de cifrado de [mensajes de Office 365.](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

Los administradores deben aplicar reglas de flujo de correo para el cifrado avanzado de mensajes solo a los usuarios con licencia. Para obtener más información acerca de la definición de reglas de flujo de correo, vea Definir reglas de flujo de correo para cifrar mensajes de correo [electrónico en Office 365.](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="communication-compliance"></a>Cumplimiento de la comunicación

El cumplimiento de las comunicaciones en Microsoft 365 ayuda a minimizar los riesgos de comunicación al ayudarle a detectar, capturar y tomar medidas correctivas para mensajes inapropiados en su organización. Puede definir directivas específicas que capturen correo electrónico interno y externo, Microsoft Teams o comunicaciones de terceros en su organización. Los revisores pueden tomar las medidas correctivas adecuadas para asegurarse de que cumplen con los estándares de mensajes de su organización.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los especialistas en cumplimiento se benefician del servicio al hacer que las comunicaciones de la organización se supervisen mediante directivas de cumplimiento de comunicaciones.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

Office 365 E5/A5, Microsoft 365 E5/A5, Cumplimiento de Microsoft 365 E5/A5 y Administración de riesgos de Microsoft 365 Insider proporcionan los derechos para que un usuario se beneficie del cumplimiento de las comunicaciones.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

Los administradores y especialistas en cumplimiento crean directivas de cumplimiento de comunicaciones en el Centro de cumplimiento de Microsoft 365. Estas directivas definen qué comunicaciones y usuarios están sujetos a revisión en la organización, definen condiciones personalizadas que deben cumplir las comunicaciones y especifican quién debe realizar revisiones.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

Los administradores eligen usuarios o grupos específicos para incluir en una directiva de cumplimiento de comunicaciones. Al elegir un grupo, también pueden seleccionar usuarios específicos del grupo para excluirlos de la directiva de cumplimiento de comunicaciones. Para obtener más información acerca de las directivas de cumplimiento de comunicaciones, vea Introducción al [cumplimiento de comunicaciones en Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/communication-compliance-configure)

## <a name="insider-risk-management"></a>Administración de riesgos de Insider

La administración de riesgos internos es una solución de Microsoft 365 que ayuda a minimizar los riesgos internos, ya que le permite detectar, investigar y tomar medidas en actividades de riesgo de su organización.

Las directivas personalizadas le permiten detectar y tomar medidas en actividades malintencionadas y de riesgo involuntaria en su organización, incluido el escalado de casos a eDiscovery avanzado de Microsoft, si es necesario. Los analistas de riesgos de su organización pueden tomar rápidamente las medidas adecuadas para asegurarse de que los usuarios cumplen con los estándares de cumplimiento de la organización.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician de que sus actividades se supervisen en busca de riesgos.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>¿Qué licencias proporcionan los derechos para que un usuario se beneficie del servicio?

El cumplimiento de Microsoft 365 E5/A5, el cumplimiento de Microsoft 365 E5/A5 y la administración de riesgos de Microsoft 365 Insider proporcionan los derechos para que un usuario se beneficie de la Administración de riesgos de Insider.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

Las directivas de administración de riesgos de Insider deben crearse en el Centro de cumplimiento de Microsoft 365 y asignarse a los usuarios.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

Al crear una directiva en el Centro de  cumplimiento de Microsoft 365, en la página Elegir usuarios y grupos, seleccione Elegir  usuarios o grupos para seleccionar solo usuarios con licencia o, si todos los usuarios tienen licencia, puede activar la casilla Todos los usuarios y grupos habilitados para correo.  Para obtener más información, vea [Introducción a la administración de riesgos de Insider.](https://docs.microsoft.com/microsoft-365/compliance/insider-risk-management-configure)

## <a name="conditional-access-policies"></a>Directivas de acceso condicional

El acceso condicional es la herramienta usada por Azure Active Directory para unir señales, tomar decisiones y aplicar directivas organizativas. El acceso condicional es el núcleo del control controlado por identidades. Las directivas de acceso condicional, en su forma más sencilla, son instrucciones if-then. Si un usuario desea tener acceso a un recurso, debe completar una acción. Ejemplo: un administrador de nóminas desea tener acceso a la aplicación de nóminas y es necesario realizar la autenticación multifactor para tener acceso a ella.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Enterprise Mobility + Security E3/A3, Microsoft 365 F3/E3/A3/Business Premium y Azure Active Directory Premium Plan 1 pueden beneficiarse de las directivas de acceso condicional. Los usuarios con licencia de Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5, Microsoft E5 Security y Azure Active Directory Premium Plan 2 pueden beneficiarse de Identity Protection (directivas de acceso condicional basado en riesgos).

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los analistas de operaciones de seguridad y los profesionales de seguridad se benefician al tener la capacidad de aplicar directivas organizativas a los usuarios, requiriendo que cumplan ciertos criterios antes de conceder acceso al contenido corporativo. Los usuarios finales se benefician al poder acceder a su trabajo donde y cuando lo elijan, al tiempo que protegen los activos de la organización.

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, las características de acceso condicional están habilitadas en el nivel de inquilino para todos los usuarios del espacio empresarial.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

Para La protección de identidades y el acceso condicional específicamente, un usuario debe incluirse en un grupo o agregarse a una directiva de acceso condicional. La condición de usuarios y grupos es obligatoria en una directiva de acceso condicional. En la directiva, puede seleccionar Todos los usuarios **o** usuarios y grupos específicos. Debe seleccionar solo usuarios y grupos con licencia adecuada. Para obtener más información, vea [Acceso condicional: Condiciones](https://docs.microsoft.com/azure/active-directory/conditional-access/conditions).

## <a name="advanced-audit"></a>Auditoría avanzada

La auditoría avanzada de Microsoft 365 proporciona una retención de un año de registros de auditoría para actividades de usuario y administrador, y proporciona la capacidad de crear directivas de retención de registros de auditoría personalizadas para administrar la retención de registros de auditoría para otros servicios de Microsoft 365. También proporciona acceso a eventos cruciales para investigaciones y acceso de ancho de banda alto a la API de actividad de administración de Office 365. Para obtener más información, vea [Auditoría avanzada en Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)

También puedes habilitar un período de retención de 10 años con una SKU de complemento. La SKU del complemento será necesaria a partir de principios de 2021.

### <a name="which-users-benefit-from-the-service"></a>¿Qué usuarios se benefician del servicio?

Los usuarios con licencia de Office 365 E5, Microsoft 365 E5, cumplimiento de Microsoft 365 E5 y eDiscovery y auditoría de Microsoft 365 pueden beneficiarse de la auditoría avanzada.

Los usuarios con licencia con auditoría avanzada y el complemento retención de registros de auditoría de 10 años pueden beneficiarse de la retención de registros de auditoría de 10 años.

### <a name="how-do-users-benefit-from-the-service"></a>¿Cómo se benefician los usuarios del servicio?

Los usuarios se benefician de la auditoría avanzada porque los registros de auditoría relacionados con la actividad de los usuarios en los servicios de Microsoft 365 se pueden conservar hasta un año. Además, se registran eventos de auditoría de gran valor, como cuando se accede o lee a los elementos del buzón de un usuario. Para obtener más información, vea [Auditoría avanzada en Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)

### <a name="how-is-the-service-provisioneddeployed"></a>¿Cómo se aprovisiona o implementa el servicio?

De forma predeterminada, la auditoría avanzada está habilitada en el nivel de inquilino para todas las organizaciones que tienen una suscripción a Office 365 o Microsoft 365 E5 y proporciona automáticamente la retención de registros de auditoría de un año para las actividades (realizadas por usuarios con la licencia adecuada) en Azure Active Directory, Exchange y SharePoint. Además, las organizaciones pueden usar directivas de retención de registros de auditoría para administrar el período de retención de los registros de auditoría generados por la actividad en otros servicios de Microsoft 365. La funcionalidad de retención del registro de auditoría de 10 años también se habilita con las mismas directivas de retención. Para obtener más información, vea [administrar directivas de retención de los registros de auditoría](https://docs.microsoft.com/microsoft-365/compliance/audit-log-retention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>¿Cómo se puede aplicar el servicio solo a los usuarios del espacio empresarial con licencia para el servicio?

La retención de un año de los registros de auditoría y la auditoría de eventos cruciales solo se aplican a los usuarios con la licencia adecuada. Además, los administradores pueden usar directivas de retención de registros de auditoría para especificar duraciones de retención más cortas para los registros de auditoría de usuarios específicos.

La retención de registros de auditoría de 10 años solo se aplica a los usuarios con la licencia de complemento adecuada. La SKU del complemento será necesaria a partir de principios de 2021.
