---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertera PNG till PPTX i C++
url: /sv/cpp/conversion/png-to-pptx/
keywords: Konvertera PNG till PPTX, PNG till PPTX, PowerPoint, PNG, PPTX, C++ API, C++ Library
description: Konvertera PNG till PPTX i C++. Använd C++ biblioteks-API för att konvertera PNG-bilder till PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertera PNG till PPTX i C++" h2="Kraftfull plattformsoberoende C++ API för att konvertera PNG till PPTX med C++-kod" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertera PNG till PPTX i C++" variant="code" %}}

Med hjälp av [**Aspose.Slides för C++**](https://products.aspose.com/slides/sv/cpp/) kan du konvertera PNG-bild till PowerPoint-presentation med bara några rader kod:

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++-kod för att konvertera PNG till PPTX" >}}
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 720.0f, 540.0f, image);

pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertera PNG till PPTX med Aspose.Slides" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/sv/cpp/) är ett kraftfullt C++-bibliotek som används för att skapa, konvertera och manipulera PowerPoint-presentationer, PDF-filer, HTML-dokument och annat filer. När du konverterar PNG till PPTX skapar du i huvudsak en PowerPoint-presentation som innehåller bilder baserade på PNG-bilder.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hur man konverterar PNG till PPTX i C++" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera **Aspose.Slides för C++**. Se [**Installation**](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lägg till biblioteket som referens i ditt projekt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Skapa en instans av klassen Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ladda PNG-bilden du vill konvertera till PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara den resulterande filen som en PPTX-presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Gratis onlinekonverterare"
  description="[Hur man konverterar PPT till HTML i Python](https://products.aspose.com/slides/sv/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra PowerPoint-konverteringar som stöds" subTitle="Du kan också konvertera filer i andra format till PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
