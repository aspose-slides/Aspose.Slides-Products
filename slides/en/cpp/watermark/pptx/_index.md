---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Add Watermark to PPTX Presentations using C++
url: /cpp/watermark/pptx/
keywords: Add Watermark PPTX, Add Text Watermark PPTX, Add Image Watermark PPTX
description: Add text or image watermarks to PPTX presentations in C++. Use Aspose.Slides for C++ to place watermarks on presentation slides.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Add Watermark to PPTX Presentation using C++" h2="Use Aspose.Slides for C++ to add text or image watermarks to presentation files without Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Add Watermark to PPTX Presentation via C++" variant="code" %}}

Aspose.Slides for C++ lets you add text or image watermarks to PPTX presentations. Add a watermark shape to the master slide with `AddAutoShape`, add text with `AddTextFrame`, or fill the shape with an image loaded through `File::ReadAllBytes` and `AddImage`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Add Text Watermark to PPTX using C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Add Image Watermark to PPTX Presentation using C++" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Add Watermark to PPTX via C++" intro="Follow these steps to add a text or image watermark to PPTX files." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the PPTX file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Select the master slide from the `Presentation::get_Masters` collection.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add a watermark shape with the `AddAutoShape` method.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add watermark text with the `AddTextFrame` method or set a picture fill with `AddImage`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the watermarked file with `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Watermark Formats" subTitle="Using C++, you can also add watermarks to the following formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
