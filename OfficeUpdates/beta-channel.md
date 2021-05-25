---
title: Notas de la versión para el canal beta
ms.author: anankani
author: anankani
manager: anankani
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Proporciona a los participantes del Modo anticipado de Insider la lista más reciente de las nuevas características, correcciones o problemas conocidos.
ms.openlocfilehash: 3a78919c5181015c88261bf66413d7f439a916cf
ms.sourcegitcommit: c615a8b353e967222e6a75121fa6aea3d673b28b
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 05/24/2021
ms.locfileid: "52625945"
---
# <a name="release-notes-for-beta-channel"></a>Notas de la versión para el canal beta

El presente artículo contiene notas de la versión para las compilaciones del canal beta de las versiones de escritorio de Word, Excel, PowerPoint, Outlook, Access y Project para Windows. Cada semana se destacarán las nuevas características, correcciones importantes y los problemas principales de mayor interés para usted. Tenga en cuenta que a menudo se implementan características (o incluso correcciones) en el canal beta durante un período de tiempo. Esto nos permite asegurarnos de que todo funciona correctamente antes de publicar la característica para un público más amplio. Por lo tanto, si ve que no dispone de algo de lo que se describe a continuación, no se preocupe, lo obtendrá en algún momento.  

> [!IMPORTANT]
> Estamos realizando algunos cambios en los canales de actualización de las Aplicaciones de Microsoft 365, incluida la adición de un nuevo canal de actualización (canal empresarial mensual) y el cambio de los nombres de los canales de actualización existentes. Para más información, [lea este artículo](/DeployOffice/update-channels-changes).

> [!NOTE]
> - Las notas de publicación se publican semanalmente y pueden ser una compilación de varias versiones.
> - La fecha de publicación de las notas de versión pueden no coincidir con la fecha real de lanzamiento de la compilación.

[//]: # (NO ELIMINAR)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

## <a name="version-2106-may-21"></a>Versión 2106: 21 de mayo
*Versión 2106 (Compilación 14117.20000)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Último inicio de sesión/Inicio de sesión sospechoso:** Outlook ahora le indica cuándo y dónde iniciado sesión por última vez en su cuenta y le avisa si se detecta actividad de inicio de sesión sospechosa


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema que causaba que las matrices dinámicas no actualizaran los valores de celda cuando se hace referencia a las funciones RealTimeData.


- Se ha corregido un problema que afectaba al rendimiento de VLOOKUP e ÍNDICE/COINCIDIR al rellenar una gran cantidad de datos.


- Se ha corregido un problema relacionado con el desplazamiento con dos dedos al usar inmovilizar paneles.


- Se ha corregido un problema relacionado con problemas de memoria al imprimir en impresoras de formato grande.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema que impedía copiar desde el panel de notas del orador mientras estaba en modo solo lectura.


### <a name="word"></a>Word

- Se ha corregido un problema en el que se mostraba un mensaje de error al Guardar como incluso después de que un usuario decidiese descartar cambios.


- Se ha corregido un problema que impedía que las imágenes se publicaran en comentarios modernos.


- Se ha corregido un problema que hace que el Panel de revisión se desplace o parezca que no está alineado con el comentario seleccionado.


- Se ha corregido un problema que causaba que no se borrara la selección del documento al hacer clic fuera de un comentario creado recientemente.


- Se ha corregido un problema en el que no se resaltaban los comentarios al seleccionarlos.


- Se ha corregido un problema que hacía que se actualizara el campo incorrecto al ejecutar una macro si se aplican restricciones de edición.


- Se ha corregido un problema que causaba que algunos archivos de Word no se abrieran debido a marcadores dañados.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema que causaba que se bloqueara el inicio de sesión con una cuenta diferente.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2106-may-14"></a>Versión 2106: 14 de mayo
*Versión 2106 (Compilación 14107.20000)*


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Hemos corregido un problema que provocaba que los usuarios vieran los mensajes que requieren acción actualizándose constantemente o revertidos a los encabezados después de la descarga, cuando se ejecute el modo Descargar solo encabezados.


- Hemos corregido un problema que provocaba que el selector de usuarios en Outlook se expandiera hacia arriba en lugar de hacia abajo para los usuarios con una licencia permanente.


- Hemos corregido un problema que causaba que los usuarios de dominios personalizados vean un mensaje de advertencia sobre los permisos al pegar un vínculo en un mensaje de correo electrónico.


### <a name="word"></a>Word

- Hemos corregido un problema que hacía que, al presionar combinaciones de teclas como Ctrl + Mayús + @, no se generaba el carácter acentuado esperado (en este caso, "å").


- Hemos corregido un problema relacionado con la compresión de imágenes.


- Se ha corregido un problema por el que se producía un fallo al copiar datos adjuntos de correo a una aplicación diferente a Word si el nombre de archivo incluía los caracteres DBCS.


- Hemos corregido un problema que hacía que Word mostrara a veces un borde alrededor del texto que no debía estar allí.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Hemos corregido un problema por el que OneDrive mostraba un mensaje de error de combinación cuando en realidad no había ningún conflicto en la combinación.


- Hemos corregido un problema relacionado con el orden z de los objetos SVG al convertirlos a formas.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2106-may-07"></a>Versión 2106: 07 de mayo
*Versión 2106 (compilación 14029.20000)*


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Hemos corregido un problema que impide que el Administrador de nombres abra libros con un gran número de nombres ocultos.


### <a name="outlook"></a>Outlook

- Hemos corregido un problema que causaba que los usuarios viesen copias de todos los elementos enviados en su carpeta Bandeja de salida.


- Hemos corregido un problema que causaba que Outlook se cerrara de forma inesperada al usar lectura en voz alta con otras versiones de Windows.


### <a name="word"></a>Word

- Hemos corregido un problema que causaba que Word se cerrara inesperadamente al usar lectura en voz alta con otras versiones de Windows.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2105-april-30"></a>Versión 2105: 30 de abril
*Versión 2105 (Compilación 14026.20000)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Sugerencia de productividad del Comprobador de accesibilidad al enviar correos electrónicos a usuarios externos de listas de distribución de gran tamaño:** Hemos agregado la funcionalidad para que mostrar automáticamente una notificación, mediante una información sobre correo, ante una infracción de accesibilidad al redactar un correo electrónico para grandes audiencias, usuarios externos, etc. Esta configuración se encuentra en Accesibilidad

### <a name="visio"></a>Visio

- **Formas y galerías de símbolos de AWS:** ahora tenemos galerías de símbolos con las formas de AWS más recientes para ayudarle a crear diagramas. [Más información](https://support.office.com/article/138206bf-d10f-4583-9f31-885ce706af49)

### <a name="word"></a>Word

- **Objetivos de escritura:** objetivos de escritura para WinWord


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Hemos corregido un problema que hacía que Excel se cerrara inesperadamente al desplazarse por los comentarios del panel Comentarios.


- Hemos corregido un problema que causaba que el formato de fecha se mostrara de forma incorrecta en algunos idiomas al usar complementos.


- Hemos corregido un problema que podía provocar que Excel se cerrara de forma inesperada al usar Pegado especial con formatos en determinadas situaciones.


### <a name="project"></a>Project

- Hemos corregido un problema que provocaba que los cambios realizados con los Asistentes para planificación no siempre se capturaran con eventos de cambio.


- Hemos corregido un problema en el que los usuarios no podían quitar proyectos del grupo de recursos.


### <a name="word"></a>Word

- Hemos corregido un problema por el cual se conservaba el formato de texto después de quitar los hipervínculos.


- Hemos corregido un problema que hacía que los comentarios no se mostraran después de filtrar por usuario.


- Hemos corregido un problema que impedía a Word combinar correspondencia con una base de datos de Access.


- Hemos corregido un problema que hacía que estuviera disponible la capacidad de contraer los márgenes de los documentos que contuvieran varias columnas.


- Hemos corregido un problema que impedía que algunos caracteres se mostraran correctamente en las celdas de la tabla cuando había comentarios en el documento.


- Hemos corregido un problema por el cual se producían los cambios en el formato de archivo al guardar documentos con el complemento AIP habilitado.


- Hemos corregido un problema que hacía que Word no respondiera al editar campos.


- Hemos corregido un problema por el cual no se solicitaba a los usuarios guardar documentos al usar un comando (en lugar del método abreviado de teclado CTRL+S).


- Hemos corregido un problema por el que la etiqueta de confidencialidad desaparecía de un archivo en Word después de cargar el archivo en SharePoint Online.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Hemos corregido un problema que causaba que el botón de dictado estuviera mal alineado al agregar comentarios a un documento.


- Hemos corregido un problema que causaba que Outlook se cerrara de forma inesperada al usar el modo de contraste alto durante largos períodos de tiempo.



[//]: # (NO QUITAR FINAL DE CONTENIDO CON DETALLES DE ERROR)

## <a name="version-2105-april-23"></a>Versión 2105: 23 de abril
*Versión 2105 (compilación 14014.20002)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Importar datos de matrices dinámicas:** ahora puede importar, dar forma y actualizar datos de matrices dinámicas en el libro actual. [Más información](https://support.office.com/article/205c6b06-03ba-4151-89a1-87a7eb36e531)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Hemos corregido un problema para ofrecer compatibilidad con versiones anteriores de Excel. El problema puede provocar que un archivo que se guarda en una versión más reciente de Excel no se cargue correctamente en versiones anteriores de Excel debido a funciones como SI.ERROR y BUSCARX agregado a Excel desde Office 2007.


- Hemos corregido un problema que en ocasiones producía errores al abrir algunos archivos en la Vista protegida.


- Hemos corregido un problema que causaba que la barra de estado no indicase un estado Listo para algunos usuarios.


### <a name="outlook"></a>Outlook

- Hemos corregido un problema que provocaba errores en la resolución de nombres al enviar en nombre de otro usuario y al resolver en una libreta de direcciones que no es la Lista global de direcciones.


### <a name="word"></a>Word

- Hemos corregido un problema que hace que el texto de los marcadores de posición esté recortado en los comentarios al usar idiomas de derecha a izquierda.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Hemos corregido un problema en el que los hipervínculos que incluyen dígitos se rompen al redactar un mensaje en Outlook en un idioma de derecha a izquierda.


- Hemos corregido un problema que hacía que algunos Scalable Vector Graphics (SVG) no se representasen correctamente.



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2105-april-16"></a>Versión 2105: 16 de abril
*Versión 2105 (compilación 14007.20002)*


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Hemos corregido un problema que causaba que Excel se bloqueara al usar Office de 32 bits en Windows de 64 bits.


- Hemos corregido un problema que causaba que Narrador leyese incorrectamente las propiedades de dos botones de la pestaña Encabezado y pie de página del cuadro de diálogo Configurar página.


### <a name="powerpoint"></a>PowerPoint

- Hemos corregido un problema relacionado con las imágenes vinculadas.



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2105-april-09"></a>Versión 2105: 09 de abril
*Versión 2105 (compilación 14002.20000)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Cinta de opciones de accesibilidad:** encuentre todas las herramientas que necesita para crear contenido accesible en un solo lugar, la cinta de opciones de accesibilidad.

### <a name="word"></a>Word

- **Ahora la corrección está disponible para el texto seleccionado dentro del documento:** con estos cambios, ahora puede revisar la ortografía, la gramática y otras sugerencias de escritura inteligente solo para el texto seleccionado. Además, también puede revisar sugerencias para todo el documento.


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO FINAL)

## <a name="version-2104-april-02"></a>Versión 2104: 02 de abril
*Versión 2104 (Compilación 13929.20016)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Respuestas sugeridas en Outlook para Windows:** Cuando recibe un mensaje de correo electrónico que puede responderse con una respuesta breve, Outlook puede sugerirle tres respuestas que puede usar con tan solo hacer un par de clics.

- **Habilitar las mejoras del calendario compartido:** Outlook puede actualizar los calendarios compartidos en Office 365 con la API de REST. Active la vista previa para obtener actualizaciones más rápidas y confiables de los calendarios compartidos.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Acceso

- Hemos corregido un problema por el que, cuando una aplicación externa solicitaba una interfaz de accesibilidad, nos impedía cerrar hasta que se liberaba su referencia.


### <a name="word"></a>Word

- Con este error, Office no estaba respetando las directivas específicas (se mostraba un grupo de plantillas en la página principal cuando debían haber estado deshabilitadas). Con esta corrección, se respetan las directivas.


- Hemos corregido un problema con el Autoguardado.


- Hemos corregido Application.OnTime donde puede que no se desencadene correctamente.



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL )

## <a name="version-2104-march-26"></a>Versión 2104: 26 de marzo
*Versión 2104 (compilación 13919.20002)*


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Hemos corregido un problema que causaba que algunos usuarios experimentasen un cierre inesperado de Outlook al sincronizar los cambios en la jerarquía de carpetas.


### <a name="word"></a>Word

- Hemos corregido un problema por el cual los estilos de copiar y pegar pueden no ser iguales en el texto pegado.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema de rendimiento relacionado con la iteración de texto.



[//]: # (NO QUITAR EL CONTENIDO FINAL DE LOS DETALLES DE LOS ERRORES)

## <a name="version-2104-march-19"></a>Versión 2104: 19 de marzo
*Versión 2104 (Compilación 13913.20000)*


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Este cambio corrige un problema por el que al ejecutar una consulta que pasara por SQL Server, se mostraba en algunos casos un mensaje de error que alertaba de un "estado de cursor no válido".


### <a name="excel"></a>Excel

- Hemos corregido un problema que bloqueaba la capacidad de pegar como fórmulas en una hoja protegida.


### <a name="project"></a>Project

- Se ha corregido un problema por el que, si el formato de fecha es W4/4, el selector de fecha puede mostrar un día y un año incorrectos.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Soluciona un problema con el soporte técnico de GDI+ LineJoinMiterClipped en Office.



[//]: # (NO QUITAR EL CONTENIDO FINAL DE LOS DETALLES DE LOS ERRORES)

## <a name="version-2104-march-12"></a>Versión 2104: 12 de marzo
*Versión 2104 (Compilación 13906.20000)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="powerpoint"></a>PowerPoint

- **Insertar vídeos de Flipgrid en PowerPoint:** PowerPoint ahora admite la inserción de vídeos de Flipgrid en las diapositivas.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Hemos corregido un problema por el que los hipervínculos creados con la función HIPERVINCULO no funcionaban si el archivo se guardaba como un documento PDF.


### <a name="word"></a>Word

- Hemos corregido un problema con los comentarios durante la coautoría.



[//]: # (NO QUITAR EL CONTENIDO FINAL DE LOS DETALLES DE LOS ERRORES)

## <a name="version-2103-march-05"></a>Versión 2103: 05 de marzo
*Versión 2103 (compilación 13901.20036)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Autoguardado y coautoría en documentos cifrados confidenciales:** no elija entre productividad y seguridad. Con Microsoft Information Protection, los documentos que se cifran con etiquetas de confidencialidad ahora permiten el autoguardado y la coautoría con otras personas en tiempo real, igual que los documentos sin cifrar. Requiere que el espacio empresarial opte por participar (más información: https://aka.ms/mipcoauth).

### <a name="powerpoint"></a>PowerPoint

- **Autoguardado y coautoría en documentos cifrados confidenciales:** no elija entre productividad y seguridad. Con Microsoft Information Protection, los documentos que se cifran con etiquetas de confidencialidad ahora permiten el autoguardado y la coautoría con otras personas en tiempo real, igual que los documentos sin cifrar. Requiere que el espacio empresarial opte por participar (más información: https://aka.ms/mipcoauth).

### <a name="word"></a>Word

- **Autoguardado y coautoría en documentos cifrados confidenciales:** no elija entre productividad y seguridad. Con Microsoft Information Protection, los documentos que se cifran con etiquetas de confidencialidad ahora permiten el autoguardado y la coautoría con otras personas en tiempo real, igual que los documentos sin cifrar. Requiere que el espacio empresarial opte por participar (más información: https://aka.ms/mipcoauth).


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Hemos corregido un problema por el que la fuente cambiaría de forma inesperada al usar un signo de multiplicación o división con una fuente japonesa. Ahora continuamos usando la misma fuente si admite el carácter.


- Hemos corregido un problema que causaba que algunos formatos de tabla dinámica dañaran el libro al guardar en formato .xls o .xlt.


- Hemos corregido un problema por el que se muestran de forma inesperada algunas notas al abrir un libro.


### <a name="outlook"></a>Outlook

- Hemos corregido un problema que causaba que los caracteres que no sean ASCII se exportaran de forma incorrecta al exportar a un archivo CSV.


- Hemos corregido un problema que causaba que los usuarios no pudieran buscar un grupo de contactos con Comprobar nombres al redactar un correo.


### <a name="powerpoint"></a>PowerPoint

- Hemos corregido un problema que hacía que las flechas de los gráficos de líneas no estuvieran tal y como se esperaba en el modo de presentación de PowerPoint.


### <a name="word"></a>Word

- Hemos corregido un problema por el que, al abrir un archivo protegido con una etiqueta de Microsoft Information Protection (MIP), se puede colgar de forma indefinida si el usuario no ha iniciado sesión en una identidad que tiene acceso a la etiqueta protegida de MIP. El usuario no puede cancelar la apertura para mostrar la solicitud de inicio de sesión yno se puede completar correctamente gasta entonces. Para solucionar este problema, permita que se muestre la solicitud de inicio de sesión durante la apertura o descarga.


- Hemos corregido un problema al usar Dictado en el nuevo Comentarios de Word. Ahora, el botón de dictado de la tarjeta Comentarios se activa y desactivada correctamente.


- Se ha corregido un problema por el que no se insertaba ningún espacio entre palabras cuando los usuarios dictaban en su documento.


- Hemos corregido un problema al publicar comentarios de varias líneas escritos en RTL que causaba que las líneas 2 en adelante se alineasen a la izquierda en lugar de a la derecha.


- Hemos corregido un problema que hace que la revisión ortográfica cambie entre dos menús contextuales de corrección ortográfica diferentes.


- Hemos corregido un problema en el que las columnas pueden tener texto superpuesto.



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2103-february-26"></a>Versión 2103: 26 de febrero
*Versión 2103 (compilación 13819.20006)*


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Hemos corregido un problema que impedía a los usuarios exportar un libro de Excel a PDF.


- Hemos corregido un problema que causaba que se perdiera algo del formato al copiar una hoja mientras se trabajaba en coautoría.


### <a name="outlook"></a>Outlook

- Hemos corregido un problema que causaba que los usuarios viesen cómo los datos adjuntos se duplicaban al quitar la protección DRM.


### <a name="project"></a>Project

- Se ha corregido un problema por el que es posible que las divisiones de tareas se creen de forma incorrecta al guardar un proyecto desde Project Web App en un archivo local. Esto sucedía al usar un calendario de tareas con horas de trabajo no estándar.


- Se ha corregido un problema por el que, si la columna de indicador no está en el primer lugar de la columna, al cortar una tarea de resumen, no se advierte de que también se quitarán las subtareas.


- Se ha corregido un problema por el que, si un usuario seleccionaba la opción Agregar su usuario a una función de tarea en su Timesheet, no se podrían usar correctamente las unidades de disponibilidad de recursos en la tarea creada.


### <a name="word"></a>Word

- Hemos corregido un problema con la alineación de varios comentarios.


- Hemos corregido un problema en los métodos abreviados de teclado del panel de tareas Leer en voz alta.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Las ubicaciones de OneDrive ahora se filtran según corresponda en la configuración de directiva de grupo.


- Soluciona un problema relacionado con la falta de respuesta que puede producirse al cargar imágenes EMF.



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2103-february-19"></a>Versión 2103: 19 de febrero
*Versión 2103 (compilación 13811.20002)*


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Hemos corregido un problema que causaba que los usuarios viesen cómo los datos adjuntos se duplicaban al quitar la protección DRM.


### <a name="project"></a>Project

- Se ha corregido un problema por el que, si la columna de indicador no está en el primer lugar de la columna, al cortar una tarea de resumen, no se advierte de que también se quitarán las subtareas.


- Se ha corregido un problema por el que, si un usuario seleccionaba la opción Agregar su usuario a una función de tarea en su Timesheet, no se podrían usar correctamente las unidades de disponibilidad de recursos en la tarea creada.


### <a name="word"></a>Word

- Hemos corregido un problema en los métodos abreviados de teclado del panel de tareas Leer en voz alta.



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2103-february-12"></a>Versión 2103: 12 de febrero
*Versión 2103 (Compilación 13806.20000)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Sugerencias de redacción con tecnología de Búsqueda de Microsoft (Para\CC\CCO):** ahora la adición de personas a la línea Para\CC usa la tecnología de Búsqueda de Microsoft.

- **Dictado está disponible en más idiomas:** ahora admite 7 idiomas nuevos: hindi, ruso, polaco, portugués (Portugal), coreano, tailandés y chino (Taiwán)

### <a name="word"></a>Word

- **Dictado está disponible en más idiomas:** ahora admite 7 idiomas nuevos: hindi, ruso, polaco, portugués (Portugal), coreano, tailandés y chino (Taiwán)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema que causaba que Excel se cerrara de forma inesperada al intentar mostrar la tarjeta tipos de datos porque una imagen no se podía recuperar.

### <a name="powerpoint"></a>PowerPoint

- Corregido un problema con la reproducción de animaciones y marcadores de audio.

### <a name="project"></a>Project

- Se ha corregido un problema por el que una tarea completada al 100 % podía aparecer como completada al 99 %.

- Se ha corregido un problema por el que Project se cerraba inesperadamente si ejecutaba JAWS e iba al diálogo de información de la tarea.

### <a name="word"></a>Word

- Hemos corregido un problema con Autoguardado.


- Hemos corregido un problema relacionado con la resolución de conflictos durante la coautoría.




[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2102-february-05"></a>Versión 2102: 05 de febrero
*Versión 2102 (Compilación 13801.20004)*


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Ahora verá las pestañas seleccionadas más claramente en Access.


### <a name="excel"></a>Excel

- Hemos corregido un problema por el que Excel dejaba de responder después de seleccionar una serie de datos en un gráfico.


- Hemos corregido un problema por el que, al presionar Entrar con determinados teclados de Android, se agregaba una nueva línea en lugar de pasar a la siguiente celda.


- Se ha corregido un problema relacionado con las imágenes que conservaban su relación de aspecto durante una operación de recorte.


### <a name="outlook"></a>Outlook

- Hemos corregido un problema por el que los mensajes de correo electrónico se enviaban como firmados digitalmente después de que el usuario desactivara esa opción.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema relacionado con las imágenes que conservaban su relación de aspecto durante una operación de recorte.


### <a name="word"></a>Word

- Se ha corregido un problema relacionado con las imágenes que conservaban su relación de aspecto durante una operación de recorte.


- Hemos corregido un problema que podía truncar un comentario con vínculos.


- Hemos corregido un problema con el modo de conflicto al trabajar en coautoría.


- Hemos corregido un problema relacionado con guardar archivos en SharePoint Online.


- Hemos corregido un problema relacionado con la exportación de un documento de Word a PDF.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema por el que, en algunas circunstancias, Office presentaba etiquetas de confidencialidad para una cuenta con la que se había iniciado sesión en lugar de presentarlas para otra cuenta diferente con la que se había iniciado sesión.




[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2102-january-29"></a>Versión 2102: 29 de enero
*Versión 2102 (Compilación 13721.20008)*


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Hemos corregido un problema en el que Excel se cerraba inesperadamente al agregar un nombre en el cuadro de diálogo Definir nombre.


### <a name="outlook"></a>Outlook

- Hemos corregido un problema que causaba que no se mostrara el icono de cifrado de los correos electrónicos enviados con la opción Solo cifrar.

### <a name="project"></a>Project

- Se ha corregido un problema por el que no se podían abrir proyectos con nombres largos en alfabeto cirílico a través del Centro de proyectos.


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2102-january-22"></a>Versión 2102: 22 de enero
*Versión 2102 (compilación 13714.20000)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Los clientes gubernamentales pueden ya aplicar etiquetas de confidencialidad a sus documentos y correos electrónicos**: las características de las etiquetas de confidencialidad ahora están disponibles para los clientes de los entornos GCC y GCC-H. [Más información](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a>Outlook

- **Los clientes gubernamentales pueden ya aplicar etiquetas de confidencialidad a sus documentos y correos electrónicos**: las características de las etiquetas de confidencialidad ahora están disponibles para los clientes de los entornos GCC y GCC-H. [Más información](/microsoft-365/compliance/sensitivity-labels)

### <a name="powerpoint"></a>PowerPoint

- **Los clientes gubernamentales pueden ya aplicar etiquetas de confidencialidad a sus documentos y correos electrónicos**: las características de las etiquetas de confidencialidad ahora están disponibles para los clientes de los entornos GCC y GCC-H. [Más información](/microsoft-365/compliance/sensitivity-labels)

### <a name="word"></a>Word

- **Los clientes gubernamentales pueden ya aplicar etiquetas de confidencialidad a sus documentos y correos electrónicos**: las características de las etiquetas de confidencialidad ahora están disponibles para los clientes de los entornos GCC y GCC-H. [Más información](/microsoft-365/compliance/sensitivity-labels)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema que hace que determinados gráficos que usan rangos de celdas discontinuos no se carguen al volver a abrir los archivos.


- Corrige un problema por el que Excel no se podía iniciar o se bloqueaba inesperadamente si se usaba determinada configuración de protección contra vulnerabilidades de Seguridad de Windows (SimExec, CallerCheck).


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema relacionado con la muestra de emojis con color.


### <a name="word"></a>Word


- Corregido un problema que impedía que la escritura en tiempo real y la presencia se restauraran tras perder la conectividad a Internet durante un período de tiempo.


- Se ha corregido un problema con la coautoría.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2102-january-15"></a>Versión 2102: 15 de enero
*Versión 2102 (compilación 13707.20008)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Compartir con Teams:** compartir un correo electrónico o una conversación desde Outlook a un usuario o canal en Teams.

### <a name="visio"></a>Visio

- **Gráficos preparados para los diagramas:** elija entre una gran biblioteca de íconos, imágenes de fotografías de archivo, personas recortadas y adhesivos que puede agregar a sus dibujos de Visio. [Más información](https://support.office.com/article/0ab844a5-289b-47f2-ba92-eeda168bc381)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="project"></a>Project

- Se corrigió un problema por el que, cuando se asignó un recurso de costo a una tarea hito, el costo de línea base no se acumulaba correctamente.


### <a name="word"></a>Word

- Se corrigió un problema por el que, al ejecutar la macro de VBA ExportAsFixedFormat2, se produce un error que indica "Valor no válido de presentación (miembro desconocido)".



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2102-january-08"></a>Versión 2102: 8 de enero
*Versión 2102 (compilación 13704.20000)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **El dictado se puso mejor:** Ahora es más fácil crear contenido con la voz gracias a la nueva barra de herramientas de dictado, comandos de voz y compatibilidad con la puntuación automática

### <a name="word"></a>Word

- **El dictado se puso mejor:** Ahora es más fácil crear contenido con la voz gracias a la nueva barra de herramientas de dictado, comandos de voz y compatibilidad con la puntuación automática


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema que provocaba que la vista previa del intervalo de Excel insertado en PowerPoint mostrara un tamaño incorrecto.



[//]: # (NO QUITAR LOS DETALLES DE ERROR AL FINAL DEL CONTENIDO)

## <a name="version-2101-january-01"></a>Versión 2101: 01 de enero
*Versión 2101 (compilación 13624.20002)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Etiqueta obligatoria:** usuarios con la Directiva de etiquetado obligatoria se debe establecer que los administradores les etiqueten sus documentos y mensajes de correo electrónico.

### <a name="powerpoint"></a>PowerPoint

- **Etiqueta obligatoria:** usuarios con la Directiva de etiquetado obligatoria se debe establecer que los administradores les etiqueten sus documentos y mensajes de correo electrónico.

### <a name="word"></a>Word

- **Etiqueta obligatoria:** usuarios con la Directiva de etiquetado obligatoria se debe establecer que los administradores les etiqueten sus documentos y mensajes de correo electrónico.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="onenote"></a>OneNote

- Este cambio resuelve un problema de representación que afecta a OneNote.


### <a name="outlook"></a>Outlook

- Este cambio permite a Outlook aprovechar una configuración de Exchange Server que suprime la presentación del buzón de correo de Exchange Online para usuarios finales.


### <a name="powerpoint"></a>PowerPoint

- Este cambio resuelve un problema con las formas de combinar trabajar con texto.


### <a name="word"></a>Word

- Corrección para mejorar la solidez de los comentarios modernos.


- Se ha corregido un problema al editar una entrada de comentario con @mention.


- Los borradores de comentarios desaparecen al crear una nueva instancia de Word.


- Corrección y problema con las barras de desplazamiento anidadas en la ventana Comentarios.



[//]: # (NO QUITAR LOS DETALLES DE ERROR AL FINAL DEL CONTENIDO)

## <a name="version-2101-december-25"></a>Versión 2101: 25 de diciembre
*Versión 2101 (compilación 13617.20002)*


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Actualización para que la configuración de los separadores decimales y de millares se mantenga al copiar un gráfico de Excel y pegarlo en Word.


- Se ha corregido un problema por el que Excel se cerraba inesperadamente al abrir archivos UNC con atributos de archivo no válidos (hora de creación, fecha de modificación, etc.).


- Este cambio resuelve un problema relacionado con la modificación de los colores del contorno de imágenes SVG.


### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que los usuarios no pudiesen especificar durante cuánto tiempo querían permitir el acceso al iniciar una combinación de correo de Word, lo que hacía que se enviasen demasiados avisos.


- Se ha corregido un problema que provocaba que Outlook se cerrara de forma inesperada para los usuarios de complementos basados en Redemption.


### <a name="powerpoint"></a>PowerPoint

- Este cambio resuelve un problema relacionado con la modificación de los colores del contorno de imágenes SVG.


### <a name="word"></a>Word

- Este cambio resuelve un problema relacionado con la modificación de los colores del contorno de imágenes SVG.


- Corrige un problema por el que el cuadro de respuesta en una tarjeta de comentario aparece fuera de la pantalla.



[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO FINAL)

## <a name="version-2101-december-18"></a>Versión 2101: 18 de diciembre
*Version 2101 (compilación 13610.20002)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Envío de datos de auditoría sobre el etiquetado de confidencialidad a los administradores de M365:** cuando los usuarios apliquen, cambien o eliminen las etiquetas de confidencialidad en sus documentos y correos electrónicos, Office enviará datos de auditoría al back-end de auditoría de M365 para que los administradores los vean. Esta es una funcionalidad silenciosa (sin interfaz de usuario) para beneficio del administrador.

### <a name="outlook"></a>Outlook

- **Envío de datos de auditoría sobre el etiquetado de confidencialidad a los administradores de M365:** cuando los usuarios apliquen, cambien o eliminen las etiquetas de confidencialidad en sus documentos y correos electrónicos, Office enviará datos de auditoría al back-end de auditoría de M365 para que los administradores los vean. Esta es una funcionalidad silenciosa (sin interfaz de usuario) para beneficio del administrador.

### <a name="powerpoint"></a>PowerPoint

- **Envío de datos de auditoría sobre el etiquetado de confidencialidad a los administradores de M365:** cuando los usuarios apliquen, cambien o eliminen las etiquetas de confidencialidad en sus documentos y correos electrónicos, Office enviará datos de auditoría al back-end de auditoría de M365 para que los administradores los vean. Esta es una funcionalidad silenciosa (sin interfaz de usuario) para beneficio del administrador.

### <a name="word"></a>Word

- **Envío de datos de auditoría sobre el etiquetado de confidencialidad a los administradores de M365:** cuando los usuarios apliquen, cambien o eliminen las etiquetas de confidencialidad en sus documentos y correos electrónicos, Office enviará datos de auditoría al back-end de auditoría de M365 para que los administradores los vean. Esta es una funcionalidad silenciosa (sin interfaz de usuario) para beneficio del administrador.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se realizó una mejora de rendimiento al aplicar estilos de formato a tablas dinámicas.


### <a name="outlook"></a>Outlook

- Se corrigió el problema que causaba que los usuarios no pudieran seleccionar más de una categoría para buscar.


- Se corrigió el problema que causaba que la hora de inicio de algunos elementos del calendario cambiara inesperadamente cuando el evento se copiaba de otra cita.


### <a name="project"></a>Project

- Hemos corregido un problema por el cual los usuarios creaban proyectos que supuestamente se guardaban con información actualizada pero en los que no había ninguna actualización.


### <a name="word"></a>Word

- Corregir animación al escribir en la parte inferior de una tarjeta de comentario.


- Se ha corregido un problema que causaba que Word se bloqueara al guardar un documento en PDF con texto oculto.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2101-december-11"></a>Versión 2101: 11 de diciembre
*Versión 2101 (compilación 13604.20000)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Su configuración de Outlook en la nube:** elija la configuración de Outlook para Windows, como Respuestas automáticas, la Bandeja de entrada Prioritarios y Privacidad, y acceda a ellos desde cualquier PC.

### <a name="word"></a>Word

- **Mejor colaboración con comentarios modernos:** Agregue comentarios a objetos, @mencione compañeros y resuelva hilos de comentarios para disfrutar de una mejor experiencia de colaboración. [Más información](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)<br />Ver detalles en [entrada de blog](https://insider.office.com/es-ES/blog/modern-commenting-in-word)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema por el que Excel mostraba de forma incorrecta una barra de mensajes donde se indicaba que estaba disponible una nueva versión del archivo y obligaba al usuario a descartar los cambios o guardarlos en una copia del libro.


- Se ha corregido un problema con los separadores de conmutación después de Selection.Parent.Copy.


### <a name="outlook"></a>Outlook

- Se corrigió un problema por el que los mensajes de texto sin formato S/MIME se volvían ilegibles al enviarse.


### <a name="powerpoint"></a>PowerPoint

- Este cambio resuelve un problema en la reproducción de vídeos de fondo en bucle en la presentación con diapositivas.


- Se ha corregido un problema por el que el comando tamaño de fuente, agregado a la herramienta de acceso rápido, se completaba automáticamente al tamaño de fuente definido más cercano al actualizarse.


### <a name="word"></a>Word

- Se ha corregido un problema en torno a la eliminación de los comentarios modernos en un control de contenido marcado como no editable.



[//]: # (NO QUITAR NINGÚN DETALLE DE ERROR EN EL FINAL DEL CONTENIDO)

## <a name="version-2012-december-04"></a>Versión 2012: 4 de diciembre
*Versión 2012 (compilación 13530.20000)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Dar algo de tiempo entre reuniones consecutivas:** asigne a los asistentes el tiempo necesario para que descansen o se desplacen entre las distintas ubicaciones. Para ello haga que las reuniones empiecen de 5 a 10 minutos antes de forma predeterminada. [Más información](https://support.office.com/article/be84396a-0903-4e25-b31c-1c99ce0dacf2)

### <a name="visio"></a>Visio

- **Nuevas galerías de símbolos y formas de Azure:** Hemos agregado muchas más galerías de símbolos para ayudarle a crear diagramas de Azure actualizados. [Más información](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema por el que la edición en idiomas que requieren el uso del IME funcionaba mal al editar en el modo de sobrescritura.


- Se ha corregido un hipervínculo roto a un artículo de ayuda en una alerta que aparecía al deshabilitar Autoguardado.


- Se ha corregido un problema que provocaba que Excel se cerrase de forma inesperada al copiar y pegar datos en la vista Fórmula.


### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que SmartLinks perdiera el formato cuando se guardaba en Borradores.


### <a name="project"></a>Project

- Se ha corregido un problema que alargaba demasiado el tiempo de apertura de un proyecto con muchos recursos.


- Se ha corregido un problema por el que algunos proyectos específicos podrían abrirse si había un problema con el archivo del proyecto en una parte específica de la carga.


### <a name="word"></a>Word

- A menudo, Pegar como texto sin formato tiene preferencia sobre Pegar como texto enriquecido. La corrección de este menú contextual permite al usuario pegar como texto sin formato. De lo contrario, el usuario tendría que copiarlo en un editor de texto sin formato como el Bloc de notas y, luego, copiarlo de allí a la aplicación de destino deseada.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2012-november-27"></a>Versión 2012: 27 de noviembre
*Versión 2012 (compilación 13519.20000)*


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Corregido un problema por el que Power Pivot no importaba correctamente un archivo de texto delimitado por tabulaciones.


### <a name="outlook"></a>Outlook

- Corregido un problema que provocaba que los usuarios experimentaran problemas al enviar correo de Outlook desde aplicaciones que no son Outlook.


### <a name="powerpoint"></a>PowerPoint

- Este cambio resuelve un problema relacionado con los tiempos de espera experimentados durante el análisis de entrada de lápiz.


- Este cambio corrige un error gramatical en la interfaz de usuario Crear un archivo GIF animado.


- Se ha corregido un problema que evitaba que algunos archivos de PowerPoint corruptos se abrieran correctamente, incluso después de la operación de reparación de un documento.


### <a name="project"></a>Project

- Se ha corregido un problema en el que los usuarios pueden ver varias tareas no asignadas asociadas a una tarea.


- Se ha corregido un problema en el que los proyectos de gran tamaño pueden tardar más en especificar un nombre de tarea.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2012-november-20"></a>Versión 2012: 20 de noviembre
*Versión 2012 (compilación 13512.20000)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Todas las reuniones en línea:** facilite la programación de reuniones en línea con una nueva configuración para que todas las reuniones sean en línea de forma predeterminada.

### <a name="powerpoint"></a>PowerPoint

- **Biblioteca de vídeos:** Mejore sus documentos con una biblioteca de videos editados y libres de royalties disponibles en la aplicación.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema que evitaba que el indicador de presencia de un coautor desconocido no se actualizara por completo cuando había disponible más información sobre el coautor.


### <a name="word"></a>Word

- Se ha corregido un problema que causaba que Word se bloqueara al guardar un documento en PDF con texto oculto.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2012-november-13"></a>Versión 2012: 13 de noviembre
*Versión 2012 (Compilación 13510.20004)*


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Hemos corregido un problema por el cual el comando Insertar objeto no muestra el icono correcto cuando se inserta un archivo desde la carpeta de sincronización local de OneDrive.


### <a name="outlook"></a>Outlook

- Hemos corregido un problema que provocaba que el campo Para: quedara en blanco en los informes de estado de la tarea.


### <a name="powerpoint"></a>PowerPoint

- Hemos corregido un problema de VBA por el cual Slide.Shapes.AddMediaObject2 se bloqueaba con formatos de vídeo heredados (MPG-1, MPEG-2).


### <a name="project"></a>Project

- Hemos corregidoo un problema por el cual no se podían eliminar las dependencias de las entregas si el sitio de SharePoint en el que estaba asociada la entrega ya no existía.


- Hemos corregido un problema por el cual los usuarios creaban proyectos que supuestamente se guardaban con información actualizada pero en lo que no había ninguna actualización.


### <a name="word"></a>Word

- Hemos corregido un problema relacionado con las imágenes difuminadas por usar el zoom.


- Hemos corregido un problema por el cual se truncaban hipervínculos largos.



[//]: # (NO QUITAR NINGÚN DETALLE DE ERROR EN EL FINAL DEL CONTENIDO)

## <a name="version-2012-november-06"></a>Versión 2012: 6 de noviembre
*Versión 2012 (compilación 13430.20000)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Mostrar varias hojas de cálculo al mismo tiempo:** no es necesario que se muestren las hojas de una en una, ya que se pueden mostrar varias hojas ocultas al mismo tiempo. [Más información](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)

### <a name="outlook"></a>Outlook

- **Misma firma, todos los dispositivos:** su firma se almacena en la nube. Créelo una vez y úselo en cualquier lugar donde use Outlook.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Hemos corregido un problema en el que algunos elementos de la cinta de opciones no se localizaban en chino simplificado.


- Hemos corregido un problema en el que Excel se terminaba inesperadamente durante la actualización.


### <a name="outlook"></a>Outlook

- Hemos arreglado un problema en el que la adición de un archivo adjunto a un mensaje abierto desde un archivo zip fallaba.



[//]: # (NO QUITAR EL CONTENIDO FINAL DE LOS DETALLES DE LOS ERRORES)

## <a name="version-2011-october-30"></a>Versión 2011: 30 de octubre
*Versión 2011 (compilación 13426.20004)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Cuadros de diálogo de formato condicional mejorados:** Los diálogos de formato condicional ahora son de tamaño ajustable y se puede duplicar la regla con un solo clic. [Más información](https://support.office.com/article/fed60dfa-1d3f-4e13-9ecb-f1951ff89d7f)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Acceso

- Se ha corregido un problema que provocaba que, al utilizar DAO desde aplicaciones que no son de Office, la aplicación se cerrara de forma inesperada.


### <a name="excel"></a>Excel

- Se ha corregido un problema con Power Pivot cuando usa una conexión en una base de datos de Oracle.


- Se corrigió un problema por el que Excel terminó de forma inesperada cuando se activó el proceso de calcular MTR y la actualización de objetos de directiva de grupo (por ejemplo, a través de la actualización remota de la directiva de grupo).


- Este cambio corrige un error que provoca un error en Excel al intentar cargar un archivo atomsvc.


- Se corrigió un problema en el que parece que Word se bloquea al insertar un libro de Excel en un documento de Word.


### <a name="outlook"></a>Outlook

- Se ha corregido un problema por el que el propietario de un buzón no podía administrar el permiso compartido en su propio Calendario de Outlook, ya que la opción se había desactivado.


- Se ha corregido un problema por el cual al guardar las plantillas de correo electrónico como .OFT se cambiaban los caracteres chinos por signos de interrogación.


- Se ha corregido un problema por el cual Outlook no podía crear un mensaje con permisos restringidos.


- Resuelto un problema que hacía que Outlook dejara de funcionar esporádicamente al agregar o guardar datos adjuntos.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema por el cual las líneas de cuadrícula se desplazaban de las diapositivas al cerrar el panel diseño.


- Se ha corregido un problema por el que la barra de desplazamiento en la diapositiva comienza a ajustarse a sí misma después de detener la grabación de pantalla con el panel de selección abierto.


### <a name="project"></a>Project

- Se ha corregido un problema que provocaba que, al guardar un proyecto desde PWA en un archivo MPP local, ProjectBeforeTaskChangeEvent se desencadenara para datos no modificados por el usuario.


- Se ha corregido un problema en el que las negociaciones de recursos buscaban un recurso por nombre en lugar de un GUID lo que causaría problemas si hubiera varios recursos con el mismo nombre.


### <a name="word"></a>Word

- Se ha corregido un problema por el que al hacer clic en la sugerencia de comentario no se mostraba la tarjeta comentario en la vista.


- Se ha corregido un problema de diseño en el que la línea entre columnas podiía haber cambiado.


- Se corrigió un problema en el que parece que Word se bloquea al insertar un libro de Excel en un documento de Word.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema en la Herramienta de implementación de Office que provocaba errores en la configuración al usar la característica RemoveMSI con el producto de Office 2007 "Informes de errores de aplicaciones de Microsoft".



[//]: # (NO QUITAR DETALLES DE ERROR DEL FIN DE CONTENIDO)

## <a name="version-2011-october-23"></a>Versión 2011: 23 de octubre
*Versión 2011 (compilación 13415.20002)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="powerpoint"></a>PowerPoint

- **Ensaye su presentación con el asesor para moderadores:** obtenga comentarios sobre las cosas que ayuden a mantener a un público comprometido, como el ritmo, el tono, las palabras de relleno, las frases sensibles y más. [Más información](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Acceso

- Corregimos un problema por el que algunos usuarios veían el error "recurso del sistema excedido" al intentar exportar una consulta de su carpeta sincronizada de OneDrive.

- Corregimos un problema en el que el cambio automático entre las ventanas de la forma estaba cambiando a otra forma.

### <a name="outlook"></a>Outlook

- Corregimos un problema al pegar una dirección URL copiada desde la ubicación de la reunión a otro lugar (como un explorador), la dirección URL contiene un punto y coma al final.

### <a name="powerpoint"></a>PowerPoint

- Corregimos un problema al duplicar la presentación con diapositivas en un monitor secundario, la presentación puede ocultarse detrás de la otra ventana.

### <a name="project"></a>Proyecto

- Corregimos un problema por el que el Proyecto puede finalizar inesperadamente al abrir archivos en los que se especificaban los contornos de los recursos de una determinada manera.

### <a name="word"></a>Word

- Corregimos un problema en control de cambios que a veces es posible que abra un documento de Word.

- Corregimos un problema de impresión cuando se aplica la etiqueta de carácter con marcas de agua.


[//]: # (NO QUITAR EL CONTENIDO FINAL DE LOS DETALLES DE LOS ERRORES)

## <a name="version-2011-october-16"></a>Versión 2011: 16 de octubre
*Versión 2011 (compilación 13408.20000)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Compatibilidad con el portapapeles SVG:** ahora puede pegar contenido SVG de Office en aplicaciones de terceros. [Más información](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a>Outlook

- **Compatibilidad con el portapapeles SVG:** ahora puede pegar contenido SVG de Office en aplicaciones de terceros. [Más información](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a>PowerPoint

- **Compatibilidad con el portapapeles SVG:** ahora puede pegar contenido SVG de Office en aplicaciones de terceros. [Más información](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="word"></a>Word

- **Compatibilidad con el portapapeles SVG:** ahora puede pegar contenido SVG de Office en aplicaciones de terceros. [Más información](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha corregido un problema que impedía a los usuarios eliminar citas en el Calendario de Grupos de Microsoft 365 en autenticación básica.


- Se ha corregido un problema que producía errores en el inicio de Outlook durante la carga de la caché de sobrenombres.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema que provocaba que el icono del marcador de posición de contenido junto a Imágenes no incluyera información sobre herramientas.


- Se ha corregido un problema debido al cual la Vista protegida de presentación con diapositivas, mostrada en archivo PPTSX, permitía la captura de pantalla de documentos protegidos por IRM.



[//]: # (NO QUITAR DETALLES DE ERROR DEL FIN DE CONTENIDO)

## <a name="version-2011-october-09"></a>Versión 2011: 09 de octubre
*Versión 2011 (compilación 13406.20000)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Crear flujos de datos de Power Platform a partir de consultas:** ahora puede exportar sus consultas a plantillas de Power Query que se pueden usar para crear nuevos flujos de datos de Power Platform.

### <a name="powerpoint"></a>PowerPoint

- **Exportar GIF animado en un rango:** seleccione un intervalo de diapositivas cuando exporte a GIF animado

- **Crear GIF con fondos transparentes:** cuando se exporta a un GIF animado, una nueva opción permite que el fondo sea transparente.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema por el que el nombre de archivo no cambiaba después de una operación Guardar como con complementos COM habilitados.


- Se ha corregido un problema cuando se produce un error de Autoguardado con un mensaje de error incorrecto o engañoso cuando hay una definición de medida incorrecta en el modelo de datos de Excel.


- Se ha corregido un problema en el que al acercar y alejar el área de presentación se daba una separación entre el recuadro de selección ampliado y el puntero del mouse.


### <a name="outlook"></a>Outlook

- Se ha corregido un problema por el que la impresión rápida de los datos adjuntos de imagen provocaba un error “Windows no puede encontrar esta imagen. Compruebe la ubicación y vuelva a intentarlo”.


- Se ha corregido un problema que provocaba que algunos usuarios vieran que Outlook se iniciaba en un estado sin conexión hasta que optaban manualmente por trabajar en línea.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema que provocaba que, al acercar y alejar el área de presentación, apareciera una separación entre el recuadro de selección ampliado y el puntero del mouse.


### <a name="project"></a>Project

- Se ha corregido un problema por el que la NewVal en el evento ProjectBeforeTaskChagne no tiene el valor correcto si se cambia un retraso en una vista de tipo de formulario de tarea.


- Se ha corregido un problema que hace que si tiene una lista de tareas en un sitio de proyecto y agrupa la lista de tareas, no pueda editar rápidamente la lista de tareas.


- Se ha corregido un problema que hace que si actualiza un recurso de empresa a través del CSOM, puede perderse la capacidad máxima del recurso.


### <a name="word"></a>Word

- Se ha corregido un problema en el que al acercar y alejar el área de presentación se daba una separación entre el recuadro de selección ampliado y el puntero del mouse.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema por el que el inicio de sesión interactivo de la API de SSO devuelve un código de error.



[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO FINAL)

## <a name="version-2010-october-02"></a>Versión 2010: 02 de octubre
*Versión 2010 (Compilación 13328.20000)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Usar el cuadro de diálogo Opciones avanzadas para crear tipos de datos:** el cuadro de diálogo Opciones avanzadas le permite seleccionar manualmente las columnas que combinan el tipo de datos que está creando.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="onenote"></a>OneNote

- Se ha corregido un problema que impedía al usuario seleccionar y copiar la dirección URL del bloc de notas del cuadro de texto en un archivo de OutSpace > Información.


### <a name="outlook"></a>Outlook

- Corrige un problema que causaba el envío de los mensajes de correo electrónico generados automáticamente con el cuerpo del correo en blanco cuando el asunto estaba vacío.


- Se ha corregido un problema que provocaba que se almacenara en caché para carpetas el GUID de carpeta incorrecto.


- Cuando un usuario copia y pega una dirección de correo electrónico en el campo del destinatario con el nombre para mostrar, la dirección de correo electrónico no siempre se analizaba de forma correcta, y esto generaba que aparezca una advertencia sobre una dirección de correo electrónico no válida.  Se ha corregido y, por tanto, el nombre y la dirección de correo electrónico se analizan de forma correcta para que ya no se muestre la advertencia.


- Se ha corregido un problema que causaba que las carpetas compartidas en línea no devolvieran el nombre de la carpeta principal. En lugar de dar error, devolvía una ruta de acceso vacía que pasaba incorrectamente a la cuenta principal.


- Se ha corregido un problema que provocaba que se activara el control de cambios después de reabrir el borrador desde el panel de vista previa de solo lectura.


- Se ha corregido un problema que impedía que la opción Guardar como estuviera disponible para los datos adjuntos clásicos.


- Se ha corregido un problema para ofrecer a los usuarios una forma de personalizar el texto de justificación al anular una directiva.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema que impedía a PowerPoint exportar las viñetas rectangulares al exportar a PDF.


- Se ha corregido un problema debido al cual, si se encuentra en la última diapositiva y pasa a la siguiente diapositiva tras pulsar "Finalizar sesión" y antes de que aparezca el resumen, el cuadro de diálogo de sesión final también aparece visible en la página de resumen.


### <a name="project"></a>Project

- Se ha corregido un problema que podía hacer que Project se bloqueara si aplicaba un grupo en la Vista de hoja o de uso de recursos y, a continuación, insertaba una columna.


- Se ha corregido un problema debido al cual, si tiene campos personalizados con fórmulas que usan el valor acumulado, puede que observe que el rendimiento retrasa el cambio de vistas y la apertura de los detalles del proyecto/tarea.


- Se ha corregido un problema que puede hacer que el método VBA ConsolidateProjects produzca errores si se intenta agregar el mismo proyecto varias veces y AttachToSources está establecido en false.


- Se ha corregido un problema por el que si se ejecuta un código de evento y se intenta realizar cambios desde la vista del Formulario de tareas, es posible que el botón Aceptar no confirme los cambios.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2010-september-25"></a>Versión 2010: 25 de septiembre
*Versión 2010 (Compilación 13318.20000)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Crear tipos de datos con Power Query:** crear tipos de datos enriquecidos con Power Query desde cualquier origen de datos

### <a name="outlook"></a>Outlook

- **Actualizaciones de la experiencia de usuario en Tareas:** Una actualización visual de los elementos de las tareas

- **Ahorre tiempo mientras redacta mensajes:** Outlook le muestra sugerencias de escritura que le ayudarán a redactar mensajes de manera rápida. Para aceptar la sugerencia, solo tiene que usar la tecla TAB.

### <a name="word"></a>Word

- **El panel del Editor Microsoft recibe una actualización en la versión de escritorio de Word:** Hemos actualizado la experiencia actual con el panel del Editor para los clientes de escritorio de Word.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Se ha corregido un problema que provocaba que la posición de la barra de desplazamiento no se estableciera de manera correcta al cargar la ventana de consulta o relación guardada mientras se realizaba el desplazamiento.


- Se ha corregido un problema que provocaba que el panel de tareas de Agregar tabla no mostrara de manera correcta los nombres que contenían "&".


### <a name="excel"></a>Excel

- Se ha corregido un problema que provocaba que el intervalo manual de categoría multinivel no funcionara en los gráficos.


- Se ha corregido un problema que podía provocar un bloqueo al actualizar las tablas dinámicas de OLAP.


- Se ha corregido un problema que provocaba que no se actualizaran las opciones de todas las hojas del libro al agregar una tabla usada para la validación de datos.


### <a name="onenote"></a>OneNote

- Se ha corregido un problema que provocaba que OneNote no respetara los colores de contraste alto en el lienzo para temas personalizados.


- Se ha corregido un problema que provocaba que, al pasar el ratón sobre el color verde en el selector de colores del bloc de notas, el elemento emergente muestre "tiza roja".


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema que provocaba que el gráfico de Excel vinculado cambiara incorrectamente a la hoja de Excel cuando el usuario cambiaba la ruta de origen a la carpeta de OneDrive local.


### <a name="word"></a>Word

- Se ha corregido un problema que provocaba que los vínculos a los archivos habilitados de flujo de trabajo no se abrieran con normalidad.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2010-september-18"></a>Versión 2010:18 de septiembre
*Versión 2010 (compilación 13312.20006)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Revisar los mensajes con el editor:** Ahora puede obtener sugerencias de gramática y de estilo en los mensajes de correo electrónico de los usuarios de 64 bits de Outlook. Busque las palabras subrayadas para ver las sugerencias del editor para refinar su escritura.

- **Rompa la barrera del idioma con un traductor incorporado:** Los complementos para la traducción ya no son necesarios. En un mensaje, haga clic con el botón derecho para traducir palabras o frases específicas, o todo el mensaje.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema con los gráficos de mapas 2D que provocaba que el uso de VBA para establecer los colores de los valores max, mid y min para una serie no funcione.


- Se ha corregido un problema que aparecía cuando se configuraba el idioma de Office en español. Este problema provocaba que las listas de validación de datos puedan no mostrar todos los elementos de la lista.


- Se ha corregido un problema que podría provocar un error que indicaba que Excel se quedó sin recursos al intentar calcular una o varias fórmulas.


- Se ha corregido un problema que provocaba que ChartSheet se bloquee en ciertos casos cuando se insertaba una fórmula en la barra de fórmulas.


### <a name="outlook"></a>Outlook

- Cuando un usuario copia y pega una dirección de correo electrónico en el campo del destinatario con el nombre para mostrar, la dirección de correo electrónico no siempre se analizaba de forma correcta, y esto generaba que aparezca una advertencia sobre una dirección de correo electrónico no válida.  Se ha corregido y, por tanto, el nombre y la dirección de correo electrónico se analizan de forma correcta para que ya no se muestre la advertencia.


### <a name="word"></a>Word

- Se ha corregido un problema que provocaba que el hecho que un usuario seleccionara una marca de revisión (inserción o eliminación) mostrara un comentario emergente.


- Se ha corregido un problema al eliminar llamadas de comentario en Word.


- Se ha corregido un problema con Outlook al establecer un mensaje en No reenviar


- Se ha corregido un problema al guardar un documento de Word que contenía cita y ecuación.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2010-september-11"></a>Versión 2010: 11 de septiembre
*Versión 2010 (Compilación 13304.20000)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="access"></a>Acceso

- **Office puede seguir con la configuración de modo oscuro de Windows 10:** ¿Usa Windows 10 en modo oscuro? Ahora Office puede cambiar entre temas de modo que coincidan de manera automática: Solo seleccione "Usar configuración del sistema" como tema de Office.

### <a name="excel"></a>Excel

- **Office puede seguir con la configuración de modo oscuro de Windows 10:** ¿Usa Windows 10 en modo oscuro? Ahora Office puede cambiar entre temas de modo que coincidan de manera automática: Solo seleccione "Usar configuración del sistema" como tema de Office.

### <a name="onenote"></a>OneNote

- **Office puede seguir con la configuración de modo oscuro de Windows 10:** ¿Usa Windows 10 en modo oscuro? Ahora Office puede cambiar entre temas de modo que coincidan de manera automática: Solo seleccione "Usar configuración del sistema" como tema de Office.

### <a name="outlook"></a>Outlook

- **Office puede seguir con la configuración de modo oscuro de Windows 10:** ¿Usa Windows 10 en modo oscuro? Ahora Office puede cambiar entre temas de modo que coincidan de manera automática: Solo seleccione "Usar configuración del sistema" como tema de Office.

### <a name="powerpoint"></a>PowerPoint

- **Office puede seguir con la configuración de modo oscuro de Windows 10:** ¿Usa Windows 10 en modo oscuro? Ahora Office puede cambiar entre temas de modo que coincidan de manera automática: Solo seleccione "Usar configuración del sistema" como tema de Office.

### <a name="project"></a>Project

- **Office puede seguir con la configuración de modo oscuro de Windows 10:** ¿Usa Windows 10 en modo oscuro? Ahora Office puede cambiar entre temas de modo que coincidan de manera automática: Solo seleccione "Usar configuración del sistema" como tema de Office.

### <a name="publisher"></a>Publisher

- **Office puede seguir con la configuración de modo oscuro de Windows 10:** ¿Usa Windows 10 en modo oscuro? Ahora Office puede cambiar entre temas de modo que coincidan de manera automática: Solo seleccione "Usar configuración del sistema" como tema de Office.

### <a name="visio"></a>Visio

- **Office puede seguir con la configuración de modo oscuro de Windows 10:** ¿Usa Windows 10 en modo oscuro? Ahora Office puede cambiar entre temas de modo que coincidan de manera automática: Solo seleccione "Usar configuración del sistema" como tema de Office.

### <a name="word"></a>Word

- **Office puede seguir con la configuración de modo oscuro de Windows 10:** ¿Usa Windows 10 en modo oscuro? Ahora Office puede cambiar entre temas de modo que coincidan de manera automática: Solo seleccione "Usar configuración del sistema" como tema de Office.

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema que provocaba un retraso considerable al cambiar entre hojas de cálculo con grandes cantidades de datos cuando la 'Vista previa de salto de página' estaba habilitada.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que los correos electrónicos se ocultaran después de desactivar la Bandeja de entrada Prioritarios y ordenarlos.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema que provocaba que los GIF solo muestren la animación una vez en el editor y en las presentaciones.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2010-september-04"></a>Versión 2010: 04 de septiembre 
*Versión 2010 (Compilación 13301.20004)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Anclar correo electrónico:** esta característica permite a los usuarios realizar un seguimiento de los correos electrónicos a los que necesitan volver o tenerlos como recordatorio manteniéndolos en la parte superior de la lista de mensajes.

- **Reciba sugerencias de correo electrónico al buscar por persona:** a medida que escriba los términos de búsqueda en Outlook, recibirá los correos electrónicos más relevantes en las sugerencias.

- **Reciba sugerencias de correo electrónico al buscar por persona:** a medida que escriba los términos de búsqueda en Outlook, recibirá los correos electrónicos más relevantes en las sugerencias.

- **Microsoft Editor proporciona una actualización para los clientes de escritorio de Word y Outlook:** añadimos un nuevo modelo de revisión con un clic para las sugerencias de estilo, gramática y ortografía avanzada del Editor. Este cambio también incluye una nueva superficie de tarjeta dedicada para revisar las sugerencias.

### <a name="word"></a>Word

- **Microsoft Editor proporciona una actualización para los clientes de escritorio de Word y Outlook:** añadimos un nuevo modelo de revisión con un clic para las sugerencias de estilo, gramática y ortografía avanzada del Editor. Este cambio también incluye una nueva superficie de tarjeta dedicada para revisar las sugerencias.

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se corrigió un problema por el cual si abría un archivo que contiene la función LET, mostraba la alerta: "Encontramos un problema con el contenido en "su archivo.xlsx". ¿Quiere que intentemos recuperar todo lo que podamos? Si confía en el origen de este libro, haga clic en Sí".
- Se corrigió un bloqueo relacionado con las referencias de complementos XLAM y los rangos con nombre.
- Se corrigió un problema por el cual los usuarios no podían modificar un filtro de tabla dinámica porque estaba configurado en un valor que ya no estaba presente en una base de datos de Analysis Services.
- Se corrigió un problema por el que si un usuario aplicaba un estilo personalizado a una matriz dinámica, obtenía el error: "No se puede cambiar parte de una matriz". Se ha eliminado una restricción heredada.
- Se corrigió un problema por el cual la barra de fórmulas de Excel no se mostraba completamente después de que se perdiera la conexión a un dispositivo, como una conexión o desconexión de sesión remota o un cambio de monitor.

### <a name="outlook"></a>Outlook

- Se corrigió un problema que proporciona más flexibilidad para habilitar o deshabilitar las opciones de registro predeterminadas mediante la directiva de grupo.
- Se corrigió un problema por el que el nombre de dominio heredado de un remitente de correo electrónico se conservaba y mostraba después de que se moviera un borrador del correo electrónico entre buzones con permisos de asistente y permisos de administrador.
- Se corrigió un problema que hacía que algunos usuarios vieran que Outlook se iniciaba en un estado sin conexión hasta que optaban manualmente por trabajar en línea.
- Se corrigió un problema por el cual ejecutar el código VBA ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") después de habilitar Cinta de opciones de una línea (SLR) daba como resultado un error de tiempo de ejecución.
- Se corrigió un problema por el cual los botones 'Aceptar' y 'Cancelar' en el cuadro de diálogo Respuestas automáticas no eran visibles en un sistema con una resolución alta (como 1750 x 1920) combinada con un tamaño de texto grande (como 175 %).
- Se corrigió una condición por la que enviar una convocatoria de reunión desde un grupo de contactos vacío a otro grupo de contactos provocaba un bloqueo.
- Se corrigió un problema que provocaba que los usuarios experimentaran un bloqueo al abrir algunos correos electrónicos muy grandes.
- Se corrigió un problema por el que si la directiva de grupo requiere que un complemento esté siempre habilitado, los complementos de supervisión no están disponibles para evitar que los usuarios deshabiliten el complemento.

### <a name="powerpoint"></a>PowerPoint

- Se corrigió un problema por el que los vídeos no se reproducen automáticamente en las presentaciones.
- Se corrigió un problema por el cual, después de iniciar PowerPoint, insertar una diapositiva y abrir y cerrar el panel de comentarios, las diapositivas en el panel de miniaturas se mostraban superpuestas.

### <a name="project"></a>Project

- Se corrigió un problema por el cual si un recurso tiene varias tablas de tasas de coste, es posible que el coste restante no se calcule correctamente.
- Se corrigió un problema por el que la fecha de finalización de Project no se actualizaba para los proyectos conectados a la lista de tareas de SharePoint.

### <a name="word"></a>Word

- Se corrigió un problema por el cual la tarjeta de Comentarios mostraba un borde alrededor del texto del comentario si el usuario hacía clic en el comentario.
- Se corrigió un problema por el cual el foco no iba al panel de comentarios si el documento se ampliaba al 160 % o más y el panel de comentarios no estaba visible.
- Se corrigió un problema por el cual los comentarios de un documento se mostraban en otros documentos abiertos después de cambiar entre varios documentos abiertos.
- Se corrigió un problema por el cual si un usuario creaba un borrador de comentario anclado a una línea que ya contenía comentarios comprometidos, el borrador se organizaba en el orden incorrecto en relación con el comentario comprometido en SideTrack.
- Se corrigió un problema por el cual los vínculos largos no se ajustaban al guardar un documento en formato HTML.
- Se corrigió un problema con las macros en las que AutoOpen se ejecuta antes de AutoExec.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2009-august-28"></a>Versión 2009: 28 de agosto
*Versión 2009 (compilación 13219.20004)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Resuelve un problema debido al cual los usuarios podían enviar contenido de correo electrónico que incluía una directiva de "No reenviar" aplicada a OneNote al seleccionar más de un mensaje.

### <a name="powerpoint"></a>PowerPoint

- Hemos corregido un problema que deshabilitaba la funcionalidad para insertar un vídeo.

### <a name="word"></a>Word

- Hemos corregido un problema que impedía al usuario salir del encabezado o pie de página al seleccionar un comentario.
- Hemos corregido un problema que impedía a los usuarios ver los hilos de comentarios que superaran el límite de la barra de los comentarios, porque el desplazamiento por dicha barra no funcionaba.
- Hemos corregido un problema que impedía la búsqueda de comentarios resueltos en el panel de los comentarios.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema en la Herramienta de implementación de Office que provocaba errores en la configuración al usar la característica RemoveMSI con el producto de Office 2007 "Informes de errores de aplicaciones de Microsoft".
- Se ha corregido un problema en el cuadro de diálogo Comprimir imágenes que impedía que se conservaran algunas opciones de configuración de PPP seleccionadas por el usuario.

[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)

## <a name="version-2009-august-21"></a>Versión 2009: 21 de agosto
*Versión 2009 (Compilación 13212.20000)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Lápiz de acción en Excel:** herramienta bolígrafo que le ayudará a escribir a mano y realizar cambios rápidos en los datos

### <a name="outlook"></a>Outlook

- **Eliminar conversación por propietario del mensaje:** esta característica permite eliminar una conversación por propietario del mensaje.

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Se ha corregido un problema por el que las conexiones a una base de datos ODBC no funcionaban con aplicaciones de terceros.

### <a name="excel"></a>Excel

- Se ha corregido un problema por el que, al usar una macro para establecer la propiedad FormulaR1C1 para un rango, las referencias de celda eran incorrectas si una hoja de gráfico era la hoja activa.
- Se ha corregido un problema por el que las entradas manuscritas podrían hacer que Excel dejara de responder.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema por el que los usuarios ahora pueden deshabilitar IRM (Information Rights Management) para Outlook sin tener que deshabilitarlo para el resto de las aplicaciones de Office.

### <a name="word"></a>Word

- Se ha corregido un problema en el que Word se podía bloquear después de eliminar comentarios.
- Se ha corregido un problema en el que, en algunos casos, las viñetas no se mostraban correctamente en el correo electrónico.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2009-august-14"></a>Versión 2009: 14 de agosto
*Versión 2009 (Compilación 13205.20000)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Hemos corregido un problema en el que si un usuario escribía el nombre de una fórmula, incluidos los paréntesis, e invocaba ayuda a través de F1, el tema de ayuda específico de esa fórmula no se mostraba.
- Se ha corregido un problema en el que los macros asignados a los botones no funcionaban después de restaurar una versión anterior del archivo.

### <a name="outlook"></a>Outlook

- Este cambio corrige un problema que hace que la página de Reunión continuara mostrándose después de que el usuario había cambiado de pestaña desde la página Reunión a la página del Asistente para programación.

### <a name="word"></a>Word

- Hemos corregido un problema en el que el icono de la imagen de viñeta no se mostraba correctamente.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2009-august-07"></a>Versión 2009: 07 de agosto
*Versión 2009 (compilación 13130.20000)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que los atributos de la cuenta de usuario de Active Directory para "otherTelephone" y "otherHomePhone" no se asignaran a los atributos LDAP correspondientes de Outlook.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema que provocaba que los usuarios no pudieran ver la barra de herramientas o de título en ciertas condiciones.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2008-july-31"></a>Versión 2008: 31 de julio
*Versión 2008 (Compilación 13127.20002)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Inserte las fotos de su iPhone directamente en Office:** las imágenes HEIC de su teléfono ahora se insertan sin problemas en Office. No es necesario realizar ninguna conversión.<br />Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)

### <a name="outlook"></a>Outlook

- **Inserte las fotos de su iPhone directamente en Office:** las imágenes HEIC de su teléfono ahora se insertan sin problemas en Office. No es necesario realizar ninguna conversión.<br />Ver detalles en [entrada de blog](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)

### <a name="powerpoint"></a>PowerPoint

- **Inserte las fotos de su iPhone directamente en Office:** las imágenes HEIC de su teléfono ahora se insertan sin problemas en Office. No es necesario realizar ninguna conversión.<br />Ver detalles en [entrada de blog](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)

### <a name="word"></a>Word

- **Inserte las fotos de su iPhone directamente en Office:** las imágenes HEIC de su teléfono ahora se insertan sin problemas en Office. No es necesario realizar ninguna conversión.<br />Ver detalles en [entrada de blog](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Esta corrección resuelve el problema en el que al intentar ejecutar determinadas consultas anteriormente se generaba el mensaje de error "La consulta es demasiado compleja".

### <a name="excel"></a>Excel

- Se ha corregido un problema por el que si se cambia el orden de una serie de gráficos, la casilla de verificación correspondiente alineada con la serie no se reordenaba junto con la serie.
- Se ha corregido un problema por el que una copia de una imagen con un relleno degradado radial no coincidía con el original.

### <a name="outlook"></a>Outlook

- Esta corrección aborda un problema que hacía que los usuarios no pudieran agregar una firma al responder a un mensaje administrado con derechos digitales desde una ventana de inspección cuando el usuario no tenía permisos de propietario sobre el mensaje al que se respondía.
- La corrección aborda un problema que provocaba que Outlook no mostrara correctamente los saltos de línea en el contenido de Markdown.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema por el que una copia de una imagen con un relleno degradado radial no coincidía con el original.
- Se ha corregido un problema por el que el botón Formularios de PowerPoint no permitía la creación de formularios cuando no se permitía el acceso a la Tienda Office.

### <a name="project"></a>Project

- Se ha corregido un problema por el que en una lista de tareas de SharePoint, los botones de la cinta de opciones en la segunda pestaña se podían deshabilitar.

### <a name="word"></a>Word

- Se ha corregido un problema por el que una copia de una imagen con un relleno degradado radial no coincidía con el original.
- Se ha corregido un problema que hacía que si se agregaba un comentario para realizar el seguimiento de un cambio, el panel de revisiones se abría de forma inesperada.
- Se ha corregido un problema en el que los vínculos a los documentos no se insertaban en el cuadro de comentarios a través de la lista desplegable Insertar > Vínculo.
- Se ha corregido un problema por el que el recuento de hipervínculos en la colección de hipervínculos de VBA no realizaba correctamente la iteración después de agregar una imagen que contenía un hipervínculo.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2008-july-24"></a>Versión 2008: 24 de julio
*Versión 2008 (compilación 13117.20000)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Cree diagramas de Visio elegantes en Excel:** cree un diagrama de flujo o un organigrama con solo escribir datos en una hoja de cálculo. [Más información](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="onenote"></a>OneNote

- Se ha corregido un problema que provocaba que el texto de marcador de posición en el cuadro de edición de búsqueda se desbordase si se reducía el tamaño de la ventana de la aplicación.

### <a name="word"></a>Word

- Se ha corregido un problema que provocaba que el texto de marcador de posición en el cuadro de edición de búsqueda se desbordase si se reducía el tamaño de la ventana de la aplicación.
- Se ha corregido un problema que provocaba la deshabilitación de la opción de "Personas específicas" de Control de cambios.
- Se ha corregido un bloqueo ocasional al abrir archivos HTML.

[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)

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
- Se ha corregido un problema que provocaba que los usuarios vieran el siguiente error al cerrar una cita guardada previamente: "No se puede guardar el elemento porque otro usuario lo modificó o se modificó en otra ventana. ¿Quiere realizar una copia en la carpeta predeterminada del elemento?".
- Se ha corregido un problema por el que las fechas del minicalendario no se podían mostrar en negrita para los usuarios de Japón.
- Se ha corregido un problema que impedía que los avisos del calendario mostraran la hora exacta de las reuniones programadas para tener lugar en menos de una semana.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema por el que el indicador de color de presencia de un usuario no se actualizaba en la galería de coautoría durante una sesión de coautoría en directo.

### <a name="project"></a>Project

- Se ha corregido un problema por el que, si las tareas de duración fija estaban completas al 100 %, pero no se especificaba la fecha de finalización real, el porcentaje de finalización de la tarea se mostraba como inferior al 100 %.

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

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

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

- **Crear tablas dinámicas de conjuntos de datos en Power BI en Excel:** puede crear tablas dinámicas en Excel conectadas a los conjuntos de datos almacenados en Power BI con tan solo unos clics. Así, podrá obtener lo mejor de las tablas dinámicas y de Power BI. Calcule, resuma y analice sus datos con tablas dinámicas desde sus conjuntos de datos seguros de Power BI. [Más información](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

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


## <a name="version-2006-may-29"></a>Versión 2006: 29 de mayo
*Versión 2006 (compilación 12920.20000)*

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Se agregaron más botones a las notificaciones del sistema de Outlook:** los botones de Acción rápida aparecen ahora en las notificaciones del sistema de Outlook cuando se ejecuta Outlook en Windows 10.

### <a name="powerpoint"></a>PowerPoint

- **Rendimiento mejorado de vídeos de Stream en PowerPoint:** hemos realizado mejoras en el rendimiento de la reproducción de los vídeos de Microsoft Stream para minimizar el tiempo de carga de vídeo y lograr una visualización más fluida.  Utilice sus vídeos corporativos de Microsoft Stream para crear presentaciones mejoradas.

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos

### <a name="excel"></a>Excel

- Se ha corregido un problema por el que Excel se cerraba ocasionalmente al utilizar OneDrive.
- Se ha corregido un problema que provocaba que, al hacer clic en un hipervínculo marcado en el propio libro, se ocultara dicho libro.
- Se ha corregido un problema por el que algunos vínculos de un gráfico copiado y pegado usaban direcciones de unidad asignadas, en lugar de direcciones universales.
- Se ha corregido un problema por el que Excel podía dejar de responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema que hacía que las diapositivas no quedaran centradas después de usar la rueda del mouse para hacer zoom.

### <a name="word"></a>Word

- Se ha corregido un problema por el que no se mostraban los textos copiados y pegados en un panel de comentarios.
- Se ha corregido un problema debido al cual las burbujas de sugerencias de comentarios aparecían borrosas al 100 % de zoom.
- Se ha corregido un problema que causaba errores en ciertos casos de coautoría al habilitar la directiva de Word 2007 y, después, las plantillas y documentos binarios.
- Se ha corregido un problema por el que no se abrían los archivos con nombres de ruta largos (mayores que 32 000 caracteres) y no se mostraba un mensaje de error adecuado.

[//]: # (NO QUITAR EL CONTENIDO FINAL DE LOS DETALLES DE LOS ERRORES)


## <a name="version-2006-may-22"></a>Versión 2006: 22 de mayo
*Versión 2006 (compilación 12914.20000)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Guardar en carpetas fijadas:** anclar las carpetas facilita el almacenamiento de archivos de Office. Recibimos un comentario en el que se nos informa de que los usuarios desean tener más control sobre las carpetas disponibles al guardar un archivo nuevo. Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar. Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil.<br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

### <a name="powerpoint"></a>PowerPoint

- **Guardar en carpetas fijadas:** anclar las carpetas facilita el almacenamiento de archivos de Office. Recibimos un comentario en el que se nos informa de que los usuarios desean tener más control sobre las carpetas disponibles al guardar un archivo nuevo. Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar. Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil.<br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

### <a name="word"></a>Word

- **Guardar en carpetas fijadas:** anclar las carpetas facilita el almacenamiento de archivos de Office. Recibimos un comentario en el que se nos informa de que los usuarios desean tener más control sobre las carpetas disponibles al guardar un archivo nuevo. Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar. Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil.<br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

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

- **Aplicar automáticamente o recomendar etiquetas de confidencialidad:** Office puede recomendar o aplicar automáticamente una etiqueta de confidencialidad basada en el contenido confidencial detectado.

### <a name="outlook"></a>Outlook

- **Encuentre lo que necesita:** Reducir la búsqueda con opciones como carpetas, remitente, fecha, información de datos adjuntos y más.

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

- **Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos ahora son más elegantes. [Más información](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01).

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
- Al habilitar la opción "Mostrar marcadores" no se mostraban los marcadores. Este error se ha corregido.
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

- **Mantenga la fidelidad de sus imágenes cuando las envíe como parte de un correo electrónico:** una nueva configuración de Outlook está disponible para limitar la compresión de imágenes cuando envía imágenes como parte de contenido del correo electrónico

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

- **Nueva opción para desactivar la mención de sugerencias al escribir el correo:**¿Encuentra el selector de @ menciones más molesto que útil? Ahora puede apagarlo si lo prefiere.

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
- **Etiquetas de confidencialidad**: ahora puede aplicar una etiqueta de confidencialidad que la organización ha configurado para pedirle permisos personalizados. [Más información](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a>PowerPoint
- **Etiquetas de confidencialidad**: ahora puede aplicar una etiqueta de confidencialidad que la organización ha configurado para pedirle permisos personalizados. [Más información](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a>Word
- **Etiquetas de confidencialidad**: ahora puede aplicar una etiqueta de confidencialidad que la organización ha configurado para pedirle permisos personalizados. [Más información](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

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
- Durante una sesión de coautoría de documentos activos, puede que agregar una imagen directamente en una tarjeta de comentario dé como resultado la adición de una etiqueta. Este problema se ha corregido.

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
### <a name="access"></a>Acceso

- Esta actualización corrige un problema por el que al usar un objeto ADODB. Recorder en código de VB podía notificarse un error incorrectamente.

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
[//]: # (|Win32|DevMain|Insiders| |16.0.14117.20000|version-2106-may-21|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14107.20000|version-2106-may-14|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14029.20000|version-2106-may-07|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14026.20000|version-2105-april-30|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14014.20002|version-2105-april-23|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14007.20002|version-2105-april-16|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14002.20000|version-2105-april-09|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13929.20016|version-2104-april-02|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13919.20002|version-2104-march-26|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13913.20000|versión-2104-marzo-19|)
[//]: # (NO MODIFICAR EL FIN DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)
