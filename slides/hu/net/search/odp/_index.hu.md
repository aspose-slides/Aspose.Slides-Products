---
title: Szöveg keresése ODP prezentációs fájlokban a .NET használatával
url: /hu/net/search/odp/
keywords: szavak keresése ODP nyelven, szöveg keresése és cseréje ODP nyelven, keresési szöveg ODP Bemutatás
description: C# forráskód a szöveg kereséséhez a ODP prezentációban.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Szöveg keresése ODP a C# használatával" h2="Készítse el saját .NET alkalmazásait a prezentációs fájlok szövegének kereséséhez és cseréjéhez szerveroldali API-k segítségével. Tanulja meg, hogyan találhat meg egy adott szó vagy kifejezés összes bejáratát a prezentációs dokumentumokban. Szöveg keresése pontos adategyezéssel és reguláris kifejezés-egyezéssel." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Szöveg keresése és cseréje ODP Prezentáció a következőn keresztül: C#" %}}
A Aspose.Slides for .NET API-kkal az alapvető dokumentumok keresése és szöveg cseréje a tartalomban, megjegyzésekben, diajegyzetekben vagy metaadatokban néhány sornyi kóddal elvégezhető. Használjon reguláris kifejezés-illesztést, és párosítsa a kis- és nagybetűket a prezentáció szövegének kereséséhez. Szöveg keresése címekben, tartalomban, láblécben vagy fejlécben.
{{% blocks/products/pf/agp/code-block title="Keresési szöveges ODP prezentáció a C# használatával" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("welcome-to-powerpoint.odp"))
{
    Aspose.Slides.Util.SlideUtil.FindAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.Save("replaced.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Szöveg keresése ODP nyelven a C# segítségével" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések a szöveges ODP fájlok kereséséhez." >}}

{{< blocks/products/pf/agp/step-autogen >}}
A ODP betöltése a Presentation egy példányával.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
A [FindAndReplaceText](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/findandreplacetext/) módszerrel kereshet és cserélhet szöveget.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az eredmény mentése ODP formátumban
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Keressen élő bemutatókat" sectionDescription="Keressen és cseréljen szöveget a ODP dokumentumok tartalmában, megjegyzéseiben vagy metaadataiban." >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott keresési formátumok" subTitle="A C# használatával a következő formátumokban is kereshet szöveget:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}