---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Extrahera text från PPT-filer med Python
url: /sv/python-net/parser/ppt/
description: Extrahera text och detaljer om textformatering från PPT-presentationer med Python.
keywords: tolka PPT med Python, PPT-tolk Python, extrahera data från PPT i Python, extrahera text från PPT med Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Extrahera text från PPT-presentationer med Python" h2="Bygg Python-program som extraherar text och formateringsdetaljer från PowerPoint-presentationer med Aspose.Slides." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Extrahera text från en PPT-presentation med Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/sv/python-net/) tillhandahåller den statiska metoden [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/) i `SlideUtil`. Den returnerar `TextFrame`-objekten från hela presentationen och kan även inkludera text från bildbakgrunder. I följande exempel extraheras text och tillhörande teckensnittsdetaljer från en PPT-presentation.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Extrahera text från en PPT-presentation – Python" >}}
```python
include_master_slides = True

with slides.Presentation("presentation.ppt") as presentation:
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så extraherar du text från PPT med Python" intro="Följ de här stegen för att extrahera text från en PPT-fil." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öppna PPT-filen med `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa `SlideUtil.get_all_text_frames` och ange om bildbakgrunder ska inkluderas.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gå igenom de returnerade `TextFrame`-objekten.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gå igenom samlingen `paragraphs` i varje textram.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gå igenom samlingen `portions` i varje stycke.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Läs `text` och formateringsegenskaperna för den aktuella textdelen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Byggd med Aspose.Slides" title="Extrahera text och bilder online" description="Den kostnadsfria appen Aspose.Slides Parser är byggd med [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/sv/python-net/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna PPT-filer." button="Öppna Aspose.Slides Parser" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides läser dina filer innan du skriver kod.
- Ladda upp en PPT-fil och få dess text och bilder.
- Ladda ner allt som ett enda ZIP-arkiv.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som kan tolkas" subTitle="Med Python kan du även extrahera text från andra presentationsformat som stöds." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/python-net/parser/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
