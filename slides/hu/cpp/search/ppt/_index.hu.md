---
title: Szöveg keresése PPT prezentációs fájlokban a C++ használatával
url: /hu/cpp/search/ppt/
keywords: szavak keresése PPT nyelven, szöveg keresése és cseréje PPT nyelven, keresési szöveg PPT Bemutatás
description: C++ forráskód a szöveg kereséséhez a PPT prezentációban.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Szöveg keresése PPT a C++ használatával" h2="Készítse el saját C++ alkalmazásait a prezentációs fájlok szövegének kereséséhez és cseréjéhez szerveroldali API-k segítségével. Tanulja meg, hogyan találhat meg egy adott szó vagy kifejezés összes bejáratát a prezentációs dokumentumokban. Szöveg keresése pontos adategyezéssel és reguláris kifejezés-egyezéssel." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Szöveg keresése és cseréje PPT Prezentáció a következőn keresztül: C++" %}}
A Aspose.Slides for C++ API-kkal az alapvető dokumentumok keresése és szöveg cseréje a tartalomban, megjegyzésekben, diajegyzetekben vagy metaadatokban néhány sornyi kóddal elvégezhető. Használjon reguláris kifejezés-illesztést, és párosítsa a kis- és nagybetűket a prezentáció szövegének kereséséhez. Szöveg keresése címekben, tartalomban, láblécben vagy fejlécben.
{{% blocks/products/pf/agp/code-block title="Keresési szöveges PPT prezentáció a C++ használatával" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.ppt");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.ppt", SaveFormat::Ppt);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Szöveg keresése PPT nyelven a C++ segítségével" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések a szöveges PPT fájlok kereséséhez." >}}

{{< blocks/products/pf/agp/step-autogen >}}
A PPT betöltése a Presentation egy példányával.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
A [FindAndReplaceText](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) módszerrel kereshet és cserélhet szöveget.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az eredmény mentése PPT formátumban
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPT Keressen élő bemutatókat" sectionDescription="Keressen és cseréljen szöveget a PPT dokumentumok tartalmában, megjegyzéseiben vagy metaadataiban." >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott keresési formátumok" subTitle="A C++ használatával a következő formátumokban is kereshet szöveget:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}