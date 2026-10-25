---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Добавление водяного знака в презентации PPTX на C#
url: /ru/net/watermark/pptx/
description: Добавляйте текстовые и графические водяные знаки в презентации PPTX на C# с помощью Aspose.Slides for .NET.
keywords: добавить водяной знак в PPTX, добавить текстовый водяной знак в PPTX, добавить графический водяной знак в PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Добавление водяного знака в презентацию PPTX на C#" h2="Создавайте приложения .NET, которые вставляют текстовые или графические водяные знаки в файлы презентаций." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Добавление водяного знака в презентацию PPTX с помощью C#" variant="code" %}}

С помощью [Aspose.Slides for .NET](/slides/ru/net/) можно добавлять текстовые и графические водяные знаки в презентации PPTX. Добавьте фигуру водяного знака на образец слайдов, чтобы водяной знак отображался на всех слайдах, которые используют этот образец.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Добавление текстового водяного знака в PPTX на C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
var watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");
watermarkTextFrame.Paragraphs[0].Portions[0].PortionFormat.FontHeight = 48;

presentation.Save("watermarked-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Добавление графического водяного знака в презентацию PPTX на C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var imageData = File.ReadAllBytes("watermark.png");
var watermarkImage = presentation.Images.AddImage(imageData);
var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

watermarkShape.FillFormat.FillType = FillType.Picture;
watermarkShape.FillFormat.PictureFillFormat.Picture.Image = watermarkImage;
watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

presentation.Save("image-watermarked-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как добавить водяной знак в PPTX на C#" intro="Выполните следующие шаги, чтобы добавить текстовый или графический водяной знак в файлы PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл `PPTX` с помощью класса `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Выберите образец слайдов из коллекции `Presentation.Masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите метод `AddAutoShape`, чтобы добавить фигуру водяного знака.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите метод `AddTextFrame`, чтобы добавить текст водяного знака, или используйте `AddImage` для графического водяного знака.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохраните файл с водяным знаком с помощью `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Создано на основе Aspose.Slides" title="Добавляйте водяные знаки в файлы PPTX онлайн" description="Бесплатное приложение Aspose.Slides Watermark создано на основе [Aspose.Slides for .NET](https://products.aspose.com/slides/ru/net/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами PPTX." button="Открыть Aspose.Slides Watermark" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides добавляет водяные знаки, ещё до написания кода.
- Добавьте текстовый или графический водяной знак в файл PPTX.
- Скачайте файл с водяным знаком.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие форматы с поддержкой водяных знаков" subTitle="С помощью C# можно также добавлять водяные знаки в следующие форматы." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/net/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
