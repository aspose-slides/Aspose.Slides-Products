---
title: Convertir PPS a PNG a través de Java
weight: 8390
url: /es/java/conversion/pps-to-png/ 
description: Ejemplo de código de conversión de Java para formato PPS a archivo PNG. Utilice este código de ejemplo para exportar presentaciones de PowerPoint y OpenOffice a PNG dentro de cualquier aplicación web o de escritorio basada en Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir PPS a PNG a través de Java" h2="Conversión de PPS a PNG Java para convertir una o varias páginas a PNG utilizando la biblioteca Java local." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PNG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Cómo convertir PPS a PNG usando Java" %}}

 Para renderizar PPS a PNG, usaremos
 [Aspose.Slides para Java](https://products.aspose.com/slides/java)
 API que es una API de conversión rica en funciones, potente y fácil de usar para la plataforma Java. Puedes descargar su última versión directamente desde
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 e instálelo dentro de su proyecto basado en Maven agregando las siguientes configuraciones al pom.xml.

{{% blocks/products/pf/agp/code-block title="Repositorio" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dependencia" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-slides</artifactId>
<version>version of aspose-slides API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Pasos para convertir PPS a PNG a través de Java" %}}

{{% blocks/products/pf/agp/text %}}

 Los desarrolladores de Java pueden convertir fácilmente un archivo PPS a PNG con solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1. Cargue el archivo PPS con una instancia de la clase Presentation
1. Iterar a través de cada diapositiva en la presentación
1. Cree una imagen a escala completa como mapa de bits con cada iteración
1. Llame al método Bitmap.save con extensión de archivo PNG e ImageFormat

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de ejecutar el código de ejemplo de conversión de Java, asegúrese de cumplir los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con Java Runtime Environment para aplicaciones JSP/JSF y aplicaciones de escritorio.
- Obtenga la última versión de Aspose.Slides para Java directamente de Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código fuente de conversión de PPS a PNG Java" offSpacer="" %}}

```cs
// load PPS with Aspose.Slides
Presentation presentation = new Presentation("template.pps");
   
    // iterate over all slides in the presentation
for (ISlide sld : presentation.getSlides()) 
{
  
  // create a full scale image of each slide
  BufferedImage bi = sld.getThumbnail(new RenderingOptions());

  // create a new file of type PNG for every slide
  File outputfile = new File(sld.getSlideNumber() + ".png");
  
  // save the slide image to disk
  ImageIO.write(bi, "png", outputfile);
}   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="PPS to PNG Conversion Live Demos" sectionDescription="[Convert PPS to PNG](https://products.aspose.app/slides/conversion/pps-to-png) right now by visiting our Live Demos website.The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PPS file, it will be converted instantly to PNG." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will get the download link." >}}

    {{% blocks/products/pf/agp/content h2="Biblioteca de manipulación de presentaciones Java" %}}

 Slides and Presentation API se puede utilizar para leer, escribir, manipular y convertir documentos de Microsoft PowerPoint a PDF, XPS, HTML, TIFF, ODP y varios otros formatos. Uno puede crear nuevos archivos desde cero y guardarlos en los formatos compatibles relevantes. Aspose.Slides es una API independiente para crear, analizar o manipular presentaciones, diapositivas y elementos y no depende de ningún software como Microsoft u OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPS" readMoreLink="https://docs.fileformat.com/presentation/pps/" >}}

PPS, PowerPoint Slide Show, files are created using Microsoft PowerPoint for Slide Show purpose. PPS file reading and creation is supported by Microsoft PowerPoint 97-2003. The more latest version of this file format is PPSX which is based on Office OpenXML standards. PPS files can still be read by latest versions of Microsoft PowerPoint, but newly created files can only be saved in PPSX file format. When a PPS file is shared with another user and opened, it starts as Powerpoint show unlike PPT file which opens in editable mode.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PNG" readMoreLink="https://docs.fileformat.com/image/png/" >}}

PNG, Portable Network Graphics, refers to a type of raster image file format that use loseless compression. This file format was created as a replacement of Graphics Interchange Format (GIF) and has no copyright limitations. However, PNG file format does not support animations. PNG file format supports loseless image compression that makes it popular among its users. With the passage of time, PNG has evolved as one of the mostly used image file format. Almost all Operating Systems have support for opening PNG files. For example, Microsoft Windows viewer has the capability to open PNG files as the OS has by default the support available as part of installation.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="También puede convertir PPS a muchos otros formatos de archivo, incluidos algunos que se enumeran a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-bmp/" name="PPS TO BMP" description="Imagen de mapa de bits" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-gif/" name="PPS TO GIF" description="Formato de intercambio gráfico" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-html/" name="PPS TO HTML" description="Lenguaje de marcado de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-jpeg/" name="PPS TO JPEG" description="Imagen JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-odp/" name="PPS TO ODP" description="Formato de presentación de OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-otp/" name="PPS TO OTP" description="Formato estándar de OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-pdf/" name="PPS TO PDF" description="Formato de Documento Portable" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-pot/" name="PPS TO POT" description="Archivos de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-potm/" name="PPS TO POTM" description="Archivo de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-potx/" name="PPS TO POTX" description="Presentación de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-ppsm/" name="PPS TO PPSM" description="Presentación de diapositivas habilitada para macros" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-ppsx/" name="PPS TO PPSX" description="Presentación de diapositivas de PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-ppt/" name="PPS TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-pptm/" name="PPS TO PPTM" description="Archivo de presentación habilitado para macros" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-pptx/" name="PPS TO PPTX" description="Formato de presentación XML abierto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-svg/" name="PPS TO SVG" description="gráficas vectoriales escalables" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-swf/" name="PPS TO SWF" description="Formato SWF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-tiff/" name="PPS TO TIFF" description="Formato de imagen etiquetada" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-xps/" name="PPS TO XPS" description="Especificaciones de papel XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}