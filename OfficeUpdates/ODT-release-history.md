---
title: Historial de versiones de la Herramienta de implementación de Office (ODT)
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: Historial de versiones de la Herramienta de implementación de Office (ODT) para los profesionales de TI
ms.openlocfilehash: 70e000f7cbdc597bde156257fc7e4b2a1e6e69eb
ms.sourcegitcommit: 58d55cf532d1d02cca85772920a6dd71089b071d
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43781573"
---
# <a name="release-history-for-office-deployment-tool"></a>Historial de versiones de la Herramienta de implementación de Office

La Herramienta de implementación de Office (ODT) es una herramienta de línea de comandos que puede usar para descargar e implementar versiones de hacer clic y ejecutar de Office, como aplicaciones de Microsoft 365, en sus equipos cliente. 


ODT le ofrece más control de la instalación de Office. Le permite definir los productos e idiomas que se instalarán, cómo se actualizarán esos productos y si quiere o no mostrar la experiencia de instalación a los usuarios. Para obtener información sobre cómo usar la ODT, vea [Información general sobre la herramienta de implementación de Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).

 **Sistemas operativos compatibles**: Windows 10, Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012 y Windows Server 2012 R2. 
 
 **Instrucciones de instalación**: Descargue y ejecute el archivo ejecutable autoextraíble de la Herramienta de implementación de Office (setup.exe) y un archivo de configuración de ejemplo (configuration.xml). 

[Descargar la Herramienta de implementación de Office](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="april-15-2020"></a>15 de abril de 2020

Versión 16.0.12624.20320 (setup.exe versión 16.0.12624.20290)
- Agrega soporte técnico para las versiones finales de Office específicas de Windows 7
- Corrige un problema en el que la configuración de personalización puede no aplicarse como se esperaba
- Corrige un problema por el que los archivos extraños .cat se pueden descargar de forma inesperada.

## <a name="january-16-2020"></a>Enero de 16 de 2020

Versión 16.0.12325.20288
- Corrige un problema que causaba que la interfaz de usuario de instalación de Office aparezca en un idioma incorrecto al instalar varios idiomas.
- Corrige un problema que causaba que la instalación de Office falle inesperadamente cuando se instalaban determinados paquetes de herramientas de corrección
- Agrega soporte para controlar, opcionalmente, la implementación inicial de la [ característica Búsqueda de Microsoft en Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345)


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