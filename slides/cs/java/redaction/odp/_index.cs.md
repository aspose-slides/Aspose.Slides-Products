---
title: Úprava souborů prezentace ODP pomocí Java
url: /cs/java/redaction/odp/
keywords: Upravit ODP, najít a nahradit text ve ODP, aktualizovat ODP prezentaci
description: Zdrojový kód Java k vyhledání a nahrazení textu v prezentaci ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Redigovat ODP pomocí Java" h2="Vytvářejte si vlastní aplikace pro Java, pomocí kterých můžete vyhledávat a nahrazovat text v prezentačních souborech pomocí rozhraní API na straně serveru. Naučte se vyhledávat a nahrazovat text v obsahu, komentářích nebo metadatech prezentací ve formátu ODP" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Úprava ODP prezentace prostřednictvím Java" %}}
Základní vyhledávání dokumentů a nahrazování textu v obsahu, komentářích, poznámkách ke snímkům nebo metadatech pomocí rozhraní API Aspose.Slides for Java lze provést pomocí několika řádků kódu. Najděte a nahraďte text v PowerPointu a OpenOffice. Upravte text, komentáře, metadata v prezentaci pomocí párování regulárních výrazů.
{{% blocks/products/pf/agp/code-block title="Upravit prezentaci ODP pomocí Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.odp", SaveFormat.Odp);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak upravit ODP prostřednictvím Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky k úpravě souborů ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Načtěte ODP s instancí Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
K vyhledání a nahrazení textu použijte metodu [FindAndReplaceText](https://reference.aspose.com/slides/java/com.aspose.slides/slideutil/#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte výsledek ve formátu ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online ODP redakční živé ukázky" sectionDescription="Vyhledejte a nahraďte text v obsahu, komentářích nebo metadatech v dokumentech ODP právě teď." >}}

{{< blocks/products/pf/agp/other-supported-section title="Další podporované formáty Redact" subTitle="Pomocí Java můžete také upravit následující formáty:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}