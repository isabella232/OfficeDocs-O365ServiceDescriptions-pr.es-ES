---
title: Búsqueda
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- sharepoint-online-search-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cb36484c-0e8f-480e-be88-5daa8bf2d47d
description: SharePoint Online es una colección de herramientas y tecnologías basadas en Web que ayudan a su organización a almacenar, compartir y administrar información digital. Integrado en Microsoft SharePoint Server 2013, este servicio alojado es ideal para trabajar en proyectos, almacenar datos y documentos en una ubicación central, y compartir información con otros individuos. Las siguientes características de Búsqueda ayudan a los usuarios a encontrar la información que necesitan para hacer su trabajo. La Búsqueda es una combinación de relevancia, refinamiento y personas.
ms.openlocfilehash: 39fdeaac67d1c7261e93dd45c4181613910d5ed0
ms.sourcegitcommit: 05458701350d269dce45c9a0812d67d653c52621
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/25/2019
ms.locfileid: "37726206"
---
# <a name="search"></a>Búsqueda

SharePoint Online es una colección de herramientas y tecnologías basadas en Web que ayudan a su organización a almacenar, compartir y administrar información digital. Integrado en Microsoft SharePoint Server 2013, este servicio alojado es ideal para trabajar en proyectos, almacenar datos y documentos en una ubicación central, y compartir información con otros individuos. Las siguientes características de Búsqueda ayudan a los usuarios a encontrar la información que necesitan para hacer su trabajo. La Búsqueda es una combinación de relevancia, refinamiento y personas.
  
## <a name="continuous-crawls"></a>Rastreos continuos

Los rastreos continuos mantienen actualizados los resultados de la búsqueda en los sitios de SharePoint. Los rastreos continuos se habilitan desde SharePoint Online y es Microsoft quien administra las frecuencias de rastreo. En SharePoint Server 2013, los administradores pueden habilitar los rastreos continuos y administrar las frecuencias correspondientes. Obtenga más información sobre las [extensiones de nombre de archivo y los tipos de archivo analizados predeterminados en SharePoint](https://docs.microsoft.com/sharepoint/technical-reference/default-crawled-file-name-extensions-and-parsed-file-types). Obtenga más información sobre [cómo administrar los rastreos continuos](https://docs.microsoft.com/SharePoint/search/manage-continuous-crawls).
  
## <a name="deep-links"></a>Vínculos profundos

El sistema de búsqueda crea automáticamente vínculos directos a subsecciones de una página principal que recibe visitas frecuentes. Estos vínculos se denominan "vínculos profundos". Obtenga más información sobre los vínculos [Sistema de búsqueda de SharePoint](https://docs.microsoft.com/sharepoint/dev/general-development/search-in-sharepoint).
  
## <a name="event-based-relevancy"></a>Relevancia basada en eventos

El sistema de búsqueda determina la relevancia de los resultados de búsqueda en parte por cómo está conectado el contenido, con qué frecuencia aparece un elemento en los resultados de la búsqueda y qué resultados de búsqueda seleccionan los usuarios. El componente de análisis realiza un seguimiento y analiza esta información, que servirá para mejorar de forma continua la relevancia. Obtenga más información sobre el [procesamiento de análisis](https://docs.microsoft.com/SharePoint/search/overview-of-analytics-processing).
  
## <a name="expertise-search"></a>Búsqueda de habilidades profesionales

En SharePoint es más sencillo encontrar a personas con aptitudes o experiencia en determinados campos en la presentación vertical de búsqueda de personas. Los resultados de la búsqueda se basan en información, como los metadatos que los usuarios especificaron en sus sitios personales y la información del contenido que crearon. Obtenga más información sobre cómo [cambiar la configuración de la presentación vertical de búsqueda](https://docs.microsoft.com/sharepoint/search/configure-properties-of-the-search-navigation-web-part).
  
## <a name="graphical-refiners"></a>Refinadores gráficos

Los nuevos refinadores gráficos ofrecen una forma más visual de filtrar los resultados de la búsqueda. Obtenga más información sobre cómo [configurar los elementos web de refinamiento](https://support.office.com/article/About-configuring-the-Refinement-Web-Part-7cef67e8-b992-4659-b21a-ba534eea102e).
  
## <a name="hybrid-search"></a>Búsqueda híbrida

En una implementación híbrida de SharePoint, el contenido de los resultados de la búsqueda proviene tanto de SharePoint Online como de los sitios locales de SharePoint Server 2013. Para obtener más información sobre el entorno híbrido de SharePoint, vea [Entornos híbridos para SharePoint Server 2013](https://docs.microsoft.com/SharePoint/hybrid/hybrid).
  
## <a name="manage-search-schema"></a>Administrar el esquema de búsqueda

Cuando los usuarios buscan contenido en los sitios de SharePoint, el contenido del índice de búsqueda determina lo que encontrarán. El índice de búsqueda contiene información de todos los documentos y páginas en el sitio y se crea rastreando el contenido del sitio de SharePoint. El esquema de búsqueda ayuda al rastreador a decidir qué contenido y metadatos seleccionar y cómo indexarlos. Si cambia el esquema de búsqueda, podrá crear una experiencia de búsqueda personalizada para sus usuarios. Obtenga más información sobre cómo [administrar el esquema de búsqueda en SharePoint Online](https://docs.microsoft.com/sharepoint/manage-search-schema).
  
## <a name="on-hover-preview"></a>Vista previa al activar el puntero

Los usuarios pueden colocar el puntero en un resultado de la búsqueda para obtener una vista previa e interactuar con el contenido del documento o sitio en el panel flotante que aparece a la derecha de los resultados. La vista previa muestra los metadatos enriquecidos y contiene vínculos profundos a las secciones principales del documento o sitio. Obtenga más información sobre las [sugerencias de búsqueda](https://support.office.com/article/Not-getting-the-search-results-you-re-looking-for-in-SharePoint-D80687F7-1010-4E6D-ADD9-584B423289D9).
  
## <a name="phonetic-name-matching"></a>Coincidencia de nombres fonéticos

La coincidencia mejorada de nombres fonéticos encuentra resultados de la búsqueda de nombres con una fonética similar (¿es John o Jon?). Obtenga más información sobre cómo [administrar orígenes de resultados](https://docs.microsoft.com/sharepoint/manage-result-sources).
  
## <a name="query-rulesadd-promoted-results"></a>Reglas de consulta: añadir resultados promocionados

En una regla de consulta, necesita especificar las condiciones y acciones correlacionadas. Cuando una consulta cumple las condiciones de una regla de consulta, el sistema de búsqueda realiza las acciones especificadas en la regla. La acción "Agregar resultados promovidos" le permite promover resultados individuales para que aparezcan en la parte superior de los resultados de la búsqueda. Obtenga más información sobre cómo [administrar reglas de consulta](https://docs.microsoft.com/SharePoint/search/manage-query-rules).
  
## <a name="query-rulesadvanced-actions"></a>Reglas de consulta: acciones avanzadas

En una regla de consulta, puede especificar las condiciones y acciones correlacionadas. La acción "Agregar bloques de resultados" permite mostrar un subconjunto de los resultados de la búsqueda como grupo. La acción "Cambiar resultados clasificados cambiando la consulta" le permite cambiar la clasificación de los resultados de la búsqueda encontrados. Obtenga más información sobre cómo [administrar reglas de consulta](https://docs.microsoft.com/SharePoint/search/manage-query-rules).
  
## <a name="query-spelling-correction"></a>Corrección ortográfica de la consulta

Edite las listas de exclusiones e inclusiones para seleccionar las consultas que quiere que se muestren en la página de resultados con una ortografía de consulta alternativa. Esta característica a menudo se denomina "¿Quiso decir?". Obtenga más información sobre la [corrección ortográfica de consultas](https://docs.microsoft.com/sharepoint/search/manage-query-spelling-correction).
  
## <a name="query-suggestions"></a>Sugerencias de consulta

Las sugerencias de consulta son frases sugeridas que los usuarios ya buscaron anteriormente. Las sugerencias aparecen en una lista debajo del cuadro de búsqueda mientras el usuario escribe una consulta. Las sugerencias de consulta se generan de forma automática. Además, se pueden agregar frases al sistema para sugerirlas "siempre" o "nunca". Obtenga más información sobre la [administración de sugerencias de consulta](https://docs.microsoft.com/sharepoint/search/manage-query-suggestions).
  
## <a name="ranking-models"></a>Modelos de clasificación

SharePoint usa modelos de clasificación para asignar un valor a los resultados de la búsqueda para que los elementos más relevantes aparezcan primero. Un modelo de clasificación es un conjunto de factores de clasificación que calcula la puntuación de clasificación de un elemento específico. SharePoint Online y SharePoint Server 2013 incluyen varios modelos de clasificación que proporcionan clasificaciones eficaces sin necesidad de más personalizaciones. Pero puede personalizar sus modelos de clasificación si necesita que los resultados de la búsqueda sean aún más relevantes para los usuarios finales. La aplicación Ranking Model Tuning permite a los clientes de SharePoint Online crear un modelo de clasificación personalizado. La aplicación proporciona una interfaz de usuario para copiar un modelo de clasificación existente, evaluar los resultados de un conjunto de consultas y "optimizarlos" agregando o quitando características de clasificación y ajustando la importancia de esas características. Obtenga más información sobre el [orden de resultados de la búsqueda](https://docs.microsoft.com/sharepoint/search/overview-of-search-result-ranking).
  
## <a name="refiners"></a>Refinadores

Los refinadores clasifican los documentos más importantes de los resultados de búsqueda de SharePoint Server en grupos para que los usuarios puedan filtrar los resultados de la búsqueda. Obtenga más información sobre cómo [configurar los elementos web de refinamiento](https://support.office.com/article/About-configuring-the-Refinement-Web-Part-7cef67e8-b992-4659-b21a-ba534eea102e).
  
## <a name="restful-query-apiquery-om"></a>API de consultas RESTful/consultas OM

Los desarrolladores pueden crear código .NET para acceder al modelo de objetos de búsqueda pública. Esto incluye las operaciones de administración de búsqueda, además de enviar consultas de búsqueda. Para interactuar con el modelo de objetos de servicio, el código .NET debe ejecutarse en un servidor web de la granja. Se puede tener acceso a un subconjunto del modelo de objetos desde un equipo remoto mediante el modelo de objetos del lado cliente (CSOM). Se puede tener acceso a las características del modelo de objetos del lado cliente (CSOM) mediante un servicio Web basado en REST o oData. Esto permite que los desarrolladores envíen consultas a la granja de SharePoint Server 2013 con las herramientas más habituales de desarrollo web.

## <a name="search-results-sorting"></a>Ordenación de los resultados de búsqueda

Los usuarios pueden elegir ordenar los resultados de búsqueda según&mdash;criterios diferentes por ejemplo, relevancia, frescura y distancia social (nombres de personas). Obtenga más información sobre el [orden de resultados de la búsqueda](https://support.office.com/article/change-settings-for-the-search-results-web-part-40ff85b3-bc5e-4230-b1dd-f088188e487e).
  
## <a name="this-list-searches"></a>Búsquedas en "esta lista"

SharePoint Online y SharePoint Server 2013 permiten limitar las búsquedas a la lista o biblioteca donde estas se realizan. En SharePoint Foundation 2013, las búsquedas devuelven resultados de todas las listas y bibliotecas que existen en o bajo el sitio donde esas búsquedas se realizan.
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes de Office 365, las opciones independientes y las soluciones locales, consulte [SharePoint Online Service Description](sharepoint-online-service-description.md).
  

