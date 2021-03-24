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
ms.openlocfilehash: 2b9b90ef7e1d9bc792be381ba35a94f883156e90
ms.sourcegitcommit: 04f3aa30703f4f1cf89721853a7c052fcca2b97f
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2021
ms.locfileid: "51169618"
---
# <a name="archived-release-notes-for-semi-annual-enterprise-channel-preview"></a>Notas de la versión archivadas para el canal semestral para empresas (versión preliminar)

En estas notas de la versión, se proporciona información sobre características nuevas y actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones del canal semestral para empresas (versión preliminar) de Office 365, Visio Pro para Office 365, el cliente de escritorio de Project Online y Office 365 Empresa.

> [!NOTE]
> - A menudo publicamos características (y, a veces, incluso correcciones) para el canal semestral para empresas (versión preliminar) durante un período de tiempo. Si no ve algo que se describe a continuación de inmediato, lo verá pronto. [Más información](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
> - Microsoft Teams está incluido en las nuevas instalaciones del canal semestral para empresas (versión preliminar), empezando por la versión 1902. Se agregará Teams a las instalaciones existentes del canal semestral para empresas (versión preliminar) cuando se actualicen a la versión 1908 o posterior. Para obtener más información, vea [Implementar Microsoft Teams con Office 365 ProPlus](/deployoffice/teams-install).

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

- Se resolvió un problema que impedía a los usuarios guardar documentos de Word, Excel y PowerPoint 2019 en las compilaciones posteriores a la versión 16.0.11929.20396.  Este problema afecta a los usuarios que crean un nuevo archivo y muestra el diálogo "Guardar como" después de hacer clic en el icono Guardar o presionar Ctrl + S.

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
### <a name="access"></a>Access

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
 - Un problema que provocaba que los archivos que contenían tablas dinámicas vinculadas a otros libros se cargaran despacio. Este problema se ha resuelto.
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
- **Instalación de Microsoft Teams:** Microsoft Teams se instala de forma predeterminada en las instalaciones existentes de Office 365 ProPlus. [Más información](/DeployOffice/teams-install)

### <a name="skype-for-business-feature-updates"></a>Skype Empresarial: actualizaciones de características

- **Compatibilidad mejorada con pantallas de alta definición**: si usa varios monitores o una base de conexión para portátil, las aplicaciones de Office ofrecen ahora una imagen nítida en todas las pantallas, incluso si tienen configuraciones de escala diferentes. [Más información](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="teams-feature-updates"></a>Teams: actualizaciones de características

- **Compatibilidad mejorada con pantallas de alta definición**: si usa varios monitores o una base de conexión para portátil, las aplicaciones de Office ofrecen ahora una imagen nítida en todas las pantallas, incluso si tienen configuraciones de escala diferentes. [Más información](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

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

-   [CVE-2018-8597](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8597): Vulnerabilidad de la ejecución remota de código de Microsoft Excel 
-   [CVE-2018-8598](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8598): Vulnerabilidad de divulgación de información de Microsoft Excel 
-   [CVE-2018-8627](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8627): vulnerabilidad de divulgación de información de Microsoft Excel 
-   [CVE-2018-8636](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8636): Vulnerabilidad de la ejecución remota de código de Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad 

-   [CVE-2018-8587](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8587): Vulnerabilidad de la ejecución remota de código de Microsoft Outlook 

### <a name="powerpoint-security-updates"></a>PowerPoint: Actualizaciones de seguridad 

-   [CVE-2018-8628](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8628): Vulnerabilidad de la ejecución remota de código de Microsoft PowerPoint 

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
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): vulnerabilidad de uso posterior gratis de la ejecución de código remoto de Microsoft Access

### <a name="excel-feature-updates"></a>Excel: Actualizaciones de características
 - **Edición colaborativa:** Trabajar con otras personas al mismo tiempo en el libro. [Más información](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)
 - **El autoguardado para archivos de nube ahora está habilitado de forma predeterminada:** el autoguardado está habilitado de forma predeterminada en la versión del canal semianual (dirigido) de septiembre de 2018. Este cambio significa que los usuarios no tendrán que preocuparse por perder los cambios en los documentos almacenados en OneDrive o SharePoint Online. Los cambios se guardarán en la nube automáticamente y los usuarios no tendrán que presionar explícitamente Ctrl + S o el botón Guardar. Sin embargo, tendrán que comprender este cambio de comportamiento para que no realicen cambios accidentales en documentos. Tenga en cuenta que los usuarios pueden desactivar el autoguardado con el botón de autoguardado en la parte superior de la pantalla. Le recomendamos que notifique a los usuarios sobre este nuevo cambio y les instruya acerca de cómo aprovechar mejor esta nueva característica de Office 365. [Más información sobre el autoguardado](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Más información sobre lo que los administradores de TI deben saber sobre el autoguardado](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Edición de la barra de fórmulas y las celdas mejorada:** ahora, puede usar CTRL + A para seleccionar el texto de una celda o de la barra de fórmulas. También se ha mejorado la compatibilidad con los emojis y otros caracteres complejos. [Más información](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
- **Mejoras del Comprobador de accesibilidad:** el Comprobador de accesibilidad ha actualizado la asistencia técnica para las normas internacionales y recomendaciones para que los libros sean más accesibles. [Más información](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **Evitar cambios no deseados:** establezca los libros para abrir como solo lectura para evitar cambios accidentales. Vaya a archivo > información > proteger libro > abrir siempre como solo lectura

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2018-8331](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8331): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8429](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8429): vulnerabilidad de divulgación de información de Microsoft Excel
-   [CVE-2018-8375](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8375): vulnerabilidad de la ejecución remota de código de Microsoft Excel 
-   [CVE-2018-8379](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8379): Vulnerabilidad de la ejecución remota de código de Microsoft Excel 
-   [CVE-2018-8382](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8382): vulnerabilidad de divulgación de información de Microsoft Excel
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246): vulnerabilidad de divulgación de información de Microsoft Excel
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248): vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147): vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163): vulnerabilidad de divulgación de información de Microsoft Excel
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029): vulnerabilidad de la ejecución remota de código de Microsoft Excel

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
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310): vulnerabilidad de manipulación de Microsoft Office
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244): vulnerabilidad de elevación de privilegios de Microsoft Outlook
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150): vulnerabilidad de omisión de característica de seguridad de Microsoft Outlook
-   [ADV180021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180021): actualización de defensa en profundidad de Microsoft Office

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
-   [CVE-2018-8430](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8430): vulnerabilidad de la ejecución remota de código de PDF de Word
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919): vulnerabilidad de divulgación de información de Microsoft Office

### <a name="word-non-security-updates"></a>Word: actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema que provocaba que apareciera un mensaje de memoria insuficiente.
-   Se ha corregido un conjunto de errores que evitaban que algunos usuarios pudiesen abrir documentos y correos electrónicos protegidos mediante IRM compartidos con ellos por gente de otras organizaciones.
-   Se han corregido algunos problemas de rendimiento.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de seguridad
-   [CVE-2018-8332](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8332): vulnerabilidad de la ejecución remota de código de gráficos de Win32k
-   [CVE-2018-8378](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8378): vulnerabilidad de divulgación de información de Microsoft Office
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281): vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157): vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158): vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950): vulnerabilidad de divulgación de información de Microsoft Office
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030): vulnerabilidad de la ejecución remota de código de Microsoft Office
-   
  **Bloqueo de la activación de controles de Flash, Silverlight y Shockwave en Office por motivos de seguridad:** por motivos de seguridad, las nuevas compilaciones de Microsoft Office para Office 365 en Windows bloquean la activación de controles de Silverlight, Flash y Shockwave. Más información[aquí](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729) y [aquí](https://support.office.com/en-us/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1?ui=en-US&rs=en-US&ad=US)

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones no relacionadas con la seguridad
-  Se ha corregido un problema que causaba que la instalación de la actualización tardase mucho tiempo en determinados escenarios.
-  Se ha corregido un problema que provocaba que, al abrir una aplicación, el usuario viera un mensaje sobre iniciar en modo seguro y después la aplicación no se abriera.
-  Se han corregido algunos problemas de rendimiento.

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

## <a name="version-1803-july-10"></a>Versión 1803: 10 de julio
*Version 1803 (compilación 9126.2259)*

### <a name="access-security-updates"></a>Access: Actualizaciones de seguridad
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): vulnerabilidad de uso posterior gratis de la ejecución de código remoto de Microsoft Access

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310): vulnerabilidad de manipulación de Microsoft Office

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281): vulnerabilidad de la ejecución remota de código de Microsoft Office

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
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246): Vulnerabilidad de divulgación de información de Microsoft Excel
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248): Vulnerabilidad de la ejecución remota de código de Microsoft Excel

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
-   Se corrige un problema que en ocasiones podía desencadenar un bloqueo en una operación de agrupación (o desagrupación) en una tabla dinámica de Excel.

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244): Vulnerabilidad de elevación de privilegios de Microsoft Outlook

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
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163): Vulnerabilidad de divulgación de información de Microsoft Excel

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema por el que Excel se bloqueaba al abrir un archivo de SharePoint Online.
-   Se soluciona un problema por el que Imprimir o la Vista previa de impresión solo imprime o muestra una parte de la hoja de cálculo, con el contenido truncado a una segmentación en la hoja de cálculo.

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150): Vulnerabilidad de omisión de característica de seguridad de Microsoft Outlook

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
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158): Vulnerabilidad de la ejecución remota de código de Microsoft Office



## <a name="version-1803-april-10"></a>Versión 1803: 10 de abril
*Versión 1803 (compilación 9126.2152)*

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029): Vulnerabilidad de la ejecución remota de código de Microsoft Excel

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema que provocaba que, cuando había varios usuarios trabajando en coautoría en la misma presentación, se duplicaran de forma incorrecta los patrones de diapositivas.
-   Se soluciona un problema que provocaba que, al abrir un archivo guardado en OneDrive, se bloqueara PowerPoint al salir de la Vista protegida.

### <a name="skype-for-business-non-security-updates"></a>Skype Empresarial: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema relacionado con la compatibilidad del protocolo TLS 1.2.

### <a name="word-non-security-updates"></a>Word: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema que provocaba que apareciera un mensaje de memoria insuficiente.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950): Vulnerabilidad de divulgación de información de Microsoft Office
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026): Vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030): Vulnerabilidad de la ejecución remota de código de Microsoft Office



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
-   [CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903): Vulnerabilidad de la ejecución remota de código de Microsoft Access

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
-   [Advertencia 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Actualización de defensa en profundidad de Microsoft Office

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
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939): Vulnerabilidad de divulgación de información de Microsoft Office
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791): Vulnerabilidad de ejecución remota de código de Microsoft Outlook
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): vulnerabilidad de ejecución remota de código de Microsoft Outlook
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850): Vulnerabilidad de elevación de privilegios de Microsoft Outlook
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852): vulnerabilidad de los daños en la memoria de Microsoft Outlook

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
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934): Vulnerabilidad de divulgación de información de Microsoft PowerPoint

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
-   Se ha corregido un problema que provocaba que Word se bloqueara cuando un usuario intentaba usar Guardar como sobre un documento existente en OneDrive para la Empresa y, seguidamente, cancelaba o intentaba combinar cambios existentes.
-   Se ha corregido un problema que, al filtrar campos de orígenes de datos que contuvieran valores nulos (vacíos), provocaba errores al ejecutar el Asistente para combinar correspondencia.
-   Se ha solucionado un problema que provocaba que Office no pudiera escribir en el disco al guardar un archivo de copia de sincronización, pero Office siguiera cargando el archivo en OneDrive. Con esta corrección, ahora el usuario ve un mensaje de error y la carga no se realiza.
-   Se ha solucionado un problema que, al quitar la protección IRM de un documento, provocaba que dicha protección no se eliminara.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795): vulnerabilidad de la ejecución remota de código de Microsoft Office
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853): vulnerabilidad de divulgación de información de Microsoft Office
-   [Aviso 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003): Actualización de defensa en profundidad de Microsoft Office

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
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841): Vulnerabilidad de la ejecución remota de código de Microsoft Excel

### <a name="outlook-security-updates"></a>Outlook: Actualizaciones de seguridad
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850): Vulnerabilidad de elevación de privilegios de Microsoft Outlook
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852): Vulnerabilidad de los daños en la memoria de Microsoft Outlook

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851): Vulnerabilidad de los daños en la memoria de Microsoft Office
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853): Vulnerabilidad de divulgación de información de Microsoft Office



## <a name="version-1708-january-9"></a>Versión 1708: 9 de enero
*Versión 1708 (compilación 8431.2153)*

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796): Vulnerabilidad de la ejecución remota de código de Microsoft Excel
-   [Advertencia 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Actualización de defensa en profundidad de Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
-   Se ha corregido un problema por el que Excel se bloqueaba al crear mediante programación una tabla dinámica y, después, realizar una actualización mediante programación.

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
-   [Aviso 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003): Actualización de defensa en profundidad de Microsoft Office

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad
-   Se agregó compatibilidad con el inicio de sesión único (SSO) para usuarios de dominio de planes de Office 365 Alemania donde la identidad está federada con un entorno local de Active Directory.
-   Se agregó una función para impedir que usuarios menores de edad puedan comprar y activar complementos de Office de la Tienda Office.


> [!NOTE]
> Si necesita ayuda con algún problema de uso de Office, le recomendamos que publique la pregunta en el [foro de preguntas de Microsoft](https://answers.microsoft.com/) o [Tech Community](https://techcommunity.microsoft.com/), o bien puede ponerse en contacto con el [servicio de soporte técnico](https://support.microsoft.com/contactus).