---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Конвертировать PNG в PPT на Java
url: /ru/java/conversion/png-to-ppt/
keywords: Преобразование PNG в PPT, PNG в PPT, PowerPoint, PNG, PPT, Java API, библиотека Java
description: Конвертируйте PNG в PPT на Java. Используйте API библиотеки Java для преобразования изображений PNG в PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Конвертировать PNG в PPT на Java" h2="Мощный кроссплатформенный Java API для преобразования PNG в PPT с использованием кода Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Конвертировать PNG в PPT на Java" variant="code" %}}

Используя [**Aspose.Slides for Java**](https://products.aspose.com/slides/ru/java/), вы можете преобразовать изображение PNG в презентацию PowerPoint всего несколькими строками кода:

{{< blocks/products/pf/slides-design-update-10-2026/code title="Код Java для преобразования PNG в PPT" >}}
```java
Presentation pres = new Presentation();
try {
	ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);

	pres.save("pres.ppt", SaveFormat.Ppt);
} finally {
	if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование PNG в PPT с помощью Aspose.Slides" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/ru/java/) — это мощная библиотека Java, используемая для создания, преобразования и управления презентациями PowerPoint, PDF-файлами, HTML-документами и другими документами. файлы. Когда вы конвертируете PNG в PPT, вы, по сути, создаете презентацию PowerPoint, содержащую слайды на основе изображений PNG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как конвертировать PNG в PPT на Java" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите **Aspose.Slides для Java**. См. [**Установка**](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Добавьте библиотеку в качестве ссылки в свой проект.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Создайте экземпляр класса Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите изображение PNG, которое вы хотите преобразовать в PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохраните полученный файл как презентацию PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Бесплатный онлайн-конвертер"
  description="[Как преобразовать PPT в HTML в Python](https://products.aspose.com/slides/ru/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые преобразования PowerPoint" subTitle="Вы также можете конвертировать файлы в других форматах в PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
