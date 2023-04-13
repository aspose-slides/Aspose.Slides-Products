---
title: Преобразование PPTX в Word на C#
url: /ru/net/conversion/pptx-to-word/
keywords: Преобразование PPTX в Word, PPTX в Word, PPTX в DOC, PowerPoint в Word, C# API, .NET Library
description: Преобразование PPTX в Word на C#. Используйте API библиотеки .NET для преобразования PowerPoint в Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Преобразование PPTX в Word на C#" h2="Мощный кроссплатформенный .NET API для преобразования PowerPoint в Word с использованием кода C# на платформах NET Framework, .NET Core, Windows Azure, Mono или Xamarin." >}}

{{% blocks/products/pf/feature-page-section h2="Конвертируйте PowerPoint в Word с помощью Aspose.Slides и Aspose.Words" %}}

[**Aspose.Slides для .NET**](https://products.aspose.com/slides/ru/net/) и [**Aspose.Words для .NET**](https://products.aspose. com/words/net/) — это мощные библиотеки .NET, используемые для управления и преобразования презентаций PowerPoint, документов Word и других файлов. Когда вы конвертируете PowerPoint в Word, вы, по сути, перемещаете содержимое слайдов презентации на страницы документа Word.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Преобразование PowerPoint в Word на C#" %}}
Вы можете быстро преобразовать PPTX в Word, написав всего несколько строк кода.

{{% blocks/products/pf/agp/code-block title="Код C# для преобразования PowerPoint в Word" offSpacer="true" %}}
```cs
using var presentation = new Presentation();
var doc = new Document();
var builder = new DocumentBuilder(doc);
foreach (var slide in presentation.Slides)
{
    // generates and inserts slide image
    using var bitmap = slide.GetThumbnail(1, 1);
    using var stream = new MemoryStream();
    bitmap.Save(stream, ImageFormat.Png);
    stream.Seek(0, SeekOrigin.Begin);
    using var skBitmap = SKBitmap.Decode(stream);
    builder.InsertImage(skBitmap);

    // inserts slide texts
    foreach (var shape in slide.Shapes)
    {
        if (shape is AutoShape autoShape)
        {
            builder.Writeln(autoShape.TextFrame.Text);
        }
    }

    builder.InsertBreak(BreakType.PageBreak);
}
doc.Save("document.docx");
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Как преобразовать PPTX в Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Установите **Aspose.Slides для .NET** и **Aspose.Words для .NET** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Добавьте две библиотеки в качестве ссылок в свой проект.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Создайте экземпляр класса Presentation и класса Doc.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Загрузите презентацию PPTX, которую вы хотите преобразовать в Word.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Создавайте изображения и тексты на основе содержимого слайдов.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохраните полученный документ Word.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Бесплатный онлайн-конвертер" sectionDescription="[Как преобразовать PPT в HTML в Python](https://products.aspose.com/slides/ru/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать PowerPoint в файлы других форматов." >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}