---
title: Ontgrendel PPTX presentatiebestanden met Java
url: /nl/java/unlock/pptx/
keywords: Schrijfbeveiliging PPTX verwijderen, een PPTX ontsleutelen, presentatie PPTX ontgrendelen, beveiliging PPTX opheffen
description: Java broncode om de beveiliging van PPTX Presentatie te verwijderen.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Ontgrendel PPTX met Java" h2="Bouw uw eigen Java-apps om wachtwoorden uit PowerPoint te verwijderen en presentatiebestanden te decoderen met behulp van server-side API's." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Versleuteling verwijderen uit PPTX-presentatie via Java" %}}
Met Aspose.Slides for Java kunt u de codering of wachtwoordbeveiliging op de PPTX-presentatie verwijderen. Op deze manier kunnen gebruikers de PPTX-presentatie zonder beperkingen openen of wijzigen.
{{% blocks/products/pf/agp/code-block title="Wachtwoordbeveiliging uitschakelen van PPTX met Java" offSpacer="true" %}}

```java

LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");
Presentation presentation = new Presentation("pres.pptx", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Schrijfbeveiliging verwijderen uit presentatie PPTX met behulp van Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.pptx");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Wachtwoord verwijderen uit PPTX via Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om de beveiliging van PPTX-bestanden te verwijderen." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad PPTX met een instantie van Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Verwijder schrijfbeveiliging met de klasse ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla resultaat op in PPTX formaat
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde formaten" subTitle="Met Java kunt u ook de beveiliging van de volgende indelingen verwijderen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/unlock/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}