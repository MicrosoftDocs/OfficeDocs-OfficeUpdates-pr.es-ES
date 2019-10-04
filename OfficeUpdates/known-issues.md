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
ms.openlocfilehash: 18082351f0ed6df9b50e5c1193adb2d85a2da40a
ms.sourcegitcommit: 01ac73d10be11b830776836c70d0a0efe4e7aafc
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 10/04/2019
ms.locfileid: "37391314"
---
# <a name="office-365-proplus-known-issues"></a>Problemas conocidos de Office 365 ProPlus

Estos problemas conocidos proporcionan información sobre actualizaciones no relacionadas con la seguridad que se incluyen en las actualizaciones del Canal mensual, SACT y SAC de Office 365 ProPlus 2019, Visio Pro para Office 365, el Cliente de escritorio de Project Online y Office 365 Empresa.

En esta tabla se ofrece un resumen de los problemas actualmente activos y los problemas resueltos.  La siguiente tabla se actualizará con los problema importantes que se están investigando.

 > [!NOTE]
 >- Esta lista no es exhaustiva.

<br>

## <a name="september-2019"></a>Septiembre de 2019

|Resumen|Investigando|Resuelto|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|**Excel**
Se encontró un problema que impide que los hipervínculos se peguen en algunas hojas protegidas.|Versión SACT 1908 <br> Versión SAC 1902|Versión mensual 1909 <br> 16.0.12026.20264|
Se encontró un problema en la característica ideas de Excel, error al cargar el complemento haciendo clic en el botón ideas en el cliente de Win32.||Versión mensual 1909 <br> 16.0.12026.20264|
Encontramos un problema en el que solo se muestran 16 complementos al buscar en el administrador de complementos.|Versión SACT 1908|Versión mensual 1909 <br> 16.0.12026.20264|
|**Outlook**
Se ha encontrado un problema que podía impedir guardar archivos en una ubicación de WebDAV||Versión mensual 1909 <br> 16.0.12026.20264|
Hemos descubierto un problema que provocaba errores en la visualización de las direcciones URL de desplazamiento simple en algunos vínculos seguros.|Versión SACT 1908|Versión mensual 1909 <br> 16.0.12026.20264|
Hemos descubierto un problema por el que las actualizaciones de datos adjuntos bloqueaban la lógica de Outlook y los datos adjuntos de Python.|Versión SACT 1908|Versión mensual 1909 <br> 16.0.12026.20264|
Se ha corregido un problema por el que los usuarios notaban una pérdida de memoria en el proceso de Outlook.|Versión SACT 1908|Versión mensual 1909 <br> 16.0.12026.20264|
|**PowerPoint**
Se ha encontrado un problema que podía provocar pérdidas de datos en sesiones relacionadas con la coautoría y la edición sin conexión en PowerPoint.|Versión SACT 1908|Versión mensual 1909 <br> 16.0.12026.20264|
|**Proyecto**
Encontramos un problema al crear un PDF o XPS desde el menú Archivo, el archivo no se ha creado. |Versión SAC 1902||
|**Word**
Encontramos un problema que se presenta a los usuarios al abrir un archivo.|Versión SACT 1908|Versión mensual 1909 <br> 16.0.12026.20264|
Encontramos un problema con los archivos de Office sincronizados por el motor de sincronización de OneDrive, los metadatos de documentos como las propiedades de los requisitos y el tipo de información ya no son validados en Guardar y guardar como.|Versión SAC 1902||
Encontramos un problema en el que las compilaciones 19H1 de JAWS en Windows no anunciaban palabras al usar Mayús. + Flecha derecha.|Versión SAC 1902||
|**Conjunto de aplicaciones de Office**
Desuso de SHA-1: para proteger la seguridad de los clientes de Office, las actualizaciones de Microsoft Office ahora se firman exclusivamente con el algoritmo SHA-2.|Versión SACT 1908|Versión mensual 1909 <br> 16.0.12026.20264|
Se encontró un problema al reanudar descargas previamente interrumpidas de actualizaciones de Office.|Versión SACT 1908|Versión mensual 1909 <br> 16.0.12026.20264||
Se encontró un problema por el que la notificación «Solucionar mi cuenta» no desaparece después de iniciar sesión correctamente.|Versión SAC 1902||



## <a name="may-2019---sample"></a>Mayo de 2019 - MUESTRA

|Resumen|Investigando|Resuelto|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|**Excel**
Ejemplo resuelto en varias compilaciones. Hemos detectado un problema por el que los gráficos de cascada y embudo dejaban de estar sincronizados con las tablas al insertar o eliminar celdas.||Versión SAC 1902 <br> (16.0.11328.20306) <br> Versión mensual 1905 <br> (16.0.11629.20210)|
|**Word**
Ejemplo resuelto en algunas compilaciones, no en todas. Hemos detectado un problema con el rendimiento al habilitar Elementos rápidos para Propiedades del documento.|Versión SAC 1808|Versión SACT 1902 <br> (16.0.11328.20340)|

<br>
<br>

> [!NOTE]
> Si necesita ayuda con algún problema de uso de Office, le recomendamos que publique la pregunta en el [foro de preguntas de Microsoft](https://answers.microsoft.com/) o [Tech Community](https://techcommunity.microsoft.com/), o bien puede ponerse en contacto con el [servicio de soporte técnico](https://support.microsoft.com/contactus).
