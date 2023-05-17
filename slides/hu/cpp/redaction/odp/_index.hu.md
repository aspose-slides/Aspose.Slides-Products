---
title: A ODP prezentációs fájlok szerkesztése a C++ használatával
url: /hu/cpp/redaction/odp/
keywords: ODP szerkesztése, szöveg keresése és cseréje a következőben ODP, ODP prezentáció frissítése
description: C++ forráskód a ODP prezentáció szövegének megkereséséhez és cseréjéhez.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="A ODP szerkesztése a C++ használatával" h2="Készítse el saját C++-alkalmazásait a prezentációs fájlok szövegének megtalálásához és cseréjéhez szerveroldali API-k segítségével. Ismerje meg, hogyan kereshet és cserélhet szöveget a ODP prezentációk tartalmában, megjegyzéseiben vagy metaadataiban" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="A ODP prezentáció szerkesztése a következőn keresztül: C++" %}}
A Aspose.Slides for C++ API-kkal az alapvető dokumentumok keresése és szöveg cseréje a tartalomban, megjegyzésekben, diajegyzetekben vagy metaadatokban néhány sornyi kóddal elvégezhető. Szöveg keresése és cseréje a PowerPointban és az OpenOffice-ban. Szöveg, megjegyzések, metaadatok szerkesztése a prezentációban reguláris kifejezéssel.
{{% blocks/products/pf/agp/code-block title="A ODP prezentáció szerkesztése a C++ használatával" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.odp");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.odp", SaveFormat::Odp);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="A ODP szerkesztése a C++ segítségével" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések a ODP fájlok szerkesztéséhez." >}}

{{< blocks/products/pf/agp/step-autogen >}}
A ODP betöltése a Presentation egy példányával.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
A [FindAndReplaceText](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) módszerrel kereshet és cserélhet szöveget.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az eredmény mentése ODP formátumban
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online ODP szerkesztés élő bemutatók" sectionDescription="Keressen és cseréljen szöveget a ODP dokumentumok tartalmában, megjegyzéseiben vagy metaadataiban." >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott Redact formátumok" subTitle="A C++ használatával a következő formátumokat is szerkesztheti:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}