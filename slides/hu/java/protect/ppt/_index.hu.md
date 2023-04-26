---
title: A PPT prezentációs fájlok védelme a Java használatával
url: /hu/java/protect/ppt/
keywords: Írásvédelem PPT, PPT titkosítása, PPT bemutató zárolása, PPT védelme
description: Java forráskód a PPT prezentáció védelmére.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Zárolás vagy jelszavas védelem PPT a Java használatával" h2="Készítse el saját Java alkalmazásait a prezentációs fájlok védelméhez szerveroldali API-k segítségével." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="A PPT prezentáció védelme a Java segítségével" %}}
A Aspose.Slides for Java használatával jelszó megadásával megvédheti PPT prezentációját a megnyitástól vagy módosítástól. Ezután a zárolt bemutató megnyitásához vagy módosításához a felhasználónak meg kell adnia a jelszót.
{{% blocks/products/pf/agp/code-block title="PPT prezentáció titkosítása a Java használatával" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.ppt");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-pres.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Írásvédelem beállítása PPT prezentációra a Java használatával" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.ppt");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-pres.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="A PPT jelszavas védelme a Java segítségével" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések a PPT fájlok védelméhez." >}}

{{< blocks/products/pf/agp/step-autogen >}}
A PPT betöltése a Presentation egy példányával
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Védje a prezentációt a ProtectionManager osztály segítségével
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az eredmény mentése PPT formátumban
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott védelmi formátumok" subTitle="A Java használatával a következő formátumokat is védheti:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}