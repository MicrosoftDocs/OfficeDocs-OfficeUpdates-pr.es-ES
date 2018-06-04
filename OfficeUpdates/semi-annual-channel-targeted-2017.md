---
title: Notas de la versión para las versiones en 2017 delimitadas anuales del canal (destino)
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 12/12/2017
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Normal
ms.collection: RelNotes_ProPlus
description: Proporciona los profesionales de TI con notas de la versión para las versiones delimitadas anuales del canal (destino) para Office 365 ProPlus en 2017
ms.openlocfilehash: 6014107ae2471707d226602cc71efaa24f1de310
ms.sourcegitcommit: 5dabd0a6045b54940da7821e2349ec78b6b99d00
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/04/2018
ms.locfileid: "19556402"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2017"></a>Notas de la versión para las versiones en 2017 delimitadas anuales del canal (destino)

Estas notas de la versión proporcionan información sobre nuevas características, actualizaciones de seguridad y las actualizaciones de seguridad comunes que se incluyen en las actualizaciones anuales delimitadas del canal (destino) para Office 365 ProPlus en 2017.
 
> [!NOTE]
> - El siguiente también proporciona la información acerca de las nuevas características, actualizaciones de seguridad y las actualizaciones de seguridad que no sean para Visio Pro a para el cliente de escritorio de Project Online y Office 365.
> - Esta información también se aplica a Office 365 empresarial, que es la versión de Office que se incluye con algunos planes de Office 365, como Business Premium.
> - Punto y anuales del canal (destino) se ha denominado primera versión para canal aplazada antes de septiembre de 2017.

## <a name="version-1708-december-12"></a>Versión 1708: 12 de diciembre
*Versión 1708 (compilación 8431.2131)*

 ### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2017-11935](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11935): vulnerabilidad de ejecución remota de código de Microsoft Excel

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones de seguridad que no sean
-   Corregir un problema donde el usuario incorrectamente ve un mensaje de error "Error grave" al abrir un Office 2007 o el libro más antiguos (.xls o .xla) con las macros.
-   Corregir un problema donde que podría provocar la pérdida de formato en una celda de texto enriquecido la apertura de un libro desde la línea de comandos.

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939): vulnerabilidad de divulgación de información de Microsoft Office

### <a name="powerpoint-security-updates"></a>PowerPoint: Actualizaciones de seguridad
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934): vulnerabilidad de divulgación de información de Microsoft PowerPoint

### <a name="project-non-security-updates"></a>Proyecto: Las actualizaciones de seguridad que no sean
-   Corregir un problema un problema donde nivel campo personalizado del proyecto pueden perderse datos en guarda.
-   Corregir un problema donde un error al guardar puede dañar un archivo y hacer que Project se bloquee en Abrir.
-   Corregir un problema donde abrir un plan de proyecto se puede producir un bloqueo.

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad
-   [Asesoría al 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Microsoft Office defensa en profundidad actualización



## <a name="version-1708-november-14"></a>Versión 1708: 14 de noviembre
*Versión 1708 (compilación 8431.2110)*

### <a name="access-non-security-updates"></a>Access: Las actualizaciones de seguridad que no sean
-   Corregir un problema donde intenta seleccionar texto en un cuadro de texto o cuadro combinado aparece para seleccionar todo el texto, en lugar de la selección de indicación.

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877): vulnerabilidad de omisión de característica de seguridad de Microsoft Excel
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878): vulnerabilidad de daños de memoria de Microsoft Excel
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884): Microsoft Office vulnerabilidad de daños en la memoria

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones de seguridad que no sean
-   Corregir un problema donde el usuario no puede cerrar un libro en Vista protegida cuando el nombre de archivo contiene corchetes.
-   Corregir un problema donde, cuando el usuario intenta insertar un objeto en un libro existente, Excel se bloquea cuando el usuario hace clic en Examinar.
-   Corregir un problema donde seleccionar "Cambiar el tamaño de la forma para corregir texto" (en la parte de cuadro de texto y las opciones de texto del panel de formato de forma) da como resultado ningún cambio a la forma.
-   Corregir un problema donde, al abrir un libro haciendo doble clic en él, no se cargan las fuentes de texto de celda y los formatos o se abren dos libros idénticos para una única plantilla.
-   Corregir un problema donde no cierre el primer libro que se crea cuando se inicia Excel cuando se abre o se crea un nuevo libro.
-   Corregir un problema donde la posición de la información sobre herramientas es mal alineada al arrastrar o arrastre rellenar.
-   Corregir un problema donde, al guardar un libro mediante el uso de archivo \> Guardar como un nombre de archivo que contiene los períodos aparece en blanco o truncado en el archivo Guardar del cuadro de diálogo.
-   Corregir un problema donde, al guardar un archivo de copia de sincronización, Office se produce un error al escribir en disco, pero mantiene Office cargar el archivo a OneDrive. Con esta revisión, usuario ahora verá un mensaje de error y no continúe con la carga.
-   Corregir un problema con la representación donde las líneas negras y los encabezados aparecen debido a un controlador de gráficos con errores.
-   Corregir un problema donde Excel deja de funcionar o no puede guardar el libro después de que se inserte un gráfico.
-   Corregir un problema de dónde se coloca incorrectamente la línea del salto de página en la vista previa de salto de página.

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones de seguridad y comunes
-   Corregir un problema donde el usuario ve el foco en la lista de mensajes inesperadamente saltar al eliminar los mensajes.
-   Corregir un problema que hace que el usuario vea mensajes de autenticación al interactuar con datos adjuntos.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones de seguridad que no sean
-   Corregir un problema donde, al guardar un archivo de copia de sincronización, Office se produce un error al escribir en disco, pero mantiene Office cargar el archivo a OneDrive. Con esta revisión, usuario ahora verá un mensaje de error y no continúe con la carga.
-   Corregir un problema donde edición y formato de texto después de una operación de deshacer de una tabla, PowerPoint se bloquea.
-   Corrección de un problema donde las referencias a Flash Player basado YouTube incrustar resultado de códigos en una nueva apertura de ventana para reproducir el vídeo. Antiguo insertar códigos ahora se actualizan a referencia HTML5 basa vídeos de YouTube para que reproducir correctamente en su lugar.

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad
-   [Asesoría al 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020): Microsoft Office defensa en profundidad actualización

### <a name="word-non-security-updates"></a>Word: Actualizaciones de seguridad que no sean
-   Corregir un problema cuando Word se bloquea cuando un usuario intenta guardar como para un documento existente en OneDrive para la empresa y, a continuación, cancela la operación de guardar o intenta combinar los cambios existentes.
-   Corregir un problema donde, al guardar un archivo de copia de sincronización, Office se produce un error al escribir en disco, pero mantiene Office cargar el archivo a OneDrive. Con esta revisión, usuario ahora verá un mensaje de error y no continúe con la carga.
-   Corregir un problema donde Word puede bloquearse si el usuario se desplaza a la ficha Insertar poco después de abrir Word.
-   Corregir un problema donde, tras hacer clic en el margen, caracteres se muestran en la esquina superior izquierda de la pantalla al escribir caracteres.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de seguridad
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882): Microsoft Office vulnerabilidad de daños en la memoria

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de seguridad comunes
-   Corregir un problema con el alejamiento y ajuste de escala en complementos de Office en el entorno de PPP dinámico.
-   Corregir un problema donde el nodo CurrentStatus del proveedor de servicios de configuración de Office (CSP) devuelve una cadena vacía, incluso si actualmente está instalado Office 365 ProPlus.
-   Solucionar un problema que hace que .box cambios de formato de archivo, lo que afecta la funcionalidad de las versiones anteriores de Office instaladas en el mismo equipo, debido a que los archivos de .box se comparten en todas las versiones de una aplicación de Office en el mismo equipo.
-   Corregir un problema que, en determinadas circunstancias cuando use la activación del equipo compartido, un mensaje de error aparece que indica que se ha ejecutado en un error que es lo que impide que funciona correctamente y que se pregunta si el usuario desea ejecutar una reparación de la aplicación.



## <a name="version-1708-october-10"></a>Versión 1708: 10 de octubre
*Versión 1708 (compilación 8431.2107)*

### <a name="access-non-security-updates"></a>Access: Las actualizaciones de seguridad que no sean
-   Corregir un problema donde una consulta no se ejecutará si la consulta tiene una combinación con una clave principal de una tabla vinculada de Microsoft Dynamics.
-   Corregir un problema donde no se muestran de posiciones decimales para los valores de moneda en una tabla de Microsoft Dynamics.

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones de seguridad que no sean
-   Corregir un problema donde Excel se bloquea al abrir un. Archivo XLL.
-   Corregir un problema donde el estilo de trama de una celda no se procesa correctamente después de agregar un encabezado o pie de página en la vista Diseño de página.
-   Corregir un problema donde pegar una copia de una tabla dinámica en otro libro podría dar como resultado un bloqueo.
-   Corregir un problema donde, cuando elija el comando Replace y se abre el cuadro de diálogo Buscar y reemplazar, que es el foco del cuadro de diálogo de la ficha Buscar en lugar de la ficha Reemplazar.
-   Corregir un problema donde Excel se bloquea al abrir el panel de actividad de un libro abierto desde un servidor de SharePoint anterior a SharePoint Server 2016.
-   Corregir un problema donde Excel se abre y muestra una ventana en blanco cuando se habilitan uno o varios complementos XLL.
-   Corregir un problema donde Excel se bloquea después de haber utilizado el botón formularios en un libro ya cerrado.
-   Corregir un problema que, cuando se usa el evento SheetBeforeRightClick, inserción de una columna que forma una intersección con celdas combinadas no expanda las celdas combinadas.

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2017-11774](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11774): vulnerabilidad de omisión de característica de seguridad de Microsoft Outlook
-   [CVE-2017-11776](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11776): vulnerabilidad de divulgación de información de Microsoft Outlook

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones de seguridad y comunes
-   Corregir un problema donde el vínculo "Más información" en sugerencias de directiva no está visible cuando se usa el tema de color gris oscuro.
-   Corregir un problema donde Outlook se bloquea cuando el usuario está intentando configurar una cuenta nueva y cierre la ventana sin completar la configuración de la cuenta.
-   Corregir un problema donde mostrar marcar como leído y marcar como no leído como opciones para los mensajes en la Bandeja de entrada compartida para un grupo.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones de seguridad que no sean
-   Corregir un problema donde PowerPoint se bloquea al abrir una presentación desde un servidor de SharePoint anterior a SharePoint Server 2016.

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad
-   [CVE-2017-11826](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11826): Microsoft Office vulnerabilidad de daños en la memoria

### <a name="word-non-security-updates"></a>Word: Actualizaciones de seguridad que no sean
-   Corregir un problema donde Word se bloquea al abrir el panel de actividad de un documento abierto desde un servidor de SharePoint anterior a SharePoint Server 2016.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de seguridad
-   [CVE-2017-11825](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11825): vulnerabilidad de ejecución remota de código de Microsoft Office

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de seguridad comunes
-   Corregir un problema donde no se muestra el progreso de la reparación en línea al usuario.
-   Corregir un problema donde no se muestran las propiedades de archivo de Office en el Explorador de archivos.
-   Corregir un problema donde se abrió en Agregar botones desaparecen de la cinta de opciones cuando hay un segundo documento de Office.
-   Corregir un problema donde no se pueden abrir algunos módulos VBA que tienen nombres con caracteres de doble byte.



## <a name="version-1708-september-12"></a>Versión 1708: 12 de septiembre
*Versión 1708 (compilación 8431.2079)*

### <a name="access-feature-updates"></a>Acceso: Actualizaciones de la característica
-   **(Propiedad) de nombre de etiqueta:** Mejorar la accesibilidad mediante la asociación de una etiqueta con un control en un formulario.
-   **Un nuevo elemento de edición sea más accesible:** Use un método abreviado de teclado rápido (Ctrl + E) para editar un nuevo elemento de un cuadro combinado o cuadro de lista.
-   **Conector de dynamics:** Importar datos desde o un vínculo a los datos almacenados en Microsoft Dynamics. [Obtener más información](https://support.office.com/article/636079c1-9fc3-4fca-8410-6596d62223da)
-   **Conector fuerza de ventas:** Importar datos desde o un vínculo a los datos almacenados en la fuerza de ventas. [Obtener más información](https://support.office.com/article/7375ffb6-1d6a-46f1-bb0c-c6ac3c58f5a0)

### <a name="excel-feature-updates"></a>Excel: Actualizaciones de la característica
-   **Mejoras en "Agregar columna de ejemplos":** Admite más transformaciones de fecha y hora, matemáticas y columna de índice.
-   **Las mejoras de rendimiento:** Excel abre libros complejos con varias hojas con mayor rapidez, por lo que puede analizar las fórmulas con intervalos de gran tamaño, filtrar una gran cantidad de filas, o copie y pegue más rápidamente.
-   **Insertar imágenes en línea:** Nueva página de aterrizaje para seleccionar imágenes e información de atribución se insertará automáticamente con la imagen.
-   **Conector de almacén de lago de datos de azure:** Los usuarios ahora pueden importar datos de almacén de lago de datos de Azure.
-   **Mejoras en "Añadir columna de ejemplos":** Admite sugerencias, más las operaciones de fecha y hora y transformaciones adicionales.
-   **Ficha de datos**: los botones de la cinta de opciones en la ficha datos se han reorganizado en dos nuevos grupos: Get y transformar datos y consultas y conexiones.
-   **Compartir consultas**: exportar cualquier definición de la consulta en un archivo de conexión de base de datos de Office (ODC) y, a continuación, compartirlo entre libros o con otros usuarios.
-   **De carga de datos:** Cargar datos de una consulta directamente en las tablas dinámicas o gráficos dinámicos sin tener que guardar los datos en el modelo de datos.
-   **Shared actividad de archivo:** Elija el botón actividad en la esquina superior derecha del archivo para ver cuándo se comparte un archivo en OneDrive para la empresa o SharePoint era shared, editado, nombre se ha cambiado o restaurar.
-   **Vínculos seguros:** Cuando un usuario hace clic en un vínculo, la protección de amenaza avanzada de Office 365 (ATP) inspecciona el vínculo para ver si es malintencionado. Si el vínculo se considera malintencionado, se redirige al usuario a una página de advertencia en lugar de la dirección URL de destino original. [Obtener más información](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Mejorado la funcionalidad de importación de datos:** Importar fácilmente y datos desde diversos orígenes de la forma. Administración de consultas de libro y conexiones con las consultas & conexión panel lateral y compartir las consultas con otros usuarios a través de los archivos ODC. [Obtener más información](https://support.office.com/article/ad78befd-eb1c-4ea7-a55d-79d1d67cf9b3)
-   **Cambios en los archivos compartidos**: ver quién ha realizado cambios en libros compartidos y restaurar las versiones anteriores. [Obtener más información](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)
-   **Selección de lazo con un botón del lápiz:** Botones del lápiz digitales a la entrada de lápiz de selección de lazo admite el uso sin necesidad de visitar la cinta de opciones.

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501): vulnerabilidad de daños en la memoria Microsoft Office
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502): Microsoft Office vulnerabilidad de daños en la memoria
-   [CVE-2017-8631](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8631): Microsoft Office vulnerabilidad de daños en la memoria
-   [CVE-2017-8632](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8632): vulnerabilidad de daños en la memoria Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones de seguridad que no sean
-   Corregir un problema donde Excel temporalmente se bloquea al expandir o contraer una tabla dinámica y mover los encabezados de tabla dinámica fuera de la pantalla.
-   Corregir un problema donde se omiten las fichas al copiar y pegar delimitado por texto de Word, por lo que el texto no se puede analizar en columnas.
-   Corregir un problema donde Excel se bloquea al abrir la publicación como cuadro de diálogo de página Web.
-   Corregir un problema donde una actualización de datos no se realiza correctamente o Excel se bloquea cuando utilizando los datos de un servidor de SQL Server Analysis Services y difieren de la configuración regional de Excel y la configuración regional del servidor SQL Server Analysis Services.
-   Corregir un problema donde aparecen errores al intentar guardar los cambios a los documentos que se sincronizan con el cliente de OneDrive.
-   Corregir un problema donde no se realizan cambios en cualquier lugar en una hoja de cálculo cuando hay una tabla dinámica con campos en el área de filtro, pero no hay campos en ningún otro lugar.

### <a name="outlook-feature-updates"></a>Outlook: Actualizaciones de la característica
-   **Mejoras en la accesibilidad:** Hemos introducido sea más fácil de leer y editar texto, tablas, listas e imágenes en el correo electrónico cuando se utiliza un lector de pantalla.
-   **Nueva configuración de cuenta:** Configurar nuevas cuentas con un nuevo asistente que requiere menos pasos manuales.
-   **Cuadro de diálogo Adjuntar vínculos:** Al adjuntar un vínculo mediante Adjuntar archivo en la cinta de opciones, puede seleccionar si se debe agregarlo como un vínculo o como datos adjuntos. Si no desea ver este cuadro de diálogo cada vez, vaya al archivo \> opciones \> General y especificar cómo desea que los vínculos que se asociará en "Opciones de datos adjuntos".
-   **Compatibilidad con datos adjuntos local:** Los archivos desde el servidor de SharePoint local se muestran como archivos recientes en el mensaje \> Adjuntar archivo local OneDrive para sitios de grupo de negocio y SharePoint aparecen bajo Adjuntar archivo \> examinar las ubicaciones de Web y archivos locales se pueden cargar a OneDrive local para sitios de negocio.
-   **Sectores empresariales para grupos:**  Se puede asignar un nivel de clasificación de negocio definido por el Administrador de inquilinos, como confidencial, al crear o editar un grupo, y esa clasificación aparece en el encabezado de grupo.
-   **Acceso de invitado a los grupos de Office 365:** Colaborar con personas fuera de la organización mediante la concesión de acceso a las conversaciones en grupo, los archivos, las invitaciones de calendario y el Bloc de notas de grupo. [Obtener más información](https://support.office.com/article/bfc7a840-868f-4fd6-a390-f347bf51aff6)
-   **Los mensajes que se pueden procesar:** Los programadores pueden crear mensajes para facilitar a los usuarios realizar acciones simples o rápidas directamente desde Outlook sin tener que cambiar a una aplicación independiente o un sitio web externo. [Obtener más información](https://dev.office.com/blogs/create-more-engaging-conversations-with-new-actionable-messages-updates-announced-at-microsoft-build)

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571): vulnerabilidad de omisión de característica de seguridad de Microsoft Office Outlook
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572): vulnerabilidad de divulgación de información de Microsoft Office Outlook
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663): vulnerabilidad de daños de memoria de Microsoft Office Outlook

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones de seguridad y comunes
-   Corregir un problema en el que esté no se puede configurar una cuenta IMAP en Outlook.
-   Corregir un problema que hace que un error intermitente al abrir Outlook.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Actualizaciones de la característica
-   **Insertar imágenes en línea:** Nueva página de aterrizaje para seleccionar imágenes e información de atribución se insertará automáticamente con la imagen.
-   **Títulos para vídeos cerrados:** Agregar títulos cerrados a un vídeo para que sea más accesible. [Obtener más información](https://support.office.com/article/a16745e1-b3da-4428-b2a7-ff0c8b758d0b)
-   **Incluir comentarios en una grabación:** Incluir vídeo de usted comentar al realizar una grabación de una presentación. Las grabaciones pueden incluir animaciones, entrada de lápiz, audio y vídeo.
-   **Shared actividad de archivo:** Elija el botón actividad en la esquina superior derecha del archivo para ver cuándo se comparte un archivo en OneDrive para la empresa o SharePoint era shared, editado, nombre se ha cambiado o restaurar.
-   **Creación de texto alternativo:** Un servicio basado en la nube genera automáticamente texto alternativo para las imágenes en una presentación.
-   **Vínculos seguros:** Cuando un usuario hace clic en un vínculo, la protección de amenaza avanzada de Office 365 (ATP) inspecciona el vínculo para ver si es malintencionado. Si el vínculo se considera malintencionado, se redirige al usuario a una página de advertencia en lugar de la dirección URL de destino original. [Obtener más información](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Mejoras del diseñador:** Se recomienda ideas de diseño profesional para las listas orientado a la acción.
-   **Cambios en los archivos compartidos:** Ver quién ha realizado cambios en presentaciones compartidas y restaurar las versiones anteriores. [Obtener más información](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="powerpoint-security-updates"></a>PowerPoint: Actualizaciones de seguridad
-   [CVE-2017-8742](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8742): vulnerabilidad de ejecución remota de código en PowerPoint
-   [CVE-2017-8743](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8743): vulnerabilidad de ejecución remota de código en PowerPoint

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones de seguridad que no sean
-   Corregir un problema donde caracteres para el usuario final definido (EUDCs) que están vinculados a las fuentes no se muestren.

### <a name="project-non-security-updates"></a>Proyecto: Las actualizaciones de seguridad que no sean
-   Corregir un problema donde la apertura de ciertos archivos de Project Online, Project se bloquea.
-   Corregir un problema donde comienzo real puede ser erróneamente desactivada cuando se establece el trabajo restante.
-   Corregir un problema donde asignación fecha de comienzo real podría mostrar los datos diferentes que se informó por el recurso a través de estado en Project Web App.
-   Corregir un problema donde se puede programar el trabajo real si se cambia la fecha de finalización de la tarea.
-   Corregir un problema donde si copiar y pegar campos de costo, los valores pegados podrían no coincidir exactamente con los valores copiados debido a un problema de redondeo.
-   Corregir un problema donde no se copian los datos de fase temporal para recursos de presupuesto al guardar desde una línea de base en otro.
-   Corregir un problema donde el campo de estado no siempre se calcula correctamente para las tareas de resumen.
-   Corregir un problema donde trabajo real erróneamente obtiene transfiere a un recurso de empresa cuando reemplaza un recurso local y trabajo protegido está habilitado.
-   Corregir un problema donde Project se bloquea si dispone de una tabla, donde la primera columna es el nombre de la tarea, la columna está bloqueada y hacer clic en una tarea.
-   Corregir un problema donde puede asignar el mismo recurso varias veces a la misma tarea a través de la vista Uso de tareas.
-   Corregir un problema donde los valores de los campos personalizados de número pueden perderse al abrir archivos XML.
-   Corregir un problema donde sangría de la tarea de nivel superior no la sincronización correctamente de Project a una lista de tareas de SharePoint.
-   Corregir un problema donde si importar información de la asignación, recurso o tarea desde un libro de Excel, los valores en el campo trabajo se pueden omitir.
-   Corregir un problema donde los valores de línea base con fases temporales no coinciden con los valores iniciales al guardar un proyecto en el formato de archivo XML.
-   Corregir un problema donde el cliente del proyecto no se abre un proyecto ya que piensa que el proyecto está desprotegido cuando realmente no lo está.
-   Solucionar un problema de modo que abrir los archivos de proyecto desde un servidor de archivos con alta latencia open con mayor rapidez.

### <a name="skype-for-business-security-updates"></a>Skype para la empresa: actualizaciones de seguridad
-   [CVE-2017-8676](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8676): Windows GDI + vulnerabilidad de divulgación de información
-   [CVE-2017-8695](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8695): vulnerabilidad de divulgación de información de componente de gráficos
-   [CVE-2017-8696](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8696): ejecución remota de código de componente de gráficos de Microsoft

### <a name="skype-for-business-non-security-updates"></a>Skype para la empresa: actualizaciones de seguridad comunes
-   Agregar cuadro de diálogo que explica por qué un usuario es no puede unirse a una reunión cuando determinados puertos están bloqueados o IP no están en la lista blanca.
-   Corregir un problema donde los mensajes no leídos en salones de chat persistentes se marcan como leídos al hacer clic en las fichas de conversación de mensajería instantánea.
-   Corregir un problema donde mensajería instantánea entrante notificaciones del sistema experiencia un retraso de segundo varias.
-   Corregir un problema donde un contacto de AD se muestra como un número de teléfono en lugar del nombre del contacto cuando está deshabilitada la sincronización con Exchange.
-   Corregir un problema donde los usuarios anónimos unirse están bloqueados se unan a cuando se deshabilita la federación y unión anónima no se bloquea explícitamente por el organizador de la reunión.
-   Corregir un problema donde se muestra incorrectamente el número de invitados a Organizador para las reuniones que superan el límite de la reunión.
-   Corregir un problema donde no se muestra el número de teléfono en la notificación del sistema en las llamadas entrantes de RTC.
-   Corregir un problema que, cuando se usa la tecla SUPR al cambiar el nombre de un grupo de la lista de contactos, se elimina todo el grupo.
-   Corregir un problema donde se descarta la notificación de uso compartida en una conversación de mensajería instantánea antes de se deja de compartir.
-   Corregir un problema donde la pantalla de inicio de sesión está en blanco para algunos idiomas distintos del inglés.
-   Corregir un problema donde caracteres no ingleses en conversaciones y el historial de chat aparecerán dañados.
-   Muestra el número de teléfono del autor de la llamada para una llamada entrante controlada por el operador automático de organizativa si no se conoce el nombre del usuario.
-   Agregar una configuración dentro de banda que permite la restricción de "Cualquier persona (sin restricciones)" como una opción para "estas personas no tienen que esperar en la sala de espera".
-   Agregar llamadas a la capacidad de activar o desactivar self-vídeo para P2P vídeo en VDIv2.
-   Corregir un problema donde mostrar números duplicados de los contactos en el menú de lista desplegable de la llamada.
-   Corregir un problema donde se quitan los delegados para los usuarios que mover entre Skype para la empresa y Skype para empresarial básica.
-   Corregir un problema donde no conectado no está visible cuando se usa el habilitar sin conexión y las directivas de cliente de dirección URL de estado personalizados.
-   Ampliar el botón unirse a la reunión para corregir el truncamiento de algunos idiomas localizados.
-   Aumentar la importancia de los mensajes de alta importancia en la conversación.
-   Agregar Office y Skype para los tipos de extensión de archivo profesionales en listas de bloqueo de transferencia de archivo permitido.
-   Correcciones de localización en invitaciones a reuniones de Outlook para el texto de pie de página de la reunión se establecen en no está en inglés.
-   Corregir un problema donde los nombres de remitente pueden cambiarse en las conversaciones de varios usuarios.
-   Corregir un problema en caso de que la ventana de conversación en blanco no aparecen hasta que se ha unido correctamente a una reunión.
-   Corregir un problema donde la información de campo de departamento en una tarjeta de contacto está vacía en los resultados de búsqueda si el campo de título está vacío.
-   Corrección de errores de inicio de sesión para los usuarios migran desde local a en línea debido a reglas de firewall.
-   Agregar una nueva clave del Registro DWORD para corregir un problema donde, cuando un usuario inicia sesión en el cliente en una red externa a realizar LyncAutoD, el cliente restablece la clave del registro OAuthUsed en false. Para corregir el problema, establezca el valor en 1 para EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket en HKEY\_actual\_usuario\\Software\\Microsoft\\Office\\16.0\\Lync\\\<SipID\>.

### <a name="visio-feature-updates"></a>Visio: Actualizaciones de la característica
-   **Crear diagramas de los datos de Excel:** Crear automáticamente un diagrama de flujo básico o un diagrama de flujo de funciones cruzadas de datos de Excel mediante el uso de nuevas plantillas de visualizador de datos. [Obtener más información](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)
-   **Vínculos seguros:** Cuando un usuario hace clic en un vínculo, la protección de amenaza avanzada de Office 365 (ATP) inspecciona el vínculo para ver si es malintencionado. Si el vínculo se considera malintencionado, se redirige al usuario a una página de advertencia en lugar de la dirección URL de destino original. [Obtener más información](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)

### <a name="visio-non-security-updates"></a>Visio: Actualizaciones de seguridad y comunes
-   Corregir un problema donde no reciben los complementos COM eventos de documento abierto cuando se abre un archivo de Visio mediante un doble clic en un icono de archivo o un nombre de archivo.

### <a name="word-feature-updates"></a>Word: Actualizaciones de la característica
-   **Insertar imágenes en línea:** Nueva página de aterrizaje para seleccionar imágenes e información de atribución se insertará automáticamente con la imagen.
-   **Creación de texto alternativo:** Un servicio basado en la nube genera automáticamente texto alternativo (texto alt) para imágenes en un documento.
-   **Shared actividad de archivo:** Elija el botón actividad en la esquina superior derecha del archivo para ver cuándo se comparte un archivo en OneDrive para la empresa o SharePoint era shared, editado, nombre se ha cambiado o restaurar.
-   **Vínculos seguros:** Cuando un usuario hace clic en un vínculo, la protección de amenaza avanzada de Office 365 (ATP) inspecciona el vínculo para ver si es malintencionado. Si el vínculo se considera malintencionado, se redirige al usuario a una página de advertencia en lugar de la dirección URL de destino original. [Obtener más información](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Cambios en los archivos compartidos:** Ver quién ha realizado cambios en documentos compartidos y restaurar las versiones anteriores. [Obtener más información](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="word-non-security-updates"></a>Word: Actualizaciones de seguridad que no sean
-   Corregir un problema donde la Word se cierra inesperadamente al cargar el complemento de Grammarly.
-   Corregir un problema donde, en determinadas condiciones, Word se bloquea al intentar recuperar archivos basados en la nube.
-   Corregir un problema donde no se puede girar las formas dentro del lienzo de dibujo.
-   Corregir un problema que, cuando se escribe en coreano, consonantes y vocales están incorrectamente separadas.
-   Guardar un documento como un archivo PDF guarda el documento como una versión 1.7 PDF.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de seguridad
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570): vulnerabilidad de ejecución remota de código de Microsoft Office
-   [CVE-2017-8630](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8630): vulnerabilidad de daños en la memoria Microsoft Office
-   [CVE-2017-8744](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8744): vulnerabilidad de daños en la memoria Microsoft Office

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de seguridad comunes
-   Solucionar un problema que impide que la ¿qué es un cuadro de diálogo nuevo que no aparezca.
-   Corregir un problema donde al hacer clic en la ficha Draw hace que la aplicación se bloquee para algunos usuarios.
-   Corregir un problema donde colocar el puntero sobre un Control común que tiene una información sobre herramientas en él hace que se bloquee la aplicación.
-   Corregir un problema donde un mensaje de error de licencia aparece cuando el uso de controles comunes.
-   Solucionar un problema con cómo algunos archivos de programa están firmados, lo que provoca que los programas antivirus marcar esos archivos, así como los problemas de protección o acceso a datos en Windows información protección (trabajo en curso).
-   Agregar support.to permitir que los usuarios que trabajan en versiones de 64 bits de Office para abrir los archivos de macro que contienen controles mscomctl.ocx.
-   Mejorar la accesibilidad de los controles que se utilizan en mscomctl.ocx.
-   Corregir un problema donde comandos aparecen en la cinta de opciones o en los cuadros de diálogo de personalización de la barra de herramientas de acceso rápido.



## <a name="version-1705-august-8"></a>Versión 1705: 8 de agosto
*Versión 1705 (compilación 8201.2171)*

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones de seguridad y comunes
-   Corregir un problema con arrastrar la barra de desplazamiento para desplazarse por una lista de mensajes.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de seguridad comunes
-   Solucionar un problema con cómo algunos archivos de programa están firmados, lo que provoca que los programas antivirus marcar esos archivos, así como los problemas de protección o acceso a datos en Windows información protección (trabajo en curso).
-   Solucionar un problema que impide que la ¿qué es un cuadro de diálogo nuevo que no aparezca.



## <a name="version-1705-july-27"></a>Versión 1705: 27 de julio
*Versión 1705 (compilación 8201.2158)*

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones de seguridad que no sean
-   Corregir un problema donde aparecen errores al intentar guardar los cambios a los documentos que se sincronizan con el cliente de OneDrive.
-   Corregir un problema donde Excel se bloquea cuando se agregan datos de hoja de cálculo a un modelo de datos y el tema de contraste alto se establece en negro.

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571): vulnerabilidad de omisión de característica de seguridad de Microsoft Office Outlook
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572): vulnerabilidad de divulgación de información de Microsoft Office Outlook
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663): vulnerabilidad de daños de memoria de Microsoft Office Outlook

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones de seguridad que no sean
-   Corregir un problema donde se agrega una forma después de que otro usuario cambia el diseño, un error de combinación.

### <a name="word-non-security-updates"></a>Word: Actualizaciones de seguridad que no sean
-   Corregir un problema que, cuando se escribe en coreano, consonantes y vocales están incorrectamente separadas.
-   Corregir un problema donde la dirección de entrega en los sobres se imprime demasiado cerca hasta el borde izquierdo.



## <a name="version-1705-july-13"></a>Versión 1705: 13 de julio
*Versión 1705 (compilación 8201.2136)*

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501): vulnerabilidad de daños en la memoria Microsoft Office
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502): Microsoft Office vulnerabilidad de daños en la memoria

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones de seguridad que no sean
-   Corregir un problema donde Excel se bloquea para los libros que contienen vínculos externos.
-   Corregir un problema donde pegar las celdas de Excel a Word muestra ceros en las celdas, incluso si no está seleccionada la opción "Mostrar un cero en las celdas que tienen un valor cero".

### <a name="project-non-security-updates"></a>Proyecto: Las actualizaciones de seguridad que no sean
-   Corregir un problema donde los valores que se han seleccionado para una tabla de gráfico no están visibles en el panel de gráfico o tabla.

### <a name="skype-for-business-non-security-updates"></a>Skype para la empresa: actualizaciones de seguridad comunes
-   Corregir un problema en una ventana de conversación no se muestra en segundo plano al unirse a una reunión y se muestra el cuadro de diálogo de combinación de dispositivos de audio para el usuario.
-   Corregir un problema en el vínculo de la reunión desde Outlook no siempre pasa URI interno correctamente.
-   Ampliar el botón unirse a la reunión para corregir el truncamiento de algunos idiomas localizados.

### <a name="word-non-security-updates"></a>Word: Actualizaciones de seguridad que no sean
-   Corregir un problema donde las tablas no se muestren correctamente después de determinadas acciones.
-   Corregir un problema donde varias modificaciones a citas algún tiempo aparece como una única acción de deshacer en lugar de acciones individuales consecutivas.
-   Corregir un problema donde deshacer está deshabilitado después de determinadas acciones.
-   Corregir un problema para evitar la pérdida de datos posible después de ciertas acciones de deshacer.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de seguridad
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570): vulnerabilidad de ejecución remota de código de Microsoft Office

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de seguridad comunes
-   Corregir un problema que provoca que las actualizaciones de desatendida de Office 2013 a Office 2016 se lleve a cabo cuando se usa System Center Configuration Manager.
-   Corregir un problema donde no cargan complementos heredados implementados desde el almacén a través del catálogo corporativo.



## <a name="version-1705-june-13"></a>Versión 1705: 13 de junio
*Versión 1705 (compilación 8201.2102)*

### <a name="access-feature-updates"></a>Acceso: Actualizaciones de la característica
-   **¿Qué es el cuadro de diálogo nuevo:** Un cuadro de diálogo que resalta las nuevas características de Access aparece cuando se abre Access después de que Access se ha actualizado con las nuevas características. El cuadro de diálogo también está disponible, vaya al archivo \> cuenta \> What ' s New.
-   **Compatibilidad con gran número (bigint):** Use el tipo de datos de gran número de tablas de Access para calcular los números de gran tamaño y para vincular o importar desde bases de datos externas que usan un tipo de datos equivalente, como bigint en SQL Server. [Obtener más información](https://blogs.office.com/2017/03/06/new-in-access-2016-large-number-bigint-support/)

### <a name="excel-feature-updates"></a>Excel: Actualizaciones de la característica
-   **Soporte técnico de protección de información de Windows (curso):**   Excel es ahora una aplicación mejorada y puede diferenciar entre los datos personales y corporativos, determinar correctamente que se va a proteger, en función de las directivas configuradas.  [Obtener más información](https://aka.ms/wiptechnet)
-   **Obtener & transformación mejora:** En el Editor de consultas, cree una nueva columna al proporcionar valores de ejemplo. Mientras se escribe, Excel detecta las transformaciones necesarias y muestra una vista previa de la nueva columna.
-   **Insertar vínculos recientes:** Fácilmente adjuntar hipervínculos a archivos recientes basados en la nube o sitios Web y crear nombres para mostrar significativo para los usuarios de lectores de pantalla. [Obtener más información](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Personalizar el diseño de tabla dinámica predeterminado:** Configurar una tabla dinámica de la forma que le gusta y empiece con ese diseño cada vez que cree una nueva tabla dinámica. [Obtener más información](https://support.office.com/article/efd8569c-f07a-43c1-9db2-4f2912a0f94e)
-   **Obtener & transformación mejoras:** Los usuarios pueden crear nuevas columnas de ejemplo y dividir las columnas de tabla en las filas. Especificar parámetros para SAP HANA y agrupar datos ahora están más fácil.
-   **Implementación centralizada de complementos**: los administradores pueden implementar y actualizar complementos a usuarios o grupos desde el centro de administración de Office 365. [Obtener más información](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **Personalización de la barra de herramientas de acceso rápido:** Los iconos de subíndice y superíndice pueden agregarse a la barra de herramientas de acceso rápido.
-   **Obtener & transformación mejoras:** Detección automática de carácter delimitador cuando división columnas mediante el Editor de consultas, elija qué archivo de ejemplo para usar con Combinar archivos binarios y especificar la recopilación del paquete para conectarse a cuando se usa el conector de DB2.
-   **Fuente Dubai:** Familia de fuentes que admite idiomas de Europa occidental así como la mayoría de los idiomas que use el script árabe. [Obtener más información](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Eliminación de fondo:** Quitar un fondo de la imagen con una herramienta de dibujo de forma libre.
-   **Obtener & transformación mejoras:** Utilice "Seleccionar tablas relacionadas" en el cuadro de diálogo Navigator con los conectores ODCB y OLEDB, combinar varios archivos directamente desde el cuadro de diálogo de vista previa de datos de carpeta y usar una nueva opción de menú contextual de la ventana del Editor de consultas para insertar pasos nuevos en las consultas existentes.
-   **Usar un lápiz para seleccionar y objetos de cambio:** Obtener identificadores de objeto con una pluma digital para cambiar el tamaño, girar, mover y mucho más.
-   **Asignar gráfico:** Comparación de valores y mostrar categorías entre regiones geográficas. [Obtener más información](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)
-   **Imágenes SVG:** Insertar y editar gráficos vectoriales escalables (SVG) en los libros. [Obtener más información](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Insertar iconos:**  Utilice los iconos de una biblioteca estándar de archivos de gráficos (SVG) vectoriales escalables yendo al insertar \> ilustraciones \> iconos. [Obtener más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **Guardar en carpetas recientes:** Guardar un libro en una carpeta usada recientemente mediante la ficha reciente cuando vaya al archivo \> Guardar como.
-   **Mejoras en la accesibilidad:** Compatibilidad mejorada para usar el teclado, Narrador y otro tecnología de asistencia para leer y editar libros. [Obtener más información](https://support.office.com/article/51fcb17a-b15b-4b13-ae04-d4f38ece3f78)

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   Boletín de seguridad de Microsoft [MS17-014](https://technet.microsoft.com/library/security/ms17-014): actualización de seguridad para Microsoft Office (3217868)

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones de seguridad que no sean
-   Corregir un problema donde Excel no establece la contraseña de protección de hoja cuando se aplica mediante programación para los libros creados en Excel 2010 o anterior.
-   Corregir un problema donde combinación & Centro no funcionan en hojas de cálculo agrupadas.
-   Corregir un problema donde nuevas funciones que se introdujeron después del lanzamiento de Office 2016 - por ejemplo, TEXTJOIN, CONCAT, IFS, MAXIFS y MINIFS - faltan.
-   Corregir un problema donde Excel se bloquea cuando el usuario intenta aplicar permisos de nivel de celda.
-   Corregir un problema donde guardar un archivo de gran tamaño en OneDrive para la empresa hace que el archivo de bloqueo y el usuario no puede editar el archivo hasta que el usuario cierre y vuelve a abrir Excel.
-   Corregir un problema donde aparece atenuada una nueva ventana cuando se abre un libro de .xls.
-   Corregir un problema donde Excel podría bloquearse al insertar hipervínculos.
-   Corregir un problema donde Excel puede producirse un error al agregar asignaciones XML.
-   Corregir un problema donde el botón de comando para un complemento no funciona después de actualiza el complemento o después de quitar y descargar el complemento de nuevo desde el almacén de Office.
-   Corregir un problema donde Excel podría bloquearse al manipular hojas de DLL a través de VBA.
-   Corregir un problema donde Excel se bloquea al seleccionar un cuadro de combinado de control de formulario en una hoja de gráfico.

### <a name="onenote-feature-updates"></a>OneNote: Actualizaciones de la característica
-   **Soporte técnico de protección de información de Windows (curso):** OneNote es ahora una aplicación mejorada y puede diferenciar entre los datos personales y corporativos, determinar correctamente que se va a proteger, en función de las directivas configuradas. [Obtener más información](https://aka.ms/wiptechnet)

### <a name="onenote-non-security-updates"></a>OneNote: Actualizaciones de seguridad que no sean
-   Corregir un problema donde lienzo de OneNote oculta contenido o actualizaciones cuando muchos de los párrafos en la vista.

### <a name="outlook-feature-updates"></a>Outlook: Actualizaciones de la característica
-   **Soporte técnico de protección de información de Windows (curso):**   Outlook es ahora una aplicación mejorada y puede diferenciar entre los datos personales y corporativos, determinar correctamente que se va a proteger, en función de las directivas configuradas.  [Obtener más información](https://aka.ms/wiptechnet)
-   **Insertar vínculos recientes:** Adjuntar hipervínculos a archivos recientes basados en la nube o sitios Web y crear nombres para mostrar significativo para los usuarios de lectores de pantalla. [Obtener más información](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Fuente Dubai:** Familia de fuentes que admite idiomas de Europa occidental así como la mayoría de los idiomas que use el script árabe. [Obtener más información](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Eliminación de fondo:** Quitar un fondo de la imagen con una herramienta de dibujo de forma libre.
-   **Comprobar el acceso a los archivos compartidos:** Outlook indica al usuario antes de tiempo si los destinatarios no podrán tener acceso a un archivo adjunto de OneDrive o SharePoint y le sugiere cómo solucionar el problema.
-   **Establecer permisos en los datos adjuntos:** Los datos adjuntos de OneDrive o SharePoint, el usuario puede establecer si los destinatarios, en la organización o de forma externa, leído o edición los permisos para los datos adjuntos.
-   **Taskpane anclables:** Deje abierto el panel de tareas en Agregar al cambiar entre los mensajes en un buzón de correo. [Obtener más información](https://blogs.msdn.microsoft.com/exchangedev/2017/01/26/pinnable-taskpane-in-outlook-2016/)
-   **Imágenes SVG:** Insertar y editar gráficos vectoriales escalables (SVG) en los mensajes de correo electrónico. [Obtener más información](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Insertar iconos:**  Utilice los iconos de una biblioteca estándar de archivos de gráficos (SVG) vectoriales escalables yendo al insertar \> ilustraciones \> iconos.  [Obtener más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2017-0106](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106): vulnerabilidad de ejecución remota de código de Microsoft Outlook
-   [CVE-2017-0204](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204): vulnerabilidad de omisión de característica de seguridad de Microsoft Office
-   [CVE-2017-8506](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8506): ejecución remota de código en Microsoft Office
-   [CVE-2017-8507](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8507): Microsoft Office vulnerabilidad de daños en la memoria
-   [CVE-2017-8508](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8508): vulnerabilidad de omisión de característica de seguridad de Microsoft Office

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones de seguridad y comunes
-   Corregir un problema que el panel de navegación de Outlook deja de representación cuando el equipo está bajo de memoria.
-   Anchos de datos adjuntos se expandan visualmente para ajustarse a la información de permiso y el nombre de archivo.
-   Corregir un problema donde el usuario no puede buscar los archivos PST.
-   Corregir un problema donde el usuario ve un nuevo "Microsoft Exchange" almacenar tipo en el cuadro de diálogo "Nuevo archivo de datos de Outlook", y si se selecciona este nuevo tipo de datos, no se puede usar el perfil del usuario.
-   Corregir un problema donde está suprimida una imagen en un mensaje cuando se envían desde un equipo que usa PPP alta.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Actualizaciones de la característica
-   **Soporte técnico de protección de información de Windows (curso):**   PowerPoint es ahora una aplicación mejorada y puede diferenciar entre los datos personales y corporativos, determinar correctamente que se va a proteger, en función de las directivas configuradas.  [Obtener más información](https://aka.ms/wiptechnet)
-   **Insertar vínculos recientes:** Adjuntar hipervínculos a archivos recientes basados en la nube o sitios Web y crear nombres para mostrar significativo para los usuarios de lectores de pantalla. [Obtener más información](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Implementación centralizada de complementos**: los administradores pueden implementar y actualizar complementos a usuarios o grupos desde el centro de administración de Office 365. [Obtener más información](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **Fuente Dubai:** Familia de fuentes que admite idiomas de Europa occidental así como la mayoría de los idiomas que use el script árabe. [Obtener más información](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Eliminación de fondo:** Quitar un fondo de la imagen con una herramienta de dibujo de forma libre.
-   **Imágenes SVG:** Insertar y editar gráficos vectoriales escalables (SVG) en las presentaciones. [Obtener más información](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Insertar iconos:**  Utilice los iconos de una biblioteca estándar de archivos de gráficos (SVG) vectoriales escalables yendo al insertar \> ilustraciones \> iconos. [Obtener más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **Escribiendo en tiempo real cuando la co-autoría:** Vea donde otros usuarios están trabajando en la presentación y ver los cambios mientras escribe. [Obtener más información](https://support.office.com/article/0c30ee3f-8674-4f0e-97be-89cf2892a34d)
-   **Guardar en carpetas recientes:** Guardar una presentación en una carpeta usada recientemente mediante la ficha reciente cuando vaya al archivo \> Guardar como.
-   **Crear formas de tinta precisa:** Arrastre el borrador de segmento para quitar bits exceso de tinta, hasta la línea más cercana.
-   **Seleccionar y manipular objetos con una pluma:** Utilice una pluma digital para mover, cambiar el tamaño o girar objetos mediante sus identificadores, o utilice los botones de lápiz compatibles para la entrada de lápiz de selección de lazo.
-   **Mejoras en la accesibilidad:** Compatibilidad mejorada para usar el teclado, Narrador y otro tecnología de asistencia para leer y editar presentaciones. [Obtener más información](https://support.office.com/article/3fce93f5-9ca8-42a6-bc1f-776749f6e32e)

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones de seguridad que no sean
-   Corregir un problema donde PowerPoint se bloquea cuando el usuario está en el panel de Ideas de diseño si el archivo mfplat.dll no está instalado en el equipo.
-   Corregir un problema donde el botón de comando para un complemento no funciona después de actualiza el complemento o después de quitar y descargar el complemento de nuevo desde el almacén de Office.

### <a name="project-feature-updates"></a>Proyecto: Actualizaciones de la característica
-   **Rápida de lista desplegable para la configuración de predecesoras:** Use la lista desplegable de Gantt para elegir qué predecesoras o sucesoras que desea vincular a una tarea.
-   **Nombre de resumen de tarea:**  Campo de tarea de sólo lectura que muestra el nombre de tarea de resumen de la tarea.  

### <a name="project-non-security-updates"></a>Proyecto: Las actualizaciones de seguridad que no sean
-   Corregir el cuadro de diálogo Crear sitio de Project para mostrar la ubicación correcta para el sitio ahora que en Project Online cada plantilla de proyecto de empresa (EPT) tendrá su propia dirección URL para los sitios de proyecto.
-   Corregir un problema donde se desencadena el evento BeforeClose VBA antes del símbolo de guardar y no dispone de una manera mediante programación para determinar la respuesta del usuario a la operación de guardar símbolo del sistema.
-   Corregir un problema donde % físico completado no resumir correctamente para tareas que comienzan después de la fecha de estado del proyecto.
-   Corregir un problema cuando un recurso de costo y trabajo se asigna a la misma tarea, es posible que no pueda cambiar el Administrador de estado de la tarea.
-   Corregir un problema donde para determinados proyectos, redistribuir todo el proyecto pueden dejar en un bucle sin fin.
-   Corrección de un problema donde la tarea de comienzo y las fechas de fin no sincronizar correctamente a una lista de tareas de SharePoint si tiene determinadas configuraciones regionales de español.
-   Corregir un problema donde si se inicia el proceso de aprobaciones de estado desde el cliente del proyecto, que es posible que nunca terminar, dejando el proyecto en un estado no utilizable.
-   Corregir un problema donde la vista preliminar no los nombres de tareas de diseño correctamente si tiene palabras de chino e inglés.
-   Corregir un problema donde copiar la escala de tiempo en PowerPoint como formas individuales no funciona.
-   Corregir un problema en el cuadro de diálogo "Vínculos entre proyectos" inesperadamente muestra el valor "Archivo no encontrado".
-   Revisión de resultados de un problema que obtendrá incoherente al asignar recursos con capacidad máxima de 0.
-   Corregir un problema donde obtiene restablecer fecha de inicio de una tarea a tan pronto como sea posible al eliminar fecha de inicio de una asignación, se omite cosas como predecesoras, que tiene las siguientes consecuencias divisiones a la izquierda en las asignaciones.
-   ¿Corregir un problema donde si abre un archivo de SharePoint a través del menú reciente, el proyecto está automáticamente desprotegido para usted, incluso si la opción "Solicitar que los documentos se desprotejan antes de que pueda modificarse"? está habilitado.
-   Corregir un problema donde si ir directamente a la aplicación de perfiles de Project, Project deja de responder.
-   Corregir un problema donde las tareas programadas manualmente no se actualizan correctamente para los usuarios actualizar desde Project 2013.
-   Corregir un problema donde cuando la lista de tareas para abrir un proyecto desde SharePoint, Project puede bloquearse como proyecto inicia el proceso de sincronización de tareas.
-   Corregir un problema donde Project a veces se bloquea si va a crear equipo.
-   Corregir un problema donde la información de línea de base se pierde al guardar un proyecto.
-   Corregir un problema donde copias impresas son difíciles de leer para los planes de proyecto grande.
-   Corregir un problema donde los proyectos que se pueden modificados en Project Web App no mostrar los valores correctos para los campos de fórmula.
-   Corregir un problema donde no se guarda correctamente información de campos personalizados de empresa de recursos para un plan de proyecto.
-   Corregir un problema en el que la actualización % de una tarea trabajo completado información actualiza información completa de % de la tarea.
-   Corregir un problema donde se cambia la propiedad del proyecto cuando se guarda el proyecto.
-   Corregir un problema que se calcula incorrectamente IRC para una tarea de resumen.
-   Corregir un problema donde copiar y pegar tareas lleva a través de los datos de línea de base y se guardan los datos, incluso aunque el usuario no está autorizado para guardar datos de línea de base protegida.
-   Corregir un problema donde resultados de importación de datos de Excel en la información de fecha incorrecta para las tareas y asignaciones.
-   Corregir un problema donde, después de abrir un informe, Project se bloquea cuando se cierra.
-   Corregir un problema donde Project deja de funcionar al guardar un proyecto donde una lista personalizada contiene la configuración de validación.
-   Corregir un problema donde escribir el "\>" carácter en la columna de prueba en el cuadro de diálogo Definición de filtro no se interpreta correctamente como significado "es mayor que".
-   Corregir un problema con la presentación de las líneas de progreso en relación con "Plan de línea base."
-   Corregir un problema donde no aparece la lista desplegable de los nombres de campo al personalizar filtros.
-   Corregir un problema donde no aparecen las vistas previas de estilo de barra en el cuadro de diálogo Estilos de barra.

### <a name="publisher-non-security-updates"></a>Publisher: Actualizaciones de seguridad y comunes
-   Corregir un problema donde Publisher no mostrar imágenes TIF CMYK.

### <a name="skype-for-business-feature-updates"></a>Skype para la empresa: actualizaciones de la característica
-   **Insertar vínculo:** Agregar un vínculo en mensajería instantánea y grupo chats y proporcionar texto descriptivo para el vínculo en lugar de la dirección URL completa.
-   **Pantalla de uso compartido de notificación:** En la ventana de conversación se muestra una notificación cuando vaya a compartir una pantalla en una conversación de mensajería instantánea o al uso compartido de pantalla continúa después de salir de una reunión. La notificación para recordarle que aún se está compartiendo su pantalla y facilita la tarea dejar de compartir mediante el botón "Dejar de compartir".
-   **Soporte técnico de protección de información de Windows (curso):** Skype para la empresa ahora se admite como una aplicación de sólo trabajo de trabajo en curso.  Mediante la adición de Skype a su lista de aplicaciones permitidas, indica a Windows que no procesa los datos personales.  Windows va a proteger los datos en nombre de Skype para la empresa.  [Obtener más información](https://aka.ms/wiptechnet)
-   **Opción de restablecimiento de contraseña:** Un vínculo de botón reset aparece en la ventana de inicio de sesión cuando se produce un error de un usuario iniciar sesión en al menos una vez.

### <a name="skype-for-business-security-updates"></a>Skype para la empresa: actualizaciones de seguridad
-   Boletín de seguridad de Microsoft [MS17-013](https://technet.microsoft.com/library/security/ms17-013): actualización de seguridad para el componente de gráficos de Microsoft (4013075)
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): vulnerabilidad de ejecución remota de código de Microsoft Office
-   [CVE-2017-0283](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0283): vulnerabilidad de ejecución de código remoto Uniscribe de Windows
-   [CVE-2017-8550](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8550): Skype para la vulnerabilidad de ejecución remota de código de negocio

### <a name="skype-for-business-non-security-updates"></a>Skype para la empresa: actualizaciones de seguridad comunes
-   Cambiar mensaje de intentos de llamadas a los usuarios con audio deshabilitada mediante una directiva de "No se puede completar la llamada" para "no se puede llamar a debido a que un administrador de TI tiene restricciones de audio. Intente utilizar el correo electrónico o mensajería instantánea en su lugar y pida a póngase en contacto con su administrador de TI".
-   Agregar que un hipervínculo "Olvidado el PIN" a la reunión invitaciones de los usuarios de conferencia RTC habilitada para Skype para profesionales en línea.
-   Habilitar la participación en la reunión de los equipos de Skype para profesionales en línea.
-   Cambiar el volumen de sesión del altavoz predeterminado de un 40% a un 75%.
-   Permitir el cambio de tamaño de la lista de fichas a un ancho mínimo menor.
-   Actualización de teclas de método abreviado para que coincida con el orden de las fichas.
-   Corrección de dirección incorrecta del texto hebreo cuando se envía desde un dispositivo móvil.
-   Corregir un problema con la información incluido comentarios con un lector de pantalla para la característica de escritorio o ceder el Control está presente.
-   Mostrar salones abiertos además de salones seguidos en listas de las salas seleccione.
-   Agregar la capacidad de deshabilitar la capacidad de VoIP mientras está habilitada la aplicación personalizada de control remoto de llamadas.
-   Cambiar sin conexión subtítulo de mensajería instantánea para "Probar el Skype para la aplicación empresarial de móvil".
-   Corregir un problema que hace que una ventana de conversación para una conversación automáticamente aceptada a abrir como una ventana normal, en lugar de minimizada e inesperadamente tenga el foco fuera de otras ventanas.
-   Corregir un problema con el uso de un lector de pantalla en el cuadro de diálogo Opciones de reunión de Skype.
-   Corregir un problema donde no se muestra el primer mensaje de una invitación en el correo electrónico de conversaciones perdidas.
-   Corregir un problema donde se muestran los números de acceso telefónico duplicados al crear una invitación de reunión de Outlook mediante el botón Nueva reunión de Skype.
-   Corregir un problema que, cuando aparece una barra de desplazamiento, todas las conversaciones de un historial de mensajería instantánea no se seleccionada cuando se usa Ctrl + A para seleccionar todo.
-   Corregir un problema donde el texto de salida no tenga el mismo formato exacto cuando se usa el cmdlet Export-CsArchivingData.
-   Corregir un problema donde el organizador de la reunión es no se puede ver un vídeo de participantes remotos al utilizar Reunirse ahora con 3 o más participantes.
-   Corregir un problema donde la primera línea de la lista de reuniones está en blanco cuando un usuario hace clic con un botón en nombre de otro usuario en la lista de participantes.
-   Corregir un problema donde los usuarios son no puedos iniciar sesión al cambiar entre las redes internas y externas corporativas.
-   Corregir un problema donde el área de chat no se cerrará cuando cambio espontáneo de mensajería instantánea a Audio de transferencia con consulta.
-   Corregir un problema donde se truncan los nombres en las notificaciones de notificación del sistema cuando se usan las llamadas simultáneas de dos extremos.
-   Corregir un problema donde el nombre de archivo se trunca en las notificaciones de uso compartido de archivo.
-   Agregar información sobre herramientas para Back a los botones de llamada y transferencia.
-   Hacer que el tiempo empleado en espera en la ventana de transferencia con consulta disponible para los lectores de pantalla, como Narrador.
-   Agregar la capacidad para elegir la mensajería instantánea o las llamadas como la preferencia de forma predeterminada para la transferencia de consultoría.
-   Agregar la capacidad de, al realizar una transferencia con consulta, para que haga clic en el botón "Transferir" para ver una lista de números de teléfono del contacto.
-   Mejorar un mensaje de error generales para que sea clear que el problema es que el usuario tiene una licencia no válida o no se ha asignado una licencia.
-   Corregir un problema donde no todos los contactos se muestran en el título de la ventana de conversación cuando un usuario inicia una conversación con un contacto y, a continuación, agrega otro contacto.
-   Corregir un problema donde el Narrador no lee la línea 2ª de notificaciones.
-   Corregir un problema donde se transfieren las llamadas VOIP en lugar del número consultado.
-   Corregir un problema donde Narrador anuncia información incorrecta cuando el usuario navega en la ventana de contenido.
-   Corregir un problema donde los nombres de creador y modificador no aparecen cuando se coloca sobre una anotación en una pizarra

### <a name="visio-feature-updates"></a>Visio: Actualizaciones de la característica
-   **Buscar las galerías de símbolos de terceros:** Busque las galerías de símbolos de terceros proporcionados por proveedores de contenido seleccionados.
-   **Diapositivas fragmentos de código:** Tomar fragmentos de código de un dibujo de Visio y exportarlos como diapositivas de PowerPoint. [Obtener más información](https://support.office.com/article/e7da404b-4208-49d1-9518-6fe1a4723657)

### <a name="word-feature-updates"></a>Word: Actualizaciones de la característica
-   **Soporte técnico de protección de información de Windows (curso):**   Word es ahora una aplicación mejorada y puede diferenciar entre los datos personales y corporativos, determinar correctamente que se va a proteger, en función de las directivas configuradas.  [Obtener más información](https://aka.ms/wiptechnet)
-   **Insertar vínculos recientes:** Adjuntar hipervínculos a archivos recientes basados en la nube o sitios Web y crear nombres para mostrar significativo para los usuarios de lectores de pantalla. [Obtener más información](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Implementación centralizada de complementos**: los administradores pueden implementar y actualizar complementos a usuarios o grupos desde el centro de administración de Office 365.  [Obtener más información](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **Fuente Dubai:** Familia de fuentes que admite idiomas de Europa occidental así como la mayoría de los idiomas que use el script árabe. [Obtener más información](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Eliminación de fondo:** Quitar un fondo de la imagen con una herramienta de dibujo de forma libre.
-   **De lado a lado:** Navegue las páginas en la vista Diseño de impresión mediante el deslizamiento de ellos lado a lado como una pila de papel. [Obtener más información](https://support.office.com/article/21bfd0ff-0e1f-4c43-b188-8b36dfe6dcf4)
-   **Usar un lápiz para seleccionar y objetos de cambio:** Obtener identificadores de objeto con una pluma digital para cambiar el tamaño, girar, mover y mucho más.
-   **Imágenes SVG:** Insertar y editar gráficos vectoriales escalables (SVG) en los documentos. [Obtener más información](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Insertar iconos:**  Utilice los iconos de una biblioteca estándar de archivos de gráficos (SVG) vectoriales escalables yendo al insertar \> ilustraciones \> iconos.  [Obtener más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **Guardar en carpetas recientes:** Guardar un documento en una carpeta usada recientemente mediante la ficha reciente cuando vaya al archivo \> Guardar como.
-   **Mejorado de lectura con herramientas de aprendizaje:** Nuevos comandos en la optimización de modo de lectura leer habilidades mediante el ajuste de espaciado de texto, que muestra los saltos entre sílabas y el resaltado de cada palabra que el documento es de lectura en voz alta. [Obtener más información](https://support.office.com/article/29efa413-e2da-4cac-b2a5-2defc6d34fd9)
-   **De reconocimiento de formas:** Transformar los dibujos en formas automáticamente mediante el uso de dibujo \> convertir a las formas. [Obtener más información](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad
-   Boletín de seguridad de Microsoft [MS17-014](https://technet.microsoft.com/library/security/ms17-014): actualización de seguridad para Microsoft Office (3217868)
-   [CVE-2017-0254](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254): Microsoft Office vulnerabilidad de daños en la memoria
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): vulnerabilidad de ejecución remota de código de Microsoft Office
-   [CVE-2017-0292](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0292): vulnerabilidad de ejecución remota de código de Windows PDF 
-   [CVE-2017-8509](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8509): vulnerabilidad de ejecución remota de código de Microsoft Office  

### <a name="word-non-security-updates"></a>Word: Actualizaciones de seguridad que no sean
-   Corregir un problema donde el usuario no puede buscar los archivos PST.
-   Corregir un problema donde el usuario ve un nuevo "Microsoft Exchange" almacenar tipo en el cuadro de diálogo "Nuevo archivo de datos de Outlook", y si se selecciona este nuevo tipo de datos, no se puede usar el perfil del usuario.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de seguridad
-   [CVE-2017-0199](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199): Microsoft Office/WordPad código remoto ejecución vulnerabilidad w/Windows API
-   [CVE-2017-0260](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0260): ejecución remota de código en Microsoft Office
-   [CVE-2017-0261](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261): vulnerabilidad de ejecución remota de código de Microsoft Office
-   [CVE-2017-0262](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262): vulnerabilidad de ejecución remota de código de Microsoft Office
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): vulnerabilidad de ejecución remota de código de Microsoft Office
-   [CVE-2017-8510](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8510): vulnerabilidad de ejecución remota de código de Microsoft Office
-   [CVE-2017-8512](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8512): vulnerabilidad de ejecución remota de código de Microsoft Office



## <a name="version-1701-may-9"></a>Versión 1701: 9 de mayo
*Versión 1701 (compilación 7766.2084)*

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones de seguridad y comunes
-   Corregir un problema que hace que los usuarios de forma intermitente vean la selección de mensaje en la lista de mensajes inesperadamente saltar al eliminar los mensajes.
-   Corregir un problema que hace que los bloqueos intermitentes.
-   Agregar el HKEY\_actual\_usuario\\Software\\Microsoft\\Office\\16.0\\Outlook\\opciones\\General\\DisableSupportBackstage clave de registro para permitir que los administradores a ocultar la compatibilidad opción en la ficha archivo.
-   Agregar HKEY que se va\_actual\_usuario\\Software\\Microsoft\\Office\\16.0\\Outlook\\opciones\\General\\DisableOutlookFeedbackFeatures clave de registro para permitir que los administradores a desactivar el Opciones de "Outlook 2016 comentarios" y "Blog de Outlook" en el archivo \> comentarios.

### <a name="skype-for-business-security-updates"></a>Skype para la empresa: actualizaciones de seguridad
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): vulnerabilidad de ejecución remota de código de Microsoft Office

### <a name="skype-for-business-non-security-updates"></a>Skype para la empresa: actualizaciones de seguridad comunes
-   Corregir un problema que hace que una ventana de conversación para una conversación automáticamente aceptada a abrir como una ventana normal, en lugar de minimizada e inesperadamente tenga el foco fuera de otras ventanas.

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad
-   [CVE-2017-0254](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254): Microsoft Office vulnerabilidad de daños en la memoria
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): vulnerabilidad de ejecución remota de código de Microsoft Office

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de seguridad
-   [CVE-2017-0261](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261): vulnerabilidad de ejecución remota de código de Microsoft Office
-   [CVE-2017-0262](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262): vulnerabilidad de ejecución remota de código de Microsoft Office
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): vulnerabilidad de ejecución remota de código de Microsoft Office



## <a name="version-1701-april-11"></a>Versión 1701: 11 de abril
*Versión 1701 (compilación 7766.2076)*

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones de seguridad que no sean
-   Corregir un problema donde aparece atenuada una nueva ventana cuando se abre un libro de .xls.

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2017-0106](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106): vulnerabilidad de ejecución remota de código de Microsoft Outlook
-   [CVE-2017-0204](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204): vulnerabilidad de omisión de característica de seguridad de Microsoft Office

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones de seguridad y comunes
-   Corregir un problema donde el usuario ve un nuevo "Microsoft Exchange" almacenar tipo en el cuadro de diálogo "Nuevo archivo de datos de Outlook", y si se selecciona este nuevo tipo de datos, no se puede usar el perfil del usuario.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones de seguridad que no sean
-   Corregir un problema donde una imagen falta el error se produce cuando el usuario realiza una "Guardar como" para una ubicación alternativa de un archivo de PowerPoint que se almacena en un medio extraíble, como una unidad USB.

### <a name="skype-for-business-non-security-updates"></a>Skype para la empresa: actualizaciones de seguridad comunes
-   Corregir un problema donde los usuarios son no puedos iniciar sesión al cambiar entre las redes internas y externas corporativas.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de seguridad
-   [CVE-2017-0199](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199): Microsoft Office/WordPad código remoto ejecución vulnerabilidad w/Windows API



## <a name="version-1701-march-14"></a>Versión 1701: 14 de marzo
*Versión 1701 (compilación 7766.2071)*

### <a name="access-non-security-updates"></a>Access: Las actualizaciones de seguridad que no sean
-   Corregir un problema donde no se puede descartar los menús desplegables.

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   Boletín de seguridad de Microsoft [MS17-014](https://technet.microsoft.com/library/security/ms17-014): actualización de seguridad para Microsoft Office (3217868)

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones de seguridad que no sean
-   Corregir un problema donde Excel podría bloquearse al insertar hipervínculos.
-   Corregir un problema donde Excel puede producirse un error al agregar asignaciones XML.
-   Corregir un problema donde el botón de comando para un complemento no funciona después de actualiza el complemento o después de quitar y descargar el complemento de nuevo desde el almacén de Office.
-   Corregir un problema donde Excel podría bloquearse al manipular hojas de DLL a través de VBA.

### <a name="onenote-non-security-updates"></a>OneNote: Actualizaciones de seguridad que no sean
-   Corregir un problema donde lienzo de página de OneNote deja de responder a clics del mouse después de la autenticación mediante un NIP en Windows 10 versión 1607 (también conocido como Windows Update aniversario).
-   Deshabilitar optimizada EDU específicas printout comportamiento cuando un usuario inserta un documento editable, por ejemplo, .docx o .pptx.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones de seguridad que no sean
-   Corregir un problema donde conflictos de combinación aparecen incorrectamente cuando la co-autoría.
-   Corregir un problema donde el botón de comando para un complemento no funciona después de actualiza el complemento o después de quitar y descargar el complemento de nuevo desde el almacén de Office.
-   Corregir un problema donde las llamadas a VBA objeto resultados de modelo un error en tiempo de ejecución cuando se aplica a las formas de los gráficos.

### <a name="publisher-non-security-updates"></a>Publisher: Actualizaciones de seguridad y comunes
-   Corregir un problema donde Publisher no mostrar imágenes TIF CMYK.

### <a name="skype-for-business-security-updates"></a>Skype para la empresa: actualizaciones de seguridad
-   Boletín de seguridad de Microsoft [MS17-013](https://technet.microsoft.com/library/security/ms17-013): actualización de seguridad para el componente de gráficos de Microsoft (4013075)

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad
-   Boletín de seguridad de Microsoft [MS17-014](https://technet.microsoft.com/library/security/ms17-014): actualización de seguridad para Microsoft Office (3217868)

### <a name="word-non-security-updates"></a>Word: Actualizaciones de seguridad que no sean
-   Corregir un problema con el consumo de memoria al usar determinadas configuraciones de monitor.
-   Corregir un problema donde el botón de comando para un complemento no funciona después de actualiza el complemento o después de quitar y descargar el complemento de nuevo desde el almacén de Office.



## <a name="version-1701-february-22"></a>Versión 1701: 22 de febrero
*Versión 1701 (compilación 7766.2060)*

### <a name="excel-feature-updates"></a>Excel: Actualizaciones de la característica
-   **Mejoras en la transformación y la conectividad de datos:** Expandir una lista en una nueva columna de texto con delimitador entre los valores y especifique una opción de conmutación por error cuando se conecta a SQL.
-   **Mejoras en la transformación y la conectividad de datos:** Ahora se admite el tipo de datos porcentaje y binarios de combinación de función experiencias de creación se han mejorado.
-   **Conector OLEDB:** Uso del conector de OLEDB en Get & transformación para crear una consulta para importar datos mediante la especificación de una cadena de conexión y, opcionalmente, una instrucción SQL para ejecutar.
-   **Reproducción de entrada de lápiz:** Vaya a Draw \> entrada de lápiz a reproducción para reproducir la escritura a mano hacia delante y hacia atrás para ocultar y mostrar contenido, se proporcionan instrucciones paso a paso o comprender mejor el flujo de ideas de otras personas. [Obtener más información](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **Compatibilidad con CSV (UTF-8):** Abrir y guardar archivos CSV que usan la codificación de caracteres UTF-8.
-   **Transformaciones de datos y mejoras de la conectividad:** Seleccione esta opción para importar tablas relacionadas al cargar los datos de orígenes de OData, agregar columnas personalizadas con los valores procedentes de un cálculo de la función o mostrar las dependencias entre las consultas que usan una vista dedicada.
-   **Compartidos conmigo:** Ver los documentos que otros usuarios han compartido con usted yendo al archivo \> abiertos \> Shared con Millennium Edition. [Obtener más información](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **Cambiar los colores:** Use Avisar para establecer el color de la fuente, el resaltado, relleno de la forma y mucho más. [Obtener más información](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   Boletín de seguridad de Microsoft [MS16-148](https://technet.microsoft.com/library/security/ms16-148): actualización de seguridad para Microsoft Office (3204068)

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones de seguridad que no sean
-   Corregir un problema que, cuando se establece el tema de Office en negro, un mensaje de error "Error inesperado" aparece cuando el botón secundario en una consulta en el panel de consultas del libro.
-   Corregir un problema donde Excel se bloquea cuando el usuario intenta obtener acceso a las opciones de tabla dinámica.
-   Corregir un problema donde los valores de celdas con texto y comillas dobles no se exportan correctamente al guardar como CSV o CSV UTF-8.
-   Corregir un problema donde Excel se bloquea o se bloquea cuando se cierra.
-   Corregir un problema donde un hipervínculo que contiene una fórmula concatenate omite parte del resultado concatenate.
-   Corregir un problema donde pegar una tabla de Excel en formato de texto enriquecido (RTF) para Word no conserva el formato de tabla.
-   Corregir un problema donde no puede realizar al usuario guardar como cuando el libro contiene una hoja de cálculo de MS Excel 4.0 Macro.
-   Asegúrese de CTRL + ALT + 5 el acceso directo para mover una selección a la capa de objetos para que coincida con otras aplicaciones.
-   Corrección de un problema donde, cuando escribiendo en la barra de fórmulas y uso de una función con una lista desplegable, por ejemplo, VLOOKUP, presione la tecla Intro para completar la fórmula seleccionan el elemento superior en la lista desplegable de Autocompletar en lugar de leavingthe se escribió en el valor como-es.
-   Corregir un problema que hace que abrir un archivo de formato (BIFF8) de archivo binario de Excel 2003 que contiene un hipervínculo en una hoja protegida Excel 97 - Excel pensar en el archivo está dañado y Excel intenta reparar o quitar el contenido que debe recibirlo.

### <a name="onedrive-for-business-non-security-updates"></a>OneDrive para la empresa: actualizaciones de seguridad comunes
-   Corregir un problema donde, si el GrooveIntlResource.dll no se puede cargar correctamente (que es poco probable en circunstancias normales), una aplicación de Office puede bloquearse si el usuario intenta abrir o guardar un archivo en una carpeta sincronizada o el Explorador de Windows puede bloquearse si el usuario se desplaza a un carpeta sincronizada con el Explorador de Windows.
-   Corregir un problema donde OneDrive para la empresa no está deshabilitado, aunque se establece la clave del registro adecuada para deshabilitarla, cuando Office está configurado para recibir actualizaciones desde una ubicación que no sea la red de entrega de contenido (CDN) de Office.

### <a name="onenote-feature-updates"></a>OneNote: Actualizaciones de la característica
-   **Controlar la sincronización de imagen y de archivo:** Vaya al archivo \> opciones \> al control de sincronización si todos los archivos y las imágenes se descargan automáticamente para todas las páginas de los blocs de notas.

### <a name="onenote-non-security-updates"></a>OneNote: Actualizaciones de seguridad que no sean
-   Corregir un problema donde OneNote se bloquea al imprimir una imagen más grande que la página.
-   Corregir un problema donde un usuario no puede eliminar una plantilla de página personalizada.

### <a name="outlook-feature-updates"></a>Outlook: Actualizaciones de la característica
-   **Colaborar en los datos adjuntos en tiempo real:** Cargar datos adjuntos a OneDrive para la empresa permitir que todos los usuarios a trabajar en la versión más reciente. Use el menú desplegable en los datos adjuntos para cargar o vuelva a guardarla.
-   **Tarjetas de resumen para viajan reservas y paquetes:** Comprobar y realizar un seguimiento de reservas de viajes, así como las entregas de paquetes, uso de tarjetas de resumen que se crean automáticamente en la Bandeja de entrada y el calendario. [Obtener más información](https://blogs.office.com/2016/06/28/stay-on-top-of-your-travel-and-deliveries-with-outlook/)
-   **Editor:** Proporciona avanzadas, contextual de corrección para ayudar a mejorar la escritura de uno. [Obtener más información](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones de seguridad y comunes
-   Corregir un problema donde, cuando el botón secundario en los datos adjuntos en la lista de datos adjuntos para mantener una conversación, todos los elementos de menú de contexto están visibles, en lugar de sólo los elementos de menú aplicables.
-   Corregir un problema donde los mensajes de correo electrónico de formato de texto enriquecido (RTF) no se puede abrir el destinatario si el mensaje se envió con Information Rights Management.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Actualizaciones de la característica
-   **Títulos cerrados:** Si una diapositiva contiene un vídeo que se ha cerrado títulos, los títulos se pueden reproducir en la presentación con diapositivas.
-   **Varias pistas de audio:** Si una diapositiva contiene un vídeo que tiene varias pistas de audio, se pueden reproducir las pistas en la presentación con diapositivas.
-   **Sección copiando:** Copie y pegue las secciones entre presentaciones.
-   **Compartidos conmigo:** Ver los documentos que otros usuarios han compartido con usted yendo al archivo \> abiertos \> Shared con Millennium Edition. [Obtener más información](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **Reproducción de entrada de lápiz:** A la reproducción de escritura a mano hacia delante y hacia atrás para ocultar y mostrar contenido, se proporcionan instrucciones paso a paso o comprender mejor el flujo de ideas de otras personas. [Obtener más información](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **Mejor grabaciones:** Crear una presentación que se compone de las diapositivas grabadas, grabaciones de pantalla y vídeo insertado y a continuación, comparta dicho contenido grabado a verse de forma remota. También puede incrustar cuestionarios para ayudarle con aprendizaje remoto y realizar su presentación más interactiva, así como cambiar el color de la tinta y usar controles más sencillos para registrar narraciones y audio.
-   **Mejoras del diseñador:** Proporciona sugerencias de diseño con SmartArt para listas con viñetas de proceso.
-   **Ficha de la cinta de opciones de grabación:** Agrega una ficha de grabación mediante la personalización de la cinta de opciones.
-   **Cambiar los colores:** Use Avisar para establecer el color de la fuente, el resaltado, relleno de la forma y mucho más. [Obtener más información](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)
-   **Acercar:** Crear un resumen de la presentación interactivo con vínculos de navegación automática. [Obtener más información](https://support.office.com/article/9d6c58cd-2125-4d29-86b1-0097c7dc47d7)
-   **Abrir hipervínculos:** Use CTRL + haga clic para abrir los hipervínculos cuando se edita una presentación.
-   **Texto resaltado:** Dibujar atención a texto importante mediante el marcador de resaltado de texto.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones de seguridad que no sean
-   Corregir un problema que, al recortar una imagen, la parte recortada de la imagen aparece oscura.
-   Corregir un problema que, cuando se ejecuta en modo de presentación con diapositivas y Narrador, PowerPoint se bloquea cuando el usuario hace clic en un hipervínculo y el sitio es lento cargar.
-   Corregir un problema donde escribe en tiempo real cuando co-autoría no funciona con las tablas.
-   Corregir un problema que, cuando se abre PowerPoint en un equipo que tenga instalado de Malwarebytes 3.0, aparece un error "Trabajo detenido" o PowerPoint se bloquea.
-   Corregir un problema donde la plantilla predeterminada no aparece en el archivo \> New.
-   Corregir un problema donde la escribiendo texto se interrumpe y posponer cuando un archivo que tiene fuentes incrustadas se guarda automáticamente.
-   Corregir un problema con la copia de imágenes de (SVG) gráficos vectoriales escalables de Adobe Illustrator.

### <a name="project-feature-updates"></a>Proyecto: Actualizaciones de la característica
-   **Campo bloqueado:** Establezca el valor en Yes para evitar que a los integrantes del grupo de envío de actualizaciones en una tarea.
-   **Etiquetas de escala de tiempo:** Diferenciar las barras de escala de tiempo mediante el uso de etiquetas para que tengan nombres descriptivos.
-   **Indicadores de progreso de la escala de tiempo:** Utilice marcas de verificación y barras de progreso en la vista escala de tiempo para mostrar cómo lejos de color están con cada tarea.
-   **Mejoras en la accesibilidad:** Compatibilidad mejorada para utilizar el teclado, Narrador y otro tecnología de asistencia para leer y editar proyectos.

### <a name="project-non-security-updates"></a>Proyecto: Las actualizaciones de seguridad que no sean
-   Corregir un problema donde no se muestra ninguna línea de vínculo al crear un vínculo entre proyectos entre un proyecto principal y un subproyecto.
-   Corregir un problema donde los valores de línea base con fases temporales siempre no se guardan correctamente en el formato XML, especialmente trabajar y valores que incluyen las duraciones parciales de costo.
-   Corregir un problema donde, al aplicar actualizaciones de estado, el trabajo real se agrega a la asignación que no haya notificado el miembro del equipo.
-   Corregir un problema donde se muestran los valores de línea de base para un recurso, incluso cuando no se ha creado una línea de base para el recurso.
-   Corregir un problema donde los clips texto de vista previa de impresión por lo que el texto no está visible.
-   Corregir un problema en el que, al abrir un archivo .mpp de SharePoint mediante el uso de una dirección URL de acceso directo, que abre el archivo como desprotegido, incluso si la configuración "solicitar que los documentos se desprotejan antes de que se puede editar?" está habilitado.
-   Corregir un problema donde se actualiza a recursos materiales de Project Web Apps incorrectamente cambia datos con fases temporales.
-   Corregir un problema donde al abrir un proyecto que tiene una tarea de hito puede agregar una fecha de comienzo real a ella aunque no tenga una fecha en el momento cuando se guardó por última vez.
-   Corregir un problema con (EDT) de la estructura de desglose del trabajo renumeración.
-   Corregir un problema donde Project se bloquea al cambiar de una vista de cuadrícula y Narrador es en.
-   Corregir un problema donde se muestra un mensaje de error incorrecto acerca de truncamiento de datos con fases temporales al abrir un archivo XML.
-   Corregir un problema donde guardar una línea de base no establece correctamente los valores de fase temporal.
-   Corregir un problema donde retraso de la asignación se pasa por alto cuando se leen datos de proyecto desde un archivo XML.
-   Corregir un problema donde, al abrir un archivo de Project Online, la muestra de fecha de última modificación la hora UTC en lugar de la zona horaria ajustados tiempo.
-   Corregir un problema donde no aparecen las bandas de color de agrupación para las filas que no sean agrupación al imprimir una vista de hoja.
-   Corregir un problema donde una opción de reparación incorrectamente se muestra cuando el usuario inspecciona una tarea que tiene una asignación más allá de problema de unidad max.
-   Corregir un problema donde no se puede cambiar el valor de un campo de código de esquema después de publica el proyecto.
-   Corregir un problema donde no están tamaño correctamente las barras de Gantt en pantallas de PPP alta en presentación de 175%.
-   Corregir un problema donde si el usuario establece el tiempo de retardo a través del cuadro de diálogo información de la tarea, se establece incorrectamente en una duración de tiempo transcurrido.
-   Corregir un problema donde al abrir ciertos archivos XML, la fecha de comienzo de tarea no se ha configurado correctamente debido a un problema con la asignación.

### <a name="skype-for-business-feature-updates"></a>Skype para la empresa: actualizaciones de la característica
-   **Estilo de notificación de Windows:** Cambios realizados en el aspecto de las notificaciones de entrantes de las llamadas y conversaciones. [Obtener más información](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/New-Skype-for-Business-2016-on-Windows-Notifications-look-and/ba-p/39885)
-   **Transferencia con consulta:** Desde dentro de una llamada, póngase en contacto con otro usuario a través de un mensaje instantáneo o llamada antes de transferir la llamada a ese usuario. [Obtener más información](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/Skype-for-Business-2016-on-Windows-Consultative-Transfer/ba-p/41122)
-   **Notificaciones de micrófono:** Mostrar una notificación en la ventana de conversación cuando el micrófono está silenciado en el sistema operativo o si el micrófono no se recoge cualquier audio.
-   **Deshabilitar "Mi número":** Use la entrada del registro de DisableDisplayMyNumber para deshabilitar a "Mi número" en el teclado de marcado.

### <a name="skype-for-business-non-security-updates"></a>Skype para la empresa: actualizaciones de seguridad comunes
-   Cambiar los botones de sala de espera que se usa para admitir o denegar a los participantes de texto a imágenes (una X o una marca de verificación).
-   Cambiar la reunión texto de notificación de aviso de "Accept" a "Join".
-   Actualizar el mensaje que se muestra para el remitente de un mensaje instantáneo al estado del destinatario se establece en No molestar.
-   El mensaje que se muestra para el remitente de un mensaje instantáneo, cuando el destinatario está sin conexión y "guardado a historial" está deshabilitado, para dejar claro que el destinatario no recibirá el mensaje de actualización.
-   Agregar la capacidad para mover la barra de división vertical entre el historial de chat y la lista de participantes en una conversación en grupo.
-   Agregar la capacidad de cambiar el tamaño de la lista de fichas en windows de mensajería instantánea o salón de chat.
-   Agregar la capacidad de seleccionar los salones de chat que desea buscados al crear un tema de fuente.
-   Corregir un problema donde mensaje detener que aparecen en la conversación intermedio del historial de chat.
-   Corregir un problema donde los mensajes duplicados aparecen en la ventana de conversación.
-   Corregir un problema donde acciones de notificación de notificación del sistema (Accept y omitir) no se muestran correctamente durante un gran volumen de notificaciones.
-   Corregir un problema donde el usuario no se puede escribir un mensaje después de utilizar ALT+TAB para abrir una ventana de conversación minimizada.
-   Corregir un problema donde el botón mensajería instantánea está atenuado en la tarjeta de contacto para un usuario, incluso aunque la mensajería instantánea está disponible.
-   Corregir un problema donde varias ventanas de conversación no abren a su tamaño anterior y la ubicación después de que se cierra y se vuelve a abrir.
-   Corregir un problema donde vínculos personalizados no iniciar cuando se selecciona.
-   Corregir un problema donde no se muestra correctamente el texto de la reunión en línea en el campo región para caracteres no ingleses.
-   Corregir un problema donde no se procesa correctamente información de notificación, como la duración de la llamada, en idiomas de derecha a izquierda.
-   Corregir un problema donde, al crear un tema de fuente, borrar los resultados de búsqueda no restablece los resultados a una lista de salones seguidos.
-   Corregir un problema donde Skype para la empresa se bloquea cuando se abren varias ventanas de conversación al mismo tiempo.
-   Corregir un problema donde la última ventana de conversación se quede en blanco una vez que se cierran todas las otras fichas.
-   Corregir un problema donde el foco de forma predeterminada no se encuentra en el área de entrada de charla cuando conversaciones en pestañas están deshabilitadas.
-   Corregir un problema donde la "¿Olvidó su PIN?" vínculo no aparece en la invitación a la reunión.
-   Corregir un problema donde se recorta y trunca parte del texto en las páginas de dispositivo General y Audio cuando el uso de PPP alta las pantallas a para mostrar 175% o superior.
-   Corregir un problema donde Skype para la empresa se bloquea cuando el equipo se suspende o se reanuda cuando no hay ninguna red y el equipo es un equipo "siempre activado, siempre conectado (AOAC").
-   Corregir un problema donde no se detecta ninguna micrófono en una llamada cuando se usa un dispositivo Polycom CX100.
-   Corregir un problema en su elección, como un vínculo \\ \\nombreDeServidor o file:// en un mensaje de IM da como resultado un mensaje de error en lugar de abrir la ubicación.
-   Corregir un problema, en un entorno de infraestructura de Escritorio Virtual (VDI) que usa enrutamiento basado en ubicación, donde el usuario no puede realizar o recibir llamadas de RTC debido a que el servidor considera que la ubicación del usuario no es válida para las llamadas de RTC.
-   Cambie la línea de asunto del mensaje de correo que se envía un mensaje perdidas, cuando el estado del usuario se establece en No molestar o presentar, desde "perdidas conversación con \<nombre\>"a"\<nombre\> envía un mensaje en Skype para la empresa."
-   Iniciar la marca de tiempo para el primer tiempo inicio de sesión en el dispositivo de captura como parte de los [datos de recuento](https://docs.microsoft.com/skypeforbusiness/legal-and-regulatory/data-collection-practices) para ayudar a identificar las tendencias de inicio de sesión de confiabilidad.
-   Corregir un problema donde no aparece la opción para compartir a un monitor secundario con determinadas configuraciones de monitor en la ventana de 10 versión 1607 (también conocido como la actualización de aniversario).
-   Corregir un problema donde de Skype para bloqueos de negocio al aumentar el contenido compartido cuando la persona que comparte está usando un 3rd terceros implementación de RDP.
-   Corregir un problema en el panel controles de Audio no aparece cuando un usuario hace clic en el botón de controles en una llamada de audio en un entorno de infraestructura de Escritorio Virtual (VDI).
-   Corregir un problema donde los visores vean una pantalla negra cuando un usuario ejecuta Windows 7 y comparte al monitor principal en primer lugar y, a continuación, se pasa para compartir a un segundo monitor.
-   Corregir un problema donde determinado especial caracteres, como la y comercial (&), no se pueden insertar en el cuadro de búsqueda o la "¿Qué ocurre hoy?" cuadro de sección.
-   Solucionar un problema donde no se muestra el recuento no leído cuando hay perdidas mensajes instantáneos sin conexión.
-   Corregir un problema donde las plantillas de "Invitar por correo electrónico" mencionan Lync en lugar de Skype.
-   Corregir un problema donde el número de línea es que faltan desde el área "Mi número" debajo del teclado de marcado.
-   Corregir un problema donde el puntero del mouse no se muestra en el área de entrada de mensajería instantánea después de enviar un mensaje en una conversación.
-   Corregir un problema donde Skype para la empresa se bloquea al iniciar la sesión y hay un problema al cargar el grupo de servidores de la memoria caché.
-   Corregir un problema donde Skype para la empresa se bloquea al inicio de sesión y la restauración de las conversaciones.
-   Corregir un problema donde Skype para la empresa se bloquea al iniciar la sesión después de reanudar.
-   Corregir un problema donde se deshabilita el vínculo de la reunión si los servidores de Exchange de ambas organizaciones tienen TNEF deshabilitado.
-   Corregir un problema donde no se puede reiniciar una llamada de vídeo si no hay sólo una conversación de mensajería instantánea ocurriendo.
-   Corregir un problema donde las anotaciones de texto en una pizarra se pierden al guardar la Pizarra como un archivo PNG.
-   Corregir un problema donde la primera línea está oculta cuando la entrada de más de dos líneas en japonés en la ventana de mensajería instantánea.
-   Corregir un problema donde el carácter de y comercial (&) incorrectamente se reemplaza por un carácter de subrayado en los nombres.
-   Corregir un problema con la dirección URL de "Unirse a la reunión en línea" en una reunión programada.
-   Corregir un problema donde colocar el puntero del mouse sobre una ventana no activará la ventana, aunque el sistema operativo está configurado para ello.
-   Corregir un problema donde los elementos de historial de conversación de llamada de salida muestra el autor de la llamada en lugar de usuario que realiza la llamada.
-   Corregir un problema donde la F12 localmente no guardar una conversación.
-   Corregir un problema donde un correo electrónico de conversaciones perdidas no contiene el mensaje instantáneo inicial.
-   Corregir un problema que puede agregarse un emoji en el área de texto de mensajería instantánea, incluso si el moderador ha deshabilitado la participación de mensajería instantánea.
-   Corregir un problema con el diseño del cuadro de diálogo opción tonos y sonidos.
-   Corregir un problema donde Skype para la empresa se bloquea cuando se cierra una ventana de conversación.
-   Corregir un problema donde menor de DNS para iniciar sesión se produce un error cuando el dominio está registrado como un dominio personal.
-   Corregir un problema donde la configuración de notificación de chat en grupo no se que se va a guardar o cargar correctamente.
-   Corregir un problema donde las ventanas de conversación punto a punto existentes o salones de chat no se muestran después de iniciar sesión, aunque se establece la configuración para volver a abrir las conversaciones.
-   Corregir un problema donde silenciar o del audio de la conversación activa hace que otras ventanas de conversación que aparezca como si tienen los mensajes no leídos.
-   Corregir un problema donde los usuarios que están configurados para el desvío de medios son no se puede reanudar una llamada desde una puerta de enlace RTC después de que la llamada pone en espera.
-   Corregir un problema donde el usuario ve un cuadro azul en lugar del vídeo al unirse a una reunión a través de una dirección URL cuando utilizando un 3rd implementación de RDP de terceros.
-   Corregir un problema que se está mostrando en la parte de la dirección SIP del usuario en lugar del nombre para mostrar en una alerta de notificación del sistema.
-   Corregir un problema donde, cuando Skype para la empresa se conecta a un servidor SIP a través del puerto 443 y un servidor proxy está presente, hay un retraso significativo en el proceso de inicio de sesión si el proxy no permite este tipo de conexiones. La corrección se habilita mediante la adición de la entrada del Registro DWORD EnableDetectProxyForAllConnections en HKEY\_actual\_usuario\\Software\\Microsoft\\UCCPlatform\\Lync y establezca el valor en 1.
-   Corregir un problema donde, al usar conversaciones en pestañas, haga doble clic en una ficha y empieza a escribir a veces para hacer que el foco se mueva a una pestaña distinta y continuar la escritura en esa ventana de conversación.
-   Corregir un problema donde direcciones URL incluidas en un mensaje instantáneo no se pueden seleccionar en la ventana del historial de chat mediante el teclado.
-   Corregir un problema donde se debe oír un sonido del teclado si se selecciona la casilla de verificación "Reproducir un sonido cuando ver una conversación de mensajería instantánea y una persona está escribiendo" en Opciones de tono de llamada y sonidos.
-   Corregir un problema donde no se ha anunciado cuadros de diálogo que aparecen cuando se usa un lector de pantalla, como Narrador.
-   Corregir un problema donde el primer tutorial de ejecución no se pueden explorar con un teclado y no se puede leer por un lector de pantalla, como Narrador.
-   Corregir un problema donde no se escala el icono de presencia de la barra de tareas en la configuración de PPP alta.
-   Corregir un problema donde no se pueden seleccionar el botón Borrar campo en el cuadro de búsqueda mediante el teclado.
-   Corregir un problema donde un usuario no puede iniciar una reunión si la invitación de es de un usuario en otro grupo de servidores.
-   Corregir un problema donde un usuario agregarse a una reunión se muestra incorrectamente como un usuario diferente.
-   Corregir un problema donde se oculta el icono de presencia de los contactos en la notificación de cambio de estado para las llamadas entrantes para el jefe.
-   Corregir un problema donde no coincide con la velocidad de parpadeo del cursor de texto en la ventana de mensajería instantánea las propiedades de teclado en Windows.
-   Corregir un problema donde un lector de pantalla anuncia un nombre incorrecto de contacto para una conversación en grupo.
-   Corregir un problema donde el usuario no puede seleccionar varios contactos mediante el teclado.
-   Corregir un problema donde no se puede recuperar fotos de usuario de Exchange.
-   Corregir un problema donde la Skype para clientes empresariales se conecta a un Skype para Business Server en la red interna, en lugar de uno en la red externa, cuando el usuario se conecta mediante acceso directo.
-   Corregir un problema donde Skype para clientes empresariales se bloquea al intentar resolver el nombre del propietario de la reunión.
-   Corregir un problema donde si se cambia un valor mientras se está iniciando Skype para la empresa o apagar de Windows, Skype para la empresa que se bloquee.
-   Corregir un problema donde Skype para la empresa se bloquea al abrir la lista de participantes en un salón de chat persistente e intentar mover el teclado centran a la lista de participantes.
-   Corregir un problema donde Skype para la empresa se bloquea en reanudar cuando no hay red está disponible.

### <a name="visio-feature-updates"></a>Visio: Actualizaciones de la característica
-   **Base de datos de modelado complemento:** Use el complemento para crear un modelo de base de datos de una base de datos existente para ayudar a planear una nueva base de datos o comprender una ya existente. [Obtener más información](https://support.office.com/article/fb034862-acfc-45bc-88b2-f33d1e1f8614), [Descargue el complemento](https://go.microsoft.com/fwlink/p/?linkid=835953)
-   **Mejoras en la accesibilidad:** Compatibilidad mejorada para usar el teclado, Narrador y otro tecnología de asistencia para trabajar con formas, editar con otras personas y mucho más.
-   **Plantillas de terceros y diagramas:** Examinar o buscar nuevas plantillas y diagramas de ejemplo disponibles en seleccionados proveedores de contenido de terceros. Nombre del proveedor de terceros se muestra en la imagen en miniatura.
-   **Soporte de entrada de lápiz:** Utilice el lápiz o el dedo para dibujar y anotar con las herramientas de la ficha dibujado por el nuevo.

### <a name="word-feature-updates"></a>Word: Actualizaciones de la característica
-   **Mejoras en la accesibilidad:** Compatibilidad mejorada para utilizar el teclado, Narrador y otro tecnología de asistencia para leer y editar documentos. [Obtener más información](https://support.office.com/article/69aed572-336e-4722-a97e-23393cc481b2)
-   **Editor:** Proporciona avanzadas, contextual de corrección para ayudar a mejorar la escritura de uno. [Obtener más información](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)
-   **Reproducción de entrada de lápiz:** Vaya a Draw \> entrada de lápiz a reproducción para reproducir la escritura a mano hacia delante y hacia atrás para ocultar y mostrar contenido, se proporcionan instrucciones paso a paso o comprender mejor el flujo de ideas de otras personas. [Obtener más información](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **Editar con gestos de lápiz natural:** Realizar cambios en un documento mediante van para seleccionar y tachado para eliminar. [Obtener más información](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)
-   **Compartidos conmigo:** Ver los documentos que otros usuarios han compartido con usted yendo al archivo \> abiertos \> Shared con Millennium Edition. [Obtener más información](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **Cambiar los colores:** Use Avisar para establecer el color de la fuente, el resaltado, relleno de la forma y mucho más. [Obtener más información](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="word-non-security-updates"></a>Word: Actualizaciones de seguridad que no sean
-   Corregir un problema donde ve un documento en modo de lectura impide que la tecla TAB trabajar en un segundo documento que se está viendo en diseño de impresión.
-   Corregir un problema donde Word se bloquea cuando se carga más de una biblioteca de gramática.
-   Corregir un problema donde trazos dibujados desaparecen después de dos o tres trazos.
-   Corregir un problema con comillas desaparecen cuando se usa el Editor de métodos de entrada (IME) de Google.
-   Corregir un problema donde un usuario no puede usar con controles de contenido o cuando se realizan las selecciones discontinuas de entrada de lápiz.

### <a name="office-suite-feature-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de la característica
-   **Proporcionar comentarios:** Sugerir nuevas características o indicar a Microsoft qué le gusta o qué no funciona, vaya al archivo \> comentarios

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de seguridad
-   Boletín de seguridad de Microsoft [MS16-148](https://technet.microsoft.com/library/security/ms16-148): actualización de seguridad para Microsoft Office (3204068)

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de seguridad comunes
-   Corregir un problema donde utiliza CTRL + ALT + 7 o CTRL + ALT + 8 en un teclado alemán, abre la herramienta de comentarios del usuario, en lugar de insertar el carácter correspondiente.
-   Corregir un problema donde TraceLogging causa un bloqueo en Windows 7 al instalar o actualizar Office.
-   Corregir un problema donde, cuando dibujo con entrada de lápiz y usar un mouse, soltar el botón del mouse hace que la entrada de lápiz a desplazar ligeramente.
-   Corregir un problema donde, después de insertar una imagen SVG en un documento de Office, la imagen SVG desaparece cuando se guarda y se vuelven a abrir el documento.
-   Corregir un problema donde Office muestra el siguiente mensaje de error durante la activación para los usuarios que no sean ingleses: "la longitud máxima de la clave de producto es 25 caracteres".
-   Corregir un problema con formularios VBA que pueden provocar el orden z de marcos a deje de funcionar o se muestran incorrectamente.
-   Corregir un problema donde una actualización activada mediante System Center Configuration Manager cambia la configuración de UpdateChannel en el registro a algo que no es un canal de actualización válida.



## <a name="version-1609-january-10"></a>Versión 1609: 10 de enero
*Versión 1609 (compilación 7369.2102)*

Nota: Las actualizaciones de seguridad que se tratan en el boletín de seguridad de Microsoft [MS17-002](https://technet.microsoft.com/library/security/ms17-002) no se aplican a la versión de Word en esta versión de canal.

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones de seguridad que no sean
-   Corregir un problema donde mediante un cuadro de diálogo Editar medida, Excel se bloquea.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones de seguridad que no sean
-   Corregir un problema donde trabajar con formas, en ocasiones, PowerPoint se bloquea.

### <a name="skype-for-business-non-security-updates"></a>Skype para la empresa: actualizaciones de seguridad comunes
-   Corregir un problema donde no aparece la opción para compartir a un monitor secundario con determinadas configuraciones de monitor en la ventana de 10 versión 1607 (también conocido como la actualización de aniversario).
-   Corregir un problema donde de Skype para bloqueos de negocio al aumentar el contenido compartido cuando la persona que comparte está usando un 3rd terceros implementación de RDP.
-   Corregir un problema donde, cuando Skype para la empresa se conecta a un servidor SIP a través del puerto 443 y un servidor proxy está presente, hay un retraso significativo en el proceso de inicio de sesión si el proxy no permite este tipo de conexiones. La corrección se habilita mediante la adición de la entrada del Registro DWORD EnableDetectProxyForAllConnections en HKEY\_actual\_usuario\\Software\\Microsoft\\UCCPlatform\\Lync y establezca el valor en 1.

### <a name="word-non-security-updates"></a>Word: Actualizaciones de seguridad que no sean
-   Corregir un problema que, cuando se usa el método InsertXML, se muestra un marcador de posición para un vínculo roto imagen en lugar de la imagen real.

