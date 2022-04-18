---
title: Преобразование презентации Microsoft PowerPoint в несколько файлов с использованием C#
url: /ru/net/conversion/
description: Преобразуйте слайды Microsoft PowerPoint в различные файлы, включая PDF, HTML и графические форматы, на платформах .NET Framework, .NET Core, Windows Azure, Mono или Xamarin.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование презентаций Microsoft<sup>®</sup> PowerPoint с помощью C#" h2="Исходные коды C# для различных случаев преобразования файлов в изображения, PDF, HTML и другие форматы." >}}

{{% blocks/products/pf/feature-page-summary %}}

Разработчикам легко и быстро преобразовывать презентации Microsoft<sup>®</sup> PowerPoint. Получите результаты в кратчайшие сроки для автоматизации бизнес-процессов. Мы обсуждаем здесь несколько случаев чтения или загрузки любых входных данных [поддерживаемые форматы PowerPoint] (https://docs.aspose.com/slides/net/supported-file-formats/) и записи или сохранения в любом поддерживаемом выходном формате. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Межконверсионное преобразование файлов Microsoft PowerPoint" %}}
Всякий раз, когда необходимо автоматизировать взаимное преобразование форматов Microsoft<sup>®</sup> PowerPoint. **Библиотека C# PowerPoint** предоставляет классы для достижения этой цели. Загрузите файл с помощью [класса презентации](https://apireference.aspose.com/net/slides/aspose.slides/presentation), чтобы загрузить или прочитать нужный формат и вызвать [метод сохранения](https://apireference. aspose.com/slides/net/aspose.slides/presentation/methods/save) того же класса, указав выходной файл и [SaveFormat](https://apireference.aspose.com/slides/net/aspose.slides.export /saveformat).Формат вывода. 
{{% blocks/products/pf/feature-page-code h3="Код преобразователя C# для презентаций Microsoft PowerPoint" %}}

```cs
// Load the Source File
var pptToPptx = new Presentation("sourceFile.ppt");
// Save into the desired format
pptToPptx.Save("powerpoiont-inter-conversion.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="C# Преобразование PowerPoint в PDF" %}}

Для точного преобразования слайдов PowerPoint в PDF программисты могут загрузить документ с помощью класса Presentation и использовать [класс PdfOptions] (https://apireference.aspose.com/slides/net/aspose.slides.export/pdfoptions) для всех конкретных и пользовательских опций. параметры, такие как уровень сжатия текста, качество Jpeg, поведение метафайлов, преобразование скрытых слайдов, а также выбор определенных слайдов и многое другое. Даже есть возможность защитить преобразованный PDF-файл паролем.
{{% blocks/products/pf/feature-page-code h3="Код конвертера C# PowerPoint в PDF" %}}

```cs
// Load PowerPoint file
Presentation pptxtopdf = new Presentation("sourceFile.pptx");

// Create PdfOptions class object for specific settings
PdfOptions pptPDFOptions = new PdfOptions();

// Set Jpeg quality
pptPDFOptions.JpegQuality = 90;

// Set behavior for metafiles
pptPDFOptions.SaveMetafilesAsPng = true;

// Set text compression level
pptPDFOptions.TextCompression = PdfTextCompression.Flate;

// Define the PDF 15 standard
pptPDFOptions.Compliance = PdfCompliance.Pdf15;

// Include hidden slides
pptPDFOptions.ShowHiddenSlides = true;

// Setting PDF password and access permissions
pptPDFOptions.Password = "password";
pptPDFOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;

// Save the presentation as PDF
pptxtopdf.Save("csharp-PowerPoint-to.pdf", SaveFormat.Pdf, pptPDFOptions);

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Преобразование Microsoft PowerPoint в HTML" %}}
Когда когда-нибудь возникает необходимость встроить презентации в веб-страницы, необходимо преобразовать слайды в HTML. API предоставляет [класс HtmlOptions](https://apireference.aspose.com/slides/net/aspose.slides.export/htmloptions), используйте его после загрузки файлов для специальных настроек, таких как скрытые слайды, так как по умолчанию они не будут включаться в процессе преобразования. Передайте доработанные параметры методу Сохранить для конвертации.
{{% blocks/products/pf/feature-page-code h3="Код C# для преобразования PowerPoint в HTML" %}}

```cs

// Load source presentation 
Presentation powerpoiontohtml = new Presentation("sourceFile.pptx");

// Create HTML options
HtmlOptions PowerPointhtmlOpt = new HtmlOptions();

// Show hidden slides
PowerPointhtmlOpt.ShowHiddenSlides = true;

// Save the PPTX as HTML
powerpoiontohtml.Save("presentation-to.html", SaveFormat.Html, PowerPointhtmlOpt); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-html pptx-to-html ppsm-to-html potx-to-html ppsx-to-html pps-to-html pptm-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование слайдов PowerPoint в форматы изображений" %}}
Преобразование форматов Microsoft<sup>®</sup> PowerPoint в изображения JPEG, PNG, TIFF и т. д. — еще один распространенный вариант использования, в основном используемый для создания эскизов слайдов. Процесс кодирования прост. После загрузки документа используйте [интерфейс ISlide](https://apireference.aspose.com/net/slides/aspose.slides/islide) для повторного просмотра каждого слайда. Во время каждой итерации используйте (Bitmap Object)[https://docs.microsoft.com/en-us/dotnet/api/system.drawing.bitmap?view=netframework-4.8] вместе с его методом GetThumbnail с настроенными размерами изображения. Наконец, сохраните изображение в нужном формате.
{{% blocks/products/pf/feature-page-code h3="C# Преобразователь кода PowerPoint в изображение" %}}
```cs
using (Presentation powerpointtoimage = new Presentation("source-file.ppt")){
foreach (ISlide sld in powerpointtoimage.Slides){

// Create a full scale image
Bitmap bmp = sld.GetThumbnail(1f, 1f);
// or use some customized dimensions as sld.GetThumbnail(x, y)

// Save the image
bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), System.Drawing.Imaging.ImageFormat.Jpeg);
}
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp" >}}