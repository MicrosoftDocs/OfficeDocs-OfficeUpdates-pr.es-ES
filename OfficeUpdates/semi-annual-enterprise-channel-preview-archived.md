---
title: Notas de la versión archivadas para las versiones del canal semestral (dirigido) en 2019
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Proporciona a los profesionales de TI las notas de la versión para las versiones del canal semestral (dirigido) de Office 365 ProPlus en 2019
ms.openlocfilehash: 72e2402dff445b9ec4b03c7241f93ee85b16bee2
ms.sourcegitcommit: 596cdb3423140df0324a952157fbc39ebedc12b9
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 05/07/2021
ms.locfileid: "52278127"
---
# <a name="archived-release-notes-for-semi-annual-enterprise-channel-preview"></a>Notas de la versión archivadas para el canal semestral para empresas (versión preliminar)

En estas notas de la versión, se proporciona información sobre características nuevas y actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones del canal semestral para empresas (versión preliminar) de Office 365, Visio Pro para Office 365, el cliente de escritorio de Project Online y Office 365 Empresa.

> [!NOTE]
> - A menudo publicamos características (y, a veces, incluso correcciones) para el canal semestral para empresas (versión preliminar) durante un período de tiempo. Si no ve algo que se describe a continuación de inmediato, lo verá pronto. [Más información](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)


## <a name="version-2008-december-08"></a>Versión 2008: 08 de diciembre
*Versión 2008 (Compilación 13127.20910)*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Se ha corregido un problema de error al intentar usar el generador de DSN de ODBC


### <a name="excel"></a>Excel

- Se ha corregido un problema que provocaba que las tablas dinámicas no se pudieran editar y los libros no se pudieran guardar si se exportaban desde el plan de Project.


- Se ha corregido un problema que provocaba que, en algunos casos, aparecieran varias barras de mensajes al abrir un archivo en modo de solo lectura.


- Se ha corregido un problema que provocaba que los subtotales de esquema pudieran dejar de funcionar cuando había muchos valores de encabezado de columna duplicados.


- Se ha corregido un problema que provocaba que Excel dejara de funcionar cuando había una actualización del objeto de directiva de grupo (por ejemplo, mediante la actualización de la directiva de grupo remota) durante el recálculo multiproceso.


- Se ha corregido un problema que provocaba que Excel dejara de funcionar cuando los usuarios utilizaban la función subtotal en más de 255 columnas.


- Interletraje de texto mejorado en PowerPoint cuando se copia contenido de Excel y se pega en PowerPoint con la opción Insertar.


- Se ha corregido un problema que impedía cambiar entre la vista previa de la tabla y el editor de consultas en PowerPivot.


- Se ha corregido un problema que provocaba que el usuario no pudiera abrir el archivo atomsvc (UTF8+BOM) directamente desde SharePoint.


- Se ha corregido un problema con Power Pivot. Ahora reconoce correctamente el delimitador de tabulaciones.


### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que el campo "Para:" estuviera vacío al enviar un informe de estado en una tarea.


- Se ha corregido un problema que provocaba que se interrumpiera el evento MailItem.BeforeAttachmentAdd.


- Se ha corregido un problema que provocaba que algunos usuarios experimentaran el cierre inesperado de la aplicación Outlook al enviar correo desde aplicaciones diferentes de Outlook.


- Se ha corregido un problema que provocaba que los usuarios experimentaran un rendimiento degradado al mover varios elementos de correo entre carpetas en el modo en línea.


- Se ha agregado una clave de registro que permite a los clientes deshabilitar la inclusión de hora de archivo para los datos adjuntos en las operaciones de IDataObject (es decir, arrastrar y soltar, portapapeles).  HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = horas de archivo están excluidas  1 = (determinado) horas de archivo están incluidas


- Se ha corregido un problema que provocaba que las imágenes en línea desaparecieran al responder a un mensaje con una etiqueta de protección de Azure Information Protection.


- Se ha corregido un problema que provocaba que el nombre de usuario se mostrara como un número de teléfono al enviar un correo de voz protegido de Azure, lo que provocaba que los usuarios de escritorio de Outlook no puedan abrir correos de voz de usuarios externos.


- Se ha corregido un problema que provocaba que, al configurar OME, se agregaban datos adjuntos extraños en el elemento de correo que obligaban a Outlook a cifrar el mensaje aunque la opción DecryptAttachmentsForEncryptOnly estuviera configurada en el lado del servicio.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema que provocaba que el gráfico de Excel vinculado cambiara incorrectamente a la hoja de Excel cuando el usuario cambiaba la ruta de origen a la carpeta de OneDrive local.


- Se ha corregido un problema que provocaba que la característica "Bienvenido de nuevo. Retomar el trabajo donde lo dejó en la oficina" no funcionara en PowerPoint.


### <a name="visio"></a>Visio

- Se ha corregido un problema que provocaba que los usuarios pudieran crear líneas rectas con conectores en Visio para Office 365, tanto para las galerías personalizadas de símbolos de Visio como para las plantillas predefinidas.


### <a name="word"></a>Word

- Se corrigió un problema que provocaba que los vínculos largos no se ajustaran al guardar un documento en formato HTML.


- Se ha corregido un problema que provocaba que, si se respondía a un comentario primario que tenía extensiones desconocidas en una lista de extensiones, la respuesta obtuviera esas mismas extensiones.


- Se ha corregido un problema con Outlook al establecer un mensaje en No reenviar


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Soluciona un problema que impedía que los usuarios importaran listas de SPO cuando se deshabilitaba ADAL.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2008-november-10"></a>Versión 2008: 10 de julio
*La versión prevista es la versión 2008 (compilación 13127.20760).*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos

### <a name="excel"></a>Excel

- Se ha corregido un problema por el que algunas funciones podían tener un resultado incorrecto después de cargar un libro.


- Se ha corregido un problema relacionado con las referencias de complemento de XLAM y los rangos con nombre que cerraba la aplicación de forma inesperada.


- Se ha corregido un problema por el que, al usar una macro para establecer la propiedad FormulaR1C1 para un rango, las referencias de celda eran incorrectas si una hoja de gráfico era la hoja activa.


- Se ha corregido un problema por el que Excel indicaba por error que se había quedado sin recursos al intentar calcular una o varias fórmulas.


- Se ha corregido un problema que aparecía cuando se configuraba el idioma de Office en español. Este problema provocaba que las listas de validación de datos puedan no mostrar todos los elementos de la lista.


- Se ha corregido un problema que podía producir un bloqueo al actualizar las tablas dinámicas de OLAP.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema por el que los usuarios ahora pueden deshabilitar IRM (Information Rights Management) para Outlook sin tener que deshabilitarlo para el resto de las aplicaciones de Office.


- Se ha corregido un problema que provocaba que los usuarios no pudieran conceder permisos de editor a los delegados.


- Se ha corregido un problema que provocaba que la aplicación finalizara de forma abrupta cuando el cliente seleccionaba un resultado de búsqueda.


- Se ha corregido un problema que provocaba que las búsquedas en calendarios de Grupo no dieran resultados.


- Corregido un problema que causaba que los delegados sufrieran errores intermitentemente al abrir carpetas compartidas en otro buzón.


- Corregido un problema que causaba que se enviaran algunos mensajes de correo electrónico generados automáticamente con el cuerpo en blanco cuando la línea del asunto estaba también en blanco.


- Se ha corregido un problema que provocaba que los encabezados de mensajes en chino fueran ilegibles al responder o reenviar.

- Se ha corregido un problema por el que las experiencias opcionales conectadas bloqueaban la carga de los complementos web.  <br />Ver detalles en la [entrada de blog](https://developer.microsoft.com/es-ES/office/blogs/outlook-add-ins-and-optional-connected-experiences/)


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema en el que el complemento de contenido de formularios no se reproducía después de la inserción hasta que el usuario hiciera clic en otra diapositiva para hacer que aparezca.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha atendido un problema para los clientes comerciales que usan el System Center Configuration Manager u otras herramientas de administración para Office Update mediante la prevención de pérdida de datos del punto de conexión de Microsoft 365.

- Corrección de un problema por el que no funcionaba la API de mensajería para los complementos de Office.



[//]: # (NO QUITAR EL CONTENIDO FINAL DE LOS DETALLES DE LOS ERRORES)

## <a name="version-2008-october-13"></a>Versión 2008: 13 de octubre
*Versión 2008 (compilación 13127.20638)*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un error con las API de PivotDateFilter en el que las condiciones de filtro 'Antes' y 'Después' se revertían.


- Se corrigió un problema por el cual los usuarios no podían modificar un filtro de tabla dinámica porque estaba configurado en un valor que ya no estaba presente en una base de datos de Analysis Services.


- Se ha corregido un problema que provocaba que Excel se bloqueara al usar el Análisis rápido después de inmovilizar la fila superior de la hoja.


- Se ha corregido un problema que podía producir una advertencia acerca de un libro dañado si contenía fórmulas que usan SI.ND.


### <a name="outlook"></a>Outlook

- Corrige un problema que provocaba que los usuarios no pudieran cerrar los calendarios compartidos haciendo clic en la "X" de la esquina.


- Corrige un problema que causaba que la configuración "Activar las mejoras del calendario compartido" en ocasiones no se pudiera aplicar a los calendarios compartidos existentes.


- Corrige un problema que provocaba que los usuarios vieran un error en la página de vínculos seguros en lugar del documento que intentaban abrir al abrir un archivo adjunto en la nube.


- Corrige un problema de rendimiento con la carga de archivos adjuntos.


### <a name="powerpoint"></a>PowerPoint

- Este cambio corrige un problema relacionado con la característica Exportar a GIF animado, en la que no se exporta al hacer clic en el botón Exportar.


- Corrección de seguridad para solucionar un problema que deshabilita las protecciones IRM al abrir un archivo de PowerPoint en la Vista protegida.

- Se ha corregido un problema en la configuración de la Acción que provocaba un bloqueo en la aplicación PowerPoint.

### <a name="visio"></a>Visio

- Se ha corregido un problema que provocaba que la Vista previa en directo se bloqueara en la alineación del texto.


### <a name="word"></a>Word

- Corrige un problema que provocaba que los usuarios experimentaran un bloqueo al abrir algunos correos electrónicos muy grandes.


- Se ha corregido un problema por el que el usuario podría experimentar un error al abrir un documento.


- Se ha corregido un problema que podía provocar un bloqueo al iniciar Word.


- Se ha corregido un problema con el cuadro de diálogo Galería de estilos.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Cuando el usuario imprime cualquier documento o archivo en las impresoras de inyección de tinta de Office y la tinta de la impresora es poco visible, el mensaje "tóner bajo" o "sin tóner" se mostrará, aunque las impresoras de inyección de tinta no tengan tóners. Cambiar mensaje para mostrar "tóner/tinta bajos" & "no tóner/tinta".


- Corrige el uso elevado de la CPU en modo inactivo con un GIF o un modelo 3D animado


- Este cambio corrige un bloqueo al iniciar las aplicaciones de Office debido a un error al cargar d2d1.dll.



[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO FINAL)

## <a name="version-2008-september-08"></a>Versión 2008: 08 de septiembre
*Versión 2008 (Compilación 13127.20408)*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="access"></a>Access

- **Aumente su productividad con el Diseñador de consultas, la vista SQL y la ventana Relaciones:** haga clic con el botón derecho en una tabla para abrirla, diseñarla, cambiar su tamaño y ocultarla. Buscar y reemplazar texto en la vista SQL. Seleccione múltiples tablas en la ventana Relaciones.

- **Agregue tablas con menos clics:** utilizar el panel de tareas agregar tablas, que permanece abierto mientras trabaja, para agregar tablas a relaciones y consultas. [Más información](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a>Excel

- **Gráficos de mapa mejorados:** hemos integrado los gráficos de mapa con los tipos de datos geográficos de Excel, para que revelen información de todo tipo sobre las ubicaciones que desee. [Más información](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- **Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Crear tablas dinámicas de conjuntos de datos en Power BI desde Excel:** puede crear tablas dinámicas en Excel conectadas a los conjuntos de datos almacenados en Power BI con tan solo unos clics. Así, podrá obtener lo mejor de las tablas dinámicas y de Power BI. Calcule, resuma y analice sus datos con tablas dinámicas desde sus conjuntos de datos seguros de Power BI. [Más información](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)

- **Sus funciones favoritas de Excel se han vuelto más rápidas:** las funciones SUMAR.SI.CONJUNTO, CONTAR.SI.CONJUNTO, PROMEDIO.SI.CONJUNTO, MAX.SI.CONJUNTO y MIN.SI.CONJUNTO son más rápidas que nunca. Llegue al final más rápidamente. Pruebe ahora una.

- **Mejoras de RealTimeData (RTD):** En la versión Microsoft Office 365 2002 canal mensual y posterior, la función RealTimeData (RTD) de Excel es mucho más rápida que calcular datos en la hoja de cálculo en Excel 2010. Hemos evitado atascos en su memoria subyacente y en las estructuras de datos, así como permitido el uso seguro de subprocesos para que se pueda calcular en todos los subprocesos disponibles de Recálculo multiproceso (MTR).

### <a name="outlook"></a>Outlook

- **Las actualizaciones del calendario compartido son más rápidas:** Outlook puede actualizar los calendarios compartidos en Office 365 con la API de REST. Active la vista previa para obtener actualizaciones más rápidas y confiables en los calendarios compartidos.

- **Mejores resultados, en un instante:** actualizamos la experiencia de búsqueda para que sea más inteligente, rápida y fiable que nunca. [Más información](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Arrastre el correo electrónico a un grupo de tu propiedad:** Mueva y copie mensajes y conversaciones arrastrándolos desde su bandeja de entrada. Los mensajes que arrastres serán compartidos con todos los miembros del grupo.<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)

- **El calendario se transforma:** vea las actualizaciones visuales que hacen que el calendario sea más fácil de examinar. [Más información](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)

- **Unirse a reuniones sin salir de la bandeja de entrada:** no es necesario cambiar al calendario para unirse a reuniones en línea. Con el Calendario de Outlook anclado en el panel de tareas pendientes, únase a una reunión con un solo clic. [Más información](https://support.office.com/article/d8baa9d5-0645-41b8-9f36-b498a6c36064 )

- **Nueva experiencia para redes WiFi cautivas:** ¿alguna vez se ha unido a una red WiFi que requiere una página web para iniciar sesión? Outlook ahora lo detecta y le ayuda a estar conectado.<br />Ver detalles en la [entrada de blog](https://insider.office.com/es-ES/blog/outlook-on-public-wi-fi-networks-just-got-easier)

- **Obtener sugerencias de correo electrónico cuando busca un contacto:** cuando escriba el nombre de una persona en el cuadro de búsqueda, se incluirán los mensajes de correo electrónico más relevantes con las sugerencias de búsqueda. [Más información](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint"></a>PowerPoint

- **Llame su atención con \@menciones:** use @menciones en los comentarios para que los compañeros de trabajo sepan cuándo necesita su opinión. [Más información](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **Gráficos de mapa mejorados:** hemos integrado los gráficos de mapa con los tipos de datos geográficos de Excel, para que revelen información de todo tipo sobre las ubicaciones que desee. [Más información](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- **GIF en un instante:** una diapositiva, un marco. Cree fácilmente archivos GIF en bucle en PowerPoint. [Más información](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)

- **Mejores diagramas** con mejores conectores y un proceso de conversión de entrada de lápiz más fluido, puede aplicar sus ideas con más confianza. [Más información](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Comentarios:** la nueva experiencia de comentarios en PowerPoint permite descubrir y agregar comentarios a los documentos de forma rápida y sencilla. Modernice sus flujos de trabajo de colaboración con nuevas características como anclaje de comentarios, resuelva, tareas, notificaciones de menciones mejoradas y mucho más. [Más información](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

- **Sincronice los cambios mientras realiza la presentación:** sincronice los cambios cuando se hagan aunque la presentación esté en el modo de presentación con diapositivas. [Más información](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)

- **Vínculo a la diapositiva:** Pídale a un compañero que participe en la presentación de diapositivas y llévelo directamente a la diapositiva con la que necesita ayuda. [Más información](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)

- **Mejor rendimiento de vídeos de Stream en PowerPoint:** hemos realizado mejoras en el rendimiento de la reproducción de los vídeos de Microsoft Stream para reducir el tiempo de carga de vídeo y crear una visualización más suave. Use los vídeos corporativos de Microsoft Stream para crear presentaciones mejoradas.


### <a name="word"></a>Word

- **Gráficos de mapa mejorados:** hemos integrado los gráficos de mapa con los tipos de datos geográficos de Excel, para que revelen información de todo tipo sobre las ubicaciones que desee. [Más información](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- **Selección de lazo de la entrada de lápiz:** la herramienta Lazo en la pestaña Dibujar le ayuda a seleccionar objetos dibujados a mano. Seleccione trazos individuales o palabras completas. [Más información](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **Elija el color perfecto:** use códigos de colores hexadecimales para elegir exactamente el color que desea para la fuente, el resaltado de texto, etc.<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Confirmación de acción en lectores de pantalla:** la confirmación de la acción es un requisito de accesibilidad importante. Con la introducción de una nueva API de notificación de Windows, ahora podemos alertar a los usuarios de lectores de pantalla sobre el éxito de sus acciones. Las opciones de cortar, copiar, pegar, negrita, cursiva, subrayado, deshacer, rehacer, corrección automática y uso automático de mayúsculas ahora se anuncian a los usuarios del narrador en Word Win32. Para habilitar esta característica, active el narrador presionando Windows + Ctrl + Entrar.<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- **Etiquetas de confidencialidad:** ahora puede aplicar una etiqueta de confidencialidad que su organización ha configurado para solicitarle permisos personalizados.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Acceso

- Se ha resuelto un problema al insertar tablas SQL vinculadas que incluyan un campo de identidad (por ejemplo, autonumeración).

- Se ha corregido un problema que provocaba que la ejecución de consultas tardara en completarse aproximadamente el doble del tiempo esperado.

- Se ha corregido un problema para poder llamar al tipo de datos Fecha/Hora ampliado en el código sin tener que bloquear la aplicación.

- Se ha corregido un problema de forma que ahora puede volver a la versión de Access más actualizada y usar DAO/VBA para administrar y editar un tipo de datos decimal.

- Esta corrección resuelve un problema por el que al intentar ejecutar determinadas consultas anteriormente se generaba el mensaje de error "La consulta es demasiado compleja".

- Access ha corregido este problema actual, pero se está investigando nuestra interfaz adicional para asegurarnos de que este problema no se conserva. El equipo le informará en actualizaciones futuras. Agradecemos su paciencia.

- Este problema fue resuelto: ahora puede usar el controlador ODBC fuera de las aplicaciones de Hacer clic y ejecutar de Office.

### <a name="excel"></a>Excel

- Es posible que se haya producido una clasificación de documentos automática en los libros que se encontraban en modo de solo lectura.

- Se ha corregido un bloqueo que podría producirse al intentar crear una conexión de datos si había cerrado la sesión de su cuenta.

- Se ha corregido un problema por el que Excel se bloqueaba al intentar insertar tablas dinámicas en una hoja de gráfico.

- Se puede producir un error al intentar guardar un archivo que contiene una fórmula con la función LET().

- Se ha corregido un problema que provocaba que Excel se bloqueara en determinadas circunstancias al usar Copiar formato.

- Se ha corregido un problema que provocaba que se quitara el XML de CustomUI para una ficha de cinta al guardar en SharePoint o OneDrive.

- Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.

- Se solucionó un problema por el cual, en algunos casos, al hacer clic en un hipervínculo a un lugar dentro del mismo libro de trabajo, el libro de trabajo se ocultaba.

- Se ha corregido un problema que hacía que el vínculo externo dejara de funcionar después de que se volviera a abrir un archivo si su ruta de acceso era demasiado larga.

- Application.Evaluate (VBA) no funcionaba para funciones definidas por el usuario en algunos casos.

- En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.

- Se ha corregido un problema que hacía que Excel se bloqueara en ciertos casos después de copiar una hoja que contenía una tabla dinámica.

- Esto soluciona un problema en el que las conexiones creadas por el proveedor de datos SQL en versiones anteriores de Office establecerían las propiedades de la tabla interna de manera diferente a Office 365. Esto provocó que el menú desplegable Vista previa de tabla / Editor de consultas se deshabilitara para los archivos con conexiones creadas en versiones anteriores de Office cuando se abrieron con Office 365.

- Corregido un problema por el que los enlaces externos no se actualizaban si el libro de origen estaba cerrado.

- Se corrigió un problema por el cual las entradas manuscritas podrían hacer que Excel dejara de responder.

### <a name="onenote"></a>OneNote

- Se informa a los usuarios mediante la barra de información sobre los ajustes temporales de Microsoft OneNote que les ayudarán a mejorar la sincronización y la disponibilidad del servicio durante un uso mundial elevado.

- Mejora de la sincronización y la estabilidad del servicio al ajustar temporalmente la frecuencia de sincronización en OneNote 2016.

- Se mejoró la detección del estado de la coautoría para reducir el uso de recursos.

- Se obtiene una mejora de la sincronización y la estabilidad del servicio al reducir temporalmente el tamaño máximo de nuevos datos adjuntos insertados a 50 MB en OneNote 2016. Si los archivos superan este límite, los usuarios tendrán la opción de cargar el archivo a OneDrive e insertar un vínculo en OneNote.

- Se obtiene una mejora de la sincronización y la estabilidad del servicio al deshabilitar temporalmente la grabación de vídeo en la aplicación en OneNote 2016. La medida no afecta a los blocs de notas locales.

- Se obtiene una mejora de la sincronización y la estabilidad del servicio al alterar temporalmente la frecuencia con la que se crean los historiales de las versiones de las páginas.

- Se obtiene una mejora de la sincronización y la estabilidad del servicio al deshabilitar temporalmente el desplazamiento de páginas a la papelera de reciclaje. A los usuarios que quieran eliminar una página se les mostrará un cuadro de diálogo en el que se le preguntará si quieren eliminar una página de forma permanente.

### <a name="outlook"></a>Outlook

- Corrige un problema que evitaba que los usuarios que intentaran crear una solicitud de reunión desde una cuenta secundaria añadida a su perfil vieran el campo De: en blanco en lugar de su dirección de correo electrónico.

- Corrige un problema que evitaba que los usuarios se conectaran a las carpetas públicas luego de agregar un buzón compartido.

- Se ha corregido un problema que provocaba un error al tratar de eliminar las reuniones del calendario de un administrador, cuando un delegado las rechazaba en determinadas circunstancias.

- Se corrigió un problema que impedía a algunos usuarios de la característica Mejoras del calendario compartido ver un calendario compartido recién agregado.

- Corrige un problema que provocaba que los usuarios experimentaran bloqueos ocasionales al interactuar con los datos adjuntos en la nube.

- Se ha corregido un problema que provocaba que los usuarios de CLP experimenten un bloqueo al cambiar la dirección del remitente en una respuesta desde un contexto protegido a uno no protegido.

- Se ha corregido un problema por el que Outlook no pudo habilitar consejos de directiva para la Protección de pérdida de datos para usuarios que pagaron por el servicio con planes M365 Business Plus.

- Se ha corregido un problema con el evento de auditoría CLP para la etiqueta de responder o reenviar.

- Se ha corregido un problema que provocaba que el ancho del panel de carpetas cambiara inesperadamente.

- Se ha corregido un problema que causaba que la fecha de creación de datos adjuntos copiados en el sistema de archivos a través de la opción de arrastrar y soltar apareciera como el 1 de enero de 4501.

- Se ha corregido un problema que provocaba que los usuarios de algunos juegos de caracteres viesen nombres de archivo que se mostraban de forma incorrecta al agregar un vínculo inteligente a un archivo de SharePoint.

- Se ha corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange", al actualizar sus reglas en Outlook.

- Se corrigió un problema que provocaba que Outlook no pudiese recuperar sugerencias de búsqueda.

- Se ha corregido un problema que provocaba que los usuarios de las mejoras del Calendario compartido vieran errores en el calendario.

- Se ha corregido un problema que causaba que los usuarios experimentasen bloqueos y errores intermitentes en algunos escenarios.

- Se ha corregido un problema que provocaba que los usuarios experimentaran un error al eliminar 4 o más mensajes de correo electrónico de una cuenta POP con la opción "Descargar solo encabezados" seleccionada.

- Se ha corregido un problema que causaba que faltara la opción "Permitir reenvío" en las "Opciones de respuesta" de la reunión de calendario compartida cuando NO está marcada Descargar carpeta compartida.

- Se ha corregido un problema que causaba que los delegados recibieran un error al editar una cita de calendario existente en el calendario de un administrador.

- Se ha corregido un problema que provocaba que los usuarios experimentaran bloqueos en aplicaciones MAPI de terceros.

- Se ha corregido un problema que provocaba que Outlook se bloqueara al abrir archivos .msg y .oft guardados localmente después de una actualización de Windows.

- Se ha corregido un problema que provocaba que Outlook se bloqueara en algunas compilaciones de Windows.

- Se ha corregido un problema que provocaba que los usuarios de las versiones de Windows 10 Server vieran la advertencia "Estado del antivirus: no válido". Esta versión de Windows admite la detección del antivirus, pero no se encontró ninguno” a pesar de tener un antivirus correctamente instalado.

- Se ha corregido un problema que provocaba que Outlook se bloqueara al abrir archivos .msg y .oft guardados localmente después de una actualización de Windows.

- Se ha corregido un problema que provocaba que Outlook se bloqueara en algunas compilaciones de Windows.

- Se ha corregido un problema que provocaba que los usuarios de Outlook vieran continuamente un aviso para que ejecutaran la herramienta de reparación de la bandeja de entrada.

- Abordó un problema que causó que los usuarios experimentaran ocasionalmente un choque al usar el botón "X" de su ratón.

- Se ha corregido un problema que evitaba que los usuarios guardaran los datos adjuntos de OneDrive desde fuera de su inquilino en su equipo local al seleccionar la opción "Guardar" en el cuadro de diálogo de seguridad.

- Se ha corregido un problema que provocaba que la página del Asistente para programación no se mostrara.

- Se ha corregido un problema que impedía a algunos usuarios visualizar correctamente la página del Asistente para programación.

- Se corrigió un problema que provocaba que los usuarios se bloquearan en ocasiones al recuperar información personal.

- Esto corrige un problema que provocaba que los usuarios experimentaran bloqueos ocasionales al editar los destinatarios.

- Corrige un problema que provocaba que los usuarios vieran anomalías al usar la vista compacta.

- Se ha corregido un problema que provocaba que los usuarios de Outlook tuvieran problemas con la navegación en vistas compactas.

- Se ha corregido un problema que provocaba que el menú contextual del botón derecho no apareciera en los controles de búsqueda.

- Corrige un problema que provocaba que los usuarios recibieran el siguiente error al responder a un correo o al redactar uno nuevo: "Algunos archivos de esta página web no están en la ubicación esperada. ¿Desea descargarlos de todos modos? Si está seguro de que la página web es una fuente de confianza, haga clic en Sí".

- Corrige un problema que provocaba que los usuarios experimentaran un error al salir de Outlook.

- Se ha corregido un problema que provocaba que la búsqueda de una característica en Sugerir una característica no devolviera resultados y no ofrecía al usuario ninguna opción para enviar una nueva idea de característica.

- Se ha abordado un problema que causaba problemas de formato en las alertas de notificación de incidentes.

- Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al enviar comentarios desde una Notificación de administrador.

- Se ha corregido un problema para copiar y pegar imágenes SVG.

- Esto corrige un problema que provocaba que los usuarios experimentaran bloqueos ocasionales al editar los destinatarios.

- Se ha corregido un problema para copiar y pegar imágenes SVG.


### <a name="powerpoint"></a>PowerPoint

- Se corrigió un bloqueo cuando los usuarios tenían comentarios tanto modernos como heredados en un archivo, lo que activaba una actualización de los comentarios.

- Se ha corregido un problema de bloqueo con la aplicación de PowerPoint.

- Se ha corregido un problema de bloqueo en el panel de sugerencias.

### <a name="project"></a>Project

- Se solucionó un problema cuando los datos del Predecesor/Sucesor se editaban dentro de una vista de formulario, se activaba un evento ProjectBeforeTaskChange adicional.

- Corregido un problema por el que Project puede bloquearse al guardar proyectos creados con versiones anteriores de Project.

- Se corrigió un problema por el que el usuario no podía especificar el trabajo previsto con fases temporales al activar la configuración para proteger el trabajo real.

- Corregido un problema por el que el porcentaje completado de la tarea se cambiaba incorrectamente a un valor inferior al 100 % después de que se marcara como completada. 

- Corregido un problema en el que el evento OnUndoOrRedo no se desencadena sin ejecutar primero el método OpenUndoTransaction.

- Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.

- Corregido un problema que hace que el evento ProjectBeforeTaskChange no detecte cuándo se ha desactivado o activado una tarea mediante el botón Desactivar.

- Se ha corregido un problema que hace que si está usando Project conectado a Project Web App y el separador decimal es una coma, el método TaskDependencies Add producirá un error al intentar agregar retardo a una dependencia.

- Se ha corregido un problema por el que los proyectos no se podían abrir en el cliente de escritorio de Project desde Project Web App si la dirección URL terminaba en .com.

- Se ha corregido un problema por el que si pegaba una tarea que tenía varias dependencias, no todas las dependencias se copiaban correctamente.

- Se ha corregido un problema que impedía guardar desde Project un PDF o XPS en una biblioteca de documentos de SharePoint.

- Se ha corregido un problema por el que una tarea marcada como completada al 100 % se mostraba por error no completada al 100 %.

- Se ha corregido un problema por el que el evento ProjectBeforeTaskChange no se activaba al darse un cambio en la tarea de resumen del proyecto: ya sea en el campo de inicio o tarea del proyecto.

- Se ha corregido un problema debido al cual, si un recurso tenía más de una tabla de tasa de costo definida, el costo restante no siempre se calculaba correctamente.

- Se ha corregido un problema en el que la fecha de finalización de Project no se actualiza para los proyectos conectados a la lista de tareas de SharePoint.

- Se ha corregido un problema por el que la tarea seleccionada en el cuadro de diálogo de asignación de recursos no era la misma que la tarea seleccionada en la vista del panel de tareas.

- Se corrigió un problema por el que no se podía abrir un proyecto que estaba en mal estado.

### <a name="skype"></a>Skype

- Cuando se asignaba a un usuario una directiva que lo llevaba a Teams solo, aún se podía usar el complemento para Outlook de Skype Empresarial para programar reuniones. Tras esta actualización, ya no se podrán programar reuniones de Skype Empresarial después de que el cliente lea la directiva en la que se indica que el usuario participa en Teams solo y entra en la reunión como Unirse solo. Además, el complemento de Outlook para Skype Empresarial no se activará durante el inicio si ve que el cliente de Skype Empresarial se encuentra en modo de Unirse solo.

- Se cambió el tono de piel del emoticono de baile a un color neutro

### <a name="word"></a>Word

- Se ha resuelto un problema al abrir documentos de Word desde la entrega de documentos personalizados (aspx) cuando la dirección URL contenía un componente de consulta.

- Este cambio corrige un problema que provocaba que las aplicaciones de Office se queden atascadas en un estado de error de guardado silencioso después de una sesión de coautoría anterior.

- Corrige un problema que provocaba que los usuarios experimentaran un bloqueo al responder o redactar un correo nuevo.

- Abordó un problema que causó que los usuarios experimentaran ocasionalmente un choque al usar el botón "X" de su ratón.

- Se ha corregido un problema para copiar y pegar imágenes SVG.

- Se ha corregido un problema por el cual el usuario podría perder contenido al cambiar el tamaño de una forma.

- Se ha corregido un problema por el cual los estilos base no se actualizaban con el estilo Normal.

- Se ha corregido un problema por el que se ejecuta la macro AutoOpen antes de AutoExec.

- Se ha corregido un problema para copiar y pegar imágenes SVG.

- Se ha corregido un problema que podría haber provocado un bloqueo al arrastrar contenido desde la aplicación.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Para un antiguo panel de uso compartido basado en servicio no Web, al cerrar el documento mientras el panel de uso compartido está abierto, se podría producir un bloqueo. Este problema ya está solucionado.

- Se corrigió un problema de temporización que podía provocar un bloqueo al cerrar archivos de Office.

- Hemos resuelto el problema de la tasa de error de ValidateInstall estableciendo la validación de instalación del Complemento de Bing como verdadera de forma predeterminada y considerando el éxito de devolución de MSI como una instalación con éxito.

- Hemos modificado la versión AppV51 para solucionar una regresión de la AppV51 anterior.

- Se ha corregido un problema de hacer clic y ejecutar que generaba errores de actualización al intentar crear un vínculo físico para vínculos simbólicos.

- Se ha corregido un problema que provocaba que se mostrara un mensaje de tiempo de ejecución aunque se completara la transición al producto completo. La corrección para este problema era asegurarse de que el servicio computase correctamente los productos agregados. Se han filtrado los nuevos productos agregados (lo que garantiza que también se encuentren en la nueva configuración) y se han agregado al final de los ID de versión de producto existentes.

- Se ha corregido un problema debido al cual los usuarios no podían visualizar el contenido o los elementos de la interfaz de usuario en determinadas condiciones, especialmente en la vista Moderador (o al salir de la misma) o al usar varios monitores.

- Este cambio resuelve posibles errores al cargar y reproducir contenido animado como GIF o modelos 3D.

- Este cambio resuelve un problema con el cuadro de diálogo de Comprimir imagen, que no retiene determinadas configuraciones de usuario.

- Esta actualización corrige un problema en Microsoft Office en el que los proyectos de Visual Basic para aplicaciones con referencias que se espera encontrar buscando las ubicaciones especificadas en la variable de entorno PATH podían no encontrarse correctamente en tiempo de ejecución, lo que provoca errores en tiempo de ejecución de VBA.

- Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.

- Esta corrección resuelve un error que impide restringir el acceso y proteger los archivos con una contraseña de forma simultánea.

- Se ha corregido un problema de bloqueo con el host de Office en Windows cuando se activa un complemento mientras el valor del registro TabProcGrowth era del tipo REG_SZ.

- El host de Office se bloqueaba en Windows, cuando se activaba un complemento si la clave del registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth estaba establecida en cero. Este cambio solucionaría el problema.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-august-11"></a>Versión 2002: 11 de agosto
*Versión 2002 (compilación 12527.20988)*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se corrigió un problema por el que no se podía cambiar a la edición de archivos que se han abierto como "recomendado solo lectura".

### <a name="onenote"></a>OneNote

- Se quitaron las llamadas de identidad redundantes para reducir el uso de recursos

- Se mejoró la detección del estado de la coautoría para reducir el uso de recursos.

- Se mejoró la función de detección de errores y la calidad de la experiencia de sincronización.

### <a name="outlook"></a>Outlook

- Se corrigió un problema que causaba un problema de rendimiento importante al iniciar Outlook en algunos espacios empresariales.

### <a name="skype"></a>Skype

- Se corrigió un problema por el que se podía producir un error al compartir la pantalla en un cliente de Skype Empresarial de 32 bits después de ejecutarlo durante varios días.

### <a name="office-suite"></a>Conjunto de programas de Office

- Se corrigió un problema que se producía al desactivar el autoguardado a través de la directiva de grupo: era posible que algunos documentos no mostraran el contenido más reciente de servidor al abrirse hasta que el usuario hiciera clic en "Actualizaciones disponibles".



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-july-14"></a>Versión 2002: 14 de julio
*Versión 2002 (compilación 12527.20880)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Acelere la carga de archivos que están disponibles en la carpeta de OneDrive local.

- Se ha corregido un problema que provocaba que se quitara el XML de CustomUI para una ficha de cinta al guardar en SharePoint o OneDrive.

- Se ha corregido un problema que producía el siguiente mensaje de error: "No se puede cerrar el libro de trabajo debido a que otro libro hace referencia al mismo". El mensaje aparecía si los complementos se cargaban en orden alfabético en lugar de en un orden especificado por el usuario.

- Se ha corregido un problema que haría que un libro se ocultara al hacer clic en un hipervínculo a un lugar dentro de un libro ya abierto.

- Se ha corregido un problema por el que algunos vínculos de un gráfico copiado y pegado usaban direcciones de unidad asignadas, en lugar de direcciones universales.

- Se ha mejorado el rendimiento al eliminar columnas con celdas combinadas.

- Se ha corregido un problema por el que los nombres de las impresoras podrían repetirse en la lista de impresoras en el cuadro de diálogo Imprimir.

- Se ha corregido un problema por el que las hojas de cálculo que contenían varias fórmulas con nombres definidos tardaban más en guardarse.


### <a name="outlook"></a>Outlook

- Se ha corregido un problema por el que la ventana del Editor de métodos de entrada (IME) se superponía al texto subyacente escrito mediante el IME cuando se usaban varios monitores con resoluciones diferentes.

- Se ha corregido un problema que causaba que las citas o reuniones periódicas se mostraran en un momento incorrecto al tratar de cambiar la definición de una zona horaria.

- Se ha corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange", al actualizar sus reglas en Outlook.

- Se ha corregido un problema que causaba que faltara la opción "Permitir reenvío" en las "Opciones de respuesta" de la reunión de calendario compartida cuando NO está marcada Descargar carpeta compartida.

- Se ha corregido un problema que provocaba que las categorías desapareciesen en ocasiones de los mensajes de correo electrónico.

- Se ha corregido un problema que provocaba que los delegados viesen distintas jerarquías de carpetas en diferentes equipos para los buzones compartidos.

- Se ha corregido un problema que causaba que los delegados recibieran un error al editar una cita de calendario existente en el calendario de un administrador.

- Se ha corregido un problema que provocaba que el cuerpo de un mensaje NDR cambiara de Unicode a ASCII después de editar el asunto.

- Se ha corregido un problema que causaba que los usuarios experimentaran un bloqueo cuando dos complementos agregan un botón al mismo grupo de la cinta de opciones.

- Se ha corregido un problema que provocaba que los usuarios no pudieran dirigir mensajes de correo electrónico a una lista de distribución personal.

- Se ha corregido un problema que provocaba que los vínculos no se agregaran a los correos electrónicos con el permiso predeterminado incorrecto de espacio empresarial cuando el permiso predeterminado de espacio empresarial se configura como "cualquiera".

- Se ha corregido un problema que evitaba que los usuarios guardaran los datos adjuntos de OneDrive desde fuera de su inquilino en su equipo local al seleccionar la opción "Guardar" en el cuadro de diálogo de seguridad.

### <a name="word"></a>Word

- Se ha corregido un problema de coautoría si se habilita la Directiva FileBlick\Word2007Files.

- Se ha corregido un problema en el que Word QuickPart no funciona al agregar un campo de búsqueda cuyo nombre se ha cambiado.

### <a name="office-suite"></a>Conjunto de programas de Office

- Se ha corregido un problema que podía hacer que los usuarios experimentaran un uso excesivo de la red y de la CPU durante la coautoría en archivos de PowerPoint grandes.

- Hemos modificado la versión AppV51 para solucionar una regresión de la AppV51 anterior.

- Se ha corregido un problema de bloqueo con el host de Office en Windows cuando se activa un complemento mientras el valor del registro TabProcGrowth era del tipo REG_SZ.


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-june-09"></a>Versión 2002: 09 de junio
*Versión 2002 (compilación 12527.20720)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema que hacía que el vínculo externo dejara de funcionar después de que se volviera a abrir el archivo si su ruta de acceso era demasiado larga.

- Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.

- Se ha corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.

- Podría producirse un bloqueo al intentar mostrar los cambios en una nueva hoja de un libro con el modo "libro compartido" heredado.

- Insertar una columna en una lista filtrada llevaba más tiempo de lo esperado.

- Se ha corregido un problema por el que un símbolo @ que inicia una fórmula se considera un operador de intersección implícita.

### <a name="outlook"></a>Outlook

- Permite unirse a una reunión de Teams directamente a través del cliente nativo de Teams.

- Se ha corregido un problema por el que Outlook no pudo habilitar consejos de directiva para la Protección de pérdida de datos para usuarios que pagaron por el servicio con planes M365 Business Plus.

- Se ha corregido un problema que provocaba que los usuarios con la configuración de emulación de explorador incorrecta no pudieran completar el mensaje de autenticación de Gmail.

- Se ha corregido un problema que provocaba que los usuarios de Outlook en sistemas operativos de servidor vieran el error: "Estado del antivirus: no válido. Esta versión de Windows admite la detección del antivirus, pero no se encontró ninguno" a pesar de tener el antivirus correctamente configurado.

### <a name="word"></a>Word

- Se ha corregido un problema por el que la alineación de las palabras de un documento se descomponía al intentar editar después de imprimir con la impresión rápida.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha resuelto este problema mediante la actualización de los nombres de canal en el backstage con los nuevos nombres de canal en la bifurcación de enero de 2020.

- Se ha corregido este problema y en adelante, si un dispositivo se administra mediante directiva, no llamará a la API de audiencia de DMS.

- Se ha resuelto el problema en el que había una eliminación incompleta al agregar y quitar aplicaciones en una sola transacción.

- El host de Office se bloqueaba en Windows, cuando se activaba un complemento si la clave del registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth estaba establecida en cero. Este cambio solucionaría el problema.


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-may-12"></a>Versión 2002: 12 de mayo
*Versión 2002 (compilación 12527.20612)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos

### <a name="excel"></a>Excel

- La apertura de un libro de trabajo con referencias a muchos otros libros de trabajo, especialmente con ventanas ocultas, era más lento de lo esperado.

- La apertura de archivos CSV tardaba más de lo esperado en algunas circunstancias.

- Excel se bloqueaba en determinadas circunstancias al cambiar entre libros con diferentes niveles de zoom.

- Se ha corregido un problema con VBA por el que escribir valores en un rango era más lento de lo esperado.

- En ocasiones, los datos copiados de una columna filtrada por color no se pegaban correctamente.

- Se ha corregido un problema que hacía que Excel se bloqueara en ciertos casos después de copiar una hoja que contenía una tabla dinámica.

- En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.

- Se ha corregido un problema por el que la propiedad "Value Crosses At" en el eje del gráfico cambiaba inesperadamente al guardar y volver a abrir un archivo.

- El uso de un Range.Value y Range.Value2 (VBA) hacía que las fórmulas se escribieran como matrices dinámicas.

### <a name="onenote"></a>OneNote

- Localiza la notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.

- Muestra una notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.

- Sincronización y estabilidad de servicio mejoradas al reducir temporalmente el número y la frecuencia de sincronización de las páginas del historial de versiones en OneNote 2016.

- Mejora de la sincronización y la estabilidad del servicio al deshabilitar temporalmente la papelera de reciclaje en OneNote 2016. Cuando un usuario intenta eliminar datos que normalmente se enviarían a la papelera de reciclaje, se le preguntará si prefiere conservarlos o eliminarlos forma permanente.

- Mejora de la sincronización y la estabilidad del servicio al ajustar temporalmente la frecuencia de sincronización en OneNote 2016.

- Mejora de la sincronización y la estabilidad del servicio al diferir temporalmente la descarga de archivos e imágenes incrustados en los blocs de notas en línea hasta que el usuario navegue a la página en OneNote 2016.

- Se obtiene una mejora de la sincronización y la estabilidad del servicio al deshabilitar temporalmente la grabación de vídeo en la aplicación en OneNote 2016. La medida no afecta a los blocs de notas locales.

- Mejora de la sincronización y la estabilidad del servicio al reducir temporalmente el tamaño máximo de nuevos datos adjuntos insertados a 50 MB en OneNote 2016. Si los archivos superan este límite, los usuarios tendrán la opción de cargar el archivo a OneDrive e insertar un vínculo en OneNote.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que el ancho del panel de carpetas cambiara inesperadamente.

- Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al intentar abrir archivos .msg y .oft después de una actualización de Windows.

- Se ha corregido un problema que hacía que los usuarios vieran truncado el cuerpo del mensaje al reenviar mensajes HTML grandes.

- Esta actualización corrige un problema en el que con Microsoft Outlook no muestra la etiqueta de confidencialidad actual al ver o redactar mensajes.

- Se ha corregido un problema que provocaba que los usuarios no pudieran dirigir mensajes de correo electrónico a una lista de distribución personal.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema para transmitir mensajes correctos para los usuarios que abren una copia de un archivo con comentarios mejorados.

### <a name="word"></a>Word

- Se ha corregido el problema por el que Access y Publisher podrían no iniciarse correctamente en función de los idiomas que se hubieran instalado.

- Se ha corregido un problema con la característica Comparar de los documentos protegidos para la edición.

- Se ha corregido un problema al combinar 2 documentos en uno.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Esta es una corrección para que la aplicación de Project no bloquee la red cuando el archivo se almacena en caché en el cliente.

- Hemos resuelto el problema por el que una operación interna producía una excepción en caso de error en lugar de registrarlo y continuar. Los usuarios afectados ya no serán bloqueados para recibir actualizaciones.

- Este cambio garantiza que el contorno Esbozado funcione correctamente en la cinta de opciones.

- Se ha corregido un problema al abrir archivos de ubicaciones locales con algunas configuraciones de proxy específicas.

- Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.

- Esta actualización corrige un problema en Microsoft Office en el que los proyectos de Visual Basic para aplicaciones con referencias que se espera encontrar buscando las ubicaciones especificadas en la variable de entorno PATH podían no encontrarse correctamente en tiempo de ejecución, lo que provoca errores en tiempo de ejecución de VBA.

- Esta actualización corrige un problema en Microsoft Word por el que el texto que supera los 255 caracteres insertados durante la aplicación de una etiqueta de confidencialidad no se pudiese identificar y quitar posteriormente cambiando o quitando la etiqueta si la directiva de etiqueta aplicó un encabezado, un pie de página o una marca de agua.

- Se ha corregido un problema que elimina bloqueos durante las sesiones de entrega de Office y se ha mejorado la fiabilidad de la experiencia del usuario.  

- Este error actualiza el extremo de la URL del servicio de configuración mejorada (ECS). Llamar a este punto de conexión más reciente tiene una tasa de éxito superior para capturar desde ECS.

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2002-april-14"></a>Versión 2002: 14 de abril
*Versión 2002 (compilación 12527.20442)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)


### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Escriba una fórmula que devuelva varios valores:** Escriba rápidamente una fórmula que devuelva múltiples valores y se derramarán automáticamente en las celdas vecinas. [Más información](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- **Seis potentes funciones:** Seis potentes funciones: Hemos agregado seis nuevas funciones para mejorar las hojas de cálculo: FILTRAR, ORDENAR, ORDENARPOR, UNICOS, SECUENCIA y MATRIZALEAT.  [Más información](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- **Busque a la izquierda, busque a la derecha... BUSCARX ya está aquí**: fila por fila, busque lo que necesite en una tabla o un rango con BUSCARX.  
  [Más información](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Excel se bloqueaba en ciertos casos cuando se volvía a abrir un libro incrustado en Word o PowerPoint.

- Cuando guarda como un archivo CSV, Excel podía combinar todas las columnas en una sola columna en algunos casos.

- Usar Range.ClearContents en un rango de una hoja protegida podía tardar más de lo esperado.

- Corregido un problema con la escala de texto en los controles de formulario cuando se mostraba en la Vista previa de impresión.

- Las macros de VBA que interactúan con la cinta de opciones se pueden ejecutar con ScreenUpdating establecido en True inesperadamente.

- Corregido un problema por el que los enlaces externos no se actualizaban al rellenar (rellenad hacia abajo, rellenar en otros, etc.) si el libro de origen estaba cerrado.

- El uso de Application.Evaluate de VBA no funcionaba para funciones definidas por el usuario en algunos casos.

- Corregido un problema de rendimiento al crear gráficos a partir de plantillas.


### <a name="outlook"></a>Outlook

- Corregido un problema que hacía que el encabezado de grupo se expandiera de forma inesperada en algunos escenarios.

- Corregido un problema que provocaba que los usuarios experimentaran un bloqueo al seleccionar determinados resultados de búsqueda.

- Corregido un problema que causaba que los usuarios experimentaran ocasionalmente un bloqueo al usar el botón X de su ratón.

- Corregido un problema que hacía que el botón Guardar en la nube faltara en las Herramientas de datos adjuntos.

### <a name="powerpoint"></a>PowerPoint

- Se ha mejorado un escenario de copiar y pegar: al copiar la forma en una diapositiva de PowerPoint y pegarla en otra diapositiva en bucle puede producir errores.


### <a name="project"></a>Proyecto

- Corregido un problema por el que Project puede bloquearse al guardar proyectos creados con versiones anteriores de Project.

- Corregido un problema que hace que el evento ProjectBeforeTaskChange no detecte cuándo se ha desactivado o activado una tarea mediante el botón Desactivar.

### <a name="word"></a>Word

- Corregido un problema que causaba que los usuarios experimentaran ocasionalmente un bloqueo al usar el botón X de su ratón.

- Corregido un problema con el ajuste de texto en una tabla.

- Corregido un problema donde al insertar líneas horizontales no eran más cortas ni centradas.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-march-10"></a>Versión 2002: 10 de marzo
*Versión 2002 (compilación 12527.20278)*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="access"></a>Access

- **Buscar tablas vinculadas rápidamente:** nuestro nuevo cuadro de búsqueda hace que buscar tablas vinculadas sea mucho más sencillo. [Más información](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a>Excel

- **Llame su atención con \@menciones:** use @menciones en los comentarios para que los compañeros de trabajo sepan cuándo necesita su opinión. [Más información](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **Encuentre lo que busca:** Realice búsquedas de comandos, personas, archivos, fotos, artículos en la web y más. [Más información](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- **Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su libro. [Más información](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.

- **Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. 

- **Resalte lo que queda por hacer**: seleccione Resolver para contraer los comentarios y hacer que resalten los elementos abiertos.

- **Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar. [Más información](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **Convertir los archivos para mejorar la accesibilidad**: actualice los archivos al formato moderno para que sean más accesibles para todos los demás.

- **Complemento del visualizador de datos:** Crear rápidamente diagramas de flujo de Visio desde Excel. [Más información](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- **Lea y responda sobre la marcha:** responda a los comentarios y las menciones directamente desde el correo electrónico, sin abrir el libro.

- **Obtenga estadísticas en el libro:** Estadísticas del libro da información general sobre el contenido de un libro, para ayudarle a descubrir más fácilmente su contenido.

- **Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos. Encuéntrelos en Insertar > Iconos. [Más información](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a>Outlook

- **Conecte su red de LinkedIn con Outlook:** Conecte de forma segura su cuenta de LinkedIn con su cuenta de Microsoft para ver la información de los perfiles de LinkedIn directamente en las tarjetas personales. [Más información](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- **Todas las opciones de cifrado en un solo lugar:** vaya a Opciones > Cifrar para elegir cómo proteger su mensaje de correo. [Más información](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)

- **Insertar el menú de vínculos en Outlook inserta un vínculo con el permiso definido por el administrador de inquilinos:** un vínculo desde Insertar vínculo utilizado recientemente en Outlook insertaba un vínculo que solo funcionaba para los usuarios que ya tenían permisos. A menudo esto causaba un intercambio continuo de mensajes de correo electrónico entre los usuarios que pedían acceso a un documento. Hemos actualizado esta experiencia para que ahora el vínculo se inserte con el permiso predeterminado establecido por el administrador de inquilinos. Para MSIT se trata de "la organización puede editar", por lo que todos los usuarios internos que reciban un vínculo compartido de esta manera podrán acceder a él.

- **Busque incluso con errores ortográficos o tipográficos:** Outlook encontrará lo que busca, aunque no coincida con la forma exacta en que lo escribió.

- **Ahora es más fácil detectar correos de suplantación de identidad:** los mensajes de correo no deseado y de suplantación de identidad tienen un aspecto diferente para que pueda identificarlos y eliminarlos fácilmente en la bandeja de entrada.

- **Protección avanzada frente a ataques**: con la Protección contra amenazas avanzada de Office 365, estará protegido frente a ataques mediante hipervínculos en asuntos de correos electrónicos, mensajes adjuntos, mensajes firmados, rutas de red, etc.

- **Deja que lo dibuje:** garabatee sobre las imágenes o agregue un Lienzo de dibujo para enviar sus pensamientos con la entrada de lápiz. [Más información](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- **Ver mensajes relevantes en los resultados de búsqueda:** Outlook analiza los términos de búsqueda y muestra los mensajes de correo electrónico más relevantes en la parte superior de los resultados de búsqueda. También verá todos los resultados ordenados por fecha en la sección de Resultados principales. [Más información](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- **Obtenga sugerencias de ubicaciones:** Empiece a escribir en Ubicación cuando programe citas y reuniones, Outlook le sugerirá salas, direcciones y otros lugares recientes. [Más información](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- **Encajar más mensajes en la pantalla:** seleccione Ver > Usar espaciado más estrecho para ajustar el espaciado entre mensajes. [Más información](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- **Ver los mensajes bajo otra luz:** use el botón sol/luna para cambiar entre fondos claros y oscuros en el panel de lectura. [Más información](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- **Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos. Encuéntrelos en Insertar > Iconos. [Más información](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a>PowerPoint

- **Colaboración rápida en tiempo real en PowerPoint:** colaboración rápida en tiempo real en PowerPoint

- **Nuevas herramientas de revisión:** no se preocupe de las palabras. Ahora en PowerPoint se ofrecen sugerencias de gramática y escritura. [Más información](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- **Transcripción y subtítulos en directo:** las palabras del moderador se muestran automáticamente en la pantalla como subtítulos o se traducen en el idioma que prefiera. [Más información](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- **Usted calcula y nosotros le damos formato:** hemos convertido las expresiones matemáticas escritas a mano en caracteres estándar. Simplemente elija Entrada de lápiz a matemáticas y seleccione las notas escritas a mano para empezar. [Más información](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **Encuentre lo que busca:** use el cuadro de búsqueda para buscar texto, comandos, ayuda y mucho más. [Más información](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- **Encuentre los títulos de diapositivas que faltan y escríbalos**: los títulos de diapositivas añaden fuerza a su discurso y permiten que las diapositivas sean accesibles para los usuarios de todas las capacidades. El comprobador de accesibilidad le muestra dónde faltan títulos para que pueda agregarlos en el momento. [Más información](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- **Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su presentación. [Más información](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.

- **Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. 

- **Guarde una ilustración como SVG:** guarde un gráfico, una forma o una ilustración como un gráfico vectorial escalable, que se puede cambiar de tamaño sin perder calidad de imagen. [Más información](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- **Impresión de números de diapositiva en documentos:** los números de diapositiva se incluyen automáticamente en los documentos. Ahora es usted quien decide si los deja o los quita. [Más información](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- **Repetición de entrada de lápiz:** cuando haya entradas de lápiz en sus diapositivas, aplique una animación de reproducción para reproducir el dibujo real de la entrada de lápiz durante la presentación con diapositivas. [Más información](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- **Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar.

- **Optimizar la presentación para todos:** el comprobador de accesibilidad le ayuda a organizar los objetos de las diapositivas pensando en los lectores de pantalla.

- **Convertir los archivos para mejorar la accesibilidad**: actualice los archivos al formato moderno para que sean más accesibles para todos los usuarios.

- **Una experiencia de vídeo más segura:** las mejoras de seguridad hacen que la experiencia de vídeo en línea sea más segura.

- **¿Para que reinventar lo que puede reutilizar?:** ahorre tiempo usando de nuevo las diapositivas que haya creado o que otros usuarios han compartido con usted. [Más información](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- **Transforme la entrada de lápiz en formas, texto o matemáticas en PowerPoint para Office 365:** convierta la entrada de lápiz en forma libre a formas, textos o expresiones matemáticas de Office en un par de trazos. [Más información](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **Entrada de tinta para magníficas diapositivas:** convierta el texto de tinta en formas estándar y texto y obtenga ideas de diseño inteligente del Diseñador de PowerPoint. [Más información](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- **Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos. Encuéntrelos en Insertar > Iconos. [Más información](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a>Visio

- **Vuelva a la escena del crimen:** use las nuevas plantillas Evidencia, Interior y Exterior en la plantilla Investigación de Escenas de Delitos para recrear con detalle escenarios de delitos.

- **Cree diagramas de Visio elegantes en Excel:** cree un diagrama de flujo o un organigrama con solo escribir datos en una hoja de cálculo. [Más información](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **El Editor para currículum vítae incorpora el Asistente para currículum vítae de LinkedIn:** el Editor para currículum vítae ofrece una selección de comprobaciones gramaticales y de estilo especialmente adaptadas a los currículums, para que el texto sea más preciso y profesional.

- **Se ha corregido un problema relacionado con los documentos causados por la combinación de objetos 3D:** corrige un problema de daños en un documento producido por la combinación de objetos 3D.

- **Encuentre lo que busca:** use el cuadro de búsqueda para buscar texto, comandos, ayuda y mucho más. [Más información](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- **Colaborando a todo color:** los comentarios y los cambios están codificados por color según la persona que contribuya, por lo que es fácil distinguir entre sus colaboradores.

- **Editar documentos habilitados para macros de forma conjunta:** guarde sus archivos .docm en OneDrive para la Empresa y edítelos con sus colaboradores en tiempo real.

- **Mejoras en la coautoría:** mejora del rendimiento de Word en coautoría en documentos con marcas de revisión.

- **Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos. Encuéntrelos en Insertar > Iconos. [Más información](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- **Otros usuarios verán los cambios rápidamente**: las mejoras en la coautoría significan que los colaboradores podrán ver los cambios más rápido que nunca.

- **Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su documento. [Más información](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Borrar con precisión:** elija entre dos tamaños de borrador para arreglar pequeñas imperfecciones de la entrada de lápiz. [Más información](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.

- **Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación.  [Más información](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- **Mejoras en la coautoría:** mejora de la confiabilidad de la coautoría.

- **Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar. [Más información](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **Convertir los archivos para mejorar la accesibilidad**: Actualice los archivos al formato moderno para que sean más accesibles para todos los usuarios.

- **Una experiencia de vídeo más segura:** las mejoras de seguridad hacen que la experiencia de vídeo en línea sea más segura. [Más información](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Acceso

- Esta actualización corrige un problema en Microsoft Access que puede causar el error "La consulta está dañada" cuando se ejecuta una consulta de actualización o cuando se usa una instrucción UPDATE en SQL.

- Esta actualización corrige un problema que puede hacer que Microsoft Access no identifique una Columna de identidad en una tabla vinculada de SQL Server, lo que puede provocar que las filas aparezcan como eliminadas de forma incorrecta.

- Esta actualización corrige un problema por el que al usar un objeto ADODB. Recorder en código de VB podía notificarse un error incorrectamente.

- Las plantillas de Access ya no deberían causar errores en columnas de datos adjuntos en una base de datos. Después de crear la instancia de una plantilla, ahora debería poder agregar un campo de datos adjuntos a la base de datos.

### <a name="excel"></a>Excel

- Corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.

- Este cambio evita un problema con ciertos controladores de gráficos Intel al aprovechar el procesamiento del software.

- Se ha corregido un problema que causaba que algunos usuarios experimentasen bloqueos al convertir texto en columnas con celdas que tienen una matriz derramada.

- Esta actualización corrige un problema que causaba que la barra de fórmulas mostrara texto en una fuente diferente a la esperada.

- La funcionalidad de Texto a columna puede fallar en algunas configuraciones regionales.

- Es posible que los usuarios vean un error si acceden a un rango con nombre oculto.

- Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.

- Corregimos un problema en el que al seleccionar una celda luego de desplazar, podía resultar en la selección de la celda incorrecta.

- Excel puede tener problemas al editar un archivo protegido desde una red compartida no confiable.

- La funcionalidad de Texto a columna puede fallar en algunas localizaciones.

- Es posible que los usuarios vean un error si acceden a un rango con nombre oculto.

- Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.

- Se ha corregido un problema que algunos usuarios pudieron sufrir con objetos incrustados y vinculados (OLE).

- Se ha corregido el botón derecho en el menú de gráficos dinámicos para habilitar la opción de mostrar los detalles.

- Se ha resuelto un problema que puede haber causado un bloqueo al buscar archivos recientes cuando no hay ningún libro de trabajo abierto.

- Se ha corregido un problema por el que algunos usuarios pueden haber visto varias ventanas emergentes cuando hubiera vínculos externos presentes en el libro.

- Se ha corregido un problema por el que los comandos de comentario en el menú contextual no aparecían.

- Se ha resuelto un problema en el que no se cargaba la personalización de cinta de opciones al abrir un libro insertado.

- Se ha solucionado un problema por el que las funciones CUBEVALUE a veces daban un resultado incorrecto.

### <a name="outlook"></a>Outlook

- Corregido un problema que causó un bloqueo en la experiencia de los comentarios de búsqueda.

- Corregido un problema que hacía que los usuarios no tuvieran respuesta de Outlook al recuperar la configuración de la nube.

- Se ha corregido un problema que provocaba que el cuadro de búsqueda estuviera mal alineado en modo de PPP alto.

- Corregido un problema que hacía que los usuarios observaran una fuga de memoria en el proceso de Outlook.

- Corregido un problema que hacía que los usuarios vieran correos electrónicos enviados a una dirección que no coincidía con la dirección SMTP mostrada en algunas circunstancias.

- Este cambio restaura la capacidad de ver sujetos de varias líneas en el encabezado del mensaje.

- Se ha corregido un problema que podía impedir que los archivos se guardaran en una ubicación de WebDAV.

- Corregido un problema con la selección del algoritmo SMIME.

- Corregido un problema que provocaba que las aplicaciones de terceros no pudiesen enviar correo electrónico.

- Se ha solucionado un problema que hacía que los usuarios vieran un cuadro de mensaje vacío con el botón "ok" cuando intentaban ponerse en contacto con el soporte técnico desde el contexto de la creación de la cuenta.

- Se ha corregido un problema que provocaba que los usuarios sufrieran un bloqueo durante la creación del perfil.

- Se ha corregido un problema por el que Outlook sincronizaba inesperadamente todo el correo, incluso cuando el deslizador de sincronización estaba configurado en un ajuste menor.

- Se corrigió un problema por el que los usuarios con el tema negro veían la lista desplegable "De" con un texto blanco sobre un fondo blanco.

- Se ha corregido un problema que provocaba que los usuarios experimentaran un error al cancelar la configuración de la cuenta.

- Corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.

- Se ha corregido un problema que hacía que la opción deshabilitar el resaltado de elementos marcados no se pudiera respetar en algunos escenarios.

- Corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange" al abrir el cuadro de diálogo Reglas.

- Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.

- Corregido un problema que causaba una fuga de memoria en sesiones de Outlook muy largas.

- Corregido un problema que podría resultar en un bloqueo del equipo cuando se veía el mismo elemento en varias ventanas.

- Corregido un problema que hacía que los usuarios vieran un retraso notable al interactuar con sus carpetas de buzón de correo a través de métodos abreviados de teclado.

- Se ha corregido un problema que provocaba que los usuarios no pudieran abrir algunas instancias de los elementos de calendario periódicos.

- Corregido un problema que provocaba que los usuarios con buzones en servidores de Exchange 2010 sufrieran problemas al agregar archivos adjuntos a elementos de calendario.

- Se ha corregido un problema que provocaba que los usuarios experimentaran problemas al responder a los mensajes firmados digitalmente.

- Se ha corregido un problema que provocaba que el campo Ubicación en las reuniones se actualizara de forma inesperada.

- Corregido un problema que causaba que las comas en el campo de Ubicación de una reunión se convirtieran en punto y coma.

- Corregido un problema que provocaba que la ubicación de una reunión se añadiera a la reunión de forma inesperada después de haberla borrado.

- Corregidos problemas relacionados con las reuniones y las citas establecidas en la zona horaria de la Brasil.

- Se corrigió un problema por el que se enviaban inesperadamente mensajes de correos electrónicos al presionar la tecla "S" después de cerrar el panel del comprobador de accesibilidad.

- Esto actualiza la lógica de bloqueo de adjuntos en Outlook para bloquear también los adjuntos de Python.

- Se ha corregido un problema que provocaba que los complementos web accedieran a los mensajes administrados con derechos digitales.

- Se ha corregido un problema que provocaba que los usuarios sufrieran un bloqueo durante la creación del perfil.

- Corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema con el método Shape.Paste: cuando el usuario copiaba y pegaba la forma con el método Shape.Paste, se cambiaba la selección a la forma pegada.

- Se ha corregido un problema que podía bloquear el equipo al usar el menú contextual en comentarios PPT heredados.

### <a name="project"></a>Project

- Identificamos un problema en el que los usuarios podían recibir varios mensajes al abrir un proyecto de solo lectura.

- Se ha corregido un problema por el que el 100 % de las tareas de tipo duración fija podían tener un cálculo del porcentaje incorrecto con menos del 100 % completado.

- Se corrigió un problema en el que las fechas de las tareas de resumen no se calculaban siempre correctamente.

- Corregido un problema en el que el evento OnUndoOrRedo no se desencadena sin ejecutar primero el método OpenUndoTransaction.

### <a name="word"></a>Word

- Corregido un problema ocasional en el que al guardar un archivo existente siempre aparece el cuadro de diálogo Guardar como, pero el archivo nunca se guarda.

- El organizador de bloques de creación puede mostrar una alerta no válida: "Ha modificado estilos, bloques de creación".

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Este cambio corrige el procesamiento lento de algunos gráficos de dispersión con marcadores.

- Este cambio resuelve problemas con adaptadores gráficos que aprovechan la GPU integrada de Intel.

- Corrección de un error en la configuración de la fecha límite de actualización de ODT y GPO, en la que la fecha límite relativa solo funciona la primera vez que se establece. Ahora, la corrección permite establecer una fecha límite relativa para las actualizaciones posteriores.

- Se ha corregido un problema por el que las actualizaciones de Office podían haber descargado inesperadamente archivos de la CDN de Office en lugar de la fuente prevista, como un recurso compartido local o de red, o una ubicación proporcionada por el Administrador de configuración.

- Corrige un problema por el que cuando hay varios documentos abiertos en Word/Excel/PowerPoint de la misma biblioteca de SharePoint, solo se analizará el primer documento abierto para el cumplimiento de las directivas.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-february-11"></a>Versión 1908: 11 de febrero
*Versión 1908 (Compilación 11929.20606)*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Esta actualización corrige un problema que provoca un error siempre que se utilizaba VBA para agregar una imagen al encabezado o pie de página de un gráfico.

- Se ha corregido un problema que hacía que el borde de un control de cuadro de grupo no estuviera visible en la vista previa de impresión o al imprimirlo.

- Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.

- Se ha corregido un problema por el que el tamaño de archivo de las imágenes en los encabezados del gráfico aumentaba cuando se guardaba el libro que contenía el gráfico.


- Se ha corregido un problema que provoca la corrupción de caracteres DBCS en los libros con referencias cruzadas manteniendo los rangos de selección sincronizados con el libro con referencias cruzadas.

- Se ha corregido un problema en el que los controles de casilla podían reducirse al usar el autoajuste para ajustar el alto de fila.


### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.

- Se ha corregido un problema que provocaba que los usuarios experimentaran errores de sincronización al procesar mensajes de conflicto.

- Se ha corregido un problema que provocaba que los usuarios experimentaran un error en la pantalla de carga del perfil al iniciar Outlook.

- Se ha corregido un problema que provocaba que los usuarios viesen bloqueos intermitentes al cambiar de vista.


- Se ha corregido un problema que causaba que los usuarios sufrieran un error al visualizar más de 30 calendarios en un entorno Citrix. [Aquí](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) está la KB individual, donde se ha documentado esto para versiones anteriores.

- Corrige un problema que provocaba que los usuarios tuvieran problemas al intentar sincronizar carpetas del calendario compartido con el OST, lo que producía errores en los permisos al tratar de interactuar con estas carpetas.


### <a name="powerpoint"></a>PowerPoint

- Se ha mejorado un escenario de copiar y pegar. Al copiar la forma en una diapositiva de PowerPoint y pegarla en otra diapositiva en bucle puede producir errores.


- Se ha corregido un problema que producía un rendimiento más lento entre los usuarios de colaboración.

- Se ha corregido un problema que puede producirse cuando un archivo que se abre incrementalmente contiene una diapositiva con más de una secuencia multimedia incrustada.

- Se ha corregido un problema por el que es posible que la barra de mensajes de advertencia de seguridad no aparezca para los complementos en los que no se confía al iniciar PowerPoint por primera vez.

### <a name="project"></a>Project

- Se ha corregido un problema en el que el trabajo real puede ser diferente entre el parte de horas y el plan del proyecto debido a que los calendarios de recursos no se actualizan cuando cambia el calendario base.

### <a name="word"></a>Word

- Se ha corregido un bloqueo en Word al dejar una API obsoleta.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Este cambio corrige el procesamiento de imágenes después de abrir un archivo dañado.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-january-14"></a>Versión 1908: 14 de enero
*Versión 1908 (compilación 11929.20562)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- La información clave en holandés para el título del documento ha sido cambiada a Alt-G.

- Se resolvió un problema con la personalización de la cinta que no se carga al abrir el libro de trabajo insertado.

- Hubo un problema en el que no se podían seleccionar elementos del cuadro combinado de un formulario de WPF (Windows Presentation Foundation) que fue abierto por un complemento.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema por el que los usuarios notaban un retraso evidente al interactuar con sus carpetas de buzón mediante métodos abreviados de teclado.

- Corregido un problema que hacía que no se mostraran las sugerencias de política cuando se utilizaba un remitente alternativo.

- Corregido un problema que hacía que los usuarios experimentaran bloqueos intermitentes al actualizar la información de presencia.

### <a name="powerpoint"></a>PowerPoint

- Arreglamos un problema cuando al copiar una diapositiva de una presentación a otra, se pueden crear patrones duplicados.
- Los archivos con nuevos comentarios modernos mostrarán una advertencia amarilla si se abren en una versión no soportada

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha solucionado un problema por el que los mensajes de actualización de Office aparecían en un idioma diferente al esperado. En el futuro, los mensajes de actualización de Office coincidirán correctamente con el idioma de visualización de Windows.

- Corregido un problema en el que una actualización no se aplicaría en ciertos casos en los que el usuario no es un administrador y la cuenta del sistema no tenía conectividad de red.



## <a name="version-1908-december-10"></a>Versión 1908 (10 de diciembre)
*Versión 1908 (compilación 11929.20516)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Se ha corregido un problema por el que una consulta de unión que incluye referencias a tablas remotas (por ejemplo, tablas de SQL Server) puede hacer que Access se cierre y se reinicie.

- Se ha corregido un problema por el que un agregado como Suma puede truncar el resultado a un valor entero.

### <a name="excel"></a>Excel

- Se ha resuelto un problema en el que al seleccionar una celda luego de desplazarse, podía resultar en la selección de la celda incorrecta.

- Se ha corregido un problema cuando el filtro de una tabla dinámica OLAP se estableció en un valor que se ha quitado del cubo.

- Este cambio evita un problema con ciertos controladores de gráficos Intel al aprovechar el procesamiento del software.

- Se ha resuelto un problema en el que la función Buscar puede devolver un error.

- Se han hecho mejoras significativas en el rendimiento al eliminar columnas con celdas combinadas.

- Se ha resuelto un problema que provocaba un error en tiempo de ejecución de la macro al activar ventanas minimizadas.

### <a name="outlook"></a>Outlook

- Corregido un problema con la selección del algoritmo SMIME.

- Se ha corregido un problema que hacía que los usuarios vieran una &quot;Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange&quot; al abrir el cuadro de diálogo de las reglas.

- Se ha corregido un problema que provocaba que los complementos web accedieran a los mensajes administrados con derechos digitales cuando no deberían.

### <a name="word"></a>Word

- Corregimos un problema en el control de cambios que a veces entra en un bucle infinito.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema en el que los caracteres katakana de ancho medio no giraban correctamente cuando se encontraban en cuadros de texto verticales en PowerPoint.

- Se ha corregido un problema por el que las actualizaciones de Office podían haber descargado inesperadamente archivos de la CDN de Office en lugar de la fuente prevista, como un recurso compartido local o de red, o una ubicación proporcionada por el Administrador de configuración.

- Para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office se firman ahora utilizando exclusivamente el algoritmo SHA-2.



[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-november-22"></a>Versión 1908: 22 de noviembre
*Versión 1908 (compilación 11929.20494)*


[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a>Problemas corregidos

### <a name="access"></a>Access

- Se corrigió un problema en el que ejecutar una consulta de actualización daría incorrectamente el mensaje de error: "La consulta está dañada".

### <a name="excel"></a>Excel

- Problema de rendimiento bajo al hacer clic en el botón Color de fuente cuando un archivo tiene un formato condicional extenso.

- Se ha corregido un problema por el que el área de impresión en la vista previa de impresión no era correcta.

- Excel puede tener problemas al editar un archivo protegido desde una red compartida no confiable.

- Corregido un problema que podía haber causado un fallo al buscar archivos recientes mientras no había ningún libro de trabajo abierto.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema por el que los usuarios veían un cuadro de mensaje vacío con el botón &quot;Aceptar&quot; al intentar ponerse en contacto con el soporte técnico desde la Creación de cuenta.

- Se ha realizado un cambio que permite a los administradores habilitar una directiva para que las solicitudes de autenticación de detección automática prefieran el correo electrónico de cuenta proporcionado sobre el UPN. De forma predeterminada, detección automática prefiere el UPN de la cuenta, cuando está disponible.

- Se ha corregido un problema que provocaba que los usuarios vieran un error en la búsqueda con grupos modernos.

- Se ha corregido un problema que provocaba que los usuarios experimentaran un error al intentar crear una regla desde un mensaje de&quot;Conversación perdida&quot;.

- Se ha corregido un problema que provocaba que los usuarios vieran un error en la búsqueda con grupos modernos.

### <a name="word"></a>Word

- Se ha corregido un problema que podría haber provocado problemas de escalabilidad al imprimir impresoras Deskjet.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema para evitar que los usuarios de PowerPoint experimenten errores al intentar presentar en línea.

- Se ha mejorado la confiabilidad del proceso de actualización de Office respecto a la integridad del registro.

- Se ha corregido un problema en el que las actualizaciones podían haberse bloqueado de forma inesperada en redes de uso medido.

- Se ha corregido un problema en la configuración de la fechas límites de actualización para ODT y GPO donde la fecha límite relativa solo funciona la primera vez que se establece, y la corrección habilita la fecha límite relativa para las actualizaciones posteriores.

[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-1908-november-12"></a>Versión 1908: 12 de noviembre
*Versión 1908 (compilación 11929.20436)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos

### <a name="excel"></a>Excel

- Se han corregido los colores que se usan en las vistas previas al insertar gráficos con plantillas de gráficos.
- Se ha corregido un problema que podía impedir que los gráficos de líneas de dispersión se representaran correctamente al cambiar la colección de series.
- Se ha resuelto un problema que provocaba interrupciones en la coautoría al cambiar las propiedades personalizadas con la ejecución de macros.
- Hemos corregido un problema de rendimiento con las funciones asíncronas definidas por el usuario que hacía que se ejecutaran de forma sincrónica.
- Mejoramos significativamente el rendimiento del filtro por color.
- Se ha resuelto un problema en el que los libros creados en versiones anteriores de Office podrían hacer que Excel se bloqueara cuando se abría en las versiones actuales de Office.
- Los vínculos de cid: las imágenes de los mensajes de Outlook ahora se pueden descomponer correctamente cuando se solicite.

### <a name="outlook"></a>Outlook

- Los vínculos de cid: las imágenes de los mensajes de Outlook ahora se pueden descomponer correctamente cuando se solicite.
- Se ha corregido un problema que provocaba que los usuarios experimentaran un error de permiso al copiar elementos de su calendario principal en un calendario de grupo.
- Se ha corregido un problema que provocaba una pérdida de memoria durante sesiones de Outlook muy largas.
- Se ha corregido un problema que podía causar un error en Outlook cuando los usuarios interactuaban con ciertos vínculos seguros.
- Se ha corregido un problema que provocaba que los usuarios experimentaran un error al procesar algunas respuestas de detección automática.
- Se ha corregido un problema que causaba que algunos usuarios vieran carpetas especiales duplicadas al agregar una cuenta de Exchange secundaria.
- Se ha corregido un problema que provocaba un bloqueo en la experiencia de búsqueda de comentarios.

### <a name="powerpoint"></a>PowerPoint

- Los vínculos de cid: las imágenes de los mensajes de Outlook ahora se pueden descomponer correctamente cuando se solicite.
- Corrección de confiabilidad: se ha solucionado un problema en el que era posible que PowerPoint fallara al usar el complemento de terceros.

### <a name="project"></a>Project

- Se ha corregido un problema por el que el comando Redistribuir todo no ha resuelto correctamente la sobreasignación de un recurso.
- Se ha corregido un problema por el que si tiene una tarea sin nada de trabajo, la tarea no se puede marcar como completada y siempre se mostrará en el 99 %.
- Identificamos un problema en el que los usuarios podían recibir varios mensajes al abrir un proyecto de solo lectura.

### <a name="word"></a>Word

- Los vínculos de cid: las imágenes de los mensajes de Outlook ahora se pueden descomponer correctamente cuando se solicite.
- Se han corregido varios problemas que causaban el bloqueo o apagado de la aplicación. También se corrigieron ciertos errores relacionados con el complemento.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Problemas resueltos relacionados con la propiedad Cuadro de texto/Autoajuste de formas en los complementos de terceros.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="october-15"></a>15 de octubre

### <a name="non-security-updates"></a>Actualizaciones que no son de seguridad

### <a name="office-suite"></a>Conjunto de aplicaciones de Office
- Hemos desactivado el cuadro de diálogo Guardar en la nube de forma temporal para solucionar el problema de almacenamiento que publicamos el 14 de octubre de 2019 de las compilaciones posteriores a la versión 16.0.11929.20396. Esta característica se volverá a habilitar próximamente.

## <a name="version-1908-october-14"></a>Versión 1908: 14 de octubre
*Versión 1908 (compilación 11929.20396)*


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="non-security-updates"></a>Actualizaciones que no son de seguridad
### <a name="excel"></a>Excel

- <div>Se resolvió un problema con Buscar y reemplazar que cambiaba el enfoque en el cuadro de diálogo después de encontrar el primer elemento.</div>

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se resolvió un problema que impedía a los usuarios guardar documentos de Word, Excel y PowerPoint 2019 en las compilaciones posteriores a la versión 16.0.11929.20396. Este problema afecta a los usuarios que crean un nuevo archivo y muestra el diálogo "Guardar como" después de hacer clic en el icono Guardar o presionar Ctrl + S.

- Se resolvió un problema en el que, en determinadas circunstancias, los accesos directos de Office desaparecían después de una actualización.  Esta actualización mejora la confiabilidad al publicar los accesos directos de Office.

[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-1908-october-08"></a>Versión 1908: 8 de octubre
*Versión 1908 (compilación 11929.20388)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="non-security-updates"></a>Actualizaciones que no son de seguridad
### <a name="excel"></a>Excel

- Se ha solucionado un problema por el que los hipervínculos no se podían pegar en algunas hojas protegidas.

- Ahora se permite mostrar más de 16 complementos al navegar por el administrador de complementos.

- Se ha corregido un problema de la característica Ideas de Excel al cargar el complemento haciendo clic en el botón Ideas en el cliente de Win32.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba errores en la visualización de las direcciones URL de desplazamiento simple en algunos vínculos seguros.

- Se ha actualizado la lógica de bloqueo de datos adjuntos en Outlook que bloqueaba también los datos adjuntos de Python.

- Se ha corregido un problema por el que los usuarios notaban una pérdida de memoria en el proceso de Outlook.

### <a name="powerpoint"></a>PowerPoint

- Se ha solucionado un problema que podía provocar pérdidas de datos en sesiones relacionadas con la coautoría y la edición sin conexión en PowerPoint.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha solucionado un problema que causaba un bloqueo al abrir un archivo.

- Se ha solucionado un problema por el que la información de accesibilidad no se mostraba en la sección Información de Lugar de la vista Backstage.

- Se ha mejorado la estabilidad al reanudar descargas previamente interrumpidas de actualizaciones de Office.

- Para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office ahora se firman exclusivamente con el algoritmo SHA-2.

[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-1908-september-10"></a>Versión 1908: 10 de septiembre
*Versión 1908 (Build 11929,20300)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="access"></a>Acceso

- **Zoom con más espacio:** agrandar el cuadro de Zoom, cambiar la fuente y hacer que Zoom lo recuerde todo. [Más información](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

- **Mantener un seguimiento de los objetos de base de datos:** ver claramente la pestaña activa, arrastrar las pestañas para reorganizarlas fácilmente y cerrar los objetos de base de datos con un solo clic.

- **Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar. Cambiar de una a otra nunca había sido tan fácil. [Más información](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="excel"></a>Excel

- **Obtener más información sobre los datos:** el nuevo botón Ideas busca patrones en los datos y los usa para crear sugerencias inteligentes y personalizadas. [Más información](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- **Encuentre ese archivo rápido:** ¿Busca un archivo en el que trabajó recientemente? Basta con que escriba en el cuadro de búsqueda en la página Archivo > Inicio para encontrar el archivo que busca.

- **Aumentar el alcance de su contenido:** ¿necesita que las presentaciones sean accesibles? Deje que el comprobador de accesibilidad le ayude sin estorbar. Pruébelo en Revisar > Comprobar accesibilidad y le informaremos en la barra de estado de cuando necesitemos que compruebe algo.

- **Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar. Cambiar de una a otra nunca había sido tan fácil. [Más información](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Vea cómo la hoja de cálculo cobra vida**: inserte gráficos 3D animados para ver corazones que laten, planetas en órbita y dinosaurios a toda velocidad por el libro. [Más información](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- **La colaboración es ahora más fácil**: las mejoras en la coautoría significan que al trabajar con el formato condicional, los estilos de celda y otros elementos, los cambios se combinan perfectamente con los de los colaboradores.

- **Unir tablas en columnas similares:** obtener y transformar (Power Query) ahora ofrece una lógica de coincidencia de texto (también denominada coincidencia aproximada) al comparar columnas en la combinación de tablas. [Más información](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- **Programar rápidamente con mejoras de Power Query:** termine rápidamente el código con colores de sintaxis y la función de autocompletar. Además, descubra fácilmente funciones, columnas y parámetros.

- **Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea. Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido. [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a>Outlook

- **Seguir trabajando mientras mueve mensajes:** Outlook ahora mueve los mensajes en segundo plano, por lo que puede seguir trabajando mientras mueve una gran cantidad de mensajes entre carpetas.

- **Creación en el tiempo entre las reuniones consecutivas:** asigne a los asistentes el tiempo para descansar o desplazarse entre las distintas ubicaciones al configurar reuniones para finalizar 5 a 10 minutos antes de forma predeterminada.

- **Verán los memes que comparta:** cuando un texto o imágenes estáticas no consigan comunicar lo que desea, use un GIF animado para aclararlo. [Más información](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)

- **Hemos actualizado la experiencia de usuario de Outlook para usted:** una experiencia simplificada, anteriormente disponible para su vista previa con Próximamente, diseñada para ayudarle a centrarse en lo más importante. [Más información](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- **¿Quiere que su diseño tenga un espaciado menor o mayor? Usted elige:** la opción de un espaciado más ajustado le permite decidir si quiere más espacio entre los elementos o un diseño más ajustado para ver más elementos.

- **Una cinta simplificada que además es personalizable:** disfrute de una sola fila simplificada con los botones más usados. Cambie fácilmente entre la vista clásica y la simplificada, y ancle o desancle comandos. [Más información](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- **Una forma más rápida de agregar cuentas:** gracias a las mejoras de configuración de cuentas, es más fácil que nunca agregar cuentas de Outlook.com y Gmail que usen la autenticación en dos fases a Outlook. [Más información](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- **Seleccione su acción favorita:** ¿no usa Etiquetar ni Eliminar? ¿Qué hay de Archivar o Marcar como leído? Personalice el menú de acciones rápidas con los comandos que use más frecuentemente.

- **Despídase de límites de sincronización:** las mejoras de Outlook significan que se ha eliminado el límite de carpetas y sincronizar los buzones compartidos.

- **Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea. Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido. [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a>PowerPoint

- **Pregunte a su público con un cuestionario o una encuesta:** coloque un cuestionario o una encuesta en una diapositiva. Office recopila y almacena las respuestas para usted. [Más información](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)

- **Encuentre ese archivo rápido:** ¿Busca un archivo en el que trabajó recientemente? Basta con que escriba en el cuadro de búsqueda en la página Archivo > Inicio para encontrar el archivo que busca.

- **Aumentar el alcance de su contenido:** ¿necesita que las presentaciones sean accesibles? Deje que el comprobador de accesibilidad le ayude sin estorbar. Pruébelo en Revisar > Comprobar accesibilidad y le informaremos en la barra de estado de cuando necesitemos que compruebe algo.

- **Guardar los cambios a medida que los realiza:** cargue el archivo en OneDrive para asegurarse de que todas las actualizaciones se guardan automáticamente.

- **Nunca fue tan fácil insertar un vídeo en línea:** ¿quiere poner un vídeo de Vimeo o de YouTube en la diapositiva? Solo necesita el vínculo a la página del vídeo. [Más información](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **Mejor transformación:** asigne un nombre a las formas para tener más control sobre cómo se transforman. [Más información](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- **Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar. Cambiar de una a otra nunca había sido tan fácil. [Más información](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Los vídeos en línea tienen un nuevo hogar:** guarde un vídeo en Microsoft Stream para que puedan verlo todas las personas de su organización. Inserte el vínculo del vídeo y disfrute de una presentación multimedia en una fracción del tamaño del archivo. [Más información](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea. Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido. [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a>Project

- **Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar. Cambiar de una a otra nunca había sido tan fácil. [Más información](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a>Visio

- **Adiós a los vínculos rotos de Excel:** ¿no encuentra el libro de Excel vinculado a un diagrama de visualizador de datos? Solo tiene que vincularlo de nuevo y ¡listo! [Más información](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)

- **Galerías de símbolos integradas en Azure:** diseñe una aplicación de nube o planee una arquitectura con las múltiples galerías de símbolos de Azure. [Más información](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- **Doble toma en diagramas de flujo de datos:** Los magníficos nuevos diseños para los diagramas de flujo del visualizador de datos son limpios, nítidos y fáciles de entender. Haga clic en la pestaña Diseño para ver las opciones.

- **Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar. Cambiar de una a otra nunca había sido tan fácil. [Más información](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Exportar diagramas de proceso a Word:** Agregue automáticamente contenido del diagrama, como formas y metadatos, a un documento de Word. Después, personalice el documento para crear instrucciones de procesos y manuales de funcionamiento. [Más información](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- **Exportar objetos visuales de Visio desde Power BI**: los objetos visuales de Visio para Power BI ahora se mostrarán correctamente al exportar informes de Power BI como archivos PDF, archivos de PowerPoint, etc. [Más información](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a>Word

- **Edición natural con el Editor para entradas de lápiz:** con un solo trazo, divida o una palabras, agregue una nueva línea o inserte palabras con el lápiz. [Más información](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- **Su documento: de estático a mágico:** transforme el documento en una página web interactiva y fácil de compartir con un aspecto fantástico en cualquier dispositivo. [Más información](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)

- **Llame su atención con \@Menciones:** use @menciones en los comentarios para avisar a otros cuando necesite su participación. [Más información](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **Mejorar la comprensión con el foco de línea:** desplácese por un documento línea por línea sin distracciones. Ajuste el foco para ver una, tres o cinco líneas a la vista. [Más información](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)

- **Encuentre ese archivo rápido:** ¿Busca un archivo en el que trabajó recientemente? Basta con que escriba en el cuadro de búsqueda en la página Archivo > Inicio para encontrar el archivo que busca.

- **Guardar los cambios a medida que los realiza:** cargue el archivo en OneDrive para asegurarse de que todas las actualizaciones se guardan automáticamente.

- **Aumentar el alcance de su contenido:** ¿necesita hacer que sus documentos sean accesibles? Deje que el comprobador de accesibilidad le ayude sin estorbar. Pruébelo en Revisar > Comprobar accesibilidad y le informaremos en la barra de estado de cuando necesitemos que compruebe algo.

- **El modo herramientas de aprendizaje tiene soporte adicional para más colores de página:** las herramientas de aprendizaje de Word son compatibles con más colores de tema de página, lo que permite cambiar el color de fondo de la página. Muchas personas tienen dificultades para leer con un fondo totalmente blanco o negro, por lo que hemos ampliado la elección de colores en Word para PC y Mac.

- **Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar. Cambiar de una a otra nunca había sido tan fácil. [Más información](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)


- **Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea. Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido. [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- **Instalación de Microsoft Teams:** se ha agregado Teams a las instalaciones existentes de Office 365 ProPlus. [Más información](/deployoffice/teams-install)

- **Guardar los cambios a medida que los realiza:** cargue el archivo en OneDrive para asegurarse de que todas las actualizaciones se guardan automáticamente.

- **Controles de privacidad:** nuevos controles para datos de diagnóstico y experiencias conectadas, actualizados y mejorados. [Más información](/DeployOffice/privacy/overview-privacy-controls?toc=%2fdeployoffice%2ftoc.json)

- **Los iconos de Office tienen un nuevo aspecto:** los iconos de Office se han rediseñado para reflejar las sencillas, inteligentes y eficaces experiencias de Office.

- **Instalación de Microsoft Teams:** Microsoft Teams se instala de forma predeterminada en las instalaciones existentes de Office 365 ProPlus. [Más información](/DeployOffice/teams-install)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="non-security-updates"></a>Actualizaciones que no son de seguridad
### <a name="excel"></a>Excel

- Se ha corregido un problema en Excel en el que las macros asignadas a formas o controles de formularios podían mostrar un mensaje de error incorrecto o funcionar en intervalos de destino incorrectos.

- Se ha corregido un problema que ocurría al cambiar la forma en que una tabla dinámica está ordenada o al actualizarla en una sesión de coautoría con otros usuarios.

- Se ha corregido un problema que causaba que los gráficos de cascada y embudo dejaran de estar sincronizados con las tablas al insertar o eliminar celdas.

- Se ha corregido un problema de conflicto de combinación en Excel que hacía que los usuarios tuvieran que abrir de nuevo el libro para elegir los cambios.

- Se ha corregido un problema que causaba errores en las operaciones de corte y pegado junto a una tabla cuando se trabajaba en coautoría con otras personas.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema que causaba que los usuarios que actualizaban su buzón de la autenticación básica a la moderna, terminaban con una cuenta incorrecta asociada a su perfil de Outlook.

- Se ha corregido un problema que causaba que un subconjunto de usuarios de POP3 viesen todos los correos electrónicos como texto sin formato, independientemente de la configuración. En esta corrección se restaurará la vista de los mensajes con formato HTML.

- Se ha corregido un problema que causaba que los usuarios no obtuvieran acceso a las sugerencias de ubicación a través de un lector de pantalla.

- Se ha corregido un problema que causaba que algunos usuarios encontraran errores de autenticación al intentar recuperar la configuración de la nube para Outlook.

- Se ha corregido un problema que causaba ambigüedad para los administradores sobre si un delegado ya había respondido a una convocatoria de reunión determinada.

- Se ha corregido un problema que causaba que los usuarios de Outlook se quedaran atascados en el estado "necesita contraseña" en ciertos escenarios.

- Se ha corregido un problema que causaba errores en la búsqueda de la carpeta actual.

- Se ha corregido un problema que causaba que los usuarios vieran sugerencias de sala para las reuniones que ocurrieron fuera de las horas de disponibilidad de este salón.

- Se ha corregido el problema de servicio temporal que causaba que los usuarios vieran el error "No se encuentra el archivo. Compruebe que la ruta de acceso y el nombre de archivo sean correctos" al usar datos adjuntos de la nube. [Más información](https://support.office.com/article/outlook-unable-to-attach-onedrive-or-sharepoint-files-to-emails-136951bb-60dc-478a-b916-6ee39e62c37a)

- Se ha corregido un problema que causaba que los usuarios vieran los archivos cargados desde Outlook a OneDrive o SharePoint tienen el nombre de archivo cambiado donde varios caracteres reemplazados por subrayado.

- Se ha corregido un problema para los usuarios que no estaban en inglés dónde la línea de asunto en un correo sería increíblemente pequeña.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema por el que algunos complementos producían errores inesperados alrededor de las formas en gráficos.

- Se ha corregido un problema para restaurar el nombre accesible para los controles de vídeo de PowerPoint.

- Se ha corregido un problema que impide que algunas animaciones se inicien

### <a name="project"></a>Project

- Se ha corregido un problema para permitir que los usuarios en Windows 7 puedan abrir proyectos desde Project Web App y sitios de SharePoint.


### <a name="visio"></a>Visio

- La exportación a SVG de Visio no funcionaba para una gran variedad de formas.

### <a name="word"></a>Word

- Se ha corregido un problema en el que los usuarios recibían mensajes de error mientras colaboran con otras personas en un documento de Word.

- Se ha corregido un problema que provocaba que los usuarios recibieran el mensaje "Hay algo que impide compartir esto" al intentar compartir archivos almacenados en SharePoint 2016.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema en el que en algunos casos un motor de sincronización de un archivo de SharePoint pudo mostrar "guardado", pero no se guardaron los cambios realmente.

- Se ha corregido un problema que provocaba errores en las vistas de árbol grandes.

- Se ha corregido un problema de identificación del nombre de la nueva era "Reiwa" en Hiragana y Kanji como una expresión gramaticalmente incorrecta o mal escrita.


[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-1902-august-13"></a>Versión 1902: 13 de agosto
*Versión 1902 (compilación 11328.20392)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)

### <a name="excel-non-security-updates"></a>Excel: actualizaciones no relacionadas con la seguridad
- Se ha corregido un problema por el que se mostraba el icono borrar filtro de las segmentaciones de datos filtrados y sin filtrar de las tablas.

### <a name="outlook-non-security-updates"></a>Outlook: actualizaciones no relacionadas con la seguridad
- Se ha corregido un problema por el que los usuarios que actualizaban el buzón de la autenticación básica a la moderna, terminaban con una cuenta incorrecta asociada.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: actualizaciones no relacionadas con la seguridad
- Se ha corregido un problema por el que la aplicación finalizaba de forma inesperada al colaborar en un documento con otros usuarios.

### <a name="word-non-security-updates"></a>Word: actualizaciones no relacionadas con la seguridad
- Se ha corregido un problema por el que los campos de actualización de VBA eran lentos.
- Se ha corregido un problema por el que al abrir un archivo DOC, indicaba que estaba dañado.
- Se ha corregido un problema por el que la aplicación finalizaba de forma inesperada al colaborar en un documento con otros usuarios.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones no relacionadas con la seguridad
- Se ha corregido un problema por el que la API de configuración no funcionaba en la biblioteca JavaScript de Office en ciertos escenarios. [Más información](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)

## <a name="version-1902-july-09"></a>Versión 1902: 09 de julio
*Versión 1902 (compilación 11328.20368)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)


### <a name="excel-non-security-updates"></a>Excel: actualizaciones no relacionadas con la seguridad
- Se ha corregido un problema de lentitud extremo en la eliminación de las filas de Excel filtradas.
- Se ha corregido un desplazamiento fijo con dos dedos que provoca que los rectángulos grises se dibujen en la hoja de cálculo y Excel se bloquee.


### <a name="outlook-non-security-updates"></a>Outlook: actualizaciones no relacionadas con la seguridad
- Se ha corregido un problema que provocaba que los usuarios vieran ocasionalmente Outlook insertando letras pinyin en inglés, en lugar de mantener abierta la ventana del candidato IME para permitir la selección de palabras en chino.
- Se ha corregido un problema que provocaba que los usuarios vieran las salas sugeridas para reuniones que estaban programadas fuera de la disponibilidad de la sala.
- Se ha corregido un problema que provocaba que los usuarios intentaran abrir una excepción a una serie de reuniones para abrir la serie principal.
- Se ha corregido un problema que provocaba que los usuarios vieran fechas de expiración calculadas incorrectamente para elementos de la carpeta elementos eliminados.


### <a name="teams-non-security-updates"></a>Teams: actualizaciones no relacionadas con la seguridad

- Teams Installer ahora tiene una política disponible para desactivar el arranque automático cuando se complete la instalación.


### <a name="visio-non-security-updates"></a>Visio: actualizaciones no relacionadas con la seguridad

- Se ha corregido un problema en el que las soluciones de ActiveX para Visio no funcionan con Office 365, mostrando un mensaje de error que indica que no se encuentra el elemento riched20.dll.


### <a name="word--non-security-updates"></a>Word: actualizaciones no relacionadas con la seguridad

- Fue corregida la configuración fija de GPO para deshabilitar la barra de búsqueda de plantillas
- Se ha corregido un problema en el que los usuarios pueden perder algunos de los cambios después de desconectarse y editar un documento que solo tenía un servidor.
- Fue mejorado el rendimiento al habilitar elementos rápidos para las propiedades del documento
- Se ha corregido un problema por el que podía producirse un error en la primera revisión de descarga del servidor


### <a name="office-suite--non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones no relacionadas con la seguridad

- Se ha corregido un problema por el que los dispositivos que usan la activación compartida de equipos pueden volver a la activación basada en el usuario de forma inesperada al instalar productos de Office o paquetes de idioma adicionales.
- Se ha corregido un problema que impedía las actualizaciones de Office al ejecutar la autenticación de proxy como sistema.
- Se han hecho correcciones para solucionar los complementos de Office que desaparecen al cambiar el perfil de usuario.


## <a name="version-1902-june-11"></a>Versión 1902: 11 de junio
*Versión 1902 (compilación 11328.20318)*
<br/>Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)

### <a name="excel-non-security-updates"></a>Excel: actualizaciones no relacionadas con la seguridad
 - Se ha resuelto un problema que provocaba un bloqueo al guardar un archivo que contenía una asignación XML para PDF.
 - Se ha resuelto un problema que provocaba que se quiten los vínculos externos al cargar libros con nombres de hojas no válidos.
 - Se ha corregido un problema en el uso de la herramienta Cámara en Excel que podía provocar el bloqueo de la hoja de cálculo.
 - Se ha resuelto un problema por el que los gráficos de cascada y embudo dejaban de estar sincronizados con las tablas al insertar o eliminar celdas.
 - Se ha resuelto un bloqueo que ocurría al recalcular una tabla de datos durante un cálculo de la hoja con una fórmula de matriz en otra hoja que dependía de la tabla. 
 - Se ha resuelto un problema que impedía que los libros protegidos con contraseña se abran desde SharePoint sin primero desproteger el archivo.
 - Se realizó un cambio para asegurar que el evento BeforeSave se controle al compartir o alternar el Autoguardado.

### <a name="outlook-non-security-updates"></a>Outlook: actualizaciones no relacionadas con la seguridad
 - Se ha corregido un problema que provocaba que los clientes vean sus tareas aparentemente desaparecer al agregar una 2ª condición a "Agrupar por".

### <a name="word-non-security-updates"></a>Word: actualizaciones no relacionadas con la seguridad
 - Se ha corregido un problema que provocaba que al compartir un documento que está en colaboración se genere un archivo adjunto con la extensión .asd.
 - Se ha corregido un problema con los comentarios que se atribuían a autores aleatorios.
 - Se ha corregido un problema con quitar firma al desproteger un documento.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones no relacionadas con la seguridad
 - Se ha corregido un error en VBA que informaba de un estado de relleno de forma incorrecto después de una acción de "deshacer".


## <a name="version-1902-may-14"></a>Versión 1902: 14 de mayo
*Versión 1902 (compilación 11328.20286)*

### <a name="excel-non-security-updates"></a>Excel: actualizaciones no relacionadas con la seguridad
 -  Se ha corregido un problema en el uso de la herramienta Cámara en Excel que podía provocar el bloqueo de la hoja de cálculo.
 - Un problema que provocaba un bloqueo al usar la rueda de desplazamiento del ratón en una ventana activa con una hoja de gráfico se ha corregido.
 - Se ha resuelto un problema que provocaba que apareciese un mensaje "Error inesperado" al importar una hoja de cálculo en SharePoint.
 - Se ha solucionado un problema que provocaba que Excel se bloqueara al abrir un libro que contenía formato condicional usando un nombre para su regla y una vista personalizada.
 - Las macros que usan la validación de datos con fórmulas de más de 255 caracteres pueden haber producido errores en tiempo de ejecución. Este problema se ha corregido.
 - Un problema que provocaba que los archivos que contenían tablas dinámicas vinculadas a otros libros se cargaran despacio. Este problema se ha corregido.
 - Se ha resuelto un problema con la apertura de archivos HTML y el error "el formato de archivo y la extensión no coinciden".
 - Se ha realizado un cambio para resolver problemas con el desplazamiento por la rueda del ratón en ventanas inactivas.  

### <a name="outlook-non-security-updates"></a>Outlook: actualizaciones no relacionadas con la seguridad
 - Se ha corregido un problema por el que los clientes no podían editar algunos campos de los elementos que se han migrado.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: actualizaciones no relacionadas con la seguridad
- Se ha corregido un problema por el que PowerPoint dejaba de cargar los cambios del usuario en la nube en raras ocasiones.

### <a name="skype-for-business-non-security-updates"></a>Skype Empresarial: actualizaciones no relacionadas con la seguridad
 - Se corrige un problema en Lync (Skype Empresarial) por el que en cualquier reunión en línea con más de 7 participantes, la ventana de reunión puede desaparecer.
 - Inicie sesión en Skype Empresarial con las credenciales que usa para iniciar sesión en otra aplicación de Office.
 - Active correctamente la aplicación de Skype Empresarial cuando se instala con la activación en equipos compartidos.

### <a name="visio-non-security-updates"></a>Visio: actualizaciones no relacionadas con la seguridad
 - Se ha corregido un problema que causaba problemas de jerarquía de ventana errónea para soluciones de terceros que ampliaban Visio al deshabilitar la característica de PPP dinámico.

### <a name="word-non-security-updates"></a>Word: actualizaciones no relacionadas con la seguridad
 - Se ha corregido un problema por el que la edición de una Persona relacionada agregada por SharePoint podía bloquearse.
 - Se ha corregido un problema en el cuadro de diálogo "Error al cargar el recurso" cuando se inicia Word.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones no relacionadas con la seguridad
 - Esta es una solución para un problema en el que no se pueden guardar archivos en carpetas WebDAV de Apache.
 - Corrige un problema en el que Office se cierra de forma abrupta cuando los clientes abren algunos archivos almacenados en la nube.
 - Se corrigió un problema de identificación del nombre de la nueva era "Reiwa" en Hiragana y Kanji como una expresión gramaticalmente incorrecta o mal escrita.
 - Se ha corregido un problema de varios usuarios de Windows 10 por el que parecía que la lista de archivos recientes se había borrado.
 - Se ha corregido un problema por el que un usuario final veía una barra de Office Update, aunque durante una actualización activada por el administrador.
 - Se han corregido problemas relacionados con indicaciones de inicio de sesión intermitentes en blanco.
 

## <a name="version-1902-april-9"></a>Versión 1902: 9 de abril
*Versión 1902 (compilación 11328.20230)*

### <a name="excel-non-security-updates"></a>Excel: actualizaciones no relacionadas con la seguridad

- Resuelto un problema por el que al presionar la tecla Tab no se pasaba a la siguiente celda cuando se estaba en una celda con una fórmula que termina en un nombre definido.
- Resuelto un problema consistente en que el formato de celda provocaba que el tamaño del archivo creciera innecesariamente.
- Resuelto un problema por el que cortar y pegar una Tabla dinámica entre libros puede dar lugar a que los datos se peguen, sin una Tabla dinámica para otros usuarios con los que esté colaborando.

### <a name="outlook-non-security-updates"></a>Outlook: actualizaciones no relacionadas con la seguridad

- Corregido un problema en el que las ventanas no aparecían en la ubicación correcta cuando la barra de tareas del sistema se mantenía en la izquierda o en la parte superior de la pantalla.
- Soluciona un problema que hacía que los clientes experimentaran un bloqueo al cargar imágenes de la tarjeta de contacto.
- Soluciona un problema que hacía que algunos clientes experimentaran bloqueos al iniciar aplicaciones de Office.
- Corregido un problema en el que las ventanas no aparecían en la ubicación correcta cuando la barra de tareas del sistema se mantenía en la izquierda o en la parte superior de la pantalla.
- Soluciona un problema por el que los clientes no podían editar algunos campos de los elementos que se han migrado.

### <a name="visio-non-security-updates"></a>Visio: actualizaciones no relacionadas con la seguridad

- Corregido un problema que causaba problemas de jerarquía de ventana errónea para soluciones de terceros que amplían Visio al deshabilitar la característica de PPP dinámico.

### <a name="word-non-security-updates"></a>Word: actualizaciones no relacionadas con la seguridad

- Si un archivo se abre en modo de solo lectura y se hace clic en Guardar como en el panel Información, se solucionará el problema para que se muestre la interfaz de usuario de guardar.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad

- Corregido un problema por el que los elementos de una actualización de Office no usan el almacenamiento en caché del mismo nivel de optimización de entrega. [Más información](/windows/deployment/update/waas-delivery-optimization)
- Corrección de un error que podría provocar que se eliminaran o no se activaran productos si Office se había instalado con la Herramienta de implementación de Office y había un caso de no coincidencia.
- Corregido un problema que causaba indicaciones de inicio de sesión excesivas en dispositivos Windows 10 (versión 1803 o posterior).
- Corregida regresión que producía bloqueos al descargar imágenes vinculadas.
- Corregida borrosidad de archivos EMF de gran tamaño pegados en Word, Excel o PowerPoint.
- Corregido el error en el historial de versiones de la lógica de análisis que en algunos casos hacía que los documentos que se abrieran en modo solo lectura.

## <a name="version-1902-march-12"></a>Versión 1902: 12 de marzo
*Versión 1902 (compilación 11328.20158)*

### <a name="access-feature-updates"></a>Access: Actualizaciones de características

- **Vincular, actualizar o quitar tablas vinculadas:** el Administrador de tablas vinculadas actualizado es la ubicación para administrar todos los orígenes de datos y tablas vinculadas. [Más información](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)
- **Píntalo negro, píntalo gris:** cambie el aspecto de Access tantas veces como quiera. Cuatro temas para elegir: multicolor, gris oscuro, negro y blanco. [Más información](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)
- **Office tiene un nuevo aspecto:** ahora las aplicaciones de Office tienen iconos modernos más sencillos y accesibles. Además, la cinta de opciones tiene efectos visuales actualizados que resaltan las características de colaboración disponibles en las aplicaciones de Office.

### <a name="excel-feature-updates"></a>Excel: Actualizaciones de características

- **Inicio más rápido** La página de Inicio recién diseñada coloca los documentos abiertos recientemente en el centro y en primer plano. Acceda a archivos con menos clics y abra la Configuración u Opciones de la cuenta desde allí.
- **Colaborar con comentarios:** mantenga la conversación activa directamente en la hoja de cálculo con el cuadro de respuesta integrado. [Más información](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)
- **Los iconos de la cinta tienen un aspecto nuevo:** no se preocupe, todo funciona de la misma forma. Además, tendrán un aspecto excelente en pantallas de todos los tamaños. [Más información](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Capacidad de insertar SVG con filtros aplicados:** ahora, los usuarios de Office tienen la capacidad de insertar SVG con filtros aplicados. [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Mostrar lo que esconde una imagen:** coloque una imagen en una hoja de cálculo, elija el valor predeterminado y vea cómo cambia la transparencia. [Más información](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Una llamada a todos los seguidores de Obtener y transformar**: si usa Obtener y transformar a menudo, le alegrará saber que se ha mejorado la característica Columna a partir de los ejemplos. [Más información](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)
- **Compatibilidad mejorada con pantallas de alta definición:** si usa varios monitores o una base de conexión para portátil, las aplicaciones de Office ofrecen ahora una imagen nítida en todas las pantallas, incluso si tienen configuraciones de escala diferentes. [Más información](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Búsqueda rápida** Se han potenciado los cálculos de las funciones BUSCARV, BUSCARH y COINCIDIR para que pueda obtener respuestas con más rapidez. [Más información](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)

### <a name="outlook-feature-updates"></a>Outlook: actualizaciones de características

- **Use Lectura en voz alta para escuchar el correo electrónico:** Outlook puede leer el correo electrónico en voz alta, resaltando el texto a medida que se lee. Para activar Lectura en voz alta, vaya a la configuración de Accesibilidad. [Más información](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)
- **Escriba sin manos:** ¿tiene un micrófono? Haga clic en Dictar y vea cómo Outlook escribe mientras habla.  [Más información](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Los iconos de la cinta tienen un aspecto nuevo:** no se preocupe, todo funciona de la misma forma. Además, tendrán un aspecto excelente en pantallas de todos los tamaños. [Más información](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Bloquear la descarga de contenido externo de forma predeterminada en los correos electrónicos firmados y encriptados SMIME:** debido a una vulnerabilidad en el protocolo SMIME, Outlook bloqueará la descarga de contenido externo en mensajes que se hayan cifrado o firmado mediante SMIME. Los usuarios no podrán descargar contenido externo con un solo clic en la interfaz de usuario de Outlook para protegerse de la vulnerabilidad de seguridad. Hay una nueva opción en el cuadro de diálogo Opciones para permitir que los usuarios vuelvan al comportamiento anterior.
- **Desactivar el reenvío para una reunión:** impida que los asistentes reenvíen la reunión a otros usuarios. Vaya a la cinta y haga clic en Opciones de respuesta. [Más información](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)
- **Sugerencias de usuarios en el Asistente para programación:** vea recomendaciones de asistentes para agregar al programar una reunión. Ya no es necesario cambiar repetidamente entre el Asistente para programación y la línea Para. [Más información](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)
- **La reserva de una sala es ahora más fácil:** busque una sala de conferencias con más de una lista de salas y cambie de listas sin perder las salas que ha seleccionado.
- **Nuevo valor predeterminado para el intervalo de periodicidad:** para el cuadro de diálogo Periodicidad, el intervalo de periodicidad utilizado de forma predeterminada es "Sin fecha de finalización". Esto facilita la creación de serie periódicas de ejecución prolongada, que pueden dañarse con el tiempo. Vamos a actualizar el valor predeterminado del cuadro de diálogo Periodicidad a "Finalizar el", para que dicho valor coincida con los procedimientos recomendados de calendarios.
- **Unirse a reuniones de Teams desde el cuadro de diálogo Recordatorios de Outlook:** cuando Outlook recuerda a los usuarios que se aproxima una reunión, se mostrará un botón Unirse en línea si la reunión que se aproxima es una reunión en línea de Teams. Esta experiencia es similar a la de unión a una reunión de Skype Empresarial desde el cuadro de diálogo Recordatorios de Outlook.
- **Dejar de ver avisos de eventos anteriores:** puede configurar el calendario para descartar de forma automática los avisos de eventos una vez que hayan finalizado. [Más información](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- **Ver la dirección URL de Vínculos seguros:** los vínculos seguros le protegen de direcciones URL malintencionadas recibidas por correo electrónico, pero ocultan la dirección URL original. Para ver el original, mueva el puntero sobre la dirección URL. Requiere una licencia de Protección contra amenazas avanzada. [Más información](https://products.office.com/exchange/advance-threat-protection)
- **Zoom y quieto**: en lugar de ajustar el Zoom cada vez que lee un mensaje, elija una configuración predeterminada para todos los mensajes. [Más información](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)
- **Cifrado de mensajes: directiva IRM de solo cifrado:** la nueva opción de solo cifrado aparece en Opciones > Menú permisos para los usuarios de cifrado de mensajes de Office 365. Esta opción le permite cifrar un mensaje y enviárselo a cualquier usuario dentro o fuera de su organización.
- **Advertencia cuando está en CCO:** el recuadro CCO le avisará antes de que responda a todos accidentalmente en un correo electrónico en el que está en copia oculta.
- **Una línea Para: más inteligente:** a la hora de redactar un mensaje, al hacer clic en la línea Para: aparecen sugerencias de destinatarios que es probable que elija. Además, puede ver sus imágenes para confirmar que lo esté enviando a la persona adecuada. [Más información](https://support.office.com/article/147208AF-CA8E-4CDF-B71F-77BA81A54069)
- **Capacidad de insertar SVG con filtros aplicados:** ahora, los usuarios de Office tienen la capacidad de insertar SVG con filtros aplicados. [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Compatibilidad mejorada con pantallas de alta definición:** si usa varios monitores o una base de conexión para portátil, las aplicaciones de Office ofrecen ahora una imagen nítida en todas las pantallas, incluso si tienen configuraciones de escala diferentes. [Más información](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="powerpoint-feature-updates"></a>PowerPoint: actualizaciones de características

- **Inicio más rápido** La página de Inicio recién diseñada coloca los documentos abiertos recientemente en el centro y en primer plano. Acceda a archivos con menos clics y abra la Configuración u Opciones de la cuenta desde allí.
- **Escriba sin manos:** ¿tiene un micrófono? Haga clic en Dictar y vea cómo PowerPoint escribe mientras habla.  [Más información](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Los iconos de la cinta tienen un aspecto nuevo:** no se preocupe, todo funciona de la misma forma. Además, tendrán un aspecto excelente en pantallas de todos los tamaños. [Más información](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Compatibilidad mejorada con pantallas de alta definición:** si usa varios monitores o una base de conexión para portátil, las aplicaciones de Office ofrecen ahora una imagen nítida en todas las pantallas, incluso si tienen configuraciones de escala diferentes. [Más información](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Hipervínculos en colores vivos:** los hipervínculos ya no son solo azules. Aplique el color que quiera a la fuente. [Más información](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)
- **Vea cómo las diapositivas cobran vida:** inserte gráficos en 3D animados para ver corazones que laten, planetas en órbita y dinosaurios a toda velocidad por la pantalla. [Más información](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **Retocamos sus bocetos:** convertimos las formas y el texto dibujado a mano en diagramas refinados. Solo tiene que seleccionar los trazos de lápiz para empezar. [Más información](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **Mostrar lo que esconde una imagen:** coloque una imagen en una hoja de cálculo, elija el valor predeterminado y vea cómo cambia la transparencia. [Más información](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Publicar en Microsoft Stream:** comparta una presentación como un vídeo de forma más segura en su organización mediante Microsoft Stream. [Más información](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- **Exportar a 4K:** ahora, la resolución 4K es una opción al exportar una presentación a vídeo.  [Más información](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- **Capacidad de insertar SVG con filtros aplicados:** ahora, los usuarios de Office tienen la capacidad de insertar SVG con filtros aplicados. [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Los archivos de gran tamaño ahora se abren más rápido:** imágenes, vídeos y otros archivos de gran tamaño ahora se descargan en segundo plano al abrir archivos almacenados en OneDrive o SharePoint.

### <a name="word-feature-updates"></a>Word: actualizaciones de características

- **Inicio más rápido** La página de Inicio recién diseñada coloca los documentos abiertos recientemente en el centro y en primer plano. Acceda a archivos con menos clics y abra la Configuración u Opciones de la cuenta desde allí.
- **Escriba sin manos:** ¿tiene un micrófono? Haga clic en Dictar y vea cómo Word escribe mientras habla.  [Más información](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Vea cómo los documentos cobran vida:** inserte gráficos 3D animados para ver corazones que laten, planetas en órbita y dinosaurios a toda velocidad por la página. [Más información](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **Los iconos de la cinta tienen un aspecto nuevo:** no se preocupe, todo funciona de la misma forma. Además, tendrán un aspecto excelente en pantallas de todos los tamaños. [Más información](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Mostrar lo que esconde una imagen:** coloque una imagen en una hoja de cálculo, elija el valor predeterminado y vea cómo cambia la transparencia. [Más información](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Capacidad de insertar SVG con filtros aplicados:** ahora, los usuarios de Office tienen la capacidad de insertar SVG con filtros aplicados. [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Compatibilidad mejorada con pantallas de alta definición:** si usa varios monitores o una base de conexión para portátil, las aplicaciones de Office ofrecen ahora una imagen nítida en todas las pantallas, incluso si tienen configuraciones de escala diferentes. [Más información](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Escriba su currículum vitae con la Ayuda de LinkedIn:** Con el Asistente de currículum, vea experiencias de trabajo, habilidades sugeridas, etc. para un determinado rol. [Obtener más información](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)

### <a name="project-feature-updates"></a>Project: Actualizaciones de características

- **Ver más información en las tarjetas del Panel de tareas:** cuando no se pueda contar la historia solo con el título, personalice las tarjetas del Panel de tareas para mostrar los detalles más importantes. [Más información](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)
- **Office tiene un nuevo aspecto:** ahora las aplicaciones de Office tienen iconos modernos más sencillos y accesibles. Además, la cinta de opciones tiene efectos visuales actualizados que resaltan las características de colaboración disponibles en las aplicaciones de Office.

### <a name="publisher-feature-updates"></a>Publisher: actualizaciones de características

- **Office tiene un nuevo aspecto:** ahora las aplicaciones de Office tienen iconos modernos más sencillos y accesibles. Además, la cinta de opciones tiene efectos visuales actualizados que resaltan las características de colaboración disponibles en las aplicaciones de Office.

### <a name="visio-feature-updates"></a>Visio: actualizaciones de características

- **Disfrute de un momento icónico en el siguiente diagrama:** elija entre 26 galerías de símbolos nuevas con iconos de análisis, arte, celebración, caras, deportes y mucho más.
- **Office tiene un nuevo aspecto:** ahora las aplicaciones de Office tienen iconos modernos más sencillos y accesibles. Además, la cinta de opciones tiene efectos visuales actualizados que resaltan las características de colaboración disponibles en las aplicaciones de Office.

### <a name="office-suite-feature-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de características

- **Ahora, las aplicaciones de terceros de Office son compatibles con la inserción de SVG a través de la API office.js:** las aplicaciones de terceros, también conocidas como complementos de Office, ahora tienen la capacidad de insertar SVG. Ahora los usuarios pueden conectar a Office su colección personal de SVG. Los desarrolladores pueden usar esta característica mediante la API Office.js.
- **Instalación de Microsoft Teams:** Microsoft Teams se instala de forma predeterminada en las instalaciones existentes de Office 365 ProPlus. [Más información](/DeployOffice/teams-install)

### <a name="skype-for-business-feature-updates"></a>Skype Empresarial: actualizaciones de características

- **Compatibilidad mejorada con pantallas de alta definición:** si usa varios monitores o una base de conexión para portátil, las aplicaciones de Office ofrecen ahora una imagen nítida en todas las pantallas, incluso si tienen configuraciones de escala diferentes. [Más información](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="teams-feature-updates"></a>Teams: actualizaciones de características

- **Compatibilidad mejorada con pantallas de alta definición:** si usa varios monitores o una base de conexión para portátil, las aplicaciones de Office ofrecen ahora una imagen nítida en todas las pantallas, incluso si tienen configuraciones de escala diferentes. [Más información](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

## <a name="version-1808-february-12"></a>Versión 1808: 12 de febrero
*Versión 1808 (compilación 10730.20280)* 

### <a name="access-non-security-updates"></a>Access: Actualizaciones no relacionadas con la seguridad 

- Esta actualización agrega compatibilidad con las nuevas eras japonesas en Access.

### <a name="outlook-non-security-updates"></a>Outlook: actualizaciones no relacionadas con la seguridad 

- Soluciona un problema que provocaba que los usuarios con reglas que hacen referencia a una carpeta que ya no existe experimenten un error al intentar administrar reglas y que las reglas del lado cliente no se ejecuten.
- Soluciona un problema que provocaba que los usuarios con buzones delegados en caché sufran bloqueos frecuentes en intervalos imprevisibles.
- Soluciona un problema que causaba que todas las reuniones de día entero aparezcan un día más de lo previsto en algunas vistas debido a que la hora de finalización de la reunión se establece en la medianoche del día siguiente.
- Corregido un bloqueo al crear citas o reuniones que hacen referencia a eras japonesas.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad

- Corregido el problema por el que los complementos implementados con la [implementación centralizada de Office O365](/office/dev/add-ins/publish/centralized-deployment) se bloqueaban y no se podían usar.


## <a name="version-1808-january-8"></a>Versión 1808: 8 de enero
*Versión 1808 (compilación 10730.20264)* 

### <a name="outlook-non-security-updates"></a>Outlook: actualizaciones no relacionadas con la seguridad 

- Se ha corregido un problema por el que se producían errores de sincronización de calendario.

### <a name="word-non-security-updates"></a>Word: actualizaciones no relacionadas con la seguridad

- Mejorar el rendimiento abierto.

## <a name="version-1808-december-11"></a>Versión 1808: 11 de diciembre
*Versión 1808 (compilación 10730.20262)*

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad 

-   [CVE-2018-8597](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8597): Vulnerabilidad de la ejecución remota de código de Microsoft Excel 
-   [CVE-2018-8598](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8598): Vulnerabilidad de divulgación de información de Microsoft Excel 
-   [CVE-2018-8627](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8627): vulnerabilidad de divulgación de información de Microsoft Excel 
-   [CVE-2018-8636](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8636): Vulnerabilidad de la ejecución remota de código de Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad 

-   [CVE-2018-8587](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8587): Vulnerabilidad de la ejecución remota de código de Microsoft Outlook 

### <a name="powerpoint-security-updates"></a>PowerPoint: Actualizaciones de seguridad 

-   [CVE-2018-8628](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8628): Vulnerabilidad de la ejecución remota de código de Microsoft PowerPoint 

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad 

- Corregido un problema en sesiones de co-autoría en el que una segmentación de datos no se actualiza correctamente cuando otro usuario aplica un filtro de columna en los datos de esa segmentación.
- Corregido un problema en una sesión de co-autoría en el que uno de los usuarios borra la descripción de una segmentación y esto provoca que otro usuario de la sesión de co-autoría sufra un bloqueo de Excel.
- Corregido un posible bloqueo al crear varias segmentaciones de tabla enlazadas a la misma columna de datos y, después, eliminar la columna de datos.
- Corregido un problema por el que Excel a veces podía bloquearse al actualizar una tabla de consulta filtrada que contenía texto ajustado en celdas cuando la opción para ajustar automáticamente el ancho de columna estaba desactivada.
- Corregido un problema por el que las segmentaciones guardadas en Excel 2007 pueden desencadenar un bloqueo cuando se abren en versiones más recientes de Excel si cambia el número de elementos que se muestra en la segmentación.
- Introduce la compatibilidad con el botón Obtener diagnósticos para simplificar la investigación de solicitudes de soporte.

### <a name="outlook-non-security-updates"></a>Outlook: actualizaciones no relacionadas con la seguridad

- Se ha corregido un problema por el que a los usuarios les daba un error al iniciar el cuadro de diálogo "Administrar reglas y alertas".
- Corregido un problema que provocaba que los usuarios no pudiesen conectarse a sus buzones a través de DirectAccess al usar una conexión de uso medido.
- Corregido un problema que causaba que los usuarios viesen documentos desprotegidos almacenados en carpetas públicas abrirse de forma errónea en "Vista protegida".
- Corregido un problema que provocaba que los usuarios viesen datos adjuntos inesperados al reenviar elementos con datos adjuntos en línea.
- Corregido un problema que provocaba que los archivos OFT no se representasen correctamente después de enviarlos como datos adjuntos.
- Se ha corregido un problema que provocaba bloqueos cuando algunos usuarios de complementos agregaban una reunión a un calendario compartido.
- Se ha corregido un problema por el que el programa dejaba de responder al abrir la carpeta Historial de conversaciones.

### <a name="project-non-security-updates"></a>Project: Actualizaciones no relacionadas con la seguridad

- Corregido un problema con la compatibilidad de la nueva moneda venezolana en Project.
- Corregido un problema por el que Project podía bloquearse al usar un Surface 4 que estuviese conectado a un monitor externo.
- Corregido un problema por el que Project podía bloquearse al guardar el proyecto en formato XML.
- Corregido un problema por el que los campos personalizados de recurso de empresa podían eliminarse después de editar el calendario de un recurso.
- Corregido un problema que provocaba que los usuarios experimentasen bloqueos al buscar nombres coreanos para mostrar.

## <a name="version-1808-november-13"></a>Versión 1808: 13 de noviembre
*Versión 1808 (compilación 10730.20205)*

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad

-   [CVE-2018-8574](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8574): vulnerabilidad de la ejecución remota de código de Microsoft Excel 
-   [CVE-2018-8577](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8577): vulnerabilidad de la ejecución remota de código de Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: actualizaciones de seguridad 

-   [CVE-2018-8522](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8522): vulnerabilidad de la ejecución remota de código de Microsoft Outlook 
-   [CVE-2018-8524](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8524): vulnerabilidad de la ejecución remota de código de Microsoft Outlook 
-   [CVE-2018-8558](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8558): vulnerabilidad de divulgación de información de Microsoft Office Outlook 
-   [CVE-2018-8576](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8576): vulnerabilidad de la ejecución remota de código de Microsoft Outlook 
-   [CVE-2018-8579](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8579): vulnerabilidad de divulgación de información de Microsoft Office Outlook 
-   [CVE-2018-8582](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8582): vulnerabilidad de la ejecución remota de código de Microsoft Outlook 

### <a name="project-security-updates"></a>Project: actualizaciones de seguridad 

-   [CVE-2018-8575](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8575): vulnerabilidad de la ejecución remota de código de Microsoft Excel 

### <a name="word-security-updates"></a>Word: actualizaciones de seguridad 

-   [CVE-2018-8573](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8573): vulnerabilidad de la ejecución remota de código de Microsoft Word 

### <a name="skype-for-business-security-updates"></a>Skype Empresarial: actualizaciones de seguridad 

-   [CVE-2018-8546](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8546): vulnerabilidad de la denegación de servicio de Microsoft Skype Empresarial 

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad 

- Corregido un error por el que Power Pivot no aparecía en algunas versiones o compilaciones.

### <a name="outlook-non-security-updates"></a>Outlook: actualizaciones no relacionadas con la seguridad 

- Corregido un problema que provocaba que los usuarios no pudieran usar correctamente el botón Control de cuentas para cambiar entre cuentas en formularios personalizados.
- Corregido un problema que provocaba que los usuarios tuviesen un bloqueo al utilizar ScanPST para reparar un archivo PST u OST.
- Corregido un problema que causaba que el campo CC: de determinados mensajes de correo no se mostrase a usuarios con perfiles de modo con conexión.

### <a name="onenote-non-security-updates"></a>OneNote: actualizaciones no relacionadas con la seguridad 

- Corregido un problema de estabilidad que podía producirse en relación con la sincronización y la navegación a una sección eliminada.

### <a name="project-non-security-updates"></a>Project: actualizaciones no relacionadas con la seguridad 

- Corregido un problema por el que, si estaba trabajando con archivos de Project en una biblioteca de documentos de SharePoint que estaba en la nueva experiencia moderna, las acciones de desprotección necesaria y solo lectura no se seguían correctamente.


## <a name="version-1808-october-9"></a>Versión 1808: 9 de octubre
*Versión 1808 (compilación 10730.20155)*

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2018-8502](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8502): Vulnerabilidad de la ejecución remota de código de Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad 
-   [ADV180026](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/ADV180026): Actualización de defensa en profundidad de Microsoft Office 

### <a name="powerpoint-security-updates"></a>PowerPoint: Actualizaciones de seguridad 
-   [CVE-2018-8501](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8501): Vulnerabilidad de la ejecución remota de código de Microsoft PowerPoint

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad 
-   [CVE-2018-8504](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8504): Vulnerabilidad de la ejecución remota de código de Microsoft Word 
-   [ADV180026](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/ADV180026): Actualización de defensa en profundidad de Microsoft Office 

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad 
-   [CVE-2018-8432](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8432): vulnerabilidad de la ejecución remota de código de componentes de gráficos de Microsoft 

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad 
-   Corregido un problema por el que los símbolos del rango entre 2190 y 2194 se cambian a Cambria Math. Esto causa que el alto de la celda de Excel aumente 3 veces.
-   Esto corrige el problema por el que Excel puede dejar de responder cuando el usuario desplaza el ratón sobre las opciones de formato en un libro con muchos nombres definidos y por el que Excel puede dejar de responder en la herramienta de análisis rápido incluso cuando la vista previa dinámica se ha deshabilitado en Opciones.
-   Estamos investigando el rendimiento lento al mover la ventana de la aplicación de Excel de un escritorio a otro. Mientras tanto, si observa esta lentitud, una solución alternativa que puede considerar es seleccionar "Optimizar para la compatibilidad" para "Al usar varias pantallas" en la pestaña "General" en el cuadro de diálogo Opciones de archivo.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: actualizaciones no relacionadas con la seguridad
-   Corregido un problema de posibles daños en el archivo al guardar los archivos con contenido ActiveX.

### <a name="word-non-security-updates"></a>Word: actualizaciones no relacionadas con la seguridad
-   Corregido un problema por el que al insertar un objeto de documento de Word, aparecía el editor de ecuaciones.

### <a name="project-non-security-updates"></a>Project: actualizaciones no relacionadas con la seguridad
-   Corregido un problema por el que si establecía un encabezado o pie de página para una impresión, el cambio no se mantenía la próxima vez que se imprimía el proyecto.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema por el que las aplicaciones mostraban animaciones a pesar de haber desactivado las animaciones mediante la configuración de accesibilidad y rendimiento. 
-   Se ha corregido un problema por el que el fondo se volvía negro al usar la herramienta de dibujo de resaltado.

## <a name="version-1808-september-11"></a>Versión 1808: 11 de septiembre
*Versión 1808 (compilación 10730.20102)*

### <a name="access-feature-updates"></a>Access: actualizaciones de características
 - **Visualizar datos con nuevos gráficos:** elija entre 11 gráficos y agregue uno a los formularios e informes para visualizar mejor los datos y tomar decisiones fundamentadas. [Más información](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)
 
 ### <a name="access-security-updates"></a>Access: actualizaciones de seguridad
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8312): vulnerabilidad de uso posterior gratis de la ejecución de código remoto de Microsoft Access

### <a name="excel-feature-updates"></a>Excel: Actualizaciones de características
 - **Edición colaborativa:** Trabajar con otras personas al mismo tiempo en el libro. [Más información](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)
 - **El autoguardado para archivos de nube ahora está habilitado de forma predeterminada:** el autoguardado está habilitado de forma predeterminada en la versión del canal semianual (dirigido) de septiembre de 2018. Este cambio significa que los usuarios no tendrán que preocuparse por perder los cambios en los documentos almacenados en OneDrive o SharePoint Online. Los cambios se guardarán en la nube automáticamente y los usuarios no tendrán que presionar explícitamente Ctrl + S o el botón Guardar. Sin embargo, tendrán que comprender este cambio de comportamiento para que no realicen cambios accidentales en documentos. Tenga en cuenta que los usuarios pueden desactivar el autoguardado con el botón de autoguardado en la parte superior de la pantalla. Le recomendamos que notifique a los usuarios sobre este nuevo cambio y les instruya acerca de cómo aprovechar mejor esta nueva característica de Office 365. [Más información sobre el autoguardado](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Más información sobre lo que los administradores de TI deben saber sobre el autoguardado](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Edición de la barra de fórmulas y las celdas mejorada:** ahora, puede usar CTRL + A para seleccionar el texto de una celda o de la barra de fórmulas. También se ha mejorado la compatibilidad con los emojis y otros caracteres complejos. [Más información](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
- **Mejoras del Comprobador de accesibilidad:** el Comprobador de accesibilidad ha actualizado la asistencia técnica para las normas internacionales y recomendaciones para que los libros sean más accesibles. [Más información](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **Evitar cambios no deseados:** establezca los libros para abrir como solo lectura para evitar cambios accidentales. Vaya a archivo > información > proteger libro > abrir siempre como solo lectura

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2018-8331](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8331): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8429](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8429): vulnerabilidad de divulgación de información de Microsoft Excel
-   [CVE-2018-8375](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8375): vulnerabilidad de la ejecución remota de código de Microsoft Excel 
-   [CVE-2018-8379](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8379): Vulnerabilidad de la ejecución remota de código de Microsoft Excel 
-   [CVE-2018-8382](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8382): vulnerabilidad de divulgación de información de Microsoft Excel
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8246): vulnerabilidad de divulgación de información de Microsoft Excel
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8248): vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8147): vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8148): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8162): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8163): vulnerabilidad de divulgación de información de Microsoft Excel
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-1029): vulnerabilidad de la ejecución remota de código de Microsoft Excel

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
-   Corregido un problema por el que Excel podía bloquearse al cambiar el origen de datos de un gráfico de su conjunto de celdas original.
-   Corregido un problema por el que la actualización podría fallar al abrir incluso si se establecía la propiedad FullCalcOnLoad.  
-   Se ha corregido un problema donde se mostraba el año incorrecto cuando se usaba el calendario japonés Era con formato de celda de fecha.
-   Al importar datos en el modelo de datos de Excel, los valores entrantes de cero negativo crearían un error. La corrección importa esos valores como cero.
-   Se corrige un problema que en ocasiones podía desencadenar un bloqueo en una operación de agrupación (o desagrupación) en una tabla dinámica de Excel.
-   Se ha corregido un problema por el que Excel se bloqueaba al realizar acciones de gráficos.
-   Se soluciona un problema por el que el complemento de Power View se deshabilita involuntariamente para algunos usuarios.
-   Se soluciona un problema por el que los archivos de recuperación automática temporales que se crean durante la recuperación de documentos no se limpian nunca.
-   Se soluciona un problema por el que, al intentar establecer una conexión nueva con un archivo de texto en un libro protegido, se recibe el mensaje de error "El libro está protegido y no se puede modificar".
-   Se ha corregido un problema por el que no se podía imprimir impresión rápida de un libro de Excel adjuntado a un correo electrónico de Outlook.
-   Se ha corregido un problema por el que al hacer clic en un hipervínculo, puede hacer que Excel se bloquee.
-   Se ha corregido un problema por el que al usar las funciones de cubo, Excel se bloquea.

### <a name="outlook-feature-updates"></a>Outlook: actualizaciones de características
 - **Mejoras del Comprobador de accesibilidad:** el Comprobador de accesibilidad ha actualizado la asistencia técnica para las normas internacionales y recomendaciones para que los mensajes sean más accesibles. [Más información](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
 - **Administrar perfiles desde el selector de perfil:** si usa el selector de perfil cuando se inicia Outlook, ahora puede realizar cambios sin usar el panel de control. Cree y elimine perfiles o cambie la configuración, todo desde el selector de perfil.
- **Accesibilidad integrada:** haga que su mensajes sean accesibles para todos los usuarios agregando texto alternativo descriptivo a las imágenes.
- **Advertencias de complemento de Outlook:** ocasionalmente un complemento COM de Outlook puede encontrar problemas que ralenticen los demás componentes de Outlook. Estos problemas podrían ser por causas de latencia de eventos, como cambiar entre carpetas de Outlook. la llegada de correo electrónico nuevo, la apertura de elementos de calendario, etc. Cuando se producen, se mostrará una advertencia en la barra de notificaciones de Outlook.
- **Saber quién se reunirá con usted:** a partir de ahora, podrá ver las respuestas de otros usuarios a las convocatorias de reunión aunque no sea el organizador.
- **Nunca pierda un aviso:** establezca avisos para que aparezcan elementos emergentes en las ventanas mientras está trabajando. En caso contrario, Outlook parpadeará en la barra de tareas para llamar su atención. [Más información](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- **Marcar los elementos eliminados como leído:** ahora puede establecer como leídos los mensajes que elimine. Para hacerlo, vaya a Archivo \> Opciones \> Correo \> Otros.
- **Ver tres zonas horarias:** ¿necesita programar una reunión en distintas zonas horarias? Agregue varias zonas horarias al calendario para ver la disponibilidad de todos los usuarios fácilmente y seleccione una hora adecuada para todos. [Más información](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)
- **Mejora de la experiencia del usuario para crear un grupo:** hemos perfeccionado la experiencia del usuario para crear grupos para darle un aspecto más moderno y ordenado.[ Más información](https://support.office.com/article/04d0c9cf-6864-423c-a380-4fa858f27102)

### <a name="outlook-security-updates"></a>Outlook: actualizaciones de seguridad
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8310): vulnerabilidad de manipulación de Microsoft Office
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8244): vulnerabilidad de elevación de privilegios de Microsoft Outlook
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8150): vulnerabilidad de omisión de característica de seguridad de Microsoft Outlook
-   [ADV180021](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/ADV180021): actualización de defensa en profundidad de Microsoft Office

### <a name="outlook-non-security-updates"></a>Outlook: actualizaciones no relacionadas con la seguridad
-   Corregido un problema por el que si cambiaba el idioma a japonés e intentaba escribir caracteres japoneses en VBA IDE cuando estuviese cargado en Outlook, se bloqueaba.
-   Se ha corregido un problema por el que Outlook se bloqueaba al cambiar a la carpeta Elementos enviados o la Bandeja de salida.
-   Se soluciona un problema por el que todos los asistentes recibían actualizaciones de la reunión cuando cambiaban el cuerpo de la reunión o los datos adjuntos, en lugar de que fuese opcional que se enviase una actualización de la reunión a los asistentes.
-   Se soluciona un problema por el que los usuarios no podían conectarse a los extremos REST y EWS debido a un cambio en la cadena de agente de usuario.
-   Se ha corregido un problema por el que una actualización de la ubicación de la reunión para los asistentes muestra la ubicación anterior en lugar de la nueva.
-   Se ha corregido un problema por el que el usuario ve un error al obtener una vista previa de los datos adjuntos en el panel de lectura.
-   Se ha corregido un problema por el que Outlook se bloquea al resolver nombres para mostrar en direcciones de correo electrónico cuando el usuario está redactando un correo electrónico.
-   Se ha corregido un problema por el que algunos usuarios no reciben características de soporte técnico que ha habilitado su administrador de espacio empresarial.

### <a name="powerpoint-feature-updates"></a>PowerPoint: actualizaciones de características 
- **El autoguardado para archivos de nube ahora está habilitado de forma predeterminada:** el autoguardado está habilitado de forma predeterminada en la versión del canal semianual (dirigido) de septiembre de 2018. Este cambio significa que los usuarios no tendrán que preocuparse por perder los cambios en los documentos almacenados en OneDrive o SharePoint Online. Los cambios se guardarán en la nube automáticamente y los usuarios no tendrán que presionar explícitamente Ctrl + S o el botón Guardar. Sin embargo, tendrán que comprender este cambio de comportamiento para que no realicen cambios accidentales en presentaciones. Tenga en cuenta que los usuarios pueden desactivar el autoguardado con el botón de autoguardado en la parte superior de la pantalla. Le recomendamos que notifique a los usuarios sobre este nuevo cambio y les instruya acerca de cómo aprovechar mejor esta nueva característica de Office 365. [Más información sobre el autoguardado](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Más información sobre lo que los administradores de TI deben saber sobre el autoguardado](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Convertir la entrada de lápiz:** dibuje y tome notas con garabatos y conviértalos en texto legible y formas nítidas para crear una presentación elegante. [Más información](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)
- **Compatibilidad con el formato SVG mejorada:** puede insertar imágenes SVG que tengan filtros aplicados. [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Escritura del título de las diapositivas con un lápiz:** use el lápiz para escribir un título y PowerPoint lo convertirá en texto. [Más información](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **Evitar cambios no deseados:** establezca los libros para abrir como solo lectura para evitar cambios accidentales. Vaya a archivo > información > proteger libro > abrir siempre como solo lectura
- **Mejoras del Comprobador de accesibilidad:** el Comprobador de accesibilidad ha actualizado la asistencia técnica para las normas internacionales y recomendaciones para que las presentaciones sean más accesibles. [Más información](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)

### <a name="powerpoint-non-security-updates"></a>PowerPoint: actualizaciones no relacionadas con la seguridad
-   Se ha corregido el problema en el que las tablas se representaban incorrectamente con un borde grueso.
-   Se corrige un problema que podía producir un posible bloqueo al cambiar la propiedad Shape.Visibile.
-   Se corrige un problema por el que no podían combinarse los cambios efectuados en documentos en coautoría.
-   Se corrige un problema por el que no se realizaba la coautoría en documentos que contenían controles ActiveX.
-   Se ha corregido un problema por el que PowerPoint se bloqueaba al pasar el corrector ortográfico en formas.
-   Se ha corregido un problema por el que PowerPoint se bloqueaba al abrir un archivo de SharePoint Online.
-   Se soluciona un problema por el que el Panel de recuperación aparecía incorrectamente cuando Autoguardado está activado.
-   Se soluciona un problema por el que Iniciar sesión no se mostraba, lo que impedía que un usuario accediese a un archivo.
-   Se soluciona un problema que provocaba que, cuando había varios usuarios trabajando en coautoría en la misma presentación, se duplicaran de forma incorrecta los patrones de diapositivas.
-   Se soluciona un problema que provocaba que, al abrir un archivo guardado en OneDrive, se bloqueara PowerPoint al salir de la Vista protegida.

### <a name="project-feature-updates"></a>Project: actualizaciones de características 
- **Administración de sprint:** agregue, actualice o elimine sprints ágiles rápidamente.
- **Filtrado del panel de tareas:** simplifique los paneles de tareas filtrando las tareas de resumen o de recursos clave.
- **Establecer el porcentaje completado de un panel de tareas:** elija un porcentaje completado de cada columna y después actualice la finalización de tareas con arrastrar y colocar.
- **Navegación sprint:** cambie de una vista de sprint a otra y desplácese rápidamente tareas entre sprints.
- **Una nueva forma de administrar sprints:** tomar un enfoque ágil para trabajar con paneles de tareas. Vaya a administrar Sprints para agregar y quitar sprints a medida que evoluciona el proyecto.
- **Todo organizado con Ubicaciones de almacenamiento recientes:** Project mantiene una lista actualizada de las ubicaciones en las que ha guardado otros proyectos. Cuando quiera guardar su proyecto, simplemente elija una de sus ubicaciones de almacenamiento recientes y continúe con su día.

### <a name="project-non-security-updates"></a>Actualizaciones de Project no relacionadas con la seguridad
- Se corrige un problema que impedía guardar un subproyecto al trabajar en él en el contexto de un proyecto principal.

### <a name="skype-for-business-non-security-updates"></a>Skype Empresarial: actualizaciones no relacionadas con la seguridad
-   Corregido un problema relacionado con la compatibilidad del protocolo TLS 1.2. (Nota: esta es la misma solución que se mencionó en las notas del 10 de abril y aquí se menciona otra vez como parte del resumen de septiembre.)
-   Se ha corregido un problema que se producía al agregar usuarios seleccionando “Llamada de Skype” en una reunión.
-   Se quita el mensaje en el que se le pregunta al usuario si quiere incluir coordenadas de Skype en una reunión al agregar una sala de Skype como ubicación cuando la reunión ya contiene las coordenadas de la reunión de Teams.
-   Se corrige un problema que provocaba que se rellenara la ubicación, incluso cuando el valor de UseLocationForE911Only era verdadero.
-   Se soluciona un problema por el que Skype Empresarial dejaba de responder al usar la opción “Llamar con el centro de conferencia” para invitar a usuarios de la lista.
-   Se soluciona un problema por el que, al ejecutar Outlook en Terminal Server, el programa se bloqueaba al crear una reunión de Skype Empresarial.
-   Se cambia el valor predeterminado de EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket a VERDADERO.

### <a name="visio-feature-updates"></a>Visio: actualizaciones de características
- **Tener sincronizados los diagramas y los orígenes:** Al editar un diagrama del Visualizador de datos en Visio, tiene la opción de actualizar los datos de origen de Excel vinculados con el contenido más reciente de un diagrama.
- **Plantilla de auditoría del Visualizador de datos:** importe contenido de Excel y cree diagramas de auditoría para las transacciones financieras, la administración de inventarios y mucho más.
- **Diagramas iniciales:** las plantillas organigrama, lluvia de ideas y SDL tienen nuevos diagramas iniciales que le ayudarán a empezar a trabajar rápidamente.
 - **Crear un documento de Word a partir de formas de Visio:** agregue automáticamente contenido de diagramas, incluidas formas y metadatos, a un documento de Word. Después, personalice el documento para crear instrucciones de procesos y manuales de operaciones. [Más información](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

### <a name="word-feature-updates"></a>Word: actualizaciones de características
- **El autoguardado para archivos de nube ahora está habilitado de forma predeterminada:** el autoguardado está habilitado de forma predeterminada en la versión del canal semianual (dirigido) de septiembre de 2018. Este cambio significa que los usuarios no tendrán que preocuparse por perder los cambios en los documentos almacenados en OneDrive o SharePoint Online. Los cambios se guardarán en la nube automáticamente y los usuarios no tendrán que presionar explícitamente Ctrl + S o el botón Guardar. Sin embargo, tendrán que comprender este cambio de comportamiento para que no realicen cambios accidentales en presentaciones. Tenga en cuenta que los usuarios pueden desactivar el autoguardado con el botón de autoguardado en la parte superior de la pantalla. Le recomendamos que notifique a los usuarios sobre este nuevo cambio y les instruya acerca de cómo aprovechar mejor esta nueva característica de Office 365. [Más información sobre el autoguardado](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Más información sobre lo que los administradores de TI deben saber sobre el autoguardado]
- **Mejoras del Comprobador de accesibilidad:** el Comprobador de accesibilidad ha actualizado la asistencia técnica para las normas internacionales y recomendaciones para que los documentos sean más accesibles. [Más información](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **Compatibilidad con el formato SVG mejorada:** puede insertar imágenes SVG que tengan filtros aplicados. [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="word-security-updates"></a>Word: actualizaciones de seguridad
-   [CVE-2018-8430](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8430): vulnerabilidad de la ejecución remota de código de PDF de Word
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0919): vulnerabilidad de divulgación de información de Microsoft Office

### <a name="word-non-security-updates"></a>Word: actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema que provocaba que apareciera un mensaje de memoria insuficiente.
-   Se ha corregido un conjunto de errores que evitaban que algunos usuarios pudiesen abrir documentos y correos electrónicos protegidos mediante IRM compartidos con ellos por gente de otras organizaciones.
-   Se han corregido algunos problemas de rendimiento.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de seguridad
-   [CVE-2018-8332](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8332): vulnerabilidad de la ejecución remota de código de gráficos de Win32k
-   [CVE-2018-8378](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8378): vulnerabilidad de divulgación de información de Microsoft Office
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8281): vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8157): vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8158): vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0950): vulnerabilidad de divulgación de información de Microsoft Office
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-1026): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-1030): vulnerabilidad de la ejecución remota de código de Microsoft Office
-   
  **Bloqueo de la activación de controles de Flash, Silverlight y Shockwave en Office por motivos de seguridad:** por motivos de seguridad, las nuevas compilaciones de Microsoft Office para Office 365 en Windows bloquean la activación de controles de Silverlight, Flash y Shockwave. Más información[aquí](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729) y [aquí](https://support.office.com/en-us/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1?ui=en-US&rs=en-US&ad=US)

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones no relacionadas con la seguridad
-  Se ha corregido un problema que causaba que la instalación de la actualización tardase mucho tiempo en determinados escenarios.
-  Se ha corregido un problema que provocaba que, al abrir una aplicación, el usuario viera un mensaje sobre iniciar en modo seguro y después la aplicación no se abriera.
-  Se han corregido algunos problemas de rendimiento.

## <a name="version-1803-august-14"></a>Versión 1803: 14 de agosto
*Versión 1803 (compilación 9126.2275)*

### <a name="access-security-updates"></a>Access: actualizaciones de seguridad
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8312): vulnerabilidad de uso posterior gratis de la ejecución de código remoto de Microsoft Access

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2018-8375](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8375): Vulnerabilidad de la ejecución remota de código de Microsoft Excel 
-   [CVE-2018-8379](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8379): Vulnerabilidad de la ejecución remota de código de Microsoft Excel 
-   [CVE-2018-8382](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8382): Vulnerabilidad de divulgación de información de Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [ADV180021](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/ADV180021): Actualización de defensa en profundidad de Microsoft Office 

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2018-8378](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8378): vulnerabilidad de divulgación de información de Microsoft Office 

## <a name="version-1803-july-10"></a>Versión 1803: 10 de julio
*Version 1803 (compilación 9126.2259)*

### <a name="access-security-updates"></a>Access: Actualizaciones de seguridad
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8312): vulnerabilidad de uso posterior gratis de la ejecución de código remoto de Microsoft Access

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8310): vulnerabilidad de manipulación de Microsoft Office

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8281): vulnerabilidad de la ejecución remota de código de Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema donde se mostraba el año incorrecto cuando se usaba el calendario japonés Era con formato de celda de fecha.
-   Al importar datos en el modelo de datos de Excel, los valores entrantes de cero negativo crearían un error. La corrección importa esos valores como cero.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido el problema en el que las tablas se representaban incorrectamente con un borde grueso.

### <a name="project-non-security-updates"></a>Project: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema en el que si se dividía una tarea con un recurso de costo, el recurso de costo no se actualiza correctamente y se perdía el costo.
-   Se ha corregido un problema por el que solo se mostraban las tareas de la primera tarea de resumen en la vista Escala de tiempo del cuadro de diálogo Agregar tareas existentes a la escala de tiempo.
-   Se ha corregido un problema por el que podía fallar Guardar como XML para proyectos principales de Project Online o Project Server.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un error que causaba que la instalación de la actualización a tardase mucho tiempo en determinados escenarios. 
-   Se ha corregido un problema en el que estaban fallando las pruebas SVG
-   Se corrige un problema por el que, al implementar actualizaciones con Configuration Manager en un cliente que tiene aplicaciones de Office en ejecución, la actualización no se aplica después de reiniciar el dispositivo mientras se ejecutan las aplicaciones de Office.


## <a name="version-1803-june-12"></a>Versión 1803: 12 de junio
*Versión 1803 (compilación 9126.2227)*

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8246): Vulnerabilidad de divulgación de información de Microsoft Excel
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8248): Vulnerabilidad de la ejecución remota de código de Microsoft Excel

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
-   Se corrige un problema que en ocasiones podía desencadenar un bloqueo en una operación de agrupación (o desagrupación) en una tabla dinámica de Excel.

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8244): Vulnerabilidad de elevación de privilegios de Microsoft Outlook

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones no relacionadas con la seguridad
-   Se corrige un problema que podía producir un posible bloqueo al cambiar la propiedad Shape.Visibile.
-   Se corrige un problema por el que no podían combinarse los cambios efectuados en documentos en coautoría.
-   Se corrige un problema por el que no se realizaba la coautoría en documentos que contenían controles ActiveX.

### <a name="project-non-security-updates"></a>Project: Actualizaciones no relacionadas con la seguridad
-   Se corrige un problema por el que solo se mostraban las tareas de la primera tarea de resumen en la vista Escala de tiempo del cuadro de diálogo Agregar tareas existentes a la escala de tiempo.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad
-   Se corrige un problema por el que, al implementar actualizaciones con Configuration Manager en un cliente que tiene aplicaciones de Office en ejecución, la actualización no se aplica después de reiniciar el dispositivo mientras se ejecutan las aplicaciones de Office.



## <a name="version-1803-may-18"></a>Versión 1803: 18 de mayo
*Versión 1803 (compilación 9126.2210)*

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
- Se ha corregido un problema por el que Excel se bloqueaba al realizar acciones de gráficos.
- Se soluciona un problema por el que el complemento de Power View se deshabilita involuntariamente para algunos usuarios.
- Se soluciona un problema por el que los archivos de recuperación automática temporales que se crean durante la recuperación de documentos no se limpian nunca.
- Se soluciona un problema por el que, al intentar establecer una conexión nueva con un archivo de texto en un libro protegido, se recibe el mensaje de error "El libro está protegido y no se puede modificar".

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones no relacionadas con la seguridad
- Se ha corregido un problema por el que PowerPoint se bloqueaba al pasar el corrector ortográfico en formas.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad
- Se ha corregido un problema que provocaba que, al abrir una aplicación, el usuario viera un mensaje sobre iniciar en modo seguro y después la aplicación no se abriera.



## <a name="version-1803-may-8"></a>Versión 1803: 8 de mayo
*Versión 1803 (compilación 9126.2191)*

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8147): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8148): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8162): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8163): Vulnerabilidad de divulgación de información de Microsoft Excel

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema por el que Excel se bloqueaba al abrir un archivo de SharePoint Online.
-   Se soluciona un problema por el que Imprimir o la Vista previa de impresión solo imprime o muestra una parte de la hoja de cálculo, con el contenido truncado a una segmentación en la hoja de cálculo.

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8150): Vulnerabilidad de omisión de característica de seguridad de Microsoft Outlook

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema por el que Outlook se bloqueaba al cambiar a la carpeta Elementos enviados o la Bandeja de salida.
-   Se soluciona un problema por el que todos los asistentes recibían actualizaciones de la reunión cuando cambiaban el cuerpo de la reunión o los datos adjuntos, en lugar de que fuese opcional que se enviase una actualización de la reunión a los asistentes.
-   Se soluciona un problema por el que los usuarios no podían conectarse a los extremos REST y EWS debido a un cambio en la cadena de agente de usuario.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema por el que PowerPoint se bloqueaba al abrir un archivo de SharePoint Online.
-   Se soluciona un problema por el que el Panel de recuperación aparecía incorrectamente cuando Autoguardado está activado.
-   Se soluciona un problema por el que Iniciar sesión no se mostraba, lo que impedía que un usuario accediese a un archivo.

### <a name="project-non-security-updates"></a>Project: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema por el que al usar el menú desplegable Filtro automático en una columna de fecha se ocultaban todas las tareas del proyecto.
-   Se soluciona un problema por el que solo se mostraban las tareas de la primera tarea de resumen en el cuadro de diálogo al agregar tareas existentes a una escala de tiempo en la vista Escala de tiempo.

### <a name="word-non-security-updates"></a>Word: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema por el que Word se bloqueaba al abrir un archivo de SharePoint Online.
-   Se soluciona un problema por el que los números de página en número romanos en minúscula se cambian incorrectamente a mayúsculas.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8157): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-8158): Vulnerabilidad de la ejecución remota de código de Microsoft Office



## <a name="version-1803-april-10"></a>Versión 1803: 10 de abril
*Versión 1803 (compilación 9126.2152)*

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-1029): Vulnerabilidad de la ejecución remota de código de Microsoft Excel

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema que provocaba que, cuando había varios usuarios trabajando en coautoría en la misma presentación, se duplicaran de forma incorrecta los patrones de diapositivas.
-   Se soluciona un problema que provocaba que, al abrir un archivo guardado en OneDrive, se bloqueara PowerPoint al salir de la Vista protegida.

### <a name="skype-for-business-non-security-updates"></a>Skype Empresarial: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema relacionado con la compatibilidad del protocolo TLS 1.2.

### <a name="word-non-security-updates"></a>Word: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema que provocaba que apareciera un mensaje de memoria insuficiente.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0950): Vulnerabilidad de divulgación de información de Microsoft Office
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-1026): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-1030): Vulnerabilidad de la ejecución remota de código de Microsoft Office



## <a name="version-1803-march-20"></a>Versión 1803: 20 de marzo
*Versión 1803 (compilación 9126.2098)*

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema por el que no se podía imprimir impresión rápida de un libro de Excel adjuntado a un correo electrónico de Outlook.
-   Se ha corregido un problema por el que al hacer clic en un hipervínculo, puede hacer que Excel se bloquee.
-   Se ha corregido un problema por el que al usar las funciones de cubo, Excel se bloquea.

### <a name="onedrive-for-business-non-security-updates"></a>OneDrive para la Empresa: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema por el que OneDrive para la Empresa (Groove.exe) consume un núcleo de la CPU válido de CPU (por ejemplo, 25 % en una CPU de 4 núcleos) en el Administrador de tareas para ampliar los períodos de tiempo.

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema por el que una actualización de la ubicación de la reunión para los asistentes muestra la ubicación anterior en lugar de la nueva.
-   Se ha corregido un problema por el que el usuario ve un error al obtener una vista previa de los datos adjuntos en el panel de lectura.
-   Se ha corregido un problema por el que Outlook se bloquea al resolver nombres para mostrar en direcciones de correo electrónico cuando el usuario está redactando un correo electrónico.
-   Se ha corregido un problema por el que algunos usuarios no reciben características de soporte técnico que ha habilitado su administrador de espacio empresarial.

### <a name="word-non-security-updates"></a>Word: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema por el que Word no se abre en un equipo con Windows 7 que no tiene la [actualización de la experiencia del cliente y la telemetría de diagnóstico](https://support.microsoft.com/help/3080149/update-for-customer-experience-and-diagnostic-telemetry) instalada.
-   Se ha corregido un problema por el que no se imprimen las viñetas de listas.



## <a name="version-1803-march-13"></a>Versión 1803: 13 de marzo
*Versión 1803 (compilación 9126.2072)*

### <a name="access-security-updates"></a>Access: Actualizaciones de seguridad
-   [CVE-2018-0903](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0903): Vulnerabilidad de la ejecución remota de código de Microsoft Access

### <a name="access-non-security-updates"></a>Access: Actualizaciones no relacionadas con la seguridad
-   Se ha solucionado un problema que provocaba que, al abrir una aplicación de Access Runtime (archivo .accde), apareciese el mensaje de error "No se puede reconocer el formato de la base de datos" y que no se abriese la aplicación.
-   Se ha solucionado un problema que provocaba que pareciera que se seleccionaba todo el texto al intentar seleccionar texto en un cuadro de texto o en un cuadro combinado, en lugar de mostrarse la selección real.

### <a name="excel-feature-updates"></a>Excel: Actualizaciones de características
-   **Microsoft Translator:** Traduzca palabras, frases u oraciones a otro idioma con Microsoft Translator. You Puede hacerlo desde la pestaña Revisar de la cinta de opciones.
-   **Convertir iconos SVG en formas:** transforme todas las imágenes e iconos SVG en formas de Office para poder cambiar su color, tamaño o textura.
-   **Anular la selección de celdas:** Realice selecciones en la hoja de cálculo y anule la selección de las celdas donde hizo clic por error sin tener que volver a empezar.
-   **Acceder rápidamente a los sitios y a los grupos:** Use el menú Archivo para trabajar con los documentos almacenados en los sitios y grupos que usa a menudo.
-   **Lápiz digital:** escriba o dibuje ideas con nuestra nueva textura de lápiz. Simplemente inclínelo para aplicar sombreado con lápices digitales compatibles.
-   **Configuración de características de LinkedIn:** vaya a Archivo \> Opciones \> General para controlar si se muestran las características de LinkedIn en las aplicaciones de Office. [Más información](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **Modelos 3D:** Use modelos 3D para aumentar el impacto visual y creativo de los libros.  Inserte fácilmente un modelo 3D y, después, podrá girarlo 360 grados. [Obtener más información](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **Nuevos efectos de lápiz:** exprese sus ideas con estilo con lápices metálicos y efectos de lápiz, como arcoíris, galaxia, lava, océano, oro, plata y más.
-   **Interfaz de usuario para compartir archivos:** en el caso de los archivos de OneDrive para la Empresa o SharePoint, haga clic en el botón Compartir que encontrará en la esquina superior derecha de la cinta de opciones o en Archivo \> Compartir. Aparecerá un cuadro de diálogo Compartir simplificado y mejorado. Para los archivos nuevos o guardados de forma local, la interfaz de usuario permite cargar los archivos fácilmente en OneDrive y empezar a colaborar.
-   **Bloquear extensiones peligrosas:** de forma predeterminada, se bloquea la activación de las extensiones consideradas de riesgo elevado y que se insertan como objetos de paquete OLE. Por ejemplo, .exe, .vbs y .js. [Más información](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **Sonidos útiles mejoran la accesibilidad:** active las indicaciones de audio para guiarse mientras trabaja. Las encontrará en Archivo \> Opciones \> Accesibilidad. No se necesita ningún complemento. [Más información](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **Ubicaciones de archivo por cuenta:** al abrir o guardar un archivo, la lista de ubicaciones se organiza en función de la cuenta asociada.
-   **Personalización del lápiz:** elija un conjunto personal de lápices y marcadores de resaltado para las entradas manuscritas. Su conjunto personalizado estará disponible en todos sus equipos PC Windows.

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2017-11877](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2017-11877): Vulnerabilidad de omisión de característica de seguridad de Microsoft Excel
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2017-11878): Vulnerabilidad de los daños en la memoria de Microsoft Excel
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2017-11884): vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0796): vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0841): vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0907): Omisión de característica de seguridad de Microsoft Office Excel
-   [Advertencia 170021](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/ADV170021): Actualización de defensa en profundidad de Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
-   Se ha solucionado un problema que provocaba que, si el idioma de edición era japonés, chino o coreano, Excel se bloquease al intentar seleccionar otra fuente en la pestaña Inicio o al realizar ediciones.
-   Se ha solucionado un problema en el que faltaban las barras de desplazamiento al abrir un libro mientras Excel estaba minimizado.
-   Se ha solucionado un problema por el que las referencias de un libro producen errores al abrir varios libros haciendo doble clic en los nombres de archivo en el Explorador de archivos.
-   Se ha solucionado un problema por el que Excel se bloqueaba al crear con programación una tabla dinámica y, después, realizar una actualización con programación.
-   Se ha solucionado un problema por el que, al realizar con programación una llamada a Workbook.Open(), Excel podía bloquearse.
-   Se ha solucionado un problema que causaba que el usuario viese incorrectamente un mensaje de error "Error grave" al abrir un libro de Office 2007 o anterior (.xls o .xla) con macros.
-   Se ha solucionado un problema que provocaba que Excel se pudiera bloquear cuando un usuario abría un menú contextual.
-   Se ha corregido un problema que provocaba que Excel se bloqueara cuando el usuario hacía clic en Examinar al intentar insertar un objeto en un libro existente.
-   Se ha solucionado un problema que provocaba que, al proteger un rango con contraseña, el cuadro de diálogo para escribir la contraseña para desbloquear el rango no fuese visible.
-   Se ha corregido un problema que provocaba que un usuario no pudiera cerrar un libro en la Vista protegida cuando el nombre de archivo contenía corchetes.
-   Se ha corregido un problema que provocaba que el desplazamiento de la información en pantalla quedara incorrectamente alineada al arrastrar elementos o rellenarlos arrastrando.
-   Se ha corregido un problema que, al guardar un libro con Archivo \> Guardar como, provocaba que los nombres de archivos que contuvieran puntos aparecieran en blanco o truncados en el cuadro de diálogo de guardar.
-   Se ha corregido un problema que provocaba que Office no pudiera escribir en el disco al guardar un archivo de copia de sincronización, pero Office siguiera cargando el archivo en OneDrive. Con esta corrección, ahora el usuario ve un mensaje de error y la carga no se realiza.

### <a name="outlook-feature-updates"></a>Outlook: Actualizaciones de características
-   **Ordene el correo electrónico con facilidad:** Gracias a sus comentarios, hemos vuelto a incorporar la ordenación encima de la lista de mensajes y el filtro de no leídos para los usuarios que no usan la Bandeja de entrada Prioritarios.
-   **Convertir iconos SVG en formas:** transforme todas las imágenes e iconos SVG en formas de Office, para poder cambiar su color, tamaño o textura.
-   **Mejoras en Grupos de Office 365:** Ahora es más fácil que nunca leer y responder a conversaciones de grupo, ya que puede hacer doble clic en un mensaje de grupo para abrirlo en su propia ventana.
-   **Configuración de características de LinkedIn:** vaya a Archivo \> Opciones \> General para controlar si se muestran las características de LinkedIn en las aplicaciones de Office. [Más información](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **Modelos 3D:** Use modelos 3D para aumentar el impacto visual y creativo del correo electrónico.  Inserte fácilmente un modelo 3D y, después, podrá girarlo 360 grados. [Obtener más información](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **Tarjeta de perfil:** Muestra los detalles más relevantes sobre personas y grupos, sin importar si está en el escritorio o en la web, o si usa una aplicación móvil.
-   **Agregar una cita a un calendario de grupo:** Ya puede informar de su disponibilidad a todos los miembros del grupo sin tener que enviar una convocatoria de reunión por correo electrónico.
-   **Descarga de datos adjuntos de la nube:** Cuando guarde o arrastre y coloque archivos adjuntos de OneDrive en su equipo, el archivo en cuestión se descargará.
-   **Sonidos útiles mejoran la accesibilidad:** Active las indicaciones de audio para guiarse mientras trabaja. Las encontrará en Archivo \> Opciones \> Accesibilidad. No se necesita ningún complemento. [Obtener más información](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **Bandeja de entrada Prioritarios:** La Bandeja de entrada se divide en dos pestañas: Prioritarios y Otros. Los mensajes se ordenan en función del contenido y de los usuarios con los que interactúa con más frecuencia. [Obtener más información](https://support.office.com/article/f445ad7f-02f4-4294-a82e-71d8964e3978)
-   **Acceso rápido a los grupos más usados:** Ahora, los grupos con los que es más probable que interactúe aparecen en la parte superior de la lista de la sección Grupos del panel de carpetas.

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2017-11939): Vulnerabilidad de divulgación de información de Microsoft Office
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0791): Vulnerabilidad de ejecución remota de código de Microsoft Outlook
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0793): vulnerabilidad de ejecución remota de código de Microsoft Outlook
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0850): Vulnerabilidad de elevación de privilegios de Microsoft Outlook
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0852): vulnerabilidad de los daños en la memoria de Microsoft Outlook

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones no relacionadas con la seguridad
-   Se ha solucionado un problema por el que la búsqueda daba el error "No se encontraron coincidencias" cuando el ámbito de la búsqueda era Todos los buzones.
-   Se ha solucionado un problema que provocaba que, al supervisar elementos con Accessible Event Watcher (AccEvent.exe), Outlook se bloquea al cambiar de carpeta.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Actualizaciones de características
-   **Microsoft Translator:** Traduzca palabras, frases u oraciones a otro idioma con Microsoft Translator. You Puede hacerlo desde la pestaña Revisar de la cinta de opciones.
-   **Animaciones 3D:** dé vida a modelos 3D con animaciones, como un balanceo ligero, o un salto y un giro.
-   **Convertir iconos SVG en formas:** Transforme todas las imágenes e iconos SVG en formas de Office para poder cambiar su color, tamaño o textura.
-   **Itinerancia de la información de seguimiento de revisión:** El estado leído/no leído que se usa para resaltar diapositivas compartidas que han modificado otros usuarios ahora se almacena en un servicio de itinerancia (en lugar del equipo local) para que la información pueda sincronizarse en varios dispositivos o plataformas.
-   **Acceder rápidamente a los sitios y a los grupos:** Use el menú Archivo para trabajar con los documentos almacenados en los sitios y grupos que usa a menudo.
-   **Lápiz digital:** escriba o dibuje ideas con nuestra nueva textura de lápiz. Simplemente inclínelo para aplicar sombreado con lápices digitales compatibles.
-   **Configuración de características de LinkedIn:** vaya a Archivo \> Opciones \> General para controlar si se muestran las características de LinkedIn en las aplicaciones de Office. [Más información](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **Ejecutar una presentación con diapositivas con el lápiz digital:** Use su Lápiz para Surface, o bien otro lápiz con un botón de Bluetooth, para avanzar por las diapositivas. Se necesita Windows 10 Fall Creators Update. [Obtener más información](https://support.office.com/article/e36da834-7d34-4b71-aafd-071727549f7a)
-   **Modelos 3D:** Use modelos 3D para aumentar el impacto visual y creativo de sus presentaciones. Haga que sus modelos 3D cobren vida en sus presentaciones con transiciones como Transformación, que permite crear animaciones cinematográficas entre diapositivas. [Obtener más información](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **Nuevos efectos de lápiz:** exprese sus ideas con estilo con lápices metálicos y efectos de lápiz, como arcoíris, galaxia, lava, océano, oro, plata y más.
-   **Interfaz de usuario para compartir archivos:** en el caso de los archivos de OneDrive para la Empresa o SharePoint, haga clic en el botón Compartir que encontrará en la esquina superior derecha de la cinta de opciones o en Archivo \> Compartir. Aparecerá un cuadro de diálogo Compartir simplificado y mejorado. Para los archivos nuevos o guardados de forma local, la interfaz de usuario permite cargar los archivos fácilmente en OneDrive y empezar a colaborar.
-   **Bloquear extensiones peligrosas:** de forma predeterminada, se bloquea la activación de las extensiones consideradas de riesgo elevado y que se insertan como objetos de paquete OLE. Por ejemplo, .exe, .vbs y .js. [Más información](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **Resaltado de revisión:** se resaltan las diapositivas que han sido modificadas por otros usuarios.
-   **Mientras estuvo fuera:** PowerPoint muestra quién editó la presentación compartida desde su última visita.
-   **Mejora del servicio Diseñador:** Diseñador ahora recomienda ideas de diseño para las escalas de tiempo en una lista con viñetas.
-   **Sonidos útiles mejoran la accesibilidad:** Active las indicaciones de audio para guiarse mientras trabaja. Las encontrará en Archivo \> Opciones \> Accesibilidad. No se necesita ningún complemento. [Obtener más información](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **Ubicaciones de archivo por cuenta:** al abrir o guardar un archivo, la lista de ubicaciones se organiza en función de la cuenta asociada.
-   **Personalización del lápiz:** elija un conjunto personal de lápices y marcadores de resaltado para las entradas manuscritas. Su conjunto personalizado estará disponible en todos sus equipos PC Windows.
-   **Mejora del servicio Diseñador:** ahora, Diseñador recomienda ideas de diseño para los gráficos que se agregan a las diapositivas.
-   **Inicio rápido:** genera automáticamente un esquema para ayudar a los usuarios a empezar a investigar un tema de su elección. [Más información](https://support.office.com/article/4784f273-0b2c-456c-9c89-24e5b977c224)
-   **Regla digital:** En los dispositivos con pantallas táctiles, vaya a Dibujar \> Regla y, a continuación, utilice el lápiz o el dedo para dibujar líneas rectas o alinear un conjunto de objetos. [Obtener más información](https://support.office.com/article/6222c9b4-2fdf-48f7-a3fd-1687fbe2bf84)

### <a name="powerpoint-security-updates"></a>PowerPoint: Actualizaciones de seguridad
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2017-11934): Vulnerabilidad de divulgación de información de Microsoft PowerPoint

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema por el que, al quitar las propiedades y la información personal de un documento, se producía un error al guardar en SharePoint.
-   Se ha solucionado un problema que provocaba que se abriera una ventana nueva para reproducir el vídeo al usar referencias a Flash Player basadas en código para insertar de YouTube. Se han actualizado los códigos para insertar antiguos con referencias a HTML5 basadas en vídeos de YouTube para que se reproduzcan correctamente en su ubicación.
-   Se ha solucionado un problema que provocaba que Office no pudiera escribir en el disco al guardar un archivo de copia de sincronización, pero Office siguiera cargando el archivo en OneDrive. Con esta corrección, ahora el usuario ve un mensaje de error y la carga no se realiza.

### <a name="project-feature-updates"></a>Project: Actualizaciones de características
-   **Visualización Panel de tareas:** Ordene tareas en las tarjetas desde la visualización Panel de tareas. Reordene y mueva las tarjetas en las columnas del panel de la misma forma que con los proyectos ágiles.
-   **Proyectos ágiles:** administre sus proyectos ágiles mediante trabajos pendientes, paneles de tareas, sprints y mucho más. Se admiten las metodologías de Scrum o Kanban. [Más información](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)  
-   **Administrar una tarea en Planner:** Vincule una tarea de Project a Planner y cree un plan para esta. Divida la tarea en subtareas, agregue un equipo, asigne tareas y administre el trabajo en un panel de tareas.

### <a name="project-non-security-updates"></a>Project: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema por el que, al configurar más de una línea base en una sesión, se establecía el mismo valor de MOD\_DATE.
-   Se ha solucionado un problema en el que el trabajo real es aún se mostraba en las tablas de informe después de quitarlos de una sesión Guardar para compartir.
-   Se ha corregido un problema en la versión de idioma alemán en el que al usar un formato de fecha de semanas, devolvía un error al programar.
-   Se ha corregido un problema en el que al editar las fechas de finalización en Programar elemento web, las tareas se concentraban en 8 horas al día en lugar de extenderse a lo largo del día.
-   Se ha solucionado un problema donde "Forma del punto de progreso" se dibujaba en una ubicación inesperada.
-   Se ha solucionado un problema por el que se pierde código VBA de proyectos.
-   Se ha solucionado un problema que provocaba que las tareas se mostraban como completadas, aunque quedase trabajo restante.
-   Se ha corregido un problema que provocaba que Project se bloquease al usar la característica de ruta de tareas.
-   Se ha corregido un problema que provocaba que la escala temporal no mostrase las etiquetas de la escala temporal.
-   Se ha corregido un problema que provocaba que los informes visuales mostrasen información incompleta o fallasen por completo.
-   Se ha corregido un problema que provocaba que un error al guardar podía dañar un archivo y hacer que Project se bloqueara al abrirlo.
-   Se ha solucionado un problema que provocaba que no pudiera arrastrar tareas en la vista Escala de tiempo ni en la vista Organizador de equipo.
-   Se ha solucionado un problema que provocaba que la disponibilidad de los recursos no se mostrara en el generador de equipos.
-   Se ha corregido un problema que provocaba que los indicadores gráficos no se mostraran correctamente.
-   Se ha corregido un problema que provocaba que Project dejara de responder al realizar distribuciones por horas o días.
-   Se ha corregido un problema al trabajar con proyectos principales y subproyectos en una biblioteca de documentos de SharePoint.
-   Se ha solucionado un problema que provocaba que, al agregar una asignación a una tarea de duración fija, muchas veces el recurso quedara sin nombre.
-   Se ha solucionado un problema que generaba un mensaje de error incorrecto de un cambio en un elemento de trabajo protegido.
-   Se ha solucionado un problema por el que Project se podría bloquear al ir a un informe que contiene varias imágenes.

### <a name="publisher-feature-updates"></a>Publisher: actualizaciones de características
-   **Bloquear extensiones peligrosas:** de forma predeterminada, se bloquea la activación de las extensiones consideradas de riesgo elevado y que se insertan como objetos de paquete OLE. Por ejemplo, .exe, .vbs y .js. [Más información](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)

### <a name="publisher-non-security-updates"></a>Publisher: actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema que, al filtrar campos de orígenes de datos que contuvieran valores nulos (vacíos), provocaba errores al ejecutar el Asistente para combinar correspondencia.

### <a name="skype-for-business-non-security-updates"></a>Skype Empresarial: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema que se producía al agregar usuarios seleccionando “Llamada de Skype” en una reunión.
-   Se quita el mensaje en el que se le pregunta al usuario si quiere incluir coordenadas de Skype en una reunión al agregar una sala de Skype como ubicación cuando la reunión ya contiene las coordenadas de la reunión de Teams.
-   Se corrige un problema que provocaba que se rellenara la ubicación, incluso cuando el valor de UseLocationForE911Only era verdadero.
-   Se soluciona un problema por el que Skype Empresarial dejaba de responder al usar la opción “Llamar con el centro de conferencia” para invitar a usuarios de la lista.
-   Se soluciona un problema por el que, al ejecutar Outlook en Terminal Server, el programa se bloqueaba al crear una reunión de Skype Empresarial.
-   Se cambia el valor predeterminado de EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket a VERDADERO.
-   Se ha solucionado un problema en el que los botones "Más opciones" y "Invitar a más personas" se ocultaba cuando una reunión estaba en modo de pantalla completa.
-   Se ha corregido un problema en el que la ventana de llamada de audio P2P o de llamada de conferencia se convertía en transparente al intentar unirse.
-   Se ha corregido un problema en el que las reuniones de Skype futuras no se mostraban en la pestaña de reuniones.
-   Se ha corregido un problema en el que si Skype Empresarial estaba configurado para unirse a las reuniones sin audio, al agregar audio a una reunión, se iniciaba una llamada P2P nueva al mismo usuario en vez de agregar el audio a la reunión existente.
-   Se ha solucionado un problema en el que el usuario recibía el mensaje de error "No hemos podido encontrar esta reunión de Skype" al hacer clic en el vínculo "Unirse a la reunión de Skype" en una convocatoria de reunión de Outlook.
-   Se ha agregado el botón "Transferir llamada" a la interfaz de usuario de notificaciones del sistema para llamadas RTC entrantes.
-   Se ha notificado a los usuarios que las llamadas y el chat se envían a Teams cuando ChatDefaultClient y CallDefaultClient se establecen en Teams.
-   Se muestra la presencia del usuario como Sin conexión cuando este no se encuentra en una reunión, se deshabilitó de Skype Empresarial y la experiencia de unirse a una reunión se establece en Cliente limitado nativo.
-   Se han deshabilitado todas las opciones, excepto Abrir y Salir, cuando Skype Empresarial se minimiza en el área de notificación.
-   Se eliminan las nuevas llamadas y conversaciones cuando se empareja con teléfonos Aries y se habilita RedirectClient.
-   Se soluciona un problema por el que, al buscar mensajes en pChat por fecha, se produce un error cuando el formato de fecha es distinto del estadounidense (mm/dd/aa).
-   Se ha solucionado un problema por el que, al establecer la directiva EnableExternalP2PFileTransfer en falso, los usuarios aún pueden adjuntar archivos a las reuniones.
-   Se ha solucionado un problema que causaba que en el historial de conversación se mostrase al autor de la llamada en lugar del receptor de esta. Esto ocurre cuando se modifica el número de trabajo del usuario llamado con Active Directory.
-   Se ha corregido un problema que causaba que para las llamadas RTC salientes a números de teléfono móvil, la información del destinatario faltase en el historial de llamadas de historial de conversaciones.
-   Se ha corregido un problema que causaba que, al iniciar un mensaje instantáneo desde un correo electrónico en Outlook, la línea de asunto del correo electrónico no se incluyese en el asunto del mensaje instantáneo.
-   Se ha corregido un problema que causaba que cuando las ventanas de conversación de mensajes instantáneos se ajustaban a un lado, las conversaciones apareciesen apiladas de dos en dos.
-   Se ha corregido un problema que causaba que, en un entorno VDIv2, las solicitudes de uso compartidas de pantalla VbSS apareciesen como solicitudes RDP.
-   Se ha corregido un problema que causaba que en una transferencia de llamada errónea, el autor de la llamada apareciese en la notificación de error, en lugar del destinatario que faltaba.
-   Se ha corregido un problema que causaba que el botón "Empezar a usar Teams" se ocultase dentro de la pancarta de redirección de actualización del cliente.
-   Se ha corregido el problema de escalado de DPI en las ventanas de mensajes instantáneos.
-   Se ha solucionado un problema que causaba que los datos de LinkedIn no apareciesen en la tarjeta de contacto de Skype Empresarial.
-   Se ha agregado la capacidad para que los usuarios dejen de recibir llamadas en nombre de un grupo de extensiones.
-   Se agrega la capacidad de poner una llamada en espera automáticamente cuando está activa en Skype Empresarial o en Microsoft Teams y se recibe o inicia otra.
-   Se ha solucionado un problema que impedía que los usuarios pudiesen usar la mensajería instantánea después de compartir en modo de pantalla completa.
-   Se ha solucionado un problema que impedía que los usuarios recibiesen una notificación cuando se les denegaba el acceso a una reunión.
-   Se ha solucionado un problema que provocaba que el control automático de ganancia aumentase de forma incontrolada durante las llamadas.
-   Se ha solucionado un problema por el que los usuarios son incapaces de seleccionar un moderador en Opciones de reunión cuando se agrega un buzón de recursos de sala de conferencia a una invitación de reunión.
-   Se soluciona un problema por el que el botón de escritorio compartido aparece atenuado durante una videollamada punto a punto si AllowlPVideo está establecido en False.
-   Se soluciona un problema por el que MI permanece deshabilitada después de cambiar la configuración de Opción de reunión para habilitar MI para las reuniones existentes creadas con Deshabilitar MI.
-   Se soluciona un problema por el que no se muestra la información sobre herramientas cuando se desplaza el puntero sobre el botón "Insertar vínculo" en la ventana de chat y no hay un nombre de accesibilidad cuando se selecciona el botón.

### <a name="visio-feature-updates"></a>Visio: Actualizaciones de características
-   **Diagramas de modelo de base de datos integrados:** use la nueva plantilla Diagrama de modelo de base de datos para modelar de forma precisa una base de datos como un diagrama de Visio. No es necesario usar complementos.
-   **Más galerías de símbolos para diagramas empresariales:** Use formas modernas, compare y contraste datos con un diagrama de Venn o dibuje diagramas piramidales, de ciclo o de matrices para proporcionar la información correspondiente.
-   **Crear un diagrama de contorno reticular para un sitio web:** Cree rápidamente un diagrama de contorno reticular de un sitio web, incluida la interfaz, la navegación y su funcionamiento en conjunto. [Obtener más información](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)
-   **Crear un contorno reticular para una aplicación móvil:** use una plantilla para crear un contorno reticular de una aplicación móvil. [Más información](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)
-   **Aplicar gráficos de datos a los diagramas del Visualizador de datos:** Aplique automáticamente datos de formas como gráficos de datos y ahorre tiempo al crear un diagrama del Visualizador de datos. [Obtener más información](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6?#apply_dg)
-   **Colaboración en dibujos:** Trabaje con otros usuarios compartiendo sus dibujos en OneDrive para la Empresa o SharePoint Online. Puede ver quién está trabajando en un dibujo, agregar comentarios y ver la actividad de los archivos. [Obtener más información](https://support.office.com/article/413c0b5a-0d52-4ace-af85-8b9bf115bbbf)
-   **Bloquear extensiones peligrosas:** de forma predeterminada, se bloquea la activación de las extensiones consideradas de riesgo elevado y que se insertan como objetos de paquete OLE. Por ejemplo, .exe, .vbs y .js. [Más información](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)

### <a name="word-feature-updates"></a>Word: actualizaciones de características
-   **Convertir iconos SVG en formas:** transforme todas las imágenes e iconos SVG en formas de Office para poder cambiar su color, tamaño o textura.
-   **Número de caracteres:** se muestra el número de caracteres en la barra de estado mientras escribe. Puede habilitar esta opción en el menú Personalizar barra de estado.
-   **Obtener acceso rápidamente a los sitios y a los grupos:** use el menú Archivo para trabajar con los documentos almacenados en los sitios y grupos que usa a menudo.
-   **Microsoft Translator:** traduzca palabras, frases o todo un documento a otro idioma mediante Microsoft Translator, directamente en Word. [Más información](https://support.office.com/article/24a987b3-03a1-4c17-8c1b-54495fca6b17)
-   **Lápiz digital:** escriba o dibuje ideas con nuestra nueva textura de lápiz. Simplemente inclínelo para aplicar sombreado con lápices digitales compatibles.
-   **Configuración de características de LinkedIn:** vaya a Archivo \> Opciones \> General para controlar si se muestran las características de LinkedIn en las aplicaciones de Office. [Más información](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **Panel de propiedades de SharePoint:** Muestre y edite valores de columna de la biblioteca de documentos de SharePoint desde el propio documento. El botón de la cinta de opciones de la pestaña Vista ofrece fácil acceso al panel. Además, los administradores de SharePoint pueden usar la configuración de la biblioteca de documentos para abrir automáticamente el panel de propiedades.
-   **Modelos 3D:** Use modelos 3D para aumentar el impacto visual y creativo de los documentos.  Inserte fácilmente un modelo 3D y, después, podrá girarlo 360 grados. [Obtener más información](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **Nuevos efectos de lápiz:** exprese sus ideas con estilo con lápices metálicos y efectos de lápiz, como arcoíris, galaxia, lava, océano, oro, plata y más.
-   **Interfaz de usuario para compartir archivos:** en el caso de los archivos de OneDrive para la Empresa o SharePoint, haga clic en el botón Compartir que encontrará en la esquina superior derecha de la cinta de opciones o en Archivo \> Compartir. Aparecerá un cuadro de diálogo Compartir simplificado y mejorado. Para los archivos nuevos o guardados de forma local, la interfaz de usuario permite cargar los archivos fácilmente en OneDrive y empezar a colaborar.
-   **Bloquear extensiones peligrosas:** de forma predeterminada, se bloquea la activación de las extensiones consideradas de riesgo elevado y que se insertan como objetos de paquete OLE. Por ejemplo, .exe, .vbs y .js. [Más información](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **Editar con herramientas de aprendizaje:** Herramientas de aprendizaje ahora está disponible en la vista de diseño web de Word. Ajustar el espaciado del texto y mostrar sílabas mientras lo edita. En cualquier vista, ver cada palabra resaltada a medida que se vaya leyendo el documento en voz alta. [Obtener más información](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)
-   **Sintaxis LaTeX:** cree y modifique ecuaciones matemáticas con sintaxis LaTeX.
-   **Sonidos útiles mejoran la accesibilidad:** Active las indicaciones de audio para guiarse mientras trabaja. Las encontrará en Archivo \> Opciones \> Accesibilidad. No se necesita ningún complemento. [Obtener más información](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **Ubicaciones de archivo por cuenta:** al abrir o guardar un archivo, la lista de ubicaciones se organiza en función de la cuenta asociada.
-   **Personalización del lápiz:** elija un conjunto personal de lápices y marcadores de resaltado para las entradas manuscritas. Su conjunto personalizado estará disponible en todos sus equipos PC Windows.
-   **Ayuda de escritura mejorada con el panel Editor:** Use el panel Editor para recomendaciones de estilo avanzadas de escritura, gramática y ortografía. Se crea para ser accesible con compatibilidad mejorada a las tecnologías de asistencia.

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0792): Vulnerabilidad de la ejecución remota de código de Microsoft Word
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0793): Vulnerabilidad de ejecución remota de código de Microsoft Outlook
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0794): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0798): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0801): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0802): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0804): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0805): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0806): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0807): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0812): vulnerabilidad de daños en la memoria de Microsoft Word
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0919): vulnerabilidad de divulgación de información de Microsoft Office
-   [Advertencia 170020](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/ADV170020): Actualización de defensa en profundidad de Microsoft Office

### <a name="word-non-security-updates"></a>Word: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema que provocaba que Word se bloqueara cuando un usuario intentaba usar Guardar como sobre un documento existente en OneDrive para la Empresa y, seguidamente, cancelaba o intentaba combinar cambios existentes.
-   Se ha corregido un problema que, al filtrar campos de orígenes de datos que contuvieran valores nulos (vacíos), provocaba errores al ejecutar el Asistente para combinar correspondencia.
-   Se ha solucionado un problema que provocaba que Office no pudiera escribir en el disco al guardar un archivo de copia de sincronización, pero Office siguiera cargando el archivo en OneDrive. Con esta corrección, ahora el usuario ve un mensaje de error y la carga no se realiza.
-   Se ha solucionado un problema que, al quitar la protección IRM de un documento, provocaba que dicha protección no se eliminara.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2017-11882): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0795): vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0851): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0853): vulnerabilidad de divulgación de información de Microsoft Office
-   [Aviso 180003](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/ADV180003): Actualización de defensa en profundidad de Microsoft Office

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema que provocaba que, al abrir una aplicación, el usuario viera un mensaje sobre iniciar en modo seguro y después la aplicación no se abriera.
-   La opción "Actualizar ahora" está oculta en Archivo \> Cuenta \> Opciones de actualización cuando se habilita un objeto COM de Office para que Configuration Manager administre las actualizaciones de cliente de Office 365.
-   Se ha solucionado un problema que causaba que la aplicación de Office se bloquease cuando el usuario intentaba activar Office con el cuadro de diálogo Activar Office.
-   Se ha solucionado un problema relacionado con el zoom y el escalado en Complementos de Office en el entorno de PPP dinámico.
-   Se ha corregido un problema que provocaba que el nodo CurrentStatus del proveedor del servicio de configuración (CSP) de Office devolviera una cadena vacía incluso si Office 365 ProPlus está instalado.
-   Se ha corregido un problema que provocaba cambios en los formatos de archivo .box. Esto afectaba la funcionalidad de versiones antiguas de Office instaladas en el mismo equipo, porque los archivos .box se comparten con todas las versiones de una aplicación de Office en el mismo equipo.



## <a name="version-1708-february-13"></a>Versión 1708: 13 de febrero
*Versión 1708 (compilación 8431.2215)*

### <a name="access-non-security-updates"></a>Access: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema que provocaba que, al usar un formulario de varios elementos, al cambiar la posición con la rueda del ratón o con la barra de desplazamiento no se cambiasen los elementos mostrados en el formulario.

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0841): Vulnerabilidad de la ejecución remota de código de Microsoft Excel

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0850): Vulnerabilidad de elevación de privilegios de Microsoft Outlook
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0852): Vulnerabilidad de los daños en la memoria de Microsoft Outlook

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0851): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0853): Vulnerabilidad de divulgación de información de Microsoft Office



## <a name="version-1708-january-9"></a>Versión 1708: 9 de enero
*Versión 1708 (compilación 8431.2153)*

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0796): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [Advertencia 170021](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/ADV170021): Actualización de defensa en profundidad de Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema por el que Excel se bloqueaba al crear mediante programación una tabla dinámica y, después, realizar una actualización mediante programación.

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0791): Vulnerabilidad de la ejecución remota de código de Microsoft Outlook
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0793): Vulnerabilidad de ejecución remota de código de Microsoft Outlook

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0792): Vulnerabilidad de la ejecución remota de código de Microsoft Word
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0793): Vulnerabilidad de ejecución remota de código de Microsoft Outlook
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0794): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0798): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0801): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0802): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0804): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0805): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0806): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0807): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0812): Vulnerabilidad de daños en la memoria de Microsoft Word

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/CVE-2018-0795): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [Aviso 180003](https://portal.msrc.microsoft.com/es-ES/security-guidance/advisory/ADV180003): Actualización de defensa en profundidad de Microsoft Office

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad
-   Se agregó compatibilidad con el inicio de sesión único (SSO) para usuarios de dominio de planes de Office 365 Alemania donde la identidad está federada con un entorno local de Active Directory.
-   Se agregó una función para impedir que usuarios menores de edad puedan comprar y activar complementos de Office de la Tienda Office.


> [!NOTE]
> Si necesita ayuda con algún problema de uso de Office, le recomendamos que publique la pregunta en el [foro de preguntas de Microsoft](https://answers.microsoft.com/) o [Tech Community](https://techcommunity.microsoft.com/), o bien puede ponerse en contacto con el [servicio de soporte técnico](https://support.microsoft.com/contactus).
