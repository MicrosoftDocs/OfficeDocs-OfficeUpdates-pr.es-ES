---
title: Notas de la versión del canal actual (versión preliminar)
ms.author: anankani
author: v-lislo
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 'Proporciona a los participantes del modo anticipado de Insider Lento la lista más reciente de las nuevas características, correcciones o problemas conocidos principales '
ms.openlocfilehash: 1a9ce7dee810cb11e7b77a0e97aa0f89fb64cb86
ms.sourcegitcommit: 5f56314a735aa6d24dec23182dbd7f343e32f87f
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 07/21/2020
ms.locfileid: "45189803"
---
# <a name="release-notes-for-office-current-channel-preview"></a>Notas de la versión del canal actual de Office (versión preliminar)

En este artículo hay notas de la versión para las compilaciones del canal actual (versión preliminar) de las versiones de escritorio de Word, Excel, PowerPoint, Outlook, Access y Project para Windows. Todas las semanas se incluyen las nuevas características, correcciones importantes y los problemas principales de mayor interés para usted. Tenga en cuenta que a menudo publicamos características (y a veces incluso correcciones) para el Canal actual (versión preliminar) durante un período de tiempo. Esto nos permite asegurarnos de que todo funciona correctamente antes de publicar la característica para un público más amplio. Por tanto, si a continuación no ve algo descrito, no se preocupe, lo recibirá con el tiempo.  

> [!IMPORTANT]
> Estamos realizando algunos cambios en los canales de actualización de las Aplicaciones de Microsoft 365, incluida la adición de un nuevo canal de actualización (canal empresarial mensual) y el cambio de los nombres de los canales de actualización existentes. [Lea este artículo](https://go.microsoft.com/fwlink/p/?linkid=2127441) para obtener más información.

> [!NOTE]
> - La fecha de publicación de las notas de versión pueden no coincidir con la fecha real de lanzamiento de la compilación.

[//]: # (NO ELIMINAR)

## <a name="version-2007-july-20"></a>Versión 2007: 20 de julio
*Versión 2007 (compilación 13029.20236)*
* Varias correcciones de errores y rendimiento.

## <a name="version-2007-july-15"></a>Versión 2007: 15 de julio
*Versión 2007 (compilación 13029.20200)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Cree diagramas de Visio elegantes en Excel:** cree un diagrama de flujo o un organigrama con solo escribir datos en una hoja de cálculo. [Más información](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Acceso

- Se ha corregido un problema por el que el administrador de tablas vinculadas solicitaba una clave principal al actualizar una tabla SQL vinculada.

- Se ha corregido un problema por el que las consultas en el Editor de consultas quedaban desplazadas fuera de la vista.

- Se ha corregido un problema que provocaba que la ejecución de consultas tardara en completarse aproximadamente el doble del tiempo esperado.

- Se ha corregido un problema que provocaba que Microsoft Access no identificara una Columna de identidad en una tabla vinculada de SQL Server, lo que podía hacer que las filas aparecieran como eliminadas de forma incorrecta.

### <a name="excel"></a>Excel

- Se ha corregido un problema por el que las direcciones URL que no se basaban en http o https no se mostraban en la lista Utilizado recientemente.

- Se ha corregido un problema por el que podía producirse un error o bloqueo al cargar un libro con varias hojas en la vista previa de salto de página.

- Se ha corregido un problema por el que las tablas del modelo de datos creadas en algunas versiones de Excel no se podían ver en "Vista previa de la tabla", pese a que no se había editado la consulta asociada a la tabla.

- La opción "Omitir tipo de referencia (relativa o absoluta)" en el cuadro de diálogo "Definir nombre/Aplicar nombres" provocaba que las fórmulas no funcionaran.

- Se ha corregido un problema que provocaba que se quitara el XML de CustomUI para una ficha de cinta personalizada al guardar un libro de trabajo en SharePoint o OneDrive.

- Se ha corregido un problema que provocaba que los libros de trabajo fueran de solo lectura cuando el archivo tenía activada la casilla "Se recomienda solo lectura".

- Se ha corregido un problema por el que podía producirse un error o bloqueo al cargar un libro con varias hojas en la vista previa de salto de página.

- Se ha corregido un problema por el que no se podía aplicar el formato correcto a las líneas de cuadrícula principales de los gráficos radiales.


- Se ha corregido un problema por el que al quitar filtros avanzados de datos se borraba el formato de tabla.


- Se ha corregido un problema que provocaba que la ruta de acceso completa de un documento PDF incrustado se mostrara en el título del documento, en lugar de mostrarse solo en el nombre de archivo.


- Se ha corregido un problema por el que deshabilitar el CloudConnector de Wolfram y, a continuación, guardar y volver a abrir un libro de Excel podía dar lugar a un bloqueo.


- Se ha corregido un problema por el que iniciar Excel con el complemento Solver habilitado daba lugar a un bloqueo.


### <a name="outlook"></a>Outlook

- Se ha corregido un problema por el que Outlook se bloqueaba si había más de 130 destinatarios en la línea "Para". Asimismo, se ha mejorado el rendimiento del procesamiento de texto.


- Se ha corregido un problema por el que la ventana del Editor de métodos de entrada (IME) se superponía al texto subyacente escrito mediante el IME al utilizar varios monitores con resoluciones diferentes.


- Se ha corregido un problema en la barra "Tareas Pendientes" que provocaba que los eventos que ocupaban más de dos días mostraran la misma hora de finalización para los siguientes días.


- Se ha corregido un problema que causaba que la fecha de creación de datos adjuntos copiados en el sistema de archivos a través de la opción de arrastrar y soltar apareciera como el 1 de enero de 4501.


- Se ha corregido un problema por el que los usuarios no podían "Enviar como" o "Enviar en nombre de" en una lista de distribución.


- Se ha corregido un problema que causaba que los delegados reciban un error al editar una cita de calendario existente en el calendario de un administrador.


- Se ha corregido un problema que provocaba que los usuarios vieran el siguiente error al cerrar una cita guardada previamente: "No se puede guardar el elemento, porque lo cambió otro usuario o se modificó en otra ventana. ¿Desea copiarlo en la carpeta predeterminada del elemento?


- Se ha corregido un problema que causaba que faltara la opción "Permitir reenvío" en las "Opciones de respuesta" de la reunión de calendario compartida cuando NO está marcado Descargar carpeta compartida.


- Se ha corregido un problema que evitaba que los usuarios guardaran los datos adjuntos de OneDrive desde fuera de su inquilino en su equipo local al seleccionar la opción "Guardar" en el cuadro de diálogo de seguridad.


- Se ha corregido un problema que provocaba que la lista de mensajes dejara de actualizarse durante varios minutos después de que los usuarios de Outlook usaran calendarios compartidos.


- Se ha corregido un problema que impedía que los avisos del calendario mostraran la hora exacta de las reuniones programadas que iban a tener lugar en menos de una semana. 


- Se ha corregido un problema por el que, al insertar una imagen en un mensaje y, a continuación, guardar el mensaje como borrador, se cambiaba el tamaño de la imagen.


- Se ha corregido un problema que provocaba que el cuerpo de un mensaje NDR cambiara de Unicode a ASCII después de editar el asunto.


- Se ha corregido un problema por el que las fechas del minicalendario no se podían mostrar en negrita para los usuarios de Japón.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema por el que el indicador de color de presencia de un usuario no se actualizaba en la galería de coautoría durante una sesión de coautoría en directo.


- Se ha corregido un problema por el que, al tratar de pegar código HTML en un área de texto en una diapositiva, el código se pegaba en un cuadro de texto creado en la parte superior de la diapositiva.


- Se ha corregido un problema por el que, al seleccionar todas las diapositivas en la vista Moderador y, a continuación, salir de dicha vista mediante ALT+TAB, volver a la presentación con diapositivas y hacer clic en "Finalizar presentación", tenía lugar una excepción no controlada.


### <a name="project"></a>Project

- Se ha corregido un problema que impedía guardar desde Project un PDF o XPS en una biblioteca de documentos de SharePoint.


- Se ha corregido un problema por el que los proyectos no se podían abrir en el cliente de escritorio de Project desde Project Web App si la dirección URL terminaba en .com.


- Se ha corregido un problema que provocaba que Project se bloqueara al abrir determinados archivos XML.


- Se ha corregido un problema por el que los proyectos no se podían abrir en el cliente de escritorio de Project en Project Web App si la dirección URL finalizaba en ".com".


- Se ha corregido un problema por el que si pegaba una tarea que tenía varias dependencias, no todas las dependencias se copiaban correctamente.


- Se ha corregido un problema por el que la tarea seleccionada en el cuadro de diálogo de asignación de recursos no era la misma que la tarea seleccionada en la vista del panel de tareas.


- Se ha corregido un problema que provocaba que el evento ProjectBeforeTaskChange no se activara al tener lugar un cambio en la tarea de resumen del proyecto, ya fuera en el campo de inicio o de tarea del proyecto.


- Se ha corregido un problema por el que, si las tareas de duración fija estaban completas al 100 %, pero no se especificaba la fecha de finalización real, el porcentaje de finalización de la tarea se mostraba como inferior al 100 %.

- Se ha corregido un problema por el que una actualización o un restablecimiento de la línea base podía cambiar los recursos de trabajo o el costo presupuestado con fases temporales, y la línea base podía reflejar valores de presupuesto incorrectos.


- Se ha corregido un problema que consistía en que los vínculos de Project Planner en entornos de Government Community Cloud habían sido deshabilitados.


- Se ha corregido un problema por el que no se podía abrir un archivo de Project de una biblioteca de documentos de SharePoint si la biblioteca estaba en modo moderno.


### <a name="word"></a>Word

- Se ha corregido un problema por el que no funcionaba la opción de borrar el formato en el Panel Comentarios mediante el botón Borrar formato de la cinta de opciones de Office.


- Se ha corregido un problema por el que el texto insertado en un archivo de gráficos vectoriales escalables (SVG) quedaba ilegible tras insertarlo en un archivo de Word, Excel o PowerPoint, guardar y cerrar el archivo y, a continuación, volver a abrirlo.


- Se ha corregido un problema que provocaba que otras aplicaciones que se ejecutaban en segundo plano comenzaran a parpadear al cambiar el tamaño de una tabla cuando la regla no se mostraba.


- Se ha corregido un problema por el que, en el modo de coautoría, las respuestas a los comentarios no se mostraban en el panel de comentarios en ocasiones, pero eran visibles en el panel de revisiones.


- Se ha corregido un problema en el modo de coautoría: cuando se produce un conflicto de fusión y el usuario ya ha elegido previamente descartar los cambios, ya no se muestra la opción que da a elegir entre guardar o descartar los cambios.


- Se ha corregido un problema por el que el color de los hipervínculos HTML no se representaba correctamente.


- Se ha corregido un problema por el que, si Word tenía una lista de más de 50 documentos abiertos con frecuencia, después de guardar y abrir un documento, se mostraba un historial de revisiones pese a que no se había modificado dicho documento.


- Se ha corregido el problema con la opción de autoguardado durante la coautoría.


- Se ha corregido un problema por el que, al intentar guardar un archivo que contenía una macro con un nombre nuevo, este se guardaba con la extensión .docx y el nombre de archivo "WRO0004.docx", independientemente de lo que el usuario escribiera, lo que provocaba que el archivo no se pudiera volver a usar.


### <a name="office-suite"></a>Conjunto de programas de Office

- Un problema de temporización podía provocar un bloqueo al cerrar archivos de Office.

- La corrección para este problema era asegurarse de que el servicio computase correctamente los productos agregados. Se han filtrado los nuevos productos agregados (lo que garantiza que también se encuentren en la nueva configuración) y se han agregado al final de los ID de versión de producto existentes.



[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2006-july-09"></a>Versión 2006: 09 de julio
*Versión 2006 (compilación 13001.20384)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Realice una conexión PDF:** Conectar, importar, actualizar los datos de un PDF. [Más información](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- **Crear variables para usar en fórmulas:** mejorar el rendimiento, la legibilidad y la composición con la función LET. Esta función le permite crear variables con nombre en fórmulas nuevas o previamente existentes. [Más información](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)

- **Métodos abreviados de teclado de Excel:** métodos abreviados de teclado actualizados para Excel

### <a name="outlook"></a>Outlook

- **Crear sondeos en Outlook con Sondeo rápido:** cree sondeos, recopile votos y vea los resultados rápidamente en un solo correo electrónico [Más información](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)

- ** Mantenga la fidelidad de sus imágenes cuando las envíe como parte de un correo electrónico:** una nueva configuración de Outlook está disponible para limitar la compresión de imágenes cuando envía imágenes como parte de contenido del correo electrónico


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Este problema se ha resuelto y ahora debería ser capaz de insertar correctamente tablas SQL vinculadas que incluyan un campo de identidad (por ejemplo, autonumeración) en Access.

### <a name="excel"></a>Excel

- Se ha corregido un bloqueo que podría producirse al intentar crear una conexión de datos si había cerrado la sesión de su cuenta.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema que evitaba que los usuarios guardaran los datos adjuntos de OneDrive desde fuera de su inquilino en su equipo local al seleccionar la opción "Guardar" en el cuadro de diálogo de seguridad.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Hemos modificado la versión AppV51 para solucionar una regresión de la AppV51 anterior.

- El host de Office se bloqueaba en Windows al activar un complemento cuando el valor del registro TabProcGrowth era del tipo REG_SZ y tenía el valor "0".  El valor de TabProcGrowth del registro puede encontrarse en una de estas cuatro rutas: HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER \Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE \Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER \Software\Policies\Microsoft\Internet Explorer\Main. Este cambio solucionaría el problema.


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2006-june-25"></a>Versión 2006: 25 de junio
*Versión 2006 (compilación 13001.20266)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="visio"></a>Visio

- **Cree diagramas de Visio elegantes en Excel:** cree un diagrama de flujo o un organigrama basado en datos en una hoja de cálculo.


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Este problema se ha resuelto. Informe al equipo si tiene problemas con este proceso.


### <a name="outlook"></a>Outlook

- <span style="display:inline !important;">Se ha corregido un problema que causaba que<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">la fecha de creación de&nbsp; datos adjuntos copiados en el sistema de archivos a través de la opción de arrastrar y soltar&nbsp; apareciera como el 1 de enero de 4501.</span><br>


- <span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Se ha corregido un problema que provocaba que los usuarios de las mejoras del Calendario compartido vieran errores en el calendario.</span><br>


- <span style="display:inline !important;">Se ha corregido un problema que provocaba que los usuarios de Outlook vieran continuamente un aviso para que ejecutaran la herramienta de Reparación de la bandeja de entrada.</span><br>


- <span style="display:inline !important;">Se ha corregido un problema por el que la búsqueda de una característica en Sugerir una característica no devolvía resultados y no ofrecía al usuario ninguna opción para enviar una nueva característica.</span><br>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2006-june-18"></a>Versión 2006: 18 de junio
*Versión 2006 (compilación 13001.20198)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel



- **Guardar en Carpetas ancladas:** anclar tus carpetas hace que el almacenamiento de archivos de Office sea más fácil. Nuestros usuarios nos dijeron que querían tener más control sobre las carpetas disponibles al guardar un archivo nuevo. Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar. Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil. <br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

### <a name="powerpoint"></a>PowerPoint

- **Guardar en Carpetas ancladas:** anclar tus carpetas hace que el almacenamiento de archivos de Office sea más fácil. Nuestros usuarios nos dijeron que querían tener más control sobre las carpetas disponibles al guardar un archivo nuevo. Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar. Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil.<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

### <a name="word"></a>Word

- **Guardar en Carpetas ancladas:** anclar tus carpetas hace que el almacenamiento de archivos de Office sea más fácil. Nuestros usuarios nos dijeron que querían tener más control sobre las carpetas disponibles al guardar un archivo nuevo. Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar. Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil. <br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema que provocaba que se quitara el XML de CustomUI para una ficha de cinta al guardar en SharePoint o OneDrive.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que Ctrl + clic dejara de funcionar cuando se habilitaba la configuración de la nube.

### <a name="project"></a>Project

- Se ha corregido un problema por el que una tarea marcada como completada al 100 % se mostraba por error no completada al 100 %.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2006-june-11"></a>Versión 2006: 11 de junio
*Versión 2006 (compilación 13001.20144)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="powerpoint"></a>PowerPoint

- **Mejor rendimiento de vídeos de Stream en PowerPoint:** hemos realizado mejoras en el rendimiento de la reproducción de los vídeos de Microsoft Stream para reducir el tiempo de carga de vídeo y crear una visualización más suave. Use los vídeos corporativos de Microsoft Stream para crear presentaciones mejoradas.

### <a name="word"></a>Word

- **Retener texto en vectores:** ahora puede conservar el texto en mapas, gráficos y otros vectores de SVG al convertir estos objetos en Excel, Word y PowerPoint.


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema por el que Excel se cerraba ocasionalmente al utilizar OneDrive.

- Se ha corregido un problema por el que los valores personalizados en el eje del gráfico no se aplicaban correctamente.

- Se ha corregido un problema por el que las hojas de cálculo que contienen varias fórmulas con nombres definidos tardaban más en guardarse.

- Hemos corregido un problema que provocaba que los nombres de las impresoras se duplicaran en la lista de impresoras disponibles.

- Hemos corregido un problema para que los usuarios tengan un mejor rendimiento al eliminar las columnas combinadas.

- Se ha corregido un problema por el que aparecía el mensaje de error "No se puede cerrar el libro debido a que otro libro hace referencia a él" si los complementos se cargaban en orden alfabético en lugar de en un orden especificado por el usuario.

- Se ha corregido un problema en el que administrar fuentes entre Excel y algunas aplicaciones tecnológicas de asistencia de terceros causaba problemas de memoria.

- Se ha corregido un problema por el que al hacer clic en un hipervínculo marcado en el mismo libro hacía que el libro se ocultara.

- Se ha corregido un problema por el que algunos vínculos de un gráfico copiado y pegado usaban direcciones de unidad asignadas, en lugar de direcciones universales.

- Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.

- Se ha corregido un problema por el que Excel se bloqueaba cuando los complementos solicitaban elementos de host en hojas de cálculo que tuvieran formas con bloqueos noSelect.

- Se ha corregido un problema por el que Excel se bloqueaba al intentar insertar tablas dinámicas en una hoja de gráfico.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema por el que la ventana del Editor de métodos de entrada (IME) se superponía al texto subyacente escrito mediante el IME cuando se usaban varios monitores con resoluciones diferentes.

- Se ha corregido un problema que causaba un bloqueo cuando se visualizaba una plantilla mientras se redactaba un nuevo mensaje de correo electrónico.

- Se ha corregido un problema por el que los usuarios no podían intercambiar carpetas públicas de Exchange 2010 después de la versión 1911 de Outlook.

- Se ha corregido un problema por el que se desactivaba el botón de Categorizar para los calendarios de grupo en la cinta de opciones de Office.

- Se ha corregido un problema por el que Outlook no pudo habilitar consejos de directiva para la Protección de pérdida de datos para usuarios que pagaron por el servicio con planes M365 Business Plus.

- Se ha corregido un problema que provocaba que Outlook se bloqueara en algunas compilaciones de Windows.

- Se ha corregido un problema por el que los usuarios no pudieron compartir un calendario con un usuario invitado.

- Se ha corregido un problema en el que los usuarios veían los elementos de calendario que pasaban de la medianoche como Eventos de todo el día.

- Se ha corregido un problema por el que la lista desplegable en las propiedades de carpeta del Archivo en línea no aparecía en monitores con un alto nivel de ppp.

- Se ha corregido un problema por el que el evento Folder.BeforeItemMove no se activaba correctamente cuando un usuario movía elementos entre carpetas.

- Se ha corregido un problema por el que Outlook se bloqueaba cuando dos complementos agregaban un botón al mismo grupo en la cinta de opciones.

- Se ha corregido un problema que provocaba un error en Outlook al trabajar con hipervínculos en mensajes de correo electrónico de texto sin formato.

- Se ha corregido un problema que provocaba que Outlook no pudiera analizar nombres de archivo largos codificados con RFC2231.

- Se ha corregido un problema que provocaba que los usuarios de Outlook experimentaran interrupciones intermitentes al usar lectores de pantalla.

- Se ha corregido un problema que hacía que los usuarios con contactos en conflicto experimentaran bloqueos en Outlook.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema al abrir archivos configurados por el servidor con autenticación basada en formularios.

- Se ha corregido un problema por el que los archivos de PowerPoint con gráficos o libros incrustados podrían causar errores al guardar el archivo.

- Se ha corregido un problema en el que al acercar y alejar el área de presentación se daba una separación entre el recuadro de selección ampliado y el puntero del mouse.

- Se ha corregido un problema que hacía que las diapositivas no se centraran después de usar la rueda del mouse para hacer zoom.

- Hemos corregido un problema por el que la revisión ortográfica y los métodos abreviados del teclado no funcionaban de manera esperada al usar un teclado de Suiza (QWERTZ) en inglés.

- Se ha corregido un problema por el que un panel de Comentarios cerrado por el usuario se abría automáticamente de nuevo.

- Se ha corregido un problema por el que el editor de diapositivas de una diapositiva se superponía a la siguiente diapositiva.

### <a name="project"></a>Project

- Se ha corregido un problema por el que el evento ProjectBeforeTaskChange no se activaba al darse un cambio en la tarea de resumen del proyecto: ya sea en el campo de inicio o tarea del proyecto.

- Se ha corregido un problema por el que una tarea marcada como completada al 100 % se mostraba por error no completada al 100 %.

- Se ha corregido un problema por el que Project se bloqueaba después de hacer clic en Opciones.

- Se ha corregido un problema que impedía que las tareas huérfanas se eliminaran o reasignarán después de eliminar su plan primario.

### <a name="visio"></a>Visio

- Se ha corregido la regresión en el código dependiente. Ahora, las imágenes se representan en los servicios de Visio que se ejecutan en SharePoint local.

### <a name="word"></a>Word

- Se ha corregido un problema por el que las marcas de hora en los paneles de comentarios no se basaban en la hora de la configuración regional del sistema.

- Se ha resuelto un problema al abrir documentos de Word desde la entrega de documentos personalizados (aspx) cuando la dirección URL contenía un componente de consulta.

- Se ha corregido un problema por el que no se mostraba un texto copiado y pegado en un panel de comentarios.

- Se ha corregido un problema por el que los hipervínculos en los comentarios no funcionaban.

- Se ha corregido un problema en el que al acercar y alejar el área de presentación se daba una separación entre el recuadro de selección ampliado y el puntero del mouse.

- Se ha corregido un problema por el que los comentarios entre la aplicación web y la aplicación de escritorio no estaban sincronizados.

- Se ha corregido un problema en el que las burbujas de sugerencias de comentarios aparecían borrosas al 100 % de zoom.

- Hemos corregido un problema en el que agregar un nuevo comentario en un documento en blanco no pasaba nada.

- Se ha corregido un problema por el que no funcionaba pegar HTML en WordMail para Calendario.

- Se ha corregido un problema por el que responder a un comentario en una sesión de coautoría podía bloquear Word.

- Hemos corregido un problema que haría que la aplicación se bloqueara cuando se insertara o actualizara un índice en un documento que contuviera más de cien entradas.

- Se ha corregido un problema por el que habilitar la directiva de Word 2007 y, luego, los documentos binarios y de plantillas podía causar errores en ciertos casos de coautoría.

- Hemos corregido un problema que provocaba que los archivos con valores XML personalizados se abrieran muy despacio.

- Se ha corregido un problema por el que no se abrían los archivos con nombres de ruta largos (mayores que 32 000 caracteres) y no se mostraba un mensaje de error adecuado.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Hemos estudiado y resuelto el problema por el que una implementación de Office 365 ProPlus a través de Intune se pausaba después de apagar el SO.

- Hemos corregido un problema en Visual Basic para las aplicaciones de Microsoft Office, por el que la aplicación de Office consideraba como corruptos ciertos proyectos de VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre o la ruta de la biblioteca.

- Esta actualización corrige un problema en Microsoft Office en el que los proyectos de Visual Basic para aplicaciones con referencias que se espera encontrar buscando las ubicaciones especificadas en la variable de entorno PATH podían no encontrarse correctamente en tiempo de ejecución, lo que provoca errores en tiempo de ejecución de VBA.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2005-june-08"></a>Versión 2005: 8 de junio
*Versión 2005 (compilación 12827.20336)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema en el cuadro de diálogo Reemplazar fuente, donde la lista desplegable Reemplazar fuente solo mostraba las fuentes de la presentación, en lugar de las fuentes instaladas en el sistema.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2005-june-04"></a>Versión 2005: 4 de junio
*Versión 2005 (compilación 12827.20320)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="access"></a>Access

- **Manténgase al día con las horas. El tipo de datos Fecha y hora extendida tiene mayor precisión.:** Presentamos un tipo de datos nuevo y mejorado.  Para mejorar la compatibilidad de la sintaxis con SQL y la precisión y el nivel de detalle en los registros que incluyen fechas y horas, estamos implementando el tipo de datos DateTime2 en Access. Este tipo de datos de fecha y hora adicional incluirá un intervalo de fechas mayor (de 0001-01-01 a 9999-12-31), con mayor precisión de tiempo (nanosegundos, en lugar de segundos) en el que se podrán ofrecer y realizar cálculos. Para habilitarlo, seleccione Nuevo campo > Fecha y hora extendida. [Más información](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a>Excel

- **Crear tablas dinámicas de conjuntos de datos en Power BI desde Excel:** puede crear tablas dinámicas en Excel conectadas a los conjuntos de datos almacenados en Power BI con tan solo unos clics.Así, podrá obtener lo mejor de las tablas dinámicas y de Power BI. Calcule, resuma y analice los conjuntos de datos seguros de Power BI con las tablas dinámicas de Excel.

### <a name="outlook"></a>Outlook

- **Opción para volver a abrir rápidamente los elementos de la sesión anterior de Outlook:** hemos agregado una opción para volver a abrir rápidamente los elementos de una sesión anterior de Outlook.


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="powerpoint"></a>PowerPoint

- Hemos corregido un bloqueo cuando el usuario tiene comentarios modernos y heredados en un archivo, lo que provoca una actualización de los comentarios.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Hemos resuelto el problema de la tasa de error de ValidateInstall estableciendo la validación de instalación del Complemento de Bing como verdadera de forma predeterminada y considerando el éxito de devolución de MSI como una instalación con éxito.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2005-may-29"></a>Versión 2005: 29 de mayo
*Versión 2005 (compilación 12827.20268)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características

### <a name="excel"></a>Excel

- **Vista de hoja:** ordenar y filtrar cuando colabore con otras personas en la versión de escritorio de Excel.

### <a name="outlook"></a>Outlook

- **Se agregaron más botones a las notificaciones del sistema de Outlook:** los botones de Acción rápida aparecen ahora en las notificaciones del sistema de Outlook cuando se ejecuta Outlook en Windows 10.


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos



### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que los usuarios de las versiones de Windows 10 Server vieran la advertencia: "Estado de antivirus: no válido". Esta versión de Windows admite la detección del antivirus, pero no se encontró ninguno a pesar de tener un antivirus correctamente instalado".

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- El host de Office se bloqueaba en Windows, cuando se activaba un complemento si la clave del registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth estaba establecida en cero. Este cambio arreglaría el problema.


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2005-may-21"></a>Versión 2005: 21 de mayo
*Versión 2005 (compilación 12827.20210)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)




[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.


- En algunos casos, al hacer clic en un hipervínculo que dirige a un lugar del mismo libro, el libro queda oculto.


### <a name="outlook"></a>Outlook

- Se ha corregido un problema con el evento de auditoría CLP para la etiqueta de responder o reenviar.


- Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al enviar comentarios desde una Notificación de administrador.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2005-may-14"></a>Versión 2005: 14 de mayo
*Versión 2005 (compilación 12827.20160)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Aplicar automáticamente o recomendar etiquetas de confidencialidad:** Office puede recomendar o aplicar automáticamente una etiqueta de confidencialidad basada en el contenido confidencial detectado.

### <a name="powerpoint"></a>PowerPoint

- **No es necesario hacer clic: sus miniauriculares tienen que cubrir lo siguiente:** Usar sus Surface Earbuds para controlar sus presentaciones de PowerPoint. Importante: Debe emparejar sus Surface Earbuds en la aplicación Surface Audio para Windows 10 para poder usar gestos para controlar las presentaciones. Aquí encontrará instrucciones para empezar a usar la aplicación Surface Audio en Windows 10. [Más información](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- **Aplicar automáticamente o recomendar etiquetas de confidencialidad:** Office puede recomendar o aplicar automáticamente una etiqueta de confidencialidad basada en el contenido confidencial detectado.

### <a name="word"></a>Word

- **Aplicar automáticamente o recomendar etiquetas de confidencialidad:** Office puede recomendar o aplicar automáticamente una etiqueta de confidencialidad basada en el contenido confidencial detectado.


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos

### <a name="excel"></a>Excel

- Se aumentó el tamaño de los controles de edición de referencia de celda en el cuadro de diálogo Barras de error personalizadas utilizado con gráficos.

- Se ha corregido un problema por el que las tablas de datos de los gráficos podían representar incorrectamente los valores de un eje de fechas.

- Se ha corregido un problema por el que los saltos de página no se podían deshabilitar después de ir al diseño de página o la vista previa de salto de página

- Se ha corregido un problema por el que los estilos de línea de los gráficos podían perderse tras ocultar y mostrar columnas con datos de series.

- Se ha corregido un problema por el que insertar una columna en una lista filtrada llevaba más tiempo de lo esperado.

- Corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.

- Se ha corregido un problema que hacía que el vínculo externo dejara de funcionar después de que se volviera a abrir el archivo si su ruta de acceso era demasiado larga.

- En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.

- Application.Evaluate (VBA) no funcionaba para funciones definidas por el usuario en algunos casos.

- En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.

- Este cambio corrige un problema que hacía que la información de formato condicional (CF) no se guardase correctamente en los archivos XLSB.

- Este cambio corrige un problema en el que el valor de la línea de tendencia del gráfico R-cuadrado (en el caso de la intersección forzada y) era incorrecto aunque la función de ESTIMACIÓN devuelva el valor correcto.

- Este cambio arregla un problema en el que no siempre se guardaba el formato de la línea de tendencia de los gráficos personalizados.

- Podría producirse un bloqueo al intentar mostrar los cambios en una nueva hoja de un libro con el modo "Libro compartido" heredado.

- Se ha corregido el problema por el que el formato personalizado de un gráfico dinámico podía no guardarse si estaba habilitada la opción "Invertir si es negativo".

- Se ha corregido un problema por el que el formato personalizado de un único punto de datos de un gráfico dinámico no se guardaba si estaba seleccionada la opción "invertir si es negativo".

- Este cambio corrige un problema por el que el carácter "@" cargado en un archivo CSV causaba que la cadena tras el carácter "@" se convirtiera en una fórmula.

- Se ha corregido un problema por el que los valores decimales de la función SECUENCIA no se redondeaban correctamente.

### <a name="onenote"></a>OneNote

- Corregido un problema en el que los saltos de línea se almacenaban como pestañas verticales.

### <a name="outlook"></a>Outlook

- Soluciona un problema que hacía que los usuarios no pudieran agregar un grupo de contactos personal como asistente de la reunión.

- Corregido un problema por el que se desactivaba el botón de Categorizar para los calendarios de grupo en la cinta de opciones de Office.

- Se ha corregido un problema que provocaba que Outlook se bloqueara al abrir archivos .msg y .oft guardados localmente después de una actualización de Windows.

- Se ha solucionado un problema por el que los clientes de las empresas con carpetas de grupo no implementadas o que no funcionaban, hacían que Outlook mostrara un mensaje de "no responde".

- Corrige un problema por el que los safelinks muy largos en los que los usuarios hacían clic en el cliente de escritorio de Outlook no se podían cargar debido a un truncamiento.

- Se ha corregido un problema por el que las carpetas de Outlook con nombres que contenían caracteres DBCS (conjunto de caracteres de doble byte) desaparecían intermitentemente al sincronizar con el servidor. Esto sucedía si Outlook estaba configurado con una cuenta IMAP y se ejecutaba en un sistema con la configuración regional configurada en japonés.

- Se solucionó un problema que hacía que las reglas de eliminación creadas para los buzones que no fueran el buzón principal del usuario dejaran de ser válidas.

- Se solucionó un problema que hacía que los datos adjuntos se perdieran al reenviar un mensaje cifrado.

- Se solucionó un problema que provocaba que las reuniones para las que faltan más de 2 meses no mostraran un tema de reunión en el Asistente de programación.

- Se ha corregido un problema que hacía que los usuarios vieran truncado el cuerpo del mensaje al reenviar mensajes HTML grandes.

- Se agregó la capacidad de aplicar la configuración de firma predeterminada de S/MIME a través de la directiva de grupo.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema por el que el borrador de los comentarios dejaba de estar disponible si un usuario creaba un comentario sin publicarlo, cerraba el panel de comentarios, abría una nueva ventana, se desplazaba por varias diapositivas, cerraba la ventana y volvía a abrir el panel de comentarios en la presentación original.

- Se ha solucionado un problema por el que al pasar el ratón por encima del símbolo del asterisco (*) no aparecía el nombre de usuario y la fecha de la última persona que actualizó el documento.

### <a name="project"></a>Project

- Cuando se editan los datos del Predecesor/Sucesor dentro de una vista de formulario, se activa un evento ProjectBeforeTaskChange adicional.

- Se solucionó un problema por el cual Proyect podía bloquearse al cambiar el campo de estado del tablero en un proyecto que conectado a una lista de tareas de SharePoint.

- Corregido un problema por el que Project puede bloquearse al guardar proyectos creados con versiones anteriores de Project.

- Se ha corregido un problema por el que, si Project estaba conectado a Project Web App y el separador decimal era una coma, el método TaskDependencies Add producía un error al agregar retardo.


### <a name="word"></a>Word

- Se ha corregido un problema por el que la inserción de comentarios en un documento en el modo de colaboración no funcionaba en ocasiones.

- Este cambio corrige un problema por el que la tarjeta de contactos parpadeaba si se hacía clic en la mención @.

- Al habilitar la opción "Mostrar marcadores" no se mostrarán los marcadores. Este error se ha corregido.

- Se ha corregido el problema por el que al cerrar un documento con borrador de comentarios se preguntaba al usuario si deseaba cerrar el documento sin guardar los comentarios del borrador. Al cancelar la solicitud, se cerraba el documento en lugar de quedar abierto.

- Se ha corregido un problema al copiar y pegar títulos.

- Se ha corregido un problema por el que al traducir un comentario publicado se producía el error "Error al insertar el texto traducido".

- Este cambio soluciona un problema por el que el texto con hipervínculos podía no aparecer si la opción "Mostrar códigos de campo en lugar de sus valores" estaba activada.

- En la Vista web o en el lector inmersivo, al hacer clic en una sugerencia se desplazaba a la parte superior incluso aunque ya estuviera a la vista. Este error se ha corregido.

- Se ha corregido un problema por el que al intentar guardar un archivo que contenía una macro con un nombre nuevo, este se guardaba con la extensión. docx y el nombre de archivo WRO0004.docx, independientemente de lo que el usuario escribiera, lo que hacía que el archivo no se pudiera volver a usar.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Cuando se asignaba a un usuario una directiva que lo llevaba a Teams solo, aún se podía usar el complemento para Outlook de Skype Empresarial para programar reuniones.  Tras esta actualización, ya no se podrán programar reuniones de Skype Empresarial después de que el cliente lea la directiva en la que se indica que el usuario participa en Teams solo y entra en la reunión como Unirse solo.  Además, el complemento de Outlook para Skype Empresarial no se activará durante el inicio si ve que el cliente de Skype Empresarial se encuentra en modo de Unirse solo.

- Esta actualización corrige un problema en Microsoft Office en el que los proyectos de Visual Basic para aplicaciones con referencias que se espera encontrar buscando las ubicaciones especificadas en la variable de entorno PATH podían no encontrarse correctamente en tiempo de ejecución, lo que provoca errores en tiempo de ejecución de VBA.

- Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2004-may-11"></a>Versión 2004: 11 de mayo
*Versión 2004 (compilación 12730.20270)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos han pasado a ser más elegantes.

### <a name="outlook"></a>Outlook

- **Vínculos mejorados en el correo electrónico:** al incluir un vínculo a un archivo, la dirección URL se reemplaza por el nombre del archivo. Puede cambiar los permisos para que todos los destinatarios tengan acceso. [Más información](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)

- **Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office. Sus documentos han pasado a ser más elegantes.

### <a name="powerpoint"></a>PowerPoint

- **Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos han pasado a ser más elegantes.  [Más información](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a>Word

- **Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos han pasado a ser más elegantes.


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al mostrar las notificaciones del sistema.



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2004-may-04"></a>Versión 2004: 4 de mayo
*Versión 2004 (Compilación 12730.20250)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Mejores resultados, en un instante:** actualizamos la experiencia de búsqueda para que sea más inteligente, rápida y fiable que nunca. [Más información](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **Notificación de incidentes para administradores de TI:** se notificará a los administradores globales de espacios empresariales de Microsoft 365 y a los administradores de aplicaciones de Office acerca de los incidentes de Outlook y Exchange de O365 que afectan a sus usuarios con una nueva notificación en el panel derecho en Outlook para Windows. [Más información](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.



[//]: # (NO QUITAR ERRORES DE DETALLES DE CONTENIDO FINAL)

## <a name="version-2004-april-29"></a>Versión 2004: 29 de abril
*Versión 2004 (compilación 12730.20236)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Protección de datos del grupo:** la etiqueta de confidencialidad que elija al crear un grupo se aplica al correo electrónico del grupo, a los documentos y a los sitios de equipo.


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Corrige un problema que causaba que Outlook se bloqueara en algunas compilaciones de Windows.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2004-april-25"></a>Versión 2004: 25 de abril
*Versión 2004 (compilación 12730.20206)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que Outlook se bloqueara al abrir archivos .msg y .oft guardados localmente después de una actualización de Windows.

### <a name="project"></a>Project

- Se ha corregido un problema que hace que si está usando Project conectado a Project Web App y el separador decimal es una coma, el método TaskDependencies Add producirá un error al intentar agregar retardo a una dependencia.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Esta corrección resuelve un error que impide restringir el acceso y proteger los archivos con una contraseña de forma simultánea.



[//]: # (NO ELIMINAR LOS DETALLES DEL CONTENIDO FINAL)

## <a name="version-2004-april-21"></a>Versión 2004: 21 de abril
*Versión 2004 (compilación 12730.20182)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Corrige un problema que provocaba que el ancho del panel de carpetas cambiara de forma inesperada.

- Corrige un problema que provocaba que los usuarios experimentaran un error al salir de Outlook.


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2004-april-15"></a>Versión 2004: 15 de abril
*Versión 2004 (compilación 12730.20150)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **El soporte para el conector de Facebook va a terminar:** a partir de abril de 2020. Excel ya no admitirá conexiones de datos externos que usen el conector de Facebook.

### <a name="outlook"></a>Outlook

- **Nueva opción para desactivar las sugerencias de @menciones al escribir correo en Outlook: **¿le resulta el selector de @menciones más molesto que útil? Ahora puede desactivarlo si lo prefiere.

### <a name="powerpoint"></a>PowerPoint

- **Sincronice los cambios mientras realiza la presentación:** sincronice los cambios cuando se hagan aunque la presentación esté en el modo de presentación con diapositivas.

### <a name="word"></a>Word

- **Anote su copia privada:** cree notas escritas a mano privadas realizando una copia privada de un documento compartido. Vaya a Ver > Crear una copia privada para empezar.


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Se han corregido problema al cambiar el tamaño y actualizar tablas en el panel de tareas.

- Se ha corregido un problema por el que las versiones internacionales de Access mostraban cadenas en inglés en la interfaz de usuario.

### <a name="excel"></a>Excel

- Se ha corregido un problema por el que seleccionar un rango de celdas en una hoja daba lugar a la selección de una sola celda.

- En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.

- Se ha corregido un problema que hacía que Excel se bloqueara en ciertos casos después de copiar una hoja que contenía una tabla dinámica.

- Application.Evaluate (VBA) no funcionaba para funciones definidas por el usuario en algunos casos.

- Se ha corregido un problema de rendimiento que los usuarios pueden haber experimentado al editar un rango de celdas grande por programación.

- Se ha corregido un problema de rendimiento al abrir archivos CSV con entornos japoneses.

- Se ha corregido un problema que provocaba que al insertar una plantilla de gráfico definida por el usuario como predeterminada se guardara como un gráfico de columnas.

- Se ha corregido un problema por el que las etiquetas de datos en los gráficos se mostraban en blanco cuando las celdas de datos subyacentes no tuvieran un título.

- Se ha corregido un problema que podía provocar que Excel dejara de responder al reducir el tamaño de un gráfico con algunos rangos de eje x.

- Se ha corregido un problema por el que, en una hoja de Excel con referencia de celda F1C1 habilitada y en coautoría o compartida, al pasar el ratón por el icono de presencia del usuario no se mostraba la referencia de celda activa en modo F1C1.

- Este cambio corrige retrasos al procesar imágenes con información de protocolo mal formada o incorrecta.

### <a name="outlook"></a>Outlook

- Este cambio corrige retrasos al procesar imágenes con información de protocolo mal formada o incorrecta.

- Este cambio corrige un problema por el que los cambios más recientes en los borradores de correo electrónico no se actualizaban.

- Se corrigió un problema por el que hacer clic derecho del mouse en un archivo y usar "Enviar a" no funcionaba.

- Se ha corregido un problema que provocaba que los delegados viesen distintas jerarquías de carpetas en diferentes equipos para los buzones compartidos.

- Se ha corregido un problema que provocaba que las categorías desapareciesen en ocasiones de los mensajes de correo electrónico.

- Se ha corregido un problema que provocaba que se produjesen errores en la activación de algunos avisos al cambiar la zona horaria en un equipo.

- Se ha corregido un problema que provocaba que los usuarios experimentasen un error al intentar ver las propiedades de un formulario de la organización.

- Se corrigió un problema por el que si un usuario tenía una ruta de búsqueda personalizada para la libreta de direcciones, el ámbito de la resolución de nombres de Outlook se limitaba a la ruta personalizada, en lugar de incluir la lista global de direcciones (LGD).

- Se ha corregido un problema que hacía que el botón "Guardar en la nube" faltara en las Herramientas de datos adjuntos.

- Se ha corregido un problema que hacía que los usuarios no pudieran agregar una firma al responder a un mensaje administrado con derechos digitales desde una ventana de inspección cuando el usuario no tenía permiso de propietario sobre el mensaje al que se respondía.

- Se ha corregido un problema que hacía que los usuarios no pudieran agregar archivos adjuntos adicionales desde una ubicación web a una reunión creada previamente.

- Se ha corregido un problema que hacía que la fecha de "última modificación" de un archivo se actualizara al agregar un archivo adjunto a un correo electrónico o al guardar un archivo adjunto desde un correo arrastrándolo y colocándolo (en lugar de hacerlo a través de un menú).

- Se ha corregido un problema que hacía que al presionar Entrar en el panel de búsqueda expandido no se iniciara la búsqueda y requería que los usuarios hiciesen clic en el botón de búsqueda.

- Se ha corregido un problema que hacía que al ordenar los resultados por categorías, en un conjunto de resultados de búsqueda devuelto no se mostraran los colores de la categoría.

- Se ha corregido un problema por el que la búsqueda no mostraba información sobre los usuarios cuando se había deshabilitado la opción "Mostrar fotografías de usuario cuando estén disponibles".


### <a name="powerpoint"></a>PowerPoint

- Este cambio corrige un error que podría causar que los archivos de PowerPoint que contienen emojis fallen al guardarlos.

- Este cambio corrige un problema en el que es posible que no siempre se muestre el título del gráfico al representar un gráfico de Excel heredado incrustado como objeto OLE en PowerPoint o Word.

- Se ha corregido un problema por el que al copiar texto de Excel en PowerPoint podía cambiar el formato.

- Este cambio corrige un problema que provocaba que la búsqueda de caracteres especiales con "Buscar solo palabras completas" no siempre funcionase como se esperaba.

### <a name="project"></a>Proyecto

- Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.

- Corregido un problema en el que el evento OnUndoOrRedo no se desencadena sin ejecutar primero el método OpenUndoTransaction.

- Se ha corregido un problema que hacía que el evento "ProjectBeforeTaskChange" de las aplicaciones de Visual Basic (VBA) no se activara cuando un usuario hacía clic en el botón "Desactivar" que se encuentra en la cinta de tareas en el grupo de programación.

- Si establece los detalles de predecesor o sucesor desde una vista de tipo formulario, el evento de las aplicaciones de Visual Basic (VBA) ProjectBeforeTaskChange no siempre captura los cambios. Por ejemplo, si ha eliminado una dependencia y ha hecho clic en Aceptar en el formulario, el evento no se ha desencadenado. Este comportamiento se ha corregido.

- Se corrigió un problema por el que los valores más recientes del coste real del trabajo realizado (CRTR) no se mostraba después de realizar un cambio, como un cambio de fecha.

- Se corrigió un problema por el que al abrir un proyecto con el menú Usados más recientemente se abría el archivo de proyecto con acceso de lectura y escritura.

- Este cambio corrige un problema por el que si creaba una tarea manual con una fecha y hora de inicio (sin la duración), se mostraba con una hora incorrecta en la escala de tiempo.

- Se corrigió un problema por el que la impresión de una escala de tiempo con el calendario Hijri saltaba un mes o lo duplicaba en la vista de impresión.

- Este cambio resuelve un problema por el que trabajar en el Organizador de equipo con objetos de GDI podía provocar la sobreasignación de dichos objetos y crear condiciones de memoria insuficiente.

- Se ha solucionado un problema por el que si se ejecuta "Lista de valores de campos personalizados GetItem" y no existe una tabla de búsqueda para el campo personalizado, se crea una tabla de búsqueda vacía aunque no debería existir.

- Cuando se editan los datos del Predecesor/Sucesor dentro de una vista de formulario, se activa un evento ProjectBeforeTaskChange adicional.

- Se corrigió un problema por el que el usuario no podía especificar el trabajo previsto con fases temporales al activar la configuración para proteger el trabajo real.

### <a name="word"></a>Word

- Este cambio corrige un problema que provoca que al colocar el cursor sobre una sugerencia no se resalte la tarjeta.

- Este cambio corrige un problema con varias páginas seleccionadas en el menú Ver, donde el panel de comentarios podía mostrarse en blanco.

- Se corrigió un problema por el que se había deshabilitado la función para publicar comentarios.

- Este cambio corrige un problema que haría que el texto de las formas agrupadas desaparezca temporalmente al usar la herramienta Selección de lazo.

- Este cambio corrige retrasos al procesar imágenes con información de protocolo mal formada o incorrecta.

- Este cambio corrige un problema en el que es posible que no siempre se muestre el título del gráfico al representar un gráfico de Excel heredado incrustado como objeto OLE en PowerPoint o Word.

- Este cambio resuelve un problema en el que el administrador de cuentas no enviaba mensajes, lo que provocaba un error en aplicaciones de terceros.

- Este cambio corrige un problema por el que, en la vista de dos páginas, al crear un comentario, el anclaje del comentario no siempre aparecía.

- Se ha corregido un problema por el que al escribir o editar un comentario y usar Ctrl + A se seleccionaba texto en el lienzo en lugar de seleccionar texto en la tarjeta del comentario.

- Se ha corregido un problema que hacía que si un párrafo con un estilo antecesor de un estilo estaba vinculado a una lista, se podía perder la numeración de la lista.

- Este cambio corrige un problema en el que la tabla de contenido se actualizaba con estilos de título que no estaban presentes en el documento.

- Se ha corregido un problema por el que la alineación de las palabras de un documento se puede codificar al intentar editar después de imprimir con la impresión rápida.

- Se ha corregido un problema al combinar dos documentos en uno.

- Se corrigió un problema por el que las firmas digitales guardadas en documentos de Word se eliminaban al enviar los documentos.

- Se ha corregido un problema que hacía que el marcado de revisiones que impliquen ecuaciones ocasionase un error al guardar el archivo.


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2003-april-14"></a>Versión 2003: 14 de abril
*Versión 2003 (compilación 12624.20466)*

Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

- Varias correcciones de errores y rendimiento.


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

## <a name="version-2003-april-09"></a>Versión 2003: 09 de abril
*Versión 2003 (compilación 12624.20442)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Selector de contenido de M365 Premium:** de vida a sus documentos. Explore gratis miles de imágenes, iconos y adhesivos [Más información](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

### <a name="outlook"></a>Outlook

- **Selector de contenido de M365 Premium:** de vida a sus documentos. Explore gratis miles de imágenes, iconos y adhesivos [Más información](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

### <a name="powerpoint"></a>PowerPoint

- **Selector de contenido de M365 Premium:** de vida a sus documentos. Explore gratis miles de imágenes, iconos y adhesivos [Más información](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

### <a name="word"></a>Word

- **Selector de contenido de M365 Premium:** de vida a sus documentos. Explore gratis miles de imágenes, iconos y adhesivos [Más información](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO INICIAL)




[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO FINAL)

## <a name="version-2003-april-03"></a>Versión 2003: 03 de abril
*Versión 2003 (Compilación 12624.20410)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- El uso de la Aplicación VBA.Evaluar no trabajaba para las funciones definidas por el usuario en algunos casos.

### <a name="outlook"></a>Outlook

- Abordó un problema que causó que los usuarios experimentaran ocasionalmente un choque al usar el botón "X" de su ratón.

### <a name="project"></a>Project

- Cuando se editan los datos del Predecesor/Sucesor dentro de una vista de formulario, se dispara un ProyectoAntesdeCambiarTareaEvento extra.

### <a name="word"></a>Word

- Abordó un problema que causó que los usuarios experimentaran ocasionalmente un choque al usar el botón "X" de su ratón.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2003-march-31"></a>Versión 2003: 31 de marzo
*Versión 2003 (compilación 12624.20382)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="access"></a>Access

- **Panel de tareas "Agregar tablas":** ¡Ya está disponible el acceso al nuevo panel de tareas "Agregar tablas"! Esta característica le permite seleccionar y hacer selección múltiple de las tablas que desea agregar o quitar de forma sencilla en una ventana de consulta, sin tener que desplazarse hasta el cuadro de diálogo "Mostrar tablas" para las consultas y la vista de relación. Esto también incluye una nueva pestaña "vínculos" para mostrar las tablas vinculadas, un cuadro de búsqueda para filtrar la lista actual, el comportamiento de "arrastrar y soltar", ¡y mucho más!


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="project"></a>Project

- <span style="display:inline !important;">Se corrigió un problema por el que el usuario no podía especificar el trabajo previsto con fases temporales al activar la configuración para proteger el trabajo real.</span><br>



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2003-march-25"></a>Versión 2003: 25 de marzo
*Versión 2003 (compilación 12624.20320)*

- Varias correcciones de errores y rendimiento.

## <a name="version-2003-march-23"></a>Versión 2003: 23 de marzo
*Versión 2003 (compilación 12624.20296)*

- Varias correcciones de errores y rendimiento.

## <a name="version-2003-march-21"></a>Versión 2003: 21 de marzo
*Versión 2003 (compilación 12624.20276)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Unirse a reuniones sin salir de la bandeja de entrada:** no es necesario cambiar al calendario para unirse a reuniones en línea. Con el Calendario de Outlook anclado en el panel de tareas pendientes, únase a una reunión con un solo clic.

- **Actualización visual del calendario:** el año pasado, hemos incorporado una experiencia de correo actualizada y este año le toca al calendario tener una cara nueva. Las actualizaciones son recientes pero son familiares, para que, como usuario de Outlook veterano, pueda empezar a ser más productivo en seguida.

### <a name="powerpoint"></a>PowerPoint

- **Actualización de las diapositivas durante la presentación:** actualice diapositivas editadas por otros autores durante la presentación.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

## <a name="version-2003-march-16"></a>Versión 2003: 16 de marzo
*Versión 2003 (compilación 12624,20224)*


[//]: # (NO QUITAR DETALLES DE CARACTERÍSTICAS CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.

### <a name="outlook"></a>Outlook

- **Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.

### <a name="powerpoint"></a>PowerPoint

- **Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.

### <a name="word"></a>Word

- **Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- **Paneles con pestañas:** ahora puede cambiar entre varios paneles con la pestaña situada en la parte derecha de la aplicación. Esta interfaz de usuario solo será visible cuando haya dos o más paneles abiertos.


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se abordó un problema donde los enlaces externos no se actualizan cuando se cierra el libro de fuentes.

### <a name="outlook"></a>Outlook

- Se abordó un problema que causó que los usuarios vieran que el proceso de Outlook permanecía en el administrador de tareas después de salir.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2003-march-10"></a>Versión 2003: 10 de marzo
*Versión 2003 (compilación 12624.20176)*

Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)
### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel
- **Etiquetas de confidencialidad**: ahora puede aplicar una etiqueta de confidencialidad que la organización ha configurado para pedirle permisos personalizados. [Más información](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a>PowerPoint
- **Etiquetas de confidencialidad**: ahora puede aplicar una etiqueta de confidencialidad que la organización ha configurado para pedirle permisos personalizados. [Más información](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a>Word
- **Etiquetas de confidencialidad**: ahora puede aplicar una etiqueta de confidencialidad que la organización ha configurado para pedirle permisos personalizados. [Más información](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)
</br>

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema estético en el que el botón "Aceptar" del cuadro de diálogo de Archivo \ Opciones se mostraba atenuado, pero la función no se veía afectada.

- Se ha corregido un problema que los usuarios pueden haber experimentado al cambiar el nombre de las medidas de tabla dinámica.

- Se ha corregido un problema en el que el texto de una segmentación de datos no se escalaba correctamente en la vista previa de impresión.

- Se ha corregido un problema de rendimiento que los usuarios pueden haber experimentado al usar una macro de VBA para borrar el contenido de un rango.

- Se ha corregido un problema que provocaba que la interfaz de usuario parpadeara cuando un usuario ejecutaba una macro que interactuaba con la cinta de opciones.

- Se ha corregido un problema por el que los archivos CSV se cargaban de forma incorrecta cuando la primera palabra del archivo estaba era TABLE.

- Se ha corregido un problema por el que los usuarios pueden haber sufrido bloqueos al cambiar entre dos libros que tienen diferentes niveles de zoom.

- Se ha solucionado un problema por el que las funciones CUBEVALUE a veces daban un resultado incorrecto.

- Este cambio resuelve un error en tiempo de ejecución en el modelo de objetos y el potencial bloqueo de la aplicación (Excel o Word) cuando los complementos pedían elementos host en documentos y hojas de cálculo que contienen formas con bloqueos noSelect.

- Corrige un problema que causaba que los usuarios de Outlook experimentaran un error al sincronizar la configuración.



### <a name="outlook"></a>Outlook

- Se ha corregido un problema que hacía que la creación de una regla con Outlook Web Access no se almacenara en el servidor de Exchange y produjera un conflicto.

- Corregido un problema que causaba que los usuarios de Outlook experimentaran un error al sincronizar la configuración.

- Se ha corregido un problema por el que, en el modo oscuro de Outlook, no se mostraba la lista desplegable en el campo "De:".

- Se ha corregido un problema que hizo que Outlook generara inesperadamente resultados de registro en algunas situaciones, incluso cuando el registro se desactivaba.

- Se ha corregido un problema que provocaba que los usuarios no puedan abrir mensajes de la carpeta pública cuando Outlook se dejaba en marcha durante la noche.

- Se ha corregido una condición en la que los botones "Permitir" y "Denegar" de la página de permisos se deshabilitan durante el flujo de trabajo de autenticación para agregar una cuenta de Gmail.

- Se ha corregido un problema que provocaba que los usuarios perdieran el acceso al cuadro de diálogo de permisos de calendario &quot;Opciones de disponibilidad&quot;.

- Se ha corregido un problema que podría provocar alerta: &quot;"Lo sentimos, tenemos problemas para abrir este elemento"&quot; al abrir algunas instancias de reuniones periódicas que se han enviado desde una zona horaria diferente.

- Se ha corregido un problema que podría ocasionar que los usuarios no puedan abrir un archivo .msg después de arrastrar y soltar datos adjuntos desde el mensaje.

- Se ha corregido un problema por el que, después de cargar un archivo adjunto desde Outlook a OneDrive, se podía cambiar el nombre de archivo si el nombre de los datos adjuntos contenía paréntesis.

- Corregido un problema por el que los usuarios no pueden adjuntar un archivo a un mensaje de correo electrónico a través del explorador de archivos cuando el archivo se abre en otra aplicación.

- Corregido un problema que causaba que los usuarios de Outlook experimentaran un error al sincronizar la configuración.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema por el que las miniaturas recomendadas parpadean al pasar el ratón por encima de las miniaturas. En algunos casos, esto provocaba un bloqueo de PowerPoint.

- Se ha corregido un problema estético en el que el botón "Aceptar" del cuadro de diálogo de Archivo \ Opciones se mostraba atenuado, pero la función no se veía afectada.

- Se ha corregido un problema que podría provocar un error al guardar un documento en PowerPoint o en Word con un gráfico de Excel.



### <a name="project"></a>Project

- Corregido un problema por el que el porcentaje completado de la tarea se cambiaba incorrectamente a un valor inferior al 100 % después de que se marcara como completada.

- Corregido un problema en el que el evento OnUndoOrRedo no se desencadena sin ejecutar primero el método OpenUndoTransaction.

- Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.

### <a name="visio"></a>Visio

- El panel información de la forma mostraba en la sección Datos de formas detalles que no coincidían con los del archivo al abrirlo en la aplicación de escritorio de Visio. Ya se ha corregido.

- Los mapas de bits importados en versiones anteriores a 2016 no se representaban por motivos de seguridad. Este problema se ha corregido en la suscripción de Visio.

### <a name="word"></a>Word

- Se ha corregido un problema en el que las tarjetas con comentario no siempre se resaltan cuando se desplaza el puntero del mouse sobre la tarjeta del comentario.

- Se ha corregido un problema por el que al ir a la tarjeta del comentario, el foco en el cuadro de edición del comentario no era visible.

- Se ha corregido un problema estético en el que el botón "Aceptar" del cuadro de diálogo de Archivo \ Opciones se mostraba atenuado, pero la función no se veía afectada.

- Durante una sesión de coautoría de documentos activos, agregar una imagen directamente en una tarjeta de comentario puede dar como resultado la adición de una etiqueta. Este problema se ha corregido.

- Si se inserta un control (como un control de contenido de texto) en una ecuación, al guardar y abrir el archivo se produce un error de contenido ilegible.

- Se ha corregido un problema que hacía que no se pudiera guardar un archivo protegido con contraseña anteriormente en un almacenamiento en la nube.

- Se ha corregido un problema con la característica Comparación para los documentos protegidos para la edición.




### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Al usar las propiedades Multichoice/Lookup/Managed-metadata con documentos de Word/Excel/PowerPoint y guardar en una biblioteca de documentos de SharePoint, estas propiedades se limitaban anteriormente a 255 caracteres. Cuando estas propiedades superaban 255 caracteres, estos documentos no se podían guardar. Con este cambio, este límite se ha aumentado a 2048 caracteres.

- Se ha corregido un problema en Word/Excel/PowerPoint. Ahora, el nombre principal de usuario (UPN) ya no distingue entre mayúsculas y minúsculas, lo que provoca menos errores al trabajar con archivos en SharePoint.

- Corregido un problema por el que cuando hay varios documentos abiertos en Word/Excel/PowerPoint de la misma biblioteca de SharePoint, solo se analizará el primer documento abierto para el cumplimiento de las directivas.


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-march-05"></a>Versión 2002: 05 de marzo
*Versión 2002 (compilación 12527.20278)*

- Varias correcciones de errores y rendimiento.


## <a name="version-2002-march-04"></a>Versión 2002: 04 de marzo
*Versión 2002 (compilación 12527.20264)*


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos

### <a name="project"></a>Project
- Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office
- Corrige un problema por el que cuando hay varios documentos abiertos en Word/Excel/PowerPoint de la misma biblioteca de SharePoint, solo se analizará el primer documento abierto para el cumplimiento de las directivas.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-march-01"></a>Versión 2002: 01 de marzo
*Versión 2002 (compilación 12527.20242)*

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Corrige un problema que provocaba que las aplicaciones de terceros no pudiesen enviar correo electrónico.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-february-24"></a>Versión de 2002: 24 de febrero
*Versión de 2002 (compilación 12527.20194)*

- Varias correcciones de errores y rendimiento.

## <a name="version-2002-february-22"></a>Versión de 2002: 22 de febrero
*Versión de 2002 (compilación 12527.20186)*

- Varias correcciones de errores y rendimiento.

## <a name="version-2002-february-21"></a>Versión 2002: 21 de febrero
*Versión 2002 (compilación 12527.20174)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="access"></a>Access

- **Aumente su productividad con el Diseñador de consultas, la vista SQL y la ventana Relaciones:** haga clic con el botón derecho en una tabla para abrirla, diseñarla, cambiar su tamaño y ocultarla. Buscar y reemplazar texto en la vista SQL. Seleccione múltiples tablas en la ventana Relaciones.

### <a name="outlook"></a>Outlook

- **Nueva experiencia para redes WiFi cautivas:** ¿alguna vez se ha unido a una red WiFi que requiere una página web para iniciar sesión? Outlook ahora lo detecta y le ayuda a estar conectado.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- <div style="box-sizing:border-box;">Se ha corregido un problema por el que las funciones CUBEVALUE a veces daban un resultado incorrecto.&nbsp;<span style="display:inline !important;"></span><br>


### <a name="outlook"></a>Outlook

- Corregido un tema que causó que las comas en el campo de ubicación de una reunión se convirtieran en punto y coma.


- Corregido un problema que podría resultar en un choque al ver el mismo elemento en varias ventanas.


- Corregido un problema que causó que Outlook sincronizara inesperadamente todo el correo, incluso cuando el deslizador de sincronización está configurado en un ajuste más pequeño.&nbsp;


- Corregido un problema que causó que los usuarios con el Tema Negro vieran&quot;de&quot; el desplegable muestra un texto blanco sobre un fondo blanco.


- <span style="display:inline !important;">Este cambio restaura la capacidad de ver sujetos de varias líneas en el encabezado del mensaje.</span><br>



[//]: # (NO ELIMINE EL CONTENIDO FINAL DE LOS DETALLES )

## <a name="version-2002-february-18"></a>Versión 2002: 18 de febrero
*Versión 2002 (compilación 12527.20138)*

## <a name="version-2002-february-11"></a>Versión 2002: 11 de febrero
*Versión 2002 (compilación 12527.20092)*

Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Arrastre el correo electrónico a un grupo de tu propiedad:** Mueva y copie mensajes y conversaciones arrastrándolos desde su bandeja de entrada. Los mensajes que arrastres serán compartidos con todos los miembros del grupo.

### <a name="word"></a>Word

- **Otros usuarios verán los cambios rápidamente**: las mejoras en la coautoría significan que los colaboradores podrán ver los cambios más rápido que nunca.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- **Iconos de la barra de estado más nítidos:** los iconos de la barra de estado ahora son más fáciles de ver.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Las plantillas de Access ya no deberían causar errores en columnas de datos adjuntos en una base de datos. Después de crear la instancia de una plantilla, ahora debería poder agregar un campo de datos adjuntos a la base de datos.

- Esta actualización corrige un problema por el que al usar un objeto de grabación de ADODB en el código de VB, se puede notificar un error incorrectamente.

- Esta actualización corrige un problema que puede hacer que Microsoft Access no identifique una Columna de identidad en una tabla vinculada de SQL Server, lo que puede provocar que las filas aparezcan como eliminadas de forma incorrecta.


### <a name="excel"></a>Excel

- Se ha corregido un problema por el que los comandos de comentario en el menú contextual no aparecían.


- Se ha corregido un problema que causaba que algunos usuarios experimentasen bloqueos al convertir texto en columnas con celdas que tienen una matriz derramada.


- Se ha corregido un problema por el que Excel se bloquea al usar la opción Texto a columnas con matrices dinámicas.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema en el que el desplazamiento en el calendario con la vista de mes no muestra eventos de calendario anteriores.

- Las carpetas guardadas en "favoritos" en el panel de navegación izquierdo podían desaparecer de forma esporádica.


- Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.


- Se ha corregido un problema que hacía que la opción deshabilitar el resaltado de elementos marcados no se pudiera respetar en algunos escenarios.

- Se ha corregido un problema que provocaba que los usuarios experimentaran un error al cancelar la configuración de la cuenta.


- Se ha corregido un problema por el que los mensajes de correo electrónico que expiraban en función de una directiva de retención mostraban dos etiquetas. Una mostraba que el correo expiraba en un día y otra que expiraba en dos días.


- Se ha corregido un problema que causaba que los usuarios sufrieran un error al visualizar más de 30 calendarios en un entorno Citrix.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema por el que la entrada de lápiz no se procesaba por completo u se omitía al usarla en una animación de entrada de lápiz de PowerPoint.

- Se ha corregido un problema que provocaba que, después de cerrar un archivo, PowerPoint no lo quitara inmediatamente de la colección Presentaciones si había algún controlador de eventos en ejecución. Por lo tanto, el número de presentaciones que informa el modelo de objetos es incorrecto y se evita el cierre de PowerPoint.


- Se ha corregido un problema con el marcador de resaltado: los textos blancos con un marcador oscuro se imprimen como negros en escala de grises.


### <a name="project"></a>Project

- Se ha corregido un problema por el que el 100 % de las tareas de tipo duración fija podían tener un cálculo del porcentaje incorrecto con menos del 100% completado.


### <a name="word"></a>Word

- Al actualizar y desplazarse por una tabla de contenido, es posible que se muestre un área gris en el documento.


- Se ha corregido un problema por el que usar "Examinar" para guardar un archivo podía no funcionar si se escribió un comentario sin publicarlo y el usuario intentó guardar el archivo.


- Se ha corregido un problema por el que al ir de una tarjeta de comentario a otra se podía mostrar el comentario seleccionado inicialmente con una selección resaltada.


- Se ha corregido un problema por el que el formato de cursiva se perdía después de editar un comentario, ponerlo en cursiva y, después, publicarlo.


- Se ha corregido un problema por el que la sugerencia de comentario no se veía en el modo lectura con el color de página invertido.


- Se ha corregido un problema por el que si se trabajaba en coautoría en un documento, la versión de borrador de un comentario raíz podía no conservarse.


- Con el Control de cambios habilitado y el panel de comentarios cerrado, Ctrl + Alt + M podía no funcionar para abrir el panel Comentarios.


- Corregido un problema al agregar una @mención en una tabla que podía generar el mensaje de error: "Una tabla de este documento está dañada".


- Se ha corregido un problema por el que los comandos de comentario (Modificar comentario, Responder a comentario, Eliminar comentario, Resolver comentario) en el menú contextual de comentarios no se mostraban.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Resuelto un problema que podía causar que el paquete de herramientas de corrección de Noruega Nynorsk (NN-no) no se instalara correctamente.


- Este cambio resuelve problemas con adaptadores gráficos que aprovechan la GPU integrada de Intel.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)
