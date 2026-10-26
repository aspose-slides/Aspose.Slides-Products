---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Tekst in PPTX-presentaties zwartlakken met Python
url: /nl/python-net/redaction/pptx/
description: Zoek en vervang gevoelige tekst in PPTX-presentaties met Python.
keywords: PPTX zwartlakken, tekst zoeken en vervangen in PPTX, PPTX-presentatie bijwerken
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Tekst in PPTX-presentaties zwartlakken met Python" h2="Bouw Python-toepassingen die gevoelige tekst in presentaties zoeken en vervangen met Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Tekst in een PPTX-presentatie zwartlakken met Python" variant="code" %}}

Met [Aspose.Slides for Python via .NET](/slides/nl/python-net/) kunt u gevoelige tekst in een hele PPTX-presentatie vervangen. Gebruik `Presentation.replace_text` met `TextSearchOptions` om de zoekopdracht te sturen en sla daarna de gewijzigde presentatie op.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tekst in een PPTX-presentatie zwartlakken – Python" >}}
```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.pptx") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Tekst in een PPTX-presentatie zwartlakken met Python – zo werkt het" intro="Volg deze stappen om gevoelige tekst in een PPTX-presentatie te vervangen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open het PPTX-bestand met `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gebruik [`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/) met `TextSearchOptions` om de gewenste tekst te vervangen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla de gewijzigde presentatie op met `SaveFormat.PPTX`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Gebouwd met Aspose.Slides" title="PPTX-bestanden online zwartlakken" description="De gratis app Aspose.Slides Redaction is gebouwd met [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/nl/python-net/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen PPTX-bestanden." button="Aspose.Slides Redaction openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides tekst zoekt en vervangt voordat u code schrijft.
- Zoek en vervang tekst in uw PPTX-bestand, ook met reguliere expressies.
- Download het zwartgelakte bestand.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten voor zwartlakken" subTitle="Gebruik Python om tekst in andere ondersteunde presentatieformaten zwart te lakken." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/python-net/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
