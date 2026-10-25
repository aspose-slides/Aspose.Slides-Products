---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Добавление водяного знака в файлы презентаций ODP на Java
url: /ru/java/watermark/odp/
description: Добавляйте текстовые и графические водяные знаки в презентации ODP на Java с помощью Aspose.Slides for Java.
keywords: добавить водяной знак в ODP, добавить текстовый водяной знак в ODP, добавить графический водяной знак в ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Добавление водяного знака в презентацию ODP на Java" h2="Создавайте приложения на Java, которые с помощью серверных API вставляют текстовые или графические водяные знаки в файлы презентаций." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Добавление водяного знака в презентацию ODP с помощью Java" variant="code" %}}

С помощью [Aspose.Slides for Java](/slides/ru/java/) можно добавлять текстовые и графические водяные знаки в презентации ODP. Добавьте фигуру водяного знака на образец слайдов, чтобы водяной знак отображался на всех слайдах, которые используют этот образец.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Добавление текстового водяного знака в ODP на Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
    watermarkTextFrame.getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().setFontHeight(48);

    presentation.save("watermark.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Добавление графического водяного знака в презентацию ODP на Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    byte[] imageData = Files.readAllBytes(Paths.get("watermark.png"));
    IPPImage watermarkImage = presentation.getImages().addImage(imageData);
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(watermarkImage);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    presentation.save("image-watermark.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как добавить водяной знак в ODP на Java" intro="Выполните следующие шаги, чтобы добавить текстовый или графический водяной знак в файлы ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл `ODP` с помощью класса `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Выберите образец слайдов с помощью метода `getMasters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите метод `addAutoShape`, чтобы добавить фигуру водяного знака.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите метод `addTextFrame`, чтобы добавить текст водяного знака, или используйте `addImage` для графического водяного знака.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохраните презентацию с водяным знаком в формате ODP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Создано на основе Aspose.Slides" title="Добавляйте водяные знаки в файлы ODP онлайн" description="Бесплатное приложение Aspose.Slides Watermark создано на основе [Aspose.Slides for Java](https://products.aspose.com/slides/ru/java/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами ODP." button="Открыть Aspose.Slides Watermark" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides добавляет водяные знаки, ещё до написания кода.
- Добавьте текстовый или графический водяной знак в файл ODP.
- Скачайте файл с водяным знаком.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие форматы с поддержкой водяных знаков" subTitle="С помощью Java можно также добавлять водяные знаки в следующие форматы." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/java/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/java/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
