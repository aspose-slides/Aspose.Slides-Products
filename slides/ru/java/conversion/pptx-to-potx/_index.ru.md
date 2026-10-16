---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Преобразование PPTX в POTX через Java
weight: 6510
url: /ru/java/conversion/pptx-to-potx/ 
description: Пример кода преобразования Java для формата PPTX в файл POTX. Используйте этот пример кода для экспорта презентаций PowerPoint и OpenOffice в POTX в любом веб- или настольном приложении на основе Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Преобразование PPTX в POTX через Java" h2="Преобразование PPTX в POTX Java для преобразования одной или нескольких страниц в POTX с использованием локальной библиотеки Java."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Как преобразовать PPTX в POTX с помощью Java" %}}

Чтобы преобразовать PPTX в POTX, мы будем использовать
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="Исходный код преобразования PPTX в POTX Java" >}}
```cs
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("template.pptx");
// save the presentation as POTX
presentation.save("output.potx", SaveFormat.Potx);   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Шаги по преобразованию PPTX в POTX через Java" intro="Разработчики Java могут легко преобразовать файл PPTX в POTX, написав всего несколько строк кода." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл PPTX с экземпляром класса Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите метод Presentation.save, указав путь к выходному файлу и SaveFormat.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Файл POTX будет сохранен по указанному пути{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Системные Требования" intro="Перед запуском примера кода преобразования Java убедитесь, что выполнены следующие предварительные условия." %}}

- Microsoft Windows или совместимая ОС со средой выполнения Java для приложений JSP/JSF и настольных приложений.
- Получите последнюю версию Aspose.Slides для Java прямо из Maven.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Бесплатное приложение для преобразования PPTX в POTX"
  description="[Попробуйте наше бесплатное приложение MP4 To MP3](https://products.aspose.app/slides/video/mp4-to-mp3/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать PPTX во многие другие форматы файлов, включая некоторые из перечисленных ниже." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="Растровое изображение" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-gif/" name="PPTX TO GIF" description="Графический формат обмена" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-html/" name="PPTX TO HTML" description="Язык гипертекстовой разметки" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" description="Изображение в формате JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-odp/" name="PPTX TO ODP" description="Формат презентации OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-otp/" name="PPTX TO OTP" description="Стандартный формат OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="Портативный формат документа" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-png/" name="PPTX TO PNG" description="Портативная сетевая графика" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-pot/" name="PPTX TO POT" description="Файлы шаблонов Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-potm/" name="PPTX TO POTM" description="Файл шаблона Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-pps/" name="PPTX TO PPS" description="Слайд-шоу PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="Слайд-шоу с поддержкой макросов" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="Слайд-шоу PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="Файл презентации с поддержкой макросов" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-svg/" name="PPTX TO SVG" description="Масштабируемая векторная графика" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-swf/" name="PPTX TO SWF" description="SWF-формат" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="Формат изображения с тегами" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-xps/" name="PPTX TO XPS" description="Спецификации XML-бумаги" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
