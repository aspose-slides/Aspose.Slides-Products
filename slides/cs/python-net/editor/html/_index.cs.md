---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Upravte HTML v Pythonu
url: /cs/python-net/editor/html/
keywords: Upravit HTML, HTML, Python API, Python Library
description: Upravte HTML v Pythonu. K úpravě souboru HTML použijte rozhraní API knihovny Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Upravte HTML v Pythonu" h2="Vysokorychlostní a multiplatformní Python knihovna pro editaci HTML pomocí Python kódu" related="PPT,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Upravte HTML v Pythonu" variant="code" %}}

Pomocí [**Aspose.Slides pro Python přes .NET**](https://products.aspose.com/slides/cs/python-net/) můžete do dokumentu HTML přidat nový řádek textu pomocí několika řádky kódu.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python kód pro úpravu HTML" >}}
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Upravte HTML pomocí Aspose.Slides" %}}

[**Aspose.Slides pro Python přes .NET**](https://products.aspose.com/slides/cs/python-net/) je výkonná knihovna Pythonu používaná k manipulaci a úpravám prezentací, dokumentů HTML a dalších souborů . Dokument HTML můžete upravit přidáním nového řádku textu.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak upravit HTML v Pythonu" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte **Aspose.Slides pro Python přes .NET**. Viz [**Instalace**](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Přidejte knihovnu jako referenci do svého projektu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vytvořte instanci třídy Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte dokument HTML, který chcete upravit.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Přidejte nový řádek textu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte změněný soubor HTML.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Upravte další soubory" subTitle="Můžete také upravovat soubory v jiných formátech" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/editor/pdf/" name="Edit PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
