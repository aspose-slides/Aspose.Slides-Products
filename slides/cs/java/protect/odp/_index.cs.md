---
title: Chraňte soubory prezentací ODP pomocí Java
url: /cs/java/protect/odp/
keywords: Ochrana proti zápisu ODP, šifrování ODP, zámek ODP prezentace, ochrana ODP
description: Zdrojový kód Java k ochraně prezentace ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Uzamknout nebo chránit heslem ODP pomocí Java" h2="Vytvářejte si vlastní aplikace pro Java, abyste chránili prezentační soubory pomocí rozhraní API na straně serveru." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Ochrana ODP prezentace prostřednictvím Java" %}}
Pomocí Aspose.Slides for Java můžete chránit svou prezentaci ODP před otevřením nebo úpravou nastavením hesla. Poté, aby uživatel mohl otevřít nebo upravit zamčenou prezentaci, musí zadat heslo.
{{% blocks/products/pf/agp/code-block title="Šifrování prezentace ve formátu ODP pomocí Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.odp");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-pres.odp", SaveFormat.Odp);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Nastavení ochrany proti zápisu na prezentaci ve formátu ODP pomocí Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.odp");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-pres.odp", SaveFormat.Odp);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak chránit heslem ODP prostřednictvím Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky k ochraně souborů ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Načtěte ODP s instancí Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chraňte prezentaci pomocí třídy ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte výsledek ve formátu ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Další podporované formáty ochrany" subTitle="Pomocí Java můžete chránit také následující formáty:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}