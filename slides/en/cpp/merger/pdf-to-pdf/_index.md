---
title: Merge PDF Files in C++
url: /cpp/merger/pdf-to-pdf/
keywords: Merge PDF, PDF to PDF, Join PDF, Combine PDF, C++ API, C++ Library
description: Merge PDF files in C++. Use Aspose.Slides for C++ to import PDF files and save the merged result as PDF.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge PDF Files in C++" h2="Use Aspose.Slides for C++ to combine PDF files in C++ applications." >}}

{{% blocks/products/pf/feature-page-section h2="Merge PDF to PDF using Aspose.Slides" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/cpp/) is a C++ API for working with presentation content and `PDF` files. You can import multiple `PDF` files into a `Presentation` and save the combined result as a single `PDF` file.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge PDF to PDF in C++" %}}
Using [**Aspose.Slides for C++**](https://products.aspose.com/slides/cpp/), you can merge `PDF` files by importing them with `AddFromPdf` and saving the presentation with `SaveFormat::Pdf`.

{{% blocks/products/pf/agp/code-block title="C++ code for merging PDF to PDF" offSpacer="true" %}}
```cpp
auto presentation = MakeObject<Presentation>();

presentation->get_Slides()->RemoveAt(0);
presentation->get_Slides()->AddFromPdf(u"first.pdf");
presentation->get_Slides()->AddFromPdf(u"second.pdf");

presentation->Save(u"merged.pdf", SaveFormat::Pdf);
presentation->Dispose();
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to merge PDF files in C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for C++**. See [**Installation**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add the library as a reference in your project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Create a `Presentation` instance.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Import the source `PDF` files with `AddFromPdf`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the merged file with `SaveFormat::Pdf`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget appName="merger" extension="" sectionTitle="Merge Files Online" sectionDescription="Merge presentations, documents, and images online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Merge other files" subTitle="You can also combine files in other formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/png-to-pdf/" name="PNG TO PDF" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}