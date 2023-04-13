---
title: Konvertera PNG till PPTX i C++
url: /sv/cpp/conversion/png-to-pptx/
keywords: Konvertera PNG till PPTX, PNG till PPTX, PowerPoint, PNG, PPTX, C++ API, C++ Library
description: Konvertera PNG till PPTX i C++. Använd C++ biblioteks-API för att konvertera PNG-bilder till PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertera PNG till PPTX i C++" h2="Kraftfull plattformsoberoende C++ API för att konvertera PNG till PPTX med C++-kod" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera PNG till PPTX med Aspose.Slides" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/sv/cpp/) är ett kraftfullt C++-bibliotek som används för att skapa, konvertera och manipulera PowerPoint-presentationer, PDF-filer, HTML-dokument och annat filer. När du konverterar PNG till PPTX skapar du i huvudsak en PowerPoint-presentation som innehåller bilder baserade på PNG-bilder.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Konvertera PNG till PPTX i C++" %}}
Med hjälp av [**Aspose.Slides för C++**](https://products.aspose.com/slides/sv/cpp/) kan du konvertera PNG-bild till PowerPoint-presentation med bara några rader kod:

{{% blocks/products/pf/agp/code-block title="C++-kod för att konvertera PNG till PPTX" offSpacer="true" %}}
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 720.0f, 540.0f, image);

pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Hur man konverterar PNG till PPTX i C++" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installera **Aspose.Slides för C++**. Se [**Installation**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till biblioteket som referens i ditt projekt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Skapa en instans av klassen Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ladda PNG-bilden du vill konvertera till PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara den resulterande filen som en PPTX-presentation.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Gratis onlinekonverterare" sectionDescription="[Hur man konverterar PPT till HTML i Python](https://products.aspose.com/slides/sv/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra PowerPoint-konverteringar som stöds" subTitle="Du kan också konvertera filer i andra format till PowerPoint" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}