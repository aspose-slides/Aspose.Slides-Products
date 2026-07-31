---
title: Merge HTML Files in C#
url: /net/merger/html-to-html/
keywords: Merge HTML, HTML to HTML, Join HTML, Combine HTML, C# API, .NET Library
description: Merge HTML files in C#. Use the .NET library API to combine HTML content into a single HTML file.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge HTML in C#" h2="Merge HTML files with a cross-platform .NET API." >}}

{{% blocks/products/pf/feature-page-section h2="Merge HTML to HTML using Aspose.Slides" %}}

[**Aspose.Slides for .NET**](/slides/net/) lets you create, convert, merge, and manipulate presentations, HTML files, and other documents. When you merge HTML files, you combine content from multiple HTML documents and save it as one HTML file while preserving presentation content and formatting.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Merge HTML to HTML in C#" %}}
Using [**Aspose.Slides for .NET**](/slides/net/), you can load HTML content into a `Presentation` object and save the result as an HTML file.

{{% blocks/products/pf/agp/code-block title="C# code for merging HTML to HTML" offSpacer="true" %}}
```cs
using var presentation = new Presentation();
presentation.Slides.RemoveAt(0);
presentation.Slides.AddFromHtml(File.ReadAllText("page1.html"));
presentation.Slides.AddFromHtml(File.ReadAllText("page2.html"));
presentation.Save("merged.html", SaveFormat.Html);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to merge HTML in C#" >}}


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
Load the HTML files with `Slides.AddFromHtml`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Save the merged file with `SaveFormat.Html`.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="Merge HTML Files Online" sectionDescription="Combine files online with Aspose.Slides Merger." >}}

{{< blocks/products/pf/agp/other-supported-section title="Merge other files" subTitle="You can also combine files in other formats to get a single file" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/pdf-to-pdf/" name="PDF TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/svg-to-png/" name="SVG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/image-to-bmp/" name="IMAGE TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/html-to-image/" name="HTML TO IMAGE" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
