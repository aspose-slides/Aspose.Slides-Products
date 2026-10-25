---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Agregar una marca de agua a presentaciones ODP con C#
url: /es/net/watermark/odp/
description: Agregue marcas de agua de texto e imagen a presentaciones ODP en C# con Aspose.Slides for .NET.
keywords: agregar marca de agua a ODP, agregar marca de agua de texto a ODP, agregar marca de agua de imagen a ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Agregar una marca de agua a una presentación ODP con C#" h2="Cree aplicaciones .NET que inserten marcas de agua de texto o imagen en archivos de presentación." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Agregar una marca de agua a una presentación ODP mediante C#" variant="code" %}}

Con [Aspose.Slides for .NET](/slides/es/net/), puede agregar marcas de agua de texto e imagen a presentaciones ODP. Agregue una forma de marca de agua a un patrón de diapositivas para que aparezca en las diapositivas que usan ese patrón.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Agregar una marca de agua de texto a ODP con C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");

var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
var watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");
watermarkTextFrame.Paragraphs[0].Portions[0].PortionFormat.FontHeight = 48;

presentation.Save("watermarked-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Agregar una marca de agua de imagen a una presentación ODP con C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");

var imageData = File.ReadAllBytes("watermark.png");
var watermarkImage = presentation.Images.AddImage(imageData);
var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

watermarkShape.FillFormat.FillType = FillType.Picture;
watermarkShape.FillFormat.PictureFillFormat.Picture.Image = watermarkImage;
watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

presentation.Save("image-watermarked-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo agregar una marca de agua a ODP con C#" intro="Siga estos pasos para agregar una marca de agua de texto o imagen a archivos ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo `ODP` con la clase `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Seleccione un patrón de diapositivas de la colección `Presentation.Masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Llame al método `AddAutoShape` para agregar una forma de marca de agua.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Llame al método `AddTextFrame` para agregar el texto de la marca de agua o use `AddImage` para una marca de agua de imagen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Guarde el archivo con marca de agua con `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Creado con Aspose.Slides" title="Agregue marcas de agua a archivos ODP en línea" description="La aplicación gratuita Aspose.Slides Watermark está creada con [Aspose.Slides for .NET](https://products.aspose.com/slides/es/net/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos ODP." button="Abrir Aspose.Slides Watermark" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides agrega marcas de agua antes de escribir código.
- Agregue una marca de agua de texto o imagen a su archivo ODP.
- Descargue el archivo con marca de agua.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos compatibles con marcas de agua" subTitle="Con C#, también puede agregar marcas de agua a los siguientes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/net/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/net/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
