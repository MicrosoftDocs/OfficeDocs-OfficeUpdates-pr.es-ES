---
title: Notas de la versión para las versiones de canal mensual en 2015
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 12/11/2015
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Normal
ms.collection: RelNotes_ProPlus
description: Proporciona a que los profesionales de TI con notas de la versión para canal mensual libera para Office 365 ProPlus en 2015
ms.openlocfilehash: 0b235ba177dd2378cbb953315e2ead6b692ed52b
ms.sourcegitcommit: 5dabd0a6045b54940da7821e2349ec78b6b99d00
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/04/2018
ms.locfileid: "19556398"
---
# <a name="release-notes-for-monthly-channel-releases-in-2015"></a>Notas de la versión para las versiones de canal mensual en 2015

Estas notas de la versión proporcionan información sobre nuevas características, actualizaciones de seguridad y las actualizaciones de seguridad comunes que se incluyen en las actualizaciones de canal mensual a Office 365 ProPlus en 2015.
 
> [!NOTE]
> - El siguiente también proporciona la información acerca de las nuevas características, actualizaciones de seguridad y las actualizaciones de seguridad que no sean para Visio Pro a para el cliente de escritorio de Project Online y Office 365.
> - Esta información también se aplica a Office 365 empresarial, que es la versión de Office que se incluye con algunos planes de Office 365, como Business Premium.
> - Canal mensual se ha denominado canal actual antes de septiembre de 2017.

## <a name="version-1511-december-11"></a>Versión 1511: 11 de diciembre
*Versión 1511 (compilación 6366.2036)*

### <a name="excel-feature-updates"></a>Excel: Actualizaciones de la característica
-   **Plantillas de inteligencia empresarial:** Tres nuevas plantillas que aprovechar de la inteligencia empresarial (BI) capacidades de Excel: [Entendimiento de calendario](https://support.office.com/article/7edbeb88-99ca-403f-a394-7e957d3d3f40), [Análisis de Stock](https://support.office.com/article/f65e62ac-7af6-4cc6-98f3-f68b147ed65d), [Mi flujo de efectivo](https://support.office.com/article/215e9e2e-5813-41ad-a9ef-a0c0874841bb)

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones de seguridad que no sean
-   Corregir un problema donde arrastrando el controlador de relleno de una celda que se ha dado formateada con un número como una fecha larga, Excel se bloquea.
-   Corregir un problema donde la creación de una conexión de datos de una tabla dinámica o gráfico dinámico y se coloca en una nueva hoja las causas Excel se bloquea.
-   Corregir un problema donde los botones de filtro para un gráfico dinámico no están visibles cuando no hay ningún filtrado en los campos de tabla dinámica subyacentes.
-   Corregir un problema donde el modelo de datos se pierde cuando se cierra Excel antes de guardar cuando hay un libro oculto de macros personal.
-   Corregir un problema donde hace que una hoja de cálculo con un gráfico de treemap en una versión anterior de Excel 2016 de edición que se creó en el gráfico de treemap perder sus datos.

### <a name="onenote-feature-updates"></a>OneNote: Actualizaciones de la característica
-   **Insertar vídeos en línea:** Incrustar vídeos de YouTube, OfficeMix o Vimeo en una página. [Obtener más información](https://support.office.com/article/0a862f29-665c-43a5-9dd8-68009423cf7c)

### <a name="onenote-non-security-updates"></a>OneNote: Actualizaciones de seguridad que no sean
-   Corregir un problema con Office 365 empresarial, donde intenta usar OneNote con SharePoint da como resultado un mensaje de error que indica a los usuarios que tienen para actualizar a una versión diferente de Office.

### <a name="outlook-feature-updates"></a>Outlook: Actualizaciones de la característica
-   **Calendario persa:** Agregue el calendario persa como un calendario principal o alternativo.

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones de seguridad y comunes
-   Corregir un problema donde arrastre la barra de desplazamiento en la lista de mensajes hace que la lista saltar al final de la lista.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Actualizaciones de la característica
-   **Orienta transición:** Cree una transición sin problemas entre las diapositivas y hacer que el movimiento a las presentaciones para transmitir más eficazmente conceptos y la información. [Obtener más información](https://support.office.com/article/8dd1c7b2-b935-44f5-a74c-741d8d9244ea)
-   **Diseñador de PowerPoint:** Un nuevo servicio que le permite tomar el contenido y generar automáticamente una variedad de ideas que puede elegir para hacer las diapositivas un aspecto mejor. [Obtener más información](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

    Este servicio requiere conectividad a Internet. Para deshabilitar esta característica, [Utilice los últimos archivos de plantilla administrativa de directiva de grupo](https://www.microsoft.com/download/details.aspx?id=49030) y habilitar a la configuración de opciones del Diseñador de PowerPoint. Puede encontrar esta configuración de directiva bajo Configuración de usuario\\plantillas administrativas\\Microsoft Office 2016\\herramientas | Opciones | General | Opciones de servicio... \\El Diseñador de PowerPoint.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones de seguridad que no sean
-   Corregir un problema donde SmartArt con animaciones no se muestra en la secuencia esperada en la vista presentación con diapositivas con la vista del moderador.
-   Corregir un problema donde número navegación clave no funciona en la vista presentación con diapositivas.

### <a name="visio-non-security-updates"></a>Visio: Actualizaciones de seguridad y comunes
-   Corregir un problema donde los archivos de AutoCAD verlos en Visio se ve borroso.

### <a name="word-non-security-updates"></a>Word: Actualizaciones de seguridad que no sean
-   Corregir un problema donde no se pueden guardar documentos en una biblioteca de documentos que tiene una columna necesaria.

### <a name="office-suite-feature-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de la característica
-   **Enviar como opciones**: enviar un documento como datos adjuntos o como un archivo PDF desde el panel de recurso compartido en Word o PowerPoint.
-   **Insertar imagen API**: insertar imágenes en Word, Excel o PowerPoint mediante el [método document.setSelectedDataAsync](https://msdn.microsoft.com/library/office/fp142145.aspx) en la biblioteca de office.js común. La API de JavaScript de Word proporciona métodos específicos del host llamados insertInlinePictureFromBase64() para establecer las imágenes en línea en el [cuerpo](https://msdn.microsoft.com/library/office/mt598674.aspx), [ContentControl](https://msdn.microsoft.com/library/office/mt598675.aspx), [párrafo](https://msdn.microsoft.com/library/office/mt598682.aspx)y objetos Range.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de seguridad comunes
-   Corregir un problema donde se trunca la información de fecha de modificación que se muestra cuando se realiza un abrir o guardar como.
-   Corregir un problema donde hace doble clic en el panel de texto para gráficos SmartArt que la aplicación se bloquee.
-   Corregir un problema donde el vídeo que se reproduce durante la instalación permanece en una pantalla negra después de que finalice y hasta que se cierre el cuadro de diálogo "Instalación finalizada".
-   Corregir un problema que hace que la notificación para ser oscurecida por un botón de desplazamiento muy amplia al mover el mouse sobre la notificación de "Vista protegida" en un documento protegido.
-   Corregir un problema donde la notificación de que se ha programado una actualización de Office se trunca en Kazajo y húngaro.
-   Corregir un problema donde no se eliminan los accesos directos agregados en la barra de tareas para todos los usuarios durante una actualización manual.
-   Corregir un problema donde errores provocados por las acciones relacionadas con la concesión de licencias durante una actualización automática deja al usuario sin una instalación de Office.
-   Corregir un problema donde actualización a 2016 de Office en un equipo de Windows 7 OEM que tenía el Kit de preinstalación de Office se ejecute en modo auditoría da como resultado el error 0 x 80070005 durante la activación.


## <a name="version-1509-december-8"></a>Versión 1509: 8 de diciembre
*Versión 1509 (compilación 6001.1043)*

### <a name="onenote-non-security-updates"></a>OneNote: Actualizaciones de seguridad que no sean
-   Corregir un problema donde XPS o copias impresas creadas mediante el cliente de escritorio de Windows aparecen como una X roja en los clientes de escritorio que no son de Windows, debido a que estos clientes no admiten XPS nativo representación.

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones de seguridad y comunes
-   Corregir un problema que se crea un marcador que abarca varios párrafos, pero cuando se recibe el correo electrónico, se selecciona sólo el primer párrafo del marcador al usar ir a.

### <a name="skype-for-business-security-updates"></a>Skype para la empresa: actualizaciones de seguridad
-   Boletín de seguridad de Microsoft [MS15-128](https://go.microsoft.com/fwlink/?LinkId=690559): actualización de seguridad para el componente de gráficos de Microsoft a solucionar la ejecución remota de código (3104503)

### <a name="skype-for-business-non-security-updates"></a>Skype para la empresa: actualizaciones de seguridad comunes
-   Corregir un problema en los que no sesiones de uso compartido de aplicaciones, especialmente durante los períodos de tráfico ráfagas.
-   Corregir un problema que, Skype para la empresa se bloquea si es la primera aplicación para iniciarse después de instalar Office 2016.

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad
-   Boletín de seguridad de Microsoft [MS15 131](https://go.microsoft.com/fwlink/?LinkId=699410): actualización de seguridad para Microsoft Office para la ejecución remota de código (3116111) de direcciones

### <a name="word-non-security-updates"></a>Word: Actualizaciones de seguridad que no sean
-   Corregir un problema donde un guión de no separación se muestra como un cuadrado al utilizar algunas fuentes.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de seguridad comunes
-   Cambiar el transporte predeterminado para la descarga de las actualizaciones en segundo plano de caché/BITS para HTTP.
-   Corregir un problema donde errores provocados por las acciones relacionadas con la concesión de licencias durante una actualización automática deja al usuario sin una instalación de Office.
-   Corregir un problema donde actualización a 2016 de Office en un equipo de Windows 7 OEM que tenía el Kit de preinstalación de Office se ejecute en modo auditoría da como resultado el error 0 x 80070005 durante la activación.



## <a name="version-1509-november-10"></a>Versión 1509: 10 de noviembre
*Versión 1509 (compilación 6001.1038)*

### <a name="access-security-updates"></a>Acceso: Actualizaciones de seguridad
-   Boletín de seguridad de Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): actualización de seguridad para Microsoft Office para la ejecución remota de código (3104540) de direcciones

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   Boletín de seguridad de Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): actualización de seguridad para Microsoft Office para la ejecución remota de código (3104540) de direcciones

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones de seguridad que no sean
-   Corregir un problema donde grabar una macro para la creación de una consulta da como resultado un error de compilación.
-   Corregir un problema que, después de eliminar una columna en el Editor de consultas, una columna en blanco aparece al final de la tabla después de actualizar la consulta.
-   Corregir un problema que se produce un error inesperado al elegir la ficha minigráficos en análisis rápido de una tabla de consulta.
-   Corregir un problema donde, después de realizar un corte y pegue la operación en una tabla de consulta, no se puede actualizar la consulta mediante el panel de consultas del libro.
-   Corrección de un problema que, al actualizar una consulta, el foco se mueve a la hoja de su tabla de consulta asociada.
-   Quite la referencia a Power consulta desde el mensaje de error sobre las versiones admitidas de OData.
-   Corregir un problema donde las características de consulta de Power aparecen como disponibles, pero no funcionan cuando todavía no se ha activado el producto.
-   Actualice la dirección URL para Dotlesscss en el archivo \> cuenta \> acerca de Excel.

### <a name="onenote-security-updates"></a>OneNote: Actualizaciones de seguridad
-   Boletín de seguridad de Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): actualización de seguridad para Microsoft Office para la ejecución remota de código (3104540) de direcciones

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones de seguridad y comunes
-   Corregir un problema donde pegar texto en Outlook no muestra el texto completo si es mayor que el alto de la ventana de la cantidad de texto pegado.

### <a name="powerpoint-security-updates"></a>PowerPoint: Actualizaciones de seguridad
-   Boletín de seguridad de Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): actualización de seguridad para Microsoft Office para la ejecución remota de código (3104540) de direcciones

### <a name="project-security-updates"></a>Project: Actualizaciones de seguridad
-   Boletín de seguridad de Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): actualización de seguridad para Microsoft Office para la ejecución remota de código (3104540) de direcciones

### <a name="publisher-security-updates"></a>Publisher: Actualizaciones de seguridad
-   Boletín de seguridad de Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): actualización de seguridad para Microsoft Office para la ejecución remota de código (3104540) de direcciones

### <a name="skype-for-business-security-updates"></a>Skype para la empresa: actualizaciones de seguridad
-   Boletín de seguridad de Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): actualización de seguridad para Microsoft Office para la ejecución remota de código (3104540) de direcciones
-   Boletín de seguridad de Microsoft [MS15-123](https://technet.microsoft.com/library/security/ms15-123): actualización de seguridad para Skype para empresas y Microsoft Lync a solucionar la divulgación de información (3105872)

### <a name="skype-for-business-non-security-updates"></a>Skype para la empresa: actualizaciones de seguridad comunes
-   Corregir un problema con el ruido de audio en los dispositivos que tienen dos micrófonos de entrada.
-   Corregir un problema donde los usuarios no se pueden unir correctamente una reunión después de reanudar un equipo portátil del modo de suspensión y antes de Skype ha iniciado sesión en el cliente.
-   Agregar compatibilidad para mensajes contextuales ayudar a proporcionar el conocimiento de las características a los usuarios.
-   Actualizar el texto en el cuadro de diálogo unirse a Audio de la reunión para dirigir a los usuarios a la ubicación correcta en la interfaz de usuario para cambiar la configuración.
-   Corregir un problema con las notificaciones de que los usuarios vea experimentar con ambos al enviar y reciben los problemas de red.

### <a name="visio-security-updates"></a>Visio: Actualizaciones de seguridad
-   Boletín de seguridad de Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): actualización de seguridad para Microsoft Office para la ejecución remota de código (3104540) de direcciones

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad
-   Boletín de seguridad de Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): actualización de seguridad para Microsoft Office para la ejecución remota de código (3104540) de direcciones

### <a name="word-non-security-updates"></a>Word: Actualizaciones de seguridad que no sean
-   Corregir un problema donde la numeración de nota al pie no coincide con entre la presentación en Word y al imprimir cuando se imprime un documento que tiene notas al pie establecidos en "Reiniciar numeración cada página" en segundo plano.
-   Corregir un problema donde co-autoría en tiempo real no funciona con archivos almacenados en OneDrive, incluido el usuario no se muestre a otros usuarios como edición en tiempo real y no hay información de presencia disponible.
-   Corregir un problema que Word produce un error durante la co-autoría en tiempo real en un documento abierto desde SharePoint o OneDrive.
-   Corrección de correos electrónicos de un problema de formato que hace que las tablas representar incorrectamente cuando se colocan en HTML en Outlook y la ventana se cambia el tamaño.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de seguridad
-   Boletín de seguridad de Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): actualización de seguridad para Microsoft Office para la ejecución remota de código (3104540) de direcciones

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de seguridad comunes
-   Corregir un problema donde se pide repetidamente el usuario para iniciar sesión cuando intenta abrir los archivos desde SharePoint Online.
-   Corregir un problema donde no se eliminan los accesos directos agregados en la barra de tareas para todos los usuarios durante una actualización manual.
-   Agregar la capacidad para el proceso de actualización manual de Click-to-Run detectar si Outlook está conectado a Exchange Server 2007 o si está instalado Business Contact Manager para advertir a los usuarios de posibles problemas con la actualización.
-   Asegúrese de cuadros de diálogo para finalizar los procesos más visibles durante la desinstalación o actualización debido a que estos cuadros de diálogo pueden obtener oculta al usuario detrás de aplicaciones open u otro la interfaz de usuario.
-   Corregir un problema donde un usuario no obtener iniciado sesión en una aplicación de Office automáticamente cuando se usa un equipo que se identifica como que se unen a un dominio y un dominio en la nube.



## <a name="version-1509-october-21"></a>Versión 1509: 21 de octubre
*Versión 1509 (compilación 6001.1034)*

### <a name="onenote-non-security-updates"></a>OneNote: Actualizaciones de seguridad que no sean
-   Corregir un problema que hace que OneNote se bloquee cuando se selecciona el mismo color de borde de dos veces en el selector de color.

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones de seguridad y comunes
-   Corregir un problema donde un lector de pantalla sólo lee el primer párrafo de una firma de correo electrónico de varios párrafo cuando se edita la firma de correo electrónico.
-   Corregir un problema donde el cursor no está en la posición correcta al escribir o responder a un correo electrónico.

### <a name="skype-for-business-non-security-updates"></a>Skype para la empresa: actualizaciones de seguridad comunes
-   Corregir un problema where, en condiciones de poca memoria, intenta ver un escritorio compartido o aplicación da como resultado desconexión e intentos repetidos de volver a unirse automáticamente y ver el escritorio compartido o la aplicación.
-   Corregir un problema donde, como aumenta el número de participantes, la experiencia de escritorio compartida obtiene peor.
-   Corregir un problema, cuando se configura la autenticación multifactor, donde se reciben mensajes repetidos para la autenticación de teléfono a lo largo del día.

### <a name="visio-non-security-updates"></a>Visio: Actualizaciones de seguridad y comunes
-   Corregir un problema donde un objeto de Word insertado para mostrar como un icono está vacío después de cerrar y volver a abrir Visio.

### <a name="word-non-security-updates"></a>Word: Actualizaciones de seguridad que no sean
-   Corregir un problema donde la co-autoría no está disponible y puede obtener bloqueado el documento cuando el documento está en SharePoint Server 2013.
-   Corregir un problema en los documentos de docx, donde table es visible, aunque en la tabla de contenido tiene que se ha aplicado un estilo que incluye la opción oculto.
-   Corregir un problema donde no se pueden guardar documentos con hipervínculos relativos después de realizar una corrección automática.
-   Corregir un problema donde Saltar líneas por durante la edición de un párrafo en un documento con una sangría de reflejo.
-   Corregir un problema donde para mostrar de la línea es incoherente durante la edición cuando está deshabilitado el posicionamiento de subpíxeles.
-   Corregir un problema donde hacer clic en una ventana emergente de comentario con varios comentarios donde el primero de ellos se marca como hecho causa un bloqueo.
-   Corregir un problema con el salto de línea incorrecto.
-   Corregir un problema donde se ejecuta una macro que usa la función TransformDocument en un documento con un cuadro de texto de un encabezado o un pie de página causa un bloqueo.
-   Corregir un problema con documentos .docm donde quitar todos los controles ActiveX hace que los errores cuando se abre el documento.
-   Corregir un problema donde ContentControlOnExit (evento) no se desencadena al hacer clic en un encabezado.
-   Corregir un problema donde el control de cambios muestra eliminaciones para revisores con el mismo nombre.
-   Corrección de un problema con la co-autoría en tiempo real de los documentos configurados para quitar información personal donde los cambios mostrar como marcas de cada documento de tiempo se guarda.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de seguridad comunes
-   Corregir un problema donde la primera vez que se abre una aplicación de Office después de actualizar a 2016 da como resultado la aplicación que se está en modo de funcionalidad reducida y requiere la aplicación a reiniciarse para obtener la funcionalidad completa.
-   Corregir un problema donde la ejecución de Office con shared activación del equipo habilitada en un equipo que ejecuta los resultados de servicios de escritorio remoto en un error al abrir una aplicación, que indica al usuario que necesitan usar una edición de licencia por volumen de Office.
-   Corregir un problema donde se bloquea la instalación en alrededor del 90% completado.
-   Corregir un problema donde los nombres de producto están localizados cuando deberían.
-   Corregir un problema donde la información sobre herramientas y la información para indicar a personal"" no coinciden con y entre en conflicto con otras sugerencias de teclas en la cinta de opciones en diversas versiones localizadas.
-   Corregir un problema donde Windows es que muestra Outlook como una aplicación nueva después de una actualización de Office 2013 a Office 2016.
-   Corregir un problema donde la actualización a Office 2016 desde Office 2013 versión 15.0.4615.1002 (mayo de 2014) da como resultado un error de 0x80041015.



## <a name="version-1509-october-5"></a>Versión 1509: 5 de octubre
*Versión 1509 (compilación 4229.1029)*

### <a name="onenote-non-security-updates"></a>OneNote: Actualizaciones de seguridad que no sean
-   Corregir un problema con Office 365 empresarial, donde intenta usar OneNote con SharePoint da como resultado un mensaje de error que indica a los usuarios que tienen para actualizar a una versión diferente de Office.
-   Corregir un problema para Surface Pro 3 donde vista previa de la grabación de vídeo no muestran lo que se está grabando.

### <a name="skype-for-business-non-security-updates"></a>Skype para la empresa: actualizaciones de seguridad comunes
-   Cambiar lo que un visor ve cuando la persona que comparte bloquea la pantalla en RDP. Visor de ahora se muestra una notificación, en lugar de la imagen de pausa RDP.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de seguridad comunes
-   Solucionar un problema de Click-to-Run donde no se restaura el servicio de Office 2013 Click-to-Run si no se completa la actualización automática para Office 2016 debido a una error o cancelación de usuario.
-   Corregir un problemas de Click-to-Run donde un error durante la actualización automática para Office 2016 da como resultado un error de actualización y no ser capaz de usar o desinstalar las aplicaciones de Office 2013.
-   Corrección de un problema de Click-to-Run donde volver a intentar la actualización automática para Office 2016 después de reiniciar durante una anterior intenta actualizar da lugar a un error en la actualización y la imposibilidad de apagar.
-   Solucionar un problema de Click-to-Run donde la tarea de secuencia durante la instalación no puede recuperar correctamente si se reinicia el equipo.
-   Solucionar un problema de Click-to-Run donde reiniciar durante una actualización manual a Office 2016 sale de tareas en un estado de "ejecución".
-   Solucionar un problema de Click-to-Run donde el proceso de inicio de una aplicación recién instalada durante la mitad de la instalación de los resultados en un cuadro de diálogo "Perdido la conexión a Internet" que aparece.
-   Solucionar un problema de Click-to-Run donde los mosaicos de aplicación que se muestra durante la instalación no están activas y no inicien la aplicación cuando los usuarios que hace clic en el icono de la aplicación.
-   Solucionar un problema de Click-to-Run donde el auto-actualizar una instalación de sr-latn-cr a Office 2016 no convierte a sr-latn-rs el idioma del cliente.
-   Solucionar un problema de Click-to-Run donde la actualización automática se produce un error durante la preparación de la actualización cuando hay varios SKU de Office instalado en el equipo.
-   Solucionar un problema de Click-to-Run donde los cuadros de diálogo de error aparecen si se ha iniciado una actualización manual mientras se ejecuta una actualización automática.
-   Actualice las referencias a "Add-ins" en el producto de la interfaz de usuario donde el uso de mayúsculas del término es incorrecta.



## <a name="version-1509-september-22"></a>Versión 1509: 22 de septiembre
*Versión 1509 (compilación 4229.1024)*

Esta es la versión inicial para este canal. Esta versión proporciona la primera disponibilidad de las aplicaciones de Office 2016.

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   Boletín de seguridad de Microsoft [MS15-099](https://technet.microsoft.com/library/security/ms15-099): vulnerabilidades en Microsoft Office podrían permitir la ejecución remota de código (3089664)
-   Boletín de seguridad de Microsoft [MS15-110](https://technet.microsoft.com/library/security/ms15-110): actualizaciones de seguridad de Office de Microsoft a solucionar remoto de código de ejecución (3096440)

### <a name="visio-security-updates"></a>Visio: Actualizaciones de seguridad
-   Boletín de seguridad de Microsoft [MS15-081](https://technet.microsoft.com/library/security/ms15-081): vulnerabilidades en Microsoft Office podrían permitir la ejecución remota de código (3080790)

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad
-   Boletín de seguridad de Microsoft [MS15-081](https://technet.microsoft.com/library/security/ms15-081): vulnerabilidades en Microsoft Office podrían permitir la ejecución remota de código (3080790)

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: actualizaciones de seguridad
-   Boletín de seguridad de Microsoft [MS15-081](https://technet.microsoft.com/library/security/ms15-081): vulnerabilidades en Microsoft Office podrían permitir la ejecución remota de código (3080790)
-   Boletín de seguridad de Microsoft [MS15-099](https://technet.microsoft.com/library/security/ms15-099): vulnerabilidades en Microsoft Office podrían permitir la ejecución remota de código (3089664)
