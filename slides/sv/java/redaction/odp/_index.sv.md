---
title: Redigera ODP presentationsfiler med Java
url: /sv/java/redaction/odp/
keywords: Redigera ODP, hitta och ersätt text i ODP, uppdatera ODP presentation
description: Källkod för Java för att hitta och ersätta text i ODP presentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Redigera ODP med Java" h2="Bygg dina egna Java-appar för att hitta och ersätta text i presentationsfiler med hjälp av API:er på serversidan. Lär dig hur du söker och ersätter text i innehåll, kommentarer eller metadata i ODP-presentationer" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Redigera ODP presentation via Java" %}}
En grundläggande dokumentsökning och ersätt text i innehåll, kommentarer, bildanteckningar eller metadata med Aspose.Slides for Java API:er kan göras med bara några rader kod. Hitta och ersätt text i PowerPoint och OpenOffice. Redigera text, kommentarer, metadata i presentationen via regexp-datamatchning.
{{% blocks/products/pf/agp/code-block title="Redigera ODP presentation med Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.odp", SaveFormat.Odp);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Så här redigerar du ODP via Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att redigera ODP-filer." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ladda ODP med en instans av Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Använd metoden [FindAndReplaceText](https://reference.aspose.com/slides/java/com.aspose.slides/slideutil/#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) för att hitta och ersätta text.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet i formatet ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Redaction Live Demos" sectionDescription="Sök och ersätt text i innehåll, kommentarer eller metadata i ODP dokument just nu." >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra Redact-format som stöds" subTitle="Med Java kan du även redigera följande format:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}