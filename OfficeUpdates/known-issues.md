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
ms.openlocfilehash: 60706952efab5ec1379cbe260442b5865f599f28
ms.sourcegitcommit: 34571aa50b48a2111dee315f0ebf2e5f90cdf434
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 10/17/2019
ms.locfileid: "37574378"
---
# <a name="office-365-proplus-known-issues"></a>Problemas conocidos de Office 365 ProPlus

Estos problemas conocidos proporcionan información sobre actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones del Canal mensual, SACT y SAC de Office 365 ProPlus 2019, Visio Pro para Office 365, el Cliente de escritorio de Project Online y Office 365 Empresa.

En esta tabla se ofrece un resumen de los problemas actualmente activos y los problemas resueltos.  La siguiente tabla se actualizará con los problema importantes que se están investigando.

> [!NOTE]
>- Esta lista no es exhaustiva.
>- Los problemas resueltos también se documentan en las páginas de canales correspondientes.

<br>

## <a name="october-2019"></a>Octubre de 2019

|Resumen|Aplicaciones afectadas|
|:-------------------------------------------------------------------------------------|:---------------------|
|Se identificó un problema con Buscar y reemplazar que cambiaba el enfoque en el cuadro de diálogo después de encontrar el primer elemento. <br><br> **Versión resuelta**: <br> Versión SACT 1908 (16.0.11929.20396) |Excel<br><br>
|Se logró identificar un problema que provocaba que los usuarios experimentaran un error de permiso al copiar elementos de su calendario principal en un calendario de grupo.<br><br> **Estado**: Investigando|Outlook<br><br>
|Se identificó un problema de rendimiento en Win7, donde la galería de insertar formas de la cinta de opciones de todas las aplicaciones tardó aproximadamente 4 segundos en aparecer. <br><br> **Versión resuelta**: <br>Versión mensual 1909 (16.0.12026.20264) <br> Versión SACT 1908 (16.0.11929.20396)|PowerPoint<br><br>
|Se identificó un problema en el que, en determinadas circunstancias, los accesos directos de Office desaparecían después de una actualización.  <br><br> **Estado**: Investigando|Conjunto de aplicaciones de Office<br><br>
|Se identificó un problema por el cual los usuarios no podían guardar documentos de Word, Excel y PowerPoint.  Este problema afecta a los usuarios que crean un nuevo archivo y abren la opción "Guardar como cuadro de diálogo" después de hacer clic en el icono Guardar o presionar Ctrl + g.<br><br> **Versión resuelta**: <br>Versión mensual 1909 (16.0.12026.20334) <br> Versión SACT 1908 (16.0.11929.20396)|Conjunto de aplicaciones de Office<br><br>
|

<br>
<br>

## <a name="september-2019"></a>Septiembre de 2019

|Resumen|Aplicaciones afectadas|
|:-------------------------------------------------------------------------------------|:---------------------|
|Se identificó un problema que impedía que se pegaran hipervínculos en algunas hojas protegidas. <br><br> **Versión resuelta**: <br>Versión mensual 1909 (16.0.12026.20052) <br> Versión SACT 1908 (16.0.11929.20344) <br> Versión SAC 1902  (16.0.11328.20434)|Excel<br><br>
|Se identificó un problema en la característica ideas de Excel, error al cargar el complemento haciendo clic en el botón ideas en el cliente de Win32. <br><br> **Versión resuelta**: <br>Versión SACT 1908 (16.0.11929.20352) <br>|Excel<br><br>
|Se identificó un problema en el que solo se muestran 16 complementos al buscar en el administrador de complementos. <br><br>**Versión resuelta**: <br>Versión mensual 1909 (16.0.12026.20264) <br> Versión SACT 1908 (16.0.11929.20352) <br>|Excel<br><br>
|Se identificó un problema que podría haber evitado que los archivos se guarden en una ubicación de WebDAV.<br><br>**Versión resuelta**: <br>Versión mensual 1909 (16.0.12026.20264)|Outlook<br><br>
|Se Identificó un problema que provocaba que las direcciones URL de desplazamiento simple no se mostraran en algunos vínculos seguros.<br><br>**Versión resuelta**: <br> Versión SACT 1908 (16.0.11929.20370)|Outlook<br><br>
|Se identificó un problema en el que las actualizaciones de la lógica de bloqueo de archivos adjuntos en Outlook también bloquea los archivos adjuntos de Python.<br><br>**Versión resuelta**: <br>Versión SACT 1908 (16.0.11929.20370)|Outlook<br><br>
|Se identificó un problema que hacía que los usuarios observaran una pérdida de memoria en el proceso de Outlook.<br><br>**Versión resuelta**: <br>Versión SACT 1908 (16.0.11929.20370)|Outlook<br><br>
|Se identificó un problema que podría causar la pérdida de datos en sesiones que involucraban tanto la coautoría como la edición sin conexión en PowerPoint.<br><br>**Versión resuelta**: <br>Versión mensual 1909 (16.0.12026.20264)<br>Versión SACT 1908 (16.0.11929.20370) |PowerPoint<br><br>
|Se identificó un problema al crear un PDF o XPS desde el menú Archivo, por lo que no se crea el archivo. <br><br>**Versión resuelta**: <br>Versión SAC 1908 (16.0.11328.20428)|Project<br><br>
|Se identificó un problema que los usuarios podrían encontrar al abrir un archivo.<br><br>**Versión resuelta**: <br>Versión mensual 1909 (16.0.12026.20264) <br> Versión SACT 1908 (16.0.11929.20340)|Word<br><br>
|Se identificó un problema con los archivos de Office sincronizados por el motor de sincronización de OneDrive, los metadatos del documento como Requerir propiedades y Requisitos de tipo de contenido ya no se validan en Guardar y Guardar como.<br><br>**Versión resuelta**: <br> Versión mensual 1906 (16.0.11727.20210)<br>Versión SAC 1902 (16.0.11328.20438)|Word<br><br>
|Se identificó un problema en el que las compilaciones actuales de JAWS en Windows no anunciarán palabras cuando se usa Mayús + Flecha derecha.<br><br>**Versión resuelta**: <br>Versión mensual 1904 (16.0.11601.20144)<br>Versión SAC 1902 (16.0.11328.20438)|Word<br><br>
|Se identificó un problema al descargar las actualizaciones de Office mediante la reanudación de las descargas que pueden haberse interrumpido previamente.<br><br>**Versión resuelta**: <br> Versión SACT 1908 (16.0.11929.20380)|Conjunto de aplicaciones de Office<br><br>
|Se identificó un problema en el que la notificación "Corregir mi cuenta" no desaparece después de iniciar sesión correctamente.<br><br>**Versión resuelta**: <br>Versión SAC 1902 (16.0.11328.20438)|Conjunto de aplicaciones de Office<br><br>
|


<br>
<br>

> [!NOTE]
> Si necesita ayuda con algún problema de uso de Office, le recomendamos que publique la pregunta en el [foro de preguntas de Microsoft](https://answers.microsoft.com/) o [Tech Community](https://techcommunity.microsoft.com/), o bien puede ponerse en contacto con el [servicio de soporte técnico](https://support.microsoft.com/contactus).
