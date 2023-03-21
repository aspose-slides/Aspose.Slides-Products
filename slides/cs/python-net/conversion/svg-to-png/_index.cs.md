---
title: Převeďte SVG na PNG v Pythonu
url: /cs/python-net/conversion/svg-to-png/
keywords: SVG do PNG, Převést SVG do PNG, Python API, Python Library, SVG, PNG
description: Převeďte SVG na PNG v Pythonu. Použijte API knihovny Python k převodu souborů SVG na PNGs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Převeďte SVG na PNG v Pythonu" h2="Vysokorychlostní a multiplatformní knihovna Python, která pomáhá při vývoji aplikací se schopností vytvářet, slučovat, kontrolovat nebo převádět prezentační soubory Microsoft PowerPoint a OpenOffice bez použití jakéhokoli softwaru, jako je Microsoft nebo Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte SVG na PNG v Pythonu" %}}

[**Aspose.Slides pro Python přes .NET**](https://products.aspose.com/slides/cs/python-net/) je výkonná knihovna Pythonu pro vytváření a manipulaci s prezentačními soubory. Navíc poskytuje flexibilní způsoby převodu SVG do PNG. Pomocí **Aspose.Slides pro Python přes .NET** může každý vývojář nebo aplikace převést soubory SVG do PNG pomocí několika řádků kódu Python.

Aspose.Slides pro Python jako moderní API pro zpracování dokumentů rychle exportuje soubory SVG do formátů souborů PNG. Knihovna Aspose PowerPoint vám umožňuje převést SVG do PNGs a mnoho dalších formátů souborů

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převeďte SVG na PNG pomocí Pythonu" %}}
Chcete-li převést SVG do PNG, budete muset vytvořit prezentaci ze souboru SVG a uložit ji jako PNG.

{{% blocks/products/pf/agp/code-block title="Python kód pro převod SVG do PNG" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    with open("image.svg", "rb") as file:
        svgContent = file.read()
    svgImage = slides.SvgImage(svgContent)
    ppImage = pres.images.add_image(svgImage)
    pres.slides[0].shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, ppImage.width, ppImage.height, ppImage)
    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.png".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.png)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak převést SVG do PNG pomocí Aspose.Slides pro Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky k převodu SVG na PNG v Pythonu." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/cs/python-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte odkaz na knihovnu (importujte knihovnu) do svého projektu Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otevřete zdrojové soubory SVG v Pythonu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložit výsledek jako soubor PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Zdarma online konvertor" sectionDescription="[Jak převést PPT na HTML v Pythonu](https://products.aspose.com/slides/cs/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Převést SVG do jiných podporovaných formátů" subTitle="Můžete také převést SVG a uložit do jiných formátů souborů. Všechny podporované formáty naleznete níže" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}