---
title: Slå samman PDF, PPT, PPTX och många andra filformat med C++
url: /sv/cpp/merger/
keywords: Sammanfoga, gå med, PowerPoint, Presentation, C++, Aspose
description: Slå samman flera filer i C++ PPT, PPTX, ODP, PDF, PNG, JPG och många fler.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Slå ihop Powerpoint, PDF, PPT eller andra dokument i C++" h2="Höghastighets C++-bibliotek för att slå samman PPT, PPTX, PDF, PNG, JPEG och andra format." >}}

{{% blocks/products/pf/feature-page-section h2="Slå samman PPT, PPTX, PDF med C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/sv/cpp/) är ett kraftfullt C++-bibliotek för att skapa och manipulera presentationsfiler. Dessutom ger det flexibla sätt att kombinera flera PPT/PPTX-presentationer. När du slår samman en presentation med en annan, kombinerar du effektivt deras bilder i en enda presentation för att få en fil. Aspose.Slides låter dig slå samman två presentationer på olika sätt. Du får sammanfoga presentationer med alla deras former, stilar, texter, formatering, kommentarer, animationer, etc. utan att behöva oroa dig för förlust av kvalitet eller data.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Slå samman PowerPoint-presentationer i C++" %}}
För att slå samman PowerPoint-presentationer måste du klona bilderna från en presentation till den andra.

{{% blocks/products/pf/agp/code-block title="Slå samman PPTX-filer med C++" offSpacer="true" %}}

```cpp

// The path to the documents directory.
const String sourceFilePath1 = u"SourceDirectory\\SamplePresentation2.pptx";
const String sourceFilePath2 = u"SourceDirectory\\SamplePresentation3.pptx";
const String outputFilePath = u"OutputDirectory\\mergedPresentation.pptx";

// Instantiate Presentation class
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

for (SharedPtr<ISlide> slide : presentation2->get_Slides())
{
	// Merge slides from source to destination 
	presentation1->get_Slides()->AddClone(slide);
}

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Pptx);
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Slå samman presentationer med Slide Master med C++" %}}
Den här C++-koden visar hur man slår ihop flera presentationer till en och tillämpar stilar från mall för bildpresentation. Så resultatpresentationen kommer att behålla samma källformatering och kommer att innehålla formatering från huvudbilden i en annan presentation.

{{% blocks/products/pf/agp/code-block title="Slå samman flera PPT till singel i C++" offSpacer="true" %}}

``` cpp

// The path to the documents directory.
const String sourceFilePath1 = u"SourceDirectory\\SamplePresentation.pptx";
const String sourceFilePath2 = u"SourceDirectory\\SamplePresentation3.pptx";
const String outputFilePath = u"OutputDirectory\\mergedPresentation.pptx";

// Load the presentation files
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

// Merge the first slide using slide master
presentation1->get_Slides()->AddClone(presentation2->get_Slides()->idx_get(0), presentation1->get_Masters()->idx_get(0), true);

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hur man slår samman presentationer med Aspose.Slides för C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att slå samman två PPTX-filer och spara resultatet som PDF i C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installera [**Aspose.Slides for C++**](https://docs.aspose.com/slides/cpp/installation/). 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till en biblioteksreferens (importera biblioteket) till ditt C++-projekt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öppna käll-PPTX-filerna i C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kombinera PPTX-filer med **AddClone**-metoden.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara presentationen och få resultatet som en enda PDF-fil.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra format som stöds att slå samman" subTitle="Du kan också kombinera andra filformat. Se andra format som stöds nedan." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}