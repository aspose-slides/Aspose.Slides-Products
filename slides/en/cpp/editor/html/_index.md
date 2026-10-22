---
lastmod: 2026-07-09
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Edit HTML in C++
url: /cpp/editor/html/
keywords: Edit HTML, HTML, C++ API, C++ Library
description: Edit HTML files in C++. Use Aspose.Slides for C++ to load HTML content, add text, and save the edited HTML file.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Edit HTML in C++" h2="Use Aspose.Slides for C++ to edit HTML files in C++ applications." related="PPT,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edit HTML in C++" variant="code" %}}

Using [**Aspose.Slides for C++**](/slides/cpp/), you can edit an `HTML` file by importing it with `AddFromHtml`, adding a text shape, and saving the result with `SaveFormat::Html5`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ code for editing HTML" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edit HTML using Aspose.Slides" %}}

[**Aspose.Slides for C++**](/slides/cpp/) is a C++ API for working with presentation content and related formats. You can load an `HTML` file into a `Presentation`, add text to a slide, and save the result as `HTML`.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to edit HTML in C++" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install **Aspose.Slides for C++**. See [**Installation**](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add the library as a reference in your project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Read the `HTML` file content with `File::ReadAllText`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` instance and load the `HTML` content with `AddFromHtml`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add a text shape with `AddAutoShape` and `set_Text`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the edited file with `SaveFormat::Html5`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Edit other files" subTitle="You can also edit files in other formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/editor/ppt/" name="Edit PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/editor/pdf/" name="Edit PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
