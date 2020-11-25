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
ms.openlocfilehash: a1553a3f08a254c9c177fec88073073c34a3427c
ms.sourcegitcommit: 413694d561d367e93ad51c9be41495ad09a24af3
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 11/23/2020
ms.locfileid: "49385486"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="a797f-103">Historial de versiones de la Herramienta de implementación de Office</span><span class="sxs-lookup"><span data-stu-id="a797f-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="a797f-104">La Herramienta de implementación de Office (ODT) es una herramienta de línea de comandos que se puede usar para descargar e implementar versiones de la característica “Hacer clic y ejecutar” de Office, como Aplicaciones de Microsoft 365, en sus equipos cliente.</span><span class="sxs-lookup"><span data-stu-id="a797f-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="a797f-p101">La ODT le ofrece más control que una instalación de Office. Puede definir los productos e idiomas que se instalarán, cómo se actualizarán esos productos y si quiere o no mostrar la experiencia de instalación a los usuarios. Para más información sobre cómo usar la ODT, consulte la [Introducción a la Herramienta de implementación de Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="a797f-p101">The ODT gives you more control over an Office installation. You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users. For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="a797f-108">**Sistema operativo compatible**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="a797f-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="a797f-109">**Instrucciones de instalación**: Descargue y ejecute el archivo ejecutable autoextraíble de la Herramienta de implementación de Office (setup.exe) y un archivo de configuración de ejemplo (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="a797f-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="a797f-110">Descargar la Herramienta de implementación de Office</span><span class="sxs-lookup"><span data-stu-id="a797f-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="november-23-2020"></a><span data-ttu-id="a797f-111">23 de noviembre de 2020</span><span class="sxs-lookup"><span data-stu-id="a797f-111">November 23, 2020</span></span>
<span data-ttu-id="a797f-112">Versión 16.0.13328.20420 (setup.exe versión 16.0.13328.20420)</span><span class="sxs-lookup"><span data-stu-id="a797f-112">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="a797f-113">Se ha corregido un problema que causaba que las herramientas de corrección no se descargaran en el modo de descarga</span><span class="sxs-lookup"><span data-stu-id="a797f-113">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="a797f-114">Se ha corregido un problema que causaba un error en el modo de descarga al ejecutarse en un contexto de usuario no elevado</span><span class="sxs-lookup"><span data-stu-id="a797f-114">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="a797f-115">Se ha corregido un problema que causaba que, al especificar un atributo de versión en el archivo XML de configuración, no se completaran las descargas en el modo de descarga</span><span class="sxs-lookup"><span data-stu-id="a797f-115">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="a797f-116">Se ha corregido un problema que causaba que la Herramienta de implementación de Office no se denominara "setup.exe" al extraerse</span><span class="sxs-lookup"><span data-stu-id="a797f-116">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="a797f-117">Se ha corregido un problema relativo a la prioridad de la instalación de origen cuando se proporciona un atributo de canal en el archivo XML de configuración</span><span class="sxs-lookup"><span data-stu-id="a797f-117">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="a797f-118">10 de noviembre de 2020</span><span class="sxs-lookup"><span data-stu-id="a797f-118">November 10, 2020</span></span>
<span data-ttu-id="a797f-119">Version 16.0.13328.20356 (setupODT.exe versión 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="a797f-119">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="a797f-120">Mejoras de confiabilidad y resiliencia</span><span class="sxs-lookup"><span data-stu-id="a797f-120">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="a797f-121">Para evitar confusiones y diagnosticar más fácilmente los errores de configuración, la ODT ahora se denomina setupODT.exe de manera predeterminada.</span><span class="sxs-lookup"><span data-stu-id="a797f-121">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="a797f-122">29 de octubre de 2020</span><span class="sxs-lookup"><span data-stu-id="a797f-122">October 29, 2020</span></span>
<span data-ttu-id="a797f-123">Versión 16.0.13328.20292 (setup.exe versión 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="a797f-123">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="a797f-124">Resuelva un problema por el que determinados productos de Office 2007 puedan bloquear la instalación inesperadamente al usar RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="a797f-124">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="a797f-125">14 de octubre de 2020</span><span class="sxs-lookup"><span data-stu-id="a797f-125">October 14, 2020</span></span>
<span data-ttu-id="a797f-126">Versión 16.0.13231.20368 (setup.exe versión 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="a797f-126">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="a797f-127">Todos los productos ahora usarán el Canal mensual de forma predeterminada cuando no se especifique ningún canal</span><span class="sxs-lookup"><span data-stu-id="a797f-127">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="a797f-128">Seguridad mejorada al ejecutar ODT desde un directorio que contiene otras DLL</span><span class="sxs-lookup"><span data-stu-id="a797f-128">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="a797f-129">Mejoras de confiabilidad y resiliencia</span><span class="sxs-lookup"><span data-stu-id="a797f-129">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="a797f-130">9 de junio de 2020</span><span class="sxs-lookup"><span data-stu-id="a797f-130">June 9, 2020</span></span>

<span data-ttu-id="a797f-131">Versión 16.0.12827.20268 (setup.exe versión 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="a797f-131">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="a797f-132">El Canal actual ahora es el canal predeterminado cuando no se especifica ningún canal</span><span class="sxs-lookup"><span data-stu-id="a797f-132">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="a797f-133">Se agregó soporte técnico para el Canal mensual para empresas</span><span class="sxs-lookup"><span data-stu-id="a797f-133">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="a797f-134">Se agregó soporte técnico para los nuevos nombres del canal</span><span class="sxs-lookup"><span data-stu-id="a797f-134">Added support for new channel names</span></span>
- <span data-ttu-id="a797f-135">Otras características de resistencia para continuar la instalación, si es posible, incluso cuando no estén disponibles algunos recursos de idioma.</span><span class="sxs-lookup"><span data-stu-id="a797f-135">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="a797f-136">Funciones MSIRemove expandidas para quitar productos de Office 2007</span><span class="sxs-lookup"><span data-stu-id="a797f-136">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="a797f-137">Funciones MSIRemove expandidas para quitar el Motor de acceso a la base de datos</span><span class="sxs-lookup"><span data-stu-id="a797f-137">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="a797f-138">15 de abril de 2020</span><span class="sxs-lookup"><span data-stu-id="a797f-138">April 15, 2020</span></span>

<span data-ttu-id="a797f-139">Versión 16.0.12624.20320 (setup.exe versión 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="a797f-139">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="a797f-140">Agrega soporte técnico para las versiones finales de Office específicas de Windows 7</span><span class="sxs-lookup"><span data-stu-id="a797f-140">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="a797f-141">Corrige un problema en el que la configuración de personalización puede no aplicarse como se esperaba</span><span class="sxs-lookup"><span data-stu-id="a797f-141">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="a797f-142">Corrige un problema por el que los archivos extraños .cat se pueden descargar de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="a797f-142">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="a797f-143">Enero de 16 de 2020</span><span class="sxs-lookup"><span data-stu-id="a797f-143">January 16, 2020</span></span>

<span data-ttu-id="a797f-144">Versión 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="a797f-144">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="a797f-145">Corrige un problema que causaba que la interfaz de usuario de instalación de Office aparezca en un idioma incorrecto al instalar varios idiomas.</span><span class="sxs-lookup"><span data-stu-id="a797f-145">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="a797f-146">Corrige un problema que causaba que la instalación de Office falle inesperadamente cuando se instalaban determinados paquetes de herramientas de corrección</span><span class="sxs-lookup"><span data-stu-id="a797f-146">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="a797f-147">Agrega soporte para controlar, opcionalmente, la implementación inicial de la [ característica Búsqueda de Microsoft en Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span><span class="sxs-lookup"><span data-stu-id="a797f-147">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="a797f-148">31 de octubre de 2019</span><span class="sxs-lookup"><span data-stu-id="a797f-148">October 31, 2019</span></span>

<span data-ttu-id="a797f-149">Versión 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="a797f-149">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="a797f-150">Se ha corregido un problema que permite que Skype Empresarial Basic 2019 se instale con productos de licencia por volumen perpetuo 2019</span><span class="sxs-lookup"><span data-stu-id="a797f-150">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="a797f-151">Se ha corregido un problema que puede ocasionar que el modo de descarga ODT falle inesperadamente en determinadas circunstancias cuando se utiliza un proxy.</span><span class="sxs-lookup"><span data-stu-id="a797f-151">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="a797f-152">Se ha desarrollado una nueva capacidad que permite que el modo de descarga ODT descargue a través de HTTP utilizando un puerto distinto al puerto 80.</span><span class="sxs-lookup"><span data-stu-id="a797f-152">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="a797f-153">10 de julio de 2019</span><span class="sxs-lookup"><span data-stu-id="a797f-153">July 10, 2019</span></span>

<span data-ttu-id="a797f-154">Versión 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="a797f-154">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="a797f-155">Compatibilidad con productos adicionales cuando se instalan con Office 2019: Access Runtime, Skype Empresarial Basic.</span><span class="sxs-lookup"><span data-stu-id="a797f-155">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="a797f-156">Compatibilidad con la instalación condicional de productos independientes al actualizar desde MSI.</span><span class="sxs-lookup"><span data-stu-id="a797f-156">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="a797f-157">23 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="a797f-157">April 23, 2019</span></span>

<span data-ttu-id="a797f-158">Versión 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="a797f-158">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="a797f-159">Se ha corregido un error con RemoveMSI=True para limpiar las configuraciones de registro relacionadas.</span><span class="sxs-lookup"><span data-stu-id="a797f-159">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="a797f-160">Se han actualizado los códigos de error para dar información adicional sobre errores inesperados (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="a797f-160">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="a797f-161">16 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="a797f-161">April 16 2019</span></span>

<span data-ttu-id="a797f-162">Versión 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="a797f-162">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="a797f-163">Compatibilidad para actualizar de C2R 32 bits a C2R 64 bits con el nuevo atributo MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="a797f-163">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="a797f-164">Se ha actualizado la lógica para /configure. Ahora permite acceder a los archivos XML de configuración almacenados en ubicaciones Web (http y https).</span><span class="sxs-lookup"><span data-stu-id="a797f-164">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="a797f-165">Se ha agregado MatchInstalled como un nuevo atributo que permite a la ODT coincidir con la versión existente cuando se agreguen más productos o idiomas.</span><span class="sxs-lookup"><span data-stu-id="a797f-165">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="a797f-166">13 de marzo de 2019</span><span class="sxs-lookup"><span data-stu-id="a797f-166">March 13, 2019</span></span>

<span data-ttu-id="a797f-167">Versión 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="a797f-167">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="a797f-168">Mejoras en situaciones de actualización y migración.</span><span class="sxs-lookup"><span data-stu-id="a797f-168">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="a797f-169">14 de enero de 2019</span><span class="sxs-lookup"><span data-stu-id="a797f-169">January 14, 2019</span></span>

<span data-ttu-id="a797f-170">Versión 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="a797f-170">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="a797f-171">Mejoras en el registro y la telemetría para la configuración de implementación.</span><span class="sxs-lookup"><span data-stu-id="a797f-171">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="a797f-172">Vínculos relacionados</span><span class="sxs-lookup"><span data-stu-id="a797f-172">Related links</span></span>

[<span data-ttu-id="a797f-173">Centro de descarga de ODT</span><span class="sxs-lookup"><span data-stu-id="a797f-173">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)