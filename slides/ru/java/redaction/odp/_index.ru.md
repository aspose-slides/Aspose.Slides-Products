---
title: Поиск и замена текста в документе ODP через Java
weight: 240
url: /ru/java/redaction/odp/ 
description: Пример кода Java для редактирования конфиденциальной информации в файле ODP в среде выполнения Java для приложений JSP/JSF и настольных приложений.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Редактировать форматы ODP в Java" h2="Собственный и высокопроизводительный ODP документирует конфиденциальную информацию о редактировании, используя серверные API-интерфейсы Aspose.Slides для Java, без использования какого-либо программного обеспечения, такого как Microsoft или Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="https://www.nuget.org/packages/aspose.slides.java" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Как отредактировать файл ODP с помощью Java" %}}

 Чтобы отредактировать файл ODP, мы будем использовать
 [Aspose.Slides для Java](https://products.aspose.com/slides/ru/java)
 API, который представляет собой многофункциональный, мощный и простой в использовании API редактирования для платформы Java. Вы можете скачать его последнюю версию прямо с
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


{{< blocks/products/pf/agp/feature-section-col title="Шаги по редактированию файлов ODP в Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Базовый поиск документа и замена текста в содержимом, комментариях или метаданных с помощью API [Aspose.Slides for Java](https://products.aspose.com/slides/ru/java) можно выполнить с помощью всего нескольких строк кода. Поиск и замена текста в PowerPoint и OpenOffice. Редактируйте текст, комментарии, метаданные в презентации с помощью сопоставления данных регулярных выражений." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Загрузить презентацию ODP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Доступ к первому слайду.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Переберите фигуры и установите ссылку на найденную таблицу.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Изменить текст каждого заполнителя
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохраните ODP-файл.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides for Java поддерживает все основные платформы и операционные системы. Пожалуйста, убедитесь, что у вас есть следующие предпосылки.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС со средой выполнения Java для приложений JSP/JSF и настольных приложений.
- Получить последнюю версию Aspose.Slides для Java прямо из
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Редактировать файлы ODP — Java" offSpacer="" %}}

```cs
 //Load ODP file

Presentation pres = new Presentation(dataDir + "sourceFile.odp");

//Access first slide

ISlide slide = pres.getSlides().get_Item(0);

IShape shape= null;

//Iterate through the shapes and set a reference to the table found

for (int i = 0 ; i < slide.getShapes().size() ; i++){

    shape = slide.getShapes().get_Item(i);

    if (shape.getPlaceholder() != null){

        //Change the text of each placeholder

        ((IAutoShape)shape).getTextFrame().setText("This is Placeholder");

    }

}

//Write the ODP to Disk

pres.save(dataDir + "AsposeReplaceTxt.odp",SaveFormat.Odp);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="О Aspose.Slides for Java API" %}}

 Aspose.Slides API можно использовать для чтения, записи, обработки и преобразования документов Microsoft PowerPoint в PDF, XPS, HTML, TIFF, ODP и другие различные форматы. Можно создавать новые файлы с нуля и сохранять их в соответствующих поддерживаемых форматах. Aspose.Slides — это автономный API для создания, анализа или управления презентациями, слайдами и элементами, который не зависит от какого-либо программного обеспечения, такого как Microsoft или OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Redaction Live Demos" sectionDescription="Search and replace text in contents, comments or metadata in ODP documents right now by visiting our [Live Demos website](https://products.aspose.app/slides/redaction). The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your ODP files." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be redacted instantly." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" >}}
Files with ODP extension represent presentation file format used by OpenOffice.org in the OASISOpen standard. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. ODP files can be opened by applications that conform to the OpenDocument format (such as OpenOffice or StarOffice). 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые документы редактирования" subTitle="Используя Java, можно легко редактировать различные форматы, в том числе." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/redaction/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/redaction/pptx/" name="PPTX" description="Формат презентации Open XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}