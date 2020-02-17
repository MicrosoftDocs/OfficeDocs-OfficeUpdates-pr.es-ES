---
title: Notas de la versión para las versiones del canal semianual (dirigido) en 2020
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Proporciona a los profesionales de TI las notas de la versión para las versiones del canal semianual (dirigido) de Office 365 ProPlus en 2020.
ms.openlocfilehash: 64270156e5985b3214a0e75c56f4bdb1713125fa
ms.sourcegitcommit: 3598ca5e26109a1f99349ce3a4e70cb1d6f13e05
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 02/14/2020
ms.locfileid: "41978718"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2020"></a>Notas de la versión para las versiones del canal semianual (dirigido) en 2020

En estas notas de la versión, se proporciona información sobre características nuevas y actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones del canal semianual (dirigido) de Office 365 ProPlus en 2020, Visio Pro para Office 365, el Cliente de escritorio de Project Online y Office 365 Empresa.

> [!NOTE]
>
> - A menudo publicamos características (y a veces incluso correcciones) para el Canal semianual (dirigido) durante un período de tiempo. Si no ve algo que se describe a continuación de inmediato, lo verá pronto. [Más información](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
> - Microsoft Teams está incluido en las nuevas instalaciones de canal semianual (dirigido), empezando por la versión 1902. Se agregará Teams a las instalaciones existentes de canal semianual (dirigido) cuando se actualicen a la versión 1908 o posterior. Para obtener más información, vea [Implementar Microsoft Teams con Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install).

## <a name="version-1908-february-11"></a>Versión 1908: 11 de febrero
*Versión 1908 (Compilación 11929.20606)*

Lista de actualizaciones de seguridad [aquí](https://docs.microsoft.com/es-ES/officeupdates/office365-proplus-security-updates)


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


- Se ha corregido un problema que causaba que los usuarios sufrieran un error al visualizar más de 30 calendarios en un entorno Citrix. [Aquí](https://support.microsoft.com/es-ES/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) está la KB individual, donde se ha documentado esto para versiones anteriores.

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

## <a name="version-1908-january-14"></a>Versión 1908: 14 de enero
*Versión 1908 (compilación 11929.20562)*

Las actualizaciones de seguridad se enumeran [aquí](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)


[//]: # (NO QUITAR ERRORES DETALLES CONTENIDO INICIO)

### <a name="resolved-issues"></a>Problemas corregidos
### <a name="excel"></a>Excel

- La información clave en holandés para el título del documento ha sido cambiada a Alt-G.

- Se resolvió un problema con la personalización de la cinta que no se carga al abrir el libro de trabajo insertado.

- Hubo un problema en el que no se podían seleccionar elementos del cuadro combinado de un formulario de WPF (Windows Presentation Foundation) que fue abierto por un complemento.

### <a name="outlook"></a>Outlook

- Se ha corregido un problema por el que los usuarios notaban un retraso evidente al interactuar con sus carpetas de buzón mediante métodos abreviados de teclado.

- Corregido un problema que hacía que no se mostraran las sugerencias de política cuando se utilizaba un remitente alternativo.

- Corregido un problema que hacía que los usuarios experimentaran bloqueos intermitentes al actualizar la información de presencia.

### <a name="powerpoint"></a>PowerPoint

- Arreglamos un problema cuando al copiar una diapositiva de una presentación a otra, se pueden crear patrones duplicados.
- Los archivos con nuevos comentarios modernos mostrarán una advertencia amarilla si se abren en una versión no soportada

### <a name="office-suite"></a>Conjunto de aplicaciones de Office

- Se ha solucionado un problema por el que los mensajes de actualización de Office aparecían en un idioma diferente al esperado. En el futuro, los mensajes de actualización de Office coincidirán correctamente con el idioma de visualización de Windows.

- Corregido un problema en el que una actualización no se aplicaría en ciertos casos en los que el usuario no es un administrador y la cuenta del sistema no tenía conectividad de red.


[//]: # (NO QUITAR DETALLES DE ERROR DEL CONTENIDO FINAL)

> [!NOTE]
> Si necesita ayuda con algún problema de uso de Office, le recomendamos que publique la pregunta en el [foro de preguntas de Microsoft](https://answers.microsoft.com/) o [Tech Community](https://techcommunity.microsoft.com/), o bien puede ponerse en contacto con el [servicio de soporte técnico](https://support.microsoft.com/contactus).