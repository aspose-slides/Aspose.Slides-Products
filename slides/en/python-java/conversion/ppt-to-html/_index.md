---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPT to HTML in Python
url: /python-java/conversion/ppt-to-html/
keywords: Python PPT conversion, PPT to HTML, PowerPoint to HTML, presentation web export, Aspose.Slides for Python via Java
description: Convert PPT presentations to HTML in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPT to HTML in Python" h2="Publish a legacy PowerPoint presentation as an HTML document with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPT to HTML in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a legacy PowerPoint presentation (`.ppt`) and export its slides and supported content to HTML. The resulting document can be viewed in a web browser without Microsoft PowerPoint.

For a basic conversion, create a `Presentation` and call `save` with `SaveFormat.Html`. Use `HtmlOptions` when you need more control over images, fonts, notes, comments, or other output settings.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPT to HTML using Python" %}}
Load the source PPT file into a `Presentation`, then pass the output path and `SaveFormat.Html` to `save`.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPT to HTML" offSpacer="true" %}}

```python
presentation = Presentation("presentation.ppt")
try:
    presentation.save("presentation.html", SaveFormat.Html)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PPT to HTML in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to export a PowerPoint PPT presentation as an HTML document." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure the package and start the Java Virtual Machine in your application.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the source PPT file with `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with `SaveFormat.Html` and an `.html` output path.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPT to Other Supported Formats" subTitle="You can also convert PPT presentations to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
