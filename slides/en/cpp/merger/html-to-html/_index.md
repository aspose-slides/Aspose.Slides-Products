---
title: Merge HTML Files in C++
url: /cpp/merger/html-to-html/
keywords: Merge HTML, HTML to HTML, Join HTML, Combine HTML, C++ API, C++ Library
description: Merge HTML files in C++. Use Aspose.Slides for C++ to combine HTML content and save the result as an HTML file.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge HTML Files in C++" h2="Use Aspose.Slides for C++ to combine HTML files in C++ applications." >}}

{{% blocks/products/pf/feature-page-section h2="Merge HTML to HTML using Aspose.Slides" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/cpp/) is a C++ API for working with presentation content and related formats. You can read multiple `HTML` files, add their content to a `Presentation`, and save the merged output with `SaveFormat::Html5`.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge HTML to HTML in C++" %}}
Using [**Aspose.Slides for C++**](https://products.aspose.com/slides/cpp/), you can merge `HTML` files by loading their content with `File::ReadAllText`, importing it with `AddFromHtml`, and saving the result as `HTML`.

{{% blocks/products/pf/agp/code-block title="C++ code for merging HTML to HTML" offSpacer="true" %}}
```cpp
auto firstHtmlText = File::ReadAllText(u"first.html");
auto secondHtmlText = File::ReadAllText(u"second.html");
auto presentation = MakeObject<Presentation>();

presentation->get_Slides()->RemoveAt(0);
presentation->get_Slides()->AddFromHtml(firstHtmlText);
presentation->get_Slides()->AddFromHtml(secondHtmlText);

presentation->Save(u"merged.html", SaveFormat::Html5);
presentation->Dispose();
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to merge HTML files in C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for C++**. See [**Installation**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add the library as a reference in your project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Read the source `HTML` files with `File::ReadAllText`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Create a `Presentation` instance and import the `HTML` content with `AddFromHtml`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the merged file with `SaveFormat::Html5`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget appName="merger" extension="" sectionTitle="Merge Files Online" sectionDescription="Merge presentations, documents, and images online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Merge other files" subTitle="You can also combine files in other formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/pdf-to-pdf/" name="PDF TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/svg-to-png/" name="SVG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/image-to-bmp/" name="IMAGE TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/html-to-image/" name="HTML TO IMAGE" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}