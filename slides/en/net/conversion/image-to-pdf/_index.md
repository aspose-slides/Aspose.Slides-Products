---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert Image to PDF in C#
weight: 30
url: /net/conversion/image-to-pdf/
keywords: Image to PDF, Convert Image to PDF, C# API, .NET Library, Image, JPG, PNG, PDF
description: Convert an image to PDF in C# using Aspose.Slides for .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert Image to PDF in C#" h2="Convert images to PDF documents in C# using server-side Aspose.Slides APIs."
  apiHomeLink="/slides/net/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/net/"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert Image to PDF in C#" %}}

Use [Aspose.Slides for .NET](/slides/net/) to place an image on a slide and save the presentation as a PDF document. Install the package from [NuGet](https://www.nuget.org/packages/Aspose.Slides.NET/) or use the following Package Manager Console command.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Package Manager Console Command" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# code to convert Image to PDF" >}}
```cs
using var presentation = new Presentation();

var imageBytes = File.ReadAllBytes("image.jpg");
var presentationImage = presentation.Images.AddImage(imageBytes);

var slide = presentation.Slides[0];
slide.Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, presentationImage);

presentation.Save("image.pdf", SaveFormat.Pdf);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert Image to PDF in C#" intro="Developers and applications can convert an image to PDF this way:" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the image file bytes.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add the image to a slide with `AddPictureFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call the `Save` method with `SaveFormat.Pdf`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Before you run the image to PDF conversion C# code, make sure that your environment includes the following prerequisites:" %}}

- A supported operating system with .NET or Mono installed.
-  Development environment like Microsoft Visual Studio.
-  Aspose.Slides for .NET referenced in your project.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free Online Converter"
  description="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Conversions" subTitle="Aspose.Slides supports conversion operations for many file formats" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
