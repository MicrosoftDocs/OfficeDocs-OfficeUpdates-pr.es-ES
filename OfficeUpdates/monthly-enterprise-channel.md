---
title: Notas de la versión para las versiones de canal de empresa mensual en 2020
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Proporciona a los profesionales de TI las notas de la versión para las versiones de canal mensual de empresa para Aplicaciones de Microsoft 365 en 2020
ms.openlocfilehash: f76ceaf76f505d9a4301f2bba66c9efcb6278ca4
ms.sourcegitcommit: 9fba85e39543d5fa71669437ad88913c574c4371
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 07/15/2020
ms.locfileid: "45138686"
---
# <a name="release-notes-for-monthly-enterprise-channel-releases-in-2020"></a>Notas de la versión para las versiones de canal de empresa mensual en 2020

Estas notas de la versión proporcionan información sobre las nuevas características y las actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones del Canal de empresa mensual en 2020 para Aplicaciones de Microsoft 365 para empresas, Aplicaciones de Microsoft 365 para negocios y las versiones de suscripción de las aplicaciones de escritorio de Project y Visio.

> [!IMPORTANT]
> Estamos realizando algunos cambios en los canales de actualización de las Aplicaciones de Microsoft 365, incluida la adición de un nuevo canal de actualización (canal empresarial mensual) y el cambio de los nombres de los canales de actualización existentes. [Lea este artículo](https://go.microsoft.com/fwlink/p/?linkid=2127441) para obtener más información.

[//]: # (NO ELIMINAR)



## <a name="version-2005-july-14"></a>Versión 2005: 14 de julio
*Versión 2005 (compilación 12827.20538)*

Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Mejores resultados, en un instante:** actualizamos la experiencia de búsqueda para que sea más inteligente, rápida y fiable que nunca. [Más información](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

### <a name="word"></a>Word

- **Decirlo de otra forma:** si lo quiere decir de forma diferente, la reescritura le puede ayudar. La reescritura ofrece alternativas para afinar sus frases.<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/08/12/rewrite-in-word-say-it-another-way/)


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Acceso

- Se ha corregido un problema para poder llamar al tipo de datos Fecha/Hora ampliado en el código sin tener que bloquear la aplicación.

- Se ha corregido un problema de forma que ahora puede volver a la versión de Access más actualizada y usar DAO/VBA para administrar y editar un tipo de datos decimal.

### <a name="excel"></a>Excel

- Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.

- En algunos casos, al hacer clic en un hipervínculo que dirige a un lugar del mismo libro, el libro queda oculto.

- Se ha corregido un problema que provocaba que se quitara el XML de CustomUI para una ficha de cinta al guardar en SharePoint o OneDrive.

- Se ha corregido un problema por el que Excel se bloqueaba al intentar insertar tablas dinámicas en una hoja de gráfico.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al enviar comentarios desde una Notificación de administrador.

- Se ha corregido un problema por el que la búsqueda de una característica en Sugerir una característica no devolvía resultados y no ofrecía al usuario ninguna opción para enviar una nueva característica.

- Se ha corregido un problema que provocaba que los usuarios de Outlook vieran continuamente un aviso para que ejecutaran la herramienta de Reparación de la bandeja de entrada.

- Se ha corregido un problema que provocaba que los usuarios de las versiones de Windows 10 Server vieran la advertencia: “Estado de antivirus: no válido. Esta versión de Windows admite la detección del antivirus, pero no se encontró ninguno” a pesar de tener un antivirus correctamente instalado.

- Se ha corregido un problema que causaba que los usuarios experimentasen bloqueos y interrupciones intermitentes en algunos casos.

- Se ha corregido un problema que provocaba que los usuarios de las mejoras del Calendario compartido vieran errores en el calendario.

- Se ha corregido un problema que hacía que los usuarios vieran el mensaje &quot;Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange&quot; al actualizar sus reglas en Outlook.

- Se ha corregido un problema que causaba que la fecha de&nbsp; creación de datos adjuntos copiados en el sistema de archivos a través de la opción de arrastrar y soltar apareciera como el 1 de enero de 4501.

- Se ha corregido un problema por el que Outlook no pudo habilitar consejos de directiva para la Protección de pérdida de datos para usuarios que pagaron por el servicio con planes M365 Business Plus.

- Se ha corregido un problema con el evento de auditoría CLP para la etiqueta de responder o reenviar.


### <a name="powerpoint"></a>PowerPoint

- Hemos corregido un bloqueo cuando el usuario tiene comentarios modernos y heredados en un archivo, lo que provoca una actualización de los comentarios.

- Se ha corregido un problema de bloqueo en el panel de sugerencias.


### <a name="project"></a>Project

- Se ha corregido un problema por el que el evento ProjectBeforeTaskChange no se activaba al darse un cambio en la tarea de resumen del proyecto: ya sea en el campo de inicio o tarea del proyecto.

- Se ha corregido un problema por el que una tarea marcada como completada al 100 % se mostraba por error no completada al 100 %.

### <a name="skype"></a>Skype

- Cuando se asignaba a un usuario una directiva que lo llevaba a Teams solo, aún se podía usar el complemento para Outlook de Skype Empresarial para programar reuniones. Tras esta actualización, ya no se podrán programar reuniones de Skype Empresarial después de que el cliente lea la directiva en la que se indica que el usuario participa en Teams solo y entra en la reunión como Unirse solo. Además, el complemento de Outlook para Skype Empresarial no se activará durante el inicio si ve que el cliente de Skype Empresarial se encuentra en modo de Unirse solo.

### <a name="word"></a>Word

- Se ha corregido un problema que puede haber provocado un bloqueo al arrastrar el contenido desde la aplicación.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Este cambio resuelve posibles bloqueos al cargar y reproducir contenido animado, como GIF o modelos 3D.

- Hemos resuelto el problema de la tasa de error de ValidateInstall estableciendo la validación de instalación del Complemento de Bing como verdadera de forma predeterminada y considerando el éxito de devolución de MSI como una instalación con éxito.

- Esta actualización corrige un problema en Microsoft Office en el que los proyectos de Visual Basic para aplicaciones con referencias que se espera encontrar buscando las ubicaciones especificadas en la variable de entorno PATH podían no encontrarse correctamente en tiempo de ejecución, lo que provoca errores en tiempo de ejecución de VBA.

- Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.

- El host de Office se bloqueaba en Windows, cuando se activaba un complemento si la clave del registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth estaba establecida en cero. Este cambio arreglaría el problema.


[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2004-july-14"></a>Versión 2004: 14 de julio
*Versión 2004 (compilación 12730.20602)*

Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

## <a name="version-2004-june-09"></a>Versión 2004: 09 de junio
*Versión 2004 (compilación 12730.20430)*

Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="access"></a>Acceso

- **Agregue tablas con menos clics:** utilizar el panel de tareas agregar tablas, que permanece abierto mientras trabaja, para agregar tablas a relaciones y consultas. [Más información](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a>Excel

- **Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **El soporte para el conector de Facebook va a terminar:** a partir de abril de 2020. Excel ya no admitirá conexiones de datos externos que usen el conector de Facebook.

- **Nuevas imágenes para dar vida a sus libros de trabajo:** miles de imágenes de archivo, iconos y adhesivos sin derechos de autor que puede usar en sus libros de trabajo. Vaya a Insertar > Imágenes > Imágenes de archivo para empezar. [Más información](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/04/06/premium-creative-content/)

### <a name="outlook"></a>Outlook

- **Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Arrastre el correo electrónico a un grupo de tu propiedad:** Mueva y copie mensajes y conversaciones arrastrándolos desde su bandeja de entrada. Los mensajes que arrastres serán compartidos con todos los miembros del grupo.<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)

- **El calendario se transforma:** vea las actualizaciones visuales que hacen que el calendario sea más fácil de examinar. [Más información](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)

- **Nuevas imágenes para dar vida a sus mensajes:** miles de imágenes de archivo, iconos y adhesivos sin derechos de autor que puede usar en sus mensajes de correo electrónico. Vaya a Insertar > Imágenes > Imágenes de archivo para empezar. [Más información](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/04/06/premium-creative-content/)

### <a name="powerpoint"></a>PowerPoint

- **Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Sincronice los cambios mientras realiza la presentación:** sincronice los cambios cuando se hagan aunque la presentación esté en el modo de presentación con diapositivas. [Más información](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)

- **Nuevas imágenes para dar vida a sus diapositivas:** miles de imágenes de archivo, iconos y adhesivos sin derechos de autor que puede usar en sus diapositivas. Vaya a Insertar > Imágenes > Imágenes de archivo para empezar. [Más información](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/04/06/premium-creative-content/)

### <a name="word"></a>Word

- **Selección de lazo de la entrada de lápiz:** la herramienta Lazo en la pestaña Dibujar le ayuda a seleccionar objetos dibujados a mano. Seleccione trazos individuales o palabras completas. [Más información](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Nuevas imágenes para dar vida a sus documentos:** miles de imágenes de archivo, iconos y adhesivos sin derechos de autor que puede usar en sus documentos. Vaya a Insertar > Imágenes > Imágenes de archivo para empezar. [Más información](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/04/06/premium-creative-content/)

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- **Etiquetas de confidencialidad:** ahora puede aplicar una etiqueta de confidencialidad que su organización ha configurado para solicitarle permisos personalizados.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema que hacía que el vínculo externo dejara de funcionar después de que se volviera a abrir el archivo si su ruta de acceso era demasiado larga.

- Application.Evaluate (VBA) no funcionaba para funciones definidas por el usuario en algunos casos.

- En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.

- Se ha corregido un problema que hacía que Excel se bloqueara en ciertos casos después de copiar una hoja que contenía una tabla dinámica.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al enviar comentarios desde una Notificación de administrador.

- Se ha corregido un problema que provocaba que los usuarios experimentaran un error al salir de Outlook.

- Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al mostrar las notificaciones del sistema.

- Se ha corregido un problema que provocaba que Outlook se bloqueara al abrir archivos .msg y .oft guardados localmente después de una actualización de Windows.

- Se ha corregido un problema que provocaba que Outlook se bloqueara en algunas compilaciones de Windows.

- Se ha corregido un problema que provocaba que el ancho del panel de carpetas cambiara inesperadamente.

### <a name="project"></a>Project

- Cuando se editan los datos del Predecesor/Sucesor dentro de una vista de formulario, se activa un evento ProjectBeforeTaskChange adicional.

- Se ha corregido un problema que hace que si está usando Project conectado a Project Web App y el separador decimal es una coma, el método TaskDependencies Add producirá un error al intentar agregar retardo a una dependencia.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema de hacer clic y ejecutar que generaba errores de actualización al intentar crear un vínculo físico para vínculos simbólicos.

- El host de Office se bloqueaba en Windows, cuando se activaba un complemento si la clave del registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth estaba establecida en cero. Este cambio arreglaría el problema.

- Esta corrección resuelve un error que impide restringir el acceso y proteger los archivos con una contraseña de forma simultánea.

- Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.

- Esta actualización corrige un problema en Microsoft Office en el que los proyectos de Visual Basic para aplicaciones con referencias que se espera encontrar buscando las ubicaciones especificadas en la variable de entorno PATH podían no encontrarse correctamente en tiempo de ejecución, lo que provoca errores en tiempo de ejecución de VBA.



[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2003-june-09"></a>Versión 2003: 09 de junio
*Versión 2003 (compilación 12624.20708)*

Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Esta actualización corrige un problema en Microsoft Office en el que los proyectos de Visual Basic para aplicaciones con referencias que se espera encontrar buscando las ubicaciones especificadas en la variable de entorno PATH podían no encontrarse correctamente en tiempo de ejecución, lo que provoca errores en tiempo de ejecución de VBA.

[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2003-may-12"></a>Versión 2003: 12 de mayo
*Versión 2003 (compilación 12624.20588)*

Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="access"></a>Access

- **Aumente su productividad con el Diseñador de consultas, la vista SQL y la ventana Relaciones:** haga clic con el botón derecho en una tabla para abrirla, diseñarla, cambiar su tamaño y ocultarla. Buscar y reemplazar texto en la vista SQL. Seleccione múltiples tablas en la ventana Relaciones.

### <a name="excel"></a>Excel

- **Escriba una fórmula que devuelva varios valores: **Escriba rápidamente una fórmula que devuelva múltiples valores y se derramarán automáticamente en las celdas vecinas. [Más información](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)

- **Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. 

- **Seis potentes funciones:** Seis potentes funciones: Hemos agregado seis nuevas funciones para mejorar las hojas de cálculo: FILTRAR, ORDENAR, ORDENARPOR, UNICOS, SECUENCIA y MATRIZALEAT. [Más información](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- **Busque a la izquierda, busque a la derecha... BUSCARX ya está aquí**: fila por fila, busque lo que necesite en una tabla o un rango con BUSCARX. [Más información](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)

- **Lea y responda sobre la marcha: **responda a los comentarios y las menciones directamente desde el correo electrónico sin abrir el libro.

### <a name="outlook"></a>Outlook

- **Obtener sugerencias de correo electrónico cuando busca un contacto:** cuando escriba el nombre de una persona en el cuadro de búsqueda, se incluirán los mensajes de correo electrónico más relevantes con las sugerencias de búsqueda. [Más información](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

- **Directiva de nomenclatura de grupos:** las directivas de nomenclatura de grupo permiten al administrador de TI normalizar y administrar los nombres de los grupos creados por usuarios de la organización. El administrador puede requerir que se añada un prefijo o sufijo concreto al nombre de un grupo cuando se crea y puede bloquear el uso de determinadas palabras. Esto ayuda a minimizar el uso de palabras inadecuadas en los nombres de grupo, y permite que el administrador de TI gestione la representación de los grupos en el directorio. La Directiva de nomenclatura también ayuda a las organizaciones que implementan sitios de grupo a organizarse en base al departamento.

- **Unirse a reuniones sin salir de la bandeja de entrada:** no es necesario cambiar al calendario para unirse a reuniones en línea. Con el Calendario de Outlook anclado en el panel de tareas pendientes, únase a una reunión con un solo clic.

- **Nueva experiencia para redes WiFi cautivas:** ¿alguna vez se ha unido a una red WiFi que requiere una página web para iniciar sesión? Outlook ahora lo detecta y le ayuda a estar conectado.

### <a name="powerpoint"></a>PowerPoint

- **Colaboración rápida en tiempo real en PowerPoint:** colaboración rápida en tiempo real en PowerPoint

- **Los vídeos en línea tienen un nuevo hogar:** guarde un vídeo en Microsoft Stream para que puedan verlo todas las personas de su organización. Inserte el vínculo del vídeo y disfrute de una presentación multimedia en una fracción del tamaño del archivo. [Más información](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. 

- **GIF en un instante:** una diapositiva, un marco. Cree fácilmente archivos GIF en bucle en PowerPoint. [Más información](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)

- **Mejores diagramas ** con mejores conectores y un proceso de conversión de entrada de lápiz más fluido, puede aplicar sus ideas con más confianza. [Más información](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **Actualización de las diapositivas durante la presentación:** actualice diapositivas editadas por otros autores durante la presentación.<br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)

### <a name="word"></a>Word

- **Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. 

- **Otros usuarios verán los cambios rápidamente**: las mejoras en la coautoría significan que los colaboradores podrán ver los cambios más rápido que nunca.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- **Abrir archivos de gran tamaño incrementalmente:** La capacidad de descargar, abrir e interactuar con presentaciones de PowerPoint de gran tamaño, incluso si algunas partes de la presentación (por ejemplo, una imagen o vídeo de gran tamaño) no se han terminado de descargar aún.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos

### <a name="excel"></a>Excel

- Application.Evaluate (VBA) no funcionaba para funciones definidas por el usuario en algunos casos.

- Se abordó un problema donde los enlaces externos no se actualizan cuando se cierra el libro de fuentes.


### <a name="onenote"></a>OneNote

- Se obtiene una mejora de la sincronización y la estabilidad del servicio al alterar temporalmente la frecuencia con la que se crean los historiales de las versiones de las páginas.


- Se obtiene una mejora de la sincronización y la estabilidad del servicio al deshabilitar temporalmente el desplazamiento de páginas a la papelera de reciclaje. A los usuarios que quieran eliminar una página se les mostrará un cuadro de diálogo en el que se le preguntará si quieren eliminar una página de forma permanente.


- Se obtiene una mejora de la sincronización y la estabilidad del servicio al reducir temporalmente el tamaño máximo de nuevos datos adjuntos insertados a 50 MB en OneNote 2016. Si los archivos superan este límite, los usuarios tendrán la opción de cargar el archivo a OneDrive e insertar un vínculo en OneNote.


- Se obtiene una mejora de la sincronización y la estabilidad del servicio al deshabilitar temporalmente la grabación de vídeo en la aplicación en OneNote 2016. La medida no afecta a los blocs de notas locales.


- Se obtiene una mejora de la sincronización y la estabilidad del servicio al ajustar temporalmente la frecuencia de sincronización en OneNote 2016.


- Informe a los usuarios mediante la barra de información sobre los ajustes temporales de Microsoft OneNote que le ayudarán a mejorar la sincronización y la disponibilidad del servicio durante el alto uso en todo el mundo.


### <a name="outlook"></a>Outlook

- Se abordó un problema que causó que los usuarios vieran que el proceso de Outlook permanecía en el administrador de tareas después de salir.


- Se ha corregido un problema que causaba que los usuarios experimentaran ocasionalmente un bloqueo al usar el botón de su ratón.


- Se ha corregido un problema que provocaba que los usuarios experimentaran bloqueos en aplicaciones MAPI de terceros.


- Se ha corregido un problema que provocaba que Outlook se bloqueara al abrir archivos .msg y .oft guardados localmente después de una actualización de Windows.


- Se ha corregido un problema que provocaba que Outlook se bloqueara en algunas compilaciones de Windows.


- Se ha corregido un problema que provocaba que el ancho del panel de carpetas cambiara inesperadamente.


### <a name="project"></a>Project

- Corregido un problema por el que el porcentaje completado de la tarea se cambiaba incorrectamente a un valor inferior al 100 % después de que se marcara como completada.


- Corregido un problema en el que el evento OnUndoOrRedo no se desencadena sin ejecutar primero el método OpenUndoTransaction.


- Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.


- Corregido un problema que hace que el evento ProjectBeforeTaskChange no detecte cuándo se ha desactivado o activado una tarea mediante el botón Desactivar.


- Corregido un problema que hace que el evento ProjectBeforeTaskChange no detecte cuándo se ha desactivado o activado una tarea mediante el botón Desactivar.


- Corregido un problema por el que Project podía bloquearse al guardar proyectos creados con versiones anteriores de Project.


- Se corrigió un problema por el que el usuario no podía especificar el trabajo previsto con fases temporales al activar la configuración para proteger el trabajo real.


- Cuando se editan los datos del Predecesor/Sucesor dentro de una vista de formulario, se activa un evento ProjectBeforeTaskChange adicional.


### <a name="word"></a>Word

- Corrige un problema que causaba que los usuarios experimentaran ocasionalmente un bloqueo al usar el botón "X" de su ratón.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Esta corrección resuelve un error que impide restringir el acceso y proteger los archivos con una contraseña de forma simultánea.

- Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

[//]: # (NO QUITAR FINAL)

> [!NOTE]
> Si necesita ayuda con algún problema de uso de Office, le recomendamos que publique la pregunta en el [foro de preguntas de Microsoft](https://answers.microsoft.com/) o [Tech Community](https://techcommunity.microsoft.com/), o bien puede ponerse en contacto con el [servicio de soporte técnico](https://support.microsoft.com/contactus).


[//]: # (NO MODIFICAR EL INICIO DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)
[//]: # (|Win32|MEC|Producción|Característica|16.0.12827.20538|version-2005-july-14|)
[//]: # (NO MODIFICAR EL FIN DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)