---
title: Edit PDF in C++
url: /cpp/editor/pdf/
keywords: Edit PDF, PDF, C++ API, C++ Library
description: Edit PDF files in C++. Use Aspose.Slides for C++ to import a PDF, add text, and save the edited PDF file.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Edit PDF in C++" h2="Use Aspose.Slides for C++ to edit PDF files in C++ applications." >}}

{{% blocks/products/pf/feature-page-section h2="Edit PDF using Aspose.Slides" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/cpp/) is a C++ API for working with presentation content and related formats. You can import a `PDF` file into a `Presentation`, add text to a slide, and save the result as `PDF`.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Edit PDF in C++" %}}
Using [**Aspose.Slides for C++**](https://products.aspose.com/slides/cpp/), you can edit a `PDF` file by importing it with `AddFromPdf`, adding a text shape, and saving the result with `SaveFormat::Pdf`.

{{% blocks/products/pf/agp/code-block title="C++ code for editing PDF" offSpacer="true" %}}
```cpp
auto presentation = MakeObject<Presentation>();

presentation->get_Slides()->RemoveAt(0);
presentation->get_Slides()->AddFromPdf(u"document.pdf");

auto slide = presentation->get_Slide(0);
auto textBox = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
textBox->get_TextFrame()->set_Text(u"New text");

presentation->Save(u"document.pdf", SaveFormat::Pdf);
presentation->Dispose();
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to edit PDF in C++" >}}

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
Import the `PDF` file with `AddFromPdf`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a text shape with `AddAutoShape` and `set_Text`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the edited file with `SaveFormat::Pdf`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Edit other files" subTitle="You can also edit files in other formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/editor/ppt/" name="Edit PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/editor/html/" name="Edit HTML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
