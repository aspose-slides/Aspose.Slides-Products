---
title: Sök text i ODP presentationsfiler med Python
url: /sv/python-net/search/odp/
keywords: sök ord i ODP, sök och ersätt text i ODP, sök text ODP Presentation
description: Python källkod för att söka text i ODP presentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Sök text ODP med Python" h2="Bygg dina egna appar för Python för att söka och ersätta text i presentationsfiler med hjälp av API:er på serversidan. Lär dig hur du hittar alla ingångar till ett visst ord eller en fras i presentationsdokument. Sök text med exakt datamatchning och matchning av reguljära uttryck." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Sök och ersätt text ODP presentation via Python" %}}
En grundläggande dokumentsökning och ersätt text i innehåll, kommentarer, bildanteckningar eller metadata med Aspose.Slides for Python via .NET API:er kan göras med bara några rader kod. Använd reguljära uttrycksmatchning, matcha skiftläge för att söka efter text i presentationen. Sök text i rubriker, innehåll, sidfot eller sidhuvud.
{{% blocks/products/pf/agp/code-block title="Sök text ODP Presentation med Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.odp") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hur man söker efter text i ODP via Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att söka efter textfiler i ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ladda ODP med en instans av Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Använd metoden [FindAndReplaceText](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) för att hitta och ersätta text.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet i formatet ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Sök livedemos" sectionDescription="Sök och ersätt text i innehåll, kommentarer eller metadata i ODP dokument just nu." >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra sökformat som stöds" subTitle="Med Python kan du även söka efter text i följande format:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}