---
title: Notas de la versión para las versiones actuales de canal en 2020
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Proporciona a los profesionales de TI las notas de la versión para las versiones de canal mensual de Aplicaciones de Microsoft 365 en 2020
ms.openlocfilehash: 6ff977d90ed98988af281f026276cbc3f0d21807
ms.sourcegitcommit: a0285b69d4d48b5ef4ac3c54678fb67ce399b73e
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/25/2020
ms.locfileid: "44874786"
---
# <a name="release-notes-for-current-channel-releases-in-2020"></a>Notas de la versión para las versiones actuales de canal en 2020

Estas notas de la versión proporcionan información sobre las nuevas características y las actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones del canal actual en 2020 para Microsoft 365 apps for Enterprise, Microsoft 365 apps for Business y las versiones de suscripción de las aplicaciones de escritorio para Project y Visio.

> [!IMPORTANT]
> Estamos realizando algunos cambios en los canales de actualización de las Aplicaciones de Microsoft 365, incluida la adición de un nuevo canal de actualización (canal empresarial mensual) y el cambio de los nombres de los canales de actualización existentes. [Lea este artículo](https://go.microsoft.com/fwlink/p/?linkid=2127441) para más información.

 > [!NOTE]
>
>- A menudo se implementan características (y, a veces, incluso soluciones) en el momento actual en un período de tiempo.  Si no ve algo que se describe a continuación de inmediato, lo verá pronto. [Más información](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)




[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2005-june-24"></a>Versión 2005:24 de junio
*Versión 2005 (compilación 12827,20470)*

[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Este error ahora se ha corregido; debe poder llamar al tipo de datos extendidos de fecha y hora en el código sin que se produzca ningún bloqueo en la aplicación. Por lo que el equipo sabrá si se encuentra con otros problemas.


- Este problema se ha corregido ahora; Ahora puede volver a la versión de Access más actualizada y usar DAO/VBA para administrar y editar un tipo de datos decimal. Deje que el equipo de acceso sepa si encuentra algún problema con el uso de nuestro tipo de datos.


### <a name="excel"></a>Excel

- Se ha corregido un problema que provocaba que se quitara el XML de CustomUI para una pestaña de cinta personalizada al guardar en SharePoint/OneDrive.





### <a name="outlook"></a>Outlook

- Se ha solucionado un problema en el que Outlook no pudo habilitar sugerencias de directivas de protección contra la pérdida de datos para los usuarios que han pagado por el servicio que se encuentran en M365 Business Plus Plans.


- Se ha solucionado un problema que provocaba que los usuarios vean la fecha de creación de los datos adjuntos que copiaron en su sistema de archivos a través de arrastrar y colocar, establecido en el 1 de enero de 4501.


- Se ha solucionado un problema que provocaba que los usuarios vean el &quot; mensaje reglas en este equipo no coinciden con las reglas de Microsoft Exchange &quot; al actualizar sus reglas en Outlook.


- Se ha solucionado un problema que provocaba que los usuarios de las mejoras del calendario compartido mostraran errores de calendario.


- Se ha solucionado un problema que provocaba que los usuarios experimentaran bloqueos y bloqueos intermitentes en algunos escenarios.


- Se ha solucionado un problema que provocaba que los usuarios vean Outlook continuamente para que ejecutaran la herramienta de reparación de la bandeja de entrada.


- Se ha solucionado un problema que provocaba la búsqueda de una característica en sugerir una característica para devolver no resultados y dejar al usuario sin opción para enviar una nueva idea de la característica.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema de bloqueo con el panel de sugerencias.


### <a name="project"></a>Project

- Corregido un problema por el que una tarea marcada como 100% completada está cambiando erróneamente para ser inferior al 100% completado.

### <a name="word"></a>Word

- Se ha resuelto un problema que podría haber causado un bloqueo al arrastrar algún contenido de la aplicación.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Este cambio soluciona posibles bloqueos al cargar y reproducir contenido animado, como GIFs o modelos 3D.




[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-2005-june-09"></a>Versión 2005:9 de junio
*Versión 2005 (compilación 12827,20336)*

Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Soluciona un problema por el que Excel se bloquea al intentar insertar tablas dinámicas en una hoja de gráfico.

### <a name="powerpoint"></a>PowerPoint

- Esto soluciona un bloqueo cuando los usuarios tienen comentarios modernos y heredados en un archivo, lo que desencadena una actualización en los comentarios.

### <a name="project"></a>Project

- Se ha corregido un problema por el que el evento ProjectBeforeTaskChange no se desencadena cuando hay un cambio en la tarea de resumen del proyecto, ya sea el campo de inicio o de tarea del proyecto.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha resuelto el problema de tasa de error de ValidateInstall estableciendo la validación de la instalación del complemento de Bing en true de forma predeterminada y considerando que MSI Return Success como una instalación correcta.



[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-2005-june-02"></a>Versión 2005: junio 02
*Versión 2005 (compilación 12827,20268)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Usar automáticamente los nuevos tipos de datos:** Cuando se escribe un valor de datos que se asemeja a una cotización o una ubicación geográfica, Excel ofrece la conversión a los tipos de datos conectados a la derecha o a la geografía. [Más información](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- **Informe a los casos de los archivos GIF animados:** Ahora, los archivos GIF animados se admiten en el editor de Office (los documentos acaban de snazzier

### <a name="outlook"></a>Outlook

- **Protección de datos del grupo:** la etiqueta de confidencialidad que elija al crear un grupo se aplica al correo electrónico, a los documentos y a los sitios del grupo

- **Mejores resultados, en un instante:** actualizamos la experiencia de búsqueda para que sea más inteligente, rápida y fiable que nunca. [Más información](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **Informe a los casos de los archivos GIF animados:** Ahora, los archivos GIF animados se admiten en el editor de Office (los documentos acaban de snazzier

- **El calendario obtiene un Makeover:** Consulta las actualizaciones visuales que facilitan el examen del calendario. [Más información](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)

### <a name="powerpoint"></a>PowerPoint

- **Informe a los casos de los archivos GIF animados:** Los archivos GIF animados ahora son compatibles con Office editor: los documentos que se acaban de snazzier más [información](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

- **Sincronice los cambios mientras realiza la presentación:** sincronice los cambios cuando se hagan aunque la presentación esté en el modo de presentación con diapositivas. [Más información](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br />Ver detalles en [entrada de blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)

- **No es necesario hacer clic: sus miniauriculares tienen que cubrir lo siguiente:** Usar sus Surface Earbuds para controlar sus presentaciones de PowerPoint. Funcionamiento: una vez emparejada, tendrá que habilitar la característica en PowerPoint. Para iniciar una presentación, presione F5 o seleccione la opción presentación con diapositivas > desde el principio.  En la presentación con diapositivas, haga clic con el botón secundario en la diapositiva y, en configuración de Earbuds de Surface, elija usar gestos para controlar la presentación.  Esta configuración se recordará para todas las presentaciones futuras. Ahora puede deslizar el dedo hacia delante y hacia atrás en el earbud izquierdo para navegar por las presentaciones en el modo de presentación con diapositivas.  Pulse dos veces para reproducir o pausar vídeos insertados.  Importante: Debe emparejar sus Surface Earbuds en la aplicación Surface Audio para Windows 10 para poder usar gestos para controlar las presentaciones. Aquí encontrará instrucciones para empezar a usar la aplicación Surface Audio en Windows 10. [Más información](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="teams"></a>Teams

- **Cambios en el diseño de vídeo en las reuniones de Microsoft Teams:** En breve, el número de participantes que se pueden visualizar simultáneamente durante una reunión de Teams aumentará de 4 a 9.

- **Incluir audio del sistema en eventos en directo:** Los moderadores y los fabricantes en eventos en directo ahora pueden incluir audio del sistema al compartir una pantalla de escritorio o de ventana durante el evento en directo. Esto permitirá a los usuarios escuchar cualquier parte de audio del contenido que esté compartiendo.

- **Habilitar organizadores para cambiar la configuración de la sala de espera para los participantes de acceso telefónico local:** Esta configuración controla si las personas que llaman por teléfono se unen directamente a la reunión o esperan en la sala independientemente de la configuración admitir automáticamente a los usuarios.

- **Levanta la mano en reuniones:** Ahora los usuarios pueden generar una mano virtual en una reunión. Otros participantes verán la mano levantada junto a su nombre en la fase de reunión y junto a su nombre en la lista.

- **Personalizar los fondos de vídeo para reuniones:** Al reunirse con vídeo, ahora tiene la opción de usar diferentes imágenes de fondo estáticas. Esto le permitirá mostrar esta imagen y no el fondo real de donde está sentado.

- **Agregue más personas para chatear:** Ahora hemos hecho posible agregar hasta 350 personas a un único hilo de chat.

- **Engranaje de configuración de la fuente de actividades:** Los usuarios ahora pueden acceder directamente a la fuente de actividades y la configuración de notificaciones desde el raíl izquierdo de la fuente por el medio de un engranaje de configuración.

- **Acceder fácilmente a las opciones de reunión desde dentro de una reunión de Teams en curso:** Estamos haciendo más fácil para los organizadores de la reunión cambiar de forma rápida y sencilla la configuración del moderador y la sala de espera una vez que se inicia una reunión de Teams, proporcionando un vínculo de fácil acceso directamente en el panel de participantes. Esta nueva funcionalidad estará presente tanto para las reuniones programadas como para "reunirse ahora".

- **Análisis de equipos y canales:** Además de los análisis de equipo, ahora también puede ver métricas y perspectivas de niveles de canal. También hemos mejorado el período de tiempo a 90 días para que pueda analizar los datos durante períodos más prolongados. Aparte de esto, esta versión también incluye nuevas métricas y gráficos en torno al número de publicaciones, respuestas y reuniones para un equipo o canal.

- **Anuncios de entrada y salida:** Agregamos esta característica que permite que los organizadores de la reunión puedan activar o desactivar los anuncios de entrada y salida para una reunión.

### <a name="word"></a>Word

- **Descodificar acrónimos sin salir de Word:** Cuando se encuentra un acrónimo, Word intentará definirlo en función de cómo lo usen otros usuarios.

- **Informe a los casos de los archivos GIF animados:** Ahora, los archivos GIF animados se admiten en el editor de Office (los documentos acaban de snazzier


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a>Problemas corregidos

### <a name="excel"></a>Excel

- Se ha corregido un problema por el que Excel podía no responder después de presionar Ctrl + Mayús + teclas de dirección para desplazarse cuando la ventana de Excel se compartía a través de Teams.

- En algunos casos, al hacer clic en un hipervínculo en un lugar dentro del mismo libro hará que se oculte el libro.

### <a name="outlook"></a>Outlook

- Se ha solucionado un problema con el evento de auditoría CLP para la etiqueta de respuesta/reenvío.

- Se ha solucionado un problema que provocaba que los usuarios de versiones de Windows 10 Server mostraran la advertencia "estado de antivirus: no válido". Esta versión de Windows es compatible con la detección antivirus, pero no se ha encontrado ningún antivirus a pesar de haber instalado correctamente anti-virus.

- Se ha solucionado un problema que provocaba que los usuarios experimentaran un bloqueo al enviar comentarios desde una notificación de administrador.

### <a name="skype"></a>Skype

- Cuando a un usuario se le concede una directiva que los mueve a Microsoft Teams, aún puede usar el complemento de Outlook para Skype empresarial para programar reuniones. Después de esta actualización, ya no podrá programar reuniones de Skype empresarial después de que el cliente Lea la Directiva, lo que indica que el usuario es solo Microsoft Teams y solo entra en el modo de unirse a la reunión. Además, el complemento de Outlook para Skype empresarial no se activará durante el inicio si ve que el cliente de Skype empresarial está en modo de solo unirse a la reunión.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.

- Esta actualización corrige un problema en Microsoft Office en el que los proyectos de Visual Basic para aplicaciones con referencias que se espera encontrar buscando las ubicaciones especificadas en la variable de entorno PATH podían no encontrarse correctamente en tiempo de ejecución, lo que provoca errores en tiempo de ejecución de VBA.

- El host de Office se bloqueaba en Windows, cuando se activa un complemento mientras la clave del registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth se establece en cero. Este cambio solucionará este problema.



[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-2004-may-21"></a>Versión 2004:21 de mayo
*Versión 2004 (compilación 12730,20352)*

[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema por el que el vínculo externo dejaba de funcionar después de volver a abrir el archivo si la ruta de acceso del archivo es demasiado larga.


### <a name="outlook"></a>Outlook

- Se ha solucionado un problema que provocaba que los usuarios experimentaran un bloqueo al enviar comentarios desde una notificación de administrador.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema de hacer clic y ejecutar que generaba errores de actualización ocasionales a las últimas compilaciones.

- Se ha corregido un problema en Microsoft Office en el que los proyectos de Visual Basic para aplicaciones con referencias que se espera encontrar buscando las ubicaciones especificadas en la variable de entorno PATH no se pueden encontrar correctamente en tiempo de ejecución, lo que provoca errores en tiempo de ejecución de VBA.



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2004-may-12"></a>Versión 2004: 12 de mayo
*Versión 2004 (compilación 12730.20270)*

Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Corrige un problema que causaba que los usuarios experimentaran un bloqueo al mostrar las notificaciones del sistema.



[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-2004-may-04"></a>Versión 2004: 4 de mayo
*Versión 2004 (Compilación 12730.20250)*

[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Esta actualización corrige un problema en Visual Basic para aplicaciones en Microsoft Office en el que ciertos proyectos VBA que contienen referencias a bibliotecas de código con caracteres DBCS en el nombre de la biblioteca o en la ruta de la biblioteca serían vistos por la aplicación de Office como corruptos en la carga.



[//]: # (NO QUITAR ERRORES DE DETALLES DE CONTENIDO FINAL)

## <a name="version-2004-april-29"></a>Versión 2004: 29 de abril
*Versión 2004 (compilación 12730.20236)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="access"></a>Access

- **Aumente su productividad con el Diseñador de consultas, la vista SQL y la ventana Relaciones:** haga clic con el botón derecho en una tabla para abrirla, diseñarla, cambiar su tamaño y ocultarla. Buscar y reemplazar texto en la vista SQL. Seleccione múltiples tablas en la ventana Relaciones.

- **Agregue tablas con menos clics:** utilizar el panel de tareas agregar tablas, que permanece abierto mientras trabaja, para agregar tablas a relaciones y consultas. [Más información](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)


### <a name="excel"></a>Excel

- **El soporte para el conector de Facebook va a terminar:** a partir de abril de 2020. Excel ya no admitirá conexiones de datos externos que usen el conector de Facebook.

- **¿Tiene alguna pregunta? Ask Excel:** ahora, las ideas de Excel le permiten formular preguntas sobre los datos, sin necesidad de dedicar tiempo a escribir fórmulas (disponible solo en inglés). [Más información](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- **Nuevas imágenes para dar vida a sus libros de trabajo:** miles de imágenes de archivo, iconos y adhesivos sin derechos de autor que puede usar en sus libros de trabajo. Vaya a Insertar > Imágenes > Imágenes de archivo para empezar. [Más información](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="outlook"></a>Outlook

- **Unirse a reuniones sin salir de la bandeja de entrada:** no es necesario cambiar al calendario para unirse a reuniones en línea. Con el Calendario de Outlook anclado en el panel de tareas pendientes, únase a una reunión con un solo clic.

- **Nuevas imágenes para dar vida a sus mensajes:** miles de imágenes de archivo, iconos y adhesivos sin derechos de autor que puede usar en sus mensajes de correo electrónico. Vaya a Insertar > Imágenes > Imágenes de archivo para empezar. [Más información](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

- **Compatibilidad con la sugerencia de ubicaciones para las reuniones periódicas:** Búsqueda de salas de conferencias con la programación de reuniones periódicas.

### <a name="powerpoint"></a>PowerPoint

- **Actualización de las diapositivas durante la presentación:** actualice diapositivas editadas por otros autores durante la presentación.

- **Nuevas imágenes para dar vida a sus diapositivas:** miles de imágenes de archivo, iconos y adhesivos sin derechos de autor que puede usar en sus diapositivas. Vaya a Insertar > Imágenes > Imágenes de archivo para empezar. [Más información](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="teams"></a>Teams

- **Mejoras en el calendario de Teams:** haga clic con el botón derecho en un elemento del calendario para extraer las opciones de RSVP, iniciar un chat con los participantes de la reunión o unirse a una reunión rápidamente cuando se inicie. También hemos realizado mejoras en el formulario de programación de eventos.

- **Etiqueta, ¡te toca!: ** cree etiquetas y asígneles personas para que pueda mencionar un grupo, rol, departamento, etc. Los propietarios de equipos ya pueden probarlo. Vaya a un equipo, seleccione Más opciones, Administrar etiquetas.

### <a name="word"></a>Word

- **Tenga a mano las herramientas:** en el cuadro de herramientas de dibujo, busque el lápiz inteligente que le permite agregar gestos de entrada de lápiz al texto. [Más información](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- **Nuevas imágenes para dar vida a sus documentos:** miles de imágenes de archivo, iconos y adhesivos sin derechos de autor que puede usar en sus documentos. Vaya a Insertar > Imágenes > Imágenes de archivo para empezar. [Obtener más información](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- En los libros guardados con una firma digital en Excel 2016 se podía invalidar la firma al abrirla en la versión actual de Excel.

- Se ha corregido un problema que hacía que Excel se bloqueara en ciertos casos después de copiar una hoja que contenía una tabla dinámica.

- Application.Evaluate (VBA) no funcionaba para funciones definidas por el usuario en algunos casos.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema que provocaba que el ancho del panel de carpetas cambiara inesperadamente.


- Se ha corregido un problema que provocaba que Outlook se bloqueara en algunas compilaciones de Windows.


- Se ha corregido un problema que provocaba que Outlook se bloqueara al abrir archivos .msg y .oft guardados localmente después de una actualización de Windows.


- Se ha corregido un problema que provocaba que Outlook se bloqueara en algunas compilaciones de Windows.


- Se corrigió un problema que provocaba que los usuarios experimentaran un error al salir de Outlook.


### <a name="project"></a>Project

- Cuando se editan los datos del Predecesor/Sucesor dentro de una vista de formulario, se activa un evento ProjectBeforeTaskChange adicional.


- Se ha corregido un problema que hace que si está usando Project conectado a Project Web App y el separador decimal es una coma, el método TaskDependencies Add producirá un error al intentar agregar retardo a una dependencia.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un error que impide restringir el acceso y proteger los archivos con una contraseña de forma simultánea.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2003-april-15"></a>Versión 2003: 15 de abril
*Versión 2003 (compilación 12624.20466)*
* Varias correcciones de errores y rendimiento.

## <a name="version-2003-april-14"></a>Versión 2003: 14 de abril
*Versión 2003 (compilación 12624.20442)*

Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Application.Evaluate (VBA) no funcionaba para funciones definidas por el usuario en algunos casos.

### <a name="outlook"></a>Outlook

- Abordó un problema que causó que los usuarios experimentaran ocasionalmente un choque al usar el botón "X" de su ratón.

### <a name="project"></a>Proyecto

- Cuando se editan los datos del Predecesor/Sucesor dentro de una vista de formulario, se activa un evento ProjectBeforeTaskChange adicional.

### <a name="word"></a>Word

- Abordó un problema que causó que los usuarios experimentaran ocasionalmente un choque al usar el botón "X" de su ratón.


[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-2003-march-31"></a>Versión 2003: 31 de marzo
*Versión 2003 (compilación 12624.20382)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="onenote"></a>OneNote

- Informe a los usuarios mediante la barra de información sobre los ajustes temporales de Microsoft OneNote que le ayudarán a mejorar la sincronización y la disponibilidad del servicio durante el alto uso en todo el mundo.

### <a name="project"></a>Project

- Se corrigió un problema por el que el usuario no podía especificar el trabajo previsto con fases temporales al activar la configuración para proteger el trabajo real.



[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-2003-march-25"></a>Versión 2003: 25 de marzo
*Versión 2003 (compilación 12624.20320)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Arrastre el correo electrónico a un grupo de tu propiedad:** Mueva y copie mensajes y conversaciones arrastrándolos desde su bandeja de entrada. Los mensajes que arrastres serán compartidos con todos los miembros del grupo.

- **Nueva experiencia para redes WiFi cautivas:** ¿alguna vez se ha unido a una red WiFi que requiere una página web para iniciar sesión? Outlook ahora lo detecta y le ayuda a estar conectado.

### <a name="word"></a>Word

- **Otros usuarios verán los cambios rápidamente**: las mejoras en la coautoría significan que los colaboradores podrán ver los cambios más rápido que nunca.

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- **Etiquetas de confidencialidad:** ahora puede aplicar una etiqueta de confidencialidad que su organización ha configurado para solicitarle permisos personalizados.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Excel se bloqueaba en ciertos casos cuando se volvía a abrir un libro incrustado en Word o PowerPoint.

- Corregido un problema por el que los enlaces externos no se actualizaban si el libro de origen estaba cerrado.

- Corregido un problema de rendimiento al crear gráficos a partir de plantillas.

### <a name="onenote"></a>OneNote

- Se obtiene una mejora de la sincronización y la estabilidad del servicio al reducir temporalmente el tamaño máximo de datos adjuntos recién insertados a 50 MB. Si los archivos superan este límite, los usuarios tendrán la opción de cargar el archivo a OneDrive e insertar un vínculo en OneNote.

- Se obtiene una mejora de la sincronización y la estabilidad del servicio al ajustar temporalmente la frecuencia de sincronización en OneNote 2016.

### <a name="outlook"></a>Outlook

- Se abordó un problema que causó que los usuarios vieran que el proceso de Outlook permanecía en el administrador de tareas después de salir.

### <a name="powerpoint"></a>PowerPoint

- Se ha mejorado un escenario de copiar y pegar: al copiar la forma en una diapositiva de PowerPoint y pegarla en otra diapositiva en bucle puede producir errores.


### <a name="project"></a>Project

- Corregido un problema que hace que el evento ProjectBeforeTaskChange no detecte cuándo se ha desactivado o activado una tarea mediante el botón Desactivar.

- Corregido un problema por el que Project puede bloquearse al guardar proyectos creados con versiones anteriores de Project.

- Corregido un problema por el que el porcentaje completado de la tarea se cambiaba incorrectamente a un valor inferior al 100 % después de que se marcara como completada. 

- Corregido un problema en el que las fechas de las tareas de resumen no se calculaban siempre correctamente.


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

## <a name="version-2002-march-10"></a>Versión 2002: 10 de marzo
*Versión 2002 (compilación 12527.20278)*

Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="project"></a>Project

- Corregido un problema en el que el evento OnUndoOrRedo no se desencadena sin ejecutar primero el método OpenUndoTransaction.



[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-2002-march-01"></a>Versión 2002: 01 de marzo
*Versión 2002 (compilación 12527.20242)*

[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="outlook"></a>Outlook

- Corrige un problema que provocaba que las aplicaciones de terceros no pudiesen enviar correo electrónico.



[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-2002-february-25"></a>Versión 2002: 25 de febrero
*Versión de 2002 (compilación 12527.20194)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Estadísticas de libros:** celdas, fórmulas, gráficos y tablas... Las contamos para que no tenga que hacerlo.

- **Perfiles de datos en el editor de consultas:** analice rápidamente los datos de las columnas, identifique errores y valores vacíos, vea histogramas de distribución y mucho más.


[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha solucionado un problema por el que las funciones CUBEVALUE a veces daban un resultado incorrecto.

### <a name="outlook"></a>Outlook

- Corregido un tema que causó que las comas en el campo de ubicación de una reunión se convirtieran en punto y coma.

- Corregido un problema que podría resultar en un choque al ver el mismo elemento en varias ventanas.

- Se ha corregido un problema por el que la opción para deshabilitar el resaltado de elementos marcados no funcionaba en algunos escenarios.

- Se ha corregido un problema por el que Outlook sincronizaba inesperadamente todo el correo, incluso cuando el deslizador de sincronización estaba configurado en un ajuste menor.


- Soluciona un problema que provocaba que los usuarios con tema negro vean la lista desplegable "de" muestra texto blanco sobre un fondo blanco.


- Este cambio restaura la capacidad de ver sujetos de varias líneas en el encabezado del mensaje.



[//]: # (NO ELIMINE EL CONTENIDO FINAL DE LOS DETALLES )

## <a name="version-2001-february-19"></a>Versión 2001: 19 de febrero
*Versión 2001 (Compilación 12430.20288)*
* Varias correcciones de errores y rendimiento.

## <a name="version-2001-february-11"></a>Versión 2001: 11 de febrero
*Versión 2001 (compilación 12430.20264)*

Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Las plantillas de Access ya no deberían causar errores en columnas de datos adjuntos en una base de datos. Después de crear la instancia de una plantilla, ahora debería poder agregar un campo de datos adjuntos a la base de datos.

### <a name="excel"></a>Excel

- Se ha corregido un problema por el que los comandos de comentario en el menú contextual no aparecían.

- Se ha corregido un problema que causaba que algunos usuarios experimentasen bloqueos al convertir texto en columnas con celdas que tienen una matriz derramada.


### <a name="outlook"></a>Outlook

- Corrige un problema que provocaba que los usuarios experimentaran un bloqueo al especificar una dirección de origen no válida.


- Corrige un problema que provocaba que los usuarios experimentaran un error al cancelar la configuración de la cuenta.


### <a name="project"></a>Project

- Se ha corregido un problema por el que el 100 % de las tareas de tipo duración fija podían tener un cálculo del porcentaje incorrecto con menos del 100% completado.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Este cambio resuelve problemas con adaptadores gráficos que aprovechan la GPU integrada de Intel.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2001-january-30"></a>Versión 2001: 30 de enero
*Versión 2001 (compilación 12430.20184)*

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Lea y responda sobre la marcha: **responda a los comentarios y las menciones directamente desde el correo electrónico sin abrir el libro.

- **Busque a la izquierda, busque a la derecha... BUSCARX ya está aquí**: fila por fila, busque lo que necesite en una tabla o un rango con BUSCARX. [Más información](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)

### <a name="outlook"></a>Outlook

- **Configuración avanzada del correo electrónico del grupo:** Esta característica ayuda a los usuarios del grupo a personalizar qué mensajes o eventos recibirán o seguirán en la bandeja de entrada.

- **Directiva de nomenclatura de grupos:** las directivas de nomenclatura de grupo permiten al administrador de TI normalizar y administrar los nombres de los grupos creados por usuarios de la organización. El administrador puede requerir que se añada un prefijo o sufijo concreto al nombre de un grupo cuando se crea y puede bloquear el uso de determinadas palabras. Esto ayuda a minimizar el uso de palabras inadecuadas en los nombres de grupo, y permite que el administrador de TI gestione la representación de los grupos en el directorio. La Directiva de nomenclatura también ayuda a las organizaciones que implementan sitios de grupo a organizarse en base al departamento.

### <a name="word"></a>Word

- **Una experiencia de vídeo más segura:** las mejoras de seguridad hacen que la experiencia de vídeo en línea sea más segura. [Más información](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- **Selección de lazo de la entrada de lápiz:** la herramienta Lazo en la pestaña Dibujar le ayuda a seleccionar objetos dibujados a mano. Seleccione trazos individuales o palabras completas. [Más información](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **Guarde formas como imágenes:** con tan solo unos pocos clics, guarde una forma, icono u otro objeto como archivo de imagen para que pueda volver a usarlo en otro lugar. [Obtener más información](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)




[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Esta actualización corrige un problema por el que al usar un objeto de grabación de ADODB en el código de VB, se puede notificar un error incorrectamente.


- Esta actualización corrige un problema que puede hacer que Microsoft Access no identifique una Columna de identidad en una tabla vinculada de SQL Server, lo que puede provocar que las filas aparezcan como eliminadas de forma incorrecta.


### <a name="excel"></a>Excel

- Corrige un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.


### <a name="outlook"></a>Outlook

- Corrige un problema que causaba que los usuarios experimentasen bloqueos al cambiar el nombre de una firma.


[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-1912-january-22"></a>Versión 1912: 22 de enero
*Versión 1912 (compilación 12325.20344)*

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Esta actualización corrige un problema que puede hacer que Microsoft Access no identifique una Columna de identidad en una tabla vinculada de SQL Server, lo que puede provocar que las filas aparezcan como eliminadas de forma incorrecta.



[//]: # (NO QUITAR DETALLES DEL ERROR CONTENIDO FINAL)

## <a name="version-1912-january-14"></a>Versión 1912: 14 de enero
*Versión 1912 (compilación 12325.20298)*

Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

## <a name="version-1912-january-08"></a>Versión 1912: 8 de enero
*Versión 1912 (compilación 12325.20288)*

[//]: # (NO BORRAR LAS CARACTERÍSTICAS DEL CONTENIDO DE INICIO)

### <a name="feature-updates"></a>Actualizaciones de características

### <a name="outlook"></a>Outlook

- **Enviar un correo electrónico accesible a los usuarios que más lo necesitan:** Outlook mostrará una sugerencia de correo para ayudarlo a asegurarse de que el contenido sea accesible al enviarlo a un usuario que prefiera el contenido accesible

### <a name="powerpoint"></a>PowerPoint

- **Optimizar la presentación para todos:** El comprobador de accesibilidad le ayuda a organizar los objetos de las diapositivas pensando en los lectores de pantalla.

- **GIF en un instante:** una diapositiva, un marco. Cree fácilmente archivos GIF en bucle en PowerPoint. [Obtener más información](https://support.office.com/en-us/article/a598753e-92de-4f1b-8393-714db4d334b4)

[//]: # (NO QUITAR LAS CARACTERÍSTICAS DEL CONTENIDO DEL FIN)

<br/>

[//]: # (NO QUITAR DETALLES DE ERROR CONTENIDO INICIAL)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Este cambio evita un problema con ciertos controladores de gráficos Intel al aprovechar el procesamiento del software.

### <a name="outlook"></a>Outlook

- Se trata de un problema que provocó que la ubicación de una reunión se añadiera a la misma de forma inesperada después de haberla despejado.

- Corregido un problema que hacía que los usuarios vieran un retraso notable al interactuar con sus carpetas de buzón de correo a través de métodos abreviados de teclado.

- Corregido un problema que hacía que los usuarios vieran correos electrónicos enviados a una dirección que no coincidía con la dirección SMTP mostrada en algunas circunstancias.

- Corregido un problema que hacía que los usuarios no tuvieran respuesta de Outlook al recuperar la configuración de la nube.

### <a name="word"></a>Word

- El organizador de bloques de creación puede mostrar una alerta no válida: "ha modificado estilos, bloques de creación".

### <a name="office-suite"></a>Conjunto de programas de Office

- Se ha corregido un problema por el que las actualizaciones de Office podían haber descargado inesperadamente archivos de la CDN de Office en lugar de la fuente prevista, como un recurso compartido local o de red, o una ubicación proporcionada por el Administrador de configuración.

[//]: # (NO ELIMINAR LOS DETALLES DE ERROR DEL CONTENIDO FINAL)

> [!NOTE]
> Si necesita ayuda con algún problema de uso de Office, le recomendamos que publique la pregunta en el [foro de preguntas de Microsoft](https://answers.microsoft.com/) o [Tech Community](https://techcommunity.microsoft.com/), o bien puede ponerse en contacto con el [servicio de soporte técnico](https://support.microsoft.com/contactus).
