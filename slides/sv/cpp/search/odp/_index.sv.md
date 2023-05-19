---
title: Sök text i ODP presentationsfiler med C++
url: /sv/cpp/search/odp/
keywords: sök ord i ODP, sök och ersätt text i ODP, sök text ODP Presentation
description: C++ källkod för att söka text i ODP presentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Sök text ODP med C++" h2="Bygg dina egna appar för C++ för att söka och ersätta text i presentationsfiler med hjälp av API:er på serversidan. Lär dig hur du hittar alla ingångar till ett visst ord eller en fras i presentationsdokument. Sök text med exakt datamatchning och matchning av reguljära uttryck." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Sök och ersätt text ODP presentation via C++" %}}
En grundläggande dokumentsökning och ersätt text i innehåll, kommentarer, bildanteckningar eller metadata med Aspose.Slides for C++ API:er kan göras med bara några rader kod. Använd reguljära uttrycksmatchning, matcha skiftläge för att söka efter text i presentationen. Sök text i rubriker, innehåll, sidfot eller sidhuvud.
{{% blocks/products/pf/agp/code-block title="Sök text ODP Presentation med C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.odp");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.odp", SaveFormat::Odp);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hur man söker efter text i ODP via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att söka efter textfiler i ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ladda ODP med en instans av Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Använd metoden [FindAndReplaceText](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) för att hitta och ersätta text.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet i formatet ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Sök livedemos" sectionDescription="Sök och ersätt text i innehåll, kommentarer eller metadata i ODP dokument just nu." >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra sökformat som stöds" subTitle="Med C++ kan du även söka efter text i följande format:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}