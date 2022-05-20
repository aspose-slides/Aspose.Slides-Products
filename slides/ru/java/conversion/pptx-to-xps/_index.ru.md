---
title: Преобразование PPTX в XPS через Java
weight: 4680
url: /ru/java/conversion/pptx-to-xps/ 
description: Пример кода преобразования Java для формата PPTX в файл XPS. Используйте этот пример кода для экспорта презентаций PowerPoint и OpenOffice в XPS в любом веб-приложении или приложении для рабочего стола на основе Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование PPTX в XPS через Java" h2="Преобразование PPTX в XPS Java для преобразования одной или нескольких страниц в XPS с использованием локальной библиотеки Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XPS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать PPTX в XPS с помощью Java" %}}

 Чтобы преобразовать PPTX в XPS, мы будем использовать
 [Aspose.Slides для Java](https://products.aspose.com/slides/ru/java)
 API, который представляет собой многофункциональный, мощный и простой в использовании API преобразования для платформы Java. Вы можете скачать его последнюю версию прямо с
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 и установите его в своем проекте на основе Maven, добавив следующие конфигурации в файл pom.xml.

{{% blocks/products/pf/agp/code-block title="Репозиторий" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Зависимость" offSpacer="true" %}}

```cs
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

{{% blocks/products/pf/agp/feature-section-col title="Шаги по преобразованию PPTX в XPS через Java" %}}

{{% blocks/products/pf/agp/text %}}

 Разработчики Java могут легко преобразовать файл PPTX в XPS, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите файл PPTX с экземпляром класса Presentation.
1. Вызовите метод Presentation.save, указав путь к выходному файлу и SaveFormat.
1. XPS-файл будет сохранен по указанному пути.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском примера кода преобразования Java убедитесь, что выполнены следующие предварительные условия.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС со средой выполнения Java для приложений JSP/JSF и настольных приложений.
- Получите последнюю версию Aspose.Slides для Java прямо из Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Исходный код преобразования PPTX в XPS Java" offSpacer="" %}}

```cs
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("template.pptx");
// save the presentation as XPS
presentation.save("output.xps", SaveFormat.Xps);   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="pptx-to-xps"
        sectionTitle="Бесплатное приложение для преобразования PPTX в XPS" 
        sectionDescription="[Попробуйте наше бесплатное приложение Video](https://products.aspose.app/slides/video/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать PPTX во многие другие форматы файлов, включая некоторые из перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="Растровое изображение" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-gif/" name="PPTX TO GIF" description="Графический формат обмена" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-html/" name="PPTX TO HTML" description="Язык гипертекстовой разметки" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" description="Изображение в формате JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-odp/" name="PPTX TO ODP" description="Формат презентации OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-otp/" name="PPTX TO OTP" description="Стандартный формат OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="Портативный формат документа" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-png/" name="PPTX TO PNG" description="Портативная сетевая графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-pot/" name="PPTX TO POT" description="Файлы шаблонов Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-potm/" name="PPTX TO POTM" description="Файл шаблона Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-potx/" name="PPTX TO POTX" description="Презентация шаблона Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-pps/" name="PPTX TO PPS" description="Слайд-шоу PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="Слайд-шоу с поддержкой макросов" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="Слайд-шоу PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="Файл презентации с поддержкой макросов" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-svg/" name="PPTX TO SVG" description="Масштабируемая векторная графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-swf/" name="PPTX TO SWF" description="SWF-формат" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="Формат изображения с тегами" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}