---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Преобразование PPSX в BMP через Java
weight: 7090
url: /ru/java/conversion/ppsx-to-bmp/ 
description: Пример кода преобразования Java для формата PPSX в файл BMP. Используйте этот пример кода для экспорта презентаций PowerPoint и OpenOffice в формат BMP в любом веб- или настольном приложении на основе Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Преобразование PPSX в BMP через Java" h2="Преобразование PPSX в BMP Java для преобразования одной или нескольких страниц в BMP с использованием локальной библиотеки Java."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Как конвертировать PPSX в BMP с помощью Java" %}}

Чтобы преобразовать PPSX в BMP, мы будем использовать
 [Aspose.Slides для Java](https://products.aspose.com/slides/ru/java/)
 API, который представляет собой многофункциональный, мощный и простой в использовании API преобразования для платформы Java. Вы можете скачать его последнюю версию прямо с
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 и установите его в своем проекте на основе Maven, добавив следующие конфигурации в файл pom.xml.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Репозиторий" >}}
```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Зависимость" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="Исходный код преобразования PPSX в BMP Java" >}}
```cs
// load PPSX with Aspose.Slides
Presentation presentation = new Presentation("template.ppsx");
   
    // iterate over all slides in the presentation
for (ISlide sld : presentation.getSlides()) 
{
  
  // create a full scale image of each slide
  BufferedImage bi = sld.getThumbnail(new RenderingOptions());

  // create a new file of type BMP for every slide
  File outputfile = new File(sld.getSlideNumber() + ".bmp");
  
  // save the slide image to disk
  ImageIO.write(bi, "bmp", outputfile);
}   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Шаги для преобразования PPSX в BMP через Java" intro="Разработчики Java могут легко преобразовать файл PPSX в BMP всего за несколько строк кода." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл PPSX с экземпляром класса Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Повторите каждый слайд в презентации.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Создавайте полномасштабное изображение в виде растрового изображения с каждой итерацией.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите метод Bitmap.save с расширением файла BMP и ImageFormat.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Системные Требования" intro="Перед запуском примера кода преобразования Java убедитесь, что выполнены следующие предварительные условия." %}}

- Microsoft Windows или совместимая ОС со средой выполнения Java для приложений JSP/JSF и настольных приложений.
- Получите последнюю версию Aspose.Slides для Java прямо из Maven.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Бесплатное приложение для преобразования PPSX в BMP"
  description="[Попробуйте наше бесплатное приложение, чтобы преобразовать PPT в BMP](https://products.aspose.app/slides/conversion/ppt-to-bmp)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать PPSX во многие другие форматы файлов, включая некоторые из перечисленных ниже." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="Графический формат обмена" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/ppsx-to-html/" name="PPSX TO HTML" description="Язык гипертекстовой разметки" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/ppsx-to-jpeg/" name="PPSX TO JPEG" description="Изображение в формате JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="Формат презентации OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="Стандартный формат OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="Портативный формат документа" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/ppsx-to-png/" name="PPSX TO PNG" description="Портативная сетевая графика" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/ppsx-to-pot/" name="PPSX TO POT" description="Файлы шаблонов Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="Файл шаблона Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Презентация шаблона Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="Слайд-шоу PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="Слайд-шоу с поддержкой макросов" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="Файл презентации с поддержкой макросов" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="Формат презентации Open XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="Масштабируемая векторная графика" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/ppsx-to-swf/" name="PPSX TO SWF" description="SWF-формат" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="Формат изображения с тегами" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="Спецификации XML-бумаги" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
