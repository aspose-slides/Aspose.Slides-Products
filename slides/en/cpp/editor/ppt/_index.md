---
title: Edit PPT in C++
url: /cpp/editor/ppt/
keywords: Edit PPT, PPT, C++ API, C++ Library
description: Edit PPT files in C++. Use Aspose.Slides for C++ to modify a PowerPoint presentation and save the edited PPT file.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Edit PPT in C++" h2="Use Aspose.Slides for C++ to edit PPT presentations in C++ applications." >}}

{{% blocks/products/pf/feature-page-section h2="Edit PPT using Aspose.Slides" %}}

[**Aspose.Slides for C++**](/slides/cpp/) is a C++ API for working with PowerPoint presentations. You can load a `PPT` file into a `Presentation`, add text to a slide, and save the result as `PPT`.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Edit PPT in C++" %}}
Using [**Aspose.Slides for C++**](/slides/cpp/), you can edit a `PPT` presentation by loading it with the `Presentation` class, adding a text shape, and saving the result with `SaveFormat::Ppt`.

{{% blocks/products/pf/agp/code-block title="C++ code for editing PPT" offSpacer="true" %}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

auto slide = presentation->get_Slide(0);
auto textBox = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
textBox->get_TextFrame()->set_Text(u"New text");

presentation->Save(u"presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to edit PPT in C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for C++**. See [**Installation**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add the library as a reference in your project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the `PPT` presentation with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Access the slide you want to edit.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Add a text shape with `AddAutoShape` and `set_Text`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Save the edited presentation with `SaveFormat::Ppt`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Edit other files" subTitle="You can also edit files in other formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/editor/pdf/" name="Edit PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/editor/html/" name="Edit HTML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
