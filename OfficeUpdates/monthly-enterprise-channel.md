---
title: Notas de la versión para las versiones de canal de empresa mensual en 2020
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Proporciona a los profesionales de TI las notas de la versión para las versiones de canal mensual de empresa para Aplicaciones de Microsoft 365 en 2020
ms.openlocfilehash: 44a77260e0e674eccf53a76a0a451a3bfa2d7566
ms.sourcegitcommit: 244f8fded28adafd66397baee0418254db5c9de2
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 12/10/2020
ms.locfileid: "49623131"
---
# <a name="release-notes-for-monthly-enterprise-channel-releases-in-2020"></a>Notas de la versión para las versiones de canal de empresa mensual en 2020

Estas notas de la versión proporcionan información sobre las nuevas características y las actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones del Canal de empresa mensual en 2020 para Aplicaciones de Microsoft 365 para empresas, Aplicaciones de Microsoft 365 para negocios y las versiones de suscripción de las aplicaciones de escritorio de Project y Visio.

> [!IMPORTANT]
> Estamos realizando algunos cambios en los canales de actualización de las Aplicaciones de Microsoft 365, incluida la adición de un nuevo canal de actualización (canal empresarial mensual) y el cambio de los nombres de los canales de actualización existentes. [Lea este artículo](https://go.microsoft.com/fwlink/p/?linkid=2127441) para obtener más información.

[//]: # (NO ELIMINAR)



## <a name="version-2010-december-08"></a>Versión 2010: 08 de diciembre
*Versión 2010 (compilación 13328.20478)*

Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Obtenga datos de organización de Power BI mediante Tipos de datos:** los tipos de datos de Excel de Power BI se están publicando ahora para participantes de Office Insider en las organizaciones con Office 365 E5/A5 o Microsoft 365 E5/A5. Obtener la información que necesita y actualizarla fácilmente es fundamental para muchos de los flujos de trabajo diarios. Le proporcionamos acceso a la información de Power BI de su empresa u organización como un tipo de datos en Excel, lo que amplía su capacidad de incorporar a las hojas de cálculo información vinculada.

### <a name="outlook"></a>Outlook

- **Actualizaciones de la experiencia de usuario en Tareas:** Una actualización visual de los elementos de las tareas

- **Vínculos mejorados en el correo electrónico:** al incluir un vínculo a un archivo, la dirección URL se reemplaza por el nombre del archivo. Puede cambiar los permisos para que todos los destinatarios tengan acceso.

### <a name="powerpoint"></a>PowerPoint

- **Exportar GIF animado en un rango:** seleccione un intervalo de diapositivas cuando exporte a GIF animado

- **Crear GIF con fondos transparentes:** cuando se exporta a un GIF animado, una nueva opción permite que el fondo sea transparente.<br />Ver detalles en la [entrada de blog](https://insider.office.com/en-us/blog/export-animated-gifs-transparent-backgrounds)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Acceso

- Se ha corregido un problema que provocaba que, al utilizar DAO desde aplicaciones que no son de Office, la aplicación se cerrara de forma inesperada.


### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que Outlook creara una segunda firma vacía para las personas que tuvieran habilitada la configuración de la nube.


- Se ha corregido un problema que, de forma predeterminada, impedía que se activara la configuración de la nube para los usuarios.


- Se ha corregido un problema que impedía guardar los cambios que se realizaran a la firma de un usuario.


- Se ha corregido un problema que provocaba que los encabezados de mensajes en chino no se pudieran leer al responder o reenviar.


- Se ha corregido un problema que provocaba que los caracteres chinos se cambiaran a signos de interrogación al guardar como archivo OFT.


- Se ha agregado una clave de registro que permite a los clientes deshabilitar la inclusión de hora de archivo para los datos adjuntos en las operaciones de IDataObject (es decir, arrastrar y soltar, portapapeles).  HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.  REG_DWORD IncludeFileTimesInDataObject.  0 = se excluyen horas de archivo.  1 = (predeterminado) se incluyen horas de archivo.


- Se ha corregido un problema que provocaba que se interrumpiera el evento MailItem.BeforeAttachmentAdd.


- Se ha corregido un problema que provocaba que los asistentes originales de algunas reuniones reciban una cancelación cuando otro asistente reenviaba la reunión.


- Se ha corregido un problema que provocaba que los usuarios no pudieran conceder permisos de editor a los delegados.


### <a name="powerpoint"></a>PowerPoint

- Esta es una solución para un problema que provocaba que se mostrara la solicitud de guardar en bucle al cerrar el documento cuando había un complemento que escuchaba al evento PresentationBeforeClose y comprobaba la propiedad Presentation.Saved como parte del controlador de eventos.


- Corrección de un problema al usar IRM o documentos protegidos durante un error de combinación.


- Se ha corregido un problema relacionado con copiar o pegar de una ecuación de Word a PowerPoint.


### <a name="project"></a>Project

- Se ha corregido un problema que podía provocar que Project se cerrara de manera inesperada al abrir archivos en los que se especificaban los contornos de los recursos de una determinada manera.


- Se ha corregido un problema que provocaba que, al guardar un proyecto desde PWA en un archivo MPP local, ProjectBeforeTaskChangeEvent se desencadenara para datos no modificados por el usuario.


- Se ha corregido un problema que provocaba que NewVal en el evento ProjectBeforeTaskChange no tuviera el valor correcto si se cambiaba un retraso en una vista de tipo de formulario de tarea.


### <a name="visio"></a>Visio

- Se ha corregido un problema que provocaba que los usuarios pudieran crear líneas rectas con conectores en Visio para Office 365, tanto para las galerías personalizadas de símbolos de Visio como para las plantillas predefinidas.


### <a name="word"></a>Word

- Se ha corregido un problema relacionado con copiar o pegar de una ecuación de Word a PowerPoint.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema que provocaba que la prevención de pérdida de datos de Microsoft 365 Endpoint no pudiera clasificar los documentos de Office en disco.


- Cuando el usuario imprime cualquier documento o archivo en las impresoras de inyección de tinta de Office y la tinta de la impresora es poco visible, el mensaje "tóner bajo" o "sin tóner" se mostrará, aunque las impresoras de inyección de tinta no tengan tóners. Cambiar mensaje para mostrar "Tóner/Tinta baja" y "Sin tóner/tinta".


- Se ha corregido un problema que provocaba que se produjera un error al copiar o pegar texto de un comentario en Excel.


- Se ha corregido un problema que producía un error al intentar Guardar como en ciertos escenarios.


- Se ha corregido un problema que provocaba un error al intentar guardar archivos que habían pasado de estar sincronizados a solo en el servidor.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2009-december-08"></a>Versión 2009: 08 de diciembre
*Versión 2009 (compilación 13231.20620)*

Las actualizaciones de seguridad se muestran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

## <a name="version-2009-november-10"></a>Versión 2009:10 de noviembre
*Versión 2009 (compilación 13231.20514)*

Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Aplicar automáticamente o recomendar etiquetas de confidencialidad:** Office puede recomendar o aplicar automáticamente una etiqueta de confidencialidad basada en el contenido confidencial detectado.

### <a name="powerpoint"></a>PowerPoint

- **Aplicar automáticamente o recomendar etiquetas de confidencialidad:** Office puede recomendar o aplicar automáticamente una etiqueta de confidencialidad basada en el contenido confidencial detectado.

### <a name="word"></a>Word

- **Aplicar automáticamente o recomendar etiquetas de confidencialidad:** Office puede recomendar o aplicar automáticamente una etiqueta de confidencialidad basada en el contenido confidencial detectado.


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que los encabezados de mensajes en chino no se pudieran leer al responder o reenviar.


- Corregido un problema que causaba que los delegados sufrieran errores intermitentemente al abrir carpetas compartidas en otro buzón.


- Corregido un problema que causaba que se enviaran algunos mensajes de correo electrónico generados automáticamente con el cuerpo en blanco cuando la línea del asunto estaba también en blanco.


- Corregido un problema que causaba que algunos usuarios vieran Outlook de forma inesperada en un estado sin conexión.


- Corregido un problema que provocaba que la búsqueda no devolviera ningún resultado al buscar en los calendarios compartidos sin almacenamiento en caché.


- Se ha corregido un problema que provocaba que la aplicación finalizara de forma abrupta cuando el cliente seleccionaba un resultado de búsqueda.


- Se ha corregido un problema que provocaba que los usuarios no pudieran conceder permisos de editor a los delegados.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema que provocaba la coautoría lenta en archivos que contienen números grandes de determinados tipos de objetos de datos (E2o).


- Corregido un problema que deshabilita las protecciones IRM al abrir un archivo de PowerPoint en la Vista protegida.


- Se ha corregido un problema en el que el complemento de contenido de formularios no se reproducía después de la inserción hasta que el usuario hiciera clic en otra diapositiva para hacer que aparezca.


### <a name="project"></a>Project

- Se ha corregido un problema por el que si se ejecuta un código de evento y se intenta realizar cambios desde la vista del Formulario de tareas, es posible que el botón Aceptar no confirme los cambios.


- Se ha corregido un problema que podía hacer que Project se cerrara de manera inesperada al abrir archivos en los que se especificaban los contornos de los recursos de una determinada manera.


- Se ha corregido un problema que provocaba que, al guardar un proyecto desde PWA en un archivo MPP local, ProjectBeforeTaskChangeEvent se desencadenara para datos no modificados por el usuario.


### <a name="word"></a>Word

- Se ha corregido un problema con el cuadro de diálogo Galería de estilos.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Corregido un problema con el cuadro de diálogo de Comprimir imagen, que no retiene determinadas configuraciones de usuario.


- Se ha corregido un problema por el que la prevención de pérdida de datos de Microsoft 365 Endpoint no pudo clasificar documentos de Office en disco.


- Cuando el usuario imprime cualquier documento o archivo en las impresoras de inyección de tinta de Office y la tinta de la impresora es poco visible, el mensaje "tóner bajo" o "sin tóner" se mostrará, aunque las impresoras de inyección de tinta no tengan tóners. Cambiar mensaje para mostrar "tóner/Ink Low" & "no tóner/tinta".



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2008-november-10"></a>Versión 2008: 10 de julio
*La versión prevista es la versión 2008 (compilación 13127.20760).*

Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema por el que, al usar una macro para establecer la propiedad FormulaR1C1 para un rango, las referencias de celda eran incorrectas si una hoja de gráfico era la hoja activa.


- Se ha corregido un problema por el que Excel indicaba por error que se había quedado sin recursos al intentar calcular una o varias fórmulas.


- Se ha corregido un problema que aparecía cuando se configuraba el idioma de Office en español. Este problema provocaba que las listas de validación de datos puedan no mostrar todos los elementos de la lista.


- Se ha corregido un problema que podía producir un bloqueo al actualizar las tablas dinámicas de OLAP.


- Se ha corregido un problema por el que algunas funciones podían tener un resultado incorrecto después de cargar un libro.


- Se ha corregido un problema relacionado con las referencias de complemento de XLAM y los rangos con nombre que cerraba la aplicación de forma inesperada.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que los encabezados de mensajes en chino fueran ilegibles al responder o reenviar.


- Corregido un problema que causaba que se enviaran algunos mensajes de correo electrónico generados automáticamente con el cuerpo en blanco cuando la línea del asunto estaba también en blanco.


- Corregido un problema que causaba que los delegados sufrieran errores intermitentemente al abrir carpetas compartidas en otro buzón.


- Se ha corregido un problema que provocaba que las búsquedas en calendarios de Grupo no dieran resultados.


- Se ha corregido un problema que provocaba que la aplicación finalizara de forma abrupta cuando el cliente seleccionaba un resultado de búsqueda.


- Se ha corregido un problema por el que los usuarios ahora pueden deshabilitar IRM (Information Rights Management) para Outlook sin tener que deshabilitarlo para el resto de las aplicaciones de Office.


- Se ha corregido un problema que provocaba que los usuarios no pudieran conceder permisos de editor a los delegados.


- Se ha corregido un problema por el que las experiencias opcionales conectadas bloqueaban la carga de los complementos web.<br />Ver detalles en la [entrada de blog](https://developer.microsoft.com/en-us/office/blogs/outlook-add-ins-and-optional-connected-experiences/)


### <a name="powerpoint"></a>PowerPoint

- Esta es una solución para un problema por el que se muestra la solicitud de guardar en un bucle al cerrar el documento cuando hay un complemento que escucha al evento PresentationBeforeClose y comprueba la propiedad Presentation.Saved como parte del controlador de eventos.


- Se ha corregido un problema en el que el complemento de contenido de formularios no se reproducía después de la inserción hasta que el usuario hiciera clic en otra diapositiva para hacer que aparezca.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha atendido un problema para los clientes comerciales que usan el System Center Configuration Manager u otras herramientas de administración para Office Update mediante la prevención de pérdida de datos del punto de conexión de Microsoft 365.

- Corrección de un problema por el que no funcionaba la API de mensajería para los complementos de Office.



[//]: # (NO QUITAR EL CONTENIDO FINAL DE LOS DETALLES DE LOS ERRORES)

## <a name="version-2008-october-13"></a>Versión 2008: 13 de octubre
*Versión 2008 (compilación 13127.20638)*

Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **¿Tiene dudas? Pregúntele a Excel:** ahora las Ideas de Excel le permiten realizar preguntas sobre sus datos, no necesita gastar tiempo escribiendo fórmulas (solo disponible en inglés). [Más información](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- **Guardar en carpetas fijadas:** anclar las carpetas facilita el almacenamiento de archivos de Office.  Recibimos un comentario en el que se nos informa de que los usuarios desean tener más control sobre las carpetas disponibles al guardar un archivo nuevo. Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar. Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil. [Más información](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

- **Realice una conexión PDF:** Conectar, importar, actualizar los datos de un PDF. [Más información](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- **Guarde formas como imágenes:** con tan solo unos pocos clics, guarde una forma, icono u otro objeto como archivo de imagen para que pueda volver a usarlo en otro lugar. [Más información](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

### <a name="outlook"></a>Outlook

- **Crear sondeos en Outlook con Sondeo rápido:** cree sondeos, recopile votos y vea los resultados rápidamente en un solo correo electrónico [Más información](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)

- **Nueva tarjeta de perfil para Outlook:** Nueva tarjeta de perfil para Outlook en la que se muestra una Vista de organización mejorada y que coincide con el estilo de tarjeta de Outlook Web. [Más información](https://support.office.com/article/e80f931f-5fc4-4a59-ba6e-c1e35a85b501)

### <a name="powerpoint"></a>PowerPoint

- **Guardar en carpetas fijadas:** anclar las carpetas facilita el almacenamiento de archivos de Office.  Recibimos un comentario en el que se nos informa de que los usuarios desean tener más control sobre las carpetas disponibles al guardar un archivo nuevo. Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar. Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil. [Más información](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

### <a name="word"></a>Word

- **Guardar en carpetas fijadas:** anclar las carpetas facilita el almacenamiento de archivos de Office.  Recibimos un comentario en el que se nos informa de que los usuarios desean tener más control sobre las carpetas disponibles al guardar un archivo nuevo. Nos complace ofrecerles una nueva funcionalidad: anclar sus carpetas en el cuadro de diálogo Guardar. Esta nueva función hará que el almacenamiento de archivos de Word, Excel y PowerPoint resulte más fácil. [Más información](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Acceso

- Este problema fue resuelto: ahora puede usar el controlador ODBC fuera de las aplicaciones de Hacer clic y ejecutar de Office.


- Este cambio corrige un problema que podía provocar que Access se bloqueara al iniciar el cuadro de Zoom (Mayús + F2) para editar el texto.


- Se ha corregido el problema y ya no debería experimentar el bloqueo.


### <a name="excel"></a>Excel

- Se ha corregido un problema que podía producir una advertencia acerca de un libro dañado si contenía fórmulas que usan SI.ND().


- Se ha corregido un problema que provocaba que Excel se bloqueara al usar el Análisis rápido después de inmovilizar la fila superior de la hoja.


- Se corrigió un problema por el cual los usuarios no podían modificar un filtro de tabla dinámica porque estaba configurado en un valor que ya no estaba presente en una base de datos de Analysis Services.


- Se ha corregido un problema que provocaba que Excel se bloqueara en determinadas circunstancias al usar Copiar formato.


- Se ha corregido un error con las API de PivotDateFilter en el que las condiciones de filtro 'Antes' y 'Después' se revertían.


### <a name="outlook"></a>Outlook

- Corrige un problema que provocaba que los usuarios recibieran el siguiente error al responder a un correo o al redactar uno nuevo: "Algunos archivos de esta página web no están en la ubicación esperada. ¿Desea descargarlos de todos modos? Si está seguro de que la página web es una fuente de confianza, haga clic en Sí".


- Se ha corregido un problema que provocaba que el menú contextual del botón derecho no apareciera en los controles de búsqueda.


- Corrige un problema que provocaba que los usuarios vieran anomalías al usar la vista compacta.


- Esto corrige un problema que provocaba que los usuarios experimentaran bloqueos ocasionales al editar los destinatarios.


- Corrige un problema que impedía a algunos usuarios visualizar correctamente la página del Asistente para programación.


- Corrige un problema de rendimiento con la carga de archivos adjuntos.


- Se ha corregido un problema que provocaba que los usuarios experimentaran un error al eliminar 4 o más mensajes de correo electrónico de una cuenta POP con la opción "Descargar solo encabezados" seleccionada.


- Corrige un problema que provocaba que los usuarios vieran un error en la página de vínculos seguros en lugar del documento que intentaban abrir al abrir un archivo adjunto en la nube.


- Corrige un problema que provocaba que los usuarios experimentaran bloqueos ocasionales al interactuar con los datos adjuntos en la nube.


- Corrige un problema que provocaba que los usuarios no pudieran cerrar los calendarios compartidos haciendo clic en la "X" de la esquina.


- Corrige un problema que evitaba que los usuarios se conectaran a las carpetas públicas luego de agregar un buzón compartido.


- Se ha corregido un problema que provocaba un error al tratar de eliminar las reuniones del calendario de un administrador, cuando un delegado las rechazaba en determinadas circunstancias.


- Se corrigió un problema que impedía a algunos usuarios de la característica Mejoras del calendario compartido ver un calendario compartido recién agregado.


- Corrige un problema que causaba que la configuración "Activar las mejoras del calendario compartido" en ocasiones no se pudiera aplicar a los calendarios compartidos existentes.


- Corrige un problema que evitaba que los usuarios que intentaran crear una solicitud de reunión desde una cuenta secundaria añadida a su perfil vieran el campo De: en blanco en lugar de su dirección de correo electrónico.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema que provocaba el bloqueo en la aplicación de PowerPoint.


- Corrección de seguridad para solucionar un problema que deshabilita las protecciones IRM al abrir un archivo de PowerPoint en la vista protegida.


- Este cambio corrige un problema relacionado con la característica Exportar a GIF animado, en la que no se exporta al hacer clic en el botón Exportar.


### <a name="project"></a>Project

- Se ha corregido un problema en el que la fecha de finalización de Project no se actualiza para los proyectos conectados a la lista de tareas de SharePoint.


- Se ha corregido un problema debido al cual, si un recurso tenía más de una tabla de tasa de costo definida, el costo restante no siempre se calculaba correctamente.

### <a name="skype"></a>Skype

- Se cambió el tono de piel del emoticono de baile a un color neutro


### <a name="visio"></a>Visio

- Los usuarios han reportado el bloqueo de la Vista previa dinámica en la alineación del texto. Bloqueo al llegar a la parte superior en la bifurcación de repositorio de julio.


### <a name="word"></a>Word

- Se ha corregido un problema por el que se ejecuta la macro AutoOpen antes de AutoExec.


- Se ha corregido un problema con el cuadro de diálogo Galería de estilos.


- Se ha corregido un problema que podía provocar un bloqueo al iniciar Word.


- Se ha corregido un problema que provocaba que los estilos base no se actualizaran con el estilo Normal.


- Se ha corregido un problema por el que el usuario podría experimentar un error al abrir un documento.


- Se ha corregido un problema que provocaba que el usuario pudiera perder contenido al cambiar el tamaño de una forma.


- Corrige un problema que provocaba que los usuarios experimentaran un bloqueo al abrir algunos correos electrónicos muy grandes.


- Corrige un problema que provocaba que los usuarios experimentaran un bloqueo al responder o redactar un correo nuevo.


- Este cambio corrige un problema que provocaba que las aplicaciones de Office se quedaran atascadas en un estado de error de guardado silencioso después de una sesión de coautoría anterior.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Este cambio corrige un bloqueo al iniciar las aplicaciones de Office debido a un error al cargar d2d1.dll.


- Corrige el uso elevado de la CPU en modo inactivo con un GIF o un modelo 3D animado


- Cuando el usuario imprime cualquier documento o archivo en las impresoras de inyección de tinta de Office y la tinta de la impresora es poco visible, el mensaje "tóner bajo" o "sin tóner" se mostrará, aunque las impresoras de inyección de tinta no tengan toners Cambiar mensaje para mostrar "tóner/Ink Low" & "no tóner/tinta".



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2007-october-13"></a>Versión 2007: 13 de octubre
*Versión 2007 (compilación 13029.20708)*

Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un error con las API de PivotDateFilter en el que las condiciones de filtro 'Antes' y 'Después' se revertían.



[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO FINAL)

## <a name="version-2007-september-08"></a>Versión 2007: 08 de septiembre
*Versión 2007 (compilación 13029.20534)*

Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Notificación de incidentes para administradores de TI:** se notificará a los administradores globales de espacios empresariales de Microsoft 365 y a los administradores de aplicaciones de Office acerca de los incidentes de Outlook y Exchange de O365 que afectan a sus usuarios con una nueva notificación en el panel derecho en Outlook para Windows. [Más información](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- **Volver a abrir rápidamente los elementos de una sesión anterior:** hemos agregado una opción para volver a abrir rápidamente los elementos de una sesión anterior de Outlook. Si Outlook se bloquea o usted cierra la aplicación, ahora podrá reiniciar elementos rápidamente al reabrir Outlook. Esta característica está activada de forma predeterminada. Para desactivarla, vaya a Opciones > General > Opciones de inicio.

### <a name="word"></a>Word

- **Retener texto en vectores:** ahora puede conservar el texto en mapas, gráficos y otros vectores de SVG al convertir estos objetos en Excel, Word y PowerPoint.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- **Paneles con pestañas:** ahora puede cambiar entre varios paneles con la pestaña situada en la parte derecha de la aplicación. Esta interfaz de usuario solo será visible cuando haya dos o más paneles abiertos.<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/20/improved-pane-management/)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Acceso

- Esta corrección resuelve un problema por el que al intentar ejecutar determinadas consultas anteriormente se generaba el mensaje de error "La consulta es demasiado compleja".


### <a name="excel"></a>Excel

- Se ha corregido un problema por el que podía producirse un error o bloqueo al cargar un libro con varias hojas en la vista previa de salto de página.


- Se puede producir un error al intentar guardar un archivo que contiene una fórmula con la función LET().


### <a name="outlook"></a>Outlook

- Se ha abordado un problema que causaba problemas de formato en las alertas de notificación de incidentes.


- Se ha corregido un problema que provocaba que los usuarios de Outlook tuvieran problemas con la navegación en vistas compactas.


- Se corrigió un problema que provocaba que los usuarios se bloquearan en ocasiones al recuperar información personal.


- Se ha corregido un problema que provocaba que la página del Asistente para programación no se mostrara.


- Se ha corregido un problema que evitaba que los usuarios guardaran los datos adjuntos de OneDrive desde fuera de su inquilino en su equipo local al seleccionar la opción "Guardar" en el cuadro de diálogo de seguridad.


- Se ha corregido un problema que causaba que faltara la opción "Permitir reenvío" en las "Opciones de respuesta" de la reunión de calendario compartida cuando NO está marcada Descargar carpeta compartida.


- Se corrigió un problema que provocaba que Outlook no pudiese recuperar sugerencias de búsqueda.


- Se ha corregido un problema que provocaba que los usuarios de algunos juegos de caracteres viesen nombres de archivo que se mostraban de forma incorrecta al agregar un vínculo inteligente a un archivo de SharePoint.


- Se ha corregido un problema que provocaba que los usuarios de CLP experimenten un bloqueo al cambiar la dirección del remitente en una respuesta desde un contexto protegido a uno no protegido.

- Corrige un problema que provocaba que los usuarios experimentaran un bloqueo al responder a un correo o al redactar uno nuevo.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema de bloqueo con la aplicación de PowerPoint.


### <a name="project"></a>Project

- Se ha corregido un problema que impedía guardar desde Project un PDF o XPS en una biblioteca de documentos de SharePoint.


- Se ha corregido un problema por el que si pegaba una tarea que tenía varias dependencias, no todas las dependencias se copiaban correctamente.


- Se ha corregido un problema por el que la tarea seleccionada en el cuadro de diálogo de asignación de recursos no era la misma que la tarea seleccionada en la vista del panel de tareas.


- Se corrigió un problema por el que no se podía abrir un proyecto que estaba en mal estado.



### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema debido al cual los usuarios no podían visualizar el contenido o los elementos de la interfaz de usuario en determinadas condiciones, especialmente en la vista Moderador (o al salir de la misma) o al usar varios monitores.


- Se ha corregido un problema que provocaba que se mostrara un mensaje de tiempo de ejecución aunque se completara la transición al producto completo. La corrección para este problema era asegurarse de que el servicio computase correctamente los productos agregados. Se han filtrado los nuevos productos agregados (lo que garantiza que también se encuentren en la nueva configuración) y se han agregado al final de los ID de versión de producto existentes.


- Para un antiguo panel de uso compartido basado en servicio no Web, al cerrar el documento mientras el panel de uso compartido está abierto, se podría producir un bloqueo. Este problema ya está solucionado.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2006-september-08"></a>Versión 2006: 08 de septiembre
*Versión 2006 (compilación 13001.20648)*

Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

## <a name="version-2006-august-11"></a>Versión 2006: 11 de agosto
*Versión 2006 (compilación 13001.20520)*

Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos han pasado a ser más elegantes.

- **Filtrar y ordenar sin perturbar a otras personas:** ahora puede ordenar y filtrar un archivo de Excel mientras colabora con otras personas con la Vista de hoja. Esta nueva característica evita que sus acciones se vean afectadas por la ordenación y los filtros de otros usuarios mientras se trabaja en un documento en coautoría. [Más información](https://support.office.com/article/0eea3dc5-d7d1-44c5-a953-25ebfbd6c1a6)

### <a name="outlook"></a>Outlook

- **Protección de datos del grupo:** la etiqueta de confidencialidad que elija al crear un grupo se aplica al correo electrónico del grupo, a los documentos y a los sitios de equipo.

- **Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office para que sus documentos sean aún más llamativos.

- **Nueva opción para desactivar las sugerencias de @menciones al escribir correo en Outlook:**¿le resulta el selector de @menciones más molesto que útil? Ahora puede desactivarlo si lo prefiere.<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)

- **Mantenga la fidelidad de las imágenes al enviarlas como parte de un correo electrónico:** una nueva configuración de Outlook está disponible para limitar la compresión de imágenes al enviarlas como parte de contenido del correo electrónico.

### <a name="powerpoint"></a>PowerPoint

- **Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos han pasado a ser más elegantes.

- **Mejor rendimiento de vídeos de Stream en PowerPoint:** hemos realizado mejoras en el rendimiento de la reproducción de los vídeos de Microsoft Stream para reducir el tiempo de carga de vídeo y crear una visualización más suave. Use los vídeos corporativos de Microsoft Stream para crear presentaciones mejoradas.

### <a name="word"></a>Word

- **Cuente sus historias con GIF animados:** los GIF animados ahora son compatibles con el editor de Office: sus documentos han pasado a ser más elegantes.

- **Decirlo de otra forma:** si lo quiere decir de forma diferente, la reescritura le puede ayudar. La reescritura ofrece alternativas para afinar sus frases.<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/08/12/rewrite-in-word-say-it-another-way/)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Acceso

- Se ha corregido un problema que provocaba que la ejecución de consultas tardara en completarse aproximadamente el doble del tiempo esperado.

- Se ha resuelto un problema al insertar tablas SQL vinculadas que incluyan un campo de identidad (por ejemplo, autonumeración).


### <a name="excel"></a>Excel

- Se ha corregido un problema que provocaba que se quitara el XML de CustomUI para una ficha de cinta al guardar en SharePoint o OneDrive.

- Se corrigió un problema por el que podía producirse un error o bloqueo al cargar un libro con varias hojas en la vista previa de salto de página.

- Se corrigió un bloqueo que podría producirse al intentar crear una conexión de datos si había cerrado la sesión de su cuenta.

- Es posible que se haya producido una clasificación de documentos automática en los libros que se encontraban en modo de solo lectura.

### <a name="onenote"></a>OneNote

- Se mejora la detección del estado de la coautoría para reducir el uso de recursos.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema para copiar y pegar imágenes SVG.

- Se ha corregido un problema por el que la búsqueda de una característica en Sugerir una característica no devolvía resultados y no ofrecía al usuario ninguna opción para enviar una nueva característica.

- Se corrigió un problema por el que Ctrl + clic dejaba de funcionar al habilitar la configuración de la nube.

- Se ha corregido un problema que evitaba que los usuarios guardaran los datos adjuntos de OneDrive desde fuera de su inquilino en su equipo local al seleccionar la opción "Guardar" en el cuadro de diálogo de seguridad.

- Se corrigió un problema por el que los usuarios de Outlook veían continuamente un aviso para que ejecutaran la herramienta de Reparación de la bandeja de entrada.

- Se corrigió un problema por el que los usuarios de las mejoras del Calendario compartido veían errores en el calendario.

- Se corrigió un problema por el que la fecha de creación de datos adjuntos copiados en el sistema de archivos a través de la opción de arrastrar y soltar parecía como el 1 de enero de 4501.

### <a name="project"></a>Project

- Se ha corregido un problema por el que el evento ProjectBeforeTaskChange no se activaba al darse un cambio en la tarea de resumen del proyecto: ya sea en el campo de inicio o tarea del proyecto.

- Se ha corregido un problema por el que una tarea marcada como completada al 100 % se mostraba por error no completada al 100 %.

- Se corrigió un problema por el que los proyectos no se podían abrir en el cliente de escritorio de Project desde Project Web App si la dirección URL terminaba en .com.

### <a name="word"></a>Word

- Se ha corregido un problema para copiar y pegar imágenes SVG.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Hemos modificado la versión AppV51 para solucionar una regresión de la AppV51 anterior.

- Un problema de temporización podía provocar un bloqueo al cerrar archivos de Office.

- Se ha corregido un problema de bloqueo con el host de Office en Windows cuando se activa un complemento mientras el valor del registro TabProcGrowth era del tipo REG_SZ.


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2005-august-11"></a>Versión 2005: 11 de agosto
*Versión 2005 (compilación 12827.20656)*

Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

## <a name="version-2005-july-14"></a>Versión 2005: 14 de julio
*Versión 2005 (compilación 12827.20538)*

Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Mejores resultados, en un instante:** actualizamos la experiencia de búsqueda para que sea más inteligente, rápida y fiable que nunca. [Más información](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)




[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

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

- Se ha corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange" al actualizar sus reglas en Outlook.

- Se corrigió un problema por el que la fecha de creación de datos adjuntos copiados en el sistema de archivos a través de la opción de arrastrar y soltar parecía como el 1 de enero de 4501.

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

- Se ha corregido un problema que podría haber provocado un bloqueo al arrastrar contenido desde la aplicación.

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

- **Escriba una fórmula que devuelva varios valores:** Escriba rápidamente una fórmula que devuelva múltiples valores y se derramarán automáticamente en las celdas vecinas. [Más información](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)

- **Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. 

- **Seis potentes funciones:** Seis potentes funciones: Hemos agregado seis nuevas funciones para mejorar las hojas de cálculo: FILTRAR, ORDENAR, ORDENARPOR, UNICOS, SECUENCIA y MATRIZALEAT. [Más información](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- **Busque a la izquierda, busque a la derecha... BUSCARX ya está aquí**: fila por fila, busque lo que necesite en una tabla o un rango con BUSCARX. [Más información](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)

- **Lea y responda sobre la marcha:** responda a los comentarios y las menciones directamente desde el correo electrónico sin abrir el libro.

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

- **Mejores diagramas** con mejores conectores y un proceso de conversión de entrada de lápiz más fluido, puede aplicar sus ideas con más confianza. [Más información](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

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


- Corregido un problema por el que Project puede bloquearse al guardar proyectos creados con versiones anteriores de Project.


- Se corrigió un problema por el que el usuario no podía especificar el trabajo previsto con fases temporales al activar la configuración para proteger el trabajo real.


- Cuando se editan los datos del Predecesor/Sucesor dentro de una vista de formulario, se activa un evento ProjectBeforeTaskChange adicional.


### <a name="word"></a>Word

- Corrige un problema que causaba que los usuarios experimentaran ocasionalmente un bloqueo al usar el botón "X" de su ratón.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Esta corrección resuelve un error que impide restringir el acceso y proteger los archivos con una contraseña de forma simultánea.

- Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

[//]: # (NO QUITAR FINAL)

> [!NOTE]
> Si necesita ayuda con algún problema de uso de Office, le recomendamos que publique la pregunta en el [foro de preguntas de Microsoft](https://answers.microsoft.com/) o [Tech Community](https://techcommunity.microsoft.com/), o bien puede ponerse en contacto con el [servicio de soporte técnico](https://support.microsoft.com/contactus).


[//]: # (NO MODIFICAR EL INICIO DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)
[//]: # (|Win32|MEC|Producción|Característica|16.0.13328.20478|versión-08-diciembre-2010|)
[//]: # (|Win32|MEC|Producción|Característica|16.0.13231.20514|versión-10-noviembre-2009|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13127.20638|versión-13-octubre-2008|)
[//]: # (| Win32 | MEC | Producción | Característica | 16.0.13029.20534 | versión-2007-septiembre-08 |)
[//]: # (|Win32|MEC|Producción|Característica|16.0.13001.20520|versión-2006-11-agosto|)
[//]: # (|Win32|MEC|Producción|Característica|16.0.12827.20538|version-2005-july-14|)
[//]: # (NO MODIFICAR EL FIN DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)
