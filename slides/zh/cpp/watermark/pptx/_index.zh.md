---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 C++ 为 PPTX 演示文稿添加水印
url: /zh/cpp/watermark/pptx/
description: 在 C++ 中为 PPTX 演示文稿添加文本或图片水印。使用 Aspose.Slides for C++ 在幻灯片上放置水印。
keywords: 为 PPTX 添加水印, 为 PPTX 添加文本水印, 为 PPTX 添加图片水印
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C++ 为 PPTX 演示文稿添加水印的方法" h2="使用 Aspose.Slides for C++，无需 Microsoft PowerPoint 即可为演示文稿文件添加文本或图片水印。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="通过 C++ 为 PPTX 演示文稿添加水印" variant="code" %}}

借助 Aspose.Slides for C++，可以为 PPTX 演示文稿添加文本或图片水印。使用 `AddAutoShape` 在母版幻灯片上添加水印形状，使用 `AddTextFrame` 添加文本，或使用通过 `File::ReadAllBytes` 和 `AddImage` 加载的图片填充形状。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C++ 为 PPTX 添加文本水印" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C++ 为 PPTX 演示文稿添加图片水印" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 C++ 为 PPTX 添加水印" intro="按照以下步骤为 PPTX 文件添加文本或图片水印。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 类加载 PPTX 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}从 `Presentation::get_Masters` 集合中选择母版幻灯片。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `AddAutoShape` 方法添加水印形状。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `AddTextFrame` 方法添加水印文本，或使用 `AddImage` 设置图片填充。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat::Pptx` 保存带水印的文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="基于 Aspose.Slides 构建" title="在线为 PPTX 文件添加水印" description="免费的 Aspose.Slides Watermark 应用基于 [Aspose.Slides for C++](https://products.aspose.com/slides/zh/cpp/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 PPTX 文件。" button="打开 Aspose.Slides Watermark" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先看看 Aspose.Slides 如何添加水印。
- 为 PPTX 文件添加文本或图片水印。
- 下载带水印的文件。
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持水印的格式" subTitle="使用 C++，还可以为以下格式添加水印。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/cpp/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
