---
title: Notas de la versión archivadas para las versiones del canal semestral
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Proporciona a los profesionales de TI las notas de la versión para las versiones del canal semestral de Office 365 ProPlus
ms.openlocfilehash: 983782e92fbcaeebe5bbcfceee691fee57134da3
ms.sourcegitcommit: 5f72a0e94cda2cb64636380605806c29bbcdc53f
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/26/2021
ms.locfileid: "52026345"
---
# <a name="archived-release-notes-for-semi-annual-enterprise-channel"></a>Notas de la versión archivadas para el canal semestral para empresas

En estas notas de la versión, se proporciona información sobre características nuevas y actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones del canal semestral para empresas de Office 365 ProPlus, Visio Pro para Office 365, el cliente de escritorio de Project Online y Office 365 Empresa.

> [!NOTE]
> - A menudo, publicamos características (y a veces incluso correcciones) para el canal semestral para empresas durante un período de tiempo. Si aún no ve alguna de las cosas que se describe a continuación, la verá pronto. [Más información](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
> - OneNote 2016 no se incluirá de forma predeterminada cuando un usuario en el canal semestral para empresas descargue e instale Office 365 en Windows 10 desde el portal de Office.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-december-08"></a>Versión 2002: 08 de diciembre
*Versión 2002 (compilación 12527.21416)*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Interletraje de texto en PowerPoint mejorado cuando el contenido se copia desde Excel y se pega en PowerPoint con la opción Insertar.


- Se ha corregido un problema que provocaba que Excel dejara de funcionar durante el recálculo.


- Se ha corregido un problema que provocaba que el usuario no pudiera abrir el archivo atomsvc (UTF8+BOM) directamente desde SharePoint.


- Se ha corregido un problema que impedía cambiar entre la vista previa de la tabla y el editor de consultas en PowerPivot.


- Rendimiento mejorado para los archivos que usan muchas de las funciones recientemente publicadas.


### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que, al configurar OME, se agregaran datos adjuntos extraños en el elemento de correo, que obligaban a Outlook a cifrar el mensaje aunque la opción DecryptAttachmentsForEncryptOnly estuviera configurada en el lado del servicio.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema que provocaba que el gráfico de Excel vinculado cambiara incorrectamente a la hoja de Excel cuando el usuario cambiaba la ruta de origen a la carpeta de OneDrive local.


### <a name="project"></a>Project

- Se ha corregido un problema que provocaba que los proyectos no se pudieran abrir en el cliente de escritorio de Project en Project Web App si la dirección URL terminaba en .com.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-december-08"></a>Versión 1908: 08 de diciembre
*Versión 1908 (compilación 11929.20984)*

Las actualizaciones de seguridad se muestran [aquí](./microsoft365-apps-security-updates.md)

## <a name="version-2002-november-10"></a>Versión 2002: 10 de noviembre
*Versión 2002 (compilación 12527.20720)*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema que aparecía cuando se configuraba el idioma de Office en español. Este problema provocaba que las listas de validación de datos puedan no mostrar todos los elementos de la lista.


- Se ha corregido un problema que podía provocar un bloqueo al actualizar las tablas dinámicas de OLAP.


- Se ha corregido un problema por el que algunas funciones podían tener un resultado incorrecto después de cargar un libro.


- Se ha corregido un problema relacionado con las referencias de complemento de XLAM y los rangos con nombre que cerraba la aplicación de forma inesperada.


- Se ha corregido un problema que producía que la ejecución de la macro de filtro avanzada mostrara errores incorrectamente.


### <a name="outlook"></a>Outlook

- Se ha corregido un problema por el que se deshabilitaban de forma inesperada complementos internos cuando se deshabilitaban las experiencias conectadas opcionales.


- Se ha corregido un problema que impedía a los usuarios enviar como (o en nombre de) una lista de distribución oculta para la lista global de direcciones.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-november-10"></a>Versión 1908: 12 de noviembre
*Versión 1908 (Build 11929,20300)*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)

## <a name="version-2002-october-13"></a>Versión 2002: 13 de octubre
*Versión 2002 (Compilación 12527.21104)*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Acceso

- Ya no debería recibir un error "La consulta es demasiado compleja" o de recurso del sistema excedido en su versión de 64 bits de Access, siempre y cuando cumpla con las directrices y requisitos de la base de datos de Access.


- Una vez que decida usar nuestra característica de filtro después de nuestro diseñador de consultas, la base de datos ya no debería bloquearse. Compruebe lo que corresponda.


### <a name="excel"></a>Excel

- Se corrigió un problema por el cual los usuarios no podían modificar un filtro de tabla dinámica porque estaba configurado en un valor que ya no estaba presente en una base de datos de Analysis Services.


### <a name="powerpoint"></a>PowerPoint

- Las nuevas presentaciones creadas a partir de una plantilla podían heredar una configuración que impedía una buena experiencia de coautoría. Esta corrección garantiza que la configuración se haya borrado en este caso.


### <a name="word"></a>Word

- Se ha corregido un problema por el que al abrir documentos con saltos de página y columnas, el usuario podía encontrar un mensaje de error, "Ha excedido el número máximo de páginas admitidas por Microsoft Word, o el documento puede estar dañado"


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Cuando el usuario imprime cualquier documento o archivo en las impresoras de inyección de tinta de Office y la tinta de la impresora es poco visible, el mensaje "tóner bajo" o "sin tóner" se mostrará, aunque las impresoras de inyección de tinta no tengan toners Cambiar mensaje para mostrar "tóner/Ink Low" & "no tóner/tinta".



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-october-13"></a>Versión 1908: 8 de octubre
*Versión 1908 (compilación 11929.20516)*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Cuando el usuario imprime cualquier documento o archivo en las impresoras de inyección de tinta de Office y la tinta de la impresora es poco visible, el mensaje "tóner bajo" o "sin tóner" se mostrará, aunque las impresoras de inyección de tinta no tengan toners Cambiar mensaje para mostrar "tóner/Ink Low" & "no tóner/tinta".



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-september-08"></a>Versión 2002: 08 de septiembre
*Versión 2002 (Compilación 12527.21104)*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Esto soluciona un problema en el que las conexiones creadas por el proveedor de datos SQL en versiones anteriores de Office establecerían las propiedades de la tabla interna de manera diferente a Office 365. Esto provocó que el menú desplegable Vista previa de tabla / Editor de consultas se deshabilitara para los archivos con conexiones creadas en versiones anteriores de Office cuando se abrieron con Office 365.


- Se corrigió un problema por el cual las entradas manuscritas podrían hacer que Excel dejara de responder.


### <a name="outlook"></a>Outlook

- Corrige un problema que evitaba que los usuarios se conectaran a las carpetas públicas luego de agregar un buzón compartido.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Este cambio resuelve un problema con el cuadro de diálogo de Comprimir imagen, que no retiene determinadas configuraciones de usuario.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-september-08"></a>Versión 1908: 08 de septiembre
*Versión 1908 (compilación 11929.20946)*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)

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

## <a name="version-1908-august-11"></a>Versión 1908: 11 de agosto
*Versión 1908 (compilación 11929.20934)*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)

## <a name="version-1902-august-11"></a>Versión 1902: 11 de agosto
*Versión 1902 (compilación 11328.20644)*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2002-july-14"></a>Versión 2002: 14 de julio
*Versión 2002 (compilación 12527.20880)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="access"></a>Access

- **Buscar tablas vinculadas rápidamente:** nuestro nuevo cuadro de búsqueda hace que buscar tablas vinculadas sea mucho más sencillo. [Más información](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a>Excel

- **Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.

- **Complemento del visualizador de datos:** Crear rápidamente diagramas de flujo de Visio desde Excel. [Más información](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- **Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar. [Más información](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)

- **Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos. Encuéntrelos en Insertar > Iconos. [Más información](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- **Convertir los archivos para mejorar la accesibilidad**: actualice los archivos al formato moderno para que sean más accesibles para todos los demás.<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)

- **Resalte lo que queda por hacer**: seleccione Resolver para contraer los comentarios y hacer que resalten los elementos abiertos.

- **Escriba una fórmula que devuelva varios valores:** Escriba rápidamente una fórmula que devuelva múltiples valores y se derramarán automáticamente en las celdas vecinas. [Más información](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)

- **Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. 

- **Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su libro. [Más información](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)

- **Encuentre lo que busca:** Realice búsquedas de comandos, personas, archivos, fotos, artículos en la web y más. [Más información](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- **Seis potentes funciones:** Seis potentes funciones: Hemos agregado seis nuevas funciones para mejorar las hojas de cálculo: FILTRAR, ORDENAR, ORDENARPOR, UNICOS, SECUENCIA y MATRIZALEAT. [Más información](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- **Busque a la izquierda, busque a la derecha... BUSCARX ya está aquí**: fila por fila, busque lo que necesite en una tabla o un rango con BUSCARX. [Más información](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)

- **Dominar el libro grande:** celdas, fórmulas, gráficos y tablas... Obtenga una instantánea de su libro con estadísticas de libros.

- **Lea y responda sobre la marcha:** responda a los comentarios y las menciones directamente desde el correo electrónico sin abrir el libro.

- **Consiga su atención con\@menciones:** use @menciones en los comentarios para avisar a los compañeros de trabajo cuando necesite su participación. [Más información](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="outlook"></a>Outlook

- **Encajar más mensajes en la pantalla:** seleccione Ver > Usar espaciado más estrecho para ajustar el espaciado entre mensajes. [Más información](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- **Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos. Encuéntrelos en Insertar > Iconos. [Más información](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- **Deja que lo dibuje:** garabatee sobre las imágenes o agregue un Lienzo de dibujo para enviar sus pensamientos con la entrada de lápiz. [Más información](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- **Obtenga sugerencias de ubicaciones:** Empiece a escribir en Ubicación cuando programe citas y reuniones, Outlook le sugerirá salas, direcciones y otros lugares recientes. [Más información](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)

- **Protección avanzada frente a ataques**: con la Protección contra amenazas avanzada de Office 365, estará protegido frente a ataques mediante hipervínculos en asuntos de correos electrónicos, mensajes adjuntos, mensajes firmados, rutas de red, etc.

- **Insertar el menú de vínculos en Outlook inserta un vínculo con el permiso definido por el administrador de inquilinos:** un vínculo desde Insertar vínculo utilizado recientemente en Outlook insertaba un vínculo que solo funcionaba para los usuarios que ya tenían permisos. A menudo esto causaba un intercambio continuo de mensajes de correo electrónico entre los usuarios que pedían acceso a un documento. Hemos actualizado esta experiencia para que ahora el vínculo se inserte con el permiso predeterminado establecido por el administrador de inquilinos. Para MSIT se trata de "la organización puede editar", por lo que todos los usuarios internos que reciban un vínculo compartido de esta manera podrán acceder a él.

- **Ver los mensajes bajo otra luz:** use el botón sol/luna para cambiar entre fondos claros y oscuros en el panel de lectura. [Más información](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- **Ahora es más fácil detectar correos de suplantación de identidad:** los mensajes de correo no deseado y de suplantación de identidad tienen un aspecto diferente para que pueda identificarlos y eliminarlos fácilmente en la bandeja de entrada.

- **Todas las opciones de cifrado en un solo lugar:** vaya a Opciones > Cifrar para elegir cómo proteger su mensaje de correo. [Más información](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)

- **Busque incluso con errores ortográficos o tipográficos:** Outlook encontrará lo que busca, aunque no coincida con la forma exacta en que lo escribió.

- **Conecte su red de LinkedIn con Outlook:** Conecte de forma segura su cuenta de LinkedIn con su cuenta de Microsoft para ver la información de los perfiles de LinkedIn directamente en las tarjetas personales. [Más información](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- **Ver mensajes relevantes en los resultados de búsqueda:** Outlook analiza los términos de búsqueda y muestra los mensajes de correo electrónico más relevantes en la parte superior de los resultados de búsqueda. También verá todos los resultados ordenados por fecha en la sección de Resultados principales. [Más información](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

### <a name="powerpoint"></a>PowerPoint

- **Usted calcula y nosotros le damos formato:** hemos convertido las expresiones matemáticas escritas a mano en caracteres estándar. Simplemente elija Entrada de lápiz a matemáticas y seleccione las notas escritas a mano para empezar. [Más información](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **Encuentre lo que busca:** use el cuadro de búsqueda para buscar texto, comandos, ayuda y mucho más. [Más información](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- **Entrada de tinta para magníficas diapositivas:** convierta el texto de tinta en formas estándar y texto y obtenga ideas de diseño inteligente del Diseñador de PowerPoint. [Más información](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- **Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su presentación. [Más información](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)

- **Repetición de entrada de lápiz:** cuando haya entradas de lápiz en sus diapositivas, aplique una animación de reproducción para reproducir el dibujo real de la entrada de lápiz durante la presentación con diapositivas. [Más información](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)

- **Una experiencia de vídeo más segura:** las mejoras de seguridad hacen que la experiencia de vídeo en línea sea más segura.

- **Guarde una ilustración como SVG:** guarde un gráfico, una forma o una ilustración como un gráfico vectorial escalable, que se puede cambiar de tamaño sin perder calidad de imagen. [Más información](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- **Impresión de números de diapositiva en documentos:** los números de diapositiva se incluyen automáticamente en los documentos. Ahora es usted quien decide si los deja o los quita. [Más información](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- **Encuentre los títulos de diapositivas que faltan y escríbalos**: los títulos de diapositivas añaden fuerza a su discurso y permiten que las diapositivas sean accesibles para los usuarios de todas las capacidades. El comprobador de accesibilidad le muestra dónde faltan títulos para que pueda agregarlos en el momento. [Más información](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- **Convertir los archivos para mejorar la accesibilidad**: actualice los archivos al formato moderno para que sean más accesibles para todos los demás.<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)

- **Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos. Encuéntrelos en Insertar > Iconos. [Más información](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- **Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar.<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)

- **Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.

- **Colaboración rápida en tiempo real en PowerPoint:** colaboración rápida en tiempo real en PowerPoint

- **Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación. 

- **Nuevas herramientas de revisión:** no se preocupe de las palabras. Ahora en PowerPoint se ofrecen sugerencias de gramática y escritura. [Más información](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- **Transcripción y subtítulos en directo:** las palabras del moderador se muestran automáticamente en la pantalla como subtítulos o se traducen en el idioma que prefiera. [Más información](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- **Optimizar la presentación para todos:** el comprobador de accesibilidad le ayuda a organizar los objetos de las diapositivas pensando en los lectores de pantalla.<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)

- **¿Para que reinventar lo que puede reutilizar?:** ahorre tiempo usando de nuevo las diapositivas que haya creado o que otros usuarios han compartido con usted. [Más información](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

### <a name="visio"></a>Visio

- **Cree diagramas de Visio elegantes en Excel:** cree un diagrama de flujo o un organigrama con solo escribir datos en una hoja de cálculo. [Más información](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- **Vuelva a la escena del crimen:** use las nuevas plantillas Evidencia, Interior y Exterior en la plantilla Investigación de Escenas de Delitos para recrear con detalle escenarios de delitos.

### <a name="word"></a>Word

- **Una experiencia de vídeo más segura:** las mejoras de seguridad hacen que la experiencia de vídeo en línea sea más segura. [Más información](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- **Cree archivos PDF más accesibles:** Cree un PDF y el verificador de accesibilidad le indicará los problemas de accesibilidad que debe solucionar antes de guardar. [Más información](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)

- **Uso compartido de archivos más rápido:** comparta sus documentos directamente desde la lista usada recientemente sin tener que abrir el archivo.

- **Más iconos para que encuentre el que refleja su estado de ánimo:** hemos agregado más de 300 iconos nuevos. Encuéntrelos en Insertar > Iconos. [Más información](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)

- **Borrar con precisión:** elija entre dos tamaños de borrador para arreglar pequeñas imperfecciones de la entrada de lápiz. [Más información](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **Convertir los archivos para mejorar la accesibilidad**: actualice los archivos al formato moderno para que sean más accesibles para todos los demás.<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)

- **Un toque humano**: dé un aspecto informal y de dibujado a mano a las formas de Office en su documento. [Más información](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)

- **Encuentre lo que busca:** use el cuadro de búsqueda para buscar texto, comandos, ayuda y mucho más. [Más información](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- **Se acabaron los saltos al explorador:** usted decide cómo se abren los vínculos a los documentos de Office: en el explorador o en la aplicación.  [Más información](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- **El Editor para currículum vítae incorpora el Asistente para currículum vítae de LinkedIn:** el Editor para currículum vítae ofrece una selección de comprobaciones gramaticales y de estilo especialmente adaptadas a los currículums, para que el texto sea más preciso y profesional.

- **Otros usuarios verán los cambios rápidamente:** con las mejoras en la coautoría, los colaboradores podrán ver los cambios más rápido que nunca.

- **Se ha corregido un problema relacionado con los documentos causados por la combinación de objetos 3D:** corrige un problema de daños en un documento producido por la combinación de objetos 3D.

- **Mejoras en la coautoría:** mejora del rendimiento de Word en coautoría en documentos con marcas de revisión.

- **Mejoras en la coautoría:** mejora de la confiabilidad de la coautoría.

- **Colaborando a todo color:** los comentarios y los cambios están codificados por color según la persona que contribuya, por lo que es fácil distinguir entre sus colaboradores.

- **Editar documentos habilitados para macros de forma conjunta:** guarde sus archivos .docm en OneDrive para la Empresa y edítelos con sus colaboradores en tiempo real.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- **Transforme la entrada de lápiz en formas, texto o matemáticas en PowerPoint para Office 365:** convierta la entrada de lápiz en forma libre a formas, textos o expresiones matemáticas de Office en un par de trazos. [Más información](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Esta actualización corrige un problema por el que al usar un objeto de grabación de ADODB en el código de VB, se puede notificar un error incorrectamente.

- Las plantillas de Access ya no deberían causar errores en columnas de datos adjuntos en una base de datos. Después de crear la instancia de una plantilla, ahora debería poder agregar un campo de datos adjuntos a la base de datos.

- Esta actualización corrige un problema que puede hacer que Microsoft Access no identifique una Columna de identidad en una tabla vinculada de SQL Server, lo que puede provocar que las filas aparezcan como eliminadas de forma incorrecta.

- Esta actualización corrige un problema en Microsoft Access que puede causar el error "La consulta está dañada" cuando se ejecuta una consulta de actualización o cuando se usa una instrucción UPDATE en SQL.

### <a name="excel"></a>Excel

- Acelere la carga de archivos que están disponibles en la carpeta de OneDrive local.

- Se ha solucionado un problema por el que las funciones CUBEVALUE a veces daban un resultado incorrecto.

- Resuelto un problema con la personalización de la cinta que no se cargaba al abrir el libro de trabajo incrustado.

- Excel se bloqueaba en ciertos casos cuando se volvía a abrir un libro incrustado en Word o PowerPoint.

- Se ha corregido un problema por el que los comandos de comentario en el menú contextual no aparecían.

- Se ha corregido el botón derecho en el menú de gráficos dinámicos para habilitar la opción de mostrar los detalles.

- Se ha resuelto un problema que puede haber causado un bloqueo al buscar archivos recientes cuando no hay ningún libro de trabajo abierto.

- Se ha corregido un problema que provocaba que, al hacer clic en un hipervínculo marcado en el propio libro, se ocultara dicho libro.

- Cuando guarda como un archivo CSV, Excel podía combinar todas las columnas en una sola columna en algunos casos.

- Usar Range.ClearContents en un rango de una hoja protegida podía tardar más de lo esperado.

- Corregido un problema con la escala de texto en los controles de formulario cuando se mostraba en la Vista previa de impresión.

- Las macros de VBA que interactúan con la cinta de opciones se pueden ejecutar con ScreenUpdating establecido en True inesperadamente.

- Se ha corregido un problema que hacía que Excel se bloqueara en ciertos casos después de copiar una hoja que contenía una tabla dinámica.

- La apertura de archivos CSV tardaba más de lo esperado en algunas circunstancias.

- Excel se bloqueaba en determinadas circunstancias al cambiar entre libros con diferentes niveles de zoom.

- Se ha corregido un problema con VBA por el que escribir valores en un rango era más lento de lo esperado.

- En ocasiones, los datos copiados de una columna filtrada por color no se pegaban correctamente.

- La apertura de un libro de trabajo con referencias a muchos otros libros de trabajo, especialmente con ventanas ocultas, era más lenta de lo esperado.

- Se ha corregido un problema por el que los enlaces externos no se actualizaban al rellenar (rellenar hacia abajo, rellenar en otros, etc.) si el libro de origen estaba cerrado.

- Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.

- En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.

- Se ha corregido un problema por el que la propiedad "Valor se cruza en" en el eje del gráfico cambiaba inesperadamente al guardar y volver a abrir un archivo.

- Se ha corregido un problema que provocaba que se quitara el XML de CustomUI para una ficha de cinta al guardar en SharePoint o OneDrive.

- Se ha mejorado el rendimiento al eliminar columnas con celdas combinadas.

- Se ha corregido un problema por el que los nombres de las impresoras podrían repetirse en la lista de impresoras en el cuadro de diálogo Imprimir.

- Se ha corregido un problema que hacía que el vínculo externo dejara de funcionar después de que se volviera a abrir el archivo si su ruta de acceso era demasiado larga.

- Se ha corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.

- Podría producirse un bloqueo al intentar mostrar los cambios en una nueva hoja de un libro con el modo "libro compartido" heredado.

- Insertar una columna en una lista filtrada llevaba más tiempo de lo esperado.

- Se ha corregido un problema por el que algunos vínculos de un gráfico copiado y pegado usaban direcciones de unidad asignadas, en lugar de direcciones universales.

- Se ha corregido un problema que producía el siguiente mensaje de error: "No se puede cerrar el libro de trabajo debido a que otro libro hace referencia al mismo". El mensaje aparecía si los complementos se cargaban en orden alfabético en lugar de en un orden especificado por el usuario.

- Se ha corregido un problema que haría que un libro se ocultara al hacer clic en un hipervínculo a un lugar dentro de un libro ya abierto.

- La apertura de un libro de trabajo con referencias a muchos otros libros de trabajo, especialmente con ventanas ocultas, era más lenta de lo esperado.

- El uso de Application.Evaluate de VBA no funcionaba para funciones definidas por el usuario en algunos casos.

- Se ha corregido un problema que algunos usuarios pudieron sufrir con objetos incrustados y vinculados (OLE).

- Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.

- Esta actualización corrige un problema que causaba que la barra de fórmulas mostrara texto en una fuente diferente a la esperada.

- Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.

- Corregimos un problema en el que al seleccionar una celda luego de desplazar, podía resultar en la selección de la celda incorrecta.

- Los usuarios pueden encontrar un error al acceder a un rango con nombre oculto.

- Excel puede tener problemas al editar un archivo protegido desde una red compartida no confiable.

- La funcionalidad de texto a columna puede fallar en algunas localizaciones.

- Se ha corregido un problema de rendimiento al crear gráficos a partir de plantillas.

- Se ha corregido un problema que causaba que algunos usuarios experimentasen bloqueos al convertir texto en columnas con celdas que tienen una matriz derramada.

- El uso de un Range.Value y Range.Value2 (VBA) hacía que las fórmulas se escribieran como matrices dinámicas.

- Se ha corregido un problema por el que un símbolo @ que inicia una fórmula se considera un operador de intersección implícita.

- Se ha corregido un problema por el que las hojas de cálculo que contenían varias fórmulas con nombres definidos tardaban más en guardarse.

- Este cambio evita un problema con ciertos controladores de gráficos Intel al aprovechar el procesamiento del software.

- Se ha corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.

### <a name="onenote"></a>OneNote

- Mejora la sincronización y la estabilidad del servicio al ajustar temporalmente la frecuencia de sincronización en OneNote 2016.

- Mejora la sincronización y la estabilidad del servicio al diferir temporalmente la descarga de archivos e imágenes incrustados en los blocs de notas en línea hasta que el usuario navegue a la página en OneNote 2016.

- Mejora la sincronización y la estabilidad del servicio al deshabilitar temporalmente la papelera de reciclaje en OneNote 2016. Cuando un usuario intenta eliminar datos que normalmente se enviarían a la papelera de reciclaje, se le preguntará si prefiere conservarlos o eliminarlos forma permanente.

- Mejora la sincronización y estabilidad de servicio mejoradas al reducir temporalmente el número y la frecuencia de sincronización de las páginas del historial de versiones en OneNote 2016.

- Muestra una notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.

- Mejora la sincronización y la estabilidad del servicio al reducir temporalmente el tamaño máximo de nuevos datos adjuntos insertados a 50 MB en OneNote 2016. Si los archivos superan este límite, los usuarios tendrán la opción de cargar el archivo a OneDrive e insertar un vínculo en OneNote.

- Mejora la sincronización y la estabilidad del servicio al deshabilitar temporalmente la grabación de vídeo en la aplicación en OneNote 2016. La medida no afecta a los blocs de notas locales.

- Localiza la notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema por el que la ventana del Editor de métodos de entrada (IME) se superponía al texto subyacente escrito mediante el IME cuando se usaban varios monitores con resoluciones diferentes.

- Se ha corregido un problema que provocaba que los usuarios vean bloqueos ocasionales en Outlook.

- Esto actualiza la lógica de bloqueo de adjuntos en Outlook para bloquear también los adjuntos de Python.

- Se ha corregido un problema que provocaba que los complementos web accedieran a los mensajes administrados con derechos digitales.

- Se ha corregido un problema que causaba que las citas o reuniones periódicas se mostraran en un momento incorrecto al tratar de cambiar la definición de una zona horaria.

- Cuando se utiliza la zona horaria de Brasilia en el año 2019, las reuniones y citas recurrentes se muestran en la franja horaria equivocada para el año 2020. Este cambio es relevante para los clientes establecidos en la zona horaria de Brasilia o para las reuniones y citas establecidas en esa zona horaria.<br><br>Este cambio permite a Outlook reemplazar algunas opciones de configuración de zona horaria utilizadas por Outlook. Para invocar una invalidación de zona horaria, debe establecer una clave del registro para el usuario actual. El nombre de la clave del registro debe coincidir con el nombre interno de la zona horaria. El valor indica el año en el que se va a usar la regla de zona horaria en vez del año efectivo. Por ejemplo, el siguiente valor para reemplazar la clave del registro usará la regla de zona horaria de Brasil para el año 2020 como regla efectiva. HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E. Hora estándar de Sudamérica"=dword:000007e4.

- Se ha corregido un problema por el que los usuarios veían cambiar el campo de ubicación de las reuniones de forma inesperada.

- Se ha corregido un problema que provocaba que el campo Ubicación en las reuniones se actualizara de forma inesperada.

- Se ha corregido un problema que provocó que la ubicación de una reunión se volviera a añadir a la reunión de forma inesperada después de despejarla.

- Se ha corregido un tema que causó que las comas en el campo de ubicación de una reunión se convirtieran en punto y coma.

- Permite unirse a una reunión de Teams directamente a través del cliente nativo de Teams.

- Se ha corregido un problema que provocaba que los usuarios con buzones en servidores de Exchange 2010 sufrieran problemas al agregar archivos adjuntos a elementos de calendario.

- Se ha corregido un problema que provocaba que los usuarios experimentaran problemas al responder a los mensajes firmados digitalmente.

- Se ha corregido un problema que provocaba que los usuarios no pudieran abrir algunas instancias de los elementos de calendario periódicos.

- Se ha corregido un problema que hacía que el encabezado de grupo se expandiera de forma inesperada en algunos escenarios.

- Se ha corregido un problema que provocaba que el ancho del panel de carpetas cambiara de forma inesperada.

- Se ha corregido un problema por el que Outlook no pudo habilitar consejos de directiva para la Protección de pérdida de datos para usuarios que pagaron por el servicio con planes M365 Business Plus.

- Se ha corregido un problema por el que los usuarios notaban un retraso evidente al interactuar con sus carpetas de buzón mediante métodos abreviados de teclado.

- Se ha corregido un problema que podría resultar en un choque al ver el mismo elemento en varias ventanas.

- Se ha corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange" al actualizar sus reglas en Outlook.

- Se ha corregido un problema que causaba una pérdida de memoria en sesiones de Outlook muy largas.

- Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.

- Se ha corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange" al abrir el cuadro de diálogo de Reglas.

- Se ha corregido un problema por el que la opción para deshabilitar el resaltado de elementos marcados no funcionaba en algunos escenarios.

- Se ha corregido un problema que provocaba que los usuarios vieran mensajes enviados inesperadamente al presionar la tecla "S" después de cerrar el panel del comprobador de accesibilidad.

- Se ha corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.

- Se ha corregido un problema que provocaba que los usuarios experimentaran un error al cancelar la configuración de la cuenta.

- Se ha corregido un problema por el que Outlook sincronizaba inesperadamente todo el correo, incluso cuando el deslizador de sincronización estaba configurado en un ajuste menor.

- Se ha corregido un problema que provocaba que los usuarios con el Tema negro vieran texto blanco sobre un fondo blanco en el desplegable "De".

- Se ha corregido un problema que provocaba que los usuarios sufrieran un bloqueo durante la creación del perfil.

- Se ha corregido un problema que hacía que los usuarios vieran un cuadro de mensaje vacío con el botón "OK" cuando intentaban ponerse en contacto con el soporte técnico desde el contexto de la creación de la cuenta.

- Se ha corregido un problema que hacía que los usuarios vieran un cuadro de mensaje vacío con el botón "OK" cuando intentaban ponerse en contacto con el soporte técnico desde el contexto de la creación de la cuenta.

- Se ha corregido un problema que provocaba que las aplicaciones de terceros no pudiesen enviar correo electrónico.

- Se ha corregido un problema que provocaba que las categorías desapareciesen en ocasiones de los mensajes de correo electrónico.

- Se ha corregido un problema que provocaba que los usuarios de Outlook en sistemas operativos de servidor vieran el error: "Estado del antivirus: no válido. Esta versión de Windows admite la detección del antivirus, pero no se encontró ninguno" a pesar de tener el antivirus correctamente configurado.

- Se ha corregido un problema que provocaba que los delegados viesen distintas jerarquías de carpetas en diferentes equipos para los buzones compartidos.

- Se ha corregido un problema que causaba que los delegados reciban un error al editar una cita de calendario existente en el calendario de un administrador.

- Se ha corregido un problema que provocaba que los usuarios con la configuración de emulación de explorador incorrecta no pudieran completar el mensaje de autenticación de Gmail.

- Se ha corregido un problema que causaba que faltara la opción "Permitir reenvío" en las "Opciones de respuesta" de la reunión de calendario compartida cuando NO está marcada Descargar carpeta compartida.

- Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al intentar abrir archivos .msg y .oft después de una actualización de Windows.

- Se ha corregido un problema que causaba que los usuarios experimentaran ocasionalmente un bloqueo al usar el botón X de su ratón.

- Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al seleccionar determinados resultados de búsqueda.

- Se ha corregido un problema que hizo que el botón "Guardar en la nube" faltara en las herramientas de adjuntos.

- Este cambio restaura la capacidad de ver sujetos de varias líneas en el encabezado del mensaje.

- Se ha corregido un problema que causaba que los usuarios experimentaran un bloqueo cuando dos complementos agregan un botón al mismo grupo de la cinta de opciones.

- Se ha corregido un problema que provocaba que los vínculos no se agreguen a los correos electrónicos con el permiso predeterminado incorrecto de espacio empresarial cuando el permiso predeterminado de espacio empresarial se configura como "cualquiera".

- Se ha corregido un problema que provocaba que los usuarios no pudieran dirigir mensajes de correo electrónico a una lista de distribución personal.

- Se ha corregido un problema que hacía que los usuarios vieran el truncamiento del cuerpo del mensaje al reenviar mensajes HTML grandes.

- Se ha corregido un problema con la selección del algoritmo SMIME.

- Se ha corregido un problema que podía impedir que los archivos se guardaran en una ubicación de WebDAV.

- Se ha corregido un problema que evitaba que los usuarios guardaran los datos adjuntos de OneDrive desde fuera de su inquilino en su equipo local al seleccionar la opción "Guardar" en el cuadro de diálogo de seguridad.

- Se ha corregido un problema que provocaba que el cuerpo de un mensaje NDR cambiara de Unicode a ASCII después de editar el asunto.

- Se ha corregido un problema que hacía que los usuarios observaran una pérdida de memoria en el proceso de Outlook.

- Corrige un problema que provocaba que los usuarios vieran mensajes de correo electrónico enviados a una dirección que no coincidía con la dirección SMTP mostrada en determinadas circunstancias.

- Se ha corregido un problema que provocaba que el cuadro de búsqueda estuviera mal alineado en modo de PPP alto.

- Se ha corregido un problema por el que los usuarios experimentan bloqueos en Outlook al recuperar la configuración de la nube.

- Se ha corregido un problema que causó un bloqueo en la experiencia de los comentarios de búsqueda.

- Se ha corregido un problema que provocaba que los usuarios vean bloqueos ocasionales en Outlook.

- Se ha corregido un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.

- Se ha corregido un problema que provocaba que los usuarios sufrieran un bloqueo durante la creación del perfil.

- Se ha corregido un problema que provocaba que los usuarios vean bloqueos ocasionales en Outlook.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema que podía bloquear el equipo al usar el menú contextual en comentarios PPT heredados.

- Se ha mejorado un escenario de copiar y pegar: al copiar la forma en una diapositiva de PowerPoint y pegarla en otra diapositiva en bucle puede producir errores.

- Se ha corregido un problema para retransmitir la mensajería correcta a los usuarios que abren una copia de un archivo que ha mejorado los comentarios.

### <a name="project"></a>Project

- Se corrigió un problema en el que las fechas de las tareas de resumen se calculaban siempre correctamente.

- Corregido un problema en el que el evento OnUndoOrRedo no se desencadena sin ejecutar primero el método OpenUndoTransaction.

- Corregido un problema que hace que el evento ProjectBeforeTaskChange no detecte cuándo se ha desactivado o activado una tarea mediante el botón Desactivar.

- Corregido un problema por el que Project puede bloquearse al guardar proyectos creados con versiones anteriores de Project.

- Identificamos un problema en el que los usuarios podían recibir varios mensajes al abrir un proyecto de solo lectura

- Se ha corregido un problema por el que el 100 % de las tareas de tipo duración fija podían tener un cálculo del porcentaje incorrecto con menos del 100% completado.

### <a name="word"></a>Word

- Se ha corregido un problema que causaba que los usuarios experimentaran ocasionalmente un bloqueo al usar el botón X de su ratón.

- Se ha corregido un problema por el que la alineación de las palabras de un documento se descomponía al intentar editar después de imprimir con la impresión rápida.

- Corregido un problema con el ajuste de texto en una tabla.

- Corregido un problema donde al insertar líneas horizontales no eran más cortas ni centradas.

- El organizador de bloques de creación puede mostrar una alerta no válida: "Ha modificado estilos, bloques de creación".

- Se ha corregido un problema de coautoría si se habilita la Directiva FileBlick\Word2007Files.

- Se ha corregido un problema en el que Word QuickPart no funciona al agregar un campo de búsqueda cuyo nombre se ha cambiado.

- Se ha corregido un problema al combinar dos documentos en uno.

- Se ha corregido un problema con la característica Comparación para los documentos protegidos para la edición.

- Esta actualización corrige un problema en Microsoft Word por el que el texto que supera los 255 caracteres insertados durante la aplicación de una etiqueta de confidencialidad no se pudiese identificar y quitar posteriormente cambiando o quitando la etiqueta si la directiva de etiqueta aplicó un encabezado, un pie de página o una marca de agua.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema en el que los usuarios puedan experimentar demasiado uso de la red y la CPU durante la coautoría en archivos de PowerPoint grandes.

- Esta es una corrección para que la aplicación de Project no bloquee la red cuando el archivo se almacena en caché en el cliente.


- Se ha resuelto este problema mediante la actualización de los nombres de canal en el backstage con los nuevos nombres de canal en la bifurcación de enero de 2020.

- Se ha corregido este problema y en adelante, si un dispositivo se administra mediante directiva, no llamará a la API de audiencia de DMS.

- Se ha corregido un problema en el que había una eliminación incompleta al agregar y quitar aplicaciones en una sola transacción.

- Corrección de un error en la configuración de la fecha límite de actualización de ODT y GPO, en la que la fecha límite relativa sólo funciona la primera vez que se establece, la corrección permite la fecha límite relativa para las actualizaciones posteriores.

- Corrige un problema por el que las actualizaciones de Office podían haber descargado inesperadamente archivos de la CDN de Office en lugar de la fuente prevista, como un recurso compartido local o de red, o una ubicación proporcionada por el Administrador de configuración.

- Corrección de un error en la configuración de la fecha límite de actualización de ODT y GPO, en la que la fecha límite relativa sólo funciona la primera vez que se establece, la corrección permite la fecha límite relativa para las actualizaciones posteriores.

- Hemos modificado la versión AppV51 para solucionar una regresión de la AppV51 anterior.

- Hemos resuelto el problema por el que una operación interna producía una excepción en caso de error en lugar de registrarlo y continuar. Los usuarios afectados ya no serán bloqueados para recibir actualizaciones.

- Nuestro equipo ha agregado compatibilidad con clientes para informar la telemetría en los dominios de la red CDN en semianual Enterprise Preview.

- Este cambio resuelve problemas con adaptadores gráficos que aprovechan la GPU integrada de Intel.

- Este cambio garantiza que el contorno Esbozado funcione correctamente en la cinta de opciones.

- Se ha corregido un problema al abrir archivos de ubicaciones locales con algunas configuraciones de proxy específicas.

- Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.

- Se ha corregido un problema que elimina bloqueos durante las sesiones de entrega de Office y se ha mejorado la fiabilidad de la experiencia del usuario.

- Este error actualiza el extremo de la URL del servicio de configuración mejorada (ECS). Llamar a este punto de conexión más reciente tiene una tasa de éxito superior para capturar desde ECS.

- Esta actualización corrige un problema en el que con Microsoft Outlook no muestra la etiqueta de confidencialidad actual al ver o redactar mensajes.

- Corrige un problema por el que cuando hay varios documentos abiertos en Word/Excel/PowerPoint de la misma biblioteca de SharePoint, solo se analizará el primer documento abierto para el cumplimiento de las directivas.

- Para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office se firman ahora utilizando exclusivamente el algoritmo SHA-2.

- El host de Office se cerraba en Windows al activar un complemento cuando la clave del registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth estaba establecida en cero. Este cambio solucionaría el problema.

- Se ha corregido el problema por el que Access y Publisher podrían no iniciarse correctamente en función de los idiomas que se hubieran instalado.



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)





[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-july-14"></a>Versión 1908: 14 de julio
*Versión 1908 (Compilación 11929.20904)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Esta actualización corrige un problema en el que la agregación como la suma puede truncar el resultado a un valor entero.

- Esta actualización corrige un problema por el que una consulta de Unión que incluye referencias a tablas remotas (por ejemplo, tablas de SQL Server) puede hacer que Access se cierre y se reinicie.

- Esta actualización corrige un problema en Microsoft Access que puede causar el error "La consulta está dañada" cuando se ejecuta una consulta de actualización o cuando se usa una instrucción UPDATE en SQL.

### <a name="excel"></a>Excel

- La información clave en holandés para el título del documento ha sido cambiada a Alt-G.

- Se ha corregido un problema en Excel en el que las macros asignadas a formas o controles de formularios podían mostrar un mensaje de error incorrecto o funcionar en intervalos de destino incorrectos.

- Se resolvió un problema con buscar y reemplazar ese cambio donde el foco estaba en el diálogo después de encontrar el primer elemento.

- Esto corrige un problema por el cual al cambiar la forma en que se ordena y actualiza una tabla dinámica mientras se está en una sesión de co autoría con otros usuarios se podía provocar un bloqueo.

- Arreglamos un problema cuando el filtro de una tabla dinámica OLAP se estableció en un valor que se había eliminado del cubo.

- Esta actualización corrige un problema que provoca un error siempre que se utilizaba VBA para agregar una imagen al encabezado o pie de página de un gráfico.

- Se ha corregido un problema que podría haber provocado que los gráficos de líneas de dispersión no se representaran correctamente al cambiar la colección de series

- Se han corregido los colores que se usan en las vistas previas al insertar gráficos con plantillas de gráficos.

- Se resolvió un problema que causó que los gráficos de cascada y embudo se desincronizara con las tablas cuando se insertaban o eliminaban celdas.

- Se ha corregido un problema de conflicto de fusión en Excel que hacía que los usuarios tuvieran que volver a abrir el libro de trabajo para elegir los cambios.

- Se resolvió un problema que causaba un error de tiempo de ejecución de la macro que activaba las ventanas minimizadas.

- Se resolvió un problema con la personalización de la cinta que no se carga al abrir el libro de trabajo integrado.

- Se resolvió un problema que causaba que las operaciones de cortar y pegar junto a una mesa fallaran cuando se co autoría con otros.

- Se resolvió un problema que causaba interrupciones de co autoría cuando se cambiaban las propiedades personalizadas con macros en ejecución.

- Hubo un problema en el que no se podían seleccionar elementos del cuadro combinado de un formulario de WPF (Windows Presentation Foundation) que fue abierto por un complemento.

- Se ha resuelto un problema que puede haber causado un bloqueo al buscar archivos recientes cuando no hay ningún libro de trabajo abierto.

- Se ha corregido un problema que hacía que el borde de un control de cuadro de grupo no estuviera visible en la vista previa de impresión o al imprimirlo.

- Se ha corregido un problema por el que algunos usuarios podían haber experimentado múltiples ventanas emergentes cuando los enlaces externos estaban presentes en el libro de trabajo.

- Se ha corregido un problema de rendimiento que los usuarios pueden haber experimentado al usar una macro de VBA para borrar el contenido de un rango.

- Se ha corregido un problema con VBA por el que escribir valores en un rango era más lento de lo esperado.

- Se ha corregido un problema por el que la propiedad "Valor se cruza en" en el eje del gráfico cambiaba inesperadamente al guardar y volver a abrir un archivo.

- En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.

- Se ha corregido un problema que provocaba un rendimiento lento al eliminar columnas que contenían celdas combinadas.

- Se ha corregido un problema con la escala de texto en los controles de formulario cuando se mostraba la Vista previa de impresión.

- Cuando se copian datos filtrados por colores en una columna con un ancho diferente, los valores no se pegan.

- Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.

- Se ha corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.

- Se ha corregido un problema que provocaba que, al hacer clic en un hipervínculo marcado en el propio libro, se ocultara dicho libro.

- Podría producirse un bloqueo al intentar mostrar los cambios en una nueva hoja de un libro con el modo "libro compartido" heredado.

- La funcionalidad de Texto a columna puede fallar en algunas configuraciones regionales.

- Es posible que los usuarios vean un error si acceden a un rango con nombre oculto.

- Es posible que los usuarios vean un error cuando guarden cambios si usan grupos de caracteres que no están en inglés.

- Se ha corregido un problema por el que el tamaño de archivo de las imágenes en los encabezados del gráfico aumentaba cuando se guardaba el libro que contenía el gráfico.

- Problema de rendimiento con las Funciones Asincrónicas Definidas por el Usuario que hacía que se ejecutaran sincrónicamente.

- Mejoras significativas en el rendimiento de la eliminación de columnas con celdas combinadas.

- Se resolvió un problema en el que la selección de una celda después del desplazamiento podía dar lugar a que se seleccionara la celda incorrecta.

- Se ha resuelto un problema en el que la función de búsqueda puede devolver un error.

- Se ha corregido un problema que provoca la corrupción de caracteres DBCS en los libros con referencias cruzadas manteniendo los rangos de selección sincronizados con el libro con referencias cruzadas.

- Se ha corregido un problema en el que los controles de casilla podían reducirse al usar el autoajuste para ajustar el alto de fila.

- Problema de rendimiento bajo al hacer clic en el botón Color de fuente cuando un archivo tiene un formato condicional extenso.

- Se ha corregido un problema por el que el área de impresión en la vista previa de impresión no era correcta.

- Excel puede tener problemas al editar un archivo protegido desde una red compartida no confiable.

- Hemos mejorado significativamente el rendimiento del filtrado por color.

- Se ha resuelto un problema por el que los libros de trabajo creados en versiones anteriores de Office podían hacer que Excel se colgara al abrirlos en las versiones actuales de Office.

- Se habilitaron más de 16 complementos para que se muestren al navegar en el administrador de complementos.

- Se ha corregido un problema que impedía que los hipervínculos se pegaran en algunas hojas protegidas.

- Este cambio evita un problema con ciertos controladores de gráficos Intel al aprovechar el procesamiento del software.

- Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. 

- Esta actualización corrige un error por el cual los documentos de Office pueden fallar al subirlos a OneDrive para la Empresa con el mensaje "Error al cargar".

- Corregir problema en la característica Ideas de Excel, error al cargar el complemento haciendo clic en el botón Ideas en el cliente Win32. 

### <a name="onenote"></a>OneNote

- Localiza la notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.

### <a name="outlook"></a>Outlook

- Los vínculos de cid:image de los mensajes de Outlook ahora se pueden romper correctamente cuando se solicite.

- Se ha corregido un problema que causaba que los usuarios que actualizaban su buzón de la autenticación básica a la moderna, terminaban con una cuenta incorrecta asociada a su perfil de Outlook.

- Se ha corregido un problema que hacía que los complementos web accedieran a los mensajes de la administración de derechos digitales cuando no deberían hacerlo.

- Se ha corregido un problema que causó que las URLS de enlace simple no se mostraran en algunos enlaces seguros.

- Esto actualiza la lógica de bloqueo de adjuntos en Outlook para bloquear también los adjuntos de Python.

- Corrige un problema que causaba que un subconjunto de usuarios de POP3 viesen todos los correos electrónicos como texto sin formato, independientemente de la configuración. Esta corrección restaurará la vista de los mensajes con formato HTML.

- Se ha corregido un problema que hacía que los usuarios experimentaran un error de permiso al copiar elementos de su calendario principal a un calendario de grupo.

- Se ha corregido un problema que hacía que los usuarios no pudieran acceder a las sugerencias de ubicación a través de un lector de pantalla.

- Se ha corregido un problema por el que los usuarios notaban un retraso evidente al interactuar con sus carpetas de buzón mediante métodos abreviados de teclado.

- Se ha corregido un problema que causaba una pérdida de memoria en sesiones de Outlook muy largas.

- Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.

- Se ha corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange" al abrir el cuadro de diálogo de Reglas.

- Se ha corregido un problema que haría que los usuarios experimentaran un bloqueo en Outlook al interactuar con ciertos vínculos seguros.

- Se ha corregido un problema que causaba ambigüedad para los administradores sobre si un delegado ya había respondido a una convocatoria de reunión determinada.

- Se ha corregido un problema que hizo que los usuarios experimentaran un fallo al procesar algunas respuestas de descubrimiento automático.

- Se ha corregido un problema que hacía que los usuarios vieran un cuadro de mensaje vacío con el botón "OK" cuando intentaban ponerse en contacto con el soporte técnico desde el contexto de la creación de la cuenta.

- Este cambio permite a los administradores habilitar una política para preferir el correo electrónico de la cuenta proporcionada en los avisos de autorización de AutoDiscover sobre el UPN. De forma predeterminada, detección automática prefiere el UPN de la cuenta, cuando está disponible.

- Se ha corregido un problema que provocaba que los usuarios vieran un error en la búsqueda con grupos modernos.

- Se ha corregido un problema que causaba que los usuarios de Outlook se quedaran atascados en el estado "Necesita contraseña" en ciertos escenarios.

- Se ha corregido un problema que provocaba que los usuarios experimentaran errores de sincronización al procesar mensajes de conflicto.

- Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al abrir archivos .msg y .oft después de aplicar una actualización reciente de Windows.

- Se ha corregido un problema que provocaba que los usuarios experimentaran un error en la pantalla de "carga del perfil" al iniciar Outlook.

- Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al seleccionar determinados resultados de búsqueda.

- Se ha corregido un problema que hizo que el botón "Guardar en la nube" faltara en las herramientas de datos adjuntos.

- De forma predeterminada, las etiquetas de directivas de retención muestran el período de tiempo de retención entre paréntesis. Esto proporciona una clave del registro para permitir que los administradores especifiquen que solo se debería mostrar el nombre de la directiva. HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = predeterminado 1 = solo se mostrará el PolicyName para el texto de la política de retención.

- Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al cerrar Outlook.

- Se ha corregido un problema que provocaba que los clientes vieran una lista de salas vacías en algunos escenarios.

- Se ha corregido un problema que provocaba que los usuarios viesen bloqueos intermitentes al cambiar de vista.

- Corrige un problema que provocaba que los usuarios tuvieran problemas al intentar sincronizar carpetas del calendario compartido con el OST, lo que producía errores en los permisos al tratar de interactuar con estas carpetas.

- Se ha corregido un problema que causaba que los usuarios sufrieran un error al visualizar más de 30 calendarios en un entorno Citrix. Aquí está el [KB individual, donde se ha documentado esto para versiones anteriores](https://support.microsoft.com/en-us/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)

- Corrige un problema con la selección de algoritmos SMIME.

- Se ha corregido un problema que provocó que las sugerencias de la política no se mostraran al utilizar un remitente alternativo.

- Se ha corregido un problema que hizo que los usuarios vieran sugerencias de salas para reuniones que se produjeron fuera de las horas de disponibilidad de dichas salas.

- Se ha corregido un problema para los usuarios que no hablan inglés, en el que la línea de asunto de un correo electrónico era increíblemente pequeña.

- Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al intentar crear una regla a partir de un mensaje de "Conversación perdida".

- Se ha corregido un problema que causaba que algunos usuarios vieran carpetas especiales duplicadas al agregar una cuenta de Exchange secundaria.

- Se ha corregido un problema que hacía que los usuarios vieran el truncamiento del cuerpo del mensaje al reenviar mensajes HTML grandes.

- Se ha corregido un problema que hacía que los usuarios observaran una pérdida de memoria en el proceso de Outlook.

- Se ha corregido un problema que hacía que los usuarios experimentaran bloqueos intermitentes al actualizar la información de presencia.

- Se ha corregido un problema que provocaba un error ocasional en la búsqueda de la carpeta actual.

- Se ha corregido un problema que hizo que algunos usuarios encontraran errores de autenticación al intentar recuperar su configuración de nube para Outlook.

- Se ha corregido un problema que causó un bloqueo en la experiencia de los comentarios de búsqueda.

- Se ha corregido un problema que hizo que los usuarios experimentaran un fallo al procesar algunas respuestas de descubrimiento automático.

- Se ha corregido un problema que hacía que los usuarios experimentaran bloqueos intermitentes al actualizar la información de presencia.

### <a name="powerpoint"></a>PowerPoint

- Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. 

- Este cambio restaura el nombre accesible de los controles de vídeo de PowerPoint.

- Se ha corregido un problema que podría impedir que comiencen algunas animaciones

- Se ha corregido un problema en el que al copiar una diapositiva de una presentación a otra, se pueden crear patrones duplicados.<br>

- Se ha mejorado un escenario de copiar y pegar: al copiar la forma en una diapositiva de PowerPoint y pegarla en otra diapositiva en bucle puede producir errores.

- Se ha corregido un problema con el marcador de resaltado: los textos blancos con un marcador oscuro se imprimen como negros en escala de grises.

- Los archivos con nuevos comentarios modernos mostrarán una advertencia amarilla si se abren en una versión no soportada.

- Se ha corregido un problema que producía un rendimiento más lento entre los usuarios de colaboración.

- Corrección de confiabilidad: se ha corregido un problema por el que el complemento de terceros podía bloquearse en PowerPoint.

- Se ha corregido un problema que puede producirse cuando un archivo que se abre incrementalmente contiene una diapositiva con más de una secuencia multimedia incrustada.

- Se ha corregido un problema con el método Shape.Paste: cuando el usuario copiaba y pegaba la forma con el método Shape.Paste, se cambiaba la selección a la forma pegada.

- Se ha corregido un problema por el que es posible que la barra de mensajes de advertencia de seguridad no aparezca para los complementos en los que no se confía al iniciar PowerPoint por primera vez.

- Se ha corregido un problema por el que algunos complementos producían errores inesperados alrededor de las formas en gráficos.

- Evita que los usuarios de PowerPoint se encuentren con un error cuando intentan hacer una presentación en línea.

### <a name="project"></a>Project

- Se ha corregido un problema para permitir que los usuarios en Windows 7 puedan abrir proyectos desde Project Web App y sitios de SharePoint.

- Se identificó un problema en el que los usuarios podían recibir varios mensajes al abrir un proyecto de sólo lectura.

- El comando Level All no resuelve adecuadamente una sobreasignación de recursos.

- Si tiene una tarea sin nada de trabajo, es posible que la tarea no se pueda marcar como completada y siempre se mostrará en el 99 %.

- Se ha corregido un problema en el que el trabajo real puede ser diferente entre el parte de horas y el plan del proyecto debido a que los calendarios de recursos no se actualizan cuando cambia el calendario base.

### <a name="skype"></a>Skype

- Se ha corregido el nombre del título de la conversación con pestañas mientras se mantenía más de una conversación.

### <a name="visio"></a>Visio

- La exportación como SVG de Visio estaba fallando por una variedad de formas.

### <a name="word"></a>Word

- Los vínculos de cid:image de los mensajes de Outlook ahora se pueden romper correctamente cuando se solicite.

- Se ha corregido un problema que podría haber provocado problemas de escala al imprimir en impresoras Deskjet

- Se ha corregido un problema al Ajustar texto en la tabla.

- Hemos corregido un problema en los cambios de pista que a veces van en un bucle infinito.

- Corregido un problema ocasional en el que al guardar un archivo existente siempre aparece el cuadro de diálogo Guardar como, pero el archivo nunca se guarda.

- Se ha corregido un problema al combinar dos documentos en uno.

- Se ha corregido un problema con la característica Comparación para los documentos protegidos para la edición.

- Se han corregido varios problemas que hacían que la aplicación se colgara al apagarse. También se corrigieron ciertos fallos relacionados con los complementos.

### <a name="office-suite"></a>Conjunto de programas de Office

- Corregido el problema de la identificación incorrecta del nombre de la nueva era "Reiwa" en hiragana y kanji como una expresión mal escrita o poco gramatical.

- Corregido un problema que hacía que los usuarios recibieran el mensaje "Lo sentimos, algo nos impide compartir esto" al intentar compartir archivos almacenados en SharePoint 2016.

- Se ha solucionado un problema que podía causar la pérdida de datos en sesiones que implicaban tanto la co autoría como la edición fuera de línea en PowerPoint.

- Esta es una solución para un fallo que los usuarios podrían sufrir al abrir un archivo.

- En algunos casos, un archivo de sharepoint respaldado por un motor de sincronización podría mostrar "Guardado" pero no haber guardado realmente ningún cambio, lo que provocaría la pérdida de datos.

- Se resolvió un problema que impedía a los usuarios guardar documentos de Word, Excel y PowerPoint. Este problema afecta a los usuarios que crean un nuevo archivo y muestra la opción "Guardar como diálogo" después de hacer clic en el icono Guardar o presionar Ctrl + S.

- Se ha corregido un bloqueo en Word al dejar una API obsoleta.

- Se ha corregido un problema por el que los caracteres katakana de medio ancho no giraban correctamente cuando estaban en cuadros de texto verticales en PowerPoint.

- Se ha corregido un problema de perf en Win7 en el que la galería de formas de inserción de la cinta en todas las aplicaciones tardaba aproximadamente 4 segundos en aparecer.

- Corregido un error por el que la información de accesibilidad no se mostraba en la losa del lugar de información de los bastidores.

- Mejora de la fiabilidad del proceso de actualización de Office en lo que respecta a la integridad del registro.

- Hemos actualizado los nombres de canal para las bifurcaciones de enero y julio de 2019 con los nuevos nombres de canal.

- Se ha corregido un problema por el que las actualizaciones se bloqueaban inesperadamente en las redes de uso medido.

- Corrección de un error en la configuración de la fecha límite de actualización de ODT y GPO, en la que la fecha límite relativa sólo funciona la primera vez que se establece, la corrección permite la fecha límite relativa para las actualizaciones posteriores.

- En determinadas circunstancias, los accesos directos de Office pueden desaparecer tras una actualización. Esta actualización mejora la fiabilidad en la publicación de los accesos directos de Office.

- Corrige un problema por el que las actualizaciones de Office podían haber descargado inesperadamente archivos de la CDN de Office en lugar de la fuente prevista, como un recurso compartido local o de red, o una ubicación proporcionada por el Administrador de configuración.

- Se ha corregido un problema en el que una actualización no se aplicaría en ciertos casos en los que el usuario no es un administrador y la cuenta del sistema no tenía conectividad de red.

- Se ha solucionado un problema por el que los mensajes de actualización de Office aparecían en un idioma diferente al esperado. En el futuro, los mensajes de actualización de Office coincidirán correctamente con el idioma de visualización de Windows.

- Se ha mejorado la confiabilidad al descargar las actualizaciones de Office al reanudar las descargas que pueden haberse interrumpido anteriormente.

- Se han corregido los problemas relacionados con la propiedad Textbox/Shape Autofit en los plug-ins de terceros.

- Este cambio corrige el procesamiento de imágenes después de abrir un archivo dañado.

- Este cambio corrige el procesamiento lento de algunos gráficos de dispersión con marcadores.

- Se ha corregido un problema por el que las vistas de árboles grandes podían dar lugar a un bloqueo

- Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.

- Para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office se firman ahora utilizando exclusivamente el algoritmo SHA-2.

- Para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office se firman ahora utilizando exclusivamente el algoritmo SHA-2.


[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1902-july-14"></a>Versión 1902: 14 de julio
*Versión 1902 (compilación 11328.20624)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)

## <a name="version-1908-june-09"></a>Versión 1908: 09 de junio
*Versión 1908 (compilación 11929.20838)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema por el que Excel podría no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía en Teams.

- Se ha corregido un problema con la escala de las casillas de verificación en los controles de formulario cuando se imprimen.

- Podría producirse un bloqueo al intentar mostrar los cambios en una nueva hoja de un libro con el modo "libro compartido" heredado.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema que hacía que los usuarios vieran truncado el cuerpo del mensaje al reenviar mensajes HTML grandes.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Hemos actualizado los nombres de canal para las bifurcaciones de enero y julio de 2019 con los nuevos nombres de canal.


[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1902-june-09"></a>Versión 1902: 09 de junio
*Versión 1902 (compilación 11328.20602)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Hemos actualizado los nombres de canal para las bifurcaciones de enero y julio de 2019 con los nuevos nombres de canal.

- Se han eliminado las referencias obsoletas de los archivos de línea base que producian errores en la compilación C2R.



[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-may-12"></a>Versión 1908: 12 de mayo
*Versión 1908 (compilación 11929.20776)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Cuando se copian datos filtrados por colores en una columna con un ancho diferente, los valores no se pegan.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al abrir archivos .msg y .oft después de aplicar una actualización reciente de Windows.

### <a name="word"></a>Word

- Se ha corregido un problema al combinar 2 documentos en uno.

- Se ha corregido un problema con la característica Comparar de los documentos protegidos para la edición.

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-1902-may-12"></a>Versión 1902:12 de mayo
*Versión 1902 (compilación 11328.20586)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha corregido un problema que hacía que los usuarios experimentaran un bloqueo al abrir archivos .msg y .oft después de aplicar una actualización reciente de Windows.

- De forma predeterminada, las etiquetas de directivas de retención muestran el período de tiempo de retención entre paréntesis. Esto proporciona una clave del registro para permitir que los administradores especifiquen que solo se debería mostrar el nombre de la directiva. HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration. 0 = predeterminado.  1 = solo se mostrará el nombre de directiva del texto de la directiva de retención.


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-1908-may-04"></a>Versión 1908: 4 de mayo
*Versión 1908 (Compilación 11929.20752)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al seleccionar determinados resultados de búsqueda.

- Se ha corregido un problema que hacía que el botón "Guardar en la nube" faltara en las Herramientas de datos adjuntos.

- De forma predeterminada, las etiquetas de directivas de retención muestran el período de tiempo de retención entre paréntesis. Esto proporciona una clave del registro para permitir que los administradores especifiquen que solo se debería mostrar el nombre de la directiva. HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration. 0 = predeterminado 1 = solo se mostrará el nombre de directiva del texto de la directiva de retención.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema en Visual Basic para las aplicaciones de Microsoft Office, por el que la aplicación de Office consideraba como corruptos ciertos proyectos de VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre o la ruta de la biblioteca.

## <a name="version-1902-may-04"></a>Versión 1902: 4 de mayo
*Versión 1902 (compilación 11328.20572)*

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema en Visual Basic para las aplicaciones de Microsoft Office, por el que la aplicación de Office consideraba como corruptos ciertos proyectos de VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre o la ruta de la biblioteca.

## <a name="version-1908-april-26"></a>Versión 1908: 26 de abril
*Versión 1908 (Compilación 11929.20736)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema de rendimiento que los usuarios pueden haber experimentado al usar una macro de VBA para borrar el contenido de un rango.

- Se ha corregido un problema con VBA por el que escribir valores en un rango era más lento de lo esperado.

- Se ha corregido un problema por el que la propiedad "Value Crosses At" en el eje del gráfico cambiaba inesperadamente al guardar y volver a abrir un archivo.

- En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.


### <a name="onenote"></a>OneNote

- Localiza la notificación que permite al usuario obtener más información sobre las medidas temporales que se implementan en la experiencia de usuario de OneNote para mejorar la sincronización y la estabilidad del servicio.


## <a name="version-1908-april-14"></a>Versión 1908: 14 de abril
*Versión 1908 (compilación 11929.20708)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema que provocaba un rendimiento lento al eliminar columnas que contenían celdas combinadas.

- Se ha corregido un problema con la escala de texto en los controles de formulario cuando se mostraba la Vista previa de impresión.

### <a name="skype"></a>Skype

- Se ha corregido el nombre del título de la conversación con pestañas mientras se mantenía más de una conversación.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que los usuarios experimentaran un bloqueo al cerrar Outlook.

- Se ha corregido un problema que provocaba que los clientes vieran una lista de salas vacías en algunos escenarios.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema con el marcador de resaltado: los textos blancos con un marcador oscuro se imprimen como negros en escala de grises.

### <a name="word"></a>Word

- Se ha corregido un problema al Ajustar texto en la tabla.


## <a name="version-1902-april-14"></a>Versión 1902: 14 de abril
*Versión 1902 (compilación 11328.20564)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-march-10"></a>Versión 1908: 10 de marzo
*Versión 1908 (compilación 11929.20648)*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema por el que algunos usuarios podían haber experimentado múltiples ventanas emergentes cuando los enlaces externos estaban presentes en el libro de trabajo.


- La funcionalidad de Texto a columna puede fallar en algunas configuraciones regionales.


- Los usuarios pueden encontrar un error al acceder a un rango con nombre oculto.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema con el método Shape.Paste: cuando el usuario copiaba y pegaba la forma con el método Shape.Paste, se cambiaba la selección a la forma pegada.


### <a name="word"></a>Word

- Corregido un problema ocasional en el que al guardar un archivo existente siempre aparece el cuadro de diálogo Guardar como, pero el archivo nunca se guarda.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Este cambio corrige el procesamiento lento de algunos gráficos de dispersión con marcadores.

## <a name="version-1902-march-10"></a>Versión 1902: 10 de marzo
*Versión 1902 (compilación 11328.20554)*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)

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

## <a name="version-1902-february-11"></a>Versión 1902: 11 de febrero
*Versión 1902 (Compilación 11328.20526)*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Corregido un problema que hizo que los usuarios encontraran errores de "algoritmo de cifrado no admitido" al enviar un correo electrónico cifrado.


### <a name="word"></a>Word

- Se ha corregido un bloqueo en Word al dejar una API obsoleta.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO INICIO)

## <a name="version-1808-february-11"></a>Versión 1808: 11 de febrero
*Versión 1808 (compilación 10730.20438)*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-january-14"></a>Versión 1908: 14 de enero
*Versión 1908 (compilación 11929.20562)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="access"></a>Access

- **Mantener un seguimiento de los objetos de base de datos:** ver claramente la pestaña activa, arrastrar las pestañas para reorganizarlas fácilmente y cerrar los objetos de base de datos con un solo clic.

- **Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar. Cambiar de una a otra nunca había sido tan fácil. [Más información](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Zoom con más espacio:** agrandar el cuadro de Zoom, cambiar la fuente y hacer que Zoom lo recuerde todo. [Más información](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a>Excel

- **Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar. Cambiar de una a otra nunca había sido tan fácil. [Más información](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Aumentar el alcance de su contenido:** ¿necesita que las presentaciones sean accesibles? Deje que el comprobador de accesibilidad le ayude sin estorbar. Pruébelo en Revisar > Comprobar accesibilidad y le informaremos en la barra de estado de cuando necesitemos que compruebe algo.

- **Encuentre ese archivo rápido:** ¿Busca un archivo en el que trabajó recientemente? Basta con que escriba en el cuadro de búsqueda en la página Archivo > Inicio para encontrar el archivo que busca.

- **Vea cómo la hoja de cálculo cobra vida**: inserte gráficos 3D animados para ver corazones que laten, planetas en órbita y dinosaurios a toda velocidad por el libro. [Más información](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- **Obtener más información sobre los datos:** el nuevo botón Ideas busca patrones en los datos y los usa para crear sugerencias inteligentes y personalizadas. [Más información](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- **La colaboración es ahora más fácil**: las mejoras en la coautoría significan que al trabajar con el formato condicional, los estilos de celda y otros elementos, los cambios se combinan perfectamente con los de los colaboradores.

- **Unir tablas en columnas similares:** obtener y transformar (Power Query) ahora ofrece una lógica de coincidencia de texto (también denominada coincidencia aproximada) al comparar columnas en la combinación de tablas. [Más información](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- **Programar rápidamente con mejoras de Power Query:** termine rápidamente el código con colores de sintaxis y la función de autocompletar. Además, descubra fácilmente funciones, columnas y parámetros.

- **Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea. Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido. [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a>Outlook

- **Hemos actualizado la experiencia de usuario de Outlook para usted:** una experiencia simplificada, anteriormente disponible para su vista previa con Próximamente, diseñada para ayudarle a centrarse en lo más importante. [Más información](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- **Una cinta simplificada que además es personalizable:** disfrute de una sola fila simplificada con los botones más usados. Cambie fácilmente entre la vista clásica y la simplificada, y ancle o desancle comandos. [Más información](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- **Seguir trabajando mientras mueve mensajes:** Outlook ahora mueve los mensajes en segundo plano, por lo que puede seguir trabajando mientras mueve una gran cantidad de mensajes entre carpetas.

- **Creación en el tiempo entre las reuniones consecutivas:** asigne a los asistentes el tiempo para descansar o desplazarse entre las distintas ubicaciones al configurar reuniones para finalizar 5 a 10 minutos antes de forma predeterminada.

- **Seleccione su acción favorita:** ¿no usa Etiquetar ni Eliminar? ¿Qué hay de Archivar o Marcar como leído? Personalice el menú de acciones rápidas con los comandos que use más frecuentemente.

- **Verán los memes que comparta:** cuando un texto o imágenes estáticas no consigan comunicar lo que desea, use un GIF animado para aclararlo. [Más información](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)

- **Una forma más rápida de agregar cuentas:** gracias a las mejoras de configuración de cuentas, es más fácil que nunca agregar cuentas de Outlook.com y Gmail que usen la autenticación en dos fases a Outlook. [Más información](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- **Despídase de límites de sincronización:** las mejoras de Outlook significan que se ha eliminado el límite de carpetas y sincronizar los buzones compartidos.

- **Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea. Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido. [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a>PowerPoint

- **Mejor transformación:** asigne un nombre a las formas para tener más control sobre cómo se transforman. [Más información](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- **Encuentre ese archivo rápido:** ¿Busca un archivo en el que trabajó recientemente? Basta con que escriba en el cuadro de búsqueda en la página Archivo > Inicio para encontrar el archivo que busca.

- **Aumentar el alcance de su contenido:** ¿necesita que las presentaciones sean accesibles? Deje que el comprobador de accesibilidad le ayude sin estorbar. Pruébelo en Revisar > Comprobar accesibilidad y le informaremos en la barra de estado de cuando necesitemos que compruebe algo.

- **Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar. Cambiar de una a otra nunca había sido tan fácil. [Más información](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Los vídeos en línea tienen un nuevo hogar:** guarde un vídeo en Microsoft Stream para que puedan verlo todas las personas de su organización. Inserte el vínculo del vídeo y disfrute de una presentación multimedia en una fracción del tamaño del archivo. [Más información](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **Guardar los cambios a medida que los realiza:** cargue el archivo en OneDrive para asegurarse de que todas las actualizaciones se guardan automáticamente.

- **Pregunte a su público con un cuestionario o una encuesta:** coloque un cuestionario o una encuesta en una diapositiva. Office recopila y almacena las respuestas para usted. [Más información](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)

- **Nunca fue tan fácil insertar un vídeo en línea:** ¿quiere poner un vídeo de Vimeo o de YouTube en la diapositiva? Solo necesita el vínculo a la página del vídeo. [Más información](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea. Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido. [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a>Project

- **Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar. Cambiar de una a otra nunca había sido tan fácil. [Más información](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a>Visio

- **Exportar diagramas de proceso a Word:** Agregue automáticamente contenido del diagrama, como formas y metadatos, a un documento de Word. Después, personalice el documento para crear instrucciones de procesos y manuales de funcionamiento. [Más información](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- **Doble toma en diagramas de flujo de datos:** Los magníficos nuevos diseños para los diagramas de flujo del visualizador de datos son limpios, nítidos y fáciles de entender. Haga clic en la pestaña Diseño para ver las opciones.

- **Galerías de símbolos integradas en Azure:** diseñe una aplicación de nube o planee una arquitectura con las múltiples galerías de símbolos de Azure. [Más información](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- **Adiós a los vínculos rotos de Excel:** ¿no encuentra el libro de Excel vinculado a un diagrama de visualizador de datos? Solo tiene que vincularlo de nuevo y ¡listo! [Más información](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)

- **Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar. Cambiar de una a otra nunca había sido tan fácil. [Más información](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Exportar objetos visuales de Visio desde Power BI**: los objetos visuales de Visio para Power BI ahora se mostrarán correctamente al exportar informes de Power BI como archivos PDF, archivos de PowerPoint, etc. [Más información](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a>Word

- **El modo herramientas de aprendizaje tiene soporte adicional para más colores de página:** las herramientas de aprendizaje de Word son compatibles con más colores de tema de página, lo que permite cambiar el color de fondo de la página. Muchas personas tienen dificultades para leer con un fondo totalmente blanco o negro, por lo que hemos ampliado la elección de colores en Word para PC y Mac.

- **Edición natural con el Editor para entradas de lápiz:** con un solo trazo, divida o una palabras, agregue una nueva línea o inserte palabras con el lápiz. [Más información](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- **Su documento: de estático a mágico:** transforme el documento en una página web interactiva y fácil de compartir con un aspecto fantástico en cualquier dispositivo. [Más información](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)

- **Aumentar el alcance de su contenido:** ¿necesita hacer que sus documentos sean accesibles? Deje que el comprobador de accesibilidad le ayude sin estorbar. Pruébelo en Revisar > Comprobar accesibilidad y le informaremos en la barra de estado de cuando necesitemos que compruebe algo.

- **Encuentre ese archivo rápido:** ¿Busca un archivo en el que trabajó recientemente? Basta con que escriba en el cuadro de búsqueda en la página Archivo > Inicio para encontrar el archivo que busca.

- **Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar. Cambiar de una a otra nunca había sido tan fácil. [Más información](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Mejorar la comprensión con el foco de línea:** desplácese por un documento línea por línea sin distracciones. Ajuste el foco para ver una, tres o cinco líneas a la vista. [Más información](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)

- **Guarde sus cambios a medida que se produzcan:** Suba su archivo a OneDrive para asegurarse de que todas sus actualizaciones se guarden automáticamente.

- **Consiga su atención con\@menciones:** use @menciones en los comentarios para avisar a los compañeros de trabajo cuando necesite su participación. [Más información](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **Buscar y disfrutar:** hemos agregado una búsqueda para insertar iconos que hacen que sea más fácil encontrar el icono que desea. Y, mientras hace la selección, el botón Insertar le indica cuántos ha elegido. [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- **Encuentra ese archivo rápido:** ¿Busca un archivo en el que haya trabajado recientemente? Sólo tiene que escribir en el cuadro de búsqueda de la pestaña Archivo > Abrir para encontrar el archivo que está buscando.

- **Guardar los cambios a medida que los realiza:** cargue el archivo en OneDrive para asegurarse de que todas las actualizaciones se guardan automáticamente.

- **Controles de privacidad:** nuevos controles para datos de diagnóstico y experiencias conectadas, actualizados y mejorados. [Más información](/DeployOffice/privacy/overview-privacy-controls?toc=%2fdeployoffice%2ftoc.json)

- **Los iconos de Office tienen un nuevo aspecto:** los iconos de Office se han rediseñado para reflejar las sencillas, inteligentes y eficaces experiencias de Office.

- **Instalación de Microsoft Teams:** Microsoft Teams se instala de forma predeterminada en las instalaciones existentes de Office 365 ProPlus. [Más información](/DeployOffice/teams-install)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Esta actualización corrige un problema en el que la agregación como la suma puede truncar el resultado a un valor entero.

- Esta actualización corrige un problema por el que una consulta de Unión que incluye referencias a tablas remotas (por ejemplo, tablas de SQL Server) puede hacer que Access se cierre y se reinicie.

- Esta actualización corrige un problema en Microsoft Access que puede causar el error &quot;La consulta está dañada&quot; cuando se ejecuta una consulta de actualización o cuando se usa una instrucción UPDATE en SQL.

### <a name="excel"></a>Excel

- La información clave en holandés para el título del documento ha sido cambiada a Alt-G.

- Se ha corregido un problema en Excel en el que las macros asignadas a formas o controles de formularios podían mostrar un mensaje de error incorrecto o funcionar en intervalos de destino incorrectos.

- Se resolvió un problema con buscar y reemplazar ese cambio donde el foco estaba en el diálogo después de encontrar el primer elemento.

- Esto corrige un problema por el cual al cambiar la forma en que se ordena y actualiza una tabla dinámica mientras se está en una sesión de co autoría con otros usuarios se podía provocar un bloqueo.

- Arreglamos un problema cuando el filtro de una tabla dinámica OLAP se estableció en un valor que se había eliminado del cubo.

- Se han corregido los colores que se usan en las vistas previas al insertar gráficos con plantillas de gráficos.

- Se ha corregido un problema que podía impedir que los gráficos de líneas de dispersión se representaran correctamente al cambiar la colección de series.

- Se resolvió un problema que causó que los gráficos de cascada y embudo se desincronizara con las tablas cuando se insertaban o eliminaban celdas.

- Se ha corregido un problema de conflicto de fusión en Excel que hacía que los usuarios tuvieran que volver a abrir el libro de trabajo para elegir los cambios.

- Se resolvió un problema con la personalización de la cinta que no se carga al abrir el libro de trabajo integrado.

- Se resolvió un problema que causaba un error de tiempo de ejecución de la macro que activaba las ventanas minimizadas.

- Se resolvió un problema con la personalización de la cinta que no se carga al abrir el libro de trabajo integrado.

- Se resolvió un problema que causaba que las operaciones de cortar y pegar junto a una mesa fallaran cuando se co autoría con otros.

- Se resolvió un problema que causaba interrupciones de co autoría cuando se cambiaban las propiedades personalizadas con macros en ejecución.

- Hubo un problema en el que no se podían seleccionar elementos del cuadro combinado de un formulario de WPF (Windows Presentation Foundation) que fue abierto por un complemento.

- Se ha resuelto un problema que puede haber causado un bloqueo al buscar archivos recientes cuando no hay ningún libro de trabajo abierto.

- Problema de rendimiento con las Funciones Asincrónicas Definidas por el Usuario que hacía que se ejecutaran sincrónicamente.

- Mejoras significativas en el rendimiento de la eliminación de columnas con celdas combinadas.

- Se resolvió un problema en el que la selección de una celda después del desplazamiento podía dar lugar a que se seleccionara la celda incorrecta.

- Se ha resuelto un problema en el que la función de búsqueda puede devolver un error.

- Se ha resuelto un problema por el que los libros de trabajo creados en versiones anteriores de Office podían hacer que Excel se colgara al abrirlos en las versiones actuales de Office.

- Problema de rendimiento bajo al hacer clic en el botón Color de fuente cuando un archivo tiene un formato condicional extenso.

- Se ha corregido un problema por el que el área de impresión en la vista previa de impresión no era correcta.

- Excel puede tener problemas al editar un archivo protegido desde una red compartida no confiable.

- Hemos mejorado significativamente el rendimiento del filtrado por color.

- Se resolvió un problema que impedía que los hipervínculos se pegaran en algunas hojas protegidas.

- Se habilitó más de 16 complementos para que se muestren al navegar en el administrador de complementos.

- Este cambio evita un problema con ciertos controladores de gráficos Intel aprovechando la renderización de software.

- Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. 

- Esta actualización corrige un error por el cual los documentos de Office pueden fallar al subirlos a OneDrive para la Empresa con el mensaje "Error al cargar".

- Corregir problema en la característica Ideas de Excel, error al cargar el complemento haciendo clic en el botón Ideas en el cliente Win32.

### <a name="outlook"></a>Outlook

- Los vínculos de cid:image de los mensajes de Outlook ahora se pueden romper correctamente cuando se solicite.

- Se ha corregido un problema que causaba que los usuarios que actualizaban su buzón de la autenticación básica a la moderna, terminaban con una cuenta incorrecta asociada a su perfil de Outlook.

- Corregido un problema que hizo que los complementos web accedieran a los mensajes de Digital Rights Managed cuando no deberían hacerlo.

- Corregido un problema que causó que las URLS de enlace simple no se mostraran en algunos enlaces seguros.

- Esto actualiza la lógica de bloqueo de adjuntos en Outlook para bloquear también los adjuntos de Python.

- Corregido un problema que hacía que un subconjunto de usuarios POP3 viera todos sus correos electrónicos formateados en texto plano, independientemente de la configuración. Esta corrección restaurará la vista de los mensajes con formato HTML.

- Corregido un problema que hacía que los usuarios experimentaran un error de permiso al copiar elementos de su calendario principal a un calendario de grupo.

- Corregido un problema que hacía que los usuarios no pudieran acceder a las sugerencias de ubicación a través de un lector de pantalla.

- Corregido un problema que hacía que los usuarios vieran un retraso notable al interactuar con sus carpetas de buzón de correo a través de métodos abreviados de teclado.

- Corregido un problema que causaba una fuga de memoria en sesiones de Outlook muy largas.

- Corregido un problema que hacía que los usuarios vieran el mensaje "Las reglas de este equipo no coinciden con las reglas de Microsoft Exchange" al abrir el cuadro de diálogo Reglas.

- Corregido un problema que haría que los usuarios experimentaran un bloqueo en Outlook al interactuar con ciertos vínculos seguros.

- Corregido un problema que causó ambigüedad a los gerentes en cuanto a si un delegado ya había respondido o no a una determinada solicitud de reunión.

- Corregido un problema que hizo que los usuarios experimentaran un fallo al procesar algunas respuestas de descubrimiento automático.

- Se ha solucionado un problema que hacía que los usuarios vieran un cuadro de mensaje vacío con el botón "ok" cuando intentaban ponerse en contacto con el soporte técnico desde el contexto de la creación de la cuenta.

- Este cambio permite a los administradores habilitar una política para preferir el correo electrónico de la cuenta proporcionada en los avisos de autorización de AutoDiscover sobre el UPN. De forma predeterminada, detección automática prefiere el UPN de la cuenta, cuando está disponible.

- Se ha corregido un problema que provocaba que los usuarios vieran un error en la búsqueda con grupos modernos.

- Solucionó un problema que causaba que los usuarios de Outlook se quedaran atascados en el estado "Necesita contraseña" en ciertos escenarios.

- Se abordó un problema que hizo que los usuarios vieran sugerencias de salas para reuniones que se produjeron fuera de las horas de disponibilidad de dichas salas.

- Corregido un problema que hizo que los usuarios encontraran errores de "algoritmo de cifrado no admitido" al enviar un correo electrónico cifrado.

- Corregido un problema para los usuarios que no hablan inglés, en el que la línea de asunto de un correo electrónico era increíblemente pequeña.

- Corregido un problema que hacía que algunos usuarios vieran duplicadas las carpetas especiales creadas al añadir una cuenta de Exchange secundaria.

- Corregido un problema que hacía que los usuarios experimentaran un bloqueo al intentar crear una regla a partir de un mensaje de "Conversación perdida".

- Corregido un problema con la selección del algoritmo SMIME.

- Corregido un problema que hacía que no se mostraran las sugerencias de política cuando se utilizaba un remitente alternativo.

- Corregido un problema que hacía que los usuarios observaran una fuga de memoria en el proceso de Outlook.

- Corregido un problema que hacía que los usuarios experimentaran bloqueos intermitentes al actualizar la información de presencia.

- Corregido un problema que causaba que la búsqueda de la carpeta actual fallara de forma intermitente.

- Corregido un problema que hizo que algunos usuarios encontraran errores de autenticación al intentar recuperar su configuración de nube para Outlook.

- Corregido un problema que causó un bloqueo en la experiencia de los comentarios de búsqueda.

- Corregido un problema que hizo que los usuarios experimentaran un fallo al procesar algunas respuestas de descubrimiento automático.

- Corregido un problema que hacía que los usuarios experimentaran bloqueos intermitentes al actualizar la información de presencia.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema por el que algunos complementos producían errores inesperados alrededor de las formas en gráficos.

- Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. 

- Este cambio restaura el nombre accesible de los controles de vídeo de PowerPoint.

- Hemos corregido un problema que podría impedir que se inicien algunas animaciones.

- Hemos corregido un problema en el que al copiar una diapositiva de una presentación a otra, se pueden crear patrones duplicados.

- Los archivos con nuevos comentarios modernos mostrarán una advertencia amarilla si se abren en una versión no soportada

- Fiabilidad fija: corregido un problema por el que el complemento de terceros podía bloquearse en PowerPoint.

- Corregido un problema por el que los caracteres katakana de medio ancho no giraban correctamente cuando estaban en cuadros de texto verticales en PowerPoint.

### <a name="project"></a>Project

- Se ha corregido un problema para permitir que los usuarios en Windows 7 puedan abrir proyectos desde Project Web App y sitios de SharePoint.

- Se identificó un problema en el que los usuarios podían recibir varios mensajes al abrir un proyecto de sólo lectura.

- El comando Level All no resuelve adecuadamente una sobreasignación de recursos.

- Si tiene una tarea sin nada de trabajo, es posible que la tarea no se pueda marcar como completada y siempre se mostrará en el 99 %.

### <a name="visio"></a>Visio

- La exportación como SVG de Visio estaba fallando por una variedad de formas.

### <a name="word"></a>Word

- Este cambio conducirá a mejoras de rendimiento en la apertura de documentos utilizando Word.

- Los enlaces de cid: las imágenes de los mensajes de Outlook pueden ahora romperse con éxito cuando se soliciten. 

- Hemos corregido un problema que podría haber causado problemas de escala al imprimir en impresoras Deskjet.

- Hemos corregido un problema en los cambios de pista que a veces van en un bucle infinito.

- Corregidos varios problemas que hacían que la aplicación se colgara al apagarse. También se corrigieron ciertos fallos relacionados con los complementos.

### <a name="office-suite"></a>Conjunto de programas de Office

- Corregido el problema de la identificación incorrecta del nombre de la nueva era "Reiwa" en hiragana y kanji como una expresión mal escrita o poco gramatical.

- Corregido un problema que hacía que los usuarios recibieran el mensaje "Lo sentimos, algo nos impide compartir esto" al intentar compartir archivos almacenados en SharePoint 2016.

- Se ha solucionado un problema que podía causar la pérdida de datos en sesiones que implicaban tanto la co autoría como la edición fuera de línea en PowerPoint.

- Esta es una solución para un fallo que los usuarios podrían sufrir al abrir un archivo.

- Evita que los usuarios de PowerPoint se encuentren con un error cuando intentan hacer una presentación en línea.

- En algunos casos, un archivo de sharepoint respaldado por un motor de sincronización podría mostrar "Guardado" pero no haber guardado realmente ningún cambio, lo que provocaría la pérdida de datos.

- Se resolvió un problema que impedía a los usuarios guardar documentos de Word, Excel y PowerPoint. Este problema afecta a los usuarios que crean un nuevo archivo y muestra la opción "Guardar como diálogo" después de hacer clic en el icono Guardar o presionar Ctrl + S.

- Se ha corregido un problema de perf en Win7 en el que la galería de formas de inserción de la cinta en todas las aplicaciones tardaba aproximadamente 4 segundos en aparecer.

- Corregido un error por el que la información de accesibilidad no se mostraba en la losa del lugar de información de los bastidores.

- Mejora de la fiabilidad del proceso de actualización de Office en lo que respecta a la integridad del registro.

- Se ha corregido un problema por el que las actualizaciones de Office podían haber descargado inesperadamente archivos de la CDN de Office en lugar de la fuente prevista, como un recurso compartido local o de red, o una ubicación proporcionada por el Administrador de configuración.

- Se ha solucionado un problema por el que los mensajes de actualización de Office aparecían en un idioma diferente al esperado. En el futuro, los mensajes de actualización de Office coincidirán correctamente con el idioma de visualización de Windows.

- Corregido un problema en el que una actualización no se aplicaría en ciertos casos en los que el usuario no es un administrador y la cuenta del sistema no tenía conectividad de red.

- En determinadas circunstancias, los accesos directos de Office pueden desaparecer tras una actualización. Esta actualización mejora la fiabilidad en la publicación de los accesos directos de Office.

- Se ha corregido un problema por el que las actualizaciones se bloqueaban inesperadamente en las redes de medición.

- Corrección de un error en la configuración de la fecha límite de actualización de ODT y GPO, en la que la fecha límite relativa sólo funciona la primera vez que se establece, la corrección permite la fecha límite relativa para las actualizaciones posteriores.

- Mejora de la confiabilidad al descargar las actualizaciones de Office al reanudar las descargas que pueden haberse interrumpido anteriormente.

- Corregidos los problemas relacionados con la propiedad Textbox/Shape Autofit en los plug-ins de terceros.

- Hemos corregido un problema en el que las vistas de árboles grandes podían resultar en un choque.

- Para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office se firman ahora utilizando exclusivamente el algoritmo SHA-2.


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1902-january-14"></a>Versión 1902: 14 de enero
*VVersión 1902 (compilación 11328.20512)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se resolvió un problema con la personalización de la cinta que no se carga al abrir el libro de trabajo integrado.

### <a name="outlook"></a>Outlook

- Corregido un problema que causó que los usuarios se encontraran con errores de "el algoritmo de cifrado no es compatible" al enviar un correo electrónico cifrado.

### <a name="powerpoint"></a>PowerPoint

- Los archivos con nuevos comentarios modernos mostrarán una advertencia amarilla si se abren en una versión no soportada.

### <a name="word"></a>Word

- Este cambio conducirá a mejoras de rendimiento en la apertura de documentos utilizando Word.


[//]: # (NO ELIMINAR LOS DETALLES DEL CONTENIDO FINAL)

## <a name="version-1808-january-14"></a>Versión 1808: 14 de enero
*Versión 1808 (compilación 10730.20432)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1902-december-10"></a>Versión 1902 (10 de diciembre)
*Versión 1902 (compilación 11328.20492)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Este cambio evita un problema con ciertos controladores de gráficos Intel al aprovechar el procesamiento del software.

### <a name="outlook"></a>Outlook

- Los elementos del calendario del próximo año pueden mostrar una hora incorrecta en Outlook. [Más información](/outlook/troubleshoot/calendars/calendar-items-display-incorrect-time)

- Se ha corregido un problema que provocaba que los usuarios encontraran un bloqueo al intentar crear una regla desde un mensaje de&quot;Conversación perdida&quot;.

### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema relacionado con la impresión en la página de notas que tenía problemas de diseño en algunos casos.

## <a name="version-1808-december-10"></a>Versión 1808 (10 de diciembre)
*Versión 1808 (compilación 10730.20426)*

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Los elementos del calendario del próximo año pueden mostrar una hora incorrecta en Outlook. [Más información](/outlook/troubleshoot/calendars/calendar-items-display-incorrect-time)

[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1902-november-22"></a>Versión 1902: 22 de noviembre
*Versión 1902 (compilación 11328.20480)*

[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Se corrigió un problema en el que ejecutar una consulta de actualización daría incorrectamente el mensaje de error: "La consulta está dañada".

### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba pérdidas de memoria cuando se habilitaban las notificaciones del sistema.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Con este cambio, la sincronización no se limitará para los errores de sincronización que no estén relacionados con la limitación.

[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-1808-november-22"></a>Versión 1808: 22 de noviembre
*Versión 1808 (compilación 10730.20422)*

[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO INICIAL)

### <a name="access"></a>Access

- Se corrigió un problema en el que ejecutar una consulta de actualización daría incorrectamente el mensaje de error: "La consulta está dañada".

[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-1902-november-12"></a>Versión 1902: 12 de noviembre
*Versión 1902 (compilación 11328.20468)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos

### <a name="excel"></a>Excel

- Se ha solucionado un problema que provocaba retrasos en la visualización de valores escritos después de eliminar un rango.
- Se ha solucionado un problema en el que los libros creados en versiones anteriores de Office podían hacer que Excel se bloqueara cuando se abría en las versiones actuales de Office.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba pérdidas de memoria cuando se habilitaban las notificaciones del sistema.
- Se ha corregido un problema que provocaba que los clientes notaran una pérdida de memoria en Outlook.

### <a name="powerpoint"></a>PowerPoint

- Corrección de confiabilidad: se ha solucionado un problema en el que era posible que PowerPoint fallara al usar el complemento de terceros.

### <a name="word"></a>Word

- Se ha corregido un problema con el cambio de fuente a MS Mincho al intentar finalizar algunos caracteres especiales.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha solucionado un problema de rendimiento en Win7, donde la galería para insertar formas de la cinta de opciones de todas las aplicaciones tardaba aproximadamente 4 segundos en aparecer.
- Se ha solucionado un problema por el que los accesos directos del menú Inicio y las extensiones de archivo de Office desaparecían inesperadamente después de una actualización.
- Para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office se firman ahora utilizando exclusivamente el algoritmo SHA-2.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1808-november-12"></a>Versión 1808: 12 de noviembre
*Versión 1808 (compilación 10730.20416)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos

### <a name="outlook"></a>Outlook

- Se corrige un problema que provocaba que los usuarios con un "correo para mantener la configuración sin conexión" de cualquier otro distinto de "Todos" podían perder datos al mover elementos fuera de la ventana de sincronización de una tienda local a un buzón de Exchange Online.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office se firman ahora utilizando exclusivamente el algoritmo SHA-2.

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1902-october-08"></a>Versión 1902: 8 de octubre
*Versión 1902 (compilación 11328.20438)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="non-security-updates"></a>Actualizaciones que no son de seguridad
### <a name="excel"></a>Excel

- Se ha solucionado un problema por el que los hipervínculos no se podían pegar en algunas hojas protegidas.

### <a name="project"></a>Project

- Se ha corregido un problema cuando el archivo PDF de XPS no se crea en el siguiente escenario:<ul><li>Usted abre un proyecto.</li><li>Hace clic en el menú Archivo, luego en exportar y, finalmente, en el botón<b> Crear PDF/XPS</b>.</li><li>En el cuadro de diálogo Examinar, escribe un nombre de archivo y hace clic en Aceptar.</li></ul>

### <a name="word"></a>Word

- Resuelto un problema en el que las compilaciones actuales de JAWS en Windows no anunciaban palabras al usar Mayús. + Flecha derecha.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Ahora, los usuarios podrán guardar los archivos de Office sincronizados por el cliente de sincronización de OneDrive sin las propiedades necesarias. Las propiedades del documento se podrán ver y editar en la vista Backstage del documento yendo a Archivo > Información. Este cambio llevará a mejoras de rendimiento.

- Resuelto un problema por el que la notificación &quot;Solucionar mi cuenta&quot; no desaparecía después de iniciar sesión correctamente.

[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-1808-october-08"></a>Versión 1808: 8 de octubre

*Versión 1808 (compilación 10730.20386)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)

## <a name="version-1902-september-10"></a>Versión 1902:10 de septiembre
*Versión 1902 (compilación 11328,20420)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="non-security-updates"></a>Actualizaciones que no son de seguridad
### <a name="access"></a>Access

- Se ha corregido un problema que provocaba que algunas consultas de Microsoft Access se ejecutaran más despacio que en las compilaciones anteriores.

### <a name="outlook"></a>Outlook

- Problema en el servicio temporal fijo que hizo que los usuarios vean el error "no se encuentra el archivo. Compruebe que la ruta de acceso y el nombre de archivo sean correctos" al usar datos adjuntos de la nube. [Más información](https://support.office.com/article/outlook-unable-to-attach-onedrive-or-sharepoint-files-to-emails-136951bb-60dc-478a-b916-6ee39e62c37a)

- Se ha corregido un problema que provocaba que los usuarios vean los archivos cargados desde Outlook a OneDrive o SharePoint tienen el nombre de archivo cambiado donde varios caracteres reemplazados por subrayado.

### <a name="word"></a>Word

- Se ha corregido un problema en el que los usuarios obtendrían mensajes de error mientras colaboran con otras personas en un documento de Word.

[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-1808-september-10"></a>Versión 1808:10 de septiembre
*Versión 1808 (compilación 10730,20380)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="non-security-updates"></a>Actualizaciones que no son de seguridad
### <a name="access"></a>Access

- Se ha corregido un problema que provocaba que algunas consultas de Microsoft Access se ejecutaran más despacio que en las compilaciones anteriores.

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

## <a name="version-1808-august-13"></a>Versión 1808: 13 de agosto
*Versión 1808 (compilación 10730.20370)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones no relacionadas con la seguridad
- Se ha corregido un problema por el que la API de configuración no funcionaba en la biblioteca JavaScript de Office en ciertos escenarios. [Más información](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)


## <a name="version-1803-august-13"></a>Versión 1803: 13 de agosto
*Versión 1803 (compilación 9126.2432)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones no relacionadas con la seguridad
- Se ha corregido un problema por el que la API de configuración no funcionaba en la biblioteca JavaScript de Office en ciertos escenarios. [Más información](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)


## <a name="version-1902-july-09"></a>Versión 1902: 09 de julio
*Versión 1902 (compilación 11328.20368)*
<br/>Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)


### <a name="access-feature-updates"></a>Access: Actualizaciones de características

- **Vincular, actualizar o quitar tablas vinculadas:** El Administrador de tablas vinculadas actualizado es la ubicación para administrar todos los orígenes de datos y tablas vinculadas. [Más información](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)
- **Píntalo negro, píntalo gris:** cambie el aspecto de Access tantas veces como quiera. Cuatro temas para elegir: multicolor, gris oscuro, negro y blanco. [Más información](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)
- **Office tiene un nuevo aspecto:** ahora las aplicaciones de Office tienen iconos modernos más sencillos y accesibles. Además, la cinta de opciones tiene efectos visuales actualizados que resaltan las características de colaboración disponibles en las aplicaciones de Office.

### <a name="excel-feature-updates"></a>Excel: Actualizaciones de características

- **Inicio más rápido** La página de Inicio recién diseñada coloca los documentos abiertos recientemente en el centro y en primer plano. Acceda a archivos con menos clics y abra la Configuración u Opciones de la cuenta desde allí.
- **Colaborar con comentarios:** mantenga la conversación activa directamente en la hoja de cálculo con el cuadro de respuesta integrado. [Más información](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)
- **Los iconos de la cinta tienen un aspecto nuevo:** no se preocupe, todo funciona de la misma forma. Además, tendrán un aspecto excelente en pantallas de todos los tamaños. [Más información](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Capacidad de insertar SVG con filtros aplicados:** ahora, los usuarios de Office tienen la capacidad de insertar SVG con filtros aplicados. [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Mostrar lo que esconde una imagen:** coloque una imagen en una hoja de cálculo, elija el valor predeterminado y vea cómo cambia la transparencia. [Más información](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Una llamada a todos los seguidores de Obtener y transformar:** si usa Obtener y transformar a menudo, le alegrará saber que se ha mejorado la característica Columna a partir de los ejemplos. Y también se han mejorado muchos conectores. [Más información](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)
- **Compatibilidad mejorada con pantallas de alta definición**: si usa varios monitores o una base de conexión para portátil, las aplicaciones de Office ofrecen ahora una imagen nítida en todas las pantallas, incluso si tienen configuraciones de escala diferentes. [Más información](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Búsqueda rápida** Se han potenciado los cálculos de las funciones BUSCARV, BUSCARH y COINCIDIR para que pueda obtener respuestas con más rapidez. [Más información](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)

### <a name="outlook-feature-updates"></a>Outlook: actualizaciones de características

- **Use Lectura en voz alta para escuchar el correo electrónico:** Outlook puede leer el correo electrónico en voz alta, resaltando el texto a medida que se lee. Para activar Lectura en voz alta, vaya a la configuración de Accesibilidad. [Más información](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)
- **Escriba sin manos:** ¿tiene un micrófono? Haga clic en Dictar y vea cómo Outlook escribe mientras habla.  [Más información](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Los iconos de la cinta tienen un aspecto nuevo:** no se preocupe, todo funciona de la misma forma. Además, tendrán un aspecto excelente en pantallas de todos los tamaños. [Más información](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Bloquear la descarga de contenido externo de forma predeterminada en los correos electrónicos firmados y encriptados SMIME:** Debido a una vulnerabilidad en el protocolo SMIME, Outlook bloqueará la descarga de contenido externo en mensajes que se hayan cifrado o firmado mediante SMIME. Los usuarios no podrán descargar contenido externo con un solo clic en la interfaz de usuario de Outlook para protegerse de la vulnerabilidad de seguridad. Hay una nueva opción en el cuadro de diálogo Opciones para permitir que los usuarios vuelvan al comportamiento anterior.
- **Desactivar el reenvío para una reunión:** impida que los asistentes reenvíen la reunión a otros usuarios. Vaya a la cinta y haga clic en Opciones de respuesta. [Más información](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)
- **Sugerencias de usuarios en el Asistente para programación:** vea recomendaciones de asistentes para agregar al programar una reunión. Ya no es necesario cambiar repetidamente entre el Asistente para programación y la línea Para. [Más información](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)
- **La reserva de una sala es ahora más fácil:** busque una sala de conferencias con más de una lista de salas y cambie de listas sin perder las salas que ha seleccionado.
- **Nuevo valor predeterminado para el intervalo de periodicidad:** para el cuadro de diálogo Periodicidad, el intervalo de periodicidad utilizado de forma predeterminada es "Sin fecha de finalización". Esto facilita la creación de serie periódicas de ejecución prolongada, que pueden dañarse con el tiempo. Vamos a actualizar el valor predeterminado del cuadro de diálogo Periodicidad a "Finalizar el", para que dicho valor coincida con los procedimientos recomendados de calendarios.
- **Unirse a reuniones de Teams desde el cuadro de diálogo Recordatorios de Outlook:** cuando Outlook recuerda a los usuarios que se aproxima una reunión, se mostrará un botón Unirse en línea si la reunión que se aproxima es una reunión en línea de Teams. Esta experiencia es similar a la de unión a una reunión de Skype Empresarial desde el cuadro de diálogo Recordatorios de Outlook.
- **Dejar de ver avisos de eventos anteriores:** puede configurar el calendario para descartar de forma automática los avisos de eventos una vez que hayan finalizado. [Más información](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- **Ver la dirección URL de Vínculos seguros:** los vínculos seguros le protegen de direcciones URL malintencionadas recibidas por correo electrónico, pero ocultan la dirección URL original. Para ver el original, mueva el puntero sobre la dirección URL. Requiere una licencia de Protección contra amenazas avanzada. [Más información](https://products.office.com/exchange/advance-threat-protection)
- **Zoom y quieto:** en lugar de ajustar el Zoom cada vez que lee un mensaje, elija una configuración predeterminada para todos los mensajes. [Más información](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)
- **Cifrado de mensajes: directiva IRM de solo cifrado:** la nueva opción de solo cifrado aparece en Opciones > Menú permisos para los usuarios de cifrado de mensajes de Office 365. Esta opción le permite cifrar un mensaje y enviárselo a cualquier usuario dentro o fuera de su organización.
- **Advertencia cuando está en CCO:** el recuadro CCO le avisará antes de que responda a todos accidentalmente en un correo electrónico en el que está en copia oculta.
- **Una línea Para: más inteligente:** a la hora de redactar un mensaje, al hacer clic en la línea Para: aparecen sugerencias de destinatarios que es probable que elija. Además, puede ver sus imágenes para confirmar que lo esté enviando a la persona adecuada. [Más información](https://support.office.com/article/147208AF-CA8E-4CDF-B71F-77BA81A54069)
- **Capacidad de insertar SVG con filtros aplicados:** ahora, los usuarios de Office tienen la capacidad de insertar SVG con filtros aplicados. [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Compatibilidad mejorada con pantallas de alta definición**: si usa varios monitores o una base de conexión para portátil, las aplicaciones de Office ofrecen ahora una imagen nítida en todas las pantallas, incluso si tienen configuraciones de escala diferentes. [Más información](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="powerpoint-feature-updates"></a>PowerPoint: actualizaciones de características

- **Inicio más rápido** La página de Inicio recién diseñada coloca los documentos abiertos recientemente en el centro y en primer plano. Acceda a archivos con menos clics y abra la Configuración u Opciones de la cuenta desde allí.
- **Escriba sin manos:** ¿tiene un micrófono? Haga clic en Dictar y vea cómo PowerPoint escribe mientras habla.  [Más información](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Los iconos de la cinta tienen un aspecto nuevo:** no se preocupe, todo funciona de la misma forma. Además, tendrán un aspecto excelente en pantallas de todos los tamaños. [Más información](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Compatibilidad mejorada con pantallas de alta definición**: si usa varios monitores o una base de conexión para portátil, las aplicaciones de Office ofrecen ahora una imagen nítida en todas las pantallas, incluso si tienen configuraciones de escala diferentes. [Más información](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Hipervínculos en colores vivos:** los hipervínculos ya no son solo azules. Aplique el color que quiera a la fuente. [Más información](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)
- **Vea cómo las diapositivas cobran vida:** inserte gráficos 3D animados para ver corazones que laten, planetas en órbita y dinosaurios a toda velocidad por la pantalla. [Más información](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **Retocamos sus bocetos:** convertimos las formas y el texto dibujado a mano en diagramas refinados. Solo tiene que seleccionar los trazos de lápiz para empezar. [Más información](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **Mostrar lo que esconde una imagen:** coloque una imagen en una hoja de cálculo, elija el valor predeterminado y vea cómo cambia la transparencia. [Más información](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Publicar en Microsoft Stream:** comparta una presentación como un vídeo de forma más segura en su organización mediante Microsoft Stream. [Más información](https://support.office.com/article/C140551F-CB37-4818-B5D4-3E30815C3E83)
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
- **Compatibilidad mejorada con pantallas de alta definición**: si usa varios monitores o una base de conexión para portátil, las aplicaciones de Office ofrecen ahora una imagen nítida en todas las pantallas, incluso si tienen configuraciones de escala diferentes. [Más información](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Escriba su currículum vitae con la Ayuda de LinkedIn:** Con el Asistente de currículum, vea experiencias de trabajo, habilidades sugeridas, etc. para un determinado rol. [Obtener más información](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)

### <a name="project-feature-updates"></a>Project: Actualizaciones de características

- **Vea más información en las tarjetas del Panel de tareas:** cuando no se pueda contar la historia solo con el título, personalice las tarjetas del Panel de tareas para mostrar los detalles más importantes. [Más información](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)
- **Office tiene un nuevo aspecto:** ahora las aplicaciones de Office tienen iconos modernos más sencillos y accesibles. Además, la cinta de opciones tiene efectos visuales actualizados que resaltan las características de colaboración disponibles en las aplicaciones de Office.

### <a name="publisher-feature-updates"></a>Publisher: actualizaciones de características

- **Office tiene un nuevo aspecto:** ahora las aplicaciones de Office tienen iconos modernos más sencillos y accesibles. Además, la cinta de opciones tiene efectos visuales actualizados que resaltan las características de colaboración disponibles en las aplicaciones de Office.

### <a name="visio-feature-updates"></a>Visio: actualizaciones de características

- **Disfrute de un momento icónico en el siguiente diagrama:** elija entre 26 galerías de símbolos nuevas con iconos de análisis, arte, celebración, caras, deportes y mucho más.
- **Office tiene un nuevo aspecto:** ahora las aplicaciones de Office tienen iconos modernos más sencillos y accesibles. Además, la cinta de opciones tiene efectos visuales actualizados que resaltan las características de colaboración disponibles en las aplicaciones de Office.

### <a name="office-suite-feature-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de características

- **Ahora, las aplicaciones de terceros de Office son compatibles con la inserción de SVG a través de la API office.js:** las aplicaciones de terceros, también conocidas como complementos de Office, ahora tienen la capacidad de insertar SVG. Ahora los usuarios pueden conectar a Office su colección personal de SVG. Los desarrolladores pueden usar esta característica mediante la API Office.js.
- **Instalación de Microsoft Teams:** Microsoft Teams se instala de forma predeterminada para las NUEVAS instalaciones de Office 365 ProPlus. [Más información](/DeployOffice/teams-install)

### <a name="skype-for-business-feature-updates"></a>Skype Empresarial: actualizaciones de características

- **Compatibilidad mejorada con pantallas de alta definición**: si usa varios monitores o una base de conexión para portátil, las aplicaciones de Office ofrecen ahora una imagen nítida en todas las pantallas, incluso si tienen configuraciones de escala diferentes. [Más información](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)


### <a name="excel-non-security-updates"></a>Excel: actualizaciones no relacionadas con la seguridad

- Se ha resuelto un problema que provocaba un bloqueo al guardar un archivo que contenía una asignación XML para PDF.
- Se ha resuelto un problema que provocaba que se quiten los vínculos externos al cargar libros con nombres de hojas no válidos.
- Se ha corregido un problema en el uso de la herramienta Cámara en Excel que podía provocar el bloqueo de la hoja de cálculo.
- Se ha resuelto un problema por el que los gráficos de cascada y embudo dejaban de estar sincronizados con las tablas al insertar o eliminar celdas.
- Se ha resuelto un problema que ocurría al recalcular una tabla de datos durante un cálculo de la hoja con una fórmula de matriz en otra hoja que dependía de la tabla. 
- Se ha resuelto un problema que impedía que los libros protegidos con contraseña se abran desde SharePoint sin primero desproteger el archivo.
- Se realizó un cambio para asegurar que el evento BeforeSave se controle al compartir o alternar el Autoguardado. 
- Se ha corregido un problema que se producía al utilizar la rueda de desplazamiento del ratón en una ventana activa con una hoja de gráfico.
- Se ha resuelto un problema que provocaba que apareciese un mensaje de "Error inesperado" al importar una hoja de cálculo en SharePoint.
- Se ha solucionado un problema que provocaba que Excel se bloqueara al abrir un libro que contenía formato condicional usando un nombre para su regla y una vista personalizada.
- Las macros que usan la validación de datos con fórmulas de más de 255 caracteres pueden haber producido errores en el tiempo de ejecución. Este problema se ha corregido.
- Un problema que provocaba que los archivos que contenían tablas dinámicas vinculadas a otros libros se cargaran despacio. Este problema se ha resuelto.
- Se ha resuelto un problema con la apertura de archivos HTML y el error "el formato de archivo y la extensión no coinciden".
- Se ha realizado un cambio para resolver problemas con el desplazamiento con la rueda del ratón en ventanas inactivas.
- Resuelto un problema por el que al presionar la tecla Tab no se pasaba a la siguiente celda cuando se estaba en una celda con una fórmula que termina en un nombre definido.
- Resuelto un problema consistente en que el formato de celda provocaba que el tamaño del archivo creciera innecesariamente.
- Resuelto un problema por el que cortar y pegar una Tabla dinámica entre libros puede dar lugar a que los datos se peguen, sin una Tabla dinámica para otros usuarios con los que esté colaborando.


### <a name="outlook-non-security-updates"></a>Outlook: actualizaciones no relacionadas con la seguridad

- Se ha corregido un problema que provocaba que los clientes vean sus tareas desaparecer aparentemente al agregar una 2ª condición a "Agrupar por".
- Se ha corregido un problema por el que los clientes no podían editar algunos campos de los elementos que se han migrado.
- Corregido un problema en el que las ventanas no aparecían en la ubicación correcta cuando la barra de tareas del sistema se mantenía en la izquierda o en la parte superior de la pantalla.
- Soluciona un problema que hacía que los clientes experimentaran un bloqueo al cargar imágenes de la tarjeta de contacto.
- Soluciona un problema que hacía que algunos clientes experimentaran bloqueos al iniciar aplicaciones de Office.
- Corregido un problema en el que las ventanas no aparecían en la ubicación correcta cuando la barra de tareas del sistema se mantenía en la izquierda o en la parte superior de la pantalla.
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

 - Se ha corregido un problema que provocaba que al compartir un documento que está en colaboración se genere un archivo adjunto con la extensión .asd.
 - Se ha corregido un problema con los comentarios que se atribuían a autores aleatorios.
 - Se ha corregido un problema relacionado con quitar firma al desproteger un documento.
 - Se ha corregido un problema por el que la edición de una Persona relacionada agregada por SharePoint podía bloquearse.
 - Se ha corregido un problema en el cuadro de diálogo "Error al cargar el recurso" cuando se inicia Word.
 - Si un archivo se abre en modo de solo lectura y se hace clic en Guardar como en el panel Información, se solucionará el problema para que se muestre la interfaz de usuario de guardar.


### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones no relacionadas con la seguridad

 - Se ha corregido un error en VBA que informaba de un estado de relleno de forma incorrecto después de una acción de "deshacer".
 - Esta es una solución para un problema en el que no se pueden guardar archivos en carpetas WebDAV de Apache.
 - Corrige un problema en el que Office se cierra de forma abrupta cuando los clientes abren algunos archivos almacenados en la nube.
 - Se corrigió un problema de identificación del nombre de la nueva era "Reiwa" en Hiragana y Kanji como una expresión gramaticalmente incorrecta o mal escrita.
 - Se ha corregido un problema de varios usuarios de Windows 10 por el que parecía que la lista de archivos recientes se había borrado.
 - Se ha corregido un problema por el que un usuario final veía una barra de Office Update, aunque durante una actualización activada por el administrador.
 - Se han corregido problemas relacionados con indicaciones de inicio de sesión intermitentes en blanco.
 - Corregido un problema por el que los elementos de una actualización de Office no usan el almacenamiento en caché del mismo nivel de optimización de entrega. [Más información](/windows/deployment/update/waas-delivery-optimization)
- Corrección de un error que podría provocar que se eliminaran o no se activaran productos si Office se había instalado con la Herramienta de implementación de Office y había un caso de no coincidencia.
- Corregido un problema que causaba indicaciones de inicio de sesión excesivas en dispositivos Windows 10 (versión 1803 o posterior).
- Corregida regresión que producía bloqueos al descargar imágenes vinculadas.
- Corregida borrosidad de archivos EMF de gran tamaño pegados en Word, Excel o PowerPoint.
- Corregido el error en el historial de versiones de la lógica de análisis que en algunos casos hacía que los documentos que se abrieran en modo solo lectura.


## <a name="version-1808-july-09"></a>Versión 1808: 09 de julio
*Versión 1808 (compilación 10730.20360)*
<br/>Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)


### <a name="word-non-security-updates"></a>Word: actualizaciones no relacionadas con la seguridad

- Se ha mejorado el rendimiento al habilitar elementos rápidos para las propiedades del documento.
- Se ha corregido un problema relacionado con quitar firma al desproteger un archivo.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones no relacionadas con la seguridad

- Se ha corregido un problema que afectaba a las aplicaciones de Office que se ejecutan en Windows virtualizado.


## <a name="version-1803-july-09"></a>Versión 1803: 09 de julio
*Versión 1803 (compilación 9126.2428)*
<br/>Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)


## <a name="version-1808-june-11"></a>Versión 1808: 11 de junio
*Versión 1808 (compilación 10730.20348)*
<br/>Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)

### <a name="word-non-security-updates"></a>Word: actualizaciones no relacionadas con la seguridad
 - Se ha corregido un problema relacionado con quitar firma al desproteger un archivo.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones no relacionadas con la seguridad
 - Se ha corregido un problema que podría bloquear las aplicaciones de Office que se ejecutan en Windows virtualizado.

## <a name="version-1803-june-11"></a>Versión 1803: 11 de junio
*Versión 1803 (compilación 9126.2388)*
<br/>Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md) 

## <a name="version-1808-may-14"></a>Versión 1808: 14 de mayo
*Versión 1808 (compilación 10730.20344)*   

### <a name="outlook-non-security-updates"></a>Outlook: actualizaciones no relacionadas con la seguridad
 - Se ha corregido un problema por el que los clientes no podían editar algunos campos de los elementos que se han migrado.

### <a name="visio-non-security-updates"></a>Visio: actualizaciones no relacionadas con la seguridad
 - Se ha corregido un problema que causaba problemas de jerarquía de ventana errónea para soluciones de terceros que ampliaban Visio al deshabilitar la característica de PPP dinámico.

### <a name="word-non-security-updates"></a>Word: actualizaciones no relacionadas con la seguridad
 - Se ha corregido un problema por el que la edición de una Persona relacionada agregada por SharePoint podía bloquearse.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad
 - Se corrigió un problema de identificación del nombre de la nueva era "Reiwa" en Hiragana y Kanji como una expresión gramaticalmente incorrecta o mal escrita.
  
## <a name="version-1803-may-14"></a>Versión 1803: 14 de mayo
*Versión 1803 (compilación 9126.2387)*

### <a name="outlook-non-security-updates"></a>Outlook: actualizaciones no relacionadas con la seguridad
 - Se ha corregido un problema por el que los clientes no podían editar algunos campos de los elementos que se han migrado.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad
 - Se corrigió un problema de identificación del nombre de la nueva era "Reiwa" en Hiragana y Kanji como una expresión gramaticalmente incorrecta o mal escrita.

## <a name="version-1808-april-9"></a>Versión 1808: 9 de abril
*Versión 1808 (compilación 10730.20334)*

### <a name="skype-for-business-non-security-updates"></a>Skype Empresarial: actualizaciones no relacionadas con la seguridad
- Se corrige un problema en Lync (Skype Empresarial) por el que en cualquier reunión en línea con más de 7 participantes, la ventana de reunión puede desaparecer.

### <a name="word-non-security-updates"></a>Word: actualizaciones no relacionadas con la seguridad

- Se ha corregido un problema que causaba que el usuario pudiese abrir documentos de forma anónima en IE o Edge.
- Se ha corregido un problema que causaba que, al aplicar un color de resaltado de texto en el campo NUMPAGES o PAGE, en el encabezado o en el pie de página de un documento Word, el campo quedase en negro en lugar del color de resaltado aplicado.
- Hemos agregado compatibilidad para el complemento del asistente para postales en japonés de Word para la nueva era japonesa. 

## <a name="version-1803-april-9"></a>Versión 1803: 9 de abril
- Las actualizaciones de seguridad se enumeran [aquí](microsoft365-apps-security-updates.md)

## <a name="version-1808-march-12"></a>Versión 1808: 12 de marzo
*Versión 1808 (compilación 10730.20304)*

### <a name="word-non-security-updates"></a>Word: actualizaciones no relacionadas con la seguridad

- Se ha corregido un problema por el que VBA devuelve el número de página incorrecto.
- Se ha mejorado el tiempo para guardar un archivo local de Word. 

### <a name="outlook-non-security-updates"></a>Outlook: actualizaciones no relacionadas con la seguridad

- Se ha proporcionado la clave del registro para deshabilitar la opción "Cifrar solo" en el menú de cifrado de mensajes de Office 365.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones no relacionadas con la seguridad

- Se ha corregido un problema por el que la actualización de Office puede quedarse bloqueada durante algún tiempo al intenta descargar.

## <a name="version-1803-march-12"></a>Versión 1803: 12 de marzo 
- Las actualizaciones de seguridad se enumeran [aquí](microsoft365-apps-security-updates.md)

## <a name="version-1808-february-12"></a>Versión 1808: 12 de febrero
*Versión 1808 (compilación 10730.20280)*

### <a name="access-non-security-updates"></a>Access: Actualizaciones no relacionadas con la seguridad 

- Esta actualización agrega compatibilidad con las nuevas eras japonesas en Access.

### <a name="outlook-non-security-updates"></a>Outlook: actualizaciones no relacionadas con la seguridad 

- Soluciona un problema que provocaba que los usuarios con reglas que hacen referencia a una carpeta que ya no existe experimentasen dos problemas: 1. Un error al intentar administrar reglas y 2. Las reglas del lado cliente no se ejecutan.
- Soluciona un problema que provocaba que los usuarios con buzones delegados en caché sufran bloqueos frecuentes en intervalos imprevisibles.
- Soluciona un problema que causaba que todas las reuniones de día entero aparezcan un día más de lo previsto en algunas vistas debido a que la hora de finalización de la reunión se establece en la medianoche del día siguiente.
- Corregido un bloqueo al crear citas o reuniones que hacen referencia a eras japonesas.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad

- Corregido el problema por el que los complementos implementados con la [implementación centralizada de Office O365](/office/dev/add-ins/publish/centralized-deployment) se bloqueaban y no se podían usar.


## <a name="version-1803-february-12"></a>Versión 1803: 12 de febrero
*Versión 1803 (compilación 9126.2356)*

*Esta es la versión del Canal semianual que ha estado disponible desde julio de 2018. Seguirá recibiendo soporte técnico y actualizaciones de seguridad hasta septiembre de 2019. Pero ahora está disponible una nueva versión del Canal semianual (versión 1808, compilación 10730.20280), que contiene nuevas características, actualizaciones de seguridad y actualizaciones no relacionadas con la seguridad.*

### <a name="access-non-security-updates"></a>Access: Actualizaciones no relacionadas con la seguridad 

- Esta actualización agrega compatibilidad con las nuevas eras japonesas en Access.

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad 

- Esta actualización agrega compatibilidad con las nuevas eras japonesas en Excel.

### <a name="outlook-non-security-updates"></a>Outlook: actualizaciones no relacionadas con la seguridad

- Corregido un bloqueo al crear citas o reuniones que hacen referencia a eras japonesas.

### <a name="project-non-security-updates"></a>Project: actualizaciones no relacionadas con la seguridad
- Esta actualización agrega compatibilidad con las nuevas eras japonesas en Project.

### <a name="word-non-security-updates"></a>Word: actualizaciones no relacionadas con la seguridad

- Esta actualización agrega compatibilidad con las nuevas eras japonesas en Word.

### <a name="visio-non-security-updates"></a>Visio: Actualizaciones no relacionadas con la seguridad

- Esta actualización agrega compatibilidad con las nuevas eras japonesas en Visio.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad

- Corregido el problema por el que los complementos implementados con la [implementación centralizada de Office O365](/office/dev/add-ins/publish/centralized-deployment) se bloqueaban y no se podían usar.

## <a name="version-1708-february-12"></a>Versión 1708: 12 de febrero
*Versión 1708 (compilación 8431.2372)*

*Esta es la versión del Canal semianual que ha estado disponible desde enero de 2018. Seguirá recibiendo soporte técnico y actualizaciones de seguridad hasta marzo de 2019. Pero ahora hay disponible una nueva versión del Canal semianual (versión 1808, compilación 10730.20280), que contiene nuevas características, actualizaciones de seguridad y actualizaciones no relacionadas con la seguridad.*

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad

- Corregido el problema por el que los complementos implementados con la [implementación centralizada de Office O365](/office/dev/add-ins/publish/centralized-deployment) se bloqueaban y no se podían usar.


## <a name="version-1808-january-8"></a>Versión 1808: 8 de enero
*Versión 1808 (compilación 10730.20264)*

### <a name="access-feature-updates"></a>Access: actualizaciones de características

 - **Visualizar datos con nuevos gráficos:** elija entre 11 gráficos y agregue uno a los formularios e informes para visualizar mejor los datos y tomar decisiones fundamentadas. [Más información](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)

### <a name="excel-feature-updates"></a>Excel: Actualizaciones de características
 - **Edición colaborativa:** Trabajar con otras personas al mismo tiempo en el libro. [Más información](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)
 - **El Autoguardado para archivos de nube ahora está habilitado de forma predeterminada:** con este cambio, los usuarios no tendrán que preocuparse por perder los cambios en los documentos almacenados en OneDrive o SharePoint Online. Los cambios se guardarán en la nube automáticamente y los usuarios no tendrán que presionar explícitamente Ctrl + G o el botón Guardar. Sin embargo, tendrán que comprender este cambio de comportamiento para que no realicen cambios accidentales en los documentos. Tenga en cuenta que los usuarios pueden desactivar el Autoguardado con el botón de Autoguardado en la parte superior de la pantalla. Le recomendamos que notifique a los usuarios sobre este nuevo cambio y les instruya sobre cómo aprovechar mejor esta nueva característica de Office 365. [Más información sobre el Autoguardado](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) y [Más información sobre lo que los administradores de TI deben saber sobre el Autoguardado](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Edición de la barra de fórmulas y las celdas mejorada:** ahora, puede usar CTRL + A para seleccionar el texto de una celda o de la barra de fórmulas. También se ha mejorado la compatibilidad con los emojis y otros caracteres complejos. [Más información](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
- **Mejoras del Comprobador de accesibilidad:** el Comprobador de accesibilidad ha actualizado la asistencia técnica para las normas internacionales y recomendaciones para que los libros sean más accesibles. [Más información](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **Evitar cambios no deseados:** establezca los libros para abrir como solo lectura para evitar cambios accidentales. Vaya a archivo > información > proteger libro > abrir siempre como solo lectura

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad 

- Corregido un problema en sesiones de co-autoría en el que una segmentación de datos no se actualiza correctamente cuando otro usuario aplica un filtro de columna en los datos de esa segmentación.
- Corregido un problema en una sesión de co-autoría en el que uno de los usuarios borra la descripción de una segmentación y esto provoca que otro usuario de la sesión de co-autoría sufra un bloqueo de Excel.
- Corregido un posible bloqueo al crear varias segmentaciones de tabla enlazadas a la misma columna de datos y, después, eliminar la columna de datos.
- Corregido un problema por el que Excel a veces podía bloquearse al actualizar una tabla de consulta filtrada que contenía texto ajustado en celdas cuando la opción para ajustar automáticamente el ancho de columna estaba desactivada.
- Corregido un problema por el que las segmentaciones guardadas en Excel 2007 pueden desencadenar un bloqueo cuando se abren en versiones más recientes de Excel si cambia el número de elementos que se muestra en la segmentación.
- Introduce la compatibilidad con el botón Obtener diagnósticos para simplificar la investigación de solicitudes de soporte.
- Se ha corregido un error por el que Power Pivot no aparecía en algunas versiones o compilaciones.
- Se ha corregido un problema por el que Excel podía dejar de responder cuando el usuario movía el puntero sobre las opciones de formato en un libro con muchos nombres definidos y cuando Excel dejaba de funcionar en la herramienta de análisis rápido, incluso cuando la vista previa dinámica se había deshabilitado en opciones.
- Estamos investigando el rendimiento lento al mover la ventana de la aplicación de Excel de un escritorio a otro. Mientras tanto, si observa esta lentitud, una solución alternativa que puede considerar es seleccionar "Optimizar para la compatibilidad" para "Al usar varias pantallas" en la pestaña "General" en el cuadro de diálogo Opciones de archivo.
- Se ha corregido un problema por el que Excel podía bloquearse al cambiar el origen de datos de un gráfico desde su conjunto de celdas original.
- Se ha corregido un problema por el que el recálculo podía fallar al abrirse, incluso si se establecía la propiedad FullCalcOnLoad.  
- Se ha corregido un problema por el que se mostraba el año incorrecto cuando se usaba el calendario japonés con formato de celda de fecha.
- Al importar datos en el modelo de datos de Excel, los valores entrantes de cero negativo crearían un error. La corrección importa esos valores como cero.
- Se ha corregido un problema por el que a veces una operación de agrupación (o desagrupación) podía producir un bloqueo en una tabla dinámica de Excel.
- Se ha corregido un problema por el que Excel se bloqueaba al realizar acciones de gráficos.
- Se ha corregido un problema por el que el complemento de Power View se deshabilitaba involuntariamente para algunos usuarios.
- Se ha corregido un problema por el que los archivos de recuperación automática temporales que se crean durante la recuperación de documentos no se limpiaban nunca.
- Se ha corregido un problema por el que, al intentar establecer una conexión nueva con un archivo de texto en un libro protegido, se recibía el mensaje de error "El libro está protegido y no se puede modificar".
- Se ha corregido un problema por el que no se podía imprimir mediante la Impresión rápida de un libro de Excel adjuntado a un correo electrónico de Outlook.
- Se ha corregido un problema por el que al hacer clic en un hipervínculo, Excel se podía bloquear.
- Se ha corregido un problema por el que al usar las funciones de cubo, Excel se podía bloquear.

### <a name="outlook-feature-updates"></a>Outlook: actualizaciones de características
 - **Mejoras del Comprobador de accesibilidad:** el Comprobador de accesibilidad ha actualizado la asistencia técnica para las normas internacionales y recomendaciones para que los mensajes sean más accesibles. [Más información](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
 - **Administrar perfiles desde el selector de perfil:** si usa el selector de perfil cuando se inicia Outlook, ahora puede realizar cambios sin usar el panel de control. Cree y elimine perfiles o cambie la configuración, todo desde el selector de perfil.
- **Accesibilidad integrada:** haga que su mensajes sean accesibles para todos los usuarios agregando texto alternativo descriptivo a las imágenes.
- **Advertencias de complemento de Outlook:** ocasionalmente un complemento COM de Outlook puede encontrar problemas que ralenticen los demás componentes de Outlook. Estos problemas podrían ser por causas de latencia de eventos, como cambiar entre carpetas de Outlook. la llegada de correo electrónico nuevo, la apertura de elementos de calendario, etc. Cuando se producen, se mostrará una advertencia en la barra de notificaciones de Outlook.
- **Saber quién se reunirá con usted:** a partir de ahora, podrá ver las respuestas de otros usuarios a las convocatorias de reunión aunque no sea el organizador.
- **Nunca pierda un aviso:** establezca avisos para que aparezcan elementos emergentes en las ventanas mientras está trabajando. En caso contrario, Outlook parpadeará en la barra de tareas para llamar su atención. [Más información](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- **Marcar los elementos eliminados como leídos:** ahora puede establecer como leídos los mensajes que elimine. Para hacerlo, vaya a Archivo \> Opciones \> Correo \> Otros.
- **Ver tres zonas horarias:** ¿necesita programar una reunión en distintas zonas horarias? Agregue varias zonas horarias al calendario para ver la disponibilidad de todos los usuarios fácilmente y seleccione una hora adecuada para todos. [Más información](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)
- **Mejora de la experiencia del usuario para crear un grupo:** hemos perfeccionado la experiencia del usuario a la hora de crear grupos para darle un aspecto más moderno y ordenado.[ Más información](https://support.office.com/article/04d0c9cf-6864-423c-a380-4fa858f27102)

### <a name="outlook-non-security-updates"></a>Outlook: actualizaciones no relacionadas con la seguridad
- Se ha corregido un problema por el que se producían errores de sincronización de calendario.
- Se ha corregido un problema por el que a los usuarios les daba un error al iniciar el cuadro de diálogo "Administrar reglas y alertas".
- Corregido un problema que provocaba que los usuarios no pudiesen conectarse a sus buzones a través de DirectAccess al usar una conexión de uso medido.
- Corregido un problema que causaba que los usuarios viesen documentos desprotegidos almacenados en carpetas públicas abrirse de forma errónea en "Vista protegida".
- Corregido un problema que provocaba que los usuarios viesen datos adjuntos inesperados al reenviar elementos con datos adjuntos en línea.
- Corregido un problema que provocaba que los archivos OFT no se representasen correctamente después de enviarlos como datos adjuntos.
- Se ha corregido un problema que provocaba bloqueos cuando algunos usuarios de complementos agregaban una reunión a un calendario compartido.
- Se ha corregido un problema por el que el programa dejaba de responder al abrir la carpeta Historial de conversaciones.
- Se ha corregido un problema por el que si cambiaba el idioma a japonés e intentaba escribir caracteres japoneses en un IDE de VBA cuando estuviese cargado en Outlook, se bloqueaba.
- Se ha corregido un problema por el que Outlook se bloqueaba al moverse a la carpeta Elementos enviados o Bandeja de salida.
- Se ha corregido un problema por el que todos los asistentes recibían actualizaciones de la reunión cuando cambiaban el cuerpo de la reunión o los datos adjuntos, en lugar de que fuese opcional que se enviase una actualización de la reunión a los asistentes.
- Se ha corregido un problema por el que los usuarios no podían conectarse a los puntos de conexión de REST y EWS debido a un cambio en la cadena de agente de usuario.
- Se ha corregido un problema por el que una actualización de la ubicación de la reunión para los asistentes mostraba la ubicación anterior en lugar de la nueva.
- Se ha corregido un problema por el que al usuario le daba un error al obtener una vista previa de los datos adjuntos en el panel de lectura.
- Se ha corregido un problema por el que Outlook se bloqueaba al resolver nombres para mostrar en direcciones de correo electrónico cuando el usuario redactaba un correo electrónico.
- Se ha corregido un problema por el que algunos usuarios no recibían características de soporte técnico que había habilitado su administrador de espacio empresarial.

### <a name="onenote-non-security-updates"></a>OneNote: actualizaciones no relacionadas con la seguridad 

- Se ha corregido un problema de estabilidad que podía producirse en relación con la sincronización y la navegación a una sección eliminada.

### <a name="powerpoint-feature-updates"></a>PowerPoint: actualizaciones de características 
- **El Autoguardado para archivos de nube ahora está habilitado de forma predeterminada:** con este cambio, los usuarios no tendrán que preocuparse por perder los cambios en los documentos almacenados en OneDrive o SharePoint Online. Los cambios se guardarán en la nube automáticamente y los usuarios no tendrán que presionar explícitamente Ctrl + G o el botón Guardar. Sin embargo, tendrán que comprender este cambio de comportamiento para que no realicen cambios accidentales en presentaciones. Tenga en cuenta que los usuarios pueden desactivar el Autoguardado con el botón de Autoguardado en la parte superior de la pantalla. Le recomendamos que notifique a los usuarios sobre este nuevo cambio y les instruya sobre cómo aprovechar mejor esta nueva característica de Office 365. [Más información sobre el Autoguardado](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) y [Más información sobre lo que los administradores de TI deben saber sobre el Autoguardado](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Edición de la barra de fórmulas y las celdas mejorada:** ahora, puede usar CTRL + A para seleccionar el texto de una celda o de la barra de fórmulas. También se ha mejorado la compatibilidad con los emojis y otros caracteres complejos. [Más información](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
- **Convertir la entrada de lápiz:** dibuje y tome notas con garabatos y conviértalos en texto legible y formas nítidas para crear una presentación elegante. [Más información](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)
- **Compatibilidad con el formato SVG mejorada:** puede insertar imágenes SVG que tengan filtros aplicados. [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Escritura del título de las diapositivas con un lápiz:** use el lápiz para escribir un título y PowerPoint lo convertirá en texto. [Más información](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **Evitar cambios no deseados:** establezca los libros para abrir como solo lectura para evitar cambios accidentales. Vaya a archivo > información > proteger libro > abrir siempre como solo lectura
- **Mejoras del Comprobador de accesibilidad:** el Comprobador de accesibilidad ha actualizado la asistencia técnica para las normas internacionales y recomendaciones para que las presentaciones sean más accesibles. [Más información](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)


### <a name="powerpoint-non-security-updates"></a>PowerPoint: actualizaciones no relacionadas con la seguridad
- Se ha corregido un problema de posibles daños en el archivo al guardar los archivos con contenido ActiveX.
- Se ha corregido el problema en el que las tablas se representaban incorrectamente con un borde grueso.
- Se ha corregido un problema que podía producir un posible bloqueo al cambiar la propiedad Shape.Visibile.
- Se ha corregido un problema por el que no podían combinarse los cambios efectuados en documentos en coautoría.
- Se ha corregido un problema por el que no se realizaba la coautoría en documentos que contenían controles ActiveX.
- Se ha corregido un problema por el que el corrector ortográfico en formas provocaba el bloqueo de PowerPoint.
- Se ha corregido un problema por el que PowerPoint se bloqueaba al abrir un archivo de SharePoint Online.
- Se ha corregido un problema por el que el Panel de recuperación aparecía incorrectamente cuando Autoguardado estaba activado.
- Se ha corregido un problema por el que iniciar sesión no se mostraba, lo que impedía que un usuario accediese a un archivo.
- Se ha corregido un problema por el que, cuando varios usuarios trabajaban en coautoría en la misma presentación, los patrones de diapositivas se duplicaban de forma incorrecta.
- Se ha corregido un problema por el que, al abrir un archivo guardado en OneDrive, PowerPoint se bloqueaba al salir de la Vista protegida.

### <a name="project-feature-updates"></a>Project: actualizaciones de características 
- **Administración de sprint:** agregue, actualice o elimine sprints ágiles rápidamente.
- **Filtrado del panel de tareas:** simplifique los paneles de tareas filtrando las tareas de resumen o de recursos clave.
- **Establecer el porcentaje completado de un panel de tareas:** elija un porcentaje completado de cada columna y después actualice la finalización de tareas con arrastrar y colocar.
- **Navegación sprint:** cambie de una vista de sprint a otra y desplácese rápidamente tareas entre sprints.
- **Una nueva forma de administrar sprints:** tomar un enfoque ágil para trabajar con paneles de tareas. Vaya a administrar Sprints para agregar y quitar sprints a medida que evoluciona el proyecto.
- **Todo organizado con Ubicaciones de almacenamiento recientes:** Project mantiene una lista actualizada de las ubicaciones en las que ha guardado otros proyectos. Cuando quiera guardar su proyecto, simplemente elija una de sus ubicaciones de almacenamiento recientes y continúe con su día.

### <a name="project-non-security-updates"></a>Project: Actualizaciones no relacionadas con la seguridad

- Corregido un problema con la compatibilidad de la nueva moneda venezolana en Project.
- Corregido un problema por el que Project podía bloquearse al usar un Surface 4 que estuviese conectado a un monitor externo.
- Corregido un problema por el que Project podía bloquearse al guardar el proyecto en formato XML.
- Corregido un problema por el que los campos personalizados de recurso de empresa podían eliminarse después de editar el calendario de un recurso.
- Se ha corregido un problema que provocaba que los usuarios experimentasen bloqueos al buscar nombres coreanos para mostrar.
- Se ha corregido un problema que impedía guardar un subproyecto al trabajar en él en el contexto de un proyecto principal.

### <a name="word-feature-updates"></a>Word: actualizaciones de características
- **El Autoguardado para archivos de nube ahora está habilitado de forma predeterminada:** con este cambio, los usuarios no tendrán que preocuparse por perder los cambios en los documentos almacenados en OneDrive o SharePoint Online. Los cambios se guardarán en la nube automáticamente y los usuarios no tendrán que presionar explícitamente Ctrl + G o el botón Guardar. Sin embargo, tendrán que comprender este cambio de comportamiento para que no realicen cambios accidentales en presentaciones. Tenga en cuenta que los usuarios pueden desactivar el Autoguardado con el botón de Autoguardado en la parte superior de la pantalla. Le recomendamos que notifique a los usuarios sobre este nuevo cambio y les instruya sobre cómo aprovechar mejor esta nueva característica de Office 365. [Más información sobre el Autoguardado](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) y [Más información sobre lo que los administradores de TI deben saber sobre el Autoguardado](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Mejoras del Comprobador de accesibilidad:** el Comprobador de accesibilidad ha actualizado la asistencia técnica para las recomendaciones y normas internacionales para que los documentos sean más accesibles. [Más información](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **Compatibilidad con el formato SVG mejorada:** puede insertar imágenes SVG que tengan filtros aplicados. [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="word-non-security-updates"></a>Word: actualizaciones no relacionadas con la seguridad
- Se ha corregido un problema por el que aparecía un mensaje de memoria insuficiente.
- Se ha corregido un conjunto de errores que evitaban que algunos usuarios pudiesen abrir documentos y correos electrónicos protegidos mediante IRM compartidos con ellos por gente de otras organizaciones.
- Se han corregido algunos problemas de rendimiento.
- Mejorar el rendimiento abierto.

### <a name="skype-for-business-non-security-updates"></a>Skype Empresarial: actualizaciones no relacionadas con la seguridad
- Corregido un problema relacionado con la compatibilidad del protocolo TLS 1.2. (Nota: esta es la misma solución que se mencionó en las notas del 10 de abril y aquí se menciona otra vez como parte del resumen de septiembre.)
- Se ha corregido un problema que se producía al agregar usuarios seleccionando “Llamada de Skype” en una reunión.
- Se quita el mensaje en el que se le pregunta al usuario si quiere incluir coordenadas de Skype en una reunión al agregar una sala de Skype como ubicación cuando la reunión ya contiene las coordenadas de la reunión de Teams.
- Se corrige un problema que provocaba que se rellenara la ubicación, incluso cuando el valor de UseLocationForE911Only era verdadero.
- Se soluciona un problema por el que Skype Empresarial dejaba de responder al usar la opción “Llamar con el centro de conferencia” para invitar a usuarios de la lista.
- Se soluciona un problema por el que, al ejecutar Outlook en Terminal Server, el programa se bloqueaba al crear una reunión de Skype Empresarial.
- Se cambia el valor predeterminado de EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket a VERDADERO.

### <a name="visio-feature-updates"></a>Visio: actualizaciones de características
- **Tener sincronizados los diagramas y los orígenes:** Al editar un diagrama del Visualizador de datos en Visio, tiene la opción de actualizar los datos de origen de Excel vinculados con el contenido más reciente de un diagrama.
- **Plantilla de auditoría del Visualizador de datos:** importe contenido de Excel y cree diagramas de auditoría para las transacciones financieras, la administración de inventarios y mucho más.
- **Diagramas iniciales:** las plantillas organigrama, lluvia de ideas y SDL tienen nuevos diagramas iniciales que le ayudarán a empezar a trabajar rápidamente.
- **Crear un documento de Word a partir de formas de Visio:** agregue automáticamente contenido de diagramas, incluidas formas y metadatos, a un documento de Word. Después, personalice el documento para crear instrucciones de procesos y manuales de operaciones. [Más información](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

### <a name="office-suite-security-update"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad

- 
  **Bloqueo de la activación de controles de Flash, Silverlight y Shockwave en Office por motivos de seguridad:** por motivos de seguridad, las nuevas compilaciones de Microsoft Office para Office 365 en Windows bloquean la activación de controles de Silverlight, Flash y Shockwave. Más información[aquí](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729) y [aquí](https://support.office.com/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1)
 
### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones no relacionadas con la seguridad
- Se ha corregido un problema por el que la instalación de la actualización tardaba mucho tiempo en determinados escenarios.
- Se ha corregido un problema que provocaba que, al abrir una aplicación, el usuario viera un mensaje sobre iniciar en modo seguro y después la aplicación no se abriera.
- Se han corregido algunos problemas de rendimiento.


## <a name="version-1803-january-8"></a>Versión 1803: 8 de enero
*Versión 1803 (compilación 9126.2351)*

*Esta es la versión del Canal semianual que ha estado disponible desde julio de 2018. Seguirá recibiendo soporte técnico y actualizaciones de seguridad hasta septiembre de 2019. Pero ahora está disponible una nueva versión del Canal semianual (versión 1808), que contiene nuevas características, actualizaciones de seguridad y actualizaciones no relacionadas con la seguridad.*

### <a name="powerpoint-non-security-updates"></a>PowerPoint: actualizaciones no relacionadas con la seguridad
- Se ha corregido un problema para garantizar la paridad de características de la opción de LinkedIn entre las aplicaciones de Office.

## <a name="version-1803-december-11"></a>Versión 1803: 11 de diciembre
*Versión 1803 (compilación 9126.2336)*

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad 

-   [CVE-2018-8597](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8597): Vulnerabilidad de la ejecución remota de código de Microsoft Excel 
-   [CVE-2018-8598](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8598): Vulnerabilidad de divulgación de información de Microsoft Excel 
-   [CVE-2018-8627](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8627): vulnerabilidad de divulgación de información de Microsoft Excel 
-   [CVE-2018-8636](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8636): Vulnerabilidad de la ejecución remota de código de Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad 

-   [CVE-2018-8587](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8587): Vulnerabilidad de la ejecución remota de código de Microsoft Outlook 

### <a name="powerpoint-security-updates"></a>PowerPoint: Actualizaciones de seguridad 

-   [CVE-2018-8628](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8628): Vulnerabilidad de la ejecución remota de código de Microsoft PowerPoint 


### <a name="outlook-non-security-updates"></a>Outlook: actualizaciones no relacionadas con la seguridad

- Corregido un problema que hacía que Outlook se cerrase inesperadamente al actualizar determinados campos de contactos.
- Soluciona un problema que hacía que los usuarios viesen un error al iniciar el cuadro de diálogo "Administrar reglas y alertas".
- Soluciona un problema que causaba bloqueos para los usuarios de Outlook al ejecutar algunos complementos.


## <a name="version-1708-december-11"></a>Versión 1708: 11 de diciembre
*Versión 1708 (compilación 8431.2351)*

*Esta es la versión del Canal semianual que ha estado disponible desde enero de 2018. Seguirá recibiendo soporte técnico y actualizaciones de seguridad hasta marzo de 2019. Pero ahora hay disponible una nueva versión del Canal semianual (versión 1803, compilación 16.0.9126.2336), que contiene nuevas características, actualizaciones de seguridad y actualizaciones no relacionadas con la seguridad.*

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad 

-   [CVE-2018-8597](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8597): Vulnerabilidad de la ejecución remota de código de Microsoft Excel 
-   [CVE-2018-8598](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8598): Vulnerabilidad de divulgación de información de Microsoft Excel 
-   [CVE-2018-8627](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8627): vulnerabilidad de divulgación de información de Microsoft Excel 
-   [CVE-2018-8636](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8636): Vulnerabilidad de la ejecución remota de código de Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad 

-   [CVE-2018-8587](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8587): Vulnerabilidad de la ejecución remota de código de Microsoft Outlook 

### <a name="powerpoint-security-updates"></a>PowerPoint: Actualizaciones de seguridad 

-   [CVE-2018-8628](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8628): Vulnerabilidad de la ejecución remota de código de Microsoft PowerPoint 

### <a name="outlook-non-security-updates"></a>Outlook: actualizaciones no relacionadas con la seguridad

- Corregido un problema que hacía que Outlook se cerrase inesperadamente al actualizar determinados campos de contactos.
- Soluciona un problema que hacía que los usuarios viesen un error al iniciar el cuadro de diálogo "Administrar reglas y alertas".
- Soluciona un problema que causaba bloqueos para los usuarios de Outlook al ejecutar algunos complementos.


## <a name="version-1803-november-13"></a>Versión 1803: 13 de noviembre
*Versión 1803 (compilación 9126.2315)*

### <a name="excel-security-updates"></a>Excel: actualizaciones de seguridad

-   [CVE-2018-8574](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8574): vulnerabilidad de la ejecución remota de código de Microsoft Excel 
-   [CVE-2018-8577](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8577): vulnerabilidad de la ejecución remota de código de Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: actualizaciones de seguridad 

-   [CVE-2018-8522](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8522): vulnerabilidad de la ejecución remota de código de Microsoft Outlook 
-   [CVE-2018-8524](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8524): vulnerabilidad de la ejecución remota de código de Microsoft Outlook 
-   [CVE-2018-8558](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8558): vulnerabilidad de divulgación de información de Microsoft Office Outlook 
-   [CVE-2018-8576](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8576): vulnerabilidad de la ejecución remota de código de Microsoft Outlook 
-   [CVE-2018-8579](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8579): vulnerabilidad de divulgación de información de Microsoft Office Outlook 
-   [CVE-2018-8582](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8582): vulnerabilidad de la ejecución remota de código de Microsoft Outlook 

### <a name="project-security-updates"></a>Project: actualizaciones de seguridad 

-   [CVE-2018-8575](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8575): vulnerabilidad de la ejecución remota de código de Microsoft Excel 

### <a name="word-security-updates"></a>Word: actualizaciones de seguridad 

-   [CVE-2018-8573](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8573): vulnerabilidad de la ejecución remota de código de Microsoft Word 

### <a name="skype-for-business-security-updates"></a>Skype Empresarial: actualizaciones de seguridad 

-   [CVE-2018-8546](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8546): vulnerabilidad de la denegación de servicio de Microsoft Skype Empresarial 

### <a name="outlook-non-security-updates"></a>Outlook: actualizaciones no relacionadas con la seguridad 

- Este cambio permite a los usuarios utilizar la opción Guardar todo para los archivos físicos en un recurso compartido de red, como una unidad de red asignada. 

## <a name="version-1708-november-13"></a>Versión 1708: 13 de noviembre
*Versión 1708 (compilación 8431.2329)*

*Esta es la versión del Canal semianual que ha estado disponible desde enero de 2018. Seguirá recibiendo soporte técnico y actualizaciones de seguridad hasta marzo de 2019. Pero ahora hay disponible una nueva versión del Canal semianual (versión 1803, compilación 16.0.9126.2315), que contiene nuevas características, actualizaciones de seguridad y actualizaciones no relacionadas con la seguridad.*

### <a name="excel-security-updates"></a>Excel: actualizaciones de seguridad

-   [CVE-2018-8574](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8574): vulnerabilidad de la ejecución remota de código de Microsoft Excel 
-   [CVE-2018-8577](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8577): vulnerabilidad de la ejecución remota de código de Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: actualizaciones de seguridad 

-   [CVE-2018-8522](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8522): vulnerabilidad de la ejecución remota de código de Microsoft Outlook 
-   [CVE-2018-8524](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8524): vulnerabilidad de la ejecución remota de código de Microsoft Outlook 
-   [CVE-2018-8558](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8558): vulnerabilidad de divulgación de información de Microsoft Office Outlook 
-   [CVE-2018-8576](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8576): vulnerabilidad de la ejecución remota de código de Microsoft Outlook 
-   [CVE-2018-8579](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8579): vulnerabilidad de divulgación de información de Microsoft Office Outlook 
-   [CVE-2018-8582](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8582): vulnerabilidad de la ejecución remota de código de Microsoft Outlook 

### <a name="project-security-updates"></a>Project: actualizaciones de seguridad 

-   [CVE-2018-8575](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8575): vulnerabilidad de la ejecución remota de código de Microsoft Excel 

### <a name="word-security-updates"></a>Word: actualizaciones de seguridad 

-   [CVE-2018-8573](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8573): vulnerabilidad de la ejecución remota de código de Microsoft Word 

### <a name="skype-for-business-security-updates"></a>Skype Empresarial: actualizaciones de seguridad 

-   [CVE-2018-8546](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8546): vulnerabilidad de la denegación de servicio de Microsoft Skype Empresarial 

### <a name="outlook-non-security-updates"></a>Outlook: actualizaciones no relacionadas con la seguridad 

- Este cambio permite a los usuarios utilizar la opción Guardar todo para los archivos físicos en un recurso compartido de red, como una unidad de red asignada. 


## <a name="version-1803-october-9"></a>Versión 1803: 9 de octubre
*Versión 1803 (compilación 9126.2295)*

### <a name="excel-security-updates"></a>Excel: actualizaciones de seguridad
-   [CVE-2018-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8502): Vulnerabilidad de la ejecución remota de código de Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad 
-   [ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026): Actualización de defensa en profundidad de Microsoft Office 

### <a name="powerpoint-security-updates"></a>PowerPoint: Actualizaciones de seguridad 
-   [CVE-2018-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8501): Vulnerabilidad de la ejecución remota de código de Microsoft PowerPoint

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad 
-   [CVE-2018-8504](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8504): Vulnerabilidad de la ejecución remota de código de Microsoft Word 
-   [ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026): Actualización de defensa en profundidad de Microsoft Office 

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad 
-   [CVE-2018-8432](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8432): vulnerabilidad de la ejecución remota de código de componentes de gráficos de Microsoft 

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema por el que las aplicaciones mostraban animaciones a pesar de haber desactivado las animaciones mediante la configuración de accesibilidad y rendimiento.
-   Se ha corregido un problema por el que el fondo se volvía negro al usar la herramienta de dibujo de resaltado.

## <a name="version-1708-october-9"></a>Versión 1708: 9 de octubre
*Versión 1708 (compilación 8431.2316)*

*Esta es la versión del Canal semianual que ha estado disponible desde enero de 2018. Seguirá recibiendo soporte técnico y actualizaciones de seguridad hasta marzo de 2019. Pero ahora hay disponible una nueva versión del Canal semianual (versión 1803, compilación 16.0.9126.2282), que contiene nuevas características, actualizaciones de seguridad y actualizaciones no relacionadas con la seguridad.*

### <a name="excel-security-updates"></a>Excel: actualizaciones de seguridad
-   [CVE-2018-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8502): Vulnerabilidad de la ejecución remota de código de Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad 
-   [ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026): Actualización de defensa en profundidad de Microsoft Office 

### <a name="powerpoint-security-updates"></a>PowerPoint: Actualizaciones de seguridad 
-   [CVE-2018-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8501): Vulnerabilidad de la ejecución remota de código de Microsoft PowerPoint

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad 
-   [CVE-2018-8504](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8504): Vulnerabilidad de la ejecución remota de código de Microsoft Word 
-   [ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026): Actualización de defensa en profundidad de Microsoft Office 

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad 
-   [CVE-2018-8432](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8432): vulnerabilidad de la ejecución remota de código de componentes de gráficos de Microsoft 


## <a name="version-1803-september-11"></a>Versión 1803: 11 de septiembre
*Versión 1803 (compilación 9126.2282)*

### <a name="excel-security-updates"></a>Excel: actualizaciones de seguridad
-   [CVE-2018-8331](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8331): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8429](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8429): Vulnerabilidad de divulgación de información de Microsoft Excel

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad
-   [CVE-2018-8430](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8430): Vulnerabilidad de la ejecución remota de código de PDF de Word

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2018-8332](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8332): vulnerabilidad de la ejecución remota de código de gráficos de Win32k


## <a name="version-1708-september-11"></a>Versión 1708: 11 de septiembre
*Versión 1708 (compilación 8431.2309)*

*Esta es la versión del Canal semianual que ha estado disponible desde enero de 2018. Seguirá recibiendo soporte técnico y actualizaciones de seguridad hasta marzo de 2019. Pero ahora hay disponible una nueva versión del Canal semianual (versión 1803, compilación 16.0.9126.2282), que contiene nuevas características, actualizaciones de seguridad y actualizaciones no relacionadas con la seguridad.*

### <a name="excel-security-updates"></a>Excel: actualizaciones de seguridad
-   [CVE-2018-8331](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8331): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8429](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8429): Vulnerabilidad de divulgación de información de Microsoft Excel

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad
-   [CVE-2018-8430](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8430): Vulnerabilidad de la ejecución remota de código de PDF de Word

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2018-8332](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8332): vulnerabilidad de la ejecución remota de código de gráficos de Win32k


## <a name="version-1803-august-14"></a>Versión 1803: 14 de agosto
*Versión 1803 (compilación 9126.2275)*

### <a name="access-security-updates"></a>Access: actualizaciones de seguridad
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): vulnerabilidad de uso posterior gratis de la ejecución de código remoto de Microsoft Access

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2018-8375](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8375): Vulnerabilidad de la ejecución remota de código de Microsoft Excel 
-   [CVE-2018-8379](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8379): Vulnerabilidad de la ejecución remota de código de Microsoft Excel 
-   [CVE-2018-8382](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8382): Vulnerabilidad de divulgación de información de Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [ADV180021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180021): Actualización de defensa en profundidad de Microsoft Office 

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2018-8378](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8378): vulnerabilidad de divulgación de información de Microsoft Office 


## <a name="version-1708-august-14"></a>Versión 1708: 14 de agosto
*Versión 1708 (compilación 8431.2299)*

*Esta es la versión del Canal semianual que ha estado disponible desde enero de 2018. Seguirá recibiendo soporte técnico y actualizaciones de seguridad hasta marzo de 2019. Pero ahora hay disponible una nueva versión del Canal semianual (versión 1803, compilación 16.0.9126.2275), que contiene nuevas características, actualizaciones de seguridad y actualizaciones no relacionadas con la seguridad.*

### <a name="access-security-updates"></a>Access: actualizaciones de seguridad
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): vulnerabilidad de uso posterior gratis de la ejecución de código remoto de Microsoft Access

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2018-8375](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8375): Vulnerabilidad de la ejecución remota de código de Microsoft Excel 
-   [CVE-2018-8379](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8379): Vulnerabilidad de la ejecución remota de código de Microsoft Excel 
-   [CVE-2018-8382](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8382): Vulnerabilidad de divulgación de información de Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [ADV180021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180021): Actualización de defensa en profundidad de Microsoft Office 

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2018-8378](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8378): vulnerabilidad de divulgación de información de Microsoft Office 


## <a name="version-1803-july-10"></a>Versión 1803: 10 de julio
*Version 1803 (compilación 9126.2259)*

### <a name="access-security-updates"></a>Access: Actualizaciones de seguridad
-   [CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903): Vulnerabilidad de la ejecución remota de código de Microsoft Access
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): vulnerabilidad de uso posterior gratis de la ejecución de código remoto de Microsoft Access 

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
-   [CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877): Vulnerabilidad de omisión de característica de seguridad de Microsoft Excel
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878): Vulnerabilidad de los daños en la memoria de Microsoft Excel
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884): vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796): vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841): vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): Omisión de característica de seguridad de Microsoft Office Excel
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162): Vulnerabilidad de la ejecución remota de código de Microsoft Excel 
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163): Vulnerabilidad de divulgación de información de Microsoft Excel 
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246): Vulnerabilidad de divulgación de información de Microsoft Excel
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): Omisión de característica de seguridad de Microsoft Office Excel
-   [Advertencia 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Actualización de defensa en profundidad de Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad

-   Se ha corregido un problema donde se mostraba el año incorrecto cuando se usaba el calendario japonés Era con formato de celda de fecha.
-   Al importar datos en el modelo de datos de Excel, los valores entrantes de cero negativo crearían un error. La corrección importa esos valores como cero.
-   Se corrige un problema que en ocasiones podía desencadenar un bloqueo en una operación de agrupación (o desagrupación) en una tabla dinámica de Excel.
-   Se ha corregido un problema por el que Excel se bloqueaba al realizar acciones de gráficos.
-   Se soluciona un problema por el que el complemento de Power View se deshabilita involuntariamente para algunos usuarios.
-   Se soluciona un problema por el que los archivos de recuperación automática temporales que se crean durante la recuperación de documentos no se limpian nunca.
-   Se ha corregido un problema por el que Excel se bloqueaba al abrir un archivo de SharePoint Online.
-   Se ha corregido un problema por el que no se podía imprimir impresión rápida de un libro de Excel adjuntado a un correo electrónico de Outlook.
-   Se ha corregido un problema por el que al hacer clic en un hipervínculo, puede hacer que Excel se bloquee.
-   Se ha corregido un problema por el que al usar las funciones de cubo, Excel se bloquea.
-   Se soluciona un problema por el que Imprimir o la Vista previa de impresión solo imprime o muestra una parte de la hoja de cálculo, con el contenido truncado a una segmentación en la hoja de cálculo.
-   Se ha corregido un problema por el que cuando se intentaba realizar una nueva conexión a un archivo de texto en un libro protegido aparecía un mensaje de error "El libro está protegido y no se puede cambiar". Se ha solucionado un problema en el que, si el idioma de edición era japonés, chino o coreano, Excel se podía inmovilizar cuando intentaba elegir una nueva fuente en la pestaña Inicio o al editar.
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
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939): Vulnerabilidad de divulgación de información de Microsoft Office
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791): Vulnerabilidad de ejecución remota de código de Microsoft Outlook
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): vulnerabilidad de ejecución remota de código de Microsoft Outlook
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850): Vulnerabilidad de elevación de privilegios de Microsoft Outlook
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852): Vulnerabilidad de los daños en la memoria de Microsoft Outlook
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150): Vulnerabilidad de omisión de característica de seguridad de Microsoft Outlook
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244): Vulnerabilidad de elevación de privilegios de Microsoft Outlook
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310): vulnerabilidad de manipulación de Microsoft Office

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema por el que Outlook se bloqueaba al cambiar a la carpeta Elementos enviados o la Bandeja de salida.
-   Se soluciona un problema por el que todos los asistentes recibían actualizaciones de la reunión cuando cambiaban el cuerpo de la reunión o los datos adjuntos, en lugar de que fuese opcional que se enviase una actualización de la reunión a los asistentes.
-   Se soluciona un problema por el que los usuarios no podían conectarse a los extremos REST y EWS debido a un cambio en la cadena de agente de usuario.
-   Se ha corregido un problema por el que una actualización de la ubicación de la reunión para los asistentes muestra la ubicación anterior en lugar de la nueva.
-   Se ha corregido un problema por el que el usuario ve un error al obtener una vista previa de los datos adjuntos en el panel de lectura.
-   Se ha corregido un problema por el que Outlook se bloquea al resolver nombres para mostrar en direcciones de correo electrónico cuando el usuario está redactando un correo electrónico.
-   Se ha corregido un problema por el que algunos usuarios no recibían características de soporte técnico que había habilitado su administrador de espacio empresarial.
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
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934): Vulnerabilidad de divulgación de información de Microsoft PowerPoint

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido el problema en el que las tablas se representaban incorrectamente con un borde grueso.
-   Se corrige un problema que podía producir un posible bloqueo al cambiar la propiedad Shape.Visibile.
-   Se corrige un problema por el que no podían combinarse los cambios efectuados en documentos en coautoría.
-   Se corrige un problema por el que no se realizaba la coautoría en documentos que contenían controles ActiveX.
-   Se ha corregido un problema por el que PowerPoint se bloqueaba al pasar el corrector ortográfico en formas.
-   Se ha corregido un problema por el que PowerPoint se bloqueaba al abrir un archivo de SharePoint Online.
-   Se soluciona un problema por el que el Panel de recuperación aparecía incorrectamente cuando Autoguardado está activado.
-   Se soluciona un problema por el que Iniciar sesión no se mostraba, lo que impedía que un usuario accediese a un archivo.
-   Se soluciona un problema que provocaba que, cuando había varios usuarios trabajando en coautoría en la misma presentación, se duplicaran de forma incorrecta los patrones de diapositivas.
-   Se ha corregido un problema en el que abrir un archivo guardado en OneDrive causaba que PowerPoint se bloquease al salir de la vista protegida. Se ha corregido un problema en el que quitar las propiedades del documento y la información personal causaba un error al guardar en SharePoint.
-   Se ha corregido un problema que provocaba que se abriera una ventana nueva para reproducir el vídeo al usar referencias a Flash Player basadas en código para insertar de YouTube. Se han actualizado los códigos para insertar antiguos con referencias a HTML5 basadas en vídeos de YouTube para que se reproduzcan correctamente en su ubicación.
-   Se ha solucionado un problema que provocaba que Office no pudiera escribir en el disco al guardar un archivo de copia de sincronización, pero Office siguiera cargando el archivo en OneDrive. Con esta corrección, ahora el usuario ve un mensaje de error y la carga no se realiza.

### <a name="project-feature-updates"></a>Project: Actualizaciones de características
-   **Visualización Panel de tareas:** Ordene tareas en las tarjetas desde la visualización Panel de tareas. Reordene y mueva las tarjetas en las columnas del panel de la misma forma que con los proyectos ágiles.
-   **Proyectos ágiles:** administre sus proyectos ágiles mediante trabajos pendientes, paneles de tareas, sprints y mucho más. Se admiten las metodologías de Scrum o Kanban. [Más información](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)  
-   **Administrar una tarea en Planner:** Vincule una tarea de Project a Planner y cree un plan para esta. Divida la tarea en subtareas, agregue un equipo, asigne tareas y administre el trabajo en un panel de tareas.

### <a name="project-non-security-updates"></a>Project: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema en el que si se dividía una tarea con un recurso de costo, el recurso de costo no se actualizaba correctamente y se perdía el costo.
-   Se corrige un problema por el que solo se mostraban las tareas de la primera tarea de resumen en la vista Escala de tiempo del cuadro de diálogo Agregar tareas existentes a la escala de tiempo.
-   Se ha corregido un problema por el que podía fallar Guardar como XML para proyectos principales de Project Online o Project Server.
-   Se corrige un problema por el que solo se mostraban las tareas de la primera tarea de resumen en la vista Escala de tiempo del cuadro de diálogo Agregar tareas existentes a la escala de tiempo.
-   Se ha corregido un problema por el que al usar el menú desplegable Filtro automático en una columna de fecha se ocultaban todas las tareas del proyecto.
-   Se soluciona un problema por el que solo se mostraban las tareas de la primera tarea de resumen en el cuadro de diálogo al agregar tareas existentes a una escala de tiempo en la vista Escala de tiempo.
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
-   Se soluciona un problema relacionado con la compatibilidad del protocolo TLS 1.2.
-   Se ha corregido un problema que se producía al agregar usuarios seleccionando “Llamada de Skype” en una reunión.
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
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792): Vulnerabilidad de la ejecución remota de código de Microsoft Word
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Vulnerabilidad de ejecución remota de código de Microsoft Outlook
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812): vulnerabilidad de daños en la memoria de Microsoft Word
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919): vulnerabilidad de divulgación de información de Microsoft Office
-   [Advertencia 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020): Actualización de defensa en profundidad de Microsoft Office

### <a name="word-non-security-updates"></a>Word: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema por el que Word se bloqueaba al abrir un archivo de SharePoint Online.
-   Se soluciona un problema por el que los números de página en número romanos en minúscula se cambian incorrectamente a mayúsculas.
-   Se soluciona un problema que provocaba que apareciera un mensaje de memoria insuficiente.
-   Se ha corregido un problema por el que Word no se abre en un equipo con Windows 7 que no tiene la actualización de la experiencia del cliente y la telemetría de diagnóstico instalada.
-   Se ha corregido un problema por el que no se imprimen las viñetas de listas.
-   Se ha corregido un problema que provocaba que Word se bloqueara cuando un usuario intentaba usar Guardar como sobre un documento existente en OneDrive para la Empresa y, seguidamente, cancelaba o intentaba combinar cambios existentes.
-   Se ha corregido un problema que, al filtrar campos de orígenes de datos que contuvieran valores nulos (vacíos), provocaba errores al ejecutar el Asistente para combinar correspondencia.
-   Se ha solucionado un problema que provocaba que Office no pudiera escribir en el disco al guardar un archivo de copia de sincronización, pero Office siguiera cargando el archivo en OneDrive. Con esta corrección, ahora el usuario ve un mensaje de error y la carga no se realiza.
-   Se ha solucionado un problema que, al quitar la protección IRM de un documento, provocaba que dicha protección no se eliminara.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795): vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853): Vulnerabilidad de divulgación de información de Microsoft Office
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950): Vulnerabilidad de divulgación de información de Microsoft Office
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281): vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [Advertencia 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003): Actualización de defensa en profundidad de Microsoft Office

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad
-   Se corrige un problema por el que, al implementar actualizaciones con Configuration Manager en un cliente que tiene aplicaciones de Office en ejecución, la actualización no se aplica después de reiniciar el dispositivo mientras se ejecutan las aplicaciones de Office.
-   Se ha corregido un problema que provocaba que, al abrir una aplicación, el usuario viera un mensaje sobre iniciar en modo seguro y después la aplicación no se abriera.
-   La opción "Actualizar ahora" está oculta en Archivo \> Cuenta \> Opciones de actualización cuando se habilita un objeto COM de Office para que Configuration Manager administre las actualizaciones de cliente de Office 365.
-   Se ha solucionado un problema que causaba que la aplicación de Office se bloquease cuando el usuario intentaba activar Office con el cuadro de diálogo Activar Office.
-   Se ha solucionado un problema relacionado con el zoom y el escalado en Complementos de Office en el entorno de PPP dinámico.
-   Se ha corregido un problema que provocaba que el nodo CurrentStatus del proveedor del servicio de configuración (CSP) de Office devolviera una cadena vacía incluso si Office 365 ProPlus está instalado.
-   Se ha corregido un problema que provocaba cambios en los formatos de archivo .box. Esto afectaba la funcionalidad de versiones antiguas de Office instaladas en el mismo equipo, porque los archivos .box se comparten con todas las versiones de una aplicación de Office en el mismo equipo.
-   Se ha corregido un error que causaba que la instalación de la actualización a tardase mucho tiempo en determinados escenarios. 
-   Se ha corregido un problema en el que estaban fallando las pruebas SVG
-   Se corrige un problema por el que, al implementar actualizaciones con Configuration Manager en un cliente que tiene aplicaciones de Office en ejecución, la actualización no se aplica después de reiniciar el dispositivo mientras se ejecutan las aplicaciones de Office.


## <a name="version-1708-july-10"></a>Versión 1708: 10 de julio
*Versión 1708 (compilación 8431.2280)*

*Esta es la versión del Canal semianual que ha estado disponible desde enero de 2018. Seguirá recibiendo soporte técnico y actualizaciones de seguridad hasta marzo de 2019. Pero ahora hay disponible una nueva versión del Canal semianual (versión 1803, compilación 9126.2259), que contiene nuevas características, actualizaciones de seguridad y actualizaciones no relacionadas con la seguridad.*

### <a name="access-security-updates"></a>Access: actualizaciones de seguridad
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): vulnerabilidad de uso posterior gratis de la ejecución de código remoto de Microsoft Access

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310): vulnerabilidad de manipulación de Microsoft Office

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281): vulnerabilidad de la ejecución remota de código de Microsoft Office


## <a name="version-1708-june-12"></a>Versión 1708: 12 de junio
*Versión 1708 (compilación 8431.2270)*

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246): Vulnerabilidad de divulgación de información de Microsoft Excel
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248): Vulnerabilidad de la ejecución remota de código de Microsoft Excel

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244): Vulnerabilidad de elevación de privilegios de Microsoft Outlook

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones no relacionadas con la seguridad
-   Se corrige un problema que impedía a los usuarios de Windows 7 SP1 agregar miembros a grupos modernos.



## <a name="version-1705-june-12"></a>Versión 1705: 12 de junio
*Versión 1705 (compilación 8201.2294)*

*Esta es la versión del Canal diferido que ha estado disponible desde septiembre de 2017. Seguirá recibiendo soporte técnico y actualizaciones de seguridad hasta julio de 2018. Pero ahora hay disponible una nueva versión del Canal semianual (versión 1708, compilación 8431.2270), que contiene nuevas características, actualizaciones de seguridad y actualizaciones no relacionadas con la seguridad.*

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246): Vulnerabilidad de divulgación de información de Microsoft Excel
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248): Vulnerabilidad de la ejecución remota de código de Microsoft Excel

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244): Vulnerabilidad de elevación de privilegios de Microsoft Outlook



## <a name="version-1708-may-8"></a>Versión 1708: 8 de mayo
*Versión 1708 (compilación 8431.2250)*

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163): Vulnerabilidad de divulgación de información de Microsoft Excel

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150): Vulnerabilidad de omisión de característica de seguridad de Microsoft Outlook

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158): Vulnerabilidad de la ejecución remota de código de Microsoft Office



## <a name="version-1705-may-8"></a>Versión 1705: 8 de mayo
*Versión 1705 (compilación 8201.2278)*

*Esta es la versión del Canal diferido que ha estado disponible desde septiembre de 2017. Seguirá recibiendo soporte técnico y actualizaciones de seguridad hasta julio de 2018. Pero ahora hay disponible una nueva versión del Canal semianual (versión 1708, compilación 8431.2250), que contiene características nuevas, actualizaciones de seguridad y actualizaciones no relacionadas con la seguridad.*

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163): Vulnerabilidad de divulgación de información de Microsoft Excel

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150): Vulnerabilidad de omisión de característica de seguridad de Microsoft Outlook

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158): Vulnerabilidad de la ejecución remota de código de Microsoft Office



## <a name="version-1708-april-10"></a>Versión 1708: 10 de abril
*Versión 1708 (compilación 8431.2242)*

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029): Vulnerabilidad de la ejecución remota de código de Microsoft Excel

### <a name="skype-for-business-non-security-updates"></a>Skype Empresarial: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema relacionado con la compatibilidad del protocolo TLS 1.2.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950): Vulnerabilidad de divulgación de información de Microsoft Office
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030): Vulnerabilidad de la ejecución remota de código de Microsoft Office



## <a name="version-1705-april-10"></a>Versión 1705: 10 de abril
*Versión 1705 (compilación 8201.2272)*

*Esta es la versión del Canal diferido que ha estado disponible desde septiembre de 2017. Seguirá recibiendo soporte técnico y actualizaciones de seguridad hasta julio de 2018. Pero ahora hay disponible una nueva versión del Canal semianual (versión 1708, compilación 8431.2242), que contiene características nuevas, actualizaciones de seguridad y actualizaciones no relacionadas con la seguridad.*

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029): Vulnerabilidad de la ejecución remota de código de Microsoft Excel

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950): Vulnerabilidad de divulgación de información de Microsoft Office
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030): Vulnerabilidad de la ejecución remota de código de Microsoft Office



## <a name="version-1708-march-13"></a>Versión 1708: 13 de marzo
*Versión 1708 (compilación 8431.2236)*

### <a name="access-security-updates"></a>Access: Actualizaciones de seguridad
-   [CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903): Vulnerabilidad de la ejecución remota de código de Microsoft Access

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): Omisión de característica de seguridad de Microsoft Office Excel

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919): Vulnerabilidad de divulgación de información de Microsoft Office



## <a name="version-1705-march-13"></a>Versión 1705: 13 de marzo
*Versión 1705 (compilación 8201.2265)*

*Esta es la versión del Canal diferido que ha estado disponible desde septiembre de 2017. Seguirá recibiendo soporte técnico y actualizaciones de seguridad hasta julio de 2018. Pero ahora hay disponible una nueva versión del Canal semianual (versión 1708, compilación 8431.2236), que contiene características nuevas, actualizaciones de seguridad y actualizaciones no relacionadas con la seguridad.*

### <a name="access-security-updates"></a>Access: Actualizaciones de seguridad
-   [CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903): Vulnerabilidad de la ejecución remota de código de Microsoft Access

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): Omisión de característica de seguridad de Microsoft Office Excel

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919): Vulnerabilidad de divulgación de información de Microsoft Office



## <a name="version-1708-february-13"></a>Versión 1708: 13 de febrero
*Versión 1708 (compilación 8431.2215)*

### <a name="access-non-security-updates"></a>Access: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema que provocaba que, al usar un formulario de varios elementos, al cambiar la posición con la rueda del ratón o con la barra de desplazamiento no se cambiasen los elementos mostrados en el formulario.

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841): Vulnerabilidad de la ejecución remota de código de Microsoft Excel

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850): Vulnerabilidad de elevación de privilegios de Microsoft Outlook
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852): Vulnerabilidad de los daños en la memoria de Microsoft Outlook

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853): Vulnerabilidad de divulgación de información de Microsoft Office



## <a name="version-1705-february-13"></a>Versión 1705: 13 de febrero
*Versión 1705 (compilación 8201.2258)*

*Esta es la versión del Canal diferido que ha estado disponible desde septiembre de 2017. Seguirá recibiendo soporte técnico y actualizaciones de seguridad hasta julio de 2018. Pero ahora hay disponible una nueva versión del Canal semianual (versión 1708, compilación 8431.2215), que contiene características nuevas, actualizaciones de seguridad y actualizaciones no relacionadas con la seguridad.*

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841): Vulnerabilidad de la ejecución remota de código de Microsoft Excel

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850): Vulnerabilidad de elevación de privilegios de Microsoft Outlook
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852): Vulnerabilidad de los daños en la memoria de Microsoft Outlook

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853): Vulnerabilidad de divulgación de información de Microsoft Office



## <a name="version-1708-january-9"></a>Versión 1708: 9 de enero
*Versión 1708 (compilación 8431.2153)*

### <a name="access-feature-updates"></a>Access: Actualizaciones de características
-   **Propiedad de nombre de etiqueta:** mejore la accesibilidad mediante la asociación de una etiqueta con un control en un formulario.
-   **Editar un nuevo elemento es más accesible:** Utilizar métodos abreviados de teclado rápido (CTRL+E) para editar un nuevo elemento de un cuadro combinado o cuadro de lista.
-   **Conector de Dynamics:** permite importar datos o vincular a datos almacenados en Microsoft Dynamics. [Más información](https://support.office.com/article/636079c1-9fc3-4fca-8410-6596d62223da)
-   **Conector de Salesforce:** permite importar datos o vincular a datos almacenados en Salesforce. [Más información](https://support.office.com/article/7375ffb6-1d6a-46f1-bb0c-c6ac3c58f5a0)

### <a name="access-non-security-updates"></a>Access: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema que provocaba que pareciera que se seleccionaba todo el texto al intentar seleccionar texto en un cuadro de texto o en un cuadro combinado, en lugar de mostrarse la selección real.
-   Se soluciona un problema por el que una consulta no se ejecuta si tiene una unión con una clave principal de una tabla vinculada de Microsoft Dynamics.
-   Se soluciona un problema por el que no aparecen los decimales para los valores de moneda en una tabla de Microsoft Dynamics.

### <a name="excel-feature-updates"></a>Excel: Actualizaciones de características
-   **Mejoras de "Agregar columna a partir de los ejemplos":** admite más transformaciones de fecha y hora, matemáticas y columna de índice.
-   **Mejora de rendimiento:** Excel abre libros complejos con varias hojas con mayor rapidez, para que pueda procesar fácilmente fórmulas con rangos extensos, filtrar un gran número de filas, o copiar y pegar más rápido.
-   **Insertar imágenes en línea:** Nueva página de destino para la selección de imágenes. Además, la información de atribución se inserta automáticamente con la imagen.
-   **Conector Azure Data Lake Store:** Ahora, los usuarios pueden importar datos desde Azure Data Lake Store.
-   **Mejoras en la opción “Agregar columna a partir de ejemplos”:** Admite sugerencias, más operaciones de fecha y hora, así como transformaciones adicionales.
-   **Pestaña Datos**: Los botones de la cinta de opciones de la pestaña Datos se han reorganizado en dos nuevos grupos: Obtener y transformar datos y Consultas y conexiones.
-   **Uso compartido de consultas**: Exporte cualquier definición de consulta en un archivo de conexión de base de datos de Office (ODC) y, a continuación, compártalo en libros o con otros usuarios.
-   **Carga de datos** Cargue datos desde una consulta directamente en tablas dinámicas o gráficos dinámicos sin tener que guardar los datos en el modelo de datos.
-   **Actividad de archivo compartido:** Elija el botón Actividad en la esquina superior derecha del archivo para ver cuando un archivo compartido en OneDrive para la Empresa o SharePoint se compartió, se editó, se restauró o se cambió de nombre.
-   **Vínculos seguros:** Cuando un usuario hace clic en un vínculo, Protección contra amenazas avanzada de Office 365 (ATP) lo inspecciona para comprobar si es malintencionado o no. Si el vínculo se considera malintencionado, se redirige al usuario a una página de advertencia en lugar de redirigirlo a la URL de destino original. [Más información](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Funcionalidad de importación de datos mejorada:** Puede importar datos de varios orígenes y darles forma con facilidad. Administre las consultas y las conexiones de los libros con el panel lateral Consultas y conexiones y comparta las consultas con otros usuarios mediante archivos ODC. [Más información](https://support.office.com/article/ad78befd-eb1c-4ea7-a55d-79d1d67cf9b3)
-   **Cambios en archivos compartidos**: vea quién ha realizado cambios en los libros compartidos y restaurar versiones anteriores. [Más información](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)
-   **Selección de lazo con un botón del lápiz:** use los botones de un lápiz digital admitido para la selección de lazo de lápiz sin necesidad de ir a la cinta de opciones.

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2017-8631](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8631): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2017-8632](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8632): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877): Vulnerabilidad de omisión de característica de seguridad de Microsoft Excel
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878): Vulnerabilidad de los daños en la memoria de Microsoft Excel
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2017-11935](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11935): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [Advertencia 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Actualización de defensa en profundidad de Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema por el que Excel se bloqueaba al crear mediante programación una tabla dinámica y, después, realizar una actualización mediante programación.
-   Se soluciona un problema por el que el usuario veía por error el mensaje “Error grave” al abrir un libro de Office 2007 o anterior (.xls o .xla) con macros.
-   Se soluciona un problema por el que, al abrir un libro desde la línea de comandos, se podía perder el formato de texto enriquecido de una celda.
-   Se soluciona un problema por el que un usuario no podía cerrar un libro en vista protegida si el nombre de archivo contenía corchetes.
-   Se ha corregido un problema que provocaba que Excel se bloqueara cuando el usuario hacía clic en Examinar al intentar insertar un objeto en un libro existente.
-   Se ha corregido un problema que provocaba que no se modificara la forma al seleccionar "Ajustar tamaño de la forma al texto" en la sección Cuadro de texto de Opciones de texto en el panel Formato de forma.
-   Se ha corregido un problema que provocaba que las fuentes y los formatos de texto de las celdas no se cargaran o se abrieran dos libros idénticos con una única plantilla al hacer doble clic para abrir un libro.
-   Se ha corregido un problema que provocaba que el primer libro creado al iniciar Excel no se cerrara al abrir o crear un libro nuevo.
-   Se ha corregido un problema que provocaba que el desplazamiento de la información en pantalla quedara incorrectamente alineada al arrastrar elementos o rellenarlos arrastrando.
-   Se ha corregido un problema que, al guardar un libro con Archivo \> Guardar como, provocaba que los nombres de archivos que contuvieran puntos aparecieran en blanco o truncados en el cuadro de diálogo de guardar.
-   Se ha corregido un problema que provocaba que Office no pudiera escribir en el disco al guardar un archivo de copia de sincronización, pero Office siguiera cargando el archivo en OneDrive. Con esta corrección, ahora el usuario ve un mensaje de error y la carga no se realiza.
-   Se ha corregido un problema de representación que provocaba que aparecieran líneas y encabezados negros debido a un controlador de gráficos defectuoso.
-   Se ha corregido un problema que provocaba que Excel se bloqueara o no fuera posible guardar un libro tras insertar un gráfico.
-   Se soluciona un problema por el que la línea de salto de página se colocaba de forma incorrecta en la vista previa de salto de página.
-   Se soluciona un problema por el que Excel se bloqueaba al abrir un archivo .XLL.
-   Se soluciona un problema por el que el estilo de trama de una celda no se representaba correctamente después de agregar un encabezado o pie de página en la vista de diseño de página.
-   Se soluciona un problema por el que pegar una copia de una tabla dinámica en otro libro podría ocasionar un bloqueo.
-   Se soluciona un problema por el que, cuando elige el comando Reemplazar y se abre el cuadro de diálogo Buscar y reemplazar, el foco del cuadro de diálogo se encuentra en la ficha Buscar, en lugar de la ficha Reemplazar.
-   Se corrige un problema por el que Excel se bloquea al abrir el panel Actividad de un libro abierto desde un servidor de SharePoint anterior a SharePoint Server 2016.
-   Se soluciona un problema por el que Excel se abre y muestra una ventana en blanco cuando están habilitados uno o más complementos XLL.
-   Se corrige un problema por el que Excel se bloquea después de haber utilizado el botón Formularios en un libro ya cerrado.
-   Se soluciona un problema por el que, cuando se utiliza el evento SheetBeforeRightClick, la inserción de una columna que forma una intersección con celdas combinadas no expande las celdas combinadas.
-   Se soluciona un problema por el que Excel se bloqueaba temporalmente al expandir o contraer una tabla dinámica. Además, los encabezados de las tablas dinámicas se mostraban fuera de la pantalla.
-   Se ha solucionado un problema por el que se omitían los caracteres de tabulación al copiar y pegar texto delimitado por tabulaciones desde Word, lo que causaba que el texto no se dividiera en columnas.
-   Se ha solucionado un problema por el que Excel se bloqueaba al abrir el cuadro de diálogo Publicar como página web.
-   Se ha solucionado un problema por el que no se realizaba correctamente una actualización de datos o Excel se bloqueaba al usar datos de un servidor de SQL Server Analysis Services cuando la configuración regional de Excel no era la misma que la del servidor de SQL Server Analysis Services.
-   Se ha solucionado un problema que provocaba errores al intentar guardar cambios de documentos sincronizados con el cliente de OneDrive.
-   Se ha corregido un problema que no permitía realizar cambios en ningún elemento de una hoja de cálculo al haber una tabla dinámica con campos en el área Filtrar, pero sin ningún otro campo en otras ubicaciones.

### <a name="outlook-feature-updates"></a>Outlook: Actualizaciones de características
-   **Mejoras de accesibilidad:** se han realizado cambios para facilitar la lectura y edición de texto, tablas, listas e imágenes en el correo electrónico al usar un lector de pantalla.
-   **Configuración de cuentas nuevas:** Configure las nuevas cuentas con un nuevo asistente que requiere menos pasos manuales.
-   **Cuadro de diálogo de adjuntar vínculos:** Al adjuntar un vínculo mediante Adjuntar archivo en la cinta de opciones, puede seleccionar si desea agregarlo como un vínculo o como un archivo adjunto. Si no quiere ver este cuadro de diálogo cada vez, vaya a Archivo \> Opciones \> General y especifique cómo desea que los vínculos se asocien en “Opciones de datos adjuntos”.
-   **Compatibilidad con archivos adjuntos locales:** Los archivos de la versión local de SharePoint Server se muestran como archivos recientes en Mensaje \> Adjuntar archivo. Los sitios de grupo de las versiones locales de OneDrive para la Empresa y SharePoint aparecen en Adjuntar archivo \> Explorar sitios web. Además, es posible cargar archivos locales en los sitios de la versión local de OneDrive para la Empresa.
-   **Clasificaciones empresariales de los grupos:**  Al crear o editar un grupo, se le puede asignar un nivel de clasificación empresarial definido por el administrador del espacio empresarial (por ejemplo, Confidencial). La clasificación en cuestión aparecerá en el encabezado de grupo.
-   **Acceso de invitado a los grupos de Office 365:** Colabore con personas ajenas a la organización concediéndoles acceso a las conversaciones del grupo, archivos, invitaciones del calendario y el bloc de notas del grupo. [Más información](https://support.office.com/article/bfc7a840-868f-4fd6-a390-f347bf51aff6)
-   **Mensajes accionables:** los desarrolladores pueden crear mensajes para facilitar a los usuarios la realización de acciones simples o rápidas y sin tener que cambiar a un sitio web externo o a otra aplicación, directamente desde Outlook. [Más información](https://dev.office.com/blogs/create-more-engaging-conversations-with-new-actionable-messages-updates-announced-at-microsoft-build)

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571): Vulnerabilidad de omisión de característica de seguridad de Microsoft Office Outlook
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572): Vulnerabilidad de divulgación de información de componente de Microsoft Office Outlook
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663): Vulnerabilidad de los daños en la memoria de Microsoft Office Outlook
-   [CVE-2017-11774](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11774): Vulnerabilidad de omisión de característica de seguridad de Microsoft Outlook
-   [CVE-2017-11776](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11776): Vulnerabilidad de divulgación de información de Microsoft Office Outlook
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939): Vulnerabilidad de divulgación de información de Microsoft Office
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791): Vulnerabilidad de ejecución remota de código de Microsoft Outlook
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Vulnerabilidad de ejecución remota de código de Microsoft Outlook

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema por el que el foco de la lista de mensajes cambiaba de ubicación de forma inesperada cuando el usuario eliminaba mensajes.
-   Se soluciona un problema por el que el usuario recibía peticiones de autenticación al interactuar con datos adjuntos.
-   Se soluciona un problema por el que el vínculo “Más información” de las sugerencias de directiva no era visible al usar el tema “Gris oscuro”.
-   Se soluciona un problema por el que Outlook se bloquea cuando un usuario está intentando configurar una nueva cuenta y cierra la ventana sin que haya finalizado la configuración de la cuenta.
-   Se soluciona un problema por el que Marcar como leído y Marcar como no leído se muestran como opciones para los mensajes de la Bandeja de entrada compartida de un grupo.
-   Se soluciona un problema por el que no se podía configurar una cuenta IMAP en Outlook.
-   Se ha solucionado un problema que provocaba un fallo intermitente al abrir Outlook.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Actualizaciones de características
-   **Insertar imágenes en línea:** nueva página de destino para la selección de imágenes. Además, la información de atribución se inserta automáticamente con la imagen.
-   **Subtítulos para los vídeos:** agregue subtítulos a los vídeos para que sean más accesibles. [Más información](https://support.office.com/article/a16745e1-b3da-4428-b2a7-ff0c8b758d0b)
-   **Incluir comentarios en una grabación:** Incluya un vídeo con sus propios comentarios cuando grabe una presentación. Las grabaciones pueden incluir animaciones, entradas de lápiz, audio y vídeo.
-   **Actividad de archivo compartido:** Elija el botón Actividad en la esquina superior derecha del archivo para ver cuando un archivo compartido en OneDrive para la Empresa o SharePoint se compartió, se editó, se restauró o se cambió de nombre.
-   **Creación de texto alternativo:** Un servicio basado en cloud genera automáticamente texto alternativo para las imágenes de una presentación.
-   **Vínculos seguros:** Cuando un usuario hace clic en un vínculo, Protección contra amenazas avanzada de Office 365 (ATP) lo inspecciona para comprobar si es malintencionado o no. Si el vínculo se considera malintencionado, se redirige al usuario a una página de advertencia en lugar de redirigirlo a la URL de destino original. [Más información](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Mejoras para diseñadores:** se recomiendan ideas de diseño profesional para las listas de acción.
-   **Cambios en archivos compartidos:** vea quién ha realizado cambios en las presentaciones compartidas y restaurar versiones anteriores. [Más información](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="powerpoint-security-updates"></a>PowerPoint: Actualizaciones de seguridad
-   [CVE-2017-8742](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8742): Vulnerabilidad de la ejecución remota de código de PowerPoint
-   [CVE-2017-8743](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8743): Vulnerabilidad de la ejecución remota de código de PowerPoint
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934): Vulnerabilidad de divulgación de información de Microsoft PowerPoint

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema que provocaba que Office no pudiera escribir en el disco al guardar un archivo de copia de sincronización, pero Office siguiera cargando el archivo en OneDrive. Con esta corrección, ahora el usuario ve un mensaje de error y la carga no se realiza.
-   Se ha corregido un problema que provocaba que PowerPoint se bloqueara al editar y aplicar formato al texto tras deshacer un cambio en una tabla.
-   Se ha corregido un problema que provocaba que se abriera una ventana nueva para reproducir el vídeo al usar referencias a Flash Player basadas en código para insertar de YouTube. Se han actualizado los códigos para insertar antiguos con referencias a HTML5 basadas en vídeos de YouTube para que se reproduzcan correctamente en su ubicación.
-   Se corrige un problema por el que PowerPoint se bloquea al abrir una presentación desde un servidor de SharePoint anterior a SharePoint Server 2016.
-   Se soluciona un problema que causaba que no se mostraran los caracteres definidos por el usuario final (EUDC) que están vinculados a  fuentes.

### <a name="project-non-security-updates"></a>Project: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema que provocaba que se pudieran perder datos de campos personalizados de nivel de proyecto al guardar.
-   Se ha corregido un problema que provocaba que un error al guardar podía dañar un archivo y hacer que Project se bloqueara al abrirlo.
-   Se ha corregido un problema que provocaba que al abrir un plan de proyecto pudiera producirse un bloqueo.
-   Se soluciona un problema por el que Project se bloqueaba al abrir determinados archivos de Project Online.
-   Se ha solucionado un problema por el que Inicio real podía borrarse por error al establecer trabajo restante.
-   Se corrigió un problema por el que, en Fecha de inicio real de la tarea, podían mostrarse datos distintos de los indicados por el recurso en el estado de Project Web App.
-   Se corrigió un problema que causaba que el trabajo real volviera a programarse si se cambiaba la fecha de finalización de la tarea.
-   Se corrigió un problema que causaba que, al copiar y pegar campos de costos, los valores pegados no coincidieran exactamente con los valores copiados debido a un error de redondeo.
-   Se corrigió un problema que causaba que los datos de fase temporal para los recursos de un presupuesto no se copiaran al guardar de una línea base a otra.
-   Se corrigió un problema que causaba que el campo de estado no siempre se calculara correctamente para las tareas de resumen.
-   Se ha solucionado un problema que producía que trabajo real se transfiriese de forma errónea a un recurso de empresa al sustituir un recurso local y cuando está habilitado el trabajo protegido.
-   Corrección de un problema que producía que Project se bloquease si tenía una tabla en la que la primera columna fuese Nombre de tarea, la columna estuviese bloqueada e hiciese clic en una tarea.
-   Corrección de un problema que producía que pudiese asignar el mismo recurso varias veces a la misma tarea mediante la vista Uso de tareas.
-   Corrección de un problema que producía que los valores en los campos personalizados de número se perdiesen al abrir archivos XML.
-   Corrección de un problema que producía que la sangría de tareas de nivel superior no se sincronizase correctamente entre Project y la lista de tareas de SharePoint.
-   Corrección de un problema que producía que, al importar información de una asignación, recurso o tarea de un libro de Excel, se ignorasen los valores en el campo de trabajo.
-   Se ha solucionado un problema que provocaba que los valores de Línea base de fase temporal no coincidieran con los valores iniciales al guardar un proyecto en el formato de archivo XML.
-   Se corrige un problema que provocaba que el cliente de Project no abriera un proyecto, ya que detectaba que se había extraído del repositorio cuando, realmente, no era así.
-   Se corrige un problema que ralentizaba la apertura de los archivos de Project desde un servidor de archivos con una latencia alta.

### <a name="skype-for-business-security-updates"></a>Skype Empresarial: Actualizaciones de seguridad
-   [CVE-2017-8676](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8676): Vulnerabilidad de la revelación de información de GDI+ de Windows
-   [CVE-2017-8695](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8695): Vulnerabilidad de divulgación de información de componente de gráficos
-   [CVE-2017-8696](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8696): Ejecución remota de código de componente de gráficos de Microsoft

### <a name="skype-for-business-non-security-updates"></a>Skype Empresarial: Actualizaciones no relacionadas con la seguridad
-   Se agrega un cuadro de diálogo en el que se explica por qué un usuario no puede unirse a una reunión cuando determinados puertos están bloqueados o las direcciones IP no están permitidos.
-   Se ha solucionado un problema por el que los mensajes no leídos en salones de chat persistentes se marcaban como leídos cuando se hace clic en las pestañas de conversación de mensajería instantánea.
-   Se ha solucionado un problema en la que las notificaciones de mensajería instantánea entrantes experimentaban un retraso de varios segundos.
-   Se ha solucionado un problema en el que un contacto de AD se mostraba como un número de teléfono en lugar del nombre del contacto cuando está deshabilitada la sincronización con Exchange.
-   Se ha solucionado un problema en el que se impedía a los usuarios anónimos unirse cuando estaba deshabilitada la federación y el organizador de la reunión no había bloqueado explícitamente las uniones anónimas.
-   Se ha solucionado un problema en el que se mostraba de manera incorrecta al organizador de la reunión el número de invitados para reuniones que excedían el límite de la reunión.
-   Se ha solucionado un problema en el que el número de teléfono no se mostraba en las notificaciones sobre llamadas RTC entrantes.
-   Se ha solucionado un problema en el que, cuando se usaba la tecla Supr mientras se cambiaba el nombre de un grupo de la lista de contactos, se eliminaba todo el grupo.
-   Se ha solucionado un problema en el que se descartaba la notificación para compartir de una conversación de mensajería instantánea antes de que se dejara de compartir.
-   Se ha solucionado un problema que causaba que la pantalla de inicio de sesión se mostrara en blanco para algunos idiomas distintos del inglés.
-   Se ha solucionado un problema que causaba que los caracteres que no pertenecieran al alfabeto inglés aparecieran cifrados en el chat y en el historial de chat.
-   Se muestra el número de teléfono de una llamada entrante controlada por el Operador automático de la organización si no se conoce el nombre del usuario.
-   Agregar una configuración de banda que permita la restricción de "Cualquiera (sin restricciones)" como una opción para "Estas personas no tienen que esperar en el vestíbulo".
-   Agregar capacidad de activar o desactivar auto vídeo para videollamadas P2P en VDIv2.
-   Se ha corregido un problema que mostraba los números duplicados de contactos en el menú desplegable llamar.
-   Se ha corregido un problema que quitaba los delegados para los usuarios que se movían entre Skype Empresarial y Skype Empresarial Basic.
-   Se ha solucionado un problema en el que el estado Desconectado no era visible al usar las directivas de cliente Habilitar desconectado y URL de estado de cliente.
-   Se ha ampliado el botón Unirse a la reunión para corregir un truncamiento en algunos de los idiomas localizados.
-   Se ha aumentado la prominencia de los mensajes de importancia alta en el chat.
-   Se agregan tipos de extensión de archivo de Skype Empresarial y de Office a las listas de transferencias de archivos bloqueadas permitidas.
-   Se aplican correcciones de ubicación en las invitaciones a reuniones de Outlook para el texto del pie de página establecido en un idioma diferente al inglés en las reuniones.
-   Se corrige un problema que provocaba que los nombres de los remitentes se cambiaran a veces en las conversaciones de varios usuarios.
-   Se corrige un problema que provocaba que la ventana de las conversaciones en blanco no apareciera hasta que no se había unido correctamente a una reunión.
-   Se corrige un problema que provocaba que la información del campo del departamento de una tarjeta de contacto no apareciera en los resultados de la búsqueda si el campo del título estaba vacío.
-   Se corrigen los errores de inicio de sesión de los usuarios migrados de un entorno local a uno en línea que se producían a causa de las reglas de firewall.
-   Se ha agregado una nueva clave del Registro DWORD para corregir un problema que provocaba que, cuando un usuario iniciaba sesión en el cliente en una red externa con LyncAutoD, el cliente restableciese la clave del Registro de OAuthUsed a false. Para solucionar el problema, establezca el valor en 1 para EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket en HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Lync\\\<SipID\>.

### <a name="visio-feature-updates"></a>Visio: actualizaciones de características
-   **Crear diagramas de los datos de Excel:** Se crea automáticamente un diagrama de flujo básico o un diagrama de flujo de funciones cruzadas a partir de datos de Excel mediante plantillas de visualizador de datos nuevos. [Más información](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)
-   **Vínculos seguros:** Cuando un usuario hace clic en un vínculo, Protección contra amenazas avanzada de Office 365 (ATP) lo inspecciona para comprobar si es malintencionado o no. Si el vínculo se considera malintencionado, se redirige al usuario a una página de advertencia en lugar de redirigirlo a la URL de destino original. [Más información](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)

### <a name="visio-non-security-updates"></a>Visio: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema en el que los complementos COM no recibían eventos abiertos de un documento cuando se abre un archivo de Visio mediante un doble clic en un icono de archivo o nombre de archivo.

### <a name="word-feature-updates"></a>Word: Actualizaciones de características
-   **Insertar imágenes en línea:** nueva página de destino para la selección de imágenes. Además, la información de atribución se inserta automáticamente con la imagen.
-   **Creación de texto alternativo:** Un servicio basado en la nube genera automáticamente texto alternativo (alt text) para las imágenes de un documento.
-   **Actividad de archivo compartido:** Elija el botón Actividad en la esquina superior derecha del archivo para ver cuando un archivo compartido en OneDrive para la Empresa o SharePoint se compartió, se editó, se restauró o se cambió de nombre.
-   **Vínculos seguros:** Cuando un usuario hace clic en un vínculo, Protección contra amenazas avanzada de Office 365 (ATP) lo inspecciona para comprobar si es malintencionado o no. Si el vínculo se considera malintencionado, se redirige al usuario a una página de advertencia en lugar de redirigirlo a la URL de destino original. [Más información](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Cambios en archivos compartidos:** vea quién ha realizado cambios en los documentos compartidos y restaurar versiones anteriores. [Más información](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad
-   [CVE-2017-11826](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11826): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Vulnerabilidad de ejecución remota de código de Microsoft Outlook
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812): Vulnerabilidad de daños en la memoria de Microsoft Word
-   [Advertencia 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020): Actualización de defensa en profundidad de Microsoft Office
-   [Advertencia 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Actualización de defensa en profundidad de Microsoft Office

### <a name="word-non-security-updates"></a>Word: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema que provocaba que Word se bloqueara cuando un usuario intentaba usar Guardar como sobre un documento existente en OneDrive para la Empresa y, seguidamente, cancelaba o intentaba combinar cambios existentes.
-   Se ha corregido un problema que provocaba que Office no pudiera escribir en el disco al guardar un archivo de copia de sincronización, pero Office siguiera cargando el archivo en OneDrive. Con esta corrección, ahora el usuario ve un mensaje de error y la carga no se realiza.
-   Se ha corregido un problema que provocaba que Word dejara de responder cuando el usuario navegaba a la pestaña Insertar poco después de abrir Word.
-   Se soluciona un problema por el que, después de hacer clic en el margen, los caracteres se mostraban en la esquina superior izquierda de la pantalla al escribir caracteres.
-   Se soluciona un problema por el que Word se bloqueaba al mostrar el panel Actividad de un documento abierto desde un servidor de SharePoint anterior a SharePoint Server 2016.
-   Se soluciona un problema por el que Word se cerraba de forma inesperada al cargar el complemento Grammarly.
-   Se ha solucionado un problema en el que, en determinadas condiciones, Word se bloqueaba al intentar recuperar los archivos en la nube.
-   Se ha solucionado un problema que no permitía girar las formas incluidas en los lienzos de dibujo.
-   Se ha corregido un problema que no permitía aplicar la separación correcta entre vocales y consonantes al escribir en coreano.
-   Al guardar un documento como archivo PDF, se guarda como PDF de versión 1.7.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2017-8630](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8630): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2017-8744](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8744): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2017-11825](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11825): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [Aviso 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003): Actualización de defensa en profundidad de Microsoft Office

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad
-   Se agregó compatibilidad con el inicio de sesión único (SSO) para usuarios de dominio de planes de Office 365 Alemania donde la identidad está federada con un entorno local de Active Directory.
-   Se agregó una función para impedir que usuarios menores de edad puedan comprar y activar complementos de Office de la Tienda Office.
-   Se soluciona un problema relacionado con el zoom y el escalado en complementos de Office en el entorno de PPP dinámico.
-   Se ha corregido un problema que provocaba que el nodo CurrentStatus del proveedor del servicio de configuración (CSP) de Office devolviera una cadena vacía incluso si Office 365 ProPlus está instalado.
-   Se ha corregido un problema que provocaba cambios en los formatos de archivo .box. Esto afectaba la funcionalidad de versiones antiguas de Office instaladas en el mismo equipo, porque los archivos .box se comparten con todas las versiones de una aplicación de Office en el mismo equipo.
-   Se soluciona un problema por el que se, al usar la activación en equipos compartidos, en determinadas circunstancias se mostraba un mensaje de error donde se indicaba que un error en la aplicación impedía el correcto funcionamiento y se preguntaba al usuario si quería ejecutar una reparación.
-   Se soluciona un problema por el que no se mostraba al usuario el progreso de una reparación en línea.
-   Se soluciona un problema por el que no se muestran las propiedades de archivo de Office en el Explorador de archivos.
-   Se soluciona un problema por el que los botones de complementos de Office desaparecen de la cinta de opciones cuando hay un segundo documento abierto.
-   Se soluciona un problema por el que no se pueden abrir algunos módulos VBA que tienen nombres con caracteres de doble byte.
-   Se soluciona un problema que impedía que se mostrara el cuadro de diálogo Novedades.
-   Se ha solucionado un problema en el que al hacer clic en la pestaña Dibujo, se bloqueaba la aplicación para algunos usuarios.
-   Se ha solucionado un problema en el que al mantener el puntero sobre un Control común que tiene una información sobre herramientas en él, hace que la aplicación se bloquee.
-   Se ha solucionado un problema en el que un mensaje de error de licencia aparece cuando se usan controles comunes.
-   Se ha solucionado un problema relacionado con la forma en que se firmaban algunos archivos de programa, lo que causaba que los programas antivirus marcaran esos archivos como potencialmente peligrosos, así como otros problemas de protección o acceso a datos en Windows Information Protection (WIP).
-   Se ha agregado compatibilidad para que los usuarios que trabajen en versiones de Office de 64 bits puedan abrir archivos de macro que contienen controles mscomctl.ocx.
-   Se han mejorado los controles de accesibilidad que se usan en mscomctl.ocx.
-   Se ha corregido un problema que provocaba que los comandos no estuvieran disponibles en los cuadros de diálogo de personalización de la cinta o de la barra de herramientas de acceso rápido.



## <a name="version-1705-january-9"></a>Versión 1705: 9 de enero
*Versión 1705 (compilación 8201.2217)*

*Esta es la versión del Canal diferido que ha estado disponible desde septiembre de 2017. Seguirá recibiendo soporte técnico y actualizaciones de seguridad hasta julio de 2018. Pero ahora hay disponible una nueva versión del Canal semianual (versión 1708, compilación 8431.2153), que contiene características nuevas, actualizaciones de seguridad y actualizaciones no relacionadas con la seguridad.*

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [Advertencia 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Actualización de defensa en profundidad de Microsoft Office

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791): Vulnerabilidad de la ejecución remota de código de Microsoft Outlook
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Vulnerabilidad de ejecución remota de código de Microsoft Outlook

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792): Vulnerabilidad de la ejecución remota de código de Microsoft Word
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Vulnerabilidad de ejecución remota de código de Microsoft Outlook
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807): Vulnerabilidad de ejecución remota de código de Microsoft Word
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812): Vulnerabilidad de daños en la memoria de Microsoft Word

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [Advertencia 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003): actualización de defensa en profundidad de Microsoft Office


> [!NOTE]
> Si necesita ayuda con algún problema de uso de Office, le recomendamos que publique la pregunta en el [foro de preguntas de Microsoft](https://answers.microsoft.com/) o [Tech Community](https://techcommunity.microsoft.com/), o bien puede ponerse en contacto con el [servicio de soporte técnico](https://support.microsoft.com/contactus).