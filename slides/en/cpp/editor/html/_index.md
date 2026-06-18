---
title: Edit HTML in C++
url: /cpp/editor/html/
keywords: Edit HTML, HTML, C++ API, C++ Library
description: Edit HTML files in C++. Use Aspose.Slides for C++ to load HTML content, add text, and save the edited HTML file.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Edit HTML in C++" h2="Use Aspose.Slides for C++ to edit HTML files in C++ applications." >}}

{{% blocks/products/pf/feature-page-section h2="Edit HTML using Aspose.Slides" %}}

[**Aspose.Slides for C++**](/slides/cpp/) is a C++ API for working with presentation content and related formats. You can load an `HTML` file into a `Presentation`, add text to a slide, and save the result as `HTML`.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Edit HTML in C++" %}}
Using [**Aspose.Slides for C++**](/slides/cpp/), you can edit an `HTML` file by importing it with `AddFromHtml`, adding a text shape, and saving the result with `SaveFormat::Html5`.

{{% blocks/products/pf/agp/code-block title="C++ code for editing HTML" offSpacer="true" %}}
```cpp
auto htmlText = File::ReadAllText(u"page.html");
auto presentation = MakeObject<Presentation>();

presentation->get_Slides()->RemoveAt(0);
presentation->get_Slides()->AddFromHtml(htmlText);

auto slide = presentation->get_Slide(0);
auto textBox = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
textBox->get_TextFrame()->set_Text(u"New text");

presentation->Save(u"page.html", SaveFormat::Html5);
presentation->Dispose();
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to edit HTML in C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for C++**. See [**Installation**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add the library as a reference in your project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Read the `HTML` file content with `File::ReadAllText`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Create a `Presentation` instance and load the `HTML` content with `AddFromHtml`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a text shape with `AddAutoShape` and `set_Text`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the edited file with `SaveFormat::Html5`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Edit other files" subTitle="You can also edit files in other formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/editor/ppt/" name="Edit PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/editor/pdf/" name="Edit PDF" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
