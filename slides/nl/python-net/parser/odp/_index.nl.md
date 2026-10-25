---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Tekst uit ODP-bestanden extraheren met Python
url: /nl/python-net/parser/odp/
description: Extraheer tekst en details van tekstopmaak uit ODP-presentaties met Python.
keywords: ODP parseren met Python, ODP-parser Python, gegevens uit ODP extraheren in Python, tekst uit ODP extraheren met Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Tekst uit ODP-presentaties extraheren met Python" h2="Bouw Python-toepassingen die met Aspose.Slides tekst en opmaakdetails uit OpenDocument-presentaties extraheren." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Tekst uit een ODP-presentatie extraheren met Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/nl/python-net/) biedt de statische methode [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/) van `SlideUtil`. Deze retourneert de `TextFrame`-objecten van de hele presentatie en kan ook tekst uit modeldia's bevatten. In het volgende voorbeeld worden tekst en bijbehorende lettertypedetails uit een ODP-presentatie geëxtraheerd.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tekst uit een ODP-presentatie extraheren – Python" >}}
```python
include_master_slides = True

with slides.Presentation("presentation.odp") as presentation:
    text_frames = slides.util.SlideUtil.get_all_text_frames(presentation, include_master_slides)

    for text_frame in text_frames:
        for paragraph in text_frame.paragraphs:
            for portion in paragraph.portions:
                print(portion.text)

                font_height = portion.portion_format.font_height
                print(font_height)

                latin_font = portion.portion_format.latin_font
                if latin_font is not None:
                    print(latin_font.font_name)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Tekst uit ODP extraheren met Python" intro="Volg deze stappen om tekst uit een ODP-bestand te extraheren." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open het ODP-bestand met `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep `SlideUtil.get_all_text_frames` aan en geef aan of modeldia's moeten worden meegenomen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Doorloop de geretourneerde `TextFrame`-objecten.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Doorloop de verzameling `paragraphs` van elk tekstkader.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Doorloop de verzameling `portions` van elke alinea.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lees `text` en de opmaakeigenschappen van het huidige tekstdeel.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Gebouwd met Aspose.Slides" title="Tekst en afbeeldingen online extraheren" description="De gratis app Aspose.Slides Parser is gebouwd met [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/nl/python-net/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen ODP-bestanden." button="Aspose.Slides Parser openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Zie hoe Aspose.Slides uw bestanden leest voordat u code schrijft.
- Upload een ODP-bestand en krijg de tekst en afbeeldingen.
- Download alles als één ZIP-archief.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten om te parseren" subTitle="Met Python kunt u ook tekst uit andere ondersteunde presentatieformaten extraheren." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/python-net/parser/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/python-net/parser/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
