---
title: Konvertera bild till PPT i C++
url: /sv/cpp/conversion/image-to-ppt/
keywords: Bild till PPT, Konvertera bild till PPT, C++ API, C++ Library, Image, PPT
description: Konvertera bild till PPT i C++. Använd C++ biblioteks-API för att konvertera bildfiler till PDF-filer
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertera bild till PPT i C++" h2="Höghastighets- och plattformsoberoende C++-bibliotek som hjälper till att utveckla applikationer med möjligheten att skapa, slå samman, inspektera eller konvertera Microsoft PowerPoint- och OpenOffice-presentationsfiler utan användning av någon programvara som Microsoft eller Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera bild till PPT i C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/sv/cpp/) är ett kraftfullt C++-bibliotek för att skapa och manipulera presentationsfiler. Dessutom ger det flexibla sätt att konvertera bild till PPT. Genom att använda **Aspose.Slides för C++** kan vilken utvecklare eller applikation som helst konvertera bild till PPT-filer med bara några rader C++-kod.

Som ett modernt dokumentbehandlings-API exporterar Aspose.Slides för C++ bildfiler till PPT-filformat snabbt. Aspose PowerPoint-bibliotek låter dig konvertera bilder till PDF-filer och många andra filformat

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera bild till PPT med C++" %}}
För att konvertera bilden till PPT måste du skapa en presentation från bildfilen och spara den som PPT.

{{% blocks/products/pf/agp/code-block title="C++-kod för att konvertera bild till PPT" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.jpg"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 720.0f, 540.0f, image);
pres->Save(u"presentation.ppt", SaveFormat::Ppt);

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hur man konverterar bild till PPT med Aspose.Slides för C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att konvertera bild till PPT i C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installera [**Aspose.Slides for C++**](https://products.aspose.com/slides/sv/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till en biblioteksreferens (importera biblioteket) till ditt C++-projekt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öppna källbildfilerna i C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet som PPT-fil.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konvertera bild till andra format som stöds" subTitle="Du kan också konvertera bild och spara till andra filformat. Se alla format som stöds nedan" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/image-to-pptx/" name="IMAGE TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}