---
title: Bewerk ODP presentatiebestanden met C++
url: /nl/cpp/redaction/odp/
keywords: Bewerk ODP, zoek en vervang tekst in ODP, update ODP presentatie
description: C++ broncode om tekst in ODP Presentatie te zoeken en te vervangen.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Bewerk ODP met C++" h2="Bouw uw eigen C++-apps om tekst in presentatiebestanden te zoeken en te vervangen met behulp van server-side API's. Leer hoe u tekst kunt zoeken en vervangen in inhoud, opmerkingen of metadata van ODP presentaties" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Presentatie ODP redigeren via C++" %}}
Een basisdocument zoeken en tekst vervangen in inhoud, opmerkingen, dia-notities of metadata met Aspose.Slides for C++ API's kan worden gedaan met slechts enkele regels code. Zoek en vervang tekst in PowerPoint en OpenOffice. Bewerk tekst, opmerkingen, metadata in presentatie via regexp data matching.
{{% blocks/products/pf/agp/code-block title="Bewerk ODP presentatie met C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.odp");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.odp", SaveFormat::Odp);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="ODP redigeren via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om ODP-bestanden te redigeren." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad ODP met een instantie van Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Gebruik de methode [FindAndReplaceText](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) om tekst te zoeken en te vervangen.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla resultaat op in ODP formaat
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online ODP redactie live demo's" sectionDescription="Zoek en vervang nu tekst in inhoud, opmerkingen of metadata in ODP documenten." >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde Redact-indelingen" subTitle="Met C++ kunt u ook de volgende indelingen redigeren:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}