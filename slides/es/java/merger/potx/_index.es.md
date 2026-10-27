---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Combinar archivos POTX a través de Java
weight: 4290
url: /es/java/merger/potx/ 
description: Código de muestra de Java para combinar documentos POTX en Java Runtime Environment para aplicaciones JSP/JSF y aplicaciones de escritorio.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Combinar formatos POTX en Java" h2="Fusión nativa de documentos POTX utilizando API de Java del lado del servidor."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="ODP,OTP,POT,POTM,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cómo fusionar archivos POTX usando Java" %}}

Para fusionar el archivo POTX, usaremos
 [Aspose.Slides para Java](https://products.aspose.com/slides/es/java/)
 API que es una API de fusión rica en funciones, potente y fácil de usar para la plataforma Java. Puedes descargar su última versión directamente desde
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="Fusionar archivos POTX - Java" >}}
```cs
// Load first POTX File
Presentation prest1 = new Presentation("prest1.potx");

// Load second POTX File
Presentation prest2 = new Presentation("prest2.potx");

// Merge
for (ISlide slide : prest2.getSlides()) {
	// Merge from source to target
	prest1.getSlides().addClone(slide);
}

// Save the File
prest1.save("merged-presentation.potx", SaveFormat.Potx);  

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Pasos para fusionar archivos POTX en Java" intro="Se puede realizar una fusión y concatenación de documentos básicos con [Aspose.Slides for Java](https://products.aspose.com/slides/es/java/) API con solo unas pocas líneas de código." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el primer archivo POTX con una instancia de la clase Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el segundo documento POTX con una instancia de la clase Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Recorra cada diapositiva del segundo archivo POTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Con cada iteración, use addClone() para agregar diapositivas con el primer archivo.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Use el método save () para guardar en la ruta especificada{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisitos del sistema" intro="Aspose.Slides para Java es compatible con todas las principales plataformas y sistemas operativos. Por favor, asegúrese de que tiene los siguientes requisitos previos." %}}

- Microsoft Windows o un sistema operativo compatible con Java Runtime Environment para aplicaciones JSP/JSF y aplicaciones de escritorio.
- Obtenga la última versión de Aspose.Slides para Java directamente desde [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides) .

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension=""
  title="Combinar archivos PDF en línea"
  description="[Cómo fusionar PDF en Python](https://products.aspose.com/slides/es/python-net/merge/pdf/)" >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="POTX" readMoreLink="https://docs.fileformat.com/presentation/potx/" %}}

Los archivos con la extensión `.POTX` son plantillas de presentación de Microsoft PowerPoint creadas con PowerPoint 2007 y versiones posteriores. Un archivo `POTX` puede almacenar diseños, estilos, temas, fondos, fuentes y valores predeterminados para crear nuevas presentaciones.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos de fusión admitidos" subTitle="Usando Java, One también puede fusionar muchos otros formatos de archivo, incluidos .." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/merger/odp/" name="ODP" description="Formato de presentación de OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/merger/otp/" name="OTP" description="Formato estándar de OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/merger/pot/" name="POT" description="Archivos de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/merger/potm/" name="POTM" description="Archivo de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/merger/pps/" name="PPS" description="Presentación de diapositivas de PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/merger/ppsm/" name="PPSM" description="Presentación de diapositivas habilitada para macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/merger/ppsx/" name="PPSX" description="Presentación de diapositivas de PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/merger/pptm/" name="PPTM" description="Archivo de presentación habilitado para macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/merger/pptx/" name="PPTX" description="Formato de presentación XML abierto" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
