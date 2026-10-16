---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convierta ODP a XPS a través de Java
weight: 4880
url: /es/java/conversion/odp-to-xps/ 
description: Ejemplo de código de conversión de Java para formato ODP a archivo XPS. Utilice este código de ejemplo para exportar presentaciones de PowerPoint y OpenOffice a XPS dentro de cualquier aplicación web o de escritorio basada en Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convierta ODP a XPS a través de Java" h2="Conversión de ODP a XPS Java para convertir páginas únicas o múltiples a XPS utilizando la biblioteca Java local."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cómo convertir ODP a XPS usando Java" %}}

Para convertir ODP a XPS, usaremos
 [Aspose.Slides para Java](https://products.aspose.com/slides/es/java/)
 API que es una API de conversión rica en funciones, potente y fácil de usar para la plataforma Java. Puedes descargar su última versión directamente desde
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 e instálelo dentro de su proyecto basado en Maven agregando las siguientes configuraciones al pom.xml.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Repositorio" >}}
```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Dependencia" >}}
```xml

<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Código fuente de conversión de ODP a XPS Java" >}}
```cs
// instantiate a Presentation object that represents a ODP file
Presentation presentation = new Presentation("template.odp");
// save the presentation as XPS
presentation.save("output.xps", SaveFormat.Xps);   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Pasos para convertir ODP a XPS a través de Java" intro="Los desarrolladores de Java pueden convertir fácilmente un archivo ODP a XPS con solo unas pocas líneas de código." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo ODP con una instancia de la clase Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Llame al método Presentation.save mientras especifica la ruta del archivo de salida y SaveFormat{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}El archivo XPS se guardará en la ruta especificada{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisitos del sistema" intro="Antes de ejecutar el código de ejemplo de conversión de Java, asegúrese de cumplir los siguientes requisitos previos." %}}

- Microsoft Windows o un sistema operativo compatible con Java Runtime Environment para aplicaciones JSP/JSF y aplicaciones de escritorio.
- Obtenga la última versión de Aspose.Slides para Java directamente de Maven.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension="odp-to-xps"
  title="Aplicación gratuita para convertir ODP a XPS"
  description="[Pruebe nuestra aplicación gratuita Video](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otras conversiones admitidas" subTitle="También puede convertir ODP a muchos otros formatos de archivo, incluidos algunos que se enumeran a continuación." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/odp-to-bmp/" name="ODP TO BMP" description="Imagen de mapa de bits" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/odp-to-gif/" name="ODP TO GIF" description="Formato de intercambio gráfico" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/odp-to-html/" name="ODP TO HTML" description="Lenguaje de marcado de hipertexto" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/odp-to-jpeg/" name="ODP TO JPEG" description="Imagen JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/odp-to-otp/" name="ODP TO OTP" description="Formato estándar de OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/odp-to-pdf/" name="ODP TO PDF" description="Formato de Documento Portable" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/odp-to-png/" name="ODP TO PNG" description="Gráficos de red portátiles" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/odp-to-pot/" name="ODP TO POT" description="Archivos de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/odp-to-potm/" name="ODP TO POTM" description="Archivo de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/odp-to-potx/" name="ODP TO POTX" description="Presentación de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/odp-to-pps/" name="ODP TO PPS" description="Presentación de diapositivas de PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="Presentación de diapositivas habilitada para macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="Presentación de diapositivas de PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/odp-to-ppt/" name="ODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/odp-to-pptm/" name="ODP TO PPTM" description="Archivo de presentación habilitado para macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/odp-to-pptx/" name="ODP TO PPTX" description="Formato de presentación XML abierto" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/odp-to-svg/" name="ODP TO SVG" description="gráficas vectoriales escalables" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/odp-to-swf/" name="ODP TO SWF" description="Formato SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/odp-to-tiff/" name="ODP TO TIFF" description="Formato de imagen etiquetada" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
