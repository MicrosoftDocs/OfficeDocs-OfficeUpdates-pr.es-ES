---
title: Historial de versiones de la Herramienta de implementación de Office (ODT)
ms.author: timda
author: TimDavenport
manager: TimDavenport
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: Historial de versiones de la Herramienta de implementación de Office (ODT) para los profesionales de TI
ms.openlocfilehash: 8e2387e11eb7327d0fe2148f2fe43633aad8c725
ms.sourcegitcommit: 4a2190fd43c552c92d8194ec4520673d75af22f1
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/13/2021
ms.locfileid: "51748958"
---
# <a name="release-history-for-office-deployment-tool"></a>Historial de versiones de la Herramienta de implementación de Office

La Herramienta de implementación de Office (ODT) es una herramienta de línea de comandos que puede usar para descargar e implementar versiones de hacer clic y ejecutar de Office, como aplicaciones de Microsoft 365, en sus equipos cliente. 


ODT le ofrece más control de la instalación de Office. Le permite definir los productos e idiomas que se instalarán, cómo se actualizarán esos productos y si quiere o no mostrar la experiencia de instalación a los usuarios. Para obtener información sobre cómo usar la ODT, vea [Información general sobre la herramienta de implementación de Office](/deployoffice/overview-of-the-office-2016-deployment-tool).

 **Sistema operativo compatible**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016 
 
 **Instrucciones de instalación**: Descargue y ejecute el archivo ejecutable autoextraíble de la Herramienta de implementación de Office (setup.exe) y un archivo de configuración de ejemplo (configuration.xml). 

[Descargar la Herramienta de implementación de Office](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="april-13-2021"></a>13 de abril de 2021
Versión 16.0.13901.20336 (versión setup.exe 16.0.13901.20328)
- Correcciones de confiabilidad para configurar operaciones que se ejecutan en dispositivos con Office ya instalado
- Correcciones para evitar mostrar la interfaz de usuario de progreso duplicada en algunos escenarios
- Mejoras en la precisión de código de error que se muestran en la interfaz de usuario
- Correcciones de confiabilidad para plataformas ARM

## <a name="march-23-2021"></a>23 de marzo de 2021
Versión 16.0.13801.20360 (versión setup.exe 16.0.13801.20340)
- Cambios para dar soporte a próximas versiones de productos de Office
- Correcciones de confiabilidad para plataformas ARM


## <a name="february-25-2021"></a>25 de febrero de 2021
Versión 16.0.13628.20476 (versión setup.exe 16.0.13628.20462)
- Se ha corregido un problema en el que se producían errores al validar archivos configuration.xml que especificaban docenas de idiomas
- Se ha corregido un problema por el que no se respetaba la propiedad FORCEAPPSHUTDOWN en los escenarios de MigrateArch
- Se ha corregido un problema por el que se producía un error al especificar 2 o más atributos PIDKEY en configuration.xml al instalar las PIDKeys



## <a name="february-9-2021"></a>9 de febrero de 2021
Versión 16.0.13628.20274 (versión setup.exe 16.0.13628.20246)
- Validación agregada para advertir y evitar sobre instalaciones no compatibles en Windows 8.0
- Correcciones de confiabilidad para dispositivos ARM64


## <a name="january-12-2021"></a>12 de enero de 2021
Versión 16.0.13530.20376 (versión setup.exe 16.0.13530.20334)
- Se ha corregido un problema por el que un registro de producto dañado o no estándar podía provocar un error en las operaciones de RemoveMSI.

## <a name="december-21-2020"></a>21 de diciembre de 2020
Versión 16.0.13426.20370 (versión setup.exe 16.0.13426.20352)
- Se solucionó un problema que provocaba que fallaran las instalaciones de fuente local de ProofingTools del canal PerpetualVL2019
- Se solucionó un problema para garantizar que el cliente Hacer clic y ejecutar trate de actualizarse al agregar productos adicionales en idiomas incompletos de Office a una instalación ya existente


## <a name="december-8-2020"></a>8 de diciembre de 2020
Versión 16.0.13426.20308 (setup.exe versión 16.0.13426.20308)
- Se ha corregido un problema que provocaba que el modo de descarga bloqueara las descargas del canal perpetuo 2019 si el dispositivo tenía un producto de Office instalado desde un canal 2019 no perpetuo.
- Se ha corregido un problema que provocaba que una migración de arquitectura produjera un error en un origen local creado mediante el modo de descarga que había especificado una versión explícita en el XML de configuración.


## <a name="november-23-2020"></a>23 de noviembre de 2020
Versión 16.0.13328.20420 (setup.exe versión 16.0.13328.20420)
- Se ha corregido un problema que provocaba que las herramientas de corrección no se descargaran en el modo de /descarga
- Se ha corregido un problema que provocaba un error en el modo de /descarga al ejecutarse en un contexto de usuario no elevado
- Se ha corregido un problema que provocaba que, al especificar un atributo de versión en el archivo XML de configuración, no se completaran las descargas en el modo de /descarga
- Se ha corregido un problema que provocaba que la Herramienta de implementación de Office no se denominara "setup.exe" al extraerse
- Se ha corregido un problema relacionado con la prioridad de la instalación de origen cuando se proporcionaba un atributo de canal en el archivo XML de configuración

## <a name="november-10-2020"></a>10 de noviembre de 2020
Version 16.0.13328.20356 (setupODT.exe versión 16.0.13328.20336)
- Mejoras de confiabilidad y resiliencia
- Para evitar confusiones y diagnosticar más fácilmente los errores de configuración, la ODT ahora se denomina setupODT.exe de manera predeterminada.

## <a name="october-29-2020"></a>29 de octubre de 2020
Versión 16.0.13328.20292 (setup.exe versión 16.0.13328.20290)
- Resuelva un problema por el que determinados productos de Office 2007 puedan bloquear la instalación inesperadamente al usar RemoveMSI

## <a name="october-14-2020"></a>14 de octubre de 2020
Versión 16.0.13231.20368 (setup.exe versión 16.0.13231.20350)
- Todos los productos ahora usarán el Canal mensual de forma predeterminada cuando no se especifique ningún canal
- Seguridad mejorada al ejecutar ODT desde un directorio que contiene otras DLL
- Mejoras de confiabilidad y resiliencia

## <a name="june-9-2020"></a>9 de junio de 2020

Versión 16.0.12827.20268 (setup.exe versión 16.0.12827.20258)
- El Canal actual ahora es el canal predeterminado cuando no se especifica ningún canal
- Se agregó soporte técnico para el Canal mensual para empresas
- Se agregó soporte técnico para los nuevos nombres del canal
- Otras características de resistencia para continuar la instalación, si es posible, incluso cuando no estén disponibles algunos recursos de idioma.
- Funciones MSIRemove expandidas para quitar productos de Office 2007
- Funciones MSIRemove expandidas para quitar el Motor de acceso a la base de datos 

## <a name="april-15-2020"></a>15 de abril de 2020

Versión 16.0.12624.20320 (setup.exe versión 16.0.12624.20290)
- Agrega soporte técnico para las versiones finales de Office específicas de Windows 7
- Corrige un problema en el que la configuración de personalización puede no aplicarse como se esperaba
- Corrige un problema por el que los archivos extraños .cat se pueden descargar de forma inesperada.

## <a name="january-16-2020"></a>Enero de 16 de 2020

Versión 16.0.12325.20288
- Corrige un problema que causaba que la interfaz de usuario de instalación de Office aparezca en un idioma incorrecto al instalar varios idiomas.
- Corrige un problema que causaba que la instalación de Office falle inesperadamente cuando se instalaban determinados paquetes de herramientas de corrección
- Agrega soporte para controlar, opcionalmente, la implementación inicial de la [ característica Búsqueda de Microsoft en Bing](/deployoffice/microsoft-search-bing)


## <a name="october-31-2019"></a>31 de octubre de 2019

Versión 16.0.12130.20272
- Se ha corregido un problema que permite que Skype Empresarial Basic 2019 se instale con productos de licencia por volumen perpetuo 2019
- Se ha corregido un problema que puede ocasionar que el modo de descarga ODT falle inesperadamente en determinadas circunstancias cuando se utiliza un proxy.
- Se ha desarrollado una nueva capacidad que permite que el modo de descarga ODT descargue a través de HTTP utilizando un puerto distinto al puerto 80.


## <a name="july-10-2019"></a>10 de julio de 2019

Versión 16.0.11901.20022
- Compatibilidad con productos adicionales cuando se instalan con Office 2019: Access Runtime, Skype Empresarial Basic.
- Compatibilidad con la instalación condicional de productos independientes al actualizar desde MSI.

## <a name="april-23-2019"></a>23 de abril de 2019

Versión 16.0.11617.33601
- Se ha corregido un error con RemoveMSI=True para limpiar las configuraciones de registro relacionadas.
- Se han actualizado los códigos de error para dar información adicional sobre errores inesperados (E_UNEXPECTED).

## <a name="april-16-2019"></a>16 de abril de 2019

Versión 16.0.11615.33602
- Compatibilidad para actualizar de C2R 32 bits a C2R 64 bits con el nuevo atributo MigrateArch.
- Se ha actualizado la lógica para /configure. Ahora permite acceder a los archivos XML de configuración almacenados en ubicaciones Web (http y https).
- Se ha agregado MatchInstalled como un nuevo atributo que permite a la ODT coincidir con la versión existente cuando se agreguen más productos o idiomas.

## <a name="march-13-2019"></a>13 de marzo de 2019

Versión 16.0.11509.33604
- Mejoras en situaciones de actualización y migración.

## <a name="january-14-2019"></a>14 de enero de 2019

Versión 16.0.11306.33602
- Mejoras en el registro y la telemetría para la configuración de implementación.


## <a name="related-links"></a>Vínculos relacionados

[Centro de descarga de ODT](https://www.microsoft.com/en-us/download/details.aspx?id=49117)