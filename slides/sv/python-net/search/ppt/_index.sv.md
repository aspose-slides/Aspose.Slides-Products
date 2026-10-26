---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Sök efter text i PPT-presentationer med Python
url: /sv/python-net/search/ppt/
description: Sök efter text i PPT-presentationer med Python och Aspose.Slides.
keywords: sök efter text i PPT, hitta ord i PPT, sök i PPT-presentation med Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Sök efter text i PPT-presentationer med Python" h2="Bygg Python-program som hittar text i PowerPoint-presentationer med Aspose.Slides." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Sök efter text i en PPT-presentation med Python" variant="code" %}}

Med [Aspose.Slides for Python via .NET](/slides/sv/python-net/) kan du använda [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) för att hitta de textramar på varje bild som innehåller en viss sträng.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Sök efter text i en PPT-presentation – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så söker du efter text i PPT med Python" intro="Följ de här stegen för att söka efter text i en PPT-presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öppna PPT-filen med `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gå igenom bilderna och anropa [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) för var och en.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Läs egenskapen `text` för varje matchande textram.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Byggd med Aspose.Slides" title="Sök efter text i PPT-filer online" description="Den kostnadsfria appen Aspose.Slides Search är byggd med [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/sv/python-net/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna PPT-filer." button="Öppna Aspose.Slides Search" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides hittar text innan du skriver kod.
- Sök efter vanlig text eller reguljära uttryck i din PPT-fil.
- Ladda ned träffarna som en textfil.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som stöds för sökning" subTitle="Använd Python för att söka efter text i andra presentationsformat som stöds." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/python-net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/python-net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
