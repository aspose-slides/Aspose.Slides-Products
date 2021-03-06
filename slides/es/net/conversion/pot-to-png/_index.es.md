---
title: Convierte POT a PNG a través de C#
weight: 6430
url: /es/net/conversion/pot-to-png/ 
description: Código de muestra para la conversión de POT a PNG C#. Utilice el código de ejemplo de API para la conversión de archivos POT por lotes a PNG dentro de VB.NET, Asp.NET o cualquier aplicación basada en .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Convierte POT a PNG a través de C#" h2="Exporte archivos POT de PowerPoint® a PNG en plataformas .NET Framework, .NET Core, Windows Azure, Mono o Xamarin" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PNG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="POT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo convertir POT a PNG usando C#" %}}

 Para convertir POT a PNG, usaremos
 [Aspose.Slides para .NET](https://products.aspose.com/slides/es/net)
 API, que es una API de manipulación y conversión de documentos rica en funciones, potente y fácil de usar para la plataforma C#. Abierto
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 administrador de paquetes, busque
 Aspose.Diapositivas
 e instalar También puede usar el siguiente comando desde la Consola del administrador de paquetes.

{{% blocks/products/pf/agp/code-block title="Comando de la consola del Administrador de paquetes" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Pasos para convertir POT a PNG a través de C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Los desarrolladores de .NET pueden cargar y convertir fácilmente archivos POT a PNG con solo unas pocas líneas de código." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cargue el archivo POT con una instancia de la clase Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Iterar a través de cada diapositiva en la presentación
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cree una imagen a escala completa como un mapa de bits con cada iteración
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Llame al método Bitmap.Save con la extensión de archivo PNG y ImageFormat.Png como parámetros
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de ejecutar el código fuente de ejemplo de conversión de .NET, asegúrese de cumplir los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con las plataformas .NET Framework, .NET Core, Windows Azure, Mono o Xamarin.
- Entorno de desarrollo como Microsoft Visual Studio.
- Aspose.Slides para .NET DLL a la que se hace referencia en su proyecto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este código de muestra muestra la conversión de POT a PNG C#" offSpacer="" %}}

```cs
using (var presentation = new Presentation("template.pot"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in PNG format
        bitmap.Save(string.Format("Slide_{0}.png", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Png);
    }
} 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="Aplicación gratuita para convertir POT a PNG" 
        sectionDescription="[Pruebe nuestra aplicación gratuita para convertir PPT a PNG](https://products.aspose.app/slides/conversion/ppt-to-png)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="También puede convertir POT a muchos otros formatos de archivo, incluidos algunos que se enumeran a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pot-to-bmp/" name="POT TO BMP" description="Imagen de mapa de bits" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pot-to-emf/" name="POT TO EMF" description="Formato de metarchivo mejorado" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pot-to-gif/" name="POT TO GIF" description="Formato de intercambio gráfico" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pot-to-html/" name="POT TO HTML" description="Lenguaje de marcado de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pot-to-jpeg/" name="POT TO JPEG" description="Imagen JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pot-to-odp/" name="POT TO ODP" description="Formato de presentación de OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pot-to-otp/" name="POT TO OTP" description="Formato estándar de OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pot-to-pdf/" name="POT TO PDF" description="Formato de Documento Portable" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pot-to-potm/" name="POT TO POTM" description="Archivo de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pot-to-potx/" name="POT TO POTX" description="Presentación de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pot-to-pps/" name="POT TO PPS" description="Presentación de diapositivas de PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pot-to-ppsm/" name="POT TO PPSM" description="Presentación de diapositivas habilitada para macros" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pot-to-ppsx/" name="POT TO PPSX" description="Presentación de diapositivas de PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pot-to-ppt/" name="POT TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pot-to-pptm/" name="POT TO PPTM" description="Archivo de presentación habilitado para macros" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pot-to-pptx/" name="POT TO PPTX" description="Formato de presentación XML abierto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pot-to-svg/" name="POT TO SVG" description="gráficas vectoriales escalables" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pot-to-swf/" name="POT TO SWF" description="Formato SWF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pot-to-tiff/" name="POT TO TIFF" description="Formato de imagen etiquetada" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pot-to-xps/" name="POT TO XPS" description="Especificaciones de papel XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}