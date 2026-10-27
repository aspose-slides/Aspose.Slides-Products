---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Слияние файлов PPS через Java
weight: 3930
url: /ru/java/merger/pps/ 
description: Пример кода Java для объединения документов PPS в среде выполнения Java для приложений JSP/JSF и настольных приложений.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Объединение форматов PPS в Java" h2="Нативное слияние документов PPS с использованием серверных API Java."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="ODP,OTP,POT,POTM,POTX,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Как объединить файлы PPS с помощью Java" %}}

Чтобы объединить файл PPS, мы будем использовать
 [Aspose.Slides для Java](https://products.aspose.com/slides/ru/java/)
 API, который представляет собой многофункциональный, мощный и простой в использовании API слияния для платформы Java. Вы можете скачать его последнюю версию прямо с
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="Объединение файлов PPS — Java" >}}
```cs
// Load first PPS File
Presentation prest1 = new Presentation("prest1.pps");

// Load second PPS File
Presentation prest2 = new Presentation("prest2.pps");

// Merge
for (ISlide slide : prest2.getSlides()) {
	// Merge from source to target
	prest1.getSlides().addClone(slide);
}

// Save the File
prest1.save("merged-presentation.pps", SaveFormat.Pps);  

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Шаги для слияния файлов PPS в Java" intro="Базовое слияние и объединение документов с помощью API [Aspose.Slides for Java](https://products.aspose.com/slides/ru/java/) можно выполнить с помощью всего нескольких строк кода." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите первый файл PPS с экземпляром класса Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите второй документ PPS с экземпляром класса Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Прокрутите каждый слайд второго файла PPS.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}С каждой итерацией, используя addClone() для добавления слайдов с первым файлом.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Используйте метод save() для сохранения по указанному пути{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Системные Требования" intro="Aspose.Slides for Java поддерживает все основные платформы и операционные системы. Пожалуйста, убедитесь, что у вас есть следующие предпосылки." %}}

- Microsoft Windows или совместимая ОС со средой выполнения Java для приложений JSP/JSF и настольных приложений.
- Получить последнюю версию Aspose.Slides для Java прямо из [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides).

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension=""
  title="Объединить PDF-файлы онлайн"
  description="[Как объединить PDF в Python](https://products.aspose.com/slides/ru/python-net/merge/pdf/)" >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPS" readMoreLink="https://docs.fileformat.com/presentation/pps/" %}}

Файлы с расширением `.PPS` — это демонстрации PowerPoint, созданные в Microsoft PowerPoint 97-2003. Файл `PPS` сразу запускается как слайд-шоу, а не открывается в режиме редактирования.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые форматы слияния" subTitle="Используя Java, можно также объединять многие другие форматы файлов, включая .." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/merger/odp/" name="ODP" description="Формат презентации OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/merger/otp/" name="OTP" description="Стандартный формат OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/merger/pot/" name="POT" description="Файлы шаблонов Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/merger/potm/" name="POTM" description="Файл шаблона Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/merger/potx/" name="POTX" description="Презентация шаблона Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/merger/ppsm/" name="PPSM" description="Слайд-шоу с поддержкой макросов" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/merger/ppsx/" name="PPSX" description="Слайд-шоу PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/merger/pptm/" name="PPTM" description="Файл презентации с поддержкой макросов" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/merger/pptx/" name="PPTX" description="Формат презентации Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
