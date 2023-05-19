---
title: Szöveg keresése PPTX prezentációs fájlokban a Java használatával
url: /hu/java/search/pptx/
keywords: szavak keresése PPTX nyelven, szöveg keresése és cseréje PPTX nyelven, keresési szöveg PPTX Bemutatás
description: Java forráskód a szöveg kereséséhez a PPTX prezentációban.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Szöveg keresése PPTX a Java használatával" h2="Készítse el saját Java alkalmazásait a prezentációs fájlok szövegének kereséséhez és cseréjéhez szerveroldali API-k segítségével. Tanulja meg, hogyan találhat meg egy adott szó vagy kifejezés összes bejáratát a prezentációs dokumentumokban. Szöveg keresése pontos adategyezéssel és reguláris kifejezés-egyezéssel." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Szöveg keresése és cseréje PPTX Prezentáció a következőn keresztül: Java" %}}
A Aspose.Slides for Java API-kkal az alapvető dokumentumok keresése és szöveg cseréje a tartalomban, megjegyzésekben, diajegyzetekben vagy metaadatokban néhány sornyi kóddal elvégezhető. Használjon reguláris kifejezés-illesztést, és párosítsa a kis- és nagybetűket a prezentáció szövegének kereséséhez. Szöveg keresése címekben, tartalomban, láblécben vagy fejlécben.
{{% blocks/products/pf/agp/code-block title="Keresési szöveges PPTX prezentáció a Java használatával" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Szöveg keresése PPTX nyelven a Java segítségével" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések a szöveges PPTX fájlok kereséséhez." >}}

{{< blocks/products/pf/agp/step-autogen >}}
A PPTX betöltése a Presentation egy példányával.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
A [FindAndReplaceText](https://reference.aspose.com/slides/java/com.aspose.slides/slideutil/#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) módszerrel kereshet és cserélhet szöveget.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az eredmény mentése PPTX formátumban
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX Keressen élő bemutatókat" sectionDescription="Keressen és cseréljen szöveget a PPTX dokumentumok tartalmában, megjegyzéseiben vagy metaadataiban." >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott keresési formátumok" subTitle="A Java használatával a következő formátumokban is kereshet szöveget:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/search/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}