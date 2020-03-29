---
title: Notas de la versión de Office para participantes de Office Insider
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 'Proporciona a los participantes del modo anticipado de Insider la lista más reciente de las nuevas características, correcciones o problemas conocidos principales '
ms.openlocfilehash: 82db5c6be4e891c0d2a50532605409d296b6d571
ms.sourcegitcommit: 973f5df717e5ed982ac91d5cc66bef6207618405
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 03/27/2020
ms.locfileid: "43028261"
---
# <a name="release-notes-for-office-insiders"></a>Notas de la versión de Office para participantes de Office Insider

En este artículo hay notas de la versión para las compilaciones de Insider de las versiones de escritorio de Word, Excel, PowerPoint, Outlook, Access y Project para Windows. Todas las semanas se incluyen las nuevas características, correcciones importantes y los problemas principales de mayor interés para usted. Tenga en cuenta que a menudo se implementan características (o incluso correcciones) durante un período de tiempo para los participantes de Insider. Esto nos permite asegurarnos de que todo funciona correctamente antes de publicar la característica para un público más amplio. Por lo tanto, si ve que no dispone de algo de lo que se describe a continuación, no se preocupe, lo obtendrá en algún momento.  

> [!NOTE]
> - Las notas de publicación se publican semanalmente y pueden ser una compilación de varias versiones.
> - La fecha de publicación de las notas de versión pueden no coincidir con la fecha real de lanzamiento de la compilación.
> - Microsoft Teams en instalaciones existentes de Office 365 ProPlus: a partir de finales de junio, Microsoft Teams se incluirá en instalaciones existentes de Office 365 ProPlus (y Office 365 Empresa) a la hora de actualizar dichas instalaciones. La fecha en la que se agregará Teams depende del canal de actualización que use. Para obtener más información, vea [Implementar Microsoft Teams con Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install).

[//]: # (NO ELIMINAR)

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

- **Notificación de incidentes para administradores de TI:** se notificará a los administradores globales de espacios empresariales de Microsoft 365 y a los administradores de aplicaciones de Office acerca de los incidentes de Outlook y Exchange de O365 que afectan a sus usuarios con una nueva notificación en el panel derecho en Outlook para Windows.

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

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-january-31"></a>Versión 2002: 31 de enero
*Versión 2002 (compilación 12513.20010)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Lea y responda sobre la marcha: **responda a los comentarios y las menciones directamente desde el correo electrónico sin abrir el libro.

- **Perfiles de datos en el editor de consultas:** analice rápidamente los datos de las columnas, identifique errores y valores vacíos, vea histogramas de distribución y mucho más.

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha corregido un problema por el que los mensajes de correo electrónico que expiraban en función de una directiva de retención mostraban dos etiquetas. Una mostraba que el correo expiraba en un día y otra que expiraba en dos días.

### <a name="word"></a>Word

- Se ha corregido un problema por el que la sugerencia de comentario no se veía en el modo lectura con el color de página &quot;invertido&quot;.

- Se ha corregido un problema por el que el formato de cursiva se perdía después de editar un comentario, ponerlo en cursiva y, después, publicarlo.

- Se ha corregido un problema por el que los comandos de comentario (Modificar comentario, Responder a comentario, Eliminar comentario, Resolver comentario) en el menú contextual de comentarios no se mostraban.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-january-17"></a>Versión 2002: 17 de enero
*Versión 2002 (compilación 12508.20000)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="word"></a>Word

- **Correos electrónicos de notificación de menciones y comentarios ahora incluyen vistas previas:** las notificaciones por correo electrónico de menciones y comentarios incluirán ahora vistas previas del texto del comentario y del contexto de lo al que hace referencia.

[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- En algunos casos, el Comprobador de accesibilidad no mostraba las recomendaciones para las formas.

### <a name="outlook"></a>Outlook

- Las carpetas guardadas en "favoritos" en el panel de navegación izquierdo podían desaparecer de forma esporádica.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema por el que la entrada de lápiz no se procesaba por completo u se omitía al usarla en una animación de entrada de lápiz de PowerPoint.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2001-january-10"></a>Versión 2001: 10 de enero
*Versión 2001 (compilación 12430.20000)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel
- **Guarde formas como imágenes:** con tan solo unos pocos clics, guarde una forma, icono u otro objeto como archivo de imagen para que pueda volver a usarlo en otro lugar. [Más información](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

### <a name="outlook"></a>Outlook
- **Ahora, el usuario puede guardar objetos en Word/Excel/Outlook como una imagen para Windows:** con la capacidad ya observada en PowerPoint, los usuarios ahora pueden guardar objetos en Word, Excel y Outlook como una imagen. Entre los objetos se incluyen formas, iconos, imágenes ¡y mucho más! Se puede acceder a él a través del menú contextual.

### <a name="word"></a>Word
- **Seleccione fácilmente entradas de lápiz en Word dibujando una forma alrededor:** la herramienta Lasso en la pestaña Dibujar le ayuda a seleccionar objetos dibujados a mano. Seleccione trazos individuales o palabras completas. Es útil cuando tiene una gran cantidad de trazos y solo desea trabajar con algunos de ellos. [Más información](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **Guarde formas como imágenes:** con tan solo unos pocos clics, guarde una forma, icono u otro objeto como archivo de imagen para que pueda volver a usarlo en otro lugar. [Más información](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="onenote"></a>OneNote
- Las pestañas de la página pueden parecer demasiado pequeñas y juntas en una resolución al 100%.

### <a name="word"></a>Word
- En un conjunto de comentarios amplio, al eliminar un comentario cerca del final de la lista de comentarios, es posible que el panel se desplace hasta la parte superior.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2001-january-03"></a>Versión 2001: 03 de enero
*Versión 2001 (compilación 12425.20000)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos

### <a name="excel"></a>Excel
- Es posible que algunas líneas de borde no se impriman como se espera en papel de tamaño A4.
- Agregar una imagen al encabezado o pie de página de un objeto de gráfico en una hoja con VBA puede provocar un error.
- Al dar formato a un eje del gráfico, el intervalo entre las etiquetas estaba limitado a 255.
- Se ha corregido un problema que ocurría al intentar actualizar una consulta XML en la que se había acortado la dirección URL del origen de datos.
- Las estadísticas del libro notificaban un recuento de macros de todos los libros abiertos, incluido el libro de macros personal.

### <a name="outlook"></a>Outlook
- Cambiar carpetas puede dar lugar a una breve luz blanca en la lista de correo y en la vista previa del correo. Este comportamiento se nota más en el modo oscuro.

### <a name="powerpoint"></a>PowerPoint
- Se ha corregido un problema con el modelo de objetos por el que al llamar al método Shape.Paste la forma pegada recibía el foco.&nbsp;
- Se ha mejorado un escenario de copiado y pegado:&nbsp;Copiar mediante programación una forma de una diapositiva de PowerPoint y pegarla en otra diapositiva en un bucle podía producir un error de excepción.&nbsp;
- La animación en la sección encabezados de diapositivas no se representaba correctamente después de contraer y expandir los encabezados de sección.

### <a name="project"></a>Project
- Se ha corregido un problema por el que el ajuste de texto no funcionaba en las vistas de tareas y de uso de recursos.
- Se ha corregido un problema por el que si un recurso tiene más de una tasa de coste, el valor de coste en las tareas podía no ser correcto.

### <a name="word"></a>Word
- Si se insertaba un control (como un control de contenido de texto) en una ecuación, al guardar y abrir el archivo se producía un error de contenido ilegible.
- Al agregar un comentario con Word Online en coautoría, este podía no aparecer en el escritorio de Word.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office
- Se ha quitado una fecha de expiración incorrecta de la licencia válida al intentar cambiar la licencia solo con una licencia.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2001-december-13"></a>Versión 2001: 13 de diciembre
*Versión 2001 (Compilación 12410.20000)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Arrastre el correo electrónico a un grupo de tu propiedad:** Mueva y copie mensajes y conversaciones arrastrándolos desde su bandeja de entrada. Los mensajes que arrastres serán compartidos con todos los miembros del grupo.

[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access
- La ejecución de una consulta de unión que hace referencia a una(s) tabla(s) ODBC enlazada(s) y que contiene una cláusula de Ordenar por que bloquea el acceso de 64 bits.
- La suma de los datos de las consultas sindicales en Access (O365) puede resultar en el truncamiento de los datos decimales.
- Las interfaces COM para ACE no están expuestas para su uso fuera de las aplicaciones de Office.

### <a name="excel"></a>Excel
- Al insertar un modelo 3D (animado o estático) e intentar el "Guardar como imagen" no funciona.
- La tecla corta (Alt+Ctrl + 7/8) para lanzar la retroalimentación desde el backstage está en conflicto con los teclados AZERTY (Alt-Gr + 7/8). Impacto: los usuarios puede+ que no sean capaces de utilizar algunos caracteres como: "\'.

### <a name="outlook"></a>Outlook
- Resuelve un problema que provocó que el correo electrónico se enviara a la dirección incorrecta del destinatario.
- Resuelve un problema que hizo que Outlook permitiera incorrectamente a los usuarios con acceso de &quot;lectura&quot; a un buzón de correo cambiar el estado de lectura/no lectura de un mensaje.
- La revocación del certificado de seguridad en el sitio web no es producible por el Soporte de producto. Es necesario añadir el registro para ayudar a solucionar el problema.
- Resuelve un problema que hizo que los usuarios vieran fallos de sincronización.

### <a name="powerpoint"></a>PowerPoint
- Al insertar un modelo 3D (animado o estático) e intentar el "Guardar como imagen" no funciona.

### <a name="project"></a>Project
- El trabajo de tareas no se calcula en la distribución de resumen para tareas secundarias programadas manualmente.
- Es posible que el código VBA de Project invocado desde un botón de la cinta no funcione cuando se intente guardar proyectos basados en el servidor.
- A menos que Project ya se esté ejecutando, al abrir Archivos de Project desde una biblioteca de documentos de SharePoint se mostrará un error y el archivo no se abrirá.

### <a name="word"></a>Word
- Es posible que la función de guardar archivos existentes no funcione.
- El uso de las teclas de flecha en la ventana del editor de ortografía y gramática puede provocar parpadeos intermitentes.
- Al resolver un seguimiento, es posible que los comentarios asociados no se conviertan en comentarios puntuales.
- Al insertar un modelo 3D (animado o estático) e intentar el "Guardar como imagen" no funciona.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office
- Se ha solucionado un problema por el que los mensajes de actualización de Office aparecían en un idioma diferente al esperado. En el futuro, los mensajes de actualización de Office coincidirán correctamente con el idioma de visualización de Windows.

[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1912-december-06"></a>Versión 1912: 6 de diciembre 
*Versión 1912 (compilación 12325.20012)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Configuración avanzada del correo electrónico del grupo:** Esta característica ayuda a los usuarios del grupo a personalizar qué mensajes o eventos recibirán o seguirán en la bandeja de entrada.

- **Directiva de nomenclatura de grupos:** las directivas de nomenclatura de grupo permiten al administrador de TI normalizar y administrar los nombres de los grupos creados por usuarios de la organización. El administrador puede requerir que se añada un prefijo o sufijo concreto al nombre de un grupo cuando se crea y puede bloquear el uso de determinadas palabras. Esto ayuda a minimizar el uso de palabras inadecuadas en los nombres de grupo, y permite que el administrador de TI gestione la representación de los grupos en el directorio. La Directiva de nomenclatura también ayuda a las organizaciones que implementan sitios de grupo a organizarse en base al departamento.

### <a name="office-suite"></a>Conjunto de programas de Office

- **Paneles con pestañas:** ahora puede cambiar entre varios paneles con la pestaña situada en la parte derecha de la aplicación. Esta interfaz de usuario solo será visible cuando haya dos o más paneles abiertos.

[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel
- Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.
- Es posible que los usuarios vean un error si acceden a un rango con nombre oculto.
- Deshabilitar la aceleración de gráficos de hardware con resolución 4K puede causar que se retrase el renderizado de celdas al desplazarse por ellas.
- También es posible que se vean los bordes de una celda cuando borre fórmulas que, por su longitud, sobrepasen el límite de la celda.
- Se ha resuelto un problema en el que no se cargaba la personalización de cinta de opciones al abrir un libro insertado.
- El margen del menú desplegable puede no renderizarse correctamente.

### <a name="onenote"></a>OneNote
- Es posible que OneNote no se abra con el complemento de Outlook "Notas de la reunión".

### <a name="outlook"></a>Outlook
- Las etiquetas de directivas de retención pueden mostrar el período de tiempo de retención entre paréntesis.
- Es posible que aparezcan espacios en blanco en las Tarjetas de contacto con el paquete de idioma japonés.
- En ocasiones, las imágenes insertadas en mensajes de correo electrónico de Outlook pueden cambiar de tamaño.

### <a name="powerpoint"></a>PowerPoint
- Si un usuario tiene dos o más vídeos diferentes en una diapositiva en un archivo de la nube, las imágenes de vídeo se procesan correctamente, pero cuando el usuario hace clic en cada una de ellas para reproducirlas, el contenido de vídeo es siempre el mismo.
- En algunos casos, no funciona el desplazamiento con los dispositivos táctiles.
- El margen del menú desplegable puede no renderizarse correctamente.
- Los vínculos seguros de una aplicación de Office a otra pueden no iniciar la aplicación vinculada.

### <a name="project"></a>Project
- Project puede bloquearse cuando se usa la función Comparar proyectos.
- Si se encuentra en el Modo oscuro, al ir al panel del inspector de tareas en una tarea con un exceso de asignación de recursos, no podrá leer la tabla.
- Establecer el esfuerzo para las tareas que no tienen asignaciones se redondea a 1 día.

### <a name="word"></a>Word
- Guardar un archivo después de una combinación de correspondencia puede no funcionar en determinadas condiciones.
- Es posible que el Organizador de bloques de creación muestre una alerta no válida: &quot;Modificó estilos, bloques de creación&quot;.
- En ocasiones, el panel de comentarios se carga cuando se usa copiar o pegar.
- En ocasiones, los comentarios no se pegan en el orden correcto.
- Aplicar una plantilla que consista en una lista multinivel con estilos personalizados para los documentos existentes quizás no mantenga el estilo en determinadas condiciones.
- Cambiar el tamaño del borde de la pantalla dividida puede incluir una pantalla dividida adicional.
- Es posible que el menú desplegable de Margen no se muestre correctamente.
- Es posible que al mencionar a un usuario en una tarjeta de comentario se muestre un JSON.
- Los vínculos seguros de una aplicación de Office a otra pueden no iniciar la aplicación vinculada.

### <a name="office-suite"></a>Conjunto de programas de Office
- Para los productos basados en japonés, el nombre y apellidos del usuario de la cuenta pueden aparecer en el orden incorrecto.
- Al colocar el puntero del ratón sobre los comentarios, se puede mostrar un contorno de cuadro de texto alrededor del comentario.

[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1912-november-15"></a>Versión 1912: 15 de noviembre
*Versión 1912 (compilación 12307.20000)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="insights-services"></a>Servicios de información
- **Consultas en lenguaje natural en Ideas en Excel:** la nueva capacidad de ideas de Excel para hacer una pregunta en lenguaje natural sobre sus datos.

[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel
- La funcionalidad de texto a columna puede fallar en algunas localizaciones.
- Editar fórmulas de matrices dinámicas dentro de una celda puede resultar en que el texto se alinee fuera del límite de la celda.

### <a name="outlook"></a>Outlook
- Añadida la posibilidad de aplicar la configuración S/MIME a través de la directiva de grupo.
- Las imágenes incrustadas pueden parecer más pequeñas de lo esperado.

### <a name="powerpoint"></a>PowerPoint
- El cursor puede desaparecer después de mover el foco del texto.

### <a name="project"></a>Project
- Los usuarios pueden experimentar un error con respecto a la licencia.
- El botón Hoy en el selector de fecha a veces puede establecer una fecha incorrecta.

### <a name="word"></a>Word
- A veces al hacer clic con el botón derecho del ratón no se puede seleccionar la palabra completa.
- El cursor puede permanecer activo dentro de un objeto después de convertirlo a un formato sugerido.
- Las imágenes de los mensajes pueden tener una escala incorrecta en algunos escenarios.
- Algunos temas pueden dificultar la determinación del comentario seleccionado.
- La selección de una sugerencia de comentario debería mostrar ahora el panel de comentarios modernos cuando esté oculto en el conmutador de paneles.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office
- Responder a un comentario puede hacer que el cuadro de texto se expanda verticalmente más allá del borde del panel.

[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1912-november-08"></a>Versión 1912: 08 de noviembre
*Versión 1912 (compilación 12231.20000)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="user-lifecycle"></a>Ciclo de vida del usuario
- **Experimente mejoras para la activación de AFO:** Actualizaciones que los clientes ven en sus pantallas cuando activan el Office que viene con su nueva PC.

### <a name="word"></a>Word
- **Nueva y mejorada experiencia de vídeo online en Word:** Nueva y más segura experiencia de vídeo en línea para ayudarle a insertar nuevos vídeos y reproducir vídeos existentes en Word.

[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook
- Accidente intermitente con contenido de carpetas cruzadas.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office
- Al pegar un gráfico de Excel a PowerPoint este puede reducir su tamaño.

[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1911-november-01"></a>Versión 1911: 01 de noviembre
*Versión 1911 (compilación 12228.20020)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel
- **¡Traiga el contexto junto con sus objetos SVG!:** ahora puede conservar el texto en mapas, gráficos y otros vectores SVG al convertir estos objetos en Office.

- **Vea las opciones de pluma al seleccionar el Lápiz para Surface**: cuando elija el Lápiz de Surface por primera vez en Word, Excel o PowerPoint, la pestaña Dibujar se activará para que sea fácil seleccionar los colores de pluma.

### <a name="powerpoint"></a>PowerPoint
- **¡Traiga el contexto junto con sus objetos SVG!:** ahora puede conservar el texto en mapas, gráficos y otros vectores SVG al convertir estos objetos en Office.

- **Vea las opciones de pluma al seleccionar el Lápiz para Surface**: cuando elija el Lápiz de Surface por primera vez en Word, Excel o PowerPoint, la pestaña Dibujar se activará para que sea fácil seleccionar los colores de pluma.

### <a name="visio"></a>Visio
- ** Haga diagramas de Visio pulidos en Excel:** Visualice rápida y fácilmente sus datos en diagramas Visio pulidos dentro de Excel. [Más información](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).

### <a name="word"></a>Word
- **Vea las opciones de pluma al seleccionar el Lápiz para Surface**: cuando elija el Lápiz de Surface por primera vez en Word, Excel o PowerPoint, la pestaña Dibujar se activará para que sea fácil seleccionar los colores de pluma.

- **Mejoras en la coautoría:** Mejoró la experiencia de coautoría al hacer más probable que los cambios de contenido sean recibidos por otros en tiempo real.

- **Otros usuarios verán los cambios rápidamente**: con las mejoras en la coautoría, los colaboradores podrán ver los cambios más rápido que nunca.

[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel
- Resuelto un problema por el que Excel podía fallar al editar un archivo protegido desde una red compartida no fiable.
- Se ha resuelto un problema por el que, al eliminar hojas que contenían minigráficos que hacían referencia a datos en otra hoja, podía provocar que el archivo se identificara como dañado al volver a abrirlo.
- Se ha resuelto un problema por el que se podían obtener resultados incorrectos al convertir los filtros de un informe junto con el resto de la tabla dinámica de consultas enviadas a servidores tabulares SQL.
- El uso simultáneo del Narrador y la Lupa puede provocar un accidente.
- El uso simultáneo del Narrador y la Lupa puede provocar un accidente.

### <a name="outlook"></a>Outlook
- Pueden faltar imágenes insertadas en un mensaje de correo electrónico reenviado.
- La herramienta Buscador de salas puede estar mostrando &quot;Ninguno&quot; en salones disponibles.
- Es posible que los usuarios no puedan crear perfiles de Outlook con restricciones estrictas para los inquilinos.

### <a name="powerpoint"></a>PowerPoint
- El uso simultáneo del Narrador y la Lupa puede provocar un accidente.

### <a name="project"></a>Project
- El usuario no puede marcar una tarea como completada, y esta se establece en un 99 %.
- Redistribuir no resuelve las sobreasignaciones.

### <a name="word"></a>Word
- El uso simultáneo del Narrador y la Lupa puede provocar un accidente.
- Abrir documentos heredados y luego ir a la pestaña Información puede causar un bloqueo.
- Las sugerencias de prueba no se muestran en los menús contextuales.
- Las políticas de contenido se están aplicando incorrectamente a los comentarios.
- Los comentarios anteriores escritos con texto oscuro no son visibles en el Modo oscuro.
- Es posible que aparezcan caracteres incorrectos al utilizar la función de autocorrección en coreano/inglés.
- Las etiquetas de política más bajas pueden aplicarse cuando una etiqueta de política más alta debería haber tenido prioridad.
- Los enlaces de cid: imágenes de los mensajes de Outlook&nbsp;ahora puede romperse con éxito cuando se solicite.
- El uso simultáneo del Narrador y la Lupa puede provocar un accidente.
- La búsqueda desde el panel de navegación puede fallar.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office
- Puede que algunos dibujos no se muestren en la vista previa o en las presentaciones.
- Algunos caracteres de katakana pueden aparecer incorrectamente en un cuadro de texto vertical.
- Si se intenta guardar un archivo en un recurso compartido de red desconectado, es posible que se produzca un error.

[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1911-october-25"></a>Versión 1911: 25 de octubre
*Versión 1911 (compilación 12215.20006)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="visio"></a>Visio

- ** Haga diagramas de Visio pulidos en Excel:** Visualice rápida y fácilmente sus datos en diagramas Visio pulidos dentro de Excel. [Más información](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **Mejoras en la coautoría:** Mejoró la experiencia de coautoría al hacer más probable que los cambios de contenido sean recibidos por otros en tiempo real.

- **Otros usuarios verán los cambios rápidamente**: con las mejoras en la coautoría, los colaboradores podrán ver los cambios más rápido que nunca.


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- <div><span>El número de registros podría ser incorrecto</span></div>


### <a name="excel"></a>Excel

- <div><span>Rendimiento significativamente superior al eliminar columnas con celdas combinadas</span></div>


- <div><span>Se podría impedir que los usuarios guarden en formato de la hoja de trabajo de Office 365 Excel</span></div>


- <div><span>Las casillas de verificación no se pueden renderizar correctamente</span></div>


- <div><span>Los cambios en el tamaño del gráfico no se han podido guardar</span></div>


- <div><span>Algunas funciones VBA devolverían un error en los nuevos tipos de gráficos</span></div>


- <div><span>Los cuadros de diálogo de selección de fuentes de datos no distinguen entre mayúsculas y minúsculas en algunos campos. </span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Los cambios en el tamaño del gráfico no se han podido guardar</span></div>


### <a name="publisher"></a>Publisher

- <div><span>Las formas pueden aparecer fuera del borde del gráfico</span></div>


### <a name="word"></a>Word

- <div><span>Las formas pueden aparecer fuera del borde del gráfico</span></div>


- <div><span>Resaltar el texto podría ser un reto</span></div>


- <div><span>Se puede impedir que un usuario navegue a un elemento individual en el editor</span></div>


- <div><span>Los errores gramaticales u ortográficos pueden no estar resaltados</span></div>


- <div><span>Los cambios en el tamaño del gráfico no se han podido guardar</span></div>


- <div><span>Se podría evitar que una tarjeta de contacto se abra después de aplicar formato a una mención @</span></div>


- <div><span>Corregido el problema en el que los usuarios no podían guardar documentos de Word, Excel y PowerPoint.&nbsp;Este problema afecta a los usuarios que crean un nuevo archivo y abren la opción&quot; guardar como dialogo modelo&quot; después de hacer clic en el icono guardar o presionar Ctrl + S. </span></div>


### <a name="office-suite"></a>Conjunto de programas de Office

- <div><span>Problema de rendimiento al usar Shapes en Windows 7</span></div>



[//]: # (No elimine los detalles del error del contenido final)

## <a name="version-1911-october-18"></a>Versión 1911: 18 de octubre
*Versión 1911 (compilación 12209.20010)*


[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Enviar un correo electrónico accesible a los usuarios que más lo necesitan:** Outlook mostrará una sugerencia de correo para ayudarlo a asegurarse de que el contenido sea accesible al enviarlo a un usuario que prefiera el contenido accesible

### <a name="powerpoint"></a>PowerPoint

- **Optimizar la presentación para todos:** El comprobador de accesibilidad le ayuda a organizar los objetos de las diapositivas pensando en los lectores de pantalla.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- **El centro de carga será reemplazado por la experiencia de los archivos que necesitan atención:** El centro de carga será reemplazado por la experiencia de los archivos que necesitan atención que aparecerá dentro de las aplicaciones de Office en Archivo > Abrir. Esta nueva experiencia es más moderna, integrada y menos intrusiva que el centro de carga.


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="non-security-updates"></a>Actualizaciones que no son de seguridad
### <a name="excel"></a>Excel

- <div><span>Corregimos un problema en el que los controles de casilla podían reducirse al usar el autoajuste para ajustar el alto de fila</span></div>


- <div><span>Corregimos un problema en el que al seleccionar una celda luego de desplazar, podía resultar en la selección de la celda incorrecta</span></div>


### <a name="outlook"></a>Outlook

- <div><span>Identificamos un problema que podía provocar la ruptura de las firmas digitales al firmar un correo electrónico con un adjunto firmado digitalmente</span></div>


- <div><span>Identificamos un problema en el que los nombres de archivo largos se truncaban después de arrastrarlos y soltarlos en el cuerpo del mensaje</span></div>


- <div>Identificamos un problema en el cual el cuadro de búsqueda podía llegar a desaparecer cuando la cinta estaba configurada para ocultarse automáticamente</div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Se identificó un problema en el que la relación de aspecto de la vista previa de diapositivas no estaba siendo correctamente bloqueada/desbloqueada. </span></div>

### <a name="project"></a>Proyecto

- <div>Identificamos un problema en el que las notas no se conservaban si se creaban mientras se realizaban tareas de actualización.<br></div>


- <div>Identificamos un problema por el que un usuario podía bloquear un archivo, pero no se mostraba ningún nombre de usuario en el mensaje de error.</div>


- <div><span>Identificamos un problema en el que los usuarios podían recibir varios mensajes al abrir un proyecto de solo lectura</span></div>


### <a name="word"></a>Word

- <div><span>Identificamos un problema al ver los comentarios mientras se usa un lector de pantalla</span></div>


- <div><span>Identificamos un problema en el que algunos análisis eran identificados erróneamente como análisis de ortografía o gramática</span></div>


- <div><span>Identificamos un problema por el que algunas veces un nuevo diálogo de comentario no podía obtener el foco</span></div>


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- <div><span>Corregimos un problema en el cual actualizar Office podía resultar en un mensaje de error incorrecto de &quot;Otra instalación en curso&quot;</span></div>

- <div><span>Identificamos un problema que podía afectar la sincronización de un recurso local a un recurso en la nube</span></div>

- <div><span>Identificamos un problema en el cual un mensaje de bienvenida contenía un vínculo no válido</span></div>


[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-1910-october-11"></a>Versión 1910: 11 de octubre
*Versión 1910 (compilación 12130.20112)*


[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)
[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)
[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="non-security-updates"></a>Actualizaciones que no son de seguridad
### <a name="excel"></a>Excel

- <div>Se ha resuelto un problema al insertar archivos como objeto desde OneDrive.</div>


- <div>Se ha resuelto un problema en el que el formato de hipervínculo no se podía aplicar correctamente a ciertos contenidos.</div>


- <div>Se ha resuelto un problema por el que las fórmulas con referencias absolutas estructuradas podrían ajustarse incorrectamente.</div>


- <div>Se ha resuelto un problema en el que los libros creados en versiones anteriores de Office podrían hacer que Excel se bloqueara cuando se abría en las versiones actuales de Office.</div>


- <div>Se ha resuelto un problema en el que el contenido copiado desde Excel podría parecer incorrecto al pegarlo en otras aplicaciones de Office.</div>


- <div>Se han corregido los colores que se usan en las vistas previas al insertar gráficos con plantillas de gráficos.</div>


### <a name="powerpoint"></a>PowerPoint

- <div>Se ha identificado un problema en el que los dispositivos ARC podrían perder la conexión al funcionar en AirSpace WinComp.</div>


### <a name="word"></a>Word

- <div>Se ha resuelto un problema al insertar archivos como objeto desde OneDrive.</div>


- <div>Hemos mejorado nuestros pasos de recuperación para <span>corregir un problema que hacía que el contenido gráfico se eliminara de las conversaciones por correo electrónico.&nbsp;</span></div>



[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-1910-october-04"></a>Versión 1910: octubre 04
*Versión 1910 (compilación 12126.20000)*


[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Complemento del visualizador de datos:** Crear rápidamente diagramas de flujo de Visio desde Excel. [Más información](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="non-security-updates"></a>Actualizaciones que no son de seguridad
### <a name="excel"></a>Excel

- <div><span>Se ha corregido un problema por el que el área de impresión en la vista previa de impresión no era correcta</span></div>


- <div><span>Se ha corregido un problema que podría haber impedido la actualización de las tablas dinámicas durante una sesión de coautoría</span></div>


### <a name="access"></a>Access

- <div>Se ha corregido un problema en el que los usuarios podían recibir un error de &quot;estado incoherente&quot; al usar una base de datos compartida.</div>


### <a name="outlook"></a>Outlook

- <div><span>Se ha corregido un problema que podría haber causado la duplicación de las carpetas de correo</span></div>


- <div><span>Se ha corregido un problema que pudo haber causado un mensaje de error incorrecto al intentar enviar correo electrónico cifrado con s/MIME</span></div>


- <div><span>Se ha corregido un problema que podría producir un bloqueo cuando un usuario recibe un mensaje de "Conversación perdida" de Skype</span></div>


- <div><span>Se ha corregido un problema que podría haber resultando en una pérdida de memoria</span></div>


- <div><span>Se ha corregido un problema que podría haber provocado que el nombre del remitente cambiara cuando se ha guardado como borrador</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span></span></div>Se ha corregido un problema que podría provocar que TextRanges se interrumpiera después de pegar el texto en el encabezado o pie de página, el número de marcadores de posición en el patrón de diapositivas y el diseño de la diapositiva


- <div><span></span></div>Se ha corregido un problema que evitó la creación de hipervínculos al pegar el texto con hipervínculos


- <div>Se ha corregido un problema que podría impedir que las estadísticas funcionaran correctamente</div>


### <a name="word"></a>Word

- <div><span>Se ha corregido un problema por el que los colores de fuente no han sido afectados</span></div>


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- <div>Se ha corregido un problema que podría ofrecer el historial de versiones cuando se deshabilitara la característica</div>



[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-1910-september-27"></a>Versión 1910: 27 de septiembre
*Versión 1910 (compilación 12119.20000)*


[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)
[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)
[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="non-security-updates"></a>Actualizaciones que no son de seguridad
### <a name="excel"></a>Excel

- <div><span>Hemos corregido un problema que podría haber provocado que los gráficos de líneas de dispersión se representaron correctamente al cambiar la colección de series</span></div>


### <a name="outlook"></a>Outlook

- <div><span>Hemos corregido un problema que podría haber reportado un error de permisos al interactuar con las carpetas de calendario compartidas</span></div>


- <div><span>Hemos corregimos un problema que podría impedir que los usuarios añadieran eventos en los calendarios</span></div>


- <div><span>Hemos corregido un problema que provocaba que se mostraran mensajes de error al responder a un mensaje firmado digitalmente</span></div>


### <a name="word"></a>Word

- <div><span>Hemos corregido un problema que podría haber provocado problemas de escala al imprimir en impresoras Deskjet</span></div>


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- <div><span>Hemos corregido un problema en el que el texto medio en negrita podría estar en un estilo erróneo</span></div>


- <div><span>Hemos corregido un problema en el que un usuario podría recibir un mensaje de error incorrecto al cerrar un archivo con una carga pendiente</span></div>



[//]: # (NO QUITAR DETALLES DEL ERROR DEL CONTENIDO FINAL)

## <a name="version-1910-september-20"></a>Versión 1910: 20 de septiembre
*Versión 1910 (compilación 12112.20000)*


[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="non-security-updates"></a>Actualizaciones que no son de seguridad
### <a name="excel"></a>Excel

- <div><span>Hemos corregido un problema en el que Excel puede colgarse en ocasiones durante el inicio</span></div>

### <a name="outlook"></a>Outlook

- <div><span>Hemos mejorado significativamente el rendimiento de la selección de sala cuando hay un gran número de salas disponibles</span></div>


- <div><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Hemos corregido un problema que puede impedir la sincronización del buzón de correo para los clientes con varios buzones en Outlook al cambiarse a la autenticación moderna en Office 365.</span><br></div>


- <div><span>Hemos corregido un problema en el que algunos caracteres de las etiquetas de firma podrían no aparecer en el menú desplegable</span></div>


### <a name="project"></a>Proyecto

- <div><span>Se ha corregido un problema que podría provocar un bloqueo al reemplazar un recurso de empresa por un recurso local</span></div>


### <a name="word"></a>Word

- <div><span>Hemos corregido un problema que podría impedir que el desplazamiento sincrónico funcione correctamente en la vista en borrador</span></div>


- <div>Hemos corregido un problema que podría impedir que la Información de herramientas se muestre correctamente después de guardar un documento por primera vez.</div>



[//]: # (NO QUITAR DETALLES DEL ERROR DEL CONTENIDO FINAL)

## <a name="version-1910-september-13"></a>Versión 1910: 13 de septiembre
*Versión 1910 (compilación 12105.20000)*


[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO INICIAL)

### <a name="non-security-updates"></a>Actualizaciones que no son de seguridad
### <a name="excel"></a>Excel

- <div><span>Se corrigió un problema que impedía a un usuario pegar hipervínculos en algunas hojas protegidas</span></div>


### <a name="outlook"></a>Outlook

- <div><span>Se ha corregido un problema por el que la UI podría quedarse atascada en una vista compacta</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Se corrigió un problema en el cual un usuario experimentaba un error al imprimir en PDF</span></div>


### <a name="project"></a>Project

- <div><span>Se corrigió un problema en el que <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">los cambios en un valor de trabajo de una tarea de resumen provocaban un fallo si se habilitaba el trabajo protegido</span></span></div>


- <font size=2 style="background-color:rgb(255, 255, 255);">Se corrigió un problema que podía inhibir la capacidad de sincronizar eventos con los calendarios de la empresa</font>


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- <div><span>Se corrigió un problema que causaba una advertencia repetida para descartar versiones locales de un archivo</span></div>



[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-1910-september-06"></a>Versión 1910: 06 de septiembre
*Versión 1910 (compilación 12030.20004)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Listo, preparado, a dibujar:** cuando agarre el Lápiz para Surface, estará listo para dibujar. [Más información](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="powerpoint"></a>PowerPoint

- **Listo, preparado, a dibujar:** cuando agarre el Lápiz para Surface, estará listo para dibujar. [Más información](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a>Word

- **Listo, preparado, a dibujar:** cuando agarre el Lápiz para Surface, estará listo para dibujar. [Más información](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="non-security-updates"></a>Actualizaciones que no son de seguridad
### <a name="excel"></a>Excel

- <div><span>Se ha corregido un problema por el que el nombre de la fuente de la cinta de opciones podía ser diferente de la fuente que se usa</span></div>


### <a name="outlook"></a>Outlook

- <div><span>Se ha corregido un problema que podía dar lugar a un consumo inadecuado de recursos con Outlook cuando el modo protegido estaba deshabilitado para sitios restringidos en Internet Explorer</span></div>


- <div><span>Se ha corregido un problema por el que a veces aparecían caracteres Unicode al pegar texto desde un origen ANSI</span></div>


- <div><span>Se ha corregido un problema por el que algunos usuarios aparecían de forma incorrecta como sin conexión en la vista de Programación de grupo</span></div>


### <a name="word"></a>Word

- <div><span>Se ha corregido un problema por el que se podía perder el formato de tabla</span></div>


- <div><span>Se ha corregido un problema por el que el método abreviado de teclado Ctrl+V podía dejar de funcionar</span></div>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-1909-august-30"></a>Versión 1909: 30 de agosto
*Versión 1909 (compilación 12026.20000)*


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características

### <a name="access"></a>Access

- **Buscar tablas vinculadas rápidamente:** nuestro nuevo cuadro de búsqueda hace que buscar tablas vinculadas sea mucho más sencillo.

### <a name="powerpoint"></a>PowerPoint

- **Guarde una ilustración como SVG:** guarde un gráfico, una forma o una ilustración como un gráfico vectorial escalable, que se puede cambiar de tamaño sin perder calidad de imagen. [Más información](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="non-security-updates"></a>Actualizaciones que no son de seguridad
### <a name="excel"></a>Excel

- <div><span>Se ha corregido un problema por el que el KeyTip para &nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">Sensibilidad </span>causaba&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">un conflicto con otro KeyTip.</span></span></div>

- <div><span>Se ha corregido un problema al trabajar en un libro compartido cuando se intentaba guardar.</span></div>

- <div><span>Se ha corregido un problema por el que Excel solo mostraba los 16 primeros complementos ubicados en los valores del registro "\Excel\Add-in Manager".<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></div>


- <div><span>Se ha corregido un problema por el que la función Frecuencia() no daba el resultado correcto.</span></div>


- <div><span>Mejoramos significativamente el rendimiento del filtrado por colores.</span></div>


- <div><span>Hemos corregido un problema para los usuarios de Surface, en el que mover el ratón podía interpretarse como un clic.</span></div>


- <div><span>Se ha corregido un problema que evitaba navegar con el teclado en el cuadro de diálogo Buscar y reemplazar.</span></div>


- <div><span>Se ha corregido un problema por el que el nombre de algunas fuentes no se mostraba correctamente</span></div>


- <div><span>Se ha corregido un problema por el que CSV no aparecía como tipo de archivo compatible</span></div>


### <a name="access"></a>Access

- <div>Se ha corregido un problema en el que los usuarios podían recibir un error de &quot;estado incoherente&quot; al usar una base de datos compartida.</div>


- <div><span>Se ha corregido un problema que podía provocar que aparezca el selector de fecha cuando no debía</span></div>


### <a name="outlook"></a>Outlook

- <div><span>Hemos arreglado un problema que impedía que el contenido HTML les apareciera a algunos usuarios de POP3.</span></div>


- <div><span>Hemos evitado que un vínculo no funcional de "Planner" del menú de desbordamiento en la tarjeta de contacto aparezca cuando se trabaja en entornos en los que no está disponible.</span></div>

### <a name="onenote"></a>OneNote

- <div><span>Se ha corregido un problema por el que &nbsp;la sincronización de fondo de OneNote en ocasiones se llevaba el foco.</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Se ha corregido un problema que afectaba a la orientación de rotación de un Giro sin parar en 3D.</span></div>

- <div><span>Se ha corregido un problema que impedía que funcionaran algunos hipervínculos si contenían caracteres especiales.</span></div>

- <div><span>Se ha corregido un problema que provocaba la apertura de varios paneles de comentarios al mismo tiempo.</span></div>

### <a name="project"></a>Project

- <div><span>Se ha corregido un problema que podía bloquear el equipo después de imprimir una vista del Organizador de equipo</span></div>

### <a name="word"></a>Word

- <div>Se ha a<span>rreglado un problema en el que los caracteres multibyte en un cuadro de texto vertical se solapaban en la vista de lectura.<br></span></div>

- <div><span>Se&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);"> ha corregido un problema por el que no se encontraban los recursos de complemento relacionados con la tarjeta postal japonesa y la tarjeta de bienvenida cuando el usuario realiza una acción en el asistente del complemento.</span></span></div>

- <div><span>Se ha corregido un problema que podría causar problemas con la interfaz de usuario de la barra de título en la vista protegida</span></div>

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- <div><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> Se ha corregido un problema de archivo corrupto que tenía lugar al cambiar la forma en una selección con una forma normal y una forma de conector.</span></span></div>

- <div><span>Se ha corregido un problema <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">en las aplicaciones al acoplar o desacoplar desde varias pantallas externas. </span></span></div>



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="august-23-2019br"></a>**23 de agosto de 2019**<br/>
Versión 1909 (compilación 12015.20004)<br/>



## <a name="non-security-updates"></a>Actualizaciones que no son de seguridad:

### <a name="excel"></a>Excel

- <div><span>Rendimiento significativamente superior al eliminar columnas con celdas combinadas</span></div>


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- <div><span>Se ha corregido un problema que impedía mostrar algunos caracteres unicode en un explorador.</span></div>


### <a name="outlook"></a>Outlook

- <div><span>Se ha corregido un problema que podía impedir guardar archivos en una ubicación de WebDAV</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Antes, cuando un usuario hacía clic en un comentario, a veces se seleccionaba otro distinto. Este problema se ha solucionado.</span></div>





## <a name="august-16-2019br"></a>**16 de agosto de 2019**<br/>
Versión 1909 (compilación 12013.20000)<br/>

### <a name="powerpoint-feature-updates"></a>Actualizaciones de características de PowerPoint:

- **Impresión de números de diapositiva en documentos:** los números de diapositiva se incluyen automáticamente en los documentos. Ahora es usted quien decide si los deja o los quita.




## <a name="non-security-updates"></a>Actualizaciones que no son de seguridad:

### <a name="excel"></a>Excel

- <div><span>Se ha corregido un problema que podía activar de forma no deseada la opción Autoguardado.</span></div>


- <div>Se ha corregido un problema que podía provocar mediciones incorrectas de la altura de las celdas</div>


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- <div><span>Se ha corregido un problema para mejorar considerablemente el rendimiento de la característica Comentarios.</span></div>


- <div><span>Se ha corregido un problema que podía provocar un bloqueo cuando se usaban las flechas en la búsqueda.</span></div>


- <div><span>Se ha corregido un problema que podía interferir con una mención con @ cuando el símbolo @ estaba detrás de determinados caracteres.</span></div>


- <div><span>Se ha corregido un problema que podía bloquear el equipo al eliminar menciones con @.</span></div>


- <div><span>Se ha corregido un problema que impedía que los emojis se mostrarán correctamente en las tarjetas de comentario.</span></div>


- <div><span>Se ha corregido un problema con el Portapapeles Activo que podía bloquear el equipo.</span></div>


- <div><span>Se ha corregido un problema que podía provocar que los botones de la barra de herramientas de acceso rápido dejaran de funcionar</span></div>


- <div><span>Se ha corregido un problema que podía impedir que la vista previa del Formato del documento pasara al fondo.</span></div>

### <a name="onenote"></a>OneNote

- Se ha corregido un problema por el que los nombres de las secciones aparecían en blanco en la lista desplegable de la sección cuando el tema de Office se configuraba en color negro.

### <a name="outlook"></a>Outlook

- <div><span>Se ha corregido un problema al enviar eventos que podía provocar que Outlook se enfocara y desenfocara reiteradamente.</span></div>


- <div><span>Se ha corregido un problema que impedía el correcto funcionamiento del acceso directo Exponer respuesta a la Carpeta.</span></div>

### <a name="powerpoint"></a>PowerPoint

- <div><span>Se ha corregido un error con la Vista protegida que podía causar problemas en las colaboraciones.</span></div>


- <div><span>Se ha corregido un problema que impedía que las tareas en los paneles de comentario se mostraran correctamente.</span></div>


- <div><span>Se ha corregido un problema que podía bloquear el equipo al insertar nuevas diapositivas.</span></div>


### <a name="user-lifecycle"></a>Ciclo de vida del usuario:

- <div><span>Se ha corregido un problema que podía hacer desaparecer las características de suscripción.</span></div>


### <a name="word"></a>Word

- <div><span>Se ha corregido un problema por el que los hipervínculos podían no funcionar si contenían determinados caracteres.</span></div>


- <div><span>Se ha corregido un problema por el que las imágenes podían tener el tamaño incorrecto cuando el usuario veía un comentario de dicha imagen.</span></div>


- <div><span>Se ha corregido un problema con el menú desplegable de la lista de viñetas que podía bloquear el equipo.</span></div>





## <a name="august-09-2019br"></a>**09 de agosto de 2019**<br/>
Versión 1909 (compilación 12001.20000)<br/>

### <a name="excel-feature-updates"></a>Actualizaciones de características de Excel:

- **La colaboración es ahora más fácil**: las mejoras en la coautoría significan que al trabajar con el formato condicional, los estilos de celda y otros elementos, los cambios se combinan perfectamente con los de los colaboradores.


- **Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea. Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido.


### <a name="office-suite-feature-updates"></a>Conjunto de aplicaciones de Office, actualizaciones de características:

- **Nuevos iconos de aplicación de Office**: nuevo diseño de iconos de la aplicación para reflejar las sencillas, eficaces e inteligentes experiencias de Office.


### <a name="outlook-feature-updates"></a>Actualizaciones de características de Outlook:

- **Protección avanzada frente a ataques**: con la Protección contra amenazas avanzada de Office 365, estará protegido frente a ataques mediante hipervínculos en asuntos de correos electrónicos, mensajes adjuntos, mensajes firmados, rutas de red, etc.


- **Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea. Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido.


### <a name="powerpoint-feature-updates"></a>Actualizaciones de características de PowerPoint:

- **Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea. Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido.


### <a name="word-feature-updates"></a>Actualizaciones de características de Word:

- **Otros usuarios verán los cambios rápidamente**: las mejoras en la coautoría significan que los colaboradores podrán ver los cambios más rápido que nunca.


- **Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea. Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido.




## <a name="non-security-updates"></a>Actualizaciones que no son de seguridad:

### <a name="outlook"></a>Outlook

- <div><span>Se ha corregido un problema que provocaba que los destinatarios de la reunión recibiesen dos notificaciones después de que se cancelara una reunión</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Se ha corregido un problema que podía provocar un bloqueo cuando el usuario seleccionaba Sin contorno o Sin relleno para formas e iconos.</span></div>





## <a name="august-02-2019br"></a>**02 de agosto de 2019**<br/>
Versión 1908 (compilación 11929.20002)<br/>

### <a name="excel-feature-updates"></a>Actualizaciones de características de Excel:

- **Convertir los archivos para mejorar la accesibilidad**: Actualice los archivos al formato moderno para que sean más accesibles para todos los usuarios.


- **Aplicar etiquetas de confidencialidad a los documentos:** Aplique etiquetas de confidencialidad a sus archivos y correos electrónicos para que cumplan las directivas de protección de la información de su organización.


### <a name="outlook-feature-updates"></a>Actualizaciones de características de Outlook:

- **Aplicar etiquetas de confidencialidad a los documentos:** Aplique etiquetas de confidencialidad a sus archivos y correos electrónicos para que cumplan las directivas de protección de la información de su organización.


### <a name="powerpoint-feature-updates"></a>Actualizaciones de características de PowerPoint:

- **Convertir los archivos para mejorar la accesibilidad**: Actualice los archivos al formato moderno para que sean más accesibles para todos los usuarios.


- **Aplicar etiquetas de confidencialidad a los documentos:** Aplique etiquetas de confidencialidad a sus archivos y correos electrónicos para que cumplan las directivas de protección de la información de su organización.


### <a name="word-feature-updates"></a>Actualizaciones de características de Word:

- **Convertir los archivos para mejorar la accesibilidad**: actualice los archivos al formato moderno para que sean más accesibles para todos los usuarios.


- **Decirlo de otra forma:** si lo quiere decir de forma diferente, la reescritura le puede ayudar. La reescritura ofrece alternativas para afinar sus frases.


- **Aplicar etiquetas de confidencialidad a los documentos:** aplique etiquetas de confidencialidad a sus archivos y correos electrónicos para que cumplan las directivas de protección de la información de su organización.




## <a name="non-security-updates"></a>Actualizaciones que no son de seguridad:

### <a name="access"></a>Access
- Varias correcciones de rendimiento y estabilidad.

### <a name="excel"></a>Excel

- <div><span>Corregimos un problema que hacía que parezca que &quot;repetir todas las etiquetas&quot; se aplicaba al imprimir en PDF</span></div>

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- <div><span>Corregimos un problema que podría impedir que los usuarios abrieran un documento desde el escritorio</span></div>

- <div><span>Corregimos un problema en el cual se podía evitar una actualización con un mensaje de error incorrecto indicando que &quot;Hay otra instalación en curso&quot;</span></div>

- <div><span>Corregimos un problema en el que un usuario podía ver mensajes de error al instalar las actualizaciones de seguridad</span></div>

- <div><span>Corregimos un problema que podría provocar la desaparición del cursor</span></div>

- <div><span>Corregimos un problema en el que un usuario podía tener cómo valor predeterminado la pestaña dibujar en lugar de la pestaña de inicio</span></div>

- <div><span>Corregimos un problema por el que las vistas de árboles grandes podían dar lugar a un bloqueo</span></div>

### <a name="outlook"></a>Outlook

- <div></div><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Corregimos un problema que puede provocar reiteradas solicitudes de contraseña</span>

- <div><span>Corregimos un problema que podría impedir que una dirección de correo electrónico se pueda consultar correctamente</span></div>

- <div><span>Corregimos un problema que podría impedir que los usuarios abran los elementos del calendario creados con las versiones heredadas de Outlook</span></div>

### <a name="powerpoint"></a>PowerPoint

- <div><span>Corregimos un problema que podría impedir que comiencen algunas animaciones</span></div>

### <a name="project"></a>Proyecto
- Varias correcciones de rendimiento y estabilidad.

### <a name="word"></a>Word

- <div><span>Corregimos un problema en el que las respuestas a los comentarios podrían aparecer desordenadas</span></div>

- <div><span>Corregimos un problema en el que en algunas situaciones, se mostrarían las sugerencias en lugar de los comentarios</span></div>

- <div><span>Corregimos un problema en el cual panel de revisiones podía mostrar cuándo el usuario intentó agregar un nuevo comentario</span></div>

- <div><span>Corregimos un problema que podría impedir que aparezca la lista desplegable deshacer</span></div>

- <div><span>Corregimos un problema que podría impedir agregar comentarios</span></div>


## <a name="july-26-2019"></a>26 de julio de 2019
Versión 1908 (versión 11916.20000)

## <a name="whats-new"></a>Novedades:

### <a name="word-excel-powerpoint"></a>Word, Excel, PowerPoint

#### <a name="create-more-accessible-pdfs"></a>Crear PDF más accesibles

Crear un archivo PDF y el comprobador de accesibilidad indicará si hay problemas de accesibilidad para solucionar el problema antes de guardar.

## <a name="notable-fixes"></a>Correcciones notables:

### <a name="all"></a>Todo

- Se ha corregido un problema por el que la asociación de tipo de archivo y los iconos de Office podría romperse en ocasiones, tras una actualización de Office

### <a name="word"></a>Word 
- Varias correcciones de rendimiento y estabilidad.

### <a name="excel"></a>Excel
- Se ha corregido un problema por el que mover un gráfico puede causar un error en ocasiones.
- Se ha corregido un problema por el que al obtener el objeto de hoja de cálculo después de cambiar de tipo de gráfico en ocasiones podría producirse un error

### <a name="powerpoint"></a>PowerPoint
- Varias correcciones de rendimiento y estabilidad

### <a name="outlook"></a>Outlook
- Se ha corregido un problema en el que, en la cinta de opciones simplificada, un control deshabilitado a veces puede no estar atenuado en la cinta de opciones

### <a name="access"></a>Access
- Diversas correcciones de rendimiento y estabilidad.

### <a name="project"></a>Project
- Varias correcciones de rendimiento y estabilidad.

</BR></BR>

## <a name="july-19-2019"></a>19 de julio de 2019
Versión 1908 (versión 11911.20000)

## <a name="whats-new"></a>Novedades:

### <a name="word"></a>Word

#### <a name="learn-what-acronyms-mean-when-you-read-in-word-online"></a>Aprenda acerca del significado de los acrónimos cuando los lee en Word online

Cuando encuentre un acrónimo, intentaremos definirlo con datos provenientes de su organización.


## <a name="notable-fixes"></a>Correcciones notables:

### <a name="word"></a>Word 
- Hemos arreglado un problema en el que la etiqueta BookMarkEnd.estaba faltando.
- Hemos arreglado un problema en el que la selección de fuente podía cambiar mientras el usuario escribía caracteres especiales.
- Hemos arreglado un problema que a veces podía causar respuestas en blanco a una nueva tarjeta de comentario.
- Hemos arreglado un problema que podía provocar que se perdiera el formato al compartir un correo electrónico.

### <a name="excel"></a>Excel
- Hemos arreglado un problema en el que en una matriz con un gran rango ocasiones, podía causar un bloqueo.
- Hemos mejorado significativamente el rendimiento al copiar datos de rangos filtrados.
- Hemos arreglado un problema que impedía que algunos archivos se abrieran si el nombres del archivo contenía caracteres especiales.

### <a name="powerpoint"></a>PowerPoint
- Hemos arreglado un problema en el que el nombre de la sección no se seleccionaba de forma predeterminada en las secciones recién creadas en PowerPoint.
- Hemos arreglado un problema que podía provocar que la interfaz de usuario fuese difícil de usar al usar una pantalla de 4:3.

### <a name="outlook"></a>Outlook
- Hemos arreglado un problema que impedía que se mostraran las salas en listados.
- Hemos arreglado un problema que impedía usar el formato HTML para algunos usuarios de POP3.

### <a name="access"></a>Access
- Diversas correcciones de rendimiento y estabilidad.

### <a name="project"></a>Project
- Varias correcciones de rendimiento y estabilidad.

</BR></BR>

## <a name="july-12-2019"></a>12 de julio de 2019
Versión 1907 (compilación 11901.20038)

## <a name="whats-new"></a>Novedades:

### <a name="powerpoint"></a>PowerPoint
 
#### <a name="use-ink-replay-in-your-presentations"></a>Usar la reproducción de entrada de lápiz en sus presentaciones
 
Aplique una animación de reproducción para la entrada de lápiz en PowerPoint para expresarse y comunicarse más efectivamente en presentaciones. 

## <a name="notable-fixes"></a>Correcciones notables:

### <a name="word"></a>Word 
- Varias correcciones de rendimiento y estabilidad.

### <a name="excel"></a>Excel
- Varias correcciones de rendimiento y estabilidad.

### <a name="powerpoint"></a>PowerPoint
- Varias correcciones de rendimiento y estabilidad

### <a name="outlook"></a>Outlook
- Varias correcciones de rendimiento y estabilidad.

### <a name="access"></a>Access
- Diversas correcciones de rendimiento y estabilidad.

### <a name="project"></a>Project
- Varias correcciones de rendimiento y estabilidad.

</BR></BR>

## <a name="july-5-2019"></a>5 de julio de 2019
Versión 1907 (compilación 11901.20018)

## <a name="whats-new"></a>Novedades:

### <a name="word-excel-powerpoint"></a>Word, Excel, PowerPoint

#### <a name="sketchy-shapes"></a>¡Formas incompletas!

¿Estás realizando una presentación? Aplique el estilo incompleto para indicar que todavía está trabajando en él. Ofrece un toque personal a los objetos sin convertirlos en formas libres, dibujadas a mano.

### <a name="excel"></a>Excel

- **Uso compartido de archivos más rápido**: comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.
### <a name="powerpoint"></a>PowerPoint

- **La configuración para imprimir números de diapositiva en documentos se ha movido al menú Imprimir para facilitar el acceso:** búsquelo en la lista desplegable imprimir > diseño de impresión cuando haya seleccionado un diseño de documento. Esto también permite que la configuración se alterne fácilmente por presentación. [Más información](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- **Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.

### <a name="word"></a>Word

- **Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.

## <a name="notable-fixes"></a>Correcciones notables:

### <a name="all"></a>Todo
- Mejoramos significativamente el rendimiento de las KeyTips de la cinta de opciones
- Se ha corregido un problema que evitó que aparezca el cuadro de diálogo "Ver pronto lo que está disponible"
- Se ha corregido un problema que podría causar que las fotografías estén mal alineadas en el control flotante de la galería de Coauth

### <a name="word"></a>Word 
- Se ha corregido un problema que a veces podría impedir agregar nuevos comentarios
- Se ha corregido un problema por el que en ocasiones las tablas podrían causar un error 
- Se ha corregido un problema por el que a veces se pueden agregar datos no válidos al final de una combinación de correspondencia
- Se ha corregido un problema que podría provocar que algunas ecuaciones LaTeX se representen de forma incorrecta

### <a name="excel"></a>Excel
- Se ha corregido un problema en el que, al cambiar los tipos de gráfico, se podría producir una excepción en el tiempo de ejecución
- Se ha corregido un problema por el que es posible que se muestre la cinta de opciones incorrecta cuando se abren varias ventanas
- Se ha corregido un problema que podría provocar un error cuando una macro abrió una segunda instancia de un libro
- Se ha corregido un problema que podría provocar un error al abrir o crear un libro, o al cambiar entre libros
- Se ha corregido un problema que impide que los usuarios abran un archivo PDF creado a partir de Word en Teams

### <a name="powerpoint"></a>PowerPoint
- Se ha corregido un problema que degradaría la calidad de un gráfico cuando se exportó a un PDF
- Se ha corregido un problema que impedía que una información sobre herramienta mostrara la distancia al centro

### <a name="outlook"></a>Outlook
- Se ha corregido un problema que a veces podía evitar que se mostrara un error de disco lleno
- Se ha corregido un problema que podría provocar que los datos adjuntos se dupliquen al actualizar una convocatoria de reunión

### <a name="access"></a>Acceso
- Se ha corregido un problema que impedía a algunas consultas devolver valores enteros grandes
- Se ha corregido un problema que haría que el cuadro de texto SQL no se pudiera editar.
- Se ha corregido un problema por el que es difícil ver información sobre herramientas en algunas pantallas altas de PPP

### <a name="project"></a>Proyecto
- Se ha corregido un problema que podría provocar que los valores del indicador no se puedan editar en nuevas tareas
- Se ha corregido un problema que podría provocar que una actualización de estado se estableciera de forma incorrecta en la fecha de inicio real de las asignaciones y tareas
- Se ha corregido un problema que podría provocar que algunos recursos aparezcan incorrectamente sobreasignados
- Se ha corregido un problema por el que el método TaskDependencies Add puede fallar cuando se agrega un retardo, el separador decimal es una coma y al estar conectado a un servidor
- Se ha corregido un problema por el que la actualización de los valores de la tabla de búsqueda de campo personalizado local a través del CSOM podía fallar
- Se ha corregido un problema en el que los valores de trabajo totales podían aparecer como incorrectos si contienen un decimal

</BR></BR>

## <a name="june-28-2019"></a>28 de junio de 2019
Versión 1907 (compilación 11819.20002)

## <a name="whats-new"></a>Novedades:

### <a name="excel"></a>Excel

- **Programar rápidamente con mejoras de Power Query:** termine rápidamente el código con colores de sintaxis y la función de autocompletar. Además, descubra fácilmente funciones, columnas y parámetros.

- **Unir tablas en columnas similares:** Obtener y transformar (Power Query) ahora ofrece una lógica de coincidencia de texto (también denominada coincidencia aproximada) al comparar columnas en la combinación de tablas.

### <a name="word"></a>Word

- **Mejoras en la coautoría:** mejora de la confiabilidad de la coautoría.
 
### <a name="word-excel-powerpoint-and-visio"></a>Word, Excel, PowerPoint y Visio

#### <a name="recommended-documents"></a>Documentos recomendados

Busque documentos con actividad relevante recomendados para usted.

## <a name="notable-fixes"></a>Correcciones notables:

### <a name="word"></a>Word 
- Se ha corregido un problema que podía impedir que se abriesen archivos .DOC.
- Se ha corregido un problema que podía impedir que los comentarios se cargasen correctamente.

### <a name="excel"></a>Excel
- Se ha mejorado el rendimiento de Power Queries.

### <a name="powerpoint"></a>PowerPoint
- Se ha corregido un problema relacionado con el uso de un lápiz en un dispositivo Surface que podía provocar que la pantalla parpadease.

### <a name="outlook"></a>Outlook
- Se ha corregido un problema que podía cambiar el estado de disponibilidad de una cita al convertirla en una reunión.
- Se ha corregido un problema por el que se mostraba la plantilla y la descripción incorrecta al proteger un correo electrónico con una plantilla ad-hoc.

### <a name="access"></a>Access
- Varias correcciones de rendimiento y estabilidad.

### <a name="project"></a>Project
- Varias correcciones de rendimiento y estabilidad.

</BR></BR>

## <a name="june-21-2019"></a>21 de junio de 2019
Versión 1907 (compilación 11815.20002)

## <a name="whats-new"></a>Novedades:

### <a name="outlook"></a>Outlook

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a>Modo oscuro para tema negro en Outlook para escritorio

Con el modo oscuro, los usuarios con tema negro ahora también verán el panel de lectura con un fondo oscuro al leer mensajes de correo electrónico y la experiencia de redacción con un fondo oscuro al escribir correos electrónicos. Hay un botón de alternancia sol y luna en el panel de lectura y en la cinta de opciones, en caso de que los usuarios quieran obtener una vista previa del aspecto que tendrá el mensaje con un fondo claro.

#### <a name="getting-started"></a>Introducción:

1. Active el tema negro y se activará el modo oscuro de manera predeterminada.
2. Use el botón de alternancia luna y sol (en el panel de lectura y en la cinta de opciones) para obtener una vista previa del aspecto que tiene el mensaje para los usuarios que no están en modo oscuro.

#### <a name="scenarios-to-try"></a>Escenarios que puede probar

1. Lea los correos electrónicos en modo oscuro. Si no puede leer, use el botón de alternancia de sol en el panel de lectura para cambiar a un fondo claro. 
2. Redacte correos electrónicos en modo oscuro. Obtenga una vista previa del aspecto que tendrá el mensaje con un fondo claro mediante el botón de alternancia de sol en la cinta de opciones. 

Si encuentra mensajes de correo electrónico que no se visualizan correctamente, envíelos como datos adjuntos a OutlookDarkModeFail@service.microsoft.com

#### <a name="get-location-suggestions"></a>Obtener sugerencias de ubicación

Comience a escribir y Outlook buscará las ubicaciones coincidentes.

Esto se aplica al campo Ubicación al crear citas y reuniones.

#### <a name="getting-started"></a>Introducción:

- Cree una cita o una reunión en un calendario de O365 o Outlook.com en Outlook. 
- Haga clic en el campo Ubicación y comience a escribir...

#### <a name="scenarios-to-try"></a>Escenarios que puede probar

Cuando agregue una sala de conferencias a una reunión, haga clic en el campo Ubicación, en lugar de usar el complemento del buscador de salas o la libreta de direcciones.
Para citas en un lugar físico con una ubicación pública, como un restaurante, cafetería o incluso el consultorio del dentista, pruebe a buscar la ubicación exacta con el nuevo selector. De esta forma, podrá obtener una notificación de Outlook Mobile cuando llegue el momento de salir.

## <a name="notable-fixes"></a>Correcciones notables:

### <a name="all"></a>Todo
- Se ha corregido un problema por el que el cuadro de búsqueda seguía activado sin conexión.

### <a name="word"></a>Word 
- Se ha corregido un problema por el que, en ocasiones, era difícil ver el foco del teclado.
- Se ha corregido un problema por el que el texto que se pegó en un documento nuevo, en ocasiones, podía tener una alineación de texto incorrecta.
- Se ha corregido un problema que impedía que algunos usuarios guardaran cambios después de suspender el equipo.
- Se ha corregido un problema por el que, en ciertos casos, se imprimía un documento completo en lugar del rango seleccionado.
- Se ha corregido un problema que podía hacer que los comentarios fueran difíciles de leer en pantallas más pequeñas.
- Se ha corregido un problema que podía provocar un bloqueo al capturar en un dispositivo.

### <a name="excel"></a>Excel
- Varias correcciones de rendimiento y estabilidad.

### <a name="powerpoint"></a>PowerPoint
- Se ha corregido un problema por el que, en ocasiones, era difícil ver el foco del teclado.

### <a name="outlook"></a>Outlook
- Se ha corregido un problema por el que se mostraba incorrectamente un complemento como activado cuando no lo estaba.
- Se ha corregido un problema que impedía que los clientes vieran todas las directivas de retención si había varias.

### <a name="access"></a>Access
- Diversas correcciones de rendimiento y estabilidad.

### <a name="project"></a>Project
- Varias correcciones de rendimiento y estabilidad.

</BR></BR>

## <a name="june-14-2019"></a>14 de junio de 2019
Versión 1907 (compilación 11807.20000)

## <a name="notable-fixes"></a>Correcciones notables:

### <a name="word"></a>Word 
- Se ha corregido un problema que podía impedir que un usuario iniciase sesión al guardar en OneDrive
- Se ha corregido un problema que podía impedir que un usuario cambiase las propiedades de SharePoint mientras estaba en el modo de acceso restringido
- Se ha corregido un problema por el que el contenido del encabezado y pie de página podría cambiar al ajustar márgenes
- Se ha corregido un problema en el que se podía perder el formato al cambiar a la vista web
- Se ha corregido un problema que podía impedir que un usuario usase campos personalizados cuando se abría desde SharePoint

### <a name="excel"></a>Excel
- Se ha corregido un problema de rendimiento al eliminar filas de un conjunto filtrado
- Se ha corregido un problema que a veces podía causar que el ratón parpadease en la vista protegida
- Se ha corregido un problema por el que la aplicación podía bloquearse al eliminar una serie
- Se ha corregido un problema por el que algunos usuarios tendían la opción de agregar el historial de versiones cuando no estaba disponible
- Se ha corregido un problema por el que la aplicación podía bloquearse al usar la herramienta de comparación de hojas de cálculo

### <a name="powerpoint"></a>PowerPoint
- Se ha corregido un problema por el que la aplicación podía bloquearse al hacer clic en un vínculo a SharePoint
- Se ha corregido un problema que podía cambiar al usuario a la página siguiente mientras escribía con un Lápiz para Surface

### <a name="outlook"></a>Outlook
- Se ha corregido un problema en el que, en algunos casos, el campo Para era más grande de lo normal.

### <a name="access"></a>Access
- Diversas correcciones de rendimiento y estabilidad.

### <a name="project"></a>Project
- Varias correcciones de rendimiento y estabilidad.

</BR></BR>

## <a name="june-7-2019"></a>7 de junio de 2019
Versión 1907 (compilación 11727.20064)

## <a name="notable-fixes"></a>Correcciones notables:

### <a name="word"></a>Word 
- Se ha corregido un problema por el que, a veces, Word podía bloquearse cuando Autocorrección se configuraba para poner en mayúscula la primera letra de una oración.
- Se ha mejorado el rendimiento al editar un documento en SharePoint.
- Se ha corregido un problema por el que las imágenes basada en vectores creadas en Adobe Illustrator no se mostraban correctamente.

### <a name="excel"></a>Excel
- Se ha corregido un problema por el que, a veces, los campos de ordenación no se establecían correctamente al grabar una macro.
- Se ha corregido un problema que provocaba bloqueos al volver a calcular una fórmula de matriz.

### <a name="powerpoint"></a>PowerPoint
- Varias correcciones de rendimiento y estabilidad

### <a name="outlook"></a>Outlook
- Se ha corregido un problema por el que los datos adjuntos en línea a veces se mostraban con una escala incorrecta.

### <a name="access"></a>Access
- Diversas correcciones de rendimiento y estabilidad.

### <a name="project"></a>Project
- Se ha corregido un problema por el que los partes de horas con una duración fija podían cambiar la fecha de finalización de la asignación.
- Se ha corregido un problema por el que los valores de Porcentaje completado podían ser incorrectos al abrir un proyecto desde una versión anterior.

</BR></BR>

## <a name="may-31-2019"></a>31 de mayo de 2019
Versión 1906 (compilación 11722.20008)

## <a name="whats-new"></a>Novedades:

### <a name="outlook"></a>Outlook

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a>El diálogo para ponerse en contacto con el servicio de atención al cliente ahora es acoplable y aparece a la derecha

El cuadro de diálogo que se usa para ponerse en contacto con el servicio de asistencia al cliente aparecerá ahora en un panel a la derecha y se iniciará como una ventana acoplada.

#### <a name="ink-in-your-email"></a>Entrada de lápiz en el correo electrónico.

Ahora puede dibujar y realizar anotaciones en imágenes en sus correos electrónicos de Outlook.

### <a name="word"></a>Word

#### <a name="open-document-links-in-word"></a>Abrir vínculos de documentos en Word

Al hacer clic en un vínculo a un documento en Office, puede actualizar sus preferencias para abrirlo en la aplicación de Word de forma predeterminada.  Para actualizar sus preferencias, vaya a Archivo -> Opciones -> Avanzadas -> Gestión de vínculos. Más información: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

##### <a name="getting-started"></a>Introducción:

La característica estará desactivada de forma predeterminada. Los usuarios pueden habilitar esta característica a través de la configuración en Opciones -> Avanzadas -> Gestión de vínculos, o pueden optar por activarla cuando las aplicaciones de Win32 WXP les dirijan a la experiencia de activación.
Cuando los usuarios hagan clic en vínculos a archivos de Word/PowerPoint/Excel almacenados en OneDrive, OneDrive para la Empresa o SharePoint desde Outlook/Word/PowerPoint/Excel, estos vínculos se abrirán de forma predeterminada en la aplicación de Office correspondiente en lugar de en el explorador.

Para cambiar este valor predeterminado, los usuarios pueden actualizar la siguiente configuración en Outlook/Word/Excel/PowerPoint:

Archivo -> Opciones -> Avanzadas -> Gestión de vínculos

Esta configuración se comparte entre Outlook/Word/PowerPoint/Excel y puede establecerse en cualquiera de estas aplicaciones.

##### <a name="scenarios-to-try"></a>Escenarios que puede probar:

Para activar la opción: abra un vínculo a un documento de Word almacenado en OneDrive o SharePoint desde Outlook/Word/PowerPoint/Excel y haga clic en Abrir en cliente desde Office Online (repita esto dos veces en un período de 30 días). Después de habilitar esta opción, los vínculos se iniciarán de forma predeterminada en las aplicaciones de Win32.

### <a name="powerpoint"></a>PowerPoint

#### <a name="open-presentation-links-in-powerpoint"></a>Abrir vínculos de presentación en PowerPoint

Al hacer clic en un vínculo a una presentación en Office, puede actualizar sus preferencias para abrirlo en la aplicación de PowerPoint de forma predeterminada. Para actualizar sus preferencias, vaya a Archivo -> Opciones -> Avanzadas -> Gestión de vínculos. Más información: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

##### <a name="getting-started"></a>Introducción:

La característica estará desactivada de forma predeterminada. Los usuarios pueden habilitar esta característica a través de la configuración en Opciones -> Avanzadas -> Gestión de vínculos, o pueden optar por activarla cuando las aplicaciones de Win32 WXP les dirijan a la experiencia de activación.
Cuando los usuarios hagan clic en vínculos a archivos de Word/PowerPoint/Excel almacenados en OneDrive, OneDrive para la Empresa o SharePoint desde Outlook/Word/PowerPoint/Excel, estos vínculos se abrirán de forma predeterminada en la aplicación de Office correspondiente en lugar de en el explorador.

Para cambiar este valor predeterminado, los usuarios pueden actualizar la siguiente configuración en Outlook/Word/Excel/PowerPoint:

Archivo -> Opciones -> Avanzadas -> Gestión de vínculos

Esta configuración se comparte entre Outlook/Word/PowerPoint/Excel y puede establecerse en cualquiera de estas aplicaciones.

##### <a name="scenarios-to-try"></a>Escenarios que puede probar:

Para activar la opción: abra un vínculo a una presentación de PowerPoint almacenada en OneDrive o SharePoint desde Outlook/Word/PowerPoint/Excel y haga clic en Abrir en cliente desde Office Online (repita esto dos veces en un período de 30 días). Después de habilitar esta opción, los vínculos se iniciarán de forma predeterminada en las aplicaciones de Win32.

### <a name="excel"></a>Excel

#### <a name="open-workbook-links-in-excel"></a>Abrir vínculos de libros en Excel

Al hacer clic en un vínculo a un libro en Office, puede actualizar sus preferencias para abrirlo en la aplicación de Excel de forma predeterminada. Para actualizar sus preferencias, vaya a Archivo -> Opciones -> Avanzadas -> Gestión de vínculos. Más información: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

##### <a name="getting-started"></a>Introducción:

La característica estará desactivada de forma predeterminada. Los usuarios pueden habilitar esta característica a través de la configuración en Opciones -> Avanzadas -> Gestión de vínculos, o pueden optar por activarla cuando las aplicaciones de Win32 WXP les dirijan a la experiencia de activación.
Cuando los usuarios hagan clic en vínculos a archivos de Word/PowerPoint/Excel almacenados en OneDrive, OneDrive para la Empresa o SharePoint desde Outlook/Word/PowerPoint/Excel, estos vínculos se abrirán de forma predeterminada en la aplicación de Office correspondiente en lugar de en el explorador.

Para cambiar este valor predeterminado, los usuarios pueden actualizar la siguiente configuración en Outlook/Word/Excel/PowerPoint:

Archivo -> Opciones -> Avanzadas -> Gestión de vínculos

Esta configuración se comparte entre Outlook/Word/PowerPoint/Excel y puede establecerse en cualquiera de estas aplicaciones.

##### <a name="scenarios-to-try"></a>Escenarios que puede probar:

Para activar la opción: abra un vínculo a un libro de Excel almacenado en OneDrive o SharePoint desde Outlook/Word/PowerPoint/Excel y haga clic en Abrir en cliente desde Office Online (repita esto dos veces en un período de 30 días). Después de habilitar esta opción, los vínculos se iniciarán de forma predeterminada en las aplicaciones de Win32.

## <a name="notable-fixes"></a>Correcciones notables:

### <a name="all"></a>Todo
- Se ha corregido un problema por el que, en ocasiones, los archivos podían guardarse automáticamente, incluso si el guardado automático estaba deshabilitado.

### <a name="word"></a>Word 
- Se ha corregido un problema que podía impedir que algunos usuarios guardaran en SharePoint.

### <a name="excel"></a>Excel
- Se ha corregido un problema por el que podía mostrarse un icono incorrecto para los filtros inactivos.

### <a name="powerpoint"></a>PowerPoint
- Varias correcciones de rendimiento y estabilidad

### <a name="outlook"></a>Outlook
- Se ha corregido un problema por el que algunos usuarios aparecen de forma incorrecta como sin conexión en la vista de Programación de grupo.
- Se ha corregido un problema que impedía que SafeLink pudiera analizar una URL con un espacio final.
- Se ha corregido un problema por el que las salas se mostraban como disponibles fuera de las horas no laborables.

### <a name="access"></a>Access
- Diversas correcciones de rendimiento y estabilidad.

### <a name="project"></a>Project
- Varias correcciones de rendimiento y estabilidad.

</BR></BR>

## <a name="may-24-2019"></a>24 de mayo de 2019
Versión 1906 (compilación 11715.20002)

## <a name="whats-new"></a>Novedades:

#### <a name="user-experience-updates"></a>Actualizaciones en la experiencia del usuario

Las actualizaciones que han estado en "Próximamente" ahora están aquí, presentando la cinta simplificada y una actualización visual del panel de carpetas, la lista de mensajes y el panel de lectura.

## <a name="notable-fixes"></a>Correcciones notables:

### <a name="all"></a>Todo

- Se ha corregido un problema por el que no se mostraba el panel de chat.

### <a name="word"></a>Word 
- Se ha corregido un problema en el que, en algunos casos, Word resaltaba erróneamente errores gramaticales.

### <a name="excel"></a>Excel
- Se ha corregido un problema por el que se usaba un icono incorrecto para los Elementos de gráfico.
- Se ha corregido un problema por el que se podía activar el libro incorrecto en un script de VBA cuando ya estaba abierto el mismo libro.

### <a name="powerpoint"></a>PowerPoint
- Varias correcciones de rendimiento y estabilidad

### <a name="outlook"></a>Outlook
- Varias correcciones de rendimiento y estabilidad.

### <a name="access"></a>Access
- Diversas correcciones de rendimiento y estabilidad.

### <a name="project"></a>Project
- Se ha corregido un problema por el que se podía bloquear el proyecto después de cambiar a la barra de tareas

</BR></BR>

## <a name="may-17-2019"></a>17 de mayo de 2019
Versión 1906 (compilación 11708.20006)

## <a name="whats-new"></a>Novedades:

### <a name="outlook"></a>Outlook

#### <a name="user-experience-updates"></a>Actualizaciones en la experiencia del usuario

Las actualizaciones que han estado en "Próximamente" ahora están aquí, presentando la cinta simplificada y una actualización visual del panel de carpetas, la lista de mensajes y el panel de lectura.

##### <a name="getting-started"></a>Introducción:

Estos cambios formarán parte de la nueva interfaz de usuario predeterminada; ha estado disponible en la opción "Próximamente" desde mediados de diciembre para 100 % de los productos.

#### <a name="customizable-simplified-ribbon"></a>Cinta simplificada personalizable

Fácilmente personalizable para el cambio entre las vistas clásica y simplificada y los comandos anclar y desanclar.

##### <a name="getting-started"></a>Introducción:

Los usuarios pueden acceder a la cinta de opciones simplificada activando Próximamente (al principio) y haciendo clic en los corchetes angulares de la cinta de opciones para alternar entre la cinta clásica de varias líneas y la nueva cinta simplificada de una sola línea.

##### <a name="scenarios-to-try"></a>Escenarios que puede probar:

Cambiar de la cinta de opciones clásica a la simplificada

#### <a name="pick-your-favorite-action"></a>Elija su acción favorita

¿No usa Etiquetar ni Eliminar? ¿Qué hay de Archivar o Marcar como leído? Personalice el menú de acciones rápidas con los comandos que use más frecuentemente.

##### <a name="getting-started"></a>Introducción:

Para seleccionar las acciones rápidas, haga clic con el botón derecho en un correo electrónico en la lista de mensajes para que aparezca el menú contextual. Después, haga clic en "Establecer acciones rápidas...".

##### <a name="scenarios-to-try"></a>Escenarios que puede probar:

Cambiar los valores predeterminados de marcar y eliminar a archivar, mover, marcar como leído o ninguno para una lista de mensajes más limpia

#### <a name="relaxed-or-tighter-layout-you-choose"></a>¿Quiere que su diseño tenga un espaciado menor o mayor? Usted elige

Usar un espaciado menor le permite decidir si quiere más espacio entre los elementos o un diseño más ajustado para ver más elementos.

##### <a name="getting-started"></a>Introducción:

Pestaña vista, casilla Usar un espaciado menor (en el grupo Mensajes de la cinta clásica, Configuración de la vista actual para la cinta simplificada)

##### <a name="scenarios-to-try"></a>Escenarios que puede probar:

Use Outlook para clasificar y escribir correos electrónicos con y sin la configuración habilitada. Con el espaciado menor activado, se ajustará el tamaño de los controles en cada página y se simplificará el uso de los controles en los formularios de redacción.

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a>Eliminación de entradas duplicadas de elementos usados más recientemente al usar el cliente de sincronización de Onedrive

Permitir una mejor integración con el cliente de sincronización de onedrive con datos adjuntos en la nube eliminando las entradas duplicadas de elementos usados más recientemente y habilitar la conexión más rápida como el comportamiento de copia para los datos sincronizados

##### <a name="getting-started"></a>Introducción:

Si usa el Cliente de sincronización de OneDrive, dejará de ver duplicados de archivos en la lista de elementos usados más recientemente en Adjuntar archivo.

##### <a name="scenarios-to-try"></a>Escenarios que puede probar:

Habilitar el Cliente de sincronización de OneDrive y usar el menú Adjuntar archivo en la versión de escritorio de Outlook

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a>Sincronización de carpetas compartidas mejorada para buzones con muchas carpetas

Durante años, Outlook se ha limitado a un máximo de 500 carpetas al sincronizar los buzones compartidos. Con este cambio Outlook se ha mejorado para sincronizar de forma que ya no encontrará este límite de 500 carpetas.

##### <a name="getting-started"></a>Introducción:

Cree 1 000 carpetas en un buzón, conceda acceso a otra persona al buzón, cree un perfil de Outlook para "otra persona" y compruebe que la sincronización funciona.

### <a name="word"></a>Word

#### <a name="erase-just-a-little-bit"></a>Borrar solo un poco.

##### <a name="getting-started"></a>Introducción:

Vaya a la pestaña Dibujar. Seleccione la lista desplegable Borrador. Elija Borrador pequeño o Borrador mediano.

##### <a name="scenarios-to-try"></a>Escenarios que puede probar:

Vaya a la pestaña Dibujar. Seleccione un lápiz. Dibuje un trazo de lápiz. Seleccione la lista desplegable Borrador. Elija Borrador pequeño o Borrador mediano. Borre solo una parte del trazo de lápiz.

## <a name="notable-fixes"></a>Correcciones notables:

### <a name="all"></a>Todo 
- Se ha corregido un problema que podría impedir que algunos usuarios guardasen como PDF.
- Se ha corregido un problema que podría afectar a los usuarios que guardan archivos grandes en un sistema de 32 bits.

### <a name="word"></a>Word 
- Se ha mejorado significativamente la respuesta de la característica de dictado.

### <a name="excel"></a>Excel
- Se ha corregido un problema por el que los eventos de doble clic podrían dar error en los dispositivos de pantalla táctil.
- Se ha corregido un problema que podría impedir que algunos usuarios pudieran editar macros de VBA.
- Se ha corregido un problema que podría afectar al rendimiento al usar segmentaciones de datos.

### <a name="powerpoint"></a>PowerPoint
- Varias correcciones de rendimiento y estabilidad

### <a name="outlook"></a>Outlook
- Se ha corregido un problema por el que podría mostrarse la plantilla incorrecta de lo que se ha seleccionado.

### <a name="access"></a>Access
- Se ha corregido un problema por el que al usar el generador de zoom para mostrar texto enriquecido largo podría ser difícil de leer.

### <a name="project"></a>Project
- Varias correcciones de rendimiento y estabilidad.

</BR></BR>

## <a name="may-10-2019"></a>10 de mayo de 2019
Version 1906 (compilación 11702.20000)

## <a name="whats-new"></a>Novedades:

### <a name="outlook"></a>Outlook

**Encajar más mensajes en la pantalla:** seleccione Ver > Usar espaciado más estrecho para ajustar el espaciado entre mensajes.

## <a name="notable-fixes"></a>Correcciones notables:

### <a name="all"></a>Todo
- Se ha corregido un problema por el que el cuadro de diálogo Guardar como podría mostrar la ruta de acceso incorrecta.

### <a name="word"></a>Word 
- Se ha corregido un problema por el cual no se insertaban algunas selecciones de Tell Me

### <a name="excel"></a>Excel
- Varias correcciones de rendimiento y estabilidad.

### <a name="powerpoint"></a>PowerPoint
- Varias correcciones de rendimiento y estabilidad

### <a name="outlook"></a>Outlook
- Varias correcciones de rendimiento y estabilidad.

### <a name="access"></a>Access
- Diversas correcciones de rendimiento y estabilidad.

### <a name="project"></a>Project
- Se ha corregido un problema por el que las ID de tareas podrían requerir resaltado para verse

</BR></BR>

## <a name="may-3-2019"></a>3 de mayo de 2019
Versión 1906 (compilación 11629.20008)

## <a name="whats-new"></a>Novedades:

### <a name="outlook"></a>Outlook

**Todas las opciones de cifrado en un solo lugar:** vaya a Opciones > Cifrar para elegir cómo proteger su mensaje de correo.

## <a name="notable-fixes"></a>Correcciones notables:

### <a name="all"></a>Todo
- Se ha corregido un problema por el que algunos usuarios experimentan problemas de sincronización de OneDrive para la Empresa

### <a name="word"></a>Word 
- Se ha corregido un problema por el que, en algunos casos, Word tardaba mucho tiempo en iniciarse.

### <a name="excel"></a>Excel
- Se ha corregido un problema por el que a veces se eliminaban los enlaces externos de los libros de trabajo después de actualizar a una versión más reciente de Excel
- Se ha corregido un problema por el que algunos usuarios podrían experimentar dificultades para seleccionar celdas en un libro nuevo

### <a name="powerpoint"></a>PowerPoint
- Se ha corregido un problema por el que los tamaños de fuente no eran consistentes al convertir dibujos a texto

### <a name="outlook"></a>Outlook
- Se ha corregido un problema por el que guardar un contacto de un archivo .VCF podía generar campos vacíos
- Se ha corregido un problema por el que un mensaje podía bloquearse en la carpeta de la bandeja de salida, aunque se había enviado
- Se ha corregido un problema por el cual Outlook podía fallar al ver un mensaje DRM

### <a name="access"></a>Access
- Diversas correcciones de rendimiento y estabilidad.

### <a name="project"></a>Project
- Se ha solucionado un problema por el que el editor cambiaba del chino al inglés
- Se ha corregido un problema por el cual las tareas no publicadas podían aparecer en la copia publicada de un proyecto maestro.

</BR></BR>

## <a name="april-26-2019"></a>26 de abril de 2019
Version 1905 (compilación 11617.20002)

## <a name="new-features"></a>Características nuevas

### <a name="outlook"></a>Outlook

**Las actualizaciones del calendario compartido son más rápidas:** Outlook puede actualizar los calendarios compartidos en Office 365 con la API de REST. Active la vista previa para obtener actualizaciones más rápidas y confiables en los calendarios compartidos.

### <a name="excel"></a>Excel

#### <a name="coauthoring-improvements"></a>Mejoras en la coautoría

Se ha mejorado la experiencia de coautoría al aumentar la probabilidad de que otros usuarios reciban los cambios de contenido en tiempo real.

### <a name="visio"></a>Visio

- **Exportar objetos visuales de Visio desde Power BI**: los objetos visuales de Visio para Power BI ahora se mostrarán correctamente al exportar informes de Power BI como archivos PDF, archivos de PowerPoint, etc.

## <a name="notable-fixes"></a>Correcciones notables:

### <a name="word"></a>Word 
- Varias correcciones de rendimiento y estabilidad.

### <a name="excel"></a>Excel
- Se ha corregido un problema que podría impedir ejecutar macros Solver
- Se ha corregido un problema que puede impedir que los archivos de Excel se importen a SharePoint

### <a name="powerpoint"></a>PowerPoint
- Varias correcciones de rendimiento y estabilidad

### <a name="outlook"></a>Outlook
- Varias correcciones de rendimiento y estabilidad.

### <a name="access"></a>Access
- Diversas correcciones de rendimiento y estabilidad.

### <a name="project"></a>Project
- Varias correcciones de rendimiento y estabilidad.

</BR></BR>

## <a name="april-19-2019"></a>19 de abril de 2019
Versión 1905 (compilación 11609.20002)

## <a name="whats-new"></a>Novedades:

### <a name="outlook"></a>Outlook

**Obtener sugerencias de correo electrónico cuando busca un contacto:** cuando escriba el nombre de una persona en el cuadro de búsqueda, se incluirán los mensajes de correo electrónico más relevantes con las sugerencias de búsqueda.

### <a name="excel"></a>Excel

#### <a name="improved-filled-maps-experience-using-data-types"></a>Experiencia mejorada de Mapas coropléticos con Tipos de datos

Esta característica es una mejora para los usuarios que trazan gráficos de mapas coropléticos con los tipos de datos geográficos de Excel. El beneficio para los usuarios finales será una integración más rica entre las características y una mayor precisión de la región que el usuario final quiere mostrar en el mapa. Entre otras ventajas adicionales está la capacidad de mostrar en el mapa polígonos urbanos.

##### <a name="getting-started"></a>Introducción:

- Esta característica es una mejora de las características existentes en Excel. Para usar la mejora: convertir ubicaciones en entidades enriquecidas y trazado con Mapas coropléticos. 

##### <a name="scenarios-to-try"></a>Escenarios que puede probar:

- Los usuarios pueden probar la creación de mapas de ciudades, estados, provincias, países y códigos postales. 


## <a name="notable-fixes"></a>Correcciones notables:

### <a name="all-applications"></a>Todas las aplicaciones
- Se ha corregido un problema por el que el cuadro de diálogo de Primera ejecución se mostraba al iniciar una aplicación.
- Se ha corregido un problema por el que podía faltar un vínculo de SharePoint en el cuadro de diálogo "Guardar como".
- Se ha corregido un problema por el que los usuarios veían un cuadro de diálogo "Reparar ahora" incorrecto.

### <a name="word"></a>Word 
- Se ha corregido un problema por el que algunos usuarios podían recibir un error de memoria o espacio en disco insuficiente al solicitar una fuente.
- Se ha corregido un problema por el que una ventana podía perder el foco al cambiar desde el panel de comentarios.

### <a name="excel"></a>Excel
- Varias correcciones de rendimiento y estabilidad.

### <a name="powerpoint"></a>PowerPoint
- Se ha corregido un problema que impedía el cambio de tamaño de las formas con marca.
- Se ha corregido un problema por el que PowerPoint podía bloquearse al abrir un archivo en modo de vista protegida.

### <a name="outlook"></a>Outlook
- Se ha corregido un problema que impedía que algunos usuarios seleccionasen palabras chinas.
- Se ha corregido un problema por el que las fechas de expiración no se calculaban correctamente.

### <a name="access"></a>Access
- Se ha corregido un problema que impedía que algunos usuarios usasen el Generador de macros.
- Se ha corregido un problema por el que al imprimir un informe solo se imprimía la primera página.
- Se ha corregido un problema por el que la aplicación podía bloquearse al pasar el puntero sobre un hipervínculo.
- Se ha corregido un problema que provocaba que algunos elementos apareciesen fuera de la pantalla al usar la vista Relaciones.

### <a name="project"></a>Project
- Varias correcciones de rendimiento y estabilidad.

</BR></BR>

## <a name="april-12-2019"></a>12 de abril de 2019
Versión 1905 (compilación 11601.20042)

## <a name="whats-new"></a>Novedades:

### <a name="access"></a>Access

#### <a name="get-smart-with-microsoft-graph"></a>Trabajar de forma más inteligente con Microsoft Graph

Importe o vincule a datos inteligentes y reinvente la base de datos de su escritorio con la Tecnología inteligente.

## <a name="notable-fixes"></a>Correcciones notables:

### <a name="all-applications"></a>Todas las aplicaciones
 - Se ha corregido un problema que impedía que algunos usuarios guardasen archivos en ubicaciones en la nube.
 - Se ha corregido un problema por el que en ocasiones se abría el panel incorrecto desde la cinta

### <a name="word"></a>Word 
- Varias correcciones de rendimiento y estabilidad.

### <a name="excel"></a>Excel
- Se ha corregido un problema que generaba un mensaje de error para tipos de datos vinculados cuando el libro no contenía tipos de datos vinculados.
- Se ha corregido un problema por el que los vínculos de direcciones URL de un documento de Word podían cambiar al verse de forma local o en línea.

### <a name="powerpoint"></a>PowerPoint
- Se ha corregido un problema por el que la aplicación podía bloquearse después de deshacer cambios desde la ficha de animaciones.

### <a name="outlook"></a>Outlook
- Se ha corregido un problema que impedía que algunos usuarios modificasen el campo Notas de los contactos de una carpeta pública
- Se ha corregido un problema que podía producir un conflicto entre las fechas de vencimiento y eliminación.

### <a name="access"></a>Access
- Diversas correcciones de rendimiento y estabilidad.

### <a name="project"></a>Project
- Varias correcciones de rendimiento y estabilidad.

</BR></BR>

## <a name="april-5-2019"></a>5 de abril de 2019
Versión 1904 (compilación 11527.20014)

## <a name="whats-new"></a>Novedades:

### <a name="outlook"></a>Outlook

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a>Outlook para Windows: establecer y compartir la configuración de su Bandeja de entrada Prioritarios.

Las preferencias de la Bandeja de entrada Prioritarios se almacenan en la nube para que pueda disfrutar de una experiencia coherente cuando use Outlook para Windows y Outlook en la web en cualquier equipo.

#### <a name="getting-started"></a>Introducción:

En Archivo > Opciones > pestaña General, hay una nueva preferencia para "Almacenar la configuración de Outlook en la nube". Los usuarios deberán activar la casilla para habilitar la configuración de la Bandeja de entrada Prioritarios a otras instalaciones de escritorio Outlook y OWA.

#### <a name="scenarios-to-try"></a>Escenarios que puede probar:

Cambiar la bandeja de entrada Prioritarios en la máquina que tenga activada la preferencia para configuración en la nube. Luego, navegue hasta OWA y verá que la preferencia también se ha aplicado allí. Cambie la bandeja de entrada Prioritarios en OWA y comience a usar la versión de escritorio de Outlook para ver que las preferencias están aplicadas allí también.

### <a name="word"></a>Word

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a>El modo Herramientas de aprendizaje tiene una opción adicional para más colores de páginas

Las Herramientas de aprendizaje de Word son compatibles con más colores de tema de página, lo que permite cambiar el color de fondo de la página.  Muchas personas tienen dificultades para leer con un fondo totalmente blanco o negro, por lo que hemos ampliado la elección de colores en Word para PC y Mac.

#### <a name="getting-started"></a>Introducción:

Si quiere probarlo, vaya a la pestaña Vista, seleccione Herramientas de aprendizaje y luego Color de página.

#### <a name="scenarios-to-try"></a>Escenarios que puede probar:

Si quiere probarlo, vaya a la pestaña Vista, seleccione Herramientas de aprendizaje y luego Color de página.

### <a name="excel"></a>Excel

#### <a name="elevate-creativity-with-animated-3d-models"></a>Potencie su creatividad con modelos 3D animados

Office es ahora compatible con modelos animados que se reproducirán en el editor para que pueda dar vida a sus hojas.

#### <a name="getting-started"></a>Introducción:

1. Abra Excel.
2. Inserte un modelo animado en 3D (pronto estará disponible en Remezcla, pero, por ahora, puede encontrar los modelos animados aquí: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)
3. ¡Podrá reproducir el modelo animado en el editor! Compruebe el modo de presentación de diapositivas y verá que también se reproduce en él.
4. En la cinta de formatos 3D puede explorar más escenas de animación para el modelo.

#### <a name="scenarios-to-try"></a>Escenarios que puede probar:

1. Inserte un modelo animado y vea cómo se reproduce en el editor.
2. Explore las escenas de animación disponibles en el modelo animado mediante la Galería de escenas (disponible en la cinta de opciones de Formato 3D).
3. Reproduzca y pause la animación fácilmente con la cinta de opciones, la barra flotante o la barra espaciadora.

## <a name="notable-fixes"></a>Correcciones notables:

### <a name="all-applications"></a>Todas las aplicaciones
- Se ha corregido un problema por el que el icono de la aplicación incorrecta podía aparecer para Excel en los menús contextuales.
- Se ha corregido un problema por el que el botón del menú Archivo podía desaparecer después de instalar una actualización.
- Se ha corregido un problema que podía cambiar la licencia de usuario.

### <a name="word"></a>Word 
- Se ha corregido un problema por el que el texto no se procesaba correctamente en algunos niveles de zoom.

### <a name="excel"></a>Excel
- Se ha corregido un problema por el que a los usuarios no se les solicitaba que guardaran un libro después de realizar cambios.
- Se ha corregido un problema por el que un evento BeforeSave podía no activarse si el usuario compartía el libro.
- Se ha corregido un problema por el que cambiar el tamaño de una columna a menos de 6 píxeles podía producir un mensaje de error incorrecto.
- Se ha corregido un problema por el que Excel omitía la marca Application.Visible.
- Se ha corregido un problema por el que las flechas de seguimiento permanecían en paneles inmovilizados no activos.
- Se ha corregido un problema por el que el formato de las celdas con fechas y monedas podía cambiar al abrir un libro.
- Se ha corregido un problema por el que la información sobre herramientas se movía inesperadamente.
- Se han corregido problemas de localización para el editor de Power Query.
- Se ha corregido un problema por el que un libro desaparecía de los datos adjuntos al enviarlo por correo electrónico.

### <a name="powerpoint"></a>PowerPoint
- Se ha corregido un problema por el que copiar formas llevaba más tiempo de lo esperado.

### <a name="outlook"></a>Outlook
- Se ha corregido un problema por el que Outlook podía bloquearse al usar la herramienta de dibujo.
- Se ha corregido un problema de localización al redactar correos electrónicos html.
- Se ha corregido un problema por el que los usuarios tenían dificultades para seleccionar el panel inferior.

### <a name="access"></a>Access
- Diversas correcciones de rendimiento y estabilidad.

### <a name="project"></a>Project
- Varias correcciones de rendimiento y estabilidad.

</BR></BR>

## <a name="march-22-2019"></a>22 de marzo de 2019
Versión 1904 (compilación 11514.20004)

## <a name="new-features"></a>Características nuevas

- **Controles de privacidad:** nuevos controles para datos de diagnóstico y experiencias conectadas, actualizados y mejorados. Más información <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json>

- **Los iconos de Office tienen un nuevo aspecto:** los iconos de Office se han rediseñado para reflejar las sencillas, inteligentes y eficaces experiencias de Office.

## <a name="notable-fixes"></a>Correcciones notables:

### <a name="word"></a>Word 
- Se ha corregido un problema por el que la interfaz de usuario mostraba constantemente "Comprobación de cambios".

### <a name="excel"></a>Excel
- Se ha corregido un problema por el que la aplicación podía bloquearse después de mover una hoja de cálculo.
- Se ha corregido un problema por el que la aplicación podía bloquearse después de guardar como PDF.
- Se ha corregido un problema por el que el cuadro de diálogo guardar no aceptaba algunos caracteres coreanos.

### <a name="powerpoint"></a>PowerPoint
- Varias correcciones de rendimiento y estabilidad

### <a name="outlook"></a>Outlook
- Varias correcciones de rendimiento y estabilidad.

### <a name="access"></a>Access
- Se ha corregido el mensaje de error en Access en el que se creaba un acceso directo adicional a Access.
- Se ha corregido un problema por el que los datos de un SharePoint vinculado no se mostraba correctamente.

### <a name="project"></a>Project
- Se ha solucionado un problema por el que la configuración del idioma cambiaba del chino al inglés.
- Se ha corregido un problema por el que la aplicación podía bloquearse cuando se sincronizaba con SharePoint.

</BR></BR>

## <a name="march-15-2019"></a>15 de marzo de 2019
Versión 1904 (compilación 11504.20000)

## <a name="whats-new"></a>Novedades:

### <a name="word"></a>Word

#### <a name="focus-mode"></a>Modo Focalizado

Cambie al modo Focalizado en el menú Vista para eliminar las distracciones y concentrarse en su trabajo. Solo para suscriptores de Office 365.

#### <a name="getting-started"></a>Introducción:

Vaya a la pestaña Vista, luego toque el botón «Foco» en la barra de estado. 

#### <a name="scenarios-to-try"></a>Escenarios que puede probar:

Descubra el Modo Focalizado y trabaje sin distracciones

## <a name="notable-fixes"></a>Correcciones notables:

### <a name="word"></a>Word 
- Se ha corregido un problema por el que las imágenes de un documento guardado como PDF tendían el valor incorrecto de PPP.

### <a name="excel"></a>Excel
- Varias correcciones de rendimiento y estabilidad.

### <a name="powerpoint"></a>PowerPoint
- Se ha corregido un problema por el que el panel de comentarios no se abría ni se cerrara correctamente.
- Se ha corregido un problema por el que la aplicación podía bloquearse al eliminar un vídeo.
- Se ha corregido un problema por el que en algunos casos la aplicación no se iniciaba.

### <a name="outlook"></a>Outlook
- Se ha corregido un problema por el que las confirmaciones de lectura eran incorrectas cuando se veían en japonés.

### <a name="access"></a>Access
- Diversas correcciones de rendimiento y estabilidad.

### <a name="project"></a>Project
- Varias correcciones de rendimiento y estabilidad.

</BR></BR>

## <a name="march-8-2019"></a>8 de marzo de 2019 
Versión 1903 (compilación 11425.20036)

## <a name="whats-new"></a>Novedades:

### <a name="word"></a>Word

### <a name="find-what-youre-looking-for-with-microsoft-search"></a>Encontrar lo que se está buscando con Búsqueda de Microsoft

Con Búsqueda de Microsoft, puede buscar todos los archivos, acciones, personas y la ayuda que necesite para realizar el trabajo.

#### <a name="getting-started"></a>Introducción:

- La característica se destaca en el encabezado en la parte superior de la interfaz de usuario.

#### <a name="scenarios-to-try"></a>Escenarios que puede probar:

- Busque una universidad, un documento reciente o los comandos de la cinta de opciones que usa con mayor frecuencia
- Busque un tema o un argumento para obtener más información sobre ellos.
- 
#### <a name="coauthoring"></a>Coautoría

¿Está cansado de no tener acceso a documentos que contienen macros? Ahora, los archivos docm de OneDrive para la empresa permiten la edición simultánea de varios autores.

#### <a name="getting-started"></a>Introducción:

No es necesario que el usuario presione los botones en la UI para obtener acceso a esta característica. Está habilitada de forma predeterminada en los archivos .docm de OneDrive para la empresa.
Por lo tanto, el usuario solo tiene que guardar un archivo docm en OneDrive para la empresa.

#### <a name="scenarios-to-try"></a>Escenarios que puede probar:

Cree un archivo docm en OneDrive para la empresa, compártalo con sus compañeros de trabajo ¡y comiencen a colaborar!

## <a name="notable-fixes"></a>Correcciones notables:

### <a name="word"></a>Word 
- Hemos resuelto un problema de bloqueo producido al presionar "ESC" en Opciones
- Se ha corregido un problema de bloqueo que se producía al responder a comentarios
- Se ha corregido un problema con copiar y pegar desde Word a PowerPoint Online

### <a name="excel"></a>Excel
- Se ha corregido un problema por el que al copiar una celda en Excel se producía un uso elevado de la CPU cuando al abrir un documento protegido y un documento editable

### <a name="powerpoint"></a>PowerPoint
- Varias correcciones de rendimiento y estabilidad

### <a name="outlook"></a>Outlook
- Se ha corregido un problema por el que la búsqueda de Outlook no respetaba la ordenación cronológica seleccionada
- Se ha corregido un problema por el que el botón de la cinta de flujo de trabajo "Abrir esta tarea" dejaba de responder para determinados mensajes de correo electrónico
- Se ha corregido un problema por el que Outlook no eliminaba las salas locales después de que los usuarios seleccionasen una sala disponible en el Buscador de salas

### <a name="access"></a>Access
- Se ha corregido el cuadro de diálogo de importación/exportación guardado que tenía texto blanco sobre fondo blanco en el tema oscuro
- Se ha corregido un problema por el que los usuarios no podían establecer la propiedad de Control de pantalla de un campo Sí/No como Cuadro de texto en el diseño de tabla

### <a name="project"></a>Project
- Varias correcciones de rendimiento y estabilidad.


## <a name="march-1-2019"></a>1 de marzo de 2019 
Versión 1903 (compilación 11414.20014)

## <a name="whats-new"></a>Novedades

### <a name="word"></a>Word

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a>El mismo color para control de cambios, comentarios y colaboración en tiempo real

Las correcciones de nuestro producto ahora aseguran que los comentarios, control de cambios y el cursor para un colaborador se muestren en el mismo color.

#### <a name="getting-started"></a>Introducción:

Abra un documento de OneDrive o SharePoint que ya hayan abierto otros usuarios. Compruebe que el control de cambios y los comentarios del usuario tienen el mismo color que el cursor de ese usuario.

#### <a name="scenarios-to-try"></a>Escenarios que puede probar:

Abra un documento de OneDrive o SharePoint que ya hayan abierto otros usuarios. Compruebe que el control de cambios y los comentarios del usuario tienen el mismo color que el cursor de ese usuario.

## <a name="notable-fixes"></a>Correcciones notables:

### <a name="word"></a>Word 
- Hemos resuelto un problema de bloqueo producido al presionar "ESC" en Opciones
- Se ha corregido un problema con copiar y pegar desde Word a PowerPoint Online

### <a name="excel"></a>Excel
- Se ha corregido un problema por el que al copiar una celda en Excel se producía un uso elevado de la CPU cuando al abrir un documento protegido y un documento editable

### <a name="powerpoint"></a>PowerPoint
- Se ha corregido un problema con el tamaño de la imagen de diapositiva al usar @Menciones en PowerPoint

### <a name="outlook"></a>Outlook
- Se ha corregido un problema por el que la búsqueda de Outlook no respetaba la ordenación cronológica seleccionada
- Se ha corregido un problema por el que el botón de la cinta de flujo de trabajo "Abrir esta tarea" dejaba de responder para determinados mensajes de correo electrónico
- Se ha corregido un problema por el que Outlook no eliminaba las salas locales después de que los usuarios seleccionasen una sala disponible en el Buscador de salas

### <a name="access"></a>Access
- Se ha actualizado el texto del mensaje que se mostraba al confirmar una nueva vinculación de las tablas con un origen de datos
- Se ha corregido el cuadro de diálogo de importación y exportación guardada que tenía texto blanco sobre fondo blanco en el tema oscuro
- Se ha corregido un problema por el que los usuarios no podían establecer la propiedad de Control de pantalla de un campo Sí/No como Cuadro de texto en el diseño de tabla

### <a name="project"></a>Project
- Varias correcciones de rendimiento y estabilidad.

</BR></BR>



## <a name="february-15-2019"></a>15 de febrero de 2019 
Versión 1903 (compilación 11310.20016)

## <a name="whats-new"></a>Novedades:

### <a name="powerpoint"></a>PowerPoint


### <a name="morph-transition-enhancements---morph-by-name"></a>Mejoras de la transición Transformación: Transformación por nombre

Especifique las formas que quiera transformar.

#### <a name="getting-started"></a>Introducción:

- Para conseguir que Transformación trate dos objetos como el mismo objeto, el usuario puede cambiar el nombre de las formas con el panel de selección.
- El nombre debe ser precedido por “!!” (dos signos de exclamación) para que Transformación lo use para reemplazar el comportamiento de coincidencia predeterminado, por ejemplo, "!!Nombre"
- Los usuarios pueden seguir cambiando el nombre de las formas con cualquier nombre que no empiece con "!!" sin tener que preocuparse de que esto cambie el funcionamiento de Transformación

#### <a name="scenarios-to-try"></a>Escenarios que puede probar:

- Inserte una forma en una diapositiva, por ejemplo, un rectángulo
- Cree una nueva diapositiva 

- Inserte una forma diferente de la segunda diapositiva, por ejemplo, un triángulo
- Abra el panel de selección, cambie el nombre del rectángulo de la diapositiva 1 a "!!forma" y haga lo mismo con el triángulo de la diapositiva 2: "!!forma"
- Aplique Transformación en la diapositiva 2

</BR>

### <a name="morph-transition-enhancements---smartart"></a>Mejoras de la transición Transformación: SmartArt

Transformación de SmartArt con transiciones más fluidas

#### <a name="getting-started"></a>Introducción:

Use Transformación del mismo modo que lo haría con SmartArt

#### <a name="scenarios-to-try"></a>Escenarios que puede probar:

- Inserte un SmartArt en una diapositiva
- Duplique la diapositiva
- Ajuste el tamaño, cambie o mueva el gráfico SmartArt en la diapositiva duplicada
- Aplique Transformación en la diapositiva duplicada

</BR>

### <a name="morph-transition-enhancements---tables"></a>Mejoras de la transición Transformación: Tablas

Transformación de las tablas con transiciones más fluidas

#### <a name="getting-started"></a>Introducción:
Use Transformación del mismo modo que lo haría con las tablas

#### <a name="scenarios-to-try"></a>Escenarios que puede probar:

- Inserte una tabla en una diapositiva
- Duplique la diapositiva
- Ajuste el tamaño, cambie o mueva la tabla en la diapositiva duplicada
- Aplique Transformación en la diapositiva duplicada

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a>Word, Excel, PowerPoint, OneNote, Access, Project, Publisher y Visio

### <a name="seamlessly-switch-between-accounts"></a>Cambiar de una cuenta a otra sin problemas

El nuevo administrador de cuentas muestra todas sus cuentas personales y de trabajo en un solo lugar y le permite cambiar entre ellas. Con esta experiencia actualizada puede ver claramente con qué cuenta ha iniciado sesión y, ahora, puede alternar entre cuentas personales y de trabajo sin tener que cerrar sesión o preocuparse de complejos cuadros de diálogo.


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a>Escenarios que puede probar:
- Cambiar de una cuenta a otra
- Agregar una nueva cuenta [Nota: le recomendamos que vaya a Archivo | Cuenta | Servicios conectados y elimine todos los servicios conectados con cuentas de trabajo o viceversa]
- Cerrar la sesión de una cuenta
</BR>

## <a name="notable-fixes"></a>Correcciones notables:

### <a name="word"></a>Word 
- Se ha corregido un problema con la versión preliminar de contexto para tablas e imágenes

### <a name="excel"></a>Excel
- Se ha corregido un problema por el que el texto en el campo de búsqueda de filtro automático aparece en color blanco en el tema Negro
- Se ha corregido un problema de consentimiento dentro de la interfaz de usuario en el nuevo complemento de Office

### <a name="powerpoint"></a>PowerPoint
- Se ha corregido un problema con la ampliación automática de la pantalla durante la presentación de diapositivas en portátiles y tabletas.

### <a name="outlook"></a>Outlook
- Se ha corregido un problema con la apariencia del botón Enviar a OneNote

### <a name="access"></a>Access
- Diversas correcciones de rendimiento y estabilidad.

### <a name="project"></a>Project
- Varias correcciones de rendimiento y estabilidad.


</BR></BR>
## <a name="february-11-2019"></a>11 de febrero de 2019
Versión 1903 (compilación 11330.20014)


## <a name="notable-fixes"></a>Correcciones notables:

### <a name="word"></a>Word 
- Se ha corregido un problema por el que algunos estilos personalizados no podían aplicarse en Word online
- Se han corregido los problemas de vista previa de contexto con objetos enriquecidos en Word
- Se ha corregido un problema por el que al pegar listas Word se bloqueaba.

### <a name="excel"></a>Excel
- Se ha corregido un problema por el que los espacios anexados después de formatos de número se dejaban de ver cuando no había ningún símbolo de moneda
- Se ha corregido un problema con la detección automática de cotizaciones

### <a name="powerpoint"></a>PowerPoint
- Varias correcciones de rendimiento y estabilidad

### <a name="outlook"></a>Outlook
- Varias correcciones de rendimiento y estabilidad.

### <a name="access"></a>Access
- Diversas correcciones de rendimiento y estabilidad.

### <a name="project"></a>Project
- Varias correcciones de rendimiento y estabilidad.

</BR></BR>


## <a name="february-1-2019"></a>1 de febrero de 2019 
Versión 1902 (compilación 11326.20000)


## <a name="notable-fixes"></a>Correcciones notables

### <a name="word"></a>Word 
- Se ha corregido un problema con el tamaño de las celdas en una tabla de Excel incrustada
- Se ha corregido un problema relacionado con copiar y pegar formas en un Lienzo de dibujo

### <a name="excel"></a>Excel
- Se ha corregido un problema con la apertura de archivos de la aplicación Excel Web
- Se ha corregido un problema por el que al intentar guardar archivos CSV como .XLSX se producía un error debido al tamaño del nombre de archivo
- Se ha corregido el menú contextual para mostrar las opciones del mismo

### <a name="powerpoint"></a>PowerPoint
- Hemos corregido un error por el que los usuarios no podían usar el método abreviado de teclado ctrl + alt + 7 o ctrl + alt + 8 para introducir corchetes
- Se ha corregido un problema por el que insertar un vídeo local en el PPT reducía el espacio del disco "C"
- Se ha corregido el botón Publicar en Microsoft Stream, ya que algunos usuarios no podían verlo

### <a name="outlook"></a>Outlook
- Se ha corregido un problema con la vista de tareas del calendario, ya que no se mostraba correctamente el asunto de la tarea.

### <a name="access"></a>Access
- Hemos corregido un problema de escalada con los gráficos 

### <a name="project"></a>Project
- Varias correcciones de rendimiento y estabilidad.
