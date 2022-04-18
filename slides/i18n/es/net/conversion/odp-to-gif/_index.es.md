---
title: Convierta ODP a GIF a través de C#
weight: 2280
url: /es/net/conversion/odp-to-gif/ 
description: Código de muestra para la conversión de C# de ODP a GIF. Utilice el código de ejemplo de API para la conversión de archivos ODP por lotes a GIF dentro de VB.NET, Asp.NET o cualquier aplicación basada en .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Convierta ODP a GIF a través de C#" h2="Exporte archivos ODP de PowerPoint® a GIF en las plataformas .NET Framework, .NET Core, Windows Azure, Mono o Xamarin" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo convertir ODP a GIF usando C#" %}}

 Para convertir ODP a GIF, usaremos
 [Aspose.Slides para .NET](https://products.aspose.com/slides/net)
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


{{< blocks/products/pf/agp/feature-section-col title="Pasos para convertir ODP a GIF a través de C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Los desarrolladores de .NET pueden cargar y convertir fácilmente archivos ODP a GIF con solo unas pocas líneas de código." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cargue el archivo ODP con una instancia de la clase Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Iterar a través de cada diapositiva en la presentación
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cree una imagen a escala completa como un mapa de bits con cada iteración
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Llame al método Bitmap.Save con extensión de archivo GIF e ImageFormat.Gif como parámetros
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

{{% blocks/products/pf/agp/code-block title="Este código de muestra muestra la conversión de ODP a GIF C#" offSpacer="" %}}

```cs
using (var presentation = new Presentation("template.odp"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in GIF format
        bitmap.Save(string.Format("Slide_{0}.gif", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Gif);
    }
} 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Free App to Convert ODP to GIF" sectionDescription="Check our live demos for [ODP to GIF conversion](https://products.aspose.app/slides/conversion/odp-to-gif) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your ODP file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant GIF file." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Una biblioteca de procesamiento de presentaciones para formatos de presentación de PowerPoint y OpenOffice. La API permite que las aplicaciones lean, escriban, protejan, modifiquen y conviertan presentaciones en .NET C#. Los desarrolladores pueden usarlo para administrar texto, formas, gráficos, tablas y animaciones, agregar audio y video a las diapositivas, obtener una vista previa de las diapositivas y mucho más.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" >}}
Files with ODP extension represent presentation file format used by OpenOffice.org in the OASISOpen standard. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. ODP files can be opened by applications that conform to the OpenDocument format (such as OpenOffice or StarOffice).

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="gif" readMoreLink="https://docs.fileformat.com/image/gif/" >}}
A GIF or Graphical Interchange Format is a type of highly compressed image. Owned by Unisys, GIF uses the LZW compression algorithm that does not degrade the image quality. For each image GIF typically allow up to 8 bits per pixel and up to 256 colours are allowed across the image. In contrast to a JPEG image, which can display up to 16 million colours and fairly touches the limits of the human eye. Back when the internet emerged, GIFs remained the best choice because they required low bandwidth and compatible for the graphics that consume solid areas of colour. An animated GIF combines numerous images or frames into a single file and displays them in a sequence to generate an animated clip or a short video. The colour limitations are up to 256 for each frame and are likely to be the least suitable for reproducing other images and photographs with colour gradient.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="También puede convertir ODP a muchos otros formatos de archivo, incluidos algunos que se enumeran a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-bmp/" name="ODP TO BMP" description="Imagen de mapa de bits" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-emf/" name="ODP TO EMF" description="Formato de metarchivo mejorado" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-html/" name="ODP TO HTML" description="Lenguaje de marcado de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-jpeg/" name="ODP TO JPEG" description="Imagen JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-otp/" name="ODP TO OTP" description="Formato estándar de OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-pdf/" name="ODP TO PDF" description="Formato de Documento Portable" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-png/" name="ODP TO PNG" description="Gráficos de red portátiles" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-pot/" name="ODP TO POT" description="Archivos de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-potm/" name="ODP TO POTM" description="Archivo de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-potx/" name="ODP TO POTX" description="Presentación de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-pps/" name="ODP TO PPS" description="Presentación de diapositivas de PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="Presentación de diapositivas habilitada para macros" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="Presentación de diapositivas de PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-ppt/" name="ODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-pptm/" name="ODP TO PPTM" description="Archivo de presentación habilitado para macros" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-pptx/" name="ODP TO PPTX" description="Formato de presentación XML abierto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-svg/" name="ODP TO SVG" description="gráficas vectoriales escalables" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-swf/" name="ODP TO SWF" description="Formato SWF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-tiff/" name="ODP TO TIFF" description="Formato de imagen etiquetada" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-xps/" name="ODP TO XPS" description="Especificaciones de papel XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}