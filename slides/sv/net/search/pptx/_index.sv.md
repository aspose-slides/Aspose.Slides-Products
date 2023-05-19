---
title: Sök text i PPTX presentationsfiler med .NET
url: /sv/net/search/pptx/
keywords: sök ord i PPTX, sök och ersätt text i PPTX, sök text PPTX Presentation
description: C# källkod för att söka text i PPTX presentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Sök text PPTX med C#" h2="Bygg dina egna appar för .NET för att söka och ersätta text i presentationsfiler med hjälp av API:er på serversidan. Lär dig hur du hittar alla ingångar till ett visst ord eller en fras i presentationsdokument. Sök text med exakt datamatchning och matchning av reguljära uttryck." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Sök och ersätt text PPTX presentation via C#" %}}
En grundläggande dokumentsökning och ersätt text i innehåll, kommentarer, bildanteckningar eller metadata med Aspose.Slides for .NET API:er kan göras med bara några rader kod. Använd reguljära uttrycksmatchning, matcha skiftläge för att söka efter text i presentationen. Sök text i rubriker, innehåll, sidfot eller sidhuvud.
{{% blocks/products/pf/agp/code-block title="Sök text PPTX Presentation med C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("welcome-to-powerpoint.pptx"))
{
    Aspose.Slides.Util.SlideUtil.FindAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.Save("replaced.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hur man söker efter text i PPTX via C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att söka efter textfiler i PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ladda PPTX med en instans av Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Använd metoden [FindAndReplaceText](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/findandreplacetext/) för att hitta och ersätta text.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet i formatet PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX Sök livedemos" sectionDescription="Sök och ersätt text i innehåll, kommentarer eller metadata i PPTX dokument just nu." >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra sökformat som stöds" subTitle="Med C# kan du även söka efter text i följande format:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/search/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}