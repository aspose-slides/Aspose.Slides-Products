---
title: Bewerk PPTX presentatiebestanden met Java
url: /nl/java/redaction/pptx/
keywords: Bewerk PPTX, zoek en vervang tekst in PPTX, update PPTX presentatie
description: Java broncode om tekst in PPTX Presentatie te zoeken en te vervangen.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Bewerk PPTX met Java" h2="Bouw uw eigen Java-apps om tekst in presentatiebestanden te zoeken en te vervangen met behulp van server-side API's. Leer hoe u tekst kunt zoeken en vervangen in inhoud, opmerkingen of metadata van PPTX presentaties" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Presentatie PPTX redigeren via Java" %}}
Een basisdocument zoeken en tekst vervangen in inhoud, opmerkingen, dia-notities of metadata met Aspose.Slides for Java API's kan worden gedaan met slechts enkele regels code. Zoek en vervang tekst in PowerPoint en OpenOffice. Bewerk tekst, opmerkingen, metadata in presentatie via regexp data matching.
{{% blocks/products/pf/agp/code-block title="Bewerk PPTX presentatie met Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("welcome-to-powerpoint.pptx");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="PPTX redigeren via Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om PPTX-bestanden te redigeren." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad PPTX met een instantie van Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Gebruik de methode [FindAndReplaceText](https://reference.aspose.com/slides/java/com.aspose.slides/slideutil/#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) om tekst te zoeken en te vervangen.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla resultaat op in PPTX formaat
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX redactie live demo's" sectionDescription="Zoek en vervang nu tekst in inhoud, opmerkingen of metadata in PPTX documenten." >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde Redact-indelingen" subTitle="Met Java kunt u ook de volgende indelingen redigeren:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/redaction/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}