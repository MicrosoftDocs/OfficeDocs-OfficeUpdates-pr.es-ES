---
title: Notas de la versión para las versiones de Canal semianual en 2019
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 1/8/2019
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Proporciona a los profesionales de TI las notas de la versión para las versiones de Canal semianual de Office 365 ProPlus en 2019.
ms.openlocfilehash: da269198a90b18ef62ae293273028d7206efd330
ms.sourcegitcommit: 3a7ca9d5320f8d2b01d8ba7f0ee3b09dc41d2a7e
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 01/08/2019
ms.locfileid: "27773208"
---
# <a name="release-notes-for-semi-annual-channel-releases-in-2019"></a>Notas de la versión para las versiones de Canal semianual en 2019

En estas notas de la versión, se proporciona información sobre características nuevas, actualizaciones de seguridad y actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones de Canal semianual para Office 365 ProPlus en 2019. 

> [!NOTE]
> - Lo siguiente también proporciona información sobre características nuevas, actualizaciones de seguridad y no relacionadas con la seguridad para Visio Pro para Office 365 y el cliente de escritorio de Project Online.
> - Esta información también se aplica a Office 365 Empresa, que es la versión de Office que viene con algunos planes de Office 365, como Empresa Premium.
> - El Canal semianual se denominaba Canal diferido antes de enero de 2019.

> [!NOTE]
> - La información sobre las actualizaciones de seguridad de cada canal de actualización de Office 365 ProPlus se empezará a mostrar por separado en [Actualizaciones de seguridad](office365-proplus-security-updates.md).

## <a name="version-1808-january-8"></a>Versión 1808: 8 de enero
*Versión 1808 (compilación 10730.20264)*

### <a name="excel-feature-updates"></a>Excel: Actualizaciones de características
 - **Edición colaborativa:** Trabajar con otras personas al mismo tiempo en el libro. [Más información](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)
 - **El autoguardado para archivos de nube ahora está habilitado de forma predeterminada:** el autoguardado está habilitado de forma predeterminada en la versión del canal semianual (dirigido) de septiembre de 2018. Este cambio significa que los usuarios no tendrán que preocuparse por perder los cambios en los documentos almacenados en OneDrive o SharePoint Online. Los cambios se guardarán en la nube automáticamente y los usuarios no tendrán que presionar explícitamente Ctrl + S o el botón Guardar. Sin embargo, tendrán que comprender este cambio de comportamiento para que no realicen cambios accidentales en documentos. Tenga en cuenta que los usuarios pueden desactivar el autoguardado con el botón de autoguardado en la parte superior de la pantalla. Le recomendamos que notifique a los usuarios sobre este nuevo cambio y les instruya acerca de cómo aprovechar mejor esta nueva característica de Office 365. [Más información sobre el autoguardado](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Más información sobre lo que los administradores de TI deben saber sobre el autoguardado](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
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
- **Marcar los elementos eliminados como leído:** ahora puede establecer como leídos los mensajes que elimine. Para hacerlo, vaya a Archivo \> Opciones \> Correo \> Otros.
- **Ver tres zonas horarias:** ¿necesita programar una reunión en distintas zonas horarias? Agregue varias zonas horarias al calendario para ver la disponibilidad de todos los usuarios fácilmente y seleccione una hora adecuada para todos. [Más información](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)
- **Mejora de la experiencia del usuario para crear un grupo:** hemos perfeccionado la experiencia del usuario para crear grupos para darle un aspecto más moderno y ordenado.[ Más información](https://support.office.com/article/04d0c9cf-6864-423c-a380-4fa858f27102)

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
- **El autoguardado para archivos de nube ahora está habilitado de forma predeterminada:** el autoguardado está habilitado de forma predeterminada en la versión del canal semianual (dirigido) de septiembre de 2018. Este cambio significa que los usuarios no tendrán que preocuparse por perder los cambios en los documentos almacenados en OneDrive o SharePoint Online. Los cambios se guardarán en la nube automáticamente y los usuarios no tendrán que presionar explícitamente Ctrl + S o el botón Guardar. Sin embargo, tendrán que comprender este cambio de comportamiento para que no realicen cambios accidentales en presentaciones. Tenga en cuenta que los usuarios pueden desactivar el autoguardado con el botón de autoguardado en la parte superior de la pantalla. Le recomendamos que notifique a los usuarios sobre este nuevo cambio y les instruya acerca de cómo aprovechar mejor esta nueva característica de Office 365. [Más información sobre el autoguardado](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Más información sobre lo que los administradores de TI deben saber sobre el autoguardado](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Edición de la barra de fórmulas y las celdas mejorada:** ahora, puede usar CTRL + A para seleccionar el texto de una celda o de la barra de fórmulas. También se ha mejorado la compatibilidad con los emojis y otros caracteres complejos. [Más información](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
- **Convertir la entrada de lápiz:** dibuje y tome notas con garabatos y conviértalos en texto leíble y formas nítidas para crear una presentación elegante. [Más información](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)
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
- **El autoguardado para archivos de nube ahora está habilitado de forma predeterminada:** el autoguardado está habilitado de forma predeterminada en la versión del canal semianual (dirigido) de septiembre de 2018. Este cambio significa que los usuarios no tendrán que preocuparse por perder los cambios en los documentos almacenados en OneDrive o SharePoint Online. Los cambios se guardarán en la nube automáticamente y los usuarios no tendrán que presionar explícitamente Ctrl + S o el botón Guardar. Sin embargo, tendrán que comprender este cambio de comportamiento para que no realicen cambios accidentales en presentaciones. Tenga en cuenta que los usuarios pueden desactivar el autoguardado con el botón de autoguardado en la parte superior de la pantalla. Le recomendamos que notifique a los usuarios sobre este nuevo cambio y les instruya acerca de cómo aprovechar mejor esta nueva característica de Office 365. [Más información sobre el autoguardado](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Más información sobre lo que los administradores de TI deben saber sobre el autoguardado]
- **Mejoras del Comprobador de accesibilidad:** el Comprobador de accesibilidad ha actualizado la asistencia técnica para las normas internacionales y recomendaciones para que los documentos sean más accesibles. [Más información](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **Compatibilidad con el formato SVG mejorada:** puede insertar imágenes SVG que tengan filtros aplicados. [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="word-non-security-updates"></a>Word: actualizaciones no relacionadas con la seguridad
- Se ha corregido un problema por el que aparecía un mensaje de memoria insuficiente.
- Se ha corregido un conjunto de errores que evitaban que algunos usuarios pudiesen abrir documentos y correos electrónicos protegidos mediante IRM compartidos con ellos por gente de otras organizaciones.
- Se han corregido algunos problemas de rendimiento.

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

 
### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones no relacionadas con la seguridad
- Se ha corregido un problema por el que la instalación de la actualización tardaba mucho tiempo en determinados escenarios.
- Se ha corregido un problema que provocaba que, al abrir una aplicación, el usuario viera un mensaje sobre iniciar en modo seguro y después la aplicación no se abriera.
- Se han corregido algunos problemas de rendimiento.


## <a name="version-1803-january-8"></a>Versión 1803: 8 de enero
*Versión 1803 (compilación 9126.2351)*

*Esta es la versión del Canal semianual que ha estado disponible desde enero de 2018. Seguirá recibiendo soporte técnico y actualizaciones de seguridad hasta marzo de 2019. Pero ahora está disponible una nueva versión del Canal semianual (versión 1803), que contiene nuevas características, actualizaciones de seguridad y actualizaciones no relacionadas con la seguridad.*



> [!NOTE]
> Si necesita ayuda con algún problema de uso de Office, le recomendamos que publique la pregunta en el [foro de preguntas de Microsoft](https://answers.microsoft.com/) o [Tech Community](https://techcommunity.microsoft.com/), o bien puede ponerse en contacto con el [servicio de soporte técnico](https://support.microsoft.com/contactus).