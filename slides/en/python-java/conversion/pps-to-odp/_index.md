---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPS to ODP in Python
url: /python-java/conversion/pps-to-odp/
keywords: Python presentation conversion, convert presentations to Python, Python for presentations, Aspose.Slides Python, PPS to ODP conversion, Python presentation library
description: Convert PPS files to editable ODP presentations in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPS to ODP in Python" h2="Transform PowerPoint Show files into editable OpenDocument presentations." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="How to Convert PPS to ODP in Python" variant="code" %}}

Create a `Presentation` from the source PPS file and save it with `SaveFormat.Odp`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python tutorial for converting PPS into ODP" >}}
```python
presentation = Presentation("presentation.pps")
try:
    presentation.save("presentation.odp", SaveFormat.Odp)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPS to ODP in Python" %}}

[Aspose.Slides for Python via Java](/slides/python-java/) can convert a PowerPoint Show (`.pps`) file to an OpenDocument Presentation (`.odp`) file without Microsoft PowerPoint or LibreOffice. The resulting ODP presentation remains editable in applications that support the OpenDocument format.

Load the source file with `Presentation`, then call `save` with `SaveFormat.Odp`. Aspose.Slides handles the format conversion while retaining supported slide content, layout, and formatting.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steps to Convert PPS to ODP in Python" intro="The conversion loads the PowerPoint Show and writes its slides to an OpenDocument presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [Aspose.Slides for Python via Java](/slides/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure JPype and make the Aspose.Slides package available to your Python project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` from the source `.pps` file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Odp` and an `.odp` output path.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPS to Other Supported Formats" subTitle="You can also convert PPS files to the formats listed below." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
