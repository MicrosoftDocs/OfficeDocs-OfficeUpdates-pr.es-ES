---
title: Notas de la versión canal actual (versión preliminar)
ms.author: anankani
author: v-lislo
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 'Proporciona a los participantes del modo anticipado de Insider Lento la lista más reciente de las nuevas características, correcciones o problemas conocidos principales '
ms.openlocfilehash: 6a81894e1eca51356512bbd7181c3d7fa9f73760
ms.sourcegitcommit: 1f8cb906d8d0af5eb26eaedf008180375d2fd55d
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/09/2020
ms.locfileid: "44668121"
---
# <a name="release-notes-for-office-current-channel-preview"></a>Notas de la versión para el canal actual de Office (versión preliminar)

Este artículo contiene las notas de la versión para las versiones de canal actual (versión preliminar) de Word, Excel, PowerPoint, Outlook, Access y Project para el escritorio de Windows. Todas las semanas se incluyen las nuevas características, correcciones importantes y los problemas principales de mayor interés para usted. Tenga en cuenta que, a menudo, implementamos características (y a veces incluso soluciones) en el canal actual (versión preliminar) durante un período de tiempo. Esto nos permite asegurarnos de que todo funciona correctamente antes de publicar la característica para un público más amplio. Por tanto, si a continuación no ve algo descrito, no se preocupe, lo recibirá con el tiempo.  

> [!IMPORTANT]
> Estamos realizando algunos cambios en los canales de actualización de las Aplicaciones de Microsoft 365, incluida la adición de un nuevo canal de actualización (canal empresarial mensual) y el cambio de los nombres de los canales de actualización existentes. [Lea este artículo](https://go.microsoft.com/fwlink/p/?linkid=2127441) para obtener más información.

> [!NOTE]
> - La fecha de publicación de las notas de versión pueden no coincidir con la fecha real de lanzamiento de la compilación.


[//]: # (NO ELIMINAR)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

## <a name="version-2005-june-08"></a>Versión 2005:8 de junio
*Versión 2005 (compilación 12827,20336)*

[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema relacionado con el cuadro de diálogo reemplazar fuentes, donde la lista desplegable reemplazar fuente sólo muestra las fuentes dentro de la presentación en lugar de las fuentes instaladas en el sistema.



[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-2005-june-04"></a>Versión 2005:4 de junio
*Versión 2005 (compilación 12827,20320)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="access"></a>Access

- **Manténgase al día con las horas. El tipo de datos extendidos de fecha y hora tiene mejor precisión.:** introducción de un tipo de datos nuevo y mejorado.  Para mejorar la compatibilidad de la sintaxis con SQL y aumentar la precisión y el nivel de detalle en los registros que incluyen fechas y horas, estamos implementando el tipo de datos DateTime2 en Access. Este tipo de datos de fecha & hora adicionales incluirá un intervalo de fechas mayor (de 0001-01-01 a 9999-12-31), con precisión de tiempo mayor (nanosegundos, en lugar de segundos) que podrá proporcionar y realizar cálculos en. Para habilitarla, seleccione nuevo campo > fecha & tiempo ampliado. [Más información](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a>Excel

- **Cree tablas dinámicas de conjuntos de elementos en Power BI en Excel:** Puede crear tablas dinámicas en Excel que estén conectadas a los conjuntos de valores almacenados en Power BI con unos pocos clics.Esto le permite sacar el máximo partido de las tablas dinámicas y de Power BI. Calcule, resume y analice los datos con tablas dinámicas de los datasets de Power BI protegidos.

### <a name="outlook"></a>Outlook

- **Opción para volver a abrir rápidamente los elementos de la sesión anterior de Outlook:** Se ha agregado una opción para volver a abrir rápidamente los elementos de una sesión anterior de Outlook.


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="powerpoint"></a>PowerPoint

- Esto soluciona un bloqueo cuando los usuarios tienen comentarios modernos y heredados en un archivo, lo que desencadena una actualización en los comentarios.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha resuelto el problema de tasa de error de ValidateInstall estableciendo la validación de la instalación del complemento de Bing en true de forma predeterminada y considerando que MSI Return Success como una instalación correcta.



[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-2005-may-29"></a>Versión 2005:29 de mayo
*Versión 2005 (compilación 12827,20268)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características

### <a name="excel"></a>Excel

- **Vista de hoja:** Ordenar o filtrar mientras colaboran con otras personas en el escritorio de Excel.

### <a name="outlook"></a>Outlook

- **Botones adicionales agregados a las notificaciones del sistema de Outlook:** Ahora aparecen botones de acción rápidos en las notificaciones del sistema de Outlook al ejecutar Outlook en Windows 10.


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos



### <a name="outlook"></a>Outlook

- Se ha solucionado un problema que provocaba que los usuarios de versiones de Windows 10 Server consultaran la advertencia Estado de antivirus: no válido. Esta versión de Windows es compatible con la detección antivirus, pero no se ha encontrado ningún antivirus a pesar de haber instalado correctamente anti-virus.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- El host de Office se bloqueaba en Windows, cuando se activa un complemento mientras la clave del registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth se establece en cero. Este cambio solucionará este problema.


[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-2005-may-21"></a>Versión 2005:21 de mayo
*Versión 2005 (compilación 12827,20210)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Obtener datos de la organización de Power BI con tipos de datos de Excel:** Puede insertar datos de la organización con los tipos de datos de Excel. Convierta una celda en el libro y obtenga información adicional y actualice los datos en cualquier momento que necesite.


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema por el que Excel podía no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía a través de Teams.


- En algunos casos, al hacer clic en un hipervínculo en un lugar dentro del mismo libro hará que se oculte el libro.


### <a name="outlook"></a>Outlook

- Se ha solucionado un problema con el evento de auditoría CLP para la etiqueta de respuesta/reenvío.


- Se ha solucionado un problema que provocaba que los usuarios experimentaran un bloqueo al enviar comentarios desde una notificación de administrador.



[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-2005-may-14"></a>Versión 2005:14 de mayo
*Versión 2005 (compilación 12827,20160)*

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

- Se ha corregido un problema que provocaba que la inserción de una columna en una lista filtrada tardara más de lo esperado.

- Corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.

- Se ha corregido un problema por el que el vínculo externo dejaba de funcionar después de volver a abrir el archivo si la ruta de acceso del archivo es demasiado larga.

- En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.

- Application.Evaluate (VBA) no funcionaba para funciones definidas por el usuario en algunos casos.

- En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.

- Este cambio corrige un problema que hacía que la información de formato condicional (CF) no se guardase correctamente en los archivos XLSB.

- Este cambio corrige un problema en el que el valor de la línea de tendencia del gráfico R-cuadrado (en el caso de la intersección forzada y) era incorrecto aunque la función de ESTIMACIÓN devuelva el valor correcto.

- Este cambio arregla un problema en el que no siempre se guardaba el formato de la línea de tendencia de los gráficos personalizados.

- Puede producirse un bloqueo al intentar enumerar los cambios en una hoja nueva para un libro mediante el modo heredado "libro compartido".

- Se ha corregido el problema por el que el formato personalizado de un gráfico dinámico podía no guardarse si estaba habilitada la opción "Invertir si es negativo".

- Se ha corregido un problema por el que el formato personalizado de un único punto de datos de un gráfico dinámico no se guardaba si estaba seleccionada la opción "invertir si es negativo".

- Este cambio corrige un problema por el que el carácter "@" cargado en un archivo CSV causaba que la cadena tras el carácter "@" se convirtiera en una fórmula.

- Se ha corregido un problema por el que los valores decimales de la función SECUENCIA no se redondeaban correctamente.

### <a name="onenote"></a>OneNote

- Corregido un problema en el que los saltos de línea se almacenaban como pestañas verticales.

### <a name="outlook"></a>Outlook

- Soluciona un problema que hacía que los usuarios no pudieran agregar un grupo de contactos personal como asistente de la reunión.

- Se ha corregido un problema por el que se deshabilitó el botón clasificar para calendarios de grupo en la cinta de Office.

- Se ha corregido un problema que provocaba que Outlook se bloqueara al abrir archivos .msg y .oft guardados localmente después de una actualización de Windows.

- Se ha solucionado un problema por el que los clientes de las empresas con carpetas de grupo no implementadas o que no funcionaban, hacían que Outlook mostrara un mensaje de "no responde".

- Se ha solucionado un problema que provocaba un safelinks muy largo en el que los usuarios hacían clic en el cliente de escritorio de Outlook para que no se cargaran debido al truncamiento.

- Se ha corregido un problema por el que las carpetas de Outlook con nombres que contenían caracteres DBCS (conjunto de caracteres de doble byte) desaparecían intermitentemente al sincronizar con el servidor. Esto sucedía si Outlook estaba configurado con una cuenta IMAP y se ejecutaba en un sistema con la configuración regional configurada en japonés.

- Se ha solucionado un problema que provocaba que las reglas de eliminación creadas para buzones de correo que no son el buzón principal del usuario dejara de ser válidas.

- Se ha solucionado un problema que provocaba la pérdida de datos adjuntos al reenviar un mensaje cifrado.

- Se ha solucionado un problema que provocaba que las reuniones de más de 2 meses no mostraran un asunto de la reunión en el Asistente para programación.

- Se ha corregido un problema que hacía que los usuarios vieran truncado el cuerpo del mensaje al reenviar mensajes HTML grandes.

- Se agregó la capacidad de aplicar la configuración de firma predeterminada de S/MIME a través de la directiva de grupo.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema por el que el borrador de los comentarios dejaba de estar disponible si un usuario creaba un comentario sin publicarlo, cerraba el panel de comentarios, abría una nueva ventana, se desplazaba por varias diapositivas, cerraba la ventana y volvía a abrir el panel de comentarios en la presentación original.

- Se ha solucionado un problema por el que al pasar el ratón por encima del símbolo del asterisco (*) no aparecía el nombre de usuario y la fecha de la última persona que actualizó el documento.

### <a name="project"></a>Proyecto

- Cuando se editan los datos del Predecesor/Sucesor dentro de una vista de formulario, se activa un evento ProjectBeforeTaskChange adicional.

- Se solucionó un problema por el cual Proyect podía bloquearse al cambiar el campo de estado del tablero en un proyecto que conectado a una lista de tareas de SharePoint.

- Corregido un problema por el que Project podía bloquearse al guardar proyectos creados con versiones anteriores de Project.

- Se ha corregido un problema por el que, si el proyecto está conectado a Project Web App y el separador decimal es una coma, se produce un error en el método Add en TaskDependencies cuando se agrega lag.


### <a name="word"></a>Word

- Se ha corregido un problema por el que la inserción de comentarios en un documento en el modo de colaboración no funcionaba en ocasiones.

- Este cambio corrige un problema por el que la tarjeta de contactos parpadeaba si se hacía clic en la mención @.

- Al habilitar la opción "Mostrar marcadores" no se mostrarán los marcadores. Este error se ha corregido.

- Se ha corregido el problema por el que al cerrar un documento con borrador de comentarios se preguntaba al usuario si deseaba cerrar el documento sin guardar los comentarios del borrador. Al cancelar la solicitud, se cerraba el documento en lugar de quedar abierto.

- Se ha corregido un problema en la copia y pegado de títulos.

- Se ha corregido un problema por el que, al traducir un comentario publicado, se producía un error "no se pudo insertar el texto traducido".

- Este cambio corrige un problema que provocaba que no se mostrara el texto con hipervínculos si se habilitaba la opción: "Mostrar códigos de campo en lugar de sus valores".

- En la Vista web o en el lector inmersivo, al hacer clic en una sugerencia se desplazaba a la parte superior incluso aunque ya estuviera a la vista. Este error se ha corregido.

- Se ha corregido un problema por el que al intentar guardar un archivo que contenía una macro con un nombre nuevo, este se guardaba con la extensión. docx y el nombre de archivo WRO0004.docx, independientemente de lo que el usuario escribiera, lo que hacía que el archivo no se pudiera volver a usar.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Cuando a un usuario se le concede una directiva que los mueve a Microsoft Teams, aún puede usar el complemento de Outlook para Skype empresarial para programar reuniones.  Después de esta actualización, ya no podrá programar reuniones de Skype empresarial después de que el cliente Lea la Directiva, lo que indica que el usuario es solo Microsoft Teams y solo entra en el modo de unirse a la reunión.  Además, el complemento de Outlook para Skype empresarial no se activará durante el inicio si ve que el cliente de Skype empresarial está en modo de solo unirse a la reunión.

- Esta actualización corrige un problema en Microsoft Office en el que los proyectos de Visual Basic para aplicaciones con referencias que se espera encontrar buscando las ubicaciones especificadas en la variable de entorno PATH podían no encontrarse correctamente en tiempo de ejecución, lo que provoca errores en tiempo de ejecución de VBA.

- Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.


[//]: # (NO QUITAR ERRORES DE DETALLES DE CONTENIDO FINAL)

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

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Mejores resultados, en un instante:** actualizamos la experiencia de búsqueda para que sea más inteligente, rápida y fiable que nunca. [Más información](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **Notificación de incidentes para administradores de TI:** se notificará a los administradores globales de espacios empresariales de Microsoft 365 y a los administradores de aplicaciones de Office acerca de los incidentes de Outlook y Exchange de O365 que afectan a sus usuarios con una nueva notificación en el panel derecho en Outlook para Windows.


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.



[//]: # (NO QUITAR ERRORES DE DETALLES DE CONTENIDO FINAL)

## <a name="version-2004-april-29"></a>Versión 2004: 29 de abril
*Versión 2004 (compilación 12730.20236)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Protección de datos del grupo:** la etiqueta de confidencialidad que elija al crear un grupo se aplica al correo electrónico del grupo, a los documentos y a los sitios de equipo.


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO INICIAL)

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

[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO INICIAL)

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

[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO INICIAL)

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

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)




[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO FINAL)

## <a name="version-2003-april-03"></a>Versión 2003: 03 de abril
*Versión 2003 (Compilación 12624.20410)*

[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- El uso de la Aplicación VBA.Evaluar no trabajaba para las funciones definidas por el usuario en algunos casos.

### <a name="outlook"></a>Outlook

- Abordó un problema que causó que los usuarios experimentaran ocasionalmente un choque al usar el botón "X" de su ratón.

### <a name="project"></a>Project

- Cuando se editan los datos del Predecesor/Sucesor dentro de una vista de formulario, se dispara un ProyectoAntesdeCambiarTareaEvento extra.

### <a name="word"></a>Word

- Abordó un problema que causó que los usuarios experimentaran ocasionalmente un choque al usar el botón "X" de su ratón.



[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-2003-march-31"></a>Versión 2003: 31 de marzo
*Versión 2003 (compilación 12624.20382)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="access"></a>Access

- **Panel de tareas "Agregar tablas":** ¡Ya está disponible el acceso al nuevo panel de tareas "Agregar tablas"! Esta característica le permite seleccionar y hacer selección múltiple de las tablas que desea agregar o quitar de forma sencilla en una ventana de consulta, sin tener que desplazarse hasta el cuadro de diálogo "Mostrar tablas" para las consultas y la vista de relación. Esto también incluye una nueva pestaña "vínculos" para mostrar las tablas vinculadas, un cuadro de búsqueda para filtrar la lista actual, el comportamiento de "arrastrar y soltar", ¡y mucho más!


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="project"></a>Proyecto

- <div><span style="display:inline !important;">Se corrigió un problema por el que el usuario no podía especificar el trabajo previsto con fases temporales al activar la configuración para proteger el trabajo real.</span><br></div>



[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

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


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

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

[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se abordó un problema donde los enlaces externos no se actualizan cuando se cierra el libro de fuentes.

### <a name="outlook"></a>Outlook

- Se abordó un problema que causó que los usuarios vieran que el proceso de Outlook permanecía en el administrador de tareas después de salir.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2003-march-10"></a>Versión 2003: 10 de marzo
*Versión 2003 (compilación 12624.20176)*

Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO INICIAL)
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


[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-2002-march-05"></a>Versión 2002: 05 de marzo
*Versión 2002 (compilación 12527.20278)*

- Varias correcciones de errores y rendimiento.


## <a name="version-2002-march-04"></a>Versión 2002: 04 de marzo
*Versión 2002 (compilación 12527.20264)*


[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a>Problemas corregidos

### <a name="project"></a>Proyecto
- <div>Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.</div>


### <a name="office-suite"></a>Conjunto de aplicaciones de Office
- <div>Corrige un problema por el que cuando hay varios documentos abiertos en Word/Excel/PowerPoint de la misma biblioteca de SharePoint, solo se analizará el primer documento abierto para el cumplimiento de las directivas.</div>



[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-2002-march-01"></a>Versión 2002: 01 de marzo
*Versión 2002 (compilación 12527.20242)*

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- <div>Corrige un problema que provocaba que las aplicaciones de terceros no pudiesen enviar correo electrónico.</div>



[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

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

- <div style="box-sizing:border-box;">Se ha solucionado un problema por el que las funciones de CUBEVALUE a veces daban un resultado incorrecto.&nbsp;</div><div><span style="display:inline !important;"></span><br></div>


### <a name="outlook"></a>Outlook

- <div>Corregido un tema que causó que las comas en el campo de ubicación de una reunión se convirtieran en punto y coma.</div>


- <div>Corregido un problema que podría resultar en un choque al ver el mismo elemento en varias ventanas.</div>


- <div>Corregido un problema que causó que Outlook sincronizara inesperadamente todo el correo, incluso cuando el deslizador de sincronización está configurado en un ajuste más pequeño.&nbsp;</div>


- <div>Corregido un problema que causó que los usuarios con el Tema Negro vieran&quot;de&quot; el desplegable muestra un texto blanco sobre un fondo blanco.</div>


- <div><span style="display:inline !important;">Este cambio restaura la capacidad de ver sujetos de varias líneas en el encabezado del mensaje.</span><br></div>



[//]: # (NO ELIMINE EL CONTENIDO FINAL DE LOS DETALLES )

## <a name="version-2002-february-18"></a>Versión 2002: 18 de febrero
*Versión 2002 (compilación 12527.20138)*

## <a name="version-2002-february-11"></a>Versión 2002: 11 de febrero
*Versión 2002 (compilación 12527.20092)*

Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Arrastre el correo electrónico a un grupo de tu propiedad:** Mueva y copie mensajes y conversaciones arrastrándolos desde su bandeja de entrada. Los mensajes que arrastres serán compartidos con todos los miembros del grupo.

### <a name="word"></a>Word

- **Otros usuarios verán los cambios rápidamente**: las mejoras en la coautoría significan que los colaboradores podrán ver los cambios más rápido que nunca.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- **Iconos de la barra de estado más nítidos:** los iconos de la barra de estado ahora son más fáciles de ver.


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

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

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

