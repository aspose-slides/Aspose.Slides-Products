---
title: Поиск и замена текста в документе PPTX через .NET
weight: 4070
url: /ru/net/redaction/pptx/ 
description: Исходный код C# для редактирования конфиденциальной информации в файле PPTX на платформах .NET Framework, .NET Core, Windows Azure, Mono или Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Редактировать форматы PPTX в C#" h2="Собственный и высокопроизводительный PPTX документирует конфиденциальную информацию о редактировании с использованием серверных API-интерфейсов Aspose.Slides для .NET без использования какого-либо программного обеспечения, такого как Microsoft или Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как отредактировать файл PPTX с помощью C#" %}}

 Чтобы отредактировать файл PPTX, мы будем использовать
 [Aspose.Slides для .NET](https://products.aspose.com/slides/ru/net)
 API, который представляет собой многофункциональный, мощный и простой в использовании API для работы с документами для платформы C#. Открытым
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 менеджер пакетов, поиск
 **Aspose.Slides**
 и установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Команда" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Действия по редактированию файлов PPTX в C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Базовый поиск документа и замена текста в содержимом, комментариях или метаданных с помощью API [Aspose.Slides for .NET](https://products.aspose.com/slides/ru/net) можно выполнить всего несколькими строками кода. Поиск и замена текста в PowerPoint и OpenOffice. Редактируйте текст, комментарии, метаданные в презентации с помощью сопоставления данных регулярных выражений." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Загрузите презентацию PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Прокрутите каждый слайд и получите коллекцию textFrame.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Перебрать коллекцию.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Используйте метод «Заменить», а затем «Выделите текст».
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохранить презентацию.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Наши API поддерживаются на всех основных платформах и операционных системах. Перед выполнением приведенного ниже кода убедитесь, что в вашей системе выполнены следующие предварительные условия.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с платформами .NET Framework, .NET Core, Windows Azure, Mono или Xamarin.
- Среда разработки, такая как Microsoft Visual Studio
- Aspose.Slides для .NET DLL, на которую ссылается ваш проект - Установите из NuGet, используя кнопку «Загрузить» выше

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Редактировать файлы PPTX — C#" offSpacer="" %}}

```cs
using (Presentation pres = new Presentation("pres.pptx")){
    const string toRedact = "bKIM";
    string stub = new string(' ', toRedact.Length);
   //Using Aspose.Slides, one can use highlight text color feature to Redact text.
    foreach (ISlide slide in pres.Slides){
        ITextFrame[] textFrames = SlideUtil.GetAllTextBoxes(slide);
        foreach (ITextFrame textFrame in textFrames){
            textFrame.Text = textFrame.Text.Replace(toRedact, stub);
            textFrame.HighlightText(stub, Color.Black);
        }
    }

    pres.Save("pres-edited.pptx", SaveFormat.Pptx);
}

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="О Aspose.Slides для .NET API" %}}

 Aspose.Slides API можно использовать для чтения, записи, обработки и преобразования документов Microsoft PowerPoint в PDF, XPS, HTML, TIFF, ODP и другие различные форматы. Можно создавать новые файлы с нуля и сохранять их в соответствующих поддерживаемых форматах. Aspose.Slides — это автономный API для создания, анализа или управления презентациями, слайдами и элементами, который не зависит от какого-либо программного обеспечения, такого как Microsoft или OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX Redaction Live Demos" sectionDescription="Search and replace text in contents, comments or metadata in PPTX documents right now by visiting our [Live Demos website](https://products.aspose.app/slides/redaction). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PPTX files." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be redacted instantly." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" >}}
Files with PPTX extension are presentation files created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы редактирования" subTitle="Используя C#, можно легко редактировать различные форматы, в том числе." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/redaction/odp/" name="ODP" description="Формат презентации OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/redaction/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}