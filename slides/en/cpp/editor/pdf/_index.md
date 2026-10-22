---
lastmod: 2026-07-09
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Edit PDF in C++
url: /cpp/editor/pdf/
keywords: Edit PDF, PDF, C++ API, C++ Library
description: Edit PDF files in C++. Use Aspose.Slides for C++ to import a PDF, add text, and save the edited PDF file.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Edit PDF in C++" h2="Use Aspose.Slides for C++ to edit PDF files in C++ applications." related="PPT,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edit PDF in C++" variant="code" %}}

Using [**Aspose.Slides for C++**](/slides/cpp/), you can edit a `PDF` file by importing it with `AddFromPdf`, adding a text shape, and saving the result with `SaveFormat::Pdf`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ code for editing PDF" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edit PDF using Aspose.Slides" %}}

[**Aspose.Slides for C++**](/slides/cpp/) is a C++ API for working with presentation content and related formats. You can import a `PDF` file into a `Presentation`, add text to a slide, and save the result as `PDF`.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to edit PDF in C++" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install **Aspose.Slides for C++**. See [**Installation**](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add the library as a reference in your project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` instance.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the `PDF` file with `AddFromPdf`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add a text shape with `AddAutoShape` and `set_Text`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the edited file with `SaveFormat::Pdf`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Edit other files" subTitle="You can also edit files in other formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/editor/ppt/" name="Edit PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
