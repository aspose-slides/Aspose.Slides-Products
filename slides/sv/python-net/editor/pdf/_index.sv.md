---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Redigera PDF i Python
url: /sv/python-net/editor/pdf/
keywords: Redigera PDF, PDF, Python API, Python Library
description: Redigera PDF i Python. Använd Python library API för att redigera PDF-dokument
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Redigera PDF i Python" h2="Höghastighets- och plattformsoberoende Python-bibliotek för redigering av PDF med Python-kod" related="PPT,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Redigera PDF i Python" variant="code" %}}

Med hjälp av [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/sv/python-net/) kan du lägga till en ny textrad till ett PDF-dokument med bara några få kodrader.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python-kod för att redigera PDF" >}}
```python

import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    pres.slides.add_from_pdf("document.pdf")

    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("document.pdf", slides.export.SaveFormat.PDF)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Redigera PDF med Aspose.Slides" %}}

[**Aspose.Slides för Python via .NET**](https://products.aspose.com/slides/sv/python-net/) är ett kraftfullt Python-bibliotek som används för att manipulera och redigera presentationer, PDF-dokument och andra filer . Du kan redigera ett PDF-dokument genom att lägga till en ny textrad till det.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hur man redigerar PDF i Python" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lägg till biblioteket som referens i ditt projekt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Skapa en instans av klassen Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ladda PDF-dokumentet du vill redigera.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lägg till en ny textrad.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara den ändrade PDF-filen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Redigera andra filer" subTitle="Du kan även redigera filer i andra format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
