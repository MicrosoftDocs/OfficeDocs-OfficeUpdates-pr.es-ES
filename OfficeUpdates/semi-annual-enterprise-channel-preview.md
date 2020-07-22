---
title: Notas de la versión para las versiones de canal empresarial semestral (vista previa) en 2020
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Proporciona a los profesionales de TI las notas de la versión para las versiones del canal semestral (dirigido) de Aplicaciones de Microsoft 365 en 2020.
ms.openlocfilehash: 28b78e3952867cb55b2b91e9e6d9d8d5f2e35063
ms.sourcegitcommit: 6f79e3c3948db4d7ae1c6dfc855970551d3b1678
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 07/20/2020
ms.locfileid: "45187590"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview-releases-in-2020"></a>Notas de la versión para las versiones de canal empresarial semestral (vista previa) en 2020

Estas notas de la versión proporcionan información sobre las nuevas características y las actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones de canal empresarial semestral (vista previa) en 2020 para las Aplicaciones de Microsoft 365 para empresas, las Aplicaciones de Microsoft 365 para negocios y las versiones de suscripción de las aplicaciones de escritorio de Project y Visio.

> [!IMPORTANT]
> Estamos realizando algunos cambios en los canales de actualización de las Aplicaciones de Microsoft 365, incluida la adición de un nuevo canal de actualización (canal empresarial mensual) y el cambio de los nombres de los canales de actualización existentes. [Lea este artículo](https://go.microsoft.com/fwlink/p/?linkid=2127441) para obtener más información.


## <a name="version-2002-july-14"></a>Versión 2002: 14 de julio
*Versión 2002 (compilación 12527.20880)*

Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


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


[//]: # (NO QUITAR LOS DETALLES DE ERROR DE FIN DE CONTENIDO)

## <a name="version-2002-june-09"></a>Versión 2002: 09 de junio
*Versión 2002 (compilación 12527.20720)*

Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


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

- El host de Office se bloqueaba en Windows, cuando se activaba un complemento si la clave del registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth estaba establecida en cero. Este cambio arreglaría el problema.


[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-may-12"></a>Versión 2002: 12 de mayo
*Versión 2002 (compilación 12527.20612)*

Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


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

Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Escriba una fórmula que devuelva varios valores:** escriba rápidamente una fórmula que devuelva varios valores y se depositarán automáticamente en las celdas vecinas. [Más información](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- **Seis potentes funciones:** hemos agregado seis nuevas funciones para mejorar las hojas de cálculo: FILTRAR, ORDENAR, ORDENARPOR, UNICOS, SECUENCIA y MATRIZALEAT.  [Más información](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- **Buscar a la izquierda, buscar a la derecha... BUSCARX ya está aquí:** fila por fila, encuentre lo que necesite en una tabla o un rango con BUSCARX.  [Más información](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)

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

Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="access"></a>Access

- **Buscar tablas vinculadas rápidamente:** nuestro nuevo cuadro de búsqueda hace que buscar tablas vinculadas sea mucho más sencillo. [Más información](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a>Excel

- **Logre la atención de sus colegas con** @menciones:\@ use @menciones en los comentarios para avisar a los compañeros de trabajo cuando necesite su participación. [Más información](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **Encuentre lo que busca:** Realice búsquedas de comandos, personas, archivos, fotos, artículos en la web y más. [Más información](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- **Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su libro. [Más información](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.

- **Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. 

- **Resalte lo que queda por hacer**: seleccione Resolver para contraer los comentarios y hacer que resalten los elementos abiertos.

- **Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar. [Más información](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **Convertir los archivos para mejorar la accesibilidad**: actualice los archivos al formato moderno para que sean más accesibles para todos los demás.

- **Complemento del visualizador de datos:** Crear rápidamente diagramas de flujo de Visio desde Excel. [Más información](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- **Lea y responda sobre la marcha: **responda a los comentarios y las menciones directamente desde el correo electrónico, sin abrir el libro.

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

- **Una experiencia de vídeo más segura:** las mejoras de seguridad hacen que la experiencia de vídeo en línea sea más segura. [Obtener más información](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Esta actualización corrige un problema en Microsoft Access que puede causar el error &quot;La consulta está dañada&quot; cuando se ejecuta una consulta de actualización o cuando se usa una instrucción UPDATE en SQL.

- Esta actualización corrige un problema que puede hacer que Microsoft Access no identifique una Columna de identidad en una tabla vinculada de SQL Server, lo que puede provocar que las filas aparezcan como eliminadas de forma incorrecta.

- Esta actualización corrige un problema por el que al usar un objeto de grabación de ADODB en el código de VB, se puede notificar un error incorrectamente.

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

- Se ha corregido un problema por el que los usuarios veían un cuadro de mensaje vacío con el botón &quot;Aceptar&quot; al intentar ponerse en contacto con el soporte técnico desde la Creación de cuenta.

- Se ha corregido un problema que provocaba que los usuarios sufrieran un bloqueo durante la creación del perfil.

- Se ha corregido un problema por el que Outlook sincronizaba inesperadamente todo el correo, incluso cuando el deslizador de sincronización estaba configurado en un ajuste menor.

- Se ha corregido un problema por el que los usuarios con el tema Negro veían la lista desplegable &quot;De&quot; con un texto blanco sobre un fondo blanco.

- Se ha corregido un problema que provocaba que los usuarios experimentaran un error al cancelar la configuración de la cuenta.

- Corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.

- Se ha corregido un problema que hacía que la opción deshabilitar el resaltado de elementos marcados no se pudiera respetar en algunos escenarios.

- Se ha corregido un problema que hacía que los usuarios vieran una &quot;Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange&quot; al abrir el cuadro de diálogo de las reglas.

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

- Se ha corregido un problema que provocaba que los usuarios vieran mensajes enviados inesperadamente al presionar la tecla &quot;S&quot; después de cerrar el panel del comprobador de accesibilidad.

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

- Corregido un problema ocasional en el que al guardar un archivo existente siempre aparece el cuadro de diálogo Guardar como y el archivo nunca se guarda.

- El organizador de bloques de construcción puede mostrar una alerta inválida:&quot;Has modificado estilos, bloques de construcción&quot;.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Este cambio corrige el procesamiento lento de algunos gráficos de dispersión con marcadores.

- Este cambio resuelve problemas con adaptadores gráficos que aprovechan la GPU integrada de Intel.

- Corrección de un error en la configuración de la fecha límite de actualización de ODT y GPO, en la que la fecha límite relativa solo funciona la primera vez que se establece. Ahora, la corrección permite establecer una fecha límite relativa para las actualizaciones posteriores.

- Se ha corregido un problema por el que las actualizaciones de Office podían haber descargado inesperadamente archivos de la CDN de Office en lugar de la fuente prevista, como un recurso compartido local o de red, o una ubicación proporcionada por el Administrador de configuración.

- Corrige un problema por el que cuando hay varios documentos abiertos en Word/Excel/PowerPoint de la misma biblioteca de SharePoint, solo se analizará el primer documento abierto para el cumplimiento de las directivas.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-february-11"></a>Versión 1908: 11 de febrero
*Versión 1908 (Compilación 11929.20606)*

Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


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

Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


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


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

> [!NOTE]
> Si necesita ayuda con algún problema de uso de Office, le recomendamos que publique la pregunta en el [foro de preguntas de Microsoft](https://answers.microsoft.com/) o [Tech Community](https://techcommunity.microsoft.com/), o bien puede ponerse en contacto con el [servicio de soporte técnico](https://support.microsoft.com/contactus).


[//]: # (NO MODIFICAR EL INICIO DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20880|version-2002-july-14|)
[//]: # (NO MODIFICAR EL FIN DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)