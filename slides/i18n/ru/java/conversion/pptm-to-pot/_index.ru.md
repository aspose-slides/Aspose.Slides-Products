---
title: Преобразование PPTM в POT через Java
weight: 7470
url: /ru/java/conversion/pptm-to-pot/ 
description: Пример кода преобразования Java для формата PPTM в файл POT. Используйте этот пример кода для экспорта презентаций PowerPoint и OpenOffice в POT в любом веб- или настольном приложении на основе Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование PPTM в POT через Java" h2="Преобразование PPTM в POT Java для преобразования одной или нескольких страниц в POT с использованием локальной библиотеки Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="POT" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPTM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать PPTM в POT с помощью Java" %}}

 Чтобы преобразовать PPTM в POT, мы будем использовать
 [Aspose.Slides для Java](https://products.aspose.com/slides/java)
 API, который представляет собой многофункциональный, мощный и простой в использовании API преобразования для платформы Java. Вы можете скачать его последнюю версию прямо с
 [Maven] (https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
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

{{% blocks/products/pf/agp/feature-section-col title="Шаги по преобразованию PPTM в POT через Java" %}}

{{% blocks/products/pf/agp/text %}}

 Разработчики Java могут легко преобразовать файл PPTM в POT, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите файл PPTM с экземпляром класса Presentation.
1. Вызовите метод Presentation.save, указав путь к выходному файлу и SaveFormat.
1. POT-файл будет сохранен по указанному пути.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском примера кода преобразования Java убедитесь, что выполнены следующие предварительные условия.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС со средой выполнения Java для приложений JSP/JSF и настольных приложений.
- Получите последнюю версию Aspose.Slides для Java прямо из Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Исходный код преобразования PPTM в POT Java" offSpacer="" %}}

```cs
// instantiate a Presentation object that represents a PPTM file
Presentation presentation = new Presentation("template.pptm");
// save the presentation as POT
presentation.save("output.pot", SaveFormat.Pot);   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="PPTM to POT Conversion Live Demos" sectionDescription="[Convert PPTM to POT](https://products.aspose.app/slides/conversion/pptm-to-pot) right now by visiting our Live Demos website.The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PPTM file, it will be converted instantly to POT." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will get the download link." >}}

    {{% blocks/products/pf/agp/content h2="Библиотека управления презентациями Java" %}}

 Slides and Presentation API можно использовать для чтения, записи, обработки и преобразования документов Microsoft PowerPoint в PDF, XPS, HTML, TIFF, ODP и различные другие форматы. Можно создавать новые файлы с нуля и сохранять их в соответствующих поддерживаемых форматах. Aspose.Slides — это автономный API для создания, анализа или управления презентациями, слайдами и элементами, который не зависит от какого-либо программного обеспечения, такого как Microsoft или OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPTM" readMoreLink="https://docs.fileformat.com/presentation/pptm/" >}}

Files with PPTM extension are Macro-enabled Presentation files that are created with Microsoft PowerPoint 2007 or higher versions. They are similar to PPTX files with the difference that the lateral can't execute macros though they can contain macros. PPTM files can be edited by opening them in Microsoft PowerPoint and updating the contents. Another similar format is PPSM but it is read-only by default and starts the slideshow when opened. PPTM, like PPTX, contains slides for different presentation elements like text, images, videos, graphs and other related material.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="POT" readMoreLink="https://docs.fileformat.com/presentation/pot/" >}}

Files with .POT extension represent Microsoft PowerPoint template files created by PowerPoint 97-2003 versions. Files created with these versions of Microsoft PowerPoint are in binary format as compared to those created in Office OpenXML file formats using the higher versions of PowerPoint. The files, hence, generated can be used to create presentations that have same layout and other settings required to be applied to new files. These settings can include styles, backgrounds, colour palette, fonts and defaults. Such files are generated in order to create ready-to-use template files for official use.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать PPTM во многие другие форматы файлов, включая некоторые из перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="Растровое изображение" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pptm-to-gif/" name="PPTM TO GIF" description="Графический формат обмена" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pptm-to-html/" name="PPTM TO HTML" description="Язык гипертекстовой разметки" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pptm-to-jpeg/" name="PPTM TO JPEG" description="Изображение в формате JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pptm-to-odp/" name="PPTM TO ODP" description="Формат презентации OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pptm-to-otp/" name="PPTM TO OTP" description="Стандартный формат OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="Портативный формат документа" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pptm-to-png/" name="PPTM TO PNG" description="Портативная сетевая графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pptm-to-potm/" name="PPTM TO POTM" description="Файл шаблона Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pptm-to-potx/" name="PPTM TO POTX" description="Презентация шаблона Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pptm-to-pps/" name="PPTM TO PPS" description="Слайд-шоу PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="Слайд-шоу с поддержкой макросов" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="Слайд-шоу PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="Формат презентации Open XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pptm-to-svg/" name="PPTM TO SVG" description="Масштабируемая векторная графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pptm-to-swf/" name="PPTM TO SWF" description="SWF-формат" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="Формат изображения с тегами" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pptm-to-xps/" name="PPTM TO XPS" description="Спецификации XML-бумаги" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}