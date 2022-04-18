---
title: Convertir POT a JPEG a través de C#
weight: 6650
url: /es/net/conversion/pot-to-jpeg/ 
description: Código de muestra para la conversión de POT a JPEG C#. Utilice el código de ejemplo API para la conversión de archivos POT por lotes a JPEG dentro de VB.NET, Asp.NET o cualquier aplicación basada en .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir POT a JPEG a través de C#" h2="Exporte archivos POT de PowerPoint® a JPEG en plataformas .NET Framework, .NET Core, Windows Azure, Mono o Xamarin" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="POT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo convertir POT a JPEG usando C#" %}}

 Para convertir POT a JPEG, usaremos
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


{{< blocks/products/pf/agp/feature-section-col title="Pasos para convertir POT a JPEG a través de C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Los desarrolladores de .NET pueden cargar y convertir fácilmente archivos POT a JPEG con solo unas pocas líneas de código." >}}

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
Llame al método Bitmap.Save con extensión de archivo JPEG e ImageFormat.Jpeg como parámetros
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

{{% blocks/products/pf/agp/code-block title="Este código de muestra muestra la conversión de POT a JPEG C#" offSpacer="" %}}

```cs
using (var presentation = new Presentation("template.pot"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in JPEG format
        bitmap.Save(string.Format("Slide_{0}.jpeg", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Jpeg);
    }
} 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Free App to Convert POT to JPEG" sectionDescription="Check our live demos for [POT to JPEG conversion](https://products.aspose.app/slides/conversion/pot-to-jpeg) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your POT file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant JPEG file." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Una biblioteca de procesamiento de presentaciones para formatos de presentación de PowerPoint y OpenOffice. La API permite que las aplicaciones lean, escriban, protejan, modifiquen y conviertan presentaciones en .NET C#. Los desarrolladores pueden usarlo para administrar texto, formas, gráficos, tablas y animaciones, agregar audio y video a las diapositivas, obtener una vista previa de las diapositivas y mucho más.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="POT" readMoreLink="https://docs.fileformat.com/presentation/pot/" >}}
Files with .POT extension represent Microsoft PowerPoint template files created by PowerPoint 97-2003 versions. Files created with these versions of Microsoft PowerPoint are in binary format as compared to those created in Office OpenXML file formats using the higher versions of PowerPoint. The files, hence, generated can be used to create presentations that have same layout and other settings required to be applied to new files. These settings can include styles, backgrounds, colour palette, fonts and defaults. Such files are generated in order to create ready-to-use template files for official use.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="jpeg" readMoreLink="https://docs.fileformat.com/image/jpeg/" >}}
A JPEG is a type of image format that is saved using the method of lossy compression. The output image, as result of compression, is a trade-off between storage size and image quality. Users can adjust the compression level to achieve the desired quality level while at the same time reduce the storage size. Image quality is negligibly affected if 10:1 compression is applied to the image.  The higher the compression value, the higher the degradation in image quality. JPEG image file format was standardized by the Joint Photographic Experts Group and, hence, the name JPEG. The format has been the choice of storing and transmitting photographic images on the web. Almost all Operating systems now have viewers that support visualization of JPEG images, which are often stored with JPG extension as well. Even the web browsers support visualization of JPEG images.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="También puede convertir POT a muchos otros formatos de archivo, incluidos algunos que se enumeran a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-bmp/" name="POT TO BMP" description="Imagen de mapa de bits" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-emf/" name="POT TO EMF" description="Formato de metarchivo mejorado" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-gif/" name="POT TO GIF" description="Formato de intercambio gráfico" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-html/" name="POT TO HTML" description="Lenguaje de marcado de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-odp/" name="POT TO ODP" description="Formato de presentación de OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-otp/" name="POT TO OTP" description="Formato estándar de OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-pdf/" name="POT TO PDF" description="Formato de Documento Portable" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-png/" name="POT TO PNG" description="Gráficos de red portátiles" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-potm/" name="POT TO POTM" description="Archivo de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-potx/" name="POT TO POTX" description="Presentación de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-pps/" name="POT TO PPS" description="Presentación de diapositivas de PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-ppsm/" name="POT TO PPSM" description="Presentación de diapositivas habilitada para macros" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-ppsx/" name="POT TO PPSX" description="Presentación de diapositivas de PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-ppt/" name="POT TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-pptm/" name="POT TO PPTM" description="Archivo de presentación habilitado para macros" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-pptx/" name="POT TO PPTX" description="Formato de presentación XML abierto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-svg/" name="POT TO SVG" description="gráficas vectoriales escalables" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-swf/" name="POT TO SWF" description="Formato SWF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-tiff/" name="POT TO TIFF" description="Formato de imagen etiquetada" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-xps/" name="POT TO XPS" description="Especificaciones de papel XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}