---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Bewerk HTML in Python
url: /nl/python-net/editor/html/
keywords: HTML, HTML, Python API, Python-bibliotheek bewerken
description: Bewerk HTML in Python. Gebruik de Python-bibliotheek-API om het HTML-bestand te bewerken
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Bewerk HTML in Python" h2="Snelle en platformonafhankelijke Python-bibliotheek voor het bewerken van HTML met behulp van Python-code" related="PPT,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Bewerk HTML in Python" variant="code" %}}

Met behulp van [**Aspose.Slides voor Python via .NET**](https://products.aspose.com/slides/nl/python-net/), kunt u met slechts een paar stappen een nieuwe regel tekst toevoegen aan een HTML-document. regels code.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python-code voor het bewerken van HTML" >}}
```python

import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    with open("page.html", "rt") as stream:
        data = stream.read()
    pres.slides.add_from_html(data)

    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("page.html", slides.export.SaveFormat.HTML5)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="HTML bewerken met Aspose.Slides" %}}

[**Aspose.Slides voor Python via .NET**](https://products.aspose.com/slides/nl/python-net/) is een krachtige Python-bibliotheek die wordt gebruikt voor het manipuleren en bewerken van presentaties, HTML-documenten en andere bestanden . U kunt een HTML-document bewerken door er een nieuwe regel tekst aan toe te voegen.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hoe HTML in Python te bewerken" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Voeg de bibliotheek toe als referentie in uw project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Maak een instantie van de klasse Presentatie.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het HTML-document dat u wilt bewerken.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Voeg een nieuwe regel tekst toe.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla het gewijzigde HTML-bestand op.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="Gebouwd met Aspose.Slides" title="PPTX-bestanden online bewerken" description="De gratis app Aspose.Slides Editor is gebouwd met [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/nl/python-net/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen PPTX-bestanden." button="Aspose.Slides Editor openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Zie hoe Aspose.Slides uw bestanden verwerkt voordat u code schrijft.
- Upload uw PPTX-bestanden en bewerk ze direct.
- Sla het bewerkte bestand op en download het.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Bewerk andere bestanden" subTitle="U kunt ook bestanden in andere indelingen bewerken" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/editor/pdf/" name="Edit PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
