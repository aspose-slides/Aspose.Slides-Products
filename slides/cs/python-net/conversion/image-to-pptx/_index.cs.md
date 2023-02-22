---
title: Převést obrázek na PPTX v Pythonu
url: /cs/python-net/conversion/image-to-pptx/
keywords: Obrázek na PPTX, Převést obrázek na PPTX, Python API, Python Library, Image, PPTX
description: Převést obrázek na PPTX v Pythonu. K převodu obrazových souborů do PDF použijte rozhraní API knihovny Python
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Převést obrázek na PPTX v Pythonu" h2="Vysokorychlostní a multiplatformní knihovna Python, která pomáhá při vývoji aplikací se schopností vytvářet, slučovat, kontrolovat nebo převádět prezentační soubory Microsoft PowerPoint a OpenOffice bez použití jakéhokoli softwaru, jako je Microsoft nebo Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Převést obrázek na PPTX v Pythonu" %}}

[**Aspose.Slides pro Python přes .NET**](https://products.aspose.com/slides/cs/python-net/) je výkonná knihovna Pythonu pro vytváření a manipulaci s prezentačními soubory. Kromě toho poskytuje flexibilní způsoby převodu obrázku na PPTX. Pomocí **Aspose.Slides pro Python přes .NET** může každý vývojář nebo aplikace převést obrázek na soubory PPTX pomocí několika řádků kódu Python.

Aspose.Slides pro Python jako moderní API pro zpracování dokumentů rychle exportuje soubory obrázků do formátů souborů PPTX. Knihovna Aspose PowerPoint vám umožňuje převádět obrázky do PDF a mnoha dalších formátů souborů

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převeďte obrázek na PPTX pomocí Pythonu" %}}
Chcete-li převést obrázek na PPTX, budete muset vytvořit prezentaci ze souboru obrázku a uložit ji jako PPTX.

{{% blocks/products/pf/agp/code-block title="Python kód pro převod obrázku do PPTX" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    pres.save("index.pptx", slides.export.SaveFormat.PPTX)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak převést obrázek na PPTX pomocí Aspose.Slides pro Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky pro převod obrázku na PPTX v Pythonu." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/cs/python-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte odkaz na knihovnu (importujte knihovnu) do svého projektu Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otevřete zdrojové soubory obrázků v Pythonu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte výsledek jako soubor PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Převést obrázek do jiných podporovaných formátů" subTitle="Můžete také převést obrázek a uložit do jiných formátů souborů. Všechny podporované formáty naleznete níže" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/image-to-ppt/" name="IMAGE TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}