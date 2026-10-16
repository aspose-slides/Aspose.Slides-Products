---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Převeďte PDF na SVG v Pythonu
url: /cs/python-net/conversion/pdf-to-svg/
keywords: PDF do SVG, Převést PDF do SVG, Python API, Python Library, PDF, SVG
description: Převeďte PDF na SVG v Pythonu. Použijte API knihovny Python k převodu souborů PDF na SVGs
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Převeďte PDF na SVG v Pythonu" h2="Vysokorychlostní a multiplatformní knihovna Python, která pomáhá při vývoji aplikací se schopností vytvářet, slučovat, kontrolovat nebo převádět prezentační soubory Microsoft PowerPoint a OpenOffice bez použití jakéhokoli softwaru, jako je Microsoft nebo Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Převeďte PDF na SVG pomocí Pythonu" variant="code" %}}

Chcete-li převést PDF do SVG, budete muset vytvořit prezentaci ze souboru PDF a uložit ji jako SVG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python kód pro převod PDF do SVG" >}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing
        
with slides.Presentation() as pres:
    pres.slides.add_from_pdf("document.pdf")
    for index in range(pres.slides.length):
        slide = pres.slides[index]

        with open("slide-{index}.svg".format(index = index), "wb") as file:
            slide.write_as_svg(file)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Převeďte PDF na SVG v Pythonu" %}}

[**Aspose.Slides pro Python přes .NET**](https://products.aspose.com/slides/cs/python-net/) je výkonná knihovna Pythonu pro vytváření a manipulaci s prezentačními soubory. Navíc poskytuje flexibilní způsoby převodu PDF do SVG. Pomocí **Aspose.Slides pro Python přes .NET** může každý vývojář nebo aplikace převést soubory PDF do SVG pomocí několika řádků kódu Python.

Aspose.Slides pro Python jako moderní API pro zpracování dokumentů rychle exportuje soubory PDF do formátů souborů SVG. Knihovna Aspose PowerPoint vám umožňuje převést PDF do SVGs a mnoho dalších formátů souborů

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak převést PDF do SVG pomocí Aspose.Slides pro Python API" intro="Toto jsou kroky k převodu PDF na SVG v Pythonu." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/cs/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Přidejte odkaz na knihovnu (importujte knihovnu) do svého projektu Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otevřete zdrojové soubory PDF v Pythonu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložit výsledek jako soubor SVG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Zdarma online konvertor"
  description="[Jak převést PPT na HTML v Pythonu](https://products.aspose.com/slides/cs/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Převést PDF do jiných podporovaných formátů" subTitle="Můžete také převést PDF a uložit do jiných formátů souborů. Všechny podporované formáty naleznete níže" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-xml/" name="PDF TO XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
