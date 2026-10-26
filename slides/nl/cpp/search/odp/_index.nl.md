---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Tekst zoeken in ODP-presentaties met C++
url: /nl/cpp/search/odp/
description: Zoek tekst in ODP-presentaties in C++. Gebruik Aspose.Slides for C++ om tekst in presentatiebestanden te vinden.
keywords: woorden zoeken in ODP, tekst vinden in ODP, tekst in ODP-presentatie zoeken
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Tekst zoeken in ODP met C++" h2="Gebruik Aspose.Slides for C++ om tekst in presentatiebestanden te vinden zonder Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Tekst zoeken in een ODP-presentatie via C++" variant="code" %}}

Met Aspose.Slides for C++ kunt u tekst zoeken in ODP-presentaties. Verzamel de tekstkaders van een dia met `SlideUtil::GetAllTextBoxes` en controleer daarna of hun tekst de gewenste zin bevat.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tekst zoeken in een ODP-presentatie met C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

auto slide = presentation->get_Slides()->idx_get(0);
auto textFrames = SlideUtil::GetAllTextBoxes(slide);

for (auto&& textFrame : textFrames)
{
    auto text = textFrame->get_Text();
    if (text.Contains(u"PowerPoint"))
    {
        Console::WriteLine(text);
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Tekst zoeken in ODP via C++" intro="Volg deze stappen om tekst in een ODP-presentatie te zoeken." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het ODP-bestand met de klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Haal de gewenste dia op met `Presentation::get_Slides` en lees de tekstkaders ervan uit met [`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Controleer of de tekst van elk kader de gewenste zin bevat.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Gebouwd met Aspose.Slides" title="Tekst zoeken in ODP-bestanden online" description="De gratis app Aspose.Slides Search is gebouwd met [Aspose.Slides for C++](https://products.aspose.com/slides/nl/cpp/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen ODP-bestanden." button="Aspose.Slides Search openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides tekst vindt voordat u code schrijft.
- Doorzoek uw ODP-bestand op gewone tekst of reguliere expressies.
- Download de resultaten als tekstbestand.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten voor zoeken" subTitle="Met C++ kunt u ook tekst zoeken in de volgende formaten." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/cpp/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/cpp/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
