---
title: Zoek tekst in PPT presentatiebestanden met behulp van Java
url: /nl/java/search/ppt/
keywords: zoek woorden in PPT, zoek en vervang tekst in PPT, zoek tekst PPT Presentatie
description: Java broncode om tekst te zoeken in PPT Presentatie.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Zoek tekst PPT met behulp van Java" h2="Bouw uw eigen Java-apps om tekst in presentatiebestanden te zoeken en te vervangen met behulp van server-side API's. Leer hoe u alle ingangen van een bepaald woord of een bepaalde woordgroep in presentatiedocumenten kunt vinden. Zoek tekst op basis van exacte gegevensovereenkomst en overeenkomst met reguliere expressies." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Zoek en vervang tekst PPT Presentatie via Java" %}}
Een basisdocument zoeken en tekst vervangen in inhoud, opmerkingen, dia-notities of metadata met Aspose.Slides for Java API's kan worden gedaan met slechts enkele regels code. Gebruik reguliere expressie-overeenkomsten, zoek hoofdletters en kleine letters om tekst in de presentatie te zoeken. Zoek tekst in titels, inhoud, footer of header.
{{% blocks/products/pf/agp/code-block title="Zoek tekst PPT Presentatie met behulp van Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("welcome-to-powerpoint.ppt");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Tekst zoeken in PPT via Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om PPT tekstbestanden te doorzoeken." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad PPT met een instantie van Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Gebruik de methode [FindAndReplaceText](https://reference.aspose.com/slides/java/com.aspose.slides/slideutil/#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) om tekst te zoeken en te vervangen.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla resultaat op in PPT formaat
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPT Zoek live demo's" sectionDescription="Zoek en vervang nu tekst in inhoud, opmerkingen of metadata in PPT documenten." >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde zoekformaten" subTitle="Met Java kunt u ook tekst zoeken in de volgende indelingen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}