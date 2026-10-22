---
lastmod: 2026-07-09
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Edit PPT in C++
url: /cpp/editor/ppt/
keywords: Edit PPT, PPT, C++ API, C++ Library
description: Edit PPT files in C++. Use Aspose.Slides for C++ to modify a PowerPoint presentation and save the edited PPT file.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Edit PPT in C++" h2="Use Aspose.Slides for C++ to edit PPT presentations in C++ applications." related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edit PPT in C++" variant="code" %}}

Using [**Aspose.Slides for C++**](/slides/cpp/), you can edit a `PPT` presentation by loading it with the `Presentation` class, adding a text shape, and saving the result with `SaveFormat::Ppt`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ code for editing PPT" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

auto slide = presentation->get_Slide(0);
auto textBox = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
textBox->get_TextFrame()->set_Text(u"New text");

presentation->Save(u"presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edit PPT using Aspose.Slides" %}}

[**Aspose.Slides for C++**](/slides/cpp/) is a C++ API for working with PowerPoint presentations. You can load a `PPT` file into a `Presentation`, add text to a slide, and save the result as `PPT`.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to edit PPT in C++" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install **Aspose.Slides for C++**. See [**Installation**](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add the library as a reference in your project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the `PPT` presentation with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Access the slide you want to edit.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add a text shape with `AddAutoShape` and `set_Text`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the edited presentation with `SaveFormat::Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Edit other files" subTitle="You can also edit files in other formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/editor/pdf/" name="Edit PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
