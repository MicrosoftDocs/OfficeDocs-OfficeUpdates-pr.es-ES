---
title: Notas de la versión para las versiones del Canal mensual para empresas
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Proporciona a los profesionales de TI las notas de la versión para las versiones del Canal mensual para empresas para Aplicaciones de Microsoft 365
ms.openlocfilehash: 96a76ed1ed1849753422dae92626484a77cec2a4
ms.sourcegitcommit: 4f5536e809f58462d81c708c153390ebfd1abc4e
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 07/13/2021
ms.locfileid: "53409566"
---
# <a name="release-notes-for-monthly-enterprise-channel"></a>Notas de la versión para el Canal mensual para empresas

Estas notas de la versión proporcionan información sobre las nuevas características y las actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones del Canal de empresa mensual para Aplicaciones de Microsoft 365 para empresas, Aplicaciones de Microsoft 365 para negocios y las versiones de suscripción de las aplicaciones de escritorio de Project y Visio.


[//]: # (NO ELIMINAR)



## <a name="version-2105-july-13"></a>Versión 2105: 13 de julio
*Versión 2105 (compilación 14026.20334)*

Lista de actualizaciones de seguridad [aquí](microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="outlook"></a>Outlook

- **Obtenga sugerencias relevantes de archivo al buscar:** Al escribir en el cuadro de búsqueda, los archivos más relevantes relacionados con la búsqueda se incluirán en sus sugerencias.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Hemos corregido un problema para permitir que el Administrador de nombres se abra en libros con un gran número de nombres ocultos.


- Hemos corregido un problema que hacía que a algunos usuarios les aparecieran entradas adicionales en la lista del complemento de Excel.


- Se ha corregido un problema en el que el complemento de Herramientas para análisis no funcionaba para algunos usuarios.


### <a name="outlook"></a>Outlook

- El cambio se está realizando en segundo plano y bajo una puerta de cambio, por lo que, si hay problemas, se puede desactivar rápidamente.


- Hemos agregado una clave del Registro que deshabilita la nueva experiencia del Buscador de salas (la misma experiencia que en Outlook para Web) y habilita el Buscador de salas heredado con Horas sugeridas.

   Clave del Registro:

    >HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar REG_DWORD “ShowLegacyRoomFinder”

    >0 (predeterminado): Outlook usa la nueva experiencia con tecnología del Buscador de salas de OWA cuando el usuario hace clic en el botón "Buscador de salas" para buscar salas disponibles.</br>
    >1: Outlook usa la interfaz de usuario del Buscador de salas heredada para buscar salas disponibles


- Este cambio permite a los usuarios enviar comentarios a través de nuestro nuevo sistema de comentarios.


- Hemos corregido un problema que causaba que la opción de comentarios no estuviese habilitada para los usuarios de la versión preliminar de Office Perpetual 2021.


- Se ha corregido un problema que provocaba que los usuarios reciban un error al seleccionar "Abrir propiedades de Outlook" en el menú contextual del botón derecho de un destinatario en un correo electrónico.


- Se ha corregido un problema que causaba que algunos usuarios experimentasen un cierre inesperado de la app al cargar tarjetas de persona.


- Hemos corregido un problema que causaba que los usuarios experimentasen un cierre inesperado al quitar carpetas de un almacén de archivos.


- Se ha corregido un problema que causaba que algunas instrucciones de la característica "Acortar reuniones" estuvieran deshabilitadas a través de las tecnologías de lector de pantalla.


- Hemos corregido un problema que provocaba que los usuarios experimentaran un aviso de cambio de propiedad inesperado al cerrar un mensaje al que habían respondido o que habían reenviado.


- Hemos solucionado un problema que podía provocar un cierre inesperado al interactuar con el Correo de Outlook o las Vistas de Calendario.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema por el que la opción de Reutilizar diapositivas no estaba disponible para unos pocos usuarios.


### <a name="project"></a>Project

- Se ha corregido un problema que hacía que las tareas de las tareas programadas manualmente se movieran a una fecha incorrecta.


- Se ha corregido un problema por el que, si crea una fórmula de campo personalizada que usa las funciones ProjectDate */ProjectDur* y si el segundo parámetro son las funciones Fecha(), Ahora() u Hora() de fecha y hora, se genera un #ERROR.


### <a name="word"></a>Word

- Corrige un problema con el que no se abre en el panel del Editor.


- Se ha corregido un problema por el que las tarjetas contextuales de lienzo de ortografía y gramática mostraban botones de iconos, pero esos botones no tenían información sobre herramientas.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema de localización por el que ahora en-gb, fr-ca y es-mx coincidirán con sus respectivas versiones primarias.


- Se ha corregido un cierre inesperado al volver a abrir determinados archivos.


- Se ha corregido una regresión de rendimiento al abrir archivos SyncBacked.


- Se ha corregido un problema que provocaba que el usuario no pudiera editar determinados documentos almacenados en servidores locales de SharePoint.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2104-july-13"></a>Versión 2104: 13 de julio
*Versión 2104 (compilación 13929.20434)*

Las actualizaciones de seguridad se enumeran [aquí](microsoft365-apps-security-updates.md)

## <a name="version-2104-june-08"></a>Versión 2104: 8 de junio
*Versión 2104 (Compilación 13929.20408)*

Lista de actualizaciones de seguridad [aquí](microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Autoguardado y coautoría en documentos cifrados confidenciales:** no elija entre productividad y seguridad. Con Microsoft Information Protection, los documentos que se cifran con etiquetas de confidencialidad ahora permiten el autoguardado y la coautoría con otras personas en tiempo real, igual que los documentos sin cifrar. Requiere que el espacio empresarial opte por participar (más información: https://aka.ms/mipcoauth).

### <a name="powerpoint"></a>PowerPoint

- **Autoguardado y coautoría en documentos cifrados confidenciales:** no elija entre productividad y seguridad. Con Microsoft Information Protection, los documentos que se cifran con etiquetas de confidencialidad ahora permiten el autoguardado y la coautoría con otras personas en tiempo real, igual que los documentos sin cifrar. Requiere que el espacio empresarial opte por participar (más información: https://aka.ms/mipcoauth).

### <a name="word"></a>Word

- **Autoguardado y coautoría en documentos cifrados confidenciales:** no elija entre productividad y seguridad. Con Microsoft Information Protection, los documentos que se cifran con etiquetas de confidencialidad ahora permiten el autoguardado y la coautoría con otras personas en tiempo real, igual que los documentos sin cifrar. Requiere que el espacio empresarial opte por participar (más información: https://aka.ms/mipcoauth).


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema que en ocasiones producía errores al abrir algunos archivos en la Vista protegida.


- Se ha corregido un problema que causaba que el formato de fecha se mostrara de forma incorrecta en algunos idiomas al usar complementos.


- Se ha corregido un problema por el que el complemento de Herramientas para análisis no funcionaba para algunos usuarios.


- Se ha corregido un problema que hacía que a algunos usuarios les aparecieran entradas adicionales en la lista del complemento de Excel.


- Corrección de un problema por el que una reversión de compilación de versión principal podía provocar la finalización de la aplicación al abrir el archivo.


### <a name="outlook"></a>Outlook

- Hemos corregido un problema que provocaba que algunos usuarios de la característica de uso compartido del calendario experimentaran problemas al interactuar con su calendario en el panel de navegación.


- Hemos agregado una clave del Registro que deshabilita la nueva experiencia del Buscador de salas (la misma experiencia que en Outlook para Web) y habilita el Buscador de salas heredado con Horas sugeridas.
    
    Clave del Registro:

    >HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar </br>
    >REG_DWORD “ShowLegacyRoomFinder”</br></br>
    > 0 (predeterminado): Outlook usa la nueva experiencia con tecnología del Buscador de salas de OWA cuando el usuario hace clic en el botón "Buscador de salas" para buscar salas disponibles.  </br>
    > 1: Outlook usa la interfaz de usuario del Buscador de salas heredada para buscar salas disponibles </br>


- Hemos corregido un problema que provocaba errores en la resolución de nombres al enviar en nombre de otro usuario y al resolver en una libreta de direcciones que no es la Lista global de direcciones.


- Hemos corregido un problema que causaba que la opción de comentarios no se mostrara a los usuarios de la versión preliminar de Office Perpetual 2021.


- Hemos corregido un problema que podía provocar que los usuarios vieran el mensaje que indica que están redactando perder el foco de la interfaz de usuario.


- Hemos corregido un problema que causaba que Outlook anulara las preferencias de la Bandeja de entrada Prioritarios configuradas en OWA.


- Hemos corregido un problema que provocaba que los usuarios vieran desaparecer las firmas de forma inesperada.


- Hemos corregido un problema que provocaba que los usuarios de la configuración de itinerancia experimentaran falta de respuesta.


- Hemos corregido un problema que causaba que los usuarios experimentaran la finalización inesperada del proceso durante una búsqueda.


- Hemos corregido un cierre inesperado relacionado con la búsqueda.


- Hemos corregido un problema que provocaba que el selector de usuarios en Outlook se expandiera hacia arriba en lugar de hacia abajo para los usuarios con una licencia permanente.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema por el que la opción de Reutilizar diapositivas no estaba disponible para unos pocos usuarios.


- Hemos corregido un problema relacionado con las imágenes vinculadas.


- Se ha corregido un problema por el que una reversión de compilación de versión principal podía provocar un cierre inesperado al abrir el archivo.


### <a name="project"></a>Project

- Se ha corregido un problema en el que los usuarios no podían quitar proyectos del grupo de recursos.


### <a name="word"></a>Word

- Hemos corregido un problema que requería un cambio en la edición de Objeto OLE.


- Se ha corregido un problema por el que algunos textos de selección no se veían al usar el tema del modo oscuro en el modo lectura.


- Se ha corregido un problema que puede provocar que Word se cierre inesperadamente al cerrarse debido a que el usuario cierra o reinicia el equipo.


- Se ha corregido un problema que actualiza el texto en la llamada de autoguardado para los archivos guardados localmente.


- Se ha corregido un problema por el que una reversión de compilación de versión principal podía provocar un cierre inesperado al abrir el archivo.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema que causaba que no se pudiera abrir el documento en la nube.


- Este cambio analiza el nuevo atributo TenantId enviado a través de las respuestas de Cobalt y lo almacena en la Tabla Central.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2103-june-08"></a>Versión 2103: 8 de junio
*Versión 2103 (Compilación 13901.20554)*

Lista de actualizaciones de seguridad [aquí](microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Corrige un problema que hacía que a algunos usuarios les aparecieran entradas adicionales en la lista del complemento de Excel.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema por el cual Word, PowerPoint y Excel no podían abrir un documento en la nube al revertir a una compilación anterior



[//]: # (NO QUITAR FINAL DE CONTENIDO CON DETALLES DE ERROR)

## <a name="version-2103-may-11"></a>Versión 2103: 11 de mayo
*Versión 2103 (compilación 13901.20516)*

Lista de actualizaciones de seguridad [aquí](microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Usar automáticamente los nuevos tipos de datos**: al digitar un valor de datos que se asemeja a una ubicación geográfica o cotización, Excel ofrece la posibilidad de convertirlo en el tipo de datos conectado apropiado (cotizaciones o geografía). [Más información](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- **Tipos de datos vinculados: datos reales para la vida real:** los nuevos tipos de datos vinculados le aportan hechos y datos sobre cientos de temas para ayudarle a lograr sus objetivos directamente en Excel.

### <a name="outlook"></a>Outlook

- **Rompa la barrera del idioma con un traductor incorporado:** Los complementos para la traducción ya no son necesarios. Ahora puede usar el Traductor inteligente en Outlook. Cuando reciba un mensaje en otro idioma, aparecerá una ventana de notificación para preguntarle si le gustaría que Outlook lo tradujera en el idioma predeterminado.
También puede hacer clic con el botón derecho para traducir palabras específicas, oraciones o el mensaje completo. [Más información](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

### <a name="visio"></a>Visio

- **Gráficos preparados para los diagramas:** elija entre una gran biblioteca de íconos, imágenes de fotografías de archivo, personas recortadas y adhesivos que puede agregar a sus dibujos de Visio. [Más información](https://support.office.com/article/0ab844a5-289b-47f2-ba92-eeda168bc381)<br />Ver detalles en [entrada de blog](https://insider.office.com/es-ES/blog/access-illustrations-icons-in-visio)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Acceso

- Hemos corregido un problema por el que, cuando una aplicación externa solicitaba una interfaz de accesibilidad, nos impedía cerrar hasta que se liberaba su referencia.


- Este cambio corrige un problema por el que al ejecutar una consulta que pasara por SQL Server, se mostraba en algunos casos un mensaje de error que alertaba de un "estado de cursor no válido".


### <a name="excel"></a>Excel

- Se ha corregido un problema que causaba que el formato de fecha se mostrara de forma incorrecta en algunos idiomas al usar complementos.


- Se ha corregido un problema por el que el complemento de Herramientas para análisis no funcionaba para algunos usuarios.


- Se ha corregido un problema por el que Word podía bloquearse al dibujar una imagen.


### <a name="outlook"></a>Outlook

- Hemos corregido un problema que provocaba errores en la resolución de nombres al enviar en nombre de otro usuario y al resolver en una libreta de direcciones que no es la Lista global de direcciones.


- Se ha corregido un problema que causaba que Outlook anulara las preferencias de la Bandeja de entrada Prioritarios configuradas en OWA.


- Se ha corregido un problema que causaba que algunas personas no pudieran tener acceso a las firmas asociadas a cuentas de correo secundarias.


- Se ha corregido un problema que causaba que los usuarios vieran más firmas de las esperadas.


- Se ha corregido un problema que causaba que algunos usuarios vieran sus calendarios principal y secundario cambiando de lugar en el panel de navegación.


- Hemos corregido un problema que causaba que los usuarios vieran por error un mensaje de "Esto puede tardar un poco" mientras añadían algún elemento a un calendario.


- Hemos solucionado un problema que hacía que los delegados aparecieran como organizadores de reuniones creadas en calendarios recién añadidos.  Las reuniones en este estado no aparecían en el calendario del principal.


- Se ha corregido un problema en un componente de Outlook que se usa en las aplicaciones habilitadas para MAPI en equipos con procesadores ARM. El problema podría provocar errores en la búsqueda o causar una carga adicional en el equipo al reiniciar las aplicaciones en segundo plano varias veces.


- Se ha corregido un problema que causaba que algunos usuarios experimentaran un cierre inesperado de Outlook al sincronizar los cambios en la jerarquía de carpetas.


- Se ha corregido un problema por el que Word podía bloquearse al dibujar una imagen.


### <a name="powerpoint"></a>PowerPoint

- Hemos corregido un problema relacionado con las imágenes vinculadas.


- Se ha corregido un problema por el que Word podía bloquearse al dibujar una imagen.


### <a name="project"></a>Project

- Se ha corregido un problema que provocaba que Visio dejara de funcionar durante el cierre.


### <a name="visio"></a>Visio

- Se ha corregido un problema que provocaba que Visio dejara de funcionar durante el cierre.


### <a name="word"></a>Word

- Se ha corregido un problema para optimizar las condiciones para ofrecer previsiones de texto.


- Se ha corregido un problema para actualizar el texto en la llamada de Autoguardado para los archivos guardados localmente.


- Se ha corregido un problema por el que al trabajar en un documento en coautoría, el borrador activo no se borraba cuando cambiaba el orden de los comentarios.


- Corrige un problema por el que la vista previa de impresión se cerraba de forma inesperada.


- Se ha corregido un problema por el que Word podía bloquearse al dibujar una imagen.



### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema de confiabilidad relacionado con la compatibilidad de las aplicaciones de Office que se ejecutan en la sesión 0.


- Se ha corregido un problema por el que el cambio de nombre no respondía cuando se abría un archivo SyncBacked fuera de línea y se le cambiaba el nombre en la aplicación antes de guardarlo.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2102-may-11"></a>Versión 2102: 11 de mayo
*Versión 2102 (compilación 13801.20638)*

Lista de actualizaciones de seguridad [aquí](microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema que causaba que el formato de fecha se mostrara de forma incorrecta en algunos idiomas al usar complementos.


- Hemos corregido un problema que bloqueaba la capacidad de pegar como fórmulas en una hoja protegida.


### <a name="outlook"></a>Outlook

- Esto permite a los usuarios finales configurar Outlook para agregar una reunión en línea a cada reunión que creen.


### <a name="powerpoint"></a>PowerPoint

- Hemos corregido un problema relacionado con las imágenes vinculadas.


### <a name="word"></a>Word

- Soluciona un problema de WordMail por el que el usuario recibía el error "No se puede enviar este elemento" cuando el número 2084 de un vínculo era un carácter de escape.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema que causaba que Word se cerrara de forma inesperada al imprimir documentos largos.


- Antes de este cambio, las plantillas de Office se mostraban incluso aunque el GPO estuviera activado para deshabilitarlas. Con este cambio, las plantillas ahora respetan correctamente el GPO y se muestran u ocultan según se solicite.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2102-april-13"></a>Versión 2102: 13 de abril
*Versión 2102 (Compilación 13801.20506)*

Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Usar el cuadro de diálogo Opciones avanzadas para crear tipos de datos:** el cuadro de diálogo Opciones avanzadas le permite seleccionar manualmente las columnas que combinan el tipo de datos que está creando.

- **Mostrar varias hojas de cálculo al mismo tiempo:** no es necesario que se muestren las hojas de una en una, ya que se pueden mostrar varias hojas ocultas al mismo tiempo. [Más información](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)


### <a name="outlook"></a>Outlook

- **La configuración de la bandeja de entrada prioritaria permanece igual en todos los dispositivos:** ahora, las preferencias de la Bandeja de entrada Prioritarios se almacenan en la nube. Disfrute de la misma experiencia al usar Outlook para Windows en cualquier equipo y Outlook en la Web. [Más información](https://support.office.com/article/d77a442e-a86c-4bf8-b3dd-5571ae556986)

- **Su configuración de Outlook en la nube:** elija la configuración de Outlook para Windows, como Respuestas automáticas, la Bandeja de entrada Prioritarios y Privacidad, y acceda a ellos desde cualquier PC.

- **Elija dónde buscar:** La nueva lista desplegable del ámbito de búsqueda le permite modificar de manera más sencilla su búsqueda y cambiar entre la carpeta actual y el buzón actual. Gracias a todos los usuarios de Próximamente, quienes brindaron comentarios acerca de la nueva experiencia de búsqueda Search at Top. ¡Este diseño y actualización son el resultado de sus comentarios!

- **Escriba mensajes con su voz:** use la nueva barra de herramientas de dictado, los comandos de voz, la puntuación automática y mucho más para redactar mensajes.

### <a name="word"></a>Word

- **Escriba documentos con su voz:** use la nueva barra de herramientas de dictado, los comandos de voz, la puntuación automática para redactar documentos.


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="access"></a>Access

- Se ha corregido un problema por el que al ejecutar una consulta que pasara por SQL Server, se mostraba en algunos casos un mensaje de error que alertaba de un "estado de cursor no válido".



### <a name="excel"></a>Excel

- Hemos corregido un error en el que la validación de datos se podía aplicar a celdas de forma inesperada después de añadir filas a una tabla o a otra hoja.


- Hemos corregido un problema donde la función de mostrar DialogSheets no funcionaba en la versión de 32 bit de Excel.


- Hemos corregido un problema que hace que las imágenes fueran más pequeñas de lo esperado al usar la opción Pegar imagen vinculada.


- Hemos corregido un problema que causaba que algunos formatos de tabla dinámica dañaran el libro al guardar en formato .xls o .xlt.


- Hemos corregido un problema que impedía a los usuarios exportar un libro de Excel a PDF.


- Se ha corregido un problema por el que los comandos deshabilitados de la cinta de opciones de Office tenían el icono (pero no el texto) atenuado en el tema de Office Gris oscuro.


### <a name="outlook"></a>Outlook

- Hemos corregido un problema que causaba que los usuarios de traducción directa no pudieran enviar comentarios.


- Hemos corregido un problema que provocaba que las firmas con contenido Unicode se dañasen.


- Hemos corregido un problema que provocaba que los usuarios vieran más firmas de las esperadas.


- Hemos corregido un problema que provocaba que Outlook se bloquease cuando estaba inactivo.


- Hemos corregido un problema que causaba que la app se cerrase para algunos usuarios al cerrar las ventanas de mensaje.


- Hemos corregido un problema que causaba que los usuarios de las mejoras del calendario compartido no pudieran establecer el color de un calendario en amarillo o marrón.


- Hemos corregido el problema que causaba que los usuarios viesen grupos de calendario duplicados después de crear un grupo.


- Hemos corregido un problema por el que los usuarios no veían los calendarios agregados recientemente en el panel de navegación si no reiniciaban Outlook.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema por el que los comandos deshabilitados de la cinta de opciones de Office tenían el icono (pero no el texto) atenuado en el tema de Office Gris oscuro.


### <a name="word"></a>Word

- Hemos corregido un problema relacionado con la resolución de conflictos durante la coautoría.


- Hemos corregido un problema con los controles de contenido de texto enriquecido.


- Hemos corregido un problema con la escritura al final de un párrafo oculto que podía provocar que la aplicación dejara de funcionar.


- Hemos corregido un problema por el que el Narrador podía omitir un párrafo.


- Se ha corregido un problema con copiar y pegar.


- Se ha corregido un problema con los colores aplicados a los iconos y a los gráficos SVG con efectos 3D.


- Se ha corregido un problema por el que los comandos deshabilitados de la cinta de opciones de Office tenían el icono (pero no el texto) atenuado en el tema de Office Gris oscuro.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha corregido un problema de confiabilidad relacionado con la compatibilidad de las aplicaciones de Office que se ejecutan en la sesión 0.


- Se ha corregido un problema que a veces provocaba que el texto en Outlook se viera transparente y no fuera legible.


- Se ha corregido un problema al usar Narrador en un texto que contiene ecuaciones matemáticas.


- Se ha corregido un problema que impedía la opción Dictado para usuarios de GCC.


- Se ha corregido un problema por el que los usuarios no podían guardar un archivo al abrirlo, realizar modificaciones sin guardar y eliminarlo. Después de la corrección, los usuarios recibirán un mensaje descriptivo para informarles de que el archivo se ha eliminado, de modo que podrán descartar cambios o usar la opción Guardar como.


- Se ha corregido el problema del cambio de nombre cuando se abría un archivo SyncBacked fuera de línea y se le cambiaba el nombre en la aplicación antes de guardarlo.



[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL )

## <a name="version-2101-april-13"></a>Versión 2101: 13 de abril
*Versión 2101 (Compilación 13628.20664)*

Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

## <a name="version-2101-march-09"></a>Versión 2101: 9 de enero
*Versión 2101 (Compilación 13628.20528)*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Corrige un problema por el que Excel no se iniciaba o se cerraba inesperadamente si se estaba usando cierta configuración de protección contra vulnerabilidades de Seguridad de Windows (SimExec, CallerCheck).


### <a name="outlook"></a>Outlook

- Hemos corregido un problema que hacía que no se mostrara el icono de cifrado de los correos electrónicos enviados con la opción de solo cifrado.


- Hemos corregido un problema por el que los mensajes de correo electrónico se enviaban como firmados digitalmente después de que el usuario desactivara esa opción.


- Hemos corregido un problema que causaba errores al mostrar la firma predeterminada correcta en OWA.


- Hemos corregido un problema que causaba que los usuarios de Configuración de la nube tuviesen un error al actualizar la configuración.


- Hemos corregido un problema que causaba que la aplicación se cerrara de forma inesperada al buscar en Outlook.


- Se ha corregido un problema que causaba que los usuarios que tienen buzones compartidos o delegados con jerarquías grandes en su perfil sufriesen bloqueos.


- Se ha corregido un problema que provocaba que Outlook se cerrara de forma inesperada para algunos usuarios en ciertos escenarios de búsqueda.


### <a name="project"></a>Project

- Se corrigió un problema por el que, cuando se asignó un recurso de costo a una tarea hito, el costo de línea base no se acumulaba correctamente.


- Se ha corregido un problema en el que los bordes no se mostraban para las tareas en la vista Organizador de equipo.


- Se ha corregido un problema en el que la opción de arrastrar y colocar no funcionaba para las tareas de la vista Organizador de equipo.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Soluciona un problema relacionado con las notificaciones de eventos del controlador multimedia.


- Soluciona un problema relacionado con los intervalos de los motores del reproductor multimedia.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2012-march-09"></a>Versión 2012: 09 de febrero
*Versión 2012 (compilación 13530.20628)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)

[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Requerir que los usuarios apliquen etiquetas de confidencialidad:** Se pedirá a los usuarios que apliquen una etiqueta de confidencialidad si la directiva de su organización lo requiere.

### <a name="powerpoint"></a>PowerPoint

- **Requerir que los usuarios apliquen etiquetas de confidencialidad:** Se pedirá a los usuarios que apliquen una etiqueta de confidencialidad si la directiva de su organización lo requiere.

### <a name="word"></a>Word

- **Requerir que los usuarios apliquen etiquetas de confidencialidad:** Se pedirá a los usuarios que apliquen una etiqueta de confidencialidad si la directiva de su organización lo requiere.


## <a name="version-2012-february-09"></a>Versión 2012: 09 de febrero
*Versión 2012 (compilación 13530.20528)*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="excel"></a>Excel

- **Compatibilidad con el portapapeles SVG:** ahora puede pegar contenido SVG de Office en aplicaciones de terceros. [Más información](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **Registro de auditoría de etiquetas de confidencialidad:** cuando los usuarios aplican, cambian o quitan etiquetas de confidencialidad en sus documentos y correos electrónicos, esa información está ahora disponible para los administradores en los registros de auditoría de Microsoft 365.

- **Los clientes gubernamentales pueden ya aplicar etiquetas de confidencialidad a sus documentos y correos electrónicos**: las características de las etiquetas de confidencialidad ahora están disponibles para los clientes de los entornos GCC y GCC-H. [Más información](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a>Outlook

- **Compatibilidad con el portapapeles SVG:** ahora puede pegar contenido SVG de Office en aplicaciones de terceros. [Más información](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **Dar algo de tiempo entre reuniones consecutivas:** asigne a los asistentes el tiempo necesario para que descansen o se desplacen entre las distintas ubicaciones. Para ello haga que las reuniones empiecen de 5 a 10 minutos antes de forma predeterminada. [Más información](https://support.office.com/article/ebb4c4c9-6992-4ea7-9772-8b5883df8500)

- **Registro de auditoría de etiquetas de confidencialidad:** cuando los usuarios aplican, cambian o quitan etiquetas de confidencialidad en sus documentos y correos electrónicos, esa información está ahora disponible para los administradores en los registros de auditoría de Microsoft 365.

- **Todas las reuniones en línea:** Actualice la configuración del calendario para que cada reunión que cree se cree sea una reunión de Teams de forma predeterminada, de modo que no tenga que recordar hacer clic en la opción Reunión de Teams

- **Los clientes gubernamentales pueden ya aplicar etiquetas de confidencialidad a sus documentos y correos electrónicos**: las características de las etiquetas de confidencialidad ahora están disponibles para los clientes de los entornos GCC y GCC-H. [Más información](/microsoft-365/compliance/sensitivity-labels)

- **Todas las reuniones en línea:** Actualice la configuración del calendario para que cada reunión que cree se cree sea una reunión de Teams de forma predeterminada, de modo que no tenga que recordar hacer clic en la opción Reunión de Teams

- **Nuevo buscador de salas:** búsqueda de salas de conferencias por distintas funcionalidades.

- **Nueva experiencia de reserva de sala de conferencias y área de trabajo:** se ha actualizado la experiencia de reserva de la sala de conferencias y, con ella, hemos agregado funcionalidades para permitirle programar áreas de trabajo individuales.


### <a name="powerpoint"></a>PowerPoint

- **Compatibilidad con el portapapeles SVG:** ahora puede pegar contenido SVG de Office en aplicaciones de terceros. [Más información](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br />Ver detalles en [entrada de blog](https://insider.office.com/es-ES/blog/svg-content-office-third-party-apps)

- **Registro de auditoría de etiquetas de confidencialidad:** cuando los usuarios aplican, cambian o quitan etiquetas de confidencialidad en sus documentos y correos electrónicos, esa información está ahora disponible para los administradores en los registros de auditoría de Microsoft 365.

- **Los clientes gubernamentales pueden ya aplicar etiquetas de confidencialidad a sus documentos y correos electrónicos**: las características de las etiquetas de confidencialidad ahora están disponibles para los clientes de los entornos GCC y GCC-H. [Más información](/microsoft-365/compliance/sensitivity-labels)

### <a name="visio"></a>Visio

- **Nuevas galerías de símbolos y formas de Azure:** Hemos agregado muchas más galerías de símbolos para ayudarle a crear diagramas de Azure actualizados. [Más información](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a>Word

- **Compatibilidad con el portapapeles SVG:** ahora puede pegar contenido SVG de Office en aplicaciones de terceros. [Más información](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **Registro de auditoría de etiquetas de confidencialidad:** cuando los usuarios aplican, cambian o quitan etiquetas de confidencialidad en sus documentos y correos electrónicos, esa información está ahora disponible para los administradores en los registros de auditoría de Microsoft 365.

- **Los clientes gubernamentales pueden ya aplicar etiquetas de confidencialidad a sus documentos y correos electrónicos**: las características de las etiquetas de confidencialidad ahora están disponibles para los clientes de los entornos GCC y GCC-H. [Más información](/microsoft-365/compliance/sensitivity-labels)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Este cambio soluciona un problema que impedía mostrar correctamente fuentes en ecuaciones.


- Se ha corregido un problema por el que algunos usuarios veían incorrectamente una barra de mensajes que les informaba de una nueva versión de un archivo durante la coautoría.


- Se ha corregido un problema que provocaba que Excel dejara macros deshabilitadas sin preguntar al abrir archivos de complemento de Excel que contuvieran macros Excel 4.0.


- Corrige un problema por el que Excel no se iniciaba o se cerraba inesperadamente si se estaba usando cierta configuración de protección contra vulnerabilidades de Seguridad de Windows (SimExec, CallerCheck).


- Se ha corregido un problema que provocaba que Excel se cerrara de manera inesperada al usar el menú "Mostrar valores como" para una tabla dinámica.


- Hemos corregido un problema que interrumpía algunas macros heredadas de Excel 4.0 y Excel 5.0, así como algunas llamadas de VBA a dialogsheets.show.


### <a name="outlook"></a>Outlook

- Se ha corregido un problema por el que la firma editada no podía guardarse tras pedirle al usuario que lo hiciera.


- Se ha corregido un problema que provocaba que Outlook se cerrara de forma inesperada para algunos usuarios en ciertos escenarios de búsqueda.


- Se ha corregido un problema que causaba que algunos clientes experimentaran un cuelgue mientras cargaban sus calendarios.


- Se ha corregido un problema que causaba que los usuarios que tienen buzones compartidos o delegados con jerarquías grandes en su perfil sufriesen bloqueos.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema por el que el comando tamaño de fuente, agregado a la herramienta de acceso rápido, se completaba automáticamente al tamaño de fuente definido más cercano al actualizarse.


- Este cambio soluciona un problema que impedía mostrar correctamente fuentes en ecuaciones.


- Este cambio resuelve un problema con el relleno de rutas al aplicar las operaciones de Combinar formas con determinadas geometrías.


### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Anaheim WebView aún no es compatible con Windows Information Protection. Con esta corrección, la plataforma de complementos de Office retrocede al nivel inferior de WebView en un entorno habilitado para WIP. Según el entorno de máquina del cliente, esto puede ser Edge Spartan WebView o Trident WebView. Las vistas previas de nivel inferior son compatibles con WIP.


- Tamaño binario optimizado.


- Se ha corregido la secuencia de cierre de archivos para que todos los componentes interdependientes se cierren correctamente.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2011-february-09"></a>Versión 2011: 09 de febrero
*Versión 2011 (compilación 13426.20658)*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)

## <a name="version-2011-january-12"></a>Versión 2011: 12 de enero
*Versión 2011 (Compilación 13426.20526)*

Lista de actualizaciones de seguridad [aquí](./microsoft365-apps-security-updates.md)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO INICIO)

### <a name="feature-updates"></a>Actualizaciones de características
### <a name="access"></a>Acceso

- **Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10. Vaya a Archivos > Cuenta y elija "Usar la opción del sistema" en la lista desplegable Temas de Office. [Más información](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a>Excel

- **Crear variables para usar en fórmulas:** mejorar el rendimiento, la legibilidad y la composición con la función LET. Esta función le permite crear variables con nombre en fórmulas nuevas o previamente existentes. [Más información](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br />Ver detalles en la [entrada de blog](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)

- **Crear un tipo de datos personalizado en Power Query:** use cualquier origen de datos para crear un tipo de datos personalizado que le permita cargar varias piezas de información relacionadas en una columna. [Más información](https://support.office.com/article/a465a3b7-3d37-4eb1-a59c-bd3163315308)<br />Ver detalles en [entrada de blog](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)

- **Dele un nombre a la nueva hoja después de la consulta de origen:** cuando se carguen los datos en la nueva hoja, la hoja recibirá un nombre basado en el nombre de la consulta de origen.

- **Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10. Vaya a Archivos > Cuenta y elija "Usar la opción del sistema" en la lista desplegable Temas de Office. [Más información](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a>OneNote

- **Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10. Vaya a Archivos > Cuenta y elija "Usar la opción del sistema" en la lista desplegable Temas de Office. [Más información](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a>Outlook

- **Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10. Vaya a Archivos > Cuenta y elija "Usar la opción del sistema" en la lista desplegable Temas de Office. [Más información](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


### <a name="powerpoint"></a>PowerPoint

- **Biblioteca de vídeos:** Mejore sus documentos con una biblioteca de videos seleccionados y libres de regalías disponibles en la aplicación.

- **Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10. Vaya a Archivos > Cuenta y elija "Usar la opción del sistema" en la lista desplegable Temas de Office. [Más información](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a>Project

- **Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10. Vaya a Archivos > Cuenta y elija "Usar la opción del sistema" en la lista desplegable Temas de Office. [Más información](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a>Publisher

- **Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10. Vaya a Archivos > Cuenta y elija "Usar la opción del sistema" en la lista desplegable Temas de Office. [Más información](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a>Visio

- **Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10. Vaya a Archivos > Cuenta y elija "Usar la opción del sistema" en la lista desplegable Temas de Office. [Más información](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a>Word

- **Cambiar los temas de Office automáticamente:** Office puede cambiar los temas automáticamente para que coincidan con la configuración de tema de Windows 10. Vaya a Archivos > Cuenta y elija "Usar la opción del sistema" en la lista desplegable Temas de Office. [Más información](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (NO QUITAR OPCIONES DETALLES CONTENIDO FINAL)

<br/>

[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- Se ha corregido un problema por el que Excel mostraba de forma incorrecta una barra de mensajes donde se indicaba que estaba disponible una nueva versión del archivo y obligaba al usuario a descartar los cambios o guardarlos en una copia del libro.


- Se solucionó un problema que provocaba que Excel dejara macros deshabilitadas sin preguntar al abrir archivos de complemento de Excel que contuvieran macros Excel 4.0.


### <a name="outlook"></a>Outlook

- Se ha corregido un problema que causaba que algunos usuarios no vieran ninguna firma en la lista desplegable a pesar de que se configuraron una o varias firmas.


- Se ha agregado una clave de registro que permite a los clientes deshabilitar la inclusión de hora de archivo para datos adjuntos en operaciones de IDataObject (es decir, arrastrar y soltar, portapapeles).  HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments. REG_DWORD IncludeFileTimesInDataObject. 0 = se excluyen horas de archivo. 1 = (predeterminado) se incluyen horas de archivo.


- Se ha corregido un problema que provocaba que las imágenes en línea desaparecieran al responder a un mensaje con una etiqueta de protección de Azure Information Protection.


- Se ha corregido un problema que interrumpía el evento MailItem.BeforeAttachmentAdd.


- Se ha corregido un problema por el que el campo "Para" quedaba vacío al enviar un informe de estado en una tarea.


- Se ha corregido un problema por el que los asistentes originales de algunas reuniones recibían una cancelación cuando otro asistente reenviaba la reunión.


### <a name="powerpoint"></a>PowerPoint

- Se ha corregido un problema por el que algunos archivos de PowerPoint corruptos no se abrían correctamente, incluso después de una operación de reparación de documento.


- Se ha corregido un problema que provocaba un error al guardar el archivo después de duplicar una diapositiva que contuviera un audio grabado recientemente.


- Se ha corregido un problema de VBA por el que Slide.Shapes.AddMediaObject2 se bloqueaba con formatos de vídeo heredados (MPG-1, MPEG-2).


- Este cambio resuelve un problema con el control de errores que pueden producirse durante la carga de vídeo.


- Se ha corregido un problema relacionado con la función de copiar y pegar una ecuación de Word a PowerPoint.


### <a name="project"></a>Project

- Se ha corregido un problema por el que algunos proyectos específicos podrían abrirse si había un problema con el archivo del proyecto en una parte específica de la carga.


### <a name="word"></a>Word

- Se ha corregido un error de aserción expuesto por puertas optimizadas que afectaba a Word.


- Se ha corregido un problema que reemplazaba los estilos del documento con otros estilos de la plantilla.


- Este cambio resuelve un problema con el cursor al editar un documento.


- Se ha corregido un problema relacionado con la función de copiar y pegar una ecuación de Word a PowerPoint.


### <a name="office-suite"></a>Conjunto de programas de Office

- Se ha corregido un problema por el que la instalación de una versión más reciente de Office sobre algunas versiones anteriores podía resultar en un deterioro de la funcionalidad (por ejemplo, la imposibilidad de usar Power Query) debido a la falta de entradas del registro.


- Se ha corregido un problema por el que un archivo se abría como NO SyncBacked cuando la dirección URL de la memoria caché y la dirección URL de OneDrive NO coincidían.


- Se ha corregido un problema que provocaba que SaveRequestManagerCam causara que la aplicación se cerrara en lugar de devolver un error.



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

## <a name="version-2010-january-12"></a>Versión 2010: 12 de enero
*Versión 2010 (compilación 13328.20550)*

Las actualizaciones de seguridad se enumeran [aquí](./microsoft365-apps-security-updates.md)



[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO FINAL)

[//]: # (NO QUITAR FINAL)

> [!NOTE]
> Si necesita ayuda con algún problema de uso de Office, le recomendamos que publique la pregunta en el [foro de preguntas de Microsoft](https://answers.microsoft.com/) o [Tech Community](https://techcommunity.microsoft.com/), o bien puede ponerse en contacto con el [servicio de soporte técnico](https://support.microsoft.com/contactus).


[//]: # (NO MODIFICAR EL INICIO DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)
[//]: # (|Win32|MEC|Production|Feature|16.0.14026.20334|version-2105-july-13|)
[//]: # (|Win32|MEC|Producción|Característica|16.0.13929.20408|version-2104-junio-08|)
[//]: # (|Win32|MEC|Producción|Característica|16.0.13901.20516|version-11-marzo-2103|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13801.20506|versión-2102-13-abril|)
[//]: # (|Win32|MEC|Producción|Característica|16.0.13628.20528|version-2101-marzo-09|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13530.20528|version-2012-february-09|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13426.20526|version-2011-january-12|)
[//]: # (|Win32|MEC|Producción|Característica|16.0.13328.20478|versión-08-diciembre-2010|)
[//]: # (|Win32|MEC|Producción|Característica|16.0.13231.20514|versión-10-noviembre-2009|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13127.20638|versión-13-octubre-2008|)
[//]: # (NO MODIFICAR EL FIN DE CONTENIDO DE METADATOS DEL CENTRO DE ADMINISTRACIÓN)
