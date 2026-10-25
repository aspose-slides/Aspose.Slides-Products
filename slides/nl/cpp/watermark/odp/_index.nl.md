---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Watermerk toevoegen aan ODP-presentaties met C++
url: /nl/cpp/watermark/odp/
description: Voeg tekst- of afbeeldingswatermerken toe aan ODP-presentaties in C++. Gebruik Aspose.Slides for C++ om watermerken op dia's te plaatsen.
keywords: watermerk toevoegen aan ODP, tekstwatermerk toevoegen aan ODP, afbeeldingswatermerk toevoegen aan ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Watermerk toevoegen aan een ODP-presentatie met C++" h2="Gebruik Aspose.Slides for C++ om tekst- of afbeeldingswatermerken toe te voegen aan presentatiebestanden zonder Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Watermerk toevoegen aan een ODP-presentatie via C++" variant="code" %}}

Met Aspose.Slides for C++ voegt u tekst- of afbeeldingswatermerken toe aan ODP-presentaties. Voeg met `AddAutoShape` een watermerkvorm toe aan de modeldia, voeg tekst toe met `AddTextFrame` of vul de vorm met een afbeelding die via `File::ReadAllBytes` en `AddImage` wordt geladen.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tekstwatermerk toevoegen aan ODP met C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Afbeeldingswatermerk toevoegen aan een ODP-presentatie met C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 200);

auto imageData = File::ReadAllBytes(u"watermark.png");
auto watermarkImage = presentation->get_Images()->AddImage(imageData);

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(watermarkImage);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"image-watermarked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Een watermerk toevoegen aan ODP met C++" intro="Volg deze stappen om een tekst- of afbeeldingswatermerk toe te voegen aan ODP-bestanden." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het ODP-bestand met de klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Selecteer de modeldia uit de verzameling `Presentation::get_Masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Voeg een watermerkvorm toe met de methode `AddAutoShape`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Voeg watermerktekst toe met de methode `AddTextFrame` of stel een afbeeldingsvulling in met `AddImage`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla het bestand met watermerk op met `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Gebouwd met Aspose.Slides" title="Watermerken toevoegen aan ODP-bestanden online" description="De gratis app Aspose.Slides Watermark is gebouwd met [Aspose.Slides for C++](https://products.aspose.com/slides/nl/cpp/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen ODP-bestanden." button="Aspose.Slides Watermark openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Zie hoe Aspose.Slides watermerken toevoegt voordat u code schrijft.
- Voeg een tekst- of afbeeldingswatermerk toe aan uw ODP-bestand.
- Download het bestand met watermerk.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten voor watermerken" subTitle="Met C++ kunt u ook watermerken toevoegen aan de volgende formaten." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/cpp/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/cpp/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
