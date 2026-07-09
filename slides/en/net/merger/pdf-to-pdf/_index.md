---
title: Merge PDF Files in C#
url: /net/merger/pdf-to-pdf/
keywords: Merge PDF, PDF to PDF, Join PDF, Combine PDF, C# API, .NET Library
description: Merge PDF files in C#. Use the .NET library API to combine PDF documents into a single PDF file.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge PDF in C#" h2="Combine PDF files with a cross-platform .NET API." >}}

{{% blocks/products/pf/feature-page-section h2="Merge PDF to PDF using Aspose.Slides" %}}

[**Aspose.Slides for .NET**](/slides/net/) lets you create, convert, merge, and manipulate presentations, PDFs, and other documents. You can import pages from several PDF files into one presentation and save the result as a single PDF file.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Merge PDF to PDF in C#" %}}
Using [**Aspose.Slides for .NET**](/slides/net/), you can load PDF files with `Slides.AddFromPdf` and save the result with `SaveFormat.Pdf`.

{{% blocks/products/pf/agp/code-block title="C# code for merging PDF to PDF" offSpacer="true" %}}
```cs
using var presentation = new Presentation();
presentation.Slides.RemoveAt(0);

presentation.Slides.AddFromPdf("first.pdf");
presentation.Slides.AddFromPdf("second.pdf");

presentation.Save("merged.pdf", SaveFormat.Pdf);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to merge PDF in C#" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{% blocks/products/pf/agp/step-autogen %}}
Install **Aspose.Slides for .NET**. See [**Installation**](https://docs.aspose.com/slides/net/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Add the library as a reference in your project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` object.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the PDF files with `Slides.AddFromPdf`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Save the merged file with `SaveFormat.Pdf`.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="Merge PDF Files Online" sectionDescription="Combine files online with Aspose.Slides Merger." >}}

{{< blocks/products/pf/agp/other-supported-section title="Merge other files" subTitle="You can also combine files in other formats to get a single file" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/png-to-pdf/" name="PNG TO PDF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
