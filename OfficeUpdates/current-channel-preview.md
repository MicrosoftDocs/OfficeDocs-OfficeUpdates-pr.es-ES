---
title: Notas de la versión del canal actual (versión preliminar)
ms.author: anankani
author: anankani
manager: anankani
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Proporcionar a los participantes del Modo aplazado de Insider la lista más reciente de las nuevas características, correcciones o problemas conocidos
ms.openlocfilehash: 98f6e608b3337cde7e20143f1612814b0398e396
ms.sourcegitcommit: 268322e5705199bb27cd07ab6e3fdabd1e20e334
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 07/09/2021
ms.locfileid: "53347963"
---
# <a name="release-notes-for-office-current-channel-preview"></a>Notas de la versión del canal actual de Office (versión preliminar)

En este artículo hay notas de la versión para las compilaciones del Canal actual (versión preliminar) de las versiones de escritorio de Word, Excel, PowerPoint, Outlook, Access, Project Y Teams para Windows. Todas las semanas se incluyen las nuevas características, correcciones importantes y los problemas principales de mayor interés para usted. Tenga en cuenta que a menudo publicamos características (y a veces incluso correcciones) para el Canal actual (versión preliminar) durante un período de tiempo. Esto nos permite asegurarnos de que todo funciona correctamente antes de publicar la característica para un público más amplio. Por tanto, si a continuación no ve algo descrito, no se preocupe, lo recibirá con el tiempo.  


> [!NOTE]
> - La fecha de publicación de las notas de versión pueden no coincidir con la fecha real de lanzamiento de la compilación.
> - Las características de Microsoft Teams pueden diferir de la última versión preliminar del Canal actual publicada ya que tienen una cadencia de publicación más frecuente.

[//]: # (NO ELIMINAR)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

## <a name="version-2107-july-08"></a>Versión 2107: 08 de julio
*Versión 2107 (Compilación 14228.20070)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Solicitud de reunión REST reenviada:** Permite a los usuarios reenviar una reunión rechazada previamente para calendarios compartidos REST.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="word"></a>Word

- Se ha corregido un problema que provocaba que las tarjetas de comentarios junto al lienzo de Word tuvieran un tamaño incorrecto.



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2107-july-06"></a>Versión 2107: 06 de julio
*Versión 2107 (Compilación 14228.20044)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Tipos de archivo adicionales admitidos para el escenario de guardar como:** Además de guardar archivos, puede guardar archivos en otros tipos de archivo.

- **Administración pública: envío de datos de auditoría sobre el etiquetado de confidencialidad a los administradores de M365.** Cuando los usuarios apliquen, cambien o eliminen las etiquetas de confidencialidad en sus documentos y correos electrónicos, Office enviará datos de auditoría al back-end de auditoría de M365 para que los administradores los vean. Esta es una funcionalidad silenciosa (sin interfaz de usuario) para beneficio del administrador.

### <a name="powerpoint"></a>PowerPoint

- **Tipos de archivo adicionales admitidos para el escenario de guardar como:** Además de guardar archivos, puede guardar archivos en otros tipos de archivo.

- **Administración pública: envío de datos de auditoría sobre el etiquetado de confidencialidad a los administradores de M365.** Cuando los usuarios apliquen, cambien o eliminen las etiquetas de confidencialidad en sus documentos y correos electrónicos, Office enviará datos de auditoría al back-end de auditoría de M365 para que los administradores los vean. Esta es una funcionalidad silenciosa (sin interfaz de usuario) para beneficio del administrador.

### <a name="word"></a>Word

- **Tipos de archivo adicionales admitidos para el escenario de guardar como:** Además de guardar archivos, puede guardar archivos en otros tipos de archivo.

- **Administración pública: envío de datos de auditoría sobre el etiquetado de confidencialidad a los administradores de M365.** Cuando los usuarios apliquen, cambien o eliminen las etiquetas de confidencialidad en sus documentos y correos electrónicos, Office enviará datos de auditoría al back-end de auditoría de M365 para que los administradores los vean. Esta es una funcionalidad silenciosa (sin interfaz de usuario) para beneficio del administrador.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Acceso

- Se ha corregido un problema que podía hacer que las aplicaciones que usan la API de ODBC de motor de base de datos de Access se cerraran de forma inesperada.


- Se ha corregido un problema que podía hacer que las aplicaciones que usan la API de OLEDB de motor de base de datos de Access con una base de datos que contiene vínculos a listas de SharePoint se cerraran de forma inesperada.


### <a name="excel"></a>Excel

- Se ha corregido un problema por el que se producía una excepción de una ejecución de CFR.


- Se ha corregido un problema por el que los valores del eje del gráfico no se podían cambiar si los separadores de miles y decimales usaban el mismo símbolo.


- Hemos corregido un problema que hacía que a algunos usuarios les aparecieran entradas adicionales en la lista del complemento de Excel.


- Hemos corregido un problema que causaba que el libro apareciera en la parte superior de la lista Recientes al guardar en una biblioteca de documentos SPO.


- Se ha corregido un problema por el que se abría una ventana duplicada en blanco cuando se habilitaban los complementos heredados.


### <a name="onenote"></a>OneNote

- Hemos corregido un problema que provocaba que copiar un vínculo a un párrafo no siempre redirigiera a la página correcta.


### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que las opciones de traducción se deshabilitaran para algunos usuarios.  Los clientes que experimentaron este error habrían visto sus opciones de traducción deshabilitadas al navegar a Archivo -> Opciones -> Idioma. Debido a esto, no habrían podido cambiar su idioma de traducción preferido y otras opciones relacionadas con la traducción.


- Se ha corregido un problema relacionado con el estado de respuesta "no se pudo cargar". La marca de respuesta predeterminada se estableció en "None". No mostramos ninguna cadena en la interfaz de usuario al desplazar el puntero sobre un calendario en el que no teníamos permisos de edición.


- Se ha corregido un problema por el que el aumento de texto predeterminado incluye el escalado de texto, por lo que no es necesario usar otra llamada de LayoutChanged.


- Se ha corregido un problema por el que las sugerencias de correo electrónico no se mostraban para las direcciones con definición.


- Hemos agregado una clave de registro para permitir que el formulario de Correo de voz se muestre en la interfaz de usuario en el escritorio de Outlook, debido a la retirada de la mensajería unificada en Exchange Online (https://techcommunity.microsoft.com/t5/exchange-team-blog/retiring-unified-messaging-in-exchange-online/ba-p/608991). Para los usuarios, empresas y organizaciones que desean que aparezca el formulario de Correo de voz, debe establecerse la siguiente clave de registro: [HKEY_CURRENT_USER\SOFTWARE\Microsoft\Office\Outlook\Addins] "AllowVoicemailForm"=dword:00000001


- Se ha corregido un problema por el que los usuarios con un gran número de grupos experimentaban una falta de respuesta al iniciar Outlook.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema relacionado con los nodos de SmartArt que tenían la opción Cambiar forma deshabilitada.


### <a name="project"></a>Project

- Se ha corregido un problema por el que las interacciones creadas en Project Web App podían no cargarse correctamente en el cliente de escritorio de Project si el nombre del recurso tenía caracteres especiales, como un punto y coma.


- Se ha corregido un problema por el que, cuando la opción de proyecto "El proyecto debería calcular los costes" está deshabilitada, los valores de coste por fases temporales podrían no haberse establecido en la línea base correctamente para los recursos de tipo de coste.


- Se ha corregido un problema por el que los campos personalizados de empresa de nivel de proyecto con tablas de búsqueda no mostraban un valor en el cliente de escritorio de Project.


- Se ha corregido un problema por el que, al guardar un proyecto local en Project Web App, se podía cambiar una línea base guardada anteriormente.


### <a name="visio"></a>Visio

- Este problema de navegación de hipervínculo se ha corregido en la compilación más reciente. Los usuarios pueden seguir teniendo acceso a los hipervínculos sin problemas para navegar al archivo vinculado deseado ubicado en su OneDrive para la Empresa, usando <CTRL> + clic en la forma con el hipervínculo.


### <a name="word"></a>Word

- Se ha corregido un problema que provocaba que, al habilitar el guardado automático, las ediciones recientes desaparecieran temporalmente.


- Se ha corregido un problema que mejora la integración con el nuevo panel de comentarios en Word y JAWS, un popular software de lectura de pantalla.


- Se ha corregido un problema relacionado con el uso de un CommentId diferente de lTagNil para la selección y el resaltado borrados.


- Se ha corregido un problema por el que los comentarios pasaban a ser de solo lectura durante la colaboración.


- Se ha corregido un problema de desplazamiento en el panel de comentarios.


- Se ha corregido un problema por el que la cola de descarga dejaba de responder.


- Se ha corregido un problema por el que el texto de encabezado o pie de página no era claramente visible en la vista previa de impresión cuando el tema de Office estaba establecido en negro.


- Hemos corregido un problema por el cual aparecían cuadros al usar el complemento Manuscript Paper de Microsoft Word.


- Hemos corregido un problema que causaba que algunas páginas aparecieran en blanco en la vista previa de impresión.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office


- Hemos corregido un problema en el que los hipervínculos que incluyen dígitos se rompen al redactar un mensaje en Outlook en un idioma de derecha a izquierda.


- Se ha corregido un problema de localización por el que ahora en-gb, fr-ca y es-mx coincidirán con sus respectivas versiones primarias.


- Se ha corregido un problema por el que la configuración de uso compartido entre OOID y ExCatalog ya no era posible, por ejemplo, para las actualizaciones de configuración de complementos web para webextension.xml, ya que se crea un nuevo archivo webextension. Solo se tuvo acceso al anterior cuando el complemento se implementó en el método original o se desactivó la nueva comparación de referencias de la solución.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2106-june-29"></a>Versión 2106: 29 de junio
*Versión 2106 (Compilación 14131.20278)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba problemas de rendimiento en dispositivos ARM64.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2106-june-25"></a>Versión 2106: 25 de junio
*Versión 2106 (compilación 14131.20250)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que las opciones de traducción se deshabilitaran para algunos usuarios.  Los clientes que experimentaron este error habrían visto sus opciones de traducción deshabilitadas al navegar a Archivo -> Opciones -> Idioma. Debido a esto, no habrían podido cambiar su idioma de traducción preferido y otras opciones relacionadas con la traducción.


- Se ha corregido un problema que provocaba que los usuarios de la opción Mejoras de calendario compartido que tuvieran muchos calendarios compartidos experimentaran algunos problemas de rendimiento.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema por el que un usuario no podía escribir credenciales en un cuadro de diálogo de Seguridad de Windows para abrir un archivo, debido a un diálogo específico de PowerPoint.


### <a name="visio"></a>Visio

- Ahora funcionarán los vínculos de SPO/ODB con acceso de invitado.


### <a name="word"></a>Word

- Se ha corregido un problema para conservar citas en un archivo docx protegido con contraseña.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2106-june-21"></a>Versión 2106: 21 de junio
*Versión 2106 (Compilación 14131.20194)*
* Varias correcciones de errores y rendimiento.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Lea mensajes con menos distracciones:** Haga que sea más fácil concentrarse en los mensajes con espaciado de texto, colores de página, ancho de columna y foco de línea personalizados, activando Lector inmersivo.

- **Último inicio de sesión/Inicio de sesión sospechoso:** Outlook ahora le indica cuándo y dónde iniciado sesión por última vez en su cuenta y le avisa si se detecta actividad de inicio de sesión sospechosa


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

## <a name="version-2106-june-14"></a>Versión 2106: 14 de junio
*Versión 2106 (Compilación 14131.20162)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="word"></a>Word

- **Buscar con la voz:** Pulse o haga clic en el micrófono de la barra de búsqueda para usar su voz en Word para buscar comandos, contenido y mucho más.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Corrige un problema que hacía que a algunos usuarios les aparecieran entradas adicionales en la lista del complemento de Excel.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2106-june-07"></a>Versión 2106: 7 de junio
*Versión 2106 (Compilación 14131.20012)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Hemos quitado "RichValue" de Range.valueTypes. Los tipos de datos vinculados devolverán ahora «Error» para que coincida con el valor de "#VALUE!" devuelto por Range.values.

- Hemos corregido un problema que impide que el Administrador de nombres abra libros con un gran número de nombres ocultos.


- Se ha corregido un problema que afectaba al rendimiento de VLOOKUP e ÍNDICE/COINCIDIR al rellenar una gran cantidad de datos.


- Se ha corregido un problema que causaba que las matrices dinámicas no actualizaran los valores de celda cuando se hace referencia a las funciones RealTimeData.


- Se ha corregido un problema que causaba que el modo de sobrescritura de IME no escribiera sobre caracteres y los dejara al final de la cadena.


- Se ha corregido un problema relacionado con el desplazamiento con dos dedos al usar inmovilizar paneles.


- Se ha corregido un problema relacionado con problemas de memoria al imprimir en impresoras de formato grande.


### <a name="outlook"></a>Outlook

- Hemos corregido un problema que provocaba que los usuarios vieran los mensajes que requieren acción actualizándose constantemente o revertidos a los encabezados después de la descarga, cuando se ejecute el modo Descargar solo encabezados.


- Hemos corregido un problema por el que los usuarios no podían mover elementos entre carpetas en versiones de Outlook con licencia "no comercial".


- Hemos corregido un problema que causaba que los usuarios experimentasen un cierre inesperado al quitar carpetas de un almacén de archivos.


- Se ha corregido un problema que causaba que algunos usuarios experimentasen un cierre inesperado al cargar tarjetas de persona.


- Hemos corregido un problema que provocaba que el selector de usuarios en Outlook se expandiera hacia arriba en lugar de hacia abajo para los usuarios con una licencia permanente.


- Hemos corregido un problema que causaba que la opción de comentarios no se mostrara a los usuarios de la versión preliminar de Office Perpetual 2021.


- Hemos corregido un problema que causaba que los usuarios viesen copias de todos los elementos enviados en su carpeta Bandeja de salida.


- Hemos corregido un problema que causaba que los usuarios de dominios personalizados vean un mensaje de advertencia sobre los permisos al pegar un vínculo en un mensaje de correo electrónico.


- Hemos agregado una clave del Registro que deshabilita la nueva experiencia del Buscador de salas (la misma experiencia que en Outlook para Web) y habilita el Buscador de salas heredado con Horas sugeridas.

    Clave del Registro:

    >HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar </br>
    > REG_DWORD “ShowLegacyRoomFinder”</br></br>
    > 0 (predeterminado): Outlook usa la nueva experiencia con tecnología del Buscador de salas de OWA cuando el usuario hace clic en el botón "Buscador de salas" para buscar salas disponibles.  </br>
    > 1: Outlook usa la interfaz de usuario del Buscador de salas heredada para buscar salas disponibles </br>


- Hemos corregido un problema que causaba un cierre inesperado al usar lectura en voz alta con otras versiones de Windows.


- Hemos corregido un problema que causaba que los usuarios experimentaran un bloqueo al quitar carpetas de un almacén de archivos.


- Se ha corregido un problema que causaba que algunos usuarios experimentasen un bloqueo al cargar tarjetas de persona.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema que impedía copiar desde el panel de notas del orador mientras estaba en modo solo lectura.


- Hemos corregido un problema para garantizar que los archivos guardados con el botón "Reintentar guardar" en la barra de bus se agreguen a la lista Archivos recientes.


- Se ha corregido un problema por el que la opción de Reutilizar diapositivas no estaba disponible para unos pocos usuarios.


### <a name="project"></a>Project

- Hemos corregido un problema por el que las asignaciones de las tareas programadas manualmente podían trasladarse a una fecha incorrecta.


- Hemos corregido un problema por el que la reserva de recursos no respondía y no se podía abrir.


- Hemos corregido un problema por el que se generaba un error si se creaba una fórmula de campo personalizada que utilizaba las funciones ProjectDate */ProjectDur* con parámetros de fecha u hora específicos.


### <a name="word"></a>Word

- Corrige un problema que hace que un comentario quede temporalmente en blanco después de publicarlo.


- Se ha corregido un problema en el que se mostraba un mensaje de error al Guardar como incluso después de que un usuario decidiese descartar cambios.


- Se ha corregido un problema que impedía que las imágenes se publicaran en comentarios modernos.


- Hemos corregido un problema que hacía que, al presionar combinaciones de teclas como Ctrl + Mayús + @, no se generaba el carácter acentuado esperado (en este caso, "å").


- Hemos corregido un problema relacionado con la compresión de imágenes.


- Se ha corregido un problema por el cual el Panel de revisión podía desplazarse o parecía desplazarse, pero no estaba alineado con el comentario seleccionado.


- Hemos corregido un problema por el que algunos comentarios no se guardaban al exportar un documento a PDF.


- Hemos corregido un problema que impedía la edición de un nuevo comentario en una zona no protegida de un documento cuando se aplica la edición restringida.


- Hemos corregido un problema relacionado con una animación de desplazamiento innecesaria.


- Se ha corregido un problema que hacía que el panel Comentarios se cerrara inesperadamente.


- Se ha corregido un problema en el que no se resaltaban los comentarios al seleccionarlos.


- Se ha corregido un problema que causaba que no se borrara la selección del documento al hacer clic fuera de un comentario creado recientemente.


- Se ha corregido un problema por el que se producía un fallo al copiar datos adjuntos de correo a una aplicación que no fuese Word si el nombre de archivo incluía los caracteres DBCS.


- Hemos corregido un problema que causaba un cierre inesperado al usar lectura en voz alta con otras versiones de Windows.


- Se ha corregido un problema por el que las tarjetas contextuales de lienzo de ortografía y gramática mostraban botones de iconos, pero esos botones no tenían información sobre herramientas.


- Hemos corregido un problema que provocaba un desajuste entre el tema del panel del editor y el tema del sistema.


- Se ha corregido un problema por el que no se abría el panel del Editor.


- Se ha corregido un problema por el que los subrayados ondulados de similitud no desaparecían al cambiar a la categoría Ortografía del Editor.


- Hemos corregido un problema que hacía que Word mostrara a veces un borde alrededor del texto que no debía estar allí.


- Corregimos un problema por el que se aumentaba el espaciado entre caracteres para fuentes específicas al girarlas 90 grados.


- Se ha corregido un problema que hacía que se actualizara el campo incorrecto al ejecutar una macro si se aplican restricciones de edición.


- Corregimos un problema que causaba que las respuestas a comentarios se perdieran en ocasiones al trabajar en coautoría con varios usuarios.


- Hemos corregido un problema de rendimiento relacionado con el trabajo con documentos de gran tamaño.


- Se ha corregido un problema que causaba que algunos archivos de Word no se abrieran debido a marcadores dañados.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Corregimos un problema por el que la característica CLP causaba guardados sin avisar en el archivo SyncBacked (archivo sincronizado por OneDrive).


- Corregimos un problema por el que los usuarios no podían editar los archivos almacenados en servidores OnPrem.


- Se ha corregido una regresión de rendimiento al abrir archivos SyncBacked.


- Hemos corregido un problema por el que OneDrive mostraba un mensaje de error de combinación cuando en realidad no había ningún conflicto en la combinación.


- Se ha corregido un problema que podía causar un apagado al iniciar sesión con una cuenta diferente.


- Hemos corregido un problema relacionado con el orden z de los objetos SVG al convertirlos a formas.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2105-june-04"></a>Versión 2105: 4 de junio
*Versión 2105 (Compilación 14026.20264)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Configuración de detección de tipos de datos:** Configura cómo se detectan diferentes tipos de datos cuando se importan al Excel datos de orígenes no estructurados con Power Query.

### <a name="word"></a>Word

- **Estilos de escritura:** Estilos de escritura mantiene el criterio según el nivel de formalidad que ha seleccionado el usuario.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Hemos corregido un problema que hacía que a algunos usuarios les aparecieran entradas adicionales en la lista del complemento de Excel.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2105-june-01"></a>Versión 2105: 1 de junio
*Versión 2105 (Compilación 14026.20254)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Último inicio de sesión/Inicio de sesión sospechoso:** Outlook ahora le indica cuándo y dónde iniciado sesión por última vez en su cuenta y le avisa si se detecta actividad de inicio de sesión sospechosa

- **Habilitar las mejoras del calendario compartido:** Outlook puede actualizar los calendarios compartidos en Office 365 con la API de REST. Active la vista previa para obtener actualizaciones más rápidas y confiables de los calendarios compartidos.<br />Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/shared-calendars-improvements-in-outlook-for-windows)

- **Sugerencia de productividad del Comprobador de accesibilidad al enviar correos electrónicos a usuarios externos de listas de distribución de gran tamaño:** Hemos agregado la funcionalidad para que mostrar automáticamente una notificación, mediante una información sobre correo, ante una infracción de accesibilidad al redactar un correo electrónico para grandes audiencias, usuarios externos, etc. Esta configuración se encuentra en Accesibilidad<br />Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/sending-accessible-emails-in-outlook-for-windows)

### <a name="visio"></a>Visio

- **Formas y galerías de símbolos de AWS:** ahora tenemos galerías de símbolos con las formas de AWS más recientes para ayudarle a crear diagramas. [Más información](https://support.office.com/article/138206bf-d10f-4583-9f31-885ce706af49)




[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Hemos solucionado un problema que podía provocar un cierre inesperado al interactuar con el Correo de Outlook o las Vistas de Calendario.




[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2105-may-23"></a>Versión 2105: 23 de mayo
*Versión 2105 (Compilación 14026.20246)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="teams"></a>Teams

- **Anuncio de las vistas del panel de datos de asistencia:** Ya no es necesario descargar manualmente los informes, ahora Teams le permite ver todos los datos agregados en la vista del panel con un solo clic.

- **Funciones de seguridad, cumplimiento y protección de datos para aplicaciones:** para las aplicaciones de Microsoft 365 Certified Teams, los administradores pueden ver las funciones de seguridad, cumplimiento y protección de datos en una nueva pestaña de la página de detalles de la aplicación en el Centro de administración de Teams. Esta transparencia ofrece a los clientes de Microsoft confianza en las aplicaciones que ejecutan sus organizaciones.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha corregido un problema que causaba que algunas instrucciones de la característica "Acortar reuniones" no estuvieran disponibles a través de las tecnologías de lector de pantalla.


- Se ha corregido un problema que causaba que algunos usuarios se cerraran de forma inesperada al cargar tarjetas de persona.


- Hemos agregado una clave del Registro que deshabilita la nueva experiencia del Buscador de salas (la misma experiencia que en Outlook para Web) y habilita el Buscador de salas heredado con Horas sugeridas.
    - Clave del Registro:

        > HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar </br>
        > REG_DWORD “ShowLegacyRoomFinder”</br></br>
        > 0 (predeterminado): Outlook usa la nueva experiencia con tecnología del Buscador de salas de OWA cuando el usuario hace clic en el botón "Buscador de salas" para buscar salas disponibles.  </br>
        > 1: Outlook usa la interfaz de usuario del Buscador de salas heredada para buscar salas disponibles </br>


### <a name="project"></a>Project

- Se ha corregido un problema que hacía que las tareas de las tareas programadas manualmente se movieran a una fecha incorrecta.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2105-may-19"></a>Versión 2105: 19 de mayo
*Versión 2105 (Compilación 14026.20202)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="teams"></a>Teams

- **Los seminarios web de Teams se integran con Dynamics 365 Marketing para consolidar clientes potenciales:** Con esta característica, los organizadores de seminarios web pueden fomentar la participación posterior al evento con los asistentes al usar D365 Marketing. Los datos de participación de los asistentes se sincronizan con la organización de D365 Marketing y habilitan recorridos de usuario automatizados

- **Oradores inteligentes:** Los oradores inteligentes son periféricos inteligentes para las salas de Microsoft Teams en Windows. Mostrarán una transcripción del orador correspondiente a los participantes de la sala de reuniones, lo que permitirá a los asistentes dedicar menos tiempo a tomar notas y seguir fácilmente lo que se dice en la sala.

- **Permitir a los usuarios de Teams comprar aplicaciones de Teams a través del cliente de Teams:** Los usuarios de Teams ahora tienen la posibilidad de comprar suscripciones de la aplicación de Teams desde la tienda de Teams.

- **Crear Teams con plantillas de equipo:** Con plantillas en Teams, los usuarios pueden elegir entre una variedad de plantillas personalizables al crear un nuevo equipo, lo que les ayuda a empezar con rapidez. Asimismo, los administradores de TI pueden crear plantillas personalizadas para su organización, lo que les permite normalizar estructuras de equipo, preinstalar aplicaciones relevantes y escalar procedimientos recomendados. Los administradores de TI pueden elegir qué plantillas de Teams se mostrarán a los usuarios finales en el Centro de administración de Teams y, además, preconfigurar las pestañas del sitio web agregando direcciones URL a una pestaña del sitio web en una plantilla de equipo.

- **Usar anotaciones de lápiz y puntero láser en PowerPoint Live en Teams:** Estamos introduciendo el puntero láser virtual y las anotaciones para que los presentadores puedan compartir contenido de forma eficaz y atraer la atención del público hacia determinadas secciones de la presentación de PowerPoint. De la misma forma que usaría un punto láser físico en una sala, PowerPoint Live le permite apuntar de forma eficaz a diferentes lugares para que el público pueda seguir fácilmente lo que hay en la diapositiva.

- **Recomendaciones de flujo de Power Automate con plantillas de equipo 1P:** Plantillas de flujo de Power Automate para Surface para equipos creados a partir de plantillas de equipo 1P


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Hemos corregido un problema que causaba que la opción de comentarios no se mostrara a los usuarios de la versión preliminar de Office Perpetual 2021.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2105-may-12"></a>Versión 2105: 12 de mayo
*Versión 2105 (compilación 14026.20164)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="teams"></a>Teams

- **Configuración de preferencias de usuario para abrir archivos de forma predeterminada en Escritorio (o) Explorador (o) Teams:** los usuarios pueden establecer su preferencia predeterminada como Explorador, Escritorio o Teams al abrir archivos de Office (Word, Excel y Power Point) que se comparten en Teams. La configuración de Escritorio puede seleccionarse si están instalados y activados los clientes de Office más recientes.

- **Modo en paralelo y reportero en reuniones de Teams:** ahora puede aparecer junto al contenido para obtener una presentación y una experiencia de consumo más atractivas.

- **Disponibilidad general de las capacidades de seminario web de Teams:** programe y realice seminarios web de 1 000 personas con la misma aplicación de Teams que usa para reuniones. Las funcionalidades de seminario web admiten la creación de páginas de registro, confirmación de correo electrónico para los solicitantes de registro, administración del host para audio y vídeo de asistentes, informes de asistentes y características interactivas, como sondeos, chat y reacciones.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="word"></a>Word

- Se ha corregido un problema por el que las tarjetas contextuales de lienzo de ortografía y gramática mostraban botones de iconos, pero esos botones no tenían información sobre herramientas.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2105-may-07"></a>Versión 2105: 07 de mayo
*Versión 2105 (compilación 14026.20138)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="teams"></a>Teams

- **Presentamos los diseños en las reuniones de Teams:** ahora puede aparecer sobre todo el contenido para obtener una presentación y una experiencia de consumo más inmersivas

- **Deshabilitar la cámara para asistentes específicos:** los organizadores de la reunión y los presentadores pueden deshabilitar las cámaras de asistentes específicos de una reunión de Teams para asegurarse de que no comparten el vídeo en la reunión.

- **Deshabilitar la cámara para todos los asistentes:** los organizadores de la reunión y los presentadores pueden deshabilitar las cámaras de todos los asistentes de una reunión de Teams para asegurarse de que no comparten el vídeo en la reunión.

- **Los usuarios anónimos pueden presentar:** al hospedar un evento en directo de Teams, hemos agregado la capacidad de que los usuarios anónimos se unan a un evento en directo para que también puedan presentar durante el evento.

- **Administrar etiquetas en Teams mediante programación: las API de etiquetas de Microsoft Teams están ahora en versión preliminar pública:** este conjunto de API se puede usar para asignar mediante programación etiquetas de usuarios en un equipo, haciendo que la creación y el mantenimiento de etiquetas sea más rápido y más fácil.  Las etiquetas de Teams permiten a los usuarios llegar rápidamente a un grupo de personas sin tener que @mencionar o escribir el nombre de todos. Para más información sobre las etiquetas en equipos, consulte Uso de etiquetas en Teams. Al usar estas nuevas API, los desarrolladores ahora pueden crear etiquetas en un equipo y asignar a usuarios, obtener una lista de etiquetas en un equipo, actualizar etiquetas y eliminar etiquetas

- **Presentar desde PowerPoint en Teams:** presente las diapositivas directamente desde la aplicación de PowerPoint en una reunión de Teams a través de PowerPoint Live.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="word"></a>Word

- Corrige un problema con el que no se abre en el panel del Editor.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- RelNotesNotNeeded



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2105-may-03"></a>Versión 2105: 03 de mayo
*Versión 2105 (Compilación 14026.20052)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="teams"></a>Teams

- **Poner en primer plano varios usuarios al mismo tiempo en una reunión:** Ahora los organizadores y los presentadores pueden poner en primer plano varios participantes simultáneamente durante las reuniones. El espacio de reunión mostrará a esos participantes en primer plano, con sus vídeos o avatares, para todos los demás participantes de la reunión.

- **Presentar desde PowerPoint en Teams:** Presente las diapositivas directamente desde la aplicación de PowerPoint en una reunión de Teams a través de PowerPoint Live.

- **Nueva experiencia de administración de etiquetas y otras mejoras:** Las Etiquetas en Teams permiten a los usuarios llegar rápidamente a un grupo de usuarios sin tener que @mencionar o escribir cada uno. La experiencia de administración de etiquetas ahora es una Pestaña. Las etiquetas ahora también tienen un campo de descripción para que pueda agregar más detalles a una etiqueta. La nueva Pestaña Etiquetas será la página de inicio de las notificaciones y la búsqueda de etiquetas, que también estará disponible próximamente.

- **Oradores inteligentes:** Los oradores inteligentes son periféricos inteligentes para las salas de Microsoft Teams en Windows. Mostrarán una transcripción del orador correspondiente a los participantes de la sala de reuniones, lo que permitirá a los asistentes dedicar menos tiempo a tomar notas y seguir fácilmente lo que se dice en la sala.

- **Cambiar la notificación nativa predeterminada para equipos púrpuras para nuevos usuarios:** Las notificaciones nativas ofrecen una serie de ventajas, como el soporte para el centro de acción, la accesibilidad, el soporte para el modo de asistencia de foco, etc. Actualmente el estilo de notificación predeterminado para un nuevo usuario en Microsoft Teams es el Equipo Púrpura. Con este cambio, el valor predeterminado para el nuevo usuario cambiará a Notificación nativa.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Hemos corregido un problema que causaba que Excel se cerrara de forma inesperada al usar Office de 32 bits en Windows de 64 bits.


- Hemos corregido un problema que hacía que Excel se cerrara inesperadamente al desplazarse por los comentarios del panel Comentarios.


- Se ha corregido un problema por el que algunos complementos de automatización para Excel no se podían cargar.


- Hemos corregido un problema que causaba que Narrador leyese incorrectamente las propiedades de dos botones de la pestaña Encabezado y pie de página del cuadro de diálogo Configurar página.


- Hemos corregido un problema que causaba que algunos libros vinculados en otras aplicaciones de Office se cerraran sin guardar los cambios al ejecutar el Vínculo de actualización.


- Se ha corregido un problema en el que el complemento de Herramientas para análisis no funcionaba para algunos usuarios.


- Hemos corregido un problema que en ocasiones producía errores al abrir algunos archivos en la Vista protegida.


- Hemos corregido un problema que causaba que el formato de fecha se mostrara de forma incorrecta en algunos idiomas al usar complementos.


- Hemos corregido un problema que causaba que la barra de estado no indicara el estado de Listo para algunos usuarios.


- Hemos realizado un cambio para permitir que el Administrador de nombres se abra en libros con un gran número de nombres ocultos.


- Hemos corregido un problema para ofrecer compatibilidad con versiones anteriores de Excel. El problema podía provocar que un archivo que se guardaba en una versión más reciente de Excel no se cargara correctamente en versiones anteriores de Excel debido a  funciones como SI.ERROR y BUSCARX agregadas a Excel desde Office 2007.


- Hemos corregido un problema que podía provocar que Excel se cerrara de forma inesperada al usar Pegado especial con formatos en determinadas situaciones.


### <a name="outlook"></a>Outlook

- Hemos corregido un problema que causaba que Outlook anulara las preferencias de la Bandeja de entrada Prioritarios configuradas en OWA.


- Hemos corregido un problema que provocaba que los usuarios de la configuración de itinerancia experimentaran bloqueos.


- Hemos corregido un problema que provocaba que se deshabilitara la resolución de nombres al enviar en nombre de otro usuario y al resolver en una libreta de direcciones que no era la Lista global de direcciones.


- Hemos corregido un problema que provocaba que algunos usuarios de la característica de uso compartido del calendario experimentaran problemas al interactuar con su calendario en el panel de navegación.


- Hemos corregido un problema que causaba que Outlook se cerrara de forma inesperada al usar el modo de Contraste alto durante largos períodos de tiempo.


- Hemos corregido un problema en el que los hipervínculos que incluyen dígitos se deshabilitarían al redactar un mensaje en Outlook en un idioma de derecha a izquierda.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema relacionado con las imágenes vinculadas.


### <a name="project"></a>Project

- Hemos corregido un problema que provocaba que los cambios realizados con los Asistentes para planificación no siempre se capturaran con eventos de cambio.


- Hemos corregido un problema en el que los usuarios no podían quitar proyectos del grupo de recursos.


### <a name="visio"></a>Visio

- Hemos corregido un problema que ha provocado que Visio se cerrara de forma inesperada con la compilación reciente.


### <a name="word"></a>Word

- Hemos corregido un problema por el cual se conservaba el formato de texto después de quitar los hipervínculos.


- Hemos corregido un problema que hacía que el texto de marcador de posición se recortara en los comentarios al usar idiomas de derecha a izquierda.


- Hemos corregido un problema que hacía que los comentarios no se mostraran después de filtrar por usuario.


- Hemos corregido un problema que impedía a Word combinar correspondencia con una base de datos de Access.


- Hemos corregido un problema que hacía que estuviera disponible la capacidad de contraer los márgenes de los documentos que contuvieran varias columnas.


- Hemos corregido un problema que impedía que algunos caracteres se mostraran correctamente en las celdas de la tabla cuando había comentarios en el documento.


- Hemos corregido un problema por el cual se producían los cambios en el formato de archivo al guardar documentos con el complemento AIP habilitado.


- Hemos corregido un problema que hacía que Word no respondiera al editar campos.


- Hemos corregido un problema por el que la etiqueta de confidencialidad desaparecía de un archivo en Word después de cargar el archivo en SharePoint Online.


- Hemos corregido un problema por el cual no se solicitaba a los usuarios guardar documentos al usar un comando (en lugar del método abreviado de teclado CTRL+S).


- Corregido un problema que podría provocar el cierre inesperado de Word al desconectarse debido a que el usuario cerraba o reiniciaba su equipo.


- Hemos corregido un problema por el cual se conservaba el formato de texto después de quitar los hipervínculos.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Hemos corregido un problema que causaba que el botón de dictado estuviera mal alineado al agregar comentarios a un documento.


- Se ha corregido un problema al analizar una cadena de procesamiento de emojis que hacía que la aplicación se cerrara inesperadamente al leer fuera de los límites de una matriz


- Hemos corregido un problema que hacía que algunos Scalable Vector Graphics (SVG) no se representasen correctamente.



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2104-april-28"></a>Versión 2104: 28 de abril
*Versión 2104 (compilación 13929.20296)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="teams"></a>Teams

- **Selector de emojis expandido:** La actualización de emojis expandida ofrece a los usuarios un lugar más divertido y expresivo en Teams. También introduce una mayor variedad en términos de diversidad y representación. El conjunto de emojis se ha expandido de 85 a más de 800 emojis, con selector de categorías, selector de tono de piel y selector de código abreviado.

- **Microsoft Teams: Experiencia de Compartir en reuniones revisada:** La interfaz de usuario de la característica Compartir en reuniones de Microsoft Teams se ha rediseñado para ayudar a los presentadores a encontrar más rápido y fácilmente el contenido deseado.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema por el que algunos complementos de automatización de Excel no se cargan.


### <a name="outlook"></a>Outlook

- Hemos corregido un problema que provocaba que los usuarios experimentaran bloqueos.


### <a name="powerpoint"></a>PowerPoint

- Hemos corregido un problema relacionado con las imágenes vinculadas.


### <a name="project"></a>Project

- Se ha corregido un problema en el que los usuarios no podían quitar proyectos del grupo de recursos.


### <a name="word"></a>Word

- Hemos realizado un cambio en la edición del objeto OLE.



[//]: # (NO QUITAR FINAL DE CONTENIDO CON DETALLES DE ERROR)

## <a name="version-2104-april-26"></a>Versión 2104: 26 de abril
*Versión 2104 (Compilación 13929.20254)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Habilitar las mejoras del calendario compartido:** Outlook puede actualizar los calendarios compartidos en Office 365 con la API de REST. Active la vista previa para obtener actualizaciones más rápidas y confiables de los calendarios compartidos.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Hemos corregido un problema que en ocasiones producía errores al abrir algunos archivos en la Vista protegida.


### <a name="outlook"></a>Outlook

- Hemos corregido un problema que causaba que Outlook anulara las preferencias de la Bandeja de entrada Prioritarios configuradas en OWA.



[//]: # (NO QUITAR FINAL DE CONTENIDO CON DETALLES DE ERROR)

## <a name="version-2104-april-19"></a>Versión 2104: 19 de abril
*Versión 2104 (compilación 13929.20216)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Importar datos de matrices dinámicas:** ahora puede importar, dar forma y actualizar datos de matrices dinámicas en el libro actual. [Más información](https://support.office.com/article/205c6b06-03ba-4151-89a1-87a7eb36e531)

### <a name="outlook"></a>Outlook

- **Búsqueda de Calendario mejorada:** mejoras en la búsqueda de Calendario, la mayor de las cuales es la capacidad de encontrar más fácilmente la siguiente repetición de una serie en los resultados de búsqueda.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Este cambio corrige un problema por el que al ejecutar una consulta que pasara por SQL Server, se mostraba en algunos casos un mensaje de error que alertaba de un "estado de cursor no válido".


- Hemos corregido un problema por el que, cuando una aplicación externa solicitaba una interfaz de accesibilidad, nos impedía cerrar hasta que se liberaba su referencia.


### <a name="excel"></a>Excel

- Hemos corregido un problema que bloqueaba la capacidad de pegar como fórmulas en una hoja protegida.


- Hemos corregido un problema por el que los hipervínculos creados con la función HIPERVINCULO no funcionaban si el archivo se guardaba como un documento PDF.


- Hemos corregido un problema que causaba que se agregara un símbolo de operador implícito (@) a la fórmula con una referencia a un intervalo vacío y proporcionara potencialmente un resultado incorrecto.


### <a name="outlook"></a>Outlook

- Hemos corregido un problema que causaba que algunos usuarios experimentasen un cierre inesperado de Outlook al sincronizar los cambios en la jerarquía de carpetas.


- Hemos corregido un problema que causaba que los usuarios vieran por error un mensaje de "Esto puede tardar un poco" mientras añadían algún elemento a un calendario.


- Hemos solucionado un problema que hacía que los delegados aparecieran como organizadores de reuniones creadas en calendarios recién añadidos.  Las reuniones en este estado no aparecían en el calendario del principal.


- Hemos corregido un problema que provocaba que los usuarios experimentaran un bloqueo al buscar.


- Hemos corregido un bloqueo relacionado con la búsqueda.


- Hemos corregido un problema que provocaba que los usuarios vieran desaparecer las firmas de forma inesperada.


- Hemos corregido un problema que podía provocar que los usuarios vieran el mensaje que indica que están redactando perder el foco de la interfaz de usuario.


- Hemos corregido un problema que causaba que Outlook anulara las preferencias de la Bandeja de entrada Prioritarios configuradas en OWA.


- Hemos corregido un problema que causaba que los usuarios de la característica Configuración de la nube vieran que se reemplazaba la configuración personalizada por la configuración predeterminada después de configurar Outlook en un nuevo dispositivo.


- Hemos corregido un problema que causaba que algunas personas no pudieran tener acceso a las firmas asociadas con cuentas de correo secundarias.


- Hemos corregido un problema que provocaba errores en la resolución de nombres al enviar en nombre de otro usuario y al resolver en una libreta de direcciones que no es la Lista global de direcciones.


- Hemos corregido un problema que provocaba errores en la resolución de nombres al enviar en nombre de otro usuario y al resolver en una libreta de direcciones que no es la Lista global de direcciones.


### <a name="project"></a>Project

- Se ha corregido un problema por el que, si el formato de fecha es W4/4, el selector de fecha puede mostrar un día y un año incorrectos.


### <a name="visio"></a>Visio

- Se ha corregido un problema que provocaba que Visio dejara de funcionar durante el cierre.


- Se ha corregido la característica "Buscar forma" para que se muestren todos los resultados



### <a name="word"></a>Word

- Con este error, Office no estaba respetando las directivas específicas (se mostraba un grupo de plantillas en la página principal cuando debían haber estado deshabilitadas). Con esta corrección, se respetan las directivas.


- Al crear con coautoría un documento, el borrador activo no se borrará cuando se realicen cambios en el orden de los comentarios.


- Se ha corregido un error en Comentarios modernos en el que los signos de puntuación y los números se mostraban en el lado incorrecto en algunos idiomas internacionales.


- Se ha corregido un problema por el que la combinación de "B" y ")" se convertía automáticamente en el emoji con gafas de sol, y ahora permanecerá como los caracteres individuales


- Texto actualizado en la llamada de autoguardado para los archivos guardados localmente.


- Hemos corregido un problema con los comentarios durante la coautoría.


- Hemos corregido un problema relacionado con el icono de comentario.


- Se ha corregido un problema que hacía que los estilos copiados y pegados pudieran no ser iguales en el texto pegado.


- Optimiza las condiciones para ofrecer previsiones de texto.


- Hemos corregido un problema relacionado con los hipervínculos.


- Algunos textos seleccionados no eran visibles al usar el tema modo oscuro en el modo Lectura.


- Hemos corregido un problema con el Autoguardado.


- Hemos corregido Application.OnTime donde puede que no se desencadene correctamente.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema de rendimiento relacionado con la iteración de texto.


- Soluciona un problema con el soporte técnico de GDI+ LineJoinMiterClipped en Office.


- Esta versión mejora el control del contenido confidencial de línea cuando la palabra clave está en la primera línea de un documento.



[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)

## <a name="version-2103-april-13"></a>Versión 2103: 13 de abril
*Versión 2103 (Compilación 13901.20400)*

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="teams"></a>Teams

- **Vista dinámica** Vista dinámica optimiza automáticamente el contenido compartido y los participantes de vídeo en las reuniones de Teams. Los nuevos controles le permiten personalizar la vista para adaptarla a sus preferencias y necesidades, como la capacidad de mostrar el contenido compartido y participantes específicos en paralelo.

[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO FINAL)

## <a name="version-2103-april-10"></a>Versión 2103: 10 de abril
*Versión 2103 (Compilación 13901.20400)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un posible problema de contención de recursos en palabras mientras se dibujaba una imagen.

### <a name="outlook"></a>Outlook

- Hemos corregido un problema que causaba que los usuarios vieran por error un mensaje de "Esto puede tardar un poco" mientras añadían algún elemento a un calendario.

- Hemos solucionado un problema que hacía que los delegados aparecieran como organizadores de reuniones creadas en calendarios recién añadidos.  Las reuniones en este estado no aparecían en el calendario del principal.

- Se ha corregido un posible problema de contención de recursos en palabras mientras se dibujaba una imagen.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un posible problema de contención de recursos en palabras mientras se dibujaba una imagen.

### <a name="word"></a>Word

- Se ha corregido un posible problema de contención de recursos en palabras mientras se dibujaba una imagen.

- Se ha corregido un problema no dinámico en la vista previa de impresión.

- Texto actualizado en la llamada de autoguardado para los archivos guardados localmente.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido el problema del cambio de nombre cuando se abría un archivo SyncBacked fuera de línea y se le cambiaba el nombre en la aplicación antes de guardarlo.



[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)

## <a name="version-2103-april-02"></a>Versión 2103: 02 de abril
*Versión 2103 (Compilación 13901.20336)*
* Varias correcciones de errores y de rendimiento.

## <a name="version-2103-april-1"></a>Versión 2103: 1° de abril
*Versión 2103 (Compilación 13901.20148)*

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="teams"></a>Teams

- **Formato de fecha y hora** Con esta actualización, los formatos de fecha y hora en Teams coincidirán con la configuración regional de los sistemas operativos Windows y Mac. Anteriormente, Teams solo mostraba la fecha y hora en el formato correspondiente al idioma de la aplicación. Es importante tener en cuenta que solo el calendario gregoriano es compatible, independientemente de la configuración de calendario del sistema operativo. 

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

## <a name="version-2103-march-30"></a>Versión 2103: 30 de marzo
*Versión 2103 (compilación 13901.20312)*
* Varias correcciones de errores y rendimiento.

## <a name="version-2103-march-28"></a>Versión 2103: 28 de marzo
*Versión 2103 (Compilación 13901.20306)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Hemos corregido un problema que causaba que algunos usuarios experimentasen un cierre inesperado de Outlook al sincronizar los cambios en la jerarquía de carpetas.


- Se ha corregido un problema que causaba que algunos usuarios viesen sus lugares de cambio de calendario principal y secundario en el panel de navegación.



[//]: # (NO QUITAR EL CONTENIDO FINAL DE LOS DETALLES DE LOS ERRORES)

## <a name="version-2103-march-22"></a>Versión 2103: 22 de marzo
*Versión 2103 (Compilación 13901.20230)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Hemos corregido un problema que provocaba que los usuarios vieran más firmas de las esperadas.



[//]: # (NO QUITAR EL CONTENIDO FINAL DE LOS DETALLES DE LOS ERRORES)

## <a name="version-2103-march-15"></a>Versión 2103: 15 de marzo
*Versión 2103 (compilación 13901.20170)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="project"></a>Project

- Se ha corregido un problema que provocaba que Visio dejara de funcionar durante el cierre.


### <a name="visio"></a>Visio

- Se ha corregido un problema que provocaba que Visio dejara de funcionar durante el cierre.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

[//]: # (NO QUITAR DETALLES DE CARACTERÍSTICAS CONTENIDO INICIO)
## <a name="version-2103-march-11"></a>Versión 2103: 11 de marzo
*Versión 2103 (compilación 13901.20148)*

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Autoguardado y coautoría en documentos cifrados confidenciales:** no elija entre productividad y seguridad. Con Microsoft Information Protection, los documentos que se cifran con etiquetas de confidencialidad ahora permiten el autoguardado y la coautoría con otras personas en tiempo real, igual que los documentos sin cifrar. Requiere que el espacio empresarial opte por participar (más información: https://aka.ms/mipcoauth).

### <a name="outlook"></a>Outlook

- **Nueva experiencia de reserva de sala de conferencias y área de trabajo:** se ha actualizado la experiencia de reserva de la sala de conferencias y, con ella, hemos agregado funcionalidades para permitirle programar áreas de trabajo individuales.

### <a name="powerpoint"></a>PowerPoint

- **Autoguardado y coautoría en documentos cifrados confidenciales:** no elija entre productividad y seguridad. Con Microsoft Information Protection, los documentos que se cifran con etiquetas de confidencialidad ahora permiten el autoguardado y la coautoría con otras personas en tiempo real, igual que los documentos sin cifrar. Requiere que el espacio empresarial opte por participar (más información: https://aka.ms/mipcoauth).

### <a name="teams"></a>Teams

- **Estado fuera de la oficina** Configure un mensaje para avisar a otras personas de que no estás trabajando o de que estás de vacaciones, y que por lo tanto no estás disponible para responder si le envían un mensaje de chat. Su estado fuera de la oficina también se sincronizará con las Respuestas automáticas de su calendario de Outlook.

### <a name="visio"></a>Visio

- **Los iconos de Office tienen un nuevo aspecto:** los iconos de producto se han rediseñado para reflejar las sencillas, inteligentes y eficaces experiencias de Office. [Más información](https://support.office.com/article/a6cdf19a-b2bd-4be1-9515-d74a37aa59bf)

### <a name="word"></a>Word

- **Modo oscuro para documentos de Word:** el modo oscuro puede ayudar a reducir la carga visual y adaptar la sensibilidad a la luz mientras trabaja en sus documentos.

- **Autoguardado y coautoría en documentos cifrados confidenciales:** no elija entre productividad y seguridad. Con Microsoft Information Protection, los documentos que se cifran con etiquetas de confidencialidad ahora permiten el autoguardado y la coautoría con otras personas en tiempo real, igual que los documentos sin cifrar. Requiere que el espacio empresarial opte por participar (más información: https://aka.ms/mipcoauth).


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Hemos corregido un problema que podría provocar que la aplicación se cerrara de forma inesperada al quitar una unidad externa.


- Hemos corregido un problema por el que, cuando una aplicación externa solicitaba una interfaz de accesibilidad, nos impedía cerrar hasta que se liberaba su referencia.


### <a name="excel"></a>Excel

- Hemos corregido un problema que podría provocar que la aplicación se cerrara de forma inesperada al quitar una unidad externa.


- Se ha corregido un problema que causaba que Excel se cerrara de forma inesperada al intentar mostrar la tarjeta tipos de datos porque una imagen no se podía recuperar.


- Hemos corregido un problema por el que la fuente cambiaría de forma inesperada al usar un signo de multiplicación o división con una fuente japonesa. Ahora continuamos usando la misma fuente si admite el carácter.


- Hemos corregido un problema que impedía a los usuarios exportar un libro de Excel a PDF.


- Hemos corregido un problema que hace que las imágenes fueran más pequeñas de lo esperado al usar la opción Pegar imagen vinculada.


- Hemos corregido un problema por el que se podía perder parte del formato al copiar una hoja mientras se trabajaba en autoría.


- Hemos corregido un problema por el que algunas notas se mostraban de forma inesperada al abrir un libro.


- Hemos corregido un problema que causaba que algunos formatos de tabla dinámica dañaran el libro al guardar en formato .xls o .xlt.


### <a name="outlook"></a>Outlook

- Hemos corregido un problema que podría provocar que la aplicación se cerrara de forma inesperada al quitar una unidad externa.


- Hemos corregido el problema que causaba que los usuarios viesen grupos de calendario duplicados después de crear un grupo.


- Hemos corregido un problema que causaba que los usuarios de las mejoras del calendario compartido no pudieran establecer el color de un calendario en amarillo o marrón.


- Hemos corregido un problema por el que los usuarios no veían los calendarios agregados recientemente en el panel de navegación si no reiniciaban Outlook.


- Hemos corregido un problema que causaba que los caracteres que no eran ASCII se exportaran de forma incorrecta al exportar a un archivo CSV.


- Hemos corregido un problema que causaba que algunos usuarios no pudieran tener acceso a las firmas asociadas con cuentas de correo secundarias.


- Hemos corregido un problema que causaba que los usuarios de la característica Configuración de la nube vieran que se reemplazaba la configuración personalizada por la configuración predeterminada después de configurar Outlook en un nuevo dispositivo.


- Hemos corregido un problema que provocaba que las firmas con contenido Unicode se dañasen.


- Hemos corregido un problema que causaba que los usuarios de traducción directa no pudieran enviar comentarios.


- Hemos corregido un problema que provocaba que los usuarios vieran archivos adjuntos duplicados al quitar la protección de DRM.


- Hemos corregido un problema que causaba que los usuarios no pudieran buscar un grupo de contactos con Comprobar nombres al redactar un correo.


### <a name="powerpoint"></a>PowerPoint

- Hemos corregido un problema que podría provocar que la aplicación se cerrara de forma inesperada al quitar una unidad externa.


- Hemos corregido un problema que hacía que las flechas de los gráficos de líneas no aparecieran tal como se esperaba en el modo de presentación de PowerPoint.


- Corregido un problema con la reproducción de animaciones y marcadores de audio.


### <a name="project"></a>Project

- Se ha corregido un problema que provocaba que Visio dejara de funcionar durante el cierre.


- Hemos corregido un problema que podría provocar que la aplicación se cerrara de forma inesperada al quitar una unidad externa.


- Se ha corregido un problema por el que una tarea completada al 100 % podía aparecer como completada al 99 %.


- Se ha corregido un problema por el que Project se cerraba inesperadamente si ejecutaba JAWS e iba al diálogo de información de la tarea.


- Se ha corregido un problema por el que, si la columna de indicador no está en el primer lugar de la columna, al cortar una tarea de resumen, no se advierte de que también se quitarán las subtareas.


- Se ha corregido un problema por el que, si un usuario seleccionaba la opción Agregar su usuario a una función de tarea en su Timesheet, no se podrían usar correctamente las unidades de disponibilidad de recursos en la tarea creada.


- Se ha corregido un problema por el que es posible que las divisiones de tareas se creen de forma incorrecta al guardar un proyecto desde Project Web App en un archivo local. Esto sucedía al usar un calendario de tareas con horas de trabajo no estándar.


### <a name="publisher"></a>Publisher

- Hemos corregido un problema que podría provocar que la aplicación se cerrara de forma inesperada al quitar una unidad externa.


### <a name="visio"></a>Visio

- Se ha corregido un problema que provocaba que Visio dejara de funcionar durante el cierre.


- Hemos corregido un problema que podría provocar que la aplicación se cerrara de forma inesperada al quitar una unidad externa.


### <a name="word"></a>Word

- Hemos corregido un problema por el que, al abrir un archivo protegido con una etiqueta de Microsoft Information Protection (MIP), se puede colgar de forma indefinida si el usuario no ha iniciado sesión en una identidad que tiene acceso a la etiqueta protegida de MIP. El usuario no puede cancelar la apertura para mostrar la solicitud de inicio de sesión yno se puede completar correctamente gasta entonces. Para solucionar este problema, permita que se muestre la solicitud de inicio de sesión durante la apertura o descarga.


- Hemos corregido un problema que podría provocar que la aplicación se cerrara de forma inesperada al quitar una unidad externa.


- Hemos corregido un problema al usar Dictado en el nuevo Comentarios de Word. Ahora, el botón de dictado de la tarjeta Comentarios se activa y desactivada correctamente.


- Al crear un documento en coautoría, el borrador activo no se borraba cuando cambiaba el orden de los comentarios.


- Se ha corregido un problema por el que no se insertaba ningún espacio entre palabras cuando los usuarios dictaban en su documento.


- Se ha corregido un problema en la canalización de representación relacionado con las capas de desplazamiento que contienen animaciones de desplazamiento o zoom.


- Se ha corregido un problema con los colores aplicados a los iconos y a los gráficos SVG con efectos 3D.


- Hemos corregido un problema con el Autoguardado.


- Hemos corregido un problema con la nota al pie.


- Hemos corregido un problema al publicar comentarios de varias líneas escritos en RTL que causaba que las líneas 2 en adelante se alineasen a la izquierda en lugar de a la derecha.


- Hemos corregido un problema con la alineación de varios comentarios.


- Hemos corregido un problema en los métodos abreviados de teclado del panel de tareas Leer en voz alta.


- Hemos corregido un problema por el que el Narrador podía omitir un párrafo.


- Hemos corregido un problema que hacía que la revisión ortográfica cambiara entre dos menús contextuales de corrección ortográfica diferentes.


- Hemos corregido un problema con los controles de contenido de texto enriquecido.


- Hemos corregido un problema con la escritura al final de un párrafo oculto que podía provocar que la aplicación dejara de funcionar.


- Hemos corregido un problema en el que las columnas podían tener texto superpuesto.


- Hemos corregido un problema relacionado con el marcador.


- Hemos corregido un problema relacionado con la resolución de conflictos durante la coautoría.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Las ubicaciones de OneDrive ahora se filtran según corresponda en la configuración de directiva de grupo.


- Se ha corregido un problema al usar Narrador en un texto que contiene ecuaciones matemáticas.


- Se ha corregido un problema de confiabilidad relacionado con la compatibilidad de las aplicaciones de Office que se ejecutan en la sesión 0.


- Se ha corregido un problema de confiabilidad relacionado con la compatibilidad de las aplicaciones de Office que se ejecutan en la sesión 0.


- Soluciona un problema relacionado con la falta de respuesta que puede producirse al cargar imágenes EMF.



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2102-march-03"></a>Versión 2102: 03 de marzo
*Versión 2102 (compilación 13801.20274)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="word"></a>Word

- Soluciona un problema con la información del tema que se aplica a los iconos y a los gráficos SVG.



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2102-march-01"></a>Versión 2102: 01 de marzo
*Versión 2102 (compilación 13801.20266)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Compartir con Teams:** comparta mensajes de Outlook con una persona o canal en Teams.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Hemos corregido el problema que causaba que los usuarios viesen grupos de calendario duplicados después de crear un grupo.


- Hemos corregido un problema que causaba que los usuarios de las mejoras del calendario compartido no pudieran establecer el color de un calendario en amarillo o marrón.


- Hemos corregido un problema que causaba que la app se cerrase para algunos usuarios al cerrar las ventanas de mensaje.


- Hemos corregido un problema que provocaba que las firmas con contenido Unicode se dañasen.


- Hemos corregido un problema que causaba que los usuarios de traducción directa no pudieran enviar comentarios.



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2102-february-21"></a>Versión 2102: 21 de febrero
*Versión 2102 (compilación 13801.20182)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Escriba mensajes con su voz:** use la nueva barra de herramientas de dictado, los comandos de voz, la puntuación automática y mucho más para redactar mensajes.

### <a name="word"></a>Word

- **Escriba documentos con su voz:** use la nueva barra de herramientas de dictado, los comandos de voz, la puntuación automática para redactar documentos.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Hemos corregido un problema que hace que las imágenes sean más pequeñas de lo esperado al usar la opción Pegar imagen vinculada.



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2102-february-16"></a>Versión 2102: 16 de febrero
*Versión 2102 (compilación 13801.20160)*
* Varias correcciones de errores y rendimiento.

## <a name="version-2102-february-15"></a>Versión 2102: 15 de febrero
*Versión 2102 (compilación 13801.20158)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Dictado está disponible en más idiomas:** ahora admite 7 idiomas nuevos: hindi, ruso, polaco, portugués (Portugal), coreano, tailandés y chino (Taiwán)

### <a name="word"></a>Word

- **Dictado está disponible en más idiomas:** ahora admite 7 idiomas nuevos: hindi, ruso, polaco, portugués (Portugal), coreano, tailandés y chino (Taiwán)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Hemos corregido un problema que impedía a los usuarios exportar un libro de Excel a PDF.


### <a name="word"></a>Word

- Hemos corregido un problema relacionado con la resolución de conflictos durante la coautoría.



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)


## <a name="version-2102-february-11"></a>Versión 2102: 11 de febrero
*Versión 2102 (compilación 13801.20158)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="teams"></a>Teams

- **Vídeo de 2x2 en los exploradores Microsoft Edge y Chrome en equipos Windows y Mac** Los usuarios pueden ver un máximo de 4 participantes en reuniones de Teams en los exploradores Microsoft Edge y Chrome en Windows y Mac. [Obtener más información](https://support.microsoft.com/office/using-video-in-microsoft-teams-3647fc29-7b92-4c26-8c2d-8a596904cdae#bkmk_videolayout)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

## <a name="version-2102-february-08"></a>Versión 2102: 8 de febrero
*Versión 2102 (Compilación 13801.20084)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Sugerencias de redacción con tecnología de Búsqueda de Microsoft (Para\CC\CCO):** ahora la adición de personas a la línea Para\CC usa la tecnología de Búsqueda de Microsoft.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Ahora verá las pestañas seleccionadas más claramente en Access.


### <a name="excel"></a>Excel

- Se ha corregido un problema que hace que determinados gráficos que usan rangos de celdas discontinuos no se carguen al volver a abrir los archivos.


- Corrige un problema por el que Excel no se iniciaba o se cerraba inesperadamente si se estaba usando cierta configuración de protección contra vulnerabilidades de Seguridad de Windows (SimExec, CallerCheck).


- Hemos corregido un problema por el que Excel dejaba de responder después de seleccionar una serie de datos en un gráfico.


- Hemos corregido un problema en el que Excel se cerraba inesperadamente al agregar un nombre en el cuadro de diálogo Definir nombre.


- Se ha corregido un problema relacionado con las imágenes que conservaban su relación de aspecto durante una operación de recorte.


### <a name="outlook"></a>Outlook

- Hemos corregido un problema por el que los mensajes de correo electrónico se enviaban como firmados digitalmente después de que el usuario desactivara esa opción.


- Hemos corregido un problema que causaba que no se mostrara el icono de cifrado de los correos electrónicos enviados con la opción Solo cifrar.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema relacionado con la muestra de emojis con color.


- Se ha corregido un problema relacionado con las imágenes que conservaban su relación de aspecto durante una operación de recorte.


### <a name="visio"></a>Visio

- Ya se ha corregido el problema con la representación de formas de galerías de símbolos de CAD. Los usuarios verán el problema resuelto en la compilación más reciente.


### <a name="word"></a>Word

- Esto corrige un problema que impedía que la escritura en tiempo real y la presencia se restauraran tras perder la conectividad a Internet durante un período de tiempo.


- Cuando un usuario selecciona texto en un comentario, ahora Word anula la selección del texto seleccionado en otros comentarios.


- Ahora Word permite copiar texto de comentarios en Excel.


- Se corrigió un problema por el que, al ejecutar la macro de VBA ExportAsFixedFormat2, se produce un error que indica "Valor no válido de presentación (miembro desconocido)".


- Se ha corregido un problema relacionado con las imágenes que conservaban su relación de aspecto durante una operación de recorte.


- Hemos corregido un problema que podía truncar un comentario con vínculos.


- Hemos corregido un problema relacionado con guardar archivos en SharePoint Online.


- Hemos corregido un problema relacionado con la exportación de un documento de Word a PDF.


- Se ha corregido un problema con la Autorrecuperación.

- Se ha corregido un problema al trabajar con coautoría en archivos protegidos DRM


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Solución de un error en PowerPoint que causaba que las viñetas desapareciesen al insertar viñetas como imágenes. Esta corrección hace que su representación sea más confiable.

- Se ha corregido un problema por el que, en algunas circunstancias, Office presentaba etiquetas de confidencialidad para una cuenta con la que se había iniciado sesión en lugar de presentarlas para otra cuenta diferente con la que se había iniciado sesión.



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2101-february-03"></a>Versión 2101: 3 de febrero
*Versión 2101 (compilación 13628.20330)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Hemos corregido un problema que causaba errores al mostrar la firma predeterminada correcta en OWA.


- Hemos corregido un problema que hacía que no se mostrara el icono de cifrado de los correos electrónicos enviados con la opción de solo cifrado.



[//]: # (NO QUITAR FINAL DE CONTENIDO CON DETALLES DE ERROR)

## <a name="version-2101-february-02"></a>Versión 2101: 02 de febrero
*Versión 2101 (compilación 13628.20320)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Hemos corregido un problema que causaba que los usuarios de Configuración de la nube tuviesen un error al actualizar la configuración.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2101-january-25"></a>Versión 2101: 25 de enero
*Versión 2101 (Compilación 13628.20274)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Los clientes gubernamentales pueden ya aplicar etiquetas de confidencialidad a sus documentos y correos electrónicos**: las características de las etiquetas de confidencialidad ahora están disponibles para los clientes de los entornos GCC y GCC-H. [Más información](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a>Outlook

- **Los clientes gubernamentales pueden ya aplicar etiquetas de confidencialidad a sus documentos y correos electrónicos**: las características de las etiquetas de confidencialidad ahora están disponibles para los clientes de los entornos GCC y GCC-H. [Más información](/microsoft-365/compliance/sensitivity-labels)

### <a name="powerpoint"></a>PowerPoint

- **Los clientes gubernamentales pueden ya aplicar etiquetas de confidencialidad a sus documentos y correos electrónicos**: las características de las etiquetas de confidencialidad ahora están disponibles para los clientes de los entornos GCC y GCC-H. [Más información](/microsoft-365/compliance/sensitivity-labels).


### <a name="word"></a>Word

- **Los clientes gubernamentales pueden ya aplicar etiquetas de confidencialidad a sus documentos y correos electrónicos**: las características de las etiquetas de confidencialidad ahora están disponibles para los clientes de los entornos GCC y GCC-H. [Más información](/microsoft-365/compliance/sensitivity-labels)


### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha corregido un problema que causaba que los usuarios que tienen buzones compartidos o delegados con jerarquías grandes en su perfil sufriesen bloqueos.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)



## <a name="version-2101-january-18"></a>Versión 2101: 18 de enero
*Versión 2101 (compilación 13628.20158)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)



[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="project"></a>Project

- Se ha corregido un problema en el que los bordes no se mostraban para las tareas en la vista Organizador de equipo.


- Se ha corregido un problema en el que la opción de arrastrar y colocar no funcionaba para las tareas de la vista Organizador de equipo.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2101-january-13"></a>Versión 2101: 13 de enero
*Versión 2101 (compilación 13628.20118)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)
### <a name="feature-updates"></a>Actualizaciones de características
### <a name="teams"></a>Teams
- **Más temas:** ahora hay nuevos temas disponibles para clientes web y de escritorio.

- **Uso compartido de PPT:** vista Moderador en Teams. Una vez que seleccione un archivo de PowerPoint en la bandeja Compartir de Teams, la vista Moderador se abrirá automáticamente. Puede ver la diapositiva actual, las notas de las diapositivas y una franja de miniaturas de todas las diapositivas de la presentación para facilitar la navegación de diapositivas ad-hoc. Esta vista está completamente en segundo plano y es privada para el moderador que tiene el control. El público solo puede ver la diapositiva actual (resaltada en el cuadro rojo grande) o la diapositiva a la que decida navegar (si la navegación del público no está bloqueada por usted). 

- **Incluir sonido de equipo al compartir ventanas o el escritorio en Mac** Al compartir un escritorio o ventana desde Teams en Mac, ahora puede incluir el sonido de su equipo para que las personas que se han unido a la reunión puedan escuchar el audio de reproducción del equipo.

[//]: # (NO QUITAR DETALLES DE CARACTERÍSTICAS CONTENIDO FINAL)
<br/>

## <a name="version-2101-january-09"></a>Versión 2101: 09 de enero
*Versión 2101 (compilación 13628.20118)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Sugerencias de escritura con un solo clic:** Aplique sugerencias de escritura con un solo clic. El editor corrige la ortografía y la gramática y le da ideas para refinar su escritura. [Más información](https://support.office.com/article/1e72a440-89a6-457c-bd76-cd5cea901dc0)<br />Ver detalles en [entrada de blog](https://insider.office.com/es-ES/blog/microsoft-editor-gets-an-upgrade)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que Outlook se cerrara de forma inesperada para algunos usuarios en ciertos escenarios de búsqueda.



[//]: # (NO QUITAR LOS DETALLES DE ERROR AL FINAL DEL CONTENIDO)

## <a name="version-2101-january-07"></a>Versión 2101: 7 de enero
*Versión 2101 (compilación 13628.20030)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Mostrar varias hojas de cálculo al mismo tiempo:** no es necesario que se muestren las hojas de una en una, ya que se pueden mostrar varias hojas ocultas al mismo tiempo. [Más información](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)

- **Cuadros de diálogo de formato condicional mejorados:** Los diálogos de formato condicional ahora son de tamaño ajustable y se puede duplicar la regla con un solo clic. [Más información](https://support.office.com/article/fed60dfa-1d3f-4e13-9ecb-f1951ff89d7f)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema por el que Excel mostraba de forma incorrecta una barra de mensajes donde se indicaba que estaba disponible una nueva versión del archivo y obligaba al usuario a descartar los cambios o guardarlos en una copia del libro.


- Se ha corregido un problema con los separadores de conmutación después de Selection.Parent.Copy.


- Se realizó una mejora de rendimiento al aplicar estilos de formato a las tablas dinámicas.


- Se ha corregido un problema que provocaba que Excel dejara macros deshabilitadas sin preguntar al abrir archivos de complemento de Excel que contuvieran macros Excel 4.0.


- Actualización para que la configuración de los separadores decimales y de millares se mantenga al copiar un gráfico de Excel y pegarlo en Word.


- Se ha corregido un problema por el que Excel se cerraba inesperadamente al abrir archivos UNC con atributos de archivo no válidos (hora de creación, fecha de modificación, etc.).


- Se ha corregido un problema que podría provocar una alerta de "recursos insuficientes" al usar la función STOCKHISTORY.


- Se ha agregado una DLL FuzzyClustering a la lista de DLL PQ.


- Este cambio resuelve un problema relacionado con la modificación de los colores del contorno de imágenes SVG.


- Se ha corregido un problema que provocaba que la vista previa del intervalo de Excel insertado en PowerPoint mostrara un tamaño incorrecto.


### <a name="onenote"></a>OneNote

- Este cambio resuelve un problema de representación que afecta a OneNote.


### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que los usuarios no pudiesen especificar durante cuánto tiempo querían permitir el acceso al iniciar una combinación de correo de Word, lo que hacía que se enviasen demasiados avisos.


- Este cambio permite a Outlook aprovechar una configuración de Exchange Server que suprime la presentación del buzón de correo de Exchange Online para usuarios finales.


- Se ha corregido un problema que provocaba que Outlook se cerrara de forma inesperada para los usuarios de complementos basados en Redemption.


- Se corrigió el problema que causaba que los usuarios no pudieran seleccionar más de una categoría para buscar.


- Se corrigió el problema que causaba que la hora de inicio de algunos elementos del calendario cambiara inesperadamente cuando el evento se copiaba de otra cita.


- Se corrigió un problema por el que los mensajes de texto sin formato S/MIME se volvían ilegibles al enviarse.


### <a name="powerpoint"></a>PowerPoint

- Este cambio resuelve un problema con las formas de combinar trabajar con texto.


- Este cambio resuelve un problema relacionado con la modificación de los colores del contorno de imágenes SVG.


- Este cambio resuelve un problema en la reproducción de vídeos de fondo en bucle en la presentación con diapositivas.


- Se ha corregido un problema por el que el comando tamaño de fuente, agregado a la herramienta de acceso rápido, se completaba automáticamente al tamaño de fuente definido más cercano al actualizarse.


### <a name="project"></a>Project

- Se ha corregido un problema que provocaba que las unidades máximas de un recurso no siempre reflejaran la actualización más reciente en las unidades máximas.


### <a name="visio"></a>Visio

- El problema se debe a una regresión reciente. Se ha resuelto el problema. El cuadro de diálogo "Guardar como página web" ahora hará que los campos se rellenen correctamente en función de las entradas de usuario, y que los usuarios puedan guardar los archivos como páginas web sin problemas.


- Este problema se ha corregido. Ahora se pueden insertar archivos de Visio como objetos en otras aplicaciones de Office, como PowerPoint y Word, y obtener acceso a ellos fácilmente desde estas aplicaciones.


### <a name="word"></a>Word

- Se ha corregido un problema que provocaba que los equipos con la configuración de hash personalizada tuvieran problemas al estar en una sesión de colaboración con una configuración de hash diferente de sha512.


- Este cambio resuelve un problema relacionado con la modificación de los colores del contorno de imágenes SVG.


- Se ha corregido un problema al editar una entrada de comentario que incluía una @mención.


- Se ha corregido un problema para mejorar la solidez de los comentarios modernos.


- Se ha corregido un problema en torno a la eliminación de los comentarios modernos en un control de contenido marcado como no editable.


- Animación corregida al escribir en la parte inferior de una tarjeta de comentario.


- Corrección de un problema que provocaba que el cuadro de respuesta en una tarjeta de comentario apareciera fuera de la pantalla.


- Corrección de un problema con una tarjeta de comentario que se mostraba en la parte superior de la página.


- Corrección de errores en comentarios en los que el texto podía desplazarse fuera de la pantalla.


- Corrección de un problema con las barras de desplazamiento anidadas en el panel de comentarios.


- Los borradores de comentarios desaparecen al crear una nueva instancia de Word.


- Se ha corregido un problema que causaba que Word se bloqueara al guardar un documento en PDF con texto oculto.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2012-january-04"></a>Versión 2012: 4 de enero
*Versión 2012 (compilación 13530.20316)*
* Varias correcciones de errores y rendimiento.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Etiqueta obligatoria:** usuarios con la Directiva de etiquetado obligatoria se debe establecer que los administradores les etiqueten sus documentos y mensajes de correo electrónico.

### <a name="powerpoint"></a>PowerPoint

- **Etiqueta obligatoria:** usuarios con la Directiva de etiquetado obligatoria se debe establecer que los administradores les etiqueten sus documentos y mensajes de correo electrónico.

### <a name="word"></a>Word

- **Etiqueta obligatoria:** usuarios con la Directiva de etiquetado obligatoria se debe establecer que los administradores les etiqueten sus documentos y mensajes de correo electrónico.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

## <a name="version-2012-december-28"></a>Versión 2012: 28 de diciembre
*Versión 2012 (Build 13530.20264)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha arreglado un problema que causaba que algunos clientes experimentaran un cuelgue mientras cargaban sus calendarios.



[//]: # (NO QUITAR LOS DETALLES DE ERROR AL FINAL DEL CONTENIDO)

## <a name="version-2012-december-21"></a>Versión 2012: 21 de diciembre
*Versión 2012 (compilación 13530.20218)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Envío de datos de auditoría sobre el etiquetado de confidencialidad a los administradores de M365:** cuando los usuarios apliquen, cambien o eliminen las etiquetas de confidencialidad en sus documentos y correos electrónicos, Office enviará datos de auditoría al back-end de auditoría de M365 para que los administradores los vean. Esta es una funcionalidad silenciosa (sin interfaz de usuario) para beneficio del administrador.

### <a name="outlook"></a>Outlook

- **Dar algo de tiempo entre reuniones consecutivas:** asigne a los asistentes el tiempo necesario para que descansen o se desplacen entre las distintas ubicaciones. Para ello haga que las reuniones empiecen de 5 a 10 minutos antes de forma predeterminada. [Más información](https://support.office.com/article/be84396a-0903-4e25-b31c-1c99ce0dacf2)

- **Envío de datos de auditoría sobre el etiquetado de confidencialidad a los administradores de M365:** cuando los usuarios apliquen, cambien o eliminen las etiquetas de confidencialidad en sus documentos y correos electrónicos, Office enviará datos de auditoría al back-end de auditoría de M365 para que los administradores los vean. Esta es una funcionalidad silenciosa (sin interfaz de usuario) para beneficio del administrador.

### <a name="powerpoint"></a>PowerPoint

- **Envío de datos de auditoría sobre el etiquetado de confidencialidad a los administradores de M365:** cuando los usuarios apliquen, cambien o eliminen las etiquetas de confidencialidad en sus documentos y correos electrónicos, Office enviará datos de auditoría al back-end de auditoría de M365 para que los administradores los vean. Esta es una funcionalidad silenciosa (sin interfaz de usuario) para beneficio del administrador.

### <a name="word"></a>Word

- **Envío de datos de auditoría sobre el etiquetado de confidencialidad a los administradores de M365:** cuando los usuarios apliquen, cambien o eliminen las etiquetas de confidencialidad en sus documentos y correos electrónicos, Office enviará datos de auditoría al back-end de auditoría de M365 para que los administradores los vean. Esta es una funcionalidad silenciosa (sin interfaz de usuario) para beneficio del administrador.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema por el que el comando tamaño de fuente, agregado a la herramienta de acceso rápido, se completaba automáticamente al tamaño de fuente definido más cercano al actualizarse.



[//]: # (NO QUITAR NINGÚN DETALLE DE ERROR EN EL FINAL DEL CONTENIDO)

## <a name="version-2012-december-14"></a>Versión 2012: 14 de diciembre
*Versión 2012 (compilación 13530.20144)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Su configuración de Outlook en la nube:** elija la configuración de Outlook para Windows, como Respuestas automáticas, la Bandeja de entrada Prioritarios y Privacidad, y acceda a ellos desde cualquier PC.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Tamaño binario optimizado.


- Anaheim WebView aún no es compatible con Windows Information Protection. Con esta corrección, la plataforma de complementos de Office retrocede al nivel inferior de WebView en un entorno habilitado para WIP. Según el entorno de máquina del cliente, esto puede ser Edge Spartan WebView o Trident WebView. Las vistas previas de nivel inferior son compatibles con WIP.



[//]: # (NO QUITAR NINGÚN DETALLE DE ERROR EN EL FINAL DEL CONTENIDO)

## <a name="version-2012-december-07"></a>Versión 2012: 7 de diciembre
*Versión 2012 (compilación 13530.20064)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características

### <a name="teams"></a>Teams

- **Las notificaciones nativas de Windows ahora son compatibles con Teams:** ahora los usuarios pueden seleccionar su forma preferida de entrega de notificaciones, ya sea a través de banners integrados en Teams o banners nativos de Windows.


- **Vista de galería 2x2 de reuniones de Microsoft Teams en Citrix y VMware VDI:** la característica vista de galería de VDI 2x2 en Microsoft Teams permitirá ver hasta cuatro vídeos de asistentes en la vista de galería de 2x2 en clientes de VDI de Citrix, VMWare cuando el cliente de Microsoft Teams está en modo optimizado para VDI.


- **Reacciones de la reunión:**  las reacciones de la reunión son una nueva forma de interactuar en las reuniones. Los participantes pueden enviar reacciones que se muestran como un flujo en el contenido que se comparte y en la persona que envió la reacción si se muestra en la fase de reunión. 


- **Modo Juntos y Galería grande para reuniones web:** la galería grande permite ver los vídeos de hasta 49 otras personas a la vez. Esta opción está disponible cuando al menos diez personas tienen las cámaras activadas. El modo Juntos le permite sentir que está en el mismo espacio compartido con todos los usuarios de la reunión. El modo Juntos está disponible cuando hay al menos cinco personas en la reunión. 


- **Combinación de llamadas** la combinación de llamadas permite a los usuarios combinar una nueva llamada que realizan o una nueva llamada entrante en su llamada con otra persona o grupal. Esto se aplica para las llamadas de VoIP de Teams y las llamadas de RTC. 


### <a name="visio"></a>Visio

- **Nuevas galerías de símbolos y formas de Azure:** Hemos agregado muchas más galerías de símbolos para ayudarle a crear diagramas de Azure actualizados. [Más información](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Hemos corregido un problema en el que algunos elementos de la cinta de opciones no se localizaban en chino simplificado.


- Hemos corregido un problema en el que Excel se terminaba inesperadamente durante la actualización.


- Hemos corregido un problema por el cual el comando Insertar objeto no muestra el icono correcto cuando se inserta un archivo desde la carpeta de sincronización local de OneDrive.


- Se ha corregido un problema por el que la edición en idiomas que requieren el uso del IME funcionaba mal al editar en el modo de sobrescritura.


- Se ha corregido un problema por el que algunos usuarios veían incorrectamente una barra de mensajes que les informaba de una nueva versión de un archivo durante la coautoría.


- Se ha corregido un problema que provocaba que Excel se cerrase de forma inesperada al copiar y pegar datos en la vista Fórmula.


- Se ha corregido un hipervínculo roto a un artículo de ayuda en una alerta que aparecía al deshabilitar Autoguardado.


- Se ha corregido un problema que causaba que Excel dejara de funcionar cuando se escribían datos en determinados lenguajes.


- Este cambio soluciona un problema que impedía mostrar correctamente fuentes en ecuaciones.


- Corregido un problema por el que Power Pivot no importaba correctamente un archivo de texto delimitado por tabulaciones.


### <a name="outlook"></a>Outlook

- Hemos corregido un problema que provocaba que el campo Para: quedara en blanco en los informes de estado de la tarea.


- Se ha corregido un problema que provocaba que se interrumpiera el evento MailItem.BeforeAttachmentAdd.


- Corregido un problema que provocaba que los usuarios experimentaran problemas al enviar correo de Outlook desde aplicaciones que no son Outlook.


- Se ha corregido un problema que provocaba que SmartLinks perdiera el formato cuando se guardaba en Borradores.


- Corregido un problema en el que la adición de un archivo adjunto a un mensaje abierto desde un archivo zip fallaba.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema relacionado con copiar o pegar una ecuación de Word a PowerPoint.


- Este cambio resuelve un problema relacionado con los tiempos de espera experimentados durante el análisis de entrada de lápiz.


- Este cambio corrige un error gramatical en la interfaz de usuario Crear un archivo GIF animado.


- Este cambio resuelve un problema con el relleno de rutas al aplicar las operaciones de Combinar formas con determinadas geometrías.


- Este cambio soluciona un problema que impedía mostrar correctamente fuentes en ecuaciones.


- Este cambio resuelve un problema con el control de errores que se pueden producir durante la carga de vídeo.


- Hemos corregido un problema de VBA por el cual Slide.Shapes.AddMediaObject2 se bloqueaba con formatos de vídeo heredados (MPG-1, MPEG-2).


- Se ha corregido un problema que evitaba que el indicador de presencia de un coautor desconocido no se actualizara por completo cuando había disponible más información sobre el coautor.


- Se ha corregido un puntero nulo al cambiar el tamaño de la vista con la regla activada.


- Se ha corregido un problema que evitaba que algunos archivos de PowerPoint corruptos se abrieran correctamente, incluso después de la operación de reparación de un documento.


### <a name="project"></a>Project

- Hemos corregido un problema por el cual los usuarios creaban proyectos que supuestamente se guardaban con información actualizada pero en los que no había ninguna actualización.


- Hemos corregido un problema por el cual no se podían eliminar las dependencias de las entregas si el sitio de SharePoint en el que estaba asociada la entrega ya no existía.


- Se ha corregido un problema que alargaba demasiado el tiempo de apertura de un proyecto con muchos recursos.


- Se ha corregido un problema en el que los usuarios pueden ver varias tareas no asignadas asociadas a una tarea.


- Se ha corregido un problema en el que los proyectos de gran tamaño pueden tardar más en especificar un nombre de tarea.


- Se ha corregido un problema por el que algunos proyectos específicos podrían abrirse si había un problema con el archivo del proyecto en una parte específica de la carga.


### <a name="word"></a>Word

- A menudo, Pegar como texto sin formato tiene preferencia sobre Pegar como texto enriquecido. La corrección de este menú contextual permite al usuario pegar como texto sin formato. De lo contrario, el usuario tendría que copiarlo en un editor de texto sin formato como el Bloc de notas y, luego, copiarlo de allí a la aplicación de destino deseada.


- Se ha corregido un problema relacionado con copiar o pegar una ecuación de Word a PowerPoint.


- Este cambio resuelve un problema con el cursor al editar un documento.


- Hemos corregido un problema relacionado con las imágenes difuminadas por usar el zoom.


- Hemos corregido un problema por el cual se truncaban hipervínculos largos.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Corregido un problema en el Conjunto de aplicaciones de Office por el que la instalación de una versión más reciente de Office sobre algunas versiones anteriores podía resultar en un deterioro de la funcionalidad (por ejemplo, no poder usar Power Query) debido a que faltaban entradas del registro.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2011-december-01"></a>Versión 2011: 1 de diciembre
*Versión 2011 (compilación 13426.20306)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Todas las reuniones en línea:** facilite la programación de reuniones en línea con una nueva configuración para que todas las reuniones sean en línea de forma predeterminada.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que los asistentes originales de algunas reuniones reciban una cancelación cuando otro asistente reenviaba la reunión.


- Se ha corregido un problema que causaba que algunos usuarios no vieran ninguna firma en la lista desplegable a pesar de que se configuraron una o varias firmas.


### <a name="project"></a>Project

- Se ha corregido un problema por el que algunos proyectos específicos podrían abrirse si había un problema con el archivo del proyecto en una parte específica de la carga.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2011-november-24"></a>Versión 2011: 24 de noviembre
*Versión 2011 (Compilación 13426.20294)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema relacionado con copiar o pegar una ecuación de Word a PowerPoint.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2011-november-21"></a>Versión 2011: 21 de noviembre
*Versión 2011 (compilación 13426.20274)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="powerpoint"></a>PowerPoint

- **Biblioteca de vídeos:** Mejore sus documentos con una biblioteca de videos editados y libres de royalties disponibles en la aplicación.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que se interrumpiera el evento MailItem.BeforeAttachmentAdd.


- Se ha agregado una clave de registro que permite a los clientes deshabilitar la inclusión de hora de archivo para los datos adjuntos en las operaciones de IDataObject (es decir, arrastrar y soltar, portapapeles). HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments. REG_DWORD IncludeFileTimesInDataObject. 0 = se excluyen filetimes. 1 = (predeterminado) filetimes se incluyen


- Se ha corregido un problema por el que las imágenes en línea desaparecían al responder a un mensaje con una etiqueta de protección de Azure Information Protection.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2011-november-18"></a>Versión 2011: 18 de noviembre
*Versión 2011 (compilación 13426.20250)*
* Varias correcciones de errores y rendimiento.

## <a name="version-2011-november-16"></a>Versión 2011: 16 de noviembre
*Versión 2011 (compilación 13426.20234)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Misma firma, todos los dispositivos:** su firma se almacena en la nube. Créelo una vez y úselo en cualquier lugar donde use Outlook.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que el campo Para quedara vacío al enviar un informe de estado en una tarea.


### <a name="powerpoint"></a>PowerPoint

- Corregimos un problema de VBA por el que Slide.Shapes.AddMediaObject2 se bloqueaba con formatos de vídeo heredados (MPG-1, MPEG-2).



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2011-november-09"></a>Versión 2011: 9 de noviembre
*Versión 2011 (compilación 13426.20184)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Crear flujos de datos de Power Platform a partir de consultas:** ahora puede exportar sus consultas a plantillas de Power Query que se pueden usar para crear nuevos flujos de datos de Power Platform.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Acceso

- Corregimos un problema por el que algunos usuarios veían el error "recurso del sistema excedido" al intentar exportar una consulta de su carpeta sincronizada de OneDrive.


- Corregimos un problema en el que el cambio automático entre las ventanas de la forma estaba cambiando a otra forma.


- Se ha corregido un problema que provocaba que, al utilizar DAO desde aplicaciones que no son de Office, la aplicación se cerrara de forma inesperada.


### <a name="excel"></a>Excel

- Se ha corregido un problema por el que el nombre de archivo no cambiaba después de una operación Guardar como con complementos COM habilitados.


- Se ha corregido un problema con Power Pivot cuando usa una conexión en una base de datos de Oracle.


- Se ha corregido un problema cuando se produce un error de Autoguardado con un mensaje de error incorrecto o engañoso cuando hay una definición de medida incorrecta en el modelo de datos de Excel.


- Se corrigió un problema por el que Excel terminó de forma inesperada cuando se activó el proceso de calcular MTR y la actualización de objetos de directiva de grupo (por ejemplo, a través de la actualización remota de la directiva de grupo).


- Corregido un problema por el que un usuario no podía abrir el archivo de atomsvc (UTF8 + BOM) desde SharePoint directamente.


- Se ha corregido un problema en el que al acercar y alejar el área de presentación se daba una separación entre el recuadro de selección ampliado y el puntero del mouse.


- Corregido un problema en el que Word parecía bloquearse al insertar un libro de Excel en un documento de Word.


### <a name="outlook"></a>Outlook

- Resuelto un problema que hacía que Outlook dejara de funcionar esporádicamente al agregar o guardar datos adjuntos.


- Se ha corregido un problema por el que la impresión rápida de los datos adjuntos de imagen provocaba un error “Windows no puede encontrar esta imagen. Compruebe la ubicación y vuelva a intentarlo”.


- Se corrigió un problema que hacía que algunos usuarios vieran que Outlook se iniciaba en un estado sin conexión hasta que optaban manualmente por trabajar en línea.


- Corregimos un problema al pegar una dirección URL copiada desde la ubicación de la reunión a otro lugar (como un explorador), la dirección URL contiene un punto y coma al final.


- Se ha corregido un problema que impedía a los usuarios eliminar citas en el Calendario de Grupos de Microsoft 365 en autenticación básica.


- Se ha corregido un problema que producía errores en el inicio de Outlook durante la carga de la caché de sobrenombres.


- Se ha corregido un problema por el que el propietario de un buzón no podía administrar el permiso compartido en su propio Calendario de Outlook, ya que la opción se había desactivado.


- Corregido un problema por el cual Outlook no podía crear un mensaje con permisos restringidos.


- Se ha corregido un problema por el cual al guardar las plantillas de correo electrónico como .OFT se cambiaban los caracteres chinos por signos de interrogación.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema que provocaba que, al acercar y alejar el área de presentación, apareciera una separación entre el recuadro de selección ampliado y el puntero del mouse.


- Se ha corregido un problema que provocaba que el icono del marcador de posición de contenido junto a Imágenes no incluyera información sobre herramientas.


- Se ha corregido un problema debido al cual la Vista protegida de presentación con diapositivas, mostrada en archivo PPTSX, permitía la captura de pantalla de documentos protegidos por IRM.


- Se ha corregido un problema por el cual las líneas de cuadrícula se desplazaban de las diapositivas al cerrar el panel Diseño.


- Corregimos un problema al duplicar la presentación con diapositivas en un monitor secundario, la presentación puede ocultarse detrás de la otra ventana.


- Se ha corregido un problema por el que la barra de desplazamiento en la diapositiva comienza a ajustarse a sí misma después de detener la grabación de pantalla con el panel de selección abierto.


### <a name="project"></a>Project

- Se ha corregido un problema por el que la NewVal en el evento ProjectBeforeTaskChagne no tiene el valor correcto si se cambia un retraso en una vista de tipo de formulario de tarea.


- Corregimos un problema por el que el Proyecto puede finalizar inesperadamente al abrir archivos en los que se especificaban los contornos de los recursos de una determinada manera.


- Se ha corregido un problema que provocaba que, al guardar un proyecto desde PWA en un archivo MPP local, ProjectBeforeTaskChangeEvent se desencadenara para datos no modificados por el usuario.


- Se ha corregido un problema en el que las negociaciones de recursos buscaban un recurso por nombre en lugar de un GUID, lo que causaba problemas si había varios recursos con el mismo nombre.


- Se ha corregido un problema que hace que si tiene una lista de tareas en un sitio de proyecto y agrupa la lista de tareas, no pueda editar rápidamente la lista de tareas.


- Se ha corregido un problema que hace que si actualiza un recurso de empresa a través del CSOM, puede perderse la capacidad máxima del recurso.


### <a name="word"></a>Word

- Se ha corregido un problema en el que al acercar y alejar el área de presentación se daba una separación entre el recuadro de selección ampliado y el puntero del mouse.


- Se ha corregido un problema por el que al hacer clic en la sugerencia de comentario no se mostraba la tarjeta comentario en la vista.


- Corregido un problema de diseño en el que la línea entre columnas podía cambiar.


- Corregimos un problema en Control de cambios por el que a veces se podía mostrar un mensaje de error al abrir un documento de Word.


- Corregido un problema en el que Word parecía bloquearse al insertar un libro de Excel en un documento de Word.


- Corregimos un problema de impresión cuando se aplica la etiqueta de carácter con marcas de agua.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema en la Herramienta de implementación de Office que provocaba errores en la configuración al usar la característica RemoveMSI con el producto de Office 2007 "Informes de errores de aplicaciones de Microsoft".


- Se ha corregido un problema por el que el inicio de sesión interactivo de la API de SSO devuelve un código de error.



[//]: # (NO QUITAR EL CONTENIDO FINAL DE LOS DETALLES DE LOS ERRORES)

## <a name="version-2010-november-06"></a>Versión 2010: 6 de noviembre
*Versión 2010 (compilación 13328.20356)*
* Varias correcciones de errores y rendimiento.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)



[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

## <a name="version-2010-november-04"></a>Versión 2010: 4 de noviembre
*Versión 2010 (compilación 13328.20340)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Compatibilidad con el portapapeles SVG:** ahora puede pegar contenido SVG de Office en aplicaciones de terceros. [Más información](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a>Outlook

- **Compatibilidad con el portapapeles SVG:** ahora puede pegar contenido SVG de Office en aplicaciones de terceros. [Más información](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a>PowerPoint

- **Compatibilidad con el portapapeles SVG:** ahora puede pegar contenido SVG de Office en aplicaciones de terceros. [Más información](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br />Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/svg-content-office-third-party-apps)

- **Crear GIF con fondos transparentes:** cuando se exporta a un GIF animado, una nueva opción permite que el fondo sea transparente.<br />Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/export-animated-gifs-transparent-backgrounds)

- **Exportar GIF animado en un rango:** seleccione un intervalo de diapositivas cuando exporte a GIF animado

### <a name="word"></a>Word

- **Compatibilidad con el portapapeles SVG:** ahora puede pegar contenido SVG de Office en aplicaciones de terceros. [Más información](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que los usuarios no puedan conceder permisos de editor a los delegados.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema que provocaba un error al intentar guardar archivos que habían pasado de sincronizados a solo en el servidor.



[//]: # (NO QUITAR DETALLES DE ERROR DEL FIN DE CONTENIDO)

## <a name="version-2010-october-27"></a>Versión 2010: 27 de octubre
*Versión 2010 (compilación 13328.20292)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha corregido un problema que, de forma predeterminada, impedía que se activara la configuración de la nube para los usuarios.


- Se ha corregido un problema que impedía guardar los cambios que se realizaran a la firma de un usuario.



[//]: # (NO QUITAR DETALLES DE ERROR DEL FIN DE CONTENIDO)

## <a name="version-2010-october-24"></a>Versión 2010: 24 de octubre
*Versión 2010 (compilación 13328.20278)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)



[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que los encabezados de mensajes en chino no se pudieran leer al responder o reenviar.


- Se ha corregido un problema que provocaba que los caracteres chinos se cambiaran a signos de interrogación al guardar como archivo .oft.


### <a name="project"></a>Proyecto

- Se ha corregido un problema que provocaba que, al guardar un proyecto desde PWA en un archivo MPP local, ProjectBeforeTaskChangeEvent se desencadenara para datos no modificados por el usuario.


- Se ha corregido un problema que causaba que NewVal en el evento ProjectBeforeTaskChange no tuviera el valor correcto si se cambiaba un retraso en una vista de tipo de formulario de tarea.



[//]: # (NO QUITAR DETALLES DE ERROR DEL FIN DE CONTENIDO)

## <a name="version-2010-october-19"></a>Versión 2010: 19 de octubre
*Versión 2010 (compilación 13328.20210)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Ahorre tiempo mientras redacta mensajes:** Outlook le muestra sugerencias de escritura que le ayudarán a redactar mensajes de manera rápida. Para aceptar la sugerencia, solo tiene que usar la tecla TAB.<br />Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/text-predictions-in-word-outlook)

- **Rompa la barrera del idioma con un traductor incorporado:** Los complementos para la traducción ya no son necesarios. En un mensaje, haga clic con el botón derecho para traducir palabras o frases específicas, o todo el mensaje. [Más información](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

- **Actualizaciones de la experiencia de usuario en Tareas:** Una actualización visual de los elementos de las tareas

### <a name="powerpoint"></a>PowerPoint

- **Practique la presentación con el Asesor para moderadores:** Obtenga asesoramiento sobre las cosas que ayudan a mantener a la audiencia comprometida, como el ritmo, el uso excesivo de palabras, el lenguaje corporal y más. [Más información](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

### <a name="word"></a>Word

- **El panel del Editor Microsoft recibe una actualización en la versión de escritorio de Word:** Hemos actualizado la experiencia actual con el panel del Editor para los clientes de escritorio de Word.

- **Sugerencias de escritura con un solo clic:** Aplique sugerencias de escritura con un solo clic. El panel del Editor actualizado facilita la navegación entre sugerencias.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="powerpoint"></a>PowerPoint

- Esta es una solución para un problema por el que se muestra la solicitud de guardar en un bucle al cerrar el documento cuando hay un complemento que escucha al evento PresentationBeforeClose y comprueba la propiedad Presentation.Saved como parte del controlador de eventos.



[//]: # (NO QUITAR DETALLES DE ERROR DEL FIN DE CONTENIDO)

## <a name="version-2010-october-11"></a>Versión 2010: 11 de octubre
*Versión 2010 (compilación 13328.20154)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Ayude a proteger sus datos de archivos malintencionados:** Protección de aplicaciones le ayuda a protegerse contra el malware permitiéndole leer, imprimir y guardar los archivos de Office en un recipiente aislado. [Más información](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="powerpoint"></a>PowerPoint

- **Ayude a proteger sus datos de archivos malintencionados:** Protección de aplicaciones le ayuda a protegerse contra el malware permitiéndole leer, imprimir y guardar los archivos de Office en un recipiente aislado. [Más información](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="word"></a>Word

- **Ayude a proteger sus datos de archivos malintencionados:** Protección de aplicaciones le ayuda a protegerse contra el malware permitiéndole leer, imprimir y guardar los archivos de Office en un recipiente aislado. [Más información](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Se ha corregido un problema que provocaba que la posición de la barra de desplazamiento no se estableciera de manera correcta al cargar la ventana de consulta o relación guardada mientras se realizaba el desplazamiento.


- Se ha corregido un problema que provocaba que el panel de tareas de Agregar tabla no mostrara de manera correcta los nombres que contenían "&".


### <a name="excel"></a>Excel

- Se ha corregido un problema que provocaba que el intervalo manual de categoría multinivel no funcionara en los gráficos.


- Se ha corregido un problema con los gráficos de mapas 2D que provocaba que el uso de VBA para establecer los colores de los valores max, mid y min para una serie no funcione.


- Se ha corregido un problema por el que Excel indicaba por error que se había quedado sin recursos al intentar calcular una o varias fórmulas.


- Se ha corregido un problema que aparecía cuando se configuraba el idioma de Office en español. Este problema provocaba que las listas de validación de datos puedan no mostrar todos los elementos de la lista.


- Se ha corregido un problema que provocaba un retraso considerable al cambiar entre hojas de cálculo con grandes cantidades de datos cuando la 'Vista previa de salto de página' estaba habilitada.


- Se ha corregido un problema que hacía que no se actualizaran las opciones de todas las hojas del libro al agregar una tabla usada para la validación de datos.


- Se ha corregido un problema que podía producir un bloqueo al actualizar las tablas dinámicas de OLAP.


- Se ha corregido un problema que hacía que ChartSheet se bloqueara en ciertos casos cuando se insertaba una fórmula en la barra de fórmulas.


- Se corrigió un problema por el cual la barra de fórmulas de Excel no se mostraba completamente después de que se perdiera la conexión a un dispositivo, como una conexión o desconexión de sesión remota o un cambio de monitor.


### <a name="onenote"></a>OneNote

- Se ha corregido un problema que impedía al usuario seleccionar y copiar la dirección URL del bloc de notas del cuadro de texto en un archivo de OutSpace > Información.


- Se ha corregido un problema que hacía que, al pasar el ratón sobre el color verde en el selector de colores del bloc de notas, el elemento emergente indicara "red chalk" (tiza roja).


- Se ha corregido un problema que hacía que OneNote no respetara los colores de contraste alto en el lienzo para temas personalizados.


### <a name="outlook"></a>Outlook

- Corrige un problema que causaba el envío de los mensajes de correo electrónico generados automáticamente con el cuerpo del correo en blanco cuando el asunto estaba vacío.


- Se ha corregido un problema que provocaba que se almacenara en caché para carpetas el GUID de carpeta incorrecto.


- Cuando un usuario copia y pega una dirección de correo electrónico en el campo del destinatario con el nombre para mostrar, la dirección de correo electrónico no siempre se analizaba de forma correcta, y esto generaba que aparezca una advertencia sobre una dirección de correo electrónico no válida.  Se ha corregido y, por tanto, el nombre y la dirección de correo electrónico se analizan de forma correcta para que ya no se muestre la advertencia.


- Se ha corregido un problema que causaba que las carpetas compartidas en línea no devolvieran el nombre de la carpeta principal. En lugar de dar error, devolvía una ruta de acceso vacía que pasaba incorrectamente a la cuenta principal.


- Se ha corregido un problema que impedía que la opción Guardar como estuviera disponible para los datos adjuntos clásicos.


- Se ha corregido un problema para ofrecer a los usuarios una forma de personalizar el texto de justificación al anular una directiva.


- Se ha corregido un problema que hacía que se activara el control de cambios después de reabrir el borrador desde el panel de vista previa de solo lectura.


- Se ha corregido un problema que hacía que los correos electrónicos se ocultaran después de desactivar la Bandeja de entrada Prioritarios y ordenarlos.


- Se ha corregido un problema que hacía que Outlook creara una segunda firma vacía para las personas con la configuración de la nube habilitada.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema que impedía a PowerPoint exportar las viñetas rectangulares al exportar a PDF.


- Se ha corregido un problema que hacía que los GIF solo mostraran la animación una vez en el editor y en las presentaciones.


- Se ha corregido un problema que hacía que el gráfico de Excel vinculado cambiara incorrectamente a la hoja de Excel cuando el usuario cambiaba la ruta de origen a la carpeta de OneDrive local.


- Se ha corregido un problema debido al cual, si se encuentra en la última diapositiva y pasa a la siguiente diapositiva tras pulsar "Finalizar sesión" y antes de que aparezca el resumen, el cuadro de diálogo de sesión final también aparece visible en la página de resumen.


### <a name="project"></a>Project

- Se ha corregido un problema que puede hacer que el método VBA ConsolidateProjects produzca errores si se intenta agregar el mismo proyecto varias veces y AttachToSources está establecido en false.


- Se ha corregido un problema por el que si se ejecuta un código de evento y se intenta realizar cambios desde la vista del Formulario de tareas, es posible que el botón Aceptar no confirme los cambios.


- Se ha corregido un problema que puede hacer que el método VBA ConsolidateProjects produzca errores si se intenta agregar el mismo proyecto varias veces y AttachToSources está establecido en false.


- Se ha corregido un problema debido al cual, si tiene campos personalizados con fórmulas que usan el valor acumulado, puede que observe que el rendimiento retrasa el cambio de vistas y la apertura de los detalles del proyecto/tarea.


- Se ha corregido un problema que podía hacer que Project se bloqueara si aplicaba un grupo en la Vista de hoja o de uso de recursos y, a continuación, insertaba una columna.


### <a name="word"></a>Word

- Se ha corregido un problema que provocaba que los vínculos a los archivos habilitados de flujo de trabajo no se abrieran con normalidad.


- Se ha corregido un problema que provocaba que el hecho que un usuario seleccionara una marca de revisión (inserción o eliminación) mostrara un comentario emergente.


- Se ha corregido un problema al eliminar llamadas de comentario en Word.


- Se ha corregido un problema con Outlook al establecer un mensaje en No reenviar


- Se ha corregido un problema al guardar un documento de Word que contenía cita y ecuación.


- Se ha corregido un problema con el cuadro de diálogo Galería de estilos.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Cuando el usuario imprime cualquier documento o archivo en las impresoras de inyección de tinta de Office y la tinta de la impresora es poco visible, el mensaje "tóner bajo" o "sin tóner" se mostrará, aunque las impresoras de inyección de tinta no tengan tóners. Cambiar mensaje para mostrar "tóner/tinta bajos" & "no tóner/tinta".



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2009-october-07"></a>Versión 2009: 7 de agosto
*Versión 2009 (Compilación 13231.20360)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Crear tipos de datos con Power Query:** crear tipos de datos enriquecidos con Power Query desde cualquier origen de datos

### <a name="outlook"></a>Outlook

- **La revisión gramatical se ha vuelto:** Outlook marca los errores gramaticales mientras escribe, por lo que puede aplicar sugerencias con un solo clic. <br />Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/grammar-and-style-suggestions-available-in-outlook)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Corrige un problema que provocaba que la búsqueda no devuelve ningún resultado al buscar en los calendarios compartidos sin almacenamiento en caché.


- Corrige un problema que causaba que algunos usuarios observaban Outlook de forma inesperada en un estado sin conexión.


- Corrige un problema que causaba que los delegados vean errores intermitentes al abrir carpetas compartidas en otro buzón.


### <a name="powerpoint"></a>PowerPoint

- Corrección de seguridad para solucionar un problema que deshabilita las protecciones IRM al abrir un archivo de PowerPoint en la vista protegida.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Cuando el usuario imprime cualquier documento o archivo en las impresoras de inyección de tinta de Office y la tinta de la impresora es poco visible, el mensaje "tóner bajo" o "sin tóner" se mostrará, aunque las impresoras de inyección de tinta no tengan tóners. Cambiar mensaje para mostrar "tóner/tinta bajos" & "no tóner/tinta".



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2009-september-26"></a>Versión 2009: 26 de septiembre
*Versión 2009 (Compilación 13231.20262)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Corrige un problema que causaba que se enviaran algunos mensajes de correo electrónico generados automáticamente con el cuerpo en blanco cuando la línea del asunto está en blanco.


### <a name="project"></a>Project

- Se ha corregido un problema por el que si se ejecuta un código de evento y se intenta realizar cambios desde la vista del Formulario de tareas, es posible que el botón Aceptar no confirme los cambios.


[//]: # (NO QUITAR EL CONTENIDO DE LOS DETALLES DE ERROR FINAL)

## <a name="version-2009-september-21"></a>Versión 2009: 21 de septiembre
*Versión 2009 (Compilación 13231.20200)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="access"></a>Acceso

- **Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10. Vaya a Archivo > Opciones y seleccione "Usar configuración del sistema" junto al Tema de Office. [Más información](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a>Excel

- **Inserte las fotos de su iPhone directamente en Office:** las imágenes HEIC de su teléfono ahora se insertan sin problemas en Office. No es necesario realizar ninguna conversión.<br />Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)

- **Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10. Vaya a Archivo > Opciones y seleccione "Usar configuración del sistema" junto al Tema de Office. [Más información](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a>OneNote

- **Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10. Vaya a Archivo > Opciones y seleccione "Usar configuración del sistema" junto al Tema de Office. [Más información](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a>Outlook

- **Eliminar conversación por propietario del mensaje:** esta característica permite eliminar una conversación por propietario del mensaje.

- **Inserte las fotos de su iPhone directamente en Office:** las imágenes HEIC de su teléfono ahora se insertan sin problemas en Office. No es necesario realizar ninguna conversión.<br />Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)

- **Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10. Vaya a Archivo > Opciones y seleccione "Usar configuración del sistema" junto al Tema de Office. [Más información](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="powerpoint"></a>PowerPoint

- **Inserte las fotos de su iPhone directamente en Office:** las imágenes HEIC de su teléfono ahora se insertan sin problemas en Office. No es necesario realizar ninguna conversión.<br />Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)

- **Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10. Vaya a Archivo > Opciones y seleccione "Usar configuración del sistema" junto al Tema de Office. [Más información](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a>Project

- **Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10. Vaya a Archivo > Opciones y seleccione "Usar configuración del sistema" junto al Tema de Office. [Más información](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a>Publisher

- **Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10. Vaya a Archivo > Opciones y seleccione "Usar configuración del sistema" junto al Tema de Office. [Más información](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a>Visio

- **Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10. Vaya a Archivo > Opciones y seleccione "Usar configuración del sistema" junto al Tema de Office. [Más información](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a>Word

- **Inserte las fotos de su iPhone directamente en Office:** las imágenes HEIC de su teléfono ahora se insertan sin problemas en Office. No es necesario realizar ninguna conversión.<br />Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/insert-apple-photos-into-office-easily)

- **Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10. Vaya a Archivo > Opciones y seleccione "Usar configuración del sistema" junto al Tema de Office. [Más información](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema que provocaba la coautoría lenta en archivos que contienen números grandes de determinados tipos de objetos de datos (E2o).



[//]: # (NO QUITAR EL EXTREMO DEL CONTENIDO CON LOS DETALLES DEL ERROR)

## <a name="version-2009-september-14"></a>Versión 2009: 14 de septiembre
*Versión 2009 (compilación 13231.20152)*
* Varias correcciones de errores y rendimiento.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

## <a name="version-2009-september-10"></a>Versión 2009: 10 de septiembre
*Versión 2009 (Compilación 13231.20126)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Acceso

- Se ha corregido el problema y ya no se debería experimentar el bloqueo.


- Se ha corregido un problema por el que las conexiones a una base de datos ODBC no funcionaban con aplicaciones de terceros.


### <a name="excel"></a>Excel

- Se corrigió un problema por el cual si abría un archivo que contiene la función LET, mostraba la alerta: "Encontramos un problema con el contenido en "su archivo.xlsx". ¿Quiere que intentemos recuperar todo lo que podamos? Si confía en el origen de este libro, haga clic en Sí".


- Hemos corregido un problema en el que si un usuario escribía el nombre de una fórmula, incluidos los paréntesis, e invocaba ayuda a través de F1, el tema de ayuda específico de esa fórmula no se mostraba.


- Se ha corregido un problema por el que, al usar una macro para establecer la propiedad FormulaR1C1 para un rango, las referencias de celda eran incorrectas si una hoja de gráfico era la hoja activa.


- Se corrigió un problema por el cual los usuarios no podían modificar un filtro de tabla dinámica porque estaba configurado en un valor que ya no estaba presente en una base de datos de Analysis Services.


- Se corrigió un bloqueo relacionado con las referencias de complementos XLAM y los rangos con nombre.


- Se corrigió un problema por el que si un usuario aplicaba un estilo personalizado a una matriz dinámica, obtenía el error: "No se puede cambiar parte de una matriz". Se ha eliminado una restricción heredada.


- Se corrigió un problema que provocaba que los macros asignados a los botones no funcionen después de restaurar una versión anterior del archivo.


- Se ha corregido un problema por el que las entradas manuscritas podrían hacer que Excel dejara de responder.


### <a name="outlook"></a>Outlook

- Se corrigió un problema que proporciona más flexibilidad para habilitar o deshabilitar las opciones de registro predeterminadas mediante la directiva de grupo.


- Se corrigió un problema por el que el nombre de dominio heredado de un remitente de correo electrónico se conservaba y mostraba después de que se moviera un borrador del correo electrónico entre buzones con permisos de asistente y permisos de administrador.


- Se corrigió un problema que provocaba que algunos usuarios vieran que Outlook se iniciaba en un estado sin conexión hasta que optaban manualmente por trabajar en línea.


- Se corrigió un problema por el cual ejecutar el código VBA ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") después de habilitar Cinta de opciones de una línea (SLR) daba como resultado un error de tiempo de ejecución.


- Se corrigió un problema por el cual los botones 'Aceptar' y 'Cancelar' en el cuadro de diálogo Respuestas automáticas no eran visibles en un sistema con una resolución alta (como 1750 x 1920) combinada con un tamaño de texto grande (como 175 %).


- Se corrigió una condición por la que enviar una convocatoria de reunión desde un grupo de contactos vacío a otro grupo de contactos provocaba un bloqueo.


- Se corrigió un problema que provocaba que los usuarios experimentaran un bloqueo al abrir algunos correos electrónicos muy grandes.


- Se corrigió un problema por el que si la directiva de grupo requiere que un complemento esté siempre habilitado, los complementos de supervisión no están disponibles para evitar que los usuarios deshabiliten el complemento.


- Resuelve un problema debido al cual los usuarios podían enviar contenido de correo electrónico que incluía una directiva de "No reenviar" aplicada a OneNote al seleccionar más de un mensaje.


- Se ha corregido un problema por el que los usuarios ahora pueden deshabilitar IRM (Information Rights Management) para Outlook sin tener que deshabilitarlo para el resto de las aplicaciones de Office.


- Se ha corregido un problema que provocaba que los atributos de la cuenta de usuario de Active Directory para "otherTelephone" y "otherHomePhone" no se asignaran a los atributos LDAP correspondientes de Outlook.


- Este cambio corrige un problema que hace que la página de Reunión continuara mostrándose después de que el usuario había cambiado de pestaña desde la página Reunión a la página del Asistente para programación.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema que provocaba que los usuarios no pudieran ver la barra de herramientas o de título en ciertas condiciones.


- Se corrigió un problema por el cual, después de iniciar PowerPoint, insertar una diapositiva y abrir y cerrar el panel de comentarios, las diapositivas en el panel de miniaturas se mostraban superpuestas.


- Se corrigió un problema que deshabilitaba la funcionalidad para insertar un vídeo.


- Se corrigió un problema que provocaba que los vídeos no se reproducieran de manera automática en las presentaciones.


### <a name="project"></a>Project

- Se corrigió un problema por el cual si un recurso tiene varias tablas de tasas de coste, es posible que el coste restante no se calcule correctamente.


- Se ha corregido un problema que provocaba que la fecha de finalización de Project no se actualice para los proyectos conectados a la lista de tareas de SharePoint.


### <a name="visio"></a>Visio

- Los usuarios han reportado el bloqueo de la Vista previa dinámica en la alineación del texto. Bloqueo al llegar a la parte superior en la bifurcación de repositorio de julio.


### <a name="word"></a>Word

- Se corrigió un problema por el cual la tarjeta de Comentarios mostraba un borde alrededor del texto del comentario si el usuario hacía clic en el comentario.


- Se ha corregido un problema que provocaba que el icono de la imagen de viñeta no se mostrara de forma correcta.


- Se ha corregido un problema que impedía al usuario salir del encabezado o pie de página al seleccionar un comentario.


- Se ha corregido un problema que provocaba que Word se pudiera bloquear después de eliminar comentarios.


- Se corrigió un problema por el cual si un usuario creaba un borrador de comentario anclado a una línea que ya contenía comentarios comprometidos, el borrador se organizaba en el orden incorrecto en relación con el comentario comprometido en SideTrack.


- Se corrigió un problema por el cual el foco no iba al panel de comentarios si el documento se ampliaba al 160 % o más y el panel de comentarios no estaba visible.


- Hemos corregido un problema que impedía a los usuarios ver los hilos de comentarios que superaran el límite de la barra de los comentarios, porque el desplazamiento por dicha barra no funcionaba.


- Hemos corregido un problema que impedía la búsqueda de comentarios resueltos en el panel de los comentarios.


- Se corrigió un problema por el cual los comentarios de un documento se mostraban en otros documentos abiertos después de cambiar entre varios documentos abiertos.


- Se corrigió un problema que provocaba que los vínculos largos no se ajustaran al guardar un documento en formato HTML.


- Se ha corregido un problema que provocaba que, en algunos casos, las viñetas no se mostraran de forma correcta en el correo electrónico.


- Se corrigió un problema con las macros que provocaba que AutoOpen se ejecutara antes de AutoExec.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema en la Herramienta de implementación de Office que provocaba errores en la configuración al usar la característica RemoveMSI con el producto de Office 2007 "Informes de errores de aplicaciones de Microsoft".


- Se ha corregido un problema en el cuadro de diálogo Comprimir imágenes que impedía que se conservaran algunas opciones de configuración de PPP seleccionadas por el usuario.


- Este cambio resuelve un problema con el cuadro de diálogo de Comprimir imagen, que no retiene determinadas configuraciones de usuario.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2008-september-04"></a>Versión 2008: 04 de septiembre
*Versión 2008 (compilación 13127.20378)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Este cambio resuelve un problema con el cuadro de diálogo de Comprimir imagen, que no retiene determinadas configuraciones de usuario.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2008-september-02"></a>Versión 2008: 02 de septiembre
*Versión 2008 (compilación 13127.20360)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Guarde formas como imágenes:** con tan solo unos pocos clics, guarde una forma, icono u otro objeto como archivo de imagen para que pueda volver a usarlo en otro lugar. [Más información](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- **Realice cambios rápidos con el lápiz de Excel:** herramienta bolígrafo que le ayudará a escribir a mano y realizar cambios rápidos en los datos



[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema que provocaba que Excel se bloqueara en determinadas circunstancias al usar Copiar formato.


### <a name="word"></a>Word

- Se ha corregido un problema por el cual los estilos base no se actualizaban con el estilo Normal.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2008-august-27"></a>Versión 2008: 27 de agosto
*Versión 2008 (Compilación 13127.20296)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Corrige un problema que evitaba que los usuarios que intentaran crear una solicitud de reunión desde una cuenta secundaria añadida a su perfil vieran el campo De: en blanco en lugar de su dirección de correo electrónico.

- Corrige un problema que evitaba que los usuarios se conectaran a las carpetas públicas luego de agregar un buzón compartido.

- Corrige un problema que provocaba que los usuarios experimentaran bloqueos ocasionales al interactuar con datos adjuntos en la nube.

- Esto corrige un problema que provocaba que los usuarios experimentaran bloqueos ocasionales al editar los destinatarios.

- Corrige un problema que provocaba que los usuarios vieran anomalías al usar la vista compacta.

### <a name="word"></a>Word

- Este cambio corrige un problema que provocaba que las aplicaciones de Office se queden atascadas en un estado de error de guardado silencioso después de una sesión de coautoría anterior.

- Se ha corregido un problema por el que se ejecuta la macro AutoOpen antes de AutoExec.



[//]: # (NO QUITAR DETALLES DE ERROR DEL FIN DE CONTENIDO)

## <a name="version-2008-august-25"></a>Versión 2008: 25 de agosto
*Versión 2008 (Compilación 13127.20268)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Reciba sugerencias por correo electrónico al buscar por persona.:** A medida que escriba los términos de búsqueda en Outlook, recibirá los correos electrónicos más relevantes en las sugerencias.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Corrige un problema que provocaba que los usuarios recibieran el siguiente error al responder a un correo o al redactar uno nuevo: "Algunos archivos de esta página web no están en la ubicación esperada. ¿Desea descargarlos de todos modos? Si está seguro de que la página web es una fuente de confianza, haga clic en Sí".


### <a name="project"></a>Project

- Se ha corregido un problema debido al cual, si un recurso tenía más de una tabla de tasa de costo definida, el costo restante no siempre se calculaba correctamente.


### <a name="word"></a>Word

- Corrige un problema que provocaba que los usuarios experimentaran un bloqueo al responder a un correo o al redactar uno nuevo.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2008-august-17"></a>Versión 2008: 17 de agosto
*Versión 2008 (Compilación 13127.20208)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba un error en la eliminación de las reuniones del calendario de un administrador cuando un delegado las rechazaba en determinadas circunstancias.


- Se ha corregido un problema que provocaba que los usuarios de algunos juegos de caracteres viesen nombres de archivo que se mostraban de forma incorrecta al agregar un vínculo inteligente a un archivo de SharePoint.


- Se ha corregido un problema que provocaba que los usuarios experimentaran un error al eliminar 4 o más mensajes de correo electrónico de una cuenta POP con la opción "Descargar solo encabezados" seleccionada.


- Se ha corregido un problema que provocaba que el menú contextual del botón derecho no apareciera en los controles de búsqueda.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2008-august-11"></a>Versión 2008: 11 de agosto
*Versión 2008 (Compilación 13127.20164)*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Acceso

- Esta corrección resuelve un problema por el que al intentar ejecutar determinadas consultas anteriormente se generaba el mensaje de error "La consulta es demasiado compleja".

- Si tiene Office 365 instalado, ya no necesita instalar el nuestro motor de Componente redistribuíble de ACE para exponer ACE fuera del ecosistema de Office. Por ello, los usuarios con Office 365 ya no necesitarán el motor de Componente redistribuíble de ACE por lo que no debería experimentar este problema.

- Este problema se ha resuelto: ahora puede usar el controlador ODBC fuera de las aplicaciones de Hacer clic y ejecutar de Office.

### <a name="excel"></a>Excel

- Se ha corregido un problema por el que si se cambia el orden de una serie de gráficos, la casilla de verificación correspondiente alineada con la serie no se reordenaba junto con la serie.

- Se puede producir un error al intentar guardar un archivo que contiene una fórmula con la función LET().

- Se corrigió un problema por el que los gráficos no siempre se actualizaban como se esperaba al habilitar "ForceFullCalculation" a través de VBA en el libro.

- Se corrigió un problema por el que una copia de una imagen con un relleno degradado radial no coincidía con el original.

### <a name="onenote"></a>OneNote

- Se ha corregido un problema que provocaba que el texto de marcador de posición en el cuadro de edición de búsqueda se desbordase si se reducía el tamaño de la ventana de la aplicación.

### <a name="outlook"></a>Outlook

- Se corrigió un problema en la creación de varios perfiles en Outlook desde el mismo dominio de correo electrónico.

- Se corrigió un problema que impedía a algunos usuarios de la característica Mejoras del calendario compartido ver un calendario compartido recién agregado.

- Se corrigió un problema por el que el icono de bloqueo no se mostraba en el encabezado de los mensajes cifrados S/MIME.

- Se corrigió un problema por el que la opción Permitir reenvío no aparecía en las Opciones de respuesta de las reuniones del calendario compartido en aquellos casos en los que la carpeta de descarga compartida NO se había comprobado.

- Se ha corregido un problema que evitaba que los usuarios guardaran los datos adjuntos de OneDrive desde fuera de su inquilino en su equipo local al seleccionar la opción "Guardar" en el cuadro de diálogo de seguridad.

- Se corrigió un problema por el que el botón Imprimir aparecía en un estado deshabilitado aunque el usuario tuviera los permisos de impresión adecuados.

- Se corrigió un problema por el que los datos adjuntos se quitaban de mensajes S/MIME al enviarse sin cifrar.

- Se corrigió un problema por el que los mensajes de texto sin formato S/MIME se volvían ilegibles al enviarse.

- Se corrigió un problema por el que los datos adjuntos se dañaban al enviar un correo electrónico S/MIME sin cifrar.

- Se corrigió un problema por el que los destinatarios no podían guardar los mensajes con derechos protegidos incluso cuando el remitente otorgaba el permiso de Guardar como.

- Esta corrección aborda un problema que hacía que los usuarios no pudieran agregar una firma al responder a un mensaje administrado con derechos digitales desde una ventana de inspección cuando el usuario no tenía permisos de propietario sobre el mensaje al que se respondía.

- La corrección aborda un problema que provocaba que Outlook no mostrara correctamente los saltos de línea en el contenido de Markdown.

- Se corrigió un problema por el que las etiquetas de algunas opciones de Búsqueda avanzada se truncaban en algunos idiomas.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema por el que una copia de una imagen con un relleno degradado radial no coincidía con el original.

- Se corrigió un problema por el que el botón Formularios de PowerPoint no permitía la creación de formularios cuando no se permitía el acceso a la Tienda Office.

### <a name="project"></a>Project

- Se corrigió un problema por el que las tareas que aparecen en la vista Panel de tareas no estaban sincronizadas con las del cuadro de diálogo Asignar recursos.

- Se corrigió un problema que impedía al usuario guardar desde Project un PDF o XPS en una biblioteca de documentos de SharePoint.

- Se corrigió un problema por el que si se copiaba y pegaba una tarea con varias dependencias, no se copiaban todas las dependencias correctamente.

- Se corrigió un problema por el que en una lista de tareas de SharePoint, los botones de la cinta de opciones en la segunda pestaña se podían deshabilitar.

### <a name="skype"></a>Skype

- Se cambió el tono de piel del emoticono de baile a un color neutro

### <a name="visio"></a>Visio

- Después de esta corrección, si el usuario detiene la ejecución del comando Delete con algún mecanismo intermedio (en este caso, con un complemento) la memoria no se verá afectada, y no afectará a todo el equipo.

### <a name="word"></a>Word

- Se ha corregido un problema que provocaba que Word dejara de responder después de pegar texto y una imagen en un cuadro de comentarios.

- Se corrigió un problema por el que una copia de una imagen con un relleno degradado radial no coincidía con el original.

- Se ha corregido un problema que provocaba que el texto de marcador de posición en el cuadro de edición de búsqueda se desbordase si se reducía el tamaño de la ventana de la aplicación.

- Se corrigió un problema por el que si se agregaba un comentario para realizar el seguimiento de un cambio, el panel de revisiones se abría de forma inesperada.

- Se corrigió un problema por el que el comando Editor se deshabilitaba cuando el foco estaba en un cuadro de texto de comentario.

- Se corrigió un problema por el que el comando Mostrar marcas se deshabilitaba cuando el foco estaba en un cuadro de texto de comentario.

- Se corrigió un problema por el que el botón Nuevo comentario quedaba deshabilitado después de eliminar el último comentario.

- Se corrigió un problema por el que se deshabilitaba la opción Personas específicas de Control de cambios.

- Se corrigió un problema por el que los vínculos a los documentos no se insertaban en el cuadro de comentarios a través de la lista desplegable Insertar > Vínculo.

- Se corrigió un bloqueo ocasional al abrir archivos HTML.

- Se corrigió un problema en un archivo XML personalizado en el que se podía perder el estado de los comentarios al abrir el documento.

- Se ha corregido un problema por el que el recuento de hipervínculos en la colección de hipervínculos de VBA no realizaba correctamente la iteración después de agregar una imagen que contenía un hipervínculo.

- Para un antiguo panel de uso compartido basado en servicio no Web, al cerrar el documento mientras el panel de uso compartido está abierto, se podría producir un bloqueo. Este problema ya está solucionado.

- Se corrigió un problema en el que, después de abrir el usuario una nueva ventana de la aplicación desde la barra de tareas y crear un nuevo documento en blanco, se creaban archivos adicionales.

- Se corrigió un problema por el que, si un usuario estaba editando un documento pero había perdido los permisos, no se informaba al usuario de que tenía que volver a autenticarse.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2007-august-05"></a>Versión 2007: 05 de agosto
*Versión 2007 (compilación 13029.20344)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)



[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se corrigió un problema que provocaba que Outlook no pudiese recuperar sugerencias de búsqueda.


- Se corrigió un problema que provocaba que los usuarios se bloquearan en ocasiones al recuperar información personal.


### <a name="project"></a>Project

- Se corrigió un problema por el que no se podía abrir un proyecto que estaba en mal estado.



[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)

## <a name="version-2007-july-29"></a>Versión 2007: 29 de julio
*Versión 2007 (compilación 13029.20308)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Obtenga datos de organización de Power BI mediante Tipos de datos:** los tipos de datos de Excel de Power BI se están publicando ahora para participantes de Office Insider en las organizaciones con Office 365 E5/A5 o Microsoft 365 E5/A5. Obtener la información que necesita y actualizarla fácilmente es fundamental para muchos de los flujos de trabajo diarios. Le proporcionamos acceso a la información de Power BI de su empresa u organización como un tipo de datos en Excel, lo que amplía su capacidad de incorporar a las hojas de cálculo información vinculada. [Más información](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)

### <a name="outlook"></a>Outlook

- **Elija dónde buscar:** La nueva lista desplegable del ámbito de búsqueda le permite modificar de manera más sencilla su búsqueda y cambiar entre la carpeta actual y el buzón actual. Gracias a todos los usuarios de Próximamente, quienes brindaron comentarios acerca de la nueva experiencia de búsqueda Search at Top. ¡Este diseño y actualización son el resultado de sus comentarios!

### <a name="word"></a>Word

- **Mejor colaboración con comentarios modernos:** Agregue comentarios a objetos, @mencione compañeros y resuelva hilos de comentarios para disfrutar de una mejor experiencia de colaboración. [Más información](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que los usuarios de CLP experimenten un bloqueo al cambiar la dirección del remitente en una respuesta desde un contexto protegido a uno no protegido.


- Se ha corregido un problema que provocaba que la página del Asistente para programación no se mostrara.


- Se ha abordado un problema que causaba problemas de formato en las alertas de notificación de incidentes.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2007-july-27"></a>Versión 2007: 27 de julio
*Versión 2007 (compilación 13029.20292)*
* Varias correcciones de errores y rendimiento.

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


- Se ha corregido un problema que provocaba que los usuarios vieran el siguiente error al cerrar una cita guardada previamente: "No se puede guardar el elemento porque otro usuario lo modificó o se modificó en otra ventana. ¿Quiere realizar una copia en la carpeta predeterminada del elemento?".


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


- Se ha corregido un problema por el que, si las tareas de duración fija estaban completas al 100 %, pero no se especificaba la fecha de finalización real, el porcentaje de finalización de la tarea se mostraba como inferior al 100 %.

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

- **Mantenga la fidelidad de sus imágenes cuando las envíe como parte de un correo electrónico:** una nueva configuración de Outlook está disponible para limitar la compresión de imágenes cuando envía imágenes como parte de contenido del correo electrónico


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



- **Guardar en Carpetas ancladas:** anclar tus carpetas hace que el almacenamiento de archivos de Office sea más fácil. Nuestros usuarios nos dijeron que querían tener más control sobre las carpetas disponibles al guardar un archivo nuevo. Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar. Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil. <br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

### <a name="powerpoint"></a>PowerPoint

- **Guardar en Carpetas ancladas:** anclar tus carpetas hace que el almacenamiento de archivos de Office sea más fácil. Nuestros usuarios nos dijeron que querían tener más control sobre las carpetas disponibles al guardar un archivo nuevo. Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar. Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil.<br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

### <a name="word"></a>Word

- **Guardar en Carpetas ancladas:** anclar tus carpetas hace que el almacenamiento de archivos de Office sea más fácil. Nuestros usuarios nos dijeron que querían tener más control sobre las carpetas disponibles al guardar un archivo nuevo. Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar. Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil. <br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

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


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

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

- **Crear tablas dinámicas de conjuntos de datos en Power BI desde Excel:** puede crear tablas dinámicas en Excel conectadas a los conjuntos de datos almacenados en Power BI con tan solo unos clics. Así, podrá obtener lo mejor de las tablas dinámicas y de Power BI. Calcule, resuma y analice los conjuntos de datos seguros de Power BI con las tablas dinámicas de Excel.

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

- El host de Office se bloqueaba en Windows, cuando se activaba un complemento si la clave del registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth estaba establecida en cero. Este cambio solucionaría el problema.


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2005-may-21"></a>Versión 2005: 21 de mayo
*Versión 2005 (compilación 12827.20210)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)




[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

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

- **Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos ahora son más elegantes. [Más información](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01).

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



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

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



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

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

- **Nueva opción para desactivar las sugerencias de @menciones al escribir correo en Outlook:**¿le resulta el selector de @menciones más molesto que útil? Ahora puede desactivarlo si lo prefiere.

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

### <a name="project"></a>Project

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

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)


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

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)
### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel
- **Etiquetas de confidencialidad**: ahora puede aplicar una etiqueta de confidencialidad que la organización ha configurado para pedirle permisos personalizados. [Más información](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a>PowerPoint
- **Etiquetas de confidencialidad**: ahora puede aplicar una etiqueta de confidencialidad que la organización ha configurado para pedirle permisos personalizados. [Más información](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a>Word
- **Etiquetas de confidencialidad**: ahora puede aplicar una etiqueta de confidencialidad que la organización ha configurado para pedirle permisos personalizados. [Más información](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)
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

- Se ha corregido un problema en Word/Excel/PowerPoint donde el nombre principal de usuario (UPN) ya no distingue entre mayúsculas y minúsculas, lo que provoca menos errores al trabajar con archivos en SharePoint.

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

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)


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

- Esta actualización corrige un problema por el que al usar un objeto ADODB. Recorder en código de VB podía notificarse un error incorrectamente.

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
