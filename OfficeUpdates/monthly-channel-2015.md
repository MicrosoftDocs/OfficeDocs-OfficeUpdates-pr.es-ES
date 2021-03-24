---
title: Notas de la versión de las versiones mensuales del canal en 2015
ms.author: anankani
author: andymosten
manager: anankani
ms.date: 12/11/2015
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Normal
ms.collection: RelNotes_ProPlus
description: Proporciona a los profesionales de TI notas de la versión de las versiones mensuales del canal para Office 365 ProPlus en 2015
ms.openlocfilehash: 21afefcf714dcdd67d193b74b2e9f7d69f64c0c9
ms.sourcegitcommit: 04f3aa30703f4f1cf89721853a7c052fcca2b97f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2021
ms.locfileid: "51169889"
---
# <a name="release-notes-for-monthly-channel-releases-in-2015"></a>Notas de la versión de las versiones mensuales del canal en 2015

Estas notas de la versión proporcionan información sobre las nuevas características, las actualizaciones de seguridad y las actualizaciones que no son de seguridad que se incluyen en las actualizaciones mensuales del canal de Office 365 ProPlus en 2015.
 
> [!NOTE]
> - Lo siguiente también proporciona información sobre características nuevas, actualizaciones de seguridad y no relacionadas con la seguridad para Visio Pro para Office 365 y el cliente de escritorio de Project Online.
> - Esta información también se aplica a Office 365 Empresa, que es la versión de Office que viene con algunos planes de Office 365, como Empresa Premium.
> - El canal mensual se denominaba Canal actual antes de septiembre de 2017.

## <a name="version-1511-december-11"></a>Versión 1511: 11 de diciembre
*Versión 1511 (compilación 6366.2036)*

### <a name="excel-feature-updates"></a>Excel: Actualizaciones de características
-   **Plantillas de BI:** Tres nuevas plantillas que aprovechan las capacidades de inteligencia empresarial (BI) de Excel: [Calendar Insights](https://support.office.com/article/7edbeb88-99ca-403f-a394-7e957d3d3f40), [Stock Analysis](https://support.office.com/article/f65e62ac-7af6-4cc6-98f3-f68b147ed65d), [My Cashflow](https://support.office.com/article/215e9e2e-5813-41ad-a9ef-a0c0874841bb)

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que, al arrastrar un controlador de relleno de una celda con formato de número como una fecha larga, hace que Excel se bloquee.
-   Se soluciona un problema en el que, al crear una tabla dinámica o un gráfico dinámico a partir de una conexión de datos y colocarla en una nueva hoja, hace que Excel se bloquee.
-   Se soluciona un problema en el que los botones de filtro de un gráfico dinámico no son visibles si no se han filtrado los campos de la tabla dinámica subyacente.
-   Se soluciona un problema en el que, si se cierra Excel antes de guardar un modelo de datos, se pierde el modelo de datos si hay un libro con una macro personal oculta.
-   Se soluciona un problema en el que, al editar una hoja de cálculo con un gráfico de rectángulos en una versión de Excel 2016 anterior a la versión con la que se creó, hace que el gráfico de rectángulos pierda los datos.

### <a name="onenote-feature-updates"></a>OneNote: Actualizaciones de características
-   **Insertar vídeos en línea:** inserte vídeos de YouTube, Office Mix o Vimeo en una página. [Más información](https://support.office.com/article/0a862f29-665c-43a5-9dd8-68009423cf7c)

### <a name="onenote-non-security-updates"></a>OneNote: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema con Office 365 Empresa en el que, cuando se intenta usar OneNote con SharePoint, se recibe un mensaje de error que indica a los usuarios que tienen que actualizar a una versión diferente de Office.

### <a name="outlook-feature-updates"></a>Outlook: Actualizaciones de características
-   **Calendario persa:** agregue el calendario persa como un calendario principal o alternativo.

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que, al arrastrar la barra de desplazamiento en una lista de mensajes, la lista salta al final de esta.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Actualizaciones de características
-   **Transición de transformación:** cree transiciones perfectas entre diapositivas e incluya movimiento en las presentaciones para transmitir con mayor eficacia conceptos e información. [Más información](https://support.office.com/article/8dd1c7b2-b935-44f5-a74c-741d8d9244ea)
-   **Diseñador de PowerPoint:** un nuevo servicio que le permite usar su contenido para generar automáticamente una amplia variedad de ideas entre las que puede elegir para mejorar la apariencia de sus diapositivas. [Más información](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

    Para usar este servicio se necesita conectividad a Internet. Para deshabilitar esta característica, use los archivos de plantilla administrativa de [directiva de grupo](https://www.microsoft.com/download/details.aspx?id=49030) más recientes y habilite la configuración opciones de PowerPoint Designer. Encontrará esta configuración de directiva en Configuración de usuario\\Plantillas administrativas\\Microsoft Office 2016\\Herramientas | Opciones | General | Opciones de servicios...\\Diseñador de PowerPoint.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que los elementos gráficos SmartArt con animaciones no se muestran en la secuencia esperada en la vista de presentación con la vista Moderador.
-   Se soluciona un problema en el que la navegación con las teclas numéricas no funciona en la vista de presentación.

### <a name="visio-non-security-updates"></a>Visio: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que los archivos de AutoCAD visualizados en Visio se muestran borrosos.

### <a name="word-non-security-updates"></a>Word: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que los documentos no se pueden guardar en una biblioteca de documentos que tiene una columna obligatoria.

### <a name="office-suite-feature-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de características
-   **Opciones de Enviar como**: envíe un documento como datos adjuntos o como un archivo PDF desde el panel Compartir en Word o en PowerPoint.
-   **API de Insertar imagen**: Inserte imágenes en Word, Excel o PowerPoint con el [método document.setSelectedDataAsync](/javascript/api/office/office.document) en la biblioteca office.js. La API de JavaScript de Word proporciona métodos específicos del host denominados insertInlinePictureFromBase64() para establecer imágenes en línea en los objetos [Body](/office/dev/add-ins/reference/overview/word-add-ins-reference-overview), [ContentControl](/javascript/api/word/word.contentcontrol), [Paragraph](/javascript/api/word/word.paragraph)y Range.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que se muestra truncada la información de Fecha de modificación que aparece al realizar una operación de Abrir o Guardar como.
-   Se soluciona un problema en el que, al hacer doble clic en el panel Texto para elementos gráficos SmartArt, hace que la aplicación se bloquee.
-   Se soluciona un problema en el que el vídeo que se reproduce durante la instalación permanece en una pantalla negra después de terminar y hasta que se cierra el diálogo "La instalación ha finalizado".
-   Se soluciona un problema en el que, al desplazar el mouse sobre la notificación de "Vista protegida" en un documento protegido, hace que la notificación se oscurezca por un botón de desplazamiento muy ancho.
-   Se soluciona un problema en el que la notificación de una actualización de Office programada aparece truncada en kazajo y en húngaro.
-   Se soluciona un problema en el que los accesos directos anclados en la barra de tareas no se quitan para todos los usuarios durante una actualización manual.
-   Se soluciona un problema en el que los errores causados por acciones relacionadas con licencias durante una actualización automática dejan al usuario sin una instalación de Office.
-   Se soluciona un problema en el que, al actualizar a Office 2016 en un equipo con Windows 7 OEM donde se ejecutaba el Kit de preinstalación de Office en el modo auditoría, se produce el error 0x80070005 durante la activación.


## <a name="version-1509-december-8"></a>Versión 1509: 8 de diciembre
*Versión 1509 (compilación 6001.1043)*

### <a name="onenote-non-security-updates"></a>OneNote: actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que los documentos XPS o las copias impresas creadas con el cliente de escritorio de Windows aparecen como una X roja en clientes de escritorio distintos de Windows, ya que esos clientes no son compatibles con la representación de XPS nativa.

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que, si se crea un marcador que abarca varios párrafos, cuando se recibe el correo electrónico solo se selecciona el primer párrafo del marcador al usar la función Ir a.

### <a name="skype-for-business-security-updates"></a>Skype Empresarial: Actualizaciones de seguridad
-   Boletín de seguridad Microsoft [MS15-128](/security-updates/SecurityBulletins/2015/ms15-128): Actualización de seguridad para componente de gráficos de Microsoft para solucionar la ejecución remota de código (3104503)

### <a name="skype-for-business-non-security-updates"></a>Skype Empresarial: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que las sesiones de uso compartido de aplicaciones producen errores, especialmente durante períodos de picos de tráfico elevado.
-   Se soluciona un problema que causa que Skype Empresarial se bloquee si es la primera aplicación en iniciarse después de instalar Office 2016.

### <a name="word-security-updates"></a>Word: Actualizaciones de seguridad
-   Boletín de seguridad Microsoft [MS15-131](/security-updates/SecurityBulletins/2015/ms15-131): actualizaciones de seguridad de Microsoft Office para solucionar la ejecución remota de código (3116111)

### <a name="word-non-security-updates"></a>Word: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que un guión de no separación se muestra como un cuadrado al usar determinadas fuentes.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad
-   Se cambia el transporte predeterminado para descargar actualizaciones en segundo plano de almacenamiento en caché/BITS a HTTP.
-   Se soluciona un problema en el que los errores causados por acciones relacionadas con licencias durante una actualización automática dejan al usuario sin una instalación de Office.
-   Se soluciona un problema en el que, al actualizar a Office 2016 en un equipo con Windows 7 OEM donde se ejecutaba el Kit de preinstalación de Office en el modo auditoría, se produce el error 0x80070005 durante la activación.



## <a name="version-1509-november-10"></a>Versión 1509: 10 de noviembre
*Versión 1509 (compilación 6001.1038)*

### <a name="access-security-updates"></a>Access: Actualizaciones de seguridad
-   Boletín de seguridad Microsoft [MS15-116](/security-updates/SecurityBulletins/2015/ms15-116): actualizaciones de seguridad de Microsoft Office para solucionar la ejecución remota de código (3104540)

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   Boletín de seguridad Microsoft [MS15-116](/security-updates/SecurityBulletins/2015/ms15-116): actualizaciones de seguridad de Microsoft Office para solucionar la ejecución remota de código (3104540)

### <a name="excel-non-security-updates"></a>Excel: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que, al grabar una macro para la creación de consultas, se produce un error de compilación.
-   Se soluciona un problema en el que, después de eliminar una columna en el Editor de consultas, aparece una columna en blanco al final de la tabla después de actualizar la consulta.
-   Se soluciona un problema en el que se produce un error inesperado al elegir la pestaña Minigráficos en Análisis rápido de una tabla de consulta.
-   Se soluciona un problema en el que, tras realizar una operación de cortar y pegar en una tabla de consulta, no se puede actualizar la consulta mediante el panel Consultas del libro.
-   Se soluciona un problema en el que al actualizar una consulta, el foco se mueve a la hoja de su tabla de consulta asociada.
-   Se quita la referencia a Power Query desde el mensaje de error sobre las versiones compatibles de OData.
-   Se soluciona un problema en el que las características de Power Query aparecen como disponibles, pero no funcionan cuando no se activó el producto.
-   Se actualiza la dirección URL para Dotlesscss en Archivo \> Cuenta \> Acerca de Excel.

### <a name="onenote-security-updates"></a>OneNote: Actualizaciones de seguridad
-   Boletín de seguridad Microsoft [MS15-116](/security-updates/SecurityBulletins/2015/ms15-116): actualizaciones de seguridad de Microsoft Office para solucionar la ejecución remota de código (3104540)

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que, al pegar texto en Outlook, no se muestra el texto completo si la cantidad de texto pegado es mayor que la altura de la ventana.

### <a name="powerpoint-security-updates"></a>PowerPoint: Actualizaciones de seguridad
-   Boletín de seguridad Microsoft [MS15-116](/security-updates/SecurityBulletins/2015/ms15-116): actualizaciones de seguridad de Microsoft Office para solucionar la ejecución remota de código (3104540)

### <a name="project-security-updates"></a>Project: actualizaciones de seguridad
-   Boletín de seguridad Microsoft [MS15-116](/security-updates/SecurityBulletins/2015/ms15-116): actualizaciones de seguridad de Microsoft Office para solucionar la ejecución remota de código (3104540)

### <a name="publisher-security-updates"></a>Publisher: Actualizaciones de seguridad
-   Boletín de seguridad Microsoft [MS15-116](/security-updates/SecurityBulletins/2015/ms15-116): actualizaciones de seguridad de Microsoft Office para solucionar la ejecución remota de código (3104540)

### <a name="skype-for-business-security-updates"></a>Skype Empresarial: Actualizaciones de seguridad
-   Boletín de seguridad Microsoft [MS15-116](/security-updates/SecurityBulletins/2015/ms15-116): actualizaciones de seguridad de Microsoft Office para solucionar la ejecución remota de código (3104540)
-   Boletín de seguridad Microsoft [MS15-123](/security-updates/SecurityBulletins/2015/ms15-123): Actualización de seguridad de Skype Empresarial y Microsoft Lync para abordar la divulgación de información (3105872)

### <a name="skype-for-business-non-security-updates"></a>Skype Empresarial: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema con el ruido de audio en los dispositivos que tienen dos micrófonos de entrada.
-   Se soluciona un problema en el que los usuarios no se pueden unir correctamente una reunión después de reanudar un equipo portátil en modo de suspensión y antes de que el cliente de Skype cliente vuelve a iniciar sesión.
-   Se agrega compatibilidad para mensajes contextuales para ayudar a advertir a los usuarios sobre las características.
-   Se actualiza el texto en el cuadro de diálogo Unirse al audio de la reunión para dirigir a los usuarios a la ubicación correcta en la interfaz de usuario para cambiar la configuración.
-   Se soluciona un problema con las notificaciones que los usuarios ven cuando se topan con problemas de envío y recepción de red.

### <a name="visio-security-updates"></a>Visio: Actualizaciones de seguridad
-   Boletín de seguridad Microsoft [MS15-116](/security-updates/SecurityBulletins/2015/ms15-116): actualizaciones de seguridad de Microsoft Office para solucionar la ejecución remota de código (3104540)

### <a name="word-security-updates"></a>Word: actualizaciones de seguridad
-   Boletín de seguridad Microsoft [MS15-116](/security-updates/SecurityBulletins/2015/ms15-116): actualizaciones de seguridad de Microsoft Office para solucionar la ejecución remota de código (3104540)

### <a name="word-non-security-updates"></a>Word: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que la numeración de notas al pie no coincide entre la presentación en Word y la impresión cuando un documento en el que las notas al pie se establecen en "Reiniciar numeración en cada página" se imprime en segundo plano.
-   Se soluciona un problema en el que la co-autoría en tiempo real no funciona con los archivos almacenados en OneDrive, como cuando el usuario no aparece para los demás mientras edita en tiempo real y no hay información de presencia disponible.
-   Se soluciona un problema en el que Word se bloquea durante la co-autoría en tiempo real en un documento abierto desde SharePoint o OneDrive.
-   Se soluciona un problema de formato que hace que las tablas se representen incorrectamente cuando se colocan en mensajes de correo electrónico HTML en Outlook y se cambia el tamaño de la ventana.

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   Boletín de seguridad Microsoft [MS15-116](/security-updates/SecurityBulletins/2015/ms15-116): actualizaciones de seguridad de Microsoft Office para solucionar la ejecución remota de código (3104540)

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que se pide repetidamente al usuario iniciar sesión cuando intenta abrir archivos de SharePoint Online.
-   Se soluciona un problema en el que los accesos directos anclados en la barra de tareas no se quitan para todos los usuarios durante una actualización manual.
-   Se agrega la capacidad para que el proceso de actualización manual de Hacer clic y ejecutar detecte si Outlook está conectado a Exchange Server 2007 o si Business Contact Manager está instalado para advertir a los usuarios de posibles problemas con la actualización.
-   Los cuadros de diálogo para terminar procesos están más visibles durante una desinstalación o actualización, ya que estos cuadros de diálogo se pueden ocultar al usuario detrás de aplicaciones abiertas u otra interfaz de usuario.
-   Se soluciona un problema en el que un usuario no puede iniciar sesión automáticamente en una aplicación de Office si usa un equipo que se identifica como unido a un dominio y a un dominio en la nube.



## <a name="version-1509-october-21"></a>Versión 1509: 21 de octubre
*Versión 1509 (compilación 6001.1034)*

### <a name="onenote-non-security-updates"></a>OneNote: actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema por el que OneNote se bloquea cuando se selecciona dos veces el mismo color para un borde en el Selector de colores.

### <a name="outlook-non-security-updates"></a>Outlook: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que un lector de pantalla solo lee el primer párrafo de una firma de correo electrónico de varios párrafos al editar la firma de correo electrónico.
-   Se soluciona un problema en el que el cursor no se encuentra en la posición correcta al escribir o responder a un correo electrónico.

### <a name="skype-for-business-non-security-updates"></a>Skype Empresarial: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que, en condiciones de memoria insuficiente, al intentar visualizar un escritorio o una aplicación compartidos se produce la desconexión e intentos repetidos para volver a unirse automáticamente y ver el escritorio o la aplicación compartidos.
-   Se soluciona un problema en el que, a medida que aumenta el número de participantes, empeora la experiencia de escritorio compartido.
-   Se soluciona un problema por el que, cuando se configura la autenticación multifactor, se reciben varias solicitudes de autenticación por teléfono durante el día.

### <a name="visio-non-security-updates"></a>Visio: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que, si se inserta un objeto de Word para mostrarlo como un icono, el objeto queda vacío después de cerrar y volver a abrir Visio.

### <a name="word-non-security-updates"></a>Word: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que la coautoría no está disponible y el documento se puede quedar bloqueado si se encuentra en SharePoint Server 2013.
-   Se soluciona un problema en el que, en documentos docx, una tabla es visible aunque el contenido de la tabla tenga aplicado un estilo que incluya la opción Oculto.
-   Se soluciona un problema en el que los documentos con hipervínculos relativos no se pueden guardar después de ejecutar una autocorrección.
-   Se soluciona un problema en el que se saltan líneas al editar un párrafo en un documento con sangrías simétricas.
-   Se soluciona un problema en el que una línea se muestra de forma incoherente durante la edición si se deshabilita el posicionamiento de subpíxeles.
-   Se soluciona un problema en el que se produce un bloqueo al hacer clic en un comentario emergente con varios comentarios (donde el primero se ha marcado como Finalizado).
-   Se soluciona un problema que produce saltos de línea incorrectos.
-   Se soluciona un problema en el que se produce un bloqueo al ejecutar una macro que usa la función TransformDocument en un documento con un cuadro de texto en un encabezado o pie de página.
-   Se soluciona un problema en el que se producen errores con documentos .docm si se abre un documento después de quitar todos los controles ActiveX.
-   Se soluciona un problema en el que no se desencadena el evento ContentControlOnExit al hacer clic en un encabezado.
-   Se soluciona un problema en el que el control de cambios muestra eliminaciones de revisores con el mismo nombre.
-   Se soluciona un problema con la co-autoría de documentos en tiempo real configurada para quitar la información personal en el que los cambios se muestran como marcas de revisión cada vez que se guarda el documento.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema en el que, la primera vez que se abre una aplicación de Office después de actualizar a 2016, la aplicación se inicia en el modo de funcionalidad reducida y es necesario reiniciarla para obtener la funcionalidad completa.
-   Se soluciona un problema en el que, si se ejecuta Office con la activación en equipos compartidos habilitada en un equipo que ejecute Servicios de Escritorio remoto, al abrir la aplicación se muestra un error que indica al usuario que necesita usar una edición de licencia por volumen de Office.
-   Se soluciona un problema en el que la instalación se detiene cuando se ha completado aproximadamente el 90 %.
-   Se soluciona un problema en el que los nombres de producto se muestran adaptados de forma incorrecta.
-   Se soluciona un problema en el que la información sobre herramientas y KeyTip para "Información" no coinciden y entran en conflicto con otros KeyTip en la cinta en varias versiones localizadas.
-   Se soluciona un problema en el que Windows muestra Outlook como una nueva aplicación después de actualizar de Office 2013 a Office 2016.
-   Se soluciona un problema en el que, después de actualizar a Office 2016 desde Office 2013 versión 15.0.4615.1002 (mayo de 2014), se produce el error 0x80041015.



## <a name="version-1509-october-5"></a>Versión 1509: 5 de octubre
*Versión 1509 (compilación 4229.1029)*

### <a name="onenote-non-security-updates"></a>OneNote: actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema con Office 365 Empresa en el que, cuando se intenta usar OneNote con SharePoint, se recibe un mensaje de error que indica a los usuarios que tienen que actualizar a una versión diferente de Office.
-   Se soluciona un problema para Surface Pro 3 en el que la vista previa de grabación de vídeo no muestra lo que se está grabando.

### <a name="skype-for-business-non-security-updates"></a>Skype Empresarial: Actualizaciones no relacionadas con la seguridad
-   Se cambia lo que un ve un usuario cuando el archivo que comparte bloquea la pantalla en RDP. Ahora el usuario recibe una notificación, en lugar de la imagen de pausa RDP.

### <a name="office-suite-non-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones no relacionadas con la seguridad
-   Se soluciona un problema de Hacer clic y ejecutar en el que no se restaura el servicio de Hacer clic y ejecutar de Office 2013 si no se completa la actualización automática a Office 2016 debido a una error o cancelación del usuario.
-   Se soluciona un problema de Hacer clic y ejecutar en el que un error durante la actualización automática a Office 2016 produce una actualización errónea y hace que no se pueda usar o desinstalar las aplicaciones de Office 2013.
-   Se soluciona un problema de Hacer clic y ejecutar en el que cuando vuelve a intentar actualizar automáticamente a Office 2016 después de un reinicio durante un intento anterior para actualizar resulta en un error en la actualización y la imposibilidad de apagar.
-   Se soluciona un problema de Hacer clic y ejecutar donde la tarea de secuencia durante la instalación no es capaz de recuperarse correctamente si se reinicia el equipo.
-   Se soluciona un problema de Hacer clic y ejecutar en el que el reinicio durante una actualización manual a Office 2016 deja las tareas en un estado "en ejecución".
-   Se soluciona un problema de Hacer clic y ejecutar en el que, al iniciar una aplicación recién instalada durante el proceso de instalación, aparece el cuadro de diálogo "Se perdió la conexión a Internet".
-   Se soluciona un problema de Hacer clic y ejecutar en el que los iconos de la aplicación que se muestran durante la instalación no están activos y no inician la aplicación cuando los usuarios hacen clic en el icono de la aplicación.
-   Se soluciona un problema de Hacer clic y ejecutar en que al actualizar automáticamente una instalación de sr-latn-cr a Office 2016 no se convierte a sr-latn-rs el idioma del cliente.
-   Se soluciona un problema de Hacer clic y ejecutar en el que hay un error en la actualización automática mientras se prepara la actualización cuando hay varios SKU de Office instalados en el equipo.
-   Se soluciona un problema de Hacer clic y ejecutar en el que aparecen cuadros de diálogo de error si se inicia una actualización manual mientras se ejecuta una actualización automática.
-   Se actualizan las referencias de "Complementos" en la interfaz de usuario del producto donde las mayúsculas y minúsculas del término no son correctas.



## <a name="version-1509-september-22"></a>Versión 1509: 22 de septiembre
*Versión 1509 (compilación 4229.1024)*

Se trata de la versión inicial de este canal. Esta versión ofrece la primera disponibilidad de las aplicaciones de Office 2016.

### <a name="excel-security-updates"></a>Excel: Actualizaciones de seguridad
-   Boletín de seguridad Microsoft [MS15-099](/security-updates/SecurityBulletins/2015/ms15-099): Ciertas vulnerabilidades de Microsoft Office podrían permitir la ejecución remota de código (3089664)
-   Boletín de seguridad Microsoft [MS15-110](/security-updates/SecurityBulletins/2015/ms15-110): Actualizaciones de seguridad de Microsoft Office para solucionar la ejecución remota de código (3096440)

### <a name="visio-security-updates"></a>Visio: Actualizaciones de seguridad
-   Boletín de seguridad Microsoft [MS15-081](/security-updates/SecurityBulletins/2015/ms15-081): Ciertas vulnerabilidades de Microsoft Office podrían permitir la ejecución remota de código (3080790)

### <a name="word-security-updates"></a>Word: actualizaciones de seguridad
-   Boletín de seguridad Microsoft [MS15-081](/security-updates/SecurityBulletins/2015/ms15-081): Ciertas vulnerabilidades de Microsoft Office podrían permitir la ejecución remota de código (3080790)

### <a name="office-suite-security-updates"></a>Conjunto de aplicaciones de Office: Actualizaciones de seguridad
-   Boletín de seguridad Microsoft [MS15-081](/security-updates/SecurityBulletins/2015/ms15-081): Ciertas vulnerabilidades de Microsoft Office podrían permitir la ejecución remota de código (3080790)
-   Boletín de seguridad Microsoft [MS15-099](/security-updates/SecurityBulletins/2015/ms15-099): Ciertas vulnerabilidades de Microsoft Office podrían permitir la ejecución remota de código (3089664)