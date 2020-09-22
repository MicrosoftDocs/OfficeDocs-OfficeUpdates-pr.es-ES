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
ms.openlocfilehash: c01fbe403dacb0b474c37b7439eba5b616f8a08f
ms.sourcegitcommit: 591f5da255de896ef3156108349c6d2eaf34ed54
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 09/22/2020
ms.locfileid: "48174649"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="211f1-103">Historial de versiones de la Herramienta de implementación de Office</span><span class="sxs-lookup"><span data-stu-id="211f1-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="211f1-104">La Herramienta de implementación de Office (ODT) es una herramienta de línea de comandos que puede usar para descargar e implementar versiones de hacer clic y ejecutar de Office, como aplicaciones de Microsoft 365, en sus equipos cliente.</span><span class="sxs-lookup"><span data-stu-id="211f1-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="211f1-105">ODT le ofrece más control de la instalación de Office.</span><span class="sxs-lookup"><span data-stu-id="211f1-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="211f1-106">Le permite definir los productos e idiomas que se instalarán, cómo se actualizarán esos productos y si quiere o no mostrar la experiencia de instalación a los usuarios.</span><span class="sxs-lookup"><span data-stu-id="211f1-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="211f1-107">Para obtener información sobre cómo usar la ODT, vea [Información general sobre la herramienta de implementación de Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="211f1-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="211f1-108">**Sistema operativo compatible**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="211f1-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="211f1-109">**Instrucciones de instalación**: Descargue y ejecute el archivo ejecutable autoextraíble de la Herramienta de implementación de Office (setup.exe) y un archivo de configuración de ejemplo (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="211f1-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="211f1-110">Descargar la Herramienta de implementación de Office</span><span class="sxs-lookup"><span data-stu-id="211f1-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="june-9-2020"></a><span data-ttu-id="211f1-111">9 de junio de 2020</span><span class="sxs-lookup"><span data-stu-id="211f1-111">June 9, 2020</span></span>

<span data-ttu-id="211f1-112">Versión 16.0.12827.20268 (setup.exe versión 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="211f1-112">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="211f1-113">El Canal actual ahora es el canal predeterminado cuando no se especifica ningún canal</span><span class="sxs-lookup"><span data-stu-id="211f1-113">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="211f1-114">Se agregó soporte técnico para el Canal mensual para empresas</span><span class="sxs-lookup"><span data-stu-id="211f1-114">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="211f1-115">Se agregó soporte técnico para los nuevos nombres del canal</span><span class="sxs-lookup"><span data-stu-id="211f1-115">Added support for new channel names</span></span>
- <span data-ttu-id="211f1-116">Otras características de resistencia para continuar la instalación, si es posible, incluso cuando no estén disponibles algunos recursos de idioma.</span><span class="sxs-lookup"><span data-stu-id="211f1-116">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="211f1-117">Funciones MSIRemove expandidas para quitar productos de Office 2007</span><span class="sxs-lookup"><span data-stu-id="211f1-117">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="211f1-118">Funciones MSIRemove expandidas para quitar el Motor de acceso a la base de datos</span><span class="sxs-lookup"><span data-stu-id="211f1-118">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="211f1-119">15 de abril de 2020</span><span class="sxs-lookup"><span data-stu-id="211f1-119">April 15, 2020</span></span>

<span data-ttu-id="211f1-120">Versión 16.0.12624.20320 (setup.exe versión 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="211f1-120">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="211f1-121">Agrega soporte técnico para las versiones finales de Office específicas de Windows 7</span><span class="sxs-lookup"><span data-stu-id="211f1-121">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="211f1-122">Corrige un problema en el que la configuración de personalización puede no aplicarse como se esperaba</span><span class="sxs-lookup"><span data-stu-id="211f1-122">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="211f1-123">Corrige un problema por el que los archivos extraños .cat se pueden descargar de forma inesperada.</span><span class="sxs-lookup"><span data-stu-id="211f1-123">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="211f1-124">Enero de 16 de 2020</span><span class="sxs-lookup"><span data-stu-id="211f1-124">January 16, 2020</span></span>

<span data-ttu-id="211f1-125">Versión 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="211f1-125">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="211f1-126">Corrige un problema que causaba que la interfaz de usuario de instalación de Office aparezca en un idioma incorrecto al instalar varios idiomas.</span><span class="sxs-lookup"><span data-stu-id="211f1-126">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="211f1-127">Corrige un problema que causaba que la instalación de Office falle inesperadamente cuando se instalaban determinados paquetes de herramientas de corrección</span><span class="sxs-lookup"><span data-stu-id="211f1-127">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="211f1-128">Agrega soporte para controlar, opcionalmente, la implementación inicial de la [ característica Búsqueda de Microsoft en Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span><span class="sxs-lookup"><span data-stu-id="211f1-128">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="211f1-129">31 de octubre de 2019</span><span class="sxs-lookup"><span data-stu-id="211f1-129">October 31, 2019</span></span>

<span data-ttu-id="211f1-130">Versión 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="211f1-130">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="211f1-131">Se ha corregido un problema que permite que Skype Empresarial Basic 2019 se instale con productos de licencia por volumen perpetuo 2019</span><span class="sxs-lookup"><span data-stu-id="211f1-131">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="211f1-132">Se ha corregido un problema que puede ocasionar que el modo de descarga ODT falle inesperadamente en determinadas circunstancias cuando se utiliza un proxy.</span><span class="sxs-lookup"><span data-stu-id="211f1-132">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="211f1-133">Se ha desarrollado una nueva capacidad que permite que el modo de descarga ODT descargue a través de HTTP utilizando un puerto distinto al puerto 80.</span><span class="sxs-lookup"><span data-stu-id="211f1-133">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="211f1-134">10 de julio de 2019</span><span class="sxs-lookup"><span data-stu-id="211f1-134">July 10, 2019</span></span>

<span data-ttu-id="211f1-135">Versión 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="211f1-135">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="211f1-136">Compatibilidad con productos adicionales cuando se instalan con Office 2019: Access Runtime, Skype Empresarial Basic.</span><span class="sxs-lookup"><span data-stu-id="211f1-136">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="211f1-137">Compatibilidad con la instalación condicional de productos independientes al actualizar desde MSI.</span><span class="sxs-lookup"><span data-stu-id="211f1-137">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="211f1-138">23 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="211f1-138">April 23, 2019</span></span>

<span data-ttu-id="211f1-139">Versión 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="211f1-139">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="211f1-140">Se ha corregido un error con RemoveMSI=True para limpiar las configuraciones de registro relacionadas.</span><span class="sxs-lookup"><span data-stu-id="211f1-140">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="211f1-141">Se han actualizado los códigos de error para dar información adicional sobre errores inesperados (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="211f1-141">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="211f1-142">16 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="211f1-142">April 16 2019</span></span>

<span data-ttu-id="211f1-143">Versión 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="211f1-143">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="211f1-144">Compatibilidad para actualizar de C2R 32 bits a C2R 64 bits con el nuevo atributo MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="211f1-144">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="211f1-145">Se ha actualizado la lógica para /configure. Ahora permite acceder a los archivos XML de configuración almacenados en ubicaciones Web (http y https).</span><span class="sxs-lookup"><span data-stu-id="211f1-145">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="211f1-146">Se ha agregado MatchInstalled como un nuevo atributo que permite a la ODT coincidir con la versión existente cuando se agreguen más productos o idiomas.</span><span class="sxs-lookup"><span data-stu-id="211f1-146">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="211f1-147">13 de marzo de 2019</span><span class="sxs-lookup"><span data-stu-id="211f1-147">March 13, 2019</span></span>

<span data-ttu-id="211f1-148">Versión 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="211f1-148">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="211f1-149">Mejoras en situaciones de actualización y migración.</span><span class="sxs-lookup"><span data-stu-id="211f1-149">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="211f1-150">14 de enero de 2019</span><span class="sxs-lookup"><span data-stu-id="211f1-150">January 14, 2019</span></span>

<span data-ttu-id="211f1-151">Versión 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="211f1-151">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="211f1-152">Mejoras en el registro y la telemetría para la configuración de implementación.</span><span class="sxs-lookup"><span data-stu-id="211f1-152">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="211f1-153">Vínculos relacionados</span><span class="sxs-lookup"><span data-stu-id="211f1-153">Related links</span></span>

[<span data-ttu-id="211f1-154">Centro de descarga de ODT</span><span class="sxs-lookup"><span data-stu-id="211f1-154">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)