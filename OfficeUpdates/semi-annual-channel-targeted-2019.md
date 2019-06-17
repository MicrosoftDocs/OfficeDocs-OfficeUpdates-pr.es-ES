---
title: Notas de la versión para las versiones de Canal semianual (dirigido) en 2019
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 6/11/2019
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Proporciona a los profesionales de TI las notas de la versión para las versiones de Canal semianual (dirigido) de Office 365 ProPlus en 2019.
ms.openlocfilehash: eabd0a3bf3c7c44a74e0991b78e11e6d079dc7f3
ms.sourcegitcommit: 2a0b5f0a6ef18194f8a8591ff2fd3e6894d162b2
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 06/12/2019
ms.locfileid: "34910400"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2019"></a>Notas de la versión para las versiones de Canal semianual (dirigido) en 2019

En estas notas de la versión, se proporciona información sobre características nuevas y actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones de Canal semianual (dirigido) para Office 365 ProPlus en 2019, incluyendo Visio Pro para Office 365 y el cliente de escritorio de Project Online.
 
> [!NOTE]
> - Esta información también se aplica a Office 365 Empresa, que es la versión de Office que viene con algunos planes de Office 365, como Empresa Premium.

 
> [!NOTE]
> - La información sobre las actualizaciones de seguridad de cada canal de actualización de Office 365 ProPlus se empezará a mostrar por separado en [Actualizaciones de seguridad](office365-proplus-security-updates.md).

## <a name="version-1902-june-11"></a>Versión 1902: 11 de junio
*Versión 1902 (compilación 11328.20318)*
<br/>Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/es-ES/officeupdates/office365-proplus-security-updates)

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
 - Soluciona un problema por el que los clientes no podían editar algunos campos de los elementos que se han migrado.

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

- Corregido un problema por el que los elementos de una actualización de Office no usan el almacenamiento en caché del mismo nivel de optimización de entrega. 
  [Más información]("https://docs.microsoft.com/es-ES/windows/deployment/update/waas-delivery-optimization)
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
- **Ver la dirección URL de Vínculos seguros:** los vínculos seguros le protegen de direcciones URL malintencionadas recibidas por correo electrónico, pero ocultan la dirección URL original. Para ver el original, mueva el puntero sobre la dirección URL. Requiere una licencia de Protección contra amenazas avanzada. 
  [Más información](https://products.office.com/es-ES/exchange/advance-threat-protection)
- **Zoom y quieto:** en lugar de ajustar el Zoom cada vez que lee un mensaje, elija una configuración predeterminada para todos los mensajes. [Más información](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)
- **Cifrado de mensajes: directiva IRM de solo cifrado:** la nueva opción de solo cifrado aparece en Opciones > Menú permisos para los usuarios de cifrado de mensajes de Office 365. Esta opción le permite cifrar un mensaje y enviárselo a cualquier usuario dentro o fuera de su organización.
- **Advertencia cuando está en CCO:** el recuadro CCO le avisará antes de que responda a todos accidentalmente en un correo electrónico en el que está en copia oculta.
- **Una línea Para: más inteligente:** a la hora de redactar un mensaje, al hacer clic en la línea Para: aparecen sugerencias de destinatarios que es probable que elija. Además, puede ver sus imágenes para confirmar que lo esté enviando a la persona adecuada. [Más información](https://support.office.com/article/147208AF-CA8E-4CDF-B71F-77BA81A54069)
- **Capacidad de insertar SVG con filtros aplicados:** ahora, los usuarios de Office tienen la capacidad de insertar SVG con filtros aplicados. [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Compatibilidad mejorada con pantallas de alta definición**: si usa varios monitores o una base de conexión para portátil, las aplicaciones de Office ofrecen ahora una imagen nítida en todas las pantallas, incluso si tienen configuraciones de escala diferentes. [Más información](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="powerpoint-feature-updates"></a>PowerPoint: actualizaciones de características

- **Inicio más rápido** La página de Inicio recién diseñada coloca los documentos abiertos recientemente en el centro y en primer plano. Acceda a archivos con menos clics y abra la Configuración u Opciones de la cuenta desde allí.
- **Escriba sin manos:** ¿Tiene un micrófono? Haga clic en Dictar y vea cómo PowerPoint escribe mientras habla.  [Más información](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Los iconos de la cinta tienen un aspecto nuevo:** no se preocupe, todo funciona de la misma forma. Además, tendrán un aspecto excelente en pantallas de todos los tamaños. [Más información](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Compatibilidad mejorada con pantallas de alta definición**: si usa varios monitores o una base de conexión para portátil, las aplicaciones de Office ofrecen ahora una imagen nítida en todas las pantallas, incluso si tienen configuraciones de escala diferentes. [Más información](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Hipervínculos en colores vivos:** los hipervínculos ya no son solo azules. Aplique el color que quiera a la fuente. [Más información](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)
- **Vea cómo las diapositivas cobran vida:** inserte gráficos 3D animados para ver corazones que laten, planetas en órbita y dinosaurios a toda velocidad por la pantalla. [Más información](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **Retocamos sus bocetos:** convertimos las formas y el texto dibujado a mano en diagramas refinados. Solo tiene que seleccionar los trazos de lápiz para empezar. [Más información](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **Mostrar lo que esconde una imagen:** coloque una imagen en una hoja de cálculo, elija el valor predeterminado y vea cómo cambia la transparencia. [Más información](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Entrada de tinta para magníficas diapositivas:** convierta el texto de tinta en formas estándar y texto y obtenga ideas de diseño inteligente del Diseñador de PowerPoint. [Más información](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)
- **Publicar en Microsoft Stream:** comparta una presentación como un vídeo de forma más segura en su organización mediante Microsoft Stream. [Más información](https://support.office.com/article/C140551F-CB37-4818-B5D4-3E30815C3E83)
- **Exportar a 4K:** ahora, la resolución 4K es una opción al exportar una presentación a vídeo.  [Más información](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- **Capacidad de insertar SVG con filtros aplicados:** ahora, los usuarios de Office tienen la capacidad de insertar SVG con filtros aplicados. [Más información](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

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
- **Instalación de Microsoft Teams:** Microsoft Teams se instala de forma predeterminada para las NUEVAS instalaciones de Office 365 ProPlus. 
  [Más información](https://docs.microsoft.com/es-ES/DeployOffice/teams-install)

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

- Corregido el problema por el que los complementos implementados con la [implementación centralizada de Office O365](https://docs.microsoft.com/es-ES/office/dev/add-ins/publish/centralized-deployment) se bloqueaban y no se podían usar.


## <a name="version-1808-january-8"></a>Versión 1808: 8 de enero
*Versión 1808 (compilación 10730.20264)* 

### <a name="outlook-non-security-updates"></a>Outlook: actualizaciones no relacionadas con la seguridad 

- Se ha corregido un problema por el que se producían errores de sincronización de calendario.

### <a name="word-non-security-updates"></a>Word: actualizaciones no relacionadas con la seguridad

- Mejorar el rendimiento abierto.


> [!NOTE]
> Si necesita ayuda con algún problema de uso de Office, le recomendamos que publique la pregunta en el [foro de preguntas de Microsoft](https://answers.microsoft.com/) o [Tech Community](https://techcommunity.microsoft.com/), o bien puede ponerse en contacto con el [servicio de soporte técnico](https://support.microsoft.com/contactus).