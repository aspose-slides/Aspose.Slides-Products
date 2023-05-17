---
title: Redigera PPT presentationsfiler med .NET
url: /sv/net/redaction/ppt/
keywords: Redigera PPT, hitta och ersätt text i PPT, uppdatera PPT presentation
description: Källkod för C# för att hitta och ersätta text i PPT presentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Redigera PPT med C#" h2="Bygg dina egna .NET-appar för att hitta och ersätta text i presentationsfiler med hjälp av API:er på serversidan. Lär dig hur du söker och ersätter text i innehåll, kommentarer eller metadata i PPT-presentationer" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Redigera PPT presentation via C#" %}}
En grundläggande dokumentsökning och ersätt text i innehåll, kommentarer, bildanteckningar eller metadata med Aspose.Slides for .NET API:er kan göras med bara några rader kod. Hitta och ersätt text i PowerPoint och OpenOffice. Redigera text, kommentarer, metadata i presentationen via regexp-datamatchning.
{{% blocks/products/pf/agp/code-block title="Redigera PPT presentation med C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("welcome-to-powerpoint.ppt"))
{
    Aspose.Slides.Util.SlideUtil.FindAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.Save("replaced.ppt", SaveFormat.Ppt);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Så här redigerar du PPT via C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att redigera PPT-filer." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ladda PPT med en instans av Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Använd metoden [FindAndReplaceText](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/findandreplacetext/) för att hitta och ersätta text.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet i formatet PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPT Redaction Live Demos" sectionDescription="Sök och ersätt text i innehåll, kommentarer eller metadata i PPT dokument just nu." >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra Redact-format som stöds" subTitle="Med C# kan du även redigera följande format:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}