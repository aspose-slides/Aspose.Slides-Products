---
title: Преобразование PPTM в JPEG через Java
weight: 6810
url: /ru/java/conversion/pptm-to-jpeg/ 
description: Пример кода преобразования Java для формата PPTM в файл JPEG. Используйте этот пример кода для экспорта презентаций PowerPoint и OpenOffice в формат JPEG в любом веб-приложении или приложении для рабочего стола на основе Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование PPTM в JPEG через Java" h2="Преобразование PPTM в JPEG Java для преобразования одной или нескольких страниц в JPEG с использованием локальной библиотеки Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPTM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать PPTM в JPEG с помощью Java" %}}

 Чтобы преобразовать PPTM в JPEG, мы будем использовать
 [Aspose.Slides для Java](https://products.aspose.com/slides/ru/java/)
 API, который представляет собой многофункциональный, мощный и простой в использовании API преобразования для платформы Java. Вы можете скачать его последнюю версию прямо с
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 и установите его в своем проекте на основе Maven, добавив следующие конфигурации в файл pom.xml.

{{% blocks/products/pf/agp/code-block title="Репозиторий" offSpacer="true" %}}

```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Зависимость" offSpacer="true" %}}

```xml

<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>version of aspose-slides API</version>
    <classifier>jdk17</classifier>
</dependency>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Шаги для преобразования PPTM в JPEG через Java" %}}

{{% blocks/products/pf/agp/text %}}

 Разработчики Java могут легко преобразовать файл PPTM в JPEG, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите файл PPTM с экземпляром класса Presentation.
1. Повторите каждый слайд в презентации.
1. Создавайте полномасштабное изображение в виде растрового изображения с каждой итерацией.
1. Вызовите метод Bitmap.save с расширением файла JPEG и ImageFormat.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском примера кода преобразования Java убедитесь, что выполнены следующие предварительные условия.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС со средой выполнения Java для приложений JSP/JSF и настольных приложений.
- Получите последнюю версию Aspose.Slides для Java прямо из Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Исходный код преобразования PPTM в JPEG Java" offSpacer="" %}}

```cs
// load PPTM with Aspose.Slides
Presentation presentation = new Presentation("template.pptm");
   
    // iterate over all slides in the presentation
for (ISlide sld : presentation.getSlides()) 
{
  
  // create a full scale image of each slide
  BufferedImage bi = sld.getThumbnail(new RenderingOptions());

  // create a new file of type JPEG for every slide
  File outputfile = new File(sld.getSlideNumber() + ".jpeg");
  
  // save the slide image to disk
  ImageIO.write(bi, "jpeg", outputfile);
}   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="Бесплатное приложение для преобразования PPTM в JPEG" 
        sectionDescription="[Попробуйте наше бесплатное приложение, чтобы преобразовать PPT в JPG](https://products.aspose.app/slides/conversion/ppt-to-jpg)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать PPTM во многие другие форматы файлов, включая некоторые из перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="Растровое изображение" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptm-to-gif/" name="PPTM TO GIF" description="Графический формат обмена" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptm-to-html/" name="PPTM TO HTML" description="Язык гипертекстовой разметки" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptm-to-odp/" name="PPTM TO ODP" description="Формат презентации OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptm-to-otp/" name="PPTM TO OTP" description="Стандартный формат OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="Портативный формат документа" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptm-to-png/" name="PPTM TO PNG" description="Портативная сетевая графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptm-to-pot/" name="PPTM TO POT" description="Файлы шаблонов Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptm-to-potm/" name="PPTM TO POTM" description="Файл шаблона Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptm-to-potx/" name="PPTM TO POTX" description="Презентация шаблона Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptm-to-pps/" name="PPTM TO PPS" description="Слайд-шоу PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="Слайд-шоу с поддержкой макросов" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="Слайд-шоу PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="Формат презентации Open XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptm-to-svg/" name="PPTM TO SVG" description="Масштабируемая векторная графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptm-to-swf/" name="PPTM TO SWF" description="SWF-формат" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="Формат изображения с тегами" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptm-to-xps/" name="PPTM TO XPS" description="Спецификации XML-бумаги" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}