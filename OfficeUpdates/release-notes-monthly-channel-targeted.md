---
title: Las compilaciones de notas de la versión del canal mensual (dirigido)
ms.author: anankani
author: v-lislo
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 'Proporciona a los participantes del modo anticipado de Insider Lento la lista más reciente de las nuevas características, correcciones o problemas conocidos principales '
ms.openlocfilehash: 219abb58ae3fc51b869adf52885e4cce2bbdb9d1
ms.sourcegitcommit: e46d02cd54b8c164b853a130ca07ce9c85f586c5
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 11/12/2019
ms.locfileid: "38282118"
---
# <a name="release-notes-for-office-monthly-channel-targeted"></a>Las compilaciones de notas de la versión del canal mensual de Office (dirigido)

En este artículo hay notas de la versión para las compilaciones del canal mensual (dirigido) de las versiones de escritorio de Word, Excel, PowerPoint, Outlook, Access y Project para Windows. Todas las semanas se incluyen las nuevas características, correcciones importantes y los problemas principales de mayor interés para usted. Tenga en cuenta que a menudo publicamos características (y a veces incluso correcciones) para el Canal mensual (dirigido) durante un período de tiempo. Esto nos permite asegurarnos de que todo funciona correctamente antes de publicar la característica para un público más amplio. Por tanto, si a continuación no ve algo descrito, no se preocupe, lo recibirá con el tiempo.  

> [!NOTE]
> - La fecha de publicación de las notas de versión pueden no coincidir con la fecha real de lanzamiento de la compilación.
> - Microsoft Teams en instalaciones existentes de Office 365 ProPlus: a partir de finales de junio, Microsoft Teams se incluirá en instalaciones existentes de Office 365 ProPlus (y Office 365 Empresa) a la hora de actualizar dichas instalaciones. La fecha en la que se agregará Teams depende del canal de actualización que use. Para obtener más información, vea [Implementar Microsoft Teams con Office 365 ProPlus](https://docs.microsoft.com/es-ES/deployoffice/teams-install).

[//]: # (NO ELIMINAR)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

## <a name="version-1911-november-12"></a>Versión 1911: 12 de noviembre
*Versión 1911 (compilación 12228.20120)*

Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/es-ES/officeupdates/office365-proplus-security-updates)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Complemento del visualizador de datos:** Crear rápidamente diagramas de flujo de Visio desde Excel. [Más información](https://support.office.com/es-ES/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a>Outlook

- **Enviar un correo electrónico accesible a los usuarios que más lo necesitan:** Outlook mostrará una sugerencia de correo para ayudarlo a asegurarse de que el contenido sea accesible al enviarlo a un usuario que prefiera el contenido accesible.

### <a name="powerpoint"></a>PowerPoint

- **Optimizar la presentación para todos:** El comprobador de accesibilidad le ayuda a organizar los objetos de las diapositivas pensando en los lectores de pantalla.

### <a name="visio"></a>Visio

- ** Haga diagramas de Visio pulidos en Excel:** Visualice rápida y fácilmente sus datos en diagramas Visio pulidos dentro de Excel. [Más información](https://support.office.com/es-ES/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **Mejoras en la coautoría:** Mejoró la experiencia de coautoría al hacer más probable que los cambios de contenido sean recibidos por otros en tiempo real.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- **El centro de carga será reemplazado por la experiencia de los archivos que necesitan atención:** El centro de carga será reemplazado por la experiencia de los archivos que necesitan atención que aparecerá dentro de las aplicaciones de Office en Archivo > Abrir. Esta nueva experiencia es más moderna, integrada y menos intrusiva que el centro de carga.


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- El número de registros podría ser incorrecto.

### <a name="excel"></a>Excel

- Se ha resuelto un problema por el que, al eliminar hojas que contenían minigráficos que hacían referencia a datos en otra hoja, podía provocar que el archivo se identificara como dañado al volver a abrirlo.
- Los cambios en el tamaño del gráfico no se han podido guardar.
- Las casillas de verificación no se pueden renderizar correctamente.
- Los cuadros de diálogo de selección de fuentes de datos no distinguen entre mayúsculas y minúsculas en algunos campos.
- Algunas funciones VBA devolverían un error en los nuevos tipos de gráficos.
- Se podría impedir que los usuarios guarden en formato de la hoja de trabajo de Office 365 Excel.
- Corregimos un problema en el que los controles de casilla podían reducirse al usar el autoajuste para ajustar el alto de fila.
- Se ha resuelto un problema por el que se podían obtener resultados incorrectos al convertir los filtros de un informe junto con el resto de la tabla dinámica de consultas enviadas a servidores tabulares SQL.
- Se ha resuelto un problema por el que Excel podía bloquearse al modificar un archivo protegido desde un recurso compartido de red que no es de confianza.
- Usar el Narrador y la Lupa al mismo tiempo puede provocar un bloqueo.
- Corregimos un problema en el que al seleccionar una celda luego de desplazar, podía resultar en la selección de la celda incorrecta.
- Rendimiento significativamente superior al eliminar columnas con celdas combinadas.

### <a name="onenote"></a>OneNote

- Identificamos un problema que podía afectar la sincronización de un recurso local a un recurso en la nube.

### <a name="outlook"></a>Outlook

- Puede que la herramienta Buscador de salas muestre &quot;Ninguno&quot; en salones disponibles.
- Identificamos un problema en el cual el cuadro de búsqueda podía llegar a desaparecer cuando la cinta estaba configurada para ocultarse automáticamente.
- Identificamos un problema que podía provocar la ruptura de las firmas digitales al firmar un correo electrónico con un adjunto firmado digitalmente.
- Pueden faltar imágenes insertadas en un mensaje de correo electrónico reenviado.
- Puede que los usuarios no puedan crear perfiles de Outlook con restricción de espacio empresarial estricta.
- Identificamos un problema en el que los nombres de archivo largos se truncaban después de arrastrarlos y soltarlos en el cuerpo del mensaje.

### <a name="powerpoint"></a>PowerPoint

- Los cambios en el tamaño del gráfico no se han podido guardar.
- Usar el Narrador y la Lupa al mismo tiempo puede provocar un bloqueo.
- Identificamos un problema en el cual la relación de aspecto de la vista previa de las diapositivas no se bloqueaba o desbloqueaba correctamente.

### <a name="project"></a>Project

- Identificamos un problema en el que las notas no se conservaban si se creaban mientras se realizaban tareas de actualización.
- El usuario no puede marcar una tarea como completada, y esta se establece en un 99 %.
- Redistribuir no resuelve las sobreasignaciones.
- Identificamos un problema en el que los usuarios podían recibir varios mensajes al abrir un proyecto de solo lectura.
- Identificamos un problema por el que un usuario podía bloquear un archivo, pero no se mostraba ningún nombre de usuario en el mensaje de error.

### <a name="publisher"></a>Publisher

- Las formas pueden aparecer fuera del borde del gráfico.

### <a name="word"></a>Word

- No se muestran sugerencias de corrección en los menús contextuales.
- Los cambios en el tamaño del gráfico no se han podido guardar.
- Las formas pueden aparecer fuera del borde del gráfico.
- Identificamos un problema al ver los comentarios mientras se usa un lector de pantalla.
- Identificamos un problema en el que algunos análisis eran identificados erróneamente como análisis de ortografía o gramática.
- Los vínculos de cid:image de los mensajes de Outlook ahora se pueden romper correctamente cuando se solicite.
- Pueden aparecer caracteres incorrectos al usar la Autocorrección de coreano-inglés.
- Puede que se produzcan errores al buscar desde el panel de navegación.
- Usar el Narrador y la Lupa al mismo tiempo puede provocar un bloqueo.
- Se aplican directivas de contenido incorrectamente a los comentarios.
- Puede que se apliquen etiquetas de directiva inferior cuando una etiqueta de directiva superior debería haber tenido prioridad.
- Al abrir documentos heredados e ir a la pestaña Información, se puede producir un bloqueo.
- Identificamos un problema por el que algunas veces un nuevo diálogo de comentario no podía obtener el foco.
- Una tarjeta de contacto podía no abrirse después de aplicar formato a una @mención.
- Resaltar el texto podía ser un reto.
- Se resolvió un problema que impedía a los usuarios guardar documentos de Word, Excel y PowerPoint. Este problema afecta a los usuarios que crean un nuevo archivo y muestra la opción "Guardar como" después de hacer clic en el icono Guardar o presionar Ctrl + S.
- Los comentarios heredados escritos con texto oscuro no se ven en el modo oscuro.
- Se puede impedir que un usuario navegue a un elemento individual en el editor.
- Los errores gramaticales u ortográficos pueden no estar resaltados.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Puede que algunos dibujos no se muestren en la vista previa o en las presentaciones.
- Corregimos un problema en el cual se podía evitar una actualización con un mensaje de error incorrecto indicando que "Hay otra instalación en curso".
- Algunos caracteres katakana pueden mostrarse incorrectamente en un cuadro de texto vertical.
- Al intentar guardar un archivo en un recurso compartido de red desconectado, se puede producir un error.
- Problema de rendimiento al usar Shapes en Windows 7.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

