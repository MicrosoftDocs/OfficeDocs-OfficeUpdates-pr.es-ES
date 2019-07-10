---
title: Notas de la versión para las versiones de canal semianual (dirigido) en 2017
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 12/12/2017
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Normal
ms.collection: RelNotes_ProPlus
description: Proporciona a los profesionales de ti las notas de la versión para las versiones de canal semianual (dirigido) para Office 365 ProPlus en 2017
ms.openlocfilehash: 6014107ae2471707d226602cc71efaa24f1de310
ms.sourcegitcommit: 358a0cbd1b722d309556c50d53abbe6c1a348f60
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2019
ms.locfileid: "32439135"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2017"></a>Notas de la versión para las versiones de canal semianual (dirigido) en 2017

Estas notas de la versión proporcionan información sobre las nuevas características, actualizaciones de seguridad y actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones de canal semianual (dirigido) a Office 365 ProPlus en 2017.
 
> [!NOTE]
> - Lo siguiente también proporciona información sobre características nuevas, actualizaciones de seguridad y no relacionadas con la seguridad para Visio Pro para Office 365 y el cliente de escritorio de Project Online.
> - Esta información también se aplica a Office 365 Empresa, que es la versión de Office que viene con algunos planes de Office 365, como Empresa Premium.
> - El canal semianual (dirigido) se llamaba First Release para el canal diferido antes de septiembre de 2017.

## <a name="version-1708-december-12"></a>Versión 1708:12 de diciembre
*Versión 1708 (compilación 8431.2131)*

 ### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2017-11935](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11935): Vulnerabilidad de la ejecución remota de código de Microsoft Excel

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
-   Se ha solucionado un problema que causaba que el usuario viese incorrectamente un mensaje de error "Error grave" al abrir un libro de Office 2007 o anterior (.xls o .xla) con macros.
-   Se ha corregido un problema que causaba que, al abrir un libro desde la línea de comandos, se pudiese perder el formato de texto enriquecido de una celda.

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939): Vulnerabilidad de divulgación de información de Microsoft Office

### <a name="powerpoint-security-updates"></a>PowerPoint: Actualizaciones de seguridad
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934): Vulnerabilidad de divulgación de información de Microsoft PowerPoint

### <a name="project-non-security-updates"></a>Project: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema que provocaba que se pudieran perder datos de campos personalizados de nivel de proyecto al guardar.
-   Se ha corregido un problema que provocaba que un error al guardar podía dañar un archivo y hacer que Project se bloqueara al abrirlo.
-   Se ha corregido un problema que provocaba que al abrir un plan de proyecto pudiera producirse un bloqueo.

### <a name="word-security-updates"></a>Word: actualizaciones de seguridad
-   [Advertencia 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Actualización de defensa en profundidad de Microsoft Office



## <a name="version-1708-november-14"></a>Versión 1708:14 de noviembre
*Versión 1708 (compilación 8431.2110)*

### <a name="access-non-security-updates"></a>Access: Actualizaciones no relacionadas con la seguridad
-   Se ha solucionado un problema que provocaba que pareciera que se seleccionaba todo el texto al intentar seleccionar texto en un cuadro de texto o en un cuadro combinado, en lugar de mostrarse la selección real.

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877): Vulnerabilidad de omisión de característica de seguridad de Microsoft Excel
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878): Vulnerabilidad de los daños en la memoria de Microsoft Excel
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884): vulnerabilidad de los daños en la memoria de Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema que provocaba que un usuario no pudiera cerrar un libro en la Vista protegida cuando el nombre de archivo contenía corchetes.
-   Se ha corregido un problema que provocaba que Excel se bloqueara cuando el usuario hacía clic en Examinar al intentar insertar un objeto en un libro existente.
-   Se ha corregido un problema que provocaba que no se modificara la forma al seleccionar "Ajustar tamaño de la forma al texto" en la sección Cuadro de texto de Opciones de texto en el panel Formato de forma.
-   Se ha corregido un problema que provocaba que las fuentes y los formatos de texto de las celdas no se cargaran o se abrieran dos libros idénticos con una única plantilla al hacer doble clic para abrir un libro.
-   Se ha corregido un problema que provocaba que el primer libro creado al iniciar Excel no se cerrara al abrir o crear un libro nuevo.
-   Se ha corregido un problema que provocaba que el desplazamiento de la información en pantalla quedara incorrectamente alineada al arrastrar elementos o rellenarlos arrastrando.
-   Se ha corregido un problema que, al guardar un libro con Archivo \> Guardar como, provocaba que los nombres de archivos que contuvieran puntos aparecieran en blanco o truncados en el cuadro de diálogo de guardar.
-   Se ha corregido un problema que provocaba que Office no pudiera escribir en el disco al guardar un archivo de copia de sincronización, pero Office siguiera cargando el archivo en OneDrive. Con esta corrección, ahora el usuario ve un mensaje de error y la carga no se realiza.
-   Se ha corregido un problema de representación que provocaba que aparecieran líneas y encabezados negros debido a un controlador de gráficos defectuoso.
-   Se ha corregido un problema que provocaba que Excel se bloqueara o no fuera posible guardar un libro tras insertar un gráfico.
-   Se ha corregido un problema que provocaba que el salto de línea de página estuviera posicionado incorrectamente en la vista previa de salto de página.

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema que provocaba que el foco de la lista de mensajes cambiara de ubicación inesperadamente cuando el usuario eliminaba mensajes.
-   Se ha corregido un problema que provocaba que el usuario recibiera solicitudes de autenticación al administrar datos adjuntos.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones no relacionadas con la seguridad
-   Se ha solucionado un problema que provocaba que Office no pudiera escribir en el disco al guardar un archivo de copia de sincronización, pero Office siguiera cargando el archivo en OneDrive. Con esta corrección, ahora el usuario ve un mensaje de error y la carga no se realiza.
-   Se ha corregido un problema que provocaba que PowerPoint se bloqueara al editar y aplicar formato al texto tras deshacer un cambio en una tabla.
-   Se ha solucionado un problema que provocaba que se abriera una ventana nueva para reproducir el vídeo al usar referencias a Flash Player basadas en código para insertar de YouTube. Se han actualizado los códigos para insertar antiguos con referencias a HTML5 basadas en vídeos de YouTube para que se reproduzcan correctamente en su ubicación.

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad
-   [Advertencia 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020): Actualización de defensa en profundidad de Microsoft Office

### <a name="word-non-security-updates"></a>Word: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema que provocaba que Word se bloqueara cuando un usuario intentaba usar Guardar como sobre un documento existente en OneDrive para la Empresa y, seguidamente, cancelaba o intentaba combinar cambios existentes.
-   Se ha solucionado un problema que provocaba que Office no pudiera escribir en el disco al guardar un archivo de copia de sincronización, pero Office siguiera cargando el archivo en OneDrive. Con esta corrección, ahora el usuario ve un mensaje de error y la carga no se realiza.
-   Se ha corregido un problema que provocaba que Word dejara de responder cuando el usuario navegaba a la pestaña Insertar poco después de abrir Word.
-   Se ha corregido un problema que provocaba que los caracteres se mostraran en la esquina superior izquierda de la pantalla tras hacer clic en el margen al introducir caracteres.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882): Vulnerabilidad de los daños en la memoria de Microsoft Office

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad
-   Se ha solucionado un problema relacionado con el zoom y el escalado en Complementos de Office en el entorno de PPP dinámico.
-   Se ha corregido un problema que provocaba que el nodo CurrentStatus del proveedor del servicio de configuración (CSP) de Office devolviera una cadena vacía incluso si Office 365 ProPlus está instalado.
-   Se ha corregido un problema que provocaba cambios en los formatos de archivo .box. Esto afectaba la funcionalidad de versiones antiguas de Office instaladas en el mismo equipo, porque los archivos .box se comparten con todas las versiones de una aplicación de Office en el mismo equipo.
-   Se ha corregido un problema que provocaba que se mostrara un mensaje de error en determinadas circunstancias al usar la activación en equipos compartidos en el que se indicaba que se había producido un error en la aplicación que impedía el correcto funcionamiento y se preguntaba al usuario si quería realizar una reparación.



## <a name="version-1708-october-10"></a>Versión 1708:10 de octubre
*Versión 1708 (compilación 8431.2107)*

### <a name="access-non-security-updates"></a>Access: Actualizaciones no relacionadas con la seguridad
-   Soluciona un problema por el que una consulta no se ejecuta si tiene una unión con una clave principal de una tabla vinculada de Microsoft Dynamics.
-   Se soluciona un problema por el que no aparecen los decimales para los valores de moneda en una tabla de Microsoft Dynamics.

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema por el que Excel se bloqueaba al abrir un archivo .XLL.
-   Se soluciona un problema por el que el estilo de trama de una celda no se representaba correctamente después de agregar un encabezado o pie de página en la vista de diseño de página.
-   Se soluciona un problema por el que pegar una copia de una tabla dinámica en otro libro podría ocasionar un bloqueo.
-   Se soluciona un problema por el que, cuando elige el comando Reemplazar y se abre el cuadro de diálogo Buscar y reemplazar, el foco del cuadro de diálogo se encuentra en la ficha Buscar, en lugar de la ficha Reemplazar.
-   Se corrige un problema por el que Excel se bloquea al abrir el panel Actividad de un libro abierto desde un servidor de SharePoint anterior a SharePoint Server 2016.
-   Se soluciona un problema por el que Excel se abre y muestra una ventana en blanco cuando están habilitados uno o más complementos XLL.
-   Se corrige un problema por el que Excel se bloquea después de haber utilizado el botón Formularios en un libro ya cerrado.
-   Se soluciona un problema por el que, cuando se utiliza el evento SheetBeforeRightClick, la inserción de una columna que forma una intersección con celdas combinadas no expande las celdas combinadas.

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2017-11774](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11774): Vulnerabilidad de omisión de característica de seguridad de Microsoft Outlook
-   [CVE-2017-11776](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11776): Vulnerabilidad de divulgación de información de Microsoft Office Outlook

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema por el que el vínculo "Más información" de las sugerencias de la directiva no está visible cuando se utiliza el tema de color Gris oscuro.
-   Se soluciona un problema por el que Outlook se bloquea cuando un usuario está intentando configurar una nueva cuenta y cierra la ventana sin que haya finalizado la configuración de la cuenta.
-   Se soluciona un problema por el que Marcar como leído y Marcar como no leído se muestran como opciones para los mensajes de la Bandeja de entrada compartida de un grupo.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones no relacionadas con la seguridad
-   Se corrige un problema por el que PowerPoint se bloquea al abrir una presentación desde un servidor de SharePoint anterior a SharePoint Server 2016.

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad
-   [CVE-2017-11826](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11826): Vulnerabilidad de los daños en la memoria de Microsoft Office

### <a name="word-non-security-updates"></a>Word: Actualizaciones no relacionadas con la seguridad
-   Se corrige un problema por el que Word se bloquea al abrir el panel Actividad de un documento abierto desde un servidor de SharePoint anterior a SharePoint Server 2016.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2017-11825](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11825): Vulnerabilidad de la ejecución remota de código de Microsoft Office

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema por el que el progreso de Reparación en línea no se muestra al usuario.
-   Se soluciona un problema por el que no se muestran las propiedades de archivo de Office en el Explorador de archivos.
-   Se soluciona un problema por el que los botones de complementos de Office desaparecen de la cinta de opciones cuando hay un segundo documento abierto.
-   Se soluciona un problema por el que no se pueden abrir algunos módulos VBA que tienen nombres con caracteres de doble byte.



## <a name="version-1708-september-12"></a>Versión 1708:12 de septiembre
*Versión 1708 (compilación 8431.2079)*

### <a name="access-feature-updates"></a>Access: Actualizaciones de características
-   **Propiedad de nombre de etiqueta:** mejore la accesibilidad mediante la asociación de una etiqueta con un control en un formulario.
-   **Editar un nuevo elemento es más accesible:** Utilizar métodos abreviados de teclado rápido (CTRL+E) para editar un nuevo elemento de un cuadro combinado o cuadro de lista.
-   **Conector de Dynamics:** permite importar datos o vincular a datos almacenados en Microsoft Dynamics. [Más información](https://support.office.com/article/636079c1-9fc3-4fca-8410-6596d62223da)
-   **Conector de Salesforce:** permite importar datos o vincular a datos almacenados en Salesforce. [Más información](https://support.office.com/article/7375ffb6-1d6a-46f1-bb0c-c6ac3c58f5a0)

### <a name="excel-feature-updates"></a>Excel: Actualizaciones de características
-   **Mejoras de "Agregar columna a partir de los ejemplos":** admite más transformaciones de fecha y hora, matemáticas y columna de índice.
-   **Mejora de rendimiento:** Excel abre libros complejos con varias hojas con mayor rapidez, para que pueda procesar fácilmente fórmulas con rangos extensos, filtrar un gran número de filas, o copiar y pegar más rápido.
-   **Insertar imágenes en línea:** Nueva página de destino para la selección de imágenes. Además, la información de atribución se inserta automáticamente con la imagen.
-   **Conector Azure Data Lake Store:** Ahora, los usuarios pueden importar datos desde Azure Data Lake Store.
-   **Mejoras en la opción “Agregar columna a partir de ejemplos”:** Admite sugerencias, más operaciones de fecha y hora, así como transformaciones adicionales.
-   **Pestaña Datos**: Los botones de la cinta de opciones de la pestaña Datos se han reorganizado en dos nuevos grupos: Obtener y transformar datos y Consultas y conexiones.
-   **Uso compartido de consultas**: Exporte cualquier definición de consulta en un archivo de conexión de base de datos de Office (ODC) y, a continuación, compártalo en libros o con otros usuarios.
-   **Carga de datos** Cargue datos desde una consulta directamente en tablas dinámicas o gráficos dinámicos sin tener que guardar los datos en el modelo de datos.
-   **Actividad de archivo compartido:** Elija el botón Actividad en la esquina superior derecha del archivo para ver cuando un archivo compartido en OneDrive para la Empresa o SharePoint se compartió, se editó, se restauró o se cambió de nombre.
-   **Vínculos seguros:** Cuando un usuario hace clic en un vínculo, Protección contra amenazas avanzada de Office 365 (ATP) lo inspecciona para comprobar si es malintencionado o no. Si el vínculo se considera malintencionado, se redirige al usuario a una página de advertencia en lugar de redirigirlo a la URL de destino original. [Más información](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Funcionalidad de importación de datos mejorada:** Puede importar datos de varios orígenes y darles forma con facilidad. Administre las consultas y las conexiones de los libros con el panel lateral Consultas y conexiones y comparta las consultas con otros usuarios mediante archivos ODC. [Más información](https://support.office.com/article/ad78befd-eb1c-4ea7-a55d-79d1d67cf9b3)
-   **Cambios en archivos compartidos**: Vea quién ha modificado los libros compartidos y restaure las versiones anteriores. [Más información](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)
-   **Selección de lazo con un botón del lápiz:** Utilice los botones de un lápiz digital admitido para la selección de lazo de lápiz sin necesidad de ir a la cinta de opciones.

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2017-8631](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8631): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2017-8632](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8632): Vulnerabilidad de los daños en la memoria de Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
-   Se ha solucionado un problema por el que Excel se bloqueaba temporalmente al expandir o contraer una tabla dinámica. Además, los encabezados de las tablas dinámicas salían de la pantalla.
-   Se ha solucionado un problema por el que se omitían los caracteres de tabulación al copiar y pegar texto delimitado por tabulaciones desde Word, lo que causaba que el texto no se dividiera en columnas.
-   Se ha solucionado un problema por el que Excel se bloqueaba al abrir el cuadro de diálogo Publicar como página web.
-   Se ha solucionado un problema por el que no se realizaba correctamente una actualización de datos o Excel se bloqueaba al usar datos de un servidor de SQL Server Analysis Services cuando la configuración regional de Excel no era la misma que la del servidor de SQL Server Analysis Services.
-   Se ha solucionado un problema que provocaba errores al intentar guardar cambios de documentos sincronizados con el cliente de OneDrive.
-   Se ha corregido un problema que no permitía realizar cambios en ningún elemento de una hoja de cálculo al haber una tabla dinámica con campos en el área Filtrar, pero sin ningún otro campo en otras ubicaciones.

### <a name="outlook-feature-updates"></a>Outlook: Actualizaciones de características
-   **Mejoras de accesibilidad:** se han realizado cambios para facilitar la lectura y edición de texto, tablas, listas e imágenes en el correo electrónico al usar un lector de pantalla.
-   **Configuración de cuentas nuevas:** Configure las nuevas cuentas con un nuevo asistente que requiere menos pasos manuales.
-   **Cuadro de diálogo de adjuntar vínculos:** Al adjuntar un vínculo mediante Adjuntar archivo en la cinta de opciones, puede seleccionar si desea agregarlo como un vínculo o como un archivo adjunto. Si no quiere ver este cuadro de diálogo cada vez, vaya a Archivo \> Opciones \> General y especifique cómo desea que los vínculos se asocien en “Opciones de datos adjuntos”.
-   **Compatibilidad con archivos adjuntos locales:** Los archivos de la versión local de SharePoint Server se muestran como archivos recientes en Mensaje \> Adjuntar archivo. Los sitios de grupo de las versiones locales de OneDrive para la Empresa y SharePoint aparecen en Adjuntar archivo \> Explorar sitios web. Además, es posible cargar archivos locales en los sitios de la versión local de OneDrive para la Empresa.
-   **Clasificaciones empresariales de los grupos:**  al crear o editar un grupo, se le puede asignar un nivel de clasificación empresarial definido por el administrador del espacio empresarial (por ejemplo, Confidencial). La clasificación en cuestión aparecerá en el encabezado de grupo.
-   **Acceso de invitado a los grupos de Office 365:** Colabore con personas ajenas a la organización concediéndoles acceso a las conversaciones del grupo, archivos, invitaciones del calendario y el bloc de notas del grupo. [Más información](https://support.office.com/article/bfc7a840-868f-4fd6-a390-f347bf51aff6)
-   **Mensajes accionables:** los desarrolladores pueden crear mensajes para facilitar a los usuarios la realización de acciones simples o rápidas y sin tener que cambiar a un sitio web externo o a otra aplicación, directamente desde Outlook. [Más información](https://dev.office.com/blogs/create-more-engaging-conversations-with-new-actionable-messages-updates-announced-at-microsoft-build)

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571): Vulnerabilidad de omisión de característica de seguridad de Microsoft Office Outlook
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572): Vulnerabilidad de divulgación de información de componente de Microsoft Office Outlook
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663): Vulnerabilidad de los daños en la memoria de Microsoft Office Outlook

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones no relacionadas con la seguridad
-   Se ha solucionado un problema que provocaba que no se pudiera configurar una cuenta IMAP en Outlook.
-   Se ha solucionado un problema que provocaba un fallo intermitente al abrir Outlook.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Actualizaciones de características
-   **Insertar imágenes en línea:** Nueva página de destino para la selección de imágenes. Además, la información de atribución se inserta automáticamente con la imagen.
-   **Subtítulos para los vídeos:** Agregue subtítulos a los vídeos para que sean más accesibles. [Más información](https://support.office.com/article/a16745e1-b3da-4428-b2a7-ff0c8b758d0b)
-   **Incluir comentarios en una grabación:** Incluya un vídeo con sus propios comentarios cuando grabe una presentación. Las grabaciones pueden incluir animaciones, entradas de lápiz, audio y vídeo.
-   **Actividad de archivo compartido:** Elija el botón Actividad en la esquina superior derecha del archivo para ver cuando un archivo compartido en OneDrive para la Empresa o SharePoint se compartió, se editó, se restauró o se cambió de nombre.
-   **Creación de texto alternativo:** Un servicio basado en cloud genera automáticamente texto alternativo para las imágenes de una presentación.
-   **Vínculos seguros:** Cuando un usuario hace clic en un vínculo, Protección contra amenazas avanzada de Office 365 (ATP) lo inspecciona para comprobar si es malintencionado o no. Si el vínculo se considera malintencionado, se redirige al usuario a una página de advertencia en lugar de redirigirlo a la URL de destino original. [Más información](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Mejoras para diseñadores:** Se recomiendan ideas de diseño profesional para listas de acción.
-   **Cambios en archivos compartidos:** Ver quién ha realizado cambios en las presentaciones compartidas y restaurar versiones anteriores. [Más información](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="powerpoint-security-updates"></a>PowerPoint: Actualizaciones de seguridad
-   [CVE-2017-8742](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8742): Vulnerabilidad de la ejecución remota de código de PowerPoint
-   [CVE-2017-8743](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8743): Vulnerabilidad de la ejecución remota de código de PowerPoint

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema que causaba que no se mostraran los caracteres definidos por el usuario final (EUDC) que están vinculados a fuentes.

### <a name="project-non-security-updates"></a>Project: Actualizaciones no relacionadas con la seguridad
-   Se ha solucionado un problema por el que Project se bloqueaba al abrir determinados archivos de Project Online.
-   Se ha solucionado un problema por el que Inicio real podía borrarse por error al establecer trabajo restante.
-   Se corrigió un problema por el que, en Fecha de inicio real de la tarea, podían mostrarse datos distintos de los indicados por el recurso en el estado de Project Web App.
-   Se corrigió un problema que causaba que el trabajo real volviera a programarse si se cambiaba la fecha de finalización de la tarea.
-   Se corrigió un problema que causaba que, al copiar y pegar campos de costos, los valores pegados no coincidieran exactamente con los valores copiados debido a un error de redondeo.
-   Se corrigió un problema que causaba que los datos de fase temporal para los recursos de un presupuesto no se copiaran al guardar de una línea base a otra.
-   Se corrigió un problema que causaba que el campo de estado no siempre se calculara correctamente para las tareas de resumen.
-   Se ha solucionado un problema que producía que trabajo real se transfiriese de forma errónea a un recurso de empresa al sustituir un recurso local y cuando está habilitado el trabajo protegido.
-   Corrección de un problema que producía que Project se bloquease si tenía una tabla en la que la primera columna fuese Nombre de tarea, la columna estuviese bloqueada e hiciese clic en una tarea.
-   Corrección de un problema que producía que pudiese asignar el mismo recurso varias veces a la misma tarea mediante la vista Uso de tareas.
-   Corrección de un problema que producía que los valores en los campos personalizados de número se perdiesen al abrir archivos XML.
-   Corrección de un problema que producía que la sangría de tareas de nivel superior no se sincronizase correctamente entre Project y la lista de tareas de SharePoint.
-   Corrección de un problema que producía que, al importar información de una asignación, recurso o tarea de un libro de Excel, se ignorasen los valores en el campo de trabajo.
-   Se ha solucionado un problema que provocaba que los valores de Línea base de fase temporal no coincidieran con los valores iniciales al guardar un proyecto en el formato de archivo XML.
-   Se corrige un problema que provocaba que el cliente de Project no abriera un proyecto, ya que detectaba que se había extraído del repositorio cuando, realmente, no era así.
-   Se corrige un problema que ralentizaba la apertura de los archivos de Project desde un servidor de archivos con una latencia alta.

### <a name="skype-for-business-security-updates"></a>Skype Empresarial: Actualizaciones de seguridad
-   [CVE-2017-8676](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8676): Vulnerabilidad de la revelación de información de GDI+ de Windows
-   [CVE-2017-8695](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8695): Vulnerabilidad de divulgación de información de componente de gráficos
-   [CVE-2017-8696](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8696): Ejecución remota de código de componente de gráficos de Microsoft

### <a name="skype-for-business-non-security-updates"></a>Skype Empresarial: Actualizaciones no relacionadas con la seguridad
-   Se agrega un cuadro de diálogo en el que se explica por qué un usuario no puede unirse a una reunión cuando determinados puertos están bloqueados o las direcciones IP no están en la lista de permitidos.
-   Se ha solucionado un problema por el que los mensajes no leídos en salones de chat persistentes se marcaban como leídos cuando se hace clic en las pestañas de conversación de mensajería instantánea.
-   Se ha solucionado un problema en la que las notificaciones de mensajería instantánea entrantes experimentaban un retraso de varios segundos.
-   Se ha solucionado un problema en el que un contacto de AD se mostraba como un número de teléfono en lugar del nombre del contacto cuando está deshabilitada la sincronización con Exchange.
-   Se ha solucionado un problema en el que se impedía a los usuarios anónimos unirse cuando estaba deshabilitada la federación y el organizador de la reunión no había bloqueado explícitamente las uniones anónimas.
-   Se ha solucionado un problema en el que se mostraba de manera incorrecta al organizador de la reunión el número de invitados para reuniones que excedían el límite de la reunión.
-   Se ha solucionado un problema en el que el número de teléfono no se mostraba en las notificaciones sobre llamadas RTC entrantes.
-   Se ha solucionado un problema en el que, cuando se usaba la tecla Supr mientras se cambiaba el nombre de un grupo de la lista de contactos, se eliminaba todo el grupo.
-   Se ha solucionado un problema en el que se descartaba la notificación para compartir de una conversación de mensajería instantánea antes de que se dejara de compartir.
-   Se ha solucionado un problema que causaba que la pantalla de inicio de sesión se mostrara en blanco para algunos idiomas distintos del inglés.
-   Se ha solucionado un problema que causaba que los caracteres que no pertenecieran al alfabeto inglés aparecieran cifrados en el chat y en el historial de chat.
-   Se muestra el número de teléfono de una llamada entrante controlada por el Operador automático de la organización si no se conoce el nombre del usuario.
-   Agregar una configuración de banda que permita la restricción de "Cualquiera (sin restricciones)" como una opción para "Estas personas no tienen que esperar en el vestíbulo".
-   Agregar capacidad de activar o desactivar auto vídeo para videollamadas P2P en VDIv2.
-   Se ha corregido un problema que mostraba los números duplicados de contactos en el menú desplegable llamar.
-   Se ha corregido un problema que quitaba los delegados para los usuarios que se movían entre Skype Empresarial y Skype Empresarial Basic.
-   Se ha solucionado un problema en el que el estado Desconectado no era visible al usar las directivas de cliente Habilitar desconectado y URL de estado de cliente.
-   Se ha ampliado el botón Unirse a la reunión para corregir un truncamiento en algunos de los idiomas localizados.
-   Se ha aumentado la prominencia de los mensajes de importancia alta en el chat.
-   Se agregan tipos de extensión de archivo de Skype Empresarial y de Office a las listas de transferencias de archivos bloqueadas permitidas.
-   Se aplican correcciones de ubicación en las invitaciones a reuniones de Outlook para el texto del pie de página establecido en un idioma diferente al inglés en las reuniones.
-   Se corrige un problema que provocaba que los nombres de los remitentes se cambiaran a veces en las conversaciones de varios usuarios.
-   Se corrige un problema que provocaba que la ventana de las conversaciones en blanco no apareciera hasta que no se había unido correctamente a una reunión.
-   Se corrige un problema que provocaba que la información del campo del departamento de una tarjeta de contacto no apareciera en los resultados de la búsqueda si el campo del título estaba vacío.
-   Se corrigen los errores de inicio de sesión de los usuarios migrados de un entorno local a uno en línea que se producían a causa de las reglas de firewall.
-   Se ha agregado una nueva clave del Registro DWORD para corregir un problema que provocaba que, cuando un usuario iniciaba sesión en el cliente en una red externa con LyncAutoD, el cliente restableciese la clave del Registro de OAuthUsed a false. Para solucionar el problema, establezca el valor en 1 para EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket en HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Lync\\\<Id.SIP\>.

### <a name="visio-feature-updates"></a>Visio: Actualizaciones de características
-   **Crear diagramas de los datos de Excel:** Se crea automáticamente un diagrama de flujo básico o un diagrama de flujo de funciones cruzadas a partir de datos de Excel mediante plantillas de visualizador de datos nuevos. [Más información](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)
-   **Vínculos seguros:** Cuando un usuario hace clic en un vínculo, Protección contra amenazas avanzada de Office 365 (ATP) lo inspecciona para comprobar si es malintencionado o no. Si el vínculo se considera malintencionado, se redirige al usuario a una página de advertencia en lugar de redirigirlo a la URL de destino original. [Más información](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)

### <a name="visio-non-security-updates"></a>Visio: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema en el que los complementos COM no recibían eventos abiertos de un documento cuando se abre un archivo de Visio mediante un doble clic en un icono de archivo o nombre de archivo.

### <a name="word-feature-updates"></a>Word: Actualizaciones de características
-   **Insertar imágenes en línea:** nueva página de destino para la selección de imágenes. Además, la información de atribución se inserta automáticamente con la imagen.
-   **Creación de texto alternativo:** Un servicio basado en la nube genera automáticamente texto alternativo (alt text) para las imágenes de un documento.
-   **Actividad de archivo compartido:** Elija el botón Actividad en la esquina superior derecha del archivo para ver cuando un archivo compartido en OneDrive para la Empresa o SharePoint se compartió, se editó, se restauró o se cambió de nombre.
-   **Vínculos seguros:** Cuando un usuario hace clic en un vínculo, Protección contra amenazas avanzada de Office 365 (ATP) lo inspecciona para comprobar si es malintencionado o no. Si el vínculo se considera malintencionado, se redirige al usuario a una página de advertencia en lugar de redirigirlo a la URL de destino original. [Más información](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Cambios en archivos compartidos:** Ver quién ha realizado cambios en los documentos compartidos y restaurar versiones anteriores. [Más información](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="word-non-security-updates"></a>Word: Actualizaciones no relacionadas con la seguridad
-   Se ha solucionado un problema que provocaba que Word se cerrara inesperadamente al cargar el complemento Grammarly.
-   Se ha solucionado un problema en el que, en determinadas condiciones, Word se bloqueaba al intentar recuperar los archivos en la nube.
-   Se ha solucionado un problema que no permitía girar las formas incluidas en los lienzos de dibujo.
-   Se ha corregido un problema que no permitía aplicar la separación correcta entre vocales y consonantes al escribir en coreano.
-   Al guardar un documento como archivo PDF, se guarda como PDF de versión 1.7.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2017-8630](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8630): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2017-8744](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8744): Vulnerabilidad de los daños en la memoria de Microsoft Office

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad
-   Se ha solucionado un problema que impedía que se mostrara el cuadro de diálogo Novedades.
-   Se ha solucionado un problema en el que al hacer clic en la pestaña Dibujo, se bloqueaba la aplicación para algunos usuarios.
-   Se ha solucionado un problema en el que al mantener el puntero sobre un Control común que tiene una información sobre herramientas en él, hace que la aplicación se bloquee.
-   Se ha solucionado un problema en el que un mensaje de error de licencia aparece cuando se usan controles comunes.
-   Se ha solucionado un problema relacionado con la forma en que se firmaban algunos archivos de programa, lo que causaba que los programas antivirus marcaran esos archivos como potencialmente peligrosos, así como otros problemas de protección o acceso a datos en Windows Information Protection (WIP).
-   Se ha agregado compatibilidad para que los usuarios que trabajen en versiones de Office de 64 bits puedan abrir archivos de macro que contienen controles mscomctl.ocx.
-   Se han mejorado los controles de accesibilidad que se usan en mscomctl.ocx.
-   Se ha corregido un problema que provocaba que los comandos no estuvieran disponibles en los cuadros de diálogo de personalización de la cinta o de la barra de herramientas de acceso rápido.



## <a name="version-1705-august-8"></a>Versión 1705:8 de agosto
*Versión 1705 (compilación 8201.2171)*

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones no relacionadas con la seguridad
-   Se he corregido un problema al arrastrar la barra de desplazamiento para desplazarse por una lista de mensajes.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad
-   Se corrigió un problema relacionado con la forma en que se firmaban algunos archivos de programa, lo que causaba que los programas antivirus marcaran esos archivos como potencialmente peligrosos, así como otros problemas de protección o acceso a datos en Windows Information Protection (WIP).
-   Se corrigió un problema que impedía que se mostrara el cuadro de diálogo Novedades.



## <a name="version-1705-july-27"></a>Versión 1705:27 de julio
*Versión 1705 (compilación 8201.2158)*

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema que provocaba errores al intentar guardar cambios de documentos sincronizados con el cliente de OneDrive.
-   Se ha corregido un problema que bloqueaba Excel cuando se agregaban datos de hoja de cálculo a un modelo de datos y se establecía el tema de contraste alto en negro.

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571): Vulnerabilidad de omisión de característica de seguridad de Microsoft Office Outlook
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572): Vulnerabilidad de divulgación de información de componente de Microsoft Office Outlook
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663): Vulnerabilidad de los daños en la memoria de Microsoft Office Outlook

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema en el que agregar una forma después de que otro usuario cambiase el diseño causaba un error de mezcla.

### <a name="word-non-security-updates"></a>Word: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema que no permitía aplicar la separación correcta entre vocales y consonantes al escribir en coreano.
-   Se ha corregido un problema que imprimía la dirección de entrega en sobres demasiado cerca del borde izquierdo.



## <a name="version-1705-july-13"></a>Versión 1705:13 de julio
*Versión 1705 (compilación 8201.2136)*

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502): Vulnerabilidad de los daños en la memoria de Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
-   Corrección de un problema que producía que Excel se bloqueara con libros con vínculos externos.
-   Corrección de un problema que producía que, al pegar celdas de Excel en Word, se mostrasen ceros en las celdas, incluso aunque la opción “Mostrar un cero en celdas que tienen un valor cero” no esté seleccionada.

### <a name="project-non-security-updates"></a>Project: Actualizaciones no relacionadas con la seguridad
-   Corrección de un problema que producía que los valores seleccionados de una gráfica o tabla no fuesen visibles en el panel de gráfica o tabla.

### <a name="skype-for-business-non-security-updates"></a>Skype Empresarial: Actualizaciones no relacionadas con la seguridad
-   Corrección de un problema que producía que no se mostrase una ventana de conversación en el fondo al unirse a una reunión y que se mostrase el diálogo de unión de dispositivos de audio al usuario.
-   Corrección de un problema que producía que el vínculo de reunión de Outlook no siempre pasase el URI interno de forma adecuada.
-   Ampliación del botón Unirse a la reunión para corregir un truncamiento en algunos de los idiomas localizados.

### <a name="word-non-security-updates"></a>Word: Actualizaciones no relacionadas con la seguridad
-   Corrección de un problema que producía que las tablas no se mostrasen adecuadamente después de realizar determinadas acciones.
-   Corrección de un problema que producía que varias ediciones a citas apareciesen a veces como una única acción de deshacer en vez de varias acciones individuales consecutivas.
-   Corrección de un problema que producía que se deshabilitase Deshacer después de determinadas acciones.
-   Corrección de un problema para evitar posible pérdida de datos después de determinadas acciones de deshacer.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570): Vulnerabilidad de la ejecución remota de código de Microsoft Office

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad
-   Corrección de un problema que producía que las actualizaciones desatentidas de Office 2013 a Office 2016 no se realizasen correctamente al usar System Center Configuration Manager.
-   Corrección de un problema que producía que los complementos heredados implementados de la tienda a través del catálogo corporativo no se pudiesen cargar.



## <a name="version-1705-june-13"></a>Versión 1705:13 de junio
*Versión 1705 (compilación 8201.2102)*

### <a name="access-feature-updates"></a>Access: Actualizaciones de características
-   **Cuadro de diálogo Novedades:** Cuadro de diálogo en el que se destacan las nuevas características de Access cuando se abre después de haberse actualizado con nuevas características. Este cuadro de diálogo también está disponible en a Archivo \> Cuenta \> Novedades.
-   **Soporte de números grandes (bigint):** Utilice el tipo de datos de número grande en las tablas de Access para calcular números grandes y vincular o importar desde bases de datos externas que utilicen un tipo de datos equivalente, como bigint en SQL Server. [Más información](https://blogs.office.com/2017/03/06/new-in-access-2016-large-number-bigint-support/)

### <a name="excel-feature-updates"></a>Excel: Actualizaciones de características
-   **Compatibilidad con Windows Information Protection (WIP):**    ahora Excel es una aplicación habilitada y puede diferenciar entre los datos personales y los datos corporativos, y determinar correctamente qué proteger, en función de las directivas configuradas.   [Más información](https://aka.ms/wiptechnet)
-   **Mejora de Obtener y transformar:** En el Editor de consultas, cree una columna nueva proporcionando valores de ejemplo. A medida que escribe, Excel detecta las transformaciones necesarias y muestra una vista previa de la columna nueva.
-   **Insertar vínculos recientes:** Adjunte fácilmente hipervínculos a sitios web o archivos basados en la nube recientes y cree nombres para mostrar significativos para los usuarios que usen lectores de pantalla. [Más información](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Personalizar el diseño de tabla dinámica predeterminado:** Configure una tabla dinámica de la forma que desee y comience con ese diseño cada vez que cree otra. [Más información](https://support.office.com/article/efd8569c-f07a-43c1-9db2-4f2912a0f94e)
-   **Mejoras de Obtener y transformar:** Los usuarios pueden crear columnas mediante ejemplos y dividir las columnas de una tabla en filas. Ahora, es más fácil especificar los parámetros para SAP HANA y agrupar los datos.
-   **Implementación centralizada de los complementos**: Los administradores pueden implementar y actualizar complementos para los usuarios o grupos desde el Centro de administración de Office 365. [Más información](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **Personalización de la barra de herramientas de acceso rápido:** Los iconos Subíndice y Superíndice pueden agregarse a la barra de herramientas de acceso rápido.
-   **Mejoras de Obtener y transformar:** Detección automática de carácter delimitador cuando se separan columnas utilizando el Editor de consultas. Elija qué archivo de ejemplo se utilizará con archivos binarios y especifique la recopilación del paquete a la que conectarse al utilizar el conector de DB2.
-   **Fuente Dubái:** Familia de fuentes que admite los idiomas de Europa occidental, así como los principales idiomas que usan el alfabeto árabe. [Más información](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Eliminación del fondo:** Quite un fondo de imagen con una herramienta de dibujo de forma libre.
-   **Mejoras de Obtener y transformar:** Utilice "Seleccionar tablas relacionadas" en el cuadro de diálogo del Navegador con los conectores ODCB y OLEDB, combine varios archivos directamente desde el cuadro de diálogo Vista previa de datos de la carpeta y utilice una nueva opción de menú contextual en la ventana Editor de consultas para insertar pasos nuevos en consultas existentes.
-   **Usar un lápiz para seleccionar y cambiar objetos:** seleccione controles de objeto con un lápiz digital para cambiar el tamaño, girar, mover y realizar otras operaciones.
-   **Gráfico de mapa:** compare valores y muestre categorías en regiones geográficas. [Más información](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)
-   **Imágenes SVG:** inserte y edite Scalable Vector Graphics (SVG) en libros. [Más información](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Insertar iconos:**   use iconos de una biblioteca estándar de archivos Scalable Vector Graphics (SVG) yendo a \> insertar \> iconos de ilustraciones. [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **Guardar en carpetas recientes:** guarde un libro en una carpeta que se ha usado recientemente mediante la pestaña Reciente cuando seleccione Archivo \> Guardar como.
-   **Mejoras en la accesibilidad:** compatibilidad mejorada para usar el teclado, Narrador y otra tecnología de asistencia para leer y editar libros. [Más información](https://support.office.com/article/51fcb17a-b15b-4b13-ae04-d4f38ece3f78)

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   Boletín de seguridad Microsoft [MS17-014](https://technet.microsoft.com/library/security/ms17-014): Actualización de seguridad para Microsoft Office (3217868)

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
-   Se corrige un problema que provocaba que en Excel non se estableciese la contraseña de protección de hojas cuando se aplicaba mediante programación en libros creados en Excel 2010 o versiones anteriores.
-   Se ha solucionado un problema que provocaba que Combinar y centrar no funcionara en hojas de cálculo agrupadas.
-   Se ha solucionado un problema que provocaba que las nuevas funciones que se introdujeron después de la presentación de Office 2016 (por ejemplo, UNIRCADENAS, CONCAT, SI.CONJUNTO, MAX.SI.CONJUNTO y MIN.SI.CONJUNTO) no estén disponibles.
-   Se soluciona un problema por el que Excel se bloquea cuando el usuario intenta aplicar permisos de nivel de celda.
-   Se soluciona un problema por el que, al guardar un archivo grande en OneDrive para la Empresa, este se bloquea y el usuario no lo puede editar hasta que cierra y vuelve a abrir Excel.
-   Se soluciona un problema por el que una nueva ventana aparece atenuada cuando se abre un libro .xls.
-   Se soluciona un problema donde Excel podría bloquearse al insertar hipervínculos.
-   Se soluciona un problema donde Excel podría fallar al agregar asignaciones XML.
-   Se soluciona un problema por el que el botón de comando de un complemento no funciona después de actualizar el complemento o después de quitar y descargar el complemento de nuevo desde la Tienda Office.
-   Se corrige un problema donde Excel podría bloquearse cuando se manipulan hojas DLL a través de VBA.
-   Se corrige un problema que provocaba que Excel se bloquease al seleccionar un cuadro combinado de control de formulario en una hoja de gráfico.

### <a name="onenote-feature-updates"></a>OneNote: Actualizaciones de características
-   **Compatibilidad con Windows Information Protection (WIP):** La aplicación OneNote ahora puede diferenciar entre los datos personales y los datos corporativos, y determinar correctamente cuáles se deben proteger basándose en las directivas configuradas. [Más información](https://aka.ms/wiptechnet)

### <a name="onenote-non-security-updates"></a>OneNote: Actualizaciones no relacionadas con la seguridad
-   Se corrige un problema que provocaba que el lienzo de OneNote ocultase contenido o actualizaciones cuando hubiese muchas fotografías en la vista.

### <a name="outlook-feature-updates"></a>Outlook: Actualizaciones de características
-   **Compatibilidad con Windows Information Protection (WIP):**    ahora Outlook es una aplicación habilitada y puede diferenciar entre los datos personales y los corporativos, lo que determina correctamente qué proteger, en función de las directivas configuradas.   [Más información](https://aka.ms/wiptechnet)
-   **Insertar vínculos recientes:** Adjunte hipervínculos a sitios web o archivos basados en la nube recientes y cree nombres para mostrar significativos para los usuarios que usen lectores de pantalla. [Más información](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Fuente Dubái:** Familia de fuentes que admite los idiomas de Europa occidental, así como los principales idiomas que usan el alfabeto árabe. [Más información](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Eliminación del fondo:** Quite un fondo de imagen con una herramienta de dibujo de forma libre.
-   **Comprobar el acceso a los archivos compartidos:** Outlook indica al usuario antes de tiempo si los destinatarios no podrán tener acceso a un archivo adjunto de OneDrive o SharePoint y le sugiere cómo solucionar el problema.
-   **Establecer permisos para los datos adjuntos:** Para los datos adjuntos de OneDrive o de SharePoint, el usuario puede establecer si los destinatarios de la organización o externos a ella tienen permisos de lectura o edición de los datos adjuntos.
-   **Panel de tareas anclable:** Deje el panel de tareas de complementos abierto mientras cambia entre los diferentes mensajes de un buzón. [Más información](https://blogs.msdn.microsoft.com/exchangedev/2017/01/26/pinnable-taskpane-in-outlook-2016/)
-   **Imágenes SVG:** inserte y edite Scalable Vector Graphics (SVG) en correos electrónicos. [Más información](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Insertar iconos:**   use iconos de una biblioteca estándar de archivos Scalable Vector Graphics (SVG) yendo a \> insertar \> iconos de ilustraciones.   [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2017-0106](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106): Vulnerabilidad de ejecución remota de código de Microsoft Outlook
-   [CVE-2017-0204](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204): Vulnerabilidad de omisión de característica de seguridad de Microsoft Office
-   [CVE-2017-8506](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8506): Ejecución remota de código de Microsoft Office
-   [CVE-2017-8507](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8507): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2017-8508](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8508): Vulnerabilidad de omisión de característica de seguridad de Microsoft Office

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones no relacionadas con la seguridad
-   Se corrige un problema que provocaba que el panel de navegación de Outlook dejase de representarse cuando la máquina tuviese poca memoria.
-   El ancho de los datos adjuntos se expande visualmente para acomodar la información de nombre y permisos de archivo.
-   Se soluciona un problema por el que el usuario no puede buscar archivos PST.
-   Se soluciona un problema por el que el usuario ve un nuevo tipo de almacén de "Microsoft Exchange" en el cuadro de diálogo "Nuevo archivo de datos de Outlook" y, si se selecciona este nuevo tipo de datos, el perfil del usuario no se puede usar.
-   Se soluciona un problema por el que no se muestra una imagen de un mensaje enviado desde un equipo con alta resolución de PPP.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Actualizaciones de características
-   **Compatibilidad con Windows Information Protection (WIP):**    ahora PowerPoint es una aplicación habilitada y puede diferenciar entre los datos personales y los datos corporativos, y determinar correctamente cuáles se deben proteger basándose en las directivas configuradas.   [Más información](https://aka.ms/wiptechnet)
-   **Insertar vínculos recientes:** Adjunte hipervínculos a sitios web o archivos basados en la nube recientes y cree nombres para mostrar significativos para los usuarios que usen lectores de pantalla. [Más información](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Implementación centralizada de los complementos**: Los administradores pueden implementar y actualizar complementos para los usuarios o grupos desde el Centro de administración de Office 365. [Más información](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **Fuente Dubái:** Familia de fuentes que admite los idiomas de Europa occidental, así como los principales idiomas que usan el alfabeto árabe. [Más información](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Eliminación del fondo:** Quite un fondo de imagen con una herramienta de dibujo de forma libre.
-   **Imágenes SVG:** inserte y edite Scalable Vector Graphics (SVG) en presentaciones. [Más información](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Insertar iconos:**   use iconos de una biblioteca estándar de archivos Scalable Vector Graphics (SVG) yendo a \> insertar \> iconos de ilustraciones. [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **Escritura en tiempo real durante la co-autoría:** Compruebe dónde están trabajando otros en la presentación y vea los cambios a medida que escriben. [Más información](https://support.office.com/article/0c30ee3f-8674-4f0e-97be-89cf2892a34d)
-   **Guardar en carpetas recientes:** guarde una presentación en una carpeta que se ha usado recientemente mediante la pestaña Reciente cuando seleccione Archivo \> Guardar como.
-   **Crear formas de lápiz precisas:** arrastre el borrador de segmentos para quitar el exceso de bits de lápiz, hasta la línea más cercana.
-   **Seleccionar y manipular objetos con un lápiz:** Utilice un lápiz digital para cambiar el tamaño de objetos, moverlos o girarlos usando sus controladores, o utilice los botones de un lápiz admitido para la selección de lazo de lápiz.
-   **Mejoras en la accesibilidad:** compatibilidad mejorada para usar el teclado, Narrador y otra tecnología de asistencia para leer y editar presentaciones. [Más información](https://support.office.com/article/3fce93f5-9ca8-42a6-bc1f-776749f6e32e)

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema por el que PowerPoint se bloquea cuando el usuario está en el panel Ideas de diseño, si el archivo mfplat.dll no está instalado en el equipo.
-   Se soluciona un problema por el que el botón de comando de un complemento no funciona después de actualizar el complemento o después de quitar y descargar el complemento de nuevo desde la Tienda Office.

### <a name="project-feature-updates"></a>Project: Actualizaciones de características
-   **Usar una lista desplegable para establecer rápidamente los predecesores:** Use la lista desplegable de los gráficos de Gantt para elegir los predecesores o sucesores que desea vincular a una tarea.
-   **Nombre de Resumen de tarea:**   campo de tarea de solo lectura que muestra el nombre de la tarea de Resumen de la tarea.  

### <a name="project-non-security-updates"></a>Project: actualizaciones no relacionadas con la seguridad
-   Se corrige el cuadro de diálogo Crear sitio de proyecto para que muestre la ubicación correcta del sitio ahora que cada plantilla de proyecto empresarial (EPT) tendrá su propia URL para los sitios de proyecto en Project Online.
-   Se corrige un problema que provocaba que el evento BeforeClose de VBA se desencadenara antes de que apareciera el mensaje para guardar y que no se tuviera ninguna manera mediante programación de determinar la respuesta del usuario al mensaje para guardar.
-   Se corrige un problema que provocaba que el indicador de % físico completado no se mostrara correctamente para las tareas con un inicio posterior a la fecha de estado del proyecto.
-   Se corrige un problema que provocaba que, en ocasiones, al asignar un costo y un recurso de trabajo a la misma tarea, no se pudiera cambiar el administrador de estado de la tarea.
-   Se corrige un problema que provocaba que, para determinados proyectos, se entrara en un bucle sin fin al redistribuir el proyecto entero.
-   Se corrige un problema que provocaba que las fechas de inicio y finalización de la tarea no se sincronizaran correctamente con una lista de tareas de SharePoint si se tenía unas opciones de configuración regional en español en concreto.
-   Se corrige un problema que provocaba que, en ocasiones, si se iniciaba el proceso de aprobaciones de estado desde el cliente de Project, este no acabara nunca y dejara el proyecto en un estado no utilizable.
-   Se corrige un problema que provocaba que, en la vista previa de impresión, no se mostraran correctamente los nombres de las tareas si había palabras en chino y en inglés.
-   Se ha solucionado un problema que provocaba que la copia de la escala de tiempo en PowerPoint como formas individuales no funcionara.
-   Se corrige un problema que provocaba que el cuadro de diálogo "Vínculos entre proyectos" mostrase de forma inesperada el valor "Archivo no encontrado".
-   Se soluciona un problema que provocaba que el usuario obtuviese resultados incoherentes al asignar recursos con unidades máximas en 0.
-   Se corrige un problema que provocaba que la fecha de inicio de la tarea se restableciese a Tan pronto como sea posible al eliminar una fecha de inicio de asignación, ignorando elementos como los predecesores, lo que provoca divisiones en las asignaciones.
-   Se corrige un problema que provocaba que, al abrir un archivo desde SharePoint a través del menú Recientes, el objeto se desprotegiese automáticamente incluso aunque la opción “¿Desea solicitar que los documentos estén desprotegidos para poder modificarlos?” estuviese habilitada.
-   Se corrige un problema que provocaba que, al ir directamente a la aplicación Perfiles de Project, se bloquease el programa.
-   Se corrige un problema que provocaba que las tareas programadas manualmente no se actualizasen correctamente para los usuarios que actualizaron desde Project 2013.
-   Se corrige un problema que provocaba que, al abrir un proyecto desde una lista de tareas de SharePoint, Project se bloquease al iniciar el proceso de sincronización de la tarea.
-   Se corrige un problema que provocaba que Project se bloquease a veces al ir a Crear equipo.
-   Se soluciona un problema por el que la información de línea base se pierde al guardar un proyecto.
-   Se soluciona un problema por el que las copias impresas son difíciles de leer para los planes de proyectos grandes.
-   Se soluciona un problema por el que los proyectos editados en Project Web App no muestran los valores correctos para los campos de fórmula.
-   Se soluciona un problema por el que la información de los campos personalizados de empresa de recursos no se guarda correctamente para un plan de proyecto.
-   Se soluciona un problema por el que la actualización de la información de porcentaje de trabajo completado actualiza la información de porcentaje de finalización de la tarea.
-   Se soluciona un problema por el que cambia la propiedad del proyecto cuando se guarda el proyecto.
-   Se soluciona un problema por el que se calcula incorrectamente el IRC de una tarea de resumen.
-   Se soluciona un problema por el que copiar y pegar tareas transfiere los datos de línea base y estos se guardan, incluso aunque el usuario no esté autorizado a guardar datos de línea base protegidos.
-   Se soluciona un problema por el que importar datos desde Excel produce una información de fecha incorrecta para tareas y asignaciones.
-   Se soluciona un problema por el que, después de abrir un informe, Project se bloquea al cerrarlo.
-   Se soluciona un problema por el que Project deja de funcionar al guardar un proyecto en el que una lista personalizada contiene la configuración de validación.
-   Se soluciona un problema por el que el carácter "\>" escrito en la columna Pruebas del cuadro de diálogo Definición de filtro no se interpreta correctamente con el significado de "es mayor que".
-   Se soluciona un problema con la visualización de las líneas de progreso en relación con el "plan de línea base".
-   Se soluciona un problema por el que la lista desplegable de nombres de campo no se muestra al personalizar los filtros.
-   Se soluciona un problema por el que no aparecen las vistas previas de los estilos de barra en el cuadro de diálogo Estilos de barra.

### <a name="publisher-non-security-updates"></a>Publisher: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema por el que Publisher no muestra imágenes TIF CMYK.

### <a name="skype-for-business-feature-updates"></a>Skype Empresarial: Actualizaciones de características
-   **Inserción de vínculos** Agregue un vínculo a la mensajería instantánea y a los chats de grupo y proporcione un texto descriptivo para el vínculo en lugar de la dirección URL completa.
-   **Screen sharing notification:** A notification displays in the conversation window when you’re sharing a screen in an IM conversation or when screen sharing continues after you leave a meeting. The notification reminds you that you are still sharing your screen and makes it easy to stop sharing by using the “Stop Sharing” button.
-   **Compatibilidad con Windows Information Protection (WIP):** Skype empresarial ahora es compatible como una aplicación de trabajo en curso.Al agregar Skype a la lista de aplicaciones permitidas, indica a Windows que no administra los datos personales.Windows protegerá los datos en nombre de Skype empresarial.   [Más información](https://aka.ms/wiptechnet)
-   **Opción de restablecimiento de contraseña:** Un vínculo de botón de restablecimiento aparece en la ventana de inicio de sesión cuando un usuario no puede iniciar sesión al menos una vez.

### <a name="skype-for-business-security-updates"></a>Skype Empresarial: Actualizaciones de seguridad
-   Boletín de seguridad Microsoft [MS17-013](https://technet.microsoft.com/library/security/ms17-013): Actualización de seguridad para el componente de gráficos de Microsoft (4013075)
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2017-0283](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0283): Vulnerabilidad de la ejecución remota de código de Uniscribe de Windows
-   [CVE-2017-8550](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8550): Vulnerabilidad de ejecución remota de código de Skype Empresarial

### <a name="skype-for-business-non-security-updates"></a>Skype Empresarial: Actualizaciones no relacionadas con la seguridad
-   Change message for attempted calls to users with audio disabled by policy from "Cannot complete the call" to "Cannot call because an IT administrator has restricted audio. Try using instant messaging or email instead and ask to check with their IT administrator."
-   Agregue el hipervínculo "¿Ha olvidado el PIN de acceso telefónico?" para las invitaciones a reuniones de los usuarios habilitados para la Conferencia RTC de Skype Empresarial Online.
-   Habilite la posibilidad de unirse a reuniones de Teams desde Skype Empresarial Online.
-   Cambie el volumen predeterminado de la sesión del altavoz del 40 % al 75 %.
-   Permita el cambio de tamaño de la lista de pestañas a un ancho mínimo menor.
-   Actualice las teclas de método abreviado para que coincidan con el orden de las pestañas.
-   Se corrige la dirección incorrecta del texto en hebreo al enviarse desde un dispositivo móvil.
-   Se corrige un problema con la información que anuncia un lector de pantalla para las características Presentar escritorio y Ceder el control.
-   Se muestran las salas abiertas además de las salas seguidas en las listas Seleccionar salas.
-   Se ha agregado la posibilidad de deshabilitar la capacidad VoIP mientras esté habilitada la aplicación personalizada RCC.
-   Se ha cambiado el lema de mensajería instantánea sin conexión a "Pruebe la aplicación para dispositivos móviles de Skype Empresarial".
-   Se ha corregido un problema que provocaba que una ventana de una conversación aceptada automáticamente se abriera como una ventana normal en lugar de una ventana minimizada y que, de forma inesperada, se apartara el foco de las otras ventanas.
-   Se ha solucionado un problema con el uso de un lector de pantalla en el cuadro de diálogo Opciones de reunión de Skype.
-   Se ha solucionado un problema que causaba que no apareciera el primer mensaje de una invitación en el correo electrónico de conversación perdida.
-   Se ha solucionado un problema que provocaba que se mostraran números de acceso telefónico duplicados al crear una invitación de reunión de Outlook mediante el botón Nueva reunión de Skype.
-   Se ha solucionado un problema en el que, cuando aparecía una barra de desplazamiento, no estaban seleccionadas todas las conversaciones de un historial de mensajería instantánea cuando se utilizaba Ctrl + A para seleccionarlo todo.
-   Se ha solucionado un problema en el que el texto de salida podía no tener el mismo formato exacto al usar el cmdlet Export-CsArchivingData.
-   Se ha solucionado un problema que causaba que el organizador de la reunión no pudiera ver el vídeo de participantes remotos al utilizar Reunirse ahora con 3 o más participantes.
-   Se ha solucionado un problema que provocaba que la primera línea de la lista de reuniones se mostrara en blanco cuando un usuario hacía clic con el botón derecho en el nombre de otro usuario de la lista de participantes.
-   Se soluciona un problema por el que los usuarios no pueden iniciar sesión al cambiar entre las redes internas y externas corporativas.
-   Se soluciona un problema por el que no se cierra el área de charla cuando se escala de MI a audio en la transferencia de consulta.
-   Se soluciona un problema por el que se truncan los nombres en las notificaciones del sistema cuando se utilizan llamadas simultáneas de dos extremos.
-   Se soluciona un problema por el que el nombre de archivo se trunca en las notificaciones para compartir archivos.
-   Se agrega información sobre herramientas para los botones de regreso a la llamada y transferencia.
-   Se pone el tiempo invertido en espera de la ventana de transferencia de consulta a disposición de los lectores de pantalla, como el Narrador.
-   Agregar la posibilidad de elegir entre mensajería instantánea o llamadas como preferencia predeterminada para la transferencia de consulta.
-   Se agrega la capacidad, cuando se realiza una transferencia de consultoría, para hacer clic en el botón "Transferir" para ver una lista de números de teléfono del contacto.
-   Se mejora un mensaje de error general para dejar claro que el problema es que el usuario tiene una licencia no válida o no se le ha asignado una licencia.
-   Se soluciona un problema por el que no todos los contactos se muestran en el título de la ventana de conversación cuando un usuario inicia una conversación con un contacto y, a continuación, agrega otro contacto.
-   Se soluciona un problema por el que el Narrador no lee la 2ª línea de las notificaciones.
-   Se soluciona un problema por el que se transfieren las llamadas a VoIP en lugar del número consultado.
-   Se soluciona un problema por el que el Narrador anuncia información incorrecta cuando el usuario se desplaza por la ventana Contenido.
-   Se soluciona un problema por el que los nombres del creador y del modificador no aparecen cuando se mueve el puntero sobre una anotación de una pizarra.

### <a name="visio-feature-updates"></a>Visio: Actualizaciones de características
-   **Buscar galerías de símbolos de terceros:** Busque las galerías de símbolos de terceros que proporcionan los proveedores de contenido seleccionados.
-   **Fragmentos de diapositiva:** Tome fragmentos de un dibujo de Visio y expórtelos como diapositivas a PowerPoint. [Más información](https://support.office.com/article/e7da404b-4208-49d1-9518-6fe1a4723657)

### <a name="word-feature-updates"></a>Word: Actualizaciones de características
-   **Compatibilidad con Windows Information Protection (WIP):**    ahora Word es una aplicación habilitada y puede diferenciar entre los datos personales y los datos corporativos, y determinar correctamente cuáles se deben proteger basándose en las directivas configuradas.   [Más información](https://aka.ms/wiptechnet)
-   **Insertar vínculos recientes:** Adjunte hipervínculos a sitios web o archivos basados en la nube recientes y cree nombres para mostrar significativos para los usuarios que usen lectores de pantalla. [Más información](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Implementación centralizada de complementos**: los administradores pueden implementar y actualizar complementos a usuarios o grupos desde el centro de administración de Office 365.   [Más información](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **Fuente Dubái:** Familia de fuentes que admite los idiomas de Europa occidental, así como los principales idiomas que usan el alfabeto árabe. [Más información](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Eliminación del fondo:** Quite un fondo de imagen con una herramienta de dibujo de forma libre.
-   **De un lado a otro:** Desplácese por las páginas de la vista Diseño de impresión deslizándolas de un lado a otro como en una pila de papel. [Más información](https://support.office.com/article/21bfd0ff-0e1f-4c43-b188-8b36dfe6dcf4)
-   **Usar un lápiz para seleccionar y cambiar objetos:** seleccione controles de objeto con un lápiz digital para cambiar el tamaño, girar, mover y realizar otras operaciones.
-   **Imágenes SVG:** inserte y edite Scalable Vector Graphics (SVG) en documentos. [Más información](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Insertar iconos:**   use iconos de una biblioteca estándar de archivos Scalable Vector Graphics (SVG) yendo a \> insertar \> iconos de ilustraciones.   [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **Guardar en carpetas recientes:** guarde un documento en una carpeta que se ha usado recientemente mediante la pestaña Reciente cuando seleccione Archivo \> Guardar como.
-   **Lectura mejorada con Herramientas de aprendizaje:** los nuevos comandos en el modo Lectura mejoran las habilidades de lectura ajustando el espaciado de texto, mostrando los saltos entre sílabas y resaltando cada palabra a medida que el documento se lee en voz alta. [Más información](https://support.office.com/article/29efa413-e2da-4cac-b2a5-2defc6d34fd9)
-   **Reconocimiento de formas:** Transforme automáticamente sus dibujos en formas utilizando Dibujar \> Convertir en formas.[Más información](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad
-   Boletín de seguridad Microsoft [MS17-014](https://technet.microsoft.com/library/security/ms17-014): Actualización de seguridad para Microsoft Office (3217868)
-   [CVE-2017-0254](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2017-0292](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0292): Vulnerabilidad de la ejecución remota de código de PDF de Windows 
-   [CVE-2017-8509](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8509): Vulnerabilidad de la ejecución remota de código de Microsoft Office  

### <a name="word-non-security-updates"></a>Word: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema por el que el usuario no puede buscar en archivos PST.
-   Se soluciona un problema por el que el usuario ve un nuevo tipo de almacén de "Microsoft Exchange" en el cuadro de diálogo "Nuevo archivo de datos de Outlook" y, si se selecciona este nuevo tipo de datos, el perfil del usuario no se puede usar.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2017-0199](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199): Vulnerabilidad de ejecución remota de código de Microsoft Office/WordPad con API de Windows
-   [CVE-2017-0260](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0260): Ejecución remota de código de Microsoft Office
-   [CVE-2017-0261](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2017-0262](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2017-8510](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8510): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2017-8512](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8512): Vulnerabilidad de la ejecución remota de código de Microsoft Office



## <a name="version-1701-may-9"></a>Versión 1701:9 de mayo
*Versión 1701 (compilación 7766.2084)*

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones no relacionadas con la seguridad
-   Se corrige un problema que provoca que los usuarios vean aparecer de forma intermitente e inesperada la selección de mensajes en la lista de mensajes al eliminar alguno.
-   Se corrige un problema que provoca bloqueos intermitentes.
-   Agregue la clave del Registro HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Outlook\\Options\\General\\DisableSupportBackstage para permitir que los administradores oculten la opción Soporte técnico de la pestaña Archivo.
-   Agregue la clave del Registro HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Outlook\\Options\\General\\DisableOutlookFeedbackFeatures para permitir que los administradores desactiven las opciones “Comentarios de Outlook 2016” y “Blog de Outlook” en Archivo \> Comentarios.

### <a name="skype-for-business-security-updates"></a>Skype Empresarial: actualizaciones de seguridad
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Vulnerabilidad de la ejecución remota de código de Microsoft Office

### <a name="skype-for-business-non-security-updates"></a>Skype Empresarial: actualizaciones no relacionadas con la seguridad
-   Se corrige un problema que provoca que una ventana de una conversación aceptada automáticamente se abra como una ventana normal en lugar de una ventana minimizada y que, de forma inesperada, se aparte el foco de las otras ventanas.

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad
-   [CVE-2017-0254](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Vulnerabilidad de la ejecución remota de código de Microsoft Office

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2017-0261](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2017-0262](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Vulnerabilidad de la ejecución remota de código de Microsoft Office



## <a name="version-1701-april-11"></a>Versión 1701:11 de abril
*Versión 1701 (compilación 7766.2076)*

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema por el que una nueva ventana aparece atenuada cuando se abre un libro .xls.

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2017-0106](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106): Vulnerabilidad de ejecución remota de código de Microsoft Outlook
-   [CVE-2017-0204](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204): Vulnerabilidad de omisión de característica de seguridad de Microsoft Office

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema por el que el usuario ve un nuevo tipo de almacén de "Microsoft Exchange" en el cuadro de diálogo "Nuevo archivo de datos de Outlook" y, si se selecciona este nuevo tipo de datos, el perfil del usuario no se puede usar.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema por el que se produce un error de falta de imagen cuando el usuario realiza una operación "Guardar como" en una ubicación alternativa de un archivo de PowerPoint que está almacenado en un medio extraíble, como una unidad USB.

### <a name="skype-for-business-non-security-updates"></a>Skype Empresarial: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema por el que los usuarios no pueden iniciar sesión al cambiar entre las redes internas y externas corporativas.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2017-0199](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199): Vulnerabilidad de ejecución remota de código de Microsoft Office/WordPad con API de Windows



## <a name="version-1701-march-14"></a>Versión 1701:14 de marzo
*Versión 1701 (compilación 7766.2071)*

### <a name="access-non-security-updates"></a>Access: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema donde no se puede descartar los menús desplegables.

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   Boletín de seguridad Microsoft [MS17-014](https://technet.microsoft.com/library/security/ms17-014): Actualización de seguridad para Microsoft Office (3217868)

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema donde Excel podría bloquearse al insertar hipervínculos.
-   Se soluciona un problema donde Excel podría fallar al agregar asignaciones XML.
-   Se soluciona un problema por el que el botón de comando de un complemento no funciona después de actualizar el complemento o después de quitar y descargar el complemento de nuevo desde la Tienda Office.
-   Se soluciona un problema donde Excel podría bloquearse cuando se manipulan hojas DLL a través de VBA.

### <a name="onenote-non-security-updates"></a>OneNote: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que el lienzo de la página de OneNote que deja de responder a los clics del mouse después de autenticar mediante el uso de un PIN en Windows 10 Versión 1607 (también conocido como Actualización de aniversario de Windows).
-   Se deshabilita el comportamiento de copia impresa de EDU específico optimizado cuando un usuario inserta un documento editable, como .docx o .pptx.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema donde aparecen incorrectamente conflictos de combinación cuando se trabaja en co-autoría.
-   Se soluciona un problema por el que el botón de comando de un complemento no funciona después de actualizar el complemento o después de quitar y descargar el complemento de nuevo desde la Tienda Office.
-   Se soluciona un problema en el que las llamadas al modelo de objeto VBA dan como resultado un error en tiempo de ejecución cuando se aplica a las formas de los gráficos.

### <a name="publisher-non-security-updates"></a>Publisher: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema por el que Publisher no muestra imágenes TIF CMYK.

### <a name="skype-for-business-security-updates"></a>Skype Empresarial: Actualizaciones de seguridad
-   Boletín de seguridad Microsoft [MS17-013](https://technet.microsoft.com/library/security/ms17-013): Actualización de seguridad para el componente de gráficos de Microsoft (4013075)

### <a name="word-security-updates"></a>Word: actualizaciones de seguridad
-   Boletín de seguridad Microsoft [MS17-014](https://technet.microsoft.com/library/security/ms17-014): Actualización de seguridad para Microsoft Office (3217868)

### <a name="word-non-security-updates"></a>Word: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un error con el consumo de memoria al usar determinadas configuraciones del monitor.
-   Se soluciona un problema por el que el botón de comando de un complemento no funciona después de actualizar el complemento o después de quitar y descargar el complemento de nuevo desde la Tienda Office.



## <a name="version-1701-february-22"></a>Versión 1701:22 de febrero
*Versión 1701 (compilación 7766.2060)*

### <a name="excel-feature-updates"></a>Excel: Actualizaciones de características
-   **Mejoras de conectividad y transformación de datos:** Expanda una lista en una nueva columna de texto con delimitadores entre los valores y especifique una opción de conmutación por error al conectarse a SQL.
-   **Mejoras de conectividad y transformación de datos:** Ahora se admite el tipo de datos de porcentaje y se han mejorado las experiencias de creación de funciones de combinación de binarios.
-   **Conector OLEDB:** Se utiliza el conector OLEDB en Obtener y transformar para crear una consulta para importar datos mediante la especificación de una cadena de conexión y, de forma opcional, una instrucción SQL para ejecutar.
-   **Reproducción de entrada de lápiz:** Vaya a Dibujo \> Reproducción de entrada de lápiz y reproduzca la escritura a mano hacia adelante y hacia atrás para ocultar y mostrar contenido, proporcione instrucciones paso a paso o comprenda mejor el flujo de ideas de otros. [Más información](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **Compatibilidad con CSV (UTF-8):** Abra y guarde archivos CSV que utilizan la codificación de caracteres UTF-8.
-   **Mejoras de conectividad y transformación de datos:** Selecciónelo para importar tablas relacionadas al cargar datos desde un origen OData, para agregar columnas personalizadas con valores de cálculo de funciones o para mostrar las dependencias entre consultas al usar una vista dedicada.
-   **Compartidos conmigo:** Vea los documentos que otros usuarios han compartido con usted yendo a Archivo \> Abrir \> Compartidos conmigo. [Más información](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **Cambiar los colores:** Use Información para establecer el color de la fuente, resaltado, relleno de forma y mucho más. [Más información](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   Boletín de seguridad Microsoft [MS16-148](https://technet.microsoft.com/library/security/ms16-148): Actualización de seguridad para Microsoft Office (3204068)

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que, cuando se establece el tema de Office en Negro, aparece un mensaje "Error inesperado" al hacer clic con el botón derecho en una consulta en el panel Consultas del libro.
-   Se soluciona un problema en el que Excel se bloquea cuando el usuario intenta tener acceso a opciones de tabla dinámica.
-   Se ha solucionado un problema que impedía que los valores de celda con texto y comillas dobles se exportasen correctamente al guardar como archivo CSV. o CSV UTF-8.
-   Se ha solucionado que provocaba que Excel se bloquease o dejase de responder al cerrarlo.
-   Se soluciona un problema en el que un hipervínculo con una fórmula de concatenación ignora parte del resultado de concatenación.
-   Se soluciona un problema donde al pegar una tabla de Excel en formato de texto enriquecido (RTF) en Word no se mantiene el formato de la tabla.
-   Se soluciona un problema en el que el usuario no puede realizar una acción Guardar como cuando el libro contiene una hoja de cálculo de macros de MS Excel 4.0.
-   Se hace que CTRL+ALT+5 sea el acceso directo para mover una selección a la capa de objeto para que coincida con otras aplicaciones.
-   Se soluciona un problema en el que, si se escribe en la barra de fórmulas y se usa una función con una lista desplegable, como BUSCARV, al pulsar Entrar para completar la fórmula, se selecciona el primer elemento de la lista desplegable Autocompletar en lugar de dejar el valor escrito como está.
-   Se soluciona un problema en el que, si se abre un archivo con formato de archivo binario (BIFF8) de Excel 97 - Excel 2003 con un hipervínculo en una hoja protegida, Excel interpreta que el archivo estaba dañado e intenta reparar o eliminar el contenido ilegible.

### <a name="onedrive-for-business-non-security-updates"></a>OneDrive para la Empresa: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema que, en ocasiones, provoca que una aplicación de Office se bloquee si el usuario intenta abrir o guardar un archivo en una carpeta sincronizada cuando GrooveIntlResource.dll no se puede cargar correctamente (situación poco probable en circunstancias normales) o que se bloquee el Explorador de Windows si el usuario se desplaza a una carpeta sincronizada mediante este.
-   Se soluciona un problema en el que OneDrive para la Empresa no está deshabilitado, incluso si se establece la clave del Registro adecuada para deshabilitarlo, cuando Office está configurado para recibir actualizaciones desde una ubicación que no sea la Content Delivery Network de Office (CDN).

### <a name="onenote-feature-updates"></a>OneNote: Actualizaciones de características
-   **Controlar la sincronización de archivos y la imagen:** Vaya a Archivo \> Opciones \> Sincronizar para controlar si todos los archivos y las imágenes se descargan automáticamente para todas las páginas en blocs de notas.

### <a name="onenote-non-security-updates"></a>OneNote: actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que OneNote se bloquea al imprimir una imagen más grande que la página.
-   Se soluciona un problema en el que un usuario no puede eliminar una plantilla de página personalizada.

### <a name="outlook-feature-updates"></a>Outlook: Actualizaciones de características
-   **Colaboración en los datos adjuntos en tiempo real:** Se cargan los datos adjuntos en OneDrive para la Empresa para que todos trabajen en la versión más reciente. Se usa el menú desplegable de los datos adjuntos para cargarlos o guardarlos.
-   **Tarjetas de resumen para reservas y paquetes de viajes:** Comprobar y realizar un seguimiento de reservas de viajes, así como entregas de paquetes, mediante tarjetas de resumen que se crean automáticamente en la Bandeja de entrada y el calendario. [Más información](https://blogs.office.com/2016/06/28/stay-on-top-of-your-travel-and-deliveries-with-outlook/)
-   **Redacción:** Proporciona una corrección avanzada y con contexto que ayuda a mejorar la escritura. [Más información](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que, cuando se hace clic con el botón secundario en un archivo adjunto en la lista de archivos adjuntos de una conversación, todos los elementos de menú contextual están visibles, en lugar de solo los elementos de menú correspondientes.
-   Se soluciona un problema en el que los destinatarios de los mensajes de correo electrónico en formato de texto enriquecido (RTF) no pueden abrirlos si los mensajes se han enviado con Information Rights Management.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Actualizaciones de características
-   **Subtítulos:** si una diapositiva contiene un vídeo con subtítulos, estos se pueden reproducir en la presentación.
-   **Varias pistas de audio:** Si una diapositiva contiene un vídeo con varias pistas de audio, estas se pueden reproducir en la presentación.
-   **Copia de secciones:** Copiar y pegar secciones entre presentaciones.
-   **Compartidos conmigo:** Vea los documentos que otros usuarios han compartido con usted yendo a Archivo \> Abrir \> Compartidos conmigo. [Más información](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **Reproducción de entrada de lápiz:** reproduzca la escritura a mano hacia adelante y hacia atrás para ocultar y mostrar contenido, proporcionar instrucciones paso a paso o comprender mejor el flujo de ideas de otros usuarios. [Más información](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **Grabaciones mejoradas:** cree una presentación formada por diapositivas grabadas, grabaciones de pantalla y vídeo insertado y, después, comparta el contenido grabado para que pueda verse de forma remota. También puede insertar cuestionarios para ayudar con el aprendizaje remoto y hacer que la presentación sea más interactiva, así como cambiar el color del trazo y usar controles más sencillos para grabar narraciones y audio.
-   **Mejoras para diseñadores:** Proporciona sugerencias de diseño usando SmartArt para listas de procesos con viñetas.
-   **Pestaña de cinta Grabación:** Agregar una pestaña de grabación mediante la personalización de la cinta de opciones.
-   **Cambiar los colores:** Use Información para establecer el color de la fuente, resaltado, relleno de forma y mucho más. [Más información](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)
-   **Zoom:** Crear un resumen interactivo de la presentación con vínculos de navegación automática. [Más información](https://support.office.com/article/9d6c58cd-2125-4d29-86b1-0097c7dc47d7)
-   **Abrir hipervínculos:** Use CTRL + clic para abrir hipervínculos mientras edita una presentación.
-   **Resaltado de texto:** Dirija la atención al texto importante con el marcador de resaltado del texto.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema que, al recortar una imagen, la parte recortada de la imagen aparece oscura.
-   Se soluciona un problema el que cuando se ejecuta Narrador en el modo Presentación, PowerPoint se bloquea cuando el usuario hace clic en un hipervínculo y el sitio tarda en cargarse.
-   Se soluciona un problema en el que la escritura en tiempo real durante la coautoría no funciona con tablas.
-   Se soluciona un problema en el que, al abrir PowerPoint en un equipo que tiene instalado Malwarebytes 3.0, aparece el error "Dejó de funcionar" o PowerPoint se bloquea.
-   Se soluciona un problema en el que la plantilla predeterminada no aparece en Archivo \> Nuevo.
-   Se soluciona un problema en el que se interrumpe y se retrasa la escritura cuando un archivo con fuentes incrustadas se guarda automáticamente.
-   Se soluciona un problema al copiar imágenes Scalable Vector Graphics (SVG) de Adobe Illustrator.

### <a name="project-feature-updates"></a>Project: Actualizaciones de características
-   **Campo bloqueado:** Se establece el valor en Sí para impedir que los integrantes del grupo envíen actualizaciones de una tarea.
-   **Etiquetas de escala de tiempo:** diferencia las barras de escala de tiempo con etiquetas para proporcionarles nombres descriptivos.
-   **Indicadores de progreso de la escala de tiempo:** use marcas y barras de progreso con color en la vista Escala de tiempo para mostrar hasta dónde ha llegado en cada tarea.
-   **Mejoras en la accesibilidad:** compatibilidad mejorada para usar el teclado, Narrador y otra tecnología de asistencia para leer y editar proyectos.

### <a name="project-non-security-updates"></a>Project: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que no se muestra ninguna línea de vínculo al crear un vínculo entre proyectos entre un proyecto principal y un subproyecto.
-   Se soluciona un problema donde los valores de fase temporal previstos no se guardan siempre correctamente en el formato XML, especialmente los valores de trabajar y de costo que incluyan las duraciones parciales.
-   Se soluciona un problema donde, al aplicar las actualizaciones de estado, el trabajo real se agrega a la asignación que no haya notificado el miembro del equipo.
-   Se soluciona un problema donde se muestran los valores de línea de base para un recurso, incluso cuando no se ha creado una línea de base para el recurso.
-   Se soluciona un problema donde la vista previa de impresión recorta el texto por lo que no está visible.
-   Se soluciona un problema en el que, al abrir un archivo .mpp de SharePoint mediante una URL contextual, el archivo se abre como desprotegido aunque la configuración "¿Requiere documentos para ser desprotegido antes de que se pueda editar?" esté habilitada.
-   Se soluciona un problema donde las actualizaciones a los recursos materiales de Project Web Apps cambian incorrectamente datos de fase temporal.
-   Se soluciona un problema en el que al abrir un proyecto que tenga una tarea de hito se pueda agregar una fecha de comienzo real a él aunque no tuviese una fecha en el momento en el que se guardó.
-   Se soluciona un problema producido cuando se volvía a numerar la estructura de descomposición de trabajo (WBS).
-   Se soluciona un problema en el que Project se bloquea cuando se cambia de una vista basada en cuadrícula y Narrador está activado.
-   Se soluciona un problema en el que se muestra un mensaje de error incorrecto sobre el truncamiento de datos de fase temporal al abrir un archivo XML.
-   Se soluciona un problema en el que al guardar una línea de base no se establecen correctamente los valores de fase temporal.
-   Se soluciona un problema en el que se omite el retraso de asignación cuando se leen datos de proyecto desde un archivo XML.
-   Se soluciona un problema en el que, al abrir un archivo de Project Online, la fecha de última modificación muestra la hora UTC en lugar de la hora ajustada de la zona horaria ajustada.
-   Se soluciona un problema en el que no aparecen bandas de color de agrupación para las filas que no son de agrupación al imprimir una vista de hoja.
-   Se soluciona un problema en el que una opción de reparación se muestra incorrectamente cuando el usuario examina una tarea que tiene una asignación más allá del problema de la unidad máxima.
-   Se soluciona un problema en el que el valor de un campo de código de esquema no se puede cambiar después de publicar el proyecto.
-   Se soluciona un problema en el que las barras de Gantt no tienen el tamaño correcto en pantallas con valores altos de PPP con una visualización del 175 %.
-   Se soluciona un problema en el que si el usuario establece un tiempo de retardo mediante el cuadro de diálogo Información de tarea, se establece incorrectamente en una duración transcurrida.
-   Se soluciona un problema en el que, al abrir determinados archivos XML, la fecha de inicio de la tarea no se establece correctamente debido a un problema con la asignación.

### <a name="skype-for-business-feature-updates"></a>Skype Empresarial: Actualizaciones de características
-   **Estilo de notificación de Windows:** Cambios en la apariencia de las notificaciones para las llamadas entrantes y las conversaciones. [Más información](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/New-Skype-for-Business-2016-on-Windows-Notifications-look-and/ba-p/39885)
-   **Transferencia Consultiva:** Desde una llamada, consulte con otro usuario a través de un mensaje instantáneo o una llamada antes de transferir la llamada a ese usuario. [Más información](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/Skype-for-Business-2016-on-Windows-Consultative-Transfer/ba-p/41122)
-   **Notificaciones de micrófono:** Establezca que se muestre una notificación en la ventana de conversación cuando el micrófono esté silenciado en el sistema operativo o si el micrófono no está recibiendo ningún audio.
-   **Deshabilitar "Mi número":** Use la entrada del Registro DisableDisplayMyNumber para deshabilitar "Mi número" en el teclado de marcado.

### <a name="skype-for-business-non-security-updates"></a>Skype Empresarial: Actualizaciones no relacionadas con la seguridad
-   Se cambian los botones de la sala de espera usados para admitir o denegar a los participantes desde texto a imágenes (una X o una marca de verificación).
-   Se cambia el texto de notificación de recordatorio de reunión de "Aceptar" a "Unirse".
-   Se actualiza el mensaje mostrado al remitente de un mensaje instantáneo cuando el estado del destinatario se establece en No molestar.
-   Se actualiza el mensaje mostrado al remitente de un mensaje instantáneo, cuando el destinatario está desconectado y "guardar en el histórico" está deshabilitada, para dejar claro que el destinatario no recibirá el mensaje de actualización.
-   Se agrega la capacidad para mover la barra de división vertical entre el historial de chat y la lista en un chat de grupo.
-   Se agrega la capacidad de cambiar el tamaño de la lista de pestañas en las ventanas de mensajes instantáneos o de salas de chat.
-   Se agrega la capacidad de seleccionar los salones de chat que se buscan al crear una fuente por tema.
-   Se soluciona un problema en el que el mensaje de detener aparecía en el medio de la conversación del historial de chat.
-   Se soluciona un problema en el que los mensajes duplicados aparecen en la ventana de conversación.
-   Se soluciona un problema en el que las acciones de notificación del sistema (Aceptar e Ignorar) no se muestran correctamente cuando hay un volumen elevado de notificaciones.
-   Se soluciona un problema en el que el usuario no puede escribir un mensaje después de utilizar ALT+TAB para abrir una ventana de conversación minimizada.
-   Se soluciona un problema en el que el botón MI está atenuado en la tarjeta de contacto de un usuario, a pesar de que MI está disponible.
-   Se soluciona un problema en el que no se vuelven a abrir varias ventanas de conversación con sus tamaños ni en sus ubicaciones anteriores después de cerrarse y abrirse de nuevo.
-   Se soluciona un problema en el que los vínculos no se abren cuando se seleccionan.
-   Se soluciona un problema en el que el texto de reunión en línea en el campo Región no se muestra correctamente para los caracteres que no son ingleses.
-   Se soluciona un problema en el que no se procesa correctamente la información de notificación, como la duración de la llamada, en idiomas de derecha a izquierda.
-   Se soluciona un problema en el que al crear una fuente por tema, borrar los resultados de búsqueda no restablece los resultados en una lista de salones seguidos.
-   Se soluciona un problema que provoca que Skype Empresarial deje de responder cuando se abren al mismo tiempo varias ventanas de conversación.
-   Se soluciona un problema en el que la ventana de la última conversación se queda en blanco cuando se cierran todas las demás pestañas.
-   Se soluciona un problema en el que el enfoque predeterminado no se encuentra en el área de entrada de chat cuando están deshabilitadas las conversaciones en pestañas.
-   Se soluciona un problema en el que el enlace "¿Olvidó su PIN de acceso telefónico?" no aparece en la invitación de reunión.
-   Se soluciona un problema en el que se recorta y trunca texto en las páginas de dispositivo General y Audio cuando se usan pantallas de configuración elevada de ppp al 175 % de la pantalla o superior.
-   Se soluciona un problema en el que Skype Empresarial se bloquea cuando el equipo se suspende o se reanuda cuando no hay ninguna red y el equipo es un equipo "siempre activado o conectado (AOAC)".
-   Se soluciona un problema en el que no se detecta ningún micrófono en una llamada al usar un dispositivo Polycom CX100.
-   Fix an issue where choosing a link such as \\\\servername or file:// in an IM message results in an error message instead of opening the location.
-   Se soluciona un problema en el que, en un entorno de Infraestructura de escritorio virtual (VDI) que usa enrutamiento basado en ubicación, el usuario no puede realizar o recibir llamadas RTC porque el servidor cree que la ubicación del usuario no es válida para las llamadas RTC.
-   Cuando el estado del usuario esté establecido en No molestar o Presentando, cambie la línea de asunto del correo enviado sobre un mensaje perdido de "Conversación perdida con \<nombre\>" a "\<Nombre\> te envió un mensaje en Skype Empresarial."
-   Para empezar, capture la marca de tiempo de la primera vez que inicie sesión en el dispositivo como parte de los [datos del censo](https://docs.microsoft.com/skypeforbusiness/legal-and-regulatory/data-collection-practices) para que sea más fácil identificar las tendencias de confiabilidad de inicio de sesión.
-   Se soluciona un problema en el que la opción de compartir un monitor secundario no aparece con determinadas configuraciones de monitor en la versión 1607 de Windows 10 (conocida también como Actualización de aniversario).
-   Se soluciona un problema en el que Skype Empresarial se bloquea al ampliar contenido compartido cuando la persona que lo comparte utiliza una implementación externa de Protocolo de escritorio remoto (RDP).
-   Se soluciona un problema en el que el panel Controles de audio no aparece cuando un usuario hace clic en el botón de controles en una llamada de audio de un entorno de Infraestructura de escritorio virtual (VDI).
-   Se soluciona un problema en el que los espectadores ven una pantalla negra cuando un usuario está ejecutando Windows 7 mientras comparte el primer monitor principal y, después, cambia para compartir un segundo monitor.
-   Se soluciona un problema donde determinados caracteres especiales, como la Y comercial (&), no pueden escribirse en el cuadro de entrada de búsqueda ni en el cuadro de la sección "¿Qué ocurre?".
-   Se soluciona un problema donde el recuento no leído no se muestra cuando existen mensajes instantáneos sin conexión perdidos.
-   Se soluciona un problema en el que las plantillas "Invitar por correo electrónico" mencionaban Lync en lugar de Skype.
-   Se soluciona un problema en el que falta el número de línea del área "Mi número" debajo del teclado de marcado.
-   Se soluciona un problema en el que el puntero del mouse no se muestra en el área de entrada de mensajes instantáneos después de enviar un mensaje en un chat.
-   Se soluciona un problema en el que Skype Empresarial deja de responder al iniciar sesión y hay un problema al cargar el grupo de memoria caché.
-   Se soluciona un problema donde Skype Empresarial se bloquea al iniciar sesión y restaurar conversaciones.
-   Se soluciona un problema en el que Skype Empresarial deja de responder al iniciar sesión después de reanudarse.
-   Se soluciona un problema en el que el vínculo de la reunión está deshabilitado si los servidores de Exchange de ambas organizaciones tienen TNEF deshabilitado.
-   Se soluciona un problema en el que una videollamada no puede reiniciarse si solo está produciéndose una conversación de mensajería instantánea.
-   Se soluciona un problema en el que las anotaciones de texto en una pizarra se pierden al guardar la pizarra como un archivo PNG.
-   Se soluciona un problema en el que la primera línea se oculta al escribir más de dos líneas en japonés en la ventana de mensajería instantánea.
-   Se soluciona un problema donde el carácter Y comercial (&) se reemplaza incorrectamente por un carácter de guion bajo en los nombres.
-   Se soluciona un problema con la dirección URL "Unirse a la reunión en línea" en una reunión programada.
-   Se soluciona un problema donde al pasar el mouse sobre una ventana no activa la ventana aunque el sistema operativo esté configurado para hacerlo.
-   Se soluciona un problema en el que los elementos del historial de conversación de llamadas salientes muestran al autor de la llamada en lugar del receptor de esta.
-   Se soluciona un problema donde F12 no guarda localmente una conversación.
-   Se soluciona un problema donde un correo electrónico de conversación perdida no contiene el mensaje instantáneo inicial.
-   Se soluciona un problema en el que un emoji puede agregarse en el área de texto de la mensajería instantánea incluso si el presentador ha deshabilitado la participación por MI.
-   Se soluciona un problema con el diseño del cuadro de diálogo de la opción Tonos de llamada y sonidos.
-   Se soluciona un problema en el que Skype Empresarial se bloquea al cerrar una ventana de conversación.
-   Se soluciona un problema en el que se produce un error en el inicio de sesión que no es DNS cuando el dominio se registra como un dominio personalizado.
-   Se soluciona un problema donde la configuración de notificaciones del chat persistente no se guarda o no se carga correctamente.
-   Se soluciona un problema en el que las ventanas de conversación de punto a punto existentes o las salas de chat no se muestran después de iniciar sesión, aunque se establezca la configuración para volver a abrir las conversaciones.
-   Se soluciona un problema en el que activar o desactivar el audio de las conversaciones activas provoca que otras ventanas de conversación aparezcan como si tuvieran mensajes sin leer.
-   Se soluciona un problema en el que los usuarios que están configurados para la omisión de medios no pueden reanudar una llamada de una puerta de enlace RTC después de que pongan la llamada en espera.
-   Se soluciona un problema en el que el usuario ve un cuadro azul en lugar de un vídeo al unirse a una reunión mediante una dirección URL con una implementación de terceros de RDP.
-   Se soluciona un problema en el que se muestra la parte de usuario de la dirección SIP en lugar del nombre para mostrar en una alerta del sistema.
-   Se soluciona un problema en el que, cuando Skype Empresarial se conecta a un servidor SIP a través del puerto 443 y hay un servidor proxy presente, se produce un retraso significativo en el proceso de inicio de sesión en caso de que el proxy no permita conexiones de ese tipo. Para implementar esta corrección, hay que agregar el registro DWORD EnableDetectProxyForAllConnections en HKEY\_CURRENT\_USER\\Software\\Microsoft\\UCCPlatform\\Lync y establecer el valor en 1.
-   Se soluciona un problema en el que, cuando se usaban las conversaciones en pestañas, al hacer doble clic en una pestaña y empezar a escribir, a veces el foco se movía a una pestaña diferente y seguía escribiendo en esa ventana de conversación.
-   Se soluciona un problema en el que las direcciones URL incluidas en un mensaje instantáneo no se pueden seleccionar en la ventana del historial de chats con el teclado.
-   Se soluciona un problema en el que se escuchará un sonido de pulsación de teclas si está seleccionada la casilla "Reproducir un sonido cuando alguien está escribiendo al ver una conversación de mensajería instantánea" en las opciones de Tonos y sonidos.
-   Se soluciona un problema en el que los cuadros de diálogo que aparecen no se anuncian al usar un lector de pantalla, como Narrador.
-   Se soluciona un problema en el que no se podía navegar con un teclado por el tutorial de primera ejecución ni se podía leer con un lector de pantalla, como Narrador.
-   Se soluciona un problema en el que el icono de presencia de la barra de tareas no se escalaba con una configuración de ppp elevado.
-   Se soluciona un problema en el que el botón Borrar campo del cuadro de búsqueda no se podía seleccionar con el teclado.
-   Se soluciona un problema en el que un usuario no podía iniciar una reunión si la invitación pertenecía a un usuario de otro grupo.
-   Se soluciona un problema en el que, cuando un usuario se agregaba a sí mismo a una reunión, se mostraba de forma incorrecta como un usuario distinto.
-   Se soluciona un problema en el que el icono de presencia del contacto en la notificación de cambio de estado estaba oculto para las llamadas entrantes para el jefe.
-   Se soluciona un problema en el que la velocidad de intermitencia del cursor de texto en la ventana de mensajería instantánea no coincidía con las propiedades del teclado establecidas en Windows.
-   Se soluciona un problema en el que un lector de pantalla anunciaba un nombre de contacto incorrecto para una conversación de grupo.
-   Se soluciona un problema en el que el usuario no podía seleccionar varios contactos con el teclado.
-   Se soluciona un problema en el que las fotos de usuarios no se podían recuperar desde Exchange.
-   Se soluciona un problema en el que el cliente de Skype Empresarial se conectaba a una implementación de Skype Empresarial Server en la red interna, en lugar de una implementación en la red externa, cuando el usuario se conectaba con un acceso directo.
-   Se soluciona un problema en el que el cliente de Skype Empresarial se bloqueaba al intentar resolver el nombre del propietario de la reunión.
-   Se soluciona un problema en el que, al cambiar una configuración de Windows mientras se iniciaba o cerraba Skype Empresarial, el programa se bloqueaba.
-   Se soluciona un problema en el que Skype Empresarial se bloqueaba si se abría la lista de participantes en un salón de chat persistente y se intentaba colocar el foco del teclado en la lista de participantes.
-   Se soluciona un problema en el que Skype Empresarial se bloqueaba al reanudarse si no había ninguna red disponible.

### <a name="visio-feature-updates"></a>Visio: Actualizaciones de características
-   **Complemento de modelado de base de datos:** Use el complemento para crear un modelo de base de datos de una base de datos existente que le sirva de ayuda para planear una nueva base de datos o comprender una existente. [Más información](https://support.office.com/article/fb034862-acfc-45bc-88b2-f33d1e1f8614), [Descargar complemento](https://go.microsoft.com/fwlink/p/?linkid=835953)
-   **Mejoras en la accesibilidad:** Compatibilidad mejorada para usar el teclado, Narrador y otra tecnología de asistencia para trabajar con formas, editar con otros usuarios y más.
-   **Plantillas de terceros y diagramas:** Examine o busque nuevas plantillas y diagramas de muestra disponibles a partir de determinados proveedores de contenido de terceros. El nombre del proveedor de terceros aparece en la miniatura.
-   **Compatibilidad con la entrada manuscrita:** Use el lápiz o el dedo para dibujar y anotar con las herramientas de la nueva pestaña Dibujar.

### <a name="word-feature-updates"></a>Word: Actualizaciones de características
-   **Mejoras en la accesibilidad:** compatibilidad mejorada para usar el teclado, Narrador y otra tecnología de asistencia para leer y editar documentos. [Más información](https://support.office.com/article/69aed572-336e-4722-a97e-23393cc481b2)
-   **Redacción:** Proporciona una corrección avanzada y con contexto que ayuda a mejorar la escritura. [Más información](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)
-   **Reproducción de entrada de lápiz:** Vaya a Dibujo \> Reproducción de entrada de lápiz y reproduzca la escritura a mano hacia adelante y hacia atrás para ocultar y mostrar contenido, proporcione instrucciones paso a paso o comprenda mejor el flujo de ideas de otros. [Más información](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **Editar con gestos de lápiz naturales:** Realice cambios en un documento dibujando un círculo alrededor para seleccionarlos y una cruz para eliminarlos. [Más información](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)
-   **Compartidos conmigo:** Vea los documentos que otros usuarios han compartido con usted yendo a Archivo \> Abrir \> Compartidos conmigo. [Más información](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **Cambiar los colores:** Use Información para establecer el color de la fuente, resaltado, relleno de forma y mucho más. [Más información](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="word-non-security-updates"></a>Word: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que ver un documento en modo de lectura impide que la tecla TAB funcione en un segundo documento visualizado en diseño de impresión.
-   Se soluciona un problema en el que Word se bloquea cuando se carga más de una biblioteca de gramática.
-   Se soluciona un problema en el que los trazos de lápiz desaparecen después de dos o tres trazos.
-   Se soluciona un problema en el que las comillas desaparecen al usar el Editor de métodos de entrada (IME) de Google.
-   Se soluciona un problema en el que un usuario no puede usar entradas manuscritas con controles de contenido o al realizar selecciones no contiguas.

### <a name="office-suite-feature-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de características
-   **Proporcionar comentarios:** Sugiera nuevas características o informe a Microsoft de qué le gusta o qué no funciona seleccionando Archivo \> Comentarios.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   Boletín de seguridad Microsoft [MS16-148](https://technet.microsoft.com/library/security/ms16-148): Actualización de seguridad para Microsoft Office (3204068)

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que usar CTRL + ALT + 7 o CTRL + ALT + 8 en un teclado alemán abre la herramienta de comentarios del usuario, en lugar de insertar el carácter adecuado.
-   Se soluciona un problema en el que TraceLogging causa un bloqueo en Windows 7 al instalar o actualizar a Office.
-   Se soluciona un problema en el que, al dibujar con lápiz y usar un ratón, al soltar el botón del ratón el lápiz se desplaza ligeramente.
-   Se corrige un problema en el que, después de insertar una imagen SVG en un documento de Office, la imagen SVG desaparece cuando se guarda el documento y se vuelve a abrir.
-   Fix an issue where Office shows the following error message during activation for non-English users: "The maximum length of the product key is 25 characters."
-   Se soluciona un problema en el que los formularios VBA que pueden provocar el orden Z de marcos dejan de funcionar o no se muestran correctamente.
-   Se soluciona un problema en el que una actualización activada por System Center Configuration Manager cambia el valor UpdateChannel en el Registro por algo que no es un canal de actualización válido.



## <a name="version-1609-january-10"></a>Versión 1609:10 de enero
*Versión 1609 (compilación 7369.2102)*

Nota: las actualizaciones de seguridad descritas en el boletín de seguridad Microsoft [MS17-002](https://technet.microsoft.com/library/security/ms17-002) no se aplican a la versión de Word en esta versión de canal.

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que Excel se bloquea al utilizar el cuadro de diálogo Modificar medida.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que, a veces, PowerPoint se bloquea al trabajar con formas.

### <a name="skype-for-business-non-security-updates"></a>Skype Empresarial: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que la opción de compartir un monitor secundario no aparece con determinadas configuraciones de monitor en la versión 1607 de Windows 10 (conocida también como Actualización de aniversario).
-   Se soluciona un problema en el que Skype Empresarial se bloquea al ampliar contenido compartido cuando la persona que lo comparte utiliza una implementación externa de Protocolo de escritorio remoto (RDP).
-   Se soluciona un problema en el que, cuando Skype Empresarial se conecta a un servidor SIP a través del puerto 443 y hay un servidor proxy presente, se produce un retraso significativo en el proceso de inicio de sesión en caso de que el proxy no permita conexiones de ese tipo. Para implementar esta corrección, hay que agregar el registro DWORD EnableDetectProxyForAllConnections en HKEY\_CURRENT\_USER\\Software\\Microsoft\\UCCPlatform\\Lync y establecer el valor en 1.

### <a name="word-non-security-updates"></a>Word: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que, al utilizar el método InsertXML, aparece un marcador de posición de un vínculo de imagen roto en lugar de la imagen en cuestión.

