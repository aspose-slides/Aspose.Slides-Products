---
title: Redigera PPTX presentationsfiler med C++
url: /sv/cpp/redaction/pptx/
keywords: Redigera PPTX, hitta och ersätt text i PPTX, uppdatera PPTX presentation
description: Källkod för C++ för att hitta och ersätta text i PPTX presentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Redigera PPTX med C++" h2="Bygg dina egna C++-appar för att hitta och ersätta text i presentationsfiler med hjälp av API:er på serversidan. Lär dig hur du söker och ersätter text i innehåll, kommentarer eller metadata i PPTX-presentationer" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Redigera PPTX presentation via C++" %}}
En grundläggande dokumentsökning och ersätt text i innehåll, kommentarer, bildanteckningar eller metadata med Aspose.Slides for C++ API:er kan göras med bara några rader kod. Hitta och ersätt text i PowerPoint och OpenOffice. Redigera text, kommentarer, metadata i presentationen via regexp-datamatchning.
{{% blocks/products/pf/agp/code-block title="Redigera PPTX presentation med C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.pptx");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.pptx", SaveFormat::Pptx);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Så här redigerar du PPTX via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att redigera PPTX-filer." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ladda PPTX med en instans av Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Använd metoden [FindAndReplaceText](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) för att hitta och ersätta text.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet i formatet PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX Redaction Live Demos" sectionDescription="Sök och ersätt text i innehåll, kommentarer eller metadata i PPTX dokument just nu." >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra Redact-format som stöds" subTitle="Med C++ kan du även redigera följande format:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/redaction/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}