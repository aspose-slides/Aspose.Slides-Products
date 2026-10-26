---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Tekst zoeken in PPT-presentaties met Python
url: /nl/python-net/search/ppt/
description: Zoek tekst in PPT-presentaties met Python en Aspose.Slides.
keywords: tekst zoeken in PPT, woorden vinden in PPT, PPT-presentatie doorzoeken met Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Tekst zoeken in PPT-presentaties met Python" h2="Bouw Python-toepassingen die tekst in PowerPoint-presentaties vinden met Aspose.Slides." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Tekst zoeken in een PPT-presentatie met Python" variant="code" %}}

Met [Aspose.Slides for Python via .NET](/slides/nl/python-net/) kunt u met [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) op elke dia de tekstkaders vinden die een bepaalde tekenreeks bevatten.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tekst zoeken in een PPT-presentatie – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Tekst zoeken in PPT met Python" intro="Volg deze stappen om tekst in een PPT-presentatie te zoeken." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open het PPT-bestand met `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Doorloop de dia's en roep voor elke dia [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) aan.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lees de eigenschap `text` van elk gevonden tekstkader.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Gebouwd met Aspose.Slides" title="Tekst zoeken in PPT-bestanden online" description="De gratis app Aspose.Slides Search is gebouwd met [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/nl/python-net/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen PPT-bestanden." button="Aspose.Slides Search openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides tekst vindt voordat u code schrijft.
- Doorzoek uw PPT-bestand op gewone tekst of reguliere expressies.
- Download de resultaten als tekstbestand.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten voor zoeken" subTitle="Gebruik Python om tekst te zoeken in andere ondersteunde presentatieformaten." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/python-net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/python-net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
