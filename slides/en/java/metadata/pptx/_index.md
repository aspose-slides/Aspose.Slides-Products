---
title: View or Edit PPTX Files Metadata using Java
url: /java/metadata/pptx/
keywords: Edit PPTX Metadata, View PPTX Metadata, Edit PPTX properties, View PPTX properties
description: View and edit PPTX metadata in Java. Use Aspose.Slides for Java to update built-in and custom presentation properties.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Edit PPTX properties using Java" h2="Build Java applications that modify built-in and custom properties in presentation files using server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="PPSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Modify PPTX Properties via Java" %}}
Using [Aspose.Slides for Java](/slides/java/), developers can access and modify built-in and custom presentation properties. Use the `getDocumentProperties` method on a `Presentation` object to access the `IDocumentProperties` object for the presentation file.
{{% blocks/products/pf/agp/code-block title="Modify PPTX Built-in Properties - Java" offSpacer="true" %}}

```java
Presentation presentation = new Presentation("Presentation.pptx");
try {
    IDocumentProperties documentProperties = presentation.getDocumentProperties();

    documentProperties.setAuthor("Aspose.Slides for Java");
    documentProperties.setTitle("Modifying Presentation Properties");
    documentProperties.setSubject("Aspose Subject");
    documentProperties.setComments("Aspose Description");
    documentProperties.setManager("Aspose Manager");

    presentation.save("DocProps.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Add Custom Properties to PPTX - Java" offSpacer="true" %}}

```java
Presentation presentation = new Presentation();
try {
    IDocumentProperties documentProperties = presentation.getDocumentProperties();

    documentProperties.set_Item("New Custom", 12);
    documentProperties.set_Item("My Name", "Aspose Metadata Editor");
    documentProperties.set_Item("Custom", 124);

    String customPropertyName = documentProperties.getCustomPropertyName(2);
    documentProperties.removeCustomProperty(customPropertyName);

    presentation.save("CustomDemo.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Extract Metadata of PPTX via Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to extract metadata from PPTX files." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the `PPTX` file with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call the `getDocumentProperties` method to get the `IDocumentProperties` object.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Read or update built-in properties such as `Author`, `Title`, `Subject`, and `Comments`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Access and modify custom properties with `set_Item`, `getCustomPropertyName`, and `removeCustomProperty`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Metadata Formats" subTitle="Using Java, you can also manipulate metadata in many other formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/metadata/pptm/" name="PPTM" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
