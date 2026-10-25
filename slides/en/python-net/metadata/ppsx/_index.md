---
lastmod: 2026-07-30
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: View or Edit PPSX Metadata with Python
url: /python-net/metadata/ppsx/
keywords: Edit PPSX Metadata, View PPSX Metadata, Edit PPSX Properties, View PPSX Properties
description: View and edit built-in and custom metadata properties in PPSX files with Python.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="View and Edit PPSX Metadata with Python" h2="Build Python applications that read and modify built-in and custom presentation properties with Aspose.Slides." related="FODP,ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="View and Modify PPSX Metadata with Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/python-net/) lets you read and update built-in metadata and add, update, or remove custom document properties in PPSX presentations. Access an [`IDocumentProperties`](https://reference.aspose.com/slides/python-net/aspose.slides/idocumentproperties/) object through `Presentation.document_properties`, modify it, and save the presentation in PPSX format.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Update Built-in PPSX Properties - Python" >}}
```python
with slides.Presentation("presentation.ppsx") as presentation:
    document_properties = presentation.document_properties
    document_properties.author = "Aspose.Slides for Python"
    document_properties.title = "Quarterly Review"
    document_properties.subject = "Presentation Metadata"
    document_properties.comments = "Built-in properties updated with Aspose.Slides."
    document_properties.manager = "Project Manager"

    presentation.save("presentation_with_updated_metadata.ppsx", slides.export.SaveFormat.PPSX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Add and Remove Custom PPSX Properties - Python" >}}
```python
with slides.Presentation("presentation.ppsx") as presentation:
    document_properties = presentation.document_properties
    document_properties.set_custom_property_value("Department", "Engineering")
    document_properties.set_custom_property_value("Review Count", 3)
    document_properties.set_custom_property_value("Obsolete Status", "Draft")
    document_properties.remove_custom_property("Obsolete Status")

    presentation.save("presentation_with_custom_metadata.ppsx", slides.export.SaveFormat.PPSX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Edit PPSX Metadata with Python" intro="Follow these steps to edit metadata in a PPSX file." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the PPSX file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Access its `IDocumentProperties` object through `Presentation.document_properties`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Update built-in properties or use `set_custom_property_value` and `remove_custom_property` for custom properties.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the presentation with `Presentation.save` and `SaveFormat.PPSX`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Metadata Formats" subTitle="Use Python to manipulate metadata in other supported presentation formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
