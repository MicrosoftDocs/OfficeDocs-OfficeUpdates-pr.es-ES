---
title: Problemas conocidos de Office 365 ProPlus
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: RelNotes_ProPlus
description: Ofrece información acerca de los problemas conocidos de Office 365 ProPlus
ms.openlocfilehash: 721c9a600b079b3214fa798a39a8ed728c89de93
ms.sourcegitcommit: 7c1759a0e733ade767da00175afc1c43e8d07e3a
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 11/15/2019
ms.locfileid: "38640829"
---
# <a name="office-365-proplus-known-issues"></a>Problemas conocidos de Office 365 ProPlus

Estos problemas conocidos proporcionan información sobre actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones del Canal mensual, SACT y SAC de Office 365 ProPlus 2019, Visio Pro para Office 365, el Cliente de escritorio de Project Online y Office 365 Empresa.

En esta tabla se ofrece un resumen de los problemas actualmente activos y los problemas resueltos.  La siguiente tabla se actualizará con los problema importantes que se están investigando.

> [!NOTE]
>- Esta lista no es exhaustiva.
>- Si experimenta un problema en un canal que no sea el canal que se muestra como resuelto, puede esperar una resolución pronto. [Más información](https://docs.microsoft.com/es-ES/DeployOffice/overview-of-update-channels-for-office-365-proplus#BKMK_SAC)
>- Los problemas resueltos también se documentan en las páginas de canales correspondientes.

<br>

### <a name="last-updated-november-12-2019"></a>Última actualización: 12 de noviembre de 2019

### <a name="excel"></a>Excel

- Los controles de casilla podrían reducirse al usar el autoajuste para ajustar el alto de fila.<br><br>**Investigando**: mensualmente, SACT

- Problema de rendimiento con las funciones asíncronas definidas por el usuario que hacía que se ejecutaran de forma sincrónica.<br><br>**Resuelto**: SACT versión 1908 (11929.20436) 

- Se podría impedir que los usuarios guarden en el formato de hoja de trabajo en Office 365 Excel<br><br>**Resuelto**: SACT versión 1908 (11929.20436)


- Problema de rendimiento bajo al hacer clic en el botón Color de fuente cuando un archivo tiene un formato condicional extenso.<br><br>**Resuelto**: SACT versión 1908 (11929.20436)

- Mejoras significativas en el rendimiento al eliminar columnas con celdas combinadas.<br><br>**Investigando**: SACT<br>**Resuelto**: Versión mensual 1910 (12130.20272)

- Resultados incorrectos al convertir los filtros de un informe junto con el resto de la tabla dinámica de consultas enviadas a servidores tabulares SQL.<br><br>**Investigando**: mensualmente 

- Se han corregido los colores que se usan en las vistas previas al insertar gráficos con plantillas de gráficos.<br><br>**Resuelto**: versión mensual 1910 (12130.20272) y versión SACT 1908 (11929.20436)


- Se identificó un problema al insertar archivos como objeto desde OneDrive.<br><br> **Resuelto**: Versión mensual 1910 (12130.20272)

- Se identificó un problema en el que los libros creados en versiones anteriores de Office podrían hacer que Excel se bloqueara cuando se abría en las versiones actuales de Office.<br><br>
**Resuelto**: versión mensual 1910 (12130.20272), versión SACT 1908 (11929.20436) y SAC Version 1902 (11328.20468)

- Identificó un problema que provocaba retrasos en la visualización de valores escritos después de eliminar un rango.<br><br>
**Resuelto**: versión SAC 1902 (11328.20468)

- Corregimos un problema en el que al seleccionar una celda luego de desplazar, podía resultar en la selección de la celda incorrecta.<br><br>
**Investigando**: SACT <br>**Resuelto**: Versión mensual 1910 (12130.20272)

- Hemos corregido un problema que podía haber causado que los gráficos de líneas de dispersión no se renderizaran correctamente al cambiar la colección de series.<br><br>
**Resuelto**: versión mensual 1910 (12130.20272) y versión SACT 1908 (11929.20300)

### <a name="outlook"></a>Outlook

- Identificó un problema que causaba que algunos usuarios vean carpetas especiales duplicadas al agregar una cuenta de Exchange secundaria.<br><br>
**Resuelto**: versión mensual 1910 (12130.20272) y versión SACT 1908 (11929.20436)

- Se ha corregido un problema que podría haber provocado una pérdida de memoria. <br><br>
**Resuelto**: versión mensual 1910 (12130.20272), versión SACT 1908 (11929.20388) y SAC Version 1902 (11328.20468)

- Se ha abordado un problema que causaba que algunos usuarios vean carpetas especiales duplicadas al agregar una cuenta de Exchange secundaria.<br><br>
**Resuelto**: versión mensual 1910 (12130.20272) y versión SACT 1908 (11929.20436)

- Se ha corregido un problema que a veces podría causar un bloqueo cuando un usuario recibe un mensaje de "conversación perdida" de Skype.<br><br>
**Resuelto**: Versión mensual 1910 (12130.20272)

- Se identificó un problema que provocaba que los usuarios reciban un error genérico "error en la operación" al abrir datos adjuntos en un equipo en el que DisableBGSave está habilitado.<br><br>
**Resuelto**: Versión mensual 1910 (12130.20272)

- Se identificó un problema con los vínculos de CID: no se pudieron romper las imágenes (imágenes basadas en mensajes de correo electrónico de Outlook).<br><br>
**Resuelto**: SACT versión 1908 (11929.20436)

- Se ha corregido un problema que pudo haber provocado un mensaje de error incorrecto al intentar enviar correo electrónico cifrado con s/MIME.<br><br>**Resuelto**: Versión mensual 1910 (12130.20272)

### <a name="powerpoint"></a>PowerPoint

- Algunos caracteres katakana pueden mostrarse incorrectamente en un cuadro de texto vertical.<br><br>
**Investigando**: mensualmente 

- Se ha corregido un problema que evitó la creación de hipervínculos al pegar el texto con hipervínculos <br><br>**Resuelto**: Versión mensual 1910 (12130.20272)

- Se ha corregido un problema que podría provocar la ruptura de TextRanges después de pegar el texto en el encabezado o pie de página, los marcadores de posición en el patrón de diapositivas y en los diseños de diapositiva. <br><br>**Resuelto**: Versión mensual 1910 (12130.20272)

- Se identificó un problema de rendimiento en Win7, donde la galería para insertar formas de la cinta de opciones de todas las aplicaciones tardaba aproximadamente 4 segundos en aparecer. <br>
<br>**Resuelto**: versión mensual 1910 (12130.20272), versión SACT 1908 (11929.20396) y SAC Version 1902 (11328.20468)

### <a name="project"></a>Project

- Si tiene una tarea sin nada de trabajo, es posible que la tarea no se pueda marcar como completada y siempre se mostrará en el 99 %.<br><br>
**Investigando**: mensualmente <br>
**Resuelto**: SACT versión 1908 (11929.20436)

- Las sobreasignaciones no se resuelven al redistribuir<br><br>
**Investigando**: mensualmente 

- Identificamos un problema en el que los usuarios podían recibir varios mensajes al abrir un proyecto de solo lectura.<br><br>
**Resuelto**: versión mensual 1910 (12130.20344) y versión SACT 1908 (11929.20436)

### <a name="word"></a>Word

- Puede que se produzcan errores al buscar desde el panel de navegación<br><br>
**Investigando**: mensualmente 

- Se identificó un problema al insertar archivos como objeto desde OneDrive.<br><br> **Resuelto**: Versión mensual 1910 (12130.20272)

### <a name="office-suite"></a>Conjunto de aplicaciones de Office
- Al intentar guardar un archivo en un recurso compartido de red desconectado, se pueden producir problemas **Investigando**: mensualmente



<br>
<br>

> [!NOTE]
> Si necesita ayuda con algún problema de uso de Office, le recomendamos que publique la pregunta en el [foro de preguntas de Microsoft](https://answers.microsoft.com/) o [Tech Community](https://techcommunity.microsoft.com/), o bien puede ponerse en contacto con el [servicio de soporte técnico](https://support.microsoft.com/contactus).
