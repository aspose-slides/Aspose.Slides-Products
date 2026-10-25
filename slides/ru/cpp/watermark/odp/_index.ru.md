---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Добавление водяного знака в презентации ODP на C++
url: /ru/cpp/watermark/odp/
description: Добавляйте текстовые или графические водяные знаки в презентации ODP на C++. С помощью Aspose.Slides for C++ можно размещать водяные знаки на слайдах.
keywords: добавить водяной знак в ODP, добавить текстовый водяной знак в ODP, добавить графический водяной знак в ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Добавление водяного знака в презентацию ODP на C++" h2="Добавляйте текстовые или графические водяные знаки в файлы презентаций без Microsoft PowerPoint с помощью Aspose.Slides for C++." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Добавление водяного знака в презентацию ODP с помощью C++" variant="code" %}}

Aspose.Slides for C++ позволяет добавлять текстовые или графические водяные знаки в презентации ODP. Добавьте фигуру водяного знака на образец слайдов с помощью `AddAutoShape`, добавьте текст с помощью `AddTextFrame` или заполните фигуру изображением, загруженным через `File::ReadAllBytes` и `AddImage`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Добавление текстового водяного знака в ODP на C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Добавление графического водяного знака в презентацию ODP на C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 200);

auto imageData = File::ReadAllBytes(u"watermark.png");
auto watermarkImage = presentation->get_Images()->AddImage(imageData);

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(watermarkImage);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"image-watermarked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как добавить водяной знак в ODP на C++" intro="Выполните следующие шаги, чтобы добавить текстовый или графический водяной знак в файлы ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл ODP с помощью класса `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Выберите образец слайдов из коллекции `Presentation::get_Masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Добавьте фигуру водяного знака с помощью метода `AddAutoShape`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Добавьте текст водяного знака с помощью метода `AddTextFrame` или задайте заливку рисунком с помощью `AddImage`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохраните файл с водяным знаком с помощью `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Создано на основе Aspose.Slides" title="Добавляйте водяные знаки в файлы ODP онлайн" description="Бесплатное приложение Aspose.Slides Watermark создано на основе [Aspose.Slides for C++](https://products.aspose.com/slides/ru/cpp/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами ODP." button="Открыть Aspose.Slides Watermark" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides добавляет водяные знаки, ещё до написания кода.
- Добавьте текстовый или графический водяной знак в файл ODP.
- Скачайте файл с водяным знаком.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие форматы с поддержкой водяных знаков" subTitle="С помощью C++ можно также добавлять водяные знаки в следующие форматы." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/cpp/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/cpp/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
