---
title: Notas de la versión para el canal beta
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Proporciona a los participantes del modo anticipado de Insider la lista más reciente de las nuevas características, correcciones o problemas conocidos principales
ms.openlocfilehash: 12cfa4a285201c2d3839abfd93c5085fa5ea1d13
ms.sourcegitcommit: a58e0b1ff6d1170fabfd95ba7f25e2eb1e4fad0a
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 07/17/2020
ms.locfileid: "45166718"
---
# <a name="release-notes-for-beta-channel"></a>Notas de la versión para el canal beta

El presente artículo contiene notas de la versión para las compilaciones del canal beta de las versiones de escritorio de Word, Excel, PowerPoint, Outlook, Access y Project para Windows. Cada semana se destacarán las nuevas características, correcciones importantes y los problemas principales de mayor interés para usted. Tenga en cuenta que a menudo se implementan características (o incluso correcciones) en el canal beta durante un período de tiempo. Esto nos permite asegurarnos de que todo funciona correctamente antes de publicar la característica para un público más amplio. Por lo tanto, si ve que no dispone de algo de lo que se describe a continuación, no se preocupe, lo obtendrá en algún momento.  

> [!IMPORTANT]
> Estamos realizando algunos cambios en los canales de actualización de las Aplicaciones de Microsoft 365, incluida la adición de un nuevo canal de actualización (canal empresarial mensual) y el cambio de los nombres de los canales de actualización existentes. [Lea este artículo](https://go.microsoft.com/fwlink/p/?linkid=2127441) para más información.

> [!NOTE]
> - Las notas de publicación se publican semanalmente y pueden ser una compilación de varias versiones.
> - La fecha de publicación de las notas de versión pueden no coincidir con la fecha real de lanzamiento de la compilación.

[//]: # (NO ELIMINAR)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

## <a name="version-2008-july-17"></a>Versión 2008: 17 de julio
*Versión 2008 (compilación 13115.20000)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se corrigió un problema por el cual cada vez que se guardaba y volvía a abrir un gráfico dinámico con líneas guía ocultas, las líneas guía se volvían visibles.

- Se corrigió un problema por el que los gráficos no siempre se actualizaban como se esperaba cuando se habilitaba "ForceFullCalculation" a través de VBA para el libro.

### <a name="outlook"></a>Outlook

- Se corrigió un problema en la creación de varios perfiles en Outlook desde el mismo dominio de correo electrónico.
- Corrige un problema que provocaba que el icono de bloqueo no se mostrara en el encabezado de los mensajes cifrados S/MIME.
- Corrige un problema que provocaba que los datos adjuntos se quitaran de mensajes S/MIME al enviarse sin cifrar.
- Corrige un problema que provocaba que los mensajes de texto sin formato S/MIME se volvieran ilegibles al enviarse.
- Corrige un problema que provocaba que los datos adjuntos se dañaran al enviar un correo electrónico S/MIME sin cifrar.
- Corrige un problema que provocaba que los usuarios no pudiesen guardar datos adjuntos de OneDrive de fuera de su espacio empresarial en su equipo local al seleccionar la opción Guardar en el cuadro de diálogo de seguridad.
- Corrige un problema que provocaba que los destinatarios no pudieran guardar los mensajes con derechos protegidos incluso cuando el remitente otorgó el permiso de Guardar como.
- Corrige un problema que provocaba que las etiquetas de algunas opciones de Búsqueda avanzada se truncaran en algunos idiomas.

### <a name="project"></a>Project

- Se corrigió un problema por el que las tareas que aparecen en la vista Panel de tareas no estaban sincronizadas con las del cuadro de diálogo Asignar recursos.
- Se ha corregido un problema por el que si se copiaba y pegaba una tarea con varias dependencias, no se copiaban todas las dependencias correctamente.

### <a name="word"></a>Word

- Se corrigió un problema por el que el comando "Editor" se deshabilitaba cuando el foco estaba en un cuadro de texto de comentario.
- Se corrigió un problema por el que el comando "Mostrar marcas" se deshabilitaba cuando el foco estaba en un cuadro de texto de comentario.
- Se corrigió un problema en el XML personalizado en el que se puede perder el estado de los comentarios al abrir el documento.

### <a name="office-suite"></a>Conjunto de programas de Office

- Se corrigió un problema en el que, después de abrir el usuario una nueva ventana de la aplicación desde la barra de tareas y crear un nuevo documento en blanco, se creaban archivos adicionales.
- Se corrigió un problema por el que, si un usuario estaba editando un documento pero había perdido los permisos, no se informaba al usuario de que tenía que volver a autenticarse.

[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2008-july-10"></a>Versión 2008: 10 de julio
*Versión 2008 (compilación 13102.20002)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha corregido un problema debido al cual la opción Permitir reenvío no aparecía en las opciones de respuesta de las reuniones del calendario compartido en aquellos casos en los que la carpeta de descarga compartida no se había comprobado.
- Se ha corregido un problema que provocaba que el botón Imprimir apareciera en un estado deshabilitado aunque el usuario tuviera los permisos de impresión adecuados.

### <a name="project"></a>Project

- Se ha corregido un problema que impedía al usuario guardar desde Project un PDF o XPS en una biblioteca de documentos de SharePoint.

### <a name="word"></a>Word

- Se ha corregido un problema que provocaba que Word dejara de responder después de pegar texto y una imagen en un cuadro de comentarios.
- Se ha corregido un problema que causaba que el botón "Nuevo comentario" quedara deshabilitado después de eliminar el último comentario.

[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)

## <a name="version-2007-july-03"></a>Versión 2007: 03 de julio
*Versión 2007 (compilación 13029.20006)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Crear sondeos en Outlook con Sondeo rápido:** cree sondeos, recopile votos y obtenga los resultados rápidamente en un solo correo electrónico [Más información](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)

- **Nuevo buscador de salas:** búsqueda de salas de conferencias por distintas funcionalidades.

[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema por el que las tablas del modelo de datos creadas en algunas versiones de Excel no se podían ver en "Vista previa de la tabla", pese a que no se había editado la consulta asociada a la tabla.
- Se ha corregido un problema por el que deshabilitar la opción "Omitir tipo de referencia (relativa o absoluta)" en el cuadro de diálogo "Definir nombre/Aplicar nombres" provocaba que las fórmulas no funcionaran.
- Se ha corregido un problema por el que al quitar filtros avanzados de datos se borraba el formato de tabla.
- Se ha corregido un problema que provocaba que la ruta de acceso completa de un documento PDF incrustado se mostrara en el título del documento, en lugar de mostrarse solo en el nombre de archivo.
- Se ha corregido un problema por el que deshabilitar el CloudConnector de Wolfram y, a continuación, guardar y volver a abrir un libro de Excel podía dar lugar a un bloqueo.
- Se ha corregido un problema por el que iniciar Excel con el complemento Solver habilitado daba lugar a un bloqueo.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema por el que Outlook se bloqueaba si había más de 130 destinatarios en la línea "Para". Asimismo, se ha mejorado el rendimiento del procesamiento de texto.
- Se ha corregido un problema en la barra "Tareas Pendientes" que provocaba que los eventos que ocupaban más de dos días mostraran la misma hora de finalización para los siguientes días.
- Se ha corregido un problema que provocaba que la lista de mensajes dejara de actualizarse durante varios minutos después de que los usuarios de Outlook usaran calendarios compartidos.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema por el que, al tratar de pegar código HTML en un área de texto en una diapositiva, el código se pegaba en un cuadro de texto creado en la parte superior de la diapositiva.
- Se ha corregido un problema por el que, al seleccionar todas las diapositivas en la vista Moderador y, a continuación, salir de dicha vista mediante ALT+TAB, volver a la presentación con diapositivas y hacer clic en "Finalizar presentación", tenía lugar una excepción no controlada.

### <a name="project"></a>Project

- Se ha corregido un problema que provocaba que Project se bloqueara al abrir determinados archivos XML.
- Se ha corregido un problema por el que no se podía abrir un archivo de Project de una biblioteca de documentos de SharePoint si la biblioteca estaba en modo moderno.
- Se ha corregido un problema por el que los proyectos no se podían abrir en el cliente de escritorio de Project en Project Web App si la dirección URL finalizaba en ".com".

### <a name="word"></a>Word

- Se ha corregido un problema en el modo de coautoría: cuando se produce un conflicto de fusión y el usuario ya ha elegido previamente descartar los cambios, ya no se muestra la opción que da a elegir entre guardar o descartar los cambios.
- Se ha corregido un problema por el que, al intentar guardar un archivo que contenía una macro con un nombre nuevo, este se guardaba con la extensión .docx y el nombre de archivo "WRO0004.docx", independientemente de lo que el usuario escribiera, lo que provocaba que el archivo no se pudiera volver a usar.

[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)

## <a name="version-2007-june-26"></a>Versión 2007: 26 de junio
*Versión 2007 (compilación 13020.20004)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Se ha corregido un problema por el que el administrador de tablas vinculadas solicitaba una clave principal al actualizar una tabla SQL vinculada.
- Se ha corregido un problema por el que las consultas en el Editor de consultas quedaban desplazadas fuera de la vista.
- Se ha corregido un problema que provocaba que la ejecución de consultas tardara en completarse aproximadamente el doble del tiempo esperado.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema por el que los usuarios no podían "Enviar como" o "Enviar en nombre de" en una lista de distribución.
- Se ha corregido un problema por el que, al insertar una imagen en un mensaje y, a continuación, guardar el mensaje como borrador, se cambiaba el tamaño de la imagen.
- Se ha corregido un problema que provocaba que el cuerpo de un mensaje NDR cambiara de Unicode a ASCII después de editar el asunto.

### <a name="project"></a>Project

- Se ha corregido un problema que consistía en que los vínculos de Project Planner en entornos de Government Community Cloud habían sido deshabilitados.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema por el que el texto insertado en un archivo de gráficos vectoriales escalables (SVG) quedaba ilegible tras insertarlo en un archivo de Word, Excel o PowerPoint, guardar y cerrar el archivo y, a continuación, volver a abrirlo.

[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)

## <a name="version-2007-june-19"></a>Versión 2007: 19 de junio
*Versión 2007 (compilación 13012.20000)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema que provocaba que se quitara el XML de CustomUI para una ficha de cinta personalizada al guardar un libro de trabajo en SharePoint o OneDrive.
- Se ha corregido un problema que provocaba que los libros de trabajo fueran de solo lectura cuando el archivo tenía activada la casilla "Se recomienda solo lectura".

### <a name="outlook"></a>Outlook

- Se ha corregido un problema por el que la ventana del Editor de métodos de entrada (IME) se superponía al texto subyacente escrito mediante el IME al utilizar varios monitores con resoluciones diferentes.
- Se ha corregido un problema que provocaba que los usuarios vieran el siguiente error al cerrar una cita guardada previamente: "No se puede guardar el elemento porque otro usuario lo modificó o se modificó en otra ventana. ¿Quiere realizar una copia en la carpeta predeterminada del elemento?"
- Se ha corregido un problema por el que las fechas del minicalendario no se podían mostrar en negrita para los usuarios de Japón.
- Se ha corregido un problema que impedía que los avisos del calendario mostraran la hora exacta de las reuniones programadas para tener lugar en menos de una semana.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema por el que el indicador de color de presencia de un usuario no se actualizaba en la galería de coautoría durante una sesión de coautoría en directo.

### <a name="project"></a>Project

- Se ha corregido un problema por el que, si las tareas de duración fija estaban completas al 100 %, pero no se especificaba la fecha de finalización real, el porcentaje de finalización de la tarea se mostraba como inferior al 100 %.

### <a name="word"></a>Word

- Se ha corregido un problema por el que el color de los hipervínculos HTML no se representaba correctamente.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema por el que las direcciones URL que no se basaban en http o https no se mostraban en la lista Utilizado recientemente.

[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)

## <a name="version-2007-june-12"></a>Versión 2007: 12 de junio
*Versión 2007 (compilación 13006.20002)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Obtenga datos de organización de Power BI mediante Tipos de datos:** los tipos de datos de Excel de Power BI se están publicando ahora para participantes de Office Insider en las organizaciones con Office 365 E5/A5 o Microsoft 365 E5/A5. Obtener la información que necesita y actualizarla fácilmente es fundamental para muchos de los flujos de trabajo diarios. Le proporcionamos acceso a la información de Power BI de su empresa u organización como un tipo de datos en Excel, lo que amplía su capacidad de incorporar a las hojas de cálculo información vinculada. [Más información](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)

[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Se ha corregido un problema que provocaba que Microsoft Access no identificara una Columna de identidad en una tabla vinculada de SQL Server, lo que podía hacer que las filas aparecieran como eliminadas de forma incorrecta.

### <a name="excel"></a>Excel

- Se ha corregido un problema por el que no se pudo aplicar el formato correcto a las líneas de cuadrícula principales de los gráficos radiales.

### <a name="project"></a>Project

- Se ha corregido un problema que provocaba que el evento ProjectBeforeTaskChange no se activara al tener lugar un cambio en la tarea de resumen del proyecto, ya fuera en el campo de inicio o de tarea del proyecto.
- Se ha corregido un problema por el que una actualización o un restablecimiento de la línea base podía cambiar los recursos de trabajo o el costo presupuestado con fases temporales, y la línea base podía reflejar valores de presupuesto incorrectos.

### <a name="word"></a>Word

- Se ha corregido un problema por el que no funcionaba la opción de borrar el formato en el Panel Comentarios mediante el botón Borrar formato de la cinta de opciones de Office.
- Se ha corregido un problema que provocaba que otras aplicaciones que se ejecutaban en segundo plano comenzaran a parpadear al cambiar el tamaño de una tabla cuando la regla no se mostraba.
- Se ha corregido un problema por el que, en el modo de coautoría, las respuestas a los comentarios no se mostraban en el panel de comentarios en ocasiones, pero eran visibles en el panel de revisiones.
- Se ha corregido un problema por el que, si Word tenía una lista de más de 50 documentos abiertos con frecuencia, después de guardar y abrir un documento, se mostraba un historial de revisiones pese a que no se había modificado dicho documento.

[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)

## <a name="version-2006-june-05"></a>Versión 2006: 05 de junio
*Versión 2006 (compilación 13001.20002)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Ordenar o filtrar mientras colabora en Excel:** ahora puede ordenar y filtrar un archivo de Excel mientras colabora con otras personas. Esta nueva característica evita que sus acciones se vean afectadas por la ordenación y los filtros de otros usuarios mientras se trabaja en un documento en coautoría.

- **Crear tablas dinámicas de conjuntos de datos en Power BI en Excel:** puede crear tablas dinámicas en Excel conectadas a los conjuntos de datos almacenados en Power BI con tan solo unos clics.Así, podrá obtener lo mejor de las tablas dinámicas y de Power BI. Calcule, resuma y analice sus datos con tablas dinámicas desde sus conjuntos de datos seguros de Power BI. [Más información](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a>Outlook

- **Volver a abrir rápidamente los elementos de una sesión anterior:** hemos agregado una opción para volver a abrir rápidamente los elementos de una sesión anterior de Outlook. Si Outlook se bloquea o usted cierra la aplicación, ahora podrá reiniciar elementos rápidamente al reabrir Outlook. Esta característica está activada de forma predeterminada. Para desactivarla, vaya a Opciones > General > Opciones de inicio.


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema por el que los valores personalizados en el eje del gráfico no se aplicaban correctamente.
- Se ha corregido un problema por el que las hojas de cálculo que contenían varias fórmulas con nombres definidos tardaban más en guardarse.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema por el que la ventana del Editor de métodos de entrada (IME) se superponía al texto subyacente escrito mediante el IME cuando se usaban varios monitores con resoluciones diferentes.
- Se ha corregido un problema que causaba un bloqueo cuando se visualizaba una plantilla mientras se redactaba un nuevo mensaje de correo electrónico.
- Se ha corregido un problema por el que los usuarios no podían intercambiar carpetas públicas de Exchange 2010 después de la versión 1911 de Outlook.
- Se ha corregido un problema por el que se deshabilitaba el botón de Categorizar para los calendarios de grupo en la cinta de opciones de Office.
- Se ha corregido un problema que hacía que los usuarios con contactos en conflicto experimentaran bloqueos en Outlook.
- Se ha corregido un problema por el que la lista desplegable del Archivo en línea en las propiedades de carpeta no aparecía en monitores con un alto nivel de ppp.
- Se ha corregido un problema que provocaba un bloqueo en Outlook al trabajar con hipervínculos en mensajes de correo electrónico de texto sin formato.
- Se ha corregido un problema que provocaba que Outlook no pudiera analizar nombres de archivo largos codificados con RFC2231.
- Se ha corregido un problema que provocaba que los usuarios de Outlook experimentaran interrupciones intermitentes al usar lectores de pantalla.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema al abrir archivos configurados por el servidor con autenticación basada en formularios.
- Se ha corregido un problema por el que los archivos de PowerPoint con gráficos o libros incrustados podían causar errores al guardar el archivo.
- Se ha corregido un problema que provocaba que los paneles de Comentarios cerrados por el usuario se abrieran automáticamente de nuevo.
- Se ha corregido un problema por el que el editor de diapositivas de una diapositiva se superponía a la siguiente diapositiva.

### <a name="project"></a>Project

- Se ha corregido un problema que impedía que las tareas huérfanas se eliminaran o reasignaran después de eliminar su plan primario.

### <a name="word"></a>Word

- Se ha corregido un problema por el que las marcas de tiempo en los paneles de comentarios no se basaban en la hora de la configuración regional del sistema.
- Se ha corregido un problema por el que los comentarios entre la aplicación web y la aplicación de escritorio no estaban sincronizados.

[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)


## <a name="version2006may29"></a>Versión 2006: 29 de mayo
*Versión 2006 (compilación 12920.20000)*

### <a name="featureupdates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Se agregaron botones adicionales a las notificaciones del sistema de Outlook:** ahora aparecen botones de acción rápida en las notificaciones del sistema de Outlook cuando se ejecuta Outlook en Windows 10.

### <a name="powerpoint"></a>PowerPoint

- **Rendimiento mejorado de vídeos de Stream en PowerPoint:** hemos realizado mejoras en el rendimiento de la reproducción de los vídeos de Microsoft Stream para minimizar el tiempo de carga de vídeo y lograr una visualización más fluida.  Utilice sus vídeos corporativos de Microsoft Stream para crear presentaciones mejoradas.

[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL FIN DE CONTENIDO)

<br/>

[//]: # (NO QUITAR DETALLES DE ERRORES DE INICIO DE CONTENIDO)

### <a name="resolvedissues"></a>Problemas resueltos

### <a name="excel"></a>Excel

- Se ha corregido un problema por el que Excel se cerraba ocasionalmente al utilizar OneDrive.
- Se ha corregido un problema que provocaba que, al hacer clic en un hipervínculo marcado en el propio libro, se ocultara dicho libro.
- Se ha corregido un problema por el que algunos vínculos de un gráfico copiado y pegado usaban direcciones de unidad asignadas, en lugar de direcciones universales.
- Se ha corregido un problema por el que Excel podía dejar de responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema que hacía que las diapositivas no quedaran centradas después de usar la rueda del mouse para hacer zoom.

### <a name="word"></a>Word

- Se ha corregido un problema por el que no se mostraban los textos copiados y pegados en un panel de comentarios.
- Se ha corregido un problema debido al cual las burbujas de sugerencias de comentarios aparecían borrosas al 100 % de zoom.
- Se ha corregido un problema que causaba errores en ciertos casos de coautoría al habilitar la directiva de Word 2007 y, después, las plantillas y documentos binarios.
- Se ha corregido un problema por el que no se abrían los archivos con nombres de ruta largos (mayores que 32 000 caracteres) y no se mostraba un mensaje de error adecuado.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2006-may-22"></a>Versión 2006: 22 de mayo
*Versión 2006 (compilación 12914.20000)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Guardar en carpetas fijadas:** anclar las carpetas facilita el almacenamiento de archivos de Office. Recibimos un comentario en el que se nos informa de que los usuarios desean tener más control sobre las carpetas disponibles al guardar un archivo nuevo. Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar. Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil.<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

### <a name="powerpoint"></a>PowerPoint

- **Guardar en carpetas fijadas:** anclar las carpetas facilita el almacenamiento de archivos de Office. Recibimos un comentario en el que se nos informa de que los usuarios desean tener más control sobre las carpetas disponibles al guardar un archivo nuevo. Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar. Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil.<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

### <a name="word"></a>Word

- **Guardar en carpetas fijadas:** anclar las carpetas facilita el almacenamiento de archivos de Office. Recibimos un comentario en el que se nos informa de que los usuarios desean tener más control sobre las carpetas disponibles al guardar un archivo nuevo. Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar. Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil.<br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema que producía el siguiente mensaje de error: "No se puede cerrar el libro de trabajo debido a que otro libro hace referencia al mismo". El mensaje aparecía si los complementos se cargaban en orden alfabético en lugar de en un orden especificado por el usuario.
- Se ha corregido un problema que causaba problemas de memoria al administrar fuentes entre Excel y algunas aplicaciones tecnológicas de asistencia de terceros.
- Se ha corregido un problema por el que Excel se bloqueaba cuando los complementos solicitaban elementos de host en hojas de cálculo que tuvieran formas con bloqueos noSelect.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema por el que el evento Folder.BeforeItemMove no se activaba correctamente cuando un usuario movía elementos entre carpetas.
- Se ha corregido un problema en el que los usuarios veían los elementos del calendario que pasaban de la medianoche como Eventos de todo el día.
- Se ha corregido un problema por el que Outlook se bloqueaba cuando dos complementos agregaban un botón al mismo grupo en la cinta de opciones.
- Se ha corregido un problema por el que los usuarios no podían compartir calendarios con usuarios invitados.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema que provocaba que, al acercar y alejar el área de presentación, apareciera una separación entre el recuadro de selección ampliado y el puntero del mouse.

### <a name="project"></a>Project

- Se ha corregido un problema por el que Project se bloqueaba después de hacer clic en Opciones.

### <a name="word"></a>Word

- Se ha corregido un problema por el que los hipervínculos en los comentarios no funcionaban.
- Se ha corregido un problema que provocaba que, al acercar y alejar el área de presentación, apareciera una separación entre el recuadro de selección ampliado y el puntero del mouse.
- Se ha corregido un problema por el que no se podía pegar código HTML en WordMail para Calendario.
- Se ha corregido un problema por el que, en ocasiones, Word se bloqueaba al responder a un comentario en una sesión de coautoría.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2006-may-15"></a>Versión 2006: 15 de mayo
*Versión 2006 (compilación 12905.20000)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Realice una conexión PDF:** Conectar, importar, actualizar los datos de un PDF. [Más información](https://support.office.com/article/9967afd8-85ee-4df3-aa06-753bcc1a2724)

### <a name="outlook"></a>Outlook

- **Encuentre lo que necesita:** Reducir la búsqueda con opciones como carpetas, remitente, fecha, información de datos adjuntos y más.

### <a name="powerpoint"></a>PowerPoint

- **No es necesario hacer clic: sus miniauriculares tienen que cubrir lo siguiente:** Usar sus Surface Earbuds para controlar sus presentaciones de PowerPoint. Importante: Debe emparejar sus Surface Earbuds en la aplicación Surface Audio para Windows 10 para poder usar gestos para controlar las presentaciones. Aquí encontrará instrucciones para empezar a usar la aplicación Surface Audio en Windows 10. [Más información](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="word"></a>Word

- **Aplicar automáticamente o recomendar etiquetas de confidencialidad:** Office puede recomendar o aplicar automáticamente una etiqueta de confidencialidad basada en el contenido confidencial detectado.

[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos

### <a name="excel"></a>Excel
- Hemos corregido un problema que provocaba que los usuarios tuvieran un mejor rendimiento al eliminar las columnas combinadas.
- <div>Hemos corregido un problema que provocaba que los nombres de las impresoras se duplicaran en la lista de impresoras disponibles.</div>

### <a name="powerpoint"></a>PowerPoint
- Hemos corregido un problema por el que la revisión ortográfica y los métodos abreviados del teclado no funcionaban de manera esperada al usar un teclado de Suiza (QWERTZ) en inglés.

### <a name="word"></a>Word
- Hemos corregido un problema en el que agregar un nuevo comentario en un documento en blanco no haría nada.
- Hemos corregido un problema que haría que la aplicación se bloqueara cuando se insertara o actualizara un índice en un documento que contuviera más de cien entradas.
- Hemos corregido un problema que provocaba que los archivos con valores XML personalizados se abrieran muy despacio.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office
- Hemos corregido un problema en Visual Basic para las aplicaciones de Microsoft Office, por el que la aplicación de Office consideraba como corruptos ciertos proyectos de VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre o la ruta de la biblioteca.


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2006-may-08"></a>Versión 2006: 08 de mayo
*Versión 2006 (Compilación 12829.20000)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos han pasado a ser más elegantes.

### <a name="outlook"></a>Outlook

- **Mejores resultados, en un instante:** actualizamos la experiencia de búsqueda para que sea más inteligente, rápida y fiable que nunca. [Más información](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos han pasado a ser más elegantes.

### <a name="powerpoint"></a>PowerPoint

- **Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos han pasado a ser más elegantes. [Más información](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a>Word

- **Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos han pasado a ser más elegantes.

[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Hemos estudiado y resuelto el problema por el que una implementación de Office 365 ProPlus a través de Intune se pausaba después de apagar el SO.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2005-may-01"></a>Versión 2005: 1 de mayo
*Versión 2005 (compilación 12827.20030)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Vínculos mejorados en el correo electrónico:** al incluir un vínculo a un archivo, la dirección URL se reemplaza por el nombre del archivo. Puede cambiar los permisos para que todos los destinatarios tengan acceso. [Más información](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema por el que las tablas de datos de los gráficos podían representar incorrectamente los valores de un eje de fechas.
- Se ha corregido un problema por el que los saltos de página no se podían deshabilitar después de ir al diseño de página o la vista previa de salto de página
- Se ha corregido un problema por el que los estilos de línea de los gráficos podían perderse tras ocultar y mostrar columnas con datos de series.
- Insertar una columna en una lista filtrada llevaba más tiempo de lo esperado.
- Podría producirse un bloqueo al intentar mostrar los cambios en una nueva hoja de un libro con el modo "libro compartido" heredado.
- Se ha corregido el problema por el que el formato personalizado de un gráfico dinámico podía no guardarse si estaba habilitada la opción "Invertir si es negativo".
- Se ha corregido un problema por el que el formato personalizado de un único punto de datos de un gráfico dinámico no se guardaba si estaba seleccionada la opción "invertir si es negativo".
- Este cambio corrige un problema por el que el carácter "@" cargado en un archivo CSV causaba que la cadena tras el carácter "@" se convirtiera en una fórmula.
- Se ha corregido un problema por el que los valores decimales de la función SECUENCIA no se redondeaban correctamente.

### <a name="outlook"></a>Outlook

- Corrige un problema por el que los safelinks muy largos en los que los usuarios hacían clic en el cliente de escritorio de Outlook no se podían cargar debido a un truncamiento.
- Se ha corregido un problema por el que las carpetas de Outlook con nombres que contenían caracteres DBCS (conjunto de caracteres de doble byte) desaparecían intermitentemente al sincronizar con el servidor. Esto sucedía si Outlook estaba configurado con una cuenta IMAP y se ejecutaba en un sistema con la configuración regional configurada en japonés.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema por el que el borrador de los comentarios dejaba de estar disponible si un usuario creaba un comentario sin publicarlo, cerraba el panel de comentarios, abría una nueva ventana, se desplazaba por varias diapositivas, cerraba la ventana y volvía a abrir el panel de comentarios en la presentación original.

### <a name="project"></a>Project

- Se ha corregido un problema por el que, si Project estaba conectado a Project Web App y el separador decimal era una coma, el método TaskDependencies Add producía un error al agregar retardo.

### <a name="word"></a>Word

- Se ha corregido un problema por el que la inserción de comentarios en un documento en el modo de colaboración no funcionaba en ocasiones.
- Este cambio corrige un problema por el que la tarjeta de contactos parpadeaba si se hacía clic en la mención @.
- Se ha corregido el problema por el que al cerrar un documento con borrador de comentarios se preguntaba al usuario si deseaba cerrar el documento sin guardar los comentarios del borrador. Al cancelar la solicitud, se cerraba el documento en lugar de quedar abierto.
- Se ha corregido un problema por el que al traducir un comentario publicado se producía el error "Error al insertar el texto traducido".
- En la Vista web o en el lector inmersivo, al hacer clic en una sugerencia se desplazaba a la parte superior incluso aunque ya estuviera a la vista. Este error se ha corregido.
- Se ha corregido un problema por el que al intentar guardar un archivo que contenía una macro con un nombre nuevo, este se guardaba con la extensión. docx y el nombre de archivo WRO0004.docx, independientemente de lo que el usuario escribiera, lo que hacía que el archivo no se pudiera volver a usar.

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)


## <a name="version-2005-april-24"></a>Versión 2005: 24 de abril
*Versión 2005 (compilación 12816.20006)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel
- Este cambio corrige un problema en el que el valor de la línea de tendencia del gráfico R-cuadrado (en el caso de la intersección forzada y) era incorrecto aunque la función de ESTIMACIÓN devuelva el valor correcto.
- Este cambio arregla un problema en el que no siempre se guardaba el formato de la línea de tendencia de los gráficos personalizados.

### <a name="outlook"></a>Outlook
- Corregido un problema por el que se desactivó el botón de Categorizar para los calendarios de grupo en la cinta de opciones de Office.
- Se ha solucionado un problema por el que los clientes de las empresas con carpetas de grupo no implementadas o que no funcionaban, hacían que Outlook mostrara un mensaje de "no responde".

### <a name="powerpoint"></a>PowerPoint
- Se ha solucionado un problema por el que al pasar el ratón por encima del símbolo del asterisco (*) no aparecía el nombre de usuario y la fecha de la última persona que actualizó el documento.

### <a name="word"></a>Word
- Al habilitar la opción "Mostrar marcadores" no se mostrarán los marcadores. Este error se ha corregido.
- Este cambio arregla un problema por el que el texto con hipervínculos puede no aparecer si la opción "Mostrar códigos de campo en lugar de sus valores" estaba activada.

[//]: # (NO ELIMINAR LOS DETALLES DEL CONTENIDO FINAL)


## <a name="version-2005-april-17"></a>Versión 2005: 17 de abril
*Versión 2005 (compilación 12810.20002)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel
- Se aumentó el tamaño de los controles de edición de referencia de celda en el cuadro de diálogo Barras de error personalizadas utilizado con gráficos.
- En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.
- Corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.
- Application.Evaluate (VBA) no funcionaba para funciones definidas por el usuario en algunos casos.
- Este cambio corrige un problema que hacía que la información de formato condicional (CF) no se guardase correctamente en los archivos XLSB.

### <a name="onenote"></a>OneNote
- Corregido un problema en el que los saltos de línea se almacenaban como pestañas verticales.

### <a name="outlook"></a>Outlook
- Soluciona un problema que hacía que los usuarios no pudieran agregar un grupo de contactos personal como asistente de la reunión.
- Soluciona un problema que provocaba que las reuniones para las que faltan más de 2 meses no muestren un tema de reunión en el Asistente de programación.
- Soluciona un problema que hacía que los usuarios vieran el truncamiento del cuerpo del mensaje al reenviar mensajes HTML grandes.
- Se agregó la capacidad de aplicar la configuración de firma predeterminada de S/MIME a través de la directiva de grupo.
- Se solucionó un problema que hacía que las reglas de eliminación creadas para los buzones que no fueran el buzón principal del usuario dejaran de ser válidas.
- Se solucionó un problema que hacía que los datos adjuntos se perdieran al reenviar un mensaje cifrado.

### <a name="project"></a>Project
- Cuando se editan los datos del Predecesor/Sucesor dentro de una vista de formulario, se activa un evento ProjectBeforeTaskChange adicional.
- Se solucionó un problema por el cual Proyect podía bloquearse al cambiar el campo de estado del tablero en un proyecto que conectado a una lista de tareas de SharePoint.
- Corregido un problema por el que Project podía bloquearse al guardar proyectos creados con versiones anteriores de Project.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)


## <a name="version-2004-april-10"></a>Versión 2004: 10 de abril
*Versión 2004 (compilación 12730.20024)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="access"></a>Access

- **Omita el cuadro de diálogo Mostrar tabla, vaya directamente a un panel de tareas y simplifique la adición de tablas y consultas:** agregue tablas y consultas haciendo clic en cuatro pestañas, seleccionando múltiples nombres, buscando por texto y arrastrando desde un panel de tareas que permanece abierto mientras trabaja.

### <a name="excel"></a>Excel

- **Selector de contenido de M365 Premium:** de vida a sus documentos. Explore gratis miles de imágenes, iconos y adhesivos. [Más información](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

### <a name="outlook"></a>Outlook

- **Selector de contenido de M365 Premium:** de vida a sus documentos. Explore gratis miles de imágenes, iconos y adhesivos. [Más información](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

- ** Mantenga la fidelidad de sus imágenes cuando las envíe como parte de un correo electrónico:** una nueva configuración de Outlook está disponible para limitar la compresión de imágenes cuando envía imágenes como parte de contenido del correo electrónico

### <a name="powerpoint"></a>PowerPoint

- **Selector de contenido de M365 Premium:** de vida a sus documentos. Explore gratis miles de imágenes, iconos y adhesivos. [Más información](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

- **Sincronice los cambios mientras realiza la presentación:** sincronice los cambios cuando se hagan aunque la presentación esté en el modo de presentación con diapositivas.

### <a name="word"></a>Word

- **Selector de contenido de M365 Premium:** de vida a sus documentos. Explore gratis miles de imágenes, iconos y adhesivos. [Más información](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

- **Anote su copia privada:** cree notas escritas a mano privadas realizando una copia privada de un documento compartido. Vaya a Ver > Crear una copia privada para empezar.

[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Se han corregido problema al cambiar el tamaño y actualizar tablas en el panel de tareas.

### <a name="excel"></a>Excel

- Se ha corregido un problema por el que seleccionar un rango de celdas en una hoja daba lugar a la selección de una sola celda.

- Se ha corregido un problema que podía provocar que Excel dejara de responder al reducir el tamaño de un gráfico con algunos rangos de eje x.

- Se ha corregido un problema que provocaba que al insertar una plantilla de gráfico definida por el usuario como predeterminada se guardara como un gráfico de columnas.

- Se ha corregido un problema por el que las etiquetas de datos en los gráficos se mostraban en blanco cuando las celdas de datos subyacentes no tuvieran un título.

- Se ha corregido un problema por el que, en una hoja de Excel con referencia de celda F1C1 habilitada y en coautoría o compartida, al pasar el ratón por el icono de presencia del usuario no se mostraba la referencia de celda activa en modo F1C1.

### <a name="outlook"></a>Outlook

- Corrige un problema que provocaba que las categorías desapareciesen en ocasiones de los mensajes de correo electrónico.

- Corrige un problema que provocaba que los delegados viesen distintas jerarquías de carpetas en diferentes equipos para los buzones compartidos.

- Corrige un problema que provocaba que los usuarios experimentasen un error al intentar ver las propiedades de un formulario de la organización.

- Corrige un problema que provocaba que se produjesen errores en la activación de algunos avisos al cambiar la zona horaria en un equipo.

### <a name="powerpoint"></a>PowerPoint

- Este cambio corrige un problema en el que es posible que no siempre se muestre el título del gráfico al representar un gráfico de Excel heredado incrustado como objeto OLE en PowerPoint o Word.

- Se ha corregido un problema por el que al copiar texto de Excel en PowerPoint podía cambiar el formato.

- Este cambio corrige un problema que provocaba que la búsqueda de caracteres especiales con "Buscar solo palabras completas" no siempre funcionase como se esperaba.

### <a name="project"></a>Project

- Se corrigió un problema por el que el usuario no podía especificar el trabajo previsto con fases temporales al activar la configuración para proteger el trabajo real.

### <a name="word"></a>Word

- Este cambio corrige un problema que provoca que al colocar el cursor sobre una sugerencia no se resalte la tarjeta.

- Este cambio corrige un problema que hacía que el texto de las formas agrupadas desapareciera temporalmente al usar la herramienta Selección de lazo.

- Este cambio corrige un problema en el que es posible que no siempre se muestre el título del gráfico al representar un gráfico de Excel heredado incrustado como objeto OLE en PowerPoint o Word.

- Este cambio corrige un problema por el que, en la vista de dos páginas, al crear un comentario, el anclaje del comentario no siempre aparecía.

- Se ha corregido un problema que hacía que si un párrafo con un estilo antecesor de un estilo estaba vinculado a una lista, se podía perder la numeración de la lista.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2004-march-27"></a>Versión 2004: 27 de marzo
*Versión 2004 (compilación 12718.20010)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Nueva opción para desactivar la mención de sugerencias al escribir el correo: **¿Encuentra el selector de @ menciones más molesto que útil? Ahora puede apagarlo si lo prefiere.

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook
- Aborde un problema que hizo que el botón "Guardar en la nube" faltara en las herramientas de adjuntos.
- Aborde un problema que hizo que los usuarios no pudieran agregar una firma al responder a un mensaje administrado con derechos digitales desde una ventana de inspección cuando el usuario no tiene permiso de propietario sobre el mensaje al que se responde.
- Aborde un problema que hizo que los usuarios no pudieran agregar archivos adjuntos adicionales desde una ubicación web a una reunión creada previamente.

### <a name="powerpoint"></a>PowerPoint
- Este cambio corrige un error que podría causar que los archivos de PowerPoint que contienen emojis fallen al guardarlos.

### <a name="project"></a>Project
- Se ha solucionado un problema por el que si se ejecuta "Lista de valores de campos personalizados GetItem" y no existe una tabla de búsqueda para el campo personalizado, se crea una tabla de búsqueda vacía aunque no debería existir.

### <a name="word"></a>Word
- Este cambio corrige un problema con varias páginas seleccionadas en el menú Ver, donde el panel de comentarios podía mostrarse en blanco.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2004-march-20"></a>Versión 2004: 20 de marzo
*Versión 2004 (compilación 12711.20000)*

[//]: # (NO QUITAR DETALLES DE CARACTERÍSTICAS CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Actualización visual del calendario:** el año pasado, hemos incorporado una experiencia de correo actualizada y este año le toca al calendario tener una cara nueva. Las actualizaciones son recientes pero son familiares, para que, como usuario de Outlook veterano, pueda empezar a ser más productivo en seguida.

- **Protección de datos del grupo:** la etiqueta de confidencialidad que elija al crear un grupo se aplica al correo electrónico, a los documentos y a los sitios del grupo

### <a name="powerpoint"></a>PowerPoint

- **Actualización de las diapositivas durante la presentación:** actualice diapositivas editadas por otros autores durante la presentación.

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Este cambio corrige retrasos al procesar imágenes con información de protocolo mal formada o incorrecta.

### <a name="outlook"></a>Outlook

- Este cambio corrige retrasos al procesar imágenes con información de protocolo mal formada o incorrecta.

- Este cambio corrige un problema por el que los cambios más recientes en los borradores de correo electrónico no se actualizaban.

- Se corrigió un problema por el que hacer clic derecho del mouse en un archivo y usar "Enviar a" no funcionaba.

- Se corrigió un problema por el que si un usuario tenía una ruta de búsqueda personalizada para la libreta de direcciones, el ámbito de la resolución de nombres de Outlook se limitaba a la ruta personalizada, en lugar de incluir la lista global de direcciones (LGD).

- Se corrigió un problema por el que, al ordenar los resultados por categorías, en un conjunto de resultados de búsqueda devuelto no se mostraban los colores de la categoría.

### <a name="project"></a>Project

- Se corrigió un problema por el que el evento "ProjectBeforeTaskChange" de las aplicaciones de Visual Basic (VBA) no se activaba cuando un usuario hacía clic en el botón "Desactivar" que se encuentra en la cinta de tareas en el grupo de programación.

- Si establece los detalles de predecesor o sucesor desde una vista de tipo formulario, el evento de las aplicaciones de Visual Basic (VBA) ProjectBeforeTaskChange no siempre captura los cambios. Por ejemplo, si ha eliminado una dependencia y ha hecho clic en Aceptar en el formulario, el evento no se ha desencadenado. Este comportamiento se ha corregido.

- Se corrigió un problema por el que los valores más recientes del coste real del trabajo realizado (CRTR) no se mostraba después de realizar un cambio, como un cambio de fecha.

- Se corrigió un problema por el que al abrir un proyecto con el menú Usados más recientemente se abría el archivo de proyecto con acceso de lectura y escritura.

- Este cambio corrige un problema por el que si creaba una tarea manual con una fecha y hora de inicio (sin la duración), se mostraba con una hora incorrecta en la escala de tiempo.

- Se corrigió un problema por el que la impresión de una escala de tiempo con el calendario Hijri saltaba un mes o lo duplicaba en la vista de impresión.

- Este cambio resuelve un problema por el que trabajar en el Organizador de equipo con objetos de GDI podía provocar la sobreasignación de dichos objetos y crear condiciones de memoria insuficiente.

### <a name="word"></a>Word

- Se corrigió un problema por el que se había deshabilitado la función para publicar comentarios.

- Este cambio corrige retrasos al procesar imágenes con información de protocolo mal formada o incorrecta.

- Este cambio resuelve un problema en el que el administrador de cuentas no enviaba mensajes, lo que provocaba un error en aplicaciones de terceros.

- Este cambio corrige un problema en el que la tabla de contenido se actualizaba con estilos de título que no estaban presentes en el documento.

- Se corrigió un problema por el que las firmas digitales guardadas en documentos de Word se eliminaban al enviar los documentos.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2004-march-13"></a>Versión 2004: 13 de marzo
*Versión 2004 (compilación 12703.20010)*

[//]: # (NO QUITAR DETALLES DE CARACTERÍSTICAS CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características

### <a name="excel"></a>Excel
- **Etiquetas de confidencialidad**: ahora puede aplicar una etiqueta de confidencialidad que la organización ha configurado para pedirle permisos personalizados. [Más información](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a>PowerPoint
- **Etiquetas de confidencialidad**: ahora puede aplicar una etiqueta de confidencialidad que la organización ha configurado para pedirle permisos personalizados. [Más información](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a>Word
- **Etiquetas de confidencialidad**: ahora puede aplicar una etiqueta de confidencialidad que la organización ha configurado para pedirle permisos personalizados. [Más información](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos

### <a name="access"></a>Access
- Se ha corregido un problema por el que las versiones internacionales de Access mostraban cadenas en inglés en la interfaz de usuario.

### <a name="excel"></a>Excel
- Se ha corregido un problema de rendimiento que los usuarios pueden haber experimentado al editar un rango de celdas grande por programación.
- Se ha corregido un problema de rendimiento al abrir archivos CSV con entornos japoneses.

### <a name="outlook"></a>Outlook
- Corrige un problema que causaba que la fecha de "última modificación" de un archivo se actualizara al agregar un archivo adjunto a un correo electrónico o al guardar un archivo adjunto desde un correo arrastrándolo y colocándolo (en lugar de hacerlo a través de un menú).
- Corrige un problema que provocaba que al presionar Entrar en el panel de búsqueda expandido no se iniciara la búsqueda y requería que los usuarios hiciesen clic en el botón de búsqueda.
- Se ha corregido un problema por el que la búsqueda no muestra información sobre los usuarios cuando se ha deshabilitado la opción "Mostrar fotografías de usuario cuando estén disponibles".

### <a name="project"></a>Project
- Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.
- Corregido un problema en el que el evento OnUndoOrRedo no se desencadena sin ejecutar primero el método OpenUndoTransaction.

### <a name="word"></a>Word
- Se ha corregido un problema por el que al escribir o editar un comentario y usar Ctrl + A se seleccionaba texto en el lienzo en lugar de seleccionar texto en la tarjeta del comentario.
- Se ha corregido un problema por el que la alineación de las palabras de un documento se puede codificar al intentar editar después de imprimir con la impresión rápida.
- Se ha corregido un problema al combinar dos documentos en uno.
- Se ha corregido un problema que hacía que el marcado de revisiones que impliquen ecuaciones ocasionase un error al guardar el archivo.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2003-march-06"></a>Versión 2003: 06 de marzo
*Versión 2003 (compilación 12624.20086)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha corregido un problema que hacía que la creación de una regla con Outlook Web Access no se almacenara en el servidor de Exchange y producía un conflicto.
- Se ha corregido un problema por el que, en el modo oscuro de Outlook, no se mostraba la lista desplegable en el campo "De:".
- Corrige un problema por el que los usuarios no pueden adjuntar un archivo a un mensaje de correo electrónico a través del explorador de archivos cuando el archivo se abre en otra aplicación.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema por el que las miniaturas recomendadas parpadean al pasar el ratón por encima de las miniaturas. En algunos casos, esto provocaba un bloqueo de PowerPoint.

### <a name="word"></a>Word

- Se ha corregido un problema con la característica de comparación de los documentos protegidos para la edición.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema en Word/Excel/PowerPoint donde el nombre principal de usuario (UPN) ya no distingue entre mayúsculas y minúsculas, lo que provoca menos errores al trabajar con archivos en SharePoint.

- Se ha corregido un problema estético en el que el botón "Aceptar" del cuadro de diálogo de Archivo \ Opciones se mostraba atenuado, pero la función no se veía afectada.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

[//]: # (NO QUITAR DETALLES DE CARACTERÍSTICAS CONTENIDO INICIO)

## <a name="version-2003-february-28"></a>Versión 2003: 28 de febrero
*Versión de 2003 (compilación 12619.20002)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Notificación de incidentes para administradores de TI:** se notificará a los administradores globales de espacios empresariales de Microsoft 365 y a los administradores de aplicaciones de Office acerca de los incidentes de Outlook y Exchange de O365 que afectan a sus usuarios con una nueva notificación en el panel derecho en Outlook para Windows. [Más información](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

### <a name="powerpoint"></a>PowerPoint

- **Se ha mejorado la experiencia de creación de diagramas con entrada de lápiz a formas:** dibuje mejores diagramas y convierta en objetos de Office que pueda manipular [Obtenga más información.](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema en el que el texto de una segmentación de datos no se escala correctamente en la vista previa de impresión.

### <a name="outlook"></a>Outlook

- Corrige un problema que causaba que la fecha de "última modificación" de un archivo se actualizara al agregar un archivo adjunto a un correo electrónico o al guardar un archivo adjunto desde un correo arrastrándolo y colocándolo (en lugar de hacerlo a través de un menú).

### <a name="word"></a>Word

- Se ha corregido un problema por el que al ir a la tarjeta del comentario, el foco en el cuadro de edición del comentario no era visible.

- Si se inserta un control (como un control de contenido de texto) en una ecuación, al guardar y abrir el archivo se produce un error de contenido ilegible.

- Se ha corregido un problema que hacía que no se pudiera guardar un archivo protegido con contraseña anteriormente en un almacenamiento en la nube.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Corrige un problema por el que cuando hay varios documentos abiertos en Word/Excel/PowerPoint de la misma biblioteca de SharePoint, solo se analizará el primer documento abierto para el cumplimiento de las directivas.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2003-february-21"></a>Versión 2003: 21 de febrero
*Versión 2003 (compilación 12615.20000)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- **Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos

### <a name="excel"></a>Excel
- Se ha corregido un problema que los usuarios pueden haber experimentado al cambiar el nombre de las medidas de tabla dinámica.
- Se ha corregido un problema de rendimiento que los usuarios pueden haber experimentado al usar una macro de VBA para borrar el contenido de un rango.
- Se ha corregido un problema que provocaba que la interfaz de usuario parpadeara cuando un usuario ejecutaba una macro que interactuaba con la cinta de opciones.
- Se ha corregido un problema por el que los archivos CSV se cargaban de forma incorrecta cuando la primera palabra del archivo estaba era TABLE.
- Se ha corregido un problema por el que los usuarios pueden haber sufrido bloqueos al cambiar entre dos libros que tienen diferentes niveles de zoom.

### <a name="outlook"></a>Outlook
- Se ha corregido un problema que provocaba que los usuarios no puedan abrir mensajes de la carpeta pública cuando Outlook se dejaba en marcha durante la noche.
- Se ha corregido una condición en la que los botones "Permitir" y "Denegar" de la página de permisos se deshabilitan durante el flujo de trabajo de autenticación para agregar una cuenta de Gmail.
- Se ha corregido un problema que hizo que Outlook generara inesperadamente resultados de registro en algunas situaciones, incluso cuando el registro se desactivaba.

### <a name="word"></a>Word
- Se ha corregido un problema en el que las tarjetas con comentario no siempre se resaltan cuando se desplaza el puntero del mouse sobre la tarjeta del comentario.
- Durante una sesión de coautoría de documentos activos, agregar una imagen directamente en una tarjeta de comentario puede dar como resultado la adición de una etiqueta. Este problema se ha corregido.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office
- Al usar las propiedades Multichoice/Lookup/Managed-metadata con documentos de Word/Excel/PowerPoint y guardar en una biblioteca de documentos de SharePoint, estas propiedades se limitaban anteriormente a 255 caracteres. Cuando estas propiedades superaban 255 caracteres, estos documentos no se podían guardar. Con este cambio, este límite se ha aumentado a 2048 caracteres.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2003-february-14"></a>Versión 2003: 14 de febrero
*Versión 2003 (compilación 12607.20000)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Nueva experiencia para redes WiFi cautivas:** ¿alguna vez se ha unido a una red WiFi que requiere una página web para iniciar sesión? Outlook ahora lo detecta y le ayuda a estar conectado.

### <a name="word"></a>Word

- **Busque el editor de entrada de lápiz en el cuadro de herramientas de dibujo:** seleccione Dibujar y seleccione el lápiz del editor de entrada de lápiz para editar el documento con el dedo o un lápiz digital. [Más información](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- **Iconos de la barra de estado más nítidos:** los iconos de la barra de estado ahora son más fáciles de ver

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que los usuarios perdieran el acceso al cuadro de diálogo de permisos de calendario "opciones de disponibilidad".

- Se ha corregido un problema que podría provocar la alerta: "lo sentimos, tenemos problemas para abrir este elemento" al abrir algunas instancias de reuniones periódicas que se han enviado desde una zona horaria diferente.

- Se ha corregido un problema que podría ocasionar que los usuarios no puedan abrir un archivo .msg después de arrastrar y soltar datos adjuntos desde el mensaje.

- Se ha corregido un problema por el que, después de cargar un archivo adjunto desde Outlook a OneDrive, se podía cambiar el nombre de archivo si el nombre de los datos adjuntos contenía paréntesis.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema que podría provocar un error al guardar un documento en PowerPoint o en Word con un gráfico de Excel.

### <a name="word"></a>Word

- Se ha corregido un problema por el que las imágenes de los documentos pierden transparencia al exportarse a PDF.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-february-07"></a>Versión 2002: 07 de febrero
*Versión 2002 (Compilación 12527.20040)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="access"></a>Access

- **Aumente su productividad con el Diseñador de consultas, la vista SQL y la ventana Relaciones:** haga clic con el botón derecho en una tabla para abrirla, diseñarla, cambiar su tamaño y ocultarla. Buscar y reemplazar texto en la vista SQL. Seleccione múltiples tablas en la ventana Relaciones.

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Esta actualización corrige un problema por el que al usar un objeto de grabación de ADODB en el código de VB, se puede notificar un error incorrectamente.

- Esta actualización corrige un problema que puede hacer que Microsoft Access no identifique una Columna de identidad en una tabla vinculada de SQL Server, lo que puede provocar que las filas aparezcan como eliminadas de forma incorrecta.

### <a name="excel"></a>Excel

- Se ha corregido un problema por el que Excel se bloquea al usar la opción Texto a columnas con matrices dinámicas.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema en el que el desplazamiento en el calendario con la vista de mes no muestra eventos de calendario anteriores.

- Corrige un problema que causaba que los usuarios sufrieran un error al visualizar más de 30 calendarios en un entorno Citrix.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema que provocaba que, después de cerrar un archivo, PowerPoint no lo quitara inmediatamente de la colección Presentaciones si había algún controlador de eventos en ejecución. Por lo tanto, el número de presentaciones que informa el modelo de objetos es incorrecto y se evita el cierre de PowerPoint.

- Se ha corregido un problema con el marcador de resaltado: los textos blancos con un marcador oscuro se imprimen como negros en escala de grises.

### <a name="word"></a>Word

- Al actualizar y desplazarse por una tabla de contenido, es posible que se muestre un área gris en el documento.

- Se ha corregido un problema por el que si se trabajaba en coautoría en un documento, la versión de borrador de un comentario raíz podía no conservarse.

- Se ha corregido un problema por el que al ir de una tarjeta de comentario a otra se podía mostrar el comentario seleccionado inicialmente con una selección resaltada.

- Se ha corregido un problema por el que usar "Examinar" para guardar un archivo podía no funcionar si se escribió un comentario sin publicarlo y el usuario intentó guardar el archivo.

- Con el Control de cambios habilitado y el panel de comentarios cerrado, Ctrl + Alt + M podía no funcionar para abrir el panel Comentarios.

- Corregido un problema al agregar una @mención en una tabla que podía generar el mensaje de error: "Una tabla de este documento está dañada".

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Resuelto un problema que podía causar que el paquete de herramientas de corrección de Noruega Nynorsk (NN-no) no se instalara correctamente.

[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)


[//]: # (NO MODIFICAR EL INICIO DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)
[//]: # (|Win32|DevMain|Insiders| |16.0.13115.20000|version-2008-july-17|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13102.20002|version-2008-july-10|)
[//]: # (NO MODIFICAR FIN DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)