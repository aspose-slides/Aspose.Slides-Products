---
title: Преобразование PPSM в GIF через приложение C++
weight: 7520
url: /ru/cpp/conversion/ppsm-to-gif/ 
description: Пример кода преобразования C++ для документа PPSM в формат GIF. Используйте пример кода для пакетного преобразования PPSM в GIF в любом приложении C++.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование PPSM в GIF через C++" h2="Высокопроизводительное преобразование PPSM в GIF с использованием библиотеки C++ без необходимости установки Microsoft PowerPoint." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как конвертировать PPSM в GIF с помощью C++" %}}

 Чтобы преобразовать PPSM в GIF, мы будем использовать
 [Aspose.Slides для C++](https://products.aspose.com/slides/cpp)
 API, который представляет собой многофункциональный, мощный и простой в использовании API для обработки и преобразования документов для платформы C++. Вы можете загрузить его последнюю версию напрямую, просто открыв
 [NuGet] (https://www.nuget.org/packages/aspose.slides)
 менеджер пакетов, поиск
 Aspose.Slides.Cpp
 и установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Команда" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Шаги по преобразованию PPSM в GIF через C++" %}}

{{% blocks/products/pf/agp/text %}}

 Разработчики C++ могут легко преобразовать файл PPSM в GIF всего за несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите файл PPSM с Aspose.Slides for C++ Presentation Object.
1. Выберите первый слайд.
1. Установите нужные размеры.
1. Получите миниатюру нужных размеров.
1. Вызвать метод Save() с выходным параметром GIF.
1. Откройте файл GIF в совместимой программе.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском кода примера преобразования C++ убедитесь, что выполнены следующие предварительные условия.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС со средой выполнения C++ для 32-разрядной версии Windows, 64-разрядной версии Windows и 64-разрядной версии Linux.
- Aspose.Slides for C++ DLL, на которые есть ссылки в вашем проекте.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Исходный код преобразования PPSM в GIF C++" offSpacer="" %}}

```cs
// Load the PPSM
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.ppsm");

// Access the first slide
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// User defined dimension
int desiredX = 1200;
int desiredY = 800;

// Getting scaled value  of X and Y
float ScaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float ScaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

// Create a custom scale image
auto bitmap = slide->GetThumbnail(ScaleX, ScaleY);

bitmap->Save(u"output.gif", ImageFormat::get_Gif());
	
//Iterate through each slide via index and convert

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="PPSM to GIF Conversion Live Demos" sectionDescription="[Convert PPSM to GIF](https://products.aspose.app/slides/conversion/ppsm-to-gif) right now by visiting our Live Demos website.The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PPSM file, it will be converted instantly to GIF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will get the download link." >}}

    {{% blocks/products/pf/agp/content h2="Библиотека управления презентациями C++" %}}

 Slides and Presentation API можно использовать для чтения, записи, обработки и преобразования документов Microsoft PowerPoint в PDF, XPS, HTML, TIFF, ODP и различные другие форматы. Можно создавать новые файлы с нуля и сохранять их в соответствующих поддерживаемых форматах. Aspose.Slides — это автономный API для создания, анализа или управления презентациями, слайдами и элементами, который не зависит от какого-либо программного обеспечения, такого как Microsoft или OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPSM" readMoreLink="https://docs.fileformat.com/presentation/ppsm/" >}}

Files with PPSM extension represent Macro-enabled Slide Show file format created with Microsoft PowerPoint 2007 or higher. Another similar file format is PPTM which differs in opening with Microsoft PowerPoint in editable format instead of running as Slide Show. When run as slide show, the PPSM file shows the presentation slides with contents intact in the slide show and is in read-only mode by default. PPSM files can still be edited in Microsoft PowerPoint by opening it in PowerPoint.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GIF" readMoreLink="https://docs.fileformat.com/image/gif/" >}}

A GIF or Graphical Interchange Format is a type of highly compressed image. Owned by Unisys, GIF uses the LZW compression algorithm that does not degrade the image quality. For each image GIF typically allow up to 8 bits per pixel and up to 256 colours are allowed across the image. In contrast to a JPEG image, which can display up to 16 million colours and fairly touches the limits of the human eye. Back when the internet emerged, GIFs remained the best choice because they required low bandwidth and compatible for the graphics that consume solid areas of colour. An animated GIF combines numerous images or frames into a single file and displays them in a sequence to generate an animated clip or a short video. The colour limitations are up to 256 for each frame and are likely to be the least suitable for reproducing other images and photographs with colour gradient.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать PPSM во многие другие форматы файлов, в том числе некоторые из перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-bmp/" name="PPSM TO BMP" description="Растровое изображение" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-emf/" name="PPSM TO EMF" description="Расширенный формат метафайла" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-html/" name="PPSM TO HTML" description="Язык гипертекстовой разметки" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-jpeg/" name="PPSM TO JPEG" description="Изображение в формате JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="Формат презентации OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="Стандартный формат OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="Портативный формат документа" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-png/" name="PPSM TO PNG" description="Портативная сетевая графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-pot/" name="PPSM TO POT" description="Файлы шаблонов Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="Файл шаблона Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="Презентация шаблона Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="Слайд-шоу PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="Слайд-шоу PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="Файл презентации с поддержкой макросов" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="Формат презентации Open XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="Масштабируемая векторная графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="Формат изображения с тегами" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-xml/" name="PPSM TO XML" description="расширяемый язык разметки" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="Спецификации XML-бумаги" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}