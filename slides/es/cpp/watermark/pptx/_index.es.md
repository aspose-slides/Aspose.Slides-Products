---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Agregar una marca de agua a presentaciones PPTX con C++
url: /es/cpp/watermark/pptx/
description: Agregue marcas de agua de texto o imagen a presentaciones PPTX en C++. Use Aspose.Slides for C++ para colocar marcas de agua en las diapositivas.
keywords: agregar marca de agua a PPTX, agregar marca de agua de texto a PPTX, agregar marca de agua de imagen a PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Agregar una marca de agua a una presentación PPTX con C++" h2="Use Aspose.Slides for C++ para agregar marcas de agua de texto o imagen a archivos de presentación sin Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Agregar una marca de agua a una presentación PPTX mediante C++" variant="code" %}}

Aspose.Slides for C++ permite agregar marcas de agua de texto o imagen a presentaciones PPTX. Agregue una forma de marca de agua al patrón de diapositivas con `AddAutoShape`, agregue texto con `AddTextFrame` o rellene la forma con una imagen cargada mediante `File::ReadAllBytes` y `AddImage`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Agregar una marca de agua de texto a PPTX con C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Agregar una marca de agua de imagen a una presentación PPTX con C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 200);

auto imageData = File::ReadAllBytes(u"watermark.png");
auto watermarkImage = presentation->get_Images()->AddImage(imageData);

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(watermarkImage);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"image-watermarked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo agregar una marca de agua a PPTX con C++" intro="Siga estos pasos para agregar una marca de agua de texto o imagen a archivos PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo PPTX con la clase `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Seleccione el patrón de diapositivas de la colección `Presentation::get_Masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Agregue una forma de marca de agua con el método `AddAutoShape`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Agregue el texto de la marca de agua con el método `AddTextFrame` o defina un relleno de imagen con `AddImage`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Guarde el archivo con marca de agua con `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Creado con Aspose.Slides" title="Agregue marcas de agua a archivos PPTX en línea" description="La aplicación gratuita Aspose.Slides Watermark está creada con [Aspose.Slides for C++](https://products.aspose.com/slides/es/cpp/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos PPTX." button="Abrir Aspose.Slides Watermark" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides agrega marcas de agua antes de escribir código.
- Agregue una marca de agua de texto o imagen a su archivo PPTX.
- Descargue el archivo con marca de agua.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos compatibles con marcas de agua" subTitle="Con C++, también puede agregar marcas de agua a los siguientes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
