---
title: Преобразование POTX в SVG через C#
weight: 7010
url: /ru/net/conversion/potx-to-svg/ 
description: Пример кода для преобразования POTX в SVG C#. Используйте пример кода API для пакетного преобразования файлов POTX в SVG в VB.NET, Asp.NET или любом приложении на основе .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование POTX в SVG через C#" h2="Экспорт файлов PowerPoint® POTX в SVG на платформах .NET Framework, .NET Core, Windows Azure, Mono или Xamarin." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="POTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать POTX в SVG с помощью C#" %}}

 Чтобы преобразовать POTX в SVG, мы будем использовать
 [Aspose.Slides для .NET](https://products.aspose.com/slides/ru/net)
 API, который представляет собой многофункциональный, мощный и простой в использовании API для обработки и преобразования документов для платформы C#. Открытым
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 менеджер пакетов, поиск
 Aspose.Слайды
 и установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Команда консоли диспетчера пакетов" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Шаги по преобразованию POTX в SVG через C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Разработчики .NET могут легко загружать и преобразовывать файлы POTX в SVG всего за несколько строк кода." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Загрузите файл POTX с экземпляром класса Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Вызовите метод Save, указав путь к выходному файлу и SaveFormat.Svg в качестве параметров.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Файл SVG будет сохранен по указанному пути
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском исходного кода примера преобразования .NET убедитесь, что выполнены следующие предварительные условия.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с платформами .NET Framework, .NET Core, Windows Azure, Mono или Xamarin.
- Среда разработки, такая как Microsoft Visual Studio.
- Aspose.Slides для .NET DLL, на которую ссылается ваш проект.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Этот пример кода показывает преобразование POTX в SVG C#" offSpacer="" %}}

```cs
using (Presentation pres = new Presentation("template.potx"))
{
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];

        using (FileStream fileStream = new FileStream($"slide-{index}.svg", FileMode.Create, FileAccess.Write))
        {
            slide.WriteAsSvg(fileStream);   
        }
    }
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
        sectionTitle="Бесплатное приложение для преобразования POTX в SVG" 
        sectionDescription="[Попробуйте наше бесплатное приложение Editor](https://products.aspose.app/slides/editor/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать POTX во многие другие форматы файлов, включая некоторые из перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/potx-to-bmp/" name="POTX TO BMP" description="Растровое изображение" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/potx-to-emf/" name="POTX TO EMF" description="Расширенный формат метафайла" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/potx-to-gif/" name="POTX TO GIF" description="Графический формат обмена" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/potx-to-html/" name="POTX TO HTML" description="Язык гипертекстовой разметки" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/potx-to-jpeg/" name="POTX TO JPEG" description="Изображение в формате JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/potx-to-odp/" name="POTX TO ODP" description="Формат презентации OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/potx-to-otp/" name="POTX TO OTP" description="Стандартный формат OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/potx-to-pdf/" name="POTX TO PDF" description="Портативный формат документа" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/potx-to-png/" name="POTX TO PNG" description="Портативная сетевая графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/potx-to-pot/" name="POTX TO POT" description="Файлы шаблонов Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/potx-to-potm/" name="POTX TO POTM" description="Файл шаблона Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/potx-to-pps/" name="POTX TO PPS" description="Слайд-шоу PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/potx-to-ppsm/" name="POTX TO PPSM" description="Слайд-шоу с поддержкой макросов" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/potx-to-ppsx/" name="POTX TO PPSX" description="Слайд-шоу PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/potx-to-ppt/" name="POTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/potx-to-pptm/" name="POTX TO PPTM" description="Файл презентации с поддержкой макросов" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/potx-to-pptx/" name="POTX TO PPTX" description="Формат презентации Open XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/potx-to-swf/" name="POTX TO SWF" description="SWF-формат" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/potx-to-tiff/" name="POTX TO TIFF" description="Формат изображения с тегами" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/potx-to-xps/" name="POTX TO XPS" description="Спецификации XML-бумаги" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}