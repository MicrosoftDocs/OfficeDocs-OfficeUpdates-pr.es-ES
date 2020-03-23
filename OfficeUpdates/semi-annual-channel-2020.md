---
title: Notas de la versión para las versiones de canal semianual en 2020
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Proporciona a los profesionales de TI las notas de la versión para las versiones del canal semianual de Office 365 ProPlus en 2020.
ms.openlocfilehash: b4a6ef107e4bd4904192d4c6e6d100194b2948b9
ms.sourcegitcommit: e2633701e5a00bd20a5f166e95fcb156461973ae
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 03/21/2020
ms.locfileid: "42890127"
---
# <a name="release-notes-for-semi-annual-channel-releases-in-2020"></a>Notas de la versión para las versiones de canal semianual en 2020

En estas notas de la versión, se proporciona información sobre características nuevas y actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones del canal semianual de Office 365 ProPlus en 2020, Visio Pro para Office 365, el Cliente de escritorio de Project Online y Office 365 Empresa.

> [!NOTE]
>
>- A menudo publicamos características (y a veces incluso correcciones) para el Canal semianual durante un período de tiempo. Si no ve algo que se describe a continuación de inmediato, lo verá pronto. [Más información](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
>- OneNote 2016 no se incluirá de forma predeterminada cuando un usuario en el canal semianual descargue e instale Office 365 en Windows 10 desde el Portal de Office.




## <a name="version-1908-march-10"></a>Versión 1908: 10 de marzo
*Versión 1908 (compilación 11929.20648)*

Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- <div><span>Se ha corregido un problema por el que algunos usuarios pueden haber visto varias ventanas emergentes cuando hubiera vínculos externos presentes en el libro.&nbsp;</span></div>


- <div><span style="display:inline !important;">La funcionalidad de Texto a columna puede fallar en algunas configuraciones regionales.</span><br></div>


- <div style="box-sizing:border-box;"><span style="box-sizing:border-box;">Es posible que los usuarios vean un error si acceden a un rango con nombre oculto.</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div>Se ha corregido un problema con el método Shape.Paste: cuando el usuario copiaba y pegaba la forma con el &nbsp;método Shape.Paste&nbsp;<span style="font-size:13.3333px;display:inline !important;">, se cambiaba la selección a la forma pegada.</span></div>


### <a name="word"></a>Word

- <div>Corregido un problema ocasional en el que al guardar un archivo existente siempre aparece el cuadro de diálogo Guardar como, pero el archivo nunca se guarda.<br></div>


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- <div><span>Este cambio corrige el procesamiento lento de algunos gráficos de dispersión con marcadores.</span></div>

## <a name="version-1902-march-10"></a>Versión 1902: 10 de marzo
*Versión 1902 (compilación 11328.20554)*

Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-february-11"></a>Versión 1908: 11 de febrero
*Versión 1908 (Compilación 11929.20606)*

Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)


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

Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)


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

Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-1908-january-14"></a>Versión 1908: 14 de enero
*Versión 1908 (compilación 11929.20562)*

Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

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

### <a name="outlook"></a>Outlook

- **Hemos actualizado la experiencia de usuario de Outlook para usted:** una experiencia simplificada, anteriormente disponible para su vista previa con Próximamente, diseñada para ayudarle a centrarse en lo más importante. [Más información](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- **Una cinta simplificada que además es personalizable:** disfrute de una sola fila simplificada con los botones más usados. Cambie fácilmente entre la vista clásica y la simplificada, y ancle o desancle comandos. [Más información](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- **Seguir trabajando mientras mueve mensajes:** Outlook ahora mueve los mensajes en segundo plano, por lo que puede seguir trabajando mientras mueve una gran cantidad de mensajes entre carpetas.

- **Creación en el tiempo entre las reuniones consecutivas:** asigne a los asistentes el tiempo para descansar o desplazarse entre las distintas ubicaciones al configurar reuniones para finalizar 5 a 10 minutos antes de forma predeterminada.

- **Seleccione su acción favorita:** ¿no usa Etiquetar ni Eliminar? ¿Qué hay de Archivar o Marcar como leído? Personalice el menú de acciones rápidas con los comandos que use más frecuentemente.

- **Verán los memes que comparta:** cuando un texto o imágenes estáticas no consigan comunicar lo que desea, use un GIF animado para aclararlo. [Más información](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)

- **¿Quiere que su diseño tenga un espaciado menor o mayor? Usted elige:** la opción de un espaciado más ajustado le permite decidir si quiere más espacio entre los elementos o un diseño más ajustado para ver más elementos.

- **Una forma más rápida de agregar cuentas:** gracias a las mejoras de configuración de cuentas, es más fácil que nunca agregar cuentas de Outlook.com y Gmail que usen la autenticación en dos fases a Outlook. [Más información](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- **Despídase de límites de sincronización:** las mejoras de Outlook significan que se ha eliminado el límite de carpetas y sincronizar los buzones compartidos.

### <a name="powerpoint"></a>PowerPoint

- **Mejor transformación:** asigne un nombre a las formas para tener más control sobre cómo se transforman. [Más información](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- **Encuentre ese archivo rápido:** ¿Busca un archivo en el que trabajó recientemente? Basta con que escriba en el cuadro de búsqueda en la página Archivo > Inicio para encontrar el archivo que busca.

- **Aumentar el alcance de su contenido:** ¿necesita que las presentaciones sean accesibles? Deje que el comprobador de accesibilidad le ayude sin estorbar. Pruébelo en Revisar > Comprobar accesibilidad y le informaremos en la barra de estado de cuando necesitemos que compruebe algo.

- **Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar. Cambiar de una a otra nunca había sido tan fácil. [Más información](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Los vídeos en línea tienen un nuevo hogar:** guarde un vídeo en Microsoft Stream para que puedan verlo todas las personas de su organización. Inserte el vínculo del vídeo y disfrute de una presentación multimedia en una fracción del tamaño del archivo. [Más información](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **Guardar los cambios a medida que los realiza:** cargue el archivo en OneDrive para asegurarse de que todas las actualizaciones se guardan automáticamente.

- **Pregunte a su público con un cuestionario o una encuesta:** coloque un cuestionario o una encuesta en una diapositiva. Office recopila y almacena las respuestas para usted. [Más información](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)

- **Nunca fue tan fácil insertar un vídeo en línea:** ¿quiere poner un vídeo de Vimeo o de YouTube en la diapositiva? Solo necesita el vínculo a la página del vídeo. [Más información](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

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

- **El modo herramientas de aprendizaje tiene soporte adicional para más colores de página: **las herramientas de aprendizaje de Word son compatibles con más colores de tema de página, lo que permite cambiar el color de fondo de la página. Muchas personas tienen dificultades para leer con un fondo totalmente blanco o negro, por lo que hemos ampliado la elección de colores en Word para PC y Mac.

- **Edición natural con el Editor para entradas de lápiz:** con un solo trazo, divida o una palabras, agregue una nueva línea o inserte palabras con el lápiz. [Más información](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- **Su documento: de estático a mágico:** transforme el documento en una página web interactiva y fácil de compartir con un aspecto fantástico en cualquier dispositivo. [Más información](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)

- **Aumentar el alcance de su contenido:** ¿necesita hacer que sus documentos sean accesibles? Deje que el comprobador de accesibilidad le ayude sin estorbar. Pruébelo en Revisar > Comprobar accesibilidad y le informaremos en la barra de estado de cuando necesitemos que compruebe algo.

- **Encuentre ese archivo rápido:** ¿Busca un archivo en el que trabajó recientemente? Basta con que escriba en el cuadro de búsqueda en la página Archivo > Inicio para encontrar el archivo que busca.

- **Cambiar sin problemas:** el nuevo administrador de cuentas muestra todas sus cuentas personales y profesionales de Office 365 en un solo lugar. Cambiar de una a otra nunca había sido tan fácil. [Más información](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Despídase de las distracciones:** llega a Windows una de las característica favoritas de Mac. Cambie al modo Focalizado en el menú Vista para eliminar las distracciones y concentrarse en su trabajo. [Más información](https://support.office.com/article/51af2fb2-194f-424b-ab7e-b65de9ec9292)

- **Mejorar la comprensión con el foco de línea:** desplácese por un documento línea por línea sin distracciones. Ajuste el foco para ver una, tres o cinco líneas a la vista. [Más información](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)

- **Guarde sus cambios a medida que se produzcan:** Suba su archivo a OneDrive para asegurarse de que todas sus actualizaciones se guarden automáticamente.

- **Consiga su atención con\@menciones:** use @menciones en los comentarios para avisar a los compañeros de trabajo cuando necesite su participación. [Más información](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- **Encuentra ese archivo rápido:** ¿Busca un archivo en el que haya trabajado recientemente? Sólo tiene que escribir en el cuadro de búsqueda de la pestaña Archivo > Abrir para encontrar el archivo que está buscando.

- **Guardar los cambios a medida que los realiza:** cargue el archivo en OneDrive para asegurarse de que todas las actualizaciones se guardan automáticamente.

- **Controles de privacidad:** nuevos controles para datos de diagnóstico y experiencias conectadas, actualizados y mejorados. [Más información](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- **Los iconos de Office tienen un nuevo aspecto:** los iconos de Office se han rediseñado para reflejar las sencillas, inteligentes y eficaces experiencias de Office.

- **Instalación de Microsoft Teams:** Microsoft Teams se instala de forma predeterminada en las instalaciones existentes de Office 365 ProPlus. [Más información](https://docs.microsoft.com/DeployOffice/teams-install)

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

Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)


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

Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

> [!NOTE]
> Si necesita ayuda con algún problema de uso de Office, le recomendamos que publique la pregunta en el [foro de preguntas de Microsoft](https://answers.microsoft.com/) o [Tech Community](https://techcommunity.microsoft.com/), o bien puede ponerse en contacto con el [servicio de soporte técnico](https://support.microsoft.com/contactus).
