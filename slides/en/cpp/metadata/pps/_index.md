---
title: View or Edit PPS Metadata using C++
url: /cpp/metadata/pps/
keywords: Edit PPS Metadata, View PPS Metadata, Edit PPS properties, View PPS properties
description: View and edit PPS metadata in C++. Use Aspose.Slides for C++ to update built-in and custom presentation properties.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Edit PPS Metadata using C++" h2="Use Aspose.Slides for C++ to view and update built-in and custom properties in presentation files." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPS" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="PPSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Modify PPS Properties via C++" %}}
Aspose.Slides for C++ lets you read and update metadata in PPS files without Microsoft PowerPoint. Use the [`DocumentProperties`](https://reference.aspose.com/slides/cpp/aspose.slides/documentproperties/) object exposed by `Presentation::get_DocumentProperties` to change built-in properties such as `Author` and `Title`, or to manage custom properties with `idx_set`, `GetCustomPropertyName`, and `RemoveCustomProperty`.
{{% blocks/products/pf/agp/code-block title="Modify PPS Built-in Properties - C++" offSpacer="true" %}}

```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pps");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->set_Author(u"New Author");
documentProperties->set_Title(u"New Title");

presentation->Save(u"updated-presentation.pps", SaveFormat::Pps);
presentation->Dispose();
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Add Custom Properties to PPS - C++" offSpacer="true" %}}

```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pps");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->idx_set(u"Department", ObjectExt::Box<String>(u"Sales"));
documentProperties->idx_set(u"Project", ObjectExt::Box<String>(u"Metadata Update"));
documentProperties->idx_set(u"Revision", ObjectExt::Box<int32_t>(3));

auto customPropertyName = documentProperties->GetCustomPropertyName(2);
documentProperties->RemoveCustomProperty(customPropertyName);

presentation->Save(u"updated-custom-properties.pps", SaveFormat::Pps);
presentation->Dispose();
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Extract Metadata of PPS via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to extract metadata from PPS files." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the PPS file with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Get the `DocumentProperties` object with `get_DocumentProperties`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Read or update built-in properties such as `Author` and `Title`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Add, read, or remove custom properties with `idx_set`, `GetCustomPropertyName`, and `RemoveCustomProperty`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Metadata Formats" subTitle="You can also view and edit metadata in other presentation formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/metadata/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
