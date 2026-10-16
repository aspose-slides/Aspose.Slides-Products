---
lastmod: 2026-07-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to POTM in Python
url: /python-java/conversion/pdf-to-potm/
keywords: Python presentation conversion, convert presentations to Python, Python for presentations, Aspose.Slides Python, PDF to POTM conversion, Python presentation library
description: Convert PDF documents to PowerPoint POTM macro-enabled presentation templates in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PDF to POTM in Python" h2="Import PDF pages and save them in the PowerPoint POTM macro-enabled template format with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to POTM using Python" variant="code" %}}

Create an empty `Presentation`, remove its default slide, and call `addFromPdf` to import the PDF pages. Then call `save` with `SaveFormat.Potm` to create the POTM file.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PDF to POTM" >}}
```python
presentation = Presentation()
try:
    presentation.getSlides().removeAt(0)
    presentation.getSlides().addFromPdf("document.pdf")
    presentation.save("presentation.potm", SaveFormat.Potm)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to POTM in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can import PDF pages as slides and save the resulting presentation as a POTM file. POTM is the macro-enabled PowerPoint Open XML template format. Because PDF documents do not contain VBA projects, the conversion transfers the page content but does not create macros.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PDF to POTM in Python" intro="Follow these steps to import a PDF document and save its pages in the PowerPoint POTM macro-enabled template format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the PDF pages by calling `addFromPdf` on the presentation's slide collection.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Potm` to create the POTM file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PDF to Other Supported Formats" subTitle="You can also convert PDF documents to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
