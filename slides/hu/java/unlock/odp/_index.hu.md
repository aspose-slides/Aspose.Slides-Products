---
title: Oldja fel a ODP prezentációs fájlokat a Java használatával
url: /hu/java/unlock/odp/
keywords: Írásvédelem eltávolítása ODP, ODP kód visszafejtése, ODP bemutató feloldása, ODP védelem feloldása
description: Java forráskód a ODP prezentáció védelmének eltávolításához.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Oldja fel a ODP zárolását a Java használatával" h2="Készítse el saját Java-alkalmazásait, amelyek segítségével eltávolíthatja a jelszavakat a PowerPointból, és dekódolhatja a prezentációs fájlokat szerveroldali API-k segítségével." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Titkosítás eltávolítása a ODP prezentációból a következőn keresztül: Java" %}}
A Aspose.Slides for Java használatával eltávolíthatja a titkosítást vagy a jelszavas védelmet a ODP bemutatóról. Így a felhasználók korlátozás nélkül hozzáférhetnek vagy módosíthatják a ODP prezentációt.
{{% blocks/products/pf/agp/code-block title="A jelszavas védelem letiltása a(z) ODP alkalmazásban a(z) Java használatával" offSpacer="true" %}}

```java

LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");
Presentation presentation = new Presentation("pres.odp", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.odp", SaveFormat.Odp);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Az írásvédelem eltávolítása a ODP prezentációból a Java használatával" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.odp");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.odp", SaveFormat.Odp);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jelszó eltávolítása a(z) ODP eszközről a(z) Java segítségével" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések a ODP fájlok védelmének eltávolítására." >}}

{{< blocks/products/pf/agp/step-autogen >}}
A ODP betöltése a Presentation egy példányával
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Távolítsa el az írásvédelmet a ProtectionManager osztály segítségével
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az eredmény mentése ODP formátumban
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott formátumok" subTitle="A Java használatával a következő formátumokból is eltávolíthatja a védelmet:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}