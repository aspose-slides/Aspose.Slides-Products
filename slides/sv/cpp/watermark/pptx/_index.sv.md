---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Lägg till vattenstämpel i PPTX-presentationer med C++
url: /sv/cpp/watermark/pptx/
description: Lägg till text- eller bildvattenstämplar i PPTX-presentationer i C++. Använd Aspose.Slides for C++ för att placera vattenstämplar på bilder.
keywords: lägg till vattenstämpel i PPTX, lägg till textvattenstämpel i PPTX, lägg till bildvattenstämpel i PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Lägg till vattenstämpel i en PPTX-presentation med C++" h2="Använd Aspose.Slides for C++ för att lägga till text- eller bildvattenstämplar i presentationsfiler utan Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Lägg till vattenstämpel i en PPTX-presentation via C++" variant="code" %}}

Med Aspose.Slides for C++ kan du lägga till text- eller bildvattenstämplar i PPTX-presentationer. Lägg till en vattenstämpelform på bildbakgrunden med `AddAutoShape`, lägg till text med `AddTextFrame` eller fyll formen med en bild som läses in via `File::ReadAllBytes` och `AddImage`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Lägg till textvattenstämpel i PPTX med C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Lägg till bildvattenstämpel i en PPTX-presentation med C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 200);

auto imageData = File::ReadAllBytes(u"watermark.png");
auto watermarkImage = presentation->get_Images()->AddImage(imageData);

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(watermarkImage);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"image-watermarked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så lägger du till en vattenstämpel i PPTX med C++" intro="Följ de här stegen för att lägga till en text- eller bildvattenstämpel i PPTX-filer." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Läs in PPTX-filen med klassen `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Välj bildbakgrunden i samlingen `Presentation::get_Masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lägg till en vattenstämpelform med metoden `AddAutoShape`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lägg till vattenstämpeltext med metoden `AddTextFrame` eller ange en bildfyllning med `AddImage`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara filen med vattenstämpel med `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Byggd med Aspose.Slides" title="Lägg till vattenstämplar i PPTX-filer online" description="Den kostnadsfria appen Aspose.Slides Watermark är byggd med [Aspose.Slides for C++](https://products.aspose.com/slides/sv/cpp/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna PPTX-filer." button="Öppna Aspose.Slides Watermark" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides lägger till vattenstämplar innan du skriver kod.
- Lägg till en text- eller bildvattenstämpel i din PPTX-fil.
- Ladda ner filen med vattenstämpel.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som stöder vattenstämplar" subTitle="Med C++ kan du även lägga till vattenstämplar i följande format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/cpp/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
